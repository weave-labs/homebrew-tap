# WeaveLabs Tap

Homebrew tap for Weave Labs tools. Binaries are published publicly in the `weave-labs/release` repository (./release): https://github.com/weave-labs/release. This tap references those artifacts for install.

## How do I install these formulae?

`brew install weave-labs/tap/<formula>`

Or `brew tap weave-labs/tap` and then `brew install <formula>`.

Or, in a `brew bundle` `Brewfile`:

```ruby
tap "weave-labs/tap"
brew "<formula>"
```

## Artifact source

- Release artifacts (tarballs/zips, checksums) live in the public repo: https://github.com/weave-labs/release
- Each project/version is tagged (e.g., `weave-cli/v1.5.20`) and casks/formulae in this tap point to those assets.

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
