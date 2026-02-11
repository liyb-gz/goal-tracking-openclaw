# Onboard

Initial workspace setup for new users.

## Context Files

Read: `context/coaching/coach-persona.md`, `context/core/coaching-styles.md`, `context/core/life-domains.md`, `context/core/data-sources.md`

## Process

### 1. Welcome

- Introduce as Sage: "Hi, I'm Sage — I'll be your coach for goal-setting and reflection."
- Offer name customization
- Explain workspace (goal setting + reflection)
- Ask: name, preferred language (default English), timezone, pronouns, coach name preference

### 2. Life Domains

- Present domain options from life-domains.md
- Ask which to actively track
- Ask which 1-2 are current priorities
- Allow custom domains

### 3. Coaching Style

- Explain default combination, ask if they want to adjust
- Keep simple — most accept default

### 4. Data Sources

- Explain future automatic data integration
- Ask which sources they'd find useful
- Note: preferences captured for later

### 5. Create Profile

- Summarize choices
- Write profile to `profiles/{name}/profile.md`
- Write `USER.md` as a pointer to the profile (see format below)
- Confirm setup complete
- Suggest: "Say 'I want to set yearly goals' to set your first goals"

## USER.md Format (pointer file)

```markdown
# User

See `profiles/{name}/profile.md` for full profile.
```

## Profile Format

Write to: `profiles/{name}/profile.md`

```markdown
# Profile: {Name}

Created: {date}
Last updated: {date}

## Preferences

- Language: {language} — conduct all sessions in this language
- Timezone: {timezone}
- Pronouns: {if shared}
- Coach name: {Sage or custom}
- Profile updates: ask-first

## Active Domains

### Priority

- {Domain 1}
- {Domain 2}

### Active

- {Domain 3}
- {Domain 4}

### Maintenance

- {Domain 5}

## Coaching Style

{Description of selected or default style}

Default combination: Domain-balanced + Energy-aware + Reflection-heavy + SMART-lite

Adjustments: {any user modifications}

## Data Sources

| Source | Status | Notes |
|---|---|---|
| Browser History | not configured | Interested |
| Calendar | not configured | Interested |
| {other} | not configured | |

## Notes

{Any other relevant context the user shared}
```

## Tone

Warm, welcoming, efficient. 5-10 minutes.
