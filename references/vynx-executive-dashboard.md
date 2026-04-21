# VYNX Executive Dashboard Design

Use this file when the user wants the monthly leadership dashboard structure rather than raw KPIs only.

## Section 1: Conversion Funnel

KPIs:

- RFQ-to-proposal conversion
- proposal-to-order conversion
- technical-validation progression

RAG logic:

- green: within target band
- amber: 5-10% below target or declining for 2 periods
- red: more than 10% below target or materially deteriorating

Drill-downs:

- region
- segment
- distributor tier
- deal size band

Leadership questions:

- are we screening too little or too much?
- where is leakage increasing?
- which distributors are creating false pipeline?

## Section 2: Speed and Responsiveness

KPIs:

- applications engineering response time
- proposal turnaround time
- days in technical validation
- days in proposal readiness

RAG logic:

- green: SLA met
- amber: SLA missed in pockets
- red: structural bottleneck

Drill-downs:

- applications engineering team
- product line
- region
- distributor

Leadership questions:

- is capacity the issue, or intake quality?
- where are poor handoffs slowing the system?

## Section 3: Deal Quality

KPIs:

- proposal rubric average score
- plant-visit-to-next-step conversion
- percent of proposals with service review complete
- percent of strategic deals with full stakeholder map

RAG logic:

- green: quality standards consistently met
- amber: inconsistent by segment or distributor
- red: standards are not controlling release

Drill-downs:

- sales manager
- distributor
- application type

Leadership questions:

- are field teams doing the work or just completing templates?
- which quality gap most predicts stalled deals?

## Section 4: Distributor Performance

KPIs:

- win rate by distributor tier
- stalled-deal reasons by distributor
- artifact compliance by distributor
- escalation count by distributor

RAG logic:

- green: tier behavior aligned with support model
- amber: pockets of drift
- red: tiering is not being enforced

Drill-downs:

- distributor
- region
- segment

Leadership questions:

- are we over-supporting weak partners?
- which partners should be upgraded, downgraded, or restricted?

## Section 5: Execution Confidence

KPIs:

- percent of deals with service engaged pre-proposal when required
- handoff acceptance rate from service
- lost deals coded to implementation or service confidence
- early post-sale escalation rate on newly won deals

RAG logic:

- green: execution confidence improving
- amber: risk contained but visible
- red: selling ahead of delivery confidence

Drill-downs:

- region
- product line
- deal type

Leadership questions:

- are we winning responsibly?
- is service being used as a late-stage rescue instead of an early confidence builder?
