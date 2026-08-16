# The Living Line

## A Hand-Drawn Animation Guide to Personality, Persona & Appeal

**Standalone lessons for Clip Studio Paint EX (desktop) and ibisPaint X (mobile)**

*August 2026 · Every link in this guide was fetched and checked live on 16 August 2026.*

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
> **C**ause · **B**ody · **L**oose · **S**ettle. Four letters, and the phrase itself describes the physics: a cool (calm) body moves, its loose parts lag, and everything settles softly. If you remember nothing else while drawing, remember these four letters — they are the order you animate *everything*. (Lesson 2 adds a twelve-beat chant for the twelve classic principles, if you want the full deck in your pocket.)

## The one idea underneath everything

Personality in animation is not *what* a character does. It is *how the drawings choose to do it.* The same head-turn, drawn with different timing, different curves, and different amounts of lag, can read as shy, smug, alien, dignified, or exhausted — without changing the character design at all.

If you want proof before you invest a single hour: watch Cento Lodigiani's three-minute film *The illusion of life* (link in the bibliography, Lesson 15). It demonstrates every classic animation principle on a plain grey cube — and the cube visibly develops moods. No face. No costume. Just motion choices. That is the power you are here to learn.

## How to use this guide with an easily-derailed memory (a note of respect, not pity)

- **Pick lessons by appetite, not order.** Feeling like fire today? Go straight to Lesson 10. The lesson will hand you every definition it needs.
- **One drill = one sitting.** Decide which drill you'll do *before* you open the app. Opening the app without a decision is how sessions evaporate.
- **The cheat-sheets are the guide's short-term memory.** There is one companion checklist per lesson — fifteen in all, from timing to the game-engine pipeline — each sized for a phone screenshot or a printout. Print them or keep them on your phone. They exist so this book doesn't have to be re-read to be used.
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
- **Part VII — The Library**
  - Lesson 15: Annotated Bibliography (every link verified, free & legal)
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

## Sources for this lesson (all free & legal; details in Lesson 15)

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

## Sources for this lesson (all free & legal; details in Lesson 15)

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

## Sources for this lesson (all free & legal; details in Lesson 15)

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

## Sources for this lesson (all free & legal; details in Lesson 15)

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

## Sources for this lesson (all free & legal; details in Lesson 15)

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

How to animate things that fly — birds, superheroes, fairies, and stranger beings — by answering one question first: **what is holding this creature up?** Every flight style is an answer to that question, and every answer casts a different character.

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

## If you only keep three things

1. First decide **what holds them up** — wings (work), power (velocity), or magic (invented rules) — and let every drawing answer consistently.
2. Wings are arms: sweep from the shoulder, broad powerful downstroke, folded quick upstroke, feather-tips always last (drag and follow-through).
3. Hovering means drifting; landings reveal power by *who absorbs the impact* — the knees, or the ground and cape.

## Sources for this lesson (all free & legal; details in Lesson 15)

- Aaron Blaise, *Animation – The Mechanics of Bird Flight* (video): https://www.youtube.com/watch?v=2FR982O37dw
- Animation Mentor blog, *Tutorial: How to Animate Birds in Flight*: https://www.animationmentor.com/blog/tutorial-how-to-animate-birds-in-flight/
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

## Sources for this lesson (all free & legal; details in Lesson 15)

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

## Sources for this lesson (all free & legal; details in Lesson 15)

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

## Sources for this lesson (all free & legal; details in Lesson 15)

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

**How to time it:** generous and eased. The splash lifecycle: impact → a canopy rises (fast, wide spacing) → columns and droplets climb, slow at the top (bunched spacing — hang time!) → fall → rings ripple outward, late and soft, the last thing to settle. Follow-through everywhere: water keeps sloshing long after the cause has stopped.

**Its personalities:** playful fountain (bouncy timing, fat droplets) = joy. Slow rolling swell (long timing, deep eases) = calm, sorrow, vastness. Chopped stabbing spray (fast, jagged for water) = storm, rage.

**Mini-drill:** a droplet falls into a still pool: drop (stretch as it falls) → canopy splash (2–3 frames) → two or three droplets arc out and fall → expanding ripple rings settle. 10–12 drawings.

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

## Sources for this lesson (all free & legal; details in Lesson 15)

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

Clip Studio Paint comes in DEBUT, PRO, and EX grades. For animation the difference is blunt: **PRO and DEBUT are capped at 24 frames of animation** (per Celsys' own FAQ and manual — at 24 fps that's one second; at 8 fps, three seconds), while **EX has no frame limit**. You have EX, so every exercise in this guide — and full scenes — fit without workarounds. (EX also unlocks a couple of pro exports mentioned below.)

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

## Sources for this lesson (all official Celsys pages; details in Lesson 15)

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

ibisPaint's **Animation Function** arrived in **version 11.0.0 (September 2023)** — the official release note reads simply "Added Animation function," and the official description is charming and accurate: your illustrations are "shown continuously like a flip-book." It is frame-by-frame animation, the same craft as this whole guide, in your pocket. (Worth knowing: it's presented as a standard feature in the official docs — no separate paid unlock is documented for it.)

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

## Sources for this lesson (all official ibis inc. pages; details in Lesson 15)

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

## Sources for this lesson (all free & legal; details in Lesson 15)

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
5. Drawn crisp pixel art? Set the node's **CanvasItem > Texture > Filter** to **Nearest** (hard pixels), or set the project-wide default under Project Settings > Rendering > Textures > Default Texture Filter. High-resolution painterly frames can stay on the default (Linear = soft scaling).

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

## Sources for this lesson (all official docs or the addon's own repository; details in Lesson 15)

- Godot (verified on the 4.7 "stable" docs): *2D sprite animation* — https://docs.godotengine.org/en/stable/tutorials/2d/2d_sprite_animation.html — *AnimatedSprite2D* — https://docs.godotengine.org/en/stable/classes/class_animatedsprite2d.html — *SpriteFrames* — https://docs.godotengine.org/en/stable/classes/class_spriteframes.html — *Importing images* — https://docs.godotengine.org/en/stable/tutorials/assets_pipeline/importing_images.html
- KoBeWi, *Godot-Universal-Fade* (MIT): https://github.com/KoBeWi/Godot-Universal-Fade — Asset Library entry: https://godotengine.org/asset-library/asset/1454
- Unity (verified on the 6000.3 = Unity 6.3 LTS manual): *Cut out sprites (Sprite Editor)* — https://docs.unity3d.com/6000.3/Documentation/Manual/sprite/sprite-editor/use-editor.html — *Sprite import settings* — https://docs.unity3d.com/6000.3/Documentation/Manual/texture-type-sprite.html — *Create a new Animation Clip* — https://docs.unity3d.com/6000.3/Documentation/Manual/animeditor-CreatingANewAnimationClip.html — *Animator Controller* — https://docs.unity3d.com/6000.3/Documentation/Manual/class-AnimatorController.html — *Animation Parameters* — https://docs.unity3d.com/6000.3/Documentation/Manual/AnimationParameters.html — *Animation Events* — https://docs.unity3d.com/6000.3/Documentation/Manual/script-AnimationWindowEvent.html
- Unreal (verified on the current 5.8 docs; Paper 2D unchanged from 5.7): *Paper 2D overview* — https://dev.epicgames.com/documentation/en-us/unreal-engine/paper-2d-overview-in-unreal-engine — *Import & use sprites* — https://dev.epicgames.com/documentation/en-us/unreal-engine/how-to-import-and-use-paper-2d-sprites-in-unreal-engine — *Flipbooks* — https://dev.epicgames.com/documentation/en-us/unreal-engine/paper-2d-flipbooks-in-unreal-engine — *UPaperFlipbookComponent API* — https://dev.epicgames.com/documentation/en-us/unreal-engine/API/Plugins/Paper2D/UPaperFlipbookComponent
- Web: MDN, *drawImage* — https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/drawImage — MDN, *steps() easing function* — https://developer.mozilla.org/en-US/docs/Web/CSS/easing-function/steps

---

# PART VII — THE LIBRARY

---

# Lesson 15 — Annotated Bibliography (Every Link Verified, Free & Legal)

**How this list was built.** Every URL below was fetched and confirmed live on **16 August 2026**. Only free *and* clearly legal sources made the cut: creators' own channels and websites, companies' own free tutorials and documentation, Wikipedia, Khan Academy, and genuinely public-domain material on the Internet Archive. (A caution from the wild: convincing-looking but *fake* URLs for animation resources circulate widely — including in AI-generated lists. Nothing below is cited from memory; everything was checked.) YouTube and Vimeo videos are free to watch on the creators' own channels; "public domain" entries are free to download, keep, and study without restriction.

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

## Public-domain study shelf

- **Superman – The Complete Collection** (Fleischer, 1941–43) — https://archive.org/details/superman-the-complete-collection-fleischerfamous-studios — flight, capes, electricity, fire, water, staging.
- **Gertie the Dinosaur** (Winsor McCay, 1914) — https://archive.org/details/gertiethe-dinosaur-512kb — the origin of personality animation; weight and temperament with zero dialogue.
- **The Sunshine Makers** (Van Beuren, 1935) — https://archive.org/details/The_Sunshine_Makers_1935 — elegant vs scruffy movement dialects inside one film.
- **Advanced Animation** (Preston Blair, 1940s) — https://archive.org/details/advanced-animation-by-preston-blair — the classic instruction book, openly downloadable (PDF/EPUB); the archive labels it public domain (the 1940s edition's copyright is commonly cited as unrenewed — and note it's the *original* edition that's free, not the modern revised "Cartoon Animation").

## Practice

- **51 Great Animation Exercises to Master** — J.K. Riki, Animator Island — article — https://www.animatorisland.com/51-great-animation-exercises-to-master/ — The community's canonical drill list in four difficulty tiers, bouncing ball to full acting; this guide's Lesson 13 is designed to feed into it.

## The paid shelf (not free — listed for honesty, with legal access routes)

These four books are the craft's holy texts, and none is legally free online. As of this guide's check (16 Aug 2026), none had a borrowable controlled-lending copy on Open Library/Internet Archive either — so the honest free route is your **public library** (physical or via the Libby app); otherwise, used copies are plentiful.

- **The Animator's Survival Kit** — Richard Williams — *the* modern textbook of timing, spacing, and walks; Lesson 4 is heavily in its debt.
- **The Illusion of Life: Disney Animation** — Frank Thomas & Ollie Johnston — the source of the twelve principles, and the best-illustrated animation book ever printed.
- **Elemental Magic, Volume I** — Joseph Gilland — the classic on hand-drawn effects: fire, water, smoke, magic.
- **Cartoon Animation** — Preston Blair (modern Walter Foster edition) — the revised, in-print descendant of the free 1940s book above.

---

# Master Glossary (same wording as the lessons — that's the point)

- **anticipation** — a small preparatory move (often in the opposite direction) before the main action; the wind-up before the pitch.
- **arc** — the curved path almost every natural motion travels along.
- **animating "on ones" / "on twos"** — a new drawing every frame (24/sec) / each drawing held 2 frames (12/sec).
- **animation folder** (Clip Studio) — the container whose cels are treated as frames of one animated element.
- **boiling** — the lively shimmer when redrawn lines wobble slightly frame to frame; noise when accidental, texture when chosen.
- **breakdown** — the drawing between two keys that decides *how* the motion travels, not just where it ends.
- **cel** — one drawing in the animation stack (a layer, or folder of layers, in Clip Studio).
- **contrapposto** — the natural stance with weight on one leg, hips tilted one way, shoulders counter-tilted.
- **counter-rotation** — hips twist one way, shoulders twist the other; the body's balancing twist.
- **cycle** — a set of drawings that loops seamlessly; the last flows back into the first.
- **drag** — a trailing part lags behind because its base moved first.
- **flipbook** — Unreal's name for a playable stack of sprite frames; a good mental model for game animation everywhere.
- **flour sack** — the classic practice prop: a half-full sack animated as a character; all acting, no face.
- **follow-through** — loose parts (hair, cloth, tails, flesh) keep moving after the main body stops.
- **fps (frames per second)** — how many frames play each second.
- **frame** — one single image in an animation; film traditionally shows 24 per second.
- **inbetween** — a drawing that fills the gap between two key drawings.
- **key drawing** — one of the main storytelling drawings; the rest exist to connect the keys.
- **light table** (Clip Studio) — pins reference drawings faintly under your working cel, like a lit glass desk.
- **line of action** — the single imaginary curve running through a pose, giving it energy and direction.
- **onion skin** — a ghost view of the frames before/after the one you're drawing.
- **overlapping action** — different parts start and stop at slightly different times, never all at once.
- **overshoot and settle** — motion goes slightly past its target, then eases back into place.
- **pivot / origin** — the anchor point of a sprite (feet, center); keep it consistent across frames or the character jitters.
- **pose to pose / straight ahead** — plan key drawings first, then fill between / draw frame 1, 2, 3…, discovering as you go.
- **secondary action** — a smaller supporting action layered on the main one, adding character without stealing focus.
- **silhouette** — the solid-black outline shape of a pose; if the action reads in silhouette, it reads.
- **slow in and slow out** — bunching drawings at the start and end of a move so it eases in and out.
- **smear** — a deliberately stretched or multiplied drawing shown for a frame or two to sell extreme speed.
- **spacing** — how far the drawing moves between one frame and the next; the handwriting of motion.
- **sprite** — a 2D image a game engine can place, move, and draw on screen.
- **sprite sheet** (texture atlas) — many animation frames packed into one image in a grid, sliced apart by the engine.
- **squash and stretch** — a form flattening under force and lengthening with speed, volume constant.
- **staging** — presenting an action so it reads instantly: clear silhouette, clear framing, one idea at a time.
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

