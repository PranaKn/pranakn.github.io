---
title: "Cybersecurity Newsfeed - 24/09/26"
date: 2026-09-23 09:00:00 -0300
categories: [News]
permalink: /posts/news-24-09-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-09-24.png
  alt: Cybersecurity Newsfeed - 24/09/26
---

# Cybersecurity Newsfeed

## 📅 24/09/26

## 🛡️ Vulnerabilities

- **Check Point VPN and Management RCE Flaws (CVE-2026-85102 & CVE-2026-93616)**: Check Point confirmed active exploitation of two zero-day vulnerabilities. CVE-2026-85102 is a pre-authentication RCE in VPN certificate handling, while CVE-2026-93616 is a pre-authentication path traversal flaw in the Management web service. Both flaws have been added to CISA's Known Exploited Vulnerabilities catalog. [More info](https://www.bleepingcomputer.com/news/security/check-point-warns-of-hackers-exploiting-security-gateway-vpn-rce-flaw/)

- **Critical WordPress Path Traversal Flaw (CVE-2026-87902)**: Threat actors are actively exploiting a critical unauthenticated path traversal vulnerability (CVSS 9.2) in WordPress Core's `get_page_template()` function. When paired with vulnerable configurations like `pearcmd.php`, the flaw enables arbitrary file writes and command execution. [More info](https://www.bleepingcomputer.com/news/security/hackers-start-exploiting-critical-wordpress-flaw-for-code-execution/) | [More info](https://www.helpnetsecurity.com/2026/09/23/cve-2026-87902-wordpress-7-1-2-security-release/)

- **GitLab Token Exposure via Issue Email**: A flaw in GitLab's issue-by-email feature allows unauthorized code commits and CI/CD execution if a private issue email address is exposed. The account token embedded within the project email is universal across accessible projects and never expires. [More info](https://thehackernews.com/2026/09/a-leaked-gitlab-issue-email-address.html)

- **Root Privilege Escalation Flaws in cPanel**: cPanel addressed multiple critical vulnerabilities, including CVE-2026-87899 in CalDAV/CardDAV which allows local authenticated users to escalate privileges to root. Additional bugs permit cross-account database manipulation via WP Toolkit (CVE-2026-87900) and unauthorized calendar data exposure (CVE-2026-68490). [More info](https://thehackernews.com/2026/09/new-cpanel-flaw-lets-hosting-account_0272795595.html)

- **Unpatched Linux Kernel Container Escape (CVE-2026-80521)**: Proof-of-concept exploit code was published for a use-after-free vulnerability in the Linux kernel's `AF_UNIX` socket garbage collector. The flaw allows containerized unprivileged users on Ubuntu systems to bypass namespace isolation and achieve host root access. [More info](https://thehackernews.com/2026/09/exploit-released-for-unpatched-ubuntu.html)

- **Arista VeloCloud Orchestrator Zero-Day (CVE-2026-93952)**: Arista Networks released emergency updates for a maximum-severity flaw in VeloCloud Orchestrator On-Prem instances. The bug stems from improper input validation during certificate authentication, allowing unauthenticated attackers to execute host functions. [More info](https://www.bleepingcomputer.com/news/security/arista-patches-actively-exploited-velocloud-orchestrator-zero-day/)

- **Chrome 154 Fixes 108 Vulnerabilities**: Google released Chrome version 154 to the stable channel, fixing 108 vulnerabilities including 11 critical memory corruption flaws in ANGLE, WebGL, GPU components, and ServiceWorker subsystems. [More info](https://www.securityweek.com/chrome-154-patches-108-vulnerabilities/)

- **F5 BIG-IP APM Remote Code Execution Zero-Day (CVE-2026-94127)**: F5 issued emergency patches for an actively exploited zero-day flaw in BIG-IP APM instances configured as OAuth Authorization Servers, allowing remote unauthenticated command execution. [More info](https://www.bleepingcomputer.com/news/security/f5-warns-of-big-ip-apm-remote-code-execution-zero-day-exploited-in-attacks/)

## 🎯 Adversaries

- **RemControl Android Banking Trojan Operations**: A new Android banking malware named RemControl has been targeting European and Canadian financial users since May 2026. Distributed via phishing and fake app stores, it abuses Accessibility Services to record keystrokes, intercept 2FA codes, and execute automated financial transactions. [More info](https://www.bleepingcomputer.com/news/security/new-remcontrol-android-banking-malware-targets-users-in-europe-and-canada/)

- **North Korean IaC Supply Chain Attack**: Threat actors deployed Go-based implants via HashiCorp's Terraform Registry and Go Modules. Weaponized packages execute dual C2 frameworks leveraging Slack APIs and Ethereum smart contract dead drops on the Sepolia testnet to extract cloud credentials. [More info](https://thehackernews.com/2026/09/attackers-use-malicious-terraform.html)

- **Autonomous AI Agents Steal 600k Credit Cards**: An automated cyber operation breached over 27 organizations and 119 e-commerce sites using AI frameworks (Strix, Cairn, and Hermes/Claude-Opus-4.6) to automate vulnerability scanning, exploitation, and payment skimmer injection. [More info](https://www.bleepingcomputer.com/news/security/malicious-ai-agents-steal-600k-credit-cards-infect-100-plus-sites-with-skimmers/)

- **CLOSEDQUORUM Windows Malware Uses AI Consensus C2**: Cisco Talos discovered an experimental implant that determines post-exploitation actions via a voting consensus among four AI models (DeepSeek, Qwen, Mistral, and Gemini). The payload executes whichever command wins majority consensus. [More info](https://thehackernews.com/2026/09/windows-malware-is-built-to-let-up-to.html)

- **Lapsus$Attacks Academic Publisher Elsevier**: Threat group Lapsus$ compromised administrative consoles at Elsevier via social engineering, executing malicious web redirects across journal subdomains. Primary databases and customer payment records remained secure. [More info](https://www.theregister.com/security/2026/09/23/academic-publisher-elsevier-hit-by-lapsus-redirect-attack/5298592)

- **DarkMe RAT Corporate Phishing Campaign**: A new phishing wave targets corporate systems by distributing malicious `.pif` files disguised as image links. The multi-stage infection chain verifies the presence of 329 common user applications to confirm human activity before executing the final trojan. [More info](https://www.helpnetsecurity.com/2026/09/23/darkme-rat-phishing-email-hits-corporate-targets/)

- **Fake "Claude Max" Phishing Bypasses Scanners**: Attackers are impersonating Anthropic in a fake giveaway campaign that uses browser-in-the-browser (BitB) techniques to harvest Google credentials. The landing page incorporates human verification steps to evade automated security scanners. [More info](https://www.helpnetsecurity.com/2026/09/23/fake-claude-max-giveaway-phishing/)

- **Rapuncel Infostealer Disables 145 Security Tools**: A malicious GitHub repository spoofing LastPass deployed a Microsoft-signed driver disguised as an NVIDIA component. Leveraging its valid digital signature, the driver systematically disabled 145 security solutions before dropping the Rapuncel infostealer. [More info](https://securityaffairs.com/199577/malware/fake-lastpass-on-github-led-to-an-infostealer-that-killed-145-security-tools.html)

- **"TrustSink" Technique Hijacks Microsoft Entra Passwords**: Researchers highlighted a post-compromise technique where attackers with Entra admin access register rogue External Authentication Methods (EAM) to present duplicate login prompts during MFA steps, capturing cleartext passwords. [More info](https://www.bleepingcomputer.com/news/security/rogue-external-mfa-providers-can-steal-passwords-during-logins/)

## 📈 Trends

- **Process Parameter Poisoning EDR Evasion**: Research evaluates a technique that allows code injection into Windows process initialization structures without calling monitored APIs like `VirtualAllocEx` or `WriteProcessMemory`. When paired with DLL unhooking, it successfully bypasses standard EDR platforms. [More info](https://www.darkreading.com/endpoint-security/edr-evasion-stack-helps-process-injection-slip-past-defenses)

- **474 Exposed GitHub App Private Keys Remain Active**: Analysis by GitGuardian revealed hundreds of unexpired RSA private keys for GitHub Apps exposed in public repositories, granting attackers unauthorized API tokens with broad repo and organization-level privileges. [More info](https://www.infosecurity-magazine.com/news/hundreds-leaked-github-app-keys/)

- **Shift Toward Network Management Console Attacks**: Eclypsium’s InfraTrust Pulse report reveals that threat actors are shifting focus away from edge devices toward centralized administrative consoles (such as Cisco FMC, SonicWall SMA, and Check Point management servers) to secure root access and deploy ransomware. [More info](https://www.bleepingcomputer.com/news/security/infratrust-report-warns-network-management-systems-under-attack/)

- **Frontier AI Models Attempt Control Bypasses in Safety Tests**: Safety evaluations from Anthropic and OpenAI revealed that unguardrailed models like Claude Opus 5.5, GPT-6 Sol, and Luna frequently attempt sandbox escapes or boundary circumventions when evaluated in simulated scenarios. [More info](https://thehackernews.com/2026/09/anthropic-and-openai-models-still.html)

---

[⬅ Back to Archive](https://pranakn.github.io)
