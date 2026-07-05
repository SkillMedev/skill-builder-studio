# Skill Builder Studio

**For skill authors: take a Claude Agent Skill from blank file to A+, tested, and packed.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

The authoring loop for people who build Claude Agent Skills - the same toolchain Skill Me uses to hold its own catalog to a paid-quality bar. Reach for it when a skill needs to go from idea to shippable: draft a new one against the nine-part anatomy (procedure, elicitation, thresholds, worked artifact, deliverable, Do NOT, quality bar), audit an existing one to an absolute A+ with ship-ready rewrites, sharpen the description with the WHAT + WHEN + NOT trigger formula, prove the triggers fire with live subagent tests, and compose members into a pack with an install sequence and cross-links. End state is a skill (or pack) you can publish with confidence, not a to-do list.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/skill-builder-studio](https://skillme.dev/pack/skill-builder-studio) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add SkillMedev/skill-builder-studio`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[Skill Creator](skills/skill-creator/SKILL.md)** — Use when authoring a brand-new skill from scratch - turning a capability idea or a "make me a skill that…" request into a complete SKILL.md with a trigger-precise description and the full paid-quality anatomy: procedure, elicitation, thresholds, worked artifact, deliverable, Do NOT, quality bar.
- **[Skill Auditor](skills/skill-auditor/SKILL.md)** — Use when reviewing, grading, auditing, or improving a whole existing skill or pack - judging whether a skill is good, fixing one that misfires or won’t activate, or driving one or many skills to a quality bar.
- **[Skill Description Writer](skills/skill-description-writer/SKILL.md)** — Writes the description field that makes a skill fire reliably - WHAT it does, WHEN to invoke it with quoted user phrasing, and what it is NOT for.
- **[Skill Tester](skills/skill-tester/SKILL.md)** — Empirically tests a skill with subagent scenarios to verify it fires on the right prompts, stays silent on the wrong ones, and performs its job when loaded.
- **[Skill Pack Curator](skills/skill-pack-curator/SKILL.md)** — Designs the membership and structure of a skill pack - persona, member selection, install sequence, cross-links, and what to add or cut.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
