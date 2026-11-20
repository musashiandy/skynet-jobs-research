# Skynet Jobs Research

Public research notes, source references, methodology, and data provenance for [Skynet Jobs](https://jobs.skynetproxy.com), the AI job-risk tracker from SkynetProxy.

This repository exists to make the public-facing claims, sources, assumptions, and update process behind Skynet Jobs easier to inspect without publishing the private website/application source code.

## What belongs here

- Source references for labor-market, automation, robotics, AI adoption, and displacement research
- Methodology notes explaining how public research is interpreted for the site
- Data dictionaries for public metrics and static datasets
- Change logs for source and methodology updates
- Notes on uncertainty, limitations, and future improvements

## What does not belong here

- Private application source code
- AWS account details, credentials, ARNs, deployment secrets, or infrastructure identifiers
- Subscriber data or any personal information
- Proprietary unpublished datasets
- Unreviewed claims presented as final research

## Current status

Skynet Jobs is currently a static public site backed by curated, versioned research inputs. The public site does not read directly from this repository at runtime. This repo is intended as the public evidence trail and methodology companion.

Future versions may add generated public data snapshots, nightly research notes, or machine-readable source manifests after review.

## Editorial research

[Ten full AI market and industry article drafts, completed November 7, 2026](editorial/2026-11-05-ai-market-series/drafts/README.md) cover hiring, software, banking, healthcare, legal services, robotics, freelance economics, working time, and career transitions. Each has a complete narrative, inline citations, and source notes. The [original research briefs](editorial/2026-11-05-ai-market-series/README.md), source registers, and claim-check ledger preserve the evidence trail and distinguish observed outcomes from surveys, company plans, and scenarios.

Article 01, [AI is spreading. Why do the jobs numbers disagree?](https://jobs.skynetproxy.com/analysis/ai-is-spreading-why-jobs-numbers-disagree), was published November 18 after a targeted source refresh. Articles 02 and 03 were published and verified live November 20, dated November 19 and November 20 respectively; the other seven remain unpublished pending editorial review. See the [hiring and banking publication record](data-notes/2026-11-20-hiring-and-banking-publication.md). See the [publication evidence](https://github.com/babbabooieq/skynet-jobs-research/blob/main/data-notes/2026-11-18-ai-jobs-numbers.md). No role-risk scores or workforce metrics changed.

## Repository map

```text
README.md
SOURCES.md
METHODOLOGY.md
DATA_DICTIONARY.md
CHANGELOG.md
LIMITATIONS.md
references/
  README.md
  2026-07-09-ai-tool-tracker-audit.md
  2026-07-09-enterprise-ai-layoff-sources.md
data-notes/
  README.md
  2026-07-09-site-update-ledger.md
methodology/
  ai-layoff-attribution.md
  scoring-model.md
editorial/
  2026-11-05-ai-market-series/
    README.md
    claim-check-ledger.md
    draft-review-notes.md
    01-...md through 10-...md
    drafts/
      README.md
      01-...md through 10-...md
```

## Citation style

When adding a source, include:

- title;
- publisher or author;
- publication date when available;
- URL or stable identifier;
- accessed date;
- short note on what the source supports;
- any important limitation or caveat.

## License

This repository is for public research notes and methodology. Source publications remain owned by their original publishers. Do not copy full third-party reports or paywalled material into this repository.
