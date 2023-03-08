# Changelog[^1]

All notable changes to Publish With Poetry will be documented here. Breaking changes are marked with a 🚩.

Publish With Poetry adheres to [semantic versioning](https://semver.org/spec/v2.0.0).

## <a name="2-0-3">[2.0.3] - 2023-03-08</a>

### Changed

- The `token` input now defaults to `${{ secrets.PYPI_TOKEN }}`.

## <a name="2-0-2">[2.0.2] - 2022-12-23</a>

No user-facing changes are introduced in this release.

## <a name="2-0-1">[2.0.1] - 2022-12-23</a>

No user-facing changes are introduced in this release.

## <a name="2-0-0">[2.0.0] - 2022-12-13</a>

### Removed

- 🚩 The `dependencies` and `extras` inputs have been removed.

### Fixed

- Fixed a bug where Poetry would not install when the `poetry-version` input was provided and an existing Poetry
  installation was found in `$PATH`.

## <a name="1-0-1">[1.0.1] - 2022-12-20</a>

No user-facing changes are introduced in this release.

## <a name="1-0-0">[1.0.0] - 2022-12-20</a>

This is the initial release of Publish With Poetry.

[^1]: Based on [Keep a Changelog](https://keepachangelog.com).