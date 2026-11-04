---
title: "Cybersecurity Newsfeed - 05/11/26"
date: 2026-11-04 09:00:00 -0300
categories: [News]
permalink: /posts/news-05-11-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-11-05.png
  alt: Cybersecurity Newsfeed - 05/11/26
---

# Cybersecurity Newsfeed

## 📅 05/11/26

## 🛡️ Vulnerabilities

- **Debian and Ubuntu APT Flaw (CVE-2026-109518)**: A critical vulnerability in the APT package manager allows adversary-in-the-middle attackers to swap verified packages with malicious alternatives during failed download retries, leading to arbitrary code execution with root privileges upon installation. System administrators are advised to apply patches immediately. [More info](https://thehackernews.com/2026/11/debian-and-ubuntu-apt-flaw-lets-mitm.html)

- **Unpatched SonicWall GMS Flaws (CVE-2026-109593 & CVE-2026-109594)**: SonicWall has warned of two unpatched security vulnerabilities in end-of-life Global Management System versions 9.5.2 and earlier. The flaws consist of an unauthenticated arbitrary file read (CVSS 9.1) and a post-authentication SQL injection (CVSS 6.8). No patches will be released due to EOL status; migration to Network Security Manager is urged. [More info](https://thehackernews.com/2026/11/sonicwall-wont-patch-eol-gms-flaws-that.html) | [More info](https://www.bleepingcomputer.com/news/security/sonicwall-warns-of-unpatched-flaws-in-end-of-life-gms-software/)

- **Google Chrome 157 Addresses 213 Flaws**: Google released Chrome 157 to the stable channel across Windows, macOS, and Linux, fixing 213 distinct security issues. The update resolves seven critical-severity vulnerabilities involving memory corruption and remote code execution within the browser engine. [More info](https://www.malwarebytes.com/blog/bugs/2026/11/chrome-157-fixes-213-security-issues-including-7-critical-flaws)

- **Critical Ruby on Rails Active Storage Flaw (GHSA-f3w6-w445-fwh9)**: A severe vulnerability (CVSS 9.8) in Ruby on Rails Active Storage permits unauthenticated attackers to perform arbitrary file writes when processing image uploads via ImageMagick. Attackers can leverage the flaw to extract secret keys and execute remote code. Patched in versions 8.1.4.1 and 8.0.5.2. [More info](https://thehackernews.com/2026/11/critical-rails-flaw-lets-attackers.html)

- **Xen Hypervisor Cross-VM Memory Access (CVE-2026-102703 & CVE-2026-102704)**: Advisory XSA-523 identifies permission caching bugs in Xen versions 4.6 and later that allow a malicious guest virtual machine to read and write memory belonging to other VMs and the dom0 host environment. Emergency patches have been released by platform vendors. [More info](https://thehackernews.com/2026/11/xen-hypervisor-flaws-let-one-malicious.html)

- **CISA Flags WordPress Core RCE in KEV Catalog (CVE-2026-119977)**: A TOCTOU race condition during full-package core upgrades allows unauthenticated remote attackers to execute code via predictable staging paths. CISA added the bug to its KEV catalog, mandating federal patching by November 7, 2026, while private admins are urged to update to WordPress 7.1.4. [More info](https://www.bleepingcomputer.com/news/security/cisa-flags-wordpress-rce-flaw-as-actively-exploited-in-attacks/)

- **Zero-Click Android Remote Code Execution (CVE-2026-58868)**: Google's November 2026 Android security bulletin patches a critical heap buffer overflow in `FrameDecoder.cpp` affecting Android 14 through 17. The vulnerability enables remote code execution without user interaction. Over 200 security flaws were addressed across system and vendor components. [More info](https://securityaffairs.com/202414/mobile-2/cve-2026-58868-critical-android-bug-could-let-attackers-run-remote-code.html) | [More info](https://thehackernews.com/2026/11/google-patches-critical-android-flaw.html)

## 🎯 Adversaries

- **Cyberattacks Target European Refrigeration Infrastructure & Blood Banks**: Malicious cyber operations disrupted refrigeration control systems at three regional French blood banks and commercial supermarkets across Sweden, Belgium, Luxembourg, Estonia, and the UK. While staff manually preserved blood stocks in France, unauthorized parameter alterations forced European retailers to discard large quantities of spoiled food products. [More info](https://securityaffairs.com/202431/hacking/cyberattack-hits-french-blood-banks-as-hackers-target-refrigeration-systems-across-europe.html) | [More info](https://hackread.com/hackers-alter-refrigeration-settings-european-discard-food/)

- **Goddess of Victory: NIKKE PC Launcher Supply-Chain Attack**: Threat actors tampered with CDN-hosted JavaScript files retrieved by the RPG launcher, deploying a secondary LuaJIT payload that drops the K2F backdoor along with a data-stealing Windows DLL designed to harvest browser credentials and crypto wallets. [More info](https://www.bleepingcomputer.com/news/security/nikke-pc-game-launcher-hacked-to-spread-remote-access-data-stealing-malware/)

- **APT29 Mobile Watering Hole Campaign**: APT29 (Midnight Blizzard) is conducting watering hole attacks exploiting mobile operating systems via lookalike domains and a supply-chain compromise of the Plerdy web analytics framework. The operation deploys n-day exploit chains like DarkSword to siphon session cookies, messages, contacts, and telemetry from iOS and Android devices. [More info](https://www.helpnetsecurity.com/2026/11/04/apt29-watering-hole-mobile-devices-n-day-exploits/) | [More info](https://thehackernews.com/2026/11/apt29-linked-hackers-hijack-web.html)

- **Operation CloudFire Targets Google Workspace Sessions**: A persistent phishing campaign relies on Google Calendar invites and reverse proxy infrastructure with Cloudflare Turnstile challenges to dynamically render sign-in pages, effectively harvesting live Google Workspace session tokens and bypassing traditional MFA controls. [More info](https://www.bleepingcomputer.com/news/security/google-calendar-phishing-campaign-hijacks-sessions-bypasses-mfa/)

## 📈 Trends

- **Fake $750 Apple Cash Reward Scam**: Security researchers highlight a widespread scam promising a $750 Apple Cash payout under the guise of device verification. Landing pages redirect victims through affiliate tracking networks to download unwanted software, providing zero financial return. [More info](https://www.malwarebytes.com/blog/scams/2026/11/the-fake-750-apple-cash-reward-that-pays-out-nothing)

## 💥 Breaches & Leaks

- **DreamHost File Manager Breach**: DreamHost disclosed that an unauthorized third party exploited a vulnerability in its web-based File Manager platform (`files.dreamhost.com`) between August and October 23, 2026. The compromise exposed FTP/SFTP credentials and webmail session data. Patches and session invalidations have been applied. [More info](https://www.bleepingcomputer.com/news/security/dreamhost-confirms-data-breach-exposed-ftp-logins-and-webmail-sessions/)

- **WorkOS Intrusion via ARTEX AI Framework**: Developer platform WorkOS suffered a breach of an internal sales application, exposing business contact info and conversation notes. Threat actors utilized the ARTEX AI offensive security framework to automate reconnaissance and exploitation tasks during the incident. [More info](https://www.bleepingcomputer.com/news/security/workos-says-attacker-used-artex-ai-to-breach-internal-sales-app/)

## 🛠️ Tools & Utilities

- **Ghostunnel Open-Source TLS Proxy Release**: Ghostunnel provides mutual authentication for legacy applications unable to support native encryption. Built as a static Go binary with Landlock sandboxing and SPIFFE ID validation, it enables secure mTLS encapsulation without application code changes. [More info](https://www.helpnetsecurity.com/2026/11/04/ghostunnel-open-source-tls-proxy/)

---

[⬅ Back to Archive](https://pranakn.github.io)
