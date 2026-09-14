---
title: "Cybersecurity Newsfeed - 15/09/26"
date: 2026-09-14 09:00:00 -0300
categories: [News]
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-09-15.png
  alt: Cybersecurity Newsfeed - 15/09/26
---

# Cybersecurity Newsfeed

## 📅 15/09/26

## 🛡️ Vulnerabilities

- **Cisco Secure Email Gateway SQL Injection (CVE-2026-76461)**: CISA added this flaw to its KEV catalog following active exploitation, allowing unauthenticated attackers to execute unauthorized commands or compromise systems. Under BOD 26-04, federal agencies must prioritize remediation, perform compromise checks prior to patching, and deprioritize lower-risk flaws. [More info](https://www.cisa.gov/news-events/alerts/2026/09/14/cisa-adds-one-known-exploited-vulnerability-catalog)

- **Gitea Critical RCE (CVE-2026-60004)**: Exploited in the wild by Chinese threat actor Red Heron, this critical vulnerability allows remote code execution in self-hosted Gitea instances. Attackers weaponized an automated framework to steal source code repositories, collect credentials, and achieve root access on a Proxmox cluster. [More info](https://thehackernews.com/2026/09/red-heron-exploits-gitea-rce-to.html)

- **Vite Dev Servers Path Traversal (CVE-2026-39364)**: A high-severity path traversal vulnerability in Vite development servers is being targeted in mass-scanning campaigns to steal cloud credentials, `.env` files, AWS directories, Azure tokens, and system variables. Attackers bypass file restrictions by appending specific query parameters to HTTP GET requests. [More info](https://www.bleepingcomputer.com/news/security/hackers-target-exposed-vite-dev-servers-to-steal-aws-azure-secrets/)

- **GitLab CE/EE Path Traversal (CVE-2026-85706)**: Active exploitation probes targeting versions 18.7 through 19.3.2 prompted CISA to add this critical path traversal bug to its KEV catalog. The flaw allows unauthenticated remote attackers to read arbitrary server files via improper path confinement in the repository commits API. [More info](https://www.infosecurity-magazine.com/news/hackers-exploit-maximum-severity/)

## 🎯 Adversaries

- **Red Heron Exploits Gitea for Network Infiltration**: Chinese threat actor Red Heron compromised 13 organizations across six countries via Gitea vulnerability CVE-2026-60004. Post-exploitation tools include JITTERLY, a 30-command Linux backdoor, and SIXZUT, an LD_PRELOAD rootkit patching 15 system functions for evasion. [More info](https://thehackernews.com/2026/09/red-heron-exploits-gitea-rce-to.html)

- **HBO Max Reddit Account Hijacked for ClickFix Campaign**: Attackers hijacked HBO Max's verified Reddit account to run 108 malicious ads pushing information stealers via the PasteSwitch operation. Victims were directed to fake landing pages instructing them to paste obfuscated commands into Windows Run, PowerShell, or macOS Terminal. [More info](https://www.bleepingcomputer.com/news/security/hackers-hijack-hbo-max-reddit-account-to-push-malware-in-clickfix-ads/)

- **Malicious Twitch Extension Steals OAuth Tokens**: The Chrome and Firefox extension "Twitch Enhanced Viewer | JeetBot" (30k+ installs) was caught intercepting account-scoped OAuth bearer tokens. It appends tokens as cleartext URL query parameters during video redirects to proxy servers operated by Russian streaming bot service JeetBot. [More info](https://www.bleepingcomputer.com/news/security/twitch-extension-with-30k-installs-exposes-users-oauth-tokens/) | [More info](https://www.infosecurity-magazine.com/news/malicious-twitch-extension-oauth/)

- **SilverFox Cybercrime Group Evolves Payload Delivery**: 360 Threat Intelligence Center tracked four operational phases of the SilverFox group's cloud delivery infrastructure. The campaign evolved from unconditional payload delivery to a cloud-side blacklist model that returns benign setup files on flagged domains while serving active malware on newly deployed domains. [More info](https://blog.netlab.360.com/yin-hu-yun-duan-sheng-si-bo-cong-wu-tiao-jian-fan-hui-dao-hei-ming-dan-ji-zhi/)

## 📈 Trends

- **Covert WebRTC Tunneling Tool Released**: A new open-source tool named `whitelist-bypass` enables covert network tunneling through whitelisted commercial video-calling platforms like VK Call and Yandex Telemost. It bypasses strict filters using WebRTC data channels or encoding data into VP8 video tracks. [More info](https://www.darknet.org.uk/2026/09/whitelist-bypass-webrtc-tunnels-through-video-calling-platforms/)

- **Rethinking Patch Management Automation**: Field CTO Gene Moody highlights that accelerating patch management without structured controls risks propagating faulty updates across enterprise endpoints. Organizations should implement staged deployment rings, health-based automated halt conditions, and mandatory human review for high-impact infrastructure. [More info](https://www.bleepingcomputer.com/news/security/why-patch-automation-needs-brakes-not-just-an-accelerator/)

- **Rise in Malicious OAuth App Exploitation**: Threat actors are increasingly shifting away from password theft to tricking users into granting broad permissions to malicious third-party OAuth apps, granting persistent access to organizational emails, files, and cloud data in Google Workspace environments. [More info](https://www.bleepingcomputer.com/news/security/webinar-how-malicious-oauth-apps-can-lead-to-google-workspace-breaches/)

## 💥 Breaches & Leaks

- **Japan's Digital Agency VPN Breach**: An attacker exploited a medium-severity VPN vulnerability to compromise a maintenance staff account, exposing 246,000 personal records of government employees and public officials using the Government Solution Service (GSS). Exposed data includes names, email addresses, phone numbers, and physical addresses. [More info](https://www.bleepingcomputer.com/news/security/japans-digital-agency-says-vpn-flaw-exposed-246-000-personnel-records/)

- **Revolut Social Engineering Data Breach**: Revolut confirmed a data breach after compliance staff fulfilled unauthorized information requests sent from a domain-authenticated government email address. Exposed PII includes customer names, DOBs, passport copies, verification selfies, transaction histories, and crypto details, specifically targeting high-net-worth users. [More info](https://www.infosecurity-magazine.com/news/revolut-data-breach-fake-government/) | [More info](https://www.bleepingcomputer.com/news/security/revolut-discloses-data-breach-exposing-financial-info-passports/)

## 🔬 Hardware & Research

- **DDRop Attack Breaks Confidential Computing Protection**: Researchers disclosed DDRop, a hardware interposer attack costing under $200 that breaks memory protection in Intel TDX, Intel Scalable SGX, and AMD SEV-SNP. By dropping memory write commands on the DDR5 memory bus, attackers force CPUs to read stale data, enabling guest VM compromise and attestation forgery. [More info](https://thehackernews.com/2026/09/new-ddrop-attack-breaks-intel-tdx-and.html)

## 📚 Others

- **Microsoft Releases Out-of-Band Windows Updates**: Emergency updates were released to address Remote Desktop Services (RDS) instability caused by the September 2026 updates. The patches resolve RDP connection failures, sign-in errors, server unresponsiveness, and Hyper-V Linux VM shared folder access issues across Windows 10, 11, and Windows Server 2022/2025. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-releases-emergency-windows-updates-to-fix-rds-failures/)

---

[⬅ Back to Archive](https://pranakn.github.io)
