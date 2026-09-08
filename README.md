# Framer Storycraft

Design, build, revise, audit, debug, or release original Framer websites with
pitch.dog’s story-first, native-first method.

The skill makes visitor understanding, proof, accessibility, responsive
composition, motion ownership, rollback, and publication authority part of the
build—not an afterthought. It derives each project’s visual language from that
project instead of cloning pitch.dog’s surface style.

## Install

[Open the install page](https://skills.sh/bomkino/framer-storycraft/framer-storycraft),
or use the Skills CLI:

```bash
npx skills add https://github.com/bomkino/framer-storycraft --skill framer-storycraft -a codex -y
```

Install globally for compatible local agents:

```bash
npx skills add https://github.com/bomkino/framer-storycraft --skill framer-storycraft -g -a codex -y
```

For ChatGPT, download the ZIP and `SHA256SUMS` from the
[latest release](https://github.com/bomkino/framer-storycraft/releases/latest),
then open **Plugins → Skills → Create → Upload from your computer**. Review the
scan and confirm the skill is available in the client you intend to use.
Availability, installation, and syncing vary by product, surface, and workspace
settings. See [OpenAI’s Skills guide](https://help.openai.com/en/articles/20001066).

## Use

Invoke it directly:

```text
$framer-storycraft Audit this Framer site before publication.
$framer-storycraft Turn this brief into a page narrative and component mould.
$framer-storycraft Debug this sticky scene and design its reduced-motion result.
```

The skill may also activate implicitly when the host supports implicit
invocation and the request clearly concerns Framer website work. Existing
authorization covers the same action, target, and scope; a missing permission
blocks only the operation that depends on it. Publication still needs explicit
authority and result readback.

## What is included

```text
skills/framer-storycraft/
├── SKILL.md
├── LICENSE
├── agents/openai.yaml
└── references/
    ├── framer-build-contract.md
    ├── house-method.md
    ├── motion-grammar.md
    ├── qa-release.md
    └── source-map.md
```

The public package contains a portable method, not private project files,
client material, purchased components, or a literal pitch.dog design system.

## License

MIT. See [LICENSE](LICENSE).
