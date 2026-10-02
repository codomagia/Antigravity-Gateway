# Antigravity with any Secure Connection: Stable connectivity without drops or Error 400

[Русский](README.md) | [English](README.en.md)

<img align="right" src="assets/logo.png" alt="Antigravity Gateway" width="220" height="220">

**Antigravity Gateway** is a launcher to run Google Antigravity through YOUR preferred secure connection or proxy (Happ, Hiddify, v2ray, Xray, Clash, Nekoray, Sing-box, AdGuard, WireGuard, etc.), ensuring stable connectivity without connection drops or Error 400.

**Version:** 1.0.0  
**Author:** [CodoMagia](https://github.com/codomagia)  
**Community & Support (Telegram):** [t.me/AntigravityGateway](https://t.me/AntigravityGateway)  
**Support the author:** [Boosty](https://boosty.to/codomagia/donate)

Pre-built releases are available in [Releases](https://github.com/codomagia/Antigravity-Gateway/releases).

---

## Screenshot

![Antigravity Gateway](assets/screenshot.png)

---

### Why is this method required?

Because Google Antigravity deliberately bypasses system-wide secure connections by default. This launcher securely instructs Antigravity to route its internet traffic through your chosen secure connection.

### Why choose this launcher over other solutions?

- **Zero file modifications:** It does **NOT** modify Antigravity binaries or any system files. All routing parameters are passed natively at startup.
- **Zero background overhead:** Immediately after launching Antigravity, the launcher exits and consumes zero RAM.
- **Clean for antivirus software:** Since no memory injection or file patching is used, antivirus tools do not trigger false positives. No exclusion rules needed.
- **Traffic isolation:** Only Antigravity is routed through the secure connection. Browsers, games, and other apps run directly at full speed.

---

### Key Features:

- **1-Click Auto-Discovery:** Instantly detects running proxy clients or active system secure connections.
- **Desktop Shortcut with Pre-Flight Splash Check:** Tests gateway reachability before starting: launches instantly if ready, or prompts to enable the secure connection if offline.
- **Real-Time Diagnostics:** Measures latency (ping), verifies Google Gemini server connectivity, and detects region/bot restrictions.

---

### Quick Start:

1. Download `Antigravity-Gateway-1.0.0.zip` from [Releases](https://github.com/codomagia/Antigravity-Gateway/releases/latest).
2. Unpack the archive into a permanent folder.
3. Launch `Antigravity Gateway.exe`.
4. Click **«🔍 Найти клиент»** (Find client), then **«📌 Создать ярлык»** (Create shortcut).

> **Protocol Tip (HTTP vs SOCKS5):** If routing through `http://` in your client causes connection drops with Google Gemini API, choose a **SOCKS5** preset from the dropdown (e.g. `socks5://127.0.0.1:10808` for Happ or `socks5://127.0.0.1:2080` for Sing-box/Hiddify). SOCKS5 tunnels raw TCP streams without breaking gRPC connections.

> **Note:** No installation required. Do not run directly from inside the ZIP file.

---

## Requirements

- **OS:** Windows 10 or Windows 11 (x64)
- **Framework:** .NET Framework 4.7.2 or newer (built into Windows 10/11)
- **Target Application:** Google Antigravity (Installed or Portable)
- **Supported Clients:** Happ, Hiddify, Clash (Verge / Meta / Nyanpasu), Xray / V2Ray, Nekoray, Sing-box, AdGuard, WireGuard, and any SOCKS5 / HTTP proxy.

---

## License

Copyright © 2026 CodoMagia. All rights reserved.
