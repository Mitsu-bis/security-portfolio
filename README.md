<div align="center">

# Skyler M. — Security Portfolio

**IT Infrastructure & Security Engineer** · Offensive security · Detection engineering · Vendor risk
USMC veteran · Sole IT & security owner for a ~200-user firm across 23 states · Top 2% on TryHackMe

[LinkedIn](https://www.linkedin.com/in/skyler-mays-11b691184/) · [GitHub @Mitsu-bis](https://github.com/Mitsu-bis) · [HackerOne](https://hackerone.com/mitsu-bis?type=user) · [TryHackMe](https://tryhackme.com/p/Mitsubish) · [Resume](resume/)

</div>

---

I'm a USMC veteran and the primary IT infrastructure and security owner for a ~200-user
construction firm operating across 23 states, so I defend a real, live environment every day
rather than a lab. My work spans offensive security, detection engineering, and vendor risk,
and I rank in the top 2% on TryHackMe. I'm building toward my own security consulting
practice. The principle that runs through everything here is simple: I test only what I'm
authorized to, scope my work carefully, and disclose responsibly.

> This repository is my working portfolio — original findings, lab write-ups, methodology
> notes, and the tooling I build. Findings against third-party systems are published **only
> after responsible disclosure and remediation**, and are sanitized of any live data.

---

## Focus Areas

| | |
|---|---|
| **Offensive security** | Web app & authentication testing — enumeration, access control, session handling |
| **Windows / Active Directory** | Endpoint security, AD attack paths, privilege escalation |
| **Detection engineering** | Security monitoring, alerting, telemetry |
| **Vendor / third-party risk** | Disclosure-program maturity, security posture assessment |
| **Physical & social engineering** | Physical intrusion testing, social-engineering assessment |
| **Research & tooling** | Home-lab-driven research and purpose-built security tools |

---

## Tooling & Projects

*Things I've built and run.*

### StrikeOps — PenTest Command Center

A purpose-built command center for running professional penetration-testing engagements end
to end — a single local cockpit driving the full lifecycle (Recon → Enumeration →
Exploitation → Reporting), with evidence capture, MITRE ATT&CK mapping, CVSS 3.1 scoring, a
findings-driven relevance engine, an attack-chain builder, and one-click client-ready report
export. Runs fully local, OPSEC-conscious by design.

**[View the StrikeOps showcase →](https://github.com/Mitsu-bis/strikeops-showcase)**

| Project | Description | Link |
|---|---|---|
| **StrikeOps** | Local pentest engagement command center — methodology, evidence, reporting | [Showcase](https://github.com/Mitsu-bis/strikeops-showcase) |
| **Home lab** | Windows/AD + Linux target range used to validate techniques and detections | *(write-up planned)* |

---

## Original Findings & Responsible Disclosures

*Real-world findings discovered in authorized contexts, validated within scope, and disclosed
responsibly. Published after remediation only.*

| Finding | Class | Severity | Status | Write-up |
|---|---|---|---|---|
| Account enumeration via password reset — construction-safety SaaS | CWE-204 | Low–Moderate | Reported; awaiting remediation | *(pending disclosure — link when cleared)* |

> Each disclosure follows a consistent structure: Summary · Discovery Context · Scope &
> Authorization · Methodology · Impact & Severity · Disclosure Timeline. More will be added
> here as they are reported and resolved.

---

## Labs & CTF Write-Ups

*Documented exploitation and methodology from training platforms and CTFs. These are
guided / known-vulnerability exercises — included to demonstrate documentation, tooling, and
process, not original research.*

| Write-up | Platform | Focus | Link |
|---|---|---|---|
| **EternalBlue (CVE-2017-0144) — SMBv1 RCE** | TryHackMe | Windows SMB remote code execution: recon → exploitation → post-exploitation → looting, fully screenshotted | **[Read →](writeups/eternalblue-cve-2017-0144/)** |

---

## Methodology & Notes

*Process-focused write-ups that show how I approach a problem, independent of any single target.*

| Note | Topic | Status |
|---|---|---|
| Validating an authentication finding safely | Controlled testing, scoping, ruling out confounders | *(planned)* |
| Vendor disclosure maturity: bounty vs VDP vs security.txt | Third-party risk framing | *(planned)* |

---

### A note on scope & ethics

Every finding here was discovered in a context I was authorized to assess — systems I
administer, platforms that authorize testing, or training environments built for it —
validated only against assets in scope, and, where a third party is involved, disclosed
responsibly before publication. Nothing here was obtained by testing systems I had no
authorization to touch.
