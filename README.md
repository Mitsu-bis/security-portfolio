# Skyler M. — Security Portfolio

IT Infrastructure & Security Engineer | Offensive security, detection, and vendor risk.
USMC veteran. Focused on practical, responsibly-handled security work.

> A collection of write-ups, lab notes, and tooling. Findings against third-party
> systems are published **only after responsible disclosure and remediation**, and are
> sanitized of any live data.

**Contact:** [Email-Skylerm@gconinc.com](mailto:skylerm@gconinc.com)· [LinkedIn](https://www.linkedin.com/in/skyler-mays-11b691184/) · [GitHub (@Mitsu-bis)](https://github.com/Mitsu-bis)

**Platforms:** [HackerOne](https://hackerone.com/mitsu-bis?type=user) · [TryHackMe](https://tryhackme.com/p/Mitsubish)

---

## Focus Areas

- Web application & authentication testing (enumeration, access control, session handling)
- Windows / Active Directory and endpoint security
- Detection engineering & security monitoring
- Third-party / vendor risk assessment
- Home-lab-driven research and tooling

---

## Original Findings & Responsible Disclosures

*Real-world findings discovered in authorized contexts, validated within scope, and disclosed
responsibly. Published after remediation only.*

| Finding | Class | Severity | Status | Write-up |
|---|---|---|---|---|
| Account enumeration via password reset — construction-safety SaaS | CWE-204 | Low–Moderate | Reported; awaiting remediation | *(pending disclosure — link when cleared)* |

> Additional disclosures will be added here as they are reported and resolved. Each follows a
> consistent structure: Summary · Discovery Context · Scope & Authorization · Methodology ·
> Impact & Severity · Disclosure Timeline.

---

## Labs & CTF Write-Ups

*Documented exploitation and methodology from training platforms (TryHackMe, HackTheBox) and
CTFs. These are guided/known-vulnerability exercises — included to demonstrate documentation,
tooling, and process, not original research.*

| Write-up | Platform | Focus | Link |
|---|---|---|---|
| EternalBlue (CVE-2017-0144) — SMBv1 RCE | TryHackMe | Windows SMB remote code execution; exploitation & documentation | [Repo](https://github.com/Mitsu-bis/Eternal-Blue-CVE-2017-0144-THM-Write-Up) |

---

## Methodology & Notes

*Process-focused write-ups that show how I approach a problem, independent of any single target.*

| Note | Topic | Link |
|---|---|---|
| Validating an authentication finding safely | Controlled testing, scoping, ruling out confounders | *(planned)* |
| Vendor disclosure maturity: bounty vs VDP vs security.txt | Third-party risk assessment framing | *(planned)* |

---

## Tooling & Projects

*Things I've built or run. Link to repos where public; describe where not.*

| Project | Description | Link |
|---|---|---|
| Home lab | [Hardware/software stack, what it's used to test] | *(describe / link)* |
| [Pentest command center / Strike Ops] | [Short description] | *(describe / link)* |

---

## About

I'm a USMC veteran and the primary IT infrastructure and security owner for a ~200-user construction firm operating across 23 states, so I defend a real, live environment every day rather than a lab.
My focus is offensive security, detection, and vendor risk, and I rank in the top 2% on TryHackMe.
I'm building toward my own security consulting practice, and the principle that runs through everything here is simple; I test only what I'm authorized to, scope my work carefully, and disclose responsibly.

---

### A note on scope & ethics

Every finding here was discovered in a context I was authorized to assess (systems I administer,
platforms that authorize testing, or training environments built for it), validated only against
assets in scope, and — where a third party is involved — disclosed responsibly before
publication. Nothing here was obtained by testing systems I had no authorization to touch.
