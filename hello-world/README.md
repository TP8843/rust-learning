# Hello World

## rustc

To compile a `.rs` file, run:

```
rustc main.rs
```

This creates an executable file of the Rust program.

## Cargo

- `cargo new` creates a new Rust project
  - Creates a Git repo, unless already inside a Git repo
  - Contains `Cargo.toml` and `src/main.rs` files
- `cargo build` creates a debug build inside `target/debug`
  - Use `--release` to create a release build inside `target/release`
- `cargo run` creates a debug build and runs it
- `cargo check` checks a project will compile without actually creating a build
