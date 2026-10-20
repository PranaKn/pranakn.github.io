---
title: "Cybersecurity Newsfeed - 21/10/26"
date: 2026-10-20 09:00:00 -0300
categories: [News]
permalink: /posts/news-21-10-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-10-21.png
  alt: Cybersecurity Newsfeed - 21/10/26
---

# Cybersecurity Newsfeed

## 📅 21/10/26

## 🛡️ Vulnerabilities

- **Urgent PHP Warning & Emergency Patches**: PHP maintainers issued an urgent warning regarding two critical flaws in the language runtime, with emergency security releases scheduled for immediate deployment. The vulnerabilities pose severe risks to web infrastructure worldwide, potentially allowing unauthenticated remote code execution depending on server configurations. [More info](https://www.bleepingcomputer.com/news/security/php-warns-admins-of-two-critical-flaws-emergency-patches-coming-tomorrow/)

- **CISA Adds Six Flaws to KEV Catalog**: CISA added six vulnerabilities to its Known Exploited Vulnerabilities catalog. Newly added issues include CVE-2026-96652, CVE-2026-96654, CVE-2026-96655, and CVE-2026-96656 affecting Plex Media Server (SSRF, URI scheme issues, file path control), CVE-2026-106931 in EG Secure Solutions SiteGuard Server Edition (OS command injection), and CVE-2026-110936 in Siemens Software Center. Federal agencies must remediate rapidly. [More info](https://www.cisa.gov/news-events/alerts/2026/10/20/cisa-adds-six-known-exploited-vulnerabilities-catalog)

- **PoC Released for Critical Fortinet FortiSIEM Flaw (CVE-2026-106173)**: Security researchers published a proof-of-concept exploit for a critical flaw in Fortinet FortiSIEM's gRPC service (CVSS 9.4). Unauthenticated remote attackers can leverage improper path validation and NUL-byte injection to write arbitrary files and execute code by targeting scheduled scripts. Patches are available in version 7.5.1. [More info](https://thehackernews.com/2026/10/critical-fortisiem-flaw-gets-public.html)

- **Microsoft Patches Over 30 Office Flaws**: Microsoft released security updates for over 30 vulnerabilities in Office, including two dozen high-severity remote code execution (RCE) bugs. Six of these RCE vulnerabilities can be triggered via the Outlook Preview Pane without user interaction. [More info](https://www.securityweek.com/microsoft-patches-two-dozen-rce-flaws-in-office/)

- **Qilin & INC Ransomware Exploit PAN-OS Authentication Bypass (CVE-2026-0257)**: Ransomware actors are actively exploiting a previously patched flaw in Palo Alto Networks PAN-OS and Prisma Access devices to bypass MFA, establish unauthorized VPN sessions, and move laterally to extract vCenter and domain controller credentials. [More info](https://thehackernews.com/2026/10/qilin-and-inc-ransomware-groups-exploit.html)

## 🎯 Adversaries

- **APT28 Breaches NATO Defense Contractors & Law Enforcement**: Russian military intelligence hackers (APT28/Swallowtail/Forest Blizzard) breached a naval shipbuilder, a military aircraft engine manufacturer, and a law enforcement agency in NATO member countries. Attackers deployed a modified HOOKEDGE backdoor with dedicated C2 infrastructure and used a custom reflective loader (`ld.exe`) alongside persistent SSH tunnels. [More info](https://cyberscoop.com/russian-hackers-apt28-target-nato-defense-firms/) | [More info](https://thehackernews.com/2026/10/russian-apt28-breaches-nato-naval.html)

- **AOMEI Backupper Supply Chain Compromise**: Threat actors tracked as UNC7017 compromised AOMEI Backupper update servers to deploy the SHINYROAD backdoor and Radmin remote administration tools. Attackers also manipulated notification configuration files to force NTLM authentication against rogue WebDAV servers to leak credential hashes. [More info](https://www.helpnetsecurity.com/2026/10/20/aomei-backupper-compromised-supply-chain/)

- **Pegasus Spyware Confirmed on Serbian Rector's iPhone**: Forensic analysis confirmed a zero-click Pegasus spyware infection targeting the rector of the University of Belgrade alongside civil society figures and a senior prosecutor investigating government corruption in Serbia. [More info](https://thehackernews.com/2026/10/pegasus-spyware-infection-confirmed-on.html)

- **ROMULUS Platform Expands ClickFix Campaigns**: Researchers uncovered the ROMULUS distribution infrastructure, which uses deceptive ClickFix lures to trick users into executing PowerShell scripts that drop trojanized MSI installers, heavily padded archives, and Legion Loader. [More info](https://thehackernews.com/2026/10/romulus-clickfix-platform-tricks-users.html)

- **Fake Web3 Venture Firm REF8801 Drops Trojanized npm Packages**: Attackers posing as Apex Accelerator published malicious npm packages (`@apexacc/cli` and `@apexacc/audit`) that deployed Windows info-stealers and a macOS backdoor while intercepting Model Context Protocol configs and OpenRouter API traffic from AI coding agents. [More info](https://thehackernews.com/2026/10/fake-web3-accelerator-uses-npm-packages.html)

## 📈 Trends

- **Google Chrome Enhanced Protection Battles ClickFix & Social Engineering**: Google updated Chrome's Enhanced Protection to inspect clipboard content for dangerous terminal commands (e.g., PowerShell, `cmd.exe`) and migrated Gemini-powered scam detection server-side to block fake browser updates and technical support scams. [More info](https://www.helpnetsecurity.com/2026/10/20/google-chrome-enhanced-protection-updates/)

- **Eightfold Increase in Broken Security Patches on GitHub**: Research indicates a dramatic rise in incomplete open-source security fixes, particularly for flaws listed in CISA's KEV catalog. Vulnerability classes relying on blocklists (e.g., SSRF, prototype pollution) show the highest failure rates. [More info](https://www.helpnetsecurity.com/2026/10/20/ncomplete-security-patches-broken-fixes-rise/)

- **Calendar Invite Phishing Surges Past 740,000 Volume**: Attackers are increasingly exploiting `.ics` attachments and Google Calendar routing to bypass standard email security gateways, placing persistent malicious financial lures and trojanized tools directly on user calendars. [More info](https://www.helpnetsecurity.com/2026/10/malicious-calendar-invites/)

## 💥 Breaches & Leaks

- **Zeabur Shutting Down Following Second Major Breach**: Hosting provider Zeabur announced it will shut down operations by December 31, 2026, after attackers leveraged unencrypted credentials and unrotated admin keys to breach 321,810 user accounts, 3.2 million environment variables, and 101 GCP servers across nine regions. [More info](https://www.bleepingcomputer.com/news/security/zeabur-shutting-down-after-second-security-breach-in-two-months/)

- **Private Keys Leaked for Eight Indian CA eMudhra Intermediate Certificates**: A major cryptographic breach occurred after private keys for eight intermediate CA certificates from eMudhra were leaked online. Major browsers and language ecosystems (Chrome, Firefox, Go, Python, Rust) issued emergency updates and revocation lists (CRLSet/OneCRL) to block trust. [More info](https://thehackernews.com/2026/10/eight-emudhra-ca-keys-compromised.html)

- **Bullhorn Disrupted by Cyberattack**: Enterprise recruitment software platform Bullhorn experienced operational disruptions after a cyberattack forced systems offline. [More info](https://www.theregister.com/security/2026/10/20/bullhorn-sees-red-after-cyberattack-knocks-recruitment-platform-offline/5304114)

## 🏛️ Policy & Regulations

- **DHS Bans DeepSeek AI Across U.S. Federal Civilian Agencies**: The U.S. Department of Homeland Security issued a binding directive ordering federal civilian agencies to eliminate all DeepSeek AI applications, APIs, and integrated software within 60 days, citing data privacy risks and state-access concerns. [More info](https://www.bleepingcomputer.com/news/security/dhs-bans-deepseek-products-across-us-federal-civilian-agencies/)

## 📚 Others

- **SecTor 2026 Concludes in Toronto**: Over 6,500 security professionals gathered at SecTor 2026 to address key industry developments, including state-sponsored targeting of civil society, agentic AI deployment risks, and machine-speed incident response frameworks. [More info](https://www.darkreading.com/cybersecurity-operations/sector-2026-reveals-a-rapidly-shifting-cybersecurity-landscape)

---

[⬅ Back to Archive](https://pranakn.github.io)
