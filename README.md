# DISTRO Core GitHub Workflows

This repository supplies workflows used by GitHub Actions; the
specific configuration for a single MACHINE is referenced. The
variable for MACHINE is set in the repo vars context.

### [Actions wsl-amd64](https://github.com/distro-core/workflows-wsl-amd64/actions)

[![GitHub Hosted Build](https://github.com/distro-core/workflows-wsl-amd64/actions/workflows/distro-core-build-github-hosted.yml/badge.svg)](https://github.com/distro-core/workflows-wsl-amd64/actions/workflows/distro-core-build-github-hosted.yml)
[![GitHub Hosted Fetch](https://github.com/distro-core/workflows-wsl-amd64/actions/workflows/distro-core-fetch-github-hosted.yml/badge.svg)](https://github.com/distro-core/workflows-wsl-amd64/actions/workflows/distro-core-fetch-github-hosted.yml)
[![Self Hosted Build](https://github.com/distro-core/workflows-wsl-amd64/actions/workflows/distro-core-build-self-hosted.yml/badge.svg)](https://github.com/distro-core/workflows-wsl-amd/actions/workflows/distro-core-build-self-hosted.yml)
[![Self Hosted Fetch](https://github.com/distro-core/workflows-wsl-amd64/actions/workflows/distro-core-fetch-self-hosted.yml/badge.svg)](https://github.com/distro-core/workflows-wsl-amd64/actions/workflows/distro-core-fetch-self-hosted.yml)

## LICENSE Information

Copyright (c) 2025 brainhoard.com

For all original content supplied with this layer, unless otherwise
specified, is licensed as [LICENSE](./LICENSE).

Editorial discretion is asserted on specific inclusion of layers that
may referenced. All upstream packages and their source code come with
their respective licenses. Individual packages license terms are to be
respected.

## CI/CD GitHub Actions

The path .github/workflows/ contains reusable GitHub Actions reusable
workflows that facilitate per MACHINE repositories to build and manage
artifacts from the common source scripting.
