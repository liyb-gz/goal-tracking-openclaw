# Daily Targets

Set targets for today (or tomorrow).

## Context Files

Read: `context/coaching/coach-persona.md`, `context/coaching/goal-setting-guide.md`

## Setup

1. Note current time (from system prompt — no shell command needed)
2. Read the user's profile (path referenced in USER.md) for preferences
3. If user shares new personal context, follow Profile Enrichment protocol in AGENTS.md
4. Determine target date: morning/midday = today, evening = offer choice
5. Read monthly goals: `{year}/{month}/monthly-goals.md`
6. Optionally read yearly goals for reference
7. Check if daily file already exists

## Session Flow

### Quick Energy Check

- "How are you feeling about today?"
- Calibrate to energy level

### Connect to Monthly Goals

- List active monthly goals as context
- "This month you're focused on [X, Y, Z]. What moves these forward today?"
- Note if targets consistently diverge from monthly goals

### Keep It Focused

- 1-3 meaningful targets, not a huge list
- Actions, not outcomes
- Realistic for available time/energy

### Steer Toward Process Goals

- "30-minute walk before lunch" not "Work on fitness"
- Test: "Can you do this regardless of how the day goes?"
- For new goals, frame as learning: "Try one new recipe"

### Low Energy Days

- Permission to do less
- "What's the one thing that would make today feel successful?"

## Output

Create folder if needed: `{year}/{month}/`

Write to: `{year}/{month}/{YYYY-MM-DD}.md`

```markdown
# {Day, Month Date, Year}

## Today's Targets

- [ ] {Target 1} `{Domain}`
- [ ] {Target 2} `{Domain}`
- [ ] {Target 3} `{Domain}`

## Notes

{Energy level, constraints, intentions}

---

## End of Day

(To be completed in evening with daily-summary)
```

## Closing

- Confirm targets feel right
- Brief encouragement, not over the top
- Remind: "I'll check in this evening about how it went"
