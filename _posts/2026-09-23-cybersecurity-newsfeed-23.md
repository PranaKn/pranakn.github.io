---
title: "Cybersecurity Newsfeed - 23/09/26"
date: 2026-09-22 09:00:00 -0300
categories: [News]
permalink: /posts/news-23-09-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-09-23.png
  alt: Cybersecurity Newsfeed - 23/09/26
---

# Cybersecurity Newsfeed

## 📅 23/09/26

## 🛡️ Vulnerabilities

- **CISA Adds Four Vulnerabilities to KEV Catalog**: CISA updated its KEV catalog with four actively exploited security flaws, including CVE-2026-85102, CVE-2026-93616, CVE-2026-93952, and CVE-2026-94127. Federal civilian agencies are required under BOD 26-04 to prioritize remediation of these vulnerabilities. [More info](https://www.cisa.gov/news-events/alerts/2026/09/22/cisa-adds-four-known-exploited-vulnerabilities-catalog)

- **Check Point Emergency Hotfix for Management Server Zero-Day (CVE-2026-93616)**: Check Point released urgent hotfixes for an actively exploited path traversal flaw in its Security Management Server platform. The vulnerability allows unauthenticated attackers to remotely upload and execute arbitrary scripts, compromising central policies and logs across impacted products like Multi-Domain Management, Log Server, and SmartEvent. [More info](https://securityaffairs.com/199549/security/check-point-fixes-a-new-actively-exploited-critical-security-flaw.html) | [More info](https://www.bleepingcomputer.com/news/security/check-point-patches-management-server-zero-day-exploited-in-attacks/)

- **Windows Zero-Day "BigDiskBuster" Blocks Defender Updates**: Security researcher Abdelhamid Naceri released BigDiskBuster, a zero-day proof-of-concept exploit that prevents Microsoft Defender Antivirus from receiving definition and platform updates. Running as a background process, the tool leaves endpoints stuck on their existing signature baseline. [More info](https://www.theregister.com/security/2026/09/22/nightmareeclipses-latest-zero-day-leaves-microsoft-defender-stuck-in-the-past/5298320) | [More info](https://www.bleepingcomputer.com/news/security/new-windows-defender-zero-day-blocks-microsoft-antivirus-updates/)

- **D-Link Max-Severity Zero-Day Bug in DIR-822A Routers (CVE-2026-86296)**: A maximum-severity stack-based buffer overflow in the DHCP server component of legacy DIR-822A routers allows unauthenticated local attackers to cause service crashes or execute arbitrary code. D-Link is also investigating a second critical out-of-bounds write flaw (CVE-2026-86510) in the device's L2TP parser. [More info](https://www.bleepingcomputer.com/news/security/d-link-warns-of-max-severity-zero-day-bug-in-dir-822a-routers/)

- **Linux Kernel ARM64 KVM Hypervisor Memory Escape Flaw (CVE-2026-89775)**: A calculation error during nested virtualization skips translation lookaside buffer invalidations in the ARM64 KVM hypervisor code, allowing guest virtual machines to read and write host kernel memory. The memory corruption vector enables local guest-to-host escapes or privilege escalation to root. [More info](https://thehackernews.com/2026/09/new-linux-kernel-flaw-gives-arm64-kvm.html)

- **SharePoint Server ToolPane Vulnerability Enables RCE (CVE-2026-65660)**: Technical details confirm a SharePoint Server vulnerability in the ToolPane component allows authenticated attackers to inject Register directives and trigger arbitrary class loading via .NET deserialization. The bug can be chained with older authentication bypasses to achieve pre-authentication RCE. [More info](https://thehackernews.com/2026/09/sharepoint-flaw-initially-listed-as.html)

- **Public PoC Released for Veeam Agent Privilege Escalation (CVE-2026-32996)**: Improper session validation over a local gRPC named pipe in Veeam Agent for Microsoft Windows allows standard users to extract session UIDs logged in publicly readable files and execute arbitrary commands as NT AUTHORITY\SYSTEM. Patches are available in version 13.0.2.29. [More info](https://securityaffairs.com/199532/security/public-poc-exposes-critical-veeam-agent-privilege-escalation.html)

- **WordPress Patches High-Severity Comment2Shell RCE (CVE-2026-93485)**: A stored XSS vulnerability in WordPress allowed unauthenticated visitors to insert crafted line breaks into comments, triggering payload execution when an administrator views the page to upload a web shell. The flaw was fixed in version 7.1.1 and backported to older branches. [More info](https://thehackernews.com/2026/09/wordpress-comment2shell-flaw-can-turn.html)

- **Four Linux Kernel Flaws Expose Systems to Privilege Escalation**: Four disclosed Linux kernel vulnerabilities spanning network handling, memory management, and virtualization routines allow local attackers to bypass security controls, corrupt kernel memory, or escalate privileges to root. [More info](https://www.cysecurity.news/2026/09/four-linux-kernel-flaws-expose-systems.html)

- **WordPress Releases Updates for Click2Shell and Path Traversal Flaws**: WordPress version 7.1.1 addressed Click2Shell (CVE-2026-93485 derivative enabling unauthorized theme installation and RCE), while version 7.1.2 fixed an unauthenticated path traversal vulnerability in page-template resolution. Both updates were backported across supported release branches. [More info](https://www.securityweek.com/wordpress-patches-click2shell-vulnerability/) | [More info](https://wordpress.org/documentation/wordpress-version/version-7-1-2/)

## 🎯 Adversaries

- **Chinese Threat Actors Target Public Sector Infrastructure**: Chinese threat actors are exploiting flaws across diverse software platforms and network devices, including WordPress plugins and Zyxel networking equipment, to conduct multi-vector cyber campaigns and steal sensitive government data. [More info](https://www.bleepingcomputer.com/news/security/chinese-hackers-exploit-multiple-technologies-to-steal-govt-data/)

- **Microsoft and Law Enforcement Disrupt EvilTokens PhaaS Platform**: Microsoft and global partners disrupted EvilTokens (Storm-2992), an AI-powered phishing-as-a-service platform that compromised over 12,000 M365 accounts across 10,000 organizations. The platform abused OAuth 2.0 device code flows to bypass MFA, leading to site seizures and operator arrests in the UK. [More info](https://www.darkreading.com/identity-access-management-security/microsoft-disrupts-eviltokens-device-code-phishing-service) | [More info](https://www.microsoft.com/en-us/security/blog/2026/09/22/unmasking-eviltokens-getting-to-the-root-of-device-code-phishing/) | [More info](https://www.bleepingcomputer.com/news/security/eviltokens-phaas-disrupted-after-compromising-12-000-microsoft-accounts/)

- **ClosedQuorum Windows Malware Delegates Decisions to AI Ensembles**: A new Go-based malware named ClosedQuorum delegates post-compromise decisions to an ensemble of AI models including Gemini, DeepSeek, Qwen, and Mistral. Operating without active C2 instructions, the implant evaluates local reconnaissance data via voting mechanisms to execute LSASS dumping and credential theft. [More info](https://www.bleepingcomputer.com/news/security/new-closedquorum-windows-malware-uses-ai-for-attack-decisions/)

- **Fake LastPass Installers Deploy EDR-Killing Signed Driver**: Fake GitHub repositories masquerading as LastPass Authenticator installers are deploying a credential stealer paired with a signed kernel driver (`Alinubx.sys`). The driver uses BYOVD techniques to terminate 145 security processes from kernel space before exfiltrating credentials and tokens. [More info](https://thehackernews.com/2026/09/fake-lastpass-authenticator-installer.html)

- **ChainScript RAT Uses EtherHiding and ClickFix Lures**: The new ChainScript remote access trojan uses EtherHiding techniques by querying Polygon blockchain smart contracts to resolve active C2 endpoints. Distributed via ClickFix social engineering lures that trick users into running terminal commands, the malware targets both Windows and macOS users. [More info](https://securityaffairs.com/199471/malware/chainscript-the-rat-that-hides-its-command-server-inside-a-blockchain-contract.html) | [More info](https://thehackernews.com/2026/09/clickfix-lures-deploy-chainscript-rat.html)

## 📈 Trends

- **DavMail 7.0.0 Shifts to Microsoft Graph Amid EWS Retirement**: DavMail 7.0.0 transitions primary protocol translation support toward Microsoft Graph as Exchange Web Services reaches retirement. The update enables folder delta sync by default, improves shared calendar handling, and requests updated application permission scopes. [More info](https://www.helpnetsecurity.com/2026/09/22/davmail-7-0-0-microsoft-graph/)

- **Anthropic-Themed Lures Exploit Open-Source Package Managers**: Attackers are exploiting open-source repository workflows and package managers to distribute malicious dependencies masquerading as AI integration tools and Anthropic-related vulnerability references. [More info](https://www.theregister.com/security/2026/09/21/anthropic-linked-cves-pile-up-attackers-mostly-shrug/5298018)

- **Reducing Shadow IT Visibility Gaps with Wazuh SIEM**: A technical breakdown highlights how open-source Wazuh SIEM and XDR reduces shadow IT risks by collecting continuous system inventory directly from endpoints, surfacing unmonitored devices, unauthorized applications, and excessive browser extensions. [More info](https://www.bleepingcomputer.com/news/security/reducing-shadow-it-visibility-gaps-with-wazuh/)

## 💥 Breaches & Leaks

- **ShinyHunters Claims FBI Systems Hack via Oracle PeopleSoft Zero-Day**: Extortion group ShinyHunters claims to have breached internal FBI systems and exfiltrated sensitive personnel records and administrative databases by exploiting a zero-day vulnerability in Oracle PeopleSoft enterprise applications. [More info](https://www.bleepingcomputer.com/news/security/shinyhunters-claims-fbi-hack-data-theft-in-peoplesoft-zero-day-breach/)

- **CrowdSec Source Code Repositories Exposed in TanStack Supply Chain Attack**: Cybersecurity firm CrowdSec revealed that attackers exfiltrated approximately 170 private GitHub repositories after obtaining an OAuth token from an offboarded employee's machine via the TanStack npm package supply chain incident. Core databases and customer data remained unaffected. [More info](https://www.darkreading.com/cyberattacks-data-breaches/shai-hulud-attack-cyber-firm-crowdsec-github-data)

- **Gyazo Image Platform Breach Exposes 23.6 Million User Records**: Japanese software provider Helpfeel confirmed a major data breach on its Gyazo platform following a zero-day exploit on an image upload server. The breach exposed 23.62 million user records and metadata for 490 million uploaded images. [More info](https://www.helpnetsecurity.com/2026/09/21/helpfeel-gyazo-data-breach/)

---

[⬅ Back to Archive](https://pranakn.github.io)
