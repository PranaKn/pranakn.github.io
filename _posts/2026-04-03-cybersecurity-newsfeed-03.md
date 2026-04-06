---
title: "Cybersecurity Newsfeed - 03/04/26"
date: 2026-04-02 09:00:00 -0300
categories: [News]
permalink: /posts/news-03-04/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-04-03.png
  alt: Cybersecurity Newsfeed - 03/04/26
---

# Cybersecurity Newsfeed

## 📅 03/04/26

## 🛡️ Vulnerabilities

- **Active Exploitation of CVE-2025-55182**: Attackers are weaponizing a critical vulnerability in widely used web frameworks to achieve remote code execution. The flaw allows unauthorized users to bypass authentication and execute commands with administrative privileges. [More info](https://thehackernews.com/2026/04/hackers-exploit-cve-2025-55182-to.html)

- **CISA Adds New Flaw to KEV Catalog**: CISA has updated its Known Exploited Vulnerabilities catalog with a new flaw being leveraged in the wild. Federal agencies are mandated to remediate this vulnerability within a set deadline to secure their networks. [More info](https://www.cisa.gov/news-events/alerts/2026/04/02/cisa-adds-one-known-exploited-vulnerability-catalog)

- **Progress ShareFile Pre-Auth RCE**: Researchers discovered that multiple vulnerabilities in Progress ShareFile can be chained to achieve pre-authentication remote code execution, potentially leading to full system compromise. [More info](https://www.bleepingcomputer.com/news/security/new-progress-sharefile-flaws-can-be-chained-in-pre-auth-rce-attacks/)

- **14,000 F5 BIG-IP Instances Exposed**: Despite available patches, thousands of F5 BIG-IP APM instances remain vulnerable to a critical RCE flaw that allows unauthenticated attackers to execute arbitrary commands via the management interface. [More info](https://www.bleepingcomputer.com/news/security/over-14-000-f5-big-ip-apm-instances-still-exposed-to-rce-attacks/)

- **Fourth Google Chrome Zero-Day of 2026**: Google released an emergency update for a high-severity flaw in the V8 JavaScript engine (exploited in the wild) that allows arbitrary code execution within the browser sandbox. [More info](https://www.bleepingcomputer.com/news/security/google-fixes-fourth-chrome-zero-day-exploited-in-attacks-in-2026/)

- **Windows WhatsApp Attachment Backdoor**: A critical flaw in how Windows handles WhatsApp attachments could allow attackers to establish backdoors on PCs through specifically crafted media files. [More info](https://hackread.com/microsoft-whatsapp-attachments-backdoor-windows-pcs/)

- **Apple Expands iOS 18 Security Patches**: Critical updates have been extended to more iPhone models to block "Darksword" attacks that bypass standard protections. [More info](https://www.bleepingcomputer.com/news/security/apple-expands-ios-18-updates-to-more-iphones-to-block-darksword-attacks/)

## 🎯 Adversaries

- **ShinyHunters Claims Cisco Breach**: The notorious group claims to have leaked internal Cisco records, including employee credentials and project documentation, posing a risk to the firm's operational security. [More info](https://hackread.com/shinyhunters-hackers-cisco-records-data-leak/)

- **Akira Ransomware Accelerates Attack Chain**: The group has optimized its tactics to move from initial access to full data encryption in just a few hours by leveraging compromised VPN credentials and unpatched flaws. [More info](https://cyberscoop.com/akira-ransomware-initial-access-to-encryption-in-hours/)

- **UAC-0255 Impersonates CERT-UA**: Threat actors are using phishing emails disguised as urgent security updates from the Ukrainian CERT to distribute "AgeWheeze" malware for data exfiltration. [More info](https://securityaffairs.com/190287/hacking-threat-actor-uac-0255-impersonate-cert-ua-to-spread-agewheeze-malware-via-phishing.html)

- **Qilin Ransomware's EDR Killer**: A new variant of Qilin ransomware specifically targets and disables Endpoint Detection and Response (EDR) software to operate without interference. [More info](https://blog.talosintelligence.com/qilin-edr-killer/)

- **Italian Spyware Vendor Fakes WhatsApp**: A targeted surveillance campaign in the Mediterranean utilized a fake WhatsApp application to monitor calls and messages of approximately 200 users. [More info](https://securityaffairs.com/190276/malware-italian-spyware-vendor-creates-fake-whatsapp-app-targeting-200-users.html)

- **CrystalRAT Hybrid Malware**: This new threat combines traditional Remote Access Trojan features with "prankware" capabilities to manipulate desktop environments and cause distress. [More info](https://www.bleepingcomputer.com/news/security/new-crystalrat-malware-adds-rat-stealer-and-prankware-features/)

- **Yurei Ransomware's "Stranger Things" Theme**: A new strain of ransomware uses pop-culture references while employing sophisticated evasion techniques to terminate security processes. [More info](https://hackread.com/yurei-ransomware-tools-stranger-things-references/)

## 📈 Trends

- **Trojanized Claude Code on GitHub**: Attackers are distributing a malicious version of Anthropic’s Claude Code tool embedded with infostealers, targeting developers' credentials and session tokens. [More info](https://www.bleepingcomputer.com/news/security/claude-code-leak-used-to-push-infostealer-malware-on-github/) | [Additional info](https://www.theregister.com/2026/04/02/trojanized_claude_code_leak_github/)

- **Google Workspace Continuous Security**: Google Cloud has introduced a dynamic, AI-driven security approach for Workspace to move away from static configurations and provide real-time threat detection. [More info](https://security.googleblog.com/2026/04/google-workspaces-continuous-approach.html)

- **Cookie-Controlled PHP Webshells**: Microsoft detailed new tradecraft where attackers use HTTP cookies to trigger execution of webshells in Linux environments, making them harder to detect than traditional scripts. [More info](https://www.microsoft.com/en-us/security/blog/2026/04/02/cookie-controlled-php-webshells-tradecraft-linux-hosting-environments/)

- **The Rise of Storm and Venom Infostealers**: New Malware-as-a-Service (MaaS) platforms like Storm and Venom Stealer are automating the theft of browser credentials and crypto wallets at scale. [Storm Info](https://hackread.com/storm-infostealer-sold-as-service-browsers-wallets/) | [Venom Info](https://www.infosecurity-magazine.com/news/venom-stealer-maas-automates-data/)

- **UAT-10608 Credential Harvesting**: A large-scale automated operation is using a distributed bot network to perform credential stuffing and brute-force attacks across various industries. [More info](https://blog.talosintelligence.com/uat-10608-inside-a-large-scale-automated-credential-harvesting-operation-targeting-web-applications/)

- **Defending Encryption in the Post-Quantum Era**: The security community is shifting focus toward post-quantum cryptography (PQC) to protect against future quantum-enabled decryption of RSA and ECC. [More info](https://hackread.com/defending-encryption-in-the-post-quantum-era/)

## 💥 Breaches & Leaks

- **Hasbro Discloses Cybersecurity Incident**: The toy giant reported an attack that disrupted operations, necessitating system isolation and the involvement of forensic experts to investigate potential data exposure. [More info](https://www.darkreading.com/cyberattacks-data-breaches/toying-around-hasbro-attack-remediate)

- **Drift DeFi Protocol Loses $280M**: Hackers seized control of the platform's Security Council governance powers, allowing them to bypass protocols and authorize massive unauthorized withdrawals. [More info](https://www.bleepingcomputer.com/news/security/drift-loses-280-million-as-hackers-seize-security-council-powers/)

## 📚 Others

- **Undocumented BitLocker FVE APIs**: Research into Windows disk encryption revealed hidden functions that allow deeper interaction with the encryption engine, relevant for both forensics and potential exploitation. [More info](https://itm4n.github.io/bitlocker-little-secrets-the-undocumented-fve-api/)

- **Red Hat Launching ELS Premium**: A new service provides security patches for legacy Linux distributions, targeting organizations unable to migrate immediately from aging systems. [More info](https://www.helpnetsecurity.com/2026/04/02/red-hat-enterprise-linux-extended-life-cycle-premium/)

- **FBI Warning on Chinese Mobile Apps**: The Bureau issued an advisory regarding data security risks and excessive permissions in Chinese-developed apps that could facilitate unauthorized data collection. [More info](https://www.bleepingcomputer.com/news/security/fbi-warns-against-using-chinese-mobile-apps-over-to-data-security-risks/)

- **Google Drive Ransomware Detection**: Paid Google Drive users now have ransomware detection enabled by default, using machine learning to identify and block suspicious file modification patterns. [More info](https://www.bleepingcomputer.com/news/security/google-drive-ransomware-detection-now-on-by-default-for-paying-users/)

---

[⬅ Back to Archive](https://pranakn.github.io)
