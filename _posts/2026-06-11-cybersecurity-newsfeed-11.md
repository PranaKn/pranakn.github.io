---
title: "Cybersecurity Newsfeed - 11/06/26"
date: 2026-06-10 19:00:00 -0300
categories: [News]
permalink: /posts/news-11-06-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-06-11.png
  alt: Cybersecurity Newsfeed - 11/06/26
---

# Cybersecurity Newsfeed

## 📅 11/06/26

## 🛡️ Vulnerabilities

- **Langflow AI Platform Path Traversal Exploited (CVE-2026-5027)**: Attackers are actively exploiting a high-severity path traversal vulnerability within the file upload functionality of the AI development platform Langflow. Discovered by Tenable, this flaw stems from a lack of sanitization in the "POST /api/v2/files" endpoint's filename parameter. Remote threat actors can issue a single unauthenticated request to acquire a valid session token, execute arbitrary path traversal sequences ("../"), and drop malicious payloads on exposed filesystems. [More info](https://www.bleepingcomputer.com/news/security/path-traversal-flaw-in-ai-dev-platform-langflow-exploited-in-attacks/)

- **Windows Defender Zero-Day Privilege Escalation Exploit**: A security researcher using the pseudonym "Nightmare-Eclipse" has released "RoguePlanet," a new zero-day local privilege escalation exploit targeting Windows Defender. Released immediately following Microsoft's June Patch Tuesday updates, the proof-of-concept exploit leverages a race condition within the security software's operational signature workflow to spawn an interactive command shell running under SYSTEM-level privileges. [More info](https://www.darkreading.com/vulnerabilities-threats/nightmare-eclipse-microsoft-exploit-rogueplanet)

- **Emergency Patches from Ivanti, Fortinet, and SAP**: Fortinet resolved CVE-2026-25089, a command injection flaw inside FortiSandbox web interfaces allowing unauthenticated attackers to execute arbitrary system commands. Simultaneously, Ivanti patched two critical vulnerabilities in its Sentry mobile gateways: CVE-2026-10520 (an OS command injection flaw granting root privileges) and CVE-2026-10523 (an authentication bypass used to create unauthorized administrator accounts). [More info](https://thehackernews.com/2026/06/ivanti-fortinet-and-sap-release-patches.html)

- **Actively Exploited Microsoft Exchange Server Zero-Day**: Microsoft has released patches resolving an actively exploited Microsoft Exchange Server zero-day vulnerability utilized in highly targeted cross-site scripting attacks. The flaw enables remote cybercriminals to execute arbitrary JavaScript code within the context of a victim's active browser session when accessing Outlook Web Access, allowing them to hijack corporate mailboxes without requiring user interaction beyond opening a specially crafted email. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-patches-exchange-server-zero-day-exploited-in-attacks/)

- **Critical Data Center Infrastructure Flaws in Vertiv and Trane**: Security firm Claroty exposed critical vulnerabilities within Vertiv uninterruptible power supply (UPS) network cards and Trane Tracer SC+ HVAC controllers. The Vertiv UPS cards suffer from a combined authentication bypass and remote code execution flaw that risks unexpected server blackouts, while the Trane HVAC controllers are vulnerable to highly exploitable unauthenticated remote code execution and information disclosure bugs. [More info](https://www.securityweek.com/critical-hvac-and-ups-vulnerabilities-could-let-hackers-disrupt-data-centers/)

## 🎯 Adversaries

- **Miasma Worm Source Code Leaked on GitHub**: The source code for "Miasma," a sophisticated, credential-stealing self-propagating worm framework, was briefly leaked and made open-source on GitHub before being deleted. Part of the broader "Shai-Hulud" supply-chain attack campaign, Miasma specifically targets open-source programming ecosystems by embedding malicious components within public registries. [More info](https://www.bleepingcomputer.com/news/security/the-miasma-worm-source-code-briefly-leaked-on-github/)

- **TikTok and Instagram Reels Manipulated to Spread Vidar Infostealer**: Cybercriminals are leveraging short-form video algorithms on TikTok and Instagram Reels to spread the Vidar information-stealing malware. A ReversingLabs analysis revealed campaigns using AI-generated voiceovers and lookalike Windows profiles to trick users into running malicious PowerShell commands via deceptive free-software and tech-support tutorials. [More info](https://hackread.com/scammers-tiktok-instagram-reels-vidar-infostealer/) | [More info](https://www.infosecurity-magazine.com/news/fake-software-videos-tiktok-vidar/)

- **ShinyHunters Targets Oracle PeopleSoft Servers**: The notorious ShinyHunters extortion syndicate has launched a series of cyberattacks targeting Oracle PeopleSoft servers, successfully exfiltrating corporate records from over 100 organizations. Threat actors compromise the internet-facing enterprise application servers by combining aggressive credential-spraying campaigns with unauthorized SSH access to dump internal database tables. [More info](https://www.bleepingcomputer.com/news/security/oracle-peoplesoft-servers-hacked-in-shinyhunters-data-theft-attacks/)

- **SilabRAT Offered as MaaS for $5,000/Month**: A sophisticated remote access trojan named SilabRAT is being distributed across dark web forums. Analyzed by Group-IB, the threat uses specialized hidden virtual network computing (hVNC) and browser-profile cloning to entirely bypass multi-factor authentication and device fingerprinting defenses, allowing attackers to silently siphon cryptocurrency assets. [More info](https://www.infosecurity-magazine.com/news/silabrat-trojan-session-hijacking/)

- **China-Linked JDY Botnet Targets U.S. Military Networks**: The China-linked JDY botnet, historically tied to advanced persistent threat actors like Volt Typhoon, has expanded its operations to control over 1,500 small office, home office (SOHO), and Internet of Things (IoT) devices. According to Lumen's Black Lotus Labs, the malware acts as a centrally managed scanning network designed to continuously map and fingerprint exposed defense infrastructure. [More info](https://www.bleepingcomputer.com/news/security/china-linked-jdy-botnet-expands-targeting-of-us-military-networks/)

## 🛠️ Supply Chain

- **GitHub Announces npm Security Changes to Thwart Supply Chain Attacks**: GitHub announced that npm version 12 will introduce critical security modifications designed to tackle supply-chain attacks within the JavaScript ecosystem. The update alters default behaviors associated with the "npm install" command, requiring explicit developer authorization before running install scripts or downloading project dependencies from external Git repositories and remote URLs. [More info](https://www.bleepingcomputer.com/news/security/github-announces-npm-security-changes-to-tackle-supply-chain-attacks/)

- **"Proto6" Vulnerabilities Discovered in protobuf.js Library**: Cybersecurity researchers at Cyera discovered six severe vulnerabilities, collectively dubbed "Proto6," within the widely used protobuf.js library for Node.js. The most critical flaw, CVE-2026-44291, allows attackers to trigger prototype pollution via malicious input, injecting arbitrary JavaScript strings into dynamic compilation functions, potentially leading to container escapes and corporate secret leakage. [More info](https://thehackernews.com/2026/06/six-proto6-vulnerabilities-in.html)

## 📈 Trends

- **Browser-in-the-Browser Phishing Campaign Targets Microsoft 365**: A novel Browser-in-the-Browser phishing campaign discovered by Palo Alto Networks Unit 42 is actively targeting Microsoft 365 users to harvest corporate credentials. The attack uses an iframe to embed an interactive, fake browser window inside a compromised webpage, flawlessly mimicking legitimate Microsoft OAuth sign-in popups while blocking browser developer consoles to hinder technical analysis. [More info](https://www.helpnetsecurity.com/2026/06/10/browser-in-the-browser-phishing-microsoft-365-users/)

---

[⬅ Back to Archive](https://pranakn.github.io)
