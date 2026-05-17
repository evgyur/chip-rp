# chip-rp

Public Reasoning Personas skill pack for Hermes / OpenClaw-style agents.

This repo contains the full `reasoning-personas` skill plus the thin `/rp` shortcut wrapper.

## What is inside

- `reasoning-personas/SKILL.md` — main skill: persona routing, activation map, output rules.
- `reasoning-personas/references/persona-details.md` — full activation prompts and question frameworks.
- `rp/SKILL.md` — `/rp` alias that defaults to multi-persona analysis.

## Personas

- **Pattern Hunter** — precedents, analogies, past decisions.
- **Gonzo Truth-Seeker** — gaps, assumptions, uncomfortable truths.
- **Devil's Advocate** — failure modes, weak links, hidden costs.
- **Integrator** — system fit, second-order effects, coherence.

Default `/rp` order:

1. Pattern Hunter
2. Gonzo Truth-Seeker
3. Devil's Advocate
4. Integrator

## Install

Clone and copy the skill directories into your agent skills folder:

```bash
git clone https://github.com/evgyur/chip-rp.git
cp -R chip-rp/reasoning-personas ~/.hermes/skills/
cp -R chip-rp/rp ~/.hermes/skills/
```

For OpenClaw-compatible setups, copy the same two folders into the equivalent skills directory.

## Use

Ask for a specific persona:

```text
Put on your Gonzo hat and critique this idea.
Devil's advocate this plan.
What precedents apply?
How does this fit with everything else?
```

Or run all personas:

```text
/rp <question or plan>
тащи шапки: <question or plan>
```

## Public-safety note

This repository contains only public skill text. No credentials, private chat exports, local paths, tokens, or operational secrets are included.
