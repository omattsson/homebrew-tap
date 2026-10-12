# homebrew-tap

Homebrew tap for [stackctl](https://github.com/omattsson/stackctl), the CLI for [k8s-stack-manager](https://github.com/omattsson/k8s-stack-manager).

## Install

```bash
brew install --cask omattsson/tap/stackctl
```

## Upgrade

```bash
brew upgrade --cask stackctl
```

## Moving from the old formula

stackctl was a formula up to version 0.3.1. It is a cask now (`Casks/stackctl.rb`, written by GoReleaser on each release). If you installed the old formula, change once:

```bash
brew uninstall --formula stackctl
brew install --cask omattsson/tap/stackctl
```
