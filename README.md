# pleme-asref-derive

Newtype AsRef: impl AsRef<Inner> for Wrapper. Lets callers pass a wrapper where the inner type is expected.

[![Build](https://github.com/pleme-io/pleme-asref-derive/actions/workflows/auto-release.yml/badge.svg)](#)
[![crates.io](https://img.shields.io/crates/v/pleme-asref-derive.svg)](https://crates.io/crates/pleme-asref-derive)

## Install

```toml
[dependencies]
pleme-asref-derive = "*"
```

## Generation

This crate is mechanically emitted by [`tatara-rust-ast`](https://github.com/pleme-io/tatara-rust-ast). The author surface is a typed `(defmacro …)` Spec — the proc-macro implementation, tests, Nix flake, caixa wrapper, and CI workflow are all generated. See the catalog at `catalog.json` in the parent registry.
