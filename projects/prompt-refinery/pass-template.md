# Pass Wrapper Template
Use this header at the top of every prompt sent to Codex via Prompt Refinery.

```
[PASS: {pass_number}] [PHASE: {phase_name}] [MODE: caveman|explained|budget]
[WRAPPERS: no-comments | no-styling | no-tests | explain-arch | budget-safe]
[FILES: {only the files Codex said it needs}]
[REPO-LINK: https://github.com/otpayt02/{repo}]
[HUMAN-INTENT: {your raw idea in plain English — filled in by popup}]
[REFINED-BY: chatgpt-5.4 | reviewed-by: kimi-k2 | critiqued-by: claude-sonnet]
[SUBPASS: {subpass_number} of {total_subpasses}]

PROMPT:
{the actual caveman-speak Codex instruction}
```
