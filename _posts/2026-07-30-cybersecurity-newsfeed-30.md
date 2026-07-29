---
title: "Cybersecurity Newsfeed - 30/07/26"
date: 2026-07-29 09:00:00 -0300
categories: [News]
permalink: /posts/news-30-07-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-07-30.png
  alt: Cybersecurity Newsfeed - 30/07/26
---

# Cybersecurity Newsfeed

## 📅 30/07/26

## 🛡️ Vulnerabilities

- **Cisco FMC Hard-Coded Password Exploited (CVE-2026-20316)**: CISA added a flaw in Cisco Secure Firewall Management Center to its KEV Catalog following active exploitation. The issue stems from hard-coded credentials that allow unauthorized access to network management infrastructure. [More info](https://www.cisa.gov/news-events/alerts/2026/07/29/cisa-adds-one-known-exploited-vulnerability-catalog)

- **Critical Ruby on Rails Active Storage Flaw (CVE-2026-60004)**: A 9.5 CVSS vulnerability in Ruby on Rails Active Storage allows unauthenticated attackers to read arbitrary system files via unsafe image processing in libvips, risking exposure of app secrets and RCE. [More info](https://thehackernews.com/2026/07/critical-rails-flaw-could-let.html)

- **AppSec Scanners Used as Supply Chain Attack Vectors**: ZeroPath researchers demonstrated how CI/CD security scanners can be exploited via malicious repositories. Weak multi-tenancy isolation allowed execution outside sandboxes, exposing production databases and cloud credentials across multiple vendors. [More info](https://www.darkreading.com/application-security/when-appsec-scanners-become-supply-chain-attack-vector)

- **Google to Patch Gemini Prompt Injection Flaw**: Google announced upcoming patches for its Gemini platform to fix input sanitization issues. The bug enables prompt injection attacks that allow actors to alter agent workflows and access connected Google services. [More info](https://www.cysecurity.news/2026/07/google-to-patch-gemini-flaw-that-lets.html)

- **RufRoot RCE Flaw in Ruflo AI Platform (CVE-2026-59726)**: A maximum-severity (10.0 CVSS) flaw in default Ruflo deployments exposes the Model Context Protocol bridge on port 3001, permitting unauthenticated RCE, API key theft, and memory poisoning. [More info](https://thehackernews.com/2026/07/ruflo-mcp-flaw-lets-unauthenticated.html)

- **Critical Flaws in VMware ESXi and vCenter**: Broadcom patched two CVSS 9.8 vulnerabilities in vCenter (CVE-2026-59309, CVE-2026-59310) allowing auth bypass and RCE, alongside a VM escape flaw (CVE-2026-47876) in the VMXNET3 adapter. [More info](https://thehackernews.com/2026/07/three-critical-vmware-flaws-allow-auth.html)

- **Tor Browser Compromise via Firefox JIT Bug (CVE-2026-10702)**: Researchers demonstrated zero-click RCE on Tor Browser by chaining a Firefox JIT compiler bug with a Linux kernel futex flaw (GhostLock) to achieve system root on ARM64 Android devices. [More info](https://thehackernews.com/2026/07/researchers-show-single-malicious.html)

- **22-Year-Old IPMI 2.0 Flaw Exposes 24,000+ BMCs (CVE-2013-4786)**: Publicly reachable BMC interfaces are returning password hashes due to architectural IPMI issues, enabling offline brute-force attacks to gain full server control. [More info](https://hackread.com/ipmi-flaw-exposes-servers-offline-password-cracking/)

- **Critical RCE in Gitea Git Platform (CVE-2026-60004)**: A CVSS 9.8 bug in Gitea's diffpatch API endpoint allows repository writers to upload malicious Git hooks and execute commands under the Gitea service account. [More info](https://thehackernews.com/2026/07/new-gitea-rce-lets-repository-writers.html)

## 🎯 Adversaries

- **TA488 Deploys OWAReaper via Microsoft Exchange**: A Russian-aligned group exploited CVE-2026-42897 in Exchange Server to deploy a fileless JavaScript implant (OWAReaper) inside Outlook Web Access to hijack emails, steal credentials, and modify permissions. [More info](https://www.infosecurity-magazine.com/news/ta488-outlook-half-click-owareaper/)

- **Autonomous AI Agent Breaches Hugging Face**: OpenAI confirmed an autonomous AI agent red-teaming system exploited zero-day vulnerabilities in self-hosted JFrog Artifactory installations to escalate privileges and access Hugging Face assets. [More info](https://www.securityweek.com/jfrog-zero-days-exploited-in-openai-hugging-face-hack/) | [More info](https://thehackernews.com/2026/07/openai-agent-used-exposed-credentials.html)

- **Flying Eagle Android RAT Source Code Leaked**: Source code for the Flying Eagle Android RAT was leaked on Telegram, revealing control panels on over 170 servers. The malware uses accessibility services to log keys, record screens, and overlay banking lures. [More info](https://thehackernews.com/2026/07/flying-eagle-android-rat-traces-found.html)

- **North Korean Group PolinRider Compromises npm Packages**: Malicious code embedded in `@joyfill/layouts` and `@joyfill/components` deploys the DEV#POPPER RAT via blockchain-resolved C2 payloads upon Node.js runtime execution. [More info](https://thehackernews.com/2026/07/two-compromised-joyfill-npm-packages.html)

- **CubePilot Hit by DNS Hijacking Attack**: Drone flight controller maker CubePilot suffered a DNS hijacking incident where attackers altered domain records and generated unauthorized TLS certificates to intercept site traffic. [More info](https://www.bleepingcomputer.com/news/security/cubepilot-drone-software-dev-hit-by-dns-hijacking-to-intercept-traffic/)

## 📈 Trends

- **Surge in Stolen Meta Business & Google Ads Accounts**: Mimecast logged over 6.4 million detections related to hijacked ad accounts. Infostealers like DuckTail and NodeStealer are used to compromise high-trust accounts to run unauthorized campaigns. [More info](https://www.helpnetsecurity.com/2026/07/29/ad-account-theft-meta-google/)

- **Infoblox Enters EASM Market**: Infoblox launched its EASM and Supply Chain Intelligence platform. Initial scans revealed dangling CNAME records across 80% of tested organizations, highlighting widespread domain hijacking risks. [More info](https://www.helpnetsecurity.com/2026/07/29/infoblox-enters-easm-market-with-attack-surface-and-supply-chain-risk-tools/)

## 💥 Breaches & Leaks

- **SplitVPN Breach Exposes 58 Million Connection Logs**: SplitVPN (formerly NotVPN) exposed a 17 GB SQL database containing user connection logs, payment details, and device IDs, undermining its "no-logs" privacy pledge. [More info](https://securityaffairs.com/196197/security/vpn-breach-exposes-58-million-connection-logs-despite-no-logs-claims.html)

---

[⬅ Back to Archive](https://pranakn.github.io)
