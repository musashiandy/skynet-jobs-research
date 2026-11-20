# Hiring and banking article publication — November 20, 2026

## Authorization, dates and scope

On November 20, 2026, America/New_York, the project owner explicitly instructed publication of both named articles, one dated yesterday and one today. The tech-hiring article displays November 19 and the banking article November 20, in the requested order. Both are actually released November 20; the earlier display date does not establish an earlier deployment or research check. Codex prepared the publication edit and rechecked the cited primary sources on November 20 under that authorization. No external human editor or independent replication is claimed.

- [The tech hiring rebound has an entry-level problem](https://jobs.skynetproxy.com/analysis/tech-hiring-rebound-entry-level-problem) — source draft `editorial/2026-11-05-ai-market-series/drafts/02-tech-hiring-entry-level.md`.
- [Banks are cutting jobs. How much of that is actually AI?](https://jobs.skynetproxy.com/analysis/banks-cutting-jobs-how-much-is-ai) — source draft `editorial/2026-11-05-ai-market-series/drafts/03-banking-ai-attribution.md`.

The original November 7 narratives are retained, with a dated dashboard description, a monitoring paragraph for hiring, explicit source-check dates, and the bank's FTE label and qualitative-attribution terminology. The existing conceptual covers, alt text and AI-illustration disclosures are preserved. The other seven drafts remain unpublished. No occupational score, workforce-event record, tracker total or dataset-review date changes.

## Sources checked November 20

### tech-hiring-rebound-entry-level-problem

- Guillermo Gallacher, Indeed Hiring Lab: AI and Job Postings: From Destruction to Creation? Published July 8, 2026. Senior roles contributed 71% of the May 2025–May 2026 increase in software-development postings; this is not the share of all jobs, completed hires, or proof of AI causation. https://hiringlab.indeed.com/2026/07/08/ai-and-job-postings-from-destruction-to-creation/ Accessed November 20, 2026.
- Challenger, Gray & Christmas: October Layoffs at Three-Year Low; Seasonal Hiring Plans Up 26%. Published November 5, 2026. Employer-announced hiring plans, including seasonal fulfillment roles classified by employer sector; not completed software-engineering hires. https://www.challengergray.com/blog/october-layoffs-at-three-year-low-seasonal-hiring-plans-up-26/ Accessed November 20, 2026.
- Stanford Digital Economy Lab with ADP Research: Canaries Dashboard. Living dashboard, displaying last updated October 21, 2026 when checked. Balanced ADP client-firm sample; age differs from seniority, and modeled exposure differs from verified adoption. No new numerical endpoint is asserted. https://digitaleconomy.stanford.edu/project/indicators/canaries-dashboard/ Accessed November 20, 2026.
- Neale Mahoney, Erika McEntarfer and Karsen Wahal, Stanford SIEPR: What is really happening to jobs? Separating AI hype from reality. Published July 2026. Research synthesis engages interest rates, pandemic hiring, remote work and timing as alternative or interacting explanations. https://siepr.stanford.edu/publications/policy-brief/what-really-happening-jobs-separating-ai-hype-reality Accessed November 20, 2026.

### banks-cutting-jobs-how-much-is-ai

- Barclays PLC: Q3 2026 Results Presentation. Published October 22, 2026. Slide 10 / physical PDF page 10: approximately 5,000 expected FTE reductions from FY26 structural cost actions, subject to consultation; the approximately 60% support-function statement applies to H2 actions. Company disclosure, not verified completed separations, exclusive AI causation, or net employment change. https://home.barclays/content/dam/home-barclays/documents/investor-relations/ResultAnnouncements/Q32026Results/Q326-Results-Presentation.pdf#page=10 Accessed November 20, 2026.
- Jeffrey S. Allen, Federal Reserve Board, FEDS Notes: Monitoring AI Adoption in the U.S. Economy. Published April 3, 2026. Compares survey evidence through 2025; financial-sector adoption supplies context, not causal evidence about Barclays’ plan. https://www.federalreserve.gov/econres/notes/feds-notes/monitoring-ai-adoption-in-the-u-s-economy-20260403.html Accessed November 20, 2026.
- Skynet Jobs Research: AI Layoff Attribution. Project definitions, not independent evidence of company outcomes. https://github.com/musashiandy/skynet-jobs-research/blob/main/methodology/ai-layoff-attribution.md Accessed November 20, 2026.

Barclays slide 10 was checked as extracted text and as a rendered PDF page, including both footnotes. No later implementation outcome or completed reduction is inferred. The Stanford dashboard displayed an October 21, 2026 update; the access date is not its data date. The hiring article makes no new dashboard endpoint claim. The cited historical publications retain their observation periods instead of being described as November hiring measurements. These checks support the bounded article claims, not a comprehensive literature review.

## Cover integrity

- `02-tech-hiring-entry-level.webp`: 147,782 bytes, 1672×941; SHA-256 `c5b2515abc4c1bef51afa2c6bec8de978e1d11dbe26df7a7c57f377a84bb2900`. Copied byte-for-byte to `public/analysis/tech-hiring-entry-level.webp`.
- `03-banking-ai-attribution.webp`: 184,658 bytes, 1672×941; SHA-256 `d0712026f4d95c34a4cdbb432a9ca344cffc6bfddc8be2a4f1c042bda18d2c8f`. Copied byte-for-byte to `public/analysis/banking-ai-attribution.webp`.

## Deployment status

**Published and verified live November 20, 2026.** The production deployment succeeded for application revision `8cd88a5c205a3369a6428138dbe1e20454176ada`, completing at 20:30:58 UTC. The prerequisite evidence revision `abb5459` was pushed first. Direct HTTPS verification completed at 2026-11-20T20:31:33.420390+00:00.


### Publication verification

- Local validation: ESLint passed with zero errors and seven existing React Refresh warnings; all 103 tests across 14 files passed; the production build prerendered 67 routes. GitHub Actions also passed its lint, test, build, upload and cache-invalidation steps.
- Each canonical article returned HTTP 200. All final source paragraphs and headings, the requested displayed date, matching Article JSON-LD date, canonical URL, social image metadata and indexing directive were checked. Both entry bundles/stylesheets loaded.
- Both live covers returned HTTP 200 and matched the approved WebP files byte-for-byte, with the SHA-256 checksums above.
- The analysis listing, sitemap and both AI discovery guides returned HTTP 200 and included both article routes. The previously released measurement article also remained available.
- The workstation resolver could not resolve the custom host. Public DNS-over-HTTPS confirmed its CDN alias; verification used the canonical HTTPS URL, original Host header and TLS SNI with normal certificate validation through that target. No certificate bypass was used.

| Canonical route | HTTP | Article date | Actual release |
| --- | --- | --- | --- |
| `/analysis/tech-hiring-rebound-entry-level-problem` | 200 | 2026-11-19 | 2026-11-20 |
| `/analysis/banks-cutting-jobs-how-much-is-ai` | 200 | 2026-11-20 | 2026-11-20 |

Publication is complete. The other seven drafts remain unpublished; no social messages were sent.
