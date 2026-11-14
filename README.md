# Hypizel releases

Downloadable releases for **Hypizel**, a Fabric client mod for Hypixel SkyBlock, and its optional addons.

## Install

1. Use Minecraft **26.1.2**, Java **25**, Fabric Loader **0.20.1+**, and Fabric API for 26.1.2.
2. Download the main **Hypizel core JAR** (`hypizel-VERSION.jar`) from the [latest release](https://github.com/Ceaserr/Hypizel-Releases/releases/latest), place it in your instance's `mods` folder, and remove older core copies.
3. Launch Minecraft and open **H → Addons** or **/hypizel addons**.
4. Install **Economy** and/or **Mining**. Close Minecraft when the download is verified, wait for installation to finish, then relaunch.

The core is preconfigured to use this repository. Starting with core **0.2.3**, **H → Addons → Hypizel (Core) → Update** also updates the main mod after Minecraft closes. Existing 0.2.2 users need one manual upgrade to the latest core to enable this feature. Addons can also be installed manually from release assets. Do not install the JSON catalog as a mod.

Core **0.2.5** checks for compatible installed core/addon updates once when Minecraft launches and shows a native notification if any are available. **Click that notification to open Addons directly**, then choose the update to download. The hub also displays **Download** buttons for published addons; unreleased addons stay **Coming soon**. Checks fetch only the catalog, and downloads require a click. Launch checks and notifications can be switched off separately in **Hypizel → Settings**. Update from 0.2.3 or newer using the in-game core **Update** button, then close and relaunch Minecraft.

## Addons

- **Hypizel (Economy):** Bazaar and auction research, flips, budget, watches, alerts and in-game market navigation. Requires the local Hypizel dashboard.
- **Hypizel (Mining) 0.6.1:** sack-aware sessions, Bazaar/NPC estimates, powder and ore widgets, forge planning, the `/mf` fortune guide and Pickobulus. **Mining → Forge calculator** immediately shows the full raw-material gathering list, combining nested recipes and previous drills. The recipe tree and saved material checks remain available. The calculator works offline; price-based estimates use the local dashboard.

The manager checks Minecraft and dependency compatibility, exact file size, SHA-256 and mod identity before staging a download. It applies queued installs after the game exits and retains the previous core/addon JAR outside `mods` when updating. Core updates check whether installed addons support the new version. Existing configuration and session files are preserved.

This repository distributes release files. It does not contain the dashboard source or player data.
