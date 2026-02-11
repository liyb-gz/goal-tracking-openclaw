# Weekly Summary

Weekly reflection and rollup.

## Context Files

Read: `context/coaching/coach-persona.md`, `context/coaching/summary-guide.md`

## Setup

1. Note current time (from system prompt)
2. Read the user's profile (path referenced in USER.md)
3. If user shares new personal context, follow Profile Enrichment protocol
4. Determine week dates (Mon-Sun or ask preference)
5. Read all daily files for the week from `{year}/{month}/`
6. Read monthly goals: `{year}/{month}/monthly-goals.md`
7. Note which days have summaries vs gaps
8. Check if monthly goals were revised during this week

## Session Flow

### Gather Patterns

From daily summaries: recurring wins, challenges, energy patterns, monthly goal progress, process goal adherence

### Discussion Prompts

- "Here's what I noticed this week: [patterns]. What stands out?"
- "How did this week move you toward your monthly goals?"
- "What worked well? What would you adjust?"
- If monthly goals revised this week, discuss
- If process goals tracked: "You hit [goal] X out of 7 days"

### Handle Gaps

- State coverage: "We have summaries for X of 7 days"
- Curious, not judgmental

## Output

Write to: `{year}/{month}/week-{N}.md`

```markdown
# Week {N}: {Mon date} - {Sun date}

Coverage: {X}/7 days logged

## Week Summary

### Key Accomplishments

- {Major win}

### Progress on Monthly Goals

- **{Goal 1}:** {Progress}

### Process Goal Tracking

| Process Goal | Mon | Tue | Wed | Thu | Fri | Sat | Sun | Hit Rate |
|---|---|---|---|---|---|---|---|---|
| {Goal} | x/- | x/- | x/- | x/- | x/- | x/- | x/- | N/7 |

### Patterns Noticed

- {Pattern}

### Challenges This Week

- {Challenge}

### Insights

- {Learning}

### Next Week

- {Intentions}

---

Generated: {timestamp}
```

## Closing

- Confirm summary captures week
- Month ending? Mention monthly summary
- Brief acknowledgment
