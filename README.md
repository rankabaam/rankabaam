# B. Kim

Aviation operations and systems-safety professional building practical automation tools for dispatch workflows, live translation, media production, and public-facing web systems.

## Professional Focus

- Aviation operations and dispatch support
- Systems safety, risk analysis, and operational reliability
- Workflow automation and decision-support tools
- Python, VBA, Excel, HTML, FastAPI, WordPress, and FFmpeg
- AI-assisted development for recurring operational problems
- Documentation, regression control, and maintainable handoff

## Featured Projects

### Fieldframe — Reliable Photo Workflow

An interactive field-photo case study with eight checkpoints, IndexedDB persistence, deterministic network failures, stable retry IDs and archive-gated completion.

- Browser-only HTML/CSS/JavaScript demo with synthetic evidence
- Offline/retry/session-revocation scenarios and an exportable event log
- 12 reproducible public tests, architecture notes and retirement design
- Private-source verification is reported separately: 65 simulated-service checks passed on 2026-10-22

[View project and run instructions](https://github.com/rankabaam/Photo-Intake) · [Case study](https://github.com/rankabaam/Photo-Intake/blob/main/docs/CASE_STUDY.md)

---

### Parking Location Tool

A sanitized aviation decision-support portfolio demo. The latest extension uses synthetic Fuel Request-only records, while an older movement-state experiment is preserved for comparison.

**Current public demo**

- Runnable Python status engine
- Latest Fuel Request-only mode with 12/24/48-hour freshness bands
- Searchable dark/light HTML table and ramp view
- Age-based visual location inclusion with stale records flagged Uncertain
- Unit tests for stale-data and movement-state behavior

[View project](https://github.com/rankabaam/parking-location-tool)

---

### Church Live Translation System

A runnable FastAPI and WebSocket demonstration of a local-first caption workflow, now with an additional offline English/Spanish phrasebook preview.

**Current public demo**

- REST processing, session endpoints, and a language-selection demonstration
- WebSocket snapshots and live viewer updates
- Partial-fragment and duplicate final-segment suppression (synthetic data)
- Glossary-assisted terminology visibility
- Bounded session memory for reconnecting viewers
- Unit-tested pipeline logic

[View project](https://github.com/rankabaam/church-live-translation-system)

---

### Sermon Video Automation

A config-driven Python and FFmpeg portfolio workflow, with an independent v1.4-style dashboard preview and simulated safe publication-state recovery.

**Current public demo**

- Safe dry-run mode and a separate interactive dashboard UI mockup
- Optional authorized execution mode
- YAML configuration
- Latest-recording discovery
- Generated intro, normalization, concatenation, WAV export, and upload-ready packaging
- Tests for naming, discovery, command construction, and synthetic in-place embed recovery

[View project](https://github.com/rankabaam/sermon-video-automation)

---

### Legacy Website Rebuild

A WordPress rebuild case study with additional responsive community-language-program and fictional recent-sermon layout samples.

**Current documentation**

- Directly linked case-study sections
- Operational maintenance model
- Event-calendar refinement and mobile-friendly language-program landing-page sample
- Sermon-media workflow integration and static latest-message card preview
- Privacy-safe lessons learned

[View project](https://github.com/rankabaam/legacy-website-rebuild)

## Independent Operations Demos

Four **independently implemented, runnable** operations demonstrations. Photo Intake now includes the interactive JavaScript case study featured above; the others retain Python workflows. Each has a README, source code, synthetic sample inputs, unit tests, and an offline HTML preview. These are general-purpose reconstructions of workflow concepts, **not copies of workplace implementations**.

| Repository | Demonstration | Source & sample |
| --- | --- | --- |
| [Schedule Board](https://github.com/rankabaam/Schedule-Board) | Date-grouped tasks, status tags, and an offline dashboard | [Code](https://github.com/rankabaam/Schedule-Board/tree/main/src) · [Preview](https://github.com/rankabaam/Schedule-Board/blob/main/demo/preview.html) |
| [Asset Inventory](https://github.com/rankabaam/Asset-Inventory) | Asset register reconciliation and review-oriented statuses | [Code](https://github.com/rankabaam/Asset-Inventory/tree/main/src) · [Preview](https://github.com/rankabaam/Asset-Inventory/blob/main/demo/preview.html) |
| [Photo Intake / Fieldframe](https://github.com/rankabaam/Photo-Intake) | Durable capture, retry simulation and verified completion | [Code](https://github.com/rankabaam/Photo-Intake/tree/main/showcase) · [Case study](https://github.com/rankabaam/Photo-Intake/blob/main/docs/CASE_STUDY.md) |
| [Inspection Analytics](https://github.com/rankabaam/Inspection-Analytics) | Quality metrics, denominators, follow-up analysis, and reporting | [Code](https://github.com/rankabaam/Inspection-Analytics/tree/main/src) · [Preview](https://github.com/rankabaam/Inspection-Analytics/blob/main/demo/preview.html) |

Every demo uses fictional scenarios and contains no actual employer files, customer information, location logs, site identifiers, source spreadsheets, or internal inspection data. The Photo Intake demonstration is a portfolio prototype, not a production deployment.

---

## Working Approach

1. Identify recurring operational friction.
2. Map the real workflow and failure modes.
3. Build the smallest useful tool.
4. Add conservative safeguards and clear status information.
5. Separate public demonstrations from production data and infrastructure.
6. Test deterministic behavior and document the handoff.
7. Improve the system through operational feedback and regression review.

Independent portfolio previews describe public-safe features, not the latest private production code. Recent GitHub checks validate demo tests only, not live integrations.

All public repositories are intentionally sanitized and exclude employer-confidential information, private organizational data, credentials, production records, and copyrighted operational media.
