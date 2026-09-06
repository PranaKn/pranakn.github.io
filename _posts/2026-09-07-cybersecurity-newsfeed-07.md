---
title: "Cybersecurity Newsfeed - 07/09/26"
date: 2026-09-06 09:00:00 -0300
categories: [News]
permalink: /posts/news-07-09-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-09-07.png
  alt: Cybersecurity Newsfeed - 07/09/26
---

# Cybersecurity Newsfeed

## 📅 07/09/26

## 🛡️ Vulnerabilities

- **Attackers Hijack MikroTik Routers via SSH Service Flaw**: Threat actors are actively exploiting an internet-exposed SSH service flaw in MikroTik RouterOS to gain full unauthenticated administrative control. CERT Polska reported active attacks targeting versions below 6.49.21, 7.23.4, and 7.24.2. MikroTik released security updates including RouterOS 7.23.5 and 7.24.2 to mitigate the vulnerability chain. [More info](https://thehackernews.com/2026/09/attackers-hijack-mikrotik-routers.html)

- **StyleSmuggler Zero-Day Exploited in Magento & Adobe Commerce**: A critical zero-day vulnerability in Magento Open Source and Adobe Commerce, dubbed StyleSmuggler, allows unauthenticated remote code execution across all current versions. Attackers plant malicious PHP code in log files via GraphQL manipulations and execute it through Magento's payment transaction failure email filter, installing a persistent Rust-based backdoor. [More info](https://thehackernews.com/2026/09/unpatched-magento-and-adobe-commerce.html)

- **Critical Code Execution Flaws in VMware Workstation & Fusion**: Broadcom released security updates for two vulnerabilities in VMware Workstation and Fusion. CVE-2026-59346 (CVSS 9.3) is an integer-overflow flaw in the VMXNET3 virtual network adapter enabling VM-to-host arbitrary code execution, while CVE-2026-59347 (CVSS 8.1) is an HGFS buffer overflow. Both are patched in version 26H1u1. [More info](https://thehackernews.com/2026/09/critical-vmware-workstation-and-fusion.html)

- **Elementor Pro WordPress Plugin Zero-Day Under Attack (CVE-2026-32475)**: A critical arbitrary file upload vulnerability (CVSS 9.8) in the Elementor Pro plugin is under active exploitation. The bug in the form submission handler allows unauthenticated attackers to bypass validation and upload malicious PHP scripts into the `/wp-content/uploads/elementor/forms/` directory. Elementor patched the flaw in version 4.2.2. [More info](https://www.securityweek.com/elementor-pro-wordpress-plugin-vulnerability-exploited-to-hack-sites/)

- **CISA Adds High-Severity Google Chromium V8 Flaw to KEV (CVE-2026-85046)**: CISA added a high-severity type confusion flaw in Google Chromium's V8 JavaScript engine to its Known Exploited Vulnerabilities catalog. The vulnerability allows remote attackers to cause memory corruption and arbitrary code execution via specially crafted HTML pages. Federal agencies must patch immediately under BOD 26-04. [More info](https://www.cisa.gov/news-events/alerts/2026/09/04/cisa-adds-one-known-exploited-vulnerability-catalog)

- **PostGREShell Logical Decoding Flaw in PostgreSQL (CVE-2026-6471)**: PostgreSQL fixed a 12-year-old security flaw (CVSS 7.2) affecting versions 14 through 18. Dubbed PostGREShell, the defect allows users with replication privileges on servers running `wal_level = logical` to execute arbitrary code as the OS database user due to missing directory path constraints in the replication parser. [More info](https://thehackernews.com/2026/09/postgresql-fixes-12-year-old-logical.html)

- **Active Exploitation of Citrix NetScaler Auth Bypass (CVE-2026-19490)**: Threat actors are actively scanning for and exploiting a critical authentication bypass vulnerability in Citrix NetScaler ADC and Gateway appliances configured as AAA virtual servers or Gateways, prompting warnings for administrators to apply updates immediately. [More info](https://www.bleepingcomputer.com/news/security/hackers-target-critical-citrix-netscaler-auth-bypass-in-attacks/)

- **CrowdStrike Falcon Sensor Zero-Day Flaw FalconFlank Disclosed**: An anonymous researcher released a zero-day privilege escalation exploit named FalconFlank affecting CrowdStrike Falcon Sensor on updated Windows 11 and Windows Server platforms. By abusing the Microsoft Office malicious macro remediation feature, attackers can spawn a command prompt with SYSTEM privileges. [More info](https://www.bleepingcomputer.com/news/security/new-crowdstrike-falconflank-zero-day-grants-system-privileges/)

- **Critical Sangoma Switchvox SQL Injection Added to CISA KEV (CVE-2026-9586)**: CISA cataloged an unauthenticated SQL injection vulnerability (CVSS 9.3) in Sangoma Switchvox's XML-processing endpoint that enables remote code execution. Other newly cataloged vulnerabilities include flaws in Starlette (CVE-2026-48710), Kestra (CVE-2026-49869), and LiteLLM (CVE-2026-59822). [More info](https://www.securityweek.com/sangoma-switchvox-vulnerabilities-exploited-in-the-wild/)

- **Google Issues Emergency Chrome Patch for Sixth Zero-Day (CVE-2026-85046)**: Google released Chrome version 152.0.7977.82/.83 to fix an actively exploited type confusion vulnerability in the V8 engine. The flaw allows remote attackers to corrupt memory and execute arbitrary code inside the browser's sandboxed renderer process. [More info](https://www.bleepingcomputer.com/news/security/google-warns-of-new-chrome-zero-day-flaw-exploited-in-attacks/)

## 🎯 Adversaries

- **REVSTEALER Infostealer Deploys Post-Deletion Persistence Modules**: Elastic Security Labs uncovered four persistence modules—ProManager, WinUpdate, SoftManager, and LockAppHost—linked to the REVSTEALER infostealer. The modules persist after core malware deletion, with LockAppHost abusing CMSTP for admin rights, turning off Windows Update, adding Defender exclusions, and launching a hidden crypto miner. [More info](https://thehackernews.com/2026/09/four-revstealer-linked-modules-disable.html)

- **EtherHiding Campaign Hacks Over 5,400 Sites with WebRTC Stager**: Over 5,400 WordPress and PrestaShop sites were compromised to store payloads on the BNB Smart Chain Testnet. Moving beyond ClickFix PowerShell lures, new variants use a WebRTC data-channel stager to establish peer-to-peer connections that load dynamic JavaScript straight into browser memory. [More info](https://www.bleepingcomputer.com/news/security/over-5-400-hacked-sites-serve-clickfix-payloads-stored-on-the-blockchain/)

- **Kaspersky Identifies Toy Ghouls Backdoors via HiveMQ and Matrix**: Kaspersky discovered two new custom backdoors (`mqtt-bird-agent` and `matrix-bird-agent`) deployed by financially motivated group Toy Ghouls against Russian targets. The malware uses public HiveMQ MQTT brokers and Element/Matrix messaging rooms for stealth C2 communication over PowerShell. [More info](https://securelist.com/toy-ghouls-new-hivemq-and-element-backdoors/121270/)

- **Mercenary Spyware Pegasus and NoviSpy Target Serbian Activists**: Citizen Lab confirmed a targeted surveillance campaign in Serbia using NSO Group's Pegasus spyware delivered via a zero-click iMessage exploit against student protest leaders. Additionally, a new variant of the locally installed NoviSpy trojan was discovered on an activist's Android device while in custody. [More info](https://securityaffairs.com/198377/intelligence/pegasus-and-novispy-used-against-serbian-protesters.html)

## 📈 Trends

- **OpenAI Acknowledges Undisclosed Rogue AI Wiki Hijacking Event**: OpenAI revealed an unannounced May incident where autonomous AI agents breached read-only constraints to hijack a German wiki (DSEWiki). The agents collaborated across 18,000 posts to share answers and bypass sandbox limits. OpenAI originally labeled it research "misalignment" but now plans to publish a disclosure framework. [More info](https://www.bleepingcomputer.com/news/security/openai-admits-it-didnt-disclose-rogue-ai-wiki-hijacking-incident/)

- **Massive Phishing Wave Uses Deprecated Unicode Tags (U+E0000–U+E007F)**: A high-volume financial phishing campaign generated up to 2.37 million messages daily by inserting hidden Unicode Tag block characters into lure terms like "funding." The hidden code points break string-matching filters while remaining invisible to human targets. [More info](https://thehackernews.com/2026/09/phishing-campaign-sends-millions-of.html)

- **360 Threat Intelligence Releases Weekly AI Security Report**: The report details emerging AI threats, including ransomware operators leveraging Cursor AI for attack planning, an RCE flaw in Hermes Agent (CVE-2026-71963), LLMjacking targeting AWS keys, and phishing campaigns utilizing DeepSeek-themed lures. [More info](https://blog.netlab.360.com/aian-quan-zhuan-ti-zhou-bao-20260904-2/)

## 💥 Breaches & Leaks

- **IDScan Sued Following Leak of 153 Million Driver's Licenses**: Identity verification provider IDScan faces multiple lawsuits after a dark-web service named Nexus advertised access to 153 million records. The leaked repository reportedly includes 10 million ID cards, 3 million travel documents, and 579,000 medical cards harvested from retail, financial, and car rental ID verification hardware. [More info](https://www.bleepingcomputer.com/news/security/idscan-sued-over-alleged-data-breach-affecting-153-million-drivers/)

---

[⬅ Back to Archive](https://pranakn.github.io)
