# TrainCalc Decisions

This is an append-only journal. Add a new decision when direction changes; do not rewrite historical decisions.

## DEC-001 — Prioritize Bing-first optimization

Date: 2026-07-25
Status: active

### Decision

Prioritize focused optimization of proven Bing opportunities while maintaining Google guardrails.

### Reason

Bing is already a material source of revenue and may offer opportunities that do not depend on high domain authority.

### Evidence

- Approximately 48% of current revenue is attributed to Bing.
- DR is approximately 2.
- Calorie Deficit has a recorded Bing average-position baseline of 6.25.

### Consequences

Start with page-level query, title/meta, query-shaped content, and internal-linking work; evaluate Bing and Google separately.

### Revisit when

Verified channel data shows Bing is no longer material, or measured page experiments fail to produce useful signals.

### Superseded by

—

## DEC-002 — Improve proven pages before large-scale expansion

Date: 2026-07-25
Status: active

### Decision

Prioritize improvement of existing calculator pages before a large-scale program of new calculator launches.

### Reason

Development capacity is limited and existing pages can be selected using observed demand and performance data.

### Evidence

- Current strategy favors proven pages and narrow calculator intent.
- A ranked list of existing candidates is maintained in `pages/priorities.md`.

### Consequences

New calculators remain candidates unless explicitly approved; selection waits until active priorities are complete or consciously reprioritized.

### Revisit when

Verified data shows existing-page work has lower expected value than a specific new calculator opportunity.

### Superseded by

—

## DEC-003 — Do not run a broad guide-production strategy

Date: 2026-07-25
Status: active

### Decision

Do not pursue broad generic guide production as the current growth strategy.

### Reason

TrainCalc's strategic thesis is calculator-driven acquisition, not generic health publishing.

### Evidence

- The active thesis prioritizes narrow calculator intent and existing calculator pages.

### Consequences

Guides require a specific calculator-cluster or acquisition rationale to be considered.

### Revisit when

Verified evidence shows guides are a higher-leverage acquisition path than calculator-focused work.

### Superseded by

—

## DEC-004 — Postpone localization until a measurable trigger

Date: 2026-07-25
Status: active

### Decision

Do not launch localization now.

### Reason

Current effort is allocated to proven page optimization and bounded experiments.

### Evidence

- Approximately 91% of current revenue is from the US.
- No verified localization demand or business case has been recorded.

### Consequences

Localization is explicitly out of current scope.

### Revisit when

Verified non-US demand, revenue opportunity, and an implementation case justify competing with active priorities.

### Superseded by

—

## DEC-005 — Treat authority as a means, not the primary KPI

Date: 2026-07-25
Status: active

### Decision

Use authority-building only when it supports measurable acquisition or revenue outcomes.

### Reason

Low authority has not prevented meaningful Bing contribution, and current constraints favor direct opportunity work.

### Evidence

- DR is approximately 2 while Bing accounts for approximately 48% of revenue.

### Consequences

Do not build a complex link-building platform or optimize work around authority metrics alone.

### Revisit when

Evidence shows authority is the binding constraint for the highest-value opportunities.

### Superseded by

—

## DEC-006 — Postpone knowledge-base automation

Date: 2026-07-25
Status: active

### Decision

Keep the knowledge base manual until at least four weekly review cycles are complete.

### Reason

The system must reduce context-restoration time without becoming a product to maintain.

### Evidence

- This is the first lightweight implementation.

### Consequences

No automation, CI, imports, dashboards, or validation scripts are added in version 1.

### Revisit when

Four manual weekly reviews are complete and a repeated, material maintenance problem is documented.

### Superseded by

—
