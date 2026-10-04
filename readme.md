# Gitify downloads

This repository contains the packaged Gitify installers. The application source code is kept in a separate private repository.

## See Gitify in action

Gitify gives you a visual workspace for repositories, branches, commits, and connected hosting accounts.

### History

![Gitify history view](screenshots/gitify-history.png)

### Repository management

![Gitify repository management](screenshots/gitify-repository-management.png)

### Branch river

![Gitify branch river](screenshots/gitify-river.png)

## Download Gitify

Open the [Releases page](https://github.com/nwaoga/gitify-downloads/releases) and choose the newest release. Prereleases are marked clearly; use one only if you want the latest testing build.

### Windows

- Most Windows PCs: download the `x64.exe` installer.
- Portable Windows copy: download the `x64.zip` archive.

### macOS

Check your Mac’s processor in **Apple menu → About This Mac**:

- Apple silicon (M1, M2, M3, M4, or newer): download the `arm64.dmg` installer or `arm64.zip` archive.
- Intel Mac: download the `x64.dmg` installer or `x64.zip` archive.

The `.dmg` file is the normal macOS installation option. Use the `.zip` archive if you prefer to copy the app manually.

### Linux

- Intel/AMD 64-bit Linux: download the `x86_64.AppImage` or `amd64.deb` package.
- ARM64 Linux: download the `arm64.AppImage` or `arm64.deb` package.

Use the `.deb` package on Debian, Ubuntu, or another Debian-based distribution. Use the AppImage on distributions where you prefer a self-contained executable.

## Files you can ignore

You normally do not need to download files ending in `.blockmap` or `latest*.yml`. They are used by Gitify’s automatic update system. The `Source code` archives are repository metadata, not application installers.

## Help

For download or installation problems, [open an issue](https://github.com/nwaoga/gitify-downloads/issues) and include:

- your operating system and CPU architecture;
- the release version;
- the filename you downloaded; and
- the error message or a screenshot, without sharing private information.

Please do not post access tokens, private repository URLs, or other secrets in an issue.
