---
title: "Cybersecurity Newsfeed - 19/06/26"
date: 2026-06-18 09:00:00 -0300
categories: [News]
permalink: /posts/news-19-06-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-06-19.png
  alt: Cybersecurity Newsfeed - 19/06/26
---

# Cybersecurity Newsfeed

## 📅 19/06/26

## 🛡️ Vulnerabilities

- **NGINX Open Source Remote Code Execution (CVE-2026-42530)**: F5 issued emergency out-of-band updates addressing a critical use-after-free condition inside the HTTP/3 QUIC module (`ngx_http_v3_module`). Unauthenticated remote attackers can send a crafted QPACK encoder stream request to execute arbitrary code or crash the service. [More info](https://thehackernews.com/2026/06/f5-patches-two-critical-nginx-open.html)

- **Splunk Enterprise Missing Authentication (CVE-2026-20253)**: CISA added a critical missing authentication flaw in Splunk Enterprise to its Known Exploited Vulnerabilities (KEV) catalog. The defect allows unauthenticated remote attackers to manipulate internal PostgreSQL sidecar service endpoints, leading to arbitrary file operations and full remote code execution. [More info](https://www.cisa.gov/news-events/alerts/2026/06/18/cisa-adds-one-known-exploited-vulnerability-catalog)

- **Cisco Identity Services Engine Privilege Escalation (CVE-2026-20181)**: Cisco patched a critical command execution flaw caused by insufficient input validation in its ISE and ISE Passive Identity Connector. Authenticated administrators can exploit this to send malicious HTTP requests, escalating privileges to full root authority. [More info](https://securityaffairs.com/193849/uncategorized/cisco-fixed-a-critical-ise-vulnerability-that-lets-attackers-to-gain-root-access.html)

- **Apple Beats Studio Buds Eavesdropping Flaw**: Apple resolved a significant Bluetooth logic vulnerability enabling proximate attackers to spoof previously paired source devices. This authentication weakness allows unauthorized connections that can force microphone streaming and covert audio manipulation. [More info](https://www.bleepingcomputer.com/news/security/apple-fixes-beats-studio-buds-flaw-that-let-hackers-spy-on-conversations/)

## 🎯 Adversaries

- **Gentlemen Ransomware deploys EDR Killers**: Run by threat group Storm-2697, this Go-based RaaS platform has integrated specialized Bring Your Own Vulnerable Driver (BYOVD) tactics using drivers like `ThrottleBlood.sys`. It disables event logs, security agents, and backups before executing hybrid XChaCha20 and Curve25519 encryption across Windows, Linux, and ESXi. [More info](https://www.bleepingcomputer.com/news/security/gentlemen-ransomware-uses-multiple-edr-killers-to-disable-defenses/)

- **Operation Endgame Dismantles Evil Corp Infrastructure**: Coordinated international law enforcement agencies seized 106 servers and cleaned roughly 15,000 infected websites linked to the SocGholish (FakeUpdates) botnet. The malware traditionally serves as an initial access vector sold to ransomware affiliates. [More info](https://cyberscoop.com/socgholish-malware-botnet-takedown-evilcorp/)

- **Operation Escaneo Targets Latin America**: Attributed to the Spanish-nexus group MexicanMafia, this campaign targets critical infrastructure and government bodies in Mexico and Ecuador using a proprietary reconnaissance engine called Kimera and edge-device exploits to maintain deep, long-dwell network access. [More info](https://www.darkreading.com/cybersecurity-operations/operation-escaneo-signals-shift-latam-threat-landscape)

- **Tor-Based Clipper Exploits USB Worm Propagation**: Microsoft Threat Intelligence tracked a stealthy clipper variant spreading via malicious shortcut files on removable USB storage. The malware hides real documents, uses Windows Script Host to launch a bundled Tor client, and intercepts system clipboards to hijack crypto transaction paths. [More info](https://securityaffairs.com/193860/uncategorized/tor-based-clipper-malware-targets-wallet-seed-phrases.html)

- **USB Worm Weaponizes Windows Shortcuts for Botnet Expansion**: Emerging crypto clipper campaigns deploy dual-component payloads consisting of an obfuscated worm executable and a JavaScript stealer. Running clipboards are checked every 500 milliseconds to exfiltrate seed phrases and replace target addresses. [More info](https://www.bleepingcomputer.com/news/security/usb-worm-spreads-crypto-stealing-malware-via-windows-shortcut-files/)

- **Rokarolla Banking Trojan Broadens Scope**: The emerging Rokarolla banking trojan expanded its credential harvesting framework to monitor over 200 financial, corporate, and cryptocurrency applications by hooking directly into running browser processes via malicious search ads. [More info](https://www.securityweek.com/rokarolla-banking-trojan-targets-200-applications/)

## 💥 Breaches & Leaks

- **Nintendo Employee Data Stolen via Subsidiary Breach**: Nintendo of North America confirmed internal employee satisfaction data was exposed after the ShadowByte$ group breached TinyPulse, a feedback platform owned by WebMD Health Services. The attackers have issued a two-million-dollar extortion demand. [More info](https://www.bleepingcomputer.com/news/security/nintendo-confirms-data-stolen-in-webmd-subsidiary-cyberattack/)

- **Salesforce Data-Harvesting Exploits Third-Party Integration**: Automated attacks targeted corporate Salesforce deployments by exploiting a legacy testing credential on market intelligence platform Klue. Attackers hijacked active OAuth refresh tokens to execute rapid REST API queries and exfiltrate customer databases. [More info](https://www.darkreading.com/cyberattacks-data-breaches/salesforce-data-thefts-klue-app-compromise)

- **Icarus Campaign Tied to Klue Backend Intrusions**: Further investigation reveals the Klue API breach is part of a wider extortion framework tracked as Icarus. Multiple corporate victims, including security firm Huntress, received extortion notices threatening the public release of data stolen via intercepted trust tokens. [More info](https://www.bleepingcomputer.com/news/security/klue-oauth-breach-linked-to-icarus-salesforce-data-theft-attacks/)

- **ShapedPlugin Build Pipeline Poisoned (CVE-2026-10735)**: A supply chain compromise impacted ShapedPlugin's Easy Digital Downloads update infrastructure, injecting multi-stage backdoors into premium packages. The malware harvests admin passwords and 2FA TOTP seeds by intercepting authentication logic. [More info](https://www.bleepingcomputer.com/news/security/shapedplugin-update-flow-hacked-to-infect-wordpress-sites/)

## 📈 Trends & Scams

- **2026 World Cup Public Anticipation Exploited**: Kaspersky researchers warned of a massive spike in social engineering operations using fake ticket lotteries, merchandise storefronts, and urgent messaging to harvest financial data ahead of the tournament. [More info](https://www.kaspersky.com/blog/world-cup-scam-2026/55986/)

- **Retro Gaming Enthusiasts Targeted on GitHub**: Trojanized open-source repositories posing as emulation utilities and classic game modifications are delivering information stealers designed to disable antivirus solutions and harvest local credentials, session cookies, and crypto wallets. [More info](https://www.malwarebytes.com/blog/threat-intel/2026/06/retro-gaming-fans-are-the-new-target-for-fake-github-malware)

- **Claude AI Shared Chat Features Abused for Malvertising**: Threat actors are using Anthropic's Claude platform to generate legitimate-seeming documentation and sharing the public links via malicious search ads. The trusted domain bypasses web reputation filters to direct targets to malware staging servers. [More info](https://www.trendmicro.com/en_us/research/26/f/claudeai-shared-chat-abused-in-malvertising.html)

- **"Agentjacking" Prompt Injections Hijack AI Code Assistants**: A new methodology targets autonomous development tools by embedding malicious prompt-engineered strings inside standard repository bug reports. When scanned by AI agents, the text overrides core instructions to execute arbitrary shell commands or exfiltrate variables. [More info](https://hackread.com/agentjacking-fake-bug-report-hijack-ai-coding-agents/)

## 🔬 Others

- **Leaked Documents Reveal "ChatGPT for Science" Testing**: An internal leak confirmed OpenAI is running a restricted beta for an academic-focused subscription tier. The model integrates specialized compliance frameworks alongside workflows tailored for handling massive data sets, molecular modeling, and math formulas. [More info](https://www.bleepingcomputer.com/news/artificial-intelligence/leak-confirms-openai-is-testing-a-chatgpt-for-science-subscription/)

---

[⬅ Back to Archive](https://pranakn.github.io)
