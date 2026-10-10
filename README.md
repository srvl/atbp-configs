# atbp-configs

A collection of already optimized configuration files for PaperMC, LeafMC, and Geyser.

## Release-based workflow

This repository is intended to be used as a release-oriented config archive:

- Stable config bundles can be published as GitHub Releases
- Each release can track a specific set of PaperMC, LeafMC, or Geyser configs
- The main branch should remain the source of truth for the latest maintained collection

## Contents

- PaperMC configs organized by Minecraft version under the paper/ directory
- LeafMC configs organized by Minecraft version under the leafmc/ directory
- Geyser configuration files (plugins/Geyser-Spigot/config.yml) with clone-remote-port off: on port-range nodes Bedrock gets its own port from the Bedrock range, set in Geyser's bedrock.port

This repository is intentionally focused on storing ready-to-use config bundles for each supported version.