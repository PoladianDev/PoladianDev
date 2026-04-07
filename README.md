# Noah Poladian
### Linux & DevOps · Self-hosted infrastructure · Open to remote

I don't just study systems — I run them.

My homelab is a **32-bit Debian server** (Intel Atom, 1 GB RAM) hosting real services in production: a password manager, cloud storage, DNS filtering, and a music streaming app I built from scratch — all behind a Tailscale overlay network, Apache reverse proxies, and proper hardening.

Currently a fresh **BBA grad in MIS** (Haigazian University '25), building toward a remote DevOps / Linux admin role by closing my gaps in CI/CD, Kubernetes, and IaC — one real project at a time.

---

## 🖥️ What's running in my homelab

| Service | Stack | Why it's interesting |
|---|---|---|
| **Vaultwarden** | Rust · Apache · Tailscale | Cross-compiled for i686 — no Docker, 1 GB RAM, still running |
| **Nextcloud** | Apache · NTFS HDD · ext4 loopback | Data dir on external HDD via loopback image workaround |
| **Napalify** | Flask · JavaScript · iTunes API | Music streaming app I built — gapless playback, mobile UI |
| **Pi-hole** | DNS · Tailscale nameserver | Network-wide ad filtering, routed through Tailscale |
| **Monitoring** | Fail2ban · UFW · Telegram bot | Health alerts, SSH/Nextcloud jails, port hardening |

---

## 🔧 Stack

```
OS          Arch Linux (daily) · Debian (server)
Networking  Tailscale · UFW · Pi-hole · Apache (reverse proxy + TLS)
Containers  Docker · Portainer
Scripting   Bash · Python
Security    Fail2ban · UFW · Tailscale certs
```

---

## 🚀 Currently building toward

- [x] Reverse proxy + TLS + network hardening
- [x] Bash scripting · systemd timers · Linux admin
- [x] Self-hosted stack on constrained hardware
- [ ] **CI/CD** — Gitea + auto-deploy pipelines *(in progress)*
- [ ] **Kubernetes** — k3s cluster setup
- [ ] **IaC** — Terraform configs
- [ ] **Observability** — Prometheus + Grafana (replacing the Telegram bot)

---

## 📬 Let's talk

[![LinkedIn](https://img.shields.io/badge/LinkedIn-nazarpoladian-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/nazarpoladian)
[![Email](https://img.shields.io/badge/Email-nazarpoladian1@gmail.com-EA4335?style=flat&logo=gmail)](mailto:nazarpoladian1@gmail.com)
