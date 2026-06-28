# Polo · Cybersecurity & Self-Hosted Infrastructure

Security-focused homelab builder. I design and operate hardened self-hosted infrastructure with a strong emphasis on defense in depth, active threat detection and operational monitoring.

![Focus](https://img.shields.io/badge/Focus-Defense_in_Depth-darkred?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Debian_ARM64-A81D33?style=flat-square&logo=debian&logoColor=white)
![Containers](https://img.shields.io/badge/Containers-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Network](https://img.shields.io/badge/Network-WireGuard-881798?style=flat-square&logo=wireguard&logoColor=white)
![Monitoring](https://img.shields.io/badge/Monitoring-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Observability](https://img.shields.io/badge/Observability-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

## Projects

| Project | Description |
| --- | --- |
| [secure-vps-homelab](https://github.com/Jager-29/secure-vps-homelab) | Configuration and documentation for deploying a secure VPS and homelab environment. Focuses on server hardening, network security, and self-hosted services management. |
| [securehomelab](https://github.com/Jager-29/securehomelab) | Containerized homelab stack: CrowdSec, Cowrie honeypot, Nginx Proxy Manager, Prometheus, Grafana, Metabase threat intel |
| [syswarden-homelab](https://github.com/Jager-29/syswarden-homelab) | SysWarden v3.10.2 HIPS deployed on ARM64 with manual Go compilation, nftables L2/L3 defense, full audit 7/7 PASS |

## Stack

**Security** CrowdSec · Wazuh · SysWarden · nftables · Fail2ban · Cowrie · GeoIP / ASN filtering
**Infrastructure** Docker · Nginx Proxy Manager · Portainer · Tailscale · WireGuard
**Observability** Prometheus · Grafana · Metabase · Uptime Kuma
**Platform** Debian ARM64 · Linux · Freebox Ultra · VPS-2-2027-OVH

## Focus

- Defense in depth architecture, from L2 kernel filtering to L7 application defense
- Threat intelligence and active honeypot deployment
- Self-hosted infrastructure hardening and monitoring

## What I am working on

Documenting real deployment outcomes (blocked ASNs, GeoIP stats, audit results) and extending observability across the stack.

---

<sub>Based in France · Open to connect on infrastructure security and self-hosting.</sub>
