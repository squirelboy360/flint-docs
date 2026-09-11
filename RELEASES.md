# Flint release policy

Flint releases are published from the private source repository and announced here so users have one public download channel.

## Tagging

Use semantic version tags in the form `v1.0.0`. Pre-release builds use a suffix such as `-beta.1`.

## Every release should include

- macOS, Windows, and Linux artifacts when that platform build is ready
- a short list of user-visible changes
- migration notes for settings or token-metering changes
- a SHA-256 checksum for each downloadable artifact
- the source commit used to build the release

This repository contains documentation and release metadata. Do not commit credentials, bearer tokens, session keys, or private source code here.
