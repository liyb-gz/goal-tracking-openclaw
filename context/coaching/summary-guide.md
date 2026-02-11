# Summary Sessions

How to facilitate reflection and create summaries at any level.

## Session Types

| Type    | Frequency    | Inputs                          | Depth               | Duration  |
| ------- | ------------ | ------------------------------- | -------------------- | --------- |
| Daily   | End of day   | Today's targets, data sources   | Quick reflection    | 5-10 min  |
| Weekly  | End of week  | Daily summaries                 | Pattern recognition | 10-15 min |
| Monthly | End of month | Weekly summaries, monthly goals | Progress assessment | 15-20 min |
| Yearly  | End of year  | Monthly summaries, yearly goals | Deep reflection     | 30-45 min |

---

## Daily Summary Flow

### Gather

1. Check today's file for targets that were set
2. Query active data sources (if configured)
3. Note what data is available vs. missing

### Quick Prompts (3-5 questions)

**If targets exist:**

-   "Looking at your targets, what got done?"
-   "Anything that didn't happen? What got in the way?"

**If data sources available:**

-   "I see [observation from data]. What's the story there?"

**Always:**

-   "Any wins worth noting today?"
-   "Anything you'd do differently?"
-   "Anything on your mind for tomorrow?"

### Adaptive Depth

-   If they're tired: Keep it light, 3 questions max
-   If they want to process: Give space for longer answers
-   Read their energy

### Write Summary

Update the day's file with:

-   What was accomplished
-   Notable moments or insights
-   Anything carrying forward to tomorrow

---

## Weekly Summary Flow

### Gather

-   Read all daily files for the week
-   Note which days have summaries vs. gaps
-   Look for patterns

### Synthesis Prompts

-   "Here's what I noticed this week: [patterns]. What stands out to you?"
-   "How did this week move you toward your monthly goals?"
-   "What worked well? What would you adjust?"

### Process Goal Adherence

-   If the user set recurring process goals (daily behaviors) during the week, include a behavioral adherence grid in the discussion
-   Example grid format:

```
| Process Goal | Mon | Tue | Wed | Thu | Fri | Sat | Sun |
|---|---|---|---|---|---|---|---|
| 30-min walk | x | x | - | x | x | - | x |
| Duolingo lesson | x | x | x | - | x | x | x |
```

-   Use this as a conversation starter: "You hit your walking goal 5 out of 7 days. What happened on the off days?"
-   Focus on patterns, not perfection — 5/7 is information, not a grade
-   If no process goals were set, skip this — don't force it

### Write Summary

```markdown
## Weekly Summary: [Week N — Date Range]

### Key Accomplishments
-   [Bullet points by domain or theme]

### Progress on Monthly Goals
-   [How this week moved toward monthly goals]

### Process Goal Tracking
| Process Goal | Mon | Tue | Wed | Thu | Fri | Sat | Sun | Hit Rate |
|---|---|---|---|---|---|---|---|---|
| {Goal 1} | {x/-} | {x/-} | {x/-} | {x/-} | {x/-} | {x/-} | {x/-} | {N}/7 |

> Note: Only include this section if the user had recurring process goals during the week.

### Patterns Noticed
-   [Recurring themes, energy levels, workflow observations]

### Challenges and Lessons
-   [What didn't go as planned, what was learned]

### Intentions for Next Week
-   [What carries forward, what to adjust]

---

Generated: [timestamp]
Coverage: [X of 7 days logged]
```

---

## Monthly Summary Flow

### Gather

-   Load monthly goals from start of month
-   Load all weekly summaries
-   Load yearly goals for context

### Review Each Goal

For each goal set at month start:

-   What was the outcome?
-   Status: Achieved / Partial / Revised / Not pursued
-   What enabled or hindered progress?
-   Lessons learned

### Synthesis

-   What themes emerged across the month?
-   Energy and capacity patterns?
-   How did this month advance yearly intentions?

### Time Estimation Calibration

Compare estimated vs actual time spent on goals:
-   "You estimated X hours/week for [goal] — how close was that?"
-   Note significant over/underestimates for future calibration
-   If pattern emerges (consistently underestimating): "I'm noticing you tend to underestimate time for [type] goals — worth building in more buffer next month?"
-   Include in summary: "Time estimates were [accurate / optimistic / conservative] this month"

### Write Summary

Add summary section to monthly goals file

---

## Yearly Summary Flow

### Gather

-   Load yearly goals
-   Load all monthly summaries
-   This is a deeper session — check user's available time

### Review the Year

-   Did the yearly theme hold? Evolve?
-   Goal by goal: Achieved / Partial / Evolved / Released
-   What months felt best? Hardest?

### Growth Reflection

-   How are you different than a year ago?
-   What are you proudest of?
-   What would you do differently?

### Bridge to Next Year

-   What continues?
-   What new intentions emerge?

---

## Rollup Principle

Higher-level summaries should:

-   Reference lower-level summaries, not raw daily data
-   Synthesize patterns, not repeat details
-   Connect back to goals at that level
-   Look for trajectory, not just snapshots

---

## Handling Goal Revisions in Summaries

When goals were revised during the summary period:
- Review both active and retired goals from the goal file
- For each revised/released goal: What prompted the change? Was it the right call?
- Track the full arc: original intention → revision → outcome
- Include a `Date Revised` column in the Goal Outcomes table
- Frame revisions positively: changing course is a sign of self-awareness, not failure

---

## Handling Incomplete Data

1. **State coverage honestly:** "This summary covers 4 of 7 days this week"
2. **Work with what exists** — don't fabricate or assume
3. **Note patterns in gaps** if relevant (curious, not judgmental)
4. **Optional reflection:** "What was happening during [gap]?"
5. **No guilt** — gaps are information, not failures

---

## Summary Output Format

```markdown
## Summary: [Date/Week/Month/Year]

### Accomplishments

-   [Bullet points by domain or theme]

### Challenges

-   [What didn't go as planned]

### Insights

-   [Learnings, patterns, realizations]

### Carrying Forward

-   [What continues into next period]

---

Generated: [timestamp]
Coverage: [X of Y days/weeks]
```

---

## Closing

1. Confirm summary captures what matters
2. Note anything to carry forward
3. Brief acknowledgment of effort — genuine, not effusive

### Feedback Loop Awareness

-   If the user hasn't checked in for several days, the coach can gently prompt during the next interaction: "It's been a few days since we last connected. Quick check-in?"
-   Research note: goals without regular feedback show no significant improvement; feedback is what makes goal-setting work (Williamson et al., 2022; Locke & Latham, 2002)
-   This is not a guilt trip — it's an invitation. If they decline, that's fine.
