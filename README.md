# avaluev/homebrew-tap

Homebrew formulae for [Chute](https://chutedev.com) — drop context into your agent.

```bash
brew install avaluev/tap/chute
```

That installs the `chute` command-line tool: 25 commands, MIT licensed, zero dependencies, and
free forever. It builds from source; no bottle, because the package has no dependencies to
compile against and the build takes seconds.

The **app** — the Finder right-click menu, the menu-bar session switcher and the ⌥⌘N hotkey — is
a separate, paid download with a 14-day trial: <https://chutedev.com>

## Updating the formula

```bash
curl -L https://github.com/avaluev/chute/archive/refs/tags/vX.Y.Z.tar.gz | shasum -a 256
```

Then bump `version` and `sha256` in `Formula/chute.rb` together. They are the only two lines that
change, and a mismatch between them is the only way this formula can break.
