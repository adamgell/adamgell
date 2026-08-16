<!-- Animated header banner (capsule-render) -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,100:2ea043&height=180&section=header&text=Adam%20Gell&fontSize=52&fontColor=ffffff&animation=fadeIn&desc=Endpoint%20management%2C%20Microsoft%20Graph%2C%20and%20tools%20that%20make%20both%20less%20painful&descSize=16&descAlignY=75" alt="banner" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/adamgell/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://cmtraceopen.com"><img src="https://img.shields.io/badge/cmtraceopen.com-1f6feb?style=for-the-badge&logo=rust&logoColor=white" alt="cmtraceopen" /></a>
  <a href="https://www.powershellgallery.com/profiles/adamgell"><img src="https://img.shields.io/badge/PSGallery-2ea043?style=for-the-badge&logo=powershell&logoColor=white" alt="PowerShell Gallery" /></a>
</p>

## 🧑‍💻 About me

```yaml
name: Adam Gell
pronouns: he/him
role: Endpoint Management Engineer
focus:
  - Microsoft Intune / Entra ID / Autopilot
  - Microsoft Graph automation (app-only, multi-tenant)
  - Windows deployment & troubleshooting tooling
languages: [PowerShell, Rust, Python, Terraform]
currently_building:
  - cmtraceopen   # cross-platform CMTrace replacement in Rust
  - GraphKit      # multi-tenant Graph execution layer for PowerShell
  - TenantPulse   # read-only Intune/Entra tenant health assessment
```

## 🛠️ Tools of the trade

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/powershell/powershell-original.svg" width="42" title="PowerShell" />&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" width="42" title="Rust" />&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="42" title="Python" />&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg" width="42" title="Terraform" />&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" width="42" title="Azure" />&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows11/windows11-original.svg" width="42" title="Windows" />&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tauri/tauri-original.svg" width="42" title="Tauri" />&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="42" title="Git" />
</p>

## 🚀 What I'm building

### [cmtraceopen](https://github.com/adamgell/cmtraceopen) — stop fighting your log viewer

[![Stars](https://img.shields.io/github/stars/adamgell/cmtraceopen?style=flat&logo=github)](https://github.com/adamgell/cmtraceopen/stargazers)
[![Release](https://img.shields.io/github/v/release/adamgell/cmtraceopen?style=flat)](https://github.com/adamgell/cmtraceopen/releases/latest)
[![Website](https://img.shields.io/badge/cmtraceopen.com-visit-1f6feb)](https://cmtraceopen.com)

The CMTrace replacement Windows admins have been waiting for — built in Rust, runs on **Windows, macOS, and Linux**. ConfigMgr/SCCM logs, Intune IME, Autopilot ESP diagnostics, DSRegCmd triage, `.evtx` viewing, real-time tailing, and built-in Windows error-code lookup. Free and open source, no MDT-era baggage.

**Get it:** download from [cmtraceopen.com](https://cmtraceopen.com) or the [latest release](https://github.com/adamgell/cmtraceopen/releases/latest).

### [GraphKit](https://github.com/adamgell/GraphKit) — Microsoft Graph at fleet scale

[![PSGallery](https://img.shields.io/powershellgallery/v/GraphKit?label=PSGallery)](https://www.powershellgallery.com/packages/GraphKit)
[![Downloads](https://img.shields.io/powershellgallery/dt/GraphKit)](https://www.powershellgallery.com/packages/GraphKit)
[![Stars](https://img.shields.io/github/stars/adamgell/GraphKit?style=flat&logo=github)](https://github.com/adamgell/GraphKit/stargazers)

Query Microsoft Graph across **many tenants at once** from PowerShell — certificate, secret, and managed-identity auth, throttling, retries, paging, and sanitized evidence export all handled for you. No `Connect-MgGraph`, no process-global SDK state leaking between tenants.

```powershell
Install-PSResource GraphKit
```

### [TenantPulse](https://github.com/adamgell/TenantPulse) — know your tenant's health score

[![PSGallery](https://img.shields.io/powershellgallery/v/TenantPulse?label=PSGallery)](https://www.powershellgallery.com/packages/TenantPulse)
[![Downloads](https://img.shields.io/powershellgallery/dt/TenantPulse)](https://www.powershellgallery.com/packages/TenantPulse)
[![Stars](https://img.shields.io/github/stars/adamgell/TenantPulse?style=flat&logo=github)](https://github.com/adamgell/TenantPulse/stargazers)

One command assesses your Intune/Entra tenant against a versioned check catalog and produces a **deterministic, pseudonymized, scored findings report**. Strictly read-only by construction — it never writes to your tenant.

```powershell
Install-PSResource TenantPulse
```

### More in the lab 🧪

- **[ProxmoxVEAutopilot](https://github.com/adamgell/ProxmoxVEAutopilot)** — turn one Proxmox node into a browser-managed Windows deployment platform: VM provisioning, OSDCloud media, Autopilot hash capture, zero guest network access needed.
- **[device-cleanup-automation](https://github.com/adamgell/device-cleanup-automation)** — Terraform-provisioned Azure Automation that retires stale devices safely: disable at 90 days, delete at 120, BitLocker/LAPS keys backed up first.

## 📊 GitHub stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=adamgell&theme=github_dark" height="180" alt="GitHub stats" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=adamgell&theme=github_dark" height="180" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=adamgell&theme=github-dark-blue&hide_border=true" height="170" alt="Contribution streak" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2ea043,100:1f6feb&height=100&section=footer" alt="footer" />
</p>
