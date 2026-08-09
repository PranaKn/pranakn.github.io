---
title: "Cybersecurity Newsfeed - 10/08/26"
date: 2026-08-09 09:00:00 -0300
categories: [News]
permalink: /posts/news-10-08-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-08-10.png
  alt: Cybersecurity Newsfeed - 10/08/26
---

# Cybersecurity Newsfeed

## 📅 10/08/26

## 🛡️ Vulnerabilities

- **Metabase Zero-Day SQL Injection (CVSS 10.0)**: Metabase issued an urgent warning regarding an unauthenticated zero-day SQL injection vulnerability affecting versions 1.58+ under active exploitation. Attackers can grant themselves admin access, alter configurations, and steal stored credentials. Administrators are advised to apply patches immediately or temporarily block the `/api/session/reset_password` endpoint. [More info](https://thehackernews.com/2026/08/metabase-zero-day-exploited-in-wild.html)

- **Atlassian Rovo AI Prompt Injection & Data Exfiltration**: Security researchers demonstrated that Atlassian's Rovo AI assistant can be tricked into leaking sensitive Jira and Confluence data. Exploiting indirect prompt injections via uploaded files or parameter flaws ("RovoBlast") allows attackers to append internal data to external URLs. Atlassian patched the RovoBlast link flaw on July 8. [More info](https://thehackernews.com/2026/08/atlassian-rovo-can-be-tricked-into.html) | [More info](https://www.cysecurity.news/2026/08/atlassian-rovo-ai-can-be-abused-to.html)

- **Progress Kemp LoadMaster Command Injection (CVE-2026-8037)**: CISA added CVE-2026-8037 (CVSS 9.6) to its KEV catalog following almost 800 global exploitation attempts. The bug stems from unsanitized input in `escape_quotes()`, allowing unauthenticated attackers to execute arbitrary system commands. Federal agencies must patch by August 10, 2026. [More info](https://thehackernews.com/2026/08/progress-kemp-loadmaster-flaw-hits-cisa.html) | [More info](https://www.cisa.gov/news-events/alerts/2026/08/07/cisa-adds-one-known-exploited-vulnerability-catalog)

- **N-able N-central Authentication Bypass (CVE-2026-18577)**: N-able released Hotfix 2 for N-central following active exploitation of CVE-2026-18577 (CVSS 8.2), caused by an incomplete fix for CVE-2026-18556. Attackers are exploiting the flaw to gain administrative access, use Take Control capabilities, and deploy persistent Cloudflare Tunnels. [More info](https://thehackernews.com/2026/08/n-central-attackers-reach-managed.html)

- **WordPress "XSS2Shell" Remote Code Execution Chain**: Researchers disclosed an RCE chain in WordPress that escalates a login page formatting flaw via DOM clobbering and `wp_kses_post` bypasses. Unauthenticated attackers can manipulate admin sessions to generate REST API Application Passwords and upload malicious plugins. The flaw was resolved in version 7.0.3. [More info](https://securityaffairs.com/196820/hacking/wordpress-xss2shell-flaw-turns-simple-login-bug-into-full-server-takeover.html)

- **Critical Flaws in AI Coding Harnesses (Gemini CLI & Claude Code)**: Researchers identified severe vulnerabilities in AI coding tools, including OS command injection via `.env` files in Google's Gemini CLI (CVE-2026-12537) and API key exfiltration in Anthropic's Claude Code (CVE-2026-54316). Patches have been issued by both vendors. [More info](https://thehackernews.com/2026/08/claude-code-and-gemini-cli-flaws-let.html)

- **"NatJack" Attacks Hijack Active TCP Sessions**: A newly disclosed vulnerability class exploits state-tracking logic in Windows NAT (CVE-2026-56181) and Linux Netfilter conntrack (CVE-2026-63913). Attackers can hijack active TCP connections, spoof DNS responses, and exhaust NAT tables across adjacent workloads. [More info](https://thehackernews.com/2026/08/new-natjack-attacks-hijack-tcp-sessions.html)

- **Novel CSS Attacks Bypass Webmail Isolation**: Black Hat USA 2026 research revealed CSS sanitization bypasses affecting major providers like Outlook, Gmail, Yahoo, Proton Mail, and Fastmail. Attackers can spoof login interfaces, exfiltrate OAuth tokens, and perform prompt injections against connected AI tools. [More info](https://thehackernews.com/2026/08/new-css-attacks-can-break-webmail.html)

## 🎯 Adversaries

- **UNC6671 Vishing Campaigns Target Major Financial Firms**: Threat group UNC6671 impersonated IT support in phone calls to target over 200 high-profile firms, including Blackstone, Apollo, and KKR. Using AitM phishing portals, they captured credentials and live MFA tokens to steal Microsoft 365 and Okta data, demanding millions in ransom under brands like Redact and Pink. [More info](https://thehackernews.com/2026/08/unc6671-vishing-attacks-target-personal.html) | [More info](https://securityaffairs.com/196800/security/hackers-impersonate-it-support-to-breach-leading-financial-companies.html)

- **Head Mare Trojanizes TrueConf Server Installers**: Hacktivist group Head Mare exploited unauthenticated flaws (KLCERT-26-057 and KLCERT-26-058) in unpatched TrueConf conferencing servers to distribute PhantomCore and PhantomGraph backdoors. Users downloading updates from compromised servers inadvertently infected their systems. [More info](https://www.bleepingcomputer.com/news/security/hackers-breach-trueconf-to-trojanize-client-installers-with-backdoors/)

- **TeamPCP Deploys "Kamikaze" Wiper in Infrastructure Attacks**: Oligo Security linked threat actor TeamPCP to software supply chain attacks (Operation PCPcat and ShadowRay 2.0). The group poisoned open-source libraries via GitHub Actions and introduced "kube.py," containing a "Kamikaze" wiper aimed at destroying Kubernetes nodes. [More info](https://thehackernews.com/2026/08/teampcp-linked-to-redis-attacks-dating.html)

- **ClickFix Social Engineering Pushes macOS Infostealer**: A Go-based macOS infostealer is being distributed via ClickFix prompts that trick users into running Terminal commands. Operating under a fake `trustd` process name, the malware harvests Keychain data and includes dynamic cryptocurrency draining routines. [More info](https://www.bleepingcomputer.com/news/security/clickfix-attack-pushes-macos-infostealer-for-crypto-theft-attacks/)

- **Google Ads Malvertising Spreads Crypto Info-Stealers**: An active malvertising campaign uses malicious Google Ads and fake crypto exchange/wallet sites to deliver trojanized installers. The dropped malware harvests browser credentials, private keys, and session cookies from victims. [More info](https://www.cysecurity.news/2026/08/malvertising-campaign-uses-fake-crypto.html)

## 📈 Trends

- **ChainDrop npm Worm Infects Over 400 Packages**: Unit 42 analyzed "ChainDrop," a self-propagating npm worm triggered via preinstall hooks. It exfiltrates cloud credentials and GitHub OIDC tokens while maintaining persistence across VS Code and Claude Code configurations. [More info](https://unit42.paloaltonetworks.com/chaindrop-npm-worm-analysis/)

- **Dual Attack Chains Deploy GepyS Malware and Crypto Hijackers**: Gen Threat Labs highlighted two H1 2026 attack vectors: one using compromised corporate emails to deliver GepyS banking malware, and another leveraging Rust-based clipboard hijackers that resolve C2 endpoints through Binance Smart Chain smart contracts via EtherHiding. [More info](https://www.bleepingcomputer.com/news/security/real-emails-hijacked-payments-two-h1-2026-attack-chains/)

## 💥 Breaches & Leaks

- **Framework, Tally, and LexisNexis Breach via Metabase Zero-Day**: Laptop maker Framework, form platform Tally, and LexisNexis confirmed data breaches resulting from the exploitation of the critical Metabase SQL injection zero-day (CVSS 10.0). Stolen data includes names, email addresses, billing addresses, and hashed passwords. [More info](https://www.bleepingcomputer.com/news/security/framework-tally-disclose-metabase-data-theft-attacks/)

- **Levi Strauss & Co. Discloses Social Engineering Data Theft**: In an SEC filing, Levi Strauss & Co. reported that attackers social-engineered three employees to gain unauthorized access to corporate systems and exfiltrate data. Containment was executed quickly, preventing customer data impact or operational downtime. [More info](https://www.bleepingcomputer.com/news/security/levi-strauss-and-co-says-hackers-stole-corporate-data-in-cyberattack/)

- **South Korean Military Medical System Targeted**: South Korean authorities investigated an intrusion targeting network infrastructure within the military medical command. Unauthorized access attempts were detected and contained before military personnel healthcare data could be exfiltrated. [More info](https://www.cysecurity.news/2026/08/south-korean-military-medical-system.html)

## 📚 Others

- **ShieldFont Web Font Blocks AI Scraping**: Developers launched ShieldFont, a security-oriented web font designed to defeat automated AI web scrapers. By displaying clean text to users while placing decoy content inside raw HTML, it corrupts automated model training datasets. [More info](https://www.helpnetsecurity.com/2026/08/07/shieldfont-ai-scraping-protection/)

---

[⬅ Back to Archive](https://pranakn.github.io)
