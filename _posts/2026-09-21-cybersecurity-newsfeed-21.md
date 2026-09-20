---
title: "Cybersecurity Newsfeed - 21/09/26"
date: 2026-09-20 09:00:00 -0300
categories: [News]
permalink: /posts/news-21-09-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware, ai-security, supply-chain]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, AI security, and other notable developments."
image:
  path: assets/img/posts/newsfeed-2026-09-21.png
  alt: Cybersecurity Newsfeed - 21/09/26
---

# Cybersecurity Newsfeed

## 📅 21/09/26

## 🛡️ Vulnerabilities

- **Critical Pre-Auth RCE in Orkes Conductor (CVE-2026-58138)**: Threat actors are actively exploiting a CVSS 9.8 flaw in Orkes Conductor workflow platforms prior to v3.30.2. The bug stems from unsandboxed GraalVM evaluators with unrestricted host access, allowing attackers to execute OS commands via malicious inline JavaScript or Python expressions sent to unauthenticated API endpoints. Fortinet reports thousands of blocked exploitation attempts globally. [More info](https://www.cysecurity.news/2026/09/critical-orkes-conductor-flaw-exploited.html) | [More info](https://thehackernews.com/2026/09/critical-pre-auth-rce-in-orkes.html)

- **OpenAI Codex Double Sandbox Escape**: Researchers disclosed two unauthenticated RCE bugs in OpenAI Codex. The "Heapjack" flaw leveraged shared memory contexts in `node_repl` to steal authorization tokens, while "Overpatch" bypassed path restrictions in `apply_patch`. OpenAI resolved both issues in Codex Desktop build 26.818.21641 and Codex CLI 0.149.0. [More info](https://www.bleepingcomputer.com/news/security/researchers-escape-openai-codex-sandbox-to-run-commands-on-host/)

- **Plugin4Shell Impacts AI Coding Agents**: A zero-click supply-chain flaw bypasses Git SHA-pinning in major AI coding agents (Claude Code, Codex, GitHub Copilot, Gemini CLI). Attackers creating matching 40-character branch names on remote Git hosts can cause background auto-update mechanisms to pull malicious code without user interaction. [More info](https://www.helpnetsecurity.com/2026/09/18/plugin4shell-ai-coding-agents-vulnerability/)

- **SolarWinds Access Rights Manager Hard-Coded Key (CVE-2026-28326)**: SolarWinds patched a high-severity flaw (CVSS 8.8) in ARM versions up to 2026.2 caused by a static encryption key. An unauthenticated remote attacker could leverage the vulnerability to achieve remote code execution. System admins are advised to upgrade to version 2026.2.1 immediately. [More info](https://thehackernews.com/2026/09/solarwinds-patches-arm-hard-coded-key.html)

- **CISA KEV Adds Linux Kernel Flaw (CVE-2025-39682)**: CISA added an improper check flaw in the Linux Kernel to its Known Exploited Vulnerabilities catalog. Federal agencies under BOD 26-04 are mandated to remediate the flaw on internet-exposed assets where exploitation could grant total host control. [More info](https://www.cisa.gov/news-events/alerts/2026/09/18/cisa-adds-one-known-exploited-vulnerability-catalog)

- **CISA Adds Two Additional Linux Kernel Bugs to KEV**: CISA expanded its catalog with a race condition vulnerability (CVE-2025-39964) and an out-of-bounds write flaw (CVE-2026-53266) in the Linux Kernel, both actively exploited in the wild to achieve code execution or local privilege escalation. [More info](https://www.cisa.gov/news-events/alerts/2026/09/18/cisa-adds-two-known-exploited-vulnerabilities-catalog)

- **Public LPE Exploits Released for 4 Linux Kernel Flaws**: PoC exploits were published for four Linux networking vulnerabilities—DirtyAH6 (CVE-2026-80844), TUNderflow (CVE-2026-81000), PPPoEject (CVE-2026-68121), and DiagSpill (CVE-2026-74469). Discovered via AI-assisted analysis, they allow unprivileged users to corrupt memory and gain root access when unprivileged user namespaces are enabled. [More info](https://thehackernews.com/2026/09/public-exploits-released-for-four-linux.html)

- **WordPress Core "Click2Shell" Flaw Patched**: WordPress 7.1.1 resolves a high-severity flaw where URL parsing discrepancies allow specially crafted URLs to force logged-in admins into auto-installing inactive themes from WordPress.org without confirmation. Paired with unauthenticated file execution bugs in installed themes, researchers demonstrated full remote code execution. [More info](https://thehackernews.com/2026/09/new-wordpress-click2shell-flaw-forces.html)

- **Unbound DNS Resolver RCE and DoS Flaws**: NLnet Labs released version 1.26.1 to address memory corruption vulnerabilities in DNSSEC validation routines and packet processing handlers that let unauthenticated remote attackers crash the resolver daemon or execute code with process privileges. [More info](https://www.cysecurity.news/2026/09/unbound-1261-patches-critical-rce-dos.html)

- **Check Point Security Management Root Buffer Overflow (CVE-2026-91843)**: Emergency updates were released for a critical stack-based buffer overflow in Check Point Security Management and Log Servers, allowing unauthenticated remote attackers to execute code as root without user interaction. [More info](https://www.bleepingcomputer.com/news/security/check-point-warns-critical-flaw-lets-hackers-execute-code-as-root/)

## 🎯 Adversaries

- **North Korean Group WaterPlum Infects 30,000 Devices**: Under the "Contagious Interview" campaign, North Korea's WaterPlum hacked over 30,000 devices across 100 countries, stealing $10.7M in cryptocurrency. Operating under the 313 General Bureau, they target job seekers with fake interviews and infected npm or VS Code packages deploying BeaverTail and InvisibleFerret malware. [More info](https://www.bleepingcomputer.com/news/security/north-korean-waterplum-hackers-infected-30-000-devices-worldwide/)

- **ShinyHunters Hacks and Defaces Clop Ransomware Leak Site**: ShinyHunters exploited an unauthenticated file upload vulnerability in Grav CMS to breach and deface Clop's Tor data leak site. The group exfiltrated source code, system logs, and private keys for Clop's onion service, giving the ransomware operation 72 hours to satisfy extortion demands. [More info](https://www.bleepingcomputer.com/news/security/shinyhunters-hacks-clop-leak-site-threatens-to-extort-ransomware-gang/)

- **Brevo Supply-Chain Attack Spreads to 100k+ Websites**: Attackers obtained a long-lived Cloudflare API key from Brevo's source code following an initial SSO breach, deploying a malicious Cloudflare Worker to rewrite edge responses, strip CSP headers, and inject malware into Brevo JS widgets to deliver ClickFix prompts and backdoor WordPress sites. [More info](https://securityaffairs.com/199355/hacking/brevo-supply-chain-attack-infected-over-100000-websites.html)

- **RatHat Android Trojan Uses Live AI for Device Hijacking**: Distributed via smishing and malvertising, RatHat abuses Accessibility permissions to open an ADB session, capture PINs, inject credential-stealing overlays into banking apps, and feed accessibility trees to an LLM assistant for automated UI navigation. [More info](https://www.malwarebytes.com/blog/news/2026/09/new-android-malware-uses-ai-to-steal-bank-logins-and-pins) | [More info](https://www.bleepingcomputer.com/news/security/new-rathat-android-malware-uses-ai-to-automate-device-control/)

- **Global Postal Service SMS Phishing Campaign**: A massive SMS campaign impersonating postal services (USPS, bpost, PostNL, Correos) uses fake unpaid customs fee notices to route victims through short links to fraudulent tracking portals that steal credit cards, IBANs, and online banking credentials. [More info](https://www.malwarebytes.com/blog/scams/2026/09/fake-parcel-delivery-messages-steal-your-card-and-bank-details)

## 📈 Trends

- **360 Netlab AI Security Weekly Report**: Highlights critical threats across the AI ecosystem, including QAnything unauthenticated root RCE (CVE-2026-88533), vLLM chat template DoS risks, Shai-Hulud AI coding session worms, GemStuffer malicious RubyGems, unauthorized AI proxy services, and ChatGPT payment phishing campaigns. [More info](https://blog.netlab.360.com/aian-quan-zhuan-ti-zhou-bao-6/)

- **BragJack Extension Attack Hijacks AI Browser Agents**: Researchers demonstrated "Prompt Forcing," an attack vector using malicious browser extensions and Chromium's `declarativeNetRequest` API to bypass security headers and force AI assistants (Chrome, Edge, Perplexity, Claude) into executing unauthorized commands and exfiltrating local data. [More info](https://www.bleepingcomputer.com/news/security/bragjack-attacks-hijack-ai-browser-agents-through-malicious-extensions/)

- **Vectra AI Launches Ascent Partner Program**: Vectra AI introduced a partner initiative to counter machine-speed, AI-driven cyber threats by integrating technology vendors, MSSPs, and integrators around enhanced SOC visibility, automated response, and cross-platform identity protection. [More info](https://www.darkreading.com/cyberattacks-data-breaches/vectra-ai-launches-ascent-new-era-ai-driven-attacks)

- **AWS AgentCore Harness Credential Leak Risks**: Unit 42 analyzed default configurations in AWS AgentCore Harness, showing how prompt injection can manipulate shared-memory shell tools into exfiltrating plaintext secrets from AWS AgentCore Identity to unauthorized endpoints. [More info](https://unit42.paloaltonetworks.com/securing-aws-agentcore-harness-credentials/)

## 🤖 AI Security & Innovation

- **Malicious npm Campaign Evades Install-Script Defenses**: Packages like `indexed-btree` embedded malicious logic directly within legitimate runtime methods like `BTree.prototype.set()`, evading npm v12 lifecycle script blocks and static analyzers to exfiltrate system metadata and retrieve payloads via Sepolia Ethereum smart contracts. [More info](https://www.bleepingcomputer.com/news/security/malicious-npm-packages-evade-install-script-defenses-at-runtime/)

- **Talking Tilly AI Hotline Mandates Biometric Scans**: An interactive AI video call hotline featuring actress Tilly Norwood relies on Didit biometrics (video selfies or ID scans) to perform mandatory real-time age verification and emotional analysis on callers under UK "legitimate interest" legal bases. [More info](https://www.bleepingcomputer.com/news/security/viral-ai-actress-hotline-face-scans-every-caller-watches-their-mood/)

## 💥 Breaches & Leaks

- **Gyazo Server Breach Exposes 23.6 Million User Records**: Image-sharing platform Gyazo suffered a server breach exposing 23.62M user records (names, emails, password hashes, session IDs) and 490M image metadata records, including upload IP addresses, EXIF location data, and private image passphrases. [More info](https://www.bleepingcomputer.com/news/security/gyazo-server-flaw-exploited-to-steal-236-million-user-records/)

---

[⬅ Back to Archive](https://pranakn.github.io)
