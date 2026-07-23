# QA, release, and rollback

Separate system integrity, mould proof, runtime proof, route quality, and production
release. Passing one layer does not imply the next.

## Contents

- Severity and proportional evidence
- Responsive, component, route, and accessibility QA
- Motion and performance QA
- Candidate sanitisation
- Publish, verification, and rollback

## Classify defects

| Severity | Meaning | Release rule |
|---|---|---|
| P0 | Privacy/security loss, destructive action, unusable core journey | Zero |
| P1 | Broken route/action, major accessibility failure, scroll trap, false material claim | Zero |
| P2 | Substantive responsive, performance, state, copy, or visual defect | Resolve or record explicit owner deferral |
| P3 | Polish without material loss | Record and prioritise |

## Scale evidence to the mode

### Lean

- goal and truth ledger;
- one golden-page capture at Phone, Tablet, and Desktop;
- keyboard, touch, reduced-motion, form/action, and route check;
- clean release candidate and rollback point.

### Standard

- Blueprint captures at reference widths;
- attached component/state inventory;
- CMS complete, long, empty, missing, Draft, and error states;
- golden route-family proof;
- core journeys, browser pass, and release ledger.

### Cinematic

- all Standard evidence;
- one folder/record per runtime scene;
- native versus enhanced scroll comparison;
- ancestor/stacking map;
- code-object property and media snapshots;
- decoder/RAF observation;
- short-landscape, Safari/iOS, and low-power evidence;
- final evidence manifest.

Screenshots do not prove semantics, keyboard, CMS state, focus, lifecycle, or motion.
Name the branch/URL, date, browser/device, viewport, specimen, result, and defect in
each evidence record.

## Test responsive composition

Use project breakpoints plus these useful house stresses where appropriate:

- 320 and 390 Phone;
- 810 Tablet;
- 1200 and 1440 Desktop;
- 1920 wide;
- 3840 ultrawide;
- approximately 900 × 420 short landscape;
- 200% zoom or large-text stress.

Pass only when there is no unintended horizontal page scroll, clipped meaning,
orphaned control, hover-only truth, microscopic target, full-bleed seam, or absurd
uncapped object.

## Test every reusable component

- shortest, longest, missing optional, empty, one item, maximum items;
- duplicate labels/sources and reordered active inputs;
- mixed portrait, square, landscape, and ultrawide media;
- missing/broken image, video, and poster;
- Fill/Fit, parent resizing, and mid-interaction resize;
- light/dark surfaces and real contrast;
- pointer, keyboard, touch, drag/click separation, Escape, and focus return;
- Canvas/static pose, reduced motion, hidden tab, offscreen return, and cleanup;
- Safari and Chromium;
- private published/staging URL, not only Canvas.

Keep a designed honest empty state. Reject broken-media icons and arbitrary frozen
animation frames.

## Test routes and journeys

For every included route, verify:

- correct route or custom 404;
- title, description, canonical, social image, and robots decision;
- one Main, one visible H1, and logical headings;
- correct navigation/current state;
- no dead link, private/Draft leak, unresolved release blocker, or false claim;
- appropriate alt/caption decisions;
- usable contextual action and footer;
- deliberate ultrawide composition.

Complete the site's real journeys, not a generic checklist. Include navigation,
discovery/filtering, detail pages, conversion or contact, forms and recovery,
disclosures, mobile menu, direct URLs, Back, reload, anchors, and 404 recovery as
applicable.

## Test accessibility

- Complete core journeys by keyboard.
- Verify skip link, landmarks, heading order, names, states, descriptions, and live
  messages in the rendered accessibility tree.
- Keep focus visible and unobscured by sticky/fixed/reveal layers.
- Lock mobile-menu or dialog focus only while open; close with Escape and restore
  focus to the opener.
- Give drag/swipe a non-drag alternative.
- Keep forms visibly labelled with associated errors and recovery.
- Check actual rendered contrast, 200% zoom, 320 reflow, and touch without hover.
- Keep reduced-motion content complete.
- Verify a pause, stop, or hide mechanism for non-essential moving content that
  starts automatically and lasts more than five seconds.
- Use WCAG 2.2 AA as the baseline.

## Test motion and performance

Record for each moving scene:

- owner and driver;
- start, focus, end, interruption, reverse, and release;
- Phone/static/reduced result;
- Lenis or enhancement on/off result;
- focus, selection, pointer pass-through, and layout shift;
- offscreen pause and decoder/RAF observation;
- console result and real browser/device.

Keep hero/LCP media modest. Use posters for repeated objects. Remove third-party
duplication, offscreen decoders, runaway loops, and gratuitous blur/filter work. Keep
the page usable when optional enhancement fails.

## Sanitize the release candidate

Treat the candidate as a whole project version:

1. Record every route's independent release decision.
2. Require `INCLUDE + PRESENT + PASS`.
3. Require `EXCLUDE + ABSENT + verified direct-URL/404 result`.
4. Stop on `UNDECIDED`, unexplained routes, private lab pages, hidden routable pages,
   or sitemap/navigation mismatch.
5. Re-run routes, navigation, sitemap, direct URLs, 404, placeholders, and core
   journeys against this exact candidate.

## Publish and verify

- Require explicit publish authority.
- Preserve the pre-release version and rollback instructions.
- Publish the already-reviewed candidate without unrelated edits.
- Recheck production routes, actions, CMS, forms, analytics/consent where applicable,
  performance, and console.
- Record production version, URL, time, reviewer, and rollback path.

Use precise completion language:

- “Mould approved” means the system passed.
- “Staging passed” means real journeys passed.
- “Published” means the explicit production action happened.
- “Production verified” means the live version was rechecked.
