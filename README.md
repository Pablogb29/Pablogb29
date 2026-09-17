`.

Assets in the profile repo root: `banner.png`, `htb-progress.svg`.

Profile settings (also updatable via API):

- Name: `Pablo Gutiérrez (M0k4)`
- Bio: `Cybersecurity Engineer · transitioning to pentesting · Brussels`
- Company: `Indra | Minsait Cyber`
- Website: `https://www.pabloinfosec.com`
- Pin: `HackTheBox` and `Webportfolio_2026`

Do not use relative image paths (`banner.png`) in HTML `<img>` tags — the profile page is `github.com/Pablogb29`, so they 404. Use `raw.githubusercontent.com`.

Do not use the official HTB badge image: it exposes the platform nickname and rank, not the professional name.

---

COPY FROM HERE

<div align="center">
  <img src="https://raw.githubusercontent.com/Pablogb29/Pablogb29/main/banner.png" alt="Pablo Gutiérrez — M0k4" width="100%" />
</div>

<h1 align="center">Pablo Gutiérrez</h1>

<p align="center">
  <strong>M0k4</strong> · Cybersecurity Engineer at <strong>Indra | Minsait Cyber</strong><br />
  IAM and security automation · transitioning to pentesting · Brussels
</p>

<p align="center">
  <a href="https://www.pabloinfosec.com"><img src="https://img.shields.io/badge/Portfolio-pabloinfosec.com-0A0A0A?style=for-the-badge&labelColor=7C3AED" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/pabloinfosec"><img src="https://img.shields.io/badge/LinkedIn-pabloinfosec-0A0A0A?style=for-the-badge&logo=linkedin&logoColor=A855F7&labelColor=7C3AED" alt="LinkedIn" /></a>
  <a href="https://github.com/Pablogb29/HackTheBox"><img src="https://img.shields.io/badge/HTB_writeups-HackTheBox-0A0A0A?style=for-the-badge&labelColor=7C3AED" alt="HTB write-ups" /></a>
  <a href="mailto:pabloinfosec@gmail.com"><img src="https://img.shields.io/badge/Email-pabloinfosec-0A0A0A?style=for-the-badge&logo=gmail&logoColor=A855F7&labelColor=7C3AED" alt="Email" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CJCA-Completed-7C3AED?style=flat-square" alt="CJCA completed" />
  <img src="https://img.shields.io/badge/CAST%20Permanent%20ICT-Successful%20Aug%202026-7C3AED?style=flat-square" alt="CAST Permanent ICT" />
  <img src="https://img.shields.io/badge/HTB-82%20machines-7C3AED?style=flat-square" alt="82 HTB machines" />
  <img src="https://img.shields.io/badge/Writeups-73-7C3AED?style=flat-square" alt="73 write-ups" />
  <img src="https://img.shields.io/badge/CPTS-5%20Nov%202026-7C3AED?style=flat-square" alt="CPTS 5 Nov 2026" />
  <img src="https://img.shields.io/badge/OSCP-Planned%202027-3F3F46?style=flat-square" alt="OSCP planned 2027" />
</p>

---

## Now

Cybersecurity engineer working on **identity, access governance, and security automation** at Minsait Cyber (Indra). Offensive practice is public: Hack The Box machines and OSCP-oriented write-ups under **M0k4**. Successful EPSO CAST Permanent candidate for **Information and Communication Technologies** — passed the reasoning tests; next phase is recruitment by EU institutions for ICT contract staff.

<table>
  <tr>
    <td width="50%" valign="top">

**This year**
- IAM / Databricks security at Minsait Cyber
- Custom permission graphing for Databricks (Neo4j / PyVis)
- HTB write-ups, OSCP-oriented, no flags
- CAST Permanent ICT — next recruitment phase

    </td>
    <td width="50%" valign="top">

**Next**
- CPTS exam · **5 Nov 2026**
- OSCP · **2027** (after CPTS)
- EU institutions · ICT contract staff
- More Active Directory attack-path write-ups

    </td>
  </tr>
</table>

> CAST Permanent — ICT (`EPSO/CAST/P/17/2017`). Reasoning tests passed in August 2026. This qualifies me for the next phase of recruitment, not for an automatic job offer.

---

## Practice

<div align="center">
  <img src="https://raw.githubusercontent.com/Pablogb29/Pablogb29/main/htb-progress.svg" alt="Hack The Box: 82 machines, 73 write-ups, Easy 64, Medium 16, Hard 2" width="840" />
</div>

Write-ups live in [Pablogb29/HackTheBox](https://github.com/Pablogb29/HackTheBox). Methodology, tooling, and mitigations — **no flags**.

| Machine | Level | Focus |
| --- | --- | --- |
| [Administrator](https://github.com/Pablogb29/HackTheBox/blob/main/Machines/MEDIUM/Administrator.md) | Medium | Windows / AD |
| [Certified](https://github.com/Pablogb29/HackTheBox/blob/main/Machines/MEDIUM/Certified/README.md) | Medium | Windows / AD |
| [Interpreter](https://github.com/Pablogb29/HackTheBox/blob/main/Machines/MEDIUM/Interpreter/README.md) | Medium | Linux |
| [EscapeTwo](https://github.com/Pablogb29/HackTheBox/blob/main/Machines/EASY/EscapeTwo/README.md) | Easy | Windows / AD |
| [Cicada](https://github.com/Pablogb29/HackTheBox/blob/main/Machines/EASY/Cicada/README.md) | Easy | Windows / AD |
| [Support](https://github.com/Pablogb29/HackTheBox/blob/main/Machines/EASY/Support/README.md) | Easy | Windows / AD |

---

## Path

```mermaid
flowchart LR
  A[IAM at Minsait Cyber] --> B[HTB 82 machines]
  B --> C[CJCA]
  C --> D[CPTS Nov 2026]
  D --> E[OSCP 2027]
  A --> F[CAST Permanent ICT]
```

| Credential | Status |
| --- | --- |
| CJCA — Hack The Box | Completed |
| CAST Permanent ICT — EPSO | Successful · Aug 2026 |
| CPTS — Hack The Box | Exam booked · 5 Nov 2026 |
| OSCP — Offensive Security | Planned · 2027 |

Education: MSc Cybersecurity (Deloitte / IMF) · MSc Artificial Intelligence (IUNIT) · BEng Electronic Telecommunications (UAB). Diplomas on [pabloinfosec.com](https://www.pabloinfosec.com).

---

## Stack I actually use

Not a tool dump — the stack that shows up in work and write-ups.

| Identity & cloud | Offensive practice | Engineering |
| --- | --- | --- |
| Azure IAM · Databricks SCIM | Linux / Windows internals | Python · SQL |
| AWS security · ENS / ISO 27001 | Active Directory · BloodHound | Bash · PowerShell |
| Neo4j + PyVis graphs | Nmap · Burp · AD attack paths | Git · Docker |

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,bash,powershell,linux,windows,docker,aws,azure,git,githubactions" alt="Python Bash PowerShell Linux Windows Docker AWS Azure Git" />
</p>

---

## GitHub

<div align="center">
  <img height="165" src="https://github-stats-extended.vercel.app/api?username=Pablogb29&show_icons=true&hide_rank=true&hide_border=true&bg_color=0A0A0A&title_color=A855F7&icon_color=A855F7&text_color=D1D5DB&ring_color=7C3AED" alt="GitHub stats" />
  <img height="165" src="https://github-stats-extended.vercel.app/api/top-langs/?username=Pablogb29&layout=compact&langs_count=6&hide_border=true&bg_color=0A0A0A&title_color=A855F7&text_color=D1D5DB" alt="Top languages" />
</div>

---

## Start here

1. [pabloinfosec.com](https://www.pabloinfosec.com) — role, experience, diplomas, CAST letter, CJCA
2. [HackTheBox write-ups](https://github.com/Pablogb29/HackTheBox) — methodology, no flags
3. [Web portfolio 2026](https://github.com/Pablogb29/Webportfolio_2026) — this site
4. [Hack The Box profile](https://app.hackthebox.com/users/1583498)
