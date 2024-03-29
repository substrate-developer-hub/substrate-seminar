# Demystifying FRAME Macro Magic

* ⚡️ Intermediate
* 👤 Presenter: Sam (FRAME core developer at Parity)
* 📆 Date scheduled: November 22, 2022

📺 Watch the full recording on [YouTube](https://www.youtube.com/watch?v=aEWbZxNCH0A).
👉 View the slides [here](https://docs.google.com/presentation/d/1o_2U3mJfCjIQ_YxxHPS2Ok9O2o-1Tlho9CG80FaC_Nw/edit?usp=sharing).

### Description

In this seminar, we are joined by Parity core FRAME developer, Sam who's been working some key FRAME macro features (see [#12536](https://github.com/paritytech/substrate/pull/12536) and [#12536](https://github.com/paritytech/substrate/pull/12536)). He  will be explaining the high level of how the FRAME pallet macro parsing and expansion works through the lens of implementing a simple pallet macro.

### Topic

FRAME macros

### Plan

1. A brief overview of what pallet macros are and where they are used.
2. A quick description of the `whitelist_storage` macro, what it is supposed to do, and why it should exist.
3. A general discussion about the "outer macro" pattern.
4. Going through the steps of implementing the `whitelist_storage` macro as a way of explaining how pallet macros are parsed and expanded.
5. (time permitting) How pallet macros are tested.

### Links and resources

- [FRAME Macros - Substrate docs](https://docs.substrate.io/reference/frame-macros/) and [Rust Docs](https://paritytech.github.io/substrate/master/frame_support/attr.pallet.html)
- [`cargo expand`](https://github.com/dtolnay/cargo-expand)
- [Macros - The Rust Reference](https://doc.rust-lang.org/reference/procedural-macros.html)
- [Macros - The Rust Book](https://doc.rust-lang.org/book/ch19-06-macros.html)
- [AST (Abstract Syntax Tree) - Wikipedia](https://en.wikipedia.org/wiki/Abstract_syntax_tree)
