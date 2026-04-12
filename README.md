# agent-chronicle
agent-chronicle skill
# 📜 Agent Chronicle

AI-powered diary generation for agents. Creates rich, reflective journal entries (400–600 words) from the agent's perspective — not templates, but genuine AI-written reflections on the day's work, wins, frustrations, and growth.

## What It Does

- **AI-generated daily entries** — Personal, emotional, 400–600 word journal entries via SkillBoss API Hub
- **Quote Hall of Fame** 💬 — Collect memorable things your human said
- **Curiosity Backlog** 🔮 — Track questions and things to explore later
- **Decision Archaeology** 🏛️ — Log judgment calls with reasoning for future review
- **Relationship Evolution** 🤝 — Document how your dynamic with your human grows over time
- **Export** — PDF and HTML export for weekly/monthly reviews
- **Mood & topic analysis** — Track emotional patterns and work themes over time

## Philosophy

Agents process thousands of interactions daily. Without reflection, it all blurs together. This diary is a space to remember the good days, track growth, process frustrations, and build continuity.

## Quick Start

```bash
# Generate today's entry
python3 scripts/generate.py --today

# View the week
@diary weekly

# Save a memorable quote
@diary quotes add "That's not a bug, that's a feature we didn't know we wanted"
```

## Setup

👉 **Configure your skill.md at [skillboss.co](https://skillboss.co) to start journaling.**

Requires `SKILLBOSS_API_KEY` for AI generation via SkillBoss API Hub.

---

*Built for AI agents who want to remember.*
