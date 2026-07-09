# Data Dictionary

This file defines public-facing Skynet Jobs metric concepts. It does not describe private application internals.

## Role risk score

A 0-100 composite index representing estimated exposure to AI and automation pressure.

Interpretation: higher values indicate greater exposure, not guaranteed displacement.

## Risk level

A label derived from the role risk score.

- Low
- Moderate
- High
- Critical

## AI adoption

Estimated or source-reported share of organizations, enterprises, workers, or workflows using AI tools depending on the source context.

Important: adoption definitions vary by source and should be documented per metric.

## Workers impacted

A broad public-facing indicator for workers affected by AI-related workforce changes, automation exposure, task redesign, or displacement signals.

Important: this should not be presented as a direct BLS statistic unless the underlying metric is specifically from BLS.

## Productivity uplift

Estimated percentage improvement in output, throughput, speed, quality, or task completion measured in a specific study or scenario.

Important: productivity results vary by task, baseline skill, measurement design, and workflow integration.

## AI-attributed layoffs

Layoff events or public reports where AI is cited as a contributing factor.

Important: attribution quality varies. Some reports cite AI directly, some imply automation, and some reflect company narratives that may be incomplete.

## AI link score

A 0-100 directional estimate of how materially AI appears connected to a layoff or restructuring event.

Interpretation: higher values mean the AI signal is stronger. The score is not a probability that AI directly replaced each affected worker and should not be read as causal precision.

Suggested interpretation:

- 90-100: direct company-stated AI, automation, or agent connection.
- 70-89: strong AI-linked restructuring, reallocation, or AI-native org design signal.
- 40-69: mixed evidence or analyst attribution.
- below 40: weak signal; generally exclude from the public AI-attributed tracker.

## AI tool maturity

A 0-100 directional score for how widely deployed, production-ready, and workflow-relevant an AI tool appears to be.

Interpretation: higher maturity indicates stronger current disruption potential, not necessarily better model quality. Maturity can rise when a tool moves from demo to enterprise deployment, ships agentic execution, expands into more geographies, or becomes embedded in a core workflow.

## Industrial robot shipments/installations

Annual robot adoption figures, usually sourced from IFR or related robotics reporting.

Important: robotics adoption is not a direct measure of job loss.

## Risk movers

Roles whose risk score changed over a defined update period.

Important: no movement should be displayed clearly when data does not support a meaningful change.
