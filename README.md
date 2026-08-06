# doit-content

The cards and Labs [doit](https://github.com/datapointchris/doit) reads.

- `workflows/` — reference cards: one tool's commands, or one procedure across several
- `labs/` — hands-on practice Labs, each with a cadence in its frontmatter

Cloned to `$XDG_DATA_HOME/doit/` on every machine, which is also where it is authored:
`doit workflows new`, `doit labs new` and `doit content edit` all write here.

It is a repo rather than a synced folder because it has to reach a machine outside
the Syncthing fleet, and `git clone` is the one channel that reaches all of them.

Content only — no code. Personal registers (`pursuits.yml`, `register.yml`,
`sources.yml`) are intentions rather than content and live in `$XDG_CONFIG_HOME/doit/`.
