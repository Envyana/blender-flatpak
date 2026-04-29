# blender-flatpak

Custom Blender Flatpak distribution — versions and updates are controlled by the admin.

## Overview
This repository contains a custom Flatpak distribution of **Blender**.
Unlike upstream releases, the Blender version and update cadence in this build are **explicitly managed by the repository administrator**.

## What this repo is for
- Publishing a controlled Blender Flatpak build
- Managing which Blender versions are made available
- Keeping updates predictable for users relying on a fixed toolchain

## Versioning & updates
- Versions are selected and updated by the admin.
- If you need a specific Blender version, open a request (and include the exact version).

## Install (example)
> Replace identifiers/commands below with the ones used by this project once finalized.

- If distributed via a Flatpak remote:
  - Add the remote
  - Install the app
  - Run Blender

## Build (for maintainers)
Typical Flatpak workflow:
1. Ensure Flatpak + flatpak-builder are installed
2. Build using the Flatpak manifest in this repository
3. Test the resulting build locally
4. Publish to the chosen distribution channel (remote / CI)

## Repository structure
- Flatpak manifest(s): (add path here)
- Patches / customizations: (add path here)
- CI / release automation: (add path here)

## Contributing
Issues and pull requests are welcome. Please include:
- Your OS + Flatpak version
- Logs / error output
- Steps to reproduce (if reporting a bug)

## License
Add license information here (or link to the LICENSE file).