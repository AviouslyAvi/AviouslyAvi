# Hi, I'm Avi 👋
### Foundation-scale IT systems administrator · Home-lab operator · Music producer

I run identity, endpoint, and network operations for a Baltimore philanthropy — and spend my off-hours in a Proxmox cluster and Ableton.

[![Website](https://img.shields.io/badge/Website-it.imavious.org-1f6feb?style=flat-square&logo=googlechrome&logoColor=white)](http://it.imavious.org)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Avi_Ben--Abram-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abenabram/)
[![Email](https://img.shields.io/badge/Email-admin@lumorait.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:admin@lumorait.com)

![IT Systems Administrator](https://img.shields.io/badge/IT_Systems_Administrator-Identity_·_Endpoint_·_Network_·_Security-2ea44f?style=flat-square)
![Lumora IT](https://img.shields.io/badge/Principal_Consultant-Lumora_IT-7c3aed?style=flat-square)
![Security+](https://img.shields.io/static/v1?label=CompTIA&message=Security%2B&color=CC0000&style=flat-square)
![A+](https://img.shields.io/static/v1?label=CompTIA&message=A%2B&color=CC0000&style=flat-square)
![AZ-900](https://img.shields.io/static/v1?label=Microsoft&message=AZ-900%20(in%20progress)&color=0078D4&style=flat-square&logo=microsoftazure&logoColor=white)

---

### About Me

IT Systems Administrator with **4+ years on mixed-OS fleets** at a Baltimore foundation and across four AmLaw firms. Identity-first operator in **Okta + SSO/SAML, Cisco Meraki, Mosyle + ManageEngine**. Co-led a fleet-wide Cisco Umbrella rollout and root-caused a firm-wide Zoom outage at the IPv6 layer.

- 🏢 **IT Systems Administrator** @ Annie E. Casey Foundation
- 🛠️ **Principal Consultant** @ [Lumora IT](http://it.imavious.org) — networks, AV, endpoints for SMB / nonprofit clients
- 🎚️ Off-hours: VST3 plugin development, Ableton, and a Proxmox cluster that refuses to stay simple
- 📍 Baltimore, MD

---

### 📜 Certifications

[![CompTIA A+](https://img.shields.io/static/v1?label=CompTIA&message=A%2B%20%E2%80%94%20Earned&color=CC0000&style=for-the-badge)](https://www.credly.com/badges/f2187817-d731-45c5-afcb-4be2aade86f8/public_url)
[![CompTIA Security+](https://img.shields.io/static/v1?label=CompTIA&message=Security%2B%20%E2%80%94%20Earned&color=CC0000&style=for-the-badge)](https://www.credly.com/badges/78cf48f4-8fe9-46cb-85b1-6b2f5060f443/public_url)
[![Microsoft AZ-900](https://img.shields.io/static/v1?label=Microsoft&message=AZ-900%20%E2%80%94%20In%20Progress&color=0078D4&style=for-the-badge&logo=microsoftazure&logoColor=white)](#)

---

### 🎚️ Audio & Music Production Projects

| Project | Description | Tech |
|---|---|---|
| [**ChainHost**](https://github.com/AviouslyAvi/ChainHost) | JUCE VST3 plugin host with parallel processing chains, dry/wet mixing, MIDI-learnable macro knobs, tempo-synced LFOs, and a preset browser | C++20, JUCE 8, VST3 |
| [**Premonition**](https://github.com/AviouslyAvi/premonition) | Offline reverse-reverb riser generator — bake risers into audio without real-time processing | C, VST3 / AU / CLAP / AAX |
| [**Stereo Discord Bot**](https://github.com/AviouslyAvi/stereo-discord-bot) | Stereo audio routing into Discord voice channels via a bot account, with a macOS setup guide | macOS, BlackHole, Discord API |
| [**revis-cloud**](https://github.com/AviouslyAvi/revis-cloud) | Multi-user music collaboration platform | HTML, Web |
| [**Music-Portfolio**](https://github.com/AviouslyAvi/Music-Portfolio) | Personal music portfolio site | HTML, CSS |

---

### 🌐 Web & App Projects

| Project | Description | Tech |
|---|---|---|
| [**ASPD Quiz**](https://github.com/AviouslyAvi/aspd-quiz) | DSM-5-aligned ASPD self-reflection questionnaire — fully client-side scoring, no data leaves the browser | TypeScript |
| [**imavious**](https://github.com/AviouslyAvi/imavious) | Personal site / portfolio backing [it.imavious.org](http://it.imavious.org) | TypeScript |
| [**guitar**](https://github.com/AviouslyAvi/guitar) | Guitar-related tooling / scripting | Python |

---

### 🏠 Home Lab & Infrastructure Projects

| Project | Description | Tech |
|---|---|---|
| [**Proxmox**](https://github.com/AviouslyAvi/Proxmox) | Personal Proxmox cluster configs and notes — see Home Lab section below for the full stack | Proxmox VE, Shell |
| [**Stardew Multiplayer Server**](https://github.com/AviouslyAvi/Stardew-Multiplayer-Server) | Dockerized multiplayer server on Debian + Docker Compose + KasmVNC with web VNC, GPU passthrough, persistent volumes, and cross-platform helper scripts | Debian, Docker Compose, KasmVNC, Shell / PowerShell / Batch |

---

### 🏠 Home Lab

A personal **Proxmox cluster** that's grown into a small private cloud:

**Hypervisor & orchestration**
- 🖧 **Proxmox VE** cluster running mixed VM + LXC workloads, snapshots, scheduled backups, and live migration between nodes
- 🐳 **Docker + Docker Compose** managed through **Portainer** for one-pane visibility across container stacks
- 💾 **Unraid** secondary node handling bulk storage (parity-protected array + cache pool) and a separate Docker stack for media + game servers

**Networking & DNS**
- 🛡️ **pfSense** as edge router/firewall — VLAN segmentation, traffic shaping, IDS/IPS, isolated IoT/guest networks
- 🕳️ **PiHole** as network-wide DNS sinkhole for ad/tracker blocking + custom local DNS records
- 🔐 **Tailscale** mesh VPN for zero-config remote access to lab nodes and services
- ☁️ **Cloudflare DNS + Tunnels** fronting publicly exposed services (no open inbound ports on the WAN)

**Virtual machines**
- 🪟 **Windows VMs** with **GPU passthrough** (PCIe IOMMU) for gaming, music production (Ableton + VST development), and Adobe workloads
- 🍎 **macOS VMs** for cross-platform plugin testing (ChainHost ships VST3 + standalone on macOS)
- 🐧 **Debian / Linux VMs** running the Docker host, dev environments, and dedicated app servers

**Self-hosted services**
- 🎮 **Stardew Valley multiplayer server** — Dockerized on Debian with **KasmVNC** for web-based access, GPU passthrough, persistent volume mounts, and cross-platform Shell / PowerShell / Batch helper scripts
- 🎥 **nginx-RTMP** stream relay (originally built for a community org — POE IP camera feed relayed across floors and out to the public site)
- 📺 Media stack (Plex/Jellyfin + the *arr suite) on Unraid
- 🔄 Scheduled off-site backups + monitoring/alerting

**Why I built it**
The lab is where I prototype the same patterns I run at work — identity, segmentation, monitoring, lifecycle automation — without anyone's SLA on the line. Most of what shows up in my day job's runbooks was tested here first.

---

### 🧰 Tech & Tools

**Identity & Endpoint**
![Okta](https://img.shields.io/badge/Okta-007DC1?style=flat-square&logo=okta&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active_Directory-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Mosyle](https://img.shields.io/badge/Mosyle_MDM-000?style=flat-square)
![ManageEngine](https://img.shields.io/badge/ManageEngine-E42527?style=flat-square)
![Microsoft 365](https://img.shields.io/badge/Microsoft_365-D83B01?style=flat-square&logo=microsoft365&logoColor=white)

**Network & Security**
![Cisco Meraki](https://img.shields.io/badge/Cisco_Meraki-1BA0D7?style=flat-square&logo=cisco&logoColor=white)
![Cisco Umbrella](https://img.shields.io/badge/Cisco_Umbrella-1BA0D7?style=flat-square&logo=cisco&logoColor=white)
![Ubiquiti](https://img.shields.io/badge/Ubiquiti-0559C9?style=flat-square&logo=ubiquiti&logoColor=white)
![pfSense](https://img.shields.io/badge/pfSense-212121?style=flat-square&logo=pfsense&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)

**Platforms & Infra**
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Unraid](https://img.shields.io/badge/Unraid-F15A2C?style=flat-square)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000?style=flat-square&logo=apple&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

**Scripting & ITSM**
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![ServiceNow](https://img.shields.io/badge/ServiceNow-81B5A1?style=flat-square&logo=servicenow&logoColor=white)
![Zendesk](https://img.shields.io/badge/Zendesk-03363D?style=flat-square&logo=zendesk&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Collaboration & AV**
![Zoom](https://img.shields.io/badge/Zoom_Rooms-2D8CFF?style=flat-square&logo=zoom&logoColor=white)
![Teams](https://img.shields.io/badge/MS_Teams-6264A7?style=flat-square&logo=microsoftteams&logoColor=white)
![OBS](https://img.shields.io/badge/OBS_Studio-302E31?style=flat-square&logo=obsstudio&logoColor=white)

---

### 📊 GitHub

![Avi's GitHub stats](https://aviouslyavi-grs.vercel.app/api?username=AviouslyAvi&show_icons=true&hide_border=true&include_all_commits=true&count_private=true)
![Top Languages](https://aviouslyavi-grs.vercel.app/api/top-langs/?username=AviouslyAvi&layout=compact&hide_border=true)

---

### 📫 Get In Touch

Open to IT engagements at foundation or mid-firm scale — identity + endpoint rollouts, network deployments, boardroom AV, Windows imaging. Also offering audio mixing, sound design, and music production lessons.

🌐 [it.imavious.org](http://it.imavious.org) · 💼 [LinkedIn](https://www.linkedin.com/in/abenabram/) · ✉️ [admin@lumorait.com](mailto:admin@lumorait.com)
