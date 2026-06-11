# Rust (for Python interop) — Resources

Curated, high-trust sources. Knowledge for lessons is drawn from here, not from parametric guesses.

## Knowledge

- [The Rust Programming Language ("the book")](https://doc.rust-lang.org/book/)
  The official, authoritative text. Use for: every core concept. Ch.4 ownership & borrowing, Ch.6 enums & `match`, Ch.9 error handling, Ch.10 traits & generics.
- [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
  Runnable, annotated snippets. Use for: "show me the syntax for X" and seeing concepts in motion.
- [Standard library docs](https://doc.rust-lang.org/std/)
  Use for: `String`, `Vec`, `Option`, `Result`, and which types implement `Copy`/`Clone`.
- [The Rust Reference](https://doc.rust-lang.org/reference/)
  Precise language semantics. Use for: deep "what *exactly* does this mean" questions.
- [Rust Playground](https://play.rust-lang.org/)
  Browser-based compiler + runner, no install. Use for: every early exercise (our lessons link straight into it).
- [Rustlings](https://github.com/rust-lang/rustlings)
  Small, compiler-driven exercises. Use for: hands-on drilling once the local toolchain is installed.
- [PyO3 User Guide](https://pyo3.rs/)
  Rust↔Python bindings. Use for: the interop milestone — exposing functions/classes, converting types, the GIL.
- [maturin](https://www.maturin.rs/)
  Builds & publishes Rust↔Python wheels. Use for: building the binding and `import`ing it from Python.

## Wisdom (Communities)

- [The Rust Users Forum](https://users.rust-lang.org/)
  Official, beginner-friendly, high-signal. Use for: "is this idiomatic?" and design feedback.
- [r/rust](https://www.reddit.com/r/rust/)
  Ecosystem news and Q&A. Use for: crate recommendations, what's current.
- [Rust community hub](https://www.rust-lang.org/community)
  Gateway to the official Discord/Zulip chat. Use for: real-time help when stuck.

_Community preference: not yet discussed with Carsten. Surface these when we hit a genuine "wisdom" question (idiomatic-style judgement, design tradeoffs)._

## Gaps

- PyO3 / maturin move fast. When we reach the interop phase, **fetch fresh** getting-started steps and confirm current versions rather than relying on these annotations.
