# AI Use Policy

**Effective:** {YYYY-MM-DD}
**Last updated:** {YYYY-MM-DD}
**Entity:** {YOUR_LEGAL_ENTITY_NAME}
**Contact:** {YOUR_LEGAL_EMAIL}

This AI Use Policy describes how {YOUR_LEGAL_ENTITY_NAME} develops, deploys, and governs artificial intelligence ("AI") in our products. It is aligned to the EU AI Act (Regulation EU 2024/1689), the NIST AI Risk Management Framework Version 1.0, and the OECD AI Principles. Replace every `{PLACEHOLDER}` and adapt this policy to your actual AI program before publishing.

## 1. Scope

This policy applies to every AI system we provide, integrate, embed, or use to deliver our Services, including:

- AI features we develop in-house
- AI components we integrate from third-party providers
- Internal-use AI tools that process Customer Data

## 2. Roles under the EU AI Act

We act as one or more of the following, depending on the system:

- **Provider** (EU AI Act Art. 3(3)) when we develop and place an AI system on the EU market
- **Deployer** (EU AI Act Art. 3(4)) when we use an AI system under our authority

We document the role we play for each AI system in our internal AI register.

## 3. Risk classification

Every AI system we provide or deploy is classified into one of four risk tiers consistent with EU AI Act Articles 5, 6, and 50:

- **Unacceptable risk** (prohibited under Art. 5): we do not provide or deploy any system in this category
- **High risk** (Art. 6 and Annex III): we maintain a conformity assessment, technical documentation per Annex IV, post-market monitoring, and human oversight
- **Limited risk** (Art. 50): we provide the transparency disclosures required
- **Minimal risk:** we apply our standard quality and security controls

## 4. Trustworthiness commitments

We design our AI systems to meet the seven characteristics of trustworthy AI identified by NIST:

- **Valid and reliable:** we evaluate against documented metrics on representative data
- **Safe:** we apply mitigations proportionate to identified harms
- **Secure and resilient:** we apply the same access control, encryption, and monitoring we apply to all production systems
- **Accountable and transparent:** we maintain audit logs of model decisions and we publish Model Cards for material models
- **Explainable and interpretable:** we surface explanations where the use case demands them
- **Privacy-enhanced:** we minimize data collected for model purposes and we delete data on the schedule documented in our Privacy Policy
- **Fair, with harmful bias managed:** we evaluate model performance across relevant demographic and contextual factors and we document residual disparities

## 5. Article 50 transparency disclosures

Where the EU AI Act Article 50 applies, we disclose to users:

- That they are interacting with an AI system (unless obvious from context)
- That content has been generated or manipulated by AI (for deepfakes, synthetic audio/video/text)
- That an emotion-recognition or biometric-categorization system is in use (where applicable)

## 6. Human oversight

Every consequential decision made by an AI system in our products has a human-oversight layer documented in the product's Risk Management documentation. We do not permit fully automated consequential decisions about identified individuals without a meaningful right of human review.

## 7. Data governance

- We do not train on Customer Data without separate written consent (see Terms of Service Section 4)
- We document the lineage, license, and quality of every dataset used to train, fine-tune, or evaluate our models
- We retain training data only as long as needed for model performance, retraining, and audit, and not longer than 36 months unless retention is required by law

## 8. Incident reporting

Serious incidents involving our AI systems are reported to:

- Your incident-response team within {N} hours of detection
- Affected customers within 72 hours of confirmation
- Regulators within the timelines required by applicable law (15 days under EU AI Act Art. 73 for high-risk systems)

Report any AI-related concern to {YOUR_SECURITY_EMAIL}.

## 9. Third-party AI components

When we integrate a third-party AI component, we:

- Review the provider's Model Card, Acceptable Use Policy, and Data Processing terms
- Document the integration in our AI register
- Pass through the provider's prohibited-use restrictions to our end users via our AUP
- Monitor for material changes in the provider's terms

## 10. Continuous improvement

We review this policy at least annually and after any material change to applicable law, our AI program, or the systems we provide. The current version is always available at {YOUR_DOMAIN}/ai-use-policy.

## 11. Contact

- **AI program questions:** {YOUR_AI_GOVERNANCE_EMAIL}
- **Concerns or incidents:** {YOUR_SECURITY_EMAIL}
- **Article 50 disclosure questions:** {YOUR_LEGAL_EMAIL}
