# Sheet 18 · The Pixel Studio — tools & pipeline (Lesson 18)

*Words on this sheet:* **nearest neighbour** = scale with hard square pixels, no blur (a.k.a. hard edges / point / pixelated) · **integer scaling** = whole numbers only (2×, 4×, 8×) · **indexed colour** = pixels store palette numbers · **frame tag** = a named frame range (`walk`) · **pixel-perfect mode** = a pencil that removes corner doubles.

> **P·I·X·L — "Palette small · Integer scale · eXport PNG · Look at 100 %."** This sheet is the I and the X.

**Clip Studio Paint EX (Ver. 5 names; older names in brackets):**

- ☐ New canvas in px · for animation set timeline **Image interpolation: Hard edges (nearest neighbor)**
- ☐ View > Grid · Grid/Ruler bar settings: Gap 1 px, divisions 1 · Window > Canvas > New Window at 100 %
- ☐ Pen > Marker group > **Dot pen** (1 px, no AA) · other pens: Advanced Tool Settings [Sub Tool Detail] > Anti-aliasing: **None**
- ☐ Fill: Anti-aliasing off + **Area scaling off** · Auto select: AA off, Color margin 0 · Text: AA off
- ☐ Transform: Interpolation method **Hard edges (nearest neighbor)** — always
- ☐ Colour: Window > Color Set > Edit color sets → Add Color (drop a Lospec 1× PNG on a layer and eyedrop)
- ☐ Scale BEFORE export: Edit > Change Image Resolution, 800 %, Hard edges → Export PNG (transparency on)
- ☐ Animation export: Image sequence (PNG) at 1× for engines · Animated GIF for sharing with **Dithering OFF** · no sprite-sheet export (engines take sequences)

**ibisPaint X:**

- ☐ New canvas → Any Size 32×32 (or Animation)
- ☐ View menu: **Grid** on (Grid 1 Interval 1) · **Display when zooming → Pixelated**
- ☐ Digital Pen 1.0 px · brush parameters > Shape > **Antialias OFF** (eraser too)
- ☐ Bucket: Strength 0 % · Expansion 0 px
- ☐ Transform: Interpolation **Nearest Neighbor (Dot)** · Canvas > Resize: **Nearest Neighbor (Pixel)**
- ☐ Save Image → PNG, Transparent ON · never "Super-resolution x2" · enlarge by Resize, export, keep the 1× original
- ☐ Animation: Save Animation Video to share; save each frame as transparent PNG for a game

**Purpose-built editors (pixel-perfect pencil, indexed palettes, ms timing, tags, sprite sheets):**

- ☐ Free: **Pixelorama** (MIT; desktop + browser) · **LibreSprite** (GPL fork of 2016 Aseprite) · **Piskel** (browser) · **GraphicsGale** (Windows) · **Pixilart** (browser)
- ☐ Paid standard: **Aseprite** $19.99 — or compile the public source yourself for personal use (legal; no redistributing)

**In the engine (pixels stay square):**

- ☐ GODOT: Stretch Mode viewport · Aspect keep · Scale Mode **integer** · Default Texture Filter **Nearest** · Snap 2D Transforms to Pixel
- ☐ UNITY: sprites Filter **Point**, Compression **None**, same PPU · **Pixel Perfect Camera** (Upscale Render Texture / Pixel Snapping)
- ☐ UNREAL: texture → Sprite Actions > **Apply Paper 2D Import Settings** · orthographic camera
- ☐ WEB: `image-rendering: pixelated;` · `ctx.imageSmoothingEnabled = false;`
- ☐ One base resolution, integer-scaled as a whole · snap the camera too

---

*The Living Line · [full guide](../The_Living_Line_Guide.md) · CC BY 4.0 © esorhizome OÜ*
