# Survey Instrument Testing Tool
### Canadian GRC Compliance + GBA Plus / ACS+ Intersectional Analysis

A single-file interactive dashboard for survey instrument design, testing, and compliance review, built for Canadian federal and provincial research teams.

---

## What it does

| Feature | Details |
|---|---|
| **GBA Plus / ACS+ checklist** | All 17 items across Steps 1–5 (WAGE Enhanced Step-by-Step Guide, 2023) |
| **Evidence library** | Every checklist item has references, alternatives, and quick actions from real Canadian sources |
| **Identity factor grid** | 10 factors assessed for both survey versions (A/B) |
| **GRC scorecard** | PIPEDA · Loi 25 · Code MRIA · EPTC 2 / TCPS 2 · OLA / LLO |
| **A/B survey comparison** | Original 12-question vs. optimized 9-question instrument |
| **Cognitive simulation** | Fatigue modelling, dropout prediction, response quality curves |
| **AI analysis** | Integrated GRC + GBA Plus recommendations via Claude API |

---

## Using the AI analysis feature

The AI analysis panel requires an **Anthropic API key**. Your key is used directly from your browser — it is never stored or sent anywhere except Anthropic's API.

1. Get an API key at [console.anthropic.com](https://console.anthropic.com)
2. Paste it into the **API key** field in the AI analysis panel
3. Complete some checklist items and run a simulation
4. Click **Analyze**

> **Note:** The key field is not persisted between sessions. You will need to re-enter it each time you visit the page.

---

## Evidence sources

All GBA Plus checklist items link to real Canadian government and research sources:

- [Women and Gender Equality Canada (WAGE) — GBA Plus Step-by-Step Guide, 2023](https://women-gender-equality.canada.ca/en/gender-based-analysis-plus/apply-to-work.html)
- Canada School of Public Service (CSPS):
  - [INC101 — Introduction to GBA Plus](https://catalogue.csps-efpc.gc.ca/product?catalog=INC101&cm_locale=en)
  - [INC102 — GBA Plus: Applying Tools and Best Practices](https://catalogue.csps-efpc.gc.ca/product?catalog=INC102&cm_locale=en)
  - [INC115 — Addressing Disability Inclusion and Barriers to Accessibility](https://catalogue.csps-efpc.gc.ca/product?catalog=INC115&cm_locale=en)
  - [INC117 — Advancing the Conversation on Systemic Racism](https://catalogue.csps-efpc.gc.ca/product?catalog=INC117&cm_locale=en)
  - [IRA142 — Cultural Competency: Indigenous Perspectives](https://catalogue.csps-efpc.gc.ca/product?catalog=IRA142&cm_locale=en)
- [First Nations Information Governance Centre — OCAP® Principles](https://fnigc.ca/ocap-training/)
- [Inuit Tapiriit Kanatami — National Inuit Strategy on Research](https://itk.ca/projects/national-inuit-strategy-on-research/)
- Statistics Canada:
  - [Non-response Bias — Quality Guidelines (Cat. no. 12-539-X)](https://www150.statcan.gc.ca/n1/pub/12-539-x/12-539-x2009001-eng.pdf)
  - [Gender, Diversity and Inclusion Statistics Hub (GDIS Hub)](https://www.statcan.gc.ca/hub-carrefour/gdis-sgdi/index-eng.htm)
  - [Canadian Internet Use Survey (CIUS)](https://www.statcan.gc.ca/en/survey/household/4432)
  - [Rural Canada Statistics Portal](https://www.statcan.gc.ca/en/subjects-start/society_and_community/rural_canada)
- Treasury Board Secretariat:
  - [Directive on Results](https://www.tbs-sct.canada.ca/pol/doc-eng.aspx?id=31306)
  - [GBA Plus Evaluation Primer, 2019](https://www.canada.ca/en/treasury-board-secretariat/services/audit-evaluation/evaluation-government-canada/gba-primer.html)
  - [Privacy Implementation Notice 2023-02](https://www.canada.ca/en/treasury-board-secretariat/services/access-information-privacy/access-information-privacy-notices/2023-02-evaluation.html)
- [Privy Council Office — Disaggregated Data Job Aid](https://www.canada.ca/en/privy-council/corporate/transparency/reporting-spending/departmental-results-reports/2022-2023/gender-based-analysis-plus.html)
- Department of Justice Canada:
  - [Official Languages Act (R.S.C. 1985, c. 31)](https://laws-lois.justice.gc.ca/eng/acts/O-3.01/index.html)
  - [Accessible Canada Act (S.C. 2019, c. 10)](https://laws-lois.justice.gc.ca/eng/acts/A-0.6/index.html)
- [W3C — Web Content Accessibility Guidelines (WCAG) 2.1 AA](https://www.w3.org/TR/WCAG21/)
- [Truth and Reconciliation Commission — Calls to Action](https://nctr.ca/records/reports/#trc-reports)
- [UN Women / UNPRPD — Intersectionality Resource Guide and Toolkit, 2022](https://www.unwomen.org/en/digital-library/publications/2022/01/intersectionality-resource-guide-and-toolkit)
- [CIHR — Guidelines for Health Research Involving Aboriginal Peoples (2007–2010)](https://cihr-irsc.gc.ca/e/29134.html)
- [Canadian Heritage — Canada's Anti-Racism Strategy 2024–2028](https://www.canada.ca/en/canadian-heritage/services/combatting-racism-discrimination/canada-anti-racism-strategy.html) *(s1b Positionality · s3b Historical relationship)*
- [Canadian Heritage — Action Plan: Black Canadians](https://www.canada.ca/en/employment-social-development/programs/social-development-partnerships/supporting-black-communities.html) *(s2d Underrepresented groups)*
- [Department of Justice Canada — Employment Equity Act S.C. 1995, c. 44](https://laws-lois.justice.gc.ca/eng/acts/e-5.401/) *(s2d Underrepresented groups · s3d Power dynamics)*
- [Canadian Race Relations Foundation (CRRF)](https://www.crrf-fcrr.ca/) *(s1b · s2d · s3b · s3d)*
- [National Inquiry into MMIWG — Calls for Justice, 2019](https://www.mmiwg-ffada.ca/final-report/) *(s3b Historical relationship · s3d Power dynamics)*


---

## Frameworks covered

| Framework | Authority | Applies to |
|---|---|---|
| PIPEDA | Office of the Privacy Commissioner | Federal & private sector |
| Loi 25 / Law 25 | Commission d'accès à l'information (Québec) | Québec operations |
| MRIA Code | Marketing Research & Intelligence Association | Survey research |
| TCPS 2 / EPTC 2 | CIHR · NSERC · SSHRC | Research ethics |
| OLA / LLO | Office of the Commissioner of Official Languages | Federal institutions |
