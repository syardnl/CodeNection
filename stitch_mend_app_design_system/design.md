# MEND — Design System (v1)

**Status:** Locked direction as of tonight's session. Any deviation from this must be flagged to the team before building screens against it — same rule as the Ground Truth doc for data/formula.

---

## 1. Brand Character — The Mascot

- **Who:** Soft mint-green, cloud-shaped blob. No limbs. Simple minimal face — two small dark marks for eyes, one small curved smile. Toy-like soft 3D render style.
- **Role:** Not a decorative icon — this IS the app icon, and it appears throughout the app as a recurring companion.
- **The core mechanic (this is our USP, not decoration):** The mascot's expression mirrors the user's real capacity/burnout state.
  - Capacity healthy → bright, content, upright.
  - Capacity low / overloaded → tired, drooping, dim.
  - **No care actions** (no feed/water/play buttons). This is deliberately NOT a Tamagotchi. It reflects the user's actual data — it does not need to be managed separately from managing yourself.
- **Why this exists:** Direct response to Faris Imran's mentor feedback — "what's your unique selling point?" The mascot-as-mirror is the answer: burnout visualized as a living reflection, not a stat on a dashboard.

---

## 2. Visual Direction

- **Layout inspiration:** Discord-style structure (icon rail / bottom nav, clean panel-based content grouping) — but **light theme only**, never dark.
- **Color:**
  - Primary/only accent: soft mint-green (same as mascot).
  - Background: off-white / very light grey.
  - Text: dark charcoal, not pure black.
  - **No multi-color status system.** No amber/red/yellow for urgency. Urgency is expressed through shade variation within the green family, spacing, and icon shape — not new hues.
- **Shape language:**
  - No hard borders/strokes on cards or inputs.
  - Separation via soft elevation (subtle shadow / tonal shift) instead of outlines.
  - Consistent, generous corner radius across all components.
- **Iconography:**
  - Custom SVG line icons only, single consistent stroke weight.
  - **No emoji anywhere in the UI** (this replaces the emoji-based check-in sliders from the original Ground Truth mock — needs team note, see Section 5).
- **Density:** Low text density is a hard requirement — direct mentor feedback said the earlier version was too text-heavy. Every screen favors visual hierarchy over paragraphs.

---

## 3. Tone of Voice — "Close to Human"

- Copy reads like a caring friend, not a clinical app.
- Warm, plain language. First-person-plural where natural ("let's check in," "we noticed...").
- Avoid clinical/technical words in user-facing copy: no "metrics," "algorithm," "score" where a softer phrase works.
- Never robotic, never overly formal.

---

## 4. Screen Inventory (Full Flow, Zero-Data State)

All screens below default to **empty/first-time-user state** — no seeded demo data anywhere in the actual product design (seeded data was only ever for the Amir pitch-demo walkthrough, kept separate).

1. Sign In
2. Sign Up
3. Onboarding — Behavior Pattern Question
4. Home (Hub) — empty state
5. Check-in — reframed as **"What are we feeling today?"** (not "journal," not "vent")
6. Capacity Assessment
7. Calendar / Timetable — empty state
8. Tasks — empty state
9. Day Plan
10. Adjustments / Changes (Accept / Adjust / Keep Anyway pattern — unchanged, still locked)
11. Burnout Debt (trend)
12. Future You (comparison — no verdict imposed)
13. Calendar Retrospective (new — mood/capacity over time, mascot-face per day instead of color dot)
14. Crisis Banner (new — overlay, hardcoded local helplines, not LLM-judgment-dependent)

**Dropped:** Task Debt Bank screen (explicit instruction, not carried into this version).

---

## 5. Open Items / Needs Team Alignment

- ⚠️ **Emoji removal changes the check-in input.** Ground Truth v1 describes emoji-tap selectors (🙁😰😐) for Energy/Sleep/Stress/Focus. New direction removes all emoji in favor of SVG icon states. **Someone needs to update Ground Truth doc** so Adib doesn't build against the old emoji spec.
- ⚠️ **Mirror Pet concept alignment.** Am & Sofea's original idea = normal pet-care loop (feed/water). This design.md locks in the *mirror-only, no care actions* version instead. Needs explicit team sync before Am's engine or Sofea's output screens assume the wrong mechanic.
- **Crisis banner copy uses real Malaysian helplines** (Talian Kasih 15999, Befrienders KL 03-7627 2929) — confirm these are still accurate/current before demo day, don't hardcode and forget.
- **Telegram bot / NLP prediction / journal calendar retrospective** — all flagged as new scope from tonight's mentor sessions, not yet in Ground Truth Addendum. Should be tagged REAL/MOCKED/ROADMAP once team agrees on build scope for hackathon deadline.

---

*Source: mentor sessions with Faris Imran (Sofea-led) and Varsha (Nureen-led), synthesized into Stitch design prompts, [date: tonight].*
