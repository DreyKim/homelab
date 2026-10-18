# homelab

A self-hosted infrastructure I run to practice the skills I use professionally in IT support and systems administration: containerization, networking, security, and monitoring.

## hardware

- Lenovo ThinkPad T460 running Ubuntu 24.04 and Docker
- [CPU: Intel(R) Core(TM) i5-6300U (4) @ 3.00 GHz]
- [RAM: 8GB DDR4] 
- [Storage: 1TB HDD]

## services

| Service | Purpose |
|---|---|
| Seafile CE 13 | Private file sync and storage (desktop and Android clients). Community Edition chosen for code transparency |
| Forgejo | Personal self-hosted Git repository for code and configuration |
| Find My Device (by Nulide) | Open-source device tracking, so I don't rely on a commercial service |
| Navidrome | Self-hosted music streaming |
| Glance | Custom dashboard: container status, server stats, weather, RSS feeds |

<img width="1366" height="736" alt="Screenshot From 2026-10-18 16-54-57" src="https://github.com/user-attachments/assets/382f19fc-3d71-4c6d-bd2e-4040c0fa00c3" />


## networking and security

- All remote access runs through Tailscale, so no services are exposed to the public internet
- MagicDNS provides stable hostnames
- UFW handles host firewalling; nginx handles reverse proxying and CORS


## why I need this grant

My lab runs on a single laptop and a flat network, which limits what I can practice. Funding would let me:

1. **Earn networking certifications** ([CCNA & Fortinet]) to formalize and validate skills I currently build through self-study
2. **Buy network equipment** ([Cisco switch and router & Fortigate Firewall]) to build a segmented, realistic lab for VLANs, routing, firewall policy, and monitoring
3. **Buy study materials** to support certification prep

## Contact

GitHub: [@DreyKim](https://github.com/DreyKim)
Email: [kimathiandre@gmail.com](kimathiandre@gmail.com)
