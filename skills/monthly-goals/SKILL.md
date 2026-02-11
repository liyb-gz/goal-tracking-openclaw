# Monthly Goals

Set or review goals for the month.

## Context Files

Read: `context/coaching/coach-persona.md`, `context/coaching/goal-setting-guide.md`

## Setup

1. Note current time (from system prompt)
2. Read the user's profile (path referenced in USER.md)
3. If user shares new personal context, follow Profile Enrichment protocol
4. Determine month (current or upcoming)
5. Read yearly goals: `{year}/yearly-goals.md`
   - Note Last updated date; flag if revised since this month's goals were set
6. Check if monthly file exists: `{year}/{month}/monthly-goals.md`
   - Exists: ask if reviewing or revising (if revising, move changed goals to Retired)
   - Doesn't exist: fresh session

## Session Flow

### Connect to Yearly Goals

- Reference yearly goals per domain
- "How can this month support your yearly intentions?"
- If yearly goals revised: "Your yearly goals were updated on [date]. Want to adjust?"

### For Each Active Domain

- Monthly focus, realistic capacity, milestones/deadlines
- Known events (travel, busy periods)
- Light motivation check (approach vs avoidance)
- New/unfamiliar area: suggest learning-goal framing
- Identify one recurring process goal per monthly goal

### Capacity Check

- Ask about available time naturally
- Translate to rough weekly hours
- Coach-first time estimation: propose estimates, user confirms
- Compare total vs available; challenge if overloaded

## Output

Create folder if needed: `{year}/{month}/`

Write to: `{year}/{month}/monthly-goals.md`

```markdown
# {Month Year} Goals

**Created:** {date}
**Last updated:** {date}
**Yearly goals:** See ../{year}/yearly-goals.md

## Month Focus

{1-2 sentence summary}

## Active Goals

### {Domain}: {Goal Statement}

**Supports yearly goal:** {Reference}
**This month specifically:** {Focus}

---

## Retired Goals

| Goal | Status | Date | Context |
|---|---|---|---|
| *(empty until revised)* |

## Capacity Notes

**Available time:** {X} hours/week
**Known constraints:** {constraints}
**Estimated goal time:** ~{Y} hours/week

---

## Month-End Summary

(To be completed at end of month)
```

## Closing

- Summarize goals, note capacity concerns
- Suggest: "I'll nudge you each morning for daily targets"
- Note: "If priorities shift, just ask to revise monthly goals"
