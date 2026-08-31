# scoop-bucket

Scoop bucket for [spinup](https://github.com/DulsaraNethmin/spinup) — start local
development services (databases, queues, GUIs, dev tooling) with one command.

```powershell
scoop bucket add spinup https://github.com/DulsaraNethmin/scoop-bucket
scoop install spinup
spinup up postgres
```

`spinup.json` is generated and committed by
[GoReleaser](https://github.com/DulsaraNethmin/spinup/blob/main/.goreleaser.yaml)
on every tagged release. Don't edit it by hand — the next release overwrites it.
Issues belong on the [spinup repository](https://github.com/DulsaraNethmin/spinup/issues).
