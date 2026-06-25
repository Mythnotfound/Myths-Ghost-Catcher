# 👻 MythsGhostCatcher

A client-side Minecraft mod integrity scanner for crystal PvP servers.

## What it does
- Scans `.jar` mod files entirely in your browser — nothing is uploaded anywhere
- Checks jar hashes against the Modrinth API to verify mods are unmodified
- Detects version tampering (modified jars, fake versions, unknown mods)
- Runs heuristic analysis on bytecode for cheat patterns (aimbot, crystal aura, macros, ESP, etc.)
- Gives an obfuscation grade per mod

## How to use
1. Open the site
2. Open your Minecraft instance's `mods` folder
3. Select all `.jar` files (`Ctrl+A`) and drag them onto the scanner
4. Review results — flagged mods are red, suspicious are yellow, clean are green
5. Export a `.txt` report if needed

## Live site
https://[your-username].github.io/mythsghostcatcher

## Tech
Pure HTML/JS, no backend, no server, no data collection. Modrinth API calls go from the user's browser directly.
