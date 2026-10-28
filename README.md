# Patricio Espinosa Quijano

**SOC Analyst Intern · Detection Engineering · Cybersecurity Engineering student (expected 2028)**

Mérida, Yucatán, México · [LinkedIn](https://www.linkedin.com/in/patricio-espinosa-quijano) · [patricio.espinosaquijano@gmail.com](mailto:patricio.espinosaquijano@gmail.com)

I work in security operations: onboarding security telemetry into Google SecOps, writing and tuning YARA-L 2.0 detection rules, and documenting SOAR response playbooks. Outside work, I build open, reproducible labs that show how attacks and defenses actually behave, and I share them with the security and CSIRT community.

**Currently looking for:** roles in SOC operations or detection engineering.

## What I work on

- **Security telemetry:** onboarding and normalizing logs from multiple sources into Google SecOps with Bindplane.
- **Detection engineering:** writing and tuning YARA-L 2.0 rules to catch suspicious and malicious activity.
- **Threat intelligence:** mapping adversary TTPs to MITRE ATT&CK to find gaps in detection coverage.
- **Response automation:** designing and documenting SOAR playbooks that standardize incident handling.
- **Awareness and community:** phishing and social-engineering sessions for local businesses and students, and participation in the LACNIC CSIRTs community.

## Featured projects

### [Email Authentication Lab (SPF, DKIM, DMARC)](https://github.com/PatoEQ/email-auth-lab)

`Docker` `Postfix` `OpenDKIM` `Rspamd` `CoreDNS` `Python` `pytest` `GitHub Actions`

A reproducible, network-isolated lab that replays a CEO-fraud (BEC) spoofing attack against a fictional bank, adding one defense per scenario until DMARC `p=reject` stops it.

- 6 spoofing techniques (envelope forgery, in-transit tampering, attacker-signed DKIM, lookalike domains) that show what each protocol blocks and where it fails.
- A Python CLI that switches scenarios with one command and explains every authentication result in plain language.
- The full attack-by-scenario matrix is checked by pytest against the running lab in GitHub Actions CI.
- Presented live to security professionals and CSIRT teams.

<!--
### [SOC Sentinel Crew](https://github.com/PatoEQ/soc-sentinel-crew)

Uncomment this block when the repository is public.
-->

## Tech stack

| Area | Tools |
|---|---|
| Detection & SIEM/SOAR | Google SecOps (YARA-L 2.0), Microsoft Sentinel (KQL), Splunk (SPL), SOAR playbooks, MITRE ATT&CK |
| Log analysis & DFIR | Windows Event Logs, Sysmon, PCAP analysis, memory analysis, incident response lifecycle |
| Email & network security | SPF, DKIM, DMARC, Postfix, Rspamd, DNS |
| Cloud & identity | Google Cloud Platform, Microsoft Azure, Active Directory, Microsoft Entra ID |
| Languages & tooling | Python, Bash, PowerShell, SQL, Docker, Git, GitHub Actions |

## Certifications

| Certification | Issuer | Date |
|---|---|---|
| Certified Defensive Security Analyst (CDSA) | Hack The Box | Jul 2026 |
| Certified CyberDefender Level 1 (CCDL1) | CyberDefenders | Mar 2026 |
| Microsoft Certified: Azure Fundamentals (AZ-900) | Microsoft | Nov 2025 |
| Google Cybersecurity Professional Certificate | Google | Oct 2024 |

## Languages

Spanish (native) · English (C1, iTEP)
