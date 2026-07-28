# Task — Calorie Deficit optimization

Phase: Measurement
Priority: P0
Created: 2026-07-25
Started: 2026-07-26
Deployment completed: 2026-07-26
Measurement started: 2026-07-26
Completed: —
Review date: August 31

## Objective

Increase qualified Bing traffic to the Calorie Deficit calculator through focused query- and page-level optimization, without causing a material Google regression.

## Context

This is the first Measurement-phase implementation of the Bing-first strategy. The experiment was deployed on 2026-07-26 and measurement started that day. The current supplied Bing baseline is an average position of 5.59 for the last 30 days; the GSC guardrail baseline is 16.1 for the last 28 days. Clicks, impressions, and CTR have not been supplied and must not be inferred.

## Baseline

- Source: Bing Webmaster Tools
- Baseline read date: 2026-07-27
- Bing reporting period: last 30 days
- Bing average position: 5.59
- Clicks: pending data import
- Impressions: pending data import
- CTR: pending data import
- GSC reporting period: last 28 days
- GSC average position: 16.1

## Scope

### Included

- GSC and Bing query analysis, recorded with source periods.
- Title and meta review and any implemented changes.
- Query-shaped sections that answer supported search intent.
- Relevant internal-linking changes.
- Focused E-E-A-T and safety improvements that support the ranking experiment.
- Depth improvements that better satisfy the page's supported search intent.
- Production deployment and the measurement window.
- Separate Bing evaluation and Google guardrail review.

### Excluded

- A full calculator rewrite.
- Broad guide production.
- Site-wide SEO changes.
- New-calculator implementation.
- Purchased links.
- Declaring success from rankings alone or before sufficient measurement.

## Planned work

- [ ] Export and record Bing query data and reporting period.
- [ ] Export and record GSC query data and reporting period.
- [ ] Identify supported query gaps and define focused page changes.
- [ ] Implement and log title/meta, query-shaped sections, and internal links.
- [x] Implement and log the approved E-E-A-T and safety improvements.
- [x] Confirm production deployment.
- [x] Register the measurement window and review date.
- [ ] Measure Bing primary metric and Google guardrails.

## Implementation log

- 2026-07-25: Task record initialized. No query analysis or implementation change is claimed yet.
- 2026-07-26: Added a personalized Tati author block and additional safety guards to the Calorie Deficit calculator as focused E-E-A-T improvements for the ranking experiment; production deployment was completed and measurement started.
- 2026-07-26: Registered the experiment with the initial supplied Bing average-position baseline of 5.82.
- 2026-07-27: Recorded the current supplied baselines: Bing average position 5.59 (last 30 days) and GSC average position 16.1 (last 28 days).
- Registration: Intervention is honest E-E-A-T plus depth improvements. No links were bought.

## Metrics

Primary success criterion: Bing average position reaches top 4 at the August 31 read.

Google guardrails:

- No material indexing loss.
- No unexplained material decline in Google clicks, impressions, or average position over comparable periods.

Measurement window: 2026-07-26 through the August 31 read.

## Result

The Measurement phase is in progress. The current Bing baseline is 5.59 (last 30 days); final evaluation remains pending the August 31 read.

## Conclusion

Pending the August 31 read.

## Lessons

Pending measurement. Do not promote observations to reusable lessons without supporting evidence.

## Decision

If the page is not top 4 on August 31, test a support-content cluster next. Only if that lever also fails should authority/links return to consideration.

## Follow-up

Record the August 31 Bing result against the top-4 criterion. If it fails, scope the support-content-cluster experiment; do not pursue authority or link acquisition first.
