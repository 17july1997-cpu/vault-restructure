# vault-restructure

A Claude Code skill that normalizes a folder of unorganized files into a proper vault. Routes files, injects YAML frontmatter, creates the 6-file vault structure, writes a manifest + vault-index for `vault-sync` to consume.

Built as part of the three-skill vault architecture described in [this article](#).

## Install

Clone into your Claude Code skills folder:

    cd ~/.claude/skills
    git clone https://github.com/17july1997-cpu/vault-restructure.git

Then in Claude Code, type `/vault-restructure` to invoke it.

## How it works

See [SKILL.md](SKILL.md) for the full specification, and [references/](references/) for deep documentation on each phase of the routing logic.

## Related skills

- [vault-sync](https://github.com/17july1997-cpu/vault-sync) — durability filter + bonding pass at session end
- [vault-lint](https://github.com/17july1997-cpu/vault-lint) — read-only audit of vault drift

## License

MIT. Fork it, make it yours.
