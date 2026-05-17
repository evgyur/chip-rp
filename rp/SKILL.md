---
name: rp
description: "Shortcut alias for reasoning-personas. Use when user types /rp to run persona-based analysis."
---

# /rp — Reasoning Personas Shortcut

This skill is a thin alias for `reasoning-personas`.

## When to use
- User types `/rp`
- User asks for persona analysis / "тащи шапки"
- Need structured multi-angle reasoning

## Behavior
1. Load and follow the installed `reasoning-personas` skill.
2. Default mode for `/rp`: run Multi-Persona Analysis in order:
   - Pattern Hunter
   - Gonzo Truth-Seeker
   - Devil's Advocate
   - Integrator
3. Keep output concise and actionable unless user asks for long form.
4. Do not use `/rp` for simple deterministic tasks (e.g. adding a meme caption, sending a file, checking one count) unless Chip explicitly asks. Persona output adds text-context; use it for decisions, risks, architecture, plans, and tradeoffs.

## Output format (default)
- [Pattern Hunter]
- [Gonzo Truth-Seeker]
- [Devil's Advocate]
- [Integrator]
- Final recommendation (1-3 bullets)
