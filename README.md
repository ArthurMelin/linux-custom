Arch Linux kernel package with some with some small customizations for my personal use.

This is the same as the Arch Linux core/linux package but:
* built with Clang/LLVM
* built with Clang's LTO (and force enabled Rust)
* uses a Git source instead of tarballs to allow incremental updates
* **disabled a bunch of drivers I don't need for my specific system**
