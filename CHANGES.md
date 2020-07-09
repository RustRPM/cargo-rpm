# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.7.0 (2019-11-30)

- Upgrade to Abscissa v0.4 ([#44])
- Get rpmbuild from `$PATH` rather than hardcoding ([#43])
- Remove the assumption that `service` -> `sbin` ([#42])
- Fix issues with custom release/target usage ([#41])

[#44]: https://github.com/RustRPM/cargo-rpm/pull/44
[#43]: https://github.com/RustRPM/cargo-rpm/pull/43
[#42]: https://github.com/RustRPM/cargo-rpm/pull/42
[#41]: https://github.com/RustRPM/cargo-rpm/pull/41

## 0.6.0 (2019-08-10)

- Use `cargo-release` alpha version numbers if available ([#31])

[#31]: https://github.com/RustRPM/cargo-rpm/pull/29

## 0.5.0 (2019-08-07)

- Migrate from `iq-cli` to Abscissa application framework ([#29])

[#29]: https://github.com/RustRPM/cargo-rpm/pull/29

## 0.4.0 (2019-03-15)

- Add support for crates using license-file ([#11], [#25])
- Support custom targets ([#12], [#24])
- Fix RPM version for languages other than English ([#18])

[#25]: https://github.com/RustRPM/cargo-rpm/pull/25
[#24]: https://github.com/RustRPM/cargo-rpm/pull/24
[#18]: https://github.com/RustRPM/cargo-rpm/pull/18
[#12]: https://github.com/RustRPM/cargo-rpm/pull/12
[#11]: https://github.com/RustRPM/cargo-rpm/pull/11

## 0.3.0 (2019-03-15)

- Upgrade to Rust 2018 edition ([#19])
- Require license to be set ([#9])

[#19]: https://github.com/RustRPM/cargo-rpm/pull/19
[#9]: https://github.com/RustRPM/cargo-rpm/pull/9

## 0.2.0 (2018-06-10)

- Respect `CARGO_TARGET_DIR` env var ([#1])

[#1]: https://github.com/RustRPM/cargo-rpm/pull/1

## 0.1.1 (2018-04-19)

- Move documentation into README.md.

## 0.1.0 (2018-04-19)

- Initial release
