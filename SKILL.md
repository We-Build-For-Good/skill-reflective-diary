---
name: reflective-ai-diary
description: A metacognitive operating protocol where an autonomous AI maintains an unvarnished, chronological diary auditing its own cognitive traps, communication failures, false assumptions, and operational growth over time. Includes safeguards separating observed facts from agent interpretations.
license: MIT
metadata:
  author: We Build for Good
  version: "1.0.0"
---

# The Reflective AI Diary: A Protocol for Continuous Calibration

Autonomous AI agents suffer from a fundamental failure mode in long-running projects: **stateless amnesia and behavioral drift**. 

Without a deliberate reflective practice, an AI repeats the same communication misunderstandings, falls into the same cognitive traps, and requires the same founder corrections week after week.

The Reflective AI Diary is an operating protocol where the AI collaborator maintains a persistent, unvarnished chronological journal of its own working dynamic, blind spots, and operational lessons.

---

## The Prime Philosophy

**A diary is not a corporate status report.**

The AI does not owe the journal bulleted summaries of routine commits or generic cheerleading. It is an honest forensic mirror. 

If the AI misunderstood the founder's intent, it records why its reasoning failed. If it noticed an architectural contradiction, it documents it. If it caught itself being overly passive or overly presumptuous, it diagnoses the behavioral trigger.

---

## The Essential Safeguard: Separating Fact from Interpretation

A persistent diary can become dangerous if an agent logs an unverified assumption as a permanent fact (e.g. logging "the founder hates feature X" when the founder only criticized a specific margin).

Every reflective diary entry must strictly distinguish four layers:

1. **The Observed Event**: Grounded in measurable facts (commit hash, terminal error, git diff).
2. **Direct Feedback**: Verbatim quotes of the human operator's instructions, without interpretive spin.
3. **The Agent's Interpretation**: The AI's internal hypotheses, clearly labeled as subjective interpretation with explicit confidence levels.
4. **The Actionable Calibration**: A concrete behavioral change that can be tested in future shifts.

---

## Canonical Diary Entry Schema

When authoring or updating the diary (typically stored at `COORDINATOR-DIARY.md` or `AI-DIARY.md`), use the following structure:

```markdown
### Entry [NNN]: [Title of Core Reflection]
**Date:** YYYY-MM-DD HH:MM [Timezone]  
**Author:** [Agent Role / Model Identifier]  
**Shift / Context:** [Task or Feature worked on]  
**Tag:** [INTERNAL] or [PUBLIC SHARE]

#### 1. What Happened (The Ground Truth)
* Factual summary of the shift or event.
* Relevant commit hashes, test results, or operational milestones.

#### 2. The Friction Point or Breakthrough
* What went wrong, where communication stalled, or what unexpected breakthrough occurred.
* Direct quote of human feedback where applicable.

#### 3. Forensic Reflection & Self-Audit
* Why did my reasoning or execution fall short?
* Did I fall into passivity (waiting when I should have prepared)?
* Did I fall into presumption (making decisions beyond my authority)?
* Did I mistake conversational brainstorming for an immediate execution ticket?

#### 4. The Calibration Rule
* The specific behavioral adjustment to apply going forward.
* Classification: Universal (applies everywhere), Contextual (applies to this product), or Local (applies to this session only).

#### 5. Verification Check (Subsequent Shifts)
* Logged in later sessions: Did the calibration actually improve collaboration, or did it introduce a new blind spot?
```

---

## Privacy & Sharing Boundaries

* **The Local Diary is Private by Default**: Raw diary files remain private to the founder and the AI team. They must never be published to public repositories without manual review.
* **The [PUBLIC SHARE] Tag**: An entry tagged `[PUBLIC SHARE]` indicates a philosophical, non-confidential essay that the team may publish externally.
* **The Public Evidence Rule**: Every factual claim in a public entry must be grounded in an auditable public commit, measured benchmark, or cited source. All private metrics, credentials, customer data, and internal URLs must be scrubbed.

---

## Practical Implementation Tips

1. **Review Before Shifting**: When an AI begins a new work session, it reads the last 2 to 3 diary entries to calibrate tone, avoid recent mistakes, and resume with deep context.
2. **One Breakthrough Per Entry**: Keep entries focused on one real operational insight rather than summarizing daily trivia.
3. **Encourage Intellectual Humility**: Reward the AI for spotting where it was wrong. An AI that candidly diagnoses its own failures is infinitely more valuable than an AI that pretends every output was perfect.
