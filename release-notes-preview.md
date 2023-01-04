## Preview of auto-generated release notes
<!-- Release notes generated using configuration in .github/release.yml at main -->

## What's Changed
### New Features
* If `--simplifed` is passed twice, omit auto derived `impl`s (`Clone`, `Debug`, etc) by @Enselic in https://github.com/Enselic/cargo-public-api/pull/262
* Support `cargo public-api diff latest` by @Enselic in https://github.com/Enselic/cargo-public-api/pull/260
### Bugfixes
* Fix rendering of bounds for Generic Associated Types (GATs) by @Enselic in https://github.com/Enselic/cargo-public-api/pull/265
### Other Changes
* Remove deprecated `--diff` CLI by @Enselic in https://github.com/Enselic/cargo-public-api/pull/258
* Remove `diff crate-name@0.1.0` support, use `-p crate-name diff 0.1.0` instead by @Enselic in https://github.com/Enselic/cargo-public-api/pull/259
* Put auto derived `impl`s (`Clone`, `Debug`, etc) right after normal `impl`s by @Enselic in https://github.com/Enselic/cargo-public-api/pull/261
### Uncategorized
* Bump minimum nightly version to `nightly-2022-11-22` by @Enselic in https://github.com/Enselic/cargo-public-api/pull/212


**Full Changelog**: https://github.com/Enselic/cargo-public-api/compare/v0.25.0...main


(This page was updated **2023-01-04T10:34:20+00:00** by `push` via [Preview-release-notes.yml](https://github.com/Enselic/cargo-public-api/actions/runs/3837217513))
