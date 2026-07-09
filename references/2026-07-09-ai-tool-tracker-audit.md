# AI Tool Tracker Audit

Accessed: 2026-07-09

This note records recommended updates to the Skynet Jobs AI Tool Tracker.

## Main finding

The existing tracker still captures major 2023-2024 disruption tools, but it under-represents the 2025-2026 shift from copilots to agents that execute work.

## Recommended additions

| Tool | Category | Suggested threatened roles | Why it matters |
| --- | --- | --- | --- |
| Salesforce Agentforce | Customer Support / Sales | customer-service-rep, sales-rep, marketing-manager | Enterprise agent platform for customer, service, sales, and marketing workflows. |
| OpenAI Codex | Coding | software-engineer | Cloud software engineering agent for multi-step coding work. |
| Devin | Coding | software-engineer | Dedicated autonomous software engineer product; useful as an agentic coding benchmark signal. |
| Abridge | Healthcare | doctor, registered-nurse | Ambient clinical documentation compresses note-taking and admin work. |
| ServiceNow AI Agents | Enterprise Workflow | hr-specialist, project-manager, customer-service-rep | Agents embedded into enterprise IT, HR, CRM, and operations workflows. |
| Sierra | Customer Support | customer-service-rep | Enterprise AI agent platform for customer interactions. |
| Gatik | Autonomy | truck-driver, delivery-driver | Middle-mile driverless freight; stronger signal than demos alone. |
| Figure AI | Robotics | factory-assembler, warehouse-worker | Humanoid robotics in factory pilots and early deployments. |
| Bloomberg ASKB | Finance | financial-analyst, stock-trader | Agentic AI inside financial research workflows. |
| Ramp AI Agents | Finance / Procurement | bookkeeper, accountant | Finance and procurement agents for vendor, expense, compliance, and renewal workflows. |
| Legora or Spellbook | Legal | paralegal, lawyer | Legal AI ecosystem has matured beyond Harvey and CoCounsel into contract and law-firm workflows. |

## Existing entries to review

- Waymo: raise maturity if current commercial deployment and ride volume support it.
- Aurora Driver: raise maturity if commercial driverless trucking is active beyond pilots.
- Intercom Fin: raise maturity if current AI resolution rates and customer adoption support it.
- Amazon Go / Just Walk Out: reframe or lower maturity because the specific cashierless retail format has mixed adoption even though checkout automation remains important.
- GPT-4 / GPT-5: rename or split into "ChatGPT / GPT-5" and separate agentic workflow tools.

## Suggested evidence fields for future tool entries

- deploymentStatus: demo, pilot, production, scaled
- sourceType: official, customer case study, reporting, benchmark
- sourceUrl
- lastReviewed
- confidenceNote

## Caveats

Tool maturity is not model quality. It should reflect production deployment, workflow integration, customer adoption, and labor substitution pressure.
