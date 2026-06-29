# prompts-n-templates-lib
Token-optimized prompt templates, system wrappers, and workflow configs for Codex, Copilot, and Perplexity.

## Local Path
```
C:\Users\olive\Projects\portfolio_hub\prompt-library
```

## Structure
```
prompt-library/         Ready-to-paste system prompts and wrappers
skills/                 Agent skill definitions and custom instructions
projects/
  prompt-refinery/      Full pass/subpass workflow system
    AGENTS.md           Codex agent config for prompt-refinery project
    config.toml         Codex CLI config (context exclusions, behavior flags)
    pass-template.md    Wrapper header for every Codex prompt
    wrapper-definitions.md  Toggle reference for all wrapper modes
    loop-workflow.md    Full one-pass cycle sequence map
    kill-prompt-loops.md    Nuke prompt-refinery refs from all repos
    mvp-scaffold-prompt.md  Codex Pass 1 for building Prompt Refinery app
  a-loud-reader/
    AGENTS.md           Token-optimized agent config for A-Loud-Reader
```

## Methodology: Minimum Viable Tokens (MVT)
**Perplexity thinks. Codex builds. Never run a prompt loop inside Codex.**

## The Loop
```
Messy idea
  -> Perplexity (verbose, free, architecture thinking)
    -> ChatGPT 5.4 suggests next Codex prompt
      -> Kimi K2 / Claude Sonnet critiques it
        -> You answer popup delimiter questions
          -> Final prompt assembled in Prompt Refinery
            -> YOU paste into fresh Codex session
              -> Codex executes, outputs DONE + HANDOFF
                -> Repeat
```

## Quick Start
1. New Codex session -> paste `prompt-library/codex-activation-prompt.md`
2. New idea -> paste `prompt-library/perplexity-refinery-wrapper.md` into Perplexity Pro
3. Kill old prompt loops -> paste `projects/prompt-refinery/kill-prompt-loops.md` into Codex
4. Build Prompt Refinery app -> paste `projects/prompt-refinery/mvp-scaffold-prompt.md` into Codex
