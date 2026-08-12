---
title: "Cybersecurity Newsfeed - 13/08/26"
date: 2026-08-12 09:00:00 -0300
categories: [News]
permalink: /posts/news-13-08-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-08-13.png
  alt: Cybersecurity Newsfeed - 13/08/26
---

# Cybersecurity Newsfeed

## 📅 13/08/26

## 🛡️ Vulnerabilities

- **Microsoft Patch Tuesday Fixes 400+ Flaws & Zero-Days**: Microsoft's August 2026 security release addresses up to 421 vulnerabilities (62 Critical), including an actively exploited privilege escalation flaw in `afd.sys` (**CVE-2026-68820**), a 9.8 CVSS RCE in Windows Deployment Services TFTP (**CVE-2026-62893**), a wormable DNS Server vulnerability (**CVE-2026-62878**), and User Profile Service flaws. System administrators are urged to patch immediately. [More info](https://www.malwarebytes.com/blog/bugs/2026/08/patch-tuesday-update-now-to-fix-421-flaws-including-three-zero-days) | [More info](https://securityaffairs.com/197048/security/microsoft-patch-tuesday-for-august-2026-fixed-a-zero-day-and-wormable-rce.html) | [More info](https://krebsonsecurity.com/2026/08/microsoft-plugs-nearly-400-security-holes/)

- **"ShieldBreak" Zero-Day Bypasses Microsoft Defender**: A new local privilege escalation exploit called ShieldBreak bypasses previous fixes (CVE-2026-50656) by abusing Cloud Filter API (`cfapi`) user-mode callback hooks during cloud-hydration scans to gain full `NT AUTHORITY\SYSTEM` privileges on Windows endpoints. [More info](https://www.bleepingcomputer.com/news/security/new-microsoft-defender-shieldbreak-zero-day-grants-system-privileges/)

- **Critical VMware vCenter Traversal Flaw (CVE-2026-59310)**: Attackers are actively exploiting a critical directory traversal bug (CVSS 9.8) in VMware vCenter Server to execute arbitrary code and establish persistent reverse SSH tunnels, alongside increased scanning for SAML SSO bypasses (**CVE-2026-59309**). [More info](https://thehackernews.com/2026/08/attackers-exploit-vmware-vcenter.html)

- **SharePoint Auth Bypass Exploited in the Wild (CVE-2026-55040)**: A PoC exploit for SharePoint's JWT token validation pipeline is being actively weaponized to hijack administrator sessions, while CISA confirmed another SharePoint RCE (**CVE-2026-45659**) is being deployed in ransomware campaigns. [More info](https://www.bleepingcomputer.com/news/microsoft/hackers-leverage-new-microsoft-sharepoint-exploit-in-attacks/)

- **"Zoomsday" Memory-Safety Bugs Hit Zoom**: Three flaws (**CVE-2026-53413, CVE-2026-53414, CVE-2026-53415**) in Zoom's annotation parsing logic allow malicious meeting participants to trigger memory corruption, causing client crashes, info leaks, or arbitrary code execution across Windows, macOS, Linux, and VDI platforms. [More info](https://www.malwarebytes.com/blog/bugs/2026/08/zoomsday-flaws-could-let-one-zoom-participant-attack-another)

- **Maximum-Severity Code Execution Flaw in SAP Commerce Cloud (CVE-2026-58231)**: SAP patched a CVSS 10.0 flaw caused by missing authorization and validation on a default authentication client, permitting unauthenticated remote takeover of application components. [More info](https://thehackernews.com/2026/08/sap-commerce-cloud-flaw-could-let.html)

- **Ivanti Patches Multiple Endpoint Manager Flaws**: Ivanti released updates addressing high-severity flaws in Endpoint Manager (EPM) version 2024 SU7 (**CVE-2026-18129**, **CVE-2026-18125**, **CVE-2026-18127**) that could lead to credential exposure, agent DoS, or recording manipulation. [More info](https://www.securityweek.com/ivanti-epm-update-patches-remotely-exploitable-flaws/)

## 🎯 Adversaries

- **Lazarus Exploits Windows Zero-Day in Defense Cyberespionage**: North Korea-linked Lazarus group weaponized a zero-day in `afd.sys` (**CVE-2026-68820**) during Operation Dream Job. Approaching defense and aerospace targets with fake job offers, they deployed a 17-command backdoor named "Troy", MISTPEN downloaders, FudModule rootkits bypassing Smart App Control, and RelayShell web shells on compromised Roundcube webmail servers. [More info](https://thehackernews.com/2026/08/lazarus-exploits-windows-zero-day-to.html) | [More info](https://www.bleepingcomputer.com/news/security/lazarus-hackers-exploited-windows-zero-day-to-target-defense-firms/) | [More info](https://www.helpnetsecurity.com/2026/08/12/north-korea-lazarus-fake-job-offers/)

- **Sandworm Targets IT Administrators with Trojanized "SopraVPN"**: Russia's APT44 (Sandworm) conducted fake job interviews over Zoom to trick IT admins into installing a trojanized WireGuard VPN client hosted on SourceForge, delivering hidden obfuscated PowerShell payloads for endpoint persistent access. [More info](https://www.bleepingcomputer.com/news/security/sandworm-hackers-target-it-pros-with-trojanized-wireguard-vpn-client/)

- **Sandworm Attack Sabotaged Polish Power Plant**: A post-mortem by CERT.PL details how Sandworm breached a combined heat and power plant via a wind farm firewall and SSH tunnels through a private APN network, manipulating WAGO and Siemens PLCs to force a shutdown of steam turbines. [More info](https://www.infosecurity-magazine.com/news/attack-polish-power-plant-2025-led/)

- **"City-Forum" Campaign Exploits Guest Profiles in Cloud Services**: Threat actors are abusing unauthenticated guest access on Salesforce Aura/LWR and ServiceNow Service Portals using a custom Go tool to extract massive amounts of telecom, financial, and government enterprise data via search endpoints and GraphQL queries. [More info](https://www.securityweek.com/stealthy-city-forum-attacks-target-salesforce-and-servicenow-with-custom-toolset/)

- **Gunra Ransomware Exploits Fortinet Vulnerabilities**: Authorities warn that Gunra ransomware affiliates are leveraging Fortinet flaws (**CVE-2024-55591** and **CVE-2025-24472**) to gain super-admin access, bypass MFA, wipe backups, and exfiltrate terabytes of data from Microsoft 365 environments. [More info](https://www.infosecurity-magazine.com/news/gunra-ransomware-fortinet-flaws/) | [More info](https://www.darkreading.com/cyberattacks-data-breaches/gunra-ransomware-gang-fortinet-flaws-bypasses-mfa)

- **DeadLock Ransomware Leverages Polygon Blockchain**: DeadLock ransomware is adopting a decentralized C2 setup by storing configuration data and victim leak logs in Polygon smart contracts, while hosting exfiltrated corporate files on Wasabi cloud storage. [More info](https://www.bleepingcomputer.com/news/security/deadlock-ransomware-uses-blockchain-to-resist-infrastructure-takedown/)

- **Ransomware Targeting AI Infrastructure Brick Model Weights**: Attackers are exploiting an unauthenticated endpoint (**CVE-2025-3248**) in Langflow servers to execute Python code and encrypt critical AI model checkpoints. Flaws in the ransomware binary render affected machine learning models permanently unrecoverable. [More info](https://www.cysecurity.news/2026/08/new-ransomware-targets-ai-model-weights.html)

- **Kimwolf v7 Android Botnet Mimics Chrome via Protocol Fingerprinting**: An upgraded variant of Kimwolf targets Android TV boxes using HTTP/2 DDoS floods, multi-tier C2 via Ethereum Name Service (ENS) resolution, and open Android Debug Bridge (ADB) ports for propagation. [More info](https://securityaffairs.com/197070/malware/kimwolf-v7-hides-ddos-traffic-behind-chrome-fingerprints-and-ethereum.html)

- **WindRelay Android NFC Relay Malware Deployed in Banking Scams**: Group-IB uncovered live-call financial scams delivering SpyNote RAT and WindRelay malware to Android devices, allowing fraudsters to intercept contactless NFC payment card data and perform real-time unauthorized transactions. [More info](https://www.infosecurity-magazine.com/news/windrelay-nfc-relay-spynote-rat/)

- **75,000 Users Infected by 737 Malicious Chrome VPN Extensions**: Socket researchers discovered a campaign leveraging hundreds of fake Chrome extensions (impersonating NordVPN, Proton VPN, and Cloudflare 1.1.1.1) to route victim HTTP traffic and capture credentials via SOCKS5 proxies on port 1082. [More info](https://www.bleepingcomputer.com/news/security/hundreds-of-fake-chrome-vpn-extensions-route-traffic-through-a-proxy/)

## 📈 Trends

- **"Plug and Pwn" Techniques Abuse Windows Plug and Play**: Researchers demonstrated local privilege escalation to `NT AUTHORITY\SYSTEM` by emulating fake USB hardware via FaceDancer or RDP USB redirection, tricking Windows into executing vulnerable vendor co-installers without UAC prompts. [More info](https://www.bleepingcomputer.com/news/security/plug-and-pwn-attack-uses-fake-usb-devices-for-windows-system-access/)

- **Fake IT Workers and North Korean Remote Applicants Infiltrate Enterprise Hiring**: Security experts warn against fraudulent remote job applicants using AI-generated profiles, forged identities, and local proxy "laptop farms" to bypass vetting, exfiltrate IP, or extort employers. [More info](https://www.bleepingcomputer.com/news/security/the-threat-hiding-in-your-hiring-process-how-fake-remote-workers-get-in/)

- **Google Chrome Blocks 7 Billion Push Notifications Daily on Android**: Google implemented automated permissions revocation, rate limiting on abusive service worker senders, and simplified one-tap unsubscribe features to mitigate notification-based phishing and scam campaigns. [More info](https://www.helpnetsecurity.com/2026/08/12/google-chrome-abusive-web-push-notifications/) | [More info](https://www.bleepingcomputer.com/news/security/google-says-chrome-cuts-7-billion-unwanted-android-notifications-a-day-to-fight-abuse/)

- **WhatsApp & Signal Upgrade Messaging Privacy Features**: WhatsApp launched on-device "Scam Alert" ML detection for messages from unknown senders verified via Cloudflare-signed ledgers, while Signal introduced Automatic Key Verification using third-party audited key transparency logs to neutralize MITM attacks. [More info](https://www.securityweek.com/whatsapp-unveils-new-scam-alert-feature/) | [More info](https://www.bleepingcomputer.com/news/security/signal-adds-new-security-feature-to-thwart-man-in-the-middle-attacks/)

## 💥 Breaches & Leaks

- **FBI & NCAA Warn of Credential Harvester Attacks Targeting Media Accounts**: Law enforcement issued warnings regarding account compromise campaigns against student-athletes and adults using phishing links and fake verification lures to steal explicit photos for extortion and illicit market distribution. [More info](https://www.bleepingcomputer.com/news/security/fbi-warns-of-hackers-targeting-online-accounts-to-steal-explicit-photos/)

---

[⬅ Back to Archive](https://pranakn.github.io)
