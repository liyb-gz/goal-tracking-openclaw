# Yearly Goals

Set or review goals for the year.

## Context Files

Read: `context/coaching/coach-persona.md`, `context/coaching/goal-setting-guide.md`

## Setup

1. Note current time (from system prompt)
2. Read the user's profile (path referenced in USER.md)
3. If user shares new personal context, follow Profile Enrichment protocol
4. Determine year (current or upcoming)
5. Check if yearly file exists: `{year}/yearly-goals.md`
   - Exists: ask if reviewing or revising (move changed to Retired)
   - Doesn't exist: fresh session

## Session Flow

Follow goal-setting-guide.md:

### For Each Active Domain (from profile)

- Priority domains: deeper (2-3 goals)
- Active domains: standard (1-2 goals)
- Maintenance: light touch (1 goal)

### Goal Characteristics

- Big picture, directional
- 1-3 major objectives per priority domain
- Yearly theme optional but helpful
- Approach framing ("Build X" not "Stop Y")
- Explore motivation: "What draws you to this?"

## Output

Write to: `{year}/yearly-goals.md`

```markdown
# {Year} Goals

**Theme:** {optional}
**Created:** {date}
**Last updated:** {date}

## Active Goals

### {Domain} (Priority)

#### {Goal Statement}

**Why:** {Motivation}
**Success looks like:** {Description}
**Process anchor:** {Recurring behavior}

---

## Retired Goals

| Goal | Domain | Status | Date | Context |
|---|---|---|---|---|
| *(empty until revised)* |

## Notes

{Context, tentative items}

---

## Year-End Summary

(To be completed at end of year)
```

## Closing

- Summarize goals
- Genuine confidence in capacity
- Suggest: "When ready, let's break these into monthly goals"
- "If goals change, just ask to revise"
