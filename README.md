# Nazar Poladian
### Linux · DevOps · Self-hosted infrastructure · Open to remote

BBA in Management Information Systems, Haigazian University '25. I run a personal homelab on a 32-bit Debian server hosting production services, and I'm working toward a remote DevOps / Linux admin role.

&nbsp;

## 🖥️ Homelab

| Service | Stack | Notes |
|---|---|---|
| **Vaultwarden** | Rust · Apache · Tailscale | Cross-compiled for i686 | no Docker, runs on 1 GB RAM |
| **Nextcloud** | Apache · ext4 loopback | Data directory on external HDD via loopback image |
| **WaveForm** | Flask · JavaScript · iTunes API | Music streaming app I built | gapless playback, mobile UI |
| **Pi-hole** | DNS · Tailscale nameserver | Network-wide ad filtering routed through Tailscale |
| **Monitoring** | Fail2ban · UFW · Telegram bot | Health alerts, SSH and Nextcloud jails, port hardening |

&nbsp;

## 🔧 Stack

```
OS            Arch Linux (daily) · Debian (server)
Networking    Tailscale · UFW · Pi-hole · Apache (reverse proxy + TLS)
Containers    Docker · Portainer
Scripting     Bash · Python
Security      Fail2ban · UFW · Tailscale certs
```

&nbsp;

## 🚀 Currently building toward

- [x] Reverse proxy, TLS, network hardening
- [x] Bash scripting, systemd timers, Linux administration
- [x] Self-hosted stack on constrained hardware
- [ ] **CI/CD** — Gitea + auto-deploy pipelines *(in progress)*
- [ ] **Kubernetes** — k3s cluster
- [ ] **IaC** — Terraform
- [ ] **Observability** — Prometheus + Grafana

&nbsp;

## 📬 Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-nazarpoladian-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/nazarpoladian)
[![Email](https://img.shields.io/badge/Email-nazarpoladian1@gmail.com-EA4335?style=flat&logo=gmail)](mailto:nazarpoladian1@gmail.com)
