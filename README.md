# SpecScore Scoop Bucket

[Scoop](https://scoop.sh/) bucket for [SpecScore](https://specscore.md) CLIs.

## Install

```powershell
scoop bucket add specscore https://github.com/specscore/scoop-bucket
scoop install specscore
```

## What's in the bucket

| Manifest | Description | Source |
|---|---|---|
| `specscore` | SpecScore CLI — lint, validate, and navigate Markdown specifications | [`specscore/specscore-cli`](https://github.com/specscore/specscore-cli) |

## How updates work

Manifests are published automatically by [GoReleaser](https://goreleaser.com/) on each tagged release of the upstream CLI. Manual edits to `*.json` (root-level, e.g. `specscore.json`) will be overwritten on the next release.

## License

MIT — see [LICENSE](LICENSE).
