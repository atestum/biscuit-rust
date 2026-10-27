# `0.4.0-r1`

- Fork release based on upstream `main` at 93832a8, whose `0.4.0` entry below is unreleased upstream. Its source differs from the published 0.3.0.
- Published as `biscuit-quote-atestum`; the library keeps the `biscuit_quote` import path.
- The `biscuit-auth` 7.0.0 that the `0.4.0` entry below requires is this fork's `biscuit-auth-atestum` 6.0.0-r1.

# `0.4.0`

- macro parameters are set through `set_lenient` and `set_scope_lenient` instead of the dedicated
  `set_macro_param` and `set_macro_scope_param` methods, which are removed. This requires
  `biscuit-auth` 7.0.0.

# `0.3.0`

- [biscuit-datalog 3.3](https://www.biscuitsec.org/blog/biscuit-3-3/) support (#217 and #271)

# `0.2.1`

- support for a `rule` macro

# `0.2.0`

- support for `biscuit`, `block`, `authorizer` macros
- support for `biscuit_merge`, `block_merge`, `authorizer_merge` macros
- support for referencing in-scope variables in macro invocations
- support for a `rule` macro
