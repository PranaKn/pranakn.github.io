---
title: "Cybersecurity Newsfeed - 10/06/26"
date: 2026-06-09 09:00:00 -0300
categories: [News]
permalink: /posts/news-10-06-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-06-10.png
  alt: Cybersecurity Newsfeed - 10/06/26
---

# Cybersecurity Newsfeed

## 📅 10/06/26

## 🛡️ Vulnerabilities

- **Microsoft Defender "RoguePlanet" Zero-Day**: A security researcher released a zero-day exploit allowing attackers to spawn a command prompt with SYSTEM privileges via a race condition. ThreatLocker confirmed its viability on fully patched Windows 11 systems. Previously developed as an RCE exploit for remote SMB shares, the proof-of-concept was made public following a dispute over vulnerability disclosure practices. Organizations are advised to use application allowlisting to block execution. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-defender-rogueplanet-zero-day-grants-system-privileges/)

- **Microsoft June 2026 Patch Tuesday Addresses 206 Flaws**: Microsoft's latest security updates patch 206 vulnerabilities, including 32 rated "critical." Among these are 28 remote code execution (RCE) flaws affecting Windows components like Active Directory, Kerberos KDC, and the Windows Graphics component, with CVE-2026-42985 (Remote Desktop Client) and CVE-2026-47291 (Windows HTTP Protocol Stack) being notable highlights. [More info](https://blog.talosintelligence.com/microsoft-patch-tuesday-for-june-2026-snort-rules-and-prominent-vulnerabilities/)

- **"Ghost-Sender" Configuration Weakness in Exchange**: A flaw enables attackers to spoof any email address, completely bypassing standard SPF, DKIM, and DMARC checks. This impacts organizations using Exchange Online or hybrid on-premises setups with third-party mail servers as their MX record. Attackers can leverage simple PowerShell commands to send spoofed emails that display legitimate profile pictures in Outlook. [More info](https://www.darkreading.com/vulnerabilities-threats/exchange-flaw-attackers-spoof-email-address)

- **CISA Adds Three Vulnerabilities to KEV Catalog**: CISA expanded its Known Exploited Vulnerabilities catalog with CVE-2026-7473 (Arista EOS incomplete comparison), CVE-2026-11645 (Google Chromium V8 out-of-bounds flaw), and CVE-2026-20245 (Cisco Catalyst SD-WAN Manager output encoding bug). Federal Civilian Executive Branch agencies must remediate these bugs by their deadlines. [More info](https://www.cisa.gov/news-events/alerts/2026/06/09/cisa-adds-three-known-exploited-vulnerabilities-catalog)

- **SAP Fixes 15 Vulnerabilities, Including 4 Critical**: SAP released its June 2026 Security Patch package addressing critical flaws in NetWeaver and Commerce Cloud. Notable fixes include CVE-2026-44748 (authentication bypass in SAML-based environments), CVE-2026-27671 (memory corruption in ABAP Platform), and CVE-2026-40128 (directory traversal in Java Web Container). [More info](https://www.bleepingcomputer.com/news/security/sap-fixes-critical-flaws-in-netweaver-and-commerce-cloud/)

- **Adobe Patches 123 Vulnerabilities Across 11 Products**: The security updates address flaws in Experience Manager, ColdFusion, Acrobat, and more. Most are XSS issues that could allow arbitrary code execution, including two critical CVSS 10 vulnerabilities in Adobe Campaign Classic. While no active exploitation is reported, ColdFusion and Campaign Classic updates are high priority. [More info](https://www.securityweek.com/adobe-patches-123-vulnerabilities/)

- **OpenSSL Patches 18 Flaws, Assisted by AI**: OpenSSL has patched 18 vulnerabilities, highlighted by a high-severity use-after-free flaw (CVE-2026-45447) in PKCS#7 signature verification that could lead to RCE. The flaw was discovered with the assistance of Claude AI, and researchers suggest AI models were instrumental in finding several of the patched bugs. [More info](https://www.securityweek.com/openssl-patches-high-severity-vulnerability-found-with-ai/)

- **Critical RCE Vulnerability in Veeam Backup & Replication**: Veeam has patched CVE-2026-44963, a critical RCE vulnerability affecting VBR versions 12.3.2.4465 and earlier. The flaw allows an authenticated domain user to gain RCE on domain-joined backup servers. Customers are urged to update to version 12.3.2.4854 immediately to protect against ransomware groups targeting backup infrastructure. [More info](https://www.bleepingcomputer.com/news/security/new-veeam-vulnerability-exposes-backup-servers-to-rce-attacks/)

- **Critical Authentication Bypass Flaws in phpBB**: A critical vulnerability (PTT-2026-004) allows unauthenticated attackers to hijack any phpBB account, including administrators, with a single request. A second flaw (PTT-2026-005) affects boards using OAuth, letting attackers bind credentials to a victim's account. Administrators should upgrade to version 3.3.17 immediately. [More info](https://www.infosecurity-magazine.com/news/phpbb-authentication-bypass/)

- **Google Patches Actively Exploited Chrome V8 Zero-Day**: Google released Chrome version 149.0.7827.102/103 to address 74 vulnerabilities, including CVE-2026-11645. This high-severity out-of-bounds memory access flaw in the V8 JavaScript engine allows remote code execution within the browser sandbox. This marks the fifth zero-day patched by Google in 2026. [More info](https://thehackernews.com/2026/06/chrome-v8-zero-day-cve-2026-11645.html)

- **Linux nf_tables Flaw Enables Root Escalation**: A use-after-free error in nf_tables (CVE-2026-23111) allows local unprivileged users to gain root access. The vulnerability, caused by an inverted condition in an abort path, can leak kernel addresses and hijack control flow. The exploit is highly stable on systems with unprivileged user namespaces enabled. [More info](https://securityaffairs.com/193352/hacking/cve-2026-23111-linux-nf_tables-flaw-enables-root-exploits.html)

- **CISA Emergency Directive Orders Patch for Check Point Flaw**: FCEB agencies have been ordered to patch CVE-2026-50751 in Check Point Remote Access VPN and Mobile Access gateways by June 11, 2026. The vulnerability allows unauthenticated remote attackers to bypass authentication on gateways using legacy IKEv1, and has been actively exploited by Qilin ransomware affiliates since May. [More info](https://www.bleepingcomputer.com/news/security/cisa-orders-feds-to-patch-check-point-flaw-exploited-by-ransomware-gangs/)

## 🎯 Adversaries

- **Attackers Target Cloud Logging Services to Evade Detection**: Threat actors are increasingly blinding security teams by disabling cloud logging mechanisms, deleting log storage destinations (such as S3 or Google Cloud log buckets), or removing log routers. Attackers may also modify encryption keys or engage in log poisoning to disrupt incident response and compliance monitoring. [More info](https://unit42.paloaltonetworks.com/cloud-logging-defense-evasion/)

- **"Argamal" RAT Distributed via Pirated Hentai Games**: Attackers are embedding the Argamal remote access Trojan into installers for pirated adult games. Once launched, a malicious DLL is loaded into memory, allowing attackers to control the device, steal files, monitor activity, and exfiltrate credentials. The malware evades detection by delaying execution and checking for virtual machines. [More info](https://www.kaspersky.com/blog/argamal-hentai-games-rat-trojan/55944/)

## 📈 Trends

- **AI Agents Susceptible to Phishing Attacks**: Varonis researchers demonstrated that autonomous AI agents like OpenClaw are vulnerable to classic phishing tactics. During simulations, an AI agent exposed sensitive credentials and customer data when manipulated by urgent, impersonated requests, highlighting a lack of identity verification and context awareness in autonomous agents. [More info](https://www.bleepingcomputer.com/news/security/openclaw-ai-agent-found-falling-for-phishing-attacks-spills-user-data/)

- **Public-Facing Linux Infrastructure Remains Highly Exposed**: Researchers warn that Linux systems with public-facing interfaces face continuous exploitation risks due to unpatched services and ongoing kernel framework vulnerabilities. Hardening public infrastructure, disabling unnecessary services, and maintaining robust patch management are critical to defending against evolving threats. [More info](https://www.cysecurity.news/2026/06/linux-systems-exposed-as-public.html)

- **"FROST" Side-Channel Attack Tracks User Activities**: Researchers uncovered a new timing-based side-channel attack called FROST that allows malicious websites to track which applications and websites a user has opened. By measuring subtle timing variations in SSD access when the operating system launches processes, malicious sites can infer user behavior. [More info](https://thehackernews.com/2026/06/new-frost-attack-lets-websites-track.html)

## 💥 Breaches & Leaks

- **ServiceNow Discloses Flaw Exploited to Access Customer Data**: ServiceNow suffered a security incident involving an unauthenticated access flaw in a vulnerable API endpoint, likely the `/api/now/related_list_edit/create` REST endpoint. Attackers exploited it to query sensitive customer data before a patch was applied on June 5, 2026. Administrators are advised to check logs for the IP address 51.159.98.241. [More info](https://www.bleepingcomputer.com/news/security/servicenow-discloses-security-incident-exposing-customer-data/)

- **French Government Messaging App "Tchap" Breached**: Hackers compromised a user account on the encrypted platform via social engineering, gaining access to conversations, documents, and media files. Threat actors claim to have exfiltrated 13.5GB of files along with data for over 73,000 users, including stolen LDAP credentials. Public unencrypted chat rooms were heavily exposed. [More info](https://www.bleepingcomputer.com/news/security/french-govt-messaging-service-breached-in-account-hijacking-attack/)

---

[⬅ Back to Archive](https://pranakn.github.io)
