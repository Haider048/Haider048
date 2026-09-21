<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:00ff41&height=200&section=header&text=Haider%20Jamal&fontSize=45&fontColor=00ff41&fontAlignY=35&desc=SOC%20Analyst%20%7C%20Blue%20Team%20%7C%20CEH%20Certified&descAlignY=55&descColor=8b949e&animation=fadeIn)

```
[root@haider]─[~]$ whoami
> Cybersecurity practitioner | Networking → Detection Engineering → Incident Response
> Turning noisy logs into signal, and attacks into documented, escalated, remediated cases
```

</div>

<br>

## `~/about`

```yaml
role:          Aspiring SOC Analyst L1 (Blue Team)
certification: CEH (Certified Ethical Hacker) — Corvit, NAVTTC — Completed
also_studying: CCNP, Huawei (GNS3 / eNSP)
focus:         Detection Engineering → Alert Triage → Incident Response → Threat Hunting
philosophy:    A SIEM that fires 200 alerts/day and gets ignored is worse than one that fires 12
               and gets read. Every detection should map to a real technique, not just a log line.
```

<br>

## `~/lab-infrastructure`

Everything below runs in an isolated, host-only virtualized lab — attacks simulated from Kali, observed and triaged through the SOC stack, never against anything I don't own or have authorization for.

| Layer | Stack |
|---|---|
| **Virtualization** | VMware Workstation, EVE-NG, GNS3, Cisco Packet Tracer |
| **Attack simulation** | Kali Linux (used to generate realistic telemetry, not for its own sake) |
| **Targets / victims** | Metasploitable 2, Windows 10/11 VMs, Cisco 3640 (GNS3) |
| **SIEM / Detection stack** | Wazuh (Manager, Indexer, Dashboard) + Sysmon + custom Sigma rules |
| **Networking gear (virtual)** | Cisco routers/switches (IOS), HSRP/VRRP/GLBP labs |

<br>

## `~/skills`

![Detection](https://img.shields.io/badge/Detection_Engineering-SIEM_Tuning_|_Sigma_Rules_|_Alert_Triage-161b22?style=for-the-badge&logo=elastic&logoColor=00ff41&labelColor=161b22)
![IR](https://img.shields.io/badge/Incident_Response-Case_Documentation_|_Escalation_|_Remediation-161b22?style=for-the-badge&logo=grafana&logoColor=00ff41&labelColor=161b22)
![MITRE](https://img.shields.io/badge/MITRE_ATT%26CK-Technique_Mapping_|_LOLBins_|_TTP_Analysis-161b22?style=for-the-badge&logo=mitre&logoColor=00ff41&labelColor=161b22)
![Forensics](https://img.shields.io/badge/Forensics-PCAP_Analysis_|_IOC_Extraction_|_Log_Correlation-161b22?style=for-the-badge&logo=wireshark&logoColor=00ff41&labelColor=161b22)
![Networking](https://img.shields.io/badge/Networking-Subnetting_|_VLANs_|_NAT_|_ACLs_|_OSPF/RIP/BGP-161b22?style=for-the-badge&logo=cisco&logoColor=00ff41&labelColor=161b22)
![OSINT](https://img.shields.io/badge/OSINT-Recon_|_Exposure_Mapping_|_Risk_Prioritization-161b22?style=for-the-badge&logo=shodan&logoColor=00ff41&labelColor=161b22)

**Tools:**

![Wazuh](https://img.shields.io/badge/Wazuh-161b22?style=flat-square&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMDBmZjQxIiBzdHJva2Utd2lkdGg9IjIuNSIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIj48cGF0aCBkPSJNMTIgMjJzOC00IDgtMTBWNWwtOC0zLTggM3Y3YzAgNiA4IDEwIDggMTB6Ij48L3BhdGg+PC9zdmc+Cg==)
![Suricata](https://img.shields.io/badge/Suricata-161b22?style=flat-square&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMDBmZjQxIiBzdHJva2Utd2lkdGg9IjIuNSIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIj48Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIxLjUiIGZpbGw9IiMwMGZmNDEiPjwvY2lyY2xlPjxwYXRoIGQ9Ik0xNi4yIDcuOGE2IDYgMCAwIDEgMCA4LjRNNy44IDcuOGE2IDYgMCAwIDAgMCA4LjRNMTkgNWExMCAxMCAwIDAgMSAwIDE0TTUgNWExMCAxMCAwIDAgMCAwIDE0Ij48L3BhdGg+PC9zdmc+Cg==)
![Wireshark](https://img.shields.io/badge/Wireshark-161b22?style=flat-square&logo=wireshark&logoColor=00ff41)
![Nmap](https://img.shields.io/badge/Nmap-161b22?style=flat-square&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMDBmZjQxIiBzdHJva2Utd2lkdGg9IjIuNSIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIj48Y2lyY2xlIGN4PSIxMSIgY3k9IjExIiByPSI3Ij48L2NpcmNsZT48bGluZSB4MT0iMjEiIHkxPSIyMSIgeDI9IjE2IiB5Mj0iMTYiPjwvbGluZT48L3N2Zz4K)
![Kali](https://img.shields.io/badge/Kali_Linux-161b22?style=flat-square&logo=kalilinux&logoColor=00ff41)

`Wazuh · Sysmon · Suricata · Sigma Rules · MITRE ATT&CK Navigator · Wireshark · Nmap · Nessus · Lynis · OSINT tooling (Aliens Eye, MailAccess, Subfinder/dnsenum/dnsrecon) · Ettercap`

<br>

## `~/evidence-portfolio`

> Documented blue-team work — detection, triage, and response, not just "SIEM installed."

```
[+] Incident Response Case Documentation
    Documented 3 end-to-end security incidents, each carried from attack simulation through
    Wazuh detection, MITRE ATT&CK technique mapping, ticket escalation, and remediation —
    modeling the full SOC Level 1 triage workflow a real analyst would run: alert → validate →
    classify severity → map to ATT&CK → escalate → close with remediation notes.

[+] SIEM Alert Tuning
    Reduced Wazuh alert volume by 94% (200 → 12 alerts/day) by tuning custom rules and decoder
    logic — while preserving true-positive detection rate. The point of tuning isn't fewer
    alerts for its own sake; it's making sure the 12 that fire are the 12 that matter, so
    analyst fatigue doesn't bury a real incident under noise.

[+] Custom Sigma Detection Rule
    Identified a coverage gap in the SIEM baseline for LOLBin (Living-off-the-Land Binary)
    execution — a technique that abuses legitimate OS binaries to evade signature-based
    detection — and wrote a custom Sigma rule to close it, extending detection beyond
    out-of-the-box coverage.

[+] OSINT Risk Assessment
    Converted raw OSINT reconnaissance findings into a risk-prioritized exposure report,
    mapping each finding to exploitability and business impact rather than just listing
    what was found — turning recon data into something a security team can actually act on.

[+] Network Traffic Forensic Analysis
    Correlated SIEM alerts with raw packet captures (PCAP) to validate detections and extract
    indicators of compromise (IOCs), closing the loop between "the SIEM fired" and "here's the
    actual evidence proving what happened on the wire."

[+] Supporting Case: Malware Delivery + C2 Investigation (PCAP)
    Victim requested /update.exe x4 over HTTP:8000 → outbound TCP:4444 to a C2 host.
    ~566KB transferred in <1s post-handshake, ~67s sustained bidirectional session — a pattern
    consistent with a staged Meterpreter payload and interactive C2. Flags used to build the
    case: PE-over-HTTP, non-standard port, staged transfer, plaintext C2 channel.

[+] Nessus / Wireshark — Windows Network Scan Analysis
    15,621 packets / ~16 min capture | ~623 TCP ports probed via SYN scan
    SMB/RPC enumeration (LSA, SAMR, share enum) + default SNMP "public" string found
    Correctly distinguished recon/enumeration activity from actual exploitation — a core
    triage skill: not every scan hit is an incident.

[+] Lynis — Linux Security Audit (Kali)
    269 tests | Hardening index: 60/100 | 1 warning, 49 suggestions
    Findings: inactive firewall/IDS, fail2ban gap, GRUB & PAM hardening opportunities

[+] Metasploitable 2 — Nessus Vulnerability Assessment
    436 findings | 28 Critical · 99 High · 148 Medium · 20 Low · 141 Info
    Used as the baseline "known-vulnerable" environment against which detections were later
    built and validated — understanding what's exploitable is what makes the detection side
    meaningful instead of guesswork.
```

<br>

## `~/detection-engineering-workflow`

The core loop this profile is built around — going from "SIEM installed" to an analyst who actually reduces noise and closes cases.

- **Wazuh** deployed: Manager / Indexer / Dashboard, with Windows + Kali agents reporting in
- **Sysmon** configured on Windows, `Microsoft-Windows-Sysmon/Operational` feeding into Wazuh telemetry
- Workflow: simulate attack in the Kali lab → observe endpoint/network telemetry → tune Wazuh rules/decoders → validate true-positive rate → write custom Sigma rules for coverage gaps → document as a full IR case with ATT&CK mapping

**Actively building toward:** more custom Sigma rules across MITRE ATT&CK tactics (persistence, credential access, lateral movement), and a repeatable case-documentation template for every new lab.

<br>

## `~/cisco-networking`

Hands-on Cisco IOS labs, not just theory:

`IPv4/binary/subnetting` · `NAT (static + dynamic)` · `Standard & Extended ACLs` · `VLANs + inter-VLAN routing` · `RIP/OSPF/EIGRP/BGP concepts` · `HSRP/VRRP/GLBP failover labs` · `STP/BPDU & switching loops` · `DHCP` · `Wireless/WLC concepts`

<br>

## `~/currently`

```diff
+ CEH (Certified Ethical Hacker) — Completed, Corvit
+ Learning CCNP + Huawei configuration (GNS3 / eNSP)
+ Writing more custom Sigma rules to close detection gaps across ATT&CK tactics
+ Preparing for SOC Analyst L1 / Blue Team roles
```

<br>

<div align="center">

`Everything above was performed in isolated, authorized lab environments — Metasploitable2, self-hosted VMs, and virtual network topologies. No unauthorized targets.`

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:00ff41,100:0d1117&height=100&section=footer)

</div>
