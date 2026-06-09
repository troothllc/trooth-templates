# Model Card: {YOUR_MODEL_NAME}

**Version:** {VERSION}
**Date:** {YYYY-MM-DD}
**Authors:** {YOUR_COMPANY_NAME}
**Contact:** {YOUR_TECHNICAL_CONTACT_EMAIL}

This Model Card follows the format proposed in [Mitchell et al. (2019), "Model Cards for Model Reporting"](https://arxiv.org/abs/1810.03993) and incorporates additional fields aligned to the EU AI Act Annex IV technical documentation requirements.

## 1. Model details

- **Model name and version:** {YOUR_MODEL_NAME} v{VERSION}
- **Model type:** {classifier, generative LLM, embedding, regression, etc.}
- **Architecture:** {brief architecture summary}
- **Base model (if any):** {parent model name and version, or "trained from scratch"}
- **License:** {SPDX license identifier}
- **Citation:** {how to cite this model}

## 2. Intended use

- **Primary intended uses:** {what this model is designed to do}
- **Primary intended users:** {who should use this model}
- **Out-of-scope use cases:** {what this model is not designed for; explicitly call out high-risk uses you do not support}

## 3. Factors

- **Relevant factors:** {demographic, environmental, instrumentation factors that affect performance}
- **Evaluation factors:** {factors used in the evaluation, with rationale}

## 4. Metrics

- **Performance measures:** {accuracy, F1, BLEU, ROUGE, calibration error, etc.}
- **Decision thresholds:** {if applicable}
- **Variation approaches:** {bootstrap, cross-validation, etc.}

## 5. Evaluation data

- **Datasets used:** {names, versions, source URLs}
- **Motivation:** {why these datasets were chosen}
- **Preprocessing:** {what was done to the data before evaluation}

## 6. Training data

- **Datasets used:** {names, versions, source URLs}
- **Distribution shifts:** {known mismatch between training and evaluation distributions}
- **Data collection process:** {how the data was gathered}
- **Data filtering and licensing:** {what was removed, what licenses apply}

## 7. Quantitative analyses

- **Unitary results:** {performance on each evaluation factor in isolation}
- **Intersectional results:** {performance on combinations of factors, especially protected classes where lawful and appropriate}

## 8. Ethical considerations

- **Sensitive use cases:** {medical, legal, financial, employment, housing, criminal-justice applications}
- **Risks identified:** {bias, hallucination, misuse, privacy, security, dependency}
- **Mitigations applied:** {filters, guardrails, human review, rate limits}
- **Residual risks:** {what remains after mitigations}

## 9. Caveats and recommendations

- **Known limitations:** {what this model is not good at}
- **Recommendations for users:** {how to use this model safely}
- **Recommendations for downstream developers:** {what they need to know before fine-tuning, distilling, or productionizing}

## 10. EU AI Act Annex IV alignment

If you are placing this model on the EU market, the following Annex IV technical documentation items are addressed by this Model Card:

- **General description of the AI system:** Sections 1, 2
- **Detailed information about the elements and the process of development:** Sections 3, 5, 6
- **Monitoring, functioning and control of the AI system:** Section 4
- **Risk management system:** Section 8

This Model Card does not by itself satisfy Annex IV. Pair it with your Risk Management System documentation, your Quality Management System documentation, and your Post-Market Monitoring Plan.

## 11. Changelog

| Version | Date | Changes |
|---|---|---|
| {VERSION} | {YYYY-MM-DD} | Initial release |
