# NetMaster — Learn Networking Like a Pro 🌐

A complete, interactive networking learning website. **No backend, no dependencies, no build step.** Pure HTML/CSS/JS — deploy to GitHub Pages in 60 seconds.

## ✨ Features

| Feature | Details |
|---|---|
| **10 Learning Modules** | Fundamentals → OSI → IP/Subnetting → TCP/IP → Routing → DNS/DHCP → Security → WiFi → Cloud/SDN → Troubleshooting |
| **Interactive OSI Model** | Click each of the 7 layers to see protocols, PDUs, devices, and examples |
| **IP/Subnet Calculator** | Enter any IP + CIDR to get network address, broadcast, usable hosts, wildcard mask + visual binary breakdown |
| **CIDR Table** | Full /0 to /32 reference with subnet masks and host counts |
| **Common Ports Reference** | 34 well-known ports, searchable |
| **Packet Simulator** | Animate TCP handshake, UDP, packet loss, retransmission, DNS resolution |
| **Binary Converter** | Decimal ↔ Binary ↔ Hex + IP-to-binary breakdown |
| **Quiz Arena** | 30 questions across all topics with instant scoring |
| **Networking Cheatsheet** | 8 quick-reference cards (private IPs, CIDR, TCP vs UDP, protocols, etc.) |
| **Glossary** | 40+ searchable networking terms |
| **Progress Tracking** | Module completion saved to localStorage |

## 🚀 Deploy to GitHub Pages

### Option 1 — New Repository
1. Create a new repository on GitHub (e.g. `networking-site`)
2. Upload `index.html` to the root
3. Go to **Settings → Pages → Source: Deploy from a branch → main / root**
4. Your site is live at `https://yourusername.github.io/networking-site`

### Option 2 — GitHub CLI
```bash
git init
git add index.html README.md
git commit -m "Initial commit: NetMaster networking website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/networking-site.git
git push -u origin main
```
Then enable GitHub Pages in repository Settings.

### Option 3 — GitHub Desktop
1. Open GitHub Desktop → File → New Repository
2. Copy `index.html` into the repo folder
3. Commit and push
4. Enable Pages in GitHub repository settings

## 📁 File Structure

```
networking-site/
├── index.html    ← Everything is here (self-contained)
└── README.md     ← This file
```

## 🎓 Topics Covered

- Network fundamentals (LAN, WAN, MAN, topologies)
- OSI 7-layer model with encapsulation
- IPv4/IPv6 addressing and subnetting (CIDR)
- TCP/IP, 3-way handshake, ports, sockets
- Routing protocols (OSPF, BGP, RIP, EIGRP)
- DNS, DHCP, NAT
- Network security (firewalls, TLS, attacks)
- Wireless networking (802.11, WiFi 6, WPA3)
- Cloud networking (VPCs, SDN, Kubernetes)
- Troubleshooting methodology and tools

## 🛠 Tech Stack

- Vanilla HTML5, CSS3, JavaScript (ES6+)
- Zero dependencies, zero build tools
- Google Fonts (Space Mono + DM Sans)
- Progress saved to localStorage

## 📄 License

MIT — free to use, modify, and distribute.
