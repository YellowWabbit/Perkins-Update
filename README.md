# Perkins updates

This public repository is the release channel for the Perkins desktop application. The application source and development files are in the separate private **Perkins** repository. Keep this repository limited to release information and downloadable application updates.

## Install an update

Perkins checks the latest published release here when it starts and every six hours while open. If a newer update is available for your operating system, choose **Update now** or **Later**. Update now downloads the package, verifies its SHA-256 digest and embedded file hashes, backs up the current application files, and installs the update. Restart Perkins afterward.

On Windows, a new `Perkins-X.Y.Z-windows-x64-setup.exe` can also be installed manually. Google Drive is used for the shared technical library; it is not an application update source.

## Release files

- `Perkins-X.Y.Z-linux-update.zip`: Linux update package for an existing Perkins installation.
- `Perkins-X.Y.Z-windows-x64-setup.exe`: Windows installer, including manual installation.
- `Perkins-X.Y.Z-windows-update.zip`: Optional Windows update ZIP.
- Matching `.sha256` files: checksums for independent verification.

The release tag must be `vX.Y.Z` or `X.Y.Z`. Attach the platform packages to a published GitHub Release. Perkins offers an update only when that release has a compatible asset with a SHA-256 digest. Release notes should describe user-visible changes.

This repository is public so installed copies of Perkins can check for updates without access to the private source repository.
