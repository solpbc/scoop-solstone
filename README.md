# scoop-solstone

A [Scoop](https://scoop.sh) bucket for **solstone** — an open-source, privacy-respecting way to collect and gain insight from your own personal data.

## Install

```powershell
scoop bucket add solstone https://github.com/solpbc/scoop-solstone
scoop install solstone
```

## What you get

The **solstone Windows observer**: a per-user, non-elevated, tray-resident app that gathers screen and system audio (plus the microphone when present) into local, owner-controlled segments for your journal. No analytics, telemetry, or tracking; nothing phones home.

- Homepage: <https://solstone.app>
- Source: <https://github.com/solpbc/solstone-windows>
- License: AGPL-3.0-only

## Updates

This is a portable install, so scoop owns updates (solstone's built-in self-updater is inert here):

```powershell
scoop update solstone
```

Your journal data lives in `%LOCALAPPDATA%\Solstone` and is preserved across updates.
