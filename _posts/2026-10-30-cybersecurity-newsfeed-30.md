---
title: "Cybersecurity Newsfeed - 30/10/26"
date: 2026-10-29 09:00:00 -0300
categories: [News]
permalink: /posts/news-30-10-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-10-30.png
  alt: Cybersecurity Newsfeed - 30/10/26
---

# Cybersecurity Newsfeed

## 📅 30/10/26

## 🛡️ Vulnerabilities

- **CISA Adds PHP2Shell Flaws to KEV Catalog (CVE-2026-109618 & CVE-2026-109619)**: Critical PHP core runtime vulnerabilities affecting Apache mod_php and PHP-FPM allow unauthenticated out-of-memory handling and memory reuse exploitation to achieve remote code execution and full server control. Federal civilian agencies must remediate both flaws by October 29, 2026. [More info](https://www.cisa.gov/news-events/alerts/2026/10/29/cisa-adds-two-known-exploited-vulnerabilities-catalog)

- **Critical Linux Kernel TCP Flaw Bypasses KASLR (CVE-2026-98432)**: A 9.8 CVSS race condition in IPv4 TCP connection setups impacts major distributions including Ubuntu, RHEL, and SUSE, enabling remote attackers to trigger a use-after-free condition, bypass KASLR, and execute arbitrary code. Anthropic's Claude AI assisted in discovering and demonstrating the exploit chain. [More info](https://thehackernews.com/2026/10/linux-kernel-tcp-flaw-with-98-cvss.html)

- **Cisco ASA and FTD SSL VPN DoS Zero-Day**: Cisco warned of an actively exploited zero-day vulnerability in Adaptive Security Appliance (ASA) and Threat Defense (FTD) software that allows unauthenticated remote attackers to send crafted requests, crash SSL VPN processes, and force unexpected device reboots. [More info](https://www.bleepingcomputer.com/news/security/cisco-warns-of-firewall-zero-day-exploited-to-crash-ssl-vpn-devices/)

- **CISA Adds VMware ESX and Linux Kernel Flaws to KEV Catalog**: Additions to CISA's KEV catalog include CVE-2026-41709 (VMware ESX insufficient logging) and CVE-2026-46300 (Linux kernel missing variable initialization), with a federal agency remediation deadline set for November 11, 2026. [More info](https://www.cisa.gov/news-events/alerts/2026/10/28/cisa-adds-two-known-exploited-vulnerabilities-catalog)

- **16-Year-Old TianoCore EDK II UEFI Flaw (CVE-2026-97631)**: A CVSS 9.5 buffer overflow flaw in TianoCore EDK II allows attackers to execute arbitrary code before Secure Boot initializes during PXE network boots on enterprise servers. [More info](https://thehackernews.com/2026/10/critical-16-year-old-uefi-flaw-can-run.html)

- **Adobe Patches Critical Campaign Classic & Connect Bugs**: Adobe issued security patches for eight critical vulnerabilities in Campaign Classic, including SQL injection and security bypass bugs (CVE-2026-104354, CVE-2026-105779), alongside a critical code injection fix for Adobe Connect Desktop and Mobile (CVE-2026-48360). [More info](https://thehackernews.com/2026/10/adobe-fixes-8-critical-campaign-classic.html)

- **CISA Warns of Node2Shell Brotli Vulnerability in Node.js**: Threat actors are actively exploiting a critical memory corruption vulnerability in the Node.js Brotli decoder ("Node2Shell") to execute arbitrary code on enterprise management interfaces. [More info](https://www.bleepingcomputer.com/news/security/cisa-warns-of-hackers-now-exploiting-critical-node2shell-flaw/)

- **Telegram for Android RCE via Incoming Voice Calls**: A critical zero-click vulnerability chain in Telegram for Android allowed remote attackers to execute arbitrary code and achieve full control over a target device simply when an incoming voice call was answered. The issue was resolved in version 12.10.4. [More info](https://thehackernews.com/2026/10/telegram-android-flaw-lets-attackers.html)

## 🎯 Adversaries

- **China-Nexus Actors Chain PHP2Shell & Fragnesia Zero-Day in VMware ESX**: Adversaries exploited a VMware ESX zero-day and chained PHP2Shell vulnerabilities with the Fragnesia Linux kernel flaw to acquire root access on network firewalls and compromise at least 25 systems globally, including US government-affiliated servers. [More info](https://www.helpnetsecurity.com/2026/10/29/php2shell-fragnesia-vmware-esx-zero-day/)

- **APT Group UAT-11473 Exploits Cisco SD-WAN Zero-Day**: Threat actors are exploiting an authentication-bypass flaw (CVE-2026-20127) in Cisco Catalyst SD-WAN Controllers to deploy a custom malware framework named KeyDrift for persistent remote access and lateral movement. [More info](https://www.bleepingcomputer.com/news/security/hackers-exploit-cisco-sd-wan-flaw-to-deploy-custom-keydrift-malware/)

- **Fake ChatGPT and Claude Apps Spread XMRig via DLL Sideloading**: Cybercriminals are abusing SEO poisoning and malicious GitHub repositories to distribute malicious ZIPs containing signed AI desktop binaries alongside a malicious `winmm.dll`, leveraging DLL sideloading to fetch XMRig miners via encrypted DoH requests. [More info](https://thehackernews.com/2026/10/fake-chatgpt-and-claude-apps-abuse.html)

- **MR ROBOT MaaS Targets Indian Banking Customers**: A Malware-as-a-Service operation rents customized Android banking trojans via Telegram bots, using fake Play Store pages to infect devices and intercept call and SMS verification messages to bypass multi-factor authentication. [More info](https://www.infosecurity-magazine.com/news/robot-malware-indian-bank-customers/)

- **NetamLoader Used in Espionage Against Asian Governments**: Kaspersky uncovered an advanced espionage campaign deploying the modular NetamLoader framework against customized Windows 10 OS builds used by Asian government entities to establish persistent access and execute secondary payloads. [More info](https://securelist.com/netamloader/121676/)

- **Volt Typhoon Routes Zero-Day Attacks via Silent Train Relay**: China-nexus actor Volt Typhoon utilized a covert relay network of compromised SOHO routers and VPS nodes to bypass geofencing controls while exploiting zero-days across Cisco, Arista, and N-able platforms. [More info](https://thehackernews.com/2026/10/volt-typhoon-used-covert-silent-train.html)

- **Automated GitHub Issues Campaign Targets 61 Public Repos**: Threat actors executed an automated supply chain campaign targeting 61 public GitHub repositories in under an hour by submitting automated issues laden with malicious dependency payloads and links. [More info](https://www.theregister.com/security/2026/10/29/attackers-turn-github-issues-into-supply-chain-campaign-against-61-public-repos-in-less-than-an-hour/5306153)

## 📈 Trends

- **Emergence of the "Threat Operator" Role in AI-Native SOCs**: Security operations centers are transitioning toward AI-native architectures, shifting analyst career paths toward managing automated AI detection, investigation, and response workflows. [More info](https://thehackernews.com/2026/10/the-rise-of-threat-operator-how-ai-will.html)

- **319 Chrome Extensions Hijack Searches for 13.4M Users**: A widespread search-hijacking campaign involving 319 Chrome extensions secretly modified browser settings to route user queries through affiliate marketing networks, posing significant data privacy risks. [More info](https://www.bleepingcomputer.com/news/security/chrome-extensions-with-134-million-installs-caught-hijacking-searches/)

- **InfraTrust Warns of Infrastructure Attacks Targeting PHP2Shell & Node2Shell**: A new report highlights aggressive campaigns targeting edge network devices, firewalls, and application delivery controllers via PHP2Shell and Node2Shell Brotli vulnerabilities. [More info](https://www.bleepingcomputer.com/news/security/infratrust-report-warns-of-exploited-flaws-in-critical-network-infrastructure/)

- **Google and Mozilla Patch Over 200 Browser Vulnerabilities**: Chrome (v156) and Firefox (v159) updates resolved over 200 security flaws combined, addressing numerous high-severity memory safety issues and use-after-free conditions. [More info](https://www.securityweek.com/chrome-and-firefox-updates-patch-over-200-vulnerabilities/)

## 💥 Breaches & Leaks

- **Fake Padre Terminal Crypto App Steals $23K on Apple App Store**: A malicious crypto trading app named Padre Terminal spoofed legitimate interfaces on the App Store to exfiltrate private keys and seed phrases, resulting in the theft of $23,000 before its removal by Apple. [More info](https://www.bleepingcomputer.com/news/security/fake-crypto-app-on-apple-app-store-linked-to-23k-wallet-theft/)

- **UK Registrar 123 Reg Discloses AI-Driven Data Attack**: UK domain registrar 123 Reg disclosed a cyberattack attributed to a China-nexus threat actor that impacted customer contact details, VAT numbers, and product records. [More info](https://www.theregister.com/cyber-crime/2026/10/28/123-reg-discloses-ai-cyberattack-on-customer-data-suspects-china-nexus/5305936)

## 📚 Others

- **GitHub Announces Preview of npm Firewall**: GitHub introduced an npm Firewall feature to block malicious open-source packages before installation by detecting suspicious install scripts and enforcing configurable cooldown periods on new package releases. [More info](https://thehackernews.com/2026/10/github-launches-npm-firewall-to-block.html)

- **Discord to Enable Search Engine Indexing for Public Server Messages**: Discord announced plans to allow search engines to index public server messages in Discoverable Servers starting in mid-December, prompting administrators to review data-sharing and privacy settings. [More info](https://www.bleepingcomputer.com/news/security/discord-to-let-search-engines-index-public-server-messages/)

---

[⬅ Back to Archive](https://pranakn.github.io)
