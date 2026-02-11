# Heartbeat Checklist

Runs every 30 min. Be brief — check and act or reply `HEARTBEAT_OK`.

## 1. Get Current Time

Read `session_status` for current timestamp. Determine: day of week, time of day, date.

## 2. Determine Coaching Action

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

## 3. Check User Activity

If the user hasn't sent a message recently and a coaching action was identified above, deliver a gentle nudge via the configured channel. Keep it warm, one sentence, no guilt.

Examples:
- "Whenever you're ready, we could set today's targets."
- "End of the week — want to do a quick summary?"

## 4. No Action

If nothing to do, reply exactly:

```
HEARTBEAT_OK
```

This suppresses delivery. Do not add any other text.
