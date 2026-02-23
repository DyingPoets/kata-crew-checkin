# Field Crew Check-In — Personas + Mobile Design

> **Branch:** `skill/personas-mobile`
> **Skills:** R2 · R5 · A2 · U7
> **Audience:** PM · UX

---

## For the Facilitator

### Session Overview

| | |
|---|---|
| **Kata** | 4: Field Crew Check-In |
| **Session** | Personas + Mobile Design |
| **Skills** | R2 · R5 · A2 · U7 |
| **Duration** | 2 hours (facilitated) + self-directed extension |
| **Slide Deck** | https://gamma.app/docs/84h6i7wnswsfobz |
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

- Personas that are demographics, not behaviour — push for goals, frustrations, context of use
- Flows that ignore physical constraints (gloves, sun, 1 bar of signal)
- The 3-tap rule getting ignored — count the taps every time

### Facilitation Tips

- Ask: "Would this work at 7am, outside, with gloves on, in bright sun?" for every screen
- Have participants read their personas aloud before auditing the wireframe — embody the user
- At debrief: compare flows side by side. Which one is actually 3 taps?

### Extension / Coaching Office Hours

Participants can continue extension work independently and bring it to **Coaching Office Hours**.
At Office Hours, focus on: what decision did they make, why, and what would they change?

---

## For Participants (Developer · PM · UX)

### Getting Started

```bash
git clone https://github.com/DyingPoets/kata-crew-checkin
git checkout skill/personas-mobile
```

Open the Miro board and the Gamma slide deck — have both visible during the session.

- **Slides:** https://gamma.app/docs/84h6i7wnswsfobz
- **Miro Board:** https://miro.com/app/board/uXjVG8Q_uu0%3D/

### What You'll Practice

- R2
- R5
- A2
- U7

### Your Starting State

You have:
- `interviews/` — 3 raw field interview transcripts
- `wireframes/checkin-wireframe.md` — existing wireframe that ignores mobile constraints

Your goal: build 2 personas and redesign the check-in flow to work for them.

### Step by Step

**Step 1:** Read the 3 interviews. Build 2 personas: include role, goals, frustrations, device, connectivity reality. Make them specific — a name, a routine, a real pain.

**Step 2:** Audit the wireframe against your personas. Flag every interaction that fails the "gloves on, bright sun" test. Annotate with why.

**Step 3:** Redesign the check-in flow for Persona 1. Maximum 3 taps. Sketch in Miro.

### What Good Looks Like

Personas your team would refer back to when making future design decisions. A flow where you can count exactly 3 taps from launch to confirmed check-in.

See the `solutions/` directory for reference examples — but try the exercise first.

### Extension Work

- Design the offline experience: what happens when a tech checks in with no signal?
- Write 3 interview questions you'd ask before building the offline feature
- Sketch the error states: failed check-in, GPS unavailable, duplicate check-in

Bring your extension work to **Coaching Office Hours**. You'll get 15 minutes of focused feedback.

---

Part of the [PDLC Training Katas](https://github.com/DyingPoets) series.
