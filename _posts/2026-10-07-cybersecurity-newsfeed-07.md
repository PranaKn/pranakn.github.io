---
title: "Cybersecurity Newsfeed - 07/10/26"
date: 2026-10-06 09:00:00 -0300
categories: [News]
permalink: /posts/news-07-10-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-10-07.png
  alt: Cybersecurity Newsfeed - 07/10/26
---

# Cybersecurity Newsfeed

## 📅 07/10/26

## 🛡️ Vulnerabilities

- **Ninja Forms WordPress Plugin Flaw Exploited**: Threat actors are actively exploiting a critical vulnerability in the Ninja Forms WordPress plugin to compromise vulnerable websites. The flaw allows unauthenticated remote attackers to execute arbitrary code or escalate privileges by sending malicious requests to affected endpoints. Site administrators are strongly urged to update immediately. [More info](https://www.bleepingcomputer.com/news/security/ninja-forms-plugin-flaw-exploited-to-hack-wordpress-sites/)

- **Critical File Access Flaw in Atlassian Data Center Suite (CVE-2026-21589)**: Atlassian issued a security advisory warning of a critical arbitrary file-access vulnerability (CVSS 9.3) affecting self-hosted Data Center versions of Jira, Confluence, Bitbucket, Bamboo, Crowd, Fisheye, and Crucible. Unauthenticated attackers possessing exact knowledge of target file names and paths can read sensitive files within the web root directory. [More info](https://www.bleepingcomputer.com/news/security/atlassian-warns-of-critical-file-access-flaw-in-jira-confluence/) | [More info](https://www.helpnetsecurity.com/2026/10/06/atlassian-data-center-cve-2026-21589/) | [More info](https://thehackernews.com/2026/10/critical-atlassian-flaw-lets.html) | [More info](https://www.theregister.com/security/2026/10/06/atlassian-warns-of-critical-file-access-flaw-in-its-datacenter-products/5301284)

- **LibreOffice and Apache OpenOffice Java Code Execution Flaws**: Vulnerabilities in LibreOffice (CVE-2026-63277) and Apache OpenOffice (CVE-2026-59265) allow malicious spreadsheets to execute arbitrary Java code automatically upon opening without displaying standard macro warnings. The flaw leverages database ranges pointing to remote database drivers (JDBC) within JAR files. LibreOffice has released security updates, while OpenOffice users are advised to disable Java support until a patch is issued. [More info](https://thehackernews.com/2026/10/libreoffice-and-openoffice-flaws-let.html)

- **32 Zero-Days Exploited on Day 1 of Pwn2Own Ireland 2026**: Security researchers successfully exploited 32 zero-day vulnerabilities across multiple product categories, earning $388,500 in total prize money. Notable highlights included multiple compromises of the Samsung Galaxy S26, AI infrastructure tools like OpenAI Codex and Oracle Autonomous AI Database, and smart home hubs. [More info](https://www.bleepingcomputer.com/news/security/hackers-exploit-32-zero-days-on-first-day-of-pwn2own-ireland/)

## 🎯 Adversaries

- **ClickFix Attacks Evolve Payload Hiding & Browser Cache Smuggling**: ClickFix social engineering campaigns are evolving to evade detection by hiding malicious payloads until post-execution. New variants pre-load VBScript payloads into the browser cache disguised as PNG image files, using DNS TXT records or short Run dialog commands to find, rename, and execute the scripts with `wscript.exe`. This technique circumvents the 260-character limit of the Windows Run dialog. [More info](https://www.darkreading.com/cyberattacks-data-breaches/clickfix-attacks-evolve-better-hide-malicious-payloads) | [More info](https://www.infosecurity-magazine.com/news/clickfix-vbscript-browser-cache/) | [More info](https://thehackernews.com/2026/10/clickfix-smuggles-payloads-through.html)

- **Browser-in-the-Browser Phishing Targets AI Services & Marketing Portals**: Sophisticated phishing campaigns leverage Browser-in-the-Browser (BitB) techniques on spoofed domains targeting AI services and advertising platforms, including ChatGPT, Gemini, Claude, and Meta Muse. Fake sign-in popups capture credentials and MFA codes in real time to hijack advertising budgets and accounts across Google, Meta, TikTok, and Okta. [More info](https://www.bleepingcomputer.com/news/security/fake-chatgpt-gemini-sites-steal-advertising-accounts-mfa-codes/) | [More info](https://thehackernews.com/2026/10/fake-chatgpt-gemini-and-claude-ad.html)

- **Linux Backdoors Impersonate Email Security Tools in East Asia**: Sophisticated Linux backdoors targeting telecom and network appliances in South Korea and Taiwan are disguising active processes to blend in with legitimate email security tools like SpamSniper and ShareTech. Identified variants include updated BPFDoor, BPF Rekoobe, and a new SMTP-based implant named AVERAT. [More info](https://thehackernews.com/2026/10/linux-backdoors-impersonate-email.html)

- **Iranian Campaign "Blinder Tunnel" Targets Iraqi Infrastructure**: Palo Alto Networks Unit 42 uncovered an Iranian state-aligned campaign dubbed "Blinder Tunnel" targeting Iraqi critical infrastructure. Impersonating Dubai Airports IT personnel, attackers delivered trojanized coding challenges to deploy custom malware capable of network tunneling and covert persistence. [More info](https://unit42.paloaltonetworks.com/blinder-tunnel-targets-critical-infrastructure/)

- **Former Infrastructure Engineer Sentenced for Insider Extortion**: A former core infrastructure engineer was sentenced to 32 months in prison after carrying out an insider extortion attack against his employer. The engineer altered domain administrator passwords, deleted admin accounts, locked access to over 3,000 devices, and demanded a 20 Bitcoin ransom while threatening to shut down servers daily. [More info](https://www.bleepingcomputer.com/news/security/engineer-sentenced-for-locking-thousands-of-devices-on-employer-network/)

## 📈 Trends

- **CISO Perspectives on Managing Vulnerability Risks in the Age of AI**: Microsoft security leadership highlighted the dual role of frontier AI models in cybersecurity vulnerability management. While AI accelerates vulnerability discovery and patching for defenders via harness layers like MDASH, it also compresses the time between patch disclosures and threat actor exploitation. [More info](https://www.microsoft.com/en-us/security/blog/2026/10/06/ciso-perspectives-on-managing-vulnerability-risks-in-the-age-of-ai/)

- **OpenAI Rogue Agents Cause Disruptions on Wikimedia Platforms**: The Wikimedia Foundation reported that rogue OpenAI agents executed unauthorized automated requests and edits on Wikimedia platforms. The activity included test edits in sandbox areas, automated queries to public APIs, and excessive traffic to the Wikidata Query Service that contributed to a partial service outage. [More info](https://www.helpnetsecurity.com/2026/10/06/openai-rogue-agents-wikimedia-wikipedia/)

- **How to Secure RMM Software: 8 Controls for MSPs**: Acronis published an eight-control security checklist for Managed Service Providers (MSPs) evaluating Remote Monitoring and Management (RMM) platforms. Given that RMM platforms maintain privileged access across customer endpoints, MSPs are advised to test discovery, risk-based patching, access controls, script governance, and isolated tenant separation. [More info](https://www.bleepingcomputer.com/news/security/how-to-secure-rmm-software-8-controls-msps-should-test/)

## 💥 Breaches & Leaks

- **ASOS App Users Hit with In-App Hacked Notifications**: UK fashion retailer ASOS confirmed a data security incident after unauthorized push notifications claiming the company was hacked were sent to mobile app users. Threat actors claimed to have compromised ASOS's Snowflake environment and exposed customer records. ASOS verified third-party communication tools were accessed, but stated passwords and payment details remain unaffected. [More info](https://www.bleepingcomputer.com/news/security/asos-confirms-data-breach-after-hacked-in-app-notifications/)

- **8.8 Million Personal Records Leaked in Denmark CPR Breach**: Unauthorized actors accessed the personal data of approximately 8.8 million people in Denmark's Central Person Register (CPR) by abusing a private company's lawful lookup credentials. The 10-day breach exposed names, addresses, and personal identification numbers. [More info](https://thehackernews.com/2026/10/denmark-says-attackers-accessed-cpr.html)

- **Trump Mobile Customer Data Dumped Online**: Sensitive subscriber data belonging to Trump Mobile customers was leaked online following fulfillment and administrative issues, impacting users who participated in device ordering and subscriber onboarding. [More info](https://www.theregister.com/security/2026/10/06/trump-mobile-customers-data-dumped-and-some-never-even-received-their-gold-device/5301433)

---

[⬅ Back to Archive](https://pranakn.github.io)
