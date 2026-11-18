# Standard Contract Templates: mutual NDA, SaaS agreement, DPA, SLA and more, in Markdown

**The market-standard versions of the most common B2B contracts. Word for word, in Markdown.**

- **Start from a standard, not a blank page.** Bonterms, Common Paper, oneNDA and the EU's own model clauses, side by side, with a "pick it when" for each.
- **Trust the text.** Every clause is the publisher's, with its source, version and license on the first line.
- **Use it anywhere.** Plain Markdown: read it on GitHub, paste it into Word, or hand it to an AI agent.

## Principles

1. **Curated and free.** At most three references per contract type, all drafted by a committee or issued by a regulator (Tier 1), or by one recognised firm under an open license (Tier 2). No signup, no export paywall, no generator.
2. **High fidelity.** Every clause, defined term and drafting note is the publisher's, as published. We only harmonize the layout (headings, numbering, fill-in fields) so all files read the same way. Each file keeps its publisher's attribution and license.
3. **Agent-ready.** One contract per file, plain Markdown, stable URLs. Any AI agent can read, compare or fill in a template without conversion.

**Why we publish this:** at [ContractFull](https://contractfull.io) we work on contracts after they are signed. Agreements that start from a standard are easier to understand, compare and manage.

## Index

Tier 1 = market standard (committee-drafted or regulator-issued). Tier 2 = one reputable firm, open license. "Law" is the governing law the template uses unless the parties pick another one.

| Contract type | Reference | Tier | License | Law | Pick it when |
|---|---|---|---|---|---|
| [Mutual NDA](mutual-nda-template/) | [Bonterms Mutual NDA 1.0](mutual-nda-template/bonterms-mutual-nda-v1.0.md) | 1 | CC BY 4.0 | Chosen on the Cover Page | Any governing law, deal terms on a separate Cover Page |
| | [Common Paper Mutual NDA 1.0](mutual-nda-template/common-paper-mutual-nda-v1.0.md) | 1 | CC BY 4.0 | A US state | US deal, cover page and terms in one file |
| | [oneNDA 2.1](mutual-nda-template/onenda-v2.1.md) | 1 | CC BY 4.0 | Chosen in the Variables | Any governing law, shortest form (~950 words) |
| [Unilateral (one-way) NDA](unilateral-nda-template/) | [Common Paper One-Way NDA](unilateral-nda-template/common-paper-one-way-nda.md) | 1 | CC BY 4.0 | A US state | Deal terms on a cover page |
| | [General Legal One-Way NDA](unilateral-nda-template/general-legal-one-way-nda.md) | 2 | CC0 1.0 | Delaware | Full standalone agreement |
| [SaaS / cloud agreement](saas-agreement-template/) | [Bonterms Cloud Terms 1.0](saas-agreement-template/bonterms-cloud-terms-v1.0.md) | 1 | CC BY 4.0 | Chosen on the Cover Page | You'll attach the Bonterms SLA and DPA |
| | [Common Paper Cloud Service Agreement 3.0](saas-agreement-template/common-paper-cloud-service-agreement-v3.0.md) | 1 | CC BY 4.0 | Chosen in the Key Terms | You'll add the Common Paper SLA or AI Addendum |
| | [oneSaaS 1.0](saas-agreement-template/onesaas-v1.0.md) | 1 | CC BY 4.0 | Chosen in the Key Terms | SLA, trial and add-on terms in one document |
| [Professional services (MSA, PSA, SOW)](professional-services-agreement-template/) | [Bonterms Professional Services Agreement 1.2](professional-services-agreement-template/bonterms-professional-services-agreement-v1.2.md) | 1 | CC BY 4.0 | Chosen on the Cover Page | You already sell on Bonterms Cloud Terms |
| | [Common Paper Professional Services Agreement 1.1 + SOW](professional-services-agreement-template/common-paper-professional-services-agreement-v1.1.md) | 1 | CC BY 4.0 | Chosen on the Cover Page | You want a SOW template included |
| | [General Legal Master Services Agreement](professional-services-agreement-template/general-legal-master-services-agreement.md) | 2 | CC0 1.0 | Delaware | One US contract for software, platform and integration services |
| [SLA](sla-template/) | [Bonterms Service Level Agreement 1.0](sla-template/bonterms-service-level-agreement-v1.0.md) | 1 | CC BY 4.0 | Follows the Cloud Terms | Your SaaS agreement is Bonterms |
| | [Common Paper Service Level Agreement 2.0](sla-template/common-paper-service-level-agreement-v2.0.md) | 1 | CC BY 4.0 | Follows the Cloud Service Agreement | Your SaaS agreement is Common Paper |
| [Data processing agreement (GDPR Art. 28)](data-processing-agreement-template/) | [EU SCCs controller–processor (2021/915)](data-processing-agreement-template/eu-sccs-controller-processor-2021-915.md) | 1 | EU reuse | EU / EEA | You want the EU's own Article 28 clauses |
| | [Bonterms Data Protection Addendum 1.0](data-processing-agreement-template/bonterms-data-protection-addendum-v1.0.md) | 1 | CC BY 4.0 | Follows the main agreement | You sell on Bonterms Cloud Terms |
| | [General Legal Data Processing Addendum (global)](data-processing-agreement-template/general-legal-data-processing-addendum-global.md) | 2 | CC0 1.0 | Follows the main agreement | One processor-side addendum for US, EU, UK and Swiss law |
| [International data transfers](standard-contractual-clauses/) | [EU Standard Contractual Clauses (2021/914)](standard-contractual-clauses/eu-sccs-international-transfers-2021-914.md) | 1 | EU reuse | An EU Member State | Personal data leaves the EU/EEA |
| [Software license (on-premises)](software-license-agreement-template/) | [Common Paper Software License Agreement 1.1](software-license-agreement-template/common-paper-software-license-agreement-v1.1.md) | 1 | CC BY 4.0 | Chosen in the Key Terms | You use Common Paper for SaaS and services |
| | [Bonterms Software License Terms 1.0](software-license-agreement-template/bonterms-software-license-terms-v1.0.md) | 1 | CC BY 4.0 | Chosen on the Cover Page | You use Bonterms for SaaS and services |
| [AI addendum and AI clauses](ai-addendum/) | [Common Paper AI Addendum 1.0](ai-addendum/common-paper-ai-addendum-v1.0.md) | 1 | CC BY 4.0 | Follows the main agreement | Adding AI terms to a signed B2B contract |
| | [EU MCC-AI, high-risk (2025)](ai-addendum/eu-mcc-ai-high-risk-2025.md) | 1 | EU reuse | Follows the procurement contract | Public buyer, high-risk AI system (AI Act) |
| | [EU MCC-AI, light (2025)](ai-addendum/eu-mcc-ai-light-2025.md) | 1 | EU reuse | Follows the procurement contract | Public buyer, other AI systems |
| [EU Data Act model terms](data-act-model-terms/) | [Model terms on data access (4 contracts) and cloud switching clauses](data-act-model-terms/) | 1 | EU reuse | An EU Member State | Pick the file matching your role |
| [EULA (marketplace)](eula-template/) | [Bonterms Standard End User Agreement 1.0](eula-template/bonterms-standard-end-user-agreement-v1.0.md) | 1 | CC BY-ND 4.0 | California, unless the listing says otherwise | Selling through an app marketplace |
| [Reseller / partnership](reseller-agreement-template/) | [Common Paper Partnership Agreement 1.1](reseller-agreement-template/common-paper-partnership-agreement-v1.1.md) | 1 | CC BY 4.0 | Chosen on the Cover Page | Referral or co-marketing partner |
| | [Bonterms Standard Reseller Agreement (for Marketplaces) 1.0](reseller-agreement-template/bonterms-standard-reseller-agreement-for-marketplaces-v1.0.md) | 1 | CC BY-ND 4.0 | California | Resale inside an app marketplace |
| [Advisor agreement](advisor-agreement-template/) | [General Legal Advisor Agreement](advisor-agreement-template/general-legal-advisor-agreement.md) | 2 | CC0 1.0 | Delaware | Startup advisor paid in equity |
| [SAFE (startup financing)](safe-agreement-template/) | [YC Post-Money SAFE 1.2, valuation cap](safe-agreement-template/yc-post-money-safe-valuation-cap-v1.2.md) | 1 | CC BY-ND 4.0 | A US state | US pre-seed or seed round |

## How the files are built

Each template starts with one source line (publisher, license, link). Below it is the publisher's text in a common layout: numbered sections as headings, sub-clauses as numbered paragraphs, fill-in fields <mark>[highlighted]</mark>, choices as **Option 1** / **Option 2** or ☐ checkboxes, and notes to the drafter as quotes. Sources, versions and licenses are listed in [SOURCES.md](SOURCES.md).

## How to use

- **Read or copy.** Open a file on GitHub and copy the text, or download the whole repo as a ZIP (green **Code** button).
- **With an AI agent.** Give the agent a file's raw URL, or the repo URL so it can read this index first. Clone the repo (`git clone https://github.com/contractfull/standard-contract-templates`) for agents that work on local files.

Example prompts:

> Read https://github.com/contractfull/standard-contract-templates and tell me which mutual NDA fits a deal between a French and a US company.

> Compare the NDA I'm attaching against https://raw.githubusercontent.com/contractfull/standard-contract-templates/main/mutual-nda-template/bonterms-mutual-nda-v1.0.md and list every clause where it departs from the standard.

> Using https://raw.githubusercontent.com/contractfull/standard-contract-templates/main/data-processing-agreement-template/eu-sccs-controller-processor-2021-915.md, list every field I need to fill in, and the annexes.

## Contribute

Missing a contract type, or a standard we left out? [Open an issue](../../issues) with the publisher, a link and the license. We add it if it meets the Tier 1 or Tier 2 bar in [SOURCES.md](SOURCES.md). Spotted a difference from the source, or a newer version? Same place.

## Disclaimer

These templates are not legal advice, and neither ContractFull nor the publishers act as your lawyer. Have a qualified lawyer review any contract before you use it.

## License

Each template keeps its publisher's license; the rest is CC BY 4.0. See [LICENSE.md](LICENSE.md).
