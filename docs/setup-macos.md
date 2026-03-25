# Installation Rust sur macOS

Ce guide installe la chaine d'outils Rust (rustc, cargo) via rustup sur macOS.

## Prerequis

- macOS (Intel ou Apple Silicon)
- Xcode Command Line Tools

```sh
xcode-select --install
```

## Installation via rustup

```sh
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Rechargez votre shell (ou sourcez le fichier d'environnement) :

```sh
source "$HOME/.cargo/env"
```

## Verification

```sh
rustc --version
cargo --version
```
