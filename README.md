# Tiny Mini OS

An absolutely minimal Operational System made in Rust.

As seen on Rust in Action, Chapter 11.

## Dependencies

- Install [QEMU](https://qemu.org)
- Rust extras

```bash
$ cargo install cargo-binutils
$ cargo install bootimage
$ rustup toolchain nightly
$ rustup default nightly
$ rustup component add rust-src
$ rustup component add llvm-tools-preview
```
