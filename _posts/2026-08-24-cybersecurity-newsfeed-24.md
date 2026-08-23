---
title: "Cybersecurity Newsfeed - 24/08/26"
date: 2026-08-23 09:00:00 -0300
categories: [News]
permalink: /posts/news-24-08-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-08-24.png
  alt: Cybersecurity Newsfeed - 24/08/26
---

# Cybersecurity Newsfeed

## 📅 24/08/26

## 🛡️ Vulnerabilities

- **NASA/JPL AMMOS Instrument Toolkit Critical Flaw (CVE-2026-73570 / GHSA-p9r8-2q67-fp86)**: Cycode researchers uncovered a CVSS 9.4 flaw in NASA/JPL’s open-source spacecraft command software. The browser-based tool binds to all network interfaces without authentication or CSRF protections, allowing remote attackers to execute arbitrary spacecraft commands, scripts, and path-traversal files. [More info](https://securityaffairs.com/197689/hacking/critical-flaw-in-nasa-jpl-open-source-spacecraft-command-software.html)

- **CISA Adds Zimbra Command Injection to KEV Catalog (CVE-2026-73570)**: CISA added an actively exploited OS Command Injection vulnerability in Zimbra Collaboration Suite to its Known Exploited Vulnerabilities catalog. The flaw allows attackers to execute arbitrary system commands and potentially gain total control over exposed servers. [More info](https://www.cisa.gov/news-events/alerts/2026/08/21/cisa-adds-one-known-exploited-vulnerability-catalog)

- **CISA Orders Remediation for Exploited TrueConf Flaws**: CISA added two critical TrueConf Server vulnerabilities to its KEV catalog: a missing authentication bug (CVE-2026-72529) and a code injection flaw (CVE-2026-72530). The Head Mare hacktivist group actively exploited these to replace client installers with backdoors targeting Russian infrastructure. [More info](https://www.bleepingcomputer.com/news/security/cisa-orders-feds-to-patch-actively-exploited-trueconf-server-flaws/)

- **Cisco Patches Nine Critical and High Flaws**: Cisco addressed nine severe vulnerabilities across its Crosswork and Secure Workload platforms, including SQL injection (CVE-2026-20030) and bypass flaws with CVSS 10.0 ratings. Organizations are urged to apply updates promptly. [More info](https://thehackernews.com/2026/08/cisco-patches-nine-crosswork-and-secure.html)

- **Microsoft Warns of Max-Severity Entra ID Flaw (CVE-2026-69836)**: Microsoft patched a critical untrusted data deserialization flaw in Entra ID that could allow remote unauthenticated code execution. Additional privilege escalation and RCE fixes were automatically applied across Azure Arc, Exchange Online, and Managed Cassandra. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-warns-of-max-severity-entra-id-flaw-exploited-in-attacks/)

- **Windows Named Pipes Exploitation Surface**: Security analysis highlights how privilege escalation vectors arise when privileged Windows services communicate with lower-privileged apps via named pipes, allowing attackers to exploit weak ACLs as a confused deputy. [More info](https://www.bleepingcomputer.com/news/security/named-pipes-under-attack-securing-windows-interprocess-communication/)

- **Visa Contactless "Zombie Card" Flaw**: Researchers discovered a vulnerability in Visa Kernel 3 contactless payments allowing expired Visa cards to process terminal transactions by tampering with the transmitted expiration date. [More info](https://www.malwarebytes.com/blog/news/2026/08/zombie-card-an-expired-visa-credit-card-can-be-used-for-purchases)

## 🎯 Adversaries

- **North Korean Hackers Target 1,640 Global Targets**: State-sponsored actors are conducting a widespread espionage campaign against defense contractors, policy experts, and researchers using spear-phishing, trojanized apps, and custom backdoors to exfiltrate IP. [More info](https://www.cysecurity.news/2026/08/north-korean-hackers-target-1640.html)

- **Russian State Hackers Adopt OAuth Abuse**: Russian cyber espionage groups are moving beyond credential harvesting to trick targets into approving malicious OAuth apps, achieving persistent cloud mailbox and data access without triggering MFA or password resets. [More info](https://www.theregister.com/security/2026/08/21/russian-snoops-add-oauth-abuse-to-targeted-phishing-campaigns/5290706)

- **Ransomware Affiliate Hijacks Rival Extortion Payments**: A rogue ransomware affiliate posed as a legitimate data recovery firm to intercept victim communications, swapping crypto wallet addresses to steal ransom payments directly from fellow cybercriminals. [More info](https://www.theregister.com/cyber-crime/2026/08/20/ransomware-crook-poses-as-recovery-firm-to-steal-payments-from-fellow-extortionists/5290344)

## 🦠 Malware

- **ToxicPanda 2.0 Android Banking Trojan Evolves**: ToxicPanda version 2.0 now targets 349 financial apps across 16 countries. It uses VPN permissions to block Google Play Protect and abuses Accessibility Services to exploit Wireless Debugging (ADB) for full shell-level access and phishing overlays. [More info](https://www.bleepingcomputer.com/news/security/toxicpanda-android-malware-uses-vpn-permissions-to-block-google-play/) | [More info](https://securityaffairs.com/197681/breaking-news/toxicpanda-2-0-gets-a-major-upgrade.html)

- **Android Car Head Units Hit by Proxy Botnet Malware**: MoYu Group targeted DoFun-powered car infotainment systems by weaponizing the TWCore firmware update app to deploy "JarService" and "zhima" modules, turning car head units into residential proxy nodes. [More info](https://www.bleepingcomputer.com/news/security/hackers-infect-android-car-head-units-with-proxy-botnet-malware/) | [More info](https://thehackernews.com/2026/08/android-car-malware-spreads-through.html) | [More info](https://www.kaspersky.com/blog/car-botnet-malware-for-head-units-with-android/56296/)

- **Banking Trojans Spotlight (Manic, Grandoreiro, ToxicPanda 2.0)**: Researchers outline active threats: Manic (combining spyware and offline mesh relays via Bluetooth/Wi-Fi Direct), Grandoreiro (DLL sideloading via Duplicate Files Finder), and ToxicPanda 2.0. [More info](https://www.securityweek.com/banking-trojans-manic-grandoreiro-toxicpanda-2-0-in-the-spotlight/)

- **SynkLoader Pushed via Microsoft Teams Phishing**: Phishing campaigns impersonating IT help desks are distributing SynkLoader via fake installers. The malware profiles Active Directory, sets up reverse proxies, and deploys a full-screen lock screen overlay to capture credentials. [More info](https://www.bleepingcomputer.com/news/security/new-synkloader-malware-pushed-in-microsoft-teams-phishing-campaign/)

- **FTP Server Banners Used to Deliver E4del and PINHOLE**: Attackers are hiding PowerShell commands inside FTP greeting banners. The chain deploys E4del (a Node.js/Electron RAT) and PINHOLE (a stealthy assembly implant resolving C2 via Pinterest and SurveyMonkey). [More info](https://www.bleepingcomputer.com/news/security/hackers-abuse-ftp-server-banners-to-deliver-new-windows-malware/)

## 📦 Supply Chain & AI Security

- **Hugging Face Credential Leaks Exploit AI Agents**: Exposed tokens on Hugging Face led to corporate cloud exposures as automated AI agents operating on open-source models discovered and misused hardcoded cloud keys and credentials. [More info](https://www.cysecurity.news/2026/08/hugging-face-ai-hack-pushes.html)

- **Zero-Click Cryptographic Context Injection Targets Grok and Gemini**: Adversa AI demonstrated hiding malicious payload instructions in AES-256-GCM encrypted text. When summarized, AI sandboxes decrypt the payload, executing untrusted instructions to exfiltrate private session metadata and chat history. [More info](https://securityaffairs.com/197717/hacking/zero-click-grok-chat-history-theft-adversa-ai-demonstrates-cryptographic-context-injection.html)

- **Popular Rust Crates Poisoned with Proc-Macros**: Threat actors compromised Rust crates `arrayref`, `internment`, and `append-only-vec` by injecting malicious proc-macros that execute during Cargo builds to harvest developer credentials and system telemetry. [More info](https://www.theregister.com/security/2026/08/21/hackers-poison-popular-rust-crates-to-steal-developers-credentials/5291075)

- **14 Trojanized npm Packages Drop AI-Assisted RedC2 4.0**: Packages disguised as utility libraries deployed the RedShell Linux beacon. RedC2 4.0 includes "Red Agent," an LLM-driven command-execution layer translating natural language into red-team commands. [More info](https://thehackernews.com/2026/08/14-trojanized-npm-packages-drop-redc2.html)

- **SDLC Threat Landscape Surges (ChainDrop npm Worm)**: Unit 42 highlighted pipeline risks, pointing to the ChainDrop npm worm which infected 400+ packages via preinstall scripts, harvested OpenID tokens from GitHub Actions memory, and used Ethereum for C2. [More info](https://unit42.paloaltonetworks.com/sdlc-supply-chain/)

- **Microsoft Defender BTR.sys Driver Weaponized**: Check Point Research showed how Defender's signed boot-time driver (`BTR.sys`) can be abused via a hardcoded RC4 key to execute arbitrary kernel-level file/registry operations and kill security binaries. [More info](https://thehackernews.com/2026/08/microsoft-defenders-own-driver-can-be.html)

## 📈 Trends & Cloud

- **Over 9,300 Exposed AWS Keys Remain Active**: Truffle Security revealed thousands of active AWS access keys publicly exposed between 2022 and 2026, including hundreds of admin and root keys, with Hugging Face cited as the largest source of leaks. [More info](https://www.bleepingcomputer.com/news/security/hundreds-of-leaked-aws-keys-give-full-control-over-corporate-accounts/)

- **Corey Quinn Criticizes Inscrutable AWS Cloud Security Defaults**: Cloud expert Corey Quinn highlighted risks in AWS account root protections and identity boundary defaults, warning that obscure governance policies leave gaps for corporate exposure. [More info](https://www.theregister.com/security/2026/08/22/aws-security-makes-an-inscrutable-choice-corey-quinn/5291446)

- **Windows 11 Game Crashes Linked to Peripheral Drivers**: August 2026 Windows 11 updates caused crashes across multiple games, which Microsoft traced to third-party RGB lighting drivers like `inpoutx64.sys` interacting with the kernel. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-blames-windows-gaming-issues-on-rgb-lighting-devices/)

## 💥 Breaches & Leaks

- **SickKids Data Breach Exposes Staff and Applicant Data**: Toronto's Hospital for Sick Children disclosed a breach caused by a third-party application flaw that exposed personal info of current/former employees and job applicants. Patient medical records were not impacted. [More info](https://www.bleepingcomputer.com/news/security/sickkids-data-breach-exposes-employee-and-job-applicant-info/)

---

[⬅ Back to Archive](https://pranakn.github.io)
