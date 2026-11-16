---
title: "Cybersecurity Newsfeed - 16/11/26"
date: 2026-11-15 09:00:00 -0300
categories: [News]
permalink: /posts/news-16-11-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware, ai-security]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, AI security, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-11-16.png
  alt: Cybersecurity Newsfeed - 16/11/26
---

# Cybersecurity Newsfeed

## 📅 16/11/26

## 🛡️ Vulnerabilities

- **UnrealIRCd Command Injection (CVE-2026-114713)**: Threat actors are actively exploiting a critical flaw in UnrealIRCd versions prior to 6.2.7.1 and EOL version 5 releases. Residing in the labeled-response module, the bug allows unauthenticated remote attackers to inject server-to-server commands with IRCOp authority on linked networks. Administrators are urged to upgrade to 6.2.7.1 or apply the emergency hot-patch immediately. [More info](https://www.cysecurity.news/2026/11/attackers-exploit-critical-unrealircd.html)

- **N-able N-central "Able2Shell" Zero-Days**: Attackers are actively exploiting a wave of 33 publicly disclosed flaws in N-able N-central RMM software, chaining XXE, OGNL injection, and path traversal bugs for root RCE and cryptomining. Follow-up chains like 4EverAble2Shell target exposed Legacy APIs to bypass initial fixes. N-able released Hotfix 2 patching seven critical CVEs—including CVE-2026-125882 and CVE-2026-125883—with Hotfix 3 incoming to disable the Legacy API. [More info](https://www.cysecurity.news/2026/11/hackers-exploit-new-n-able-n-central.html)

- **CISA Adds UnrealIRCd and Check Point Flaws to KEV**: Under Binding Operational Directive 26-04, CISA added two actively exploited flaws to its KEV catalog: UnrealIRCd delimiter neutralization (CVE-2026-114713) and Check Point DynamicCLI privilege escalation to root (CVE-2026-123039). Federal agencies must remediate both flaws rapidly, and all organizations are urged to prioritize patching public-facing assets. [More info](https://www.cisa.gov/news-events/alerts/2026/11/13/cisa-adds-two-known-exploited-vulnerabilities-catalog)

- **Mior and Skyfall Attacks on AMD SEV-SNP**: ETH Zurich and Google researchers disclosed two hardware-level attacks—Mior (CVE-2026-0462) and Skyfall (CVE-2026-40671, CVE-2026-18448)—allowing rogue cloud hypervisors to compromise AMD EPYC confidential VMs. Mior leaves the Reverse Map Table uninitialized to read or alter encrypted memory, while Skyfall leaks cached CPU registers and encryption keys during failed startups. Cloud providers must deploy updated AMD firmware and microcode mitigations. [More info](https://thehackernews.com/2026/11/new-mior-and-skyfall-attacks-let-rogue.html)

- **Critical Apache HTTP/2 Race Condition (CVE-2026-119618)**: Apache released HTTP Server 2.4.71 to patch a CVSS 9.8 race condition in `mod_http2` affecting versions 2.4.55 through 2.4.70. With public PoC exploit code circulating, the heap memory corruption flaw enables unauthenticated remote code execution on servers with HTTP/2 enabled. Administrators should upgrade immediately or temporarily disable HTTP/2. [More info](https://www.cysecurity.news/2026/11/apache-http2-security-flaw-exposes.html)

- **Emergency Google Chrome Update Fixes 83 Flaws**: Google pushed its second emergency desktop security update within two days (versions 157.0.8103.78/.79), patching 83 vulnerabilities including five Critical use-after-free memory corruption bugs. Users are advised to manually check for updates and relaunch Chrome rather than waiting for automatic rollouts. [More info](https://www.malwarebytes.com/blog/bugs/2026/11/google-pushes-second-chrome-update-this-week)

- **Citrix Patches 10 Critical NetScaler Vulnerabilities**: Citrix released updates addressing 28 flaws across NetScaler ADC, Gateway, and Console. Nine critical ADC/Gateway memory overflow flaws risk denial-of-service, while CVE-2026-120869 (CVSS 9.4) enables unauthenticated access control bypass in NetScaler Console 14.1 prior to 14.1-74.34. Citrix urged immediate upgrades despite no confirmed wild exploitation. [More info](https://www.securityweek.com/citrix-patches-10-critical-netscaler-vulnerabilities/)

## 🎯 Adversaries

- **FBI Warns of AI-Powered ARTEX Attack Framework**: An FBI FLASH advisory warns that threat actors—including China-state-aligned groups Storm-0940 and Vapor Panda—are weaponizing ARTEX, an open-source Go-based autonomous pentesting tool powered by external LLMs. Since August 2026, attackers have compromised financial, defense, healthcare, and government targets from reconnaissance to privileged access in under three hours, with over 1,600 consoles still exposed via forks. [More info](https://www.bleepingcomputer.com/news/security/fbi-warns-artex-ai-hacking-tool-is-powering-global-cyberattacks/)

- **ArcticRAT 2.0 Integrates Grok AI to Profile Victim Finances**: Zimperium researchers revealed that the Android crypto stealer ArcticRAT has evolved into a full RAT leveraging xAI's Grok LLM. Distributed via malvertising and smishing, it hides remote control behind a black screen overlay and uses the Grok API to analyze stolen SMS messages and banking apps to estimate victim net worth before exfiltrating data. [More info](https://www.darkreading.com/mobile-security/arcticrat-cybercrime-gang-profiles-victim-finances-ai)

- **Check Point Gateways Hacked to Deploy ESXi Wiper**: Attackers chained PHP2Shell RCE flaws (CVE-2026-109618, CVE-2026-109619) with a DynamicCLI zero-day (CVE-2026-123039) to gain root access on Check Point Mobile Access portals starting October 30. In attacks targeting Israeli organizations, intruders deployed webshells and the TSGA backdoor before pivoting to internal VMware ESXi hosts to deploy the destructive `destroy_v6` wiper. [More info](https://www.bleepingcomputer.com/news/security/check-point-gateways-hacked-via-php2shell-to-deploy-vmware-esxi-wiper/)

- **Fake GTA VI Downloads Spread WARDEN Stealer**: Cynet uncovered a campaign abusing Google Colab notebooks to lure victims seeking a non-existent PC release of Grand Theft Auto VI to a fake "Windows Software Hub." The site delivers a WARDEN Stealer loader that instructs users to disable antivirus and run as administrator, harvesting passwords, Steam/Roblox logins, and crypto wallets. [More info](https://www.helpnetsecurity.com/2026/11/13/fake-gta-6-download-scam/)

- **Macfinger ClickFix Campaign Delivers DownTheDRAIN**: SANS ISC analyzed a November 11 sample from the Macfinger ClickFix campaign using a fake CAPTCHA page to trick macOS users into running malicious Terminal commands. The script downloads a 35MB ARM64 Mach-O infostealer dubbed DownTheDRAIN to hijack crypto wallet funds, though macOS 26.7.3 successfully blocked the payload and moved it to Trash. [More info](https://isc.sans.edu/diary/rss/33518)

## 💥 Breaches & Leaks

- **TSMC Employee Data Exposed via Cloud Vendor**: TSMC confirmed a breach of current and former employee data after threat actor "SmithBianl" auctioned 46,000 records (6.9GB) containing national IDs, addresses, and banking details for 3 BTC. TSMC stated its internal systems and customer operations remain uncompromised, attributing the leak to an external cloud service provider. [More info](https://www.bleepingcomputer.com/news/security/tsmc-employee-data-breach-linked-to-cloud-provider/)

- **Fireworks AI Breach Leads to Trojanized Claude Code Extension**: A breach at Fireworks AI exposed an access key to storage containing 2025 Cursor coding agent traces without Privacy Mode enabled. Attackers harvested unredacted API keys to breach Cursor's internal tools and publish trojanized versions (2.1.312 and 2.1.313) of Anthropic's Claude Code extension, attempting to deploy SSH backdoors on up to 5,000 users before removal. [More info](https://thehackernews.com/2026/11/stolen-fireworks-ai-key-led-to-cursor.html)

## 🤖 AI Security & Trends

- **360 Netlab Weekly AI Security Report**: Report TIC-202611-AI02 details 12 AI security incidents from November 7–13, including an SGLang RCE breach at NEAR AI, active exploitation of GPUStack flaw CVE-2026-102895, a critical Azure OpenAI privilege escalation bug (CVE-2026-119990), VS Code MCP vulnerabilities, and unauthenticated exposure across 35,578 Grok-generated applications. [More info](https://blog.netlab.360.com/aian-quan-zhuan-ti-zhou-bao-20261113/)

- **Enterprise AI Agent Adoption Drives Specialized Security Hiring**: Rapid enterprise deployment of autonomous AI agents via APIs and MCP servers is fueling demand for five core security roles: AI red teaming, defensive AI security engineering, model evaluation, regulatory governance, and SOC detection. Teams rely on OWASP Top 10 for LLMs, MITRE ATLAS, and NIST AI RMF to secure non-human identities and trust boundaries. [More info](https://hackread.com/security-jobs-growing-around-enterprise-ai-agents/)

## 📚 Others

- **Detecting GNSS Spoofing and Jamming in RTK Positioning**: Because Real-Time Kinematic (RTK) positioning systems rely on unauthenticated satellite signals alongside NTRIP correction streams, field operations face risks from radio jamming and coordinate-altering GNSS spoofing. Teams are advised to monitor for sudden position jumps or clock shifts, verify coordinates against physical control points, and use optical fallbacks. [More info](https://hackread.com/gnss-spoofing-jamming-rtk-positioning-teams-spot/)

---

[⬅ Back to Archive](https://pranakn.github.io)
