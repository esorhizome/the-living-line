# The Living Line

## A Hand-Drawn Animation Guide to Personality, Persona & Appeal

**Standalone lessons for Clip Studio Paint EX (desktop) and ibisPaint X (mobile)**

*August 2026 · Every link in this guide was fetched and checked live on 16 August 2026; the links in Part VII (The Pixel, Lessons 15–18) on 20 August 2026.*

*Licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) © esorhizome OÜ — share and adapt freely, with attribution.*

---

# How This Guide Works (read me first — or never; every lesson survives without me)

This guide makes you six promises, and it keeps them in every single lesson:

1. **Every lesson stands alone.** Open the book anywhere. No lesson ever requires you to remember an earlier one. If a lesson needs an idea, it re-teaches that idea on the spot.
2. **Jargon is re-explained every time it appears.** That is not an accident or padding — it is the design. Each technical word gets the *same short definition in the same wording* everywhere it shows up, because repeated identical phrasing is what makes definitions finally stick. If you ever think "didn't it already tell me this?" — yes, on purpose, and it will again.
3. **Lessons come in short chunks** with a recap box at the end called **"If you only keep three things."** If your attention slides mid-lesson, skip straight to that box. It is a complete miniature of the lesson.
4. **Every lesson ends with tiny drills** for Clip Studio Paint EX and ibisPaint X. One drill is sized for one sitting (roughly 15–25 minutes). You never need to finish a chapter to earn the drill.
5. **One mantra runs through the whole book:**

> **Cause first → body next → loose parts last → settle.**
>
> Animate the thing that causes the motion. Then the main body that carries it. Then the loose things that react (hair, cloth, flames, droplets). Then let everything ease into stillness. Every lesson in this guide is that sentence wearing a different costume.

6. **The pocket mnemonic, for days when even the mantra feels long:**

> **C·B·L·S — "Cool Bodies Lag Softly."**
>
> **C**ause · **B**ody · **L**oose · **S**ettle. Four letters, and the phrase itself describes the physics: a cool (calm) body moves, its loose parts lag, and everything settles softly. If you remember nothing else while drawing, remember these four letters — they are the order you animate *everything*. (Lesson 2 adds a twelve-beat chant for the twelve classic principles, if you want the full deck in your pocket; Part VII adds a second four-letter one for pixel art, **P·I·X·L**.)

## The one idea underneath everything

Personality in animation is not *what* a character does. It is *how the drawings choose to do it.* The same head-turn, drawn with different timing, different curves, and different amounts of lag, can read as shy, smug, alien, dignified, or exhausted — without changing the character design at all.

If you want proof before you invest a single hour: watch Cento Lodigiani's three-minute film *The illusion of life* (link in the bibliography, Lesson 19). It demonstrates every classic animation principle on a plain grey cube — and the cube visibly develops moods. No face. No costume. Just motion choices. That is the power you are here to learn.

## How to use this guide with an easily-derailed memory (a note of respect, not pity)

- **Pick lessons by appetite, not order.** Feeling like fire today? Go straight to Lesson 10. The lesson will hand you every definition it needs.
- **One drill = one sitting.** Decide which drill you'll do *before* you open the app. Opening the app without a decision is how sessions evaporate.
- **The cheat-sheets are the guide's short-term memory.** There is one companion checklist per lesson — nineteen in all, from timing to pixel art — each sized for a phone screenshot or a printout. Print them or keep them on your phone. They exist so this book doesn't have to be re-read to be used.
- **Repetition is a feature you deserve.** Nothing in this guide assumes you remember the previous page. Learning by loops is still learning — it's even rather fitting for an art form made of loops.

## Contents

- **Part I — Foundations**
  - Lesson 1: The Clock and the Handwriting (frames, timing, spacing)
  - Lesson 2: The Twelve Principles, told as personality tools
  - Lesson 3: The Personality Toolkit (shape, silhouette, asymmetry, signatures)
- **Part II — The Four Big Performances**
  - Lesson 4: The Walk Cycle
  - Lesson 5: The Head Turn
  - Lesson 6: Flight
- **Part III — Casting the Body**
  - Lesson 7: Human vs Alien vs Superhuman
  - Lesson 8: Elegance vs Scruffiness
- **Part IV — The Loose and the Living**
  - Lesson 9: Overlap & Follow-Through (hair, clothing, tails)
  - Lesson 10: Animating the Elements (electricity, water, fire, wind)
- **Part V — Your Studio**
  - Lesson 11: Clip Studio Paint EX — the animation workflow
  - Lesson 12: ibisPaint X — the animation workflow
  - Lesson 13: The Practice Program (drills, weekly plan, and free films to study frame by frame)
- **Part VI — Into the Game**
  - Lesson 14: Bringing Your Animation into Games (Godot, Unity, Unreal, and the plain web)
- **Part VII — The Pixel**
  - Lesson 15: The Grid (every pixel is a decision — resolution, clusters, lines, anti-aliasing, outlines)
  - Lesson 16: Colour in Pixels (palettes, ramps, hue-shifting, dither, the recolour trick)
  - Lesson 17: Pixel Animation (sub-pixel motion, frame budgets, idles, walks, smears, the elements in pixels)
  - Lesson 18: The Pixel Studio (Clip Studio Paint EX, ibisPaint X, the free editors, Aseprite, and the road into the game)
- **Part VIII — The Library**
  - Lesson 19: Annotated Bibliography (every link verified, free & legal)
  - Master Glossary (every term in one place, same wording as the lessons)

---

# PART I — FOUNDATIONS

---

# Lesson 1 — The Clock and the Handwriting (Frames, Timing, Spacing)

*Standalone lesson. Everything you need is on this page.*

## What this lesson gives you

The two most fundamental dials in all of animation — **timing** and **spacing** — and how just those two dials, with nothing else, already create weight, mood, and personality.

## Words used in this lesson (fresh definitions, every time)

- **frame** — one single image in an animation. Film traditionally shows 24 frames every second.
- **fps (frames per second)** — how many frames are shown each second. Higher fps = smoother but more drawings.
- **timing** — how many frames an action takes; in other words, how long it lasts.
- **spacing** — how far the drawing moves between one frame and the next.
- **key drawing** — one of the main storytelling drawings of an action; everything else exists to connect the keys.
- **inbetween** — a drawing that fills the gap between two key drawings.
- **slow in and slow out** (also called *easing*) — bunching drawings close together at the start and end of a move, so it eases into motion and eases back out instead of starting and stopping like a machine.
- **animating "on ones" / "on twos"** — on ones = a new drawing on every frame (24 drawings per second at 24 fps). On twos = each drawing is held for 2 frames (12 drawings per second). Most hand-drawn animation lives happily on twos.
- **cycle** — a set of drawings that loops seamlessly; the last drawing flows back into the first.

## Timing and spacing are two different dials

They get confused because they live inside the same stack of drawings, so here is the cleanest split:

- **Timing answers: HOW LONG?** An action that takes 6 frames is fast. The same action across 30 frames is slow. Timing is the clock.
- **Spacing answers: HOW FAR EACH STEP?** Across those frames, does the drawing move in even steps? Tiny steps that grow huge? Huge steps that shrink to a feather-soft stop? Spacing is the handwriting — the texture of the movement.

> **Pin this:** Timing is the clock. Spacing is the handwriting. Two actions can take the *same number of frames* and feel utterly different because the distance travelled per frame is distributed differently.

## The bouncing ball: personality from nothing

The classic first exercise in every animation course — including Pixar's free lessons on Khan Academy — is a bouncing ball, and it's the fastest proof that timing + spacing alone create character.

Draw a ball falling and bouncing:

- **Even spacing** (same distance every frame): the ball floats like it's on a conveyor belt. Mechanical. Dead.
- **Bunched at the top of the arc, wide near the ground:** now it hangs weightless for a moment, then accelerates and *smacks* the floor. Gravity appears. Weight appears.
- **Wide bounces that decay into small ones:** the ball is losing energy — it feels rubbery and real.
- Now shrink the whole performance: **tight little bounces, quick timing** → a nervous ping-pong ball. **Long slow arcs, heavy landing** → a weary bowling ball. Same circle. Different soul.

No face was drawn. Timing and spacing did all the acting. Keep that lesson forever: *before* you reach for expressions or costumes, your motion is already talking.

## Slow in, slow out — the courtesy of living things

**Slow in and slow out** (reminder: bunching drawings at the start and end of a move so it eases in and out) exists because real bodies have mass. Muscles ramp up; momentum ramps down.

- Generous easing at both ends → calm, deliberate, confident, graceful.
- No easing at all — full speed on frame one, dead stop at the end → mechanical, robotic, unsettling, alien. (Useful! Lesson 7 weaponises exactly this.)
- Easing only *out* of a sudden start → startled, reactive, jumpy.

## Ones, twos, and honest budgets

At 24 fps, animating **on ones** (a new drawing every frame) means 24 drawings per second — silky, and exhausting. Animating **on twos** (each drawing held 2 frames) means 12 drawings per second, which is the traditional backbone of hand-drawn animation and reads beautifully. You can mix them: hold calm moments on twos, drop to ones for a fast flourish.

Beginner-friendly budget: set your app to **12 fps and draw one drawing per frame** — that's the same rhythm as 24 fps on twos, with simpler arithmetic. (Lessons 11 and 12 show exactly where the fps setting lives in Clip Studio Paint EX and ibisPaint X.)

## The personality dial for this lesson

| Choice | Reads as |
|---|---|
| Quick timing (few frames per action) | alert, nervous, young, energetic, comic |
| Slow timing (many frames) | heavy, calm, weary, grand, powerful |
| Even, cushioned spacing | composed, elegant, controlled |
| Jumpy, irregular spacing | jittery, panicky, scrappy, chaotic |
| No easing anywhere | robotic, eerie, inhuman |
| Deep easing everywhere | dreamy, floaty, luxurious |

## Try it — Clip Studio Paint EX

Make a new **Animation** project (File > New, set Project to *Animation*; the frame rate box is right there — choose 12 fps, 24 frames = 2 seconds). Draw a ball dropping and bouncing across 12–24 frames using the four-spacing experiment above. Turn on **onion skin** (a ghost view of the frames before and after the one you're drawing — Animation menu > Show animation cels > Onion skin settings) so you can *see* your spacing as you place each drawing. Loop the playback.

## Try it — ibisPaint X

Open a canvas, open the **Animation bar** (ibisPaint's frame strip along the bottom of the canvas), add frames with the **+** button, and draw the same bouncing ball with onion skin turned on (it shows past/future frames as ghosts; you can adjust how many and how faint). Set fps in the frame settings; play on Loop. Phone-sized screens love this drill — the ball reads at any size.

## If you only keep three things

1. **Timing = how long (the clock). Spacing = how far per frame (the handwriting).**
2. Even spacing feels mechanical; bunched-then-wide spacing creates weight and gravity.
3. A plain ball with good timing and spacing already has a personality — motion acts before design does.

## Sources for this lesson (all free & legal; details in Lesson 19)

- Khan Academy × Pixar, *Pixar in a Box — Animation unit*: https://www.khanacademy.org/computing/pixar/animate
- Adobe, *12 Principles of Animation*: https://www.adobe.com/creativecloud/animation/discover/principles-of-animation.html
- Cento Lodigiani, *The illusion of life* (short film): https://vimeo.com/93206523
- AlanBeckerTutorials, *12 Principles of Animation* (full series video): https://www.youtube.com/watch?v=uDqjIdI4bF4

---

# Lesson 2 — The Twelve Principles, Told as Personality Tools

*Standalone lesson. Everything you need is on this page.*

## What this lesson gives you

The famous "12 principles of animation" — but framed the way this whole guide frames everything: not as rules to obey, as *levers that change who your character seems to be.*

## Where they come from (30 seconds of history)

Two of Disney's legendary veteran animators, **Frank Thomas and Ollie Johnston**, distilled the studio's 1930s discoveries into twelve principles in their 1981 book *The Illusion of Life: Disney Animation*. The principles are not laws of physics — they are a toolkit for making drawn things feel alive, and every one of them doubles as a personality dial.

## Words used in this lesson (fresh definitions, every time)

- **frame** — one single image in an animation; film traditionally shows 24 per second.
- **timing** — how many frames an action takes; how long it lasts.
- **spacing** — how far the drawing moves between one frame and the next.
- **silhouette** — the solid-black outline shape of a pose; if an action reads in silhouette, it reads, full stop.
- **key drawing** — one of the main storytelling drawings; the rest connect the keys.
- **inbetween** — a drawing that fills the gap between two key drawings.

## The twelve, one by one

**1 · Squash and stretch.** Letting a form flatten under impact (squash) and lengthen with speed (stretch) while keeping its volume the same — a ball flattens on the floor, stretches as it falls. *Personality lever:* lots of squash and stretch = bouncy, elastic, comic, young. Almost none = stiff, dignified, tough, or robotic.

**2 · Anticipation.** A small preparatory move in the opposite direction before the main action — the crouch before the jump, the arm drawing back before the throw. It tells the audience *something is about to happen.* *Personality lever:* big wind-ups read theatrical or comic; tiny ones read controlled and professional; **zero anticipation reads inhuman** — which is exactly how you'll animate certain aliens in Lesson 7.

**3 · Staging.** Presenting an action so it reads instantly — clear silhouette (the solid-black outline shape of the pose), clear framing, one idea at a time. *Personality lever:* how you stage a character is how the audience is told to feel about them — loom them large and low-angle for menace, tuck them small in a corner for loneliness.

**4 · Straight-ahead action and pose-to-pose.** Two ways of working. **Straight ahead** = draw frame 1, then 2, then 3, discovering the motion as you go — great for fire, water, wild energy. **Pose to pose** = plan the key drawings (the main storytelling drawings) first, then fill the gaps with inbetweens — great for control and acting. *Personality lever:* straight-ahead sections feel alive and unpredictable; pose-to-pose sections feel deliberate and composed. Most animators mix both.

**5 · Follow-through and overlapping action.** **Follow-through:** loose parts — hair, cloth, tails, flesh — keep moving after the body stops. **Overlapping action:** different parts start and stop at slightly different times, never all at once. *Personality lever:* this pair is the difference between a living body and a cardboard cut-out; Lesson 9 is an entire chapter on it.

**6 · Slow in and slow out.** Bunching drawings close together at the start and end of a move so it eases in and out instead of starting and stopping like a machine. *Personality lever:* deep easing = graceful, heavy, calm; no easing = mechanical, eerie, or superhumanly precise.

**7 · Arcs.** Almost every natural motion travels along a curved path — a swinging arm, a turning head, a thrown ball. Straight-line motion reads mechanical. *Personality lever:* long smooth arcs = elegance; broken, jagged paths = chaos, panic, wrongness.

**8 · Secondary action.** A smaller supporting action layered on the main one — whistling while walking, fiddling with a sleeve while talking. It adds character *without stealing focus from the main action.* *Personality lever:* secondary actions are practically a diary of who the character is; a nervous hair-twirl says more than a paragraph of dialogue.

**9 · Timing.** How many frames an action takes — how long it lasts. Fewer frames = faster; more frames = slower. *Personality lever:* the same gesture done quick reads eager or twitchy; done slow it reads weary or grand. Timing *is* mood.

**10 · Exaggeration.** Pushing an idea past real life so it reads clearly from across the room. Not lying — clarifying. *Personality lever:* how much you exaggerate sets the whole register of the character, from naturalistic drama to full cartoon.

**11 · Solid drawing.** Drawing forms so they feel three-dimensional and consistent — with weight, volume, and structure — from any angle. *Personality lever:* solid, weighted drawing makes even a fantasy creature feel credible; deliberately flimsy drawing can make a character feel frail or comic.

**12 · Appeal.** The charisma of a drawing or motion — how watchable it is. Crucially, appeal does **not** mean "cute" or "nice": villains and monsters can drip with appeal. A useful split (from Animation Mentor's essay on the topic): appeal = **order** (clarity, believability, readable shapes) + **interest** (variation, surprise, asymmetry). *Personality lever:* appeal is the sum of all the other levers pulled with intention.

## The twelve as a chant (memory aid, ADHD-honest)

Acronyms for these twelve are famously useless (the initials spell nothing). A *chant* sticks better — twelve beats, in order, each word echoing its principle:

> **Squish · wind-up · stage it · plan-or-don't ·**
> **lag · ease · curve · fidget ·**
> **clock it · push it · weigh it · charm.**

That is: **squash & stretch** (squish) → **anticipation** (wind-up) → **staging** (stage it) → **straight-ahead vs pose-to-pose** (plan-or-don't) → **follow-through & overlap** (lag) → **slow in & slow out** (ease) → **arcs** (curve) → **secondary action** (fidget) → **timing** (clock it) → **exaggeration** (push it) → **solid drawing** (weigh it) → **appeal** (charm). Say it a few times while the kettle boils; it files itself away on its own.

## Watch the whole toolkit in three minutes

Cento Lodigiani's short *The illusion of life* performs all twelve principles on a plain grey cube, and the cube becomes a *character*. Then, when you have an evening, Alan Becker's free video series walks through each principle with drawn examples. Both links below.

## If you only keep three things

1. The twelve principles come from Disney's Frank Thomas & Ollie Johnston (*The Illusion of Life*, 1981) — and they are levers, not laws.
2. Every principle is secretly a personality dial: the *amount* of squash, anticipation, easing, or exaggeration is a casting decision.
3. Appeal = order + interest — clarity plus surprise — and villains can have heaps of it.

## Sources for this lesson (all free & legal; details in Lesson 19)

- Wikipedia, *Twelve basic principles of animation*: https://en.wikipedia.org/wiki/Twelve_basic_principles_of_animation
- AlanBeckerTutorials, *12 Principles of Animation* (full series): https://www.youtube.com/watch?v=uDqjIdI4bF4
- Cento Lodigiani, *The illusion of life*: https://vimeo.com/93206523
- Animation Mentor blog, *Appeal: The 12 Basic Principles of Animation*: https://www.animationmentor.com/blog/appeal-the-12-basic-principles-of-animation/
- Adobe, *12 Principles of Animation*: https://www.adobe.com/creativecloud/animation/discover/principles-of-animation.html
- Preston Blair, *Advanced Animation* (public-domain book scan): https://archive.org/details/advanced-animation-by-preston-blair

---

# Lesson 3 — The Personality Toolkit (Shape, Silhouette, Asymmetry, Signatures)

*Standalone lesson. Everything you need is on this page.*

## What this lesson gives you

The design-side dials that work hand in hand with motion: what a character's shapes, outline, posture, and repeated habits tell an audience before a single word is spoken.

## Words used in this lesson (fresh definitions, every time)

- **silhouette** — the solid-black outline shape of a pose; if an action reads in silhouette, it reads, full stop.
- **line of action** — the single imaginary curve running through a pose from feet to head, giving it energy and direction.
- **shape language** — the use of basic forms (circles, squares, triangles) to signal character before any motion happens.
- **timing** — how many frames an action takes; how long it lasts.
- **asymmetry** — making the left and right sides of a pose or motion deliberately unequal.
- **contrapposto** — the natural stance where weight rests on one leg, tilting hips one way and shoulders the other.
- **secondary action** — a smaller supporting action layered on the main one (a hum, a sleeve-fiddle) that adds character without stealing focus.

## Shape language: the audience reads geometry first

Long before motion, viewers read shapes — and they read them fast:

- **Circles** → soft, friendly, approachable, childlike. (Round cheeks, round bodies, round hands.)
- **Squares** → sturdy, dependable, stubborn, immovable. (Blocky jaws, brick torsos.)
- **Triangles** → sharp, dynamic, dangerous, cunning. (Pointed chins, wedge shoulders, spiky hair.)

Real designs mix all three; the *dominant* shape sets the first impression, and your animation can then confirm it or delightfully betray it (a triangle-shaped assassin who moves like a bouncy circle is instantly memorable).

## Silhouette: the two-second test

**Silhouette** (reminder: the solid-black outline shape of a pose) is the fastest quality check in animation. Fill your drawing with black. Can you still tell what's happening — who's reaching, cowering, strutting? If yes, the pose reads. If the silhouette is a mud-blob, no amount of pretty rendering will save it. Check silhouettes on key drawings *especially* on a phone screen, where ibisPaint work will actually be watched.

## Line of action: one curve, one attitude

The **line of action** (reminder: the single imaginary curve running through a pose) is posture distilled. A proud C-curve arching back reads confident. A collapsed forward C reads defeated or sneaky. A straight vertical line reads stiff, formal, or robotic. Before detailing any key drawing, draw this one curve first — it is the pose's personality in a single stroke. (Preston Blair's public-domain book, linked below, has a wonderful section literally titled "Line of Action in Animation.")

## Asymmetry: the difference between alive and laminated

**Perfect symmetry kills believability** — that's a near-direct quote from School of Motion's list of the most common beginner mistakes. Living bodies are never perfectly mirrored: weight sits on one leg (**contrapposto** — hips tilt one way, shoulders counter-tilt the other), one arm swings a little wider, one eyebrow works harder. When you *want* stiff — a soldier at attention, an android, a porcelain aristocrat — symmetry is exactly the tool. Otherwise, break it everywhere, gently.

## Motion signatures: the Milt Kahl Head Swaggle

Legendary Disney animator Milt Kahl had a trademark move that animation folk affectionately call the **head swaggle**: a quick side-to-side rattle of the head he gave characters *specifically when they were feeling cocky or self-assured* — Tigger, Little John in *Robin Hood*, Shere Khan in *The Jungle Book*. One repeatable gesture, deployed at the right emotional moments, became a personality trademark (and a quiet flex of 3D draftsmanship — rattling a head in perspective is hard).

Steal the *strategy*, not the move: give your character one signature motion habit — a particular way of flicking hair, planting feet, tilting the chin before speaking. Repetition of a distinctive choice is how audiences learn who someone is.

## The four questions (ask them of every action you animate)

1. **What causes this motion?** (Muscle? Wind? Magic? Impact?)
2. **What leads?** (Eyes? Hips? Chest? A pointing hand?)
3. **What lags?** (Hair, sleeves, bellies, capes — the loose parts.)
4. **What does the timing say?** (Reminder: timing = how many frames it takes. Quick = eager or nervous; slow = heavy or grand.)

Answer those four and the personality choices practically make themselves.

## If you only keep three things

1. Audiences read shapes first (circle-soft, square-sturdy, triangle-sharp), silhouettes second, motion third — design and animation should agree (or disagree *on purpose*).
2. Asymmetry is life: weight on one leg, unequal arms, one working eyebrow. Symmetry is a special effect reserved for the stiff, the formal, and the inhuman.
3. Give every character one signature move — their own "head swaggle" — and spend it at emotionally right moments.

## Sources for this lesson (all free & legal; details in Lesson 19)

- Winged Canvas, *Shape Language In Character Design* (video): https://www.youtube.com/watch?v=v6n9OYtaWZs
- Chelsea Gracei, *How to Use SHAPES to Create Character Designs* (video): https://www.youtube.com/watch?v=GbG45s1EZvo
- School of Motion, *New to 2D Character Animation? The Most Common Mistakes*: https://schoolofmotion.com/blog/new-to-2d-character-animation-here-are-the-most-common-mistakes-and-how-to-avoid-them
- Michael Ruocco (Cartoon Brew), *The Milt Kahl Head Swaggle*: https://www.cartoonbrew.com/disney/the-milt-kahl-head-swaggle-80861.html
- Animation Mentor blog, *Appeal: The 12 Basic Principles of Animation*: https://www.animationmentor.com/blog/appeal-the-12-basic-principles-of-animation/
- Preston Blair, *Advanced Animation* (public-domain scan; see "Line of Action in Animation"): https://archive.org/details/advanced-animation-by-preston-blair
- Winsor McCay, *Gertie the Dinosaur* (1914, public domain — personality with zero dialogue): https://archive.org/details/gertiethe-dinosaur-512kb

---

# PART II — THE FOUR BIG PERFORMANCES

---

# Lesson 4 — The Walk Cycle

*Standalone lesson. Everything you need is on this page.*

## What this lesson gives you

The complete anatomy of a walk cycle — the poses, the frame counts, the body mechanics — and then the real prize: the walk as a *personality machine*, where every dial you turn recasts the character.

## Words used in this lesson (fresh definitions, every time)

- **cycle** — a set of drawings that loops seamlessly; the last drawing flows back into the first.
- **frame** — one single image in an animation; film traditionally shows 24 per second.
- **timing** — how many frames an action takes; how long it lasts.
- **spacing** — how far the drawing moves between one frame and the next.
- **key drawing** — one of the main storytelling drawings of an action; the rest connect the keys.
- **inbetween** — a drawing that fills the gap between two key drawings.
- **animating "on twos"** — holding each drawing for 2 frames (12 drawings per second at 24 fps) — the traditional hand-drawn rhythm.
- **squash and stretch** — letting a form flatten under impact and lengthen with speed, while keeping its volume the same.
- **arc** — the curved path almost every natural motion travels along.
- **line of action** — the single imaginary curve running through a pose, giving it energy and direction.
- **counter-rotation** — hips twist one way, shoulders twist the other; the body's natural balancing twist.
- **drag** — a trailing part lags behind because its base moved first.
- **follow-through** — loose parts (hair, cloth, tails) keep moving after the body stops.
- **onion skin** — a ghost view of the frames before/after the one you're drawing.

## What a walk actually is

A walk is **controlled falling**. The body tips forward off one leg, begins to fall, and the other leg swings round to catch it — over and over. That's why walks are believable only when weight is believable: every step is a small rescue.

A **walk cycle** (reminder: a seamlessly looping set of drawings) animates one full stride — left step plus right step — that repeats forever. The character walks "on the spot" like on a treadmill; the background slides past.

## The four cornerstone drawings

Different teachers use slightly different names — you'll see all of these in the sources — but the mechanics are identical. For one step (say, the left foot stepping forward):

1. **CONTACT** — the moment both feet touch the ground: front heel just landing, back toe about to push off, legs scissored at their widest. Arms at their widest swing too (opposite arm forward — more below). Veteran 2D teacher Dermot O'Connor says the contact pose "determines 80 % of the walk" — it *is* the walk's attitude in one drawing.
2. **DOWN** (some call it *recoil*) — the body's lowest point. The front knee bends as it absorbs the landing; weight fully arrives. This is the walk's **squash** moment (reminder: squash = the form compressing under force). Heaviness lives here.
3. **PASSING** — the free leg swings past the planted leg; the body starts rising; the planted leg is straightish under the hips.
4. **UP** (some call it *high point*) — the highest point: the planted foot's toes push the body up and forward, about to tip into the next fall. This is the **stretch** moment, and where bounce or spring lives.

Then the same four again on the other side: **8 key drawings per full cycle**. (Adobe's beginner guide calls an 8-drawing cycle "the standard.")

## Frame counts you can actually use

- **Starter recipe:** 8 drawings, each held 2 frames (**on twos**) at 24 fps = a 16-frame cycle — a brisk, cheerful walk of about ⅔ of a second per full stride.
- **Dermot O'Connor's worked example:** 12 drawings at 12 fps = a one-second cycle. His layout: frame 1 contact → frame 2 recoil/down → frame 5 high point → frame 7 the opposite contact → frames 8–12 mirror the first half.
- **Animation Mentor's guidance:** a typical relaxed walk runs roughly 20–30 frames at 24 fps per full left-right cycle (about 12–16 frames per single step).
- Rule of thumb: **fewer frames = busier, snappier, smaller creature; more frames = heavier, calmer, larger creature.** (That's timing — how many frames an action takes — doing its personality work.)

## What the rest of the body is doing

- **Hips** lead the weight story: they drop toward the Down, rise toward the Up, and tilt side to side as each leg takes the load.
- **Shoulders counter-rotate** (reminder: hips twist one way, shoulders twist the other). When the left leg swings forward, the left hip comes forward and the *right* shoulder and arm swing forward to balance it.
- **Arms swing opposite the legs**, and they are chains, not paddles: the upper arm leads, the forearm lags a touch, the hand lags more (that lag is **drag** — a trailing part left behind because its base moved first). Loose hands flop slightly at the top of each swing.
- **The head bobs** gently with the body's rise and fall — a little behind the body's beat, not welded to it. Too still = eerie or ultra-formal; too bouncy = goofy or shaken.
- **Everything travels on arcs** (reminder: the curved paths natural motion follows): the head bobs along a shallow wave, hands swing along curves, even the hips trace a figure-8-ish path.
- **Hair, coat hems, bellies, tails** trail the whole affair and keep moving a beat after each footfall (**follow-through** — loose parts continuing after the body stops or changes direction). Lesson 9 goes deep on this.

## The walk as a personality machine

Here is the entire reason walks are worth obsessing over. Hold the *mechanics* fixed and turn these dials:

| Dial | Turn it down | Turn it up |
|---|---|---|
| Stride length | timid, frail, sneaky | confident, brash, striding hero |
| Tempo (timing) | weary, grand, cautious | eager, nervous, busy little legs |
| Depth of DOWN | light, floaty, dainty | heavy, tired, carrying the world |
| Height of UP | shuffling, defeated | bouncy, cocky, musical-number joy |
| Head bob | poised, icy, dignified | goofy, giddy, unhinged |
| Arm swing | reserved, shy, cold | swaggering, theatrical |
| Posture / line of action (that single energy-curve through the pose) | slumped C = tired, sad, sly | proud back-arch = pompous, heroic |
| Symmetry | (asymmetric) natural, quirky, human | (symmetric) military, mechanical, uncanny |

Classic personality walks, as recipes:

- **Confident / cocky:** long stride, strong Up, chest leading the line of action, head high with minimal bob, wide relaxed arm swing. (Preston Blair's public-domain book literally includes "The Strut.")
- **Shy:** short stride, shallow Up, shoulders curled in, head down, arms barely swinging, elbows tucked.
- **Tired / heavy:** deep long Down, slow timing, feet barely clearing the ground, arms hanging, head drooping a beat behind every step.
- **Sneak:** from Animation Mentor's sneak-walk tutorial — knees stay bent and *never fully straighten*, contacts land on tiptoe, quick foot lifts but slow deliberate landings, and symmetry is deliberately broken (one arm held straight, the other bent; eyes down, watching foot placement). Blair's book has "The Sneak" too.
- **Eager / bouncy:** high Up pose, quick timing, springy squash-and-stretch through the whole body, almost skipping.

> **Pin this:** you can re-cast a character without redrawing them. Change only the walk's dials and the audience meets a different person.

## Common walk mistakes (all fixable)

1. **Foot sliding** — the planted foot must stay nailed to the same spot (or glide backwards at a perfectly constant rate in a treadmill-style cycle). Check it with onion skin (the ghost view of neighbouring frames).
2. **Floating** — no Down pose, so no weight. Deepen the Down; let the knee really bend.
3. **Perfect mirroring** — left step identical to right step reads robotic. Vary something small.
4. **Everything moving at once** — animate hips and legs first, then torso and shoulders, then head, then arms, then hair/cloth. (The guide's mantra: *cause first → body next → loose parts last → settle.*)
5. **Straight-line paths** — heads and hands bobbing in straight lines instead of arcs.

## Walk vs run (a one-box detour)

A **run** is not a fast walk: in a walk one foot is *always* on the ground; in a run there is an **airborne moment when both feet leave the ground**. Runs lean the whole body forward, stretch the stride, pump the arms, and often drop to fewer, punchier drawings. If your "fast walk" looks wrong, you may be asking it to be a run.

## Try it — Clip Studio Paint EX

New Animation project (File > New → Project: *Animation*), 24 fps, 16-frame timeline. In an animation folder, draw the two CONTACT drawings first (frames 1 and 9) — remember, contact carries 80 % of the attitude. Add Down, Passing, Up between them using **onion skin** (Animation menu > Show animation cels > Onion skin settings). Use the **light table** (Animation cels palette — it lets you pin reference drawings under your working cel) when inbetweening. Loop playback obsessively; watch the feet for sliding.

## Try it — ibisPaint X

Modest canvas (phone-friendly), Animation bar open, 8 frames at 8–12 fps. Draw the 8 cornerstone drawings only — no inbetweens — one per frame: Contact, Down, Passing, Up, Contact, Down, Passing, Up. Onion skin on. Play on Loop. An 8-drawing walk with strong poses beats a 24-drawing walk with mushy ones, especially at phone size where **silhouette** (the solid-black outline shape of the pose) does all the talking.

## Drills (one sitting each)

1. **Neutral walk:** 8 drawings, on twos. Just make it loop without sliding.
2. **Recast it twice:** copy the project; turn dials only (stride, tempo, Down-depth, posture) to make (a) exhausted, (b) cocky. Do not redraw the character design.
3. **The 80 % test:** draw ONLY two contact poses of a sneak. Show someone. Can they name the attitude from two drawings?

## If you only keep three things

1. A walk is controlled falling: **Contact → Down → Passing → Up**, twice per cycle (8 key drawings; ~16 frames on twos at 24 fps).
2. The Down pose is where weight lives; the Up pose is where spring lives; the Contact pose is where *attitude* lives.
3. Walks are personality machines — stride, tempo, bob, posture, and symmetry are casting decisions, not physics.

## Sources for this lesson (all free & legal; details in Lesson 19)

- Dermot O'Connor (Angry Animator), *Tutorial #2: Walk Cycle* (via the Internet Archive's Wayback Machine — the original site retired its free articles in a 2026 rebuild): https://web.archive.org/web/20230814111643/https://www.angryanimator.com/word/2010/11/26/tutorial-2-walk-cycle/
- Animation Mentor blog, *Tutorial: Animating a Basic Human Walk Cycle*: https://www.animationmentor.com/blog/tutorial-animating-human-walk-cycle/
- Animation Mentor blog, *Tutorial: Animating a Sneak Walk Cycle with Personality*: https://www.animationmentor.com/blog/tutorial-animating-sneak-walk-cycle-with-personality/
- Adobe, *What Is an Animated Walk Cycle and How Can I Make One?*: https://www.adobe.com/creativecloud/animation/discover/animation-walk-cycle.html
- School of Motion, *Walk Cycle Reference: The Ultimate List for Animators*: https://schoolofmotion.com/blog/walk-cycle-reference-ultimate-list-for-animators
- Aaron Blaise, *Animating a Walk* (video): https://www.youtube.com/watch?v=5bUZc45wtXw
- Preston Blair, *Advanced Animation* (public-domain scan — see "The Walk," "The Strut," "The Sneak"): https://archive.org/details/advanced-animation-by-preston-blair

---

# Lesson 5 — The Head Turn

*Standalone lesson. Everything you need is on this page.*

## What this lesson gives you

The head turn is a two-second acting scene disguised as a mechanical exercise. This lesson gives you its full sequence — thought, anticipation, arc, overshoot, settle, follow-through — and the dials that turn one head-turn into a dozen different people.

## Words used in this lesson (fresh definitions, every time)

- **frame** — one single image in an animation; film traditionally shows 24 per second.
- **timing** — how many frames an action takes; how long it lasts.
- **spacing** — how far the drawing moves between one frame and the next.
- **anticipation** — a small preparatory move (often in the opposite direction) before the main action — the wind-up before the pitch.
- **arc** — the curved path almost every natural motion travels along.
- **overshoot and settle** — the motion goes slightly past its target, then eases back into place.
- **follow-through** — loose parts (hair, earrings, collars) keep moving after the head stops.
- **overlapping action** — different parts start and stop at slightly different times, never all at once.
- **slow in and slow out** — bunching drawings at the start and end of a move so it eases in and out rather than starting/stopping like a machine.
- **smear** — a deliberately stretched or multiplied drawing shown for just a frame or two to sell extreme speed.
- **key drawing** — one of the main storytelling drawings; the rest connect the keys.
- **breakdown** — the drawing between two keys that decides *how* the motion travels (its path and character), not just where it ends.

## Why a head turn is acting

A head turn happens because of a *thought* — something caught the character's attention. The audience must feel that thought arrive **before** the head moves. That's why a head turn is never "rotate object 90 degrees": it is a tiny story with a beginning (noticing), a middle (turning), and an end (arriving and reacting).

## The full sequence, beat by beat

For a turn from screen-left to screen-right:

1. **The eyes dart first.** Eyes are faster than heads — a couple of frames ahead. This is the thought becoming visible. (It's also **overlapping action**: parts moving at different times, never all at once.)
2. **Anticipation.** (Reminder: a small preparatory move before the main action.) The head dips slightly, or eases a hair *away* from the target, or the chin tucks. It can be tiny — two or three frames — but it announces "here we go." How big you make it is a personality decision; see the dials below.
3. **The turn itself, on an arc.** (Reminder: natural motion travels curved paths.) The nose must not slide in a straight line — trace it and it should draw a shallow rainbow or a gentle U. The classic, beautiful version: the head **dips down through the middle of the turn** (chin drops slightly at the halfway point, then rises to the new position). Draw the **breakdown** — the middle drawing that decides the path — with that dip. Bunch drawings at the start, stretch them wide mid-turn (fast), bunch again approaching the end (that's slow in and slow out — easing at both ends).
4. **A blink, mid-turn (optional but magic).** Real heads blink during turns; a blink on the fastest frames also hides the biggest drawing changes and makes the turn feel effortless.
5. **Overshoot and settle.** (Reminder: go slightly past the target, then ease back.) The head rotates a few degrees beyond its destination for a frame or two, then relaxes back. Skip this and the head "docks" like a machine part.
6. **Follow-through arrives late.** (Reminder: loose parts keep moving after the body stops.) Hair swings, earrings pendulum, collars shift — starting a beat after the head begins, and settling a beat after the head stops. The jaw can even lag a frame on a fast turn.

## Timing recipes

- **Languid, thoughtful turn:** 18–30 frames, deep easing both ends, soft overshoot, long soft hair settle.
- **Standard conversational turn:** 8–12 frames, modest anticipation, small overshoot.
- **Snap turn (alarm!):** big anticipation (the wind-up sells the speed), then the turn in 3–5 frames — often with a **smear** (a stretched or multiplied drawing shown for a single frame to sell extreme speed) — then a hard stop with a strong overshoot and a quick settle. School of Motion's anticipation essay has the rule: **the bigger the anticipation, the bigger the action reads.**

## The personality dials

| Choice | Reads as |
|---|---|
| Long ease, small overshoot, quiet hair | elegant, dignified, composed |
| Uneven timing, big overshoot, hair everywhere | scruffy, flustered, endearing mess |
| Eyes lead early + slow head | curious, dreamy, cautious |
| Huge anticipation + snap turn | comic alarm, melodrama |
| Tiny anticipation + fast precise turn, minimal settle | trained, dangerous, professional |
| **No anticipation at all**, constant-speed turn, dead stop | uncanny, mechanical, *alien* (Lesson 7 uses this deliberately) |
| Eyes do NOT lead — head turns first, eyes catch up last | deeply wrong, haunted, possessed (a superb horror trick) |
| A cocky little side-to-side rattle after arriving | swagger — the famous "Milt Kahl head swaggle," a signature Disney flourish reserved for characters feeling full of themselves |

## Try it — Clip Studio Paint EX

New Animation project, 24 fps, ~24 frames. Keep the head simple — a Preston-Blair-style construction (ball for the skull + a muzzle/jaw shape) so redrawing angles stays cheap; his public-domain book's "Construction of the Head" pages are ideal warm-up copying material. Key drawings: start pose → anticipation → mid-turn breakdown (with the chin-dip) → arrival → overshoot → settle. Use **onion skin** (the ghost view of neighbouring frames: Animation menu > Show animation cels > Onion skin settings) to check the nose's arc — actually plot its path with a dot per frame on a scratch layer. Then add hair on its *own* animation folder, one to two frames behind the head throughout.

## Try it — ibisPaint X

6–8 frames, 8–12 fps. Frame plan: (1) resting, eyes forward → (2) eyes darted toward target → (3) small anticipation dip → (4) mid-turn, chin dipped, maybe a blink → (5) arrived, slightly overshot → (6) settled, hair still drifting → optional (7–8) hair finishing. Duplicate the previous frame each time (long-press a frame on the Animation bar for frame options) and redraw only what changed — the mobile-friendly way to keep volumes consistent. Play on Loop; if it reads at phone size, it reads.

## Drills (one sitting each)

1. **The arc plot:** animate any 8-frame turn, then dot the nose position on every frame. If the dots make a straight line, redo the middle drawings until they curve.
2. **Same turn, three castings:** identical start and end poses; change only timing, anticipation size, and settle to produce (a) dignified, (b) panicked, (c) haunted (eyes last!).
3. **The swaggle:** after any completed turn, add a two-frame side-to-side rattle at the end. Watch smugness appear from nowhere.

## If you only keep three things

1. Sequence: **eyes → anticipation → arced turn (chin dips mid-way) → overshoot → settle → hair last.** Never everything at once.
2. The nose draws a curve, not a line; bunch drawings at both ends of the turn (slow in, slow out — easing into and out of the move).
3. Anticipation size + settle softness = the casting sheet: big/loose is comic, small/crisp is dangerous, absent is alien.

## Sources for this lesson (all free & legal; details in Lesson 19)

- BaM Animation, *Animating a Head Turn: The Important Exercise Everyone Forgets!* (video): https://www.youtube.com/watch?v=3Mik2Gcrq-g
- AMB Animation Academy, *How to Animate a Head Turn – 2D Animation Tutorial* (video): https://www.youtube.com/watch?v=iDagC_BZrCA — and the software-agnostic companion: https://www.youtube.com/watch?v=IpurGrHTnMY
- Toniko Pantoja, *Head Turn Around* (annotated boards on his own site): https://www.tonikopantoja.com/head-turn — plus his general tips page: https://www.tonikopantoja.com/tips
- Michael Ruocco (Cartoon Brew), *The Milt Kahl Head Swaggle*: https://www.cartoonbrew.com/disney/the-milt-kahl-head-swaggle-80861.html
- School of Motion, *Understanding the Principles of Anticipation*: https://schoolofmotion.com/blog/understanding-the-principles-of-anticipation
- Preston Blair, *Advanced Animation* (public-domain scan — "Construction of the Head"): https://archive.org/details/advanced-animation-by-preston-blair

---

# Lesson 6 — Flight

*Standalone lesson. Everything you need is on this page.*

## What this lesson gives you

How to animate things that fly — birds, superheroes, fairies, and stranger beings — by answering one question first: **what is holding this creature up?** Every flight style is an answer to that question, and every answer casts a different character. (Swimmers live here too: water is just thick sky, and the section near the end shows how every flight rule translates.)

## Words used in this lesson (fresh definitions, every time)

- **timing** — how many frames an action takes; how long it lasts.
- **spacing** — how far the drawing moves between one frame and the next.
- **arc** — the curved path almost every natural motion travels along.
- **squash and stretch** — letting a form flatten under compression and lengthen with speed, keeping its volume the same.
- **anticipation** — a small preparatory move before the main action (the crouch before the leap).
- **follow-through** — loose parts (capes, hair, feathers) keep moving after the body stops or changes direction.
- **overlapping action** — different parts start and stop at slightly different times, never all at once.
- **drag** — a trailing part lags behind because its base moved first.
- **cycle** — a set of drawings that loops seamlessly.
- **slow in and slow out** — bunching drawings at the start and end of a move so it eases rather than snapping.
- **smear** — a stretched or multiplied drawing shown for a frame or two to sell extreme speed.

## First question: what holds them up?

- **Wings pushing air** → flight is *work*. You'll animate effort, rhythm, and recovery.
- **Raw power** (superhero thrust) → flight is *velocity management*. You'll animate momentum, banking, and controlled stops.
- **Magic / ignoring physics** (fairies, ghosts, certain aliens) → flight is *a rule-set you invent*. You'll animate consistency inside strange rules.

Decide before drawing frame one. The audience can't see lift, but they can absolutely see whether *you* knew.

## Wings: the mechanics (birds, dragons, winged anything)

From Animation Mentor's bird-flight tutorial and Aaron Blaise's wing-mechanics lesson (both free, linked below):

- **A wing is an arm.** Same basic joints: upper arm, forearm, wrist. Animate it as an arm that happens to carry feathers, and it instantly stops looking like a flapping plank.
- **The flap is a sweep, not an up-down piston.** The motion pours out from the shoulder, the elbow shapes the arc (reminder: arc = the curved path of natural motion), and the wrist/feather-tips arrive last — that lag is **drag**, and the tips continuing after the bones reverse is **follow-through**.
- **The two strokes are not symmetrical.** Downstroke: wing spread broad, pushing down and back — this is the power, so give it authority (wider spacing, i.e. bigger movement per frame). Upstroke: wing partly folded, slicing up with low resistance — quicker and lighter.
- **The body rides the flap.** Body rises on (slightly after) the downstroke, sinks during the upstroke — offset a beat from the wings. Head stays steadiest (birds stabilise their heads); tail trails and steers last. Head leads, tail follows: **overlapping action** head to toe.
- **A flap cycle** (a seamlessly looping set of drawings) can live in 8–12 drawings: two keys (downstroke bottom, upstroke top) plus breakdowns that carry the fold and the feather drag.

Personality dials for wings: slow deep flaps + long glides = grand, huge, serene. Rapid shallow flaps = small, busy, anxious (sparrows, pixies). Irregular labored flaps + sagging recoveries = wounded, old, or overloaded.

## Superhero flight: the Fleischer masterclass

The gold-standard free study material is genuinely public domain: the **Fleischer Studios *Superman* shorts (1941–43)** — their copyrights were never renewed, and the whole collection sits legally on the Internet Archive (link below). Two study notes:

- In the earliest shorts Superman **leaps** rather than flies: ballistic arcs, gravity always winning at the top. Compare against later sustained flight — the difference between a *thrown body* and a *self-propelled body* is exactly the difference you must choose for your own character.
- **The cape is doing half the acting.** It trails the flight path (drag), whips on direction changes, and keeps travelling after landings (follow-through). Watch *The Mechanical Monsters* frame by frame for cape physics that still humbles animators.

Mechanics of the power-flier:

1. **Takeoff:** anticipation crouch (squash — the body compressing, storing force) → explosive launch with full-body stretch. The deeper the crouch and the fewer frames the launch takes, the more powerful they read.
2. **Cruise:** long straight-ish path softened into shallow arcs; body held firm like a keel; hair and cape stream behind and ripple (the ripples travel *backwards* along the cloth — overlapping action within the cape itself).
3. **Banking / turning:** the head and eyes look into the turn first, the body rolls after, the cape sweeps wide on the outside of the curve. Lead with intention, follow with mass.
4. **Hover:** never dead-still. A slow drift — down a touch, up a touch — on tight spacing (tiny movement per frame), with cloth and hair gently late on every drift. Dead-still hovering reads like a paused video, or — usefully — like something *deeply* uncanny (Lesson 7 exploits this).
5. **Landing:** the reverse launch. Decelerate (drawings bunch), touch down toe-first, knees bend to swallow momentum (squash), cape catches up and settles last. A superhuman landing takes the impact with almost no bend — power shown by *how little* the body yields, while the ground, dust, and cape do the yielding instead.

## Magic flight: floaters, fairies, and the untethered

No wings, no thrust — so pick the rules and keep them consistent:

- **The fairy/sprite:** weightless timing — everything eased, tight spacing, drifting arcs; direction changes are soft S-curves; clothes and hair float as if underwater, follow-through stretched long and dreamy.
- **The ghost/eldritch drifter:** move the *whole silhouette* at constant speed with no easing at all while the trailing parts undulate — the contradiction (mechanical core + organic streamers) is what makes skin crawl.
- **The gleeful chaos-flier:** breaks its own arcs, overshoots corners, wobbles on hover — flight as a scribble. Pure scruffy joy (Lesson 8 vocabulary).

## Swimming: flight's denser sibling

Water is thick sky. The first question is the same — *what moves them through it?* — but water adds a second question the air never asks this loudly: **what does the water do back?** Drag on everything, drift after every stroke, and nothing stops on the frame it decides to stop — the glide always gets the last word.

- **The undulator (eels, sea serpents, ribbon-tailed anything):** the body *is* the wave. Draw one S-curve and send it travelling from nose to tail-tip — the curve moves *backwards* along the body while the creature moves *forwards* through the water. This is Lesson 9's overlapping action promoted from hair-and-capes to an entire anatomy: animate the wave, and the swimmer comes free. A loop lives happily in 6–8 drawings; the slower and wider the wave, the calmer and larger the swimmer reads.
- **The tail-and-keel fish:** body held firm like the superhero's cruise, tail sweeping side to side for power, every fin trailing as drag and follow-through. The pectoral fins are the hands — a hovering fish *sculls*, tiny fan-flicks to stay put, which is the underwater version of the hover rule: never dead-still.
- **The burst-and-glide darter:** real fish rarely cruise at constant speed. Anticipation coil → two or three explosive frames → a long eased glide, drawings bunching as the water's drag wins. Every dash is a takeoff and landing compressed into a second.

Personality dials underwater: slow wide undulation = serene, huge, wise. Fast tight wiggles = small, busy, nervous. Interrupted glides with wobbling corrections = clumsy, flustered, or shy. And bubbles are the water's cape — secondary motion (rising, wobbling, always *late*) that tells the audience the speed and the mood the body alone can't show.

## The personality dials

| Choice | Reads as |
|---|---|
| Deep crouch, 2–3 frame launch, smear off screen | overwhelming power |
| Long ease into a gentle takeoff | serenity, grace, holiness |
| Constant flap rhythm, level path | steady, dependable, patrol-bird |
| Broken rhythm, dipping path, effortful recoveries | struggle, exhaustion, courage |
| Rigid body + still hover, zero drift | uncanny, artificial, wrong (on purpose) |
| Cape/hair follow-through huge and slow | epic scale, drama |
| Cape/hair follow-through quick and snappy | lightness, sport, fun |

## Try it — Clip Studio Paint EX

Two-part sitting. (1) **Wing cycle:** 8 drawings on twos (each drawing held 2 frames), side view, simple gull — animate the *arm*, then add feather-tip drag one to two frames behind. Onion skin on (Animation menu > Show animation cels > Onion skin settings). (2) **Cape study:** import nothing, copy nothing — just watch a Fleischer Superman clip at the Internet Archive, scrub frame by frame, and copy five consecutive cape poses onto five cels. You'll learn more about cloth in those five drawings than in an hour of theory. (KevinFarias's free Clip Studio TIPS article on animating a cape in the wind — 10 key drawings — pairs perfectly; link below.)

## Try it — ibisPaint X

**Hover drill:** 6 frames, 8 fps, Loop. A small character bobs: frames 1–3 drift down a few pixels, frames 4–6 drift back up. Hair and scarf drawn one frame late relative to the body's drift. Then duplicate the project and make the *same* character hover with **zero** drift, cloth frozen — feel how the first is alive and the second is eerie. Congratulations: you just animated the difference between a fairy and a haunting.

## Drills (one sitting each)

1. **Flap cycle:** 8-drawing bird loop. Downstroke broad and powerful, upstroke folded and quick, tips always late.
2. **Takeoff triptych:** three versions of the same launch — human effort (big crouch, strain, wobble), superhuman (small crouch, instant, clean), magical (no crouch at all, simply *lifts*). Timing dials only.
3. **Cape tail:** a 12-frame flight loop where you animate ONLY the cape on a stiff dummy body. The cape must tell us the speed.
4. **Eel wave:** an 8-drawing loop, side view, of a ribbon-bodied swimmer — animate ONLY one S-curve travelling nose to tail. Then double the wave's speed and halve its width on a copy: the same creature goes from serene to nervous without a single new body part.

## If you only keep three things

1. First decide **what holds them up** — wings (work), power (velocity), or magic (invented rules) — and let every drawing answer consistently.
2. Wings are arms: sweep from the shoulder, broad powerful downstroke, folded quick upstroke, feather-tips always last (drag and follow-through).
3. Hovering means drifting; landings reveal power by *who absorbs the impact* — the knees, or the ground and cape.

## Sources for this lesson (all free & legal; details in Lesson 19)

- Aaron Blaise, *Animation – The Mechanics of Bird Flight* (video): https://www.youtube.com/watch?v=2FR982O37dw
- Animation Mentor blog, *Tutorial: How to Animate Birds in Flight*: https://www.animationmentor.com/blog/tutorial-how-to-animate-birds-in-flight/
- Animation Mentor blog, *Tutorial: How to Animate Swimming* (body mechanics, timing, and flow for believable underwater motion): https://www.animationmentor.com/blog/tutorial-how-to-animate-swimming/
- KevinFarias (Clip Studio TIPS, official), *How to Animate a Cape in the Wind*: https://tips.clip-studio.com/en-us/articles/2160
- Fleischer Studios, *Superman – The Complete Collection* (1941–43, public domain): https://archive.org/details/superman-the-complete-collection-fleischerfamous-studios — single-short copy of *The Mad Scientist*: https://archive.org/details/superman_the_mad_scientist — background: <https://en.wikipedia.org/wiki/Superman_(1941_film)>

---

# PART III — CASTING THE BODY

---

# Lesson 7 — Human vs Alien vs Superhuman

*Standalone lesson. Everything you need is on this page.*

## What this lesson gives you

A single powerful framing: **every creature is a rule-set of motion.** Humans follow familiar rules imperfectly. Superhumans follow familiar rules pushed to extremes — with control. Aliens follow *different* rules — consistently. Once you think in rule-sets, "how do I make it feel non-human?" stops being a mystery and becomes a menu.

## Words used in this lesson (fresh definitions, every time)

- **timing** — how many frames an action takes; how long it lasts.
- **spacing** — how far the drawing moves between one frame and the next.
- **anticipation** — a small preparatory move before the main action (the crouch before the jump, the eyes before the head).
- **slow in and slow out** — bunching drawings at the start and end of a move so it eases in and out rather than starting/stopping like a machine.
- **arc** — the curved path almost every natural motion travels along.
- **overshoot and settle** — motion goes slightly past its target, then eases back into place.
- **follow-through** — loose parts (hair, cloth, flesh) keep moving after the body stops.
- **overlapping action** — different parts start and stop at slightly different times, never all at once.
- **squash and stretch** — a form flattening under force and lengthening with speed, volume constant.
- **smear** — a stretched or multiplied drawing shown for a frame or two to sell extreme speed.
- **asymmetry** — left and right sides of a pose or motion deliberately unequal.

## The human rule-set: familiar physics, worn imperfectly

Humans read as human because of *flaws*:

- **Weight is always being managed.** Every step is a small fall and catch; every lift strains; every stop wobbles a little before stillness.
- **Anticipation before everything.** (Reminder: the small preparatory move before an action.) Eyes before heads, crouches before jumps, breath before speech.
- **Eases everywhere.** Muscles ramp up and down — slow in and slow out on nearly every move.
- **Nothing is simultaneous.** Parts lead and lag (overlapping action); hair and cloth trail (follow-through).
- **Nothing is symmetrical.** One shoulder higher, one stride longer, small corrections everywhere (asymmetry).
- **Arcs everywhere** — curved paths for heads, hands, hips.

Animate all of that honestly and you get a person. Which means every one of those bullets is also a *dial you can break on purpose* — and that's the rest of this lesson.

## The superhuman rule-set: human rules at impossible values, with total control

A superhuman is *legible*. The audience must read the motion as "human, but beyond." So you keep the human rule-set — anticipation, arcs, eases, follow-through — and push the **values** past possibility while keeping the motion clean:

- **Extreme timing:** actions in 2–4 frames that would take a person 20. Use a **smear** (a stretched/multiplied drawing held one or two frames) so the eye can follow.
- **Extreme spacing:** enormous distance covered between frames — but along clean arcs, so it reads as speed, not error.
- **Effort without struggle:** small anticipation, instant delivery, minimal recovery. A superhuman lifting a truck crouches an inch, not a foot.
- **The world reacts instead.** Power is shown by consequences: the ground cracks under a landing (the *ground* squashes, the hero barely bends), dust storms outward, capes thunder. The body stays composed; physics happens to everything else.
- **Stops are dead-clean:** tiny overshoot, crisp settle, then stillness with confidence. Control *is* the superpower.

## The alien rule-set: different rules, kept consistently

The secret of good alien motion: it is **not random**. It obeys laws — just not ours. Pick one to three violations from this menu and apply them *everywhere, always*:

| Human rule | The alien break | It reads as |
|---|---|---|
| Anticipation before actions | **No anticipation, ever** — actions simply begin | predatory, mechanical, deeply unsettling |
| Eyes lead, head follows | **Head turns first, eyes catch up last** | possessed, wrong, haunted |
| Eases (slow in/out) on every move | **Constant-speed motion, dead stops** | robotic, insectile, eerie |
| Arcs everywhere | **Straight-line paths, angular direction changes** | unnatural precision, machine logic |
| Parts lead and lag (overlap) | **Everything arrives at once, as one block** | puppet-like, uncanny |
| Hair/cloth trails (follow-through) | **Loose parts hang inert, or move *before* the body** | physics itself is disobeying — pure horror |
| Weight managed with effort | **No weight: drifting, or too-easy lifts** | ghostly, deep-sea, low-gravity native |
| Joints bend within limits | **Joints fold the wrong way, or too smoothly, or in extra places** | anatomy from elsewhere |
| Small human asymmetries | **Perfect symmetry, metronome rhythm** | hive-made, artificial, sacred |

Two craft notes. First, **dosage**: break one rule and you get "uncanny"; break several and you get "gloriously other." Choose your dose deliberately. Second, **consistency**: if your alien never anticipates, it never anticipates — the day it winds up before a jump, it becomes a person in a costume.

## Same action, three castings (a worked example)

**Reaching for a cup.**

- **Human:** eyes flick to the cup → shoulder eases the arm out on an arc → hand overshoots a touch, fingers adjust, settle → sleeve follows through late.
- **Superhuman:** eyes flick → the hand is simply *there* in 2 frames with a smear → cup lifted with zero strain → stillness, absolute.
- **Alien:** no glance. The arm extends at constant speed on a dead-straight path, every joint arriving simultaneously; the sleeve doesn't stir. Grip. (Shudder — and notice: *nothing was exaggerated.* Rules were removed, not added.)

## Try it — Clip Studio Paint EX

One simple figure, one action (the cup reach or a two-step approach), three animation folders: HUMAN, SUPER, ALIEN. Same key poses where possible — change only timing (frame counts), spacing (distance per frame), anticipation, easing, and follow-through per the rule-sets. Loop each and compare. Label which alien rules you broke in the layer names, so the experiment stays honest.

## Try it — ibisPaint X

Phone-sized version: 6 frames each, three short clips of a figure turning and stepping toward the viewer. Human (eyes first, eases, hair late), superhuman (2-frame move + smear, clean stop), alien (constant speed, head before eyes, hair inert). Export all three and watch them in a row — on the small screen the rule-breaks read *instantly*, which is excellent feedback.

## Drills (one sitting each)

1. **Rule-break roulette:** animate one 8-frame gesture; then re-animate it three times, each time breaking exactly one human rule from the table. Name the vibe each break produces.
2. **The dose test:** build an alien with ONE break (uncanny) and another with THREE (fully other). Show someone; ask which is scarier. (Answers vary — that's the lesson.)
3. **Consequence shot:** a superhuman lands from off-screen. The body may use at most a 10 % knee bend; sell all the impact with ground cracks, dust, and cape. (Cape mechanics: Lesson 9; dust and debris: Lesson 10.)

## If you only keep three things

1. **Creatures are rule-sets.** Humans: familiar rules, imperfectly. Superhumans: familiar rules at impossible values, with control. Aliens: different rules, kept with total consistency.
2. The alien menu is subtraction: remove anticipation, eases, arcs, overlap, or follow-through — and remove them *everywhere, always*.
3. Superhuman power is shown by the world's reaction (cracking ground, storming dust, thundering cape) while the body stays composed.

## Sources for this lesson (all free & legal; details in Lesson 19)

- Wikipedia, *Twelve basic principles of animation* (the rule-set you're bending): https://en.wikipedia.org/wiki/Twelve_basic_principles_of_animation
- Fleischer Studios, *Superman – The Complete Collection* (public domain; leaping vs flying, composed power): https://archive.org/details/superman-the-complete-collection-fleischerfamous-studios
- Winsor McCay, *Gertie the Dinosaur* (1914, public domain; weight and temperament with zero dialogue): https://archive.org/details/gertiethe-dinosaur-512kb
- Cento Lodigiani, *The illusion of life* (rules creating persona on a plain cube): https://vimeo.com/93206523
- School of Motion, *Understanding the Principles of Anticipation* (what you're deleting when you delete it): https://schoolofmotion.com/blog/understanding-the-principles-of-anticipation

---

# Lesson 8 — Elegance vs Scruffiness

*Standalone lesson. Everything you need is on this page.*

## What this lesson gives you

Elegance and scruffiness are not levels of quality — they are **two dialects of the same movement language**, and you can speak either fluently once you know which dials produce which accent.

## Words used in this lesson (fresh definitions, every time)

- **timing** — how many frames an action takes; how long it lasts.
- **spacing** — how far the drawing moves between one frame and the next.
- **arc** — the curved path almost every natural motion travels along.
- **slow in and slow out** — bunching drawings at the start and end of a move so it eases in and out.
- **overshoot and settle** — motion goes slightly past its target, then eases back into place.
- **follow-through** — loose parts (hair, cloth) keep moving after the body stops.
- **overlapping action** — different parts start and stop at slightly different times.
- **line of action** — the single imaginary curve running through a pose, giving it energy and direction.
- **silhouette** — the solid-black outline shape of a pose.
- **boiling** — the lively shimmer when redrawn lines wobble slightly from frame to frame; accidental boil is noise, deliberate boil is texture.
- **key drawing** — one of the main storytelling drawings; the rest connect the keys.

## The two dialects, dial by dial

| Dial | Elegance speaks it as… | Scruffiness speaks it as… |
|---|---|---|
| Arcs (curved motion paths) | long, unbroken, continuous curves | curves that kink, double back, or jitter |
| Spacing (distance per frame) | evenly graded, deeply cushioned at the ends | irregular — lurches and hesitations |
| Timing (frames per action) | unhurried, consistent tempo | syncopated bursts; quick-quick-slow |
| Overshoot & settle | barely-there overshoot; long soft settle | big floppy overshoot; bouncy multi-hit settles |
| Follow-through | restrained, orderly, silk-like | loose, noisy, everything flapping |
| Overlap | subtle offsets, a beat apart | exaggerated offsets, limbs on different schedules |
| Line of action (the pose's energy-curve) | long, lifted, extended | compressed, slumped, tangled |
| Silhouette | clean, simple, uncluttered | busy, spiky, delightfully messy |
| Line quality | few, confident, flowing strokes | broken, sketchy strokes; deliberate **boiling** (that frame-to-frame line shimmer) |
| Symmetry | composed near-symmetry, poised | cheerful dishevelment, all asymmetry |

**Neither column is "better."** A prima ballerina animated with scruffy dials becomes comedy; a street urchin animated with elegant dials becomes a dancer pretending to be an urchin. The only true failure is *accidental* scruffiness — jitter and uneven spacing you didn't choose — or *accidental* elegance (rarer, but a slobby character who eases beautifully into every pose reads oddly graceful).

## Elegance ≠ slow, scruffiness ≠ fast

An elegant character can move like lightning — a fencer's lunge — as long as the path is a clean arc, the stop is controlled, and the settle is quiet. A scruffy character can be slow — a hungover shuffle — as long as the spacing stumbles and the parts disagree. The dialect lives in *quality of path and stop*, not in speed.

## A free, legal side-by-side study

One public-domain film hands you both dialects in the same reel: **The Sunshine Makers** (Van Beuren Studios, 1935; link below). Bottling-sunshine gnomes bounce with round, buoyant, elastic motion; the gloomy goblins ("we're happy when we're sad!") droop, trudge, and sag. Same studio, same year, same film — two complete movement vocabularies. Watch it once for fun, then scrub it slowly and list which dials from the table each side is using. (The film even colour-codes the two moods — warm oranges vs cold blue-greys.)

For pure elegance-of-weight, watch **Gertie the Dinosaur** (1914): Winsor McCay gives a cartoon dinosaur shy, coy, stubborn charm through timing and weight alone.

## Try it — Clip Studio Paint EX

**The bow, twice.** Animate a simple character taking a 2-second bow (24 fps, on twos — each drawing held 2 frames — so 24 drawings max; 12–16 is plenty). Version A, elegant: one long arc, deep eases, hair and coat settle in a single soft wave. Version B, scruffy: same start and end poses, but the path kinks, the timing hiccups (quick-quick-slow), the overshoot flops, the hair settles in three bounces, and you let the lines **boil** (redraw them loosely so they shimmer). Same choreography — two different people.

## Try it — ibisPaint X

**Wave hello, twice.** 8 frames, 8 fps, Loop. Elegant wave: the hand travels one smooth arc with tight even spacing at the ends. Scruffy wave: elbow leads erratically, hand overshoots twice, fingers splay on the extremes, spacing lurches mid-swing. At phone size, notice how much of the dialect survives shrinking — the *stops* carry most of it.

## Drills (one sitting each)

1. **Dial audit:** take any animation you've already made. Score it against the ten dials (which column does each dial sit in?). Is the mixture on purpose?
2. **Cross-casting:** animate a diva sitting down scruffily, then a scarecrow sitting down elegantly. Feel how loudly motion overrides design.
3. **Sunshine study:** frame-scrub *The Sunshine Makers*; copy three gnome poses and three goblin poses. Note the line of action (that single energy-curve) in each — lifted vs collapsed.

## If you only keep three things

1. Elegance and scruffiness are dialects, chosen dial by dial: smooth unbroken arcs, even cushioned spacing, quiet settles vs kinked paths, lurching spacing, floppy multi-bounce settles.
2. Speed is not the dialect — *quality of path and stop* is. Fast can be elegant; slow can be scruffy.
3. The only failure is the accidental version. Choose your column on purpose, dial by dial.

## Sources for this lesson (all free & legal; details in Lesson 19)

- Van Beuren Studios, *The Sunshine Makers* (1935, public domain): https://archive.org/details/The_Sunshine_Makers_1935
- Winsor McCay, *Gertie the Dinosaur* (1914, public domain): https://archive.org/details/gertiethe-dinosaur-512kb
- School of Motion, *New to 2D Character Animation? The Most Common Mistakes* (accidental scruffiness, catalogued): https://schoolofmotion.com/blog/new-to-2d-character-animation-here-are-the-most-common-mistakes-and-how-to-avoid-them
- Animation Mentor blog, *Appeal: The 12 Basic Principles of Animation* (order + interest — elegance and scruffiness are both appeals): https://www.animationmentor.com/blog/appeal-the-12-basic-principles-of-animation/

---

# PART IV — THE LOOSE AND THE LIVING

---

# Lesson 9 — Overlap & Follow-Through (Hair, Clothing, Tails)

*Standalone lesson. Everything you need is on this page.*

## What this lesson gives you

The pair of principles that glue a character together: why loose things lag and keep going, the chain-and-pendulum mechanics that make it drawable, and exact recipes for hair and cloth.

## Words used in this lesson (fresh definitions, every time)

- **follow-through** — loose parts (hair, cloth, tails, flesh) keep moving after the main body stops.
- **overlapping action** — different parts start and stop at slightly different times, never all at once.
- **drag** — a trailing part lags behind because its base moved first.
- **secondary action** — a smaller supporting action layered on the main one, adding character without stealing focus. (Related but different: secondary action is *chosen acting*; follow-through is *physics happening to loose stuff*.)
- **overshoot and settle** — motion goes slightly past its target, then eases back into place.
- **timing** — how many frames an action takes.
- **spacing** — how far the drawing moves between one frame and the next.
- **arc** — the curved path almost every natural motion travels along.
- **key drawing** — one of the main storytelling drawings; the rest connect the keys.
- **cycle** — a set of drawings that loops seamlessly.
- **onion skin** — a ghost view of the frames before/after the one you're drawing.

## The physics in one image

Animation Mentor's essay on this principle uses the perfect everyday picture: **a car braking hard.** The car stops; the passenger keeps going and catches the seatbelt. Every loose thing attached to a moving body is that passenger. Newton's first law, wearing a ponytail.

- The body moves first → the loose part is *left behind*, then yanked after it: that's **drag**.
- The body stops → the loose part *keeps travelling*, swings past, and comes back: that's **follow-through**, usually with an **overshoot and settle** (past the resting point, then easing back).
- And because all of this happens at slightly different times for different parts, the whole figure exhibits **overlapping action** — nothing starts or stops in unison.

Without this, characters look like they're cut from cardboard — stiff and mechanical. With it, they gain fluidity and life. It is the single highest-value polish in character animation.

## The chain rule (how to actually draw it)

Treat any loose thing — ponytail, sleeve, tail, cape, necklace — as a **chain of segments**: root, middle(s), tip.

1. **Animate the base first.** The head, the shoulders, the hips — the *cause*. (The guide's mantra: cause first → body next → loose parts last → settle.)
2. **Offset each segment behind its parent.** Pixar animator Anthony Wong's free tutorial gives the classic method: each joint of the chain runs **one to two frames behind** the segment above it. Root follows the head almost immediately; middle is a beat late; tip is latest of all.
3. **A wave travels down the chain.** When the base changes direction, that reversal ripples root → middle → tip over several frames. Draw the chain curving one way at the root while the tip still curves the other — an S-shape mid-swing is the signature of correct overlap.
4. **Tips travel farthest and settle last**, with the biggest overshoot. When everything has stopped, let the tip do one small extra sway before stillness.

Pendulum facts worth keeping (from the same tutorial): the drag is biggest when the base is moving fastest; the chain's extreme positions happen just *after* the base stops; and how quickly the swinging decays tells the audience the material's weight.

## Hair recipes

- **Split hair into 2–4 chains**, not fifty strands: fringe, side locks, main mass or ponytail. Animate each as its own chain, slightly offset from the others (overlapping action *between* the chains, too).
- **Roots are welded to the skull** — they move with the head instantly. All the lag lives toward the tips.
- **A head turn** (eyes → head → hair): hair starts a beat after the head, sweeps on an arc, overshoots past the face or shoulder, settles back in one or two diminishing sways.
- **A looping wind cycle:** KevinFarias's free Clip Studio TIPS article builds wind-blown hair as a **24-frame loop with key drawings every 3 frames** (frames 1, 4, 7, 10, 13, 16, 19, 22), flowing along an action line drawn from the head over the ear. His golden warning: prioritising volume makes hair look coarse — **prioritise softness**, let the mass flow like ribbon before you worry about thickness.
- **Material = timing** (how many frames things take): short stiff hair barely lags a frame; a heavy braid lags long and settles in one slow swing; silky anime hair lags long *and* ripples internally.

## Clothing recipes

- **Cloth is trailing-edge physics:** hems, capes, sleeves, and coat-tails are chains whose root is the garment's attachment (shoulders, waist) — same offset method, same waves.
- **Cloth has memory and gravity:** after the swing, it wants to fall into hanging folds. Let folds re-form during the settle rather than freezing mid-flap.
- **A walking coat-hem** bounces on every step, a beat after each footfall — one of the cheapest "this character is alive" effects in existence.
- **The cape masterclass, free:** the Fleischer *Superman* shorts (public domain, linked below) — scrub *The Mechanical Monsters* and watch the cape drag on takeoff, stream in flight, whip on turns, and settle after landings. Then try KevinFarias's cape-in-the-wind tutorial (10 key drawings) in Clip Studio Paint.
- **Personality through cloth:** crisp minimal lag = starched, wealthy, controlled. Big soft floppy lag = comfy, shabby, warm. Cloth that *leads* before the body moves = haunted (that's an alien rule-break from Lesson 7 — loose parts moving first reads as physics disobeying).

## How much lag is "right"?

There's no single number — there's a casting decision (this is a personality guide, after all):

- **Elegant characters:** modest offsets, orderly single-wave settles. (Lesson 8 calls this the elegant dialect.)
- **Scruffy characters:** bigger offsets, floppier overshoots, multi-bounce settles.
- **Heavy materials:** short lag, fast decay. **Light materials:** long lag, slow decay, big travel.
- **Too much everywhere = seaweed.** If every part flops equally, the character reads drunk or underwater. Lag amounts should *differ* between parts — that difference is what reads as structure.

## Try it — Clip Studio Paint EX

**The pendulum first** (everything else is this drill in costume): 12 drawings on twos, a ball on a string swinging left-right-left from a fixed pivot. The string tip runs 2 frames behind the pivot's reversal; the ball overshoots each swing's end and the swings decay. Onion skin on (Animation menu > Show animation cels > Onion skin settings). Then **the ponytail turn:** head turns in 8 frames on one animation folder; ponytail on a second folder, starting 2 frames late, S-curving mid-swing, overshooting, settling in two diminishing sways.

## Try it — ibisPaint X

**Flag on a pole:** 8 frames, 8 fps, Loop. The pole never moves; the flag's wave travels outward — draw the wave crest at the pole in frame 1, mid-flag by frame 3, at the free edge by frame 5, while a new crest starts at the pole. (You've just animated a travelling wave — the heart of all cloth and hair.) Onion skin makes the crest positions easy to march outward frame by frame.

## Drills (one sitting each)

1. **Pendulum with three weights:** same 12-frame swing drawn three times — iron ball (short lag, fast decay), tennis ball (medium), balloon on a string (huge lag, floaty decay). Timing and spacing sell the material; the drawing barely changes.
2. **Stop test:** a character runs in and stops dead. Body stops on frame 6; hair, scarf, and coat settle over frames 7–16, each on its own schedule. The body may not move at all after frame 6 — let the loose parts do *all* the talking.
3. **Cape only:** stiff dummy body flies a loop; animate only the cape (root at the shoulders, wave travelling to the hem). Fleischer-check your work against *The Mechanical Monsters*.

## If you only keep three things

1. Loose parts are passengers: **drag** behind a moving base, **follow-through** past a stopping one, **overshoot and settle** at the end — nothing starts or stops in unison (**overlapping action**).
2. Draw loose things as chains offset **1–2 frames per segment**, with a wave travelling root → tip; tips travel farthest and settle last.
3. Lag amount is both material *and* personality: crisp = controlled, floppy = scruffy-warm, none = cardboard, everywhere-equal = seaweed.

## Sources for this lesson (all free & legal; details in Lesson 19)

- AlanBeckerTutorials, *5. Follow Through & Overlapping Action – 12 Principles of Animation* (video): https://www.youtube.com/watch?v=4OxphYV8W3E
- Animation Mentor blog (Drew Adams), *Follow-through and Overlapping Action*: https://www.animationmentor.com/blog/follow-through-and-overlapping-action-the-12-basic-principles-of-animation/
- Animation Mentor blog (Anthony Wong, Pixar), *Tutorial: Overlap and Pendulum Motion in Animation*: https://www.animationmentor.com/blog/tutorial-overlap-pendulum-motion-animation/
- Dong Chang, *How to animate hair and secondary action* (video): https://www.youtube.com/watch?v=eIgIaHXnG8U
- KevinFarias (Clip Studio TIPS, official), *Draw and Animate Wind-Blown Hair in Clip Studio Paint*: https://tips.clip-studio.com/en-us/articles/10861 — and *How to Animate a Cape in the Wind*: https://tips.clip-studio.com/en-us/articles/2160
- Fleischer Studios, *Superman – The Complete Collection* (public domain cape physics): https://archive.org/details/superman-the-complete-collection-fleischerfamous-studios

---

# Lesson 10 — Animating the Elements (Electricity, Water, Fire, Wind)

*Standalone lesson. Everything you need is on this page. Each element's section is also self-contained — jump straight to the one you need.*

## What this lesson gives you

Effects animation — the elements — treated the way this guide treats everything: as *actors*. Each element has a body (or pointedly lacks one), a tempo, and a temperament. Working effects animators say it plainly: effects sit at the apex of emotional resonance — they amplify whatever the scene is feeling.

## Words used in this lesson (fresh definitions, every time)

- **timing** — how many frames an action takes; how long it lasts.
- **spacing** — how far the drawing moves between one frame and the next.
- **frame** — one single image in an animation; film traditionally shows 24 per second.
- **follow-through** — loose or trailing parts keep moving after the main mass stops.
- **overlapping action** — different parts start and stop at slightly different times.
- **arc** — the curved path almost every natural motion travels along.
- **cycle** — a set of drawings that loops seamlessly.
- **straight-ahead animation** — drawing frame 1, then 2, then 3, discovering the motion as you go (the natural mode for fire and water).
- **onion skin** — a ghost view of the frames before/after the one you're drawing.
- **silhouette** — the solid-black outline shape of a drawing.

## Before the four: two working rules

1. **Observe, then stylise.** Professional FX animators keep phone folders full of slow-motion fire pits and dripping taps. Physics first, then push the timing and spacing until it's *yours*. A stylised flame still obeys "hot air rises"; it just says it with attitude.
2. **Effects belong to their context.** If the ground is dusty, a landing kicks dust. If a character is soaked, every whip of the head throws droplets. Elements are how the *world* participates in the acting.

---

### ELECTRICITY — the element with no body

**Its nature:** effectively massless and instantaneous. Which means: **almost no follow-through** (reminder: follow-through = trailing parts continuing after a stop — electricity has nothing trailing) and no eases — it appears, restructures, vanishes.

**How to draw it:** jagged paths — straight-ish segments with sharp angle changes, branching like a river delta in a hurry. Thick core, thin forks.

**How to time it:** total discontinuity. Sarrah Wilkinson's free official Clip Studio TIPS tutorial gives the liberating instruction: **draw a completely new random bolt every frame — deliberately ignore the onion skin** (the ghost view of neighbouring frames). The frame-to-frame *disagreement* IS the crackle. Her recipe: a guide shape, bolts redrawn per frame at roughly **6 fps across 6 frames**, plus a soft glow layer (in Clip Studio: a second folder with an airbrushed pale blue set to the "Add (Glow)" blending mode).

**Its personalities:** surgical single zap (2–3 frames, one clean bolt, gone) = precision, menace. Continuous dancing arcs = wild, barely-contained power. Slow lazy sparks = dying machine, sputtering magic.

**Mini-drill:** 6 frames, 6 fps, loop: a bolt between two points, redrawn from scratch every frame. Add the glow layer. Ten minutes; instant lightning.

---

### WATER — the element that is all body

**Its nature:** heavy, connected, always seeking the lowest level. Water is the **overlap champion** (overlapping action — parts moving on different schedules): a wave's crest curls *after* its base has moved on; a splash's droplets are each on their own little schedule.

**How to draw it:** smooth, muscular curves; simple readable masses (a wave is one clear silhouette — the solid outline shape — before it is a thousand ripples). Droplets separate into their own small shapes and fly on **arcs** (curved paths), like tiny thrown balls.

**How to time it:** generous and eased. The splash lifecycle: impact → a rim rises (fast, wide spacing) → columns and droplets climb, slow at the top (bunched spacing — hang time!) → fall → rings ripple outward, late and soft, the last thing to settle. Follow-through everywhere: water keeps sloshing long after the cause has stopped.

**Its personalities:** playful fountain (bouncy timing, fat droplets) = joy. Slow rolling swell (long timing, deep eases) = calm, sorrow, vastness. Chopped stabbing spray (fast, jagged for water) = storm, rage.

**Mini-drill:** a droplet falls into a still pool: drop (stretch as it falls) → rim splash (2–3 frames) → two or three droplets arc out and fall → expanding ripple rings settle. 10–12 drawings.

---

### FIRE — the element that eats

**Its nature:** buoyant, hungry, never still. Hot air rises, so **the base leads and the tips follow** — flame licks are born at the bottom, travel upward, and die at the top. That's overlapping action running vertically, forever.

**How to draw it:** the official Clip Studio TIPS fire tutorial (KevinFarias) gives the flame's four-beat lifecycle — a loop of **Ascent → Swelling → Division → Reduction**: the flame rises from the base, swells, splits into separate tongues, and the split-off tips shrink away to nothing. Draw flames as clean flowing S-curves with sharp licks — simple silhouettes; too many tongues turns fire into scribble.

**How to time it:** perpetual change — fire never holds a shape and never repeats exactly (a good fire cycle hides its seam by varying each pass). Mostly **straight-ahead animation** (drawing frame 1, 2, 3…, discovering as you go) with the lifecycle as your map. Candle = few frames of difference, gentle sway. Bonfire = faster, bigger licks, sparks as separate late-arriving particles (their lag is the fire's follow-through).

**Its personalities:** small rhythmic candle = cosy, intimate, fragile. Tall reaching licks with quick timing = hunger, danger. Slow fat rolling flames = oppressive heat, doom. A flame that *leans* = wind exists (see next section) and the fire is *reacting* — elements act on each other.

**Mini-drill:** 8-drawing candle-flame loop using Ascent → Swelling → Division → Reduction. Then redo it angry: faster, sharper, one tongue tearing free per pass.

---

### WIND — the invisible element

**Its nature:** wind cannot be drawn — **only its victims can.** You animate wind by animating everything it touches: hair, cloth, grass, leaves, dust, smoke, a struggling umbrella.

**How to draw it:** choose debris with silhouettes that read small (leaves, petals, paper, dust puffs) and send them along long **arcs** — rising-and-dipping curved paths, tumbling as they go. Smoke and dust reveal the wind's actual shape: curls, vortices, gusts.

**How to time it:** wind is a **traveling push**: a gust arrives at the near tree *before* the far tree, hits the character's fringe *before* the coat-hem — staggered starts everywhere (overlapping action at the scale of the whole scene). Then the *recovery*: after the gust, everything eases back at its own rate — grass quickly, a heavy coat slowly, hair with an overshoot and settle (going past resting position, then easing back). For a looping wind-in-hair cycle, the free official Clip Studio TIPS recipe: a **24-frame loop, keys every 3 frames**, hair flowing along one drawn action line, softness prioritised over volume.

**Its personalities:** a single polite gust (one wave through the scene, gentle recovery) = a world taking a breath — melancholy, transition. Constant streaming wind (everything leaning, flags snapping) = adventure, exposure, urgency. Chaotic swirling bursts = storm, panic, magic arriving.

**Mini-drill:** one character, one gust, 12 frames: fringe reacts frames 1–3, scarf frames 2–6 (bigger travel, later settle), a leaf tumbles through on an arc frames 1–12. The gust is never drawn. It is completely visible.

---

## Elements as character accessories

The moment an element belongs to a *character*, every dial above becomes a personality dial: the storm-mage whose lightning is surgical vs the one whose lightning sprays everywhere; the water spirit who moves like a lazy swell vs one who moves like chop; the fire familiar that flickers nervously vs one that burns in slow menace. Decide the character's temperament first (Lessons 1–3), then let their element speak the same dialect (Lesson 8: elegant or scruffy applies to flames, too).

## Try it — Clip Studio Paint EX

Each element's mini-drill above fits one sitting. Clip Studio specifics: separate animation folder per element layer (bolts / glow, water mass / droplets, flame / sparks); the "Add (Glow)" layer blending mode for electricity and embers; onion skin ON for water and fire (their shapes must flow), onion skin deliberately IGNORED for electricity (its shapes must not).

## Try it — ibisPaint X

The same drills scale down happily: electricity at 6 frames/6 fps is practically *designed* for phone animation; the candle loop and the flag-gust drill both live comfortably in 8 frames. Use Loop playback for cycles, and preview small — an effect that reads as a thumbnail will read anywhere.

## If you only keep three things

1. Each element is a body-type: electricity has none (redraw it from scratch every frame — the discontinuity is the crackle), water is all connected mass (overlap champion, eased and arcing), fire is buoyant appetite (base leads, tips die: Ascent → Swelling → Division → Reduction), wind is invisible (animate its victims, as a traveling push plus recovery).
2. Physics first, then push timing and spacing until the element has *your* character's temperament.
3. Elements are actors: they amplify the scene's emotion and obey the same elegant-vs-scruffy dialect as the characters they belong to.

## Sources for this lesson (all free & legal; details in Lesson 19)

- MsRedNebula / Sarrah Wilkinson (Clip Studio TIPS, official), *3 Magical Animated Effects – Lightning, Fire, and Sparkles*: https://tips.clip-studio.com/en-us/articles/7688
- KevinFarias (Clip Studio TIPS, official), *How to Animate Fire in Clip Studio Paint*: https://tips.clip-studio.com/en-us/articles/2568 — and *Draw and Animate Wind-Blown Hair*: https://tips.clip-studio.com/en-us/articles/10861
- Micah Buzan, *How To Animate Better LIGHTNING – 2D Animation Tutorial* (video): https://www.youtube.com/watch?v=sasfZPPLfAY
- Kuzillon, *How to animate WATER* (video): https://www.youtube.com/watch?v=t9Vu0rYGoIQ
- Dong Chang, *How to animate Explosions* (video — smoke/debris technique): https://www.youtube.com/watch?v=LUeELkfGR-I
- VFX Apprentice / Jason Keyser, *jkFX Animation Tutorials – 2D Flash FX* (47-video playlist): https://www.youtube.com/playlist?list=PLQD_sA-R5qVLOZ2EIi4zqsD3WSnF4QwIy
- Toon Boom (interview), *Jason Keyser and Chris Graf share secrets behind 2D FX's magic*: https://www.toonboom.com/jason-keyser-and-chris-graf-share-secrets-behind-2d-fxs-magic
- Khan Academy × Pixar, *Pixar in a Box — Effects unit*: https://www.khanacademy.org/computing/pixar/effects
- Dan Root, *How to Animate Fire* (video, alternative take): https://www.youtube.com/watch?v=W1NA4Lk-__M

---

# PART V — YOUR STUDIO

---

# Lesson 11 — Clip Studio Paint EX: The Animation Workflow (Desktop)

*Standalone lesson. Everything here was checked against Celsys' official manual and official Clip Studio TIPS tutorials (links at the end).*

## What this lesson gives you

The complete tour of animating in Clip Studio Paint EX: project setup, the Timeline, cels, onion skin, the light table, and export — plus a sane default workflow for every drill in this guide.

## Words used in this lesson (fresh definitions, every time)

- **frame** — one single image-slot in the animation's time; film traditionally runs 24 frames per second.
- **fps (frames per second)** — how many frames play each second.
- **cel** — one drawing in the stack (named after the transparent celluloid sheets of classic animation). In Clip Studio, a cel is a layer (or a folder of layers — e.g. separate line and colour layers acting as one drawing).
- **animation folder** — Clip Studio's container for cels; everything inside it is treated as the frames of one animated element.
- **timeline** — the panel where cels are placed in time and the animation is played back.
- **onion skin** — a ghost view of the cels before/after the one you're drawing.
- **light table** — a Clip Studio feature for pinning reference drawings faintly under your working cel (the digital version of a glass desk with a lamp beneath).
- **key drawing** — one of the main storytelling drawings; **inbetween** — a drawing filling the gap between two keys.
- **animating "on twos"** — holding each drawing for 2 frames (12 drawings per second at 24 fps).
- **cycle** — a set of drawings that loops seamlessly.

## Why EX matters here

Clip Studio Paint is a paid app that comes in DEBUT, PRO, and EX grades (EX is the most expensive tier — sold as a one-time purchase on Windows/macOS or by subscription; there's a free trial). For animation the difference is blunt: **PRO and DEBUT are capped at 24 frames of animation** (per Celsys' own FAQ and manual — at 24 fps that's one second; at 8 fps, three seconds), while **EX has no frame limit**. You have EX, so every exercise in this guide — and full scenes — fit without workarounds. (EX also unlocks a couple of pro exports mentioned below.)

## Setting up

1. **File > New**, and set **Project: Animation**. This creates a canvas with an animation folder and timeline ready to go.
2. In the same dialog choose canvas size, **frame rate** (fps), and playback time. Friendly defaults for this guide's drills: **24 fps working on twos** (each drawing held 2 frames), or simply **12 fps with one drawing per frame** — the same rhythm with easier arithmetic.
3. If the timeline isn't visible: **Window > Timeline**.

Two bits of vocabulary Clip Studio uses constantly (defined above, used everywhere): your drawings live as **cels** inside an **animation folder**, and the **timeline** decides which cel shows on which frame.

## The core loop of work

- **Make a new drawing:** the **New animation cel** button on the Timeline palette (also available by long-pressing the track, from the Timeline palette menu, or the Animation menu). Each cel can be a single layer — or a folder of layers, so one "drawing" can keep its lines and colours separate.
- **Place / re-time drawings:** cels are *assigned* to frames on the timeline. You can hold a drawing for 2 frames (that's animating **on twos**), re-assign cels to new positions, and batch-assign via Animation menu > Edit track > Batch specify cels. To reuse a drawing later in the timeline (a blink, a loop), assign the same cel again — no redrawing.
- **See neighbours while you draw:** enable **onion skin** (ghost view of previous/next cels): Animation menu > Show animation cels > **Onion skin settings**, or the Enable onion skin button on the Timeline palette. You can set how many neighbouring cels show, in colour or monochrome, and how quickly they fade.
- **Inbetween with the light table:** register any cel, layer, or imported image to the **light table** (Animation cels palette; or Animation menu > Light table > Register selected layer / Register onion skin images). Registered drawings glow faintly under your working cel — exactly how paper animators tape keys to a lit desk to draw the inbetween. This is the professional way to draw a breakdown between two keys.
- **Play it:** loop playback from the Timeline palette constantly. Animation is judged in motion, never as stills.
- **Organise scenes:** tracks can be split and merged as clips (Animation menu > Edit track > Split clip / Merge clips) — handy once drills become shots.

## A default structure for this guide's drills

- Animation folder **BODY** — the character's main motion (cause and body of the mantra: *cause first → body next → loose parts last → settle*).
- Animation folder **LOOSE** — hair/cloth cels, offset 1–2 frames behind BODY.
- Animation folder **FX** — element cels (electricity/water/fire), with glow layers set to the "Add (Glow)" blending mode when you want shine.
- A regular (non-animated) layer at the bottom for the ground line or background.

## Exporting

**File > Export animation** offers, among others: **Movie** (MP4 everywhere; AVI on Windows; QuickTime on macOS/iPad), **Animated GIF** (transparency supported), **Animated sticker (APNG)**, **Animated WebP**, **Image sequence** (PNG/TIFF/etc.), and — EX-only extras — **Export animation cels** and an **exposure sheet** (the frame-by-frame timing chart professional studios use), plus OpenToonz scene export. For sharing drills from this guide: MP4 for social/messaging, GIF for quick loops.

## If you only keep three things

1. File > New → **Project: Animation**; drawings are **cels** living in an **animation folder**, scheduled on the **timeline** (Window > Timeline). EX has no frame cap (PRO/DEBUT stop at 24 frames).
2. Draw with **onion skin** on; inbetween with the **light table**; hold drawings 2 frames to work **on twos**.
3. Separate animation folders for BODY / LOOSE / FX keep the mantra honest: cause first, body next, loose parts last, settle.

## Sources for this lesson (all official Celsys pages; details in Lesson 19)

- Clip Studio TIPS (official), *Basics of the Animation Feature — "How to animate #1"*: https://tips.clip-studio.com/en-us/articles/2047
- Clip Studio TIPS (official), *Hand-drawn animation — "How to animate #2"*: https://tips.clip-studio.com/en-us/articles/2048
- Clip Studio TIPS (official), *Useful functions for hand-drawn animation — #3*: https://tips.clip-studio.com/en-us/articles/2049
- Official manual — Animation section index: https://help.clip-studio.com/en-us/manual_en/600_animation/600_animation.htm (Timeline palette, Animation folders and cels, Onion skin, Using light table layers, Export animation, Using clips)
- Official FAQ (frame limit wording): https://support.clip-studio.com/en-us/faq/articles/20210092
- Official feature page — Export options: https://www.clipstudio.net/en/animation/tool/exporting/

---

# Lesson 12 — ibisPaint X: The Animation Workflow (Mobile)

*Standalone lesson. Everything here was checked against ibis inc.'s official how-to lecture and release notes (links at the end).*

## What this lesson gives you

The full tour of ibisPaint X's animation feature — what it is, where everything lives, its honest limits, and how to make phone-sized animation a strength instead of a compromise.

## Words used in this lesson (fresh definitions, every time)

- **frame** — one single image in the animation; shown in sequence like a flip-book.
- **fps (frames per second)** — how many frames play each second.
- **onion skin** — a ghost view of the frames before/after the one you're drawing.
- **cycle / loop** — a set of drawings that repeats seamlessly.
- **key drawing** — one of the main storytelling drawings of an action.
- **silhouette** — the solid-black outline shape of a pose; at phone size, silhouette does most of the talking.
- **timing** — how many frames an action takes; **spacing** — how far the drawing moves between frames.

## What the feature is (and when it arrived)

ibisPaint's **Animation Function** arrived in **version 11.0.0 (September 2023)** — the official release note reads simply "Added Animation function," and the official description is charming and accurate: your illustrations are "shown continuously like a flip-book." It is frame-by-frame animation, the same craft as this whole guide, in your pocket. (Worth knowing: ibisPaint X itself is a free app supported by ads, with optional paid ad removal — and the Animation Function is presented as a standard feature in the official docs, with no separate paid unlock documented for it.)

## Where everything lives

- **The Animation bar** — the frame strip along the bottom of the canvas. This is your timeline.
- **Add a frame:** the **+** button on the Animation bar.
- **Manage a frame:** frames can be **duplicated** and **deleted**; reorder by **long-pressing a frame and dragging it** along the bar.
- **Frame Settings** — playback options live here, including **fps** and playback modes: **Loop** (repeat forever — cycles live here), **Ping pong** (play forward then backward — lovely for sway-type motions), and **One-shot**.
- **Onion skin** — (ghost view of neighbouring frames) adjustable: how many past/future frames show, and how faint the nearest/furthest appear.
- **Saving:** back out via the Back button and choose **Save Animated Video** to export your animation as a video file.

One honest note: the official documentation doesn't publish a hard maximum frame count; practical limits depend on your device and canvas size. Numbers you may see quoted online for "max frames per canvas size" come from fan wikis, not ibis inc. — treat them as folklore. For this guide's drills (6–24 frames), you will never meet the ceiling.

## Making mobile a strength

Phone animation punishes clutter and rewards clarity — which happens to be exactly what animation training needs:

- **Fewer, stronger drawings.** An 8-frame walk with fierce poses beats a 24-frame walk with mushy ones. Every drill in this guide has an 8-frames-or-fewer version.
- **Silhouette first.** (Reminder: the solid-black outline shape of the pose.) If it reads as a thumbnail on your phone, it reads projected on a wall.
- **Duplicate-and-redraw** is your onion-skin-plus: duplicate the previous frame, then redraw only what moved. Volumes stay consistent — the hardest part of frame-by-frame for beginners — almost for free.
- **Layers still work.** Keep the character and the loose parts (hair/scarf) on separate layers within frames where practical, so the mantra survives: *cause first → body next → loose parts last → settle.*
- **Modest canvas sizes** keep playback smooth on-device; you're drawing motion studies, not posters.
- **Export early, export often.** Save Animated Video and watch it *outside* the app, at the size the world will see it.

## A default drill recipe (works for every lesson in this guide)

1. New canvas (modest size), Animation bar open.
2. 6–8 frames, 8–12 fps, playback mode **Loop**.
3. Onion skin on; rough the key drawings first (contact poses, or the start/mid/end of a turn).
4. Duplicate-and-redraw to refine; loose parts one frame late.
5. Save Animated Video; watch it three times: full size, thumbnail size, and once with your eyes half-closed (the squint test — if the action survives blur, the poses are working).

## If you only keep three things

1. ibisPaint's Animation Function (since v11.0.0, Sept 2023) is flip-book frame-by-frame: the **Animation bar** below the canvas, **+** to add frames, long-press-drag to reorder, duplicate/delete per frame.
2. **Frame Settings** hold fps and Loop / Ping pong / One-shot playback; **onion skin** is adjustable; export via **Save Animated Video**.
3. Phone scale is a teacher: fewer, stronger drawings; silhouette first; duplicate-and-redraw for consistent volumes.

## Sources for this lesson (all official ibis inc. pages; details in Lesson 19)

- Official how-to lecture *171. Create an animation*: https://ibispaint.com/lecture/index.jsp?no=182
- Official tutorials index (lecture list): https://ibispaint.com/lecture/index.jsp?no=0&lang=en
- Official release notes, ver. 11.0.0 ("Added Animation function"): https://ibispaint.com/information.jsp?newsID=78536238
- Official new-features page (Animation Function section): https://ibispaint.com/newFeature.jsp?lang=en
- Official ibisPaint YouTube channel: https://www.youtube.com/@ibisPaint

---

# Lesson 13 — The Practice Program (Drills, a Weekly Loop, and Films to Study Frame by Frame)

*Standalone lesson. Everything you need is on this page.*

## What this lesson gives you

A structure for actually practising: session design that respects a wandering memory, a repeatable weekly loop, and a legal, free film-study shelf with exact assignments per film.

## Words used in this lesson (fresh definitions, every time)

- **cycle** — a set of drawings that loops seamlessly.
- **key drawing** — one of the main storytelling drawings of an action.
- **timing** — how many frames an action takes; **spacing** — how far the drawing moves between frames.
- **follow-through** — loose parts keep moving after the body stops; **overlapping action** — parts start and stop at different times.
- **silhouette** — the solid-black outline shape of a pose.
- **flour sack** — the classic animation practice prop: a half-full sack of flour animated as a character. It has weight, it can hop, slump, wave, and grieve — and it has no face to hide behind, so *all* the acting is body acting.

## Session design (the ADHD-honest version)

- **Decide the drill before opening the app.** The decision is the hard part; do it while the kettle boils, not while staring at a blank canvas.
- **One sitting = one drill = 15–25 minutes.** Done is the target. Polish is a different sitting, *if you feel like it*.
- **Repeat drills shamelessly.** The tenth pendulum teaches things the first one couldn't. Repetition isn't remedial — in animation it is literally the professional training method (see the 51-exercise list below: professionals treat these as a permanent gym, not a syllabus to finish).
- **Externalise memory.** Keep the companion cheat-sheets where you practise. The sheet remembers the steps so your head can spend itself on the drawing.
- **End by watching your loop five times.** The loop playing is the reward — let it play. That tiny hit of "it moves!" is the engine of this whole craft.

## The weekly loop (repeat forever, rotate freely)

- **Day 1 — Ball:** bouncing-ball timing and spacing (Lesson 1). Personality twist: same ball as ping-pong ball, then bowling ball.
- **Day 2 — Walk:** 8-drawing cycle (Lesson 4). Twist: re-cast it (tired / cocky / sneaky) by dials only.
- **Day 3 — Head turn:** (Lesson 5). Twist: dignified, then panicked, then haunted (eyes last).
- **Day 4 — Overlap:** pendulum or ponytail or flag (Lesson 9). Twist: three materials — iron, tennis ball, balloon.
- **Day 5 — Element:** one of electricity / water / fire / wind (Lesson 10). Twist: the same element, elegant then scruffy (Lesson 8's dials).
- **Day 6 — Flight:** flap cycle, hover, or takeoff triptych (Lesson 6). Twist: human effort vs superhuman ease vs alien rules (Lesson 7).
- **Day 7 — Rewatch and remix:** line up the week's exports; pick the one you like least; redo it with ONE dial changed. Note (on the cheat-sheet, not in your head) which single change helped most.

A day skipped is a day skipped — the loop has no score. It's a carousel, not a ladder; climb on wherever it happens to be turning.

**The pixel variant (Part VII):** any day of the loop can be done at 16 or 32 pixels in 4–8 frames — ball, walk, head turn, flag, candle, flap — with Lesson 17's recipes. Same dials, smaller grid; when a drill has gone stale, shrinking it is a new drill.

## The flour sack (your no-face acting coach)

When a drill feels too easy, do it as a **flour sack** (reminder: the classic practice prop — a half-full sack animated as a character). Sack waves hello; sack walks proudly; sack is defeated by wind; sack takes flight and is terrified. The sack forces every personality choice into timing, spacing, posture, and follow-through — which is precisely this guide's thesis with the corners stitched shut. (The Animator Island exercise list below prescribes the sack repeatedly, including "Flour Sack waving (loop)".)

## The free, legal film-study shelf (with assignments)

All links verified on the Internet Archive or as noted; every film below is public domain. "Scrub" = step through frame by frame (VLC: the E key advances one frame; or import short clips as reference).

| Film | Why it's on the shelf | Your assignment |
|---|---|---|
| *Superman – The Complete Collection* (Fleischer, 1941–43) — https://archive.org/details/superman-the-complete-collection-fleischerfamous-studios | The free masterclass in dramatic action: flight, capes, effects, staging | *The Mechanical Monsters*: scrub the cape in flight (Lesson 9). *Electric Earthquake* & *The Magnetic Telescope*: electricity (Lesson 10). *Volcano*: fire and smoke. *The Arctic Giant*: water and ice. Early shorts: Superman *leaps* — compare ballistic arcs vs later sustained flight (Lesson 6). |
| *Gertie the Dinosaur* (Winsor McCay, 1914) — https://archive.org/details/gertiethe-dinosaur-512kb | The founding document of personality animation: weight, hesitation, moods — zero dialogue | List every moment you can *name a feeling* (shy, stubborn, pleased). For each: which dial produced it — timing, posture, or follow-through? (Lessons 1, 3, 9.) |
| *The Sunshine Makers* (Van Beuren, 1935) — https://archive.org/details/The_Sunshine_Makers_1935 | Two complete movement dialects in one film: bouncy gnomes vs drooping goblins | Copy three poses per side; mark each **line of action** (the single energy-curve through a pose). Score both sides against Lesson 8's elegance/scruffiness dial table. |
| Preston Blair, *Advanced Animation* (1940s book, public-domain scan) — https://archive.org/details/advanced-animation-by-preston-blair | Not a film — the classic how-to-draw-for-animation book, free | Copy one page per sitting: head construction; then "The Walk," "The Strut," "The Sneak" (Lesson 4's personality walks, drawn by a master in 1949). |

## The 51-exercise gym

Animator Island's free article **"51 Great Animation Exercises to Master"** is the community's canonical practice list — from "Ball bouncing in place (loop)" through "Flour Sack waving (loop)" and "Walk Cycle" up to full acting shots, in four difficulty tiers. Its thesis matches this guide's: *doing* the exercises beats reading about them. Keep it bookmarked as your menu when the weekly loop wants variety: https://www.animatorisland.com/51-great-animation-exercises-to-master/

## If you only keep three things

1. Decide the drill before opening the app; one sitting = one drill; repetition is the method, not the remedial track.
2. Rotate the weekly carousel (ball → walk → head turn → overlap → element → flight → remix) and always add a personality twist.
3. Study the free shelf frame by frame — Fleischer *Superman* for capes/effects/flight, *Gertie* for personality-through-weight, *The Sunshine Makers* for elegant-vs-scruffy, Preston Blair's book for everything drawable.

## Sources for this lesson (all free & legal; details in Lesson 19)

- Animator Island (J.K. Riki), *51 Great Animation Exercises to Master*: https://www.animatorisland.com/51-great-animation-exercises-to-master/
- The four study links in the table above (Internet Archive, all public domain).

---

# PART VI — INTO THE GAME

---

# Lesson 14 — Bringing Your Animation into Games (Godot, Unity, Unreal, and the Plain Web)

*Standalone lesson. Everything you need is on this page. Each engine's section is also self-contained — jump straight to the one you use. Every workflow and every line of code below was checked against the engines' current official documentation on 16 August 2026 (and the web code was actually run in a browser that day).*

## What this lesson gives you

Your drawings, moving inside a game. The pipeline is the same everywhere: **export your frames as images → hand them to the engine → tell the engine how fast to flip them.** That's it. A game engine playing your animation is a flip-book with a computer holding the pages. This lesson walks that pipeline through Godot 4.7, Unity 6.3, Unreal Engine 5.7+, and the plain web — plus one lovely Godot addon (Universal Fade) for scene transitions.

A version note, honestly: engines update constantly. This lesson was verified against **Godot 4.7.1**, **Unity 6.3 LTS**, and **Unreal Engine 5.7/5.8** — but frame-by-frame sprite animation is one of the *oldest and most stable* features in all three engines. If you're reading this a few versions later, expect button positions to drift, not concepts.

A cost note, equally honestly: **Godot** is free and open source (MIT licence, no fees ever); **Unity** and **Unreal Engine** are free to download and use, with fees or royalties that only begin above revenue thresholds most hobby projects never meet (check their current terms if you ship commercially); the **plain web** costs nothing at all. All the documentation linked in this lesson is free.

## Words used in this lesson (fresh definitions, every time)

- **frame** — one single image in an animation; your drawings, one at a time.
- **fps (frames per second)** — how many frames are shown each second. Your *art* can run at 8–12 fps while the *game* runs at 60 — engines handle that mismatch happily (more below).
- **sprite** — a 2D image a game engine can place, move, and draw on screen. Each of your exported drawings becomes a sprite (or one frame of one).
- **sprite sheet** (also *texture atlas*) — many frames packed into a single image, usually in a grid, which the engine slices back apart. One file instead of thirty.
- **image sequence** — the alternative to a sprite sheet: each frame as its own numbered file (`walk_01.png`, `walk_02.png`, …).
- **flipbook** — Unreal's name for a playable stack of sprite frames; a useful mental model everywhere.
- **alpha channel / transparency** — the invisible part of a PNG. Export with transparency so your character isn't trapped in a white rectangle.
- **texture filtering** — how the engine smooths (or doesn't smooth) your image when it's scaled. *Nearest/Point* = crisp hard pixels (right for pixel art); *Linear/Bilinear* = soft blending (right for high-resolution hand-drawn art).
- **pivot / origin** — the anchor point of a sprite (often the feet or the center). If it drifts between frames, your character will jitter — keep your drawings aligned on a consistent canvas.
- **looping** — playing an animation on repeat (walk cycles) vs **one-shot** — playing once and stopping (a head turn, a landing).
- **node / scene** (Godot), **GameObject / component** (Unity), **Actor** (Unreal) — the three engines' words for "a thing in the game world" and "a behavior attached to it." You'll see them in context below.

## First: get the frames out of your drawing app

**From Clip Studio Paint EX:** File > **Export animation** > **Image sequence**, and choose PNG. Hide (or delete) the white *Paper* layer first so the PNGs keep their transparent background — you want your character on a checkerboard, not in a white box. Export at the size you drew; engines scale down better than up.

**From ibisPaint X:** the animation feature exports *video* (Save Animated Video) — video has no transparency, so for game work export the frames themselves: save each frame's canvas as a **transparent PNG** (ibisPaint's PNG export preserves transparency), or redraw the final frames into one wide canvas as a sheet. For 6–8-frame drills this is minutes, not hours. (It's also a good excuse to keep frame counts honest — Lesson 12's "fewer, stronger drawings" pays off twice here.)

**Name frames with zero-padded numbers:** `walk_01.png` … `walk_08.png`, not `walk_1.png` … `walk_10.png`. Engines (Unreal especially) order frames *alphabetically*, and alphabetically `walk_10` comes before `walk_2`. Zero-padding makes alphabetical and numerical order agree, and the problem never exists.

**Sheet or sequence?** Every engine below accepts either. Individual PNGs are simpler to re-export when you fix one drawing; a sheet is one tidy file and is what the CSS technique on the web needs. If you want a sheet, lay your frames left-to-right in one wide canvas (all cells exactly the same size — e.g. 8 frames of 256×256 = one 2048×256 image).

## The one idea that makes engine animation easy

**Your animation's fps is a property of the *animation*, not the game.** The game may render 60 or 120 frames every second; you tell the engine "this walk cycle plays at 12 fps" and the engine holds each drawing for as long as needed. Animating **on twos** (each drawing held 2 frames at 24 fps — Lesson 1) translates directly: *set the animation's fps to 12*. Your timing — the personality clock from Lesson 1 — survives the trip into the engine untouched. Better: every engine exposes a play-speed multiplier at runtime, which means **timing becomes a dial you can turn while the game runs.** The same walk cycle at speed 0.6 is weary; at 1.4 it's eager. That is Lesson 4's personality machine, now scriptable.

---

## GODOT 4.7 — AnimatedSprite2D

Godot thinks in **nodes** (small building blocks — a sprite, a sound, a camera — that you stack into a tree) and **scenes** (a saved tree of nodes: a character, a level). Its built-in node for frame-by-frame animation is **AnimatedSprite2D**, and the resource holding the frames is called **SpriteFrames**. ("Resource" is Godot's word for a reusable data file.)

### Editor steps

1. Add an **AnimatedSprite2D** node to your character's scene.
2. In the Inspector (the panel listing the node's properties), click its **Sprite Frames** property → **New SpriteFrames**, then click it again to open the **SpriteFrames panel** at the bottom of the editor.
3. Make one named animation per action — `idle`, `walk`, `head_turn`. For each:
   - **Image sequence:** drag your PNGs into the frame list (or use the "Add frames from file" button).
   - **Sprite sheet:** click the grid-shaped **"Add frames from a Sprite Sheet"** button, tell it your grid (e.g. 4 across × 2 down), click the cells you want, in order.
4. Set each animation's **Speed (FPS)** — 12 for drawings made on twos — and toggle **Loop** on for cycles, off for one-shots.
5. Drawn crisp pixel art? Set the node's **CanvasItem > Texture > Filter** to **Nearest** (hard pixels), or set the project-wide default under Project Settings > Rendering > Textures > Default Texture Filter. High-resolution painterly frames can stay on the default (Linear = soft scaling). (Lesson 18 has the full pixel-perfect checklist for every engine: filtering, integer scaling, pixel snapping.)

*(One deprecation warning, so an old tutorial doesn't eat your afternoon: Godot also has an `AnimatedTexture` class. Its own documentation now says it "does not work properly in current versions and may be removed in the future." Use AnimatedSprite2D or AnimationPlayer instead.)*

### Playing it from code (GDScript)

GDScript is Godot's built-in language — Python-flavored, indentation-based. This script drives a walking character; attach it to a **CharacterBody2D** (Godot's node for physics-moved characters) with the AnimatedSprite2D as its child:

```gdscript
extends CharacterBody2D
# "extends" = this script is a behavior attached to a CharacterBody2D node.

# @onready = "fill this variable in once the scene is loaded".
# The $ syntax fetches a child node by name.
@onready var sprite: AnimatedSprite2D = $AnimatedSprite2D

const SPEED := 80.0  # pixels per second

func _physics_process(_delta: float) -> void:
	# _physics_process runs every physics tick (60 times a second by default).
	# Input.get_axis returns -1 (left), +1 (right), or 0 (no key held).
	var direction := Input.get_axis("ui_left", "ui_right")
	velocity.x = direction * SPEED
	move_and_slide()  # CharacterBody2D's built-in "apply velocity, handle collisions"

	if direction != 0.0:
		sprite.flip_h = direction < 0.0  # mirror the drawing when walking left
		sprite.play("walk")
	else:
		sprite.play("idle")
```

Calling `play("walk")` every tick is safe: if that animation is already playing, Godot lets it continue rather than restarting it — no stutter.

**One-shot animations** (a head turn, a landing) use the `animation_finished` **signal** (Godot's word for an event a node emits). `await` pauses the function until the signal fires:

```gdscript
func do_head_turn() -> void:
	sprite.play("head_turn")        # "head_turn" has Loop switched OFF
	await sprite.animation_finished  # wait here until the last frame has shown
	sprite.play("idle")              # then settle back
```

And the personality dial, live at runtime — `speed_scale` multiplies the animation's own fps:

```gdscript
sprite.speed_scale = 0.6  # same drawings, wearier walker
sprite.speed_scale = 1.4  # same drawings, eager walker
```

*(Alternative path, for completeness: a plain **Sprite2D** node can hold a whole sheet with its `hframes`/`vframes` grid properties, while an **AnimationPlayer** node keys the `frame` number over time. It's more setup, but AnimationPlayer can also key position, scale, and color in the same timeline — useful when a drill grows into a cutscene. The official "2D sprite animation" page, linked below, shows both workflows.)*

### Scene transitions with Godot Universal Fade

[Godot-Universal-Fade](https://github.com/KoBeWi/Godot-Universal-Fade) (MIT-licensed, by KoBeWi, a Godot core contributor) gives you screen fades — the classic "fade to black, change scene, fade back in" — in one line. A fade is your mantra's *settle* applied to the whole screen: it's how a scene change stops feeling like a hard cut.

**Install:** copy the `addons/UniversalFade` folder into your project (or grab "Universal Fade" from Godot's built-in AssetLib tab). That's genuinely all — there is no plugin to enable and no autoload to configure: the addon exposes a global class named `Fade` with **static methods** (functions you call on the class itself, no instance needed), so `Fade.fade_out()` works from any script the moment the folder exists. Current master targets Godot 4.4+ (it uses `.uid` files, introduced in 4.4), so 4.7 is comfortably covered.

**The API, one line each** (defaults shown):

- `Fade.fade_out(time := 1.0, color := Color.BLACK, pattern: Texture2D = null, reverse := false, smooth := false)` — fade the screen *to* a color.
- `Fade.fade_in(...)` — same parameters; fade *back from* the color.
- `Fade.crossfade_prepare(time := 1.0, ...)` then `Fade.crossfade_execute()` — screenshot the current screen, change anything you like, then melt the screenshot into the new state.
- Every call returns the fade object, which emits a `finished` signal — so `await` works naturally.

`time` is the fade's length in seconds (a timing dial! quick fade = snappy scene change, slow fade = grand one). `color` is what you fade to. `pattern` is optional: a grayscale texture that shapes *how* the fade sweeps across the screen — the addon ships seven (Diagonal, Diamond, GradientHorizontal, GradientVertical, Noise, Swirl, Radial) in its `Patterns/` folder. `reverse` flips the pattern's direction; `smooth` softens the pattern's edge.

```gdscript
func go_to_forest() -> void:
	# Fade to black over 0.8 s, and wait for it to finish...
	await Fade.fade_out(0.8).finished
	# ...swap the scene while the screen is fully covered...
	get_tree().change_scene_to_file("res://scenes/forest.tscn")
	# ...and fade back in on the new scene.
	Fade.fade_in(0.8)
```

```gdscript
# A patterned wipe — an old-cartoon iris-out, in one line:
var radial := load("res://addons/UniversalFade/Patterns/Radial.png")
await Fade.fade_out(1.2, Color.BLACK, radial).finished
```

*(Small honesty notes: the addon's README examples use Godot 3's old `change_scene()` — in Godot 4 the method is `change_scene_to_file()`, as above. The fade draws on CanvasLayer 100, i.e. on top of essentially everything; and it can't be called on the very first frame of the game — wait one frame if you want to fade in from a cold start.)*

---

## UNITY 6.3 — Sprites, the Animation window, and the Animator

Unity thinks in **GameObjects** (things in the world) carrying **components** (behaviors: a SpriteRenderer draws an image, an Animator plays animations, your C# scripts add logic). Unity 6 versions are numbered `6000.x` under the hood — "Unity 6.3" is `6000.3`, the current Long-Term Support release. Everything here uses only built-in pieces (the Sprite Editor ships in the core `2D Sprite` package, present by default in any 2D project; the separate "2D Animation" package is for *skeletal* rigs, not flip-books — you don't need it).

### Editor steps

1. Drop your PNGs (or one sheet) into the Project window. Select the file(s) and, in the Inspector, confirm **Texture Type = Sprite (2D and UI)**.
2. **For a sheet:** set **Sprite Mode = Multiple**, then click the **Sprite Editor** button. In the Sprite Editor's **Slice** menu choose **Grid By Cell Size** (enter your cell dimensions, e.g. 256 × 256) or **Grid By Cell Count**, click **Slice**, then **Apply**. Unity now treats each cell as its own sprite. **For an image sequence:** nothing to slice — each PNG is already one sprite.
3. Import settings worth touching, same Inspector: **Filter Mode** — "Point (no filter)" for pixel art, Bilinear for high-res drawings; **Pixels Per Unit** — how many pixels of your art equal one world-space unit (affects size in the scene, not quality).
4. Make the clips (a **Animation Clip** is Unity's word for one playable animation — your `walk`, your `idle`): select your character GameObject, open **Window > Animation > Animation**, click **Create**, name the clip (e.g. `Walk.anim`). Then select all the frames for that action in the Project window and drag them into the Animation window's timeline. Set the **sample rate** to your animation's fps (12 for drawings on twos). Repeat per action via the clip dropdown > Create New Clip.
   - *(Old-tutorial shortcut that still works but is no longer in the manual: multi-selecting sliced sprites and dragging them straight into the Scene makes Unity prompt for a clip name and set everything up. Fine to use; just know the documented path above.)*
5. Creating the first clip auto-created an **Animator Controller** (the flow-chart asset deciding which clip plays when) and put an **Animator** component on your GameObject. Open **Window > Animation > Animator** to see the chart: each clip is a **state**; arrows between states are **transitions**; loop cycles by ticking **Loop Time** on the clip asset.

### Playing it from code (C#)

Two idioms. The **direct** one mirrors Godot — tell the Animator which state to show:

```csharp
using UnityEngine;

// A component: attach this script to the GameObject that has
// the SpriteRenderer (draws the sprite) and Animator (plays clips).
public class HeroAnimation : MonoBehaviour
{
    Animator animator;              // plays the animation clips
    SpriteRenderer spriteRenderer;  // draws the current frame

    void Awake()
    {
        // GetComponent fetches a sibling component on the same GameObject.
        animator = GetComponent<Animator>();
        spriteRenderer = GetComponent<SpriteRenderer>();
    }

    void Update()  // runs once per rendered frame
    {
        // -1 (left key), +1 (right key), or 0. "Raw" = no smoothing.
        float direction = Input.GetAxisRaw("Horizontal");

        if (direction != 0f)
        {
            spriteRenderer.flipX = direction < 0f;  // mirror when walking left
            animator.Play("Walk");   // jump the Animator to the "Walk" state
        }
        else
        {
            animator.Play("Idle");
        }
    }
}
```

Calling `Play` with the state that's already playing simply lets it continue (Unity's documentation: with no explicit start-time argument, the state "will continue playing from its current time") — so, as in Godot, calling it every frame is safe.

The **Unity-idiomatic** way for one-shots is a **Trigger parameter** (a one-use flag the Animator consumes): in the Animator window's Parameters tab add a Trigger named `HeadTurn`, draw a transition Idle → HeadTurn conditioned on it, and a transition HeadTurn → Idle with **Has Exit Time** ticked (meaning: leave when the clip finishes). Then:

```csharp
public void PlayHeadTurn()
{
    animator.SetTrigger("HeadTurn");
    // The Animator handles playing it once and flowing back to Idle.
}
```

Detecting "is my one-shot done?" from code uses `normalizedTime` — the state's progress where 1.0 means "played once through":

```csharp
AnimatorStateInfo state = animator.GetCurrentAnimatorStateInfo(0); // layer 0
bool headTurnDone = state.IsName("HeadTurn") && state.normalizedTime >= 1f;
```

*(Or place an **Animation Event** — a marker on the clip's timeline that calls a method by name on the same GameObject — via the Event button in the Animation window. Good for "spawn the dust puff exactly on the Down pose.")*

And the runtime timing dial — `speed` multiplies all playback on the Animator:

```csharp
animator.speed = 0.6f;  // weary
animator.speed = 1.4f;  // eager
```

---

## UNREAL ENGINE 5.7+ — Paper 2D flipbooks

Unreal thinks in **Actors** (things in the world) carrying **components**. Its built-in 2D toolset is a plugin called **Paper 2D**: your images become **Paper Sprites**, and a playable stack of sprites is a **Paper Flipbook** — the most honest name in the business. (Verified against UE 5.7 and the current 5.8 docs; Paper 2D is unchanged between them.)

### Editor steps

1. **Edit > Plugins**, find **Paper 2D** in the 2D section, enable it (restart if prompted).
2. Import your PNGs via the Content Browser's **Import** button (or drag-drop).
3. Right-click each imported texture > **Sprite Actions > Apply Paper 2D Import Settings** — this switches the texture to 2D-friendly settings (no compression artifacts on line art, appropriate filtering).
4. **For a sheet:** right-click the texture > **Sprite Actions > Extract Sprites**, set **Sprite Extract Mode = Grid**, enter **Cell Width / Cell Height** (plus Spacing/Margin if your sheet has gutters), and extract — one Paper Sprite per cell, top-left first, left to right. **For a sequence:** right-click each texture > **Sprite Actions > Create Sprite** (or select them all and do it once).
5. Select all the sprites of one action in the Content Browser, right-click > **Create Flipbook**. ⚠ Frames are added in *alphabetical* order — this is where the zero-padded filenames from the top of this lesson save you.
6. Open the flipbook and set **Frames Per Second** (12 for drawings on twos). Each keyframe can also hold a custom frame count — Unreal will happily let you hold a contact pose 3 frames and snap through the passing pose in 1, which is exactly how a hand animator thinks.
7. Drag the flipbook into the level to get an Actor with a **PaperFlipbookComponent** (the component that renders and plays a flipbook).

### Playing it — Blueprint first

Most Paper 2D games are driven from **Blueprints** (Unreal's visual scripting — boxes and wires instead of code). The nodes mirror the C++ below exactly: **Set Flipbook** (swap which animation the component shows), **Play from Start**, **Set Looping**, and the component's **On Finished Playing** event (fires when a *non-looping* flipbook ends). A walk/idle toggle is four nodes; a one-shot head turn is Set Looping (false) → Set Flipbook → Play from Start → On Finished Playing → back to the walk.

### Playing it from code (C++)

```cpp
// ---- HeroCharacter.h (the header: declares what the class contains) ----

// UPROPERTY exposes a variable to the editor so you can assign
// assets by drag-and-drop instead of hard-coding paths.
UPROPERTY(VisibleAnywhere, Category = "Animation")
UPaperFlipbookComponent* SpriteComponent;  // renders & plays the flipbook

UPROPERTY(EditAnywhere, Category = "Animation")
UPaperFlipbook* IdleFlipbook;    // assign in the editor

UPROPERTY(EditAnywhere, Category = "Animation")
UPaperFlipbook* WalkFlipbook;    // assign in the editor

UPROPERTY(EditAnywhere, Category = "Animation")
UPaperFlipbook* HeadTurnFlipbook;

UFUNCTION()
void HandleHeadTurnFinished();   // UFUNCTION() lets Unreal's event system call it
```

```cpp
// ---- HeroCharacter.cpp (the implementation) ----

void AHeroCharacter::StartWalking()
{
    // Only swap if it actually changed — swapping restarts playback.
    if (SpriteComponent->GetFlipbook() != WalkFlipbook)
    {
        SpriteComponent->SetLooping(true);
        SpriteComponent->SetFlipbook(WalkFlipbook);
        SpriteComponent->Play();
    }
}

void AHeroCharacter::PlayHeadTurn()
{
    SpriteComponent->SetLooping(false);
    SpriteComponent->SetFlipbook(HeadTurnFlipbook);

    // AddDynamic subscribes a function to the "finished" event.
    SpriteComponent->OnFinishedPlaying.AddDynamic(
        this, &AHeroCharacter::HandleHeadTurnFinished);

    SpriteComponent->PlayFromStart();
}

void AHeroCharacter::HandleHeadTurnFinished()
{
    // Unsubscribe (so it doesn't fire again for other one-shots), then settle.
    SpriteComponent->OnFinishedPlaying.RemoveDynamic(
        this, &AHeroCharacter::HandleHeadTurnFinished);
    StartWalking();
}
```

Two footnotes worth their pixels: `SetFlipbook` refuses to work on a component whose **Mobility** is Static — leave it Movable (the default for flipbook actors). And the runtime timing dial here is `SpriteComponent->SetPlayRate(0.6f)` — weary; `1.4f` — eager.

*(If your 2D game grows past a handful of flipbooks: the free community plugin **PaperZD** adds proper animation state machines and notifies on top of Paper 2D, and Epic has featured it in official streams. For purely screen-space animation — menus, HUD flourishes — UMG widget animations with their own timeline are the simpler tool.)*

---

## THE PLAIN WEB — three techniques, zero engines

Sometimes the "game engine" is a browser: an itch.io page, a portfolio, a web toy. Three techniques, in ascending order of control. (The CSS and JavaScript below were run and verified in a real browser on the day this was checked.)

### Technique 1: just use a file that loops (zero code)

Clip Studio exports **Animated GIF**, **APNG** ("animated PNG" — like GIF but with full transparency and real colors), and **Animated WebP** (modern, small, transparent). Drop the file in an `<img>` tag and you're done:

```html
<img src="walk-cycle.webp" alt="hand-drawn character walking" width="256">
```

Cost: no play/pause control, no events, and GIF in particular is big and limited to crude transparency. For a decorative loop, though, this is honestly the right tool.

### Technique 2: CSS `steps()` — a sprite sheet with no JavaScript

CSS animations normally *glide* between values. The `steps(n)` timing function makes them *jump* in `n` equal hops instead — which turns a smooth slide of your sprite sheet into frame-by-frame playback. The element is a fixed-size window; the sheet slides behind it in frame-sized jumps:

```css
.walker {
  width: 128px;    /* one frame's width  */
  height: 128px;   /* one frame's height */
  background-image: url("walk-sheet.png");  /* 8 frames in a row: 1024×128 */
  /* 0.667s per loop ≈ 8 frames at 12 fps; steps(8) = 8 jumps; infinite = loop */
  animation: play-walk 0.667s steps(8) infinite;
}

@keyframes play-walk {
  from { background-position: 0 0; }
  to   { background-position: -1024px 0; }  /* minus the FULL sheet width */
}
```

Why `-1024px` (the whole sheet) and not the last frame's position: `steps(8)` divides the journey into 8 hops and shows the state *before each hop* — so the browser shows frames 1 through 8 and never actually arrives at -1024px. It's the same off-by-one that trips people in flip-books ("8 drawings = 8 held positions, not 9"). Duration = frame count ÷ fps: 8 ÷ 12 ≈ 0.667 s. For crisp pixel art, add `image-rendering: pixelated;`.

### Technique 3: `<canvas>` + JavaScript — full control

A `<canvas>` is a blank bitmap you draw onto from JavaScript. The player below is a complete flip-book engine in ~60 lines: it uses `requestAnimationFrame` (the browser's "call me before the next repaint" — typically 60×/second) plus a **time accumulator**, so your 12-fps animation plays at correct speed on any display, including 144 Hz monitors. The drawing itself is one call: the 9-argument form of `drawImage`, which crops a source rectangle out of the sheet (the current frame) and paints it onto the canvas.

```html
<canvas id="stage" width="128" height="128"></canvas>
```

```js
class FlipbookPlayer {
  /**
   * canvas       — the <canvas> element to draw into
   * image        — a loaded Image whose frames sit left-to-right in one row
   * frameWidth   — width of ONE frame in pixels
   * frameHeight  — height of ONE frame in pixels
   * fps          — playback speed of the ART (e.g. 12), not of the screen
   * loop         — true for cycles (walk), false for one-shots (head turn)
   */
  constructor(canvas, image, frameWidth, frameHeight, fps, loop = true) {
    this.ctx = canvas.getContext("2d");     // the canvas's drawing tool
    this.image = image;
    this.frameWidth = frameWidth;
    this.frameHeight = frameHeight;
    this.frameCount = Math.floor(image.width / frameWidth);
    this.frameDuration = 1000 / fps;        // ms each drawing is held
    this.loop = loop;
    this.frame = 0;                         // which drawing is showing
    this.accumulator = 0;                   // ms of unspent time
    this.lastTime = null;
    this.playing = false;
    this.onFinished = null;                 // set this for one-shot endings
    this.ctx.imageSmoothingEnabled = false; // crisp pixels when scaled
  }

  play() {
    if (this.playing) return;
    this.playing = true;
    this.lastTime = null;
    requestAnimationFrame((t) => this._tick(t));
  }

  stop() { this.playing = false; }

  _tick(now) {
    if (!this.playing) return;
    if (this.lastTime === null) this.lastTime = now;
    // Bank the real time that passed; spend it in frame-sized chunks.
    // This is what keeps 12 fps art correct on a 60 or 144 Hz screen.
    this.accumulator += now - this.lastTime;
    this.lastTime = now;

    while (this.accumulator >= this.frameDuration) {
      this.accumulator -= this.frameDuration;
      this.frame++;
      if (this.frame >= this.frameCount) {
        if (this.loop) {
          this.frame = 0;                    // wrap: cycles loop seamlessly
        } else {
          this.frame = this.frameCount - 1;  // hold the last drawing
          this.playing = false;
          if (this.onFinished) this.onFinished();  // the "settle" hook
          break;  // stop spending banked time — the show is over
        }
      }
    }

    this._draw();
    if (this.playing) requestAnimationFrame((t) => this._tick(t));
  }

  _draw() {
    const sx = this.frame * this.frameWidth;  // where this frame starts in the sheet
    this.ctx.clearRect(0, 0, this.frameWidth, this.frameHeight);
    // 9-argument drawImage: crop [sx,0,w,h] from the sheet → paint at [0,0,w,h].
    this.ctx.drawImage(
      this.image,
      sx, 0, this.frameWidth, this.frameHeight,   // source rectangle (the frame)
      0, 0, this.frameWidth, this.frameHeight     // destination on the canvas
    );
  }
}

// Usage:
const img = new Image();
img.onload = () => {
  const walker = new FlipbookPlayer(
    document.getElementById("stage"), img, 128, 128, 12, true);
  walker.play();
};
img.src = "walk-sheet.png";
```

The timing dial here is yours to build — multiply `frameDuration`, or simply construct the player with a different `fps`. And `onFinished` is the web's `animation_finished` / `OnFinishedPlaying`: the hook where a one-shot settles back to idle.

---

## The personality survives the pipeline

A last connecting thought, because it is the whole point: **nothing in this lesson changed your animation.** The contact pose still carries 80 % of the walk's attitude; the loose parts still lag; the settle still sells the weight. The engine only holds the pages. Which means everything this guide taught about *dials* now has a runtime knob: play-speed is the timing dial (`speed_scale` / `animator.speed` / `SetPlayRate` / `fps`), and swapping flipbooks is recasting. A character who walks at speed 1.0 when rested and 0.6 when wounded is personality animation — running live, in a game, from drawings you made on a phone.

## If you only keep three things

1. The pipeline is identical everywhere: **export transparent PNGs (zero-padded names!) → import → group frames per action → set the animation's fps (12 = "on twos") → loop cycles, signal the end of one-shots.**
2. The names to look for: Godot **AnimatedSprite2D + SpriteFrames** (`play()`, `animation_finished`), Unity **Sprite Editor → Animation Clips → Animator** (`Play()`, triggers, `normalizedTime`), Unreal **Paper 2D sprites → Flipbook** (`SetFlipbook`, `OnFinishedPlaying`), web **CSS `steps()`** or a small **canvas** player.
3. Play-speed is the timing dial from Lesson 1, now scriptable — and one line of Godot Universal Fade (`await Fade.fade_out().finished`) gives every scene change a settle.

## Sources for this lesson (all official docs or the addon's own repository; details in Lesson 19)

- Godot (verified on the 4.7 "stable" docs): *2D sprite animation* — https://docs.godotengine.org/en/stable/tutorials/2d/2d_sprite_animation.html — *AnimatedSprite2D* — https://docs.godotengine.org/en/stable/classes/class_animatedsprite2d.html — *SpriteFrames* — https://docs.godotengine.org/en/stable/classes/class_spriteframes.html — *Importing images* — https://docs.godotengine.org/en/stable/tutorials/assets_pipeline/importing_images.html
- KoBeWi, *Godot-Universal-Fade* (MIT): https://github.com/KoBeWi/Godot-Universal-Fade — Asset Library entry: https://godotengine.org/asset-library/asset/1454
- Unity (verified on the 6000.3 = Unity 6.3 LTS manual): *Cut out sprites (Sprite Editor)* — https://docs.unity3d.com/6000.3/Documentation/Manual/sprite/sprite-editor/use-editor.html — *Sprite import settings* — https://docs.unity3d.com/6000.3/Documentation/Manual/texture-type-sprite.html — *Create a new Animation Clip* — https://docs.unity3d.com/6000.3/Documentation/Manual/animeditor-CreatingANewAnimationClip.html — *Animator Controller* — https://docs.unity3d.com/6000.3/Documentation/Manual/class-AnimatorController.html — *Animation Parameters* — https://docs.unity3d.com/6000.3/Documentation/Manual/AnimationParameters.html — *Animation Events* — https://docs.unity3d.com/6000.3/Documentation/Manual/script-AnimationWindowEvent.html
- Unreal (verified on the current 5.8 docs; Paper 2D unchanged from 5.7): *Paper 2D overview* — https://dev.epicgames.com/documentation/en-us/unreal-engine/paper-2d-overview-in-unreal-engine — *Import & use sprites* — https://dev.epicgames.com/documentation/en-us/unreal-engine/how-to-import-and-use-paper-2d-sprites-in-unreal-engine — *Flipbooks* — https://dev.epicgames.com/documentation/en-us/unreal-engine/paper-2d-flipbooks-in-unreal-engine — *UPaperFlipbookComponent API* — https://dev.epicgames.com/documentation/en-us/unreal-engine/API/Plugins/Paper2D/UPaperFlipbookComponent
- Web: MDN, *drawImage* — https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/drawImage — MDN, *steps() easing function* — https://developer.mozilla.org/en-US/docs/Web/CSS/easing-function/steps

---

# PART VII — THE PIXEL

---

# Lesson 15 — The Grid (Every Pixel Is a Decision)

*Standalone lesson. Everything you need is on this page. Every link in Part VII was fetched and checked live on 20 August 2026.*

## What this lesson gives you

The foundations of pixel art as a *drawing* discipline — what a pixel is, why the size of your canvas is a casting decision, how to draw clean lines on a grid, what a "cluster" is and why it is the real brushstroke of the medium, how to anti-alias by hand (and when not to), and the three outline styles — with every one of those choices read the way this whole guide reads things: as a personality decision.

Why pixel art belongs in an animation guide: it is the native dialect of 2D games (the engines of Lesson 14 were built for it), and at low resolution the dials this book cares about — timing, spacing, silhouette, lag — get *sharper*, not softer. The fewer the pixels, the more each one says. Pedro Medeiros, the pixel artist of *Celeste*, puts it plainly in his free beginner series: "Each pixel you place is a big choice you need to make."

## The pocket mnemonic for Part VII

> **P·I·X·L — "Palette small · Integer scale · eXport PNG · Look at 100 %."**
>
> Four habits that prevent 90 % of beginner pixel-art damage: use few colours; enlarge only by whole numbers (2×, 3×, 4× — never 107 %); save PNG, never JPG; and judge the drawing at its real size, not zoomed in. Every lesson in this Part repeats these four, on purpose.

## Words used in this lesson (fresh definitions, every time)

- **pixel** — "picture element": the smallest square of colour a screen can show. In pixel art it is the only building block, and every one is placed by hand.
- **resolution / canvas size** — the width × height of the image in pixels (16×16, 32×32, 64×64…). "Low resolution" simply means few pixels.
- **sprite** — a 2D image (a character, an object) that a game can place and move on screen; in pixel art, a small drawing on a transparent background.
- **cluster** — a continuous group of touching pixels of the same colour. Clusters, not single pixels, are the brushstrokes of pixel art.
- **orphan pixel** — a single pixel touching no other pixel of its colour. It reads as noise unless it is deliberately a particle, a sparkle, or a texture.
- **jaggies** — unintended bumps and uneven stair-steps along a line or curve, where the steps don't follow a consistent rhythm.
- **doubles** — a spot where a one-pixel line has two pixels side by side at a corner (a little "L"), so the line looks thicker there.
- **pixel-perfect line** — a one-pixel-wide line that connects diagonally corner to corner, with no doubles.
- **anti-aliasing (AA)** — placing in-between colours by hand at the stair-steps of an edge so that, at real size, the edge reads smoother. (Drawing apps also have *automatic* anti-aliasing on their brushes; for pixel art that stays **off** — Lesson 18 shows where.)
- **banding** — parallel bands of colour hugging a shape's edge like contour lines; the eye sees the borders between bands instead of the form.
- **pillow shading** — shading every edge darker towards a bright centre with no light direction, so everything looks like a cushion.
- **outline** — a dark line around a sprite's silhouette. **Selective outlining ("selout")** — an outline that changes colour along its length (lighter where the light hits, darker in shadow) instead of being flat black.
- **silhouette** — the solid-black outline shape of a drawing. If the idea reads in silhouette, it reads.
- **nearest neighbour** — the scaling method that copies each pixel as a hard square with no blur. Apps call it "hard edges," "point," "none," or "pixelated."
- **integer scaling** — enlarging only by whole numbers (2×, 3×, 4×) so every pixel stays a clean square.

## The pixel is the atom

Pixel art is digital art in which the image is built from pixels as the only building block — Wikipedia's definition, and a good one. The *term* was first published in 1982 by Adele Goldberg and Robert Flegal of Xerox PARC, though people had been doing it for at least a decade by then (Richard Shoup's SuperPaint, 1972). What makes it a distinct craft rather than "small drawings" is deliberateness: each pixel is chosen, not generated. Derek Yu (maker of *Spelunky*) opens his free tutorial with the two sentences that matter most: "Pixel art is defined by its constraints," and "A pixel has much more meaning in pixel art than other digital mediums."

Two practical consequences follow immediately:

1. **Automatic tools are switched off.** Soft brushes, blur, gradients, and the automatic anti-aliasing on your pens all place pixels *for* you — and the classic community tutorial by Cure states the community's rule of thumb: "If you can create the image without zooming in, chances are it isn't pixel art." You draw zoomed in, with a hard one-pixel pen, and you *judge* zoomed out.
2. **Every pixel must earn its place.** Pedro Medeiros's note on very low resolution: only the essentials are shown, and the viewer's imagination fills in the rest. Raymond Schlitter (SLYNYRD) says the same thing as a compliment: "The beauty of pixel art comes from the lack of information."

## Resolution is a casting decision

The first choice you make — how many pixels tall the character is — already tells the audience who they are, because proportion changes with size:

| Sprite height | What fits | Typical proportions | Reads as |
|---|---|---|---|
| **8×8** | an icon, a mascot, a tile | 1–1½ heads tall; a face *is* the body | toy, symbol, retro console, cute |
| **16×16** | the classic RPG hero | 2–3 heads tall; head is a third to half the sprite | friendly, young, comic, approachable |
| **32×32** | an expressive action sprite | 3–4 heads; visible hands, hair, costume | capable, characterful — the sweet spot for learning animation |
| **48–64 px and up** | realistic proportions | 4–6 heads; 6–8 for fully realistic figures | serious, adult, elegant, cinematic |

(The head-ratio figures come from PIXNOTE's free character guide; the 6- and 8-head models from SLYNYRD's anatomy post, which adds that "big-headed, or doll-like features tend to read well and capture a lot of expression." SLYNYRD's top-down sprite tutorial notes that at small sizes "the head usually takes up a third to half of the total sprite" so the face can carry expression.)

The personality arithmetic is the same as Lesson 3's shape language: a big head on a short body says *child, pet, comedian*; long proportions say *hero, aristocrat, threat*. A 16-pixel knight is inevitably a little adorable. If you want menace at 16 px, you get it from silhouette and colour, not from anatomy.

**Start small.** Medeiros's beginner guide starts at **16×16** — "a good starting point," he says, for "understanding the interactions of pixels with their neighbors" — then moves to 32×32. Derek Yu: "Making small sprites is about making compromises" — and learning which compromises to make *is* the skill.

**Work at 1×, judge at 100 %.** Keep a second view of the canvas at actual size while you draw zoomed in (Clip Studio: Window > Canvas > New Window; ibisPaint: zoom out, often). Nearly every beginner pixel-art problem is invisible at 800 % and glaring at 100 %.

## Clusters: the brushstroke of pixel art

A **cluster** (reminder: a continuous group of touching pixels of one colour) is how a pixel artist thinks about a drawing — not as lines, but as shapes of colour meeting other shapes. The old Pixelation-forum "Ramblethread" that shaped a generation of pixel artists says it in one line: "The prime job of the pixel artist is to find the ideal shape for every cluster."

Medeiros's second free article teaches a method he calls **cluster sketching**: start with big blobs of colour, refine them in passes, and only *then* worry about edges — no line work first. His rules: aim to *minimise the total number of clusters*, treat diagonal-only touches as weak connections, and eliminate **orphan pixels** (reminder: single pixels touching none of their colour) — one-pixel clusters, he writes, "usually are responsible for the image looking noisy and confusing." His exceptions: texture, anti-aliasing, and strong details (his example is a pair of red eyes). (Lesson 17 will legalise orphans for water droplets and sparks; that's the point — an exception you *chose*.)

Clusters are also **style**. SLYNYRD's Developing Style post: "Lots of simple and repetitive clusters arranged in a controlled manner tends to create a clean or cute look. Widely varied spontaneous clusters creates a sketchy organic look." His Back to Basics post adds the other axis in two captions — "Simple angular clusters makes for a clean sharp look" and "Lots of unique organic shaped clusters makes for a natural look." In this guide's terms: angular = hard, rounded = soft, and your cluster habits become your signature. That is Lesson 8 (elegance vs scruffiness) happening at the scale of a single shape.

## Lines on a grid: jaggies, doubles, and the rhythm rule

A grid only likes two angles. Ramblethread again: "Perfect lines are the 90 and 45 degree ones." A vertical or horizontal line is a run of pixels; a 45° line is steps of one pixel; everything else is a stair-step pattern, and the *rhythm* of the steps is what makes a line look straight or wobbly.

- **A straight line has a constant step length.** A gentle slope might be steps of 3-3-3-3; a steeper one 2-2-2-2. Medeiros's glossary calls these "regular lines," and notes they usually need no anti-aliasing at all.
- **A curve changes its step length *consistently*.** A good curve runs 1-1-2-3-5 as it flattens, or 4-3-2-1-1 as it tightens. Derek Yu defines jaggies on curves precisely: they appear "when the length of the line segments don't grow or shrink in a consistent manner." A lone 2 among 1s, or a 3 sandwiched between 1s, is a jaggy. The goal, in his words, "is simply to minimize them while expressing what you want to express."
- **Doubles** (reminder: two pixels side by side at a corner of a one-pixel line) are the other classic fault; they make a line look lumpy. Purpose-built editors have a "pixel-perfect" pencil mode that removes them as you draw (Lesson 18); in Clip Studio and ibisPaint you draw slowly and erase the corner pixel by hand. MortMort's short video on "doubles, jaggies & outline" is the fastest way to train your eye for both.
- **Lines are expensive.** Medeiros, in his free article on lines: at low resolution a line costs a full pixel of width, so minimise lines and let shadow or colour contrast do their job; and keep the *exterior* outline darkest with lighter internal lines so the interior doesn't fragment.
- **Design for the grid.** Arne Niklas Jansson's long-running pixel tutorial makes the point with a Dalek: he kept its conical shape but "avoided the longer slopes by breaking them into steps of 90 and 45 degrees" — edges the grid can render crisply, where long shallow slopes always look a little off. Medeiros's low-resolution notes agree — 90° for sharpness, 45° for pointed things like blades.

> **Pin this:** on a grid, a line's *rhythm* is its straightness. Consistent steps = straight. Consistently changing steps = curve. Anything else = jaggy.

## Anti-aliasing by hand (and when not to)

Your app's automatic anti-aliasing is off; now you put the smoothing back *by choice*, one pixel at a time. Medeiros's anti-alias article gives the working rules:

- Anti-alias slopes and curves whose steps are **longer than one pixel** — that is where the staircase shows. Do **not** anti-alias 45° lines, pure horizontals/verticals, or 1×1 staircases: they're already as smooth as the grid can make them, and AA just blurs them.
- Use one or two in-between tones at a corner, never a gradient. PIXNOTE's guide: "AA is for blending at actual size, not for looking clean when zoomed in."
- Too much AA is mud. "If the anti-alias is doing more harm than good, just remove it."
- **Never anti-alias outward past the silhouette of a game sprite.** Derek Yu: "Be careful not to anti-alias the outside of a sprite used for a game" — you don't know what background it will sit on, and a halo of in-between colours will look like a smudge on every background but one. PIXNOTE adds: don't overuse AA on tiny sprites (16 px or smaller); there's barely room for it.

Two faults that masquerade as shading belong here too:

- **Banding** (reminder: parallel bands hugging an edge like contour lines). Jansson: "Banding draws attention to the borders between color fields." Fixes, from Medeiros: compress the bands into a small area, or change the *direction* of the transition so it no longer runs parallel to the edge.
- **Pillow shading** (reminder: dark edges, bright middle, no light direction). Medeiros's shading article: decide the light source *first*; flat faces get one colour, rounded forms get a ramp, and "Good pixel art eliminates all unnecessary detail." (Lesson 16 is all about those ramps.)

## Outlines: three styles, three personalities

There are exactly three ways to end a sprite, and each casts it differently.

1. **Full dark outline** (black, or a very dark colour) — maximum readability on any background, bold and toy-like; the classic arcade and cartoon look; also the right choice for icons and UI.
2. **Selective outline ("selout")** — the outline lightens where the light hits and darkens in shadow; PIXNOTE suggests the outline colour be "a darker version of the body's darkest tone" rather than black. Derek Yu's tutorial walks through replacing a black outline with lighter colours on lit areas and darker shadow colours for internal segmentation. Reads as lit, dimensional, naturalistic.
3. **No outline** — shape meets shape, like a painting. Atmospheric and soft, but it lives or dies on contrast with whatever is behind it. Thomas Feichtmeir (Cyangmou)'s free readability chart is, in his words, "a tut about shape contrasts" — **readability is governed by shape contrast**, not by how many pixels you fuss over. In the notes under his companion *Shapes and Outlines* chart he spells out the mechanism: two close colours can read as one shape, while too much contrast between them reads as two; and in the readability chart's comments he says he prefers one of the lighter outline treatments at small sizes and a fuller one for bigger sprites.

Jansson's warning applies to all three: "Excessive black lining might arise from some sort of compulsion to mark and separate every detail," and it flattens the form. Lighten the upper outline, keep the lower one dark, and the sprite is suddenly lit from above.

## The silhouette test at sixteen pixels

Lesson 3's two-second test works even better in pixels: fill the sprite solid black. Does it still read — the pose, the prop, the species? PIXNOTE's character guide uses exactly this test, and adds the most pixel-specific fact in the whole lesson: **moving an eye by one pixel changes the expression.** SLYNYRD's tiny-sprites post says the same about posture: "Shift one or two pixels and boom, a turn of the head, or change of posture." Keep that in your pocket for Lesson 17 — the head turn of Lesson 5 is, at 16 px, a two-pixel event.

## The personality dial for this lesson

| Choice | Reads as |
|---|---|
| Big head, short body (8–16 px) | cute, young, comic, approachable |
| Long proportions (48 px and up) | serious, elegant, heroic, adult |
| Angular clusters, 90°/45° edges | hard, mechanical, armoured, menacing |
| Rounded, stepped clusters | soft, organic, friendly |
| Full black outline | bold, toy-like, cartoon, arcade |
| Selective outline | lit, dimensional, naturalistic |
| No outline | atmospheric, painterly, dreamy |
| Generous hand AA | smooth, refined, calm ("16-bit lavish") |
| No AA, crisp steps | punchy, modern-retro, energetic |
| A few deliberate orphan pixels | scruffy, glittery, nervous — *if chosen* |

## Try it — Clip Studio Paint EX

(The complete pixel-perfect setup, with every menu path, is in Lesson 18; this is the short version.) File > New, unit **px**, **32×32**. Turn on the grid (View > Grid) and set it to one pixel (View > Grid/Ruler bar settings: Gap 1 px, Number of divisions 1). Pick the **Dot pen** — it lives in the Pen tool's **Marker** group — which is fixed at one pixel with anti-aliasing off. In the Fill tool, turn **Anti-aliasing** off and **Area scaling** off. Open a second view at 100 % (Window > Canvas > New Window). Now draw Medeiros's beginner objects: a mug, a skull, a sword, a face — four colours each. When you want to share, *don't* scale in the export dialog: Edit > **Change Image Resolution**, 800 %, Interpolation **Hard edges (nearest neighbor)** — then export PNG.

## Try it — ibisPaint X

New canvas → **Any Size**, 32×32 (this is the setup in ibisPaint's own lecture "53. Display Grid on the Canvas"). View menu → **Grid** on; View menu → **Display when zooming** → **Pixelated**. Brush: **Digital Pen** at **1.0 px**, and in the brush's parameters switch **Antialias** off. Draw the same four objects. Save as **PNG** with Transparent on. Zoom out constantly — the phone screen is your 100 % view.

## Try it — a free pixel editor (optional)

Pixelorama (desktop or in the browser), LibreSprite, or Piskel (browser) give you a one-pixel pencil with a **pixel-perfect** mode, a one-pixel grid, and a palette panel out of the box — nothing to configure. Lesson 18 compares them. For this lesson any of them is fine: open it, set 32×32, draw the four objects.

## Drills (one sitting each)

1. **The four objects.** Mug, skull, sword, face — 16×16, four colours, no outline first, then outlined. Which reads better at 100 %?
2. **The line gym.** Draw ten curves with the one-pixel pen. Fix every jaggy by making step lengths change consistently; erase every double.
3. **Outline trio.** One 32×32 character three ways: black outline, selout, no outline. Name the person each one has become.
4. **The one-pixel expression.** Copy a 16×16 face four times. Move only the eyes or mouth by one pixel each. Write the mood under each.

## If you only keep three things

1. **Pixel art is deliberate:** automatic smoothing off, one-pixel pen on, draw zoomed in, judge at 100 %. Think in **clusters**, hunt **orphan pixels**, keep line rhythms consistent.
2. **Resolution and outline style are casting decisions** — a 16-px big-head is adorable before it moves; selout lights a character, black outline makes a toy, no outline makes a painting.
3. **P·I·X·L:** palette small, integer scale, export PNG, look at 100 %.

## Sources for this lesson (all free & legal; details in Lesson 19)

- Pedro Medeiros (Saint11), *Pixel Art Articles* — the free beginner series (guide, clusters, shading, anti-alias & banding): https://saint11.art/pixel_articles — and *Working with lines* (on Medium; free to read): https://medium.com/pixel-grimoire/how-to-start-making-pixel-art-7-e504bfa4ddf2 — *My Thoughts on Very Low Resolution*: https://saint11.art/blog/thoughts_on_low_resolution — glossary: https://saint11.art/blog/glossary/
- Derek Yu, *Pixel Art Tutorial: Basics*: https://www.derekyu.com/makegames/pixelart.html
- PIXNOTE, *Getting Started*: https://pixnote.net/en/learn/getting-started/ — *Outlines & Anti-Aliasing*: https://pixnote.net/en/learn/outlines/ — *Characters*: https://pixnote.net/en/learn/character/ — glossary: https://pixnote.net/en/learn/glossary/
- Raymond Schlitter (SLYNYRD), *Pixelblog 5 – Back to Basics*: https://www.slynyrd.com/blog/2018/5/16/pixelblog-5-back-to-basics — *7 – Developing Style*: https://www.slynyrd.com/blog/2018/7/14/pixelblog-7-developing-style — *17 – Human Anatomy*: https://www.slynyrd.com/blog/2019/5/21/pixelblog-17-human-anatomy — *22 – Top Down Character Sprites*: https://www.slynyrd.com/blog/2019/10/21/pixelblog-22-top-down-character-sprites — *47 – Tiny Pixels*: https://www.slynyrd.com/blog/2023/11/26/pixelblog-47-tiny-pixels
- Cure, *The Pixel Art Tutorial* (Pixel Joint forum): https://pixeljoint.com/forum/forum_posts.asp?TID=11299&PID=139318 — and the Pixelation forum's *Ramblethread*: https://web.archive.org/web/20250323171825/https://pixelation.org/index.php?topic=8110.0
- Arne Niklas Jansson, *Pixel Art Tutorial*: https://androidarts.com/pixtut/pixelart.htm
- Thomas Feichtmeir (Cyangmou), *Readability – Pixel art style possibilities*: https://web.archive.org/web/20220914214941/https://www.deviantart.com/cyangmou/art/Readability-Pixel-art-Style-possibilities-723970229 — *Pixel Art – Shapes and Outlines*: https://web.archive.org/web/20221205174609/https://www.deviantart.com/cyangmou/art/Pixel-Art-Shapes-and-Outlines-722784595 (the original DeviantArt pages have been taken down, so both links are Wayback Machine copies)
- MortMort, *3 PixelArt Techniques/Common Mistakes (Doubles, Jaggies & Outline)* (video): https://www.youtube.com/watch?v=gW1G_FLsuEs — *Basic Anti-Aliasing for beginners* (video): https://www.youtube.com/watch?v=UN-m3o9V7kk
- AdamCYounis, *Pixel Art Class – What is Pixel Art?* (video): https://www.youtube.com/watch?v=7BWr2tlK-4c
- Lospec, *Pixel Art: Where to Start*: https://lospec.com/pixel-art-where-to-start
- Wikipedia, *Pixel art*: https://en.wikipedia.org/wiki/Pixel_art — *Spatial anti-aliasing*: https://en.wikipedia.org/wiki/Spatial_anti-aliasing — *Sprite (computer graphics)*: https://en.wikipedia.org/wiki/Sprite_(computer_graphics)

---
# Lesson 16 — Colour in Pixels (Palettes, Ramps, Hue-Shifting, Dither, and the Recolour Trick)

*Standalone lesson. Everything you need is on this page. Every link in Part VII was fetched and checked live on 20 August 2026.*

## What this lesson gives you

How pixel artists choose colours — why a *small* palette produces better art than a big one, how to build a ramp that glows instead of going muddy (hue-shifting), what dithering is for and when it is noise, and the oldest personality trick in video games: the palette swap, where one drawing becomes a different character by changing its colours alone. That last one is this guide's thesis — *same action, different person* — in its purest form.

## The pocket mnemonic for Part VII

> **P·I·X·L — "Palette small · Integer scale · eXport PNG · Look at 100 %."**
>
> Few colours; enlarge only by whole numbers (2×, 3×, 4×); save PNG, never JPG; judge at real size. This lesson is the **P**.

## Words used in this lesson (fresh definitions, every time)

- **palette** — the fixed list of colours an image is allowed to use. In pixel art you choose it *before* you draw.
- **hue / saturation / value** — the three dials of a colour: **hue** is the colour family (red, teal, violet); **saturation** is its intensity (grey → vivid); **value** (also *brightness* or *lightness*) is how light or dark it is. Most apps show them as an HSV or HSB picker.
- **ramp** — a short row of palette colours from dark to light used to shade one material (skin, metal, cloth).
- **hue-shifting** — moving the *hue* as a ramp goes from shadow to light (typically cooler in shadow, warmer in light) instead of only changing the value.
- **dithering** — placing two colours in a pattern (checkerboard, stripes, ordered grids) so that, at real size, the eye blends them into a third colour or a texture.
- **banding** — parallel bands of colour hugging a shape's edge like contour lines; the eye sees the borders instead of the form.
- **pillow shading** — shading every edge dark towards a bright middle with no light direction; everything looks like a cushion.
- **cluster** — a continuous group of touching pixels of the same colour; the brushstroke of pixel art.
- **indexed colour** — an image format in which each pixel stores a *palette number* rather than a colour. Change the palette and the whole picture recolours at once.
- **palette swap** — reusing one sprite with a different palette to create a "new" character.
- **1-bit** — a palette of exactly two colours.
- **contrast** — the difference in value between neighbouring areas; it is what makes a sprite readable at a glance.

## Why fewer colours make better pixel art

Every serious pixel-art teacher says the same thing in different words. Cure's classic tutorial: "If you can't make a good sprite in 4 colors, using 40 colors isn't going to help." The Pixelation Ramblethread: "If you can't render your item with 4 colors in a gameboy screen, you will not be able to do any better at 800x600 with 256 colors or more." Pedro Medeiros: "My main objective when it comes to colors is to do as much as I can with as little as possible."

Three reasons it's true, not just tradition:

1. **Readability.** A sprite 16 pixels tall is read in a glance. Each extra colour is one more boundary the eye must resolve, and two colours that are close in value merge into one shape anyway — so a small set of clearly separated colours reads faster than a large set of near-neighbours.
2. **Clusters.** A small palette forces big clusters (reminder: groups of same-colour pixels), and big clusters are what make pixel art look designed rather than noisy.
3. **Consistency.** Ten sprites drawn from one shared palette belong to one world. Medeiros's post on consistency: pick a limited, reusable palette for the whole project and break it only with intent.

**Numbers to start with.** Medeiros's beginner guide: begin with 4 colours (he recommends the free *ARQ4* palette), then 12 (*AAP-Micro12*), then up to 16 at 48×48. PIXNOTE: 3–5 colours for a first object; for a character, 2–3 colours per body part and 6–12 in total. Derek Yu works from a 32-colour palette and notes that 16 is also common.

**Borrow a palette; don't build one yet.** Lospec's *Where to Start* page recommends exactly this — use a ready-made palette so colour choice doesn't stall you. Lospec's Palette List holds thousands, each downloadable in every app format. Names worth knowing: **ENDESGA 32** (32 colours, the modern indie workhorse), **DawnBringer 32** (32 — the palette Aseprite ships as its default, per its own docs), **PICO-8** (16, the fantasy console's palette), **Sweetie 16** (16, a modern favourite), **AAP-64** (64, when you need range). Where these come from historically: early hardware stored images as **indexed colour** — a few bits per pixel pointing at a palette of 4, 16, or 256 entries — so the limit was the machine's, and artists learned to make it sing.

## Ramps and hue-shifting: the most important trick

A **ramp** (reminder: a row of colours from dark to light for one material) drawn by only darkening the base colour goes grey and muddy. Arne Niklas Jansson's tutorial puts the diagnosis in one sentence: "In nature, the hue of a color often changes as it goes from light to dark, so a black-pink-white ramp can look muddy and artificial." The cure is **hue-shifting** — and PIXNOTE's shading guide calls it, flatly, "the most important technique for attractive pixel art shadows."

The recipe, gathered from three teachers (who agree on the hue and disagree, productively, on the saturation):

- **Shadows: lower value, hue nudged cooler** (towards blue/violet) — PIXNOTE's shading table adds *slightly higher* saturation in the shadow; Medeiros's own example goes the other way, "a little more blue and less saturated (colder)." **Light: hue nudged warmer** (towards yellow/orange) and, in Medeiros's example, "a little more yellow and saturated (warmer)." His general preference: "usually a hot light and cold shadows, but sometimes the opposite can work too."
- **How much?** Raymond Schlitter builds nine-swatch ramps in HSB with "20 degrees of positive hue shift between each swatch"; in his example the saturation peaks in the middle swatch — "but this is not a hard rule. Generally, darker colors have more saturation" — and the value steps grow smaller near white, so the top of a ramp never burns. His warning is the funniest line in pixel-art pedagogy: "The biggest mistake is combining high saturation and brightness, unless you want to burn some eyeballs."
- **Avoid 100 % saturation** anywhere. Keep large areas low-saturation and spend saturation on small accents — eyes, a gem, a glow (Medeiros).
- **Light source first, always.** Schlitter: "A light source should be established at the very start of any illustration," and "Light is one of the biggest factors in determining mood." Decide where the light is and every ramp knows which end is which.
- **How many tones?** PIXNOTE's working numbers: a 16×16 sprite needs about **two** tones per material; 64×64 and up, **four to five**. More tones than that is banding waiting to happen.
- **Check the values.** Desaturate the image (Derek Yu's final step) or, in Clip Studio, drop a black layer set to the **Color** blending mode on top (the official Art Rocket pixel tutorial's trick): if the sprite still reads in grey, the values are right; if it vanishes, the hues were doing all the work and will fail at a glance.

> **Pin this:** a ramp is three dials turning at once — value down, hue towards cool, and saturation *decided* (PIXNOTE nudges it up in shadow, Medeiros down; pick one and be consistent) — not one dial turning down.

## Dithering: texture, gradient, and restraint

**Dithering** (reminder: two colours in a pattern that the eye blends) is how a 4-colour Game Boy showed a sunset. The word is older than computers — Wikipedia traces it to WWII bomb computers that ran more accurately while *vibrating*, from the Middle English "didderen," to tremble — and ordered (Bayer) dithering dates from 1973.

Patterns, as PIXNOTE lists them: **checkerboard** (the 50/50 workhorse), **ordered/Bayer** (a tiled threshold grid, with a recognisable cross-hatch look), **stripes**, **crosshatch**, **random**. A gradient is built in density stages: 100 % A → mostly A → checkerboard → mostly B → 100 % B.

The rules, because dithering is the most over-used tool in the medium:

- **Only between colours of similar value.** High-contrast dithering reads as a net thrown over the drawing.
- **Never dither an outline, and never dither the whole screen.** PIXNOTE: "Don't fill the entire screen with dithering (gets noisy)."
- **Best uses:** large flat areas that need life, and fighting banding (Derek Yu). Jansson's higher bar: dithering is most effective "when I can make it do double duty — create a gradient AND portray an appropriate texture" (stone, sand, cloth weave).
- **Judge at 100 %.** A pattern that looks like a nice weave at 800 % may look like static at real size.

Dithering is also a *dialect* — the Lesson 8 dial: heavy, textured dither reads as gritty, retro-PC, scruffy; clean flat clusters read as modern, elegant, calm. Two games with the same palette can feel decades apart on this choice alone.

## The recolour trick: palette swaps as casting

Because so much pixel art is (or behaves like) **indexed colour** (reminder: pixels store palette numbers, not colours), swapping the palette recolours every sprite that uses it — instantly, for free. Games have used this since the beginning: Pac-Man's four ghosts are one sprite in four palettes; Luigi began life as a green Mario; fighting games recolour the second player in a mirror match; and whole casts of ninjas were born from one set of frames because the hardware had no memory for more.

For this guide, the trick matters because it isolates the thesis. Same drawing, same animation — change only the colours:

| Recolour | Reads as |
|---|---|
| Warm, mid-saturation, strong value contrast | hero, friendly, energetic |
| Cool, desaturated, low contrast | tired, cold, ghostly, sick |
| Dark body, one hot saturated accent | villain, danger, "don't touch" |
| Pale, low-contrast pastels | gentle, dreamy, fragile, healer |
| High-contrast black/white with one colour | graphic, modern, stylish |
| Complementary accent on the eyes or weapon | focus, intent, magic |

PIXNOTE's character guide uses this deliberately for class archetypes — sturdy warrior in metal greys, mage in a trapezoid robe of purple or blue, healer in soft whites. That's Lesson 3 shape language plus colour, at 16 px.

**How to do it in your apps (full setup in Lesson 18):** in Aseprite or Pixelorama, work in **indexed** mode and edit the palette — the sprite follows. In Clip Studio Paint, the **Auto select** tool with Color margin 0, Area scaling off, and anti-aliasing off grabs every pixel of one colour so Edit > Fill can replace it; for a whole-cast recast, Edit > Tonal Correction > Hue/Saturation/Luminosity shifts every colour at once. In ibisPaint X, the **Bucket** with Strength 0 % and Expansion 0 px replaces exactly one colour at a time.

## The personality dial for this lesson

| Choice | Reads as |
|---|---|
| 4–8 colours, big clusters | confident, iconic, "designed" |
| 32+ colours on a tiny sprite | fussy, noisy, hard to read |
| Hue-shifted ramps | alive, lit, warm-blooded |
| Straight value ramps | grey, plastic, older-software |
| High saturation + high value together | loud, eye-searing, cheap |
| Low-saturation fields + one saturated accent | elegant, focused, expensive |
| Heavy dithering | gritty, retro, textured, scruffy |
| No dithering, flat clusters | clean, modern, calm, elegant |
| 1-bit | graphic, stark, witty (Brandon James Greer's 1-bit video shows how much two colours can do) |

## Try it — Clip Studio Paint EX

Download **ENDESGA 32** (or any Lospec palette) as a **PNG (1×)**, drop it onto a layer in a 64×64 canvas, and register each colour to a **Color Set**: Window > Color Set, **Edit color sets** (the spanner icon) → new set, then eyedrop each swatch and press **Add Color** at the bottom of the palette. Draw one sphere three times with the Dot pen (Pen tool > Marker group): (a) a straight value ramp, (b) a hue-shifted ramp, (c) the light from the other side. Drop a black layer on top set to the **Color** blending mode and look at the values. Scale for sharing with Edit > Change Image Resolution → **Hard edges (nearest neighbor)**, never in the export dialog.

## Try it — ibisPaint X

32×32 canvas, View menu → **Grid** on and **Display when zooming → Pixelated**, **Digital Pen** at 1.0 px with **Antialias** off. Build a four-colour palette by hand from one hue (ibisPaint 14 keeps multiple named colour palettes). Draw a mushroom; shade it with two tones per material. Then do the recolour trick: duplicate the canvas and use the **Bucket** with Strength 0 % and Expansion 0 px to swap each colour — same mushroom, poisonous.

## Try it — a free pixel editor (optional)

In Aseprite or Pixelorama, make the sprite in **Indexed** mode and load a Lospec palette (`.gpl` or the PNG). Draw once; then duplicate the file and *only* edit the palette entries to make the four recasts in the table above. No pixel moves; four characters appear.

## Drills (one sitting each)

1. **Four colours, one hero.** A 16×16 character in ARQ4 (white, two blues, black). If it reads, you have learned clusters and contrast in one sitting.
2. **Ramp lab.** One sphere, three ramps (straight, hue-shifted, over-shifted). Desaturate all three. Which survives?
3. **The recolour cast.** One 32×32 sprite, four palettes: hero, villain, ghost, exhausted. Show someone only the colours — can they cast them?
4. **Dither discipline.** A 32×32 sky: (a) 8 banded colours, (b) 3 colours with checkerboard transitions, (c) 3 colours, hard edges. Judge at 100 %, not 800 %.

## If you only keep three things

1. **Small palettes read faster, cluster better, and unify a project.** Start at 4–12 colours, borrowed from Lospec.
2. **A ramp turns three dials** — value down, hue towards cool in shadow and warm in light, saturation decided on purpose. Light source first. Check the values in grey.
3. **Dither only between similar values, never on outlines or everywhere** — and remember the palette swap: colour alone can recast a character without moving a pixel.

## Sources for this lesson (all free & legal; details in Lesson 19)

- Raymond Schlitter (SLYNYRD), *Pixelblog 1 – Color Palettes*: https://www.slynyrd.com/blog/2018/1/10/pixelblog-1-color-palettes — *6 – Light and Shadow*: https://www.slynyrd.com/blog/2018/6/15/pixelblog-6-light-and-shadow
- Pedro Medeiros (Saint11), *Basic Color Theory*: https://saint11.art/pixel_art_articles/article6 — *Basic Shading*: https://saint11.art/pixel_art_articles/article4 — *Consistency*: https://saint11.art/blog/consistency/
- PIXNOTE, *Shading & Lighting*: https://pixnote.net/en/learn/shading/ — *Dithering*: https://pixnote.net/en/learn/dithering/ — *Characters*: https://pixnote.net/en/learn/character/
- Derek Yu, *Pixel Art Tutorial: Basics* (shading, selout, dithering, the desaturation check): https://www.derekyu.com/makegames/pixelart.html
- Arne Niklas Jansson, *Pixel Art Tutorial* (ramps, banding, dithering) — https://androidarts.com/pixtut/pixelart.htm — and *PSG Art Tutorial* (hues, skin, saturated gradients): https://androidarts.com/art_tut.htm
- Cure, *The Pixel Art Tutorial* (Pixel Joint): https://pixeljoint.com/forum/forum_posts.asp?TID=11299&PID=139318 — Pixelation, *Ramblethread*: https://web.archive.org/web/20250323171825/https://pixelation.org/index.php?topic=8110.0
- Thomas Feichtmeir (Cyangmou), *Readability – Pixel art style possibilities*: https://web.archive.org/web/20220914214941/https://www.deviantart.com/cyangmou/art/Readability-Pixel-art-Style-possibilities-723970229
- Lospec, *Palette List*: https://lospec.com/palette-list — *ENDESGA 32*: https://lospec.com/palette-list/endesga-32 — *DawnBringer 32*: https://lospec.com/palette-list/dawnbringer-32 — *PICO-8*: https://lospec.com/palette-list/pico-8 — *Sweetie 16*: https://lospec.com/palette-list/sweetie-16 — *AAP-64*: https://lospec.com/palette-list/aap-64 — *ARQ4*: https://lospec.com/palette-list/arq4 — *AAP-Micro12*: https://lospec.com/palette-list/aap-micro12 — *Where to Start*: https://lospec.com/pixel-art-where-to-start — Aseprite docs, *Default palette* (DawnBringer 32): https://www.aseprite.org/docs/default-palette/
- AdamCYounis, *Pixel Art Class – Palettes & Colour* (video): https://www.youtube.com/watch?v=hkrK65FPmDI — *Lighting & Shading Basics* (video): https://www.youtube.com/watch?v=u7v4uEDwW9o — *Palette Mixing Tutorial* (video): https://www.youtube.com/watch?v=rSy9xef-MXM
- Brandon James Greer, *1-Bit Pixel Art Techniques* (video): https://www.youtube.com/watch?v=0BZwEoj50uw — and on Celsys' official channel, *3 shading and coloring tips for clean pixel art!*: https://www.youtube.com/watch?v=ihmH5jFn_a4 — *1 must-know tip when coloring pixel art!*: https://www.youtube.com/watch?v=lCv-HAEHMVE
- Dado Almeida, *How to Draw Pixel Art: A Tutorial* (Celsys' official Art Rocket site — NES palette, the Color-mode value check): https://www.clipstudio.net/how-to-draw/archives/161082
- Tsugumo, *So You Want To Be A Pixel Artist?* — chapter 6 on dithering and key colours (community mirror of a free 2000s classic): http://www.geocities.ws/skulkraken2002/Tsugumo/chapter6.htm
- Wikipedia, *Dither*: https://en.wikipedia.org/wiki/Dither — *Ordered dithering*: https://en.wikipedia.org/wiki/Ordered_dithering — *Indexed color*: https://en.wikipedia.org/wiki/Indexed_color — Giant Bomb, *Palette Swap* (definition; community wiki): https://www.giantbomb.com/wiki/Concepts/Palette_Swap — TV Tropes, *Palette Swap* (the game-history examples; community wiki): https://tvtropes.org/pmwiki/pmwiki.php/Main/PaletteSwap

---
# Lesson 17 — Pixel Animation (Moving Less Than a Pixel, and Why Fewer Frames Can Say More)

*Standalone lesson. Everything you need is on this page. Every link in Part VII was fetched and checked live on 20 August 2026.*

## What this lesson gives you

The whole of this guide, translated into a grid. When the smallest possible move is a full pixel and a character is sixteen of them tall, **spacing** becomes a puzzle, **timing** becomes a matter of milliseconds, and the answer to "how many drawings?" is often "fewer than you think." You'll get: the spacing problem and its solutions (including *sub-pixel animation*, the medium's signature trick), honest frame budgets, the pixel idle, the pixel walk and run, jumps and attacks with smears and holds, hair and cloth and the elements at one pixel per frame — and every one of them as a personality decision, because that is the only reason to animate anything.

## The two mantras

> **Cause first → body next → loose parts last → settle.** (C·B·L·S — "Cool Bodies Lag Softly.") The order you animate everything, in pixels as on paper.
>
> **P·I·X·L — "Palette small · Integer scale · eXport PNG · Look at 100 %."** The four pixel-art habits. For animation the **L** matters most: *always judge the loop at real size and real speed.*

## Words used in this lesson (fresh definitions, every time)

- **frame** — one single image in an animation; **fps (frames per second)** — how many frames are shown each second.
- **milliseconds per frame (ms)** — many pixel-art tools time each frame in milliseconds instead of fps. Conversions you'll use constantly: **100 ms = 10 fps · 125 ms = 8 fps · 83 ms ≈ 12 fps · 50 ms = 20 fps.** One frame can have its own duration, which is how you make a *hold*.
- **timing** — how many frames (or milliseconds) an action takes; the clock. **spacing** — how far the drawing moves between one frame and the next; the handwriting.
- **hold** — a drawing shown longer than its neighbours. In pixel art, holds do much of the acting.
- **key drawing** — one of the main storytelling drawings; **inbetween** — a drawing that fills the gap between two keys.
- **cycle / loop** — a set of drawings that repeats seamlessly; the last flows back into the first.
- **sub-pixel animation** — faking movement smaller than one pixel by changing the *colours* at an edge instead of moving whole pixels.
- **smear** — a deliberately stretched or multiplied drawing shown for a frame or two to sell extreme speed.
- **squash and stretch** — a form flattening under force and lengthening with speed, its volume staying constant (in pixels: roughly the same *number* of pixels).
- **anticipation** — a small preparatory move, often in the opposite direction, before the main action.
- **follow-through** — loose parts (hair, cloth, tails) keep moving after the body stops; **overlapping action** — different parts start and stop at slightly different times; **overshoot and settle** — going slightly past the target, then easing back.
- **onion skin** — a ghost view of the frames before and after the one you're drawing.
- **Contact / Down / Passing / Up** — the four cornerstone drawings of a walk: feet widest apart and both touching; weight dropping onto the front leg; the free leg passing the planted one; the body at its highest as the toes push off.
- **sprite sheet** — many frames packed into one image in a grid, which a game engine slices back apart.

## The spacing problem: one pixel is a big step

**Spacing** (reminder: the distance moved per frame) is the dial that creates weight and ease in Lesson 1's bouncing ball. In pixel art it comes with a floor: nothing can move less than one whole pixel. On a character sixteen pixels tall, that floor is a sixteenth of the entire body per frame. Tsugumo's old sprite-animation chapter makes the point with a 20-pixel-wide fighter — a one-pixel shift is a twentieth of him, a lurch, not a breath.

So the slow, subtle motions that make a character feel *alive* — breathing, swaying, drifting — can't be made by sliding pixels smoothly. Four solutions, and real pixel animation uses all of them:

1. **Move the timing instead of the drawing.** Hold frames longer. Two positions one pixel apart, held 300 ms each, read as calm; the same two positions at 80 ms read as a twitch.
2. **Move part of the shape, not the whole.** A breathing chest is the top edge of the torso rising one pixel while the feet stay planted; SLYNYRD's fighting idle moves the head and torso one pixel, the shoulders, elbows and outer fist two, the inner fist four — a chain of different amounts, which is Lesson 9's overlapping action drawn in integers.
3. **Change colours instead of positions — sub-pixel animation** (next section).
4. **Embrace the bounce.** A cheerful 2-pixel bob is not a failure of subtlety; it's a casting choice (goofy, eager, cartoon). PIXNOTE's rule for squash and stretch in pixels: "Even 1 pixel of change is effective."

## Sub-pixel animation: moving less than a pixel

Picture the right-hand edge of a red shape against a dark background. To slide that edge right by *half* a pixel, you don't move anything: you recolour the first background pixel beyond the edge to a colour halfway between red and the background. Next frame, make it fully red — the edge has now moved a whole pixel, in two soft steps instead of one hard one. Move the trailing edge the same way (half-tone, then background) and the whole shape appears to glide. PIXNOTE's glossary defines the technique exactly that way: "simulating movement smaller than one pixel through color changes."

Where it shines: breathing, idle sway, a slowly turning planet, drifting clouds, hair lifting in a draught, a pupil sliding across an eye — anything slow and small. Where it fails: fast motion, where the half-tones just look like blur. The cost: extra palette colours (the in-betweens), so it pairs naturally with the ramps of Lesson 16 — the half-tone is usually a colour you already own. Pedro Medeiros has a free animated board on it in his tutorial set, and AdamCYounis's *Pixel Art Class – Sub-Pixel Animation* demonstrates it step by step.

**Personality:** sub-pixel motion reads as *calm, alive, composed, expensive* — Lesson 8's elegance. Whole-pixel bobbing reads as *energetic, comic, retro*. Same character; choose the dialect.

## Frame budgets: fewer can say more

The guide's hand-drawn lessons live on twos at 12 drawings a second. Pixel animation often runs on *far* fewer drawings, and not only to save work — Raymond Schlitter's Intro to Animation says why: "Too many frames can leach the energy from your motion." His timing equivalence is worth memorising: an 8-frame cycle at 80 ms per frame and a 4-frame cycle at 160 ms per frame take **the same time to loop** — the 8-frame version is smoother, the 4-frame version punchier. Same clock, different handwriting (Lesson 1 again).

| Frames in the cycle | Typical use | How it feels |
|---|---|---|
| **2** | blink, torch flicker, a tiny idle | twitchy, mechanical, charmingly retro |
| **3** | the *Mega Man* run — two stride poses and a pass, played A-B-C-B | kinetic; Schlitter: "With just 3-frames it captures more kinetic energy" |
| **4** | the classic NES walk: contact–pass–contact–pass | brisk, economical, instantly readable |
| **6** | walks and runs with a Down pose | Schlitter's "nice middle ground" between economy and fluidity |
| **8** | fluid walks and runs; an 8-frame bird flight | smooth, weighty, elegant |
| **12–16** | luxurious cinematic cycles | lavish — and at risk of going floaty |

Speeds to start from (PIXNOTE's working numbers): **8–12 fps** as the standard feel for pixel animation; **4–6 fps** for idles and ambient effects; **15–24 fps** for attacks and anything that needs snap. Schlitter's own loops: walks around **120 ms** per frame, runs around **60 ms**, idles at **100 ms** with faster frames where gravity takes over.

And the rule that pixel animators repeat like a prayer, because a loop shows every frame hundreds of times: hold the extremes longer than the inbetweens (Schlitter's top-down characters; Tsugumo held breath-peaks about twice as long as the transitions). Schlitter: "A single misplaced pixel can create an eyesore."

## The pixel idle: the personality machine of games

An **idle** is what a game character does while the player does nothing — and Wikipedia's history of the idle animation notes it exists precisely "to give personality towards games and their characters," the one moment they act on their own. Sonic's impatient foot-tap is the famous example. Schlitter is blunter: "A character's idle loop is one of the most effective means of displaying personality, and bringing the sprite to life."

The classic recipe, from Tsugumo's chapter on breathing and Sandro Maglione's free character-animation guide:

- **4 frames** (2 is possible, 6–8 for a fighter). The body rises and falls **one pixel**; the chest edge lifts; the head follows a frame later; hair or a scarf follows a frame after that. Maglione's finding: "Leaving 1 frame delay between the body and hair movement makes it look like the hairs are floating, following the movement of the body." That is *cause → body → loose parts → settle*, in four frames.
- **Hold the top and bottom.** Frames at the peaks last roughly twice as long as the transitions.
- **Build by shifting, not redrawing.** Duplicate the frame, nudge the cluster, fix the seams. Volumes stay consistent for free.
- **Timing with gravity:** Schlitter's 8-frame fighting idle plays frames 1–4 at 100 ms and frames 5–8 at 50 ms — slow up, quick down — so the bounce has weight.

And the casting table, which is the whole reason to bother. Tsugumo compared two Capcom fighters: one bounces restlessly on his toes, the other stands almost motionless — "The animation you give your character should be based on their personality and fighting style." His closing advice: "Less is more."

| Idle recipe | Reads as |
|---|---|
| sub-pixel breath, 4 frames at 5 fps, hair drifting a frame late | calm, composed, confident, alive |
| 2-pixel bob, 4 frames at 10 fps, one asymmetric twitch | nervous, eager, comic |
| slow 1-pixel sink with a long hold at the bottom, weary rise | heavy, tired, carrying the world |
| still body, only the eyes move (one pixel, then a blink) | watchful, menacing, alien |
| bounce + a head swaggle at the top (two pixels, two frames) | cocky — Lesson 3's Milt Kahl head swaggle, in pixels |
| perfectly symmetrical, perfectly even timing | robot, statue, uncanny |

## The pixel walk: Contact → Down → Passing → Up, in four, six, or eight

The mechanics are Lesson 4's, unchanged — re-defined here so this page stands alone. **Contact:** both feet touch, legs and arms at their widest. **Down:** weight lands on the bent front leg; lowest point. **Passing:** the free leg passes the planted one; the body rises. **Up:** highest point, toes pushing off. Then the other side. PIXNOTE's walk page: "You can loop with 4 frames per step — 8 for both feet."

How the budget maps onto the cornerstones:

- **4 frames:** Contact – Passing – Contact – Passing. The body sits one pixel lower on the Contact frames (legs spread = shorter) and one higher on Passing. Jason Perry's classic walk-cycle article even shows a **3-frame** version (step–idle–step) and insists that "at no point do both of your legs line up on the ground next to each other" — and that the planted foot's backward drag "really 'sells' the illusion." His ceiling: "you will never really need more than eight frames for a walk cycle like this."
- **6 frames:** add the Down. Schlitter: the six-frame version "strikes a nice middle ground."
- **8 frames:** all four cornerstones, twice. Schlitter's Human Walk Cycle tutorial — built by reducing 60-fps reference by hand to eight drawings — adds the one detail nobody guesses: the head's path should trace a **triangle wave, not a sine wave** — sharp-ish turns at top and bottom, which read as "an appealing sense of energy that feels organic." Even bobs look robotic; his top-down runs use a bounce of down 1, down 1, up 2 for the same reason.

Build order (Schlitter's Motion Cycles): "Animate the legs first, then the arms, head, and overall body movement" — one body part at a time across *all* frames, never one frame at a time. This guide adds the obvious last step: loose parts (hair, cloth) after the body. That is the mantra with the body split into its own little sequence. Check with onion skin that the planted foot never slides — in a loop, one slipping pixel is visible forever.

**Personality dials in a pixel walk** are Lesson 4's, now measured in pixels:

| Dial | Down | Up |
|---|---|---|
| Stride (Contact width) | timid, sneaking | brash, striding |
| Bob height | poised, icy (1 px, or sub-pixel) | goofy, jaunty (2–3 px on a 32-px sprite) |
| Arm swing | Schlitter: tight swings read "stiff, business like" | full swings past the hips read as "peppy elegance" |
| Tempo (ms per frame) | weary, grand (150 ms+) | eager, nervous (60–80 ms) |
| Torso lean | upright, formal | forward = urgent, hunting |
| Symmetry | (asymmetric) alive, human | (mirror-flipped) mechanical — fine for robots, wrong for drunks |

Schlitter's observation list is the best drill brief in the medium: "a carefree child marches with pride, the elderly shuffle slowly with hunched backs, the drunk sway and stumble."

## Runs, jumps, attacks — and the smear

**Run.** Not a fast walk (Lesson 4's box): there is an airborne moment. Lean the torso forward, lengthen the stride, enlarge the bounce, and drop to fewer, punchier frames — Schlitter's side-view run plays at about 60 ms per frame against the walk's 120; his 3-frame *Mega Man* analysis shows how two extended stride poses, one pass, and a vertical bounce can carry more energy than eight careful drawings. Top-down: 8 directions need only **5 unique orientations** (flip the rest).

**Jump.** PIXNOTE's jump page is the cleanest primer: crouch for 1–2 frames (deeper crouch = stronger jump); stretch tall on take-off (the fastest moment); a parabolic arc with *more* frames near the slow apex; squash on landing; 12–18 frames in all. Their motto: "Contrast is everything. Make the crouch and landing slow with more frames, and the take-off and fall fast with fewer." Then the honest game-design twist, from Schlitter's run-and-gun post: a *player-controlled* jump often has **no anticipation crouch at all** — a single take-off frame, then an up pose and a down pose — because a wind-up between the button and the jump feels like input lag. Anticipation is a dial with a price — "gameplay is king," as Schlitter puts it in his Melee Attacks post — and a character who *does* wind up reads as theatrical, heavy, or cinematic.

**Attack.** From Schlitter's melee posts: start from a stance that suits the weapon's weight; a load/anticipation frame telegraphs power; at peak velocity, one **smear** frame (reminder: a stretched or multiplied drawing) painted in simple colours; the **impact frame is held slightly longer** — "The hit frame is slightly longer to enhance the sense of impact"; follow-through extends the limb 1–2 pixels past the pivot; recovery overshoots and snaps back a pixel into idle. Jabs get almost no delay; kicks get two or more prep frames. For numbers, his top-down sword attack (Pixelblog 58) times its six frames **100 / 50 / 50 / 50 / 100 / 50 ms** — read that as a slower load, a fast swing, a longer hit, a quick recovery (this guide's reading of his figures). That is Lesson 1's timing-as-personality, in a row of numbers.

**Squash and stretch in pixels.** Medeiros's bouncing-ball exercise (32×32, drawn straight ahead) holds the impact frame for 300 ms and squashes the ball wide while keeping its pixel count: "Keeping the volume is very important so your object doesn't look like it got smaller or bigger."

## Hair, cloth, and the elements — one pixel per frame

**Hair and cloth (the loose parts).** The chain rule of Lesson 9, in integers: the base moves least and first, the tip moves most and last; send an S-curve from base to tip and move its crest one pixel towards the tip each frame (PIXNOTE's waving guide: 8–12 frames per wave; hair and tails "keep going a beat later"). Schlitter's wind-effects post gives exact numbers for a flag: waves start small at the pole and *expand* as they travel, spaced about 12 px apart, moving 2 px per frame over a 6-frame loop. And a liberating trick from his top-down sprites: hair doesn't have to move every frame — his shifts on frames 2 and 4 only. Schlitter: "The waves start small and expand as they flow out of the form."

**Fire.** Lesson 10's flame lifecycle — Ascent → Swelling → Division → Reduction — is the map; in pixels it's drawn in a three- or four-colour ramp (dark red, orange, yellow, a touch of white at the core), as clusters with no outline, with the base stable and the top chaotic. Tongues split off into 1–2-pixel embers that rise and vanish — the one place orphan pixels are fully legal. Vary each pass so the loop doesn't show its seam. Medeiros's free boards include fire, smoke, and explosions; Jason Tomlee's Pixilart tutorial walks through a simple flame's shading and animation.

**Water.** Schlitter's Water in Motion: build waves from chains of ovals (round = deep, wide = shallow), remember that "the crests of surface waves are actually slightly steeper than the inverse dips," make a waterfall from a bright mouth, darkening bands, and a synchronised splash base, and only hunt for the loop point *after* the motion looks right. Droplets are single pixels on arcs — Lesson 10's "tiny thrown balls," each on its own schedule.

**Electricity.** Lesson 10's rule (redraw the bolt from scratch every frame, ignore the onion skin) is even easier in pixels: two or three colours (white core, bright blue, dark blue), one-pixel branches built from 45° and 90° segments, two or three frames, then gone — with one frame of full-white flash if you want a thunderclap. Medeiros's board set includes an electricity sheet.

**Wind.** Invisible, so animate its victims (Lesson 10): Schlitter's swirl particles as the general cue ("Swirls are a good general solution to illustrate wind in just about any environment"), 2×2 leaves falling at one pixel per frame with the top half cut on alternate frames to flutter, foliage nudged one pixel up-right, down, left in sequence at about 0.2 s per frame.

## C·B·L·S in sixteen pixels: the head turn, worked

Lesson 5's head turn, on a 32×32 sprite, as one standalone recipe: **Cause** — the eyes move first: two pixels slide one step towards the new direction (1 frame, 100 ms). **Body** — a one-pixel anticipation *away* from the turn (1 frame), then the turn itself in two or three drawings built from the same clusters — profile, three-quarter, front — at 80 ms each. **Loose parts** — the hair or hood lands one frame after the face; overshoot the head one pixel past its final position. **Settle** — ease back into place and hold the end pose for 300–400 ms. Six to eight frames. Re-time it and the person changes: drop the anticipation and the hold and it is a startled glance; stretch the hold and slow the eyes and it is suspicion.

## The personality dial for this lesson

| Choice | Reads as |
|---|---|
| 2–3-frame cycles, whole-pixel steps | retro, punchy, comic, nervous |
| 8-frame cycles with sub-pixel eases | smooth, elegant, calm, "16-bit lavish" |
| Long holds on the extremes | weight, confidence, drama |
| Even timing, no holds | mechanical, floaty, cheap |
| Big bob (2–3 px on 32 px) | bouncy, goofy, joyful |
| Tiny or sub-pixel bob | poised, stealthy, cold |
| Hair/cloth one frame late | alive, soft, warm |
| Everything moving on the same frame | cardboard cut-out |
| Anticipation omitted | responsive (games) — or abrupt, alien |
| Smear + held hit frame | speed, power, comedy |
| Triangle-wave bob | organic energy |
| Perfect sine / perfect mirror | robot, statue |

## Try it — Clip Studio Paint EX

File > New → Project **Animation**, canvas **32×32 px**, **10 fps** (100 ms a frame — the pixel tools' native rhythm); in the same dialog set the timeline's **Image interpolation** to **Hard edges (nearest neighbor)**. Draw with the **Dot pen** (Pen tool > Marker group). Four cels in one animation folder: a breathing idle — torso edge up one pixel on cel 2, back on cel 4; put the hair on a second animation folder one frame late. Use cel assignment to *hold* the peaks for two frames each. Loop it. Then make the sub-pixel version: instead of moving the torso edge, recolour its top row to a half-tone on cel 2. Export: File > Export animation > **Animated GIF** (turn **Dithering** off — it adds noise to pixel art) or **Image sequence** (PNG) for an engine, *at 1×*; enlarge beforehand with Edit > Change Image Resolution → Hard edges if it's for sharing.

## Try it — ibisPaint X

New canvas → **Animation**, 32×32, 8 fps; View menu → **Grid** and **Display when zooming → Pixelated**; **Digital Pen** 1.0 px with **Antialias** off. Four frames: duplicate-and-nudge rather than redraw — body up one pixel on frame 2, hair up on frame 3, everything home by 4. Use per-frame **Duration** to hold frames 1 and 3 longer. Play on **Loop**, then watch it at thumbnail size: the phone screen is your 100 % check.

## Try it — a free pixel editor (optional)

Aseprite, Pixelorama, or LibreSprite time frames in **milliseconds**, tag frame ranges by name (`idle`, `walk`), and export a sprite sheet directly — the most comfortable home for this lesson's drills. Medeiros's free article *A Basic Aseprite Animation* is the short on-ramp (new frame, frame duration, the preview window, export).

## Drills (one sitting each)

1. **Two idles, one sprite.** A 16×16 character breathing in 4 frames — once by moving whole pixels, once by sub-pixel recolouring. Play them side by side at 100 %.
2. **The four-frame walk.** Contact–Passing–Contact–Passing. Loop it; fix the sliding foot. Then recast it twice by changing *only* bob height and arm swing.
3. **Three-frame run.** A-B-C-B, 60 ms a frame. Make it lean.
4. **One slash.** Six frames, 100/50/50/50/100/50 ms, one smear, one held hit.
5. **A candle and a bolt.** Six-frame candle loop, three colours, no outline; then a three-frame bolt redrawn from scratch each frame.

## If you only keep three things

1. **One pixel is a big step**, so pixel animation acts with *timing* (holds, ms per frame), *partial* moves, and *sub-pixel* colour shifts more than with distance.
2. **Fewer frames, stronger poses:** 4–8-frame cycles at 8–12 fps, extremes held longer than inbetweens, loose parts one frame late — C·B·L·S in integers.
3. **Idles and walks are personality machines:** bob height, hold length, arm swing, symmetry, and whether you allow an anticipation are casting decisions, in pixels as on paper.

## Sources for this lesson (all free & legal; details in Lesson 19)

- Pedro Medeiros (Saint11), *Pixel Art Tutorials* (the free animated boards: walk, run, idle, jump, sub-pixel, squash, easing, motion blur, fabric, fire, water, smoke, explosion, electric, wind): https://saint11.art/blog/pixel-art-tutorials/ — *A Basic Aseprite Animation*: https://saint11.art/pixel_art_articles/article3 — *Saving and Exporting Pixel Art* (on Medium; free to read): https://medium.com/pixel-grimoire/how-to-start-making-pixel-art-8-eb218a4637dd
- Raymond Schlitter (SLYNYRD), *Pixelblog 8 – Intro to Animation*: https://www.slynyrd.com/blog/2018/8/19/pixelblog-8-intro-to-animation — *9 – Melee Attacks*: https://www.slynyrd.com/blog/2018/9/8/pixelblog-9-melee-attacks — *10 – Water in Motion*: https://www.slynyrd.com/blog/2018/10/12/pixelblog-10-water-in-motion — *25 – Motion Cycles*: https://www.slynyrd.com/blog/2020/1/23/pixelblog-25-motion-cycles — *33 – Wind Effects*: https://www.slynyrd.com/blog/2021/7/16/pixelblog-33-wind-effects — *50 – Human Walk Cycle*: https://www.slynyrd.com/blog/2024/5/24/pixelblog-50-human-walk-cycle — *52 – Idle Fighting Stance*: https://www.slynyrd.com/blog/2024/9/26/pixelblog-52-idle-fighting-stance — *53 – Punches and Kicks*: https://www.slynyrd.com/blog/2024/11/25/pixelblog-53-punches-and-kicks — *55 – Top Down Character Animation*: https://www.slynyrd.com/blog/2025/3/24/pixelblog-55-top-down-character-animation — *58 – Top Down Character Animation Part 3*: https://www.slynyrd.com/blog/2025/10/2/pixelblog-58-top-down-character-animation-part-3 — *60 – Side View Run 'N Gun*: https://www.slynyrd.com/blog/2026/1/26/side-view-run-n-gun
- PIXNOTE, *How to Animate Pixel Art*: https://pixnote.net/en/learn/animation/ — *Walk cycle*: https://pixnote.net/en/learn/animate-walk-cycle/ — *Jump*: https://pixnote.net/en/learn/animate-jump/ — *Bouncing ball*: https://pixnote.net/en/learn/animate-bouncing-ball/ — *Waving (flags, hair, tails)*: https://pixnote.net/en/learn/animate-waving/
- Tsugumo, *So You Want To Be A Pixel Artist?* — chapter 10, *Breathing Life Into Your Sprites* (community mirror of a free 2000s classic): http://www.geocities.ws/skulkraken2002/Tsugumo/chapter10.htm — index: https://mirror.motherhamster.org/tsugumo/default.html
- Jason Perry, *Walk Cycles, Part 1*: http://finalbossblues.com/walk-cycles-p1/
- Sandro Maglione, *Pixel art Character Animations guide*: https://www.sandromaglione.com/articles/pixel-art-character-animations-guide
- AdamCYounis, *Pixel Art Class – Sub-Pixel Animation* (video): https://www.youtube.com/watch?v=cs1Gp61yafQ — *Simple Character Idle Animation*: https://www.youtube.com/watch?v=vs-ierVdE7I — *Run Animation Tutorial [Part 1]*: https://www.youtube.com/watch?v=LPBvrdJ_1a8 — *Making Pixel Art Worth Animating*: https://www.youtube.com/watch?v=52A4KgX-wNI — *Attack Animations*: https://www.youtube.com/watch?v=nJbzBSVy1u0
- Brandon James Greer, *Pixel Art Character Animation | Tips, Tricks, and Workflow* (video): https://www.youtube.com/watch?v=jdnCOlATb-c
- Saultoons, *Easy Pixel Art Walk Cycle Tutorial* (video): https://www.youtube.com/watch?v=7T6yOk5n-zk — Dual Core Studio, *Walk Cycle (6 & 8 frames)*: https://www.youtube.com/watch?v=5QTCwiJUmmo — *2 & 4 Frames Walk/Run Cycle Animations*: https://www.youtube.com/watch?v=9lemPuqxIug — Pixel Overload, *The secrets to good Pixel Art animation!*: https://www.youtube.com/watch?v=J1sFBDQt8J0
- Jason Tomlee (Pixilart), *Fire: Shading and Animation*: https://www.pixilart.com/tutorial/fire-shading-and-animation-115 — *Animation: Squash & Stretch*: https://www.pixilart.com/tutorial/animation-squash-stretch-61 — *Animation – Anticipation*: https://www.pixilart.com/tutorial/animation-anticipation-62 — *SmokePoofs – Movement*: https://www.pixilart.com/tutorial/smokepoofs-movement-51
- Lospec, walk-cycle tutorials tag: https://lospec.com/pixel-art-tutorials/tags/walkcycle — animation tag: https://lospec.com/pixel-art-tutorials/tags/animation
- Wikipedia, *Idle animation*: https://en.wikipedia.org/wiki/Idle_animation

---
# Lesson 18 — The Pixel Studio (Clip Studio Paint EX, ibisPaint X, the Free Editors, Aseprite — and the Road into the Game)

*Standalone lesson. Everything you need is on this page. Each tool's section is also self-contained — jump straight to the one you use. Every setting below was checked against the tools' official documentation on 20 August 2026; Clip Studio menu names are the Ver. 5 names, with the older names in brackets where they changed.*

## What this lesson gives you

The exact setup that keeps pixels square in the two apps you already own, an honest tour of the purpose-built pixel editors (the free ones and the paid standard), and the export and engine settings that stop your sprites from turning to soup on the way into a game. No drawing theory here — that's Lessons 15–17. This is the workbench.

## The pocket mnemonic for Part VII

> **P·I·X·L — "Palette small · Integer scale · eXport PNG · Look at 100 %."**
>
> This lesson is the **I** and the **X**: every scale step a whole number with **nearest-neighbour** sampling, and every export a **PNG** (or GIF/APNG/WebP for loops) — never JPG. Cure's tutorial, in the community's tone of voice: "Never, ever save as JPG. Instead, save as PNG or GIF." Pedro Medeiros on scaling: "Always resize your art using whole numbers (200%, 300% and so on) and never fractions (130%, 250%)" — and the reward: "You can scale up pixel art forever without losing quality."

## Words used in this lesson (fresh definitions, every time)

- **anti-aliasing (as a tool setting)** — the automatic edge-softening your app applies to brushes, fills, selections, and text. For pixel art it is switched **off** everywhere; you add any smoothing by hand (Lesson 15).
- **nearest neighbour** — scaling that copies each source pixel as a hard square, no blending. Apps call it *hard edges*, *point*, *none*, *pixelated*, or *nearest*. **Bilinear / bicubic / "smooth"** are the blurring alternatives you must avoid.
- **integer scaling** — enlarging only by whole numbers (2×, 3×, 8×) so each source pixel becomes an exact square of screen pixels.
- **indexed colour** — an image whose pixels store palette numbers, not colours; edit the palette and the image recolours.
- **timeline / frame / cel** — the panel where drawings are placed in time; one slot of time; one drawing in the stack (Clip Studio's word).
- **onion skin** — a ghost view of neighbouring frames.
- **frame tag** — in Aseprite and Pixelorama, a named range of frames (`idle`, `walk`) that an engine can treat as one animation.
- **pixel-perfect mode** — a pencil mode in purpose-built editors that removes the corner "doubles" from one-pixel lines as you draw.
- **sprite sheet** — many frames packed into one image in a grid; **image sequence** — one numbered PNG per frame. Engines accept either.
- **texture filter (engines)** — how a game engine samples your image when it scales it: **Nearest/Point** = crisp pixels; **Linear/Bilinear** = blur.

## Clip Studio Paint EX — the pixel-perfect setup

Clip Studio is not a pixel editor, but with eight settings it becomes a very good one — this is the workflow in Celsys' own Art Rocket tutorial by Dado Almeida and in a dozen official Clip Studio TIPS articles. Palette names changed in Ver. 5.0: the *Sub Tool* palette is now **Tool Group**, *Tool Property* is now **Tool Settings**, and *Sub Tool Detail* is now **Advanced Tool Settings** (older tutorials use the old names; the buttons are the same).

1. **Canvas.** File > New, unit **px**, a small size — 32×32, 64×64, or a game screen like 320×180. For animation choose Project **Animation**, and in the same dialog set the timeline's **Image interpolation** to **Hard edges (nearest neighbor)** so that moving or scaling a cel never blurs it.
2. **Display.** Leave Preferences > Canvas > **Display quality** on **Default** — the manual describes "High quality" as the prettier, slower rendering, and Default as the one where the image may look pixelated at some zoom levels, which for once is exactly what you want. Open a second view at 100 %: **Window > Canvas > New Window**. Add zoom steps under Preferences > Canvas > Scale if 800 % isn't in the list.
3. **Grid.** **View > Grid** to show it; **View > Grid/Ruler bar settings** → **Gap 1 px, Number of divisions 1** — the field names as the official-site tutorials give them (the manual only says the default is 10 mm with 4 divisions); make sure Preferences > Ruler/Unit is in px. **View > Snap > Snap to grid** is optional.
4. **Pen.** The **Dot pen** lives in the Pen tool's **Marker** group (Tool Group palette): fixed at one pixel, anti-aliasing off, no stabilisation — the manual's words: "used for drawing single-pixel lines, and the brush size cannot be changed above 1 pixel." For a bigger square pixel brush, duplicate any pen and in **Advanced Tool Settings > Anti-aliasing** choose **None**, set Brush size to 2–4, and turn off stabilisation. Do the same to an **Eraser**.
5. **Fill and select.** In the **Fill** tool: **Anti-aliasing** off and **Area scaling** off (Area scaling grows the fill by a fraction of a pixel to hide anti-aliased gaps — pixel art has none, and it will eat your lines). In the **Auto select** tool: anti-aliasing off, Color margin 0. Text tool: anti-aliasing off.
6. **Transform.** Every move, scale, or rotate of a selection (Edit > Transform) exposes **Interpolation method** in Tool Settings: set it to **Hard edges (nearest neighbor)** and leave it there.
7. **Palette.** **Window > Color Set** → the spanner icon (**Edit color sets**) → a new empty set; then eyedrop colours and press **Add Color** at the bottom. Lospec palettes download as PNG — drop the 1× PNG onto a layer and eyedrop it in. (Color Set can also import `.cls` and Photoshop `.aco` files.) There is no indexed-colour mode in Clip Studio; discipline is your palette lock.
8. **Scale and export.** The export dialog's scaling options blur pixel art — there is no nearest-neighbour choice there. So: **Edit > Change Image Resolution**, scale **800 %** (or any whole multiple), Interpolation **Hard edges (nearest neighbor)**, *then* **File > Export (Single Layer)** as PNG with **Export transparency** on. Keep the 1× `.clip` as your master. For animation: **File > Export animation > Image sequence** (PNG) at 1× for engines, **Animated GIF** for sharing — and switch the GIF dialog's **Dithering** option **off**, because dithering is a Lesson 16 decision, not something an exporter should make for you. Clip Studio does not export sprite sheets; engines take image sequences happily (Lesson 14), and the purpose-built editors below can assemble a sheet from your PNGs if you need one.

Two more official helpers: **Filter > Effect > Mosaic** pixelates a drawing (useful to rough a sketch into blocks, never a substitute for placing pixels), and the Celsys channel has pixel-art videos with Brandon James Greer — *How to correctly scale and texture pixel art in Clip Studio Paint* and *Animate your pixel art with Clip Studio Paint!* — plus Dadotronic's *How to make custom pixel art tools*.

## ibisPaint X — the pixel setup (phone)

ibisPaint's own lecture "53. Display Grid on the Canvas" *is* a pixel-art setup guide, and two View-menu features added in version 10 (November 2022) exist specifically for it.

1. **Canvas.** New canvas → **Any Size** → 32 × 32 (the lecture's example). For animation choose the **Animation** canvas type (Lesson 12) and set fps before creating.
2. **View menu.** Turn **Grid** on (**Grid Settings**: Grid 1 Interval = 1; Grid 2 Interval = 8 or 16 for tile guides). Switch **Display when zooming** from **Smooth** to **Pixelated** — the official new-features page: "for pixel art drawings, Pixelated is appropriate."
3. **Pen.** **Digital Pen**, Thickness **1.0 px**. Open the brush's parameters and under **Shape** turn **Antialias** off ("When turned off, the edges of the brush pattern are jagged" — here, a feature). If you use a textured brush, turn **Texture Antialiasing** off too. Same for the **Eraser**.
4. **Bucket.** **Strength 0 %** (exact colour only) and **Expansion 0 px** — the default 1.5 px exists to cover anti-aliased line edges, which pixel art doesn't have.
5. **Transform and resize.** In the **Transform** tool's Translate/Scale, set **Interpolation Method** to **Nearest Neighbor (Dot)** ("No interpolation. Suitable for pixel art"). In the **Canvas** tool's **Resize**, choose **Nearest Neighbor (Pixel)** — the one the manual recommends "for enlarging and reducing pixel art."
6. **Export.** Save Image → **PNG**, **Transparent** on. There is no scale-on-export option except **Super-resolution x2**, which is an AI upscaler — never use it on pixel art. For a big share copy: duplicate the canvas, **Resize** to 800 % with Nearest Neighbor (Pixel), export; keep the 1× original.
7. **Animation.** Frames, onion skin, per-frame **Duration**, and **Loop / Ping pong / One-shot** work exactly as in Lesson 12; **Save Animation Video** is for sharing. Video has no transparency, so for a game export each frame as a transparent PNG (the official docs describe no sprite-sheet export — say so to yourself and plan the minute it takes).
8. **Palettes.** Version 14 (March 2026) added multiple named colour palettes, with export/import and sharing by QR code — make one per project.

Toys, honestly labelled: **Filter > Retro Game** converts a picture to eight colours and chunky dots, and the **Pixelate** filters (Square, Hexagonal, Triangular) mosaic an image. They can rough out a reference; they are not pixel art, because nobody chose the pixels. The official ibisPaint channel has a short *How to draw Pixel Art* video if you want to watch the setup once.

## The purpose-built editors (free, open, legal)

Pixel art has its own tools, and the free ones are excellent. They share the features Clip Studio and ibisPaint lack: a pixel-perfect pencil, an always-on pixel grid, indexed palettes, frame timing in milliseconds, frame tags, and one-click sprite-sheet export.

| Editor | Licence / price | Runs on | Animation | Standouts |
|---|---|---|---|---|
| **Pixelorama** (Orama Interactive) | MIT, free (optional paid Steam build) | Windows, macOS, Linux, **web browser** (on its itch.io page), Android (experimental) | timeline with layers and frames, onion skin, frame tags, loop / ping-pong | indexed mode, palettes (`.gpl`, `.json`, PNG), spritesheet and APNG/GIF export, tilemap layers, non-destructive effects; v1.2.1 released August 2026 |
| **LibreSprite** | GPLv2, free | Windows, macOS, Linux, Android, web build | real-time preview, onion skin, layers and frames | a community fork of Aseprite's last GPL code (2016); shading mode, tiled drawing mode for patterns |
| **Piskel** | Apache-2.0, free | any browser; desktop builds for Windows/macOS/Linux | live preview, layers, onion skin, per-animation fps | GIF, PNG, and spritesheet export; the simplest possible on-ramp — but development has been quiet since 2018 (the site itself recommends the web version over the desktop builds) |
| **GraphicsGale** | freeware since 2017 (commercial use allowed) | Windows only | real-time preview, onion skin, layers | palette control, sprite-sheet and GIF export; a veteran Japanese sprite tool |
| **Pixilart** (the editor at pixilart.com/draw) | free, browser | any browser | frames with speed control, onion skin | GIF/WEBP/MP4/sprite-sheet export, palettes, a pixel-perfect pencil toggle, and a social community around it |

Honourable mentions: **Krita** (free, GPLv3) ships a "Pixel" group of brush presets, a pixel grid and a Nearest Neighbour canvas-scaling option in its display settings, and a full animation timeline with an onion-skin docker — a serious free option if you already paint in it. **GIMP** (free, GPL) gets you there with the Pencil tool (which the manual notes "does not even do anti-aliasing"), Interpolation **None** for scaling, and **Image > Mode > Indexed** — but has no animation timeline. Lospec's own browser editor still works but is no longer developed.

Which one? If you want zero installation, **Piskel** or **Pixilart** in a browser tab. If you want the fullest free feature set, **Pixelorama**. If you want the Aseprite workflow without paying, **LibreSprite** — with the caveat that it is ten years behind its parent.

## Aseprite — the paid standard, and the legal free route

**Aseprite** is the tool most working pixel artists use, and most tutorials assume. It is not free: the official FAQ's wording is that "$19.99/USD is the minimum pledge amount" for the ready-made Windows, macOS, and Linux builds (also sold on Steam), DRM-free, with a free trial that can't save. Current version at this check: 1.3.18.2 (August 2026).

The honest legal route to a free copy: Aseprite's **source code is public on GitHub**, and its licence permits you to build it yourself for personal use. The EULA: "You may only compile and modify the source code of the SOFTWARE PRODUCT for your own personal purpose or to propose a contribution to the SOFTWARE PRODUCT." The FAQ: "Now you can still download its source code, compile it, and use it for your personal purposes." You may *not* redistribute builds — that has been the rule since August 2016, when the project left the GPL (which is why LibreSprite, forked from the last GPL commit, exists). Compiling is a developer task (CMake, Ninja, a C++ toolchain — the repo's INSTALL file walks through it); if that isn't you, the $19.99 is one of the better-spent sums in indie art. Teachers in educational institutions can request a special educational licence.

What you get, from the official docs: **Indexed** mode with palettes up to 256 colours (the colour-bar docs: "You cannot use colors that are not present in the palette, except by modifying the palette itself" — the palette lock Clip Studio lacks); a **timeline** of layers, frames, and cels with **onion skinning** (F3); **tags** (Frame > Tags > New Tag) with Forward / Reverse / Ping-pong directions and a **loop section** (F2); **File > Export Sprite Sheet** with JSON data that engines and tools read, and a command-line interface (`--sheet`, `--data`, `--split-tags`) for batch export; a **pixel-perfect** freehand mode; and the DawnBringer 32 palette as the default. Medeiros's free article *A Basic Aseprite Animation* and MortMort's *Aseprite Guide for Beginners* are the two on-ramps.

## The road into the game: keeping pixels square

Lesson 14's pipeline is unchanged — transparent PNGs, zero-padded names, frames grouped per action, the animation's fps set in the engine — with one new requirement: the engine must never blur or fractionally scale your pixels. Each engine has a three-line answer, all from the official documentation:

- **Godot 4.7.** Project Settings > Display > Window > Stretch: **Mode = viewport**, **Aspect = keep** (or expand), **Scale Mode = integer** — the manual: "This is useful to prevent distortion when displaying pixel art." Give the project a small base size (the docs: "Most pixel art games use viewport sizes between 256×224 and 640×480" — 320×180 or 640×360 suit widescreen). Rendering > Textures > Canvas Textures > **Default Texture Filter = Nearest** (the project setting `rendering/textures/canvas_textures/default_texture_filter`). Rendering > 2D > Snap > **Snap 2D Transforms to Pixel** on (`rendering/2d/snap/snap_2d_transforms_to_pixel`), so sprites never sit between pixels — the Sprite2D class reference warns that for "a pixel art aesthetic, textures may appear deformed when centered" and points to exactly these snap settings. Import textures as **Lossless**.
- **Unity 6.3.** On every sprite: the same **Pixels Per Unit**, **Filter Mode = Point (no filter)**, **Compression = None** (the manual's prerequisites for its pixel-perfect camera). Then add the **Pixel Perfect Camera** component (built into URP): **Asset Pixels Per Unit** to match the sprites, **Reference Resolution** to your design size, and **Grid Snapping** set to **Upscale Render Texture** (renders at the reference size, then scales up — the crispest option) or **Pixel Snapping**.
- **Unreal 5.7/5.8.** Right-click each imported texture → **Sprite Actions > Apply Paper 2D Import Settings** — it "removes Mipmaps, sets the Filter to Nearest"; use an **Orthographic** camera (Projection Mode in the camera's Details) for a flat 2D view.
- **The plain web.** CSS: `img, canvas { image-rendering: pixelated; }` (MDN: scaled "with the 'nearest neighbor' or similar algorithm"). Canvas: `ctx.imageSmoothingEnabled = false;` before any `drawImage` — MDN: "When enlarging images, the default resizing algorithm will blur the pixels. Set this property to false to retain the pixels' sharpness." Lesson 14's `steps()` and canvas player need nothing else.

```css
/* Pixel art on the web: whole-number scale, no smoothing. */
.sprite {
  width: 128px;            /* a 32 px sprite shown at exactly 4× */
  height: 128px;
  image-rendering: pixelated;
}
```

Two traps the settings don't cover: **scrolling cameras at fractional positions** make sprites shimmer — snap the camera, too (Godot's snap settings; Unity's Pixel Snapping) — and **mixed resolutions** (a 16-px hero next to 32-px tiles drawn at a different scale) break the illusion that the screen *is* a low-resolution display. Medeiros's consistency post: one base resolution, integer-scaled as a whole.

## The personality survives the pipeline

Nothing here changed a drawing — and that is the point of doing it right. A sprite whose pixels stay square carries every decision from Lessons 15–17 into the game intact: the one-pixel eye shift, the held hit frame, the hair one frame late. And the runtime dial from Lesson 14 still works: the engine's play-speed multiplier is the timing dial, so the same 4-frame walk at 0.6× is a trudge and at 1.4× is a scurry. Blur any of it and the audience can't read it. Keep it square and a sixteen-pixel person can act.

## If you only keep three things

1. **Clip Studio:** Dot pen (Pen > Marker), anti-aliasing **None** on pens, fills, selections and text, Area scaling off, Interpolation **Hard edges (nearest neighbor)** on every transform, a 1-px grid — and scale with **Edit > Change Image Resolution**, never in the export dialog. **ibisPaint:** Grid on, **Display when zooming = Pixelated**, Digital Pen 1.0 px with Antialias off, Bucket Strength 0 % / Expansion 0 px, **Nearest Neighbor** for transform and resize, PNG export at 1×.
2. **Purpose-built editors** add pixel-perfect pencils, indexed palettes, ms timing, tags, and sprite-sheet export: **Pixelorama**, **LibreSprite**, **Piskel**, **GraphicsGale**, **Pixilart** are free; **Aseprite** ($19.99, or compile it yourself for personal use) is the standard.
3. **In the engine:** Nearest/Point filtering, **integer** scaling, and pixel snapping — Godot's viewport + integer stretch, Unity's Pixel Perfect Camera, Unreal's Paper 2D import settings, the web's `image-rendering: pixelated` / `imageSmoothingEnabled = false`.

## Sources for this lesson (official documentation and the tools' own sites; details in Lesson 19)

- **Clip Studio Paint (Celsys):** Dado Almeida, *How to Draw Pixel Art: A Tutorial* (Art Rocket): https://www.clipstudio.net/how-to-draw/archives/161082 — Official manual: *Special brushes* (Dot pen): https://help.clip-studio.com/en-us/manual_en/240_brushes/Special_brushes.htm — *Anti-aliasing* setting (Advanced Tool Settings): https://help.clip-studio.com/en-us/manual_en/810_subtools/A.htm — *Change Image Resolution* (interpolation method names): https://help.clip-studio.com/en-us/manual_en/210_file/Change_canvas_size.htm — *Creating a new canvas* (timeline Image interpolation): https://help.clip-studio.com/en-us/manual_en/210_file/Creating_a_New_Canvas.htm — *Using the ruler bar and grid*: https://help.clip-studio.com/en-us/manual_en/270_canvas/Using_the_ruler_bar_and_grid.htm — *Preferences* (Display quality): https://help.clip-studio.com/en-us/manual_en/720_preferences/Preferences.htm — *Color Set palette*: https://help.clip-studio.com/en-us/manual_en/300_color/Color_Set_palette.htm — *Exporting files*: https://help.clip-studio.com/en-us/manual_en/210_file/Exporting_files.htm — *Export animation*: https://help.clip-studio.com/en-us/manual_en/600_animation/Export_animation.htm — *Filters* (Mosaic): https://help.clip-studio.com/en-us/manual_en/390_filters/Filters.htm — Ver. 5 palette renames: https://www.clipstudio.net/en/dl/release_note/latest/ — Clip Studio TIPS: KevinFarias, *How to make PIXEL ART Animation in Clip Studio Paint*: https://tips.clip-studio.com/en-us/articles/5314 — babeoded, *Animated Retro Pixel Art for Game Splash Screen*: https://tips.clip-studio.com/en-us/articles/3562 — babeoded, *Making Pixel Art Forest Tilesets* (Grid "Gap(D)" 1 px; Color Set palettes): https://tips.clip-studio.com/en-us/articles/7567 — Naoi21-arts, *Turn Your Illustrations into Pixel Art Using Clip Studio* (the grid dialog's "Gap(D)" and "Number of divisions" fields): https://tips.clip-studio.com/en-us/articles/5384 — FrostDrive, *Pixel Art Practices Explained Simply*: https://tips.clip-studio.com/en-us/articles/5360 — robertoivy_01, *Pixel Art Characters: Workflow, Setup & Styles*: https://tips.clip-studio.com/en-us/articles/11460 — Official channel videos: Brandon James Greer, *How to correctly scale and texture pixel art in Clip Studio Paint*: https://www.youtube.com/watch?v=LgDA3RqbgCY — *Animate your pixel art with Clip Studio Paint!*: https://www.youtube.com/watch?v=L3AXOqtuY2o — Dadotronic, *How to make custom pixel art tools in Clip Studio Paint*: https://www.youtube.com/watch?v=ChwPpSbD524
- **ibisPaint X (ibis inc.):** lecture *53. Display Grid on the Canvas*: https://ibispaint.com/lecture/index.jsp?no=171&lang=en — *184. View Menu Details* (Grid, Display when zooming): https://ibispaint.com/lecture/index.jsp?no=168&lang=en — *179. Details of Brush Parameters* (Antialias): https://ibispaint.com/lecture/index.jsp?no=118&lang=en — *180. Bucket tool details*: https://ibispaint.com/lecture/index.jsp?no=82&lang=en — *67. Changing image resolution with Resize*: https://ibispaint.com/lecture/index.jsp?no=77&lang=en — *182. Transform Tool Details*: https://ibispaint.com/lecture/index.jsp?no=154&lang=en — *54. Export an Artwork (Save)*: https://ibispaint.com/lecture/index.jsp?no=206&lang=en — new-features page (Pixelated zoom, grid): https://ibispaint.com/newFeature.jsp?lang=en — ver. 10.0.1 release note (grid, zoom interpolation): https://ibispaint.com/information.jsp?newsID=54735849 — ver. 9.0.0 release note (Nearest Neighbor transform): https://ibispaint.com/information.jsp?newsID=22182838 — news: *How to draw Pixel Art* (official video): https://ibispaint.com/information.jsp?newsID=26557593
- **Free editors:** Pixelorama — https://pixelorama.org/ — itch.io (with the web version): https://orama-interactive.itch.io/pixelorama — GitHub (MIT): https://github.com/Orama-Interactive/Pixelorama — LibreSprite: https://libresprite.github.io/ — GitHub (GPLv2): https://github.com/LibreSprite/LibreSprite — Piskel: https://www.piskelapp.com/ — GitHub (Apache-2.0): https://github.com/piskelapp/piskel — GraphicsGale: https://graphicsgale.com/us/ — Pixilart editor: https://www.pixilart.com/draw — Krita docs, *Animation*: https://docs.krita.org/en/user_manual/animation.html — *Display settings* (pixel grid, Nearest Neighbour scaling): https://docs.krita.org/en/reference_manual/preferences/display_settings.html — *Onion skin docker*: https://docs.krita.org/en/reference_manual/dockers/onion_skin.html — *Brush preset bundle* (the Pixel presets): https://docs.krita.org/en/reference_manual/krita_4_preset_bundle.html — GIMP docs, *Pencil*: https://docs.gimp.org/en/gimp-tool-pencil.html — *Indexed mode*: https://docs.gimp.org/en/gimp-image-convert-indexed.html
- **Aseprite:** https://www.aseprite.org/ — FAQ (price, source, licence history): https://www.aseprite.org/faq/ — GitHub: https://github.com/aseprite/aseprite — EULA: https://raw.githubusercontent.com/aseprite/aseprite/main/EULA.txt — docs: *Color modes*: https://www.aseprite.org/docs/color-mode/ — *Color bar* (palette lock in Indexed images): https://www.aseprite.org/docs/color-bar/ — *Timeline*: https://www.aseprite.org/docs/timeline/ — *Onion skinning*: https://www.aseprite.org/docs/onion-skinning/ — *Tags*: https://www.aseprite.org/docs/tags/ — *Sprite sheet*: https://www.aseprite.org/docs/sprite-sheet/ — *CLI*: https://www.aseprite.org/docs/cli/ — MortMort, *Aseprite Guide for Beginners* (video): https://www.youtube.com/watch?v=Md6W79jtLJM
- **Engines and web:** Godot, *Multiple resolutions*: https://docs.godotengine.org/en/stable/tutorials/rendering/multiple_resolutions.html — *Importing images*: https://docs.godotengine.org/en/stable/tutorials/assets_pipeline/importing_images.html — *Sprite2D* class reference (the pixel-snap note and setting names): https://docs.godotengine.org/en/stable/classes/class_sprite2d.html — Unity, *Pixel Perfect Camera component reference* (6.3 manual): https://docs.unity3d.com/6000.3/Documentation/Manual/urp/2d-pixelperfect-ref.html — *Add a pixel perfect camera* (sprite prerequisites): https://docs.unity3d.com/6000.3/Documentation/Manual/urp/2d-pixelperfect-prep-sprites.html — Unreal, *Import & use Paper 2D sprites* (Apply Paper 2D Import Settings): https://dev.epicgames.com/documentation/en-us/unreal-engine/how-to-import-and-use-paper-2d-sprites-in-unreal-engine — *Orthographic camera*: https://dev.epicgames.com/documentation/unreal-engine/orthographic-camera-in-unreal-engine?lang=en-US — MDN, *image-rendering*: https://developer.mozilla.org/en-US/docs/Web/CSS/image-rendering — *imageSmoothingEnabled*: https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/imageSmoothingEnabled
- **Habits:** Pedro Medeiros, *Scaling Pixel Art*: https://saint11.art/blog/scaling/ — *Saving and Exporting Pixel Art* (whole numbers, never fractions; PNG only — on Medium; free to read): https://medium.com/pixel-grimoire/how-to-start-making-pixel-art-8-eb218a4637dd — *Consistency*: https://saint11.art/blog/consistency/ — Cure, *The Pixel Art Tutorial*: https://pixeljoint.com/forum/forum_posts.asp?TID=11299&PID=139318

---

# PART VIII — THE LIBRARY

---

# Lesson 19 — Annotated Bibliography (Every Link Verified, Free & Legal)

**How this list was built.** Every URL below was fetched and confirmed live on **16 August 2026** — the pixel-art entries added for Part VII on **20 August 2026** (for those, YouTube videos were confirmed through YouTube's own embed service, which returns each video's exact title and channel, because the watch pages themselves rate-limit automated checks). Only free *and* clearly legal sources made the cut: creators' own channels and websites, companies' own free tutorials and documentation, Wikipedia, Khan Academy, and genuinely public-domain material on the Internet Archive. (A caution from the wild: convincing-looking but *fake* URLs for animation resources circulate widely — including in AI-generated lists. Nothing below is cited from memory; everything was checked.) YouTube and Vimeo videos are free to watch on the creators' own channels; "public domain" entries are free to download, keep, and study without restriction.

## Foundations & the twelve principles

- **Twelve basic principles of animation** — Wikipedia — encyclopedia article — https://en.wikipedia.org/wiki/Twelve_basic_principles_of_animation — The canonical reference for the principles from Frank Thomas & Ollie Johnston's *The Illusion of Life* (1981), including the origin story and the note that appeal isn't niceness ("charisma in an actor" — villains included).
- **12 Principles of Animation (full series)** — AlanBeckerTutorials (Alan Becker's own channel) — video — https://www.youtube.com/watch?v=uDqjIdI4bF4 — The most-watched free visual walkthrough of all twelve principles, with drawn examples; ideal first watch, and a lovely rewatch before any drill.
- **The illusion of life** — Cento Lodigiani (self-published on Vimeo) — 3-minute short film — https://vimeo.com/93206523 — All twelve principles performed by a plain grey cube that visibly develops moods; the fastest possible proof that motion choices, alone, create personality.
- **12 Principles of Animation | Basic Animation Principles** — Adobe (official free article) — article — https://www.adobe.com/creativecloud/animation/discover/principles-of-animation.html — Plain-language rundown; useful second phrasing of everything (it calls slow in/out "ease in, ease out").
- **Pixar in a Box — Animation unit** — Khan Academy × Pixar — free interactive course — https://www.khanacademy.org/computing/pixar/animate — Pixar artists teach timing and spacing through bouncing-ball lessons with hands-on interactive exercises; the ideas transfer to paper and tablet perfectly.

## Personality, appeal & design

- **Appeal: The 12 Basic Principles of Animation** — Animation Mentor blog — article — https://www.animationmentor.com/blog/appeal-the-12-basic-principles-of-animation/ — The best free deep-dive on appeal, split into Order (clarity, believability) and Interest (variation, surprise); argues presentation beats subject matter.
- **The Milt Kahl Head Swaggle** — Michael Ruocco, Cartoon Brew — article — https://www.cartoonbrew.com/disney/the-milt-kahl-head-swaggle-80861.html — A signature Disney head-rattle deployed only when characters feel cocky: the cleanest professional example of one repeated motion becoming a personality trademark.
- **Shape Language In Character Design** — Winged Canvas (art school's own channel) — video — https://www.youtube.com/watch?v=v6n9OYtaWZs — How circles, squares, and triangles telegraph personality before anything moves.
- **How to Use SHAPES to Create Character Designs** — Chelsea Gracei (her own channel) — video — https://www.youtube.com/watch?v=GbG45s1EZvo — A second, complementary take on shape language from a character designer.
- **New to 2D Character Animation? Here Are The Most Common Mistakes And How To Avoid Them** — School of Motion blog — article — https://schoolofmotion.com/blog/new-to-2d-character-animation-here-are-the-most-common-mistakes-and-how-to-avoid-them — Seven beginner mistakes (symmetry, floating weight, missing secondary motion, no reference…) that double as a personality checklist.
- **Understanding the Principles of Anticipation** — School of Motion blog — article — https://schoolofmotion.com/blog/understanding-the-principles-of-anticipation — Anticipation as the audience's telegraph; includes the scaling rule: the bigger the anticipation, the bigger the action reads.

## Walk cycles

- **Tutorial #2: Walk Cycle** — Dermot O'Connor, Angry Animator — article/tutorial, now preserved on the Wayback Machine — https://web.archive.org/web/20230814111643/https://www.angryanimator.com/word/2010/11/26/tutorial-2-walk-cycle/ — The classic free 2D walk tutorial: Contact / Recoil / Passing / High Point, a worked 12-frame cycle, and the dictum that the contact pose determines 80 % of the walk. (His site rebranded to animatewithdermot.com in 2026 and the free article came down; the archived copy above is complete. His current tutorials live at https://animatewithdermot.com/tuts/index.shtml — many now point to his paid LinkedIn Learning courses.)
- **Tutorial: Animating a Basic Human Walk Cycle** — Animation Mentor blog (Jason Martinsen) — article + embedded video — https://www.animationmentor.com/blog/tutorial-animating-human-walk-cycle/ — Full professional workflow: poses, breakdowns, hip swing, upper-body counter-rotation, arm drag; ~20–30 frames at 24 fps for a typical walk.
- **Tutorial: Animating a Sneak Walk Cycle with Personality** — Animation Mentor blog (Natasha Krinsky) — article + embedded video — https://www.animationmentor.com/blog/tutorial-animating-sneak-walk-cycle-with-personality/ — The personality-walk masterclass: bent knees that never straighten, tiptoe contacts, deliberately broken left/right symmetry.
- **What Is an Animated Walk Cycle and How Can I Make One?** — Adobe — article — https://www.adobe.com/creativecloud/animation/discover/animation-walk-cycle.html — Gentle beginner framing; names the 8-drawing cycle as the standard starting point.
- **Walk Cycle Reference: The Ultimate List for Animators** — School of Motion blog — article — https://schoolofmotion.com/blog/walk-cycle-reference-ultimate-list-for-animators — A curated pile of reference (Muybridge plates onward) plus the warning that perfect symmetry kills believability.
- **Animating a Walk** — Aaron Blaise (his own channel; Disney veteran, *Brother Bear* co-director) — video — https://www.youtube.com/watch?v=5bUZc45wtXw — A former Disney animator drawing a walk in real time; watch for how early the weight decisions happen.

## Head turns

- **Animating a Head Turn: The Important Exercise Everyone Forgets!** — BaM Animation (Brent Noll & Maximus Pauson's own channel) — video — https://www.youtube.com/watch?v=3Mik2Gcrq-g — TV-animation pros on the head turn as a core exercise: anticipation, overlap, and acting choices.
- **How to Animate a Head Turn – 2D Animation Tutorial** — AMB Animation Academy (own channel) — video — https://www.youtube.com/watch?v=iDagC_BZrCA — Step-by-step head turn; the same channel's software-agnostic companion is https://www.youtube.com/watch?v=IpurGrHTnMY — useful when hopping between Clip Studio and ibisPaint.
- **Head Turn Around** — Toniko Pantoja (DreamWorks/Netflix story artist & animator; his own site) — annotated boards — https://www.tonikopantoja.com/head-turn — A pro's breakdown of a character head rotation, with teaching boards; his general tips page https://www.tonikopantoja.com/tips adds cycles and straight-ahead vs pose-to-pose comparisons.

## Flight

- **Animation – The Mechanics of Bird Flight** — Aaron Blaise (his own channel) — video — https://www.youtube.com/watch?v=2FR982O37dw — Wing mechanics for hand-drawn flight from a Disney veteran; the antidote to flapping-plank birds.
- **Tutorial: How to Animate Birds in Flight** — Animation Mentor blog (Gleb Sitnichenko) — article — https://www.animationmentor.com/blog/tutorial-how-to-animate-birds-in-flight/ — A wing is an arm (upper arm, forearm, wrist); asymmetric up/downstrokes; feather follow-through; body, head, and tail integration.
- **Tutorial: How to Animate Swimming** — Animation Mentor blog — article — https://www.animationmentor.com/blog/tutorial-how-to-animate-swimming/ — Body mechanics, timing, and flow for believable underwater motion; the companion to Lesson 6's "Swimming: flight's denser sibling" section.
- **How to Animate a Cape in the Wind** — KevinFarias, Clip Studio TIPS (Celsys' official free tutorial site) — article + video — https://tips.clip-studio.com/en-us/articles/2160 — A ten-key cape cycle in the exact software this guide targets; capes are flight's co-star.
- **Superman – The Complete Collection (1941–43)** — Fleischer/Famous Studios, on the Internet Archive — public-domain films — https://archive.org/details/superman-the-complete-collection-fleischerfamous-studios — All seventeen shorts, openly streamable and downloadable (copyrights were never renewed — background: <https://en.wikipedia.org/wiki/Superman_(1941_film)> ; single-short copy: https://archive.org/details/superman_the_mad_scientist ). The free masterclass in flight, capes, effects, and heroic staging.

## Overlap & follow-through

- **5. Follow Through & Overlapping Action – 12 Principles of Animation** — AlanBeckerTutorials — video — https://www.youtube.com/watch?v=4OxphYV8W3E — The standard visual explainer for drag, follow-through, and offsets.
- **Follow-through and Overlapping Action: The 12 Basic Principles of Animation** — Animation Mentor blog (Drew Adams) — article — https://www.animationmentor.com/blog/follow-through-and-overlapping-action-the-12-basic-principles-of-animation/ — Newton's-first-law framing (the braking car and its passenger) with hair, clothing, and earring examples; explicitly ties overlap to escaping stiff, mechanical motion.
- **Tutorial: Overlap and Pendulum Motion in Animation** — Animation Mentor blog (Anthony Wong, Pixar) — article — https://www.animationmentor.com/blog/tutorial-overlap-pendulum-motion-animation/ — The chain-mechanics deep dive: 1–2-frame offsets per joint, the travelling wave, and tuning swing decay to sell weight.
- **How to animate hair and secondary action** — Dong Chang (his own channel) — video — https://www.youtube.com/watch?v=eIgIaHXnG8U — A working animator's practical hair-and-secondary-motion demo; the "now draw it" companion to the theory articles.
- **Draw and Animate Wind-Blown Hair in Clip Studio Paint** — KevinFarias, Clip Studio TIPS (official) — article + video — https://tips.clip-studio.com/en-us/articles/10861 — A 24-frame looping wind-in-hair cycle with keys every 3 frames; prioritise softness over volume.

## Elements & effects

- **3 Magical Animated Effects – Lightning, Fire, and Sparkles** — MsRedNebula (Sarrah Wilkinson), Clip Studio TIPS (official) — article — https://tips.clip-studio.com/en-us/articles/7688 — Concrete CSP recipes: redraw lightning from scratch every frame (ignore the onion skin — the discontinuity is the crackle), 6 fps × 6 frames, glow layer on "Add (Glow)".
- **How to Animate Fire in Clip Studio Paint** — KevinFarias, Clip Studio TIPS (official) — article + video — https://tips.clip-studio.com/en-us/articles/2568 — Two looping flame cycles built on the flame lifecycle: Ascent → Swelling → Division → Reduction.
- **How To Animate Better LIGHTNING – 2D Animation Tutorial** — Micah Buzan (his own channel) — video — https://www.youtube.com/watch?v=sasfZPPLfAY — Frame-by-frame electricity from a working FX-heavy animator.
- **How to animate WATER** — Kuzillon (his own channel) — video — https://www.youtube.com/watch?v=t9Vu0rYGoIQ — Efficient hand-drawn water: masses, crests, droplets.
- **How to animate Explosions** — Dong Chang (his own channel) — video — https://www.youtube.com/watch?v=LUeELkfGR-I — Explosion and smoke technique; the debris-and-dust side of effects.
- **jkFX Animation Tutorials – 2D Flash FX** — Jason Keyser / VFX Apprentice (his own channel) — 47-video playlist — https://www.youtube.com/playlist?list=PLQD_sA-R5qVLOZ2EIi4zqsD3WSnF4QwIy — The legendary free 2D-FX series, from effect shape language to full hand-drawn elements.
- **Jason Keyser and Chris Graf share secrets behind 2D FX's magic** — Toon Boom blog (interview) — article — https://www.toonboom.com/jason-keyser-and-chris-graf-share-secrets-behind-2d-fxs-magic — Two pros on observation habits, design consistency, and effects as emotional amplifiers ("the apex of emotional resonance").
- **Pixar in a Box — Effects unit** — Khan Academy × Pixar — free interactive course — https://www.khanacademy.org/computing/pixar/effects — How Pixar thinks about effects (particles, simulated water); the simulation mindset, translated by you onto paper.
- **How to Animate Fire** — Dan Root (his own channel) — video — https://www.youtube.com/watch?v=W1NA4Lk-__M — An alternative fire walkthrough, if you want a second voice.

## Software — Clip Studio Paint (all official Celsys)

- **Basics of the Animation Feature — "How to animate #1"** — Clip Studio TIPS — https://tips.clip-studio.com/en-us/articles/2047 — New animation canvas, Timeline palette, folders and cels, fps; states the PRO/DEBUT 24-frame cap vs EX's no-limit.
- **Hand-drawn animation — "How to animate #2"** — Clip Studio TIPS — https://tips.clip-studio.com/en-us/articles/2048 — Keys with onion skin, inbetweening with the light table, camera folders, exporting; exact menu paths throughout.
- **Useful functions for hand-drawn animation — #3** — Clip Studio TIPS — https://tips.clip-studio.com/en-us/articles/2049 — Batch-creating cels, renaming cels in timeline order, multi-layer cels.
- **Official manual — Animation section** — https://help.clip-studio.com/en-us/manual_en/600_animation/600_animation.htm — The reference for everything: Timeline palette, animation folders and cels, onion skin, light table, clips, and export (MP4/GIF/APNG/WebP/image sequences; exposure-sheet export on EX).
- **Official FAQ — frame limits** — https://support.clip-studio.com/en-us/faq/articles/20210092 — Current wording of the PRO 24-frame maximum.
- **Official feature page — export options** — https://www.clipstudio.net/en/animation/tool/exporting/ — MP4 and transparency-capable GIF export, per-track image sequences.

## Software — ibisPaint X (all official ibis inc.)

- **171. Create an animation — How to use ibisPaint** — official lecture — https://ibispaint.com/lecture/index.jsp?no=182 — The official animation tutorial: Animation bar, frames, onion skin, playback modes (Loop / Ping pong / One-shot), Save Animation Video.
- **Official tutorials index** — https://ibispaint.com/lecture/index.jsp?no=0&lang=en — Where lecture 171 lives, alongside everything else.
- **ver. 11.0.0 release notes** — https://ibispaint.com/information.jsp?newsID=78536238 — "Added Animation function" (September 2023) — the feature's birth certificate.
- **New-features page (Animation Function section)** — https://ibispaint.com/newFeature.jsp?lang=en — The flip-book description, Animation bar, + button, Save Animated Video.
- **Official ibisPaint YouTube channel** — https://www.youtube.com/@ibisPaint — Official video tutorials, including animation-feature walkthroughs.

## Software — game engines & the web (Lesson 14; all official documentation or the tool's own repository)

- **2D sprite animation** — Godot official docs (verified on the 4.7-stable manual) — https://docs.godotengine.org/en/stable/tutorials/2d/2d_sprite_animation.html — The engine's own walkthrough of exactly Lesson 14's Godot workflows: AnimatedSprite2D with an image sequence, with a sprite sheet, and the AnimationPlayer alternative. Companion class references: *AnimatedSprite2D* — https://docs.godotengine.org/en/stable/classes/class_animatedsprite2d.html — *SpriteFrames* — https://docs.godotengine.org/en/stable/classes/class_spriteframes.html — and *Importing images* — https://docs.godotengine.org/en/stable/tutorials/assets_pipeline/importing_images.html
- **Godot-Universal-Fade** — KoBeWi (Godot contributor; MIT license) — addon repository — https://github.com/KoBeWi/Godot-Universal-Fade — One-line screen fades and crossfades for Godot (`Fade.fade_out()` / `Fade.fade_in()`, seven wipe patterns); Asset Library entry: https://godotengine.org/asset-library/asset/1454
- **Unity Manual, 2D & animation pages** — Unity (verified on the 6000.3 = Unity 6.3 LTS manual) — *Sprite Editor slicing* — https://docs.unity3d.com/6000.3/Documentation/Manual/sprite/sprite-editor/use-editor.html — *Sprite import settings* — https://docs.unity3d.com/6000.3/Documentation/Manual/texture-type-sprite.html — *Create a new Animation Clip* — https://docs.unity3d.com/6000.3/Documentation/Manual/animeditor-CreatingANewAnimationClip.html — *Animator Controller* — https://docs.unity3d.com/6000.3/Documentation/Manual/class-AnimatorController.html — *Animation Parameters* — https://docs.unity3d.com/6000.3/Documentation/Manual/AnimationParameters.html — *Animation Events* — https://docs.unity3d.com/6000.3/Documentation/Manual/script-AnimationWindowEvent.html
- **Unreal Engine documentation, Paper 2D** — Epic Games (verified on the current 5.8 docs; identical for 5.7) — *Paper 2D overview* — https://dev.epicgames.com/documentation/en-us/unreal-engine/paper-2d-overview-in-unreal-engine — *Import & use sprites* — https://dev.epicgames.com/documentation/en-us/unreal-engine/how-to-import-and-use-paper-2d-sprites-in-unreal-engine — *Flipbooks* — https://dev.epicgames.com/documentation/en-us/unreal-engine/paper-2d-flipbooks-in-unreal-engine — *UPaperFlipbookComponent* — https://dev.epicgames.com/documentation/en-us/unreal-engine/API/Plugins/Paper2D/UPaperFlipbookComponent
- **MDN Web Docs** — Mozilla — *CanvasRenderingContext2D.drawImage* (the 9-argument crop-and-paint call behind the canvas player) — https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/drawImage — *steps() easing function* (frame-by-frame playback in pure CSS) — https://developer.mozilla.org/en-US/docs/Web/CSS/easing-function/steps

## Pixel art — foundations (Lesson 15)

- **Pixel Art Articles** (free beginner series, 8 parts) — Pedro Medeiros / Saint11 (pixel artist of *Celeste*; his own site) — articles — https://saint11.art/pixel_articles — Start here: *An Absolute Beginner's Guide* (16×16 first, 4–12 colours, pixel-perfect lines, orphan pixels) — https://saint11.art/pixel_art_articles/article1 — *Cluster Sketching and Painting* — https://saint11.art/pixel_art_articles/article2 — *A Basic Aseprite Animation* — https://saint11.art/pixel_art_articles/article3 — *Basic Shading* — https://saint11.art/pixel_art_articles/article4 — *Anti-Alias and Banding* — https://saint11.art/pixel_art_articles/article5 — *Basic Color Theory* — https://saint11.art/pixel_art_articles/article6 — *Working with lines* (on Medium; free to read, though Medium may nag you to sign in) — https://medium.com/pixel-grimoire/how-to-start-making-pixel-art-7-e504bfa4ddf2 — *Saving and Exporting Pixel Art* (on Medium; free to read) — https://medium.com/pixel-grimoire/how-to-start-making-pixel-art-8-eb218a4637dd — Companion pages: *Glossary* — https://saint11.art/blog/glossary/ — *Scaling Pixel Art* — https://saint11.art/blog/scaling/ — *Consistency* — https://saint11.art/blog/consistency/ — *My Thoughts on Very Low Resolution* — https://saint11.art/blog/thoughts_on_low_resolution — His tutorials are released under CC BY 4.0 (stated in the GitHub repository that hosts them: https://github.com/saint11/Saint11Tutorials ).
- **Pixel Art Tutorial: Basics** — Derek Yu (creator of *Spelunky*; his own site) — article — https://www.derekyu.com/makegames/pixelart.html — The eight-step sprite process (sketch → clean lines → flat colour → shade → anti-alias → selective outline → touches and dither → review), with the clearest definitions of jaggies, banding, and selout in print; "Pixel art is defined by its constraints."
- **PIXNOTE — Learn** — PIXNOTE (a free browser pixel-art maker with a tutorial wing) — articles — https://pixnote.net/en/learn/ — *Getting Started* — https://pixnote.net/en/learn/getting-started/ — *Outlines & Anti-Aliasing (selout)* — https://pixnote.net/en/learn/outlines/ — *Characters* (sizes, head ratios, the silhouette test, "moving an eye by one pixel changes expression") — https://pixnote.net/en/learn/character/ — *Glossary with visual demos* — https://pixnote.net/en/learn/glossary/ — Free to read; tidy, numerical, beginner-first.
- **Pixelblog** (the complete catalogue) — Raymond Schlitter / SLYNYRD (his own site) — illustrated tutorials — https://www.slynyrd.com/pixelblog-catalogue — Foundations posts used in Lesson 15: *5 – Back to Basics* (clusters, scale only by whole multiples) — https://www.slynyrd.com/blog/2018/5/16/pixelblog-5-back-to-basics — *7 – Developing Style* — https://www.slynyrd.com/blog/2018/7/14/pixelblog-7-developing-style — *17 – Human Anatomy* — https://www.slynyrd.com/blog/2019/5/21/pixelblog-17-human-anatomy — *22 – Top Down Character Sprites* — https://www.slynyrd.com/blog/2019/10/21/pixelblog-22-top-down-character-sprites — *47 – Tiny Pixels* ("The beauty of pixel art comes from the lack of information") — https://www.slynyrd.com/blog/2023/11/26/pixelblog-47-tiny-pixels
- **The Pixel Art Tutorial** — Cure, Pixel Joint forum (2010) — forum tutorial — https://pixeljoint.com/forum/forum_posts.asp?TID=11299&PID=139318 — The community's foundational text: what pixel art is, terms to know, things to avoid, and "Never, ever save as JPG."
- **Ramblethread! A brainstorm approaches!** — Pixelation forum — forum thread (the live topic page no longer loads, so this is a Wayback Machine copy) — https://web.archive.org/web/20250323171825/https://pixelation.org/index.php?topic=8110.0 — The cluster doctrine in raw form: "The prime job of the pixel artist is to find the ideal shape for every cluster"; "Perfect lines are the 90 and 45 degree ones."
- **Pixel Art Tutorial** — Arne Niklas Jansson (his own site, androidarts.com) — article — https://androidarts.com/pixtut/pixelart.htm — A painter's approach to pixels: outlines and top-lighting, orphan pixels, hue-shifted ramps, banding, dithering as texture, designing for the grid's angles. Companion *PSG Art Tutorial* — https://androidarts.com/art_tut.htm
- **Readability – Pixel art style possibilities** / **Pixel Art – Shapes and Outlines** — Thomas Feichtmeir / Cyangmou (originally on his DeviantArt, since taken down; Wayback Machine copies) — tutorial charts — https://web.archive.org/web/20220914214941/https://www.deviantart.com/cyangmou/art/Readability-Pixel-art-Style-possibilities-723970229 — https://web.archive.org/web/20221205174609/https://www.deviantart.com/cyangmou/art/Pixel-Art-Shapes-and-Outlines-722784595 — Readability as shape contrast; outline styles from minimal to complex and which suit small vs large sprites.
- **3 PixelArt Techniques/Common Mistakes (Doubles, Jaggies & Outline)** / **Basic Anti-Aliasing for beginners** — MortMort (his own channel) — videos — https://www.youtube.com/watch?v=gW1G_FLsuEs — https://www.youtube.com/watch?v=UN-m3o9V7kk — Short, visual, and exactly on target for Lesson 15's line faults.
- **Pixel Art Class – What is Pixel Art?** — AdamCYounis (his own channel) — video — https://www.youtube.com/watch?v=7BWr2tlK-4c — The opening of a 57-video free series; the full playlist is https://www.youtube.com/playlist?list=PLLdxW--S_0h4dlWUpl-TzBp-ulqK3NiM_
- **Pixel Art: Where to Start** — Lospec (skeddles) — article — https://lospec.com/pixel-art-where-to-start — Use a ready-made palette, pick an editor, start now; communities to join. Lospec's searchable tutorial database (hundreds of entries, tagged) — https://lospec.com/pixel-art-tutorials
- **Pixel art** / **Spatial anti-aliasing** / **Sprite (computer graphics)** / **Pixel-art scaling algorithms** — Wikipedia — encyclopedia articles — https://en.wikipedia.org/wiki/Pixel_art — https://en.wikipedia.org/wiki/Spatial_anti-aliasing — https://en.wikipedia.org/wiki/Sprite_(computer_graphics) — https://en.wikipedia.org/wiki/Pixel-art_scaling_algorithms — Definitions and history (the 1982 Xerox PARC coinage; why sprites are called sprites); the last one explains the hqx/xBR filters emulators use — and why you never run them on art you authored.

## Pixel art — colour (Lesson 16)

- **Pixelblog 1 – Color Palettes** / **6 – Light and Shadow** — Raymond Schlitter / SLYNYRD — https://www.slynyrd.com/blog/2018/1/10/pixelblog-1-color-palettes — https://www.slynyrd.com/blog/2018/6/15/pixelblog-6-light-and-shadow — HSB ramps with 20° of hue shift per swatch (saturation peaking mid-ramp in his example, "not a hard rule"); light source first, light as mood.
- **Shading & Lighting** / **Dithering** — PIXNOTE — https://pixnote.net/en/learn/shading/ — https://pixnote.net/en/learn/dithering/ — Hue shifting as "the most important technique for attractive pixel art shadows"; tone counts by sprite size; the five dither patterns and when not to use them.
- **Palette List** — Lospec — palette database (free downloads in PNG/PAL/ASE/GPL/HEX) — https://lospec.com/palette-list — Named palettes used in this guide: *ENDESGA 32* — https://lospec.com/palette-list/endesga-32 — *DawnBringer 32* (Aseprite's default) — https://lospec.com/palette-list/dawnbringer-32 — *PICO-8* — https://lospec.com/palette-list/pico-8 — *Sweetie 16* — https://lospec.com/palette-list/sweetie-16 — *AAP-64* — https://lospec.com/palette-list/aap-64 — *ARQ4* — https://lospec.com/palette-list/arq4 — *AAP-Micro12* — https://lospec.com/palette-list/aap-micro12
- **Pixel Art Class – Palettes & Colour** / **Lighting & Shading Basics** / **Palette Mixing Tutorial** — AdamCYounis — videos — https://www.youtube.com/watch?v=hkrK65FPmDI — https://www.youtube.com/watch?v=u7v4uEDwW9o — https://www.youtube.com/watch?v=rSy9xef-MXM
- **1-Bit Pixel Art Techniques** — Brandon James Greer (his own channel) — video — https://www.youtube.com/watch?v=0BZwEoj50uw — What two colours can do when pattern and silhouette carry everything. His Clip Studio colour videos on Celsys' official channel: *3 shading and coloring tips for clean pixel art!* — https://www.youtube.com/watch?v=ihmH5jFn_a4 — *1 must-know tip when coloring pixel art!* — https://www.youtube.com/watch?v=lCv-HAEHMVE
- **So You Want To Be A Pixel Artist?** — Tsugumo (early-2000s classic; community mirror, the original site is long gone) — text tutorial — index: https://mirror.motherhamster.org/tsugumo/default.html — chapter 6 (dithering, black as a key colour, keep floors low-contrast so the player never squints): http://www.geocities.ws/skulkraken2002/Tsugumo/chapter6.htm — Cited as a historical text that has circulated freely with the author's name for two decades; no formal licence exists.
- **Dither** / **Ordered dithering** / **Indexed color** — Wikipedia — https://en.wikipedia.org/wiki/Dither — https://en.wikipedia.org/wiki/Ordered_dithering — https://en.wikipedia.org/wiki/Indexed_color — Where the word comes from (WWII bomb computers that ran better while trembling), the Bayer matrix, and why old hardware had palettes at all.
- **Palette Swap** — Giant Bomb (community wiki; definition) — https://www.giantbomb.com/wiki/Concepts/Palette_Swap — and TV Tropes (community wiki; the game-history examples: Pac-Man's ghosts, Luigi, mirror matches, the ninjas) — https://tvtropes.org/pmwiki/pmwiki.php/Main/PaletteSwap — Pop references for Lesson 16's recolour trick, not craft sources.

## Pixel art — animation (Lesson 17)

- **Pixel Art Tutorials** (the animated boards) — Pedro Medeiros / Saint11 — ~90 free 512×512 animated tutorial sheets on one page — https://saint11.art/blog/pixel-art-tutorials/ — Walk, run, idle, jump, wall-slide, top-down cycles, sub-pixel, squash, easing, motion blur, outlines, silhouette, fabric, fire, water, smoke, explosions, electricity, wind, wings and more. "All these tutorials are free to access" (his words); also mirrored in the CC BY 4.0 repository above. The itch.io zip of the same boards is an optional $5 convenience, not a paywall.
- **Pixelblog — animation posts** — Raymond Schlitter / SLYNYRD — *8 – Intro to Animation* ("Too many frames can leach the energy from your motion") — https://www.slynyrd.com/blog/2018/8/19/pixelblog-8-intro-to-animation — *9 – Melee Attacks* — https://www.slynyrd.com/blog/2018/9/8/pixelblog-9-melee-attacks — *10 – Water in Motion* — https://www.slynyrd.com/blog/2018/10/12/pixelblog-10-water-in-motion — *25 – Motion Cycles* (walk, dog walk, bird flight in 8 frames) — https://www.slynyrd.com/blog/2020/1/23/pixelblog-25-motion-cycles — *33 – Wind Effects* — https://www.slynyrd.com/blog/2021/7/16/pixelblog-33-wind-effects — *50 – Human Walk Cycle* (triangle-wave head bob; arm swing as personality) — https://www.slynyrd.com/blog/2024/5/24/pixelblog-50-human-walk-cycle — *52 – Idle Fighting Stance* ("one of the most effective means of displaying personality") — https://www.slynyrd.com/blog/2024/9/26/pixelblog-52-idle-fighting-stance — *53 – Punches and Kicks* (smears, held hit frames) — https://www.slynyrd.com/blog/2024/11/25/pixelblog-53-punches-and-kicks — *55 – Top Down Character Animation* — https://www.slynyrd.com/blog/2025/3/24/pixelblog-55-top-down-character-animation — *58 – Part 3* (ms timings) — https://www.slynyrd.com/blog/2025/10/2/pixelblog-58-top-down-character-animation-part-3 — *60 – Side View Run 'N Gun* — https://www.slynyrd.com/blog/2026/1/26/side-view-run-n-gun
- **How to Animate Pixel Art** and the flipbook lessons — PIXNOTE — https://pixnote.net/en/learn/animation/ — *Walk cycle* — https://pixnote.net/en/learn/animate-walk-cycle/ — *Jump* — https://pixnote.net/en/learn/animate-jump/ — *Bouncing ball* — https://pixnote.net/en/learn/animate-bouncing-ball/ — *Waving (flags, hair, tails)* — https://pixnote.net/en/learn/animate-waving/ — fps bands (8–12 standard, 4–6 idle, 15–24 attacks), frame counts, and the follow-through wave.
- **So You Want To Be A Pixel Artist? — chapter 10, Breathing Life Into Your Sprites** — Tsugumo (community mirror) — http://www.geocities.ws/skulkraken2002/Tsugumo/chapter10.htm — The personality-idle text: breathing in four frames, peaks held longer, "The animation you give your character should be based on their personality," and "Less is more."
- **Walk Cycles, Part 1** — Jason Perry, Final Boss Blues (his own site) — article — http://finalbossblues.com/walk-cycles-p1/ — 3-, 4-, and 8-frame RPG walks; "lift-plant-push"; the backward drag of the planted foot.
- **Pixel art Character Animations guide** — Sandro Maglione (his own site) — article — https://www.sandromaglione.com/articles/pixel-art-character-animations-guide — A 16×16 character's idle, walk, and jump with frame counts, including the one-frame hair delay.
- **Pixel Art Class — animation episodes** — AdamCYounis — videos — *Sub-Pixel Animation* — https://www.youtube.com/watch?v=cs1Gp61yafQ — *Simple Character Idle Animation* — https://www.youtube.com/watch?v=vs-ierVdE7I — *Run Animation Tutorial [Part 1]* — https://www.youtube.com/watch?v=LPBvrdJ_1a8 — *Making Pixel Art Worth Animating* — https://www.youtube.com/watch?v=52A4KgX-wNI — *Attack Animations* — https://www.youtube.com/watch?v=nJbzBSVy1u0
- **Pixel Art Character Animation | Tips, Tricks, and Workflow** — Brandon James Greer — video — https://www.youtube.com/watch?v=jdnCOlATb-c
- **Easy Pixel Art Walk Cycle Tutorial** — Saultoons (own channel) — https://www.youtube.com/watch?v=7T6yOk5n-zk — **How To Pixel Art Tutorials [17] – Walk Cycle (6 & 8 frames)** and **[12] – 2&4 Frames Walk/Run Cycle Animations** — Dual Core Studio (own channel) — https://www.youtube.com/watch?v=5QTCwiJUmmo — https://www.youtube.com/watch?v=9lemPuqxIug — **The secrets to good Pixel Art animation!** — Pixel Overload (own channel) — https://www.youtube.com/watch?v=J1sFBDQt8J0
- **Pixilart tutorials by Jason Tomlee** — Pixilart (free browser editor with a community tutorial wing) — image tutorials — *Fire: Shading and Animation* — https://www.pixilart.com/tutorial/fire-shading-and-animation-115 — *Animation: Squash & Stretch* — https://www.pixilart.com/tutorial/animation-squash-stretch-61 — *Animation – Anticipation* — https://www.pixilart.com/tutorial/animation-anticipation-62 — *SmokePoofs – Movement* — https://www.pixilart.com/tutorial/smokepoofs-movement-51 — Tutorials hub: https://www.pixilart.com/tutorials
- **Lospec tutorial tags** — *walkcycle* — https://lospec.com/pixel-art-tutorials/tags/walkcycle — *animation* — https://lospec.com/pixel-art-tutorials/tags/animation
- **Idle animation** — Wikipedia — https://en.wikipedia.org/wiki/Idle_animation — Why idles exist ("to give personality towards games and their characters"), from 1978 to Sonic's foot-tap.

## Software — pixel art in Clip Studio Paint (Lesson 18; all on Celsys' official sites)

- **How to Draw Pixel Art: A Tutorial** — Dado Almeida, Art Rocket (clipstudio.net) — https://www.clipstudio.net/how-to-draw/archives/161082 — The canonical CSP pixel setup: 64×64, a one-pixel grid, a second window at 100 %, the Dot pen, anti-aliasing off everywhere, Hard edges on transforms, PNG/GIF never JPEG.
- **Official manual pages** — *Special brushes* (Dot pen) — https://help.clip-studio.com/en-us/manual_en/240_brushes/Special_brushes.htm — *Anti-aliasing* (Advanced Tool Settings: None/Weak/Middle/Strong) — https://help.clip-studio.com/en-us/manual_en/810_subtools/A.htm — *Change Image Resolution* (Smooth edges / Hard edges (nearest neighbor) / Clear edges / High accuracy) — https://help.clip-studio.com/en-us/manual_en/210_file/Change_canvas_size.htm — *Creating a new canvas* (timeline Image interpolation) — https://help.clip-studio.com/en-us/manual_en/210_file/Creating_a_New_Canvas.htm — *Ruler bar and grid* — https://help.clip-studio.com/en-us/manual_en/270_canvas/Using_the_ruler_bar_and_grid.htm — *Preferences* (Display quality) — https://help.clip-studio.com/en-us/manual_en/720_preferences/Preferences.htm — *Color Set palette* — https://help.clip-studio.com/en-us/manual_en/300_color/Color_Set_palette.htm — *Exporting files* — https://help.clip-studio.com/en-us/manual_en/210_file/Exporting_files.htm — *Export animation* (GIF dithering, image sequences) — https://help.clip-studio.com/en-us/manual_en/600_animation/Export_animation.htm — *Filters* (Mosaic) — https://help.clip-studio.com/en-us/manual_en/390_filters/Filters.htm — Release notes (Ver. 5 palette renames) — https://www.clipstudio.net/en/dl/release_note/latest/
- **Clip Studio TIPS (official tutorial site)** — KevinFarias, *How to make PIXEL ART Animation in Clip Studio Paint* — https://tips.clip-studio.com/en-us/articles/5314 — babeoded, *Animated Retro Pixel Art for Game Splash Screen* (128×72 canvas, Dot pen, Hard edges timeline, image-sequence export) — https://tips.clip-studio.com/en-us/articles/3562 — babeoded, *Making Pixel Art Forest Tilesets* (Color Set palettes, 32×32 tiles) — https://tips.clip-studio.com/en-us/articles/7567 — Naoi21-arts, *Turn Your Illustrations into Pixel Art Using Clip Studio* (names the grid dialog's "Gap(D)" and "Number of divisions" fields) — https://tips.clip-studio.com/en-us/articles/5384 — FrostDrive, *Pixel Art Practices Explained Simply* (why not to scale in the export dialog) — https://tips.clip-studio.com/en-us/articles/5360 — TamilVolk, *Dive into Pixel Art* — https://tips.clip-studio.com/en-us/articles/5277 — robertoivy_01, *Pixel Art Characters: Workflow, Setup & Styles* — https://tips.clip-studio.com/en-us/articles/11460 — Livresquare, *Creating Pixel Character Art: from Sketch to Sprite* — https://tips.clip-studio.com/en-us/articles/11408
- **Official CLIP STUDIO PAINT channel — pixel-art videos** — Brandon James Greer, *How to correctly scale and texture pixel art in Clip Studio Paint* — https://www.youtube.com/watch?v=LgDA3RqbgCY — *Animate your pixel art with Clip Studio Paint!* — https://www.youtube.com/watch?v=L3AXOqtuY2o — *Designing pixel art characters and game scenes!* — https://www.youtube.com/watch?v=lIhpsoSFtBo — Dadotronic, *How to make custom pixel art tools in Clip Studio Paint* — https://www.youtube.com/watch?v=ChwPpSbD524

## Software — pixel art in ibisPaint X (Lesson 18; all official ibis inc. pages)

- **Lecture 53. Display Grid on the Canvas** — https://ibispaint.com/lecture/index.jsp?no=171&lang=en — The official pixel-art setup: 32×32 canvas, Grid on, Display when zooming → Pixelated, Digital Pen at 1.0 px.
- **Lecture 184. View Menu Details** (Grid Settings; Display when zooming: "'Pixelated' is better when drawing pixel art") — https://ibispaint.com/lecture/index.jsp?no=168&lang=en
- **Lecture 179. Details of Brush Parameters** (Antialias, MSAA, Texture Antialiasing) — https://ibispaint.com/lecture/index.jsp?no=118&lang=en
- **Lecture 180. Bucket tool details** (Strength, Expansion) — https://ibispaint.com/lecture/index.jsp?no=82&lang=en
- **Lecture 67. Changing image resolution with Resize** (Nearest Neighbor (Pixel) "recommended for enlarging and reducing pixel art") — https://ibispaint.com/lecture/index.jsp?no=77&lang=en
- **Lecture 182. Transform Tool Details** (Interpolation Method: Nearest Neighbor (Dot)) — https://ibispaint.com/lecture/index.jsp?no=154&lang=en
- **Lecture 54. Export an Artwork (Save)** (PNG, Transparent, the AI "Super-resolution x2" to avoid) — https://ibispaint.com/lecture/index.jsp?no=206&lang=en
- **New-features page** (Grid and "Display when zooming" under Ver. 10; palettes under Ver. 14) — https://ibispaint.com/newFeature.jsp?lang=en — **Release notes**: ver. 10.0.1 (grid; zoom interpolation) — https://ibispaint.com/information.jsp?newsID=54735849 — ver. 9.0.0 (Nearest Neighbor in the Transform tool) — https://ibispaint.com/information.jsp?newsID=22182838
- **News: "How to draw Pixel Art"** (official video by the creator Esu, on the official ibisPaint channel) — https://ibispaint.com/information.jsp?newsID=26557593

## Software — pixel editors (Lesson 18; the tools' own sites and repositories)

- **Pixelorama** — Orama Interactive — free, MIT — homepage and docs: https://pixelorama.org/ — itch.io page (Windows/macOS/Linux/Android builds and the in-browser version): https://orama-interactive.itch.io/pixelorama — GitHub: https://github.com/Orama-Interactive/Pixelorama — Timeline, onion skin, frame tags, indexed mode, palettes, spritesheet/GIF/APNG export, tilemap layers.
- **LibreSprite** — free, GPLv2 — https://libresprite.github.io/ — GitHub: https://github.com/LibreSprite/LibreSprite — "Fork of the last GPLv2 commit of Aseprite" (2016), developed independently; Windows, macOS, Linux, Android, web build.
- **Piskel** — Julian Descottes — free, Apache-2.0 — https://www.piskelapp.com/ — GitHub: https://github.com/piskelapp/piskel — Browser sprite editor with GIF/PNG/spritesheet export; desktop builds are best-effort and dated (the site recommends the web version).
- **GraphicsGale** — HUMANBALANCE — freeware since June 2017, Windows only — https://graphicsgale.com/us/ — Onion skin, real-time preview, palette control, sprite-sheet and GIF export.
- **Pixilart editor** — free, browser — https://www.pixilart.com/draw — Frames, onion skin, pixel-perfect pencil toggle, GIF/WEBP/MP4/sprite-sheet export.
- **Krita** — free, GPLv3 — *Animation* — https://docs.krita.org/en/user_manual/animation.html — *Display settings* (Nearest Neighbour canvas scaling, pixel grid) — https://docs.krita.org/en/reference_manual/preferences/display_settings.html — *Onion skin docker* — https://docs.krita.org/en/reference_manual/dockers/onion_skin.html — *Brush preset bundle* (the Pixel presets) — https://docs.krita.org/en/reference_manual/krita_4_preset_bundle.html
- **GIMP** — free, GPL — *Pencil tool* ("does not even do anti-aliasing") — https://docs.gimp.org/en/gimp-tool-pencil.html — *Indexed mode* — https://docs.gimp.org/en/gimp-image-convert-indexed.html — *Scale Image* — https://docs.gimp.org/en/gimp-image-scale.html
- **Aseprite** — Igara Studio — $19.99 for official builds; source available for personal compilation — https://www.aseprite.org/ — FAQ (price, the 2016 licence change, "download its source code, compile it, and use it for your personal purposes") — https://www.aseprite.org/faq/ — GitHub — https://github.com/aseprite/aseprite — EULA — https://raw.githubusercontent.com/aseprite/aseprite/main/EULA.txt — Docs: *Color modes* (Indexed, up to 256) — https://www.aseprite.org/docs/color-mode/ — *Color bar* (the palette lock) — https://www.aseprite.org/docs/color-bar/ — *Timeline* — https://www.aseprite.org/docs/timeline/ — *Onion skinning* — https://www.aseprite.org/docs/onion-skinning/ — *Tags* — https://www.aseprite.org/docs/tags/ — *Loop section* — https://www.aseprite.org/docs/loop/ — *Sprite sheet export* — https://www.aseprite.org/docs/sprite-sheet/ — *Command-line interface* — https://www.aseprite.org/docs/cli/ — *Default palette* (DawnBringer 32) — https://www.aseprite.org/docs/default-palette/ — MortMort's video on-ramps: *Aseprite Guide for Beginners* — https://www.youtube.com/watch?v=Md6W79jtLJM — *Aseprite Animation Timeline & tools* — https://www.youtube.com/watch?v=N4Z4MdZ1KWY

## Software — pixel-perfect game settings (Lesson 18; official documentation)

- **Godot — Multiple resolutions** (stretch mode viewport, aspect keep, integer scale mode, snap settings; "Most pixel art games use viewport sizes between 256×224 and 640×480") — https://docs.godotengine.org/en/stable/tutorials/rendering/multiple_resolutions.html — *Importing images* (Lossless for pixel art) — https://docs.godotengine.org/en/stable/tutorials/assets_pipeline/importing_images.html — *Sprite2D* class reference (the pixel-snap note) — https://docs.godotengine.org/en/stable/classes/class_sprite2d.html
- **Unity — Pixel Perfect Camera (URP)** — component reference — https://docs.unity3d.com/6000.3/Documentation/Manual/urp/2d-pixelperfect-ref.html — *Add a pixel perfect camera* (sprite prerequisites: same Pixels Per Unit, Filter Mode Point, Compression None) — https://docs.unity3d.com/6000.3/Documentation/Manual/urp/2d-pixelperfect-prep-sprites.html
- **Unreal — Import & use Paper 2D sprites** ("Sprite Actions > Apply Paper 2D Import Settings … removes Mipmaps, sets the Filter to Nearest") — https://dev.epicgames.com/documentation/en-us/unreal-engine/how-to-import-and-use-paper-2d-sprites-in-unreal-engine — *Orthographic camera* — https://dev.epicgames.com/documentation/unreal-engine/orthographic-camera-in-unreal-engine?lang=en-US
- **MDN — image-rendering** (`pixelated`, `crisp-edges`) — https://developer.mozilla.org/en-US/docs/Web/CSS/image-rendering — **CanvasRenderingContext2D.imageSmoothingEnabled** — https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/imageSmoothingEnabled

## Free, legal practice material for pixel art

- **Kenney — free game assets (CC0)** — https://kenney.nl/assets — e.g. *Pixel Platformer* (18×18 tiles) — https://kenney.nl/assets/pixel-platformer — *Tiny Dungeon* (16×16) — https://kenney.nl/assets/tiny-dungeon — Public-domain (CC0) sprites you may open in your editor, study pixel by pixel, recolour, and re-animate without asking anyone.
- **PICO-8 Education Edition** — Lexaloffle — free in the browser — https://www.pico-8-edu.com/ — about page: https://www.lexaloffle.com/pico-8.php?page=schools — A 128×128, 16-colour, 8×8-sprite fantasy console with its own sprite editor; the purest constraint gym there is. (The full PICO-8 is paid; the education edition lacks only exporters and the cartridge browser.)

## Public-domain study shelf

- **Superman – The Complete Collection** (Fleischer, 1941–43) — https://archive.org/details/superman-the-complete-collection-fleischerfamous-studios — flight, capes, electricity, fire, water, staging.
- **Gertie the Dinosaur** (Winsor McCay, 1914) — https://archive.org/details/gertiethe-dinosaur-512kb — the origin of personality animation; weight and temperament with zero dialogue.
- **The Sunshine Makers** (Van Beuren, 1935) — https://archive.org/details/The_Sunshine_Makers_1935 — elegant vs scruffy movement dialects inside one film.
- **Advanced Animation** (Preston Blair, 1940s) — https://archive.org/details/advanced-animation-by-preston-blair — the classic instruction book, openly downloadable (PDF/EPUB); the archive labels it public domain (the 1940s edition's copyright is commonly cited as unrenewed — and note it's the *original* edition that's free, not the modern revised "Cartoon Animation").

## Practice

- **51 Great Animation Exercises to Master** — J.K. Riki, Animator Island — article — https://www.animatorisland.com/51-great-animation-exercises-to-master/ — The community's canonical drill list in four difficulty tiers, bouncing ball to full acting; this guide's Lesson 13 is designed to feed into it.

## The paid shelf (not free — listed for honesty, with legal access routes)

These four books are the craft's holy texts, and none is legally free online (two pixel-art items follow them). As of this guide's check (16 Aug 2026), none had a borrowable controlled-lending copy on Open Library/Internet Archive either — so the honest free route is your **public library** (physical or via the Libby app); otherwise, used copies are plentiful.

- **The Animator's Survival Kit** — Richard Williams — *the* modern textbook of timing, spacing, and walks; Lesson 4 is heavily in its debt.
- **The Illusion of Life: Disney Animation** — Frank Thomas & Ollie Johnston — the source of the twelve principles, and the best-illustrated animation book ever printed.
- **Elemental Magic, Volume I** — Joseph Gilland — the classic on hand-drawn effects: fire, water, smoke, magic.
- **Cartoon Animation** — Preston Blair (modern Walter Foster edition) — the revised, in-print descendant of the free 1940s book above.
- **Pixel Logic – A Guide to Pixel Art** — Michael Azzi — the modern visual pixel-art textbook (line art, anti-aliasing, colour, readability, dithering, sub-pixelling, animation); a 242-page PDF sold for about $10 — https://michafrar.gumroad.com/l/pixel-logic — (the Scribd/archive copies that circulate are unauthorised; don't).
- **Aseprite** — Igara Studio — the standard pixel-animation program; $19.99 for the official builds, or free if you compile the public source yourself for personal use (details and links in Lesson 18).

---

# Master Glossary (same wording as the lessons — that's the point)

- **1-bit** — a palette of exactly two colours.
- **anti-aliasing (AA)** — placing in-between colours by hand at the stair-steps of an edge so it reads smoother at real size; as an *app setting*, the automatic edge-softening that stays off for pixel art.
- **anticipation** — a small preparatory move (often in the opposite direction) before the main action; the wind-up before the pitch.
- **arc** — the curved path almost every natural motion travels along.
- **animating "on ones" / "on twos"** — a new drawing every frame (24/sec) / each drawing held 2 frames (12/sec).
- **animation folder** (Clip Studio) — the container whose cels are treated as frames of one animated element.
- **banding** — parallel bands of colour hugging a shape's edge like contour lines; the eye sees the borders instead of the form.
- **boiling** — the lively shimmer when redrawn lines wobble slightly frame to frame; noise when accidental, texture when chosen.
- **breakdown** — the drawing between two keys that decides *how* the motion travels, not just where it ends.
- **cel** — one drawing in the animation stack (a layer, or folder of layers, in Clip Studio).
- **cluster** — a continuous group of touching pixels of the same colour; the brushstroke of pixel art.
- **contrapposto** — the natural stance with weight on one leg, hips tilted one way, shoulders counter-tilted.
- **counter-rotation** — hips twist one way, shoulders twist the other; the body's balancing twist.
- **cycle** — a set of drawings that loops seamlessly; the last flows back into the first.
- **dithering** — placing two colours in a pattern (checkerboard, stripes, ordered grids) so the eye blends them into a third colour or a texture.
- **doubles** — a spot where a one-pixel line has two pixels side by side at a corner, so it looks thicker there.
- **drag** — a trailing part lags behind because its base moved first.
- **flipbook** — Unreal's name for a playable stack of sprite frames; a good mental model for game animation everywhere.
- **flour sack** — the classic practice prop: a half-full sack animated as a character; all acting, no face.
- **follow-through** — loose parts (hair, cloth, tails, flesh) keep moving after the main body stops.
- **fps (frames per second)** — how many frames play each second.
- **frame** — one single image in an animation; film traditionally shows 24 per second.
- **frame tag** — in Aseprite and Pixelorama, a named range of frames (`idle`, `walk`) treated as one animation.
- **hold** — a drawing shown longer than its neighbours; in pixel art, holds do much of the acting.
- **hue / saturation / value** — a colour's family (red, teal…); its intensity (grey → vivid); its lightness.
- **hue-shifting** — moving the hue as a ramp goes from shadow to light (cooler in shadow, warmer in light) instead of only changing the value.
- **idle** — what a game character does while the player does nothing; a short loop, and the sprite's chief personality display.
- **inbetween** — a drawing that fills the gap between two key drawings.
- **indexed colour** — an image format in which each pixel stores a palette number, not a colour; change the palette and the whole picture recolours.
- **integer scaling** — enlarging only by whole numbers (2×, 3×, 4×) so every pixel stays a clean square.
- **jaggies** — unintended bumps and uneven stair-steps along a line or curve, where the steps don't follow a consistent rhythm.
- **key drawing** — one of the main storytelling drawings; the rest exist to connect the keys.
- **light table** (Clip Studio) — pins reference drawings faintly under your working cel, like a lit glass desk.
- **line of action** — the single imaginary curve running through a pose, giving it energy and direction.
- **milliseconds per frame (ms)** — the per-frame timing pixel tools use: 100 ms = 10 fps · 125 ms = 8 fps · 83 ms ≈ 12 fps · 50 ms = 20 fps.
- **nearest neighbour** — scaling that copies each pixel as a hard square with no blur; also called hard edges, point, none, or pixelated.
- **onion skin** — a ghost view of the frames before/after the one you're drawing.
- **orphan pixel** — a single pixel touching no other pixel of its colour; noise unless it is deliberately a particle or texture.
- **outline / selective outline ("selout")** — a dark line around a sprite's silhouette / an outline that lightens where the light hits and darkens in shadow instead of being flat black.
- **overlapping action** — different parts start and stop at slightly different times, never all at once.
- **overshoot and settle** — motion goes slightly past its target, then eases back into place.
- **palette** — the fixed list of colours an image is allowed to use.
- **palette swap** — reusing one sprite with a different palette to make a "new" character.
- **pillow shading** — shading every edge dark towards a bright centre with no light direction; everything looks like a cushion.
- **pivot / origin** — the anchor point of a sprite (feet, center); keep it consistent across frames or the character jitters.
- **pixel** — "picture element": the smallest square of colour a screen can show; in pixel art, the only building block, placed by hand.
- **pixel-perfect line / mode** — a one-pixel line that connects diagonally without doubles / the pencil mode in pixel editors that removes doubles as you draw.
- **P·I·X·L** — the Part VII pocket mnemonic: Palette small · Integer scale · eXport PNG · Look at 100 %.
- **pose to pose / straight ahead** — plan key drawings first, then fill between / draw frame 1, 2, 3…, discovering as you go.
- **ramp** — a short row of palette colours from dark to light used to shade one material.
- **resolution / canvas size** — the width × height of an image in pixels; "low resolution" simply means few pixels.
- **secondary action** — a smaller supporting action layered on the main one, adding character without stealing focus.
- **silhouette** — the solid-black outline shape of a pose; if the action reads in silhouette, it reads.
- **slow in and slow out** — bunching drawings at the start and end of a move so it eases in and out.
- **smear** — a deliberately stretched or multiplied drawing shown for a frame or two to sell extreme speed.
- **spacing** — how far the drawing moves between one frame and the next; the handwriting of motion.
- **sprite** — a 2D image a game engine can place, move, and draw on screen.
- **sprite sheet** (texture atlas) — many animation frames packed into one image in a grid, sliced apart by the engine.
- **squash and stretch** — a form flattening under force and lengthening with speed, volume constant.
- **staging** — presenting an action so it reads instantly: clear silhouette, clear framing, one idea at a time.
- **sub-pixel animation** — faking movement smaller than one pixel by changing the colours at an edge instead of moving whole pixels.
- **texture filtering** — how an engine smooths a scaled image: Nearest/Point = crisp pixels (pixel art), Linear/Bilinear = soft blending (high-res drawings).
- **timing** — how many frames an action takes; how long it lasts; the clock of motion.

---

## A closing note

Every lesson in this book is the same sentence in a different costume — so here it is one last time, to carry with you:

> **Cause first → body next → loose parts last → settle.**
>
> And at every step, the *dials* — timing, spacing, arcs, anticipation, overlap — are not physics homework. They are casting decisions. Turn them, and someone new walks in.

> And the pocket version, one last time: **C·B·L·S — "Cool Bodies Lag Softly."**

Happy animating. Draw the contact pose first.

---

*The Living Line is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) © esorhizome OÜ.*

