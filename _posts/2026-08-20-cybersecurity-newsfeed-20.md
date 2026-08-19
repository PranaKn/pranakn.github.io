---
title: "Cybersecurity Newsfeed - 20/08/26"
date: 2026-08-19 09:00:00 -0300
categories: [News]
permalink: /posts/news-20-08-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-08-20.png
  alt: Cybersecurity Newsfeed - 20/08/26
---

# Cybersecurity Newsfeed

## 📅 20/08/26

## 🛡️ Vulnerabilities

- **MLflow SSRF Vulnerability (CVE-2026-64849)**: CISA added an MLflow Server-Side Request Forgery flaw to its KEV catalog following confirmed active exploitation. Attackers can abuse input parameters to send unauthorized HTTP requests from the underlying server. Federal agencies are mandated to check for compromise before patching. [More info](https://www.cisa.gov/news-events/alerts/2026/08/19/cisa-adds-one-known-exploited-vulnerability-catalog)

- **CISA Adds macOS, SharePoint, vCenter, and IKE Flaws to KEV**: CISA expanded its catalog with four actively exploited vulnerabilities: Apple macOS Screen Sharing (CVE-2026-65400) abused to install Monero miners; Microsoft SharePoint authentication bypass (CVE-2026-55040); VMware vCenter path traversal (CVE-2026-59310) used by China-linked actors; and Microsoft IKE double free (CVE-2026-33824). Federal agencies must patch immediately. [More info](https://thehackernews.com/2026/08/critical-macos-sharepoint-vcenter-and.html) | [More info](https://www.cisa.gov/news-events/alerts/2026/08/18/cisa-adds-four-known-exploited-vulnerabilities-catalog)

- **Critical Memory Corruption Bugs in Google Chrome**: Google released Chrome version 151.0.7922.169/.170 fixing 15 security flaws, including two critical buffer overflows in WebGL (CVE-2026-76034) and Dawn/WebGPU (CVE-2026-76036). Remote attackers can execute arbitrary code outside the browser sandbox via malicious HTML pages. [More info](https://www.malwarebytes.com/blog/bugs/2026/08/update-chrome-now-two-critical-vulnerabilities-fixed)

- **Windows IKE Extension Flaw Exploited in Attacks (CVE-2026-33824)**: CISA alerted that unauthenticated attackers are actively exploiting a critical double free flaw in Microsoft Internet Key Exchange Extensions. Sending crafted UDP packets to ports 500 or 4500 enables remote code execution across Windows endpoints and servers. [More info](https://www.bleepingcomputer.com/news/security/cisa-critical-windows-ike-extension-flaw-now-exploited-in-attacks/)

- **Microsoft Copilot "CoSnitch" Flaws (CVE-2026-24301)**: Varonis detailed three vulnerabilities in Copilot Personal enabling one-click data exfiltration and long-term memory manipulation via URL prompt injection. Attackers can automatically trigger prompts to steal data from connected services or inject persistent instructions. Microsoft patched the issues on August 18. [More info](https://thehackernews.com/2026/08/microsoft-copilot-personal-flaws-could.html)

- **Apple Image Processing Code Execution (CVE-2026-65346)**: Apple released updates across iOS, iPadOS, and macOS Tahoe addressing an integer overflow in the ImageIO framework. The vulnerability allows arbitrary code execution or privilege escalation simply by processing a specially crafted image file. [More info](https://www.malwarebytes.com/blog/bugs/2026/08/apple-fixes-another-image-processing-flaw-that-could-allow-code-execution)

- **Ransomware Gangs Exploit Windows Task Host Flaw (CVE-2025-60710)**: CISA updated its KEV entry to warn that ransomware operators are actively exploiting a Windows Task Host link-following flaw patched in late 2025. Local users with basic rights can escalate to SYSTEM privileges on Windows 11 and Windows Server 2025. [More info](https://www.bleepingcomputer.com/news/security/cisa-windows-task-host-flaw-now-exploited-by-ransomware-gangs/)

## 🎯 Adversaries

- **CameraSwarm Campaign Compromises 14,500 Dahua Cameras**: A 35-day campaign compromised over 14,500 Dahua IP cameras across Ukraine and Russia using TCP brute-forcing, CVE-2021-33044/33045 exploitation via a custom "p2pwn" tool, and cloud-relay attacks. The created backdoor accounts survive factory resets on most firmware. [More info](https://www.bleepingcomputer.com/news/security/hackers-compromise-14-500-dahua-web-cameras-in-35-day-campaign/)

- **Fake Crypto Exec Targets Security Researcher Post-DEF CON**: A targeted social engineering campaign hit a researcher using a booby-trapped Google Doc sent by an actor impersonating a cryptocurrency executive. The document contained an embedded malicious payload designed to compromise the endpoint upon interaction. [More info](https://www.itsecurityguru.org/2026/08/19/fake-crypto-exec-used-booby-trapped-google-doc-to-target-security-researcher-after-def-con/)

- **Grandoreiro Banking Trojan Targets Latin America**: Acronis observed a new Grandoreiro campaign with 40% of detections in Mexico. Attackers leverage DLL sideloading via a modified mingwm10.dll file alongside a renamed Duplicate Files Finder utility, incorporating heavy evasion and multi-stage loading routines. [More info](https://www.infosecurity-magazine.com/news/grandoreiro-mexico-dll-sideloading/)

- **Medusa Ransomware Hits Over 500 Critical Infrastructure Orgs**: A joint CISA, FBI, and HHS advisory revealed Medusa ransomware has impacted over 500 critical organizations globally. Operating a RaaS model, the group pays initial access brokers up to $1M for exclusive access to target environments. [More info](https://www.bleepingcomputer.com/news/security/cisa-medusa-ransomware-hit-over-500-critical-infrastructure-orgs/)

- **Clop Gang Uses Custom JSP Web Shell on Windchill Servers**: ReliaQuest identified a custom JSP web shell deployed by Clop exploiting CVE-2026-12569 in PTC Windchill and FlexPLM servers. Interfacing directly with internal APIs and database schemas, the shell decrypts LDAP credentials and exfiltrates files via custom HTTP headers. [More info](https://www.bleepingcomputer.com/news/security/clop-created-custom-web-shell-for-windchill-data-theft-attacks/)

- **"Ransom Busters" Affiliate Poses as Recovery Firm**: GuidePoint Security uncovered a rogue ransomware affiliate operating as "Ransom Busters" that contacts breach victims posing as a recovery service. The actor offers to delete stolen data or provide decryption keys for $20K–$60K to bypass RaaS revenue-sharing models. [More info](https://www.darkreading.com/cyberattacks-data-breaches/ransom-busters-ransomware-actor-incident-recovery-service) | [More info](https://www.bleepingcomputer.com/news/security/rogue-ransomware-affiliate-ransom-busters-poses-as-data-recovery-firm/)

- **Evooo1Bot Targets Edge Devices and Firewalls**: Fortinet discovered a new Mirai-based botnet targeting Linux edge devices, firewalls, and IoT hardware. Evooo1Bot uses AES-256/ChaCha20 encryption over port 443, embeds 18 exploits, and features a !socks module to convert hosts into proxy nodes for routing malicious traffic. [More info](https://securityaffairs.com/197434/malware/new-mirai-based-evooo1bot-botnet-targets-linux-devices.html)

## 📈 Trends

- **Unmoderated "Kriminal" AI Platform Emerges**: ThreatDown uncovered a subscription-based cybercrime platform providing unmoderated AI tools for OSINT, social engineering, and exploit drafting. The platform aggregates existing models (Grok, Claude, Llama) via OpenRouter routed through Cloudflare and Google Cloud. [More info](https://www.darkreading.com/application-security/no-filter-kriminal-ai-platform-cybercrime-concerns)

- **Password Spraying Attacks Surge 155x via Azure CLI**: Huntress reported a massive spike in password spraying targeting Microsoft's Azure CLI. Originating from an IPv6 range, attackers leveraged leaked credential lists to exploit legacy Resource Owner Password Credentials (ROPC) OAuth flows and bypass MFA. [More info](https://www.bleepingcomputer.com/news/security/password-spraying-attacks-surge-155x-as-hackers-exploit-mfa-gaps/)

## 💥 Breaches & Leaks

- **Sakura Internet Breach Exposes Data of 1.36 Million Accounts**: Japanese provider Sakura Internet disclosed a breach where unauthorized actors accessed its sales management system, exposing contract and membership data of up to 1.36M member accounts following a separate intrusion on its rental server platform. [More info](https://www.bleepingcomputer.com/news/security/sakura-internet-hack-exposes-data-of-up-to-136-million-accounts/)

- **CareCloud Breach Impacts 3.7 Million Patients**: Healthtech firm CareCloud disclosed that a March 2026 AWS breach affected over 3.75 million individuals. Threat actors exfiltrated database records containing sensitive personal information, causing an eight-hour network disruption. [More info](https://www.bleepingcomputer.com/news/security/healthtech-firm-carecloud-data-breach-impacts-37-million-patients/)

---

[⬅ Back to Archive](https://pranakn.github.io)
