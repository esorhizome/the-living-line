# Sheet 15 · The Grid — pixel fundamentals (Lesson 15)

*Words on this sheet:* **pixel** = the smallest square of colour; in pixel art, placed by hand · **cluster** = touching pixels of one colour (the real brushstroke) · **orphan pixel** = a lone pixel of its colour (noise unless deliberate) · **jaggies** = uneven stair-steps on a line · **doubles** = a 2-pixel corner on a 1-pixel line · **AA (anti-aliasing)** = in-between colours placed by hand at stair-steps · **selout** = an outline that lightens where lit.

> **P·I·X·L — "Palette small · Integer scale · eXport PNG · Look at 100 %."**

**Before drawing:**

- ☐ Automatic anti-aliasing OFF on pens, fills, selections, text (Lesson 18 has every menu)
- ☐ 1-pixel pen · 1-pixel grid · a second view at 100 %
- ☐ Start at 16×16, then 32×32 · pick the size as a casting choice (big head = cute; long body = serious)

**While drawing:**

- ☐ Think in clusters: big blobs first, edges last · hunt orphan pixels
- ☐ Lines: constant steps = straight (3-3-3) · consistently changing steps = curve (1-1-2-3-5) · anything else = jaggy
- ☐ Erase doubles (the L-corners) · lines are expensive — let contrast do their job
- ☐ AA only on steps longer than 1 px · never on 45° lines · never outward past a game sprite's edge · not at all ≤ 16 px
- ☐ Light source first → no pillow shading · break up banding
- ☐ Outline = a casting choice: black = toy/arcade · selout = lit/dimensional · none = painterly

**Check at 100 %:**

- ☐ Silhouette test (fill it black) · does one pixel of eye-shift change the mood? It should
- ☐ Angular clusters = hard/mechanical · rounded = soft/organic · stray orphans = scruffy (only if chosen)

---

*The Living Line · [full guide](../The_Living_Line_Guide.md) · CC BY 4.0 © esorhizome OÜ*
