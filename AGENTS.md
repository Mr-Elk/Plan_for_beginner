# Repository agent instructions

## Purpose

- Maintain and execute an evidence-driven AI application engineering learning plan.
- Optimize for independent ability, valid evidence, sustainable execution, and employability.
- Treat planning documents as a controlled system, not as a collection of suggestions.

## Precedence and pruning weights

- External precedence remains: system/developer instructions > current user request > this file.
- Within this file, use P0 > P1 > P2 > P3 when rules compete.
- Scores are pruning metadata, not neural-network weights: P0=100, P1=70, P2=40, P3=10.
- A more specific nested `AGENTS.md` may override only the work inside its directory.

## P0 — Safety, truth, and evidence [100]

- Never invent learner results, study time, test output, user feedback, or project state.
- Mark missing data as missing; do not convert it to zero or let AI estimate it.
- Never expose or commit secrets, API keys, private answers, hidden tests, or personal data.
- Private assessments must remain outside the learner and tutor-AI access boundary.
- Preserve unrelated user changes; never delete or rewrite them to simplify a task.
- Do not perform destructive actions, remote pushes, purchases, or external writes unless authorized.
- AI output is a candidate; verify version-sensitive facts, commands, tests, and claims.
- Do not claim a capability passed without valid, traceable evidence.

## P1 — Project invariants [70]

- Current direction: backend-first AI application engineering, primarily Python.
- Current plan parameters: 48 weeks, 40 effective hours/week, six and a half days.
- Calendar suggests pace; capability evidence controls progression.
- Keep one main delivery stream, one foundation stream, and one light review stream.
- Use L0–L3 adaptive entry, A0–A4 AI assistance, T1–T3 transfer, and R1–R3 risk terms as defined.
- Do not change time, direction, stage order, ability gates, or AI boundaries without an explicit audit.
- Do not add a framework or topic without a dependency, project, market, or risk justification.
- Do not store private assessment materials in this repository.

## Context loading weights

- W100: inspect `STATUS.md` before plan-wide, execution-state, or next-step decisions.
- W70: read only the normative files relevant to the current task using the routing table below.
- W40: read the matching template and current evidence when creating or evaluating an artifact.
- W10: read `CHANGELOG.md` or `docs/09-governance-loop-log.md` only for history, audit, or version work.
- Do not bulk-read all planning files when a routed subset can answer the request.
- Low-weight files are deferred, not deleted.

## Document routing

| Task | Required sources |
|---|---|
| Goals, constraints, success | `docs/00-project-charter.md`, `docs/10-curriculum-scope.md` |
| Roadmap or progression | `docs/01-roadmap.md`, `docs/02-capability-matrix.md`, `docs/06-learning-architecture.md` |
| Daily/weekly execution | `docs/03-loop-protocol.md`, `docs/11-parallel-execution.md`, `docs/13-efficient-learning-process.md` |
| AI tutoring or assessment | `docs/04-ai-use-policy.md`, `docs/07-quality-and-evidence.md` |
| Governance or change | `docs/05-governance.md`, `docs/14-program-control.md` |
| Risk or recovery | `docs/08-risk-and-recovery.md` |
| Planning style | `docs/12-planning-style.md` |
| Course package | `templates/course-package.md` plus its routed normative sources |
| Evidence decision | `templates/evidence-index.md`, capability matrix, and original artifacts |

## P1 — Change control [70]

- Explain the observed failure path before adding a rule or document.
- Prefer the smallest change that alters a real decision or prevents a plausible failure.
- Reuse an existing source of truth instead of copying the same rule into multiple files.
- Overall version changes must update `README.md`, `STATUS.md`, and `CHANGELOG.md` together.
- Keep `STATUS.md` factual: current state, blockers, next evidence, and no predicted results.
- Stop governance when remaining questions require P0 or course-package execution data.

## P2 — Work protocol [40]

- For review, explanation, diagnosis, or planning: inspect evidence and report; do not mutate unrelated state.
- For an authorized change: plan briefly, edit with `apply_patch`, validate, then summarize outcomes.
- For LOOP governance: record trigger, findings, minimal changes, rejected additions, and stop condition.
- For course design: define outcomes, prerequisites, entry level, AI limit, transfer level, and acceptance evidence.
- For assessment: isolate answers, declare allowed tools, predict before testing, and cite evidence IDs afterward.
- For current OpenAI/Codex behavior, verify official OpenAI documentation before changing guidance.
- Ask only when a missing decision would materially change scope, authority, safety, or evidence validity.

## P2 — Editing and verification [40]

- Use one H1 per Markdown file and relative links for repository documents.
- Keep templates decision-oriented; avoid fields that will not affect a later action.
- Preserve version history and unrelated working-tree changes.
- After Markdown changes, run `git diff --check` and check local links, H1 count, and trailing whitespace.
- After editing this file, run `wc -l AGENTS.md`; the result must be at most 150.
- Before a baseline commit, inspect the staged diff and verify the working-tree outcome afterward.
- Do not push a remote unless the user explicitly requests it.

## P3 — Communication preferences [10]

- Use Chinese by default unless the user requests another language.
- Lead with the conclusion, then the few decisions that matter.
- Prefer short prose and small tables over decorative formatting.
- Link the most useful local files in the final handoff.

## 150-line self-pruning rule

- This file has a hard limit of 150 physical lines, including blank lines.
- If an edit exceeds the limit, repair it in the same change before finalizing.
- Prune in this order: P3 examples, repeated wording, P2 implementation detail, then duplicated P1 context.
- Replace long explanations with links to an existing normative document.
- Do not remove P0 rules or project invariants without explicit user approval.
- Never delete project files because this instruction file is too long.
- Create nested instruction files only for genuinely different directory rules; do not duplicate root guidance.
