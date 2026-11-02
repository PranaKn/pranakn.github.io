---
title: "Cybersecurity Newsfeed - 03/11/26"
date: 2026-11-02 09:00:00 -0300
categories: [News]
permalink: /posts/news-03-11-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-11-03.png
  alt: Cybersecurity Newsfeed - 03/11/26
---

# Cybersecurity Newsfeed

## 📅 03/11/26

## 🛡️ Vulnerabilities

- **Over 1,000 GitLab Instances Vulnerable to RCE**: Over 1,000 self-hosted GitLab instances remain exposed to critical remote code execution attacks targeting maximum-severity vulnerabilities. Attackers are actively targeting flaws like CVE-2026-97229, an integer overflow bug in GitLab's CI/CD Regular Expression Compiler, which is currently listed in CISA's Known Exploited Vulnerabilities (KEV) catalog alongside CVE-2026-85706. [More info](https://www.bleepingcomputer.com/news/security/over-1-000-gitlab-servers-vulnerable-to-code-execution-attacks/)

- **Ivanti Connect Secure VPN Zero-Days Exploited**: Ivanti released emergency security patches for Connect Secure VPN appliances addressing two actively exploited zero-day vulnerabilities (including CVE-2026-104935). CISA added these flaws to its KEV catalog after threat actors chained them with existing exploits to achieve unauthenticated root code execution, steal credentials, and alter system logs. [More info](https://www.bleepingcomputer.com/news/security/ivanti-patches-two-more-connect-secure-zero-days-chained-in-attacks/)

- **Synology NAS Devices Targeted by C3RB3R Ransomware**: Synology alerted NAS device owners to ongoing ransomware attacks deploying the C3RB3R payload, which encrypts files with a `.L0CK3D` extension. Attackers are exploiting unpatched 2024 vulnerabilities (including critical RCE flaw CVE-2024-10441 with a CVSS 9.8) on outdated DiskStation Manager (DSM) software builds. [More info](https://www.bleepingcomputer.com/news/security/synology-warns-customers-of-ongoing-c3rb3r-ransomware-attacks/)

## 🎯 Adversaries

- **BITTER APT Targets South Asian Government and Engineering Sectors**: FortiGuard Labs and security researchers uncovered a cyberespionage campaign by the BITTER APT group targeting South Asian government, energy, and engineering entities. The multi-stage infection chain leverages fake diplomatic LNK lure documents and custom PowerShell scripts to deploy PapRAT spyware for persistent data exfiltration and remote code execution. [More info](https://hackread.com/bitter-apt-fake-diplomatic-documents-paprat-spyware/) | [More info](https://www.darkreading.com/cyberattacks-data-breaches/paprat-cyberespionage-campaign-bitter-south-asia)

- **DarkBlinders Campaign Targets Israeli and Iraqi Kurdish Targets**: Iran-aligned threat cluster DarkBlinders launched spear-phishing campaigns targeting high-profile Israeli targets and Iraqi Kurdish government cloud environments. The group exploited AppDomainManager injection, DLL sideloading, and spoofed government portals to deploy SHELBYLOADER malware and establish persistent access. [More info](https://thehackernews.com/2026/11/darkblinders-compromises-israeli-target.html)

- **Chinese Threat Actors Deploy ARTEX AI Framework**: Chinese threat actors leveraged ARTEX, an open-source agentic AI penetration-testing framework, to execute automated, parallel attacks targeting over 200 international organizations across government, telecom, and technology sectors. [More info](https://www.bleepingcomputer.com/news/security/chinese-hackers-use-artex-ai-in-automated-attacks-against-200-orgs/)

- **SysGoRAT Malware Targets Government Linux Servers**: Palo Alto Networks Unit 42 detected cyber espionage activity targeting government Linux servers using SysGoRAT malware alongside suspected AI-generated shell scripts containing inline conversational notes to harvest system credentials and establish persistent access. [More info](https://thehackernews.com/2026/11/government-linux-servers-targeted-with.html)

- **Fake Adobe Acrobat Pages Distribute ScreenConnect Installer**: Threat actors are deploying fake Adobe Acrobat document-signing web pages to trick victims into executing genuine, digitally signed ScreenConnect remote management installers, granting attackers persistent remote access and elevated privileges on target endpoints. [More info](https://hackread.com/hackers-remote-access-tool-fake-adobe-acrobat-pages/)

## 🦠 Malware & Botnets

- **XCPE Android TV Botnet Disrupted**: International law enforcement agencies alongside Google disrupted the XCPE Android malware botnet involving over 1.3 million compromised Android TV set-top boxes across 206 models. The modular backdoor (`x.cpe`) operated with system-level privileges via MQTT protocols to execute commands, steal logs, and install payloads. Google permanently banned OEM manufacturer Videostrong for intentionally pre-installing the firmware backdoor for financial gain. [More info](https://www.helpnetsecurity.com/2026/11/02/xcpe-botnet-android-backdoor/) | [More info](https://www.theregister.com/cyber-crime/2026/11/02/cops-bust-botnet-of-13m-infected-android-tv-boxes/5307045)

- **VOLTA Infostealer Weaponizes LLMs for Victim Assessment**: Cisco Talos uncovered VOLTA, a novel Windows infostealer leveraging Large Language Models (LLMs) such as Claude, Gemini, and Kimi to evaluate stolen victim data automatically. After harvesting credentials and personal files, VOLTA queries AI backends to rate target monetization value before delivering priority victim assessments to threat actors via Telegram. [More info](https://securityaffairs.com/202281/malware/volta-the-infostealer-that-asks-an-ai-which-victims-are-worth-the-effort.html)

- **Deep Dive into Brazil's Astaroth Banking Trojan Ecosystem**: Security researchers analyzed the evolving Astaroth banking Trojan ecosystem targeting Brazil, detailing its abuse of GitHub steganography and WhatsApp Web for resilient Command-and-Control configuration hosting and lateral spreading. The malware employs geo-restricted JS downloaders and process hollowing techniques to harvest sensitive banking credentials from targeted browsers. [More info](https://0x0d4y.blog/inside-brazils-financial-malware-ecosystem-deep-dive-into-the-astaroth/)

## 📈 Trends

- **Mobile Carriers Retain Customer Metadata for Years**: A privacy review highlighted that major mobile carriers retain customer call, text, and geolocation metadata for years, creating severe data breach and surveillance risks. Telecom security firm Cape demonstrated how core carrier retention windows leave long-term logs exposed, urging aggressive data minimization policies. [More info](https://www.bleepingcomputer.com/news/security/your-mobile-carrier-stores-your-call-logs-for-years/)

- **Guardz Integrates Palo Alto Networks Prisma Browser**: Guardz integrated Palo Alto Networks Prisma Browser for Business into its security suite to deliver enterprise-grade browser protection tailored for small businesses. The combined platform detects in-session web threats—including HTML smuggling and phishing—and correlates browser events directly with identity and endpoint telemetry. [More info](https://hackread.com/guardz-brings-palo-alto-networks-prisma-browser-protection-to-small-businesses/)

## 💥 Breaches & Leaks

- **Fintech Provider Abrigo (Sageworks) Taken Offline After Attack**: Financial technology provider Abrigo initiated emergency maintenance on October 30 after detecting suspicious activity, taking its Sageworks banking application offline. Threat actors claim to have exfiltrated employee and account data, including names, email addresses, and phone numbers. Security researchers strongly advise affected financial institutions to rotate Sageworks API keys immediately. [More info](https://www.bleepingcomputer.com/news/security/fintech-platform-sageworks-taken-offline-after-suspected-cyberattack/)

- **Chainalysis Confirms Security Breach via Autonomous Agentic AI**: Blockchain analytics platform Chainalysis confirmed a security breach where attackers utilized autonomous agentic AI techniques to breach internal tools. The incident exposed customer names, emails, user IDs, and roles, though core investigation graphs, notes, and authentication secrets remained uncompromised. [More info](https://www.helpnetsecurity.com/2026/11/02/chainalysis-breached-using-offensive-agentic-techniques/)

- **BTCPay Server Instances Targeted in Hot Wallet Crypto Thefts**: BTCPay Server warned administrators to update their cryptocurrency payment processing software immediately due to unauthorized hot wallet thefts affecting outdated instances. Hosting providers suspended vulnerable instances running version 2.4.1 while maintainers investigate how attackers gained unauthorized administrative privileges. [More info](https://www.bleepingcomputer.com/news/security/btcpay-server-warns-of-hot-wallet-thefts-targeting-outdated-instances/)

## 📚 Others

- **Guide on Reverse Engineering Android Applications with Apktool**: A technical guide details using Apktool to reverse engineer Android applications by decompiling APK resources, modifying XML manifests and configurations, and recompiling and signing the modified binary for analysis. [More info](https://www.darknet.org.uk/2026/11/apktool-decompile-edit-rebuild-android-apk/)

---

[⬅ Back to Archive](https://pranakn.github.io)
