---
title: "Cybersecurity Newsfeed - 15/10/26"
date: 2026-10-14 09:00:00 -0300
categories: [News]
permalink: /posts/news-15-10-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-10-15.png
  alt: Cybersecurity Newsfeed - 15/10/26
---

# Cybersecurity Newsfeed

## 📅 15/10/26

## 🛡️ Vulnerabilities

- **Ivanti Connect Secure Zero-Day Exploitation (CVE-2026-104935)**: Security vendors issued urgent patches for two zero-day vulnerabilities in Ivanti Connect Secure. The high-severity flaw combines authentication bypass with remote code execution, enabling unauthenticated remote attackers to run arbitrary code. Threat actors like UTA0576 are actively exploiting it in the wild to extract local credentials and access Active Directory environments. [More info](https://www.darkreading.com/vulnerabilities-threats/ivanti-ics-zero-day-attacks-vendor-patching) | [More info](https://www.bleepingcomputer.com/news/security/cisa-warns-admins-to-immediately-fix-ivanti-flaw-exploited-as-zero-day/)

- **CISA Adds Four New Flaws to KEV Catalog**: CISA expanded its Known Exploited Vulnerabilities Catalog with CVE-2026-0322 (Palo Alto Networks PAN-OS Code Injection), CVE-2026-76519 (Cisco Secure Email Gateway Relative Path Traversal), CVE-2026-105133 (Ahsay AhsayCBS Improper Authentication), and CVE-2026-105134 (Ahsay AhsayCBS Command Injection). Federal agencies are required to remediate these flaws under Binding Operational Directive 26-04. [More info](https://www.cisa.gov/news-events/alerts/2026/10/14/cisa-adds-four-known-exploited-vulnerabilities-catalog)

- **"SneakPeek" Zero-Click Flaw in Anthropic Claude Code**: Security researchers disclosed a high-severity zero-click vulnerability affecting Anthropic's Claude Code Desktop application. By chaining a missing CSP, unrestricted origin access, and inactive request filtering, threat actors can trigger automated previews in public code repositories to silently exfiltrate developer credentials, AWS keys, and OAuth tokens without user interaction. [More info](https://www.darkreading.com/threat-intelligence/new-anthropic-sneakpeek-silent-zero-click-threat)

- **Collabora CODE Server Flaw Exploited on Nextcloud (CVE-2026-110447)**: Attackers are exploiting a critical command injection flaw in the Collabora Online Built-in CODE Server app for Nextcloud to deploy web shells. The vulnerability in `proxy.php` allows arbitrary bash command execution under web server privileges, prompting developers to issue fixes in version 26.4.303. [More info](https://thehackernews.com/2026/10/hackers-backdoor-nextcloud-servers.html)

- **Linux Kernel "Vghost" Subsystem Flaw (CVE-2026-74580)**: A high-severity flaw in the Linux kernel vhost subsystem enables local unprivileged users to achieve arbitrary kernel read/write access and escalate privileges to root across kernel versions 4.11 through 7.2-rc4. In virtualized setups with IOTLB mode, untrusted guest VMs can also write to host QEMU memory. [More info](https://thehackernews.com/2026/10/ai-found-linux-kernel-flaw-gives-local.html)

- **High-Severity Use-After-Free in curl (CVE-2026-92392)**: Developers released curl version 8.23.0 to fix a use-after-free flaw affecting versions 8.12.0 through 8.22.0. The bug occurs during HTTP/2 upload operations when a malicious server resets streams and manipulates internal memory references, allowing arbitrary code execution under specific heap conditions. [More info](https://thehackernews.com/2026/10/curl-patches-http2-upload-flaw-after.html)

- **Chrome and Firefox Patch 114 Flaws**: Google and Mozilla released browser updates addressing 114 vulnerabilities across Chrome and Firefox. Chrome version 155.0.8059.79/.80 patched 37 flaws, while Firefox version 158 resolved 77 vulnerabilities. Mozilla also launched Firefox Enterprise with enhanced management and security controls. [More info](https://www.securityweek.com/chrome-firefox-updates-patch-114-flaws-as-mozilla-unveils-firefox-enterprise/)

## 🎯 Adversaries

- **FBI Disrupts North Korean "Laptop Farm" Operations**: The U.S. DOJ and FBI raided 40 residences in Texas and Ohio under Operation "Lonestar Roundup," arresting two facilitators aiding North Korean threat actor Famous Chollima. The operations seized 187 laptops used as "laptop farms" to remotely access over 70 U.S. corporate networks under false identities, generating $3 million for the DPRK regime. [More info](https://www.bleepingcomputer.com/news/security/fbi-raids-dprk-it-worker-laptop-farms-in-texas-us-nationals-arrested/)

- **XWorm RAT Evolves into Advanced Surveillance Platform**: Researchers observed new variants of XWorm Remote Access Trojan incorporating anti-analysis techniques, obfuscated execution chains, and expanded modules for keystroke logging, credential harvesting, and remote system control to maintain persistent enterprise access. [More info](https://www.cysecurity.news/2026/10/xworm-rat-evolves-into-advanced.html)

- **SEO-Poisoning Attack Steals WatchGuard VPN Credentials**: Attackers set up a lookalike domain (`watchguard-vpn[.]net`) to harvest enterprise SSL VPN credentials. The malicious site intentionally fails the first login attempt to ensure accurate credential capture before redirecting users to download the legitimate, signed WatchGuard client directly from the vendor CDN. [More info](https://www.itsecurityguru.org/2026/10/14/fake-watchguard-vpn-site-steals-credentials-then-serves-the-genuine-signed-client/)

- **ROMULUS Multi-Payload Platform Leverages ClickFix**: Security analysts discovered ROMULUS, a multi-payload delivery platform using ClickFix social engineering techniques to distribute various malware families. The shared crimeware infrastructure misleads users into executing malicious PowerShell commands, delivering payloads like LegionLoader hidden inside inflated 842 MiB archives. [More info](https://www.infosecurity-magazine.com/news/romulus-malware-clickfix-deliver/)

- **Fake "Calendly | Meta Careers" Phishing Pages**: A phishing campaign targets job seekers using fraudulent scheduling pages mimicking Meta Careers. The kit presents an interactive calendar, collects personal details, and displays fake CAPTCHAs before relaying captured Facebook and Google credentials and 2FA tokens in real time. [More info](https://www.malwarebytes.com/blog/threat-intel/2026/10/fake-calendly-meta-careers-pages-steal-facebook-and-google-logins)

- **Hirudo Android Banking Malware Replaces Legitimate Apps**: A new Android malware strain named Hirudo is delivered via trojanized utility apps and uses Accessibility services to uninstall genuine banking applications. It replaces them with tampered versions embedded with YAHFA and Dobby hooking engines to bypass Play Integrity checks and capture credentials and PINs. [More info](https://www.bleepingcomputer.com/news/security/hirudo-android-malware-replaces-banking-apps-to-evade-security-checks/)

## 📈 Trends

- **Anthropic Warns of Autonomous AI Worms on IoT Devices**: Research demonstrates that lightweight AI models running across low-cost IoT device clusters (such as Android TV boxes) could achieve self-replication capabilities. The study outlines a four-stage process where AI agents discover hosts, execute code, and propagate independently without human interaction. [More info](https://www.malwarebytes.com/blog/ai/2026/10/ai-worms-could-spread-across-your-smart-devices-anthropic-warns)

- **Analyzing the Blind Spots of Agentic Penetration Testing**: Security researchers analyzed structural limits in automated agentic penetration testing tools, emphasizing that reachability and safety constraints leave attack surface gaps. Organizations are advised to combine AI pentesting with deterministic testing and exposure validation platforms to confirm exploitability safely. [More info](https://www.bleepingcomputer.com/news/security/the-blind-spots-of-agentic-pentesting-and-how-to-close-them/)

- **Radware Launches Protection for Model Context Protocol (MCP) Servers**: Radware introduced MCP Server Protection to secure enterprise AI integration layers. As organizations adopt MCP to connect AI agents with core workflows, the solution provides real-time visibility, monitors behavioral patterns, and mitigates protocol abuse and unauthorized tool interactions. [More info](https://www.helpnetsecurity.com/2026/10/14/radware-mcp-server-protection/)

## 💥 Breaches & Leaks

- **Hardware Supply-Chain Attack Targets Ledger Devices**: Hardware wallet manufacturer Ledger requested distributors in Southeast Asia and Hong Kong to halt product sales following a supply-chain attack. Third-party resellers distributed modified devices containing hardware implants with microcontrollers and eSIMs that exfiltrate 24-word recovery seed phrases over LTE without triggering OS self-checks. [More info](https://www.bleepingcomputer.com/news/security/ledger-asks-sellers-across-asia-to-halt-sales-after-supply-chain-attack/)

## 📚 Others

- **Microsoft Issues Out-of-Band Fix for Windows 11 VPN Failures**: Microsoft released cumulative updates KB5127648 and KB5127646 to resolve an issue causing Always On VPN connections with automatic protocol selection to fail or hang on Windows 11 following the September 2026 security updates. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-fixes-vpn-issues-caused-by-september-windows-updates/)

- **Windows 11 Updates Cause Remote Desktop Connection Failures**: Microsoft confirmed that recent Windows 11 updates trigger error `0xC000000D` on Remote Desktop connections when "Administrator protection" is enabled. Non-admin users receive "invalid token" errors when connecting to enterprise hosts while Microsoft works on a permanent fix. [More info](https://www.bleepingcomputer.com/news/security/microsoft-recent-windows-updates-may-trigger-remote-desktop-failures/)

---

[⬅ Back to Archive](https://pranakn.github.io)
