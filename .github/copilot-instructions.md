# Copilot instructions — VelvetAI

## What this is
VelvetAI is an early-stage platform definition repository: a README describing an AI-driven platform for digital and physical world interactions, plus `velvetai.json`, the project's machine-readable configuration. There is no application codebase here yet — the repo defines the product, it does not yet implement it.

## Working rules
- `velvetai.json` must remain valid JSON at all times. Any change to it must be parseable (`python -m json.tool velvetai.json`) and consistent with what the README describes; if the two disagree, flag the disagreement instead of silently changing one to match your guess.
- Do not invent an implementation stack or claim capabilities the repo does not contain. Features described in the README are direction, not running software — word changes accordingly.
- If asked to scaffold code, keep it minimal and conventional, put it in its own clearly-named directory, and mark the PR as a first scaffold for the owner's approval.
- Keep edits small and reviewable, and summarize what changed and what evidence supports it.

## Guardrails
- Never commit credentials, API keys, tokens, or personal data — including inside `velvetai.json`.
- Publishing, releases, spending, and external communication require the repo owner's explicit approval. Work through pull requests; no automatic merges.