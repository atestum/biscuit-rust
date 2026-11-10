# `0.2.0-r2`

- Fork release based on upstream `main` at aa5a672, where this crate still declares 0.2.0. Its source differs from the published 0.2.0 (upstream moved to nom 8 without a version bump). The `0.3.0` entry below is upstream's and unreleased.
- Published as `biscuit-parser-atestum`; the library keeps the `biscuit_parser` import path.

# `0.3.0`

- Fix parsing of empty maps in facts (#355)

## Breaking changes

- Bump nom version in exported types
- Update macro codegen to follow biscuit-auth 7.0.0 changes 

# `0.2.0`

- [biscuit-datalog 3.3](https://www.biscuitsec.org/blog/biscuit-3-3/) support (#217 and #271)

# `0.1.1`

- Support chained method calls

# `0.1.0` 

- Initial release
