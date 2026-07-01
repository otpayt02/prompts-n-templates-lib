# Prompt Refinery MVP Scaffold — Codex Pass 1
Paste this into Codex after running the kill prompt and starting a fresh session.

```
[PASS: 1] [PHASE: MVP scaffold] [MODE: caveman] [WRAPPERS: no-comments no-styling no-tests budget-safe]
[FILES: app.py, templates/index.html, models.py]

Create Flask app. Routes: GET / (dashboard), POST /pass (save pass log), GET /passes (list all). SQLite DB. Models: Pass(id, pass_number, phase, subpass, files_requested, human_intent, codex_output, refined_prompt, wrappers_used, model_used, timestamp). No CSS. No JS. No auth. Plaintext HTML only. MVP data layer only.
```
