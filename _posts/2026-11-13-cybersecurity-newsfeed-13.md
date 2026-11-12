---
title: "Cybersecurity Newsfeed - 13/11/26"
date: 2026-11-12 09:00:00 -0300
categories: [News]
permalink: /posts/news-13-11-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-11-13.png
  alt: Cybersecurity Newsfeed - 13/11/26
---

# Cybersecurity Newsfeed

## 📅 13/11/26

## 🛡️ Vulnerabilities

- **Windows "SignDrop" CLFS Zero-Day (Unpatched)**: Security researchers Abdelhamid Naceri and MSNightmare published PoC exploits for a local privilege escalation zero-day in the Windows Common Log File System (`clfs.sys`). By abusing Microsoft's October 2025 log-authentication mitigation with object manager symbolic links, attackers force privileged processes like Microsoft Defender to create writable `.cnpf` recovery files, bypassing tamper protection to spawn a `SYSTEM` shell on Windows 11 26H2 and Windows Server 2025. [More info](https://thehackernews.com/2026/11/new-signdrop-zero-day-exploit-turns.html) | [More info](https://www.bleepingcomputer.com/news/security/new-windows-signdrop-zero-day-gives-hackers-system-privileges/)

- **N-able N-central "4EverAble2Shell" Zero-Day (CVE-2026-90436 / VULN-2026-0009)**: Threat actors are actively exploiting a newly disclosed zero-day chain hours after PoC release to gain root access and deploy XMRig Monero miners on at least 21 servers. Chaining an Apache Axis bug with a privilege escalation flaw in `setLDFileOwner`, the exploit bypasses Hotfix 2 when Legacy APIs are enabled. [More info](https://www.bleepingcomputer.com/news/security/new-n-able-4everable2shell-zero-day-exploited-hours-after-poc-released/)

- **Apache HTTP Server HTTP/2 RCE (CVE-2026-119618)**: Discovered by Anthropic and Google Cloud researchers, a thread synchronization race condition in `mod_http2`'s `assign_headers()` function causes heap memory corruption. Unauthenticated attackers can achieve remote code execution on HTTP Server versions 2.4.55–2.4.70 and standalone `mod_h2` 2.0.8–2.0.42. [More info](https://www.bleepingcomputer.com/news/security/apache-http-server-patches-critical-http-2-remote-code-execution-flaw/)

- **Critical Red Hat Quay Registry Flaws (CVE-2026-123710 & CVE-2026-110697)**: Red Hat patched two critical flaws (CVSS 9.8 and 9.9) allowing attackers to abuse anonymous `/v2/auth` tokens to register persistent signing keys or exploit SQL `LIKE` wildcards to leak robot account tokens across tenants, enabling unauthorized read/write access to private container images. [More info](https://thehackernews.com/2026/11/critical-red-hat-quay-flaw-lets.html)

- **Citrix NetScaler & Secure Access Updates**: Citrix resolved 12 vulnerabilities uncovered via AI-assisted code analysis across NetScaler ADC, Gateway, Console, and Secure Access Clients, including nine critical memory corruption/DoS bugs, unauthenticated Console access (CVE-2026-120869), and local privilege escalation flaws. [More info](https://thehackernews.com/2026/11/citrix-patches-12-netscaler-and-secure.html)

- **Fortinet Patches Nearly 100 Vulnerabilities**: Using frontier AI models in internal testing, Fortinet issued 89 advisories resolving roughly 17 critical flaws across FortiOS, FortiMail, FortiAuthenticator, and FortiClient—including "Fortinet2Shell," a CORS misconfiguration enabling local code execution when FortiPAM is active. [More info](https://www.securityweek.com/fortinet-patches-nearly-100-vulnerabilities/)

- **Node.js HTTP/2, HTTPS, and TLS Security Fixes**: Updates across Node.js 22.x, 24.x, and 26.x resolve 16 vulnerabilities, including seven high-severity flaws such as CVE-2026-123864, which allows unauthenticated clients to leak TLS private keys and cross-user memory when `res.flushHeaders()` is used. [More info](https://thehackernews.com/2026/11/nodejs-fixes-16-flaws-including-http2.html)

- **Chrome 157 and Firefox 160 Patch 182 Flaws**: Google fixed 83 vulnerabilities in Chrome 157 (including five critical use-after-free bugs, 18 reported by Anthropic and OpenAI), while Mozilla patched 99 defects in Firefox 160, addressing 57 high-severity memory corruption, sandbox escape, and SOP bypass issues. [More info](https://www.securityweek.com/chrome-firefox-updates-patch-180-vulnerabilities/)

- **Android "GhostMap" Persistent Boot-Loop Flaw**: Bitdefender disclosed an unpatched bug affecting Android 10–17 where simply installing a malformed APK triggers a `SIGBUS` crash in `system_server` due to zip parsing discrepancies between `libziparchive` and `libandroidfw`, forcing a factory reset to recover. [More info](https://hackread.com/ghostmap-android-flaw-phones-stuck-crash-loop/)

## 🎯 Adversaries

- **Luna Moth Re-Targets Law Firms via Copilot Vishing**: The data extortion group is using broken PDF lures and fake IT support video calls to trick victims into opening browser developer tools inside Microsoft Copilot, copying their Microsoft Graph API bearer tokens, and pasting them on public text-sharing sites to bypass MFA and exfiltrate files. [More info](https://www.darkreading.com/data-privacy/extortion-luna-moth-law-firms-second-time)

- **SilentAir & Liminal Panda Target Telecom Networks**: Enea identified state-sponsored group SilentAir exploiting SS7/Diameter signaling and silent SMS across hijacked Asian mobile operators to intercept VIP calls, texts, and 2FA codes in Taiwan. Meanwhile, China-nexus group Liminal Panda deployed a new `GTPDoor` backdoor variant tunneling C2 traffic inside 5G GTP-U user-plane data. [More info](https://www.infosecurity-magazine.com/news/silentair-liminal-panda-telco/)

- **"Falcon" Browser C2 Framework Hits Government Webmail**: Palo Alto Unit 42 detailed Falcon (aka XG / Xiàng Gē), a JavaScript C2 framework related to PeckBirdy injected into compromised Middle Eastern and Southeast Asian government webmail portals to sideload malicious Chrome extensions and deploy the OneDrive-abusing `Antino` implant. [More info](https://unit42.paloaltonetworks.com/falcon-c2-browser-compromise/)

- **MS SQL Brute-Force Campaign Deploys Gh0st RAT & Miners**: FortiGuard Labs tracked attackers scanning port 1433 with Naabu and brute-forcing MS SQL admin credentials (`dwm.exe`) to enable `xp_cmdshell` via `2018.sql`, subsequently installing a disguised XMRig miner and a Gh0st RAT variant for persistent remote control. [More info](https://hackread.com/hackers-abuse-microsoft-sql-servers-monero-miner-gh0st-rat/)

- **"TypoPrompting" Hijacks 186 Fake AI Domains**: Island uncovered 186 typosquatted domains impersonating 27 AI tools (ChatGPT, Claude, Gemini, Copilot) that fingerprint visitors to serve ClickFix malware, Net Guard hijackers, or redirect users to 16 search-hijacking Chrome extensions with nearly 1 million installs. [More info](https://thehackernews.com/2026/11/186-fake-ai-domains-redirect-users-to.html)

## 📈 Trends

- **356% Surge in Malicious GSocket Abuse on Linux**: Microsoft warned that attackers are planting the legitimate open-source Global Socket (`GSocket`) relay tool on compromised PHP, cPanel, and Apache servers to maintain firewall-bypassing persistent access even after initial vulnerabilities are patched. [More info](https://www.bleepingcomputer.com/news/security/hackers-plant-gsocket-on-linux-servers-for-persistent-access/)

- **Threat Actors Weaponize AI Red-Teaming Frameworks**: Unit 42 observed adversaries hosting AI-powered autonomous penetration testing tools like ARTEX and CyberStrikeAI to target global cloud environments, compressing the timeline between reconnaissance and exploitation. [More info](https://unit42.paloaltonetworks.com/artex-and-ai-powered-red-teaming-tools/)

- **eBPF Rootkits Enter Underground Cybercrime Forums**: Flare researchers report that stealthy eBPF kernel implants—capable of hooking syscalls like `getdents64` and `execve` while evading `lsmod`—have moved from academic concepts into Russian-language cybercrime tutorials and source code repositories. [More info](https://www.bleepingcomputer.com/news/security/ebpf-rootkits-why-underground-actors-are-taking-notice/)

- **Weekly Threat Roundup (Binance Laundering, Europol Takedown & AI Agents)**: Key developments include North Korean actors laundering $6.43B from Binance via NEAR meme coins, Europol seizing 235 servers to disrupt GootLoader, CastleRAT, and StealC, and Silent Lynx leveraging AI agents to breach Tajik ministries. [More info](https://thehackernews.com/2026/11/threatsday-59-linux-kernel-bugs-falcon.html)

## 💥 Breaches & Leaks

- **Apify Rotates API Tokens After Internal Breach**: Web scraping platform Apify—serving 80,000 customers including Microsoft and Samsung—disclosed unauthorized internal access between November 9–10. While no stored passwords or account data appear compromised, Apify terminated sessions, rotated API tokens/proxy passwords, revoked GitHub OAuth links, and urged immediate 2FA resets. [More info](https://www.bleepingcomputer.com/news/security/apify-rotates-api-tokens-prompts-2fa-resets-after-breach/)

- **Baker Tilly Discloses Third-Party Data Breach**: U.S. accounting firm Baker Tilly notified clients that a September intrusion at an unnamed third-party provider exposed names, addresses, and Social Security numbers of clients and dependents, impacting at least 10,456 individuals in Texas alone. [More info](https://www.bleepingcomputer.com/news/security/baker-tilly-notifies-clients-of-data-breach-at-third-party-provider/)

- **Lego's BrickLink Offline Nearly a Week After "Unusual Activity"**: Following unusual activity detected on November 6, Lego-owned marketplace BrickLink remains offline under containment and security investigation, leaving buyers and sellers locked out without a confirmed restoration timeline. [More info](https://www.theregister.com/security/2026/11/12/lego-marketplace-bricklink-in-pieces-after-unusual-activity-takes-it-offline-for-almost-a-week/5309425)

- **Poland Takes ePUAP Government Portal Offline Amid Cyberattack**: Polish authorities temporarily shut down the national ePUAP electronic services platform after halting a cyberattack, disrupting digital mailboxes and Trusted Profile identity services while confirming core IT infrastructure remained uncompromised. [More info](https://www.cysecurity.news/2026/11/poland-takes-government-services.html)

## 📚 Others

- **AWS Releases AI-Built Open-Source Cloud Emulator**: Amazon Web Services open-sourced `AWS Emulator`, a local/CI cloud simulation tool written entirely by autonomous AI agents without human code review—though AWS cautions it lacks IAM policy evaluation and is unsuitable for security testing. [More info](https://www.helpnetsecurity.com/2026/11/12/aws-ai-agents-built-emulator/)

- **Microsoft Launches .NET 11 with Supply Chain Hardening**: Released alongside the end-of-support for .NET 8 and 9, .NET 11 introduces NuGet minimum package publication age controls, reproducible container digests, SignalR live auth refreshes, and experimental MCP server templates. [More info](https://www.helpnetsecurity.com/2026/11/12/net-11-security-changes/)

- **European Spyware Victims Face Legal Stonewalling**: An IrpiMedia investigation highlights that despite a February 2026 Greek court conviction of Intellexa executives and a Polish parliamentary inquiry, EU governments in Spain, Hungary, Poland, and Italy continue invoking national security exemptions to block Pegasus, Predator, and Graphite spyware accountability. [More info](https://securityaffairs.com/202922/malware/predator-pegasus-and-graphite-governments-accused-of-spyware-abuse-face-little-accountability.html)

---

[⬅ Back to Archive](https://pranakn.github.io)
