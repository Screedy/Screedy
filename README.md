# Petr Jurásek · Infrastructure & Platform Engineering

MSc student in Applied Computer Science at Palacký University in Olomouc. My background is in software development, but the work I find most compelling sits at the boundary between software and infrastructure — the layer where reliability, security, and operational discipline actually get enforced.

🌍 Czech Republic &nbsp;·&nbsp; 📬 petr@jurasek.cc &nbsp;·&nbsp; 🔗 **[portfolio.jurasek.cc](https://portfolio.jurasek.cc)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/petr-jurásek-423a92315)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=firefox&logoColor=white)](https://portfolio.jurasek.cc)
[![Printables](https://img.shields.io/badge/Printables-FA6831?style=for-the-badge&logo=printables&logoColor=white)](https://www.printables.com/@Screedy_229738)

---

## Homelab — production-grade, self-built, self-operated

A two-node Proxmox VE cluster with VLAN-segmented networking, zero-trust external access via Cloudflare Tunnels, and a full observability stack. Every design decision mirrors what you'd find in a real production environment.

| | |
|---|---|
| **Compute** | 2-node Proxmox VE cluster · Proxmox Backup Server · Raspberry Pi quorum device |
| **Storage** | TrueNAS SCALE over NFS/SMB |
| **Networking** | UniFi · 6 VLANs · default-deny firewall policy |
| **Ingress** | Traefik v3 · Cloudflare Tunnel · wildcard TLS via DNS-01 |
| **Observability** | Prometheus · Grafana · Wazuh SIEM · Beszel |
| **Identity** | Authentik SSO · split-horizon DNS via Technitium |
| **Services** | 25+ self-hosted apps across isolated VLANs |

Full architecture, VLAN map, firewall rules, and engineering decisions at **[portfolio.jurasek.cc](https://portfolio.jurasek.cc)**

---

## Open to

`Network administrator` · `Linux systems admin` · `Hypervisor / virtualisation` · `Infrastructure engineer` · `Data infrastructure` · `Storage & ACL management`
