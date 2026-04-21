# Vicode Windows Releases

This repo is the public download and auto-update feed for the Vicode Windows beta.

It is for:

- Windows installer downloads
- desktop app updates for installed builds
- release notes and release assets

It is not the source-code repo.

## What To Download

For most testers, download the latest Windows installer from:

- [Releases](https://github.com/lowluds/vicode-windows-releases/releases)

Look for:

- `Vicode-Setup-<version>.exe`

## How To Install

1. Download the latest `Vicode-Setup-<version>.exe`.
2. Run the installer on Windows.
3. Launch Vicode.
4. Open a project folder and trust that workspace when prompted.

## How Updates Work

- Installed Windows builds check for updates on launch.
- Update status is also visible in `Settings > General`.
- When an update is ready, Vicode shows an update action in the titlebar.
- If a run is active, Vicode waits for that run to finish before restarting to install the update.

## Providers

Recommended first providers:

- `OpenAI / Codex CLI`
- `Gemini CLI`

Supported secondary lane:

- `Ollama`

Compatibility-only lanes:

- `Qwen`
- `Kimi`

## Source Code

If you want the public source snapshot, use:

- [lowluds/vicode-windows-public](https://github.com/lowluds/vicode-windows-public)

## Notes

- Public `npm install` is not the supported end-user install path right now.
- This repo is intentionally release-only so testers can install and update the Windows app without needing the internal working repo.
