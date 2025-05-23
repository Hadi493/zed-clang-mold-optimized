# Zed Editor - Native Linux Build 🇧🇩🐧

A blazing fast, native-optimized build of the [Zed Code Editor](https://github.com/Hadi493/zed), compiled from source using:

- `clang` + `mold` linker
- `target-cpu=native`
- `opt-level=3`, `lto=thin`, `panic=abort`
- Supports `.rpm` and `.deb` packaging (via `fpm`)

## 🚀 Why?

The official Zed binary may not be optimized for your CPU. This build is faster, smaller, and tailored for your machine.

