# Mission: Learn Rust — and call it from Python

## Why
Carsten wants **genuine Rust fluency** — to actually *think* in Rust, not transliterate from another language. Calling Rust from Python is the concrete proof-of-skill milestone: a Rust core that Python can `import` and use means ownership, the type system, and the build/packaging story have all genuinely clicked.

## Success looks like
- Read and write idiomatic Rust comfortably: ownership & borrowing, enums & pattern matching, `Result`-based error handling, traits, and generics.
- Build and test a small Rust crate with `cargo`.
- Expose Rust functions and types to Python with **PyO3**, build a wheel with **maturin**, and `import` it from Python 3.11.
- Be able to *explain why* the Rust↔Python boundary is both safe and fast (ownership across the FFI boundary; releasing the GIL for real parallelism).

## Constraints
- Experienced developer; wrote C/C++ ~20 years ago — the stack/heap, pointer, and manual-memory mental model is dormant but recoverable. **Move fast on syntax; anchor new ideas to that background.**
- Learning style: **concepts first, thoroughly, then practice.**
- No Rust toolchain installed yet → early lessons use the **Rust Playground** (zero install). Local `rustup` setup is deferred until we need `cargo` (real crates / the Python phase). Python 3.11 is present.
- No specific project yet — toy examples for now; a real one may arrive later.

## Out of scope (for now)
- `async`/await, declarative & procedural macros, `unsafe` internals, embedded / `no_std` — until the fundamentals and a working Python binding exist.
- Application domains off the interop path (web frameworks, game engines, CLIs-for-their-own-sake).
