# Tarun Cherukuri · Network Engineering Portfolio

**View it:** [taruncherukurigit.github.io/portfolio-page](https://taruncherukurigit.github.io/portfolio-page/)

M.Eng in Cybersecurity (University of Maryland, 3.9 GPA). Graduate Course Assistant and Graduate Teaching Assistant for UMD networking courses. CompTIA Network+ and Security+, AWS Certified Cloud Practitioner, CCNA in progress. This site is the front door to seven projects from my personal lab, all built on real hardware rather than a simulator.

## Projects

| Project | Repository | Summary |
|---|---|---|
| **Segmented Enterprise Network** | [cherwood-health](https://github.com/taruncherukurigit/cherwood-health) | FortiGate 60E and Cisco 3560E/1921 hardware, 4 VLANs, firewall policy, SSL-VPN, RIPv2 branch routing and Prometheus/Grafana monitoring. |
| **Python Network Automation and ServiceNow** | [network-automation-toolkit](https://github.com/taruncherukurigit/network-automation-toolkit) | Nightly Netmiko backups, Git history, drift detection and LLDP topology discovery. Root-caused a 12-year-old open Paramiko/Cisco IOS SSH bug. Drift opens a ServiceNow Incident through the Table REST API. |
| **HSRP High-Availability Lab** | [hsrp-failover-lab](https://github.com/taruncherukurigit/hsrp-failover-lab) | Two physical Cisco 3560E switches sharing a virtual gateway, proven with a power-pull test and measured at 3.33 seconds from packet timestamps. |
| **Active Directory, 802.1X and RADIUS** | [activedirectory-cherwood](https://github.com/taruncherukurigit/activedirectory-cherwood) | AD DS/DNS, an Enterprise CA and NPS as RADIUS for a Cisco AP and FortiGate SSL-VPN, with valid and invalid logins tested on both. |
| **Suricata IDS and SIEM-lite Dashboard** | [suricata-siem-lite-lab](https://github.com/taruncherukurigit/suricata-siem-lite-lab) | Suricata on a dedicated VLAN with the 52,713-signature ET Open ruleset plus two custom rules, two live detections verified in a Flask/SQLite dashboard. |
| **Wireless Site Survey, Plainsboro Public Library** | [plainsboro-library-survey](https://github.com/taruncherukurigit/plainsboro-library-survey) | Passive 802.11 survey with permission: 67 points, 1,523 observations, 8 access points. Coverage was fine. Channel planning was the problem. |
| **Self-Hosted Automation Pipelines** | [kindle-daily-digest](https://github.com/taruncherukurigit/kindle-daily-digest) · [homelab-rss-digest-pipeline](https://github.com/taruncherukurigit/homelab-rss-digest-pipeline) | FreshRSS, n8n, Flask and pandoc on Proxmox LXC deliver a Kindle EPUB twice a day. Docker Compose and ntfy push digests over Tailscale. |
| **Packet Capture Casebook** | [packet-capture-casebook](https://github.com/taruncherukurigit/packet-capture-casebook) | Four real captures tied to bugs in the projects above: TLS 1.3 on the SSL-VPN, HSRP failover, LLDP frames and blocked DMZ recon. |

## Structure

    index.html    The full site: experience, education, certifications and every project in detail

Single static file, no build step, no dependencies. Served by GitHub Pages.

## Contact

[taruncheru@gmail.com](mailto:taruncheru@gmail.com) · [LinkedIn](https://www.linkedin.com/in/dsstaruncherukuri) · [GitHub](https://github.com/taruncherukurigit)

## License

MIT
