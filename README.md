# Ingrained client releases

Builds of the Ingrained client for macOS and Linux, with checksums.

Install:

    curl -fsSL https://ingrained.dev/install.sh | sh

Upgrade, with the client already installed:

    ingrained upgrade

Each release holds one build for each platform and a `SHA256SUMS` file. The install script and `ingrained upgrade` check a build against it before putting it in place.

More at https://ingrained.dev/install
