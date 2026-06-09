# trooth-templates

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Open-source starter templates for AI vendors. Eight production-grade documents you can copy, fill in, and ship.

These templates ship with the Trooth Bronze tier and are free for anyone to use, modify, and distribute under the Apache License 2.0. They were written for AI vendors that need to stand up the standard set of compliance documents quickly without a lawyer drafting from scratch.

## What's included

| File | What it is | When you need it |
|---|---|---|
| `templates/privacy-policy.md` | Privacy Policy skeleton with GDPR / CCPA placeholders | Day one of any product that processes personal data |
| `templates/terms-of-service.md` | Terms of Service skeleton for SaaS / API products | Day one of any paid product |
| `templates/acceptable-use-policy.md` | Acceptable Use Policy with AI-specific prohibitions | Day one of any product that lets users submit content |
| `templates/ai-use-policy.md` | AI Use Policy aligned to EU AI Act and NIST AI RMF | Any product that uses or builds AI |
| `templates/model-card.md` | Model Card template (Mitchell et al. format) | Any product that ships a model |
| `templates/security.txt` | RFC 9116 security contact disclosure | Every public website |
| `templates/sbom-cyclonedx.json` | CycloneDX 1.5 Software Bill of Materials skeleton | EU AI Act Annex IV, SOC 2 vendor reviews |
| `templates/ai-code-disclosure.md` | Disclosure of AI-generated code in your codebase | Public repos that use Copilot, Cursor, Claude Code |

## How to use

1. Pick a template
2. Find every `{PLACEHOLDER}` and replace with your information
3. Have qualified counsel review before publishing
4. Publish

The templates are not legal advice. Trooth, LLC is not a law firm. Have a licensed attorney in your jurisdiction review every legal document before it has public effect.

## Why we publish these

We built every one of these templates for our own use and for our customers. Making them open-source costs us nothing and helps every AI builder ship faster. If you find a bug or want to contribute an improvement, open a pull request.

## Contributing

See `CONTRIBUTING.md`. We welcome additions, corrections, and translations.

## License

Apache License 2.0. You can use these templates in commercial or non-commercial products without attribution.

## About Trooth

Trooth provides cryptographic compliance infrastructure for AI products. Continuous monitoring against SOC 2, ISO 27001, EU AI Act, NIST AI RMF, and HIPAA. Free at Bronze.

[trooth.co](https://www.trooth.co) · [Trust Center](https://www.trooth.co/security)
