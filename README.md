# terminal-library

A curated body of terminal knowledge, authored by hand.

- `workflows/` — reference cards: one tool's commands, or one procedure across several
- `labs/` — hands-on practice Labs, each with a cadence in its frontmatter

"Terminal" rather than "CLI" because most of what is here is not a binary: tmux bindings,
shell functions, aliases, forgit shortcuts. "Library" because it is curated and written,
not accumulated — which is the line that keeps caches, exports and `{name: date}` state
files out of it.

[doit](https://github.com/datapointchris/doit) is one reader of it, not its owner. It
clones this to `$XDG_DATA_HOME/terminal-library/` on every machine, which is also where
it is authored: `doit workflows new`, `doit labs new` and `doit content edit` all write
here.

It is a repo rather than a synced folder because it has to reach a machine outside
the Syncthing fleet, and `git clone` is the one channel that reaches all of them.

No code. Personal registers (`pursuits.yml`, `register.yml`, `sources.yml`) are
intentions rather than knowledge and live in `$XDG_CONFIG_HOME/doit/`.
