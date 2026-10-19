---
title: "Cybersecurity Newsfeed - 20/10/26"
date: 2026-10-19 09:00:00 -0300
categories: [News]
permalink: /posts/news-20-10-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-10-20.png
  alt: Cybersecurity Newsfeed - 20/10/26
---

# Cybersecurity Newsfeed

## 📅 20/10/26

## 🛡️ Vulnerabilities

- **Plex2Shell Vulnerabilities Exploited in the Wild**: Threat actors are actively exploiting a chain of four Plex Media Server vulnerabilities (CVE-2026-96652, CVE-2026-96654, CVE-2026-96655, and CVE-2026-96656) known as Plex2Shell. The flaw chain combines unauthenticated SSRF, token leakage, and path traversal to execute remote code, with public PoCs driving immediate exploitation to deploy crypto miners and proxy backdoors. [More info](https://thehackernews.com/2026/10/hackers-exploit-plex2shell-flaws-to.html) | [More info](https://www.securityweek.com/plex2shell-exploit-chain-weaponized-against-plex-servers-hours-after-disclosure/)

- **Critical Drupal Core RCE Patch Released**: Drupal released emergency security updates addressing five vulnerabilities, highlighted by two critical RCE flaws (CVE-2026-108099 and CVE-2026-108097) in the Entity List and Field UI modules. Administrators are urged to update core installations to versions 11.4.10, 11.3.19, or 10.6.19 due to rapid exploitation risks. [More info](https://www.securityweek.com/drupal-warns-of-fast-exploitation-risk-for-critical-core-rce-flaw/)

- **Out-of-Band Patches for Critical NGINX RCEs**: F5 issued out-of-band updates to address three critical heap-based buffer overflow and use-after-free defects in NGINX Open Source and NGINX Plus (CVE-2026-15176, CVE-2026-97205, and CVE-2026-93479). The flaws enable unauthenticated remote code execution via crafted HTTP requests under specific configurations. [More info](https://www.bleepingcomputer.com/news/security/f5-releases-out-of-band-patches-for-critical-nginx-vulnerabilities/) | [More info](https://securityaffairs.com/201106/security/f5-addressed-critical-rce-flaws-in-nginx/)

- **SiteGuard WAF Command Injection Flaw Exploited**: CVE-2026-106931, a critical command injection vulnerability in SiteGuard Server Edition's statistics feature, is under active exploitation. The default-enabled flaw allows low-privilege local attackers to elevate privileges to root or SYSTEM. [More info](https://securityaffairs.com/201258/security/japans-siteguard-waf-flaw-cve-2026-106931-is-already-being-exploited.html)

- **Critical Linux KVM Guest-to-Host Escape**: Security analysts identified a critical vulnerability in Linux KVM virtualization that allows guest virtual machines to break isolation boundaries and execute arbitrary code on the underlying host hypervisor, posing significant risks for multi-tenant cloud environments. [More info](https://www.theregister.com/virtualization/2026/10/19/linux-kvm-guest-host-escape-rated-critical-may-represent-a-new-way-to-attack-penguin-powered-networking/5303744)

- **CISA Adds Critical Atlassian Flaw to KEV**: CISA added CVE-2026-21589, a CVSS 9.3 arbitrary file access/path traversal flaw affecting Atlassian Bitbucket, Confluence, Jira, and Crowd, to its Known Exploited Vulnerabilities catalog following confirmed exploitation in the wild. [More info](https://securityaffairs.com/201086/hacking/u-s-cisa-adds-atlassian-flaw-to-its-known-exploited-vulnerabilities-catalog.html)

## 🎯 Adversaries

- **Rank Math SEO WordPress Supply Chain Compromise**: WordPress SEO plugin Rank Math PRO suffered a supply chain attack that injected backdoors into active website installations. Attackers manipulated plugin update packages to drop self-rebuilding PHP backdoors and grant unauthorized administrative control. [More info](https://www.bleepingcomputer.com/news/security/wordpress-seo-plugin-rank-math-compromised-to-backdoor-websites/)

- **Hackers Hijack AOMEI Update Infrastructure**: Threat actor UNC7017 compromised AOMEI update servers between April and July 2026. By tampering with update configuration files during brief windows, the attackers distributed the CROSSROAD downloader and SHINYROAD backdoor to Backupper users. [More info](https://www.bleepingcomputer.com/news/security/hackers-hijack-aomei-update-servers-to-secretly-spread-malware/)

- **GhostAction Campaign Targets Open-Source Devs**: The threat actor behind GhostAction updated its tactics, utilizing malicious GitHub OAuth phishing pages and credential-stealing font files in public repositories to harvest AWS, PyPI, npm, and AI provider tokens. [More info](https://thehackernews.com/2026/10/ghostaction-attackers-plant-credential.html)

- **CikaBika Bot Weaponizes Discord & Ngrok**: Darktrace uncovered a novel Rust-based remote access trojan named CikaBika Bot operated entirely via Discord channels and Ngrok tunnels, deployed via ISO lures, Nim loaders, and UAC bypasses. [More info](https://securityaffairs.com/201210/security/rust-based-cikabika-bot-turns-discord-into-a-command-center/)

## 📈 Trends

- **Underground Market Expansion for Fake KYC Services**: Threat intelligence reveals a surge in underground cybercrime services offering fake identity documentation, deepfakes, and automated camera-feed bypass tools to defeat biometric KYC checks at crypto exchanges and financial institutions. [More info](https://www.bleepingcomputer.com/news/security/inside-the-underground-market-for-know-your-client-services/)

- **Surge in Stolen AI API Keys & Autonomous Scanners**: Threat actors are increasingly trading stolen OpenAI, Anthropic, and Google API keys on dark web markets to fund automated vulnerability scanners like MONST3R-AI, leading to a 67% rise in AI-related dark web activity. [More info](https://www.helpnetsecurity.com/2026/10/16/stolen-ai-api-keys-autonomous-scans/)

- **Global DDoS Attacks Rise 24% Year-Over-Year**: Netscout's DDoS Threat Intelligence Report documented over 9.1 million DDoS incidents in H1 2026, driven by high-rate assault methods and residential proxy botnets that exhaust firewall state tables before network bandwidth limits. [More info](https://www.helpnetsecurity.com/2026/10/16/netscout-ddos-attack-growth-report/)

## 💥 Breaches & Leaks

- **Bullhorn Takes Recruitment Platform Offline After Attack**: Staffing software vendor Bullhorn shut down its cloud recruitment platform following a cyberattack that disrupted applicant tracking, onboarding, and billing. The company mandated password and API credential rotations while conducting a forensic investigation alongside CrowdStrike. [More info](https://www.bleepingcomputer.com/news/security/bullhorn-takes-staffing-platform-offline-to-contain-cyberattack/)

- **OpenCode Breach Exposes User API Keys**: OpenCode suffered a breach during large-scale AI distillation attacks, exposing stored API keys for 1.4% of its Console users and causing high unexpected billing charges across external AI providers. [More info](https://www.bleepingcomputer.com/news/security/opencode-hack-exposes-api-keys-amid-ai-distillation-attacks/)

## 📚 Others

- **Microsoft Resolves AC-3 Audio Game Crash Bug**: Microsoft released Patch Tuesday update KB5127648 to fix a known issue introduced in optional preview KB5124010, which caused crashes in Windows 11 games and applications using legacy AC-3 audio decoding. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-fixes-game-app-crashes-caused-by-windows-kb5124010-preview-update/)

- **Fastfetch 2.70.0 Release**: Utility tool Fastfetch released version 2.70.0, switching scripting support from QuickJS to Lua, updating command error capture parameters, and altering formatting for Disk, Shell, and Android sensor modules. [More info](https://www.helpnetsecurity.com/2026/10/16/fastfetch-2-70-0-released/)

---

[⬅ Back to Archive](https://pranakn.github.io)
