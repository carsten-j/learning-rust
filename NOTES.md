# Teaching Notes

## How Carsten learns
- **Concepts first, thoroughly, then practice.** Lead every lesson with the mental model before any exercise.
- **Anchor to C/C++ (~20 yrs ago).** Stack/heap, pointers, `malloc`/`free`, dangling pointers, double-free, RAII, `std::move`/`unique_ptr` are all fair analogies — he'll get them. The model is dormant, not gone; a one-line refresher is enough.
- Experienced dev: **don't dwell on trivial syntax** or basic programming concepts. Move briskly; spend the time on what's *distinctly Rust*.

## Cadence & format
- Lessons that work: **predict-then-verify** — state a concept, show a snippet, have him predict whether it compiles, then run it to get immediate feedback.
- Keep each lesson to ONE idea with a tangible win.

## Toolchain state (as of 2026-06-08)
- **No Rust installed** (`rustc`/`cargo`/`rustup` all absent). Early lessons use the **Rust Playground** — one-click "Run" buttons in the HTML pre-fill it via `?code=`.
- Defer `rustup` install until we need `cargo` (first real crate / the Python phase).
- Python 3.11.10 present. ⚠️ `pip3` resolves to a 3.9 CommandLineTools framework — **set up a clean venv** before doing anything with maturin, to avoid version confusion.
- macOS; `open <file>` works for launching lesson HTML.

## Keep in view
- Mission milestone is **calling Rust from Python**. Tie lessons back to "why this matters for the Rust↔Python boundary" so the abstract fundamentals stay grounded.

## Opening lessons
- `open lessons/0001-ownership-and-moves.html` (and increment for later lessons).
