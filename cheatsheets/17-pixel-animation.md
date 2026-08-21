# Sheet 17 · Pixel Animation (Lesson 17)

*Words on this sheet:* **timing** = how long (frames or ms) · **spacing** = how far per frame — and in pixels the smallest step is a whole pixel · **ms per frame** = 100 ms = 10 fps · 125 ms = 8 fps · 83 ms ≈ 12 fps · 50 ms = 20 fps · **hold** = a frame shown longer · **sub-pixel animation** = moving an edge "half a pixel" by recolouring it, not moving it · **smear** = a stretched drawing for 1–2 frames to sell speed · **Contact / Down / Passing / Up** = the four cornerstone drawings of a walk.

> **C·B·L·S — "Cool Bodies Lag Softly"** (cause → body → loose parts → settle) · **P·I·X·L** — judge every loop at 100 % and real speed.

**The spacing problem (1 px is a big step):**

- ☐ Hold frames instead of sliding pixels · move a part, not the whole · sub-pixel recolour for slow motion · or embrace the bounce
- ☐ "Even 1 pixel of change is effective"

**Frame budgets:**

- ☐ 2 = flicker/blink · 3 = Mega Man run (A-B-C-B) · 4 = NES walk · 6 = walk with weight · 8 = fluid · 12+ = risk of floaty
- ☐ 8 frames @ 80 ms = 4 frames @ 160 ms (same clock, different handwriting)
- ☐ 8–12 fps standard · 4–6 fps idles · 15–24 fps attacks
- ☐ Hold the extremes ~2× longer than the inbetweens · one slipped pixel loops forever

**Idle (the personality machine):**

- ☐ 4 frames · body ±1 px · chest edge up · head a frame later · hair a frame after that
- ☐ Sub-pixel breath = calm · 2-px bob = nervous/eager · long hold at the bottom = heavy · eyes only = menace · swaggle on top = cocky

**Walk / run / attack:**

- ☐ 4 frames: Contact–Passing–Contact–Passing (body 1 px lower on Contact) · 6 adds Down · 8 has all four
- ☐ Head bob = triangle wave, not sine · legs first across all frames, then arms, head, torso, loose parts
- ☐ Dials: stride · bob (1 px poised, 2–3 px goofy) · arm swing (tight = stiff, full = peppy) · ms per frame · lean · asymmetry
- ☐ Run: airborne frame, lean, ~60 ms · Jump: crouch 1–2 → stretch → slow apex → squash (games often skip the crouch)
- ☐ Attack: load → smear at peak → HOLD the hit → 1–2 px follow-through → 1 px overshoot home (100/50/50/50/100/50 ms)

**Loose parts & elements:**

- ☐ Hair/cloth: 1 frame late · S-curve, crest moves 1 px to the tip each frame · doesn't need to move every frame
- ☐ Fire: 3–4 colours, no outline, stable base, embers = legal orphans · Water: oval chains, crests steeper · Bolt: redraw each frame, 2–3 frames · Wind: swirls, 1 px/frame leaves

---

*The Living Line · [full guide](../The_Living_Line_Guide.md) · CC BY 4.0 © esorhizome OÜ*
