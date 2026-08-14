# Labor0 public releases

This repository contains public release assets for Labor0 products. Release families include the prebuilt `l0` command-line client with its matching `labor0-runner` runtime, plus official Envbox clients and the `envbox` CLI. Follow the asset-specific installation and verification guidance attached to each release.

Labor0 CLI archives contain `l0`, `labor0-runner`, the runner-managed skill bundle, and generated third-party notices. Their versions come from `vX.Y.Z` Git tags. Select the archive for your operating system and CPU architecture, verify it against the release's `labor0-cli_<tag>_SHA256SUMS` file, and keep the two executables and `.agents/runner-skills` together after extraction.

Published releases are immutable. A failed release is replaced by a new version; assets and tags are never overwritten or reused.

For the current installation path, see [Install the Labor0 CLI](https://docs.labor0.com/cli/install). For broader setup, recovery, and product guidance, see [Labor0 CLI documentation](https://docs.labor0.com/cli).

For safe support and issue-reporting guidance, see [SUPPORT.md](SUPPORT.md).
