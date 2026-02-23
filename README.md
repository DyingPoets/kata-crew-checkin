# Field Crew Check-In — Monitoring + Feedback Loops

> **Branch:** `skill/monitoring-feedback`
> **Skills:** O2 · C1 · M3
> **Audience:** PM · Eng

---

## For the Facilitator

### Session Overview

| | |
|---|---|
| **Kata** | 4: Field Crew Check-In |
| **Session** | Monitoring + Feedback Loops |
| **Skills** | O2 · C1 · M3 |
| **Duration** | 2 hours (facilitated) + self-directed extension |
| **Slide Deck** | https://gamma.app/docs/renh4tjfsea4jrk |
| **Miro Board** | https://miro.com/app/board/uXjVG8Q_uu0%3D/ |

### Session Timing

| Time | Activity |
|------|----------|
| 0:00–0:15 | Concept framing — open the Gamma slide deck and walk through each slide |
| 0:15–0:30 | Orient to Miro board + this starting state |
| 0:30–1:05 | Step 1 exercise (Miro — Context frame) |
| 1:05–1:25 | Step 2 exercise (Miro — Exercise frame) |
| 1:25–1:30 | Step 3 wrap-up |
| 1:30–1:50 | Debrief — use Miro Debrief frame prompts |
| 1:50–2:00 | Extension brief — point to Extension Zone in Miro |

### What to Watch For

- Alerts without runbooks — "what does the on-call do?" must be answered
- Metrics that measure activity (number of check-ins) not outcomes (check-ins completing successfully)
- Feedback prompts that would annoy a field tech — test every design against the Marcus persona

### Facilitation Tips

- Ask: "How long after a silent failure would you know?" — the answer should be minutes, not days
- For each metric: "If this number goes to zero, what does that mean?" — ensures they're measuring outcomes
- Pair PMs and engineers on the metric-to-intent exercise — both perspectives needed

### Extension / Coaching Office Hours

Participants can continue extension work independently and bring it to **Coaching Office Hours**.
At Office Hours, focus on: what decision did they make, why, and what would they change?

---

## For Participants (Developer · PM · UX)

### Getting Started

```bash
git clone https://github.com/DyingPoets/kata-crew-checkin
git checkout skill/monitoring-feedback
```

Open the Miro board and the Gamma slide deck — have both visible during the session.

- **Slides:** https://gamma.app/docs/renh4tjfsea4jrk
- **Miro Board:** https://miro.com/app/board/uXjVG8Q_uu0%3D/

### What You'll Practice

- O2
- C1
- M3

### Your Starting State

You have:
- `app/monitoring-config.md` — the current (empty) monitoring setup
- `personas/marcus-persona.md` — the field tech persona to design the feedback mechanism for

Your goal: define 3 production alerts, design a feedback mechanism, and write metric-to-intent statements.

### Step by Step

**Step 1:** Define 3 production alerts. For each: what event triggers it, what threshold, who gets paged, what they should do (one-paragraph runbook).

**Step 2:** Design an in-app feedback mechanism for Marcus. One screen, one question, one tap. Consider: timing (when to show it), frequency (survey fatigue), and what you do with the data.

**Step 3:** For each metric you defined: complete the sentence "If this metric moves as intended, it proves ____."

### What Good Looks Like

Alerts with runbooks an on-call engineer could follow at 3am. A feedback mechanism a field tech would actually use. Metrics with clear intent statements.

See the `solutions/` directory for reference examples — but try the exercise first.

### Extension Work

- Write a full runbook for your most critical alert: triggers, escalation, resolution steps
- Design an A/B test for two feedback prompt placements (end of session vs. next-day push)
- Define what "done" looks like for monitoring: what would you need to see before you'd trust this system in production?

Bring your extension work to **Coaching Office Hours**. You'll get 15 minutes of focused feedback.

---

Part of the [PDLC Training Katas](https://github.com/DyingPoets) series.
