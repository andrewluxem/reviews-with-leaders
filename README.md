# reviews-with-leaders

Prepares a concise leadership review brief with decision asks, evidence, and follow-through.

It produces:

- **Leadership Review Brief:** a working artifact built from supplied facts, labeled inference, and visible missing fields.

It executes the [Reviews with Leaders playbook](https://www.andrewluxem.com/playbooks/reviews-with-leaders). The playbook teaches the framework. This skill runs it and returns a working artifact.

**Static by construction: no dependencies, executable code, telemetry, network calls, remote instructions, auto-update, scheduled work, or background behavior.** It reads only the files in its own skill folder. Nothing happens until a user or agent invokes it.

## Install

Clone and copy the skill into Claude Code:

```bash
git clone https://github.com/andrewluxem/reviews-with-leaders.git
cp -r reviews-with-leaders/skills/reviews-with-leaders ~/.claude/skills/
```

For Codex, copy the same complete folder to the Codex skills directory:

```bash
cp -r reviews-with-leaders/skills/reviews-with-leaders ~/.codex/skills/
```

Or install it as a Claude Code plugin:

```text
/plugin marketplace add andrewluxem/reviews-with-leaders
/plugin install reviews-with-leaders@reviews-with-leaders
```

For clients that install from an archive, use the versioned [reviews-with-leaders v1.0.0 ZIP](https://www.andrewluxem.com/downloads/reviews-with-leaders-v1.0.0.zip).

## Invoke it

```text
Prepare this leadership review brief and decision asks
Use the reviews-with-leaders skill.
```

Naming the skill is always valid: `use the reviews-with-leaders skill`.

## Files

```text
.claude-plugin/
  plugin.json
  marketplace.json
skills/reviews-with-leaders/
  assets/leadership-review-brief-template.md
  LICENSE.md
  meta.yaml
  references/leadership-review-standard.md
  SKILL.md
README.md
LICENSE
```

The complete canonical package is copied under `skills/reviews-with-leaders/`, including every asset, reference, test prompt, source note, changelog entry, and license file present in the source.

## Versioning

Plugin installation is version-pinned. When behavior changes, update the version consistently in `SKILL.md`, `meta.yaml`, `.claude-plugin/plugin.json`, and `.claude-plugin/marketplace.json`, then add a changelog entry. Reinstalling is an explicit update; this repository never auto-updates itself.

## License

MIT. See [LICENSE](LICENSE). The canonical skill folder carries the same authorization in [skills/reviews-with-leaders/LICENSE.md](skills/reviews-with-leaders/LICENSE.md).

---

## More playbooks

This skill packages one playbook from the free library at [github.com/andrewluxem/playbooks](https://github.com/andrewluxem/playbooks). Every playbook is free to read, with no email required.