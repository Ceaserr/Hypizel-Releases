# Hypizel releases

Downloadable releases for **Hypizel**, a Fabric client mod for Hypixel SkyBlock, and its optional addons.

## Install

1. Use Minecraft **26.1.2**, Java **25**, Fabric Loader **0.20.1+**, and Fabric API for 26.1.2.
2. Download the main **hypizel-0.2.2.jar** from the [latest release](https://github.com/Ceaserr/Hypizel-Releases/releases/latest), place it in your instance's `mods` folder, and remove older core copies.
3. Launch Minecraft and open **H → Addons** or **/hypizel addons**.
4. Install **Economy** and/or **Mining**. Close Minecraft when the download is verified, wait for installation to finish, then relaunch.

The core is preconfigured to use this repository. Addons can also be installed manually from release assets. Do not install the JSON catalog as a mod. Core upgrades remain manual in this version.

## Addons

- **Hypizel (Economy):** Bazaar and auction research, flips, budget, watches, alerts and in-game market navigation. Requires the local Hypizel dashboard.
- **Hypizel (Mining):** sack-aware mining sessions, Bazaar/NPC estimates, powder and ore widgets, forge planning, the `/mf` fortune guide and Pickobulus preview/cooldown widget. Price-based estimates use the local dashboard; mining capture and Pickobulus features work independently.

The addon manager checks Minecraft and dependency compatibility, exact file size, SHA-256 and mod identity before staging a download. It applies queued installs after the game exits and retains the previous addon JAR outside `mods` when updating. Existing configuration and session files are preserved.

This repository distributes release files. It does not contain the dashboard source or player data.
