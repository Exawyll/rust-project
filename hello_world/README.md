# hello_world

A minimal Rust binary project generated with Cargo.

## Requirements

- [Rust toolchain](https://rustup.rs/) (rustc + cargo)

## Project structure

```
hello_world/
├── Cargo.toml   # package manifest
└── src/
    └── main.rs  # entry point
```

## Usage

```bash
# Build and run
cargo run

# Build only
cargo build

# Build in release mode
cargo build --release

# Run the release binary directly
./target/release/hello_world

# Or build and run in release mode in one step
cargo run --release
```

The program prints:

```
Hello, World!
```
