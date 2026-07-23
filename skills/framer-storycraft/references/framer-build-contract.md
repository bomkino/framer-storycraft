# Framer build contract

Use this contract for project structure, responsive systems, components, CMS, and
agent-assisted changes.

## Contents

- Protection, inventory, and authority
- Blueprint and Story Lab
- Ownership and responsive foundations
- Native/code component contracts
- CMS, semantics, and agent mutations

## Protect and inventory

For an existing project:

1. Identify the exact project, version or branch, routes, styles, components, CMS,
   assets, integrations, redirects, collaborators, and publish target.
2. Create or confirm a protected duplicate/version and rollback point.
3. Begin with a read-only mismatch report.
4. Preserve unrelated work.
5. Treat `noindex` as discoverability guidance, never privacy.

For a new project, record source truth, scope, and the release boundary before
multiplying pages.

## Keep authority explicit

Use these separate axes for Standard and Cinematic work:

| Axis | Question |
|---|---|
| Readiness | Is the specimen building, under review, approved, blocked, or deprecated? |
| Placement intent | Is it production, conditional, reserve, or lab? |
| Test result | Did the observed test pass, fail, remain blocked, or not apply? |
| Route policy | Is the route core, conditional, gated, or held? |
| Release decision | Is this exact candidate including, excluding, or leaving the route undecided? |

Never infer approval from a passing test, production intent from approval, or release
inclusion from route policy.

## Separate the mould surfaces

Use a private Blueprint or Design Page for:

- linked colour and text roles;
- spacing, wrappers, grids, full-bleed recipes, and responsive compositions;
- attached native component masters and variants;
- complete, long, short, empty, missing-media, and error states;
- CMS specimens, media rooms, code-object specimens, semantics, and evidence labels.

Use a protected runtime Story Lab only when Preview behaviour must be proved:

- sticky containment, pin, release, and reverse scroll;
- anchors, history, keyboard and focus jumps;
- stacking and reveal behaviour;
- specialist code-object drivers;
- smooth-scroll or text-reveal integration;
- Phone, short-landscape, and reduced-motion results.

Keep runtime lab pages out of the production candidate.

## Assign ownership

| Layer | Owns |
|---|---|
| Native Framer | Page structure, ordinary layout, copy, CMS, headings, navigation, forms, breakpoints, sticky wrappers, semantics, and fallbacks |
| Code component | One named difficult visual or gestural instrument |
| Smooth-scroll tool | Scroll feel only |
| Text-reveal tool | Effect rendering from linked native text, never wording truth |
| Human/owner | Claims, taste, crop, choreography, identity, policy, approval, and publish |

Allow an agent to compose when explicitly requested, but require review of the first
composition or golden page before broad reuse.

## Build responsive foundations

- Use controls exposed by the current Framer Canvas; verify capabilities that may have
  changed.
- Keep the page shell uncapped and in ordinary vertical flow.
- Put max width and horizontal padding on section inner wrappers, not Main or the
  content slot.
- Let atmosphere extend full bleed while copy and useful objects remain capped.
- Prefer flow layout. Reserve absolute positioning for deliberate overlays and stage
  objects.
- Use `Overflow: Visible` through sticky ancestor chains. Clip only the smallest
  necessary media or decorative frame.
- Change layout, gaps, type, crop, and information order across breakpoints. Never
  scale a whole component to make it responsive.
- Base component internals on measured component width and height, not browser width.

Use 1200/810/390, a 1440 px wrapper, and 64/32/20 px side padding only as a useful
house starting point. Adapt them to the project.

## Give every reusable component a contract

Record:

1. purpose;
2. named anatomy;
3. editable variables and optional children;
4. Fill/Fit/fixed sizing, min/max, and aspect rules;
5. necessary states only;
6. explicit Desktop/Tablet/Phone variants when internal geometry or type changes;
7. theme/surface behaviour;
8. semantic element, accessible name, and focus behaviour;
9. motion owner and reduced state;
10. shortest, longest, missing, keyboard, touch, overflow, and zoom tests.

Use variables for content and variants for meaningful structural/state changes. Avoid
combinatorial variant soup. Keep instances attached to their masters.

Merge two components only when they share semantic job, DOM topology, driver,
interaction/accessibility contract, lifecycle/terminal states, and differ only through
tokens. Fail one condition: keep them separate.

## Constrain code components

- Preserve a deliberate Canvas/static pose.
- Use one clock or progress owner.
- Use component measurement for geometry.
- Keep browser APIs inside guarded effects or event paths.
- Avoid state updates per animation frame, `transition: all`, random first renders,
  and permanent idle loops.
- Clean up observers, listeners, animation frames, timers, portals, object URLs, and
  media sources on every exit path.
- Preserve Framer's outer `style` prop and accurate layout annotations.
- Keep essential copy and accessible navigation outside the code object.
- Migrate one real instance at a time and retain rollback.

## Keep CMS and semantics native

- Use native CMS as the indexable and accessible content spine.
- Keep uncertain or private records Draft; hiding an element is not security.
- Import in dependency order and map by stable ID or slug.
- Preview create/update/skip counts before a bulk change; never imply deletion.
- Hide absent optional sections cleanly instead of inventing outcomes or proof.
- Use one Main and one visible H1 per content page.
- Separate visual text style from heading rank.
- Make links navigate and buttons change state.
- Give drag/swipe interfaces a keyboard or button alternative.
- Use visible form labels and associated errors.
- If a disclosure cannot prove correct keyboard/state semantics, show its content open.

## Structure agent mutations

For every change, state:

```text
SOURCE · TARGET · OPERATION · BOUNDARY · GATES · EVIDENCE · STOP · PUBLISH
```

Follow:

```text
READ → REPORT → MAP → APPROVAL GATE → APPLY SMALL BATCH → EVIDENCE → REVIEW
```

Stop on missing or contradictory sources, mismatched live structure, blocked
specimens, destructive ambiguity, private-content exposure, inaccessible fallback,
unsupported tool behaviour, or unclear publish authority.
