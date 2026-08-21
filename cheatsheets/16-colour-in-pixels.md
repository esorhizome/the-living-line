# Sheet 16 · Colour in Pixels (Lesson 16)

*Words on this sheet:* **palette** = the fixed list of allowed colours · **ramp** = dark→light colours for one material · **hue / saturation / value** = colour family / intensity / lightness · **hue-shifting** = hue moves cooler in shadow, warmer in light · **dithering** = two colours in a pattern the eye blends · **indexed colour** = pixels store palette numbers, so editing the palette recolours the image · **palette swap** = one sprite, new colours, "new" character.

> **P·I·X·L — "Palette small · Integer scale · eXport PNG · Look at 100 %."** This sheet is the P.

**Palette:**

- ☐ Start with 4 colours (ARQ4) → 12 (AAP-Micro12) → 16 · 2–3 colours per body part · 6–12 per character
- ☐ Borrow from Lospec: ENDESGA 32 · DawnBringer 32 · PICO-8 · Sweetie 16 · AAP-64
- ☐ "If you can't make a good sprite in 4 colors, using 40 colors isn't going to help"

**Ramps:**

- ☐ Light source FIRST
- ☐ Shadow = value down + hue towards cool · Light = value up + hue towards warm · saturation: decide (PIXNOTE nudges it up in shadow, Medeiros down) and stay consistent
- ☐ Schlitter's ramps: ~20° of hue shift per swatch · value steps shrink near white · never 100 % saturation
- ☐ 16×16 → 2 tones per material · 64×64+ → 4–5
- ☐ Check in grey (desaturate, or a black layer on "Color" mode): if it still reads, the values work

**Dither:**

- ☐ Only between similar values · never on outlines · never the whole screen
- ☐ Best for big flat areas, banding, and texture that does double duty (stone, sand, weave)
- ☐ Heavy dither = gritty/retro/scruffy · flat clusters = clean/modern/elegant

**The recolour trick (casting with colour only):**

- ☐ Warm + contrast = hero · cool + desaturated = tired/ghost · dark + one hot accent = villain · pastels = gentle
- ☐ Indexed mode (Aseprite/Pixelorama): edit the palette, not the pixels

---

*The Living Line · [full guide](../The_Living_Line_Guide.md) · CC BY 4.0 © esorhizome OÜ*
