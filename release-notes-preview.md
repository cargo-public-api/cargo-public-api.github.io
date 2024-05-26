## Preview of auto-generated release notes
<!-- Release notes generated using configuration in .github/release.yml at main -->

## What's Changed
### New Features
* Allow `stdout` and `stderr` of rustdoc JSON building to be captured with new `rustdoc_json::Builder::build_with_captured_output(self, stdout: impl Write, stderr: impl Write)` function by @orium in https://github.com/Enselic/cargo-public-api/pull/574
### Bugfixes
* Make most CLI options global so they also work as subcommand args (e.g. `cargo public-api diff --package=...`) by @Enselic in https://github.com/Enselic/cargo-public-api/pull/569
* Match `cargo`'s handling of spaces with `--features` by @Enselic in https://github.com/Enselic/cargo-public-api/pull/580

## New Contributors
* @orium made their first contribution in https://github.com/Enselic/cargo-public-api/pull/574

**Full Changelog**: https://github.com/Enselic/cargo-public-api/compare/v0.34.1...main


(This page was updated **2024-05-26T19:15:32+00:00** by `push` via [Preview-release-notes.yml](https://github.com/Enselic/cargo-public-api/actions/runs/9245617143))
