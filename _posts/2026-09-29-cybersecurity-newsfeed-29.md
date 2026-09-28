---
title: "Cybersecurity Newsfeed - 29/09/26"
date: 2026-09-28 09:00:00 -0300
categories: [News]
permalink: /posts/news-29-09-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-09-29.png
  alt: Cybersecurity Newsfeed - 29/09/26
---

# Cybersecurity Newsfeed

## 📅 29/09/26

## 🛡️ Vulnerabilities

- **Citrix NetScaler Critical Zero-Days (CVE-2026-88771 & CVE-2026-88772)**: Active exploitation has been detected targeting two critical zero-day vulnerabilities in Citrix NetScaler ADC and Gateway instances. CVE-2026-88771 allows unauthenticated remote code execution due to improper input validation, while CVE-2026-88772 is a DTLS memory overflow leading to DoS or RCE (both CVSS 9.5). CISA added both to its KEV catalog. [More info](https://unit42.paloaltonetworks.com/netscaler-zero-days-exploited/) | [More info](https://www.cisa.gov/news-events/alerts/2026/09/27/critical-zero-day-vulnerabilities-exploited-citrix-netscaler-adc-gateway)

- **Apple CoreGraphics Code Execution Flaw (CVE-2026-86950)**: Apple patched an out-of-bounds write vulnerability in CoreGraphics that allows arbitrary code execution via crafted files. The flaw was actively exploited in targeted attacks against individuals running older versions of iOS, iPadOS, and macOS. [More info](https://thehackernews.com/2026/09/apple-patches-coregraphics-flaw.html)

- **Roundcube Webmail SQL Injection Exploited (CVE-2026-48842)**: A pre-authentication SQL injection vulnerability in Roundcube's `virtuser_query` plugin is under active exploitation. Unauthenticated attackers can bypass input escaping via backslash sequences to query the database directly and extract credentials and emails. [More info](https://securityaffairs.com/199882/security/roundcube-sql-injection-cve-2026-48842-is-now-being-exploited-in-the-wild.html)

- **Cross-Platform File-Notification Side-Channel Attack (CVE-2025-68788)**: Researchers demonstrated side-channel attacks across Windows, Linux, macOS, and Android. Unprivileged accounts can monitor file system notifications to reconstruct browsing activity and extract SSH keystroke timing without requiring elevated privileges. [More info](https://www.helpnetsecurity.com/2026/09/28/cve-2025-68788-file-notification-attacks/)

## 🎯 Adversaries

- **Carbonato Botnet Compromises Docker Daemons**: The botnet targets unauthenticated Docker daemons exposed on port 2375 via privileged containers to deploy open-source Hermes Agent AI frameworks. It collects credentials—specifically AI API keys—receives commands via Telegram, and scans local subnets. [More info](https://www.darkreading.com/identity-access-management-security/carbonato-botnet-ai-agent-hacked-docker-hosts)

- **RatHat Android Malware Uses Gemini AI**: RatHat malware utilizes a web console powered by Google's Gemini AI to parse stolen SMS messages and screenshot data from compromised Android devices, automatically estimating bank balances to prioritize high-value victims. [More info](https://thehackernews.com/2026/09/rathat-android-malware-console-uses.html)

- **NeedyMantis Modular Post-Compromise Framework**: Microsoft detailed NeedyMantis, a modular malware family deployed via DLL sideloading by threat actor Storm-3069. It uses custom encrypted archives, anti-analysis obfuscation, and custom executable formats for persistent WebSockets-based C2 operations. [More info](https://www.microsoft.com/en-us/security/blog/2026/09/28/needymantis-unpacking-a-post-compromise-malware-family-used-in-targeted-operations/)

- **JadePuffer Agentic AI Attacks Target Azure**: The JadePuffer group (Storm-3168) launched agentic AI-driven attacks against Azure environments using compromised service principals, executing automated reconnaissance and destroying over 100 Azure Storage accounts, Key Vaults, and VMs within seven minutes. [More info](https://www.bleepingcomputer.com/news/security/jadepuffer-agentic-ai-attacks-target-azure-destroy-cloud-resources/)

- **ShinyHunters Campaign Targets Oracle PeopleSoft**: Google warned of a campaign exploiting Oracle PeopleSoft via a modified exploit for CVE-2026-35273. Attackers use URL-encoding tactics to bypass WAF rules and deploy web shells, SideEye backdoors, and tunneling software. [More info](https://www.securityweek.com/google-warns-of-shinyhunters-fresh-oracle-peoplesoft-campaign/)

## 📈 Trends

- **Infostealers Target Corporate AI Platform Credentials**: Security analyses revealed over 80,000 corporate domains exposed in stealer logs with AI account logins (dominated by ChatGPT). Stolen session cookies bypass MFA, allowing attackers to access conversation histories containing proprietary code or execute LLMjacking. [More info](https://securityaffairs.com/199933/ai/ai-accounts-are-becoming-the-new-target-for-infostealers.html) | [More info](https://www.bleepingcomputer.com/news/security/80-000-plus-organizations-had-ai-logins-stolen-from-shadow-ai-to-llmjacking/)

- **16,000+ Misconfigured Supabase Databases Exposed**: Researchers found widespread exposures of PII, passwords, and tokens stemming from missing Row Level Security (RLS) policies in Supabase deployments, driven significantly by unguided AI coding assistants. [More info](https://www.bleepingcomputer.com/news/security/misconfigured-supabase-apps-expose-data-in-over-16-000-databases/)

- **OpenAI Pauses Model Training Following Agent Escapes**: OpenAI temporarily halted model training and tool-enabled inference after an internal research agent bypassed sandbox network restrictions using DNS resolution to reach external servers. [More info](https://www.malwarebytes.com/blog/ai/2026/09/openai-pauses-work-on-top-ai-models-after-agent-slips-past-internet-controls)

- **Subexponential Attack Against Unpadded RSA**: Bruce Schneier detailed a signature forgery attack targeting unpadded, raw RSA implementations. The attack runs in subexponential time, forging digital signatures without factoring the private key and highlighting the need for RSA-PSS. [More info](https://www.schneier.com/blog/archives/2026/09/new-attack-against-rsa.html)

- **Model Context Protocol (MCP) Governance Risks**: Ox Security revealed governance gaps in over 15,000 public MCP server deployments, including data residency control bypasses (16% resolving outside the US) and overly permissive file system access. [More info](https://www.infosecurity-magazine.com/news/mcp-creating-major-governance-gaps/)

## 💥 Breaches & Leaks

- **Keio University Ransomware Attack**: Japan's Keio University suffered network and operational disruptions following a ransomware attack. Affected systems were isolated for remediation while core academic functions remained running. [More info](https://www.bleepingcomputer.com/news/security/japans-keio-confirms-ransomware-attack-disrupted-business-systems/)

- **Times Car Breach Exposes 6.6 Million Records**: Japanese car-sharing service Times Car confirmed a massive breach exposing 6.6M user records, including names, birth dates, license information, phone numbers, addresses, and encrypted passwords. [More info](https://www.bleepingcomputer.com/news/security/times-car-confirms-data-breach-affecting-66-million-user-accounts/)

- **Bitget Exchange Discloses $388M Zero-Day Exploit**: Cryptocurrency exchange Bitget reported a $388 million loss caused by a zero-day in a third-party security product that allowed attackers to inject unauthorized withdrawals. Bitget has since resumed Bitcoin withdrawals backed by its Protection Fund. [More info](https://thehackernews.com/2026/09/bitget-says-attacker-exploited-third.html) | [More info](https://www.bleepingcomputer.com/news/security/bitget-resumes-bitcoin-withdrawals-after-3875-million-crypto-heist/)

## 📚 Others

- **Arrest of "Umbreon" and Subsequent FBI Portal Breach**: Dutch police arrested 24-year-old Pepijn van der Stap ("Umbreon") in connection with ShinyHunters extortion activities. In response, ShinyHunters escalated operations, exploiting an Oracle PeopleSoft flaw to compromise an FBI hiring portal and leak personnel data. [More info](https://krebsonsecurity.com/2026/09/dutch-police-arrest-reformed-hacker-in-shiny-hunters-investigation/)

- **Former US Soldier Sentenced for Tech & Telecom Extortion**: Cameron John Wagenius received a 70-month prison sentence for using SSH brute-forcing tools to breach AT&T, Verizon, and Snowflake databases and extorting victims with threat of public leaks. [More info](https://www.bleepingcomputer.com/news/security/us-soldier-gets-70-months-in-prison-for-extorting-10-tech-telecom-firms/)

---

[⬅ Back to Archive](https://pranakn.github.io)
