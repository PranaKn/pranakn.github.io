---
title: "Cybersecurity Newsfeed - 31/03/26"
date: 2026-03-30 09:00:00 -0300
categories: [News]
permalink: /posts/news-31-03/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware, AI]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-03-31.png
  alt: Cybersecurity Newsfeed - 31/03/26
---

# Cybersecurity Newsfeed

## 📅 31/03/26

## 🛡️ Vulnerabilities

- **rsync Symbolic Link Bypass (CVE-2024-12084)**: A critical flaw in rsync's handling of symbolic links when `--inc-recursive` is enabled allows attackers to bypass directory restrictions. Users are urged to patch to version 3.3.0 or use `--safe-links` as a mitigation. [More info](https://kb.cert.org/vuls/id/655822)

- **OpenAI Codex Token Leakage**: Researchers discovered that prompt injection and indirect training data leakage can force OpenAI Codex to reveal sensitive GitHub personal access tokens, exposing private repositories to unauthorized access. [More info](https://hackread.com/openai-codex-vulnerability-steal-github-tokens/)

- **Fortinet & F5 BIG-IP Reclassified as RCE**: Previously known vulnerabilities in these appliances have been reclassified as critical remote code execution (RCE) flaws. Attackers can achieve full system compromise via the administrative interface without authentication. [More info](https://www.darkreading.com/application-security/fortinet-big-ip-vulnerability-reclassified-rce-exploitation)

- **CISA Adds New Flaw to KEV Catalog**: CISA has added a new vulnerability to its Known Exploited Vulnerabilities Catalog, signaling active exploitation. Organizations are mandated to remediate the flaw within a defined timeframe to mitigate risk. [More info](https://www.cisa.gov/news-events/alerts/2026/03/30/cisa-adds-one-known-exploited-vulnerability-catalog)

- **Telegram "No-Click" Remote Code Execution**: A critical "no-click" vulnerability in Telegram allows for RCE on target devices simply by receiving a specially crafted media message. The flaw stems from an issue in how the app processes certain data formats. [More info](https://www.darkreading.com/application-security/storm-brews-critical-no-click-telegram-flaw)

- **strongSwan VPN DoS (Integer Underflow)**: An integer underflow vulnerability in strongSwan can be exploited to crash the VPN service during the processing of IKEv2 packets. Administrators should update to version 5.9.14 or later. [More info](https://hackread.com/strongswan-flaw-attackers-crash-vpn-integer-underflow/)

- **Citrix NetScaler Memory Corruption**: A critical memory corruption flaw in NetScaler ADC and Gateway is being actively exploited for unauthorized data theft and session hijacking. Citrix has released emergency updates to address the buffer overflow. [More info](https://www.bleepingcomputer.com/news/security/critical-citrix-netscaler-memory-flaw-actively-exploited-in-attacks/)

- **FortiClient EMS Exploitation (CVE-2026-21643)**: A critical flaw in Fortinet’s FortiClient EMS allows unauthenticated attackers to execute arbitrary code with elevated privileges. Immediate patching is recommended as it is being exploited in the wild. [More info](https://www.helpnetsecurity.com/2026/03/30/forticlient-ems-cve-2026-21643-reported-exploitation/)

## 🎯 Adversaries

- **DeepLoad Malware Uses AI & ClickFix**: The DeepLoad credential stealer uses AI-generated code to enhance evasion and a "ClickFix" social engineering tactic to trick victims into executing malicious commands via PowerShell. [More info](https://www.darkreading.com/cyberattacks-data-breaches/ai-powered-deepload-steals-credentials-evades-detection) | [More info](https://thehackernews.com/2026/03/deepload-malware-uses-clickfix-and-wmi.html)

- **ROADK1LL WebSocket Implant**: Security researchers identified a new implant called ROADK1LL that utilizes WebSockets to facilitate persistence and lateral movement by masquerading as legitimate web traffic. [More info](https://www.bleepingcomputer.com/news/security/new-roadk1ll-websocket-implant-used-to-pivot-on-breached-networks/)

- **China-Linked APTs Target SE Asia**: Chinese threat groups launched a concentrated malware campaign against Southeast Asian government entities for long-term espionage, utilizing custom backdoors and edge device exploitation. [More info](https://securityaffairs.com/190174/apt/china-linked-groups-target-southeast-asian-government-with-advanced-malware-in-2025.html)

- **Russian CTRL Toolkit Phishing**: Russian-linked threat actors are distributing the "CTRL Toolkit," a modular set of post-exploitation tools for credential harvesting and network mapping, through targeted phishing. [More info](https://thehackernews.com/2026/03/russian-ctrl-toolkit-delivered-via.html)

- **Infinity Stealer Targets macOS**: A new malware dubbed Infinity Stealer is targeting macOS users with a Nuitka-packaged Python payload and "ClickFix" lures to steal browser data and crypto wallets. [More info](https://securityaffairs.com/190147/security/new-macos-infinity-stealer-uses-nuitka-python-payload-and-clickfix.html)

## 📈 Trends

- **Wave Browser & PUP Concerns**: Researchers identified privacy risks regarding Wave Browser and Ocean Cleanup Tab, classified as Potentially Unwanted Programs (PUPs) due to extensive data collection and system setting alterations. [More info](https://hackread.com/wave-browser-gaming-tools-ocean-cleanup-tab/)

- **Security in the "Machine Economy"**: The rise of autonomous agents handling crypto payments introduces new challenges, requiring robust authentication and secure execution environments to prevent systemic financial losses. [More info](https://hackread.com/payments-agents-crypto-in-the-machine-economy/)

- **AI-Enhanced Malware Evolution**: The use of AI in malware development, such as in DeepLoad, allows for rapid iteration of code obfuscation, creating more adaptive threats that challenge traditional security paradigms. [More info](https://www.infosecurity-magazine.com/news/deepload-malware-clickfix-ai-code/)

- **macOS Fights "ClickFix" Attacks**: Apple has introduced a new security feature in macOS that alerts users when they attempt to paste commands into the Terminal that are known to be associated with social engineering attacks. [More info](https://www.malwarebytes.com/blog/news/2026/03/new-macos-security-feature-will-alert-users-about-possible-clickfix-attacks) | [More info](https://www.bleepingcomputer.com/news/security/apple-adds-macos-terminal-warning-to-block-clickfix-attacks/)

## 💥 Breaches & Leaks

- **CareCloud Data Breach**: Healthcare provider CareCloud confirmed a data breach involving unauthorized access to patient names, contact details, and medical records. Forensic investigations and law enforcement notifications are underway. [More info](https://www.bleepingcomputer.com/news/security/healthcare-tech-firm-carecloud-says-hackers-stole-patient-data/)

- **Alleged Lockheed Martin Data Leak**: A threat actor claims to be selling 375TB of data belonging to defense contractor Lockheed Martin on a dark web marketplace, including sensitive information on military and aerospace technology. [More info](https://hackread.com/dark-web-market-375tb-lockheed-martin-data/)

---

[⬅ Back to Archive](https://pranakn.github.io)
