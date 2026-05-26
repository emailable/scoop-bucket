# Emailable Scoop Bucket

[Scoop](https://scoop.sh/) bucket for the [Emailable CLI](https://github.com/emailable/emailable-cli).

## Install

```powershell
scoop bucket add emailable https://github.com/emailable/scoop-bucket
scoop install emailable
```

## Update

```powershell
scoop update emailable
```

## How this bucket is maintained

The `bucket/emailable.json` manifest is generated and pushed automatically by
[GoReleaser](https://goreleaser.com/) on every release of
[emailable/emailable-cli](https://github.com/emailable/emailable-cli). Don't
edit it by hand — open issues and PRs on the CLI repo instead.
