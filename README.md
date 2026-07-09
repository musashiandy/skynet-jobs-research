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
