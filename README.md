<p align="center">
  <img src="header.svg" alt="deviannt — Offensive Security Engineer" width="100%"/>
</p>

<br/>

```
Offensive Security Engineer — vulnerability research, reverse engineering, exploit development.
I document the full path: from the first wrong hypothesis to the working PoC.
Santiago, Chile · me@deviannt.com
```

---

## CVEs

| ID | Severity | Summary |
|----|----------|---------|
| [CVE-2025-55182](https://www.cve.org/CVERecord?id=CVE-2025-55182) | **CVSS 10.0 — Critical** | RCE in React Server Components via prototype pollution in the Flight protocol. Unauthenticated, single-request, deterministic. |
| [CVE-2024-30051](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2024-30051) | CVSS 7.8 — High | Windows DWM heap overflow → SYSTEM-level code execution. Empirical heap spray analysis across 50 sessions: 12.9×–19× more deterministic than the theoretical model. |
| [CVE-2024-51324](https://www.cve.org/CVERecord?id=CVE-2024-51324) | CVSS 9.5 — Critical | BYOVD via BdApiUtil64.sys. Reverse engineering uncovered three undocumented kernel primitives — including one capable of neutralizing an EDR without touching its process. |
| CVE-2021-4034 (PwnKit) | CVSS 7.8 — High | Linux local privilege escalation — full exploit framework. |

---

## Research

**MSc Thesis — "Analysis, Management and Exploit Development for N-Day Vulnerabilities and Threats"**  
Grade: 100/100 · UCAM + Campus Internacional de Ciberseguridad · 2025

Original exploit development beyond existing public PoCs for four CVEs spanning: modern web applications, Linux kernel, Windows desktop, and Windows kernel drivers.

---

## Tools

- **[react2shell](https://github.com/devianntsec/CVE-2025-55182)** — Multi-payload exploit framework for CVE-2025-55182. Vectors: RCE, interactive reverse shell, exfiltration, defacement, shutdown, integrity bypass.

---

## Stack

```
Languages     Python · C · JavaScript / TypeScript · PHP
RE            Ghidra · WinDbg · BinDiff · x64dbg
Web           Burp Suite · Kali Linux
Platforms     Windows kernel · Linux kernel · Node.js runtime
```

---

## Links

[deviannt.com](https://deviannt.com) · [blog.deviannt.com](https://blog.deviannt.com) · [links.deviannt.com](https://links.deviannt.com) · [@devianntsec](https://github.com/devianntsec)