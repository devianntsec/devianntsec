<p align="center">
  <img src="header.svg" alt="deviannt — Offensive Security Engineer" width="100%"/>
</p>

<p align="center">
  <a href="https://github.com/devianntsec/CVE-2025-55182"><img src="https://img.shields.io/badge/CVE--2025--55182-CVSS%2010.0%20Critical-b91c1c?style=flat-square"/></a>
  <a href="https://blog.deviannt.com"><img src="https://img.shields.io/badge/CVE--2024--51324-CVSS%209.5%20Critical-b91c1c?style=flat-square"/></a>
  <a href="https://blog.deviannt.com"><img src="https://img.shields.io/badge/CVE--2021--4034-CVSS%207.8%20High-d97706?style=flat-square"/></a>
</p>

<p align="center">
Offensive Security Engineer — vulnerability research, reverse engineering, exploit development.<br/>
I document the full path: from the first wrong hypothesis to the working PoC.
</p>

---

## CVEs

| ID | Severity | Summary |
|----|----------|---------|
| [CVE-2025-55182](https://www.cve.org/CVERecord?id=CVE-2025-55182) | **CVSS 10.0 — Critical** | RCE in React Server Components via prototype pollution in the Flight protocol. Unauthenticated, single-request, deterministic. |
| [CVE-2024-51324](https://www.cve.org/CVERecord?id=CVE-2024-51324) | **CVSS 9.5 — Critical** | BYOVD via BdApiUtil64.sys. Three undocumented kernel primitives — including one capable of neutralizing an EDR without touching its process. |
| [CVE-2021-4034](https://www.cve.org/CVERecord?id=CVE-2021-4034) (PwnKit) | CVSS 7.8 — High | Linux local privilege escalation — full exploit framework. |

---

## Research

**MSc Thesis — "Analysis, Management and Exploit Development for N-Day Vulnerabilities and Threats"**  
Grade: 100/100 · UCAM + Campus Internacional de Ciberseguridad · 2025

Original exploit development beyond existing public PoCs across modern web, Linux kernel, Windows desktop, and Windows kernel drivers. Includes empirical heap spray analysis of CVE-2024-30051 across 50 sessions: 12.9×–19× more deterministic than the theoretical model.

---

## Tools

**[react2shell](https://github.com/devianntsec/CVE-2025-55182)** — Exploit framework for CVE-2025-55182. Vectors: RCE, reverse shell, exfiltration, defacement, shutdown, integrity bypass.

---

## Stack

```
Languages     Python · C · JavaScript / TypeScript · PHP
RE            Ghidra · WinDbg · BinDiff · x64dbg
Web           Burp Suite · Kali Linux
Platforms     Windows kernel · Linux kernel · Node.js runtime
```

---

[deviannt.com](https://deviannt.com) · [blog.deviannt.com](https://blog.deviannt.com) · [links.deviannt.com](https://links.deviannt.com) · [@devianntsec](https://github.com/devianntsec) · me@deviannt.com