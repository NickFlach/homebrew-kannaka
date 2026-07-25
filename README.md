# homebrew-kannaka

Homebrew tap for [kannaka](https://github.com/NickFlach/kannaka-memory) — the
wave-interference (Holographic Resonance Medium) memory CLI for AI agents.

```sh
brew install nickflach/kannaka/kannaka
kannaka --version
```

Or in two steps:

```sh
brew tap nickflach/kannaka
brew install kannaka
```

The formula installs the prebuilt release binary for your platform (macOS
arm64/x86_64, Linux arm64/x86_64 — Linux builds are static musl) and Homebrew
verifies its sha256 against the digests pinned in the formula.

The formula is bumped automatically on each kannaka release by the
`publish-channels` workflow in the main repo.

## Other install channels

- npm: `npx kannaka` / `npm i -g kannaka`
- Docker: `docker run --rm ghcr.io/nickflach/kannaka --version`
- Direct: `curl -sSf https://install.ninja-portal.com/kannaka | sh`
