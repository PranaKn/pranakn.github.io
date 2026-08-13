---
title: "Cybersecurity Newsfeed - 14/08/26"
date: 2026-08-13 09:00:00 -0300
categories: [News]
permalink: /posts/news-14-08-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-08-14.png
  alt: Cybersecurity Newsfeed - 14/08/26
---

# Cybersecurity Newsfeed

## 📅 14/08/26

## 🛡️ Vulnerabilities

- **Microsoft Patches "LegacyHive" Windows Zero-Day (CVE-2026-62832)**: Microsoft addressed a local privilege escalation flaw in the Windows User Profile Service. Authenticated local attackers can exploit improper link resolution during file access to load and modify registry hives, gaining administrator privileges without user interaction. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-patches-legacyhive-windows-zero-day-vulnerability/)

- **Critical VMware vCenter RCE Flaw Under Exploitation (CVE-2026-59310)**: Threat actors are actively exploiting a critical directory traversal vulnerability (CVSS 9.8) in VMware vCenter Syslog Server. Attackers are leveraging unauthenticated remote code execution to deploy `reverse_ssh` for persistent C2 access across hundreds of exposed instances worldwide. [More info](https://www.bleepingcomputer.com/news/security/critical-vmware-vcenter-rce-flaw-exploited-for-reverse-ssh-access/) | [More info](https://www.infosecurity-magazine.com/news/vcenter-cve-2026-59310-exploited/)

- **WordPress 7.0.4 Fixes High-Severity RCE (CVE-2026-65640)**: WordPress released security updates to patch an RCE flaw (CVSS 8.8) affecting sites using ImageMagick alongside Ghostscript. Authenticated users with Author privileges or higher can upload crafted files with embedded PostScript to trigger arbitrary command execution. [More info](https://www.securityweek.com/wordpress-7-0-4-patches-remote-code-execution-vulnerability/)

- **Active Attacks Target Microsoft SharePoint Auth Bypass (CVE-2026-55040)**: Following public PoC disclosure, automated exploit attempts are targeting a critical authentication bypass flaw (CVSS 9.1) in SharePoint Server. Improper JWT token validation allows unauthenticated remote attackers to forge tokens and impersonate any user or administrator. [More info](https://securityaffairs.com/197137/hacking/sharepoint-cve-2026-55040-comes-under-attack-following-public-exploit.html)

- **ShieldBreak Zero-Day Exploit Targets Microsoft Defender (CVE-2026-50656)**: Security researcher Nightmare Eclipse published a local privilege escalation PoC targeting Microsoft Defender on Windows 11 and Server 2025. The exploit leverages Cloud Filter API callback hooks to manipulate System32 file swapping and execute arbitrary code as SYSTEM via missing DLLs. [More info](https://www.securityweek.com/nightmare-eclipse-drops-windows-zero-day-exploit-shieldbreak/)

- **Wireshark 4.6.8 Resolves 28 Security Vulnerabilities**: The update patches high-risk parser flaws in pcapng, Endace ERF, and Tektronix K12xx formats that can trigger memory corruption when opening malicious packet captures, alongside fixes for RDP, SSH, and Kerberos dissectors. [More info](https://www.helpnetsecurity.com/2026/08/13/wireshark-4-6-8-patches-security-bugs/)

- **Critical Adobe Commerce & Magento Auth Bypass (CVE-2026-71362)**: Unauthenticated threat actors are exploiting an authorization bypass vulnerability in Adobe Commerce and Magento platforms to swap session contexts and hijack customer accounts without credentials. [More info](https://www.bleepingcomputer.com/news/security/hackers-exploit-critical-adobe-commerce-flaw-to-hijack-customer-accounts/)

## 🎯 Adversaries

- **Akira Ransomware Disables EDR via Safe Mode Reboot**: An Akira ransomware affiliate gained initial access via an unauthenticated SonicWall VPN, rebooted an application server into Safe Mode with Networking to bypass Defender and EDR protections, and exfiltrated file shares using `s5cmd` and AnyDesk before execution failed due to low memory. [More info](https://www.bleepingcomputer.com/news/security/akira-hackers-disable-edr-with-safe-mode-steal-data-but-fail-to-encrypt/)

- **Jewelbug Compromises Govt Webmail & Conducts Crypto Fraud**: Chinese APT group Jewelbug breached government webmail servers across 15 Middle Eastern tenants to deploy the Antino backdoor and the PDF Viewer extension, while simultaneously running large-scale AI-driven cryptocurrency fraud schemes using a C2 panel called XG-Web. [More info](https://www.bleepingcomputer.com/news/security/hackers-breach-govt-webmail-while-running-parallel-crypto-fraud/) | [More info](https://www.darkreading.com/threat-intelligence/jewelbug-apt-state-espionage-cryptocurrency-theft)

- **Storm-1175 Deploys New StormEncryptor Ransomware**: Threat actor Storm-1175 has moved away from Medusa to deploy a custom C++ ransomware called StormEncryptor. The group weaponizes edge device vulnerabilities like N-able (CVE-2026-18577), ConnectWise, and SmarterMail to complete full domain compromise within 24 hours. [More info](https://securityaffairs.com/197119/malware/storm-1175-replaces-medusa-with-new-stormencryptor-ransomware.html)

- **Armored Likho Espionage Campaign Uses Still Toolkit**: Kaspersky uncovered a targeted campaign against Russian government and enterprise entities using droppers disguised as donation apps. The malware suite includes Still Sync (exfiltrating Telegram chats/media via gRPC) and Still Audio (covert microphone surveillance). [More info](https://securelist.com/armored-likho-still-toolkit/121033/)

- **Lazarus Group Weaponizes Windows Zero-Day (CVE-2026-68820)**: North Korean APT Lazarus launched an Operation Dream Job campaign targeting defense firms in France, Germany, Brazil, and India. The attack chain exploits an AFD.sys kernel driver privilege escalation flaw to deploy the MISTPEN downloader, Troy backdoor, and FudModule 3.1 rootkit. [More info](https://securityaffairs.com/197098/uncategorized/north-korean-lazarus-group-uses-windows-zero-day-in-operation-dream-job.html)

- **SpyNote and WindRelay Malware Pair for Android NFC Fraud**: A new mobile campaign combines the SpyNote RAT with WindRelay NFC relay malware. Attackers impersonate bank support to trick victims into side-loading the malware, taking out fraudulent loans, and relaying physical credit card taps to perform instant fraud. [More info](https://www.bleepingcomputer.com/news/security/android-malware-combo-takes-out-loans-and-relays-victims-credit-cards/)

- **Ukraine Shuts Down 94 Fraudulent Call Centers**: Authorities in Ukraine conducted 411 searches and dismantled 94 illegal call center operations targeting domestic and EU citizens through financial and investment scams. Law enforcement seized 3,300+ computers, 5,200 SIM cards, crypto wallet credentials, and millions in cash. [More info](https://www.bleepingcomputer.com/news/security/ukraine-shuts-down-94-fraudulent-call-centers-seize-millions-in-cash/)

## 📈 Trends

- **Emergence of Unverified AI Watermark Removers**: Following Anthropic's text watermarking in Claude outputs for EU AI Act compliance, open-source and commercial utilities claiming to strip AI watermarks have flooded the web. Analysts warn that integrating these unverified tools into developer agent pipelines poses software supply chain security risks. [More info](https://www.bleepingcomputer.com/news/security/ai-watermark-removers-flood-the-web-almost-none-can-prove-they-work/)

- **US Presidential Memorandum Authorizes Private Offensive Cyber Ops**: A new policy allows vetted private US firms to conduct government-sanctioned offensive cyber operations and surveillance against foreign ransomware and fraud networks under DOJ and DHS task force oversight. [More info](https://www.helpnetsecurity.com/2026/08/13/usa-private-companies-offensive-cyber-operations/)

- **Google Cloud Releases Post-Quantum Cryptography Roadmap**: Google outlined key PQC milestones running through 2028 to protect against "store-now-decrypt-later" threats. The roadmap includes implementing hybrid ML-KEM key exchange, deploying ML-DSA/SLH-DSA in Cloud KMS, and using Merkle Tree Certificates for TLS. [More info](https://www.infosecurity-magazine.com/news/google-cloud-post-quantum-roadmap/)

- **WhatsApp Tests On-Device ML Scam Alerts**: WhatsApp introduced an optional Scam Alert feature using local, on-device machine learning models to detect fraud structures from unknown numbers without breaking end-to-end encryption or transmitting user content to Meta servers. [More info](https://www.bleepingcomputer.com/news/security/whatsapp-rolls-out-new-feature-that-flags-potential-scam-messages/)

- **Cloudflare H1 2026 DDoS Report Highlights Hyper-Volumetric Attacks**: Cloudflare reported peak attack traffic of 6.46 trillion requests in April 2026. DNS floods accounted for 34.3% of network-layer activity, CLDAP reflection attacks surged 580%, and Brazil surfaced as the top source country for global DDoS traffic. [More info](https://www.helpnetsecurity.com/2026/08/13/cloudflare-h1-2026-ddos-trends-report/)

## 💥 Breaches & Leaks

- **Trezor Discloses Breach Affecting 14k Customers**: Hardware wallet maker Trezor alerted 13,689 customers following a cyberattack at logistics provider ShipMonk. Attackers exploited a Metabase SQL injection zero-day to steal names, emails, phone numbers, and shipping addresses. Internal Trezor systems and wallet seed phrases were not compromised. [More info](https://www.bleepingcomputer.com/news/security/trezor-discloses-data-breach-affecting-nearly-14-000-customers/)

---

[⬅ Back to Archive](https://pranakn.github.io)
