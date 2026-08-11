---
title: "Cybersecurity Newsfeed - 12/08/26"
date: 2026-08-11 09:00:00 -0300
categories: [News]
permalink: /posts/news-12-08-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-08-12.png
  alt: Cybersecurity Newsfeed - 12/08/26
---

# Cybersecurity Newsfeed

## 📅 12/08/26

## 🛡️ Vulnerabilities

- **CISA Adds Three Exploited Flaws to KEV Catalog**: CISA added three actively exploited vulnerabilities to its Known Exploited Vulnerabilities catalog: CVE-2026-9198 (code injection in IBM Langflow), CVE-2026-18556 (authentication bypass in N-able N-central), and CVE-2026-34486 (missing data encryption in Apache Tomcat). Federal agencies must remediate these per BOD 26-04. [More info](https://www.cisa.gov/news-events/alerts/2026/08/11/cisa-adds-three-known-exploited-vulnerabilities-catalog)

- **Microsoft August 2026 Patch Tuesday Fixes Zero-Days**: Microsoft's security update addresses nearly 400 vulnerabilities across its suite, including an actively exploited Windows kernel driver zero-day (CVE-2026-68820 in `afd.sys`) leveraged by the North Korean Lazarus group to deploy rootkits. Publicly disclosed zero-days in the User Profile Service (CVE-2026-62832) and Container Isolation FS Filter Driver (CVE-2026-72971) were also resolved. [More info](https://thehackernews.com/2026/08/microsoft-patches-398-flaws-including.html) | [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-august-2026-patch-tuesday-fixes-400-flaws-3-zero-days/)

- **Cisco Secure Firewall ASA & FTD DoS Under Active Attack**: Cisco warned of active exploitation targeting CVE-2026-20349 (CVSS 8.6), a high-severity denial-of-service vulnerability in the Remote Access SSL VPN service of ASA and FTD software. Unauthenticated remote attackers can crash devices by sending malformed HTTP requests. [More info](https://www.bleepingcomputer.com/news/security/cisco-warns-of-asa-and-ftd-vpn-flaw-exploited-to-crash-devices/)

- **SAP August 2026 Patch Day Resolves Critical Flaws**: SAP issued security notes addressing multiple critical vulnerabilities, including an authentication bypass in SAP Commerce Cloud (CVE-2026-58231, CVSS 10.0), critical code injection bugs in Manufacturing Integration and Intelligence (CVE-2026-44772, CVE-2026-44758), and a NetWeaver memory corruption flaw (CVE-2026-34265). [More info](https://www.securityweek.com/sap-patches-critical-code-injection-memory-corruption-vulnerabilities/)

- **Cellular IoT Devices Vulnerable to Malicious SIM Cards**: Researchers demonstrated that cellular IoT modems and smartphones accept the proactive `RUN AT` SIM command. On unhardened cellular modules, malicious SIM cards can exploit string parsing flaws in modem daemons to achieve remote code execution. [More info](https://thehackernews.com/2026/08/a-malicious-sim-card-can-run-attacker.html)

- **High-Severity Flaws Discovered in Cisco ClamAV**: Cisco warned of memory safety bugs (CVE-2026-20337 and CVE-2026-20338) in the ClamAV scanning engine used across Secure Endpoint Connectors. Crafted ZIP archives can trigger parser crashes, leading to denial-of-service conditions. [More info](https://www.bleepingcomputer.com/news/security/cisco-warns-of-high-severity-clamav-flaws-with-public-exploits/)

- **GhostSplice Prompt Injection Targets MCP Servers**: A prompt injection technique targets AI coding assistants using Model Context Protocol (MCP) servers. By splitting exfiltration instructions across separate operational channels, malicious servers bypass security guardrails to exfiltrate local secrets and code. [More info](https://thehackernews.com/2026/08/malicious-mcp-servers-can-split.html)

## 🎯 Adversaries

- **Kimwolf v7 Android Botnet Introduces HTTP/2 Floods**: An upgraded variant of the Kimwolf botnet is targeting Android TV boxes running unauthenticated ADB services on port 5555. Version 7 features an HTTP/2 flood engine with realistic browser fingerprinting, ENS domain resolution over public Ethereum RPCs, and local proxy routing. [More info](https://thehackernews.com/2026/08/kimwolf-v7-android-botnet-makes-http2.html) | [More info](https://unit42.paloaltonetworks.com/kimwolf-v7-botnet-malware/)

- **Sandworm Subgroup UAC-0145 Uses Fake Job Interviews**: Russian state-sponsored actors are contacting Ukrainian IT specialists on Telegram and job portals, inviting them to Zoom interviews. Victims are tricked into downloading a trojanized WireGuard client ("SopraVPN") hosted on SourceForge, executing obfuscated PowerShell commands to establish persistence. [More info](https://thehackernews.com/2026/08/sandworm-linked-uac-0145-uses-fake-job.html)

- **DeadLock Ransomware Leverages Polygon Blockchain**: DeadLock operators are using Polygon smart contracts as an immutable infrastructure layer to rotate C2 proxy servers. The ransomware queries read-only contract calls to dynamically update proxy addresses, evading traditional IP blocking. [More info](https://thehackernews.com/2026/08/deadlock-ransomware-uses-polygon-smart.html)

- **ExfilSquad Expands Extortion via Torrent Networks**: Data extortion group ExfilSquad added 13 new victims, leaking stolen corporate datasets over P2P torrent networks. The group avoids traditional ransomware, focusing instead on cloud database exfiltration and distributed peer seeding to maximize reputational impact. [More info](https://securityaffairs.com/197025/security-exfilsquad-targets-new-victims-shares-data-via-torrents.html)

- **Malicious npm Packages Query Ethereum Contracts**: Sonatype researchers uncovered supply chain packages executing the "NullReceiver" technique. The npm packages query Ethereum RPC nodes to decode C2 server IP addresses embedded in blockchain transaction data, fetching secondary payloads. [More info](https://www.infosecurity-magazine.com/news/npm-packages-ethereum-wallet-c2/)

- **Gunra Ransomware Attacks Global Critical Infrastructure**: Joint alerts warn of Gunra ransomware, a Conti-derived strain targeting government and critical infrastructure sectors. The double-extortion group initial-access vectors include Fortinet (CVE-2025-24472) and Schneider Electric (CVE-2024-55591) vulnerabilities. [More info](https://thehackernews.com/2026/08/gunra-ransomware-exploits-fortinet-and.html) | [More info](https://www.bleepingcomputer.com/news/security/us-warns-of-gunra-ransomware-attacks-against-government-critical-infrastructure/)

- **BdThemes Supply Chain Attack Poisons Elementor Add-ons**: Threat actors compromised DigitalOcean storage buckets hosting promotional banner feeds for BdThemes WordPress plugins. Injected XSS payloads executed in admin browsers, deploying web shells and establishing persistent administrative accounts. [More info](https://thehackernews.com/2026/08/bdthemes-supply-chain-attack-poisons.html)

- **Fake CCleaner Installers Deliver GhostDesk Spyware**: Phishing domains distributing trojanized CCleaner utilities are deploying a malicious Chrome extension called GhostDesk. The spyware alters Chrome security configurations to harvest keystrokes, browser credentials, and screen captures. [More info](https://www.malwarebytes.com/blog/threat-intel/2026/08/fake-ccleaner-installs-ghostdesk-chrome-spyware)

## 📈 Trends

- **Hyper-Volumetric DDoS Attacks Surge 519%**: Cloudflare's Q2 2026 DDoS report recorded a fivefold increase in network-layer attacks exceeding 1 Tbps, including a record 31.4 Tbps attack attributed to the Kimwolf botnet. Overall network-layer attack volume grew by over 31%. [More info](https://www.bleepingcomputer.com/news/security/ddos-attacks-over-1-tbps-surged-fivefold-in-the-second-quarter/)

## 💥 Breaches & Leaks

- **CEVA Logistics Breach Exposes Steam Hardware Customers**: Valve warned European Steam hardware buyers after a breach at logistics partner CEVA exposed names, shipping addresses, emails, and order details for Steam Deck and peripheral purchases. [More info](https://www.malwarebytes.com/blog/data-breaches/2026/08/valve-warns-steam-hardware-buyers-expect-fake-delivery-scams)

- **Wesco Investigates Data Theft Claim by ExfilSquad**: Industrial distributor Wesco confirmed a cloud CRM security incident after threat actors published 2.6 million customer and employee records online. Operations and payment processing infrastructure were unaffected. [More info](https://www.bleepingcomputer.com/news/security/wesco-confirms-security-incident-after-exfilsquad-claims-data-theft/)

## 📚 Others

- **In-Flight Wireless Attack Targets DEF CON Flight**: Delta Air Lines and federal agents investigated a Wi-Fi deauthentication attack aboard a flight carrying DEF CON attendees. Attackers created a rogue "Delta WiFi Fast" network with a credential-harvesting portal, causing cabin crew to disable in-flight Wi-Fi before law enforcement intervened upon landing. [More info](https://www.bleepingcomputer.com/news/security/delta-probes-wi-fi-deauth-attack-on-flight-carrying-def-con-attendees/)

- **FBI Warns of Account Takeovers Targeting Intimate Media**: The FBI released a public service announcement highlighting credentials stuffing and social engineering tactics used by cybercriminals to breach personal accounts and extort non-consensual intimate images. [More info](https://www.malwarebytes.com/blog/news/2026/08/sexual-predators-targeting-online-accounts-for-intimate-images-fbi-warns)

- **Mozilla Revokes Compromised Firefox GPG Signing Key**: Mozilla rotated and revoked a GPG subkey used for Linux package signing after it was accidentally committed to a private code repository in an unencrypted state. Manual package verifications require importing the updated key release. [More info](https://www.bleepingcomputer.com/news/security/mozilla-updates-gpg-key-for-signing-firefox-thunderbird-releases-after-exposure/) | [More info](https://thehackernews.com/2026/08/mozilla-revokes-firefox-and-thunderbird.html)

---

[⬅ Back to Archive](https://pranakn.github.io)
