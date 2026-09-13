<div align="center">

<img src="icon.png" alt="MigMig VPN" width="96" />

# MigMig VPN

**A modern desktop VPN client for Windows**

<div align="center">

[![Version](https://img.shields.io/badge/version-1.1.0-7C3AED?style=for-the-badge&logo=semanticrelease&logoColor=white)](#download)
[![Status](https://img.shields.io/badge/status-stable-22C55E?style=for-the-badge&logo=checkmarx&logoColor=white)](#)
[![Discord](https://img.shields.io/badge/Discord-Join%20Server-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/Wt3vD45hu2)
[![GitHub Stars](https://img.shields.io/github/stars/USERNAME/REPO?style=for-the-badge&logo=github&color=FFD700&labelColor=181717)](https://github.com/USERNAME/REPO/stargazers)
[![Downloads](https://img.shields.io/github/downloads/USERNAME/REPO/total?style=for-the-badge&logo=github&color=8B5CF6&labelColor=181717&label=Total%20Downloads)](https://github.com/USERNAME/REPO/releases)

</div>

---

## Overview

MigMig VPN is a Windows desktop client built for reliability and clarity.  
It connects through your own subscriptions and manual configs, surfaces real exit information, and recovers automatically when a route fails.

---

## Features

### Connectivity
- **Subscription support** for `vless://`, `vmess://`, `trojan://`, `ss://`, `hysteria2://`, `wireguard://`, `anytls://`, and `vpn://`
- **Manual configs** — paste share links or WireGuard / AmneziaWG profiles and use them alongside subscriptions
- **Smart selection** — filter by country or protocol, or pin a specific node; invalid choices are rejected instead of ignored
- **Accurate status** — shows the node’s claimed location and the real exit country measured through the tunnel; when they differ, the measurement wins

### Reliability
- **Health checks** every 20 seconds with automatic failover when traffic stops
- **Pinned nodes stay pinned** — manual selections are never silently overridden
- **Background operation** — closing the window minimizes to the tray; the tunnel keeps running

### Tools
- **Server workbench** — test reachability, latency, and throughput; sort results; share node links
- **Tunnel-check engine** — probes over TCP / TLS / HTTP / WebSocket / UDP / QUIC / DNS with A+–F grading and false-positive detection

### Interface
- Clean, animated UI with light and dark modes
- Violet-to-pink brand theme and smooth transitions throughout

---

## Download

See the [Releases](../../releases) page for the latest Windows build.

**Requirements:** Windows 10 or Windows 11

---

## Community

Join the Discord for support, feedback, and updates:  
[https://discord.gg/Wt3vD45hu2](https://discord.gg/Wt3vD45hu2)

---

<div align="center">

**Made with ❤️ and ☕ by RyxoStudio**

</div>
