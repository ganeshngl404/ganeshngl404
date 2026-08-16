# SOC Portfolio Evidence Map

This document explains what each public repository proves and what evidence can be discussed in an interview.

## Evidence Principles

- No private credentials, tokens, hostnames, or personal lab secrets are published.
- Raw logs are sanitized or synthetic when needed.
- The portfolio is written to demonstrate analyst thinking, not to exaggerate experience.
- Each project includes enough structure for an interviewer to review the workflow.

## Project Evidence Matrix

| Repository | Evidence Included | Interview Story |
| --- | --- | --- |
| `soc-splunk-apache-log-analysis-lab` | SPL searches, sanitized Apache logs, detections, triage playbook, final report | “I built an Apache/Splunk lab and investigated scanning, suspicious paths, and HTTP error bursts.” |
| `siem-detection-engineering-lab` | YAML detection catalog, triage steps, tuning notes, validator script | “I can turn suspicious behavior into alert logic and think about false positives.” |
| `windows-event-threat-hunting-lab` | Windows hunting queries, sample event CSV, report, triage playbook | “I can hunt endpoint logs for failed logons, PowerShell behavior, and privilege changes.” |
| `phishing-email-triage-playbook` | Email triage workflow, IOC register, ticket template, sample case report | “I can handle a user-reported phishing case and document impact.” |
| `network-incident-response-casebook` | Incident case timeline, network IR playbook, detection ideas, report template | “I can investigate suspicious network traffic and write containment actions.” |
| `CYBER-SECURITY-TASKS` | Nmap learning task and reconnaissance notes | “This shows my early practical security learning path.” |

## Suggested Evidence To Add Later

These can make the portfolio even stronger after careful sanitization:

1. Splunk dashboard screenshots with private fields blurred.
2. VirtualBox lab architecture screenshot without local usernames.
3. Apache log ingestion screenshot showing index and sourcetype.
4. Windows Event Viewer screenshots from a lab VM.
5. A short `demo.md` walkthrough for each repository.

## What To Avoid Publishing

- Real credentials or `.env` files.
- Real public IPs from personal networks.
- Full VM exports.
- Unredacted screenshots showing usernames, hostnames, or private directories.
- Any exploit code pointed at real third-party systems.

