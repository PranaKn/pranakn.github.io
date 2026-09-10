---
title: "Cybersecurity Newsfeed - 10/09/26"
date: 2026-09-09 09:00:00 -0300
categories: [News]
permalink: /posts/news-10-09-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-09-10.png
  alt: Cybersecurity Newsfeed - 10/09/26
---

# Cybersecurity Newsfeed

## 📅 10/09/26

## 🛡️ Vulnerabilities

- **Maximum-Severity Cisco FMC Authentication Bypass (CVE-2026-20079)**: Cisco confirmed active exploitation of a CVSS 10.0 authentication bypass flaw in Secure Firewall Management Center (FMC) software. Unauthenticated remote attackers can send crafted HTTP requests to execute arbitrary commands with root privileges across on-premises and Security Cloud Control services. [More info](https://www.bleepingcomputer.com/news/security/cisco-confirms-cve-2026-20079-secure-fmc-flaw-exploited-in-attacks/)

- **CISA Adds Four Vulnerabilities to KEV Catalog**: CISA added CVE-2025-25249 (Fortinet buffer overflow), CVE-2026-19490 (Citrix NetScaler authentication bypass), CVE-2026-87491 (Google Chromium V8 write flaw), and CVE-2026-20079 (Cisco FMC root access flaw) to its KEV catalog, ordering federal agencies to patch immediately. [More info](https://www.cisa.gov/news-events/alerts/2026/09/09/cisa-adds-four-known-exploited-vulnerabilities-catalog)

- **Microsoft Defender "ShieldCrash" Zero-Day Disclosed**: A zero-day flaw in Microsoft Defender permits local privilege escalation to SYSTEM level and denial-of-service conditions by abusing real-time scanning engine file parsing routines. [More info](https://www.theregister.com/security/2026/09/09/serial-microsoft-0-day-hunter-drops-yet-another-defender-exploit/5295335) | [More info](https://www.bleepingcomputer.com/news/security/new-microsoft-defender-shieldcrash-zero-day-grants-system-access/)

- **Critical Pre-Auth RCE in N-able N-central**: A critical vulnerability in N-able N-central remote monitoring software allows unauthenticated remote attackers to send crafted requests and execute arbitrary commands with SYSTEM rights on central management servers. [More info](https://thehackernews.com/2026/09/n-able-n-central-pre-auth-rce-flaw.html)

- **Chrome 153 Patches Seventh Zero-Day of 2026 (CVE-2026-87491)**: Google addressed an actively exploited out-of-bounds write flaw in the Chrome V8 JavaScript engine that allows attackers to crash processes or execute arbitrary code. [More info](https://www.securityweek.com/chrome-153-patches-seventh-zero-day-of-2026/)

- **Critical Input Validation Flaw in Alby Hub**: Open-source Lightning Network management software Alby Hub fixed an API endpoint input validation flaw that could allow unauthenticated remote code execution and wallet draining. [More info](https://thehackernews.com/2026/09/alby-hub-critical-flaw-could-let.html)

- **Ivanti Issues Emergency Patches Across Enterprise Products**: Security updates addressed multiple critical remote code execution, SQL injection, and privilege escalation vulnerabilities affecting Endpoint Manager and Connect Secure appliances. [More info](https://www.securityweek.com/ivanti-patches-critical-flaws-across-enterprise-security-products/)

- **cPanel Shared Hosting Local Privilege Escalation**: A vulnerability in cPanel system management scripts allows web hosting users to bypass permission checks and elevate privileges to root across multi-tenant shared hosting environments. [More info](https://thehackernews.com/2026/09/new-cpanel-flaw-lets-hosting-account.html)

- **Bluetooth Hijacking Flaw in Skullcandy Dime 3 Earbuds**: Improper pairing authentication procedures in Skullcandy Dime 3 wireless earbuds allow nearby unauthenticated attackers to force connections, inject audio, or intercept microphone input. [More info](https://www.bleepingcomputer.com/news/security/skullcandy-dime-3-earbuds-expose-users-to-bluetooth-hijacking/)

- **Android September 2026 Security Updates Patch 180 Flaws**: Google released fixes for 180 vulnerabilities across system components, frameworks, and vendor hardware drivers, addressing high-severity remote code execution and privilege escalation flaws. [More info](https://www.securityweek.com/androids-september-2026-updates-patch-180-vulnerabilities/)

## 🎯 Adversaries

- **Four Espionage Groups Exploit Identical Chrome and Windows Zero-Days**: Four distinct state-sponsored APT groups independently deployed identical commercial exploit chains targeting browser parsing engines and Windows kernel privilege escalation flaws. [More info](https://thehackernews.com/2026/09/four-spy-groups-used-same-chrome-and.html)

- **AI-Powered "Blue Moon" Exploitation Framework Disclosed**: Threat actors are using the "Blue Moon" framework targeting Chrome and Windows environments, leveraging integrated AI code generation to automate exploit chain development and dynamic payload obfuscation. [More info](https://www.theregister.com/research/2026/09/09/novel-blue-moon-kit-targeting-chrome-and-windows-reflects-new-reality-of-ai-driven-exploits/5295399)

- **Fileless Memory Rootkit Targets F5 BIG-IP APM**: Threat actors are deploying a rootkit hiding a web shell entirely within volatile RAM on F5 BIG-IP Access Policy Manager appliances to evade file integrity checks and intercept authentication traffic. [More info](https://www.helpnetsecurity.com/2026/09/09/f5-big-ip-apm-rootkit-hides-web-shell-in-memory/)

- **US Accuses Chinese Firms of Extensively Scraping US AI Models**: US officials and agencies warned that foreign entities are using proxy networks to extract billions of tokens and model outputs from frontier American AI models via knowledge distillation techniques. [More info](https://www.bleepingcomputer.com/news/security/us-says-chinese-firms-extracted-billions-of-tokens-from-frontier-ai-models/) | [More info](https://www.helpnetsecurity.com/2026/09/09/china-malicious-ai-knowledge-distillation-against-us-companies/) | [More info](https://thehackernews.com/2026/09/us-agencies-accuse-china-ai-firms-of.html)

- **Passkey-Themed Social Engineering Attacks Cloud Identity**: Attackers are bypassing traditional MFA by tricking corporate employees into registering attacker-controlled passkeys during fake account recovery workflows. [More info](https://www.microsoft.com/en-us/security/blog/2026/09/09/passkey-themed-social-engineering-leads-identity-cloud-compromise/)

## 📈 Trends

- **Account Recovery Flow Becomes Primary MFA Bypass Vector**: Threat actors are shifting away from direct protocol attacks to target self-service password resets, help desk social engineering, and SIM swaps to reset parameters and gain access. [More info](https://www.bleepingcomputer.com/news/security/mfas-weakest-link-account-recovery-is-the-new-attack-path/)

- **Infostealer Logs Expose Replayable AI Session Tokens**: Leaked session cookies captured by infostealers allow unauthorized actors to replay active sessions and gain persistent access to corporate AI platform logs, prompt histories, and code snippets. [More info](https://thehackernews.com/2026/09/infostealer-logs-expose-replayable-ai.html)

- **Over 100,000 Fraudulent Online Stores Harvesting Payment Cards**: Threat researchers uncovered a network of over 100,000 fake retail storefronts that mimic legitimate brands to harvest consumer credit card details and personal identity data. [More info](https://www.malwarebytes.com/blog/scams/2026/09/more-than-100000-fake-stores-are-out-to-steal-your-card-details)

- **Microsoft Releases Cloud and Web Application Threat Matrix**: Microsoft published a comprehensive security framework detailing threat patterns across enterprise identity boundaries, cross-cloud tenant exposures, and web service API vulnerabilities. [More info](https://www.microsoft.com/en-us/security/blog/2026/09/09/threat-matrix-mapping-threats-across-cloud-web-applications/)

## 💥 Breaches & Leaks

- **AdaptHealth Discloses Healthcare Data Breach Impacting 4.1M People**: Medical supplier AdaptHealth confirmed a major breach following a July cyberattack that compromised personal identifiers, contact details, medical records, and health insurance information. [More info](https://www.bleepingcomputer.com/news/security/adapthealth-confirms-41-million-people-exposed-in-july-cyberattack/)

- **Veradigm Patient Data Breach Claimed by "Gentlemen" Group**: Healthcare software provider Veradigm confirmed a network intrusion resulting in the extraction of patient names, clinical details, and demographic indicators by extortion actors. [More info](https://www.bleepingcomputer.com/news/security/veradigm-discloses-patient-data-breach-after-gentlemen-gang-claims-attack/)

## ⚖️ Law Enforcement & Defense

- **US Authorities Disrupt "Xinbi Guarantee" Escrow Scam Network**: The US Department of Justice seized server infrastructure, web domains, and cryptocurrency assets belonging to Xinbi Guarantee, an illicit escrow platform that laundered hundreds of millions from ransomware and BEC scams. [More info](https://thehackernews.com/2026/09/us-disrupts-xinbi-guarantee-scam.html)

## 📚 Others

- **Zscaler Launches Agentic SOC Solution**: Zscaler introduced an autonomous SOC solution leveraging dynamic AI agents to automate threat triage, context enrichment, and incident containment across enterprise telemetry. [More info](https://www.helpnetsecurity.com/2026/09/09/zscaler-agentic-soc-solution/)

- **Securin Updates Exposure Management Platform**: Securin released an updated attack surface monitoring platform combining vulnerability management, asset inventory tracking, and real-time threat intelligence. [More info](https://www.helpnetsecurity.com/2026/09/09/securin-exposure-management-platform/)

- **Microsoft Unveils Age Awareness APIs for Developers**: Microsoft introduced privacy-preserving APIs that analyze account telemetry to indicate whether users are children, teens, or adults to aid global child safety compliance. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-adds-age-awareness-apis-that-can-tell-if-users-are-children-teens-or-adults/)

---

[⬅ Back to Archive](https://pranakn.github.io)
