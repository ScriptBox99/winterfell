# Changelog

## 0.3.0 (2022-01-04)
* Added `f64` field.
* Added support for cubic field extensions.
* Added an implementation of Rescue Prime hash function in `f64` field.
* Switched to Rust 2021 and increased min version of `rustc` to 1.57.
* [BREAKING] Renamed `Air::BaseElement` to `Air::BaseField`.
* [BREAKING] Replaced `prover::prove()` function with `Prover` trait.
* [BREAKING] Split `ExecutionTrace` struct into `Trace` trait and `TraceTable` struct.

## 0.2.0 (2021-08-23)
* Added `Blake3_192` as hash function option.
* Implemented high-performance version of Rescue Prime hash function.
* Removed `alloc` feature in favor of turning on `no_std` via `--no-default-features` flag only.
* Moved `rand` dependency to `dev-dependencies` only and removed `hashbrown` dependency.
* Increased min version of `rustc` to 1.54.

## 0.1.0 (2021-08-03)
* Initial release