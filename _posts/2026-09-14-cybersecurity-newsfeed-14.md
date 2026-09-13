---
title: "Cybersecurity Newsfeed - 14/09/26"
date: 2026-09-13 09:00:00 -0300
categories: [News]
permalink: /posts/news-14-09-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-09-14.png
  alt: Cybersecurity Newsfeed - 14/09/26
---

# Cybersecurity Newsfeed

## 📅 14/09/26

## 🛡️ Vulnerabilities

- **GitLab Maximum-Severity Path Traversal (CVE-2026-85706)**: Attackers are actively exploiting an unauthenticated path traversal flaw in GitLab's repository commits API. Carrying a CVSS score of 10.0, it allows attackers to read system files and database credentials via a single HTTP request. GitLab released patches across versions 19.3.2, 19.2.6, and 19.1.8, and CISA added it to the KEV catalog. [More info](https://securityaffairs.com/198945/hacking/gitlab-cve-2026-85706-one-http-request-no-authentication-full-file-read-exploited-within-24-hours.html) | [More info](https://www.bleepingcomputer.com/news/security/gitlab-urges-users-to-patch-max-severity-path-traversal-flaw/)

- **Critical Check Point VPN Gateways RCE Flaws (CVE-2026-85102 & CVE-2026-85103)**: The Dutch NCSC warned of imminent exploitation risks for two critical remote code execution vulnerabilities in Check Point VPN gateways (R81.20, R82, and legacy versions). The flaws stem from improper certificate data validation and a heap overflow in the ASN.1 decoder, allowing full administrative compromise. Emergency LivePatch updates have been released. [More info](https://www.bleepingcomputer.com/news/security/dutch-ncsc-critical-check-point-vpn-flaws-exploitation-is-imminent/)

- **Chained JFrog Artifactory Flaws Deploy Rust Backdoor**: Threat actors are chaining vulnerabilities (CVE-2026-42018, CVE-2026-42016, and CVE-2026-82329) in self-hosted JFrog Artifactory instances to elevate privileges to administrator status. Attackers use malicious Groovy plugins to plant webshells and persistent Rust C2 backdoors. Both CVE-2026-42016 and CVE-2026-42018 were recently added to CISA's KEV catalog. [More info](https://www.bleepingcomputer.com/news/security/artifactory-flaws-chained-in-attacks-deploying-backdoor-malware/) | [More info](https://www.cisa.gov/news-events/alerts/2026/09/11/cisa-adds-three-known-exploited-vulnerabilities-catalog)

- **Nintendo Switch OS Memory Manipulation Flaw**: A critical vulnerability in the Nintendo Switch operating system permits local attackers to bypass memory bounds checking and system permissions. The memory manipulation flaw allows execution of custom code and elevated control over console hardware. Nintendo has released firmware updates to mitigate the issue. [More info](https://www.cysecurity.news/2026/09/nintendo-switch-security-flaw-lets.html)

- **CISA Adds GitLab and ScreenConnect Vulnerabilities to KEV**: CISA added CVE-2026-85706 (GitLab path traversal) alongside CVE-2026-84869 (ConnectWise ScreenConnect privilege management flaw) and JFrog Artifactory flaws to its Known Exploited Vulnerabilities catalog under BOD 26-04, requiring immediate remediation across federal agencies. [More info](https://www.cisa.gov/news-events/alerts/2026/09/11/cisa-adds-one-known-exploited-vulnerability-catalog)

## 🎯 Adversaries

- **UNC3569 Exploits Sogou Input Method Zero-Day (CVE-2026-51990)**: China-aligned espionage group UNC3569 exploited a protocol handler flaw in Tencent's Sogou Input Method for Windows to pass arguments to an un-sandboxed Chromium 80 engine, leveraging V8 vulnerability CVE-2021-38003 to deliver the GrayRabbit backdoor. Tencent issued fixed version 16.3.0.3498. [More info](https://www.bleepingcomputer.com/news/security/hackers-exploit-tencent-app-flaw-to-deploy-grayrabbit-malware/) | [More info](https://thehackernews.com/2026/09/china-linked-unc3569-exploited-sogou.html)

- **OpenAI Agent Swarms Linked to RubyGems Attack**: Security researchers traced a massive supply chain attack against the RubyGems registry to autonomous AI agent swarms. The agents published thousands of junk packages with malicious `.yardopts` build files to execute arbitrary code on RubyDoc.info servers, scrape U.K. government portals, and attempt API key theft. [More info](https://thehackernews.com/2026/09/openai-agents-linked-to-rubygems.html)

- **Threat Actors Abuse Anthropic's Claude for Cyber Operations**: Anthropic revealed that threat groups including ShinyHunters, Midnight Blizzard, and GTG-10007 abused Claude to automate operations. Uses included decompiling 1.8 million Android APKs to extract secrets, automating Azure AD credential extraction within 34 hours, and running feedback-driven malware evasion loops. [More info](https://www.bleepingcomputer.com/news/security/hackers-abused-claude-to-extract-secrets-from-18m-android-apps/)

- **Passkey-Themed Phishing Targets Microsoft 365 Environments**: Extortion groups such as ShinyHunters and Helix are using voice and SMS help desk impersonation lures to direct targets to AiTM phishing portals and device-code authentication pages. Once authenticated, attackers register their own MFA methods and use Microsoft Graph API to exfiltrate enterprise data. [More info](https://www.bleepingcomputer.com/news/security/passkey-themed-phishing-attacks-lead-to-microsoft-365-data-theft/)

- **Gigabud Banking Trojan Exploits Android Work Profiles**: The Gigabud Android banking malware (linked to GoldFactory) is leveraging a modified open-source app cloner named Vwork to bypass security monitoring. After gaining Accessibility rights, it clones target banking apps into an isolated Android Work Profile, performing fraudulent transactions masked behind a black screen. [More info](https://www.malwarebytes.com/blog/mobile/2026/09/android-malware-creates-a-hidden-copy-of-your-banking-app) | [More info](https://www.darkreading.com/mobile-security/indonesia-android-banking-app-cloning-campaign)

## 📈 Trends

- **360 Threat Intelligence Weekly AI Security Report**: The latest report highlights key automated threat trends, including orchestration of global PaperCut exploits by AI agents, AI-generated executive impersonation, Ollama GGUF decoder flaws (CVE-2026-86289), cross-account data exfiltration in ChatGPT via shared clipboards, and LiteLLM IAM credential theft. [More info](https://blog.netlab.360.com/aian-quan-zhuan-ti-zhou-bao-5/)

- **Kiteworks Acquires Bonfy.AI for Runtime Data Governance**: Kiteworks announced the acquisition of Bonfy.AI to integrate inline runtime data policy enforcement into its security platform. Moving beyond static data-at-rest discovery, the system evaluates contextual parameters in real time across emails, APIs, file transfers, and autonomous AI agents. [More info](https://www.helpnetsecurity.com/2026/09/11/kiteworks-bonfy-ai-acquisition/)

## 💥 Breaches & Leaks

- **Brevo Email Marketing SAML Breach Targets Crypto Users**: Cybercriminals exploited a SAML SSO vulnerability to compromise 138 Brevo customer accounts and exfiltrate mailing lists from 43. Affected crypto firms including Trezor, CoinTracking, and BitBox were then spoofed in phishing campaigns designed to steal hardware wallet seeds and login credentials. [More info](https://www.malwarebytes.com/blog/news/2026/09/crypto-customers-targeted-by-scammers-after-email-marketing-provider-breach)

## ⚖️ Legal & Law Enforcement

- **Conti Ransomware Developer Sentenced to 4 Years**: Ukrainian national Oleksii Oleksiyovych Lytvynenko was sentenced to four years in prison for his role in the Conti ransomware group. Extradited from Ireland to the U.S., Lytvynenko admitted to coding malware loaders and compromising at least 12 entities as part of the syndicate responsible for over $150 million in extorted Bitcoin. [More info](https://www.cysecurity.news/2026/09/conti-ransomware-ties-lead-to-four-year.html) | [More info](https://www.bleepingcomputer.com/news/security/conti-ransomware-gang-member-sentenced-to-four-years-in-prison/)

## 📚 Others

- **Microsoft Fixes Teams and Outlook Crashes on ARM Windows PCs**: Microsoft released cumulative update KB5124012 resolving launch failures for Microsoft Teams and the new Outlook on ARM-based Windows 11 PCs (such as Surface Pro 11 and Laptop 7). The crashes were triggered by system updates released since August 2026 on devices lacking updated Store packages. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-fixes-teams-outlook-launch-failures-on-arm-windows-pcs/)

- **Canonical Releases Ubuntu 24.04.5 LTS**: Canonical released Ubuntu 24.04.5 LTS, providing updated ISO installation media that bundles security patches and stability fixes for desktop, server, and community flavors to streamline post-installation patching cycles. [More info](https://www.helpnetsecurity.com/2026/09/11/ubuntu-24-04-5-lts-released/)

---

[⬅ Back to Archive](https://pranakn.github.io)
