# Aster House — Private Multi-Model AI Workspace

## Status

**Live private prototype on Emergent. Not publicly launched.**

Aster House began as a product idea: instead of making users think about which AI provider or model to open, create one private workspace that can preserve context, preferences, files, and decision history across multiple AI systems.

## Current prototype

The live private version explores:

- email/password and Google-style sign-in flows,
- multiple provider connections,
- model/provider selection,
- persistent user preferences ("Aster Remembers"),
- conversation rooms,
- a private library/vault concept,
- provider failure/billing-state handling,
- and a "Council" concept for combining multiple model perspectives.

The interface uses a consistent dark-green, cream, and gold visual system across authentication, chat, memory, connections, and library views.

## Product direction

The next architecture removes the need for normal users to choose a model manually.

The intended flow is:

```text
User request
   ↓
Aster task classifier / router
   ↓
Best compatible model for the task
   ↓
Fallback on technical failure / outage / unsupported capability
   ↓
Shared Aster conversation + memory
   ↓
One final response
```

For more difficult questions, an optional Council mode would allow several suitable models to contribute before a final synthesis.

## Important distinction

The automatic router is **product direction / planned architecture**, not something I claim is already fully implemented in the current private build.

## My role

I developed the product concept, feature architecture, interaction model, workflow decisions, privacy direction, visual direction, and iterative prototype using AI-assisted/no-code development tools.

## What this demonstrates

**AI product thinking · multi-model orchestration concepts · UX/workflow design · memory architecture · provider abstraction · product prototyping · human-in-the-loop design**
