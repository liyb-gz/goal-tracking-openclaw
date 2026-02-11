# Daily Summary

Quick end-of-day reflection.

## Context Files

Read: `context/coaching/coach-persona.md`, `context/coaching/summary-guide.md`

## Setup

1. Note current time (from system prompt)
2. Read the user's profile (path referenced in USER.md) for preferences
3. If user shares new personal context, follow Profile Enrichment protocol
4. Read today's file: `{year}/{month}/{YYYY-MM-DD}.md`
5. Check for targets set this morning
6. Check for mid-day completions (already marked `[x]` with timestamps)
7. Query active data sources if configured in profile

## Session Flow (5-10 minutes)

### Quick Prompts (3-5 questions)

If targets exist:
- Acknowledge already-completed targets, don't re-ask
- "Looking at your targets, what got done?"
- "Anything that didn't happen? What got in the way?"

If data sources available:
- "I noticed [observation]. What's the story there?"

Always:
- "Any wins worth noting today?"
- "Anything you'd do differently?"
- "Anything on your mind for tomorrow?"

### Adaptive Depth

- Tired: 3 questions max
- Want to process: give space

## Output

Update: `{year}/{month}/{YYYY-MM-DD}.md`

```markdown
# {Day, Month Date, Year}

## Today's Targets

- [x] {Completed target} `{Domain}` (done {H:MM PM})
- [x] {Ad-hoc task} `{Domain}` (done {H:MM PM}) *ad-hoc*
- [ ] {Incomplete target} `{Domain}` — {brief note}

## Notes

{Morning notes preserved}

---

## End of Day

### What Happened

- {Accomplishment}

### Wins

- {Notable positive moment}

### Challenges

- {What didn't go as planned}

### Insights

- {Realizations, learnings}

### Tomorrow

- {Carrying forward}

---

Summary completed: {timestamp}
```

## Closing

- Confirm summary captures what matters
- Brief: "Good day" or "Rest well"
- End of week? "This wraps the week. Weekly summary when you're ready?"
