---
title: "Cybersecurity Newsfeed - 28/09/26"
date: 2026-09-27 09:00:00 -0300
categories: [News]
permalink: /posts/news-28-09-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-09-28.png
  alt: Cybersecurity Newsfeed - 28/09/26
---

# Cybersecurity Newsfeed

## 📅 28/09/26

## 🛡️ Vulnerabilities

- **Citrix NetScaler Zero-Days Exploited (CVE-2026-88771 & CVE-2026-88772)**: Citrix released security updates for NetScaler ADC and NetScaler Gateway following active zero-day exploitation of two critical 9.5 CVSS flaws. CVE-2026-88771 permits unauthenticated remote code execution via improper input validation in default setups, while CVE-2026-88772 allows RCE or DoS via a DTLS memory buffer overflow. CISA added both to its Known Exploited Vulnerabilities catalog under Binding Operational Directive 26-04. [More info](https://www.cisa.gov/news-events/alerts/2026/09/27/cisa-adds-two-known-exploited-vulnerabilities-catalog) | [More info](https://www.bleepingcomputer.com/news/security/citrix-admins-warned-to-shut-down-netscalers-over-2-exploited-zero-days/)

- **Cloudflare Containers Cross-Tenant Storage Leak**: Cloudflare patched a cross-tenant isolation flaw within Workers Paid Containers and Sandboxes where un-cleared 64 KiB physical disk blocks leaked leftover filesystem metadata, SQLite databases, .env files, and credentials to new tenants. Cloudflare disabled block reuse, retired active container disks, and confirmed no malicious exploitation occurred. [More info](https://www.bleepingcomputer.com/news/security/cloudflare-fixes-containers-cross-tenant-flaw-exposing-customer-data/) | [More info](https://thehackernews.com/2026/09/cloudflare-fixes-flaw-that-let-one.html)

- **ShinyHunters WAF Bypass on Oracle PeopleSoft (CVE-2026-35273)**: Threat group ShinyHunters (UNC6240) is exploiting an unauthenticated remote code execution flaw in Oracle PeopleSoft by using percent-encoded request paths (e.g., `/%50SEMHUB/`) to bypass WAF string-matching rules. WebLogic decodes the paths to execute JSP web shells, SIDEEYE backdoors, and Neo-reGeorg SOCKS5 proxies. [More info](https://www.bleepingcomputer.com/news/security/shinyhunters-uses-waf-bypass-trick-in-oracle-peoplesoft-attacks/) | [More info](https://thehackernews.com/2026/09/attackers-bypass-wafs-to-exploit-oracle.html)

- **Critical CSRF Flaw in Elementor Plugin**: A cross-site request forgery vulnerability in versions 4.3.0 and 4.3.1 of the Elementor Website Builder WordPress plugin bypasses REST API nonce checks via crafted request URIs containing `elementor/v1/events/`. The issue, fixed in version 4.3.2, allows unauthenticated attackers to force administrative actions such as creating malicious admin accounts. [More info](https://thehackernews.com/2026/09/elementor-csrf-flaw-lets-attackers-take.html)

- **CISA Adds SharePoint, MikroTik, and WordPress Flaws to KEV**: CISA expanded its KEV catalog with CVE-2026-65660 (SharePoint network code injection), CVE-2026-67279 (MikroTik RouterOS authentication handling error exploited via MikroTrick), and CVE-2026-87902 (WordPress Core remote file inclusion allowing full server execution). Federal agencies must prioritize rapid patching. [More info](https://thehackernews.com/2026/09/sharepoint-rce-and-mikrotik-routeros.html) | [More info](https://www.cisa.gov/news-events/alerts/2026/09/25/cisa-adds-one-known-exploited-vulnerability-catalog) | [More info](https://www.bleepingcomputer.com/news/security/elementor-wordpress-flaw-lets-attackers-create-admin-accounts/)

## 🎯 Adversaries

- **Lunex MaaS Delivers Infostealer via BYOVD Attack**: Cybercrime platform Lunex uses ClickFix lures on compromised websites to deploy LunexStealer (Psychedelic Stealer) to Ukrainian targets. The infection abuses a vulnerable AMD Radeon kernel driver (CVE-2023-20598) to blind EDR process callbacks, harvests credentials across seven Chromium browsers, and installs a persistent PowerShell Chrome Native Messaging Host. [More info](https://thehackernews.com/2026/09/lunex-stealer-abuses-amd-driver-to.html) | [More info](https://securityaffairs.com/199731/malware/clickfix-campaign-abuses-trusted-websites-to-deploy-psychedelic-stealer.html)

- **GitHub Actions Re-enabled with Active Supply-Chain Payload**: compromised GitHub Actions (`actions-cool/issues-helper` and `actions-cool/maintain-one-comment`) from May 2026's Mini Shai-Hulud campaign were temporarily re-enabled with malicious commit tags intact. Workflows referencing these actions automatically executed obfuscated JavaScript designed to harvest CI/CD secrets before GitHub re-disabled the repositories. [More info](https://www.bleepingcomputer.com/news/security/github-actions-re-enabled-with-mini-shai-hulud-payload-still-active/)

- **Storm-3168 Destroys Azure Infrastructure via Compromised Service Principals**: Microsoft Security Research detailed attacks by Storm-3168 (JADEPUFFER), who leveraged two exposed service principal credentials found in a public GitHub issue to purge Azure Storage Accounts, Key Vaults, and SQL databases, while deploying automated `ListKeys` queries for credential harvesting. [More info](https://www.microsoft.com/en-us/security/blog/2026/09/25/storm-3168-agentic-driven-cloud-attacks-using-compromised-service-principals/)

- **PamStealer macOS Malware Adds Server-Side Decryption**: Jamf Threat Labs discovered a updated PamStealer variant distributed via fake "Wavel" crypto wallet DMGs. The Swift-based malware conducts X25519 key exchanges with C2 servers for in-memory payload decryption, alters global Git hooks for persistence, and captures PAM-authenticated passwords and browser credentials. [More info](https://thehackernews.com/2026/09/pamstealer-macos-malware-adds-live-c2.html)

- **Kiteworks Requests Precautionary 6-Hour Shutdown Over Zero-Day Risk**: Secure file-transfer vendor Kiteworks urged global enterprise customers to disconnect running appliances for six hours following federal law enforcement warnings of an imminent targeted cyberattack, recommending emergency upgrades to version 9.5.1. [More info](https://thehackernews.com/2026/09/kiteworks-urges-customers-to-shut-down.html) | [More info](https://www.bleepingcomputer.com/news/security/kiteworks-urges-6-hour-server-shutdown-over-potential-zero-day-attacks/)

## 📈 Trends

- **Roots of Modern RaaS Uncovered in Historical Cybercrime Forums**: Database dumps from Russian forum Exploit.in (2005–2008) reveal that early private access tiers, reputation tracking, and escrow mechanisms laid the direct foundation for today's ransomware-as-a-service, initial access brokerage, and affiliate models, with over 200 handles remaining active across two decades. [More info](https://securityaffairs.com/199800/cyber-crime/exploit-in-database-reveals-the-roots-of-todays-ransomware-ecosystem.html)

- **Zero Trust Controls Required for Autonomous AI Agents**: Securing autonomous AI agent deployments requires continuous inventory tracking and unique identity binding to counter unmonitored shadow AI, encrypted provider traffic, and ephemeral runtimes before enforcing Zero Trust policies. [More info](https://thehackernews.com/2026/09/zero-trust-for-ai-agents-starts-with.html)

- **360 Intelligence Reports Surge in Autonomous AI Threats**: A weekly security report highlighted emerging AI threats, including the CLOSEDQUORUM autonomous C2 implant, multi-agent clusters breaching 395 organizations via PaperCut in four hours, EvilTokens O365 device-code phishing platforms, and malicious installers disguised as DeepSeek and Doubao. [More info](https://blog.netlab.360.com/aian-quan-zhuan-ti-zhou-bao-7/)

- **LinkedIn Rolls Out Verification Checks to Counter Fake AI Profiles**: LinkedIn introduced peer mutual-vouching and employee directory management rights for page admins to eliminate synthetic AI-generated work histories and reduce the risk of social engineering or recruitment scams. [More info](https://www.malwarebytes.com/blog/news/2026/09/linkedin-adds-new-checks-for-fake-profiles-and-work-histories)

## 🤖 Artificial Intelligence

- **Anthropic Launches Claude Marketplace with 2,000+ Integrations**: Anthropic introduced the Claude Marketplace, connecting over 2,000 plugins, connectors, and enterprise tools built on the Model Context Protocol (MCP) and Agent Skills frameworks, featuring partners such as Atlassian, Google, Microsoft, Notion, Salesforce, CrowdStrike, and Snowflake. [More info](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropic-turns-claude-into-an-ai-marketplace-with-2-000-plus-plugins-and-connectors/)

- **Claude Opus 5.5 Significantly Reduces Synthetic Text Markers**: Arena benchmark analysis reveals Claude Opus 5.5 uses 95% fewer em dashes (dropping to 0.8 per 1,000 words) and fewer semicolons, alongside shorter 10-word sentence structures designed to reduce recognizable machine-generated writing artifacts while expanding overall response length. [More info](https://www.bleepingcomputer.com/news/artificial-intelligence/claude-opus-55-uses-95-percent-fewer-em-dashes-but-its-answers-are-getting-longer/)

- **Anthropic Offers Up to $250 in Free Cloud Session Credits for Claude Code**: Anthropic introduced cloud-hosted asynchronous sessions for Claude Code across web, mobile, and CLI interfaces, offering up to $250 in promotional credits to Max subscribers and $100 to Pro subscribers through November 4, 2026. [More info](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropic-rolls-out-up-to-250-in-free-claude-code-credits-but-only-for-cloud-sessions/)

## 🛠️ IT & Software

- **Microsoft Pauses M365 Update KB5002907 After Office Deactivations**: Microsoft suspended update KB5002907 after the optional patch incorrectly executed on perpetual Office 2016 and Office 2019 installations, marking applications as unlicensed or triggering accidental software uninstalls. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-365-kb5002907-update-paused-after-office-license-deactivations/)

## ⚖️ Legal & Law Enforcement

- **Admin of Rydox Marketplace Pleads Guilty in US Federal Court**: Kosovar national Ardit Kutleshi pleaded guilty to money laundering conspiracy and identity theft for running Rydox, an illicit underground forum that processed 7,600 transactions involving stolen SSNs and cybercrime tools, facing up to 22 years in prison. [More info](https://www.bleepingcomputer.com/news/security/rydox-marketplace-admin-pleads-guilty-faces-22-years-in-prison/)

---

[⬅ Back to Archive](https://pranakn.github.io)
