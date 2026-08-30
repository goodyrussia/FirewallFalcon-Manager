<div align="center">
  <img src="https://img.shields.io/badge/FirewallFalcon-Manager-blue?style=for-the-badge&logo=shield" alt="FirewallFalcon" />
  <h1>🦅 FirewallFalcon Manager v4.0.0</h1>
  <p><b>The ultimate, lightning-fast, and beautiful terminal UI manager for VPN tunneling, protocol deployments, and advanced user administration on Linux servers.</b></p>
  
  <img src="https://img.shields.io/badge/platform-linux-lightgrey?style=flat-square" alt="Platform">
  <img src="https://img.shields.io/badge/bash-%3E%3D4.0-yellow?style=flat-square&logo=gnu-bash" alt="Bash">
</div>

---

## ✨ Why FirewallFalcon Manager?

FirewallFalcon Manager is built with an **obsessive focus on speed, fluidity, and aesthetics**. We took the traditional chunky script and refined it into a gorgeous, highly responsive, and relentlessly efficient terminal experience.

Whether you're managing 5 users or 500, deploying complex protocols, or locking down your server traffic—you can do it all in seconds, with zero frustration.

---

## 🚀 Installation

It takes less than a minute to deploy the complete FirewallFalcon Manager on your fresh VPS. Choose the installation method that works best for you:

### Primary Method (Recommended)
```bash
bash <(curl -Ls https://raw.githubusercontent.com/goodyrussia/FirewallFalcon-Manager/main/install.sh)
```

*(Once installed, simply type `menu` in your terminal to launch the interface!)*

---

## 🌟 Elite Features

### 👤 Hyper-Optimized User Management
* **Batch Operations Engine:** Delete, Lock, Unlock, or Renew multiple users simultaneously. You can type `1 3 5` or ranges like `1-4` to execute massive operations in the blink of an eye.
* **Smart UI Selection:** Automatically detects your user count. If you have fewer than 15 active users, it dynamically skips the search prompt to save you keystrokes.
* **Agile Creation:** Bulk string generation with instant preset defaults (`Enter` for 30 Days, unlimited Bandwidth, 1 Device Connection).
* **Temporary Trial Accounts:** Instantly spin up self-destructing trial accounts spanning 1, 2, 6, 12, or 24 hours (powered autonomously by the `at` daemon).

### 🛠️ One-Click VPN & Protocol Deployers
Easily spin up entire tunneling infrastructures onto your server without touching a single complex config file.
* **BadVPN (UDP Gateway):** Optimize gaming and tunneling packets.
* **UDP Custom:** Manage customizable UDP bypasses.
* **SSL Tunnels:** HAProxy payload routing on port 444.
* **Nginx Reverse Proxy:** Full HTTP/HTTPS webserver installer, featuring **Auto-Certbot integration** for free SSL certificates.
* **DNSTT (SlowDNS):** Bypass heavy firewalls through port 53 DNS records — bring your **own nameserver + tunnel domain**.
* **ZiVPN (UDP):** Accelerated custom UDP handling.
* **3X-UI / X-UI Web Panel:** One-click installer with a chooser menu — 3X-UI (recommended) or legacy X-UI.

### 📊 Advanced Quotas & Network Safety
* **Strict Bandwidth Limiting:** Assign gigabyte allowances (e.g., 50GB) upon creation. Background services will safely and automatically lock users who exceed their usage.
* **Active Connection Limits:** Ensure nobody shares their account by enforcing strict concurrent session limits. 
* **Live Traffic Monitor:** Check high-speed Bash network tracking (or install `vnstat` for persistent metrics).
* **Anti-Torrent Guard:** Deploy stateful iptables payload inspection to permanently drop `BitTorrent` data, protecting your host from abuse complaints.

### 🎨 Beautiful SSH Customization
* **Dynamic Login Banners:** FirewallFalcon overrides the default SSH `sshd_config` to inject an intelligent script. 
* When your users connect via an HTTP injector or SSH tunnel app, they are greeted by a beautiful customized text box detailing their exact:
  * Expiry Date
  * Quota Remaining
  * Real-Time Active Connections

### 🌐 Bring Your Own Domain
* Register your own domain (or subdomain) whose **A record points to your server's IP** — used automatically for the SSL tunnel, Certbot, and client config generation.
* **DNSTT** uses your own nameserver (`ns1.yourdomain.com`) + tunnel domain (`tun.yourdomain.com`).

### 💾 Backup & Restore Stability
* Automatically collect your payload records, user databases, TLS certificates, and bandwidth usage statistics into single portable `.tar.gz` archives. Restore entire businesses onto a new server with one menu click.

---

<div align="center">
  <b>FirewallFalcon Manager — community edition</b><br>
  <i>"Fast configuration, Secure tunneling, Beautiful interfaces."</i>
</div>
