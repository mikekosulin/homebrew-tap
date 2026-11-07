# Homebrew tap of kanareika

[kanareika](https://github.com/mikekosulin/kanareika): agentless, read-only security audit of servers over SSH.

```bash
brew install mikekosulin/tap/kanareika
```

or `brew tap mikekosulin/tap`, then `brew install kanareika`. macOS and Linux (arm64, amd64); `brew upgrade` picks up
new releases.

`Formula/kanareika.rb` installs the release binary and is generated: `bin/formula.sh` writes it from a release's
`SHA256SUMS`, and `.github/workflows/update.yml` runs it for the latest release every six hours. Do not edit it by
hand. Problems with kanareika itself: [its issues](https://github.com/mikekosulin/kanareika/issues/new/choose).
