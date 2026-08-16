# Sheet 14 · Into the Game (Lesson 14)

*Words on this sheet:* **sprite** = a 2D image an engine can draw · **sprite sheet** = frames packed in one grid image · **flipbook** = a playable stack of frames · **fps** = frames per second — a property of your ART (8–12), not the game (60).

**The pipeline (identical in every engine):**

- ☐ Export transparent PNGs (hide the paper layer!)
- ☐ Zero-pad the names: `walk_01.png` … `walk_08.png` (engines sort alphabetically)
- ☐ Same canvas size + consistent pivot for every frame, or the character jitters
- ☐ Group frames per action (idle / walk / head_turn)
- ☐ Set the ANIMATION's fps — on twos = 12
- ☐ Loop cycles · one-shots fire a "finished" event → settle back to idle
- ☐ Crisp pixel art = Nearest/Point filtering · painterly = Linear/Bilinear

**Where things live:**

- ☐ GODOT: AnimatedSprite2D + SpriteFrames · `play("walk")` · `await sprite.animation_finished`
- ☐ UNITY: Sprite Editor (slice) → Animation window (clips) → Animator · `animator.Play("Walk")` · done when `normalizedTime >= 1`
- ☐ UNREAL: Sprite Actions → Extract Sprites → Create Flipbook · `SetFlipbook` + `PlayFromStart` · `OnFinishedPlaying`
- ☐ WEB: `<img src="loop.webp">` · CSS `steps(8)` · canvas `drawImage` player

**Scene fades (Godot, one line):**

- ☐ `await Fade.fade_out(0.8).finished` → change scene → `Fade.fade_in(0.8)`
- ☐ Universal Fade addon: copy folder, done — no autoload, 7 wipe patterns

**The dial that survives:** play-speed = the timing dial, live at runtime —
☐ Godot `speed_scale` ☐ Unity `animator.speed` ☐ Unreal `SetPlayRate` ☐ 0.6 = weary · 1.4 = eager

---

*The Living Line · [full guide](../The_Living_Line_Guide.md) · CC BY 4.0 © esorhizome OÜ*
