# Changelog

## 0.3.0 — 2026-11-16

- Translate the skill entry point and all nine references into English. The plugin is now written in English throughout.
- Update repository links to `XuZhaoyue1995/CFDAgent`.

## 0.2.2 — 2026-10-22

- Refresh solver guidance, reference links, and family counts.

## 0.2.1 — 2026-10-07

- Replace the plugin icon with a closed fan outline without lettering.

## 0.2.0

First public release.

- One skill entry point (`cfdagent`) with nine references read on demand: solver selection, case setup, mesh quality, execution, result validation, benchmark library, post-processing and delivery, working notes, and plugin evaluation.
- A solver map covering 11 external solver families and PyIB, with guidance for recommending candidates and letting the user choose a single solver or a cross-solver comparison.
- Guidance on startup trial runs versus production runs: resource and time estimates, stopping criteria and monitoring.
- Completion judged against the user's goal and the evidence. Exported figures and reports are opened and checked for overflow, overlap, clipped text and illegibility before delivery.
- Manifests for Claude (`.claude-plugin/plugin.json`) and Codex (`.codex-plugin/plugin.json`) sharing one `skills/` folder.
