# AGENTS.md — prompt-refinery
MVT ACTIVE. Execute only. No comments. No styling. No tests unless asked.

## Project Identity
Standalone Flask app. Manages prompt pass/subpass workflow. No API connection to Codex ever.
Zero agentic loops. Zero repo scanning. Zero background tasks.

## Stack
Python, Flask, SQLite, Vanilla HTML/JS

## Session Protocol
One task per session. One file per task if possible.
HANDOFF: {file} | {status} | {blocker}

## Context Exclusions
/tests /docs /logs /assets node_modules __pycache__ .venv *.mp3 *.wav *.md (except this)

## HARD RULE
This app does NOT connect to Codex, GitHub API, or any external model API.
All model interaction is manual copy-paste by the user.
