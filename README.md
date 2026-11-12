# modeling-languages-releases

Public releases of **Modeling Languages** from NovoCircle: one guide for each of 19 modeling languages, and one shared layout standard for sizes and spacing. The guides describe the languages, not any diagramming tool, so any tool's skills can read them.

## What this repository holds

Only released plugin trees, under `plugins/modeling-languages/`, each tagged `modeling-languages--v<version>`. Each GitHub release has its notes and attaches `modeling-languages.plugin`. The plugin folder holds `CHANGELOG.md`, the license and the notices. Source code is private.

## Install

In Claude Code:

```
claude plugin marketplace add NovoCircle/ai-power-tools-releases
claude plugin install modeling-languages@novocircle
```

To update later:

```
claude plugin marketplace update novocircle
claude plugin update modeling-languages@novocircle
```

For Claude Desktop chat or Claude Cowork, upload `modeling-languages.plugin` from a release. An uploaded plugin doesn't update itself: upload the new file to take a later release.

## License

MIT. See [LICENSE](LICENSE).

## Copyright and trademarks

Each language is defined by a standard published by its owner, who holds the copyright in it. These guides are NovoCircle's own descriptions of the languages. They don't reproduce the standards, and where a guide takes specific content from another source, it names that source. The owner's standard is authoritative: where a guide and the standard differ, follow the standard.

NovoCircle is a trademark of SFI Ventures, LLC. The MIT License grants no rights in that name. The trademarks of the languages' owners and others that the guides name are listed in `NOTICE.md` in the plugin folder. Other names are trademarks of their respective owners. NovoCircle is not affiliated with or endorsed by any of these organizations.
