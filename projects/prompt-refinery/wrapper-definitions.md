# Wrapper Definitions
Toggle these per pass in Prompt Refinery.

| Wrapper | Effect on prompt |
|---|---|
| `caveman` | Strips all filler, terse only |
| `explained` | Adds brief architecture note before the command |
| `budget-safe` | Forces single-file scope, no repo scan |
| `no-comments` | Explicit ban on code comments |
| `no-styling` | Explicit ban on CSS/UI polish |
| `no-tests` | No test file generation |
| `explain-arch` | Perplexity explains WHY before Codex builds |
| `minimal-context` | Lists only the 1-3 files Codex actually needs |

## Model Routing
| Task | Model |
|---|---|
| Next prompt suggestion | ChatGPT 5.4 (in Perplexity) |
| Critique of suggestion | Kimi K2 or Claude Sonnet |
| Architecture explanation | Gemini 3.1 Pro or Nemotron 3 Super |
| Quick edits / Q&A | Any cheap model |
