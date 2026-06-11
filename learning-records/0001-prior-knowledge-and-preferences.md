# Starting point: dormant C/C++ background + concepts-first learner

Carsten is an experienced developer who wrote C and C++ ~20 years ago, so the stack/heap, pointer, and manual-memory mental model exists but is dormant. This is the key teaching lever: anchor Rust's ownership system directly to it (`malloc`/`free`, dangling pointers, use-after-free, double-free, RAII, `std::move`). He prefers to understand concepts thoroughly *before* practicing.

Mission is genuine Rust fluency, with **calling Rust from Python** as the proof-of-skill milestone; no specific project yet (toy examples for now).

**Implications for future sessions:**
- Start at **ownership**, not "hello world" — trivial syntax can be skimmed; the distinctly-Rust ideas deserve the time.
- Lead with the conceptual model, then a tight predict-then-verify practice loop.
- No toolchain installed → Rust Playground for early exercises; defer `rustup`/`cargo` and the messy `pip3`/venv cleanup until the first real crate and the Python phase.
- Borrowing (references) is the natural next lesson — Lesson 1 deliberately ends on a function-move error that only borrowing can fix.
