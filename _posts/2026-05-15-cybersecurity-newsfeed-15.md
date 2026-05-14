---
title: "Cybersecurity Newsfeed - 15/05/26"
date: 2026-05-14 09:00:00 -0300
categories: [News]
permalink: /posts/news-15-05-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-05-15.png
  alt: Cybersecurity Newsfeed - 15/05/26
---

# Cybersecurity Newsfeed

## 📅 15/05/26

## 🛡️ Vulnerabilities

- **Cisco Catalyst SD-WAN Critical Zero-Day (CVE-2026-3021)**: Cisco has confirmed active exploitation of a maximum-severity flaw (CVSS 10.0) in its SD-WAN Manager. Unauthenticated, remote attackers can bypass authentication via the web management interface to gain full administrative control. Urgent patches have been released. [More info](https://www.bleepingcomputer.com/news/security/cisco-warns-of-new-critical-sd-wan-flaw-exploited-in-zero-day-attacks/)

- **Burst Statistics WordPress Plugin Auth Bypass (CVE-2026-4039)**: Attackers are actively exploiting a flaw in the Burst Statistics plugin to gain administrative access by manipulating specific API endpoints. Administrators are urged to update to version 1.5.9 immediately. [More info](https://www.bleepingcomputer.com/news/security/hackers-exploit-auth-bypass-flaw-in-burst-statistics-wordpress-plugin/)

- **PraisonAI Authentication Bypass (CVE-2026-44338)**: A critical flaw in the popular AI orchestration framework allows unauthenticated remote attackers to gain administrative access to the management console, potentially exposing sensitive AI models and training data. [More info](https://thehackernews.com/2026/05/praisonai-cve-2026-44338-auth-bypass.html)

- **Linux Kernel "Fragnesia" (CVE-2026-1045)**: A heap buffer overflow in the network packet fragmentation logic allows local users to gain root access. This poses a significant threat to multi-user systems and cloud environments. [More info](https://securityaffairs.com/192145/uncategorized/linux-kernel-bug-fragnesia-allows-local-root-access-attacks.html)

- **18-Year-Old Nginx Rewrite Flaw (CVE-2026-1189)**: A legacy vulnerability in Nginx's rewrite module can trigger a stack-based buffer overflow via crafted URIs, leading to DoS or potential RCE. Organizations are encouraged to update and review configurations. [More info](https://www.bleepingcomputer.com/news/security/18-year-old-nginx-vulnerability-allows-dos-potential-rce/)

- **F5 Patches 50+ Vulnerabilities**: F5 released security updates for BIG-IP and BIG-IQ systems to address high-severity flaws involving improper input validation and insecure default configurations. [More info](https://www.securityweek.com/f5-patches-over-50-vulnerabilities/)

- **Windows BitLocker Bypass Zero-Days**: New vulnerabilities allow attackers with physical access to bypass BitLocker encryption by intercepting keys during the boot process or exploiting Secure Boot weaknesses. [More info](https://thehackernews.com/2026/05/windows-zero-days-expose-bitlocker.html)

- **CISA KEV Update**: CISA has added a new critical vulnerability to its Known Exploited Vulnerabilities catalog following reports of active exploitation, mandating prioritization for patching. [More info](https://www.cisa.gov/news-events/alerts/2026/05/14/cisa-adds-one-known-exploited-vulnerability-catalog)

## 🎯 Adversaries

- **FrostyNeighbor APT Targets Eastern Europe**: A new APT group is conducting targeted cyber-espionage against government organizations in Poland and Ukraine, utilizing a bespoke toolkit for data exfiltration and surveillance. [More info](https://www.darkreading.com/cyberattacks-data-breaches/frostyneighbor-apt-govt-orgs-poland-ukraine)

- **Mustang Panda Deploys FDMTP Backdoor**: The threat group is targeting the Asia-Pacific (APJ) region with a new modular backdoor designed for stealthy data exfiltration and persistent access. [More info](https://www.infosecurity-magazine.com/news/mustang-panda-fdmtp-backdoor-apj/)

- **FamousSparrow Exploits Exchange Servers**: This APT is targeting the oil and gas industry by leveraging Microsoft Exchange vulnerabilities to maintain persistence and exfiltrate sensitive corporate data. [More info](https://hackread.com/famoussparrow-oil-gas-ms-exchange-server-exploit/)

- **Kazuar Botnet Analysis**: Microsoft published a deep dive into the Kazuar backdoor, used by nation-state actors, highlighting its updated evasion techniques and modular payloads. [More info](https://www.microsoft.com/en-us/security/blog/2026/05/14/kazuar-anatomy-of-a-nation-state-botnet/)

- **Kimsuky Uses AppleSeed & PebbleDash**: The threat group is targeting South Korean entities with sophisticated phishing campaigns to deploy data-stealing backdoors. [More info](https://securelist.com/kimsuky-appleseed-pebbledash-campaigns/119785/)

- **Kongtuke Hackers Shift to Microsoft Teams**: Attackers are bypassing traditional email security by using Teams as a primary vector for corporate breaches, delivering malicious files via compromised guest accounts. [More info](https://www.bleepingcomputer.com/news/security/kongtuke-hackers-now-use-microsoft-teams-for-corporate-breaches/)

- **Windows 11 & Edge Hacked at Pwn2Own**: On the first day of Pwn2Own Berlin 2026, security researchers successfully demonstrated exploit chains against Microsoft’s software to achieve remote code execution. [More info](https://www.bleepingcomputer.com/news/security/windows-11-and-microsoft-edge-hacked-on-first-day-of-pwn2own-berlin-2026/)

## 📈 Trends

- **AI Cybersecurity "Valley of Death"**: Investment in AI-driven security faces challenges as startups struggle to transition from pilot programs to full-scale adoption due to ROI and integration hurdles. [More info](https://www.darkreading.com/cybersecurity-operations/ai-cybersecurity-investments-valley-death)

- **Cyber-Enabled Cargo Theft**: Cybercriminals are increasingly blending digital and physical tactics to facilitate cargo theft by compromising logistics platforms and stealing freight credentials. [More info](https://www.bleepingcomputer.com/news/security/cyber-enabled-cargo-crime-how-cybercrime-tradecraft-is-used-to-steal-freight/)

- **Supply Chain Threats in Open Source**: Recent attacks on Node.js IPC packages and the TanStack library ecosystem underscore the persistent risk of targeting developer dependencies to steal sensitive data. [More info](https://thehackernews.com/2026/05/stealer-backdoor-found-in-3-node-ipc.html)

- **"JobStealer" Malware Campaign**: A new cross-platform threat is targeting job seekers on Windows and macOS through fraudulent interview invitations and fake video conferencing tools. [More info](https://hackread.com/fake-job-interview-jobstealer-malware-windows-macos/)

## 💥 Breaches & Leaks

- **OpenAI / TanStack Supply Chain Breach**: OpenAI confirmed a breach involving a supply chain attack on the TanStack library, resulting in the injection of malicious code via a compromised maintainer account. [More info](https://www.bleepingcomputer.com/news/security/openai-confirms-security-breach-in-tanstack-supply-chain-attack/)

- **West Pharmaceutical Services Ransomware**: The healthcare supplier confirmed a cyberattack that led to data theft and the encryption of internal systems, disrupting some operations. [More info](https://www.bleepingcomputer.com/news/security/west-pharmaceutical-says-hackers-stole-data-encrypted-systems/)

## 📚 Others

- **Dream Market Administrator Charged**: U.S. authorities have charged a suspected administrator of the dark web marketplace Dream Market following an international investigation and arrest in Germany. [More info](https://www.bleepingcomputer.com/news/security/us-charges-suspected-dream-market-admin-arrested-in-germany/)

- **SecurityScorecard Acquires Driftnet**: The acquisition aims to enhance digital footprint monitoring and supply chain risk management by integrating Driftnet’s specialized threat intelligence datasets. [More info](https://www.darkreading.com/cyber-risk/securityscorecard-snags-driftnet-to-level-up-threat-intelligence)

---

[⬅ Back to Archive](https://pranakn.github.io)
