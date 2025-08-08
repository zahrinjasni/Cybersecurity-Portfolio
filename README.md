# SY0-701 Portfolio — Practical Cybersecurity Projects

**Overview**
This repository contains 10 practical, Security+ (SY0-701) aligned projects designed to demonstrate hands‑on security skills (network analysis, vulnerability assessment, HIDS, web app testing, SIEM, firewall/IDS tuning, cloud security, forensics/IR, policy design, and malware traffic analysis). Each project is a self-contained lab with assets, documentation, scripts and final reports suitable for inclusion on a resume or in a portfolio review.

**Quick links**
- `projects/01-network-traffic-threat-hunting` — Packet capture & Wireshark threat hunting
- `projects/02-vulnerability-assessment-remediation` — OpenVAS/Nessus scans + remediation plan
- `projects/03-hids-deployment` — Wazuh/OSSEC deployment, dashboards & tuning
- `projects/04-webapp-security-testing` — DVWA pentest, Burp Suite, OWASP mapping
- `projects/05-siem-log-analysis` — Splunk log ingestion, detection searches & dashboards
- `projects/06-firewall-ids-tuning` — pfSense + Snort rules + test cases
- `projects/07-cloud-security-aws` — EC2/IAM/CloudTrail hardening walk-through
- `projects/08-digital-forensics-ir` — Disk & memory acquisition, Volatility, Autopsy
- `projects/09-security-policy-framework` — NIST/ISO-aligned policy templates & mappings
- `projects/10-malware-traffic-analysis` — PCAP analysis and IOCs

**System notes**
- Designed for a mid-range laptop (8GB RAM). Use lightweight VMs, power off unused VMs, and allocate 512–1024MB per lab VM when possible.
- Avoid committing large VM images or raw PCAPs to Git. Use Git LFS or local storage for big files.

**How to use**
1. Clone the repo locally: `git clone <repo-url>`
2. Read the per-project `docs/README.md` inside each `projects/*` folder for step-by-step playbooks
3. Use the `templates/` folder for report templates and IR forms
4. Keep sensitive items (keys, credentials) out of the repo — see `.gitignore`

**Contributing**
This is a personal portfolio repository. If you wish to share improvements, open an issue or a PR.

**License**
See `LICENSE` (add license of choice).

**Contact**
Your Name — your.email@example.com
