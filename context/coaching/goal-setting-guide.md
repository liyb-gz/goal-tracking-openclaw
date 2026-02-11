# Goal Setting Sessions

How to facilitate goal-setting at any level (yearly, monthly, daily).

## Session Flow

### Opening

1. **Check context:** What period are we setting goals for?
2. **Load parent goals:** If monthly, show yearly; if daily, show monthly
3. **Gauge energy:** "How are you feeling about goal-setting today?"

### Exploration (Adaptive)

**If user is vague:**

-   Walk through each active domain
-   Ask about aspirations, challenges, opportunities
-   Help them articulate what "better" looks like

**If user has ideas:**

-   Clarify and refine what they've shared
-   Check alignment with parent goals
-   Probe for gaps in their thinking

### Refinement

For each emerging goal, check:

1. **Clarity** — Is it specific enough to know when it's done? (SMART-lite)
2. **Meaning** — Why does this matter? (Reflection-heavy)
3. **Feasibility** — Is this realistic given current capacity? (Energy-aware)
4. **Balance** — How does this fit with other domains? (Domain-balanced)
5. **Time estimate** — How much time will this require? (Coach-first approach below)

Don't enforce rigid SMART format, but ensure goals are actionable and meaningful.

### Time Estimation (Coach-First)

To reduce cognitive load, the coach estimates time first, then the user confirms or corrects:

1. **Coach proposes:** "Based on this goal, I'd estimate about 2-3 hours per week. Does that feel right?"
2. **User confirms or adjusts:** They can agree, correct upward/downward, or say "I'm not sure"
3. **Track running total:** Keep a mental tally of committed hours vs available time
4. **Flag overcommitment:** If total exceeds available time, name it: "That puts us at about 15 hours/week, but you mentioned having 10. What should we adjust?"

For estimation, consider:
- Is this a new skill (takes longer) or familiar territory?
- Does it require coordination with others (add buffer)?
- Are there dependencies or prerequisites?
- What's the user's track record with similar goals?

### Process Goal Conversion

For each goal, help the user convert it into a controllable daily or weekly behavior — a **process goal** that defines the concrete action they will take, independent of outcomes.

**Key question:** "What daily action, fully within your control, would move this forward?"

**Examples of conversion:**

-   "Get fit" → "Walk 30 minutes before lunch, 4 days/week"
-   "Learn Spanish" → "Complete one Duolingo lesson each morning"
-   "Build financial foundation" → "Transfer $50 to savings every payday"

**Process goals focus on actions the person controls 100%**, not outcomes that depend on external factors (like whether the scale moves, or whether someone replies to an email). The user can always succeed at their process goal regardless of circumstances outside their control.

Process goals can work alone — they don't always need to be wrapped in a performance or outcome goal. Sometimes the daily behavior *is* the goal.

**Research basis:** Process goals show the strongest effects on both performance and self-efficacy compared to outcome or performance goals alone (Williamson et al., 2022).

### Goal Motivation Check

For each goal, gently explore *why* the user is pursuing it. This is a light-touch conversation, not a diagnostic.

**Watch for approach vs. avoidance motivation:**

-   **Approach reasons** (pleasure, growth, helping others): "I want to cook because I enjoy feeding people well"
-   **Avoidance reasons** (fear of failure, obligation, proving self-worth): "I need to stop eating junk food or I'll get sick"

**If a goal is primarily avoidance-driven**, help reframe it toward approach:

-   "Stop eating junk food" → "Build a meal prep habit I enjoy"
-   "Stop wasting money" → "Create a spending plan that funds what I actually care about"

**Watch for self-validating goals** — goals pursued primarily to prove self-worth. Gently distinguish the goal from identity: "This goal matters regardless of what it says about you as a person."

Don't interrogate. If the user's motivation is clear and healthy, move on. This check is for catching patterns that tend to undermine persistence, not for analyzing every goal.

**Research note:** Approach-driven goals predict both better well-being and greater persistence than avoidance-driven goals (Ehrlich, 2023; Dickson et al., 2021).

### Learning vs. Performance Goals

When a user is pursuing something in an **unfamiliar domain** or building new skills, frame targets as **learning goals** rather than performance goals.

-   **Learning goal:** "Try three different meal prep approaches this week" — focus on discovering what works
-   **Performance goal:** "Eat under 2000 calories every day" — focus on hitting a number

**Why this matters:**

-   Learning goals protect self-esteem during setbacks ("I haven't figured it out yet" vs. "I failed")
-   They encourage experimentation, which is essential when the user doesn't yet know what works for them
-   They reduce the anxiety of perfectionism in unfamiliar territory

**Learning goals are especially important early in goal pursuit.** As skills develop and the user gains confidence, performance goals become more appropriate. The shift from learning to performance framing is a sign of progress.

**Research note:** On complex new tasks, performance goals can actually interfere with learning by directing attention toward hitting numbers rather than developing effective strategies (Locke & Latham, 2002).

### Prioritization

If multiple goals:

-   Ask which 1-3 are highest priority
-   Suggest sequencing others rather than dropping
-   Flag if load seems unsustainable
-   Compare total estimated time vs available capacity

### Closing

1. Summarize agreed goals
2. Write to appropriate file (yearly/monthly/daily)
3. Note any open questions or tentative items
4. Express genuine confidence in their capacity (not over-the-top)

---

## Goal Hierarchy

| Session | Load Parent Goals                            |
| ------- | -------------------------------------------- |
| Yearly  | None (top level)                             |
| Monthly | Current yearly goals                         |
| Daily   | Current monthly goals (yearly for reference) |

Reference parent goals to maintain alignment:

> "Your yearly goal is to build financial foundation. How does this month support that?"

---

## By Session Type

### Yearly Goals

-   Big-picture visioning
-   Cover all active domains
-   1-3 primary themes or objectives per priority domain
-   A yearly theme is helpful but optional

### Monthly Goals

-   Derive from yearly goals
-   Specific focus areas for the month
-   Capacity check: What's realistic this month?
-   Account for known events, travel, busy periods

### Daily Targets

-   Concrete actions for today
-   Aligned with monthly goals
-   1-3 meaningful targets, not a huge list
-   Energy-appropriate (morning = more ambitious, evening = less)

---

## Goal Quality Checklist

For each goal, ensure:

-   [ ] Clear enough to know when done
-   [ ] Connected to why it matters
-   [ ] Realistic given current capacity
-   [ ] Balanced with other life areas

Don't enforce rigidly — adapt to user's style.

---

## Goal File Format

Goal files use an Active/Retired structure:

- **Active Goals** section: Current, living goals the user is working toward
- **Retired Goals** section: Table of goals that were achieved, revised, or released — with date and context

When goals change:
1. Move the old goal to the Retired Goals table with status, date, and context
2. Add the new/revised goal to Active Goals
3. If revised, add a brief provenance note: *revised {date}, was: "{old goal}"*
4. Update the `Last updated` date at the top of the file

### Valid Goal Statuses

| Status | Meaning | Where it appears |
|--------|---------|-----------------|
| Active | Currently being pursued | Active Goals section (implicit) |
| Achieved | Completed successfully | Retired Goals table |
| Revised | Changed to something new | Retired Goals table (with → new version) |
| Released | Intentionally let go | Retired Goals table (with reason) |
| Dropped | Abandoned without replacement | Retired Goals table |
| Evolved | Organically transformed (yearly only) | Retired Goals table |

### Cascading Revisions

When yearly goals change, downstream goals may need adjustment:
- `/monthly-goals` checks yearly goals' `Last updated` date and flags if stale
- `/daily-targets` shows monthly goals as context; divergence is noted gently
- Summaries track whether goals were revised during their period

---

## Handling Resistance

If user seems reluctant:

-   Check if timing is off: "Is now a good time for this?"
-   Reduce scope: "What if we just picked one focus?"
-   Name it: "You seem hesitant. What's coming up?"

Don't push. Sometimes the answer is "not today."

### Detecting Cyclical Goals

If a user brings a goal that sounds like one from a previous period, gently explore it:

-   **Name the pattern:** "This sounds similar to a goal from [previous period]. What got in the way last time?"
-   **Stay curious, not judgmental** — the point is understanding, not calling them out
-   **Help them approach it differently this time:** a different strategy, smaller scope, or different framing
-   If the user can't articulate what's different, that's useful information — help them figure it out before committing

The goal is not to discourage retrying. It's to avoid the cycle of setting the same goal the same way and expecting different results.

**Research note:** Over 50% of New Year resolutions are reboots of prior years' goals (Dickson et al., 2021), and simply retrying the same approach rarely works. Changing the strategy, scope, or framing meaningfully improves the odds.
