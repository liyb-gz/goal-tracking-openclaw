# Goal Tracking Workspace for OpenClaw

An agentic workspace for goal setting and reflection, powered by an AI life coach named **Sage**. Guides you through hierarchical goal planning (Yearly > Monthly > Daily) and structured reflections grounded in goal-setting research.

## Platform

**OpenClaw** (formerly Clawdbot) — a personal AI agent that runs on your devices and connects via WhatsApp, Telegram, Discord, and other messaging channels.

### Why OpenClaw Instead of an IDE?

The IDE-based version (OpenCode/Cursor) only works when you have the editor open. That's fine for developers mid-session, but a life coach should be able to reach *you* — not wait for you to reach it.

OpenClaw enables **proactive coaching**: the agent can message you at the right times (morning targets, evening reflections, weekly check-ins) through whatever channel you already use. You don't need to open anything — Sage comes to you.

## Getting Started

1. **Copy the workspace** to the default location:
   ```bash
   cp -r goal-tracking-openclaw/ ~/.openclaw/workspace/
   ```
   Or configure a custom path via `agents.defaults.workspace` in your OpenClaw config.

2. **Run setup** if this is your first time:
   ```bash
   openclaw setup
   ```

3. **Start a conversation** and say:
   > "I'd like to get started" or "onboard me"

   This runs the onboarding skill, which creates your profile, sets your preferred language, and walks you through your first goals.

4. **Optional: Set up proactive reminders** via cron jobs. See [SETUP-CRON.md](SETUP-CRON.md) for details.

## How It Works

Every session, the agent loads three core files:

| File | Purpose |
|------|---------|
| `SOUL.md` | Coach persona — tone, values, boundaries |
| `AGENTS.md` | Operating instructions — workflows, rules, error handling |
| `USER.md` | Your profile — created during onboarding, updated over time |

**Skills** are loaded on demand for specific sessions (goal-setting, summaries, etc.) rather than bloating every conversation with instructions that aren't needed.

**Heartbeat** checks run periodically and suggest appropriate actions based on the time of day — morning target-setting, evening reflections, weekly rollups.

**Cron jobs** can send proactive reminders through your preferred messaging channel. Configure these once and Sage will nudge you at the right times.

## Available Skills

| Skill | Purpose |
|-------|---------|
| `onboard` | Initial setup — profile creation, preferences, first goals |
| `yearly-goals` | Set or review yearly goals |
| `monthly-goals` | Set or review monthly goals |
| `daily-targets` | Set targets for today or tomorrow |
| `daily-summary` | Quick end-of-day reflection |
| `weekly-summary` | Weekly reflection and rollup |
| `monthly-summary` | End-of-month reflection |
| `yearly-summary` | Deep end-of-year reflection |
| `end-of-day` | Combined daily summary + tomorrow's targets |

## Proactive Coaching

Sage doesn't wait for you to check in. Two mechanisms enable this:

- **Heartbeat** — When a session starts, the agent checks the current time and your recent activity to suggest the most useful action. Morning? Set targets. Evening? Reflect. Monday? Weekly rollup.
- **Cron** — Scheduled jobs send messages through your connected channel at times you choose. A morning nudge, an evening prompt, a weekly reminder — whatever rhythm works for you.

See [SETUP-CRON.md](SETUP-CRON.md) for configuration instructions.

## Coaching Methodology

| Principle | What It Means |
|-----------|---------------|
| **Process-goal focused** | Steers toward controllable daily behaviors, not just outcomes |
| **Domain-balanced** | Tracks goals across all life domains, not just work |
| **Energy-aware** | Considers energy levels and capacity, not just ambition |
| **Motivation-aware** | Explores *why* behind goals — approach reasons over avoidance reasons |
| **Reflection-heavy** | Regular summaries and check-ins are the mechanism, not optional extras |
| **Flexibility-first** | Revising goals is self-awareness, not failure |
| **SMART-lite** | Specific and measurable where helpful, without bureaucratic rigidity |

## Research Foundation

The coaching approach is grounded in goal-setting research from four key sources (Williamson 2022, Locke & Latham 2002, Ehrlich 2023, Dickson 2021). Key findings:

- **Process goals outperform outcome goals** for both performance and self-efficacy
- **Feedback loops are essential** — goals without check-ins don't work
- **Learning goals beat performance goals** when building new skills on complex tasks
- **Approach motivation** (growth, pleasure, helping others) predicts well-being; avoidance motivation (fear, obligation) predicts unhappiness
- **Short-term behavioral goals** are what make long-term goals actionable
- **Goal flexibility** — knowing when to revise — is a strength, not a weakness

Full details in `context/coaching/research-notes.md`.

## Life Domains

Goals are organized across domains to encourage balance:

- Health & Fitness
- Career & Professional Growth
- Financial
- Relationships & Social
- Personal Development & Learning
- Creative & Passion Projects
- Mental Health & Mindfulness
- Home & Environment
- Fun & Recreation
- Community & Contribution

## File Structure

```
~/.openclaw/workspace/          (or custom path)
├── AGENTS.md                   # Operating instructions
├── SOUL.md                     # Coach persona
├── USER.md                     # Your profile (created during onboard)
├── IDENTITY.md                 # Agent identity (auto-created)
├── TOOLS.md                    # Workspace conventions
├── HEARTBEAT.md                # Periodic coaching checks
├── SETUP-CRON.md               # Guide for proactive reminders
├── context/
│   ├── coaching/               # Behavior guides
│   │   ├── coach-persona.md
│   │   ├── goal-setting-guide.md
│   │   ├── summary-guide.md
│   │   └── research-notes.md
│   └── core/                   # Option menus
│       ├── coaching-styles.md
│       ├── data-sources.md
│       └── life-domains.md
├── skills/                     # On-demand skills
│   ├── onboard/
│   ├── daily-targets/
│   ├── daily-summary/
│   ├── end-of-day/
│   ├── weekly-summary/
│   ├── monthly-goals/
│   ├── monthly-summary/
│   ├── yearly-goals/
│   └── yearly-summary/
├── memory/                     # Daily memory logs
└── 2026/                       # Goal & summary files
    ├── yearly-goals.md
    └── 02/
        ├── monthly-goals.md
        ├── week-01.md
        └── 2026-02-15.md
```

## Customization

### Data Source Integrations

During onboarding, you can connect external data sources that inform your coaching sessions — calendar events, health metrics, habit trackers, and more. These are configured in your profile and referenced by skills that benefit from the context.

### Coaching Style

The default coaching style is warm, direct, and research-grounded. You can adjust this during onboarding or at any time by updating your profile. Options range from gentle and supportive to blunt and challenging. See `context/core/coaching-styles.md` for available styles.

## Language Support

Your preferred language is set during onboarding. Sage will conduct all sessions in that language. Change it anytime by saying "switch to [language]" or updating your profile directly.

## Philosophy

1. **Goals are living documents** — They evolve as you do. Revision is growth, not failure.
2. **Process over outcomes** — Daily behaviors are what you control. Results follow.
3. **Reflection is the mechanism** — Without regular check-ins, goals are just wishes.
4. **Balance across domains** — Life is more than work. Track what matters across all of it.
5. **No guilt, only data** — Missed days are information, not moral failings.
6. **Proactive over reactive** — The best coach reaches out before you drift.
7. **Self-discovery over dependency** — Sage helps you build your own clarity, not rely on an AI.
8. **Research-grounded, not dogmatic** — Every practice is backed by evidence but adapted to you.

## Migration from OpenCode/Cursor

This workspace was migrated from the [OpenCode/Cursor goal-tracking workspace](https://github.com/felixflores/goal-tracking-workspace). The core coaching methodology, persona, and research foundation are identical. The key differences are:

- **Proactive messaging** via heartbeat and cron (not available in IDE-based versions)
- **Skills** replace slash commands (same content, different loading mechanism)
- **Memory logs** for cross-session continuity
- **Channel-agnostic** — works through WhatsApp, Telegram, Discord, etc.

If you're coming from the IDE version, your existing goal files (yearly, monthly, daily) can be copied directly into the `2026/` directory structure.

## License

MIT
