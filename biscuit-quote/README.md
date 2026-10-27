# Macro crate for biscuit datalog

> This is `biscuit-quote-atestum`, a fork of biscuit-quote (source: https://github.com/atestum/biscuit-rust). It is based on upstream `main` at 93832a8, whose published version is 0.3.0 and whose CHANGELOG heads the unreleased 0.4.0. A version `0.3.0-rN` is fork release N on top of that. It is used through `biscuit-auth-atestum`; to depend on it directly, write `biscuit-quote = { package = "biscuit-quote-atestum", version = "0.3.0-r1" }` with the full version, since Semver treats `-rN` as a pre-release.

This crate provides datalog parsing macros for [`biscuit-auth`](https://crates.io/crates/biscuit-auth). It is
reexported by it, so it is not meant to be used directly. It is split in a separate crate in order to avoid a
dependency cycle.
