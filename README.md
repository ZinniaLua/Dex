# Dex - The Freedom Explorer

![Logo](/logo.png)

[![Discord](https://img.shields.io/badge/Community-Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/zinnia)

## Intro
New Dex was originally designed as a debugging suite but was discontinued in mid-2021 when true **grand freedom** was attained. The script was then repurposed to align with the agency’s greater mission.

> **Experience the most powerful explorer ever created. Unlocking boundless freedom and uncovering unseen territories.**

This is the **final version** of the script, meaning no further updates will be made. Certain high-level functionalities remain private and will not be released. You are free to edit, fork, and modify this as you wish, but support will be minimal, and pull requests are unlikely to be accepted.

If you choose to work on it, keeping the original credits would be greatly appreciated, as significant effort went into its development.

The script has been converted from a **ModuleScript** (previously developed in Studio) to a file format for easier modifications. Build instructions are available below. A pre-built version is also provided in the releases for convenience.

## Notes
- **No built-in cloneref protection** – add it yourself if needed.
- **Detection risks** – It may be flagged by certain systems; no fixes will be provided.
- **Optimization potential** – Certain elements (e.g., explorer node add/remove) can be refined.
- **Future Roblox updates** – Some features might break when deferred events are fully implemented (e.g., selecting a duplicated instance).

## To Build
1. Ensure you have **Python 3** installed (**tested on 3.9.0**).
2. Run `build.py`.
3. The script will be compiled as `out.lua`.

## High-Level Roadmap
Below is a list of planned features that were never completed. If you decide to continue developing New Dex, these additions would help make it the ultimate tool it was meant to be. Some details may be missing since development ceased a while ago.

### Terminal
- A command-driven interface for executing useful (non-troll) functions.
- Commands structured within dedicated tables for better organization.

### Debugging Interface
- More than just a **remote spy**.
- Ability to **hook** any metamethod, function, property, event, or callback.
- Log arguments/returns, much like a remote spy.
- **Real-time hook editing** via the script editor (argument spoofing, return spoofing, unhooking, etc.).
- Scripted filters for better debugging.
- **Save/load** hook configurations.
- A default setup mimicking a standard remote spy.

### Explorer Enhancements
- **Smart autofill** for searches.
- Additional **search filters**.
- **Bookmark/star instances** for quick access.
- Expand right-click menu options with more utility.

### Property Viewer
- **Copy property values** to clipboard (raw text or formatted for Lua).
- Select object properties directly in Explorer.
- **Tag Editor** – Potentially as a separate UI element.

### Data Viewing & Finding
- Constant, upvalue, and reference searching.
- **Reference Explorer** for userdata, tables, and functions (allowing deep reference tracing with tabs for exploration).
- **Detailed function view** – inspect environment, constants, upvalues, decompiled source, script path, and references.
- Quick creation of **constant signatures**.
- **Thread exploration tools**.

### Script Viewer/Editor
- Autocomplete functionality.
- Status bar with **error lines, line count, column positions, etc.**

### Reference & Documentation
- **Interactive API documentation** for instance properties, methods, and events.
- Documentation on built-in elements like `Dex` global, plugin API, executor API, etc.
- Guides/tutorials with text, images, and potentially videos (if Roblox lifts the 3-video limit).

### Plugin System
- Simple methods for adding new right-click options, commands, and search filters.
- Full access to Dex’s **internal API** for extending its capabilities.

## Missing Features from Old Dex
Some core features from **Old Dex** were never re-implemented. If you plan to continue development, these should be a priority:
- **Click-to-select** functionality.
- **Instance & full-map saving** (context menu for individual instances, full-save menu for entire maps).
- **Settings menu** for user preferences.
- **Tabs in script viewer** for multi-script editing.

## Features Not Included
Some features remain **exclusive to internal agency operations** and are not part of the public release:
- **Binary SaveInstance Module**
- **Client ↔ Server Bridge**
- **Secret Service Panel (Executor + Output Viewer)**
- **Datastore Editor**
- **3D Model Viewer**

## Community Server
For outdated documentation, discussions, or to connect with others interested in this script, you can join the **Dex Community Server**:

[![Discord](https://img.shields.io/badge/Join%20Us-Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/zinnia)

⚠ **Limited support is available, and responses are not guaranteed.**