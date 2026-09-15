---
title: "Cybersecurity Newsfeed - 16/09/26"
date: 2026-09-15 09:00:00 -0300
categories: [News]
permalink: /posts/news-16-09-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-09-16.png
  alt: Cybersecurity Newsfeed - 16/09/26
---

# Cybersecurity Newsfeed

## 📅 16/09/26

## 🛡️ Vulnerabilities

- **Record Apple Security Update Patch Release**: Apple released a massive security update covering iOS, iPadOS, macOS, and visionOS. The updates fix flaw types including memory corruption, logic issues, and remote code execution across core components like WebKit and the kernel. [More info](https://www.theregister.com/security/2026/09/15/the-vulnpocalypse-rains-ibugs-down-on-apple-with-record-setting-number-of-patches/5296679)

- **Acronis Privilege Escalation Flaw (CVE-2026-87886)**: Acronis warned of an actively exploited high-severity flaw in its backup integration plugins for cPanel, WHM, and Plesk. The vulnerability enables low-privileged Linux attackers to elevate privileges without user interaction. [More info](https://www.bleepingcomputer.com/news/security/acronis-warns-of-actively-exploited-flaw-in-its-cpanel-backup-plugin/)

- **Critical WooCommerce Lead Capture Flaw (CVE-2026-27540)**: Attackers are actively targeting an unauthenticated arbitrary file-upload flaw in older versions of the WooCommerce Wholesale Lead Capture WordPress plugin to drop PHP web shells. [More info](https://www.bleepingcomputer.com/news/security/hackers-target-wordpress-sites-via-third-party-woocommerce-plugin/)

- **Ransomware Gangs Exploit VMware vCenter Flaw (CVE-2026-59310)**: CISA updated its KEV catalog warning that ransomware groups are actively exploiting a critical directory traversal vulnerability in VMware vCenter Server Syslog service for root-level remote code execution. [More info](https://www.bleepingcomputer.com/news/security/cisa-critical-vmware-vcenter-rce-flaw-now-exploited-by-ransomware-gangs/)

- **Rapid Marimo Notebooks RCE Exploitation (CVE-2026-39987)**: Security researchers detailed an intrusion where an attacker exploited a critical RCE vulnerability in Marimo notebooks to pivot to an SSH bastion host in just eight seconds during a targeted key-harvesting campaign. [More info](https://thehackernews.com/2026/09/human-attacker-exploits-marimo-rce.html)

- **Mass-Scanning Campaign Exploits Vite Servers (CVE-2026-39364)**: A high-severity data disclosure flaw in Vite development servers is under active scanning, allowing unauthenticated attackers to extract environment variables and cloud credentials via crafted HTTP queries. [More info](https://thehackernews.com/2026/09/mass-scanning-campaign-exploits-vite.html)

- **Cisco Secure Email Gateway Zero-Day (CVE-2026-76461)**: Cisco patched an actively exploited SQL injection vulnerability in AsyncOS for Secure Email Gateway appliances that allowed unauthenticated remote command execution via crafted email parsing. [More info](https://www.helpnetsecurity.com/2026/09/15/cve-2026-76461-cisco-email-gateway-zero-day-exploited/)

- **Telegram Desktop Export Function XSS Flaw**: A stored cross-site scripting vulnerability in Telegram Desktop's HTML chat export feature allowed malicious bots to inject JavaScript that executed when users opened exported HTML files in browsers. [More info](https://securityaffairs.com/199076/security/telegram-desktop-flaw-could-turn-old-chat-exports-into-data-theft-traps.html)

- **Critical Check Point VPN RCE Flaws (CVE-2026-85102, CVE-2026-85103)**: Dutch NCSC warned of two CVSS 9.8 vulnerabilities impacting Check Point VPN products that allow unauthenticated remote code execution via VPN negotiation and ASN.1 certificate decoding. [More info](https://securityaffairs.com/199015/security/dutch-ncsc-warns-critical-check-point-vpn-flaws-put-networks-at-risk.html)

## 🎯 Adversaries

- **Admin Menu Editor Pro Compromise Backdoors Sites**: Threat actors compromised the plugin developer's site to distribute trojanized versions (2.35 & 2.36) containing web shells and rogue admin account creation scripts, affecting ~1,500 WordPress sites. [More info](https://www.bleepingcomputer.com/news/security/malcious-admin-menu-editor-pro-plugin-backdoors-1-500-wordpress-sites/)

- **KREMLIN Banking Malware Targets Brazilian Institutions**: A multi-stage banking malware toolkit uses Ethereum smart contracts as C2 resolvers and installs malicious Chrome/Edge extensions by bypassing Chromium integrity controls. [More info](https://thehackernews.com/2026/09/kremlin-banking-malware-hijacks-chrome.html)

- **Iranian Actors Deploy Telegram-Controlled Malware**: Iranian hackers are targeting dissidents and journalists with custom malware that uses Telegram bot infrastructure to disguise C2 communication as benign traffic. [More info](https://thehackernews.com/2026/09/iranian-hackers-use-telegram-controlled.html)

- **VectraRAT MaaS Targets Enterprise Workstations**: A newly identified malware-as-a-service platform offered for $250/month features UAC bypass, hidden desktop sessions, and automated credential harvesting delivered via ClickFix and loaders. [More info](https://www.darkreading.com/endpoint-security/vectrarat-hack-windows-enterprises)

- **BambooToken Framework Uses MQTT Protocol for C2**: The multi-platform BambooToken malware targets Windows and Linux across Asia and South America, leveraging MQTT publish-subscribe messaging and DLL sideloading for persistence and telemetry exfiltration. [More info](https://thehackernews.com/2026/09/bambootoken-malware-uses-mqtt-to.html) | [More info](https://www.bleepingcomputer.com/news/security/bambootoken-malware-controls-windows-and-linux-systems-via-mqtt/)

- **HBO Max Verified Reddit Account Hijacked for Malware**: Threat actors hijacked HBO Max's verified Reddit account to push 108 malicious ads that leveraged ClickFix lures to install Atomic Stealer and MacSync info-stealers. [More info](https://www.malwarebytes.com/blog/news/2026/09/hbo-maxs-verified-reddit-account-hijacked-to-spread-malware)

- **China-Linked Hackers Exploit Chrome Zero-Day Chain**: Attackers combined Chrome V8 zero-days (CVE-2026-85046, CVE-2026-87491) with a Windows ALPC vulnerability (CVE-2026-85880) to escape sandboxes and deploy the GRIMWEDGE backdoor. [More info](https://thehackernews.com/2026/09/china-linked-hackers-exploit-chrome.html)

## 📈 Trends

- **UltraViolet Cyber Releases Equinox Detection Platform**: Equinox automates SIEM and EDR log coverage analysis against MITRE ATT&CK and MITRE ATLAS frameworks to validate rules and detect coverage gaps in under 30 minutes. [More info](https://www.helpnetsecurity.com/2026/09/15/ultraviolet-cyber-equinox/)

- **Rethinking Zero-Day Response in the AI Era**: Industry experts highlight how AI-driven exploit automation requires organizations to adopt continuous attack path testing and agentic pen-testing rather than relying strictly on reactive patching. [More info](https://www.bleepingcomputer.com/news/security/what-zero-day-response-should-be-in-the-post-mythos-era/)

- **Focusing Defense on End-to-End Attack Chains**: Security analysis emphasizes evaluating full attack chains rather than isolated techniques to identify choke points across initial access, lateral movement, and privilege escalation. [More info](https://thehackernews.com/2026/09/attack-chains-not-just-attack-surfaces.html)

## 💥 Breaches & Leaks

- **CenterPoint Energy Confirms Data Exfiltration**: A threat actor scraped an unauthenticated, non-rate-limited public API to steal 7.49 million customer records containing names, addresses, account details, and partial SSNs. [More info](https://www.bleepingcomputer.com/news/security/centerpoint-energy-confirms-customer-data-stolen-in-cyberattack/)

- **Japan Digital Agency Discloses VPN Appliance Leak**: A non-zero-day VPN flaw and compromised credentials resulted in the exposure of ~246,000 personnel records across 23 government ministries. [More info](https://securityaffairs.com/199090/security/non-zero-day-vpn-flaw-left-japan-government-shared-network-platform-exposed-246000-records-at-risk.html)

- **Revolut Duped by Government Impostor Scam**: An attacker impersonating a government agency via a legitimate government email domain successfully submitted fraudulent data requests, compromising customer IDs, selfies, and statements. [More info](https://www.malwarebytes.com/blog/news/2026/09/revolut-gave-customer-ids-and-financial-data-to-a-government-impostor)

## ⚖️ Legal & Law Enforcement

- **Black Axe Cybercrime Leaders Extradited to US**: Five alleged senior members of the Black Axe syndicate were extradited from South Africa to the US to face wire fraud, money laundering, and identity theft charges. [More info](https://www.bleepingcomputer.com/news/security/black-axe-gang-members-extradited-to-us-face-cybercrime-charges/)

## 📚 Others

- **Microsoft Releases Emergency Out-of-Band Patch**: Microsoft issued emergency update KB5129195 to resolve widespread instability, freeze, Remote Desktop, and Hyper-V errors caused by September Patch Tuesday updates. [More info](https://www.infosecurity-magazine.com/news/microsoft-releases-emergency-patch/)

---

[⬅ Back to Archive](https://pranakn.github.io)
