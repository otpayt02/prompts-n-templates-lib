# Prompt Refinery Loop — One Pass Cycle

## Workflow Sequence
```
1. Codex finishes a task -> you copy its output
2. Paste output into Prompt Refinery Pass Log
3. Prompt Refinery shows: files Codex touched, what changed
4. ChatGPT 5.4 (in Perplexity) asked: what should next Codex prompt be?
5. Kimi K2 / Claude Sonnet critiques that suggestion
6. You answer any questions ChatGPT asks (popup delimiter prompts)
7. Prompt Refinery assembles final prompt with your wrapper selections
8. YOU manually copy-paste that prompt into a fresh Codex session
9. Repeat
```

## Rules
- Prompt Refinery NEVER connects to Codex via API
- Codex NEVER suggests its own next prompt
- All model interaction is manual copy-paste
- One Codex session = one atomic task
- Close Codex session immediately after task completes
- Never link entire GitHub repo to Codex — only list specific files requested

## Phase Structure
```
Project
  └── MVP Planning (done entirely in Prompt Refinery + Perplexity)
      └── Phase 1..N (feature implementation)
          └── Pass 1..N (atomic Codex sessions)
              └── Subpass 1..N (model review cycles before Codex runs)
```
