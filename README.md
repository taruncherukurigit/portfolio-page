# Tarun Cherukuri — Network & Wireless Engineering Portfolio
[![Live Pages mirror](https://img.shields.io/badge/live-tarunc.com-4FD1C5)](https://tarunc.com) [![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

**View live:** [tarunc.com](https://tarunc.com) *(if the server's down or being updated: [GitHub Pages mirror](https://taruncherukurigit.github.io/portfolio-page/) or browse this repo)*

Network engineer pursuing CCNA and CWNA, M.Eng in Cybersecurity (University of Maryland, 3.9 GPA). This site is the front door to seven projects, all built end to end on real enterprise hardware rather than a simulator.

## Projects

| Project | Live | Repository | Pages mirror | Summary |
|---|---|---|---|---|
| **Cherwood Health** | [cherwood.tarunc.com](https://cherwood.tarunc.com) | [cherwood-health](https://github.com/taruncherukurigit/cherwood-health) | [Pages mirror](https://taruncherukurigit.github.io/cherwood-health/) | Segmented enterprise network on real FortiGate and Cisco hardware — VLANs, firewall policy, SSL-VPN, RIPv2 branch routing, Prometheus/Grafana monitoring, automated config drift detection. 21/21 build parts complete. |
| **Cherwood Network Solutions** | [networksolutions.tarunc.com](https://networksolutions.tarunc.com) · [Live topology map](https://netmap.tarunc.com) | [network-automation-toolkit](https://github.com/taruncherukurigit/network-automation-toolkit) | [Pages mirror](https://taruncherukurigit.github.io/network-automation-toolkit/) | Unattended Python/Netmiko automation that backs up, version-controls, drift-checks, and automatically maps the topology of Cherwood Health's core devices nightly via LLDP — includes root-causing a 12-year-old open-source Paramiko/Cisco IOS SSH compatibility bug. Extended with a real ServiceNow integration: config drift auto-opens an Incident via the Table REST API, verified end-to-end against a full Change Request approval lifecycle. |
| **Cherwood Legal — SIEM-lite + IDS Lab** | [legal.tarunc.com](https://legal.tarunc.com) | [suricata-siem-lite-lab](https://github.com/taruncherukurigit/suricata-siem-lite-lab) | [Pages mirror](https://taruncherukurigit.github.io/suricata-siem-lite-lab/) | A passive intrusion-detection lab on a dedicated VLAN — a live Suricata sensor running the full 52,713-signature Emerging Threats Open ruleset, verified against two real tests: a malware-signature file transfer and a live port scan, both correctly detected and surfaced through a lightweight custom dashboard. |
| **Packetgeist** | [packetgeist.tarunc.com](https://packetgeist.tarunc.com) | [plainsboro-library-survey](https://github.com/taruncherukurigit/plainsboro-library-survey) | [Pages mirror](https://taruncherukurigit.github.io/plainsboro-library-survey/) | Passive 802.11 site survey of a three-storey public library, conducted with permission — 67 measurement points, 1,523 network observations, 8 access points, 6 documented findings extracted directly from the survey database. |
| **Cherwood Financial — HA/Failover Lab** | [failover.tarunc.com](https://failover.tarunc.com) | [hsrp-failover-lab](https://github.com/taruncherukurigit/hsrp-failover-lab) | [Pages mirror](https://taruncherukurigit.github.io/hsrp-failover-lab/) | A real two-switch HSRP failover pair, proven against an actual power-pull rather than a config toggle — measured failover later re-verified at the packet level via the Packet Capture Casebook below. |
| **Cherwood Foundation — AD / 802.1X / SSL-VPN** *(client engagement, delivered by Network Solutions)* | [foundation.tarunc.com](https://foundation.tarunc.com) | [activedirectory-cherwood](https://github.com/taruncherukurigit/activedirectory-cherwood) | [Pages mirror](https://taruncherukurigit.github.io/activedirectory-cherwood/) | Active Directory, 802.1X wireless authentication, and RADIUS-backed SSL-VPN for a nonprofit client — one verified identity across Wi-Fi, VPN, and the desktop itself, replacing a shared Wi-Fi password and unmanaged local VPN accounts. |
| **Packet Capture Casebook** | — (GitHub only) | [packet-capture-casebook](https://github.com/taruncherukurigit/packet-capture-casebook) | — | Four real packet captures tied to specific bugs and design decisions across the other divisions — SSL-VPN TLS negotiation, HSRP failover re-measured at 3.33s from raw timestamps, LLDP discovery frames, and blocked DMZ→Trusted segmentation, each with the real troubleshooting story behind it. |

## Structure

    index.html    The full site — experience, education, certifications, all
                  flagship projects in detail, and other applied work

Single static file, no build step, no dependencies.

## Contact

📧 [taruncheru@gmail.com](mailto:taruncheru@gmail.com)
💼 [LinkedIn](https://www.linkedin.com/in/dsstaruncherukuri)
🐙 [GitHub](https://github.com/taruncherukurigit)

## License

MIT
