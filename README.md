# tak848/homebrew-tap

A personal [Homebrew](https://brew.sh) tap for [tak848](https://github.com/tak848)'s CLI tools.

Works on **macOS** and **Linux** (Homebrew on Linux).

## Install

One-shot:

```sh
brew install tak848/tap/<formula>
```

Or tap first, then install:

```sh
brew tap tak848/tap
brew install <formula>
```

## Formulae

| Formula | Upstream | Description |
| ------- | -------- | ----------- |
| `ccgate` | <https://github.com/tak848/ccgate> | A `PermissionRequest` hook for AI coding tools that delegates tool-execution permission decisions to an LLM. |

Each formula is generated and pushed to this tap automatically by the upstream project's [GoReleaser](https://goreleaser.com/) workflow on every release tag, so the `Formula/*.rb` files here are not edited by hand.

## License

[MIT](LICENSE)
