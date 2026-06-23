# Skill Builder Studio

**For skill authors: take a Claude Agent Skill from blank file to A+, tested, and packed.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

The authoring loop for people who build Claude Agent Skills. Reach for it when a skill needs to go from idea to shippable: draft a new one from scratch, audit an existing one to an A+ bar, sharpen the description so it triggers reliably, prove the triggers fire with live tests, and assemble members into a pack that holds together. End state is a skill (or pack) you can publish with confidence, not a to-do list.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/skill-builder-studio](https://skillme.dev/pack/skill-builder-studio) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add aouellets/skill-builder-studio`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[Skill Creator](skills/skill-creator/SKILL.md)** — Use when authoring a brand-new skill from scratch — turning a repeated workflow, an existing prompt, or a "make me a skill that…" request into a well-formed SKILL.md with a trigger-precise description and an imperative, ordered body that meets the A+ bar.
- **[Skill Auditor](skills/skill-auditor/SKILL.md)** — Use when reviewing, grading, auditing, or improving a whole existing skill or pack — judging whether a skill is good, fixing one that misfires or won't activate, or driving one or many skills to a quality bar.
- **[Skill Description Writer](skills/skill-description-writer/SKILL.md)** — Writes discoverable skill descriptions (what + when, third person) that trigger reliably.
- **[Skill Tester](skills/skill-tester/SKILL.md)** — Empirically tests a skill with subagent scenarios to verify it triggers correctly and performs its job.
- **[Skill Pack Curator](skills/skill-pack-curator/SKILL.md)** — Composes a coherent pack of skills by resolving persona vs workflow conflicts and enforcing overlap limits.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
