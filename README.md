# HeroAntiCheat

Anti-cheat plugin source for Paper/Purpur 1.21.11. Built for Java 21+.

## Build automatically on GitHub

1. Create a GitHub repository named `HeroAntiCheat`.
2. Upload the **contents** of this project folder (the `pom.xml`, `src/`, and `.github/` folder) to the repository root.
3. Open **Actions** and select **Build HeroAntiCheat**. It also runs automatically after a push.
4. Open the successful workflow run and download the artifact named `HeroAntiCheat-1.0.0`.
5. Extract the artifact ZIP and copy `hero-anticheat-1.0.0.jar` into the server's `plugins/` folder, then restart.

## Command

- `/heroac reload` — reload configuration.
- Permission: `heroac.admin` (default: operators).
- Bypass permission: `heroac.bypass`.

## Important safety note

Anti-cheat detections are heuristics and may produce false positives. Test on a staging server first and keep automatic punishments conservative. Freecam and aim-assist cannot be reliably proven from ordinary server-side events. For timed bans, install and configure LiteBans or AdvancedBan. Without either plugin, this plugin kicks rather than silently issuing a permanent ban.
