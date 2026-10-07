# Guilt corpus viewer

A browser tool for exploring the annotated Facebook corpus of the PLEDGE guilt-assignment study
(Hungarian political actors and news outlets, 2025–2026).

**This repository contains code only – no data.** The page opens a corpus file (`corpus.json.gz`) from your own
computer and does all processing inside your browser; nothing is uploaded. The corpus file is produced in the
private analysis repository (`results/viewer/corpus.json.gz`) and is available to project members only.

- **Browse:** filter by actor/outlet, period and guilt assignment, search the text, read posts with
  guilt-assignment sentences highlighted, and drill into any week from the timeline.
- **Charts:** interactive figures for data coverage and RQ1–RQ4, each downloadable as SVG.

The page is published with GitHub Pages by `.github/workflows/pages.yml`, which refuses to publish if a data
file is ever added.
