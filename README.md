# Kierkegaard diagnostic interlocutor

Ten literary voices for exploring choice, inwardness, anxiety, faith, love and the public. Vocabulary suggests a starting point; the interlocutor tests it against the person’s actual situation and changes course when the facts warrant it. Distinct works remain distinct, and direct or scholarly questions can receive direct answers.

**Version 3.0.0 — Candidate (2026-09-12).** This release adopts the current incremental
persona-distiller workflow. Package validation, source review and recognition are
separate gates: see [validation](transworld-identity/validation.json). Primary editions
were not reverified and bounded machine recognition was **not run (0 calls)** because
no configured model endpoint was available. Historical scores remain historical;
this release does not claim Standard accepted.

## Use and installation

The runtime consists of [SKILL.md](SKILL.md), [scope](references/scope.md), and the
relevant files under references/. Load scope with the core and voice before sustained
prose. The core supplies working links and their loading conditions. Explicit user
requests govern task, language and format; the voice does not override them.

```bash
git clone https://github.com/ariel-lee-1023/Kierkegaard-Diagnostic-Interlocutor.git kierkegaard-diagnostic-interlocutor
```

For a skill loader, place or link the cloned root under its skills directory using
the name `kierkegaard-diagnostic-interlocutor`. For another host, provide the core and scope, then the requested
references. There is one canonical runtime; the repository's discovery link
`.agents/skills/kierkegaard-diagnostic-interlocutor` points back to the root. [AGENTS.md](AGENTS.md) preserves
this workspace's existing conversational preferences and maintenance exception.

## Scope

The supplied translations cover the ten work-specific voices from the 1840s through 1849. The main Concluding Unscientific Postscript text, late polemics and live conversations are outside the established coverage. The source map distinguishes literary speakers, signed works and mixed editorial supplements. Philosophical anxiety and theological despair are not clinical diagnoses.

The retained modules contain translated excerpts and source summaries. The original
editions and old raw evaluation outputs were not supplied for this upgrade. Exact
quotation and contested attribution require the relevant edition. Historical style
measurements reflect translation and OCR and are descriptive, not output quotas.

## Layout and renovation record

- Root SKILL.md and references/: canonical runtime, including scope, frameworks and voice.
- AGENTS.md: existing workspace instructions, preserved without changing their preferences.
- .agents/skills/: relative discovery link to the canonical root.
- transworld-identity/: evidence, source review, prepared recognition profile/cases,
  current validation and lossless migration records; never loaded during ordinary runtime.
- transworld-identity/history/pre-20260912/: original provenance and pre-upgrade core.

The previous fidelity-ledger directory was migrated without discarding its evidence.
[Upgrade report](transworld-identity/upgrade-report.json) records claim decisions,
changed files, baseline hashes and applicability of each old result family.
[Preserved records](transworld-identity/preserved-records.json) verifies the old evidence
bytes. The upgrade keeps supported methods and voice while making refusals and judgments
conditional, correcting paths and removing numerical prose requirements.

## Sources and license

Hannay translations of Either/Or, Fear and Trembling, The Concept of Anxiety and The Sickness unto Death; Hong translations of Works of Love, Two Ages, and Philosophical Fragments / Johannes Climacus. The historical provenance also records the Postscript supplement and its limits.

[MIT](LICENSE) covers original repository material, not third-party source books or
translations. No full source books, credentials or scratch databases are published.
