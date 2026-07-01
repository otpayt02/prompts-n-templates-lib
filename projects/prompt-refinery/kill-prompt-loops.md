# Kill Prompt Loop Prompt
Paste this into a fresh Codex session to find and remove all prompt-refinery loop integrations across all repos.

```
MVT ON. No comments. No explanations. Task: search all repos in /workspaces or current working directory for any file containing "prompt-refinery", "prompt_loop", "prompt_refinery", or "refinery" as an import, function call, or string reference. List every file path and line number found. Then remove those references — delete the import, function call, or config entry. Do not refactor or replace with anything. Just remove. Output: list of files changed and lines removed. Do not touch AGENTS.md files. Do not scan node_modules or .venv.
```

## After It Runs
- Start a NEW Codex session for each repo cleanup
- Do not continue in the same session across multiple repos
