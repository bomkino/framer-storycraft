# Motion grammar

Treat motion as the visible part of an argument, not decoration added after layout.

## Contents

- Scene contracts and story states
- Budgets and ownership
- Scroll, sticky, and stacking
- Phone and reduced motion
- Media lifecycle and rejection rules

## Write a scene contract first

Record:

```text
CLAIM
EVIDENCE
WHY MOTION IS NECESSARY
SCROLL / TIME / POINTER OWNER
STICKY CONTAINING BLOCK
TRAVEL OWNER AND HEIGHT
START, FOCUS, END
RELEASE CONDITION
DOM AND LAYER ORDER
OVERFLOW AND STACKING CONTEXTS
INPUT ALTERNATIVES
PHONE RESULT
SHORT-LANDSCAPE RESULT
REDUCED-MOTION RESULT
STATIC FALLBACK
PERFORMANCE BUDGET
```

Remove the scene if movement does not improve understanding.

## Use the three-state story

1. **Arrive** — establish source, category, tension, or possibility.
2. **Take focus** — make one piece of evidence current.
3. **Resolve** — land in a stable grid, list, ledger, control, or linked result.

Reject an end state that merely proves cards moved around.

## Enforce a motion ceiling

For an ordinary page, allow at most:

- one long scrub;
- one direct-hand instrument;
- one ambient or repeating object;
- one dominant moving owner per viewport;
- one or two restrained text-reveal moments.

Separate peaks with calm reading. Keep pricing, forms, legal content, policy, FAQ
answers, and contact methods stable. Use no adjacent pinned scenes.

## Keep ownership singular

- Let native Framer own section geometry, sticky wrappers, ordinary entrances, layout
  transitions, and breakpoint composition.
- Let a code object own its internal mechanism and, when designed for it, its own
  progress measurement and mapping.
- Let smooth scrolling own feel, never scene state.
- Let a text-reveal tool render linked native text, never become the sole source.
- Never drive one object with two progress systems.

## Build native scroll first

1. Prove anchors, history, focus jumps, keyboard, touch, pin, release, and reverse
   scroll without enhancement.
2. Add one smooth-scroll instance only after native behaviour passes.
3. Repeat the complete scene and navigation tests.
4. Remove the enhancement if it breaks meaning or operation.

Treat optional enhancement as terminal:

- `ENABLED + PASS`, or
- `EXCLUDED/BLOCKED + native fallback PASS`.

Do not leave a release waiting indefinitely for polish.

## Make sticky geometry honest

A sticky scene needs:

- a known scroll owner;
- a parent taller than the sticky child;
- an explicit offset;
- an ancestor chain without accidental scroll containers;
- a visible release point;
- enough room for short windows;
- stable source order.

Do not assume `100vh` creates travel. Do not put `Overflow: Hidden`, transforms,
filters, blur, partial opacity, masks, blend modes, or accidental isolation on the
sticky owner chain. Clip the smallest media child when necessary.

When z-index appears ineffective, inspect the parent tree. A high child z-index cannot
escape a lower stacking context. Fix the tree instead of escalating numbers.

## Keep concealed layers non-interactive

Do not place links, buttons, inputs, or media controls behind an opaque reveal curtain.
If interaction is essential, abandon the native reveal or build and verify an
accessible implementation. Keep semantic DOM order intact.

## Recompose Phone

Convert continuous Desktop progress into:

- a complete still;
- a three- or four-state stepper;
- manual previous/next or swipe with visible controls;
- a natural-flow list;
- a short opacity/position entrance.

Prioritise vertical touch scrolling. Do not depend on hover. Treat short landscape as
a failure test rather than claiming an unsupported automatic height variant.

## Author reduced motion

- Begin with complete words, evidence, and actions.
- Remove translation, scale, looping, parallax, depth sweep, and autoplay where
  possible.
- Keep selection, focus, links, copy, and hierarchy.
- Use a complete still or restrained fade.
- Verify each third-party tool separately; do not assume Framer's setting governs it.

## Bound media and lifecycle

- Start with images and prove composition before video.
- Require a deliberate poster for every video.
- Use control-free silent inline video only when it is purely decorative, conveys no
  unique meaning, and satisfies reduced-motion and pause, stop, or hide requirements.
  Use a labelled player plus equivalent text, captions, or description as applicable
  for content-bearing video.
- Give playback to one materially visible active/focused item.
- Keep repeated rivers, clones, satellites, and buried cards as posters.
- Pause offscreen work and hidden tabs without catch-up jumps.
- Keep Canvas, export, error, rejected autoplay, and reduced states complete.

## Reject

- text waiting at opacity zero for a flourish;
- ambient movement behind an active scrub;
- timed loops added to scroll specialists;
- hover-only meaning;
- drag gestures that leak into clicks;
- motion that intercepts pointer or focus;
- endless animation frames while parked;
- global page scaling;
- animation used to hide weak hierarchy.
