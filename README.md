# Hi, I'm yamekuro 👋

**Security engineer · SOC / CSIRT · Detection engineering**

Every alert has a system behind it. Five years in IT infrastructure taught me how those systems behave when nothing is wrong. Now I build detections from real telemetry, test them with controlled attacks and publish what held up and what didn't.

Based in Spain, open to SOC and CSIRT roles across Europe.

---

### 🧱 Building: soc-homelab

A segmented SOC lab on a single workstation: an OPNsense firewall between six zones, Wazuh with Microsoft Sentinel and Splunk, phishing analysis, vulnerability management and an AI assistant that has to pass an evaluation before it acts. It is designed against eight ATT&CK scenarios, and each phase closes only when its exit gate is verified and its write-up is published. A parallel cloud track covers LLMjacking in AWS: stolen cloud credentials used to run paid AI models.

| Phase | Scope | Status |
|---|---|---|
| P0 | Foundation: hypervisor, firewall, zones, bastion | ✅ Complete · [write-up](https://github.com/yamekuro/soc-homelab/blob/main/writeups/p0-foundation.md) |
| P1 | Telemetry: Wazuh, Windows and Linux endpoints | 🔜 Next |
| P2 | First SOC case: detection, phishing, vulnerability scan, report | Planned |
| P3 | Identity and platforms: AD, Entra, Sentinel, Splunk | Planned |
| P4 | Network, hunting and automated response | Planned |
| P5 | AI assistant, evaluated before it acts | Planned |
| P6 | Capstone campaign and resilience | Planned |
| L | Parallel cloud track: AWS LLMjacking with CloudTrail, Bedrock logging and Sigma | Planned |

`VMware` · `OPNsense` · `Wazuh` · `Microsoft Sentinel` · `Splunk` · `AWS` · `Terraform` · `CloudTrail` · `Amazon Bedrock` · `Sigma` · `Stratus Red Team` · `MITRE ATT&CK`

### 🛠️ Technical focus

- **Systems & networks:** Linux and Windows, segmentation, firewalls, bastion access, hardening
- **Detection:** Wazuh, Sysmon, Sigma, Microsoft Sentinel, Splunk, cloud audit logs from Azure and AWS
- **Validation:** Atomic Red Team, Stratus Red Team, controlled attack simulation, detection validation

### 🌐 More

[Portfolio](https://yamekuro.github.io/)

---

*Build. Attack. Detect. Measure what you missed.*
