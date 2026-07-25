# TrainCalc Knowledge Rules

This repository is the operational memory for TrainCalc.

## Context loading

For any TrainCalc strategy or execution request:

1. Read `NOW.md`.
2. Read `STRATEGY.md`.
3. Read `CURRENT-STATS.md` when metrics matter.
4. Read `DECISIONS.md` and `KNOWN-TRUTHS.md`.
5. Read the relevant task, page-priority, backlog, or weekly file.
6. Read the latest two weekly reviews when comparing trends.

## Sources of truth

- Production implementation: TrainCalc code and live website
- Google performance: Google Search Console
- Bing performance: Bing Webmaster Tools
- Traffic: GA4
- Revenue: Mediavine
- Current priorities: `NOW.md`
- Current metrics: `CURRENT-STATS.md`
- Strategic decisions: `DECISIONS.md`
- Confirmed lessons: `KNOWN-TRUTHS.md`
- Task scope and results: `tasks/`

## Rules

1. Never invent metrics, dates, results, or completed work.
2. Separate facts, assumptions, hypotheses, conclusions, and decisions.
3. Do not restart analysis from first principles when a relevant decision or task exists.
4. Identify any conflict before proposing work outside current priorities.
5. Prefer updating an existing file over creating a new file.
6. Do not create files for low-value pages without a concrete reason.
7. Completed tasks require a result, conclusion, lessons, and final decision.
8. Decisions are append-only.
9. Put evidence-supported reusable lessons in `KNOWN-TRUTHS.md`.
10. `CURRENT-STATS.md` contains only the latest verified snapshot.
11. Weekly files are historical snapshots; do not rewrite them as current state.
12. Every weekly review ends with no more than three priorities.
13. The system must reduce work, not generate administrative work.

## Update behavior

When a meaningful change occurs:

- update `NOW.md` if priorities or active work changed;
- update `CURRENT-STATS.md` if verified current metrics changed;
- update the relevant task when scope, progress, metrics, or results changed;
- append to `DECISIONS.md` for a strategic decision;
- update `KNOWN-TRUTHS.md` only for evidence-supported conclusions;
- update `BACKLOG.md` when ideas or future calculators change;
- add or update the current weekly review when weekly data is available.
