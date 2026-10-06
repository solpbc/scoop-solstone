# scoop-solstone

a [Scoop](https://scoop.sh) bucket for the solstone app for windows.

## install

```powershell
scoop bucket add solstone https://github.com/solpbc/scoop-solstone
scoop install solstone
```

## what you get

the solstone app for windows takes in what you share with it from your screen, system audio, and any microphone you choose. it prepares local, owner-controlled segments for your journal. no telemetry.

the app reaches your journal directly or through a relay (by default link.solstone.app).

- homepage: <https://solstone.app>
- source: <https://github.com/solpbc/solstone-windows>
- license: AGPL-3.0-only

## updates

run this for new versions:

```powershell
scoop update solstone
```

your local segments live in `%LOCALAPPDATA%\Solstone` and are preserved across Scoop updates.
