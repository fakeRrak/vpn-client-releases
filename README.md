# Codex VPN Client — Releases

This repository hosts **release binaries only**. Source code lives at https://github.com/fakeRrak/vpn-client.

## Installing

Grab the latest installer from the [Releases](https://github.com/fakeRrak/vpn-client-releases/releases/latest) page:

- `Codex-VPN-Client-Setup-<version>.exe` — NSIS installer (recommended).

## Auto-update

The application checks this repository on startup. When a new release is published, it downloads in the background and installs silently on the next opportunity. No user prompt — silent install + auto-restart.

## Verifying

Every release ships with `latest.yml` containing SHA-512 of the installer. `electron-updater` verifies the hash before launching the installer.