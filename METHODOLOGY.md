# Methodology

Skynet Jobs is an AI job-risk tracker. The goal is not to claim perfect forecasts. The goal is to make automation exposure, AI adoption, productivity uplift, and workforce displacement signals easier to inspect and discuss.

## Research posture

Skynet Jobs should distinguish between:

- observed data;
- source-reported estimates;
- modeled exposure;
- analyst interpretation;
- forecasts or scenarios.

These categories should not be blended into a single claim without labeling.

## Current data posture

The production website currently uses curated static data. That keeps the public site fast, low-cost, and resilient. Research inputs and methodology notes can evolve independently from runtime infrastructure.

Planned v2 architecture may introduce nightly research workflows that produce reviewed static snapshots. The production site should still prefer static published artifacts over direct runtime database reads for public metrics.

## Role risk model

Role risk should be treated as a composite index, not a direct probability that a job disappears.

A reasonable role-risk model can include:

- task automation exposure;
- share of work tasks affected by AI;
- current AI capability fit;
- adoption speed in the occupation or sector;
- regulatory and safety constraints;
- physical-world requirements;
- human trust and accountability requirements;
- wage/cost pressure;
- evidence of current displacement or hiring slowdown;
- evidence of productivity uplift without displacement.

## Suggested scoring bands

- 0-24: Low exposure
- 25-49: Moderate exposure
- 50-74: High exposure
- 75-100: Critical exposure

These are communication bands, not mathematically precise categories.

## Change discipline

When a metric changes, record:

- date of change;
- source or reason;
- affected metric or role;
- old value;
- new value;
- confidence level;
- reviewer notes.

## Human review

AI-assisted research can help discover, summarize, and compare sources, but public-facing claims should be reviewed before publication. AI-generated summaries should preserve source attribution and uncertainty.
