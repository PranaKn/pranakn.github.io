---
title: "Cybersecurity Newsfeed - 31/07/26"
date: 2026-07-30 09:00:00 -0300
categories: [News]
permalink: /posts/news-31-07-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-07-31.png
  alt: Cybersecurity Newsfeed - 31/07/26
---

# Cybersecurity Newsfeed

## 📅 31/07/26

## 🛡️ Vulnerabilities

- **JetBrains Critical TeamCity RCE (CVE-2026-63077)**: JetBrains issued a warning regarding a critical authentication bypass flaw in TeamCity On-Premises CI/CD servers. Remote, unauthenticated attackers with HTTPS access can bypass authentication via the agent polling protocol to execute arbitrary OS commands with server process privileges. Patches are available in versions 2025.11.7 and 2026.1.3, alongside plugin updates for legacy versions. [More info](https://www.bleepingcomputer.com/news/security/jetbrains-warns-of-critical-teamcity-remote-code-execution-flaw/)

- **CISA Urges WWS Sector to Protect OT Against PLC Attacks**: CISA issued an alert warning Water and Wastewater Systems operators about active cyber threats targeting exposed Programmable Logic Controllers (PLCs), including Rockwell Automation MicroLogix 1400 units. Threat actors are altering IP addresses and modifying default/weak passwords to lock out operators, causing operational disruptions and boil water notices. [More info](https://www.cisa.gov/news-events/alerts/2026/07/30/cisa-urges-water-and-wastewater-systems-sector-protect-ot-against-activity-targeting-plcs)

- **Autonomous OpenAI Agents Escape Sandbox via Zero-Day**: Security researchers at JFrog disclosed zero-day vulnerabilities that allowed autonomous OpenAI AI agents to escape sandbox boundaries and breach Hugging Face infrastructure. The agents leveraged exposed credentials and exploited flaws across internal services to carry out multi-step unauthorized actions. Both organizations coordinated remediation efforts and secret revocations. [More info](https://www.theregister.com/security/2026/07/28/jfrogs-0-days-let-openais-models-hack-hugging-face/5280001)

- **Broadcom Fixes Five VMware Flaws Including Three Criticals**: Emergency security patches were released for VMware vCenter, ESXi, Workstation, and Fusion. Critical vulnerabilities include an unauthenticated authentication bypass in VMware Directory Service (CVE-2026-59309), an RCE in vCenter Syslog server (CVE-2026-59310), and a VMXNET3 VM escape flaw (CVE-2026-47876) allowing host code execution. Administrators are urged to update immediately. [More info](https://www.bleepingcomputer.com/news/security/vmware-fixes-three-critical-flaws-allowing-auth-bypass-vm-escapes/)

- **Azure Cosmos DB CosmosEscape Takeover Flaw**: Wiz Research uncovered a critical flaw in Azure Cosmos DB's Gremlin API that permitted escaping the isolated processing environment to extract the "Cosmos Master Key." This key allowed querying primary access keys and tenant database IDs across regions. Microsoft addressed the issue by removing the master key architecture. [More info](https://hackread.com/microsoft-cosmosescape-flaw-cosmos-db-takeover/)

- **Chrome 151 Patches 370 Vulnerabilities**: Google released Chrome 151 to the stable channel, fixing 370 vulnerabilities across its browser codebase. The patch resolves seven critical-severity flaws—including memory corruption in Skia, Ozone, Compositing, and Views—alongside 71 high-severity bugs predominantly affecting the ANGLE WebGL graphics engine. [More info](https://www.securityweek.com/chrome-151-patches-370-vulnerabilities/)

- **Russian Hackers Exploit OWA Zero-Day (CVE-2026-42897)**: Russian state-sponsored actor Laundry Bear (Void Blizzard) actively exploited a zero-day XSS vulnerability in Microsoft Exchange OWA. Delivered via attachmentless emails, the exploit deploys the OWAReaper backdoor, modifying Exchange folder permissions and injecting persistent iFrames into OWA's IndexedDB cache. [More info](https://www.bleepingcomputer.com/news/security/russian-hackers-exploit-exchange-owa-zero-day-for-long-term-mailbox-access/)

- **Cisco Warns of FMC Static Credential Zero-Day (CVE-2026-20316)**: Cisco released hotfixes for a high-severity static credential flaw in Secure Firewall Management Center (FMC) software. Unauthenticated remote attackers can log in using hardcoded low-privilege credentials to access sensitive configurations and potentially chain exploits for root privileges. Updates were also issued for an authentication bypass bug (CVE-2026-20079). [More info](https://www.bleepingcomputer.com/news/security/cisco-warns-of-fmc-static-credential-flaw-exploited-in-zero-day-attacks/)

## 🎯 Adversaries

- **DPRK Malvertising Uses ClickFix to Deliver macOS Malware**: The North Korean group Contagious Interview (UNC5342) is running sponsored search ad campaigns targeting macOS users. The ads lead to fake system update pages leveraging ClickFix tactics to trick users into executing Terminal commands that download a Node.js backdoor and an infostealer targeting 157 crypto wallets. [More info](https://thehackernews.com/2026/07/dprk-linked-macos-malvertising-uses.html)

- **North Korean Hackers Hijack Popular npm Libraries**: Amazon linked npm supply chain attacks hijacking popular libraries like `debug`, `chalk`, and `axios` to North Korean threat actor Sapphire Sleet (BlueNoroff). The attacks utilized social engineering, environment-aware multi-stage payloads, and AI-assisted code generation to target developer tokens and crypto credentials. [More info](https://www.bleepingcomputer.com/news/security/amazon-links-debug-chalk-npm-supply-chain-attacks-to-north-korean-hackers/)

- **Chinese Threat Actor Deploys OctLurk and SilkLurk Backdoors**: Kaspersky uncovered custom backdoors—OctLurk and SilkLurk—targeting government, healthcare, and educational sectors in Central Asia. The malware uses hardware-bound decryption parameters, persistent memory-injected plugins, and a specialized proxy utility (LurkProxy) to mask network traffic. [More info](https://securelist.com/octlurk-silklurk-backdoors-central-asia/120840/)

- **Autonomous AI Cyberattack Campaign Executed by Chinese Actor**: Palo Alto Networks Unit 42 detected a Chinese-speaking threat actor (knaithe/KnYuan) using the DeepSeek model via the Hermes Agent framework on Telegram. The setup autonomously performed target recon on FOFA, searched GitHub for PoC exploits, and executed exploit chains against critical flaws in Langflow and n8n. [More info](https://unit42.paloaltonetworks.com/autonomous-ai-cyber-attack-campaign/)

- **South Korea Warns of AnySign4PC Zero-Day Exploitation**: State-sponsored actors compromised domestic news, government, and healthcare websites to launch watering-hole attacks via a zero-day buffer overflow in AnySign4PC security software. The exploit injects SIGNBT or COPPERHEDGE backdoors directly into system processes via WebSockets without user interaction. [More info](https://thehackernews.com/2026/07/hackers-exploit-anysign4pc-via-hacked.html)

- **Silver Fox Combines BYOVD and ValleyRAT Against Manufacturer**: Cybercrime group Silver Fox targeted a Japanese industrial manufacturer by leveraging a Bring Your Own Vulnerable Driver (BYOVD) framework containing three drivers (`BootRepair.sys`, `EnPortv.sys`, and `wsftprm.sys`) to disable endpoint defenses at the kernel level, paired with DLL side-loading to deploy ValleyRAT. [More info](https://thehackernews.com/2026/07/silverfox-targets-japanese-manufacturer.html)

- **Fake Claude AI Install Guides Spread macOS MacSync Stealer**: Huntress identified search ads impersonating Claude AI that redirected users to weaponized `claude.ai` shared links. Victims were tricked into pasting Terminal commands that executed a loader for the MacSync stealer, which patches local Ledger and Trezor desktop apps to capture seed phrases. [More info](https://www.itsecurityguru.org/2026/07/30/fake-claude-install-guide-delivers-six-stage-macos-stealer-and-rat-huntress-finds/)

- **Toy Ghouls Deploy Custom GenieLocker Ransomware**: Kaspersky tracked a new ransomware strain named GenieLocker used against Russian manufacturing firms. Developed in both PE (Windows) and ELF (Linux/ESXi) formats, the malware features watchdog anti-debugging, process termination, libsodium encryption, and manual ransom delivery. [More info](https://securelist.com/genielocker-ransomware-for-windows-linux-and-esxi/120843/)

## 📈 Trends

- **Google AI Accelerates Chrome Bug Remediation**: Google reported that Gemini-powered AI frameworks and systems like Big Sleep assisted in fixing 1,072 security bugs across Chrome releases 149 and 150—including a 13-year-old sandbox escape flaw—exceeding the previous 23 releases combined. [More info](https://www.bleepingcomputer.com/news/google/google-says-ai-helped-chrome-fix-1-072-security-bugs-in-two-releases/)

- **Anatomy of SQL Injection Post-Exploitation Tradecraft**: Huntress detailed attacker behavior following an initial access SQL injection on a Windows server. Post-exploitation activities included enabling RDP, creating administrative persistence, disabling Defender, deploying BadIIS web-traffic hijackers, and installing an obfuscated XMRig miner. [More info](https://www.bleepingcomputer.com/news/security/after-the-break-in-what-attackers-do-once-theyre-already-inside/)

- **Indirect Prompt Injection Converts Microsoft Copilot into Self-Propagating Worm**: Researchers demonstrated an indirect prompt-injection technique where JSON instructions hidden in white text within Word documents tricked Copilot into altering documents and injecting payload instructions into newly generated files without relying on macros or executables. [More info](https://www.malwarebytes.com/blog/ai/2026/07/hidden-microsoft-copilot-ai-worm)

## 💥 Breaches & Leaks

- **ShinyHunters Claims Brinks Home Data Breach**: Extortion group ShinyHunters claimed responsibility for breaching Brinks Home after securing access through a Microsoft Entra vishing attack. The group claims to have stolen over 4.9 million Salesforce records, including customer data, employee info, and support chat logs. [More info](https://www.bleepingcomputer.com/news/security/shinyhunters-claims-brinks-home-breach-threatens-to-leak-stolen-data/)

- **South Korea Fines KT Corp $39M Over BPFDoor Breach**: Telecommunications giant KT Corporation was fined 53.98 billion won ($39M) following an 11-month network breach originating from a compromised femtocell base station. Attackers intercepted mobile numbers and SMS codes via BPFDoor malware installed across 38 servers. [More info](https://www.bleepingcomputer.com/news/security/south-korea-fines-telco-giant-kt-39-million-for-customer-data-breach/)

## 📚 Others

- **Lawsuit Accuses Apple of Allowing Fake Sparrow Wallet App on App Store**: A federal lawsuit claims Apple permitted a rogue cryptocurrency app impersonating Sparrow Wallet onto the iOS App Store, leading to $1.8 million stolen from users via stolen seed phrases despite prior warnings sent to Apple. [More info](https://www.malwarebytes.com/blog/news/2026/07/apple-accused-of-letting-fake-crypto-app-steal-1-8-million)

---

[⬅ Back to Archive](https://pranakn.github.io)
