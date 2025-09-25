<div align="center">

# `tosca-stack`

[![Actions][actions badge]][actions]
[![Codecov][codecov badge]][codecov]
[![LICENSE][license badge]][license]

</div>

> [!CAUTION]
> `tosca-stack` is in a very early, experimental stage of development.
The APIs are still unstable and subject to change.
Be aware that even a minor version may introduce API breakages.
A major version will be released only when the APIs remain stable and
unchanged for an extended period.
This approach aims to provide clearer and more precise APIs, shaped by user
feedback and suggestions during the initial stages of the project

This crate is a variant of the
[tosca](https://github.com/ToscaLabs/tosca/tree/master/crates/tosca) library
designed specifically for stack-oriented devices. It performs no heap
allocations and relies exclusively on stack-allocated data structures.

## Building

To build using the `debug` profile, run:

```console
cargo build
```

To build with the `release` profile, which enables all time and memory
optimizations, run:

```console
cargo build --release
```

## License

Licensed under

- [MIT License](LICENSE-MIT)

## Contribution

Contributions are welcome via pull request.
The [Rust Code of Conduct](https://www.rust-lang.org/policies/code-of-conduct) 
applies.

Unless explicitly stated otherwise, all contributions will be licensed under
the project defined license, without any additional terms or conditions.

<!-- Links -->
[actions]: https://github.com/ToscaLabs/tosca-stack/actions
[codecov]: https://codecov.io/gh/ToscaLabs/tosca-stack
[license]: https://github.com/ToscaLabs/tosca-stack/blob/master/LICENSE-MIT

<!-- Badges -->
[actions badge]: https://github.com/ToscaLabs/tosca-stack/workflows/ci/badge.svg
[codecov badge]: https://codecov.io/gh/ToscaLabs/tosca-stack/branch/master/graph/badge.svg
[license badge]: https://img.shields.io/badge/license-MIT-blue.svg
