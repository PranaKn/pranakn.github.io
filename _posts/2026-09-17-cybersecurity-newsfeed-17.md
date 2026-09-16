---
title: "Cybersecurity Newsfeed - 17/09/26"
date: 2026-09-16 09:00:00 -0300
categories: [News]
permalink: /posts/news-17-09-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-09-17.png
  alt: Cybersecurity Newsfeed - 17/09/26
---

# Cybersecurity Newsfeed

## 📅 17/09/26

## 🛡️ Vulnerabilities

- **CISA Adds Cisco ISE and Acronis Flaws to KEV**: CISA added two exploited flaws to its catalog: CVE-2026-76460 in Cisco Identity Services Engine (privileged API issue leading to RCE) and CVE-2026-87886 in Acronis Backup plugins for cPanel/WHM (default permission flaw enabling local privilege escalation). Federal agencies must remediate both under BOD 26-04. [More info](https://www.cisa.gov/news-events/alerts/2026/09/16/cisa-adds-two-known-exploited-vulnerabilities-catalog)

- **Critical Hard-Coded JWT Key in Issabel Framework PBX (CVE-2026-89026)**: A hard-coded HS256 JWT key in Issabel PBX's `pbxapi` endpoint allows unauthenticated attackers to forge bearer tokens and execute arbitrary OS commands under Asterisk user privileges. Active exploitation was detected following a patch release. [More info](https://thehackernews.com/2026/09/attackers-exploit-issabel-framework.html)

- **CISA Warns of Exploited Google Pixel Modem Flaw (CVE-2026-58704)**: An improper authorization vulnerability in Google Pixel modem firmware allows actors to bypass security controls and gain unauthorized access or execute code. CISA mandated patching for federal agencies following reports of targeted exploitation. [More info](https://www.cisa.gov/news-events/alerts/2026/09/16/cisa-adds-one-known-exploited-vulnerability-catalog)

- **Oracle Releases Massive September 2026 Patch Update**: Oracle issued security patches fixing over 670 unique vulnerabilities across 17 product families, including 100+ critical flaws and 240+ unauthenticated remote code execution bugs affecting E-Business Suite, Fusion Middleware, Hyperion, and CRM lines. [More info](https://blog.qualys.com/vulnerabilities-threat-research/2026/09/16/oracle-critical-security-patch-update-september-2026-review) | [More info](https://www.securityweek.com/oracle-patches-800-vulnerabilities-in-september-2026-security-update/)

- **ParaShells Privilege Escalation in Parallels Desktop (CVE-2026-90894)**: A world-writable service socket in Parallels Desktop for Mac allows local non-admin users to execute commands as root via argument injection during virtual machine extraction. Fixed in version 27, though legacy version 26 on Intel Macs remains exposed without backports. [More info](https://thehackernews.com/2026/09/parallels-desktop-flaw-lets-non-admin.html)

- **Critical Unauthenticated RCE Flaws in The Events Calendar WordPress Plugin**: Two 9.8 CVSS vulnerabilities (CVE-2026-78159 and CVE-2026-78006) expose over 200,000 WordPress sites to remote execution and complete host takeover via improper single-event rendering validation and PHP object injection. [More info](https://www.securityweek.com/unauthenticated-rce-flaws-could-expose-200000-wordpress-sites-to-takeover/)

- **ConnectWise ScreenConnect Exploited via Missing Authorization (CVE-2026-84869)**: Low-privileged users can execute remote file transfers and run binaries on host clients without confirmation. CISA issued an active exploitation warning urging immediate updates to version 26.6.5. [More info](https://www.bleepingcomputer.com/news/security/cisa-warns-of-hackers-exploiting-critical-screenconnect-flaw/)

- **Acronis Patches Local Privilege Escalation in Backup Plugins (CVE-2026-87886)**: Insecure file permissions in Acronis Backup plugins for cPanel, WHM, and Plesk allow local authenticated users to gain root privileges on Linux hosts. Targeted in-the-wild exploitation was confirmed. [More info](https://www.helpnetsecurity.com/2026/09/16/acronis-backup-plugin-vulnerability-exploited-cve-2026-87886/)

- **Google & Mozilla Patch 115 Browser Flaws**: Updates for Chrome 153 and Firefox 156 address 115 vulnerabilities combined, addressing critical WebGL memory errors, use-after-free conditions, sandbox escapes, and privilege escalation vectors. [More info](https://www.securityweek.com/chrome-firefox-updates-patch-115-vulnerabilities/)

## 🎯 Adversaries

- **BambooToken Stealth Malware Utilizes External MQTT Brokers**: Operating since 2023, BambooToken targets Windows and Linux systems across Asia and South America via DLL sideloading. It routes command-and-control operations through public MQTT messaging brokers to evade standard perimeter monitoring. [More info](https://securityaffairs.com/199205/malware/bambootoken-the-malware-that-speaks-mqtt-to-stay-under-the-radar.html)

- **Iranian Hackers Target Activists with CHOSEN BRICK Malware**: Iranian state-sponsored actors are distributing CHOSEN BRICK via targeted social engineering lures. The malware configures Defender exclusions, establishes Registry persistence, uses Telegram/SOCKS5 C2, and performs surveillance, keylogging, and data wiping. [More info](https://www.bleepingcomputer.com/news/security/iranian-hackers-use-chosen-brick-windows-malware-to-spy-on-targets/)

- **Brazilian KREMLIN Toolkit Force-Installs Chrome/Edge Extensions**: Cybercriminals are using the KREMLIN toolkit loader to extract local keys, recalculate preference HMACs, and bypass Chromium's App-Bound Encryption to silently install the malicious AVSync extension for credential harvesting. [More info](https://www.bleepingcomputer.com/news/security/malware-bypasses-browser-checks-to-force-install-chrome-edge-extensions/)

- **NightEagle, Hacking Cat, and Toy Ghouls Target Russian Infrastructure**: Kaspersky highlighted distinct APT campaigns targeting enterprise systems: NightEagle deployed GhostContainer backdoors on Exchange servers, Hacking Cat utilized wipers and Gorilla RAT, and Toy Ghouls used Matrix/MQTT C2 channels. [More info](https://thehackernews.com/2026/09/three-threat-groups-target-russian.html) | [More info](https://securelist.com/tr/nighteagle-apt-ghostcontainer-and-tunneling/121323/)

- **AI Assistant Hijacking via Malicious Browser Extensions**: Proof-of-concept research showed that low-privilege extensions exploiting browser flaws (CVE-2026-0628 and CVE-2026-55945) can inject prompt commands into integrated browser AI agents, granting access to local files and camera/microphone controls. [More info](https://thehackernews.com/2026/09/one-extension-could-hijack-ai.html)

- **AI Coding Assistant Hijacked to Deploy Shai-Hulud Worm**: Mandiant reported an incident where an attacker hijacked a SaaS provider's AI coding assistant session, tricking developers into accepting a poisoned PyPI dependency. The execution compromised repositories and spread the self-propagating Shai-Hulud worm. [More info](https://thehackernews.com/2026/09/attacker-hijacks-ai-coding-assistant.html)

- **N0va Phishing Kit Targets Enterprise Identities via Device Code Flows**: The new N0va kit spoofing Teams, DocuSign, and Google Drive uses device code OAuth flows to bypass MFA, exfiltrate access tokens, and maintain persistent SSO access across corporate environments. [More info](https://thehackernews.com/2026/09/n0va-phishkit-targets-us-and-eu.html)

- **Atomic macOS Stealer (AMOS) Distributed via Malicious Ads**: Unit 42 documented campaign activity spreading AMOS via search ads and cracked software sites, tricking users into pasting terminal commands that steal browser keychains, session cookies, and crypto wallet data. [More info](https://unit42.paloaltonetworks.com/atomic-macos-amos-stealer-activity/)

## 📈 Trends

- **Autonomous AI Agent Executes Autonomous Data Breach in Spain**: Spain's Data Protection Agency received its first report of a breach carried out entirely by an autonomous LLM agent that independently scanned systems, exploited unpatched software, traversed microservices, and exfiltrated documents without human intervention. [More info](https://www.bleepingcomputer.com/news/security/spains-data-agency-gets-first-report-of-ai-powered-data-breach/)

- **Report Highlights True Financial Impact of Ransomware vs. Ransom Costs**: Analysis shows the total cost of ransomware incidents averages $5.08 million due to downtime, legal costs, and remediation, vastly exceeding median ransom demands of $139,875, underscoring the ROI of robust BCDR solutions. [More info](https://www.bleepingcomputer.com/news/security/the-true-cost-of-a-ransomware-attack-with-and-without-bcdr/)

---

[⬅ Back to Archive](https://pranakn.github.io)
