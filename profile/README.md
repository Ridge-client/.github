<div align="center">

# Ridge

**One desktop app for OSINT investigations. Search 1,700+ tools in one catalog and run sock-puppet personas in their own isolated browsers.**

<br>

[Download Latest Release](https://github.com/cmpnn-romain/Ridge/releases)

</div>

## What is Ridge?

Ridge puts the OSINT toolkit and your sock-puppet personas in one place. You no longer keep bookmark lists, spreadsheets of fake identities and separate browser profiles side by side. The app has two tabs:

* **OSINT Tool Catalog**: All 1,700+ tools from the [Awesome-OSINT-List](https://github.com/Astrosp/Awesome-OSINT-List), searchable by name and category. One click checks which sites are `ACTIVE`, `GUARDED` or `DOWN`, and another opens a tool in your browser.
* **Persona Builder**: Fill in an identity sheet (names, birth, documents, address, job, vehicle, profile picture). The ID generator sites open in a built-in browser next to the form, so you can copy values across.
* **Isolated Persona Browsers**: Each persona runs in its own Docker container and keeps its own history, bookmarks and logins between sessions. Before a persona starts, a checklist asks you to confirm your VPN is on and your timezone matches its country.

## Ecosystem Repositories

| Repository | Description |
| :--- | :--- |
| **[`Ridge`](https://github.com/cmpnn-romain/Ridge)** | The desktop app, built in Rust with egui, with Docker for persona containers. |

## Quick Start

1. **Grab the App**: Download the latest build from the [`Ridge/releases`](https://github.com/cmpnn-romain/Ridge/releases) page. On **Windows 10/11**, use `Ridge-Setup-X.Y.Z.exe` (it installs without administrator rights). Builds for **macOS** and **Linux** are also available.
2. **Prerequisites**: The Personas tab needs **Docker Desktop** running. The OSINT tools tab works without it.
3. **Explore the Catalog**: Search for a tool or pick a category, press **Check status** to see which sites are up, then **Open** the one you need.
4. **Build a Persona**: Press **Create persona**, fill in the identity sheet and save it. Ridge downloads the persona browser in the background (once, about 1 GB). Then press **Start**.

## Disclaimer & Licensing

Ridge is an independent project and is **not affiliated with, endorsed by, or associated with the Awesome-OSINT-List or any of the tools and websites it catalogs**.

The client is released under the GNU General Public License v3.0 (GPL-3.0). Please refer to individual repositories for contributor history, lineage, and upstream credits.