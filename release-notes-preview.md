## Preview of auto-generated release notes
<!-- Release notes generated using configuration in .github/release.yml at main -->

## What's Changed
### New Features
* Allow `stdout` and `stderr` of rustdoc JSON building to be captured with new `rustdoc_json::Builder::build_with_captured_output(self, stdout: impl Write, stderr: impl Write)` function by @orium in https://github.com/Enselic/cargo-public-api/pull/574
### Bugfixes
* Allow `--package`, `--color` etc also after subcommands such as `diff` by @Enselic in https://github.com/Enselic/cargo-public-api/pull/569
* Match `cargo`'s handling of spaces with `--features` by @Enselic in https://github.com/Enselic/cargo-public-api/pull/580

## New Contributors
* @orium made their first contribution in https://github.com/Enselic/cargo-public-api/pull/574

**Full Changelog**: https://github.com/Enselic/cargo-public-api/compare/v0.34.1...main


(This page was updated **2024-05-26T19:06:03+00:00** by `pull_request_target` via [Preview-release-notes.yml](https://github.com/Enselic/cargo-public-api/actions/runs/9245554515))
