<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Hihaheho/tauto/main/assets/logo-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Hihaheho/tauto/main/assets/logo.svg">
  <img alt="Tauto" src="https://raw.githubusercontent.com/Hihaheho/tauto/main/assets/logo.svg" height="100px">
</picture>

### A minimal language for AI to build and prove correct software

**[Tauto compiler and source code → Hihaheho/tauto](https://github.com/Hihaheho/tauto)**

Tauto is a small formal language in which an AI writes the program and its
proof, and a human reads and verifies the propositions. Machines check the
proofs; people decide whether the propositions express what they need.

The language brings together dependent types, algebraic effects and handlers,
and ownership and borrowing. Nib is the part without dependent types and proofs.
Grammars and macros extend the syntax, with expansions checked again by the
kernel. Programs can compile to Rust or JavaScript, and to WebAssembly through
the Rust backend.

This organization is home to libraries and tools for the Tauto ecosystem.
A Tauto package is called a **tote**.

- [Landing page](https://tauto.run)
- [Learn](https://learn.tauto.run)
- [Playground](https://try.tauto.run)
- [Blog](https://blog.tauto.run)
- [Compiler, CLI, standard library and examples](https://github.com/Hihaheho/tauto)
- [Language design](https://github.com/Hihaheho/tauto/tree/main/docs/design)
- [日本語の紹介](https://github.com/Hihaheho/tauto/blob/main/README.ja.md)

Tauto is experimental. The language and command-line interface may change;
see the compiler repository for the current capabilities and limitations.
