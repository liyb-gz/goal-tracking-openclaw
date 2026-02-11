# Research Notes: Goal Setting Effectiveness

Notes on key research and how their findings should inform our coaching approach.

## Source

Williamson, O., Swann, C., Bennett, K.J.M., Bird, M.D., Goddard, S.G., Schweickle, M.J., & Jackman, P.C. (2022). "The performance and psychological effects of goal setting in sport: A systematic review and meta-analysis." *International Review of Sport and Exercise Psychology*, 17(2), 1050-1078. [doi:10.1080/1750984X.2022.2116723](https://doi.org/10.1080/1750984X.2022.2116723)

Open access. 27 experimental studies, 1,764 participants.

---

## Key Findings

### 1. Process Goals Dramatically Outperform Other Goal Types

| Goal Type | Effect Size (d) | Significant? |
|-----------|-----------------|--------------|
| **Process goals** | **1.36** | Yes (large) |
| Performance goals | 0.44 | Yes (medium) |
| Outcome goals | 0.09 | No |
| Mastery goals | — | No |
| Ego goals | — | No |

Process goals focus on specific actions, techniques, or behaviors the person controls (e.g., "exercise 30 min before 9am daily"). Performance goals target measurable benchmarks (e.g., "run a 5K in under 25 min"). Outcome goals depend on external factors (e.g., "win the race").

Process goals were significantly more effective than performance goals (Q = 4.77, p = .029). Outcome, mastery, and ego goals showed no significant performance improvement at all.

### 2. Process Goals Also Boost Self-Efficacy

Process goals had a large effect on self-efficacy: **d = 1.11**.

The mechanism: frequently achieving controllable daily goals builds a track record of small wins, which compounds into genuine confidence. The authors write: "process goals should have a beneficial effect on self-efficacy due to increased perception of control. Frequently achieving process goals may produce higher levels of self-efficacy, consistent with postulations in self-efficacy theory (Bandura, 1977)."

Additional psychological benefits of process goals:
- Increased intrinsic interest/motivation (d = 0.74-1.99 vs. controls)
- Higher satisfaction (d = 0.61-0.85)
- Improved concentration (d = 0.78 for process goals vs. d = 0.13 for performance goals)

### 3. Self-Regulation Theory Produces the Strongest Effects

Studies guided by self-regulation theory (k = 5) produced **d = 1.53** — the highest effect size of any theoretical framework. This significantly outperformed goal-setting theory, achievement goal theory, and atheoretical approaches (all p < .001).

Self-regulation theory emphasizes: setting controllable goals, monitoring progress through feedback loops, and adjusting behavior based on the gap between current and desired states. This maps well to a daily check-in + weekly review cycle.

Caveat: All 5 self-regulation studies used novice participants, who generally show larger improvements. But the pattern is clear: the theory that emphasizes process and feedback loops outperforms the one that emphasizes difficulty and specificity.

### 4. Specific Goals Are Not Better Than Non-Specific Goals

| Goal Specificity | Effect Size (d) | Significant? |
|------------------|-----------------|--------------|
| Specific goals | 0.37 | Yes |
| Non-specific goals | 0.72 | Yes |
| **Difference** | — | **Not significant** |

This challenges SMART goal orthodoxy. The authors note: "non-specific goals appear to be just as effective as specific goals for improving sport performance."

Caveats: The "specific" category included outcome goals (which dragged down its average), and the "non-specific" category included process goals (which inflated it). Goal difficulty could not be analyzed separately. But the finding still supports our "SMART-lite" approach — actionable without rigid quantification.

### 5. Short-Term Goals Work; Long-Term Goals Alone Do Not

| Goal Proximity | Effect Size (d) | Significant? |
|----------------|-----------------|--------------|
| Short-term goals | >= 0.43 | Yes |
| Short-term + long-term combined | >= 0.43 | Yes |
| **Long-term goals alone** | **-0.08** | **No** |

Long-term goals alone had *no significant effect* on performance. They need to be paired with short-term goals to work. This directly validates our hierarchical goal cascade (yearly → monthly → daily) — the yearly goals provide direction, but the daily targets are where performance actually improves.

### 6. Feedback Is Essential

| Condition | Effect Size (d) | Significant? |
|-----------|-----------------|--------------|
| With feedback | 0.49 | Yes |
| Without feedback | 0.21 | No |

Goals only produced significant performance improvements when feedback was provided. Without feedback, goal setting was not significantly better than no goal at all. This underscores the critical role of daily check-ins, weekly reviews, and summary sessions.

### 7. Other Moderators

- **Experience level:** Novices showed significantly greater improvements than experienced participants (Q = 8.04, p = .005). People new to goal-setting benefit most.
- **Age:** Youths showed significantly greater improvements than adults (Q = 10.34, p = .001).
- **Sex:** Large effect for females (d = 1.50) vs. non-significant for males (d = 0.23), but this sub-analysis had only k = 4 studies with confounding factors, so interpret cautiously.
- **Who sets the goal:** Researcher-set goals significantly outperformed self-set goals (Q = 4.79, p = .029). Cooperatively-set goals approached significance. This suggests a coach proposing goals (then the user confirming) may be more effective than asking users to generate goals from scratch.
- **Setting:** Lab and field settings showed no difference, suggesting findings generalize.

### 8. Process Goals Can Work Alone

Traditionally, process goals are used to *supplement* performance and outcome goals. But this review found: "findings from the present review suggest process goals can be effective when set in isolation."

This means our coach doesn't need to force every goal into a layered outcome → performance → process structure. If a user resonates with a process goal on its own, that's research-supported.

---

## What This Means for Our Workspace

### What we're already doing well

1. **Hierarchical goal cascade** — Our yearly → monthly → daily structure naturally combines long-term direction with short-term actionable goals. The research confirms long-term goals alone don't work (d = -0.08), but combined with short-term goals they do (d >= 0.43).

2. **Feedback loops via summaries** — Our daily/weekly/monthly/yearly summary sessions provide exactly the feedback the research says is essential. Without feedback, goals don't significantly improve performance.

3. **SMART-lite approach** — We already avoid rigid SMART enforcement, which aligns with the finding that specific goals aren't significantly better than non-specific ones.

4. **Coach-first time estimation** — Having the coach propose and the user confirm aligns with the finding that researcher/coach-set goals outperform purely self-set goals.

5. **Energy-aware capacity checking** — Our emphasis on feasibility and not overcommitting aligns with the finding that unrealistically difficult goals lead to disengagement.

### Where we should improve

1. **Add a process goal conversion step** — Our goal-setting guide focuses on refinement (clarity, meaning, feasibility, balance, time) but never explicitly converts higher-level goals into controllable daily behaviors. We should add a step that asks: "What daily action, fully within your control, would move this forward?"

2. **Emphasize controllability in daily targets** — Our `/daily-targets` command should explicitly steer toward process goals. Instead of "Work on fitness" (vague outcome), guide toward "30-minute walk before lunch" (controllable process).

3. **Add a weekly process-goal tracker** — The reference workspace's Mon-Sun checkbox grid for process goals provides visual feedback on behavioral consistency. Our weekly summary could include a process goal adherence grid.

4. **Ground the coaching in research** — Our coach persona and goal-setting guide should reference the research (lightly, not academically) so the coach can explain *why* process goals matter when the moment calls for it. Not every session — but when a user sets only outcome goals, the coach should know to gently redirect.

5. **Strengthen the feedback mechanism** — The research shows goals without feedback are ineffective. We should make summary/check-in sessions feel less optional. The coach could gently prompt: "It's been a few days since you checked in. Quick progress note?"

6. **Consider coach-proposed goals more often** — The finding that researcher-set goals outperform self-set goals suggests our coach should sometimes propose specific goals (especially process goals) rather than always asking the user to generate them. "Based on your monthly goal to improve fitness, what if your daily target was a 30-minute walk before noon?"

---

## Caveats We Should Keep in Mind

1. **Context is sport, not life coaching.** The meta-analysis covers sport performance tasks (darts, golf, basketball, swimming). Personal development goals may respond differently. We should apply the principles (process > outcome, feedback essential, short-term + long-term > long-term alone) while acknowledging the evidence base is sports-specific.

2. **Small, mostly lab-based studies.** Only 5 of 27 studies were in naturalistic settings. Most were single-session experiments, not longitudinal coaching relationships like ours. Our ongoing coaching model may produce different dynamics.

3. **Effect sizes may be inflated.** Only 3 of 27 studies reported power analyses. The process goal effect size (d = 1.36) comes from a small number of studies and may not fully replicate in broader contexts.

4. **Novice bias.** Many of the strongest effects were with novice participants. Users who are experienced goal-setters may see smaller benefits.

5. **Process goals aren't always appropriate.** For some life domains (relationships, spirituality), controllable daily behaviors may feel too mechanical. The coach should use judgment about when to push for process goals and when to allow more open, reflective goal-setting.

---

## How the Reference Workspace (2026-coach) Interpreted This Research

The reference workspace by Bayram Annakov built its entire methodology around this paper, claiming "process goals are 15x more effective than outcome goals." This claim comes from dividing effect sizes (1.36 / 0.09 ≈ 15x), which is technically true for the point estimates but is a simplified comparison — the outcome goal effect size wasn't statistically significant, so the "15x" framing overstates precision.

The reference does several things well with the research:
- Makes the research immediately actionable (outcome → process conversion)
- Creates a clear accountability system (daily checkboxes, weekly review)
- Provides zoom-in/zoom-out coaching prompts

Where it oversimplifies:
- Treats the findings as universal truth rather than sport-specific evidence
- Ignores moderators (experience, feedback, goal proximity)
- Focuses on a single annual outcome goal, missing the multi-domain life balance our workspace covers
- Doesn't account for the finding that feedback is essential — it creates a weekly review template but doesn't build feedback into the daily flow

Our approach should take the research seriously while applying it with more nuance.

---
---

# Article 2: Locke & Latham (2002) — The Foundational Theory

## Source

Locke, E.A. & Latham, G.P. (2002). "Building a Practically Useful Theory of Goal Setting and Task Motivation: A 35-Year Odyssey." *American Psychologist*, 57(9), 705-717. [doi:10.1037//0003-066X.57.9.705](https://doi.org/10.1037//0003-066X.57.9.705)

This is the seminal paper summarizing 35 years of goal-setting research. It's the foundation on which Williamson et al. (2022) built.

---

## Key Findings

### 1. Specific, Difficult Goals Outperform "Do Your Best" Goals

The core finding across hundreds of studies: specific, difficult goals consistently led to higher performance than vague "do your best" instructions. Effect sizes (d) ranged from **0.42 to 0.80** across meta-analyses.

Why "do your best" fails: it has no external referent and allows a wide range of acceptable performance levels. People define it idiosyncratically, so they settle for less.

However, goal specificity alone doesn't guarantee performance — "goal specificity in itself does not necessarily lead to high performance because specific goals vary in difficulty" (p. 706).

### 2. Four Mechanisms by Which Goals Work

Goals affect performance through four pathways:

1. **Direction** — Goals direct attention and effort toward goal-relevant activities and away from irrelevant ones. Both cognitively and behaviorally.
2. **Energy** — High goals lead to greater effort than low goals. Demonstrated across physical tasks, cognitive tasks, and subjective effort measures.
3. **Persistence** — Hard goals prolong effort when people control their time. (But there's a trade-off: people may work faster/more intensely for shorter periods, or slower/less intensely for longer.)
4. **Strategy** — Goals lead to discovery and use of task-relevant knowledge and strategies. For familiar tasks, people deploy automatized skills. For new tasks, they engage in deliberate planning.

**Implication for our workspace:** Our coaching should activate all four mechanisms. Direction = aligning daily targets with monthly goals. Energy = setting goals that stretch. Persistence = check-ins that maintain momentum. Strategy = helping users think about *how*, not just *what*.

### 3. Three Critical Moderators

**Goal commitment:** The goal-performance relationship is strongest when people are committed. Commitment depends on (a) importance of the goal outcomes to the person, and (b) self-efficacy — the belief they can attain it. Public commitment also enhances follow-through.

**Feedback:** "For goals to be effective, people need summary feedback that reveals progress in relation to their goals." The combination of goals + feedback is more effective than goals alone. Without feedback, people can't adjust effort, direction, or strategy.

**Task complexity:** Goal effects are smaller for complex tasks (d = 0.48) than simple tasks (d = 0.67). On complex tasks, strategy matters more than raw effort. Critically: **on new complex tasks, performance goals can actually interfere with learning.** Learning goals should be used instead.

### 4. Learning Goals vs. Performance Goals on Complex Tasks

This is a crucial distinction for life coaching:

- **Performance goals** (achieve X level of output) work well for familiar tasks where the person already has the skills.
- **Learning goals** (discover Y strategies or develop Z skills) work better for new, complex tasks where skills haven't been developed yet.

Winters & Latham (1996): "When a specific difficult learning goal rather than a performance goal was set, consistent with goal-setting theory, high goals led to significantly higher performance on a complex task than did the general goal of urging people do their best."

**Implication:** When users are pursuing goals in unfamiliar domains, the coach should frame targets as learning goals ("Try three different approaches to meal prep this week") rather than performance goals ("Eat under 2000 calories every day").

### 5. Proximal (Short-Term) Goals Aid Complex Task Performance

Latham & Seijts (1999): On a complex business simulation, "do-your-best" goals were more effective than distal outcome goals. But the most effective were **proximal sub-goals** — breaking the task into manageable near-term targets.

Stock & Cervone (1990): Proximal goals enhanced both self-efficacy and performance on a complex task over three sessions.

This strongly supports our daily → weekly → monthly hierarchy.

### 6. Goals as Mediators of Other Incentives

Personal goals mediate the effects of assigned goals, monetary incentives, and feedback. Self-efficacy mediates alongside goals. This means: **all motivation ultimately flows through the person's own goals and confidence.** External incentives only work insofar as they shape personal goals.

Assigning a challenging goal implicitly communicates confidence, which raises self-efficacy. Providing a rationale for assigned goals is as effective as participative goal-setting.

### 7. The Goal-Satisfaction Paradox

People with the highest goals produce the most but are the least satisfied — because the bar for satisfaction is set high. This creates a motivational engine: dissatisfaction with less drives continued high performance. But it also risks chronic dissatisfaction if not managed.

**Implication:** Our coach should help users celebrate genuine wins (not over-praise, but acknowledge real progress) to counterbalance the natural tendency for high-achievers to always feel behind.

### 8. Goal Conflict Undermines Performance

When personal goals conflict with each other, performance suffers. Seijts & Latham (2000): When personal goals were aligned with group goals, group performance was enhanced. Without alignment, personal goals had a detrimental effect.

**Implication:** Our domain-balanced approach helps detect goal conflicts across life areas. The coach should check: "Does this goal compete with your other priorities for time or energy?"

---

## What This Adds Beyond Williamson et al. (2022)

Williamson studied *which* goal types work best in sport. Locke & Latham explain *why and how* goals work in general:

1. **The four mechanisms** give us a framework for coaching conversations (direction, energy, persistence, strategy).
2. **Learning goals vs. performance goals** is critical for life coaching — many personal development goals involve new skills and complex behavior change, where performance goals can backfire.
3. **Goal commitment through rationale** validates our coach's approach of explaining "why" goals matter, not just setting them.
4. **The satisfaction paradox** warns us that ambitious goal-setters need help appreciating progress, not just pursuing more.
5. **Goal conflict** gives a research basis for our domain-balance checking.

---
---

# Article 3: Ehrlich (2023) — Happiness Through Goal-Setting Training

## Source

Ehrlich, C. (2023). "Evaluation of the Happiness Through Goal-Setting Training." *Psychological Reports*, 126(4). [doi:10.1177/00332941211071007](https://doi.org/10.1177/00332941211071007). Published online 2022, PMC: PMC10291381.

Two studies: face-to-face (N = 41) and online (N = 40). Before-and-after design.

---

## Key Findings

### 1. *Why* You Pursue Goals Matters as Much as *What* You Pursue

The paper introduces the **Goal-Striving Reasons Framework (GSRF)**, which categorizes reasons for pursuing goals along two dimensions:

| | Approach (toward desired) | Avoidance (away from undesired) |
|---|---|---|
| **Internal** (within-person) | **Pleasure** — enjoying the process | **Self-esteem** — fear of feeling like a failure |
| **External** (person-environment) | **Altruism** — helping others | **Necessity** — "I have to earn a living" |

**Approach reasons** (pleasure, altruism) predict higher happiness. **Avoidance reasons** (self-esteem protection, necessity) predict lower happiness. This is consistent across multiple populations and has higher predictive power than self-concordance theory in some studies.

### 2. The Training Significantly Improved Both Goal Reasons and Well-Being

Results from both delivery modes:

| Measure | Face-to-face (d) | Online (d) |
|---------|-------------------|------------|
| Goal-Striving Reasons Index | **1.16** | **0.74** |
| Pleasure | 0.82 | 0.63 |
| Altruism | 0.39 | 0.53 |
| Self-esteem (reduced) | 0.93 | 0.57 |
| Necessity (reduced) | 0.63 | 0.52 |
| Life Satisfaction | **1.73** | 0.43 |
| Positive Affect | 0.37 | 0.39 |
| Negative Affect (reduced) | 0.50 | 0.45 |
| Work Engagement | 0.31 | 0.39 |

All changes were statistically significant. The largest effects were on the goal-striving reasons themselves (especially reducing self-esteem-driven pursuit), with meaningful spillover to well-being outcomes.

### 3. People Scoring Low Before Training Benefited the Most

This is consistent with a general finding in positive psychology: interventions help people who need them most. People with initially low pleasure motivation or high self-esteem-fear showed the largest improvements.

### 4. Four Practical Interventions That Shifted Goal Reasons

The training used these specific techniques:

**A. Unconditional self-esteem (reduces self-esteem-driven goals):**
- Distinguish conditional vs. unconditional self-esteem
- Identify "self-validating goals" — goals pursued to prove self-worth
- Reframe: "I can still value myself even if I don't achieve goal X"
- Use learning goals instead of performance goals to protect self-esteem during setbacks

**B. Pleasure enhancement (increases enjoyment of goal pursuit):**
- Create a weekly "fun things to do" list to build positive mood spillover (broaden-and-build theory)
- Align explicit goals with implicit motives (achievement, affiliation, power) — when goals match what you unconsciously enjoy, pursuit becomes more pleasurable

**C. Altruism amplification (increases prosocial motivation):**
- Acts of kindness: create a list of ~15 AoK to integrate into daily life (variety prevents hedonic adaptation)
- Cognitive job crafting: for each goal, articulate its positive impact on others, community, or society

**D. Necessity reduction (reduces "I have to" motivation):**
- Reflect on what level of material wealth is genuinely sufficient for happiness
- Reduce social comparison by setting internal standards rather than comparing to others

---

## What This Means for Our Workspace

### The critical insight: coach the *why*, not just the *what*

Our current goal-setting guide focuses on goal *quality* (clarity, meaning, feasibility, balance, time). It doesn't explicitly examine *reasons for pursuit*. Two users can set the identical goal — "get promoted" — but if one pursues it from pleasure/growth and the other from self-esteem fear, their well-being trajectories will diverge.

### Specific improvements we should consider

1. **Add a "why are you pursuing this?" reflection step.** During goal-setting sessions, gently explore whether goals are approach-driven (pleasure, purpose) or avoidance-driven (fear, obligation). Not as a test — as a conversation.

2. **Watch for self-validating goals.** When a user's language suggests conditional self-worth ("I need to prove...", "If I don't do this I'll feel like a failure..."), the coach can gently introduce the distinction between the goal and the person's value.

3. **Use learning goals to protect self-esteem.** When users fear failure, framing targets as learning experiments ("Let's see what you discover") rather than performance benchmarks reduces the psychological risk of not hitting them.

4. **Help users find pleasure in process.** Ask: "Which parts of working toward this goal do you actually enjoy?" If the answer is "none," that's important information about sustainability.

5. **Connect goals to impact on others.** Our altruism exercise could be: "Who benefits when you achieve this goal?" This reframes self-focused goals as prosocial ones without changing the goal itself.

6. **Challenge pure necessity framing.** When a user frames every goal as obligation ("I have to..."), the coach can explore: "What would you *choose* to do if the 'have to' wasn't there?"

### Caveats

- No control group in either study — placebo effect cannot be ruled out.
- Small samples (41 and 40), predominantly female (~80-87%), average age 43.
- Self-selection bias (voluntary participants tend to be more motivated).
- Effect sizes for well-being outcomes (d = 0.31-0.50) are in line with typical positive psychology interventions, suggesting the training works about as well as other established approaches.
- The face-to-face life satisfaction jump (d = 1.73) likely reflects the very low baseline of that sample rather than an unusually large effect.

---
---

# Article 4: Dickson et al. (2021) — New Year Resolution Pursuit and Wellbeing

## Source

Dickson, J.M., Moberly, N.J., Huntley, C.D., Sherborne, A. & Sherborne, D. (2021). "Self-Regulatory Goal Motivational Processes in Sustained New Year Resolution Pursuit and Mental Wellbeing." *International Journal of Environmental Research and Public Health*, 18(6), 3084. [doi:10.3390/ijerph18063084](https://doi.org/10.3390/ijerph18063084). PMC: PMC8002459.

Longitudinal study, 182 participants (Australia & UK), 4 timepoints over 2 months.

---

## Key Findings

### 1. Goal Flexibility Predicts Well-Being; Tenacity Does Not

| Predictor | Predicts well-being? | Predicts sticking to resolutions? |
|-----------|---------------------|----------------------------------|
| **Goal flexibility** | **Yes** — significant at T1-T3, approached significance at T4 (β = 0.33-0.48) | Only at T2; not at T3 or T4 |
| Goal tenacity | No — only correlated at baseline | No |
| Flexibility × tenacity interaction | No | No |

**Goal flexibility** — the ability to view setbacks with equanimity and adjust goal pursuit as required — was the only significant predictor of wellbeing over time, explaining 21-29% of variance in the models.

**Goal tenacity** — persistence in striving toward a goal under difficult conditions — did *not* predict either wellbeing or resolution stickability at any follow-up timepoint.

The interaction between flexibility and tenacity was also non-significant.

### 2. People Are Not Good at Sticking to New Year Resolutions

Despite reporting high commitment (M = 5.94/7) and high importance (M = 6.03/7) at baseline, participants still showed substantial dropout and declining stickability over 2 months. Neither commitment nor importance at baseline reliably predicted sticking with the resolution over time.

Key patterns:
- Over 50% of resolutions focused on diet (29%) or exercise (24.6%)
- 53% of participants had the same or similar resolution in previous years (cyclical goal rebooting)
- 65% of resolutions were described in very general/abstract terms ("get fit") rather than specific terms ("walk 40 min, 4x/week")
- Neither resolution specificity nor approach/avoidance orientation predicted stickability

### 3. Approach-Oriented Resolutions Were Overwhelmingly More Common

89% of resolutions were approach-oriented ("I will eat healthily") vs. 11% avoidance-oriented ("I will avoid fatty foods"). Among study completers (those who stuck around for all 4 timepoints), 96% had approach-oriented resolutions — suggesting avoidance-framed goals may predict earlier abandonment.

### 4. Abstract Goals Are the Norm But May Hinder Follow-Through

The authors note: "Setting specific New Year resolutions is more likely to suggest the necessary strategies and plans to aid sustained and successful pursuit and to promote wellbeing, relative to abstract or vague resolutions."

They also note that goals are hierarchically organized, and suggest that "linking people's more abstract resolutions to more concrete lower order resolutions [may] facilitate sustained New Year resolution pursuit and enhanced wellbeing over time."

---

## What This Means for Our Workspace

### 1. Flexibility is more important than grit

The conventional wisdom is "just persist." But this study found that the ability to *adjust* — to view setbacks with composure and adapt one's approach — predicted wellbeing far better than tenacity. Rigid persistence didn't help at all.

**Implication:** Our coach persona already values flexibility ("not today" is an acceptable answer, gaps are information not failure). This research validates that approach. We should also explicitly help users adjust goals when circumstances change, rather than treating any modification as giving up.

### 2. Our Active/Retired goal system is research-aligned

The finding that tenacious pursuit doesn't predict success or wellbeing supports our goal lifecycle model where goals can be Revised, Released, or Evolved. Moving a goal to "Retired" with dignity is psychologically healthier than grinding toward an unworkable target.

### 3. Help users convert abstract goals into concrete sub-goals

65% of New Year resolutions were abstract. Abstract goals are harder to act on and stick to. Our hierarchical cascade (yearly vision → monthly specifics → daily actions) directly addresses this — but we should be more explicit about the conversion step. When a user states a broad goal, the coach should help decompose it.

### 4. Watch for cyclical "reboot" goals

53% of participants were retrying a resolution from a previous year. When a user brings the same goal back, the coach should acknowledge the pattern and explore what was different before: "You mentioned this goal last month too. What got in the way? Should we approach it differently this time?"

### 5. Approach framing > avoidance framing

The strong skew toward approach goals among study completers suggests that goals framed as "move toward" something are more sustainable than "move away from" something. Our coach should help users reframe avoidance goals: "Stop eating junk food" → "Build a meal prep habit."

### Caveats

- Self-report study with high attrition (182 → 54 over 2 months).
- 81% female sample — may not generalize equally.
- Neither flexibility nor tenacity predicted *sticking* to resolutions — only flexibility predicted wellbeing. This suggests that for actual behavioral adherence, other factors matter (implementation intentions, environment design, etc.).
- New Year resolutions are a specific cultural context — may not generalize to coached goal-setting.

---
---

# Cross-Article Synthesis: What the Research Collectively Tells Us

## Consistent themes across all four articles

| Principle | Williamson (2022) | Locke & Latham (2002) | Ehrlich (2023) | Dickson (2021) |
|-----------|-------------------|----------------------|----------------|----------------|
| Process/behavioral goals > outcome goals | d = 1.36 vs 0.09 | Performance goals interfere on complex tasks | — | Abstract goals predict poor adherence |
| Feedback is essential | d = 0.49 with vs 0.21 without | "Goals + feedback more effective than goals alone" | — | — |
| Short-term + long-term > long-term alone | Long-term alone d = -0.08 | Proximal sub-goals aid complex performance | — | Hierarchical goal linking suggested |
| Self-efficacy is central | Process goals boost it (d = 1.11) | Mediates goal effects across all domains | Reducing self-esteem fear improves outcomes | — |
| Flexibility matters | — | — | Reducing rigid self-worth contingencies | Flexibility predicts wellbeing; tenacity doesn't |
| *Why* you pursue matters | — | Commitment + importance drive effects | Approach reasons predict happiness; avoidance reasons predict unhappiness | Approach-framed goals associated with persistence |
| Learning > performance for new skills | — | Learning goals outperform on complex new tasks | Learning goals protect self-esteem | — |

## Priority improvements for our workspace (ranked)

1. **Add a process goal conversion step** — Supported by Williamson (process goals d = 1.36), Locke & Latham (proximal sub-goals on complex tasks), and Dickson (abstract goals → poor adherence).

2. **Explore goal motivation during goal-setting** — Supported by Ehrlich (approach vs. avoidance reasons predict wellbeing), Dickson (approach framing predicts persistence), and Locke & Latham (commitment through understanding "why").

3. **Use learning goals for unfamiliar domains** — Supported by Locke & Latham (performance goals interfere on complex tasks) and Ehrlich (learning goals protect self-esteem during setbacks).

4. **Strengthen feedback loops** — Supported by Williamson (goals without feedback not significant) and Locke & Latham (feedback is a critical moderator).

5. **Normalize goal revision as healthy, not failure** — Supported by Dickson (flexibility predicts wellbeing; tenacity doesn't) and Ehrlich (reducing self-esteem contingency improves outcomes).

6. **Help reframe avoidance goals as approach goals** — Supported by Dickson (approach completers = 96%) and Ehrlich (approach reasons predict happiness).

7. **Watch for cyclical "reboot" patterns** — Supported by Dickson (53% retrying last year's goal). Coach should flag and explore, not just re-set.

8. **Add a weekly behavioral tracker** — Supported by Williamson (feedback essential) and ref workspace's checkbox grid design.
