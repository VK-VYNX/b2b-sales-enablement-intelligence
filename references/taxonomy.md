# Taxonomy

Use this file as the routing layer for the skill. Classify work by both domain category and reusable intelligence theme.

## Source Categories

These are the main domain buckets represented by the package:

1. Sales Enablement
2. Sales Training
3. Sales Coaching
4. Sales Enablement Technology
5. Sales Enablement Content
6. Sales Methodology
7. Sales
8. FAQ

## Canonical Intelligence Themes

Use these themes to merge repeated ideas across categories:

1. Function purpose and scope
2. Strategy and operating model
3. Roles, ownership, and team structure
4. Stakeholder management and cross-functional alignment
5. Onboarding, readiness, training, and reinforcement
6. Coaching systems and manager enablement
7. Content strategy, governance, and adoption
8. Methodology selection, rollout, and adherence
9. Technology selection, integration, and usage
10. Measurement, KPIs, and business impact
11. Program governance, intake, and prioritization
12. Maturity models and sequencing
13. FAQ clarifications and first-principles answers

## Routing Rules

- If the request is about function design, ownership, maturity, intake, or stakeholder alignment, prioritize operating-model and stakeholder references.
- If the request is about rep capability building, prioritize training and coaching references separately. Do not collapse them into one concept.
- If the request is about tools, first test whether the issue is actually process, manager behavior, content quality, or methodology adoption.
- If the request is about measurement, distinguish outputs, performance levers, and business outcomes.
- If multiple categories touch the same idea, synthesize it once as a canonical principle and cross-reference the categories.

## Reference Architecture

Keep the package focused on repeated, durable intelligence in canonical files such as:

- `core-principles.md`
- `diagnostics.md`
- `operating-model.md`
- `stakeholders.md`
- `measurement.md`
- category files for domain-specific nuance

## Working Assumption

Treat domain categories as routing helpers, not as final truth. If a topic is better explained by a cross-cutting theme, classify it by theme for the actual recommendation logic.
