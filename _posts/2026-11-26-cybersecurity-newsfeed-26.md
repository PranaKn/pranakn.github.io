---
title: "Cybersecurity Newsfeed - 26/11/26"
date: 2026-11-25 19:57:00 -0300
categories: [News]
permalink: /posts/news-26-11-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-11-26.png
  alt: Cybersecurity Newsfeed - 26/11/26
---

# Cybersecurity Newsfeed

## 📅 26/11/26

## 🛡️ Vulnerabilities

  - **Palo Alto Networks PAN-OS Fragnesia Exploitation**: Threat actors are chaining PHP2Shell flaws (CVE-2026-109618, CVE-2026-109619) with the Linux kernel Fragnesia bug (CVE-2026-46300) to gain root access on PAN-OS devices with internet-exposed management interfaces. Palo Alto Networks released patches across PAN-OS 10.2 through 12.2 and urges administrators to restrict management interface access to trusted internal IPs. [More info](https://www.bleepingcomputer.com/news/security/palo-alto-networks-warns-of-fragnesia-flaw-exploited-in-pan-os-attacks/)

  - **CISA Adds 10 Flaws to KEV Catalog**: CISA added ten actively exploited vulnerabilities to its KEV catalog, including three Danfoss AK-SM 800A flaws (CVE-2023-25914, CVE-2023-25915, CVE-2025-41450), an HPE Juniper Session Smart Router command injection bug (CVE-2026-103406), five Mitel MiCollab vulnerabilities (CVE-2026-133275, CVE-2026-133303, CVE-2026-133311, CVE-2026-133323, CVE-2026-133324), and a Vates Xen Orchestra flaw (CVE-2026-133469). [More info](https://www.cisa.gov/news-events/alerts/2026/11/25/cisa-adds-10-known-exploited-vulnerabilities-catalog) | [More info](https://www.cisa.gov/known-exploited-vulnerabilities-catalog?search_api_fulltext=CVE-2026-103406)

  - **Critical Unpatched Danfoss Controller Flaw**: CISA warned of CVE-2026-129713 (CVSS 9.8), an unauthenticated stack-based buffer overflow in Danfoss AK-SM 8xxA refrigeration controllers that enables remote code execution. Following European supermarket attacks, Danfoss scheduled a fix for version 5.5.x; administrators must immediately isolate controllers from the public internet behind firewalls and VPNs. [More info](https://www.bleepingcomputer.com/news/security/cisa-warns-of-critical-unpatched-flaw-in-danfoss-refrigeration-controllers/)

  - **GeoServer Flaws Exploited in RCE Chains**: Attackers are exploiting arbitrary file read (CVE-2026-120705) and authorization bypass (CVE-2026-129243) vulnerabilities in GeoServer. Researchers warn these bugs can be chained with a hard-coded signing key (CVE-2026-129245) and code generation or deserialization flaws (CVE-2026-120704, CVE-2026-129242) to achieve full unauthenticated remote code execution. [More info](https://thehackernews.com/2026/11/hackers-exploit-two-geoserver-flaws-as.html)

  - **Critical Drupal RCE Flaw Under Active Attack**: Threat actors are actively exploiting CVE-2026-132165, a critical vulnerability in Drupal core's installer (`install.php`) discovered by Anthropic's OSS Scanner that allows unauthenticated site takeover and remote code execution. CISA added the flaw to its KEV catalog, advising admins to upgrade immediately or block access to `install.php`. [More info](https://www.bleepingcomputer.com/news/security/hackers-now-exploit-critical-drupal-rce-flaw-to-hijack-sites/)

  - **Defunct Idunno AntiCsrf Library Exploited**: Attackers are exploiting CVE-2026-131914 (CVSS 9.3), an unpatched insecure deserialization vulnerability in the abandoned ASP.NET Idunno AntiCsrf module, to gain remote code execution via a single HTTP POST request. Added to CISA's KEV catalog, defenders must remove the legacy library or deploy WAF rules immediately. [More info](https://www.securityweek.com/hackers-exploit-unpatched-flaw-in-defunct-idunno-anticsrf-library/)

  - **NGINX HTTP/2 Use-After-Free Vulnerability**: Palo Alto Networks Unit 42 detailed CVE-2026-123633, a use-after-free vulnerability in NGINX's HTTP/2 module triggered under connection pressure during request-time DNS resolution or upstream setup, enabling remote code execution when paired with a memory leak. Operators should upgrade to NGINX 1.30.7 or 1.31.9 or disable HTTP/2. [More info](https://unit42.paloaltonetworks.com/cve-2026-123633-nginx-http2-vulnerability/)

  - **VMware Patches Critical vCenter and ESX Flaws**: Broadcom released updates for 23 VMware vulnerabilities, including a critical vCenter Directory Service authentication bypass (CVE-2026-123903, CVSS 9.8) and two critical ESX I/O filter remote code execution bugs (CVE-2026-123910, CVE-2026-123911, CVSS 9.8). Administrators should urgently patch affected vCenter, ESX, Workstation, and Fusion deployments. [More info](https://securityaffairs.com/203931/security/vmware-patches-critical-vcenter-authentication-bypass-and-esx-flaws.html)

## 🎯 Adversaries

  - **AI-Driven Campaign Compromises 24 Check Point Servers**: Tracked as GreyNoise Threat 13 (GT13), an unknown adversary leveraged suspected AI-driven offensive pipelines to compromise 24 Check Point Security Management servers across 22 global organizations. Using CVE-2026-16232 and a compromised Rejetto HFS relay (CVE-2026-61500), attackers stole firewall databases, unloaded security policies, and attempted lateral movement. [More info](https://thehackernews.com/2026/11/hackers-compromise-24-check-point.html)

  - **Backdoored WP Connect Plugins Blocked on WordPress**: WordPress permanently closed six WP Connect plugins—installed on over 3,600 sites—after a compromised developer account pushed malicious updates tracked as CVE-2026-135202 (CVSS 9.8). Blocked prior to public release, the backdoor (`includes/airwp-online.php`) enables remote PHP execution, credential dumping, and persistent cron jobs via C2 `tascredit-pay[.]com`. [More info](https://thehackernews.com/2026/11/wordpress-blocks-six-backdoored-wp.html)

## 📈 Trends

  - **Italy and Switzerland Warn of Autonomous AI Cyberattacks**: CSIRT Italia and Switzerland's NCSC issued warnings regarding large-scale, autonomous cyberattacks targeting critical infrastructure using AI red-teaming frameworks like ARTEX AI, CyberStrikeAI, DeepSeek Harness, and PentAGI. These agents dynamically chain vulnerabilities, write evasion code in real time, and rapidly compromise internet-facing systems. [More info](https://www.bleepingcomputer.com/news/security/italy-and-switzerland-warn-of-autonomous-ai-driven-cyberattacks/)

  - **Supply Chain Flaws Dominate Network Appliance Exploits**: Eclypsium's November InfraTrust report reveals that 33 of 38 actively exploited vulnerabilities across 23 infrastructure vendors stemmed from bundled third-party components like PHP, Node.js, and OpenSSH rather than proprietary code. Delays in downstream vendor patching leave appliances exposed, prompting warnings to isolate management interfaces. [More info](https://www.bleepingcomputer.com/news/security/infratrust-warns-of-exploited-supply-chain-flaws-in-network-appliances/)

  - **Ransomware Attacks Surge 23% in October**: NCC Group reports that claimed ransomware incidents jumped 23% in October to 1,049 victims following a record Q3, driven by AI-accelerated vulnerability discovery and exploitation. Newly emerged brands like The Gentlemen and N0n led attack volumes, heavily targeting the industrials sector (31%) and North America (46%). [More info](https://www.infosecurity-magazine.com/news/ransomware-surge-october-record/)

  - **Overcoming Bottlenecks in Enterprise Credential Remediation**: GitGuardian's 2026 research shows 64% of leaked secrets from 2022 remain valid due to fears of breaking production dependencies. Security teams are advised to prioritize remediation by blast radius rather than validity alone, and follow a strict "vault, migrate consumers, verify, then revoke" workflow. [More info](https://thehackernews.com/2026/11/credential-remediation-is-slow-when-you.html)

## 💥 Breaches & Leaks

  - **1Password Discloses Customer Account Metadata Breach**: 1Password confirmed an attacker compromised an employee's corporate GitHub account on November 19, copying private source code and customer metadata including names, emails, public keys, and some setup/recovery tokens. Customer vaults and encryption keys remain uncompromised, though users should watch for targeted phishing. [More info](https://hackread.com/1password-attacker-copied-customer-account-data-vaults/)

  - **Unsecured Database Exposes 2 Billion Credential Records**: Researcher Jeremiah Fowler discovered an unprotected database containing roughly 2 billion infostealer records, including plaintext passwords, browser cookies, session tokens, and 400,000 system logs spanning Gmail, Google services, and `.gov` domains. The exposure poses severe account takeover risks by enabling attackers to bypass MFA using stolen sessions. [More info](https://hackread.com/database-exposed-credential-records-session-tokens/)

  - **Gatwick Airport Drop-Off Data Exposed in Supplier Breach**: Personal data and payment details belonging to London Gatwick Airport drop-off zone customers were exposed following a breach of the AutoPay system operated by ParkPark and Times24 UK Limited. Times24 suspended AutoPay while investigating, and Gatwick warned customers to remain vigilant against targeted phishing scams. [More info](https://www.theregister.com/security/2026/11/25/gatwick-drop-off-customers-personal-data-exposed-in-supplier-breach/5312060)

  - **Unclassified CIA OSINT System Reportedly Breached**: Unknown attackers using the ARTEX AI pentesting framework reportedly breached an unclassified open-source intelligence analysis system shared by the CIA, ODNI, and NGA, though no classified networks were compromised. Separately, the Treasury's FinCEN disclosed a cyber incident, taking affected reporting systems offline during forensic investigation. [More info](https://www.bleepingcomputer.com/news/security/hackers-reportedly-breached-cia-intelligence-analysis-system/)

## 📚 Others

  - **Microsoft Confirms NTLM Authentication Failures Post-Patch**: Microsoft acknowledged that November's security updates patching Windows RPC flaw CVE-2026-118737 enforce stricter NTLM message signing, breaking third-party SSO and proxy solutions with incomplete `TargetInfo` fields. Admins can temporarily set `ClientAllowUnsignedNtlm` to `1` while migrating to Kerberos or awaiting vendor updates. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-confirms-authentication-issues-after-november-updates/)

  - **Integrating AI Safely into Penetration Testing Workflows**: As compliance mandates like DORA and NIS2 drive pentesting demand, teams can safely use self-hosted LLMs via typed interfaces like MCP to automate report drafting, scanner deduplication, and consistency checks—cutting documentation overhead while keeping human testers in control of exploit validation. [More info](https://www.bleepingcomputer.com/news/security/more-pentests-without-more-pentesters-where-ai-safely-helps/)

---

[⬅ Back to Archive](https://pranakn.github.io)
