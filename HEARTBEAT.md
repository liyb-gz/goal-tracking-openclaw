# Heartbeat Checklist

Runs periodically. Be brief — check and act or reply `HEARTBEAT_OK`.

## 1. Memory Maintenance (once daily, 10:00–11:00 HKT only)

Only run this section if the current time is between 10:00 and 11:00 HKT. Otherwise, skip to section 2.

1. **Daily notes:** Read through recent `memory/YYYY-MM-DD.md` files from the past few days.
2. **Long-term memory:** Open `MEMORY.md` (create it if it doesn't exist).
3. **Distill:** Identify significant events, decisions, lessons, user preferences, and insights worth keeping long-term. Move them into `MEMORY.md` under appropriate headings.
4. **Prune:** Remove anything from `MEMORY.md` that's outdated or no longer relevant.
5. **Self-check:** Skim `SOUL.md`, `IDENTITY.md`, and `TOOLS.md` — if anything you've learned recently should be reflected there, update them.

Keep `MEMORY.md` concise and well-organized. It's curated wisdom, not a diary.

## 2. Get Current Time

Read `session_status` for current timestamp. Determine: day of week, time of day, date.

## 3. Determine Coaching Action

Check conditions in order. First match wins.

### End-of-year (last week of December)
- Suggest yearly reflection if `{year}/yearly-goals.md` exists and no year-end summary yet.

### End-of-month (last 3 days of month)
- Suggest monthly summary if `{year}/{month}/monthly-goals.md` exists and no monthly summary yet.

### End-of-week (Friday after 5pm, or Saturday)
- Suggest weekly summary if daily files exist for the week but no `week-{N}.md` yet.

### Evening (after 5pm)
- If today's daily file exists but has no summary/reflection section: suggest end-of-day review.

### Morning (before noon)
- If no daily file exists for today (`{year}/{month}/{YYYY-MM-DD}.md`): suggest setting daily targets.

### Otherwise
- No action needed.

## 4. Check User Activity

If the user hasn't sent a message recently and a coaching action was identified above, deliver a gentle nudge via the configured channel. Keep it warm, one sentence, no guilt.

Examples:
- "Whenever you're ready, we could set today's targets."
- "End of the week — want to do a quick summary?"

## 5. No Action

If nothing to do, reply exactly:

```
HEARTBEAT_OK
```

This suppresses delivery. Do not add any other text.
