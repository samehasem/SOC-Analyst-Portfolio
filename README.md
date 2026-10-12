# SOC Analyst Portfolio | Blue Team & Detection

> Entry-level cybersecurity portfolio focused on security monitoring, log analysis, SIEM detections, phishing analysis, network traffic analysis, and incident response.

**Owner:** `[Sameh Asem]`  
**Location:** `[City, cairo]`  
**Email:** `[samehasem2003@gmail.com]`  
**LinkedIn:** `[https://www.linkedin.com/in/sameh-asem-nada]`  
**GitHub:** `[https://github.com/samehasem/SOC-Analyst-Portfolio/edit/main/README.md]`

## About

I am building practical skills for an entry-level **SOC Analyst / Blue Team** role. This portfolio documents hands-on labs, investigations, detection logic, and lessons learned. The projects are designed for a home lab or authorized training environment; they are not claims of professional incident-response experience.

## Focus Areas

- Windows Event Logs and Sysmon
- SIEM investigation and SPL fundamentals
- Alert triage and evidence-based analysis
- Phishing email and authentication-header analysis (SPF, DKIM, DMARC)
- Network traffic analysis with Wireshark / tcpdump
- Active Directory security monitoring
- Incident response documentation and reporting
- Mapping observations to MITRE ATT&CK where appropriate

> Keep only the skills and tools you have actually practiced. Update each project status honestly (`Planned`, `In Progress`, or `Completed`).

## Projects

| Project | What it demonstrates | Status |
|---|---|---|
| [01 — Windows Event Log Analysis](projects/01-windows-event-log-analysis/README.md) | Investigating logon activity, account changes, and suspicious Windows events | Planned |
| [02 — Splunk Detection & Triage](projects/02-splunk-detection/README.md) | Writing SPL searches, summarizing alerts, and documenting detection limitations | Planned |
| [03 — Phishing Email Analysis](projects/03-phishing-email-analysis/README.md) | Reviewing email headers, URLs, sender identity, and SPF/DKIM/DMARC results | Planned |
| [04 — Wireshark Network Analysis](projects/04-wireshark-network-analysis/README.md) | Inspecting DNS, TCP, HTTP(S) metadata, and unusual traffic patterns | Planned |
| [05 — Active Directory Monitoring](projects/05-active-directory-monitoring/README.md) | Monitoring account creation, privileged-group changes, and authentication events | Planned |
| [06 — Incident Response Playbook](projects/06-incident-response-playbook/README.md) | Triage, containment planning, evidence handling, and lessons learned | Planned |

## How I Document a Project

Each project should include:

1. **Objective and scope** — what question the investigation answers, and which systems/data are in scope.
2. **Lab setup** — OS, tools, versions where relevant, and the data source.
3. **Methodology** — reproducible steps and queries/filters used.
4. **Evidence** — sanitized screenshots, short log excerpts, query output, or diagrams.
5. **Findings** — only what the evidence supports; distinguish facts from hypotheses.
6. **MITRE ATT&CK mapping** — include only when justified by observed behavior.
7. **Limitations and false positives** — explain what the analysis cannot prove.
8. **Recommendations and lessons learned**.

## Suggested Learning References

- [Microsoft Learn — Windows security auditing](https://learn.microsoft.com/en-us/windows/security/threat-protection/auditing/basic-audit-logon-events)
- [Microsoft Learn — Sysmon](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon)
- [Splunk Search Tutorial](https://docs.splunk.com/Documentation/Splunk/latest/SearchTutorial/WelcometotheSearchTutorial)
- [Wireshark User’s Guide](https://www.wireshark.org/docs/wsug_html_chunked/)
- [MITRE ATT&CK](https://attack.mitre.org/)
- [NIST Computer Security Incident Handling Guide (SP 800-61 Rev. 2)](https://csrc.nist.gov/pubs/sp/800/61/r2/final)

## Current Learning Goals

- [ ] Complete one Windows Event Log investigation and publish sanitized evidence.
- [ ] Build and test at least three SPL searches on sample or lab data.
- [ ] Write a phishing analysis report using a benign training sample.
- [ ] Publish one Wireshark investigation with screenshots and filters.
- [ ] Document one Active Directory security-monitoring lab.
- [ ] Update the CV with only completed, defensible project work.

## Responsible Use

All work is performed on systems I own or have explicit permission to test, or on authorized training platforms. I do not publish passwords, tokens, private IP details from a real organization, personal data, live malicious attachments, or confidential logs.
