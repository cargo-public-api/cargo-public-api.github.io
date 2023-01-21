## Preview of auto-generated release notes
<!-- Release notes generated using configuration in .github/release.yml at main -->

## What's Changed
### Bugfixes
* Fix RUSTSEC-2023-0003 / CVE-2023-22742 "git2 does not verify SSH keys by default" by bumping libgit2-sys in Cargo.lock by @dependabot in https://github.com/Enselic/cargo-public-api/pull/300
### Other Changes
* Make `diff latest` diff highest semver version, not most recently published by @Enselic in https://github.com/Enselic/cargo-public-api/pull/296
* When diffing, build rustdoc JSON with `--cap-lints allow` by default by @Enselic in https://github.com/Enselic/cargo-public-api/pull/279
### `public-api` library
* Deprecate `PublicApi::from_rustdoc_json_str()` by @Enselic in https://github.com/Enselic/cargo-public-api/pull/295


**Full Changelog**: https://github.com/Enselic/cargo-public-api/compare/v0.27.0...main


(This page was updated **2023-01-21T06:47:45+00:00** by `pull_request_target` via [Preview-release-notes.yml](https://github.com/Enselic/cargo-public-api/actions/runs/3973701014))
