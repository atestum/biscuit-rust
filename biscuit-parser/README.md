# Parser crate for biscuit datalog

> This is `biscuit-parser-atestum`, a fork of biscuit-parser (source: https://github.com/atestum/biscuit-rust). It is based on upstream `main` at 93832a8, where this crate still declares 0.2.0. A version `0.2.0-rN` is fork release N on top of that. It is used through `biscuit-auth-atestum`; to depend on it directly, write `biscuit-parser = { package = "biscuit-parser-atestum", version = "0.2.0-r1" }` with the full version, since Semver treats `-rN` as a pre-release.

This crate provides datalog parsing support for [`biscuit-auth`](https://crates.io/crates/biscuit-auth). It is
reexported by it, so it is not meant to be used directly. It is split in a separate crate in order to avoid a
dependency cycle. 
