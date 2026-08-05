# NimbusNexus Homebrew tap

```bash
brew install nimbusnexus/tap/nn-webhooks
```

`nn-webhooks` is the CLI for [NimbusNexus Webhooks](https://github.com/NimbusNexus/Webhooks-sdks).

## About this repo

Homebrew requires a third-party formula repo to be named `homebrew-<name>` and strips the prefix
when you reference it — which is why `NimbusNexus/homebrew-tap` is written as `nimbusnexus/tap`.

**Nothing here is edited by hand.** GoReleaser generates and commits each cask on release, from
`.goreleaser.yaml` in the Webhooks-sdks repo. Editing a file in `Casks/` would be overwritten by
the next release, and would drift from the checksums of the published archives in the meantime.

A tap rather than homebrew-core: core has notability requirements a new product SDK does not meet,
and going through their review on every release is not a release process.
