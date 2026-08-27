# Stonetop GM Tools

Agent Skills for running a *Stonetop* tabletop RPG campaign, packaged as a
dual-format plugin readable by both [Kimi Code](https://moonshotai.github.io/kimi-code/)
and [Claude Code](https://docs.claude.com/en/docs/claude-code).

Each skill distills one area of GMing — player moves, GM moves, threats,
harm & healing, session prep — into two layers: quick at-the-table
mechanics, and distilled interpretation advice for running them well. None
of the skills reproduce the book's text at length; each links back to the
[stonetop-srd](https://github.com/karimn/stonetop-srd) repo, which carries
the full CC BY-SA 4.0 licensed text, for anything that needs the exact
wording.

## Skills

| Skill | Covers |
| --- | --- |
| `stonetop-player-moves` | Resolving player moves — triggers, roll ranges, effects |
| `stonetop-gm-moves` | The GM's agenda, principles, and moves — soft vs. hard, when to make one |
| `stonetop-threats` | Designing and running threats/fronts, impending dooms, grim portents |
| `stonetop-harm` | Harm, debilities, wounds, death & dying, healing |
| `stonetop-session-prep` | What to prep between sessions, building an adventure |

## Install

### Kimi Code

Add this repo's `skills/` directory to `extra_skill_dirs` in
`~/.kimi-code/config.toml`:

```toml
extra_skill_dirs = ["/path/to/stonetop-gm-tools/skills"]
```

Or install as a plugin from the TUI: `/plugins install <path-or-github-url>`
(Kimi Code reads the manifest at `kimi.plugin.json`).

### Claude Code

Run with the plugin directory attached:

```sh
claude --plugin-dir /path/to/stonetop-gm-tools
```

Claude Code reads the manifest at `.claude-plugin/plugin.json` and
auto-discovers skills under `skills/`.

## Licensing and attribution

*Stonetop* is written by Jeremy Strandberg and published by
[Lampblack & Brimstone](https://www.lampblackandbrimstone.com/), with art
by Lucie Arnoux. The book's text is released under
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/); this
repository's content is licensed the same way — see `LICENSE`.

Constraints this repo observes:

- **No artwork** from the book is reproduced here.
- **No campaign-specific or vault content** — this is a generic tool for
  running *any* Stonetop campaign, not notes for a particular one.
- Anything derived from the book text carries attribution back to Jeremy
  Strandberg / Lampblack & Brimstone, CC BY-SA 4.0.

You can purchase *Stonetop* (print or PDF) via
[Plus One Experience](https://ttrpg.link/stonetop).
