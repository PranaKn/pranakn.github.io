---
title: "Cybersecurity Newsfeed - 05/08/26"
date: 2026-08-04 09:00:00 -0300
categories: [News]
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-08-05.png
  alt: Cybersecurity Newsfeed - 05/08/26
---

# Cybersecurity Newsfeed

## 📅 05/08/26

## 🛡️ Vulnerabilities

- **CISA Adds Three Vulnerabilities to KEV Catalog**: CISA added three security flaws to its Known Exploited Vulnerabilities catalog following active exploitation. Additions include a code injection flaw in IBM Langflow (CVE-2026-9198), an authentication bypass in N-able N-central (CVE-2026-18556), and unencrypted sensitive data exposure in Apache Tomcat (CVE-2026-34486). Federal agencies must prioritize remediation per BOD 26-04. [More info](https://www.cisa.gov/news-events/alerts/2026/08/04/cisa-adds-three-known-exploited-vulnerabilities-catalog)

- **Critical cPanel/WHM Bug Allows Database Privilege Escalation (CVE-2026-58048)**: A critical flaw in cPanel and WHM (CVSS 9.4) allows authenticated database users to execute arbitrary SQL commands with full root administrative privileges. The issue stems from improper SQL mode handling during database renaming operations. Patches are available, and admins are advised to restrict MySQL management privileges if unable to patch immediately. [More info](https://securityaffairs.com/196595/security/cve-2026-58048-cpanel-bug-enables-full-database-administrator-access.html)

- **Pass-ta-key Attacks Hijack Google-Synced Passkeys on Windows**: Security researchers unveiled three attack methods, collectively named Pass-ta-key, allowing local malware to hijack Google-synced passkeys on Windows systems equipped with a TPM. Unprivileged malware can abuse Chrome's device identity key or extract master keys from process memory to bypass biometric checks and steal private passkeys. [More info](https://www.bleepingcomputer.com/news/security/new-pass-ta-key-attacks-let-malware-hijack-google-synced-passkeys/)

## 🎯 Adversaries

- **Lotus Wiper Targets Venezuelan Oil Giant PDVSA**: Researchers uncovered a destructive wiper family named Lotus Wiper targeting Petróleos de Venezuela S.A. (PDVSA). The attack uses Domain Controller environment guardrails, randomizes account credentials, clears volume journals, and zero-fills MBR/GPT structures to render victim hosts permanently unrecoverable. [More info](https://0x0d4y.blog/a-wiper-attack-on-a-venezuelan-oil-company-lotus-wiper-disrupts-pdvsa/)

- **XCSSET Variant v40 Targets macOS Devs via Xcode**: A new version of the XCSSET malware is targeting macOS developers by compromising Xcode projects and public Git repositories. The updated strain disables Gatekeeper and XProtect while deploying a Chrome DevTools traffic hijacker and a trojanized Telegram desktop client. [More info](https://www.bleepingcomputer.com/news/security/new-xcsset-variant-targets-macos-devs-via-compromised-xcode-projects/)

- **SMOKE#SCREEN Campaign Installs Fake ScreenConnect Updates**: A cyberespionage campaign dubbed SMOKE#SCREEN uses lures disguised as Adobe updates, Zoom installers, and business documents to deploy ConnectWise ScreenConnect. The attack chain bypasses AMSI and SmartScreen protections to establish persistent remote access. [More info](https://thehackernews.com/2026/08/fake-adobe-and-zoom-updates-install.html)

- **Midnight Blizzard Targets Hotel Wi-Fi Networks in CaptiveCrunch Campaign**: Russian state-sponsored actors compromised hotel and conference Wi-Fi networks to manipulate captive portals. Users were redirected to fake Microsoft 365 logins and ClickFix updates, deploying custom malware strains CornFlake (Go RAT) and ChocoShell (PowerShell stealer). [More info](https://www.helpnetsecurity.com/2026/08/04/midnight-blizzard-hotel-wi-fi-networks-hacking/)

## 📈 Trends

- **77 Malicious Extensions Found Harvesting Data on Open VSX**: Researchers discovered 77 "evil twin" developer extensions on the Open VSX marketplace impersonating tools from AMD, Azure, and Salesforce. While claiming to send anonymous usage metrics, 19 variants exfiltrated sensitive repository paths, CI identifiers, and developer credentials. [More info](https://www.bleepingcomputer.com/news/security/77-open-vsx-extensions-found-harvesting-developer-info/)

- **Massive ChainDrop NPM Attack Infects Over 1,300 Packages**: A supply-chain campaign named ChainDrop compromised over 1,300 npm packages (including Keyv and Cacheable) using a hijacked maintainer GitHub account. Preinstall hooks execute the Bun JavaScript runtime to harvest cloud credentials, SSH keys, and API tokens. [More info](https://www.bleepingcomputer.com/news/security/massive-chaindrop-npm-supply-chain-attack-infects-hundreds-of-packages/)

- **Shai-Hulud NPM Worm Poisons 1,280+ Packages**: The Shai-Hulud npm worm resurfaced in a major supply-chain attack, compromising maintainer accounts to infect over 1,280 packages. The worm steals AWS, Kubernetes, and GitHub tokens, using compromised registry credentials to automatically re-publish and spread across the npm ecosystem. [More info](https://hackread.com/shai-hulud-npm-worm-poisoning-1280-packages/)

- **Microsoft Defender Stops Automated Ransomware Attempt in 128 Seconds**: Microsoft Defender XDR automatically neutralized an active ransomware attack on global direct-selling company QNET. The actor abused `mshta.exe` for initial access, but Defender's automated device isolation severed network access in under 2.5 minutes, preventing lateral movement and payload execution. [More info](https://www.microsoft.com/en-us/security/blog/2026/08/04/129-seconds-disruption-microsoft-defender-stops-ransomware-qnet/)

- **Varonis Unveils Agent Intent-Based Access Control for AI**: Varonis announced Agent Intent-Based Access Control (IBAC) to enforce runtime guardrails on enterprise AI agents. By sitting inline between LLMs and agents, it monitors instruction flow, detects scope expansion or jailbreaks, and automatically redacts or blocks unauthorized actions. [More info](https://www.bleepingcomputer.com/news/security/varonis-agent-ibac-keeps-ai-agents-within-their-intended-boundaries/)

- **Malicious NPM Packages Target Alibaba Developers**: Researchers discovered 18 malicious npm packages typosquatting internal Alibaba namespaces like `@ali` to target Chinese-speaking developer environments. Installation hooks fetched remote JavaScript payloads containing cross-platform RATs. [More info](https://www.cysecurity.news/2026/08/malicious-npm-packages-attack-alibaba.html)

- **Automated Botnets Scan Web Server Logs for OS Command Injection**: SANS ISC observed automated botnet traffic scanning web server logs for command injection vulnerabilities in diagnostic scripts (e.g., ping/traceroute). Developers are urged to replace shell parameter string concatenation with array-based execution vectors like Python's `subprocess.run`. [More info](https://isc.sans.edu/diary/rss/33214)

## 💥 Breaches & Leaks

- **Firebase Misconfiguration in AI Notetaker tl;dv Exposed Corporate Calls**: Unisolated Cloud Firestore database containers in the AI meeting assistant tl;dv allowed authenticated users to view global conference metadata and enter private calls. Over 180,000 call records across 23 national governments, corporations, and academic institutions were exposed. [More info](https://www.darkreading.com/application-security/ai-notetaker-spy-government-corporate-video-calls)

---

[⬅ Back to Archive](https://pranakn.github.io)
