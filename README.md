# DeepLink Homebrew Formulae

Homebrew formulae for DeepLink projects. This repository contains package metadata;
pVisor binaries are downloaded from the [pVisor releases](https://github.com/DeepLink-org/pvisor/releases).

## Install pVisor

```sh
brew tap DeepLink-org/formula https://github.com/DeepLink-org/Formula.git
brew install DeepLink-org/formula/pvisor
```

The explicit URL is required because this repository is named `Formula`, rather
than `homebrew-formula`. Supported platforms are Apple Silicon macOS and Linux
x86_64. See the [pVisor installation guide](https://deeplink-org.github.io/pvisor/en/start/installation/)
for platform prerequisites.

## Update

```sh
brew update
brew upgrade DeepLink-org/formula/pvisor
```

## Maintaining the formula

`Formula/pvisor.rb` is generated and tested by pVisor's release pipeline. Copy
updates from the release's `pvisor.rb` asset and verify it against the accompanying
`SHA256SUMS`; do not edit archive checksums by hand. The initial formula installs
pVisor 0.3.1. Automatic publishing to this repository must be configured in the
pVisor repository separately.

## License

[Apache License 2.0](LICENSE). See [NOTICE](NOTICE) for attributions.
