---
title: "Cybersecurity Newsfeed - 28/10/26"
date: 2026-10-27 09:00:00 -0300
categories: [News]
permalink: /posts/news-28-10-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-10-28.png
  alt: Cybersecurity Newsfeed - 28/10/26
---

# Cybersecurity Newsfeed

## 📅 28/10/26

## 🛡️ Vulnerabilities

- **CISA Adds Two PHP Remote Code Execution Flaws to KEV Catalog (CVE-2026-109618, CVE-2026-109619)**: CISA added two critical PHP vulnerabilities to its Known Exploited Vulnerabilities catalog involving memory corruption and internal request-state handling. Both allow unauthenticated attackers to execute arbitrary code remotely on web servers. Federal agencies must patch immediately under operational binding deadlines. [More info](https://www.cisa.gov/news-events/alerts/2026/10/27/cisa-adds-two-known-exploited-vulnerabilities-catalog) | [More info](https://www.cisa.gov/news-events/alerts/2026/10/26/cisa-adds-two-known-exploited-vulnerabilities-catalog)

- **AI Security Agent Discovers 4 Severe ICS Flaws in Under 4 Hours**: An autonomous AI security tool successfully discovered four high-severity vulnerabilities in widely deployed industrial control system (ICS) software within four hours. The flaws allow authentication bypasses and remote code execution across operational technology environments. [More info](https://www.theregister.com/security/2026/10/27/ai-hacker-finds-4-severe-bugs-in-popular-industrial-control-software-in-under-4-hours/5305811)

- **Critical Brotli "Node2Shell / Brotli2Shell" Out-of-Bounds Write Flaw (CVE-2026-111497)**: A severe memory corruption flaw in Google's open-source Brotli compression library exposes Node.js, .NET, Bun, Envoy Proxy, and Python HTTP clients to remote code execution. Threat intelligence confirms active exploitation in the wild against unpatched instances. [More info](https://www.helpnetsecurity.com/2026/10/27/node2shell-broccoli2shell-vulnerability-cve-2026-111497/) | [More info](https://www.securityweek.com/node2shell-brotli-flaw-triggers-patching-across-microsoft-node-js-python-packages/)

- **Microsoft Distrusts eMudhra Digital Certificates via Out-of-Band Update**: Microsoft issued emergency updates to revoke trust from seven root and intermediate digital certificates linked to eMudhra CA due to sub-256 key cryptographic weaknesses, preventing mathematical key recovery and MITM decryption. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-releases-windows-oob-updates-to-distrust-emudhra-certificates/)

- **GoAhead Web Server TLS Authentication Flaws (CVE-2026-115881)**: EmbedThis patched GoAhead web server v6.1.1 to fix OpenSSL backend failures that permitted revoked client certificates to authenticate under mTLS, alongside LibreSSL and Mbed TLS certificate validation bugs. [More info](https://thehackernews.com/2026/10/goahead-tls-flaws-allow-revoked-client.html)

- **Apple Backports iOS/iPadOS 18.7.11 Fix for Zero-Day (CVE-2026-86950)**: Apple released emergency updates backporting fixes for a CoreGraphics out-of-bounds write flaw that allowed arbitrary code execution, which was actively exploited against individuals running iOS versions prior to iOS 27. [More info](https://thehackernews.com/2026/10/apple-backports-fix-for-exploited.html)

- **Tailscale "Tailworm" Flaws Allow Root Remote Code Execution**: Cyberdione Labs disclosed 11 unpatched vulnerabilities in Tailscale mesh VPN and Headscale control servers, including an embedded SSH Unix-socket forwarding flaw that grants authorized users root execution and enrollment key theft. [More info](https://www.bleepingcomputer.com/news/security/tailscale-warns-of-serious-ssh-flaws-allowing-root-privilege-escalation/)

- **HPE Patches 72 Vulnerabilities Across Aruba AOS-8 and AOS-10**: Hewlett Packard Enterprise resolved 72 security flaws, including eight critical RCE and authentication bypass vulnerabilities (CVE-2026-79844 through CVE-2026-79851) impacting mobility conductors, controllers, and access points. [More info](https://www.securityweek.com/hpe-patches-dozens-of-critical-flaws-in-networking-products/)

- **Apple Releases macOS Tahoe 26.7.2 Patches**: Security advisories detail fixes for APFS, CoreGraphics, CoreAudio, and AppleAVD memory corruption flaws alongside Gatekeeper bypasses and sandbox escape vectors in macOS. [More info](https://seclists.org/fulldisclosure/2026/Oct/48)

- **Microsoft Issues Emergency .NET Patches for Brotli Vulnerability**: Out-of-band updates were pushed for .NET 8 through .NET 11 RC3 to patch CVE-2026-111497 in ASP.NET Core request decompression and HttpClient response processing. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-releases-emergency-net-patches-for-critical-brotli-flaw/)

- **Critical Wasmtime WebAssembly Runtime Sandbox Escapes (CVE-2026-115889, CVE-2026-115893)**: Wasmtime patched two Cranelift compiler vulnerabilities rated CVSS 9.9 involving value tracking overflows and ARM64 branch index truncations that permit host sandbox escapes. [More info](https://thehackernews.com/2026/10/two-critical-wasmtime-flaws-could-let.html)

## 🎯 Adversaries

- **CyberStrikeAI Deploying 44 Autonomous AI Agents in Japanese Attacks**: Threat actors are using CyberStrikeAI, an open-source framework leveraging 44 autonomous AI agents, to execute end-to-end multi-stage attacks including automated Japanese phishing, C2, and exfiltration. [More info](https://thehackernews.com/2026/10/cyberstrikeai-uses-44-ai-agents-to.html)

- **Email Spam Flooding Combined with Social Engineering via Microsoft Teams**: Attackers are flooding victim inboxes with spam before contacting them via Microsoft Teams external chat, posing as internal IT help desk staff to gain Quick Assist remote desktop access. [More info](https://www.helpnetsecurity.com/2026/10/27/microsoft-teams-social-engineering-fake-it-help-desk/)

- **Aokigahara Stealer Targets AI Tool Tokens and Developer Keyrings**: Check Point discovered Aokigahara, a Windows infostealer specifically engineered to harvest session tokens for Claude, ChatGPT Desktop, Codex, Cursor, GitHub Copilot, and Gemini CLI along with cloud SSH/Git credentials. [More info](https://www.darkreading.com/endpoint-security/aokigahara-stealer-developer-keyrings-ai-assistants)

- **Lazarus Group Abuses South Korean Initech Software in Operation FlashHole**: North Korean state-sponsored threat actors are exploiting INISAFE CrossWeb EX software vulnerabilities to sideload malicious DLLs in memory and deploy the Cubridge framework using post-quantum ML-KEM-1024 encryption for C2. [More info](https://thehackernews.com/2026/10/lazarus-abuses-south-korean-security.html)

- **Cyberattacks Hijack Dahua IP Cameras via Easy4IP Cloud Platform**: Ukraine's CERT-UA warned of active attacks brute-forcing device serial numbers and abusing legacy authentication bypass flaws (CVE-2021-33044, CVE-2021-33045) on Dahua IP cameras and NVRs to establish backdoor admin access. [More info](https://thehackernews.com/2026/10/attackers-hijack-dahua-ip-cameras-in.html)

- **LiteLLM Open-Source Framework Hit by Supply Chain Attack**: Maintainers of LiteLLM resolved a supply chain compromise after an exposed master API key allowed threat actors to push malicious package updates aimed at stealing environment variables and secrets. [More info](https://www.theregister.com/security/2026/10/26/litellm-supply-chain-attack-started-with-an-exposed-master-key/5305544)

## 📈 Trends

- **Huntress "Tragic Quadrant" Highlights RMM Software Abuse**: Huntress released a threat landscape report showing that legitimate Remote Monitoring and Management tool hijacking accounted for 45% of SMB endpoint incidents alongside AitM MFA bypasses and ClickFix attacks. [More info](https://www.bleepingcomputer.com/news/security/the-huntress-tragic-quadrant-ranking-threats-hitting-businesses-hardest/)

- **DNSFilter Launches LUMINATE Security Platform**: A new platform integrating DNS filtering, shadow AI controls, and remote workforce protection into a single console without requiring traditional VPN architectures. [More info](https://www.helpnetsecurity.com/2026/10/27/dnsfilter-luminate/)

- **FireMon Integrates Agentic AI into Network Policy Management**: FireMon announced FireMon Agentic AI to assist security teams with natural language policy queries, multi-vendor firewall access analysis, and Model Context Protocol integration. [More info](https://www.helpnetsecurity.com/2026/10/27/firemon-agentic-ai/)

- **ThreatAware Introduces Dimension for AI App Governance**: Dimension provides a governed workspace to build, test, and manage custom AI-generated security applications with built-in RBAC, isolated multi-tenancy, and API execution approvals. [More info](https://www.helpnetsecurity.com/2026/10/27/threataware-dimension-governed-workspace/)

## 💥 Breaches & Leaks

- **Developer Tool Provider Warp Discloses Data Incident**: Warp disclosed a security breach resulting from third-party vendor exploitation that exposed AI agent decision logs and user telemetry for ~1% of its user base. [More info](https://www.bleepingcomputer.com/news/security/warp-discloses-breach-exposing-ai-agent-logs-user-telemetry-data/)

- **French Energy Giant ENGIE Discloses Customer Data Breach**: Unauthorized actors accessed a partner marketing platform, exposing customer names, postal/email addresses, phone numbers, and energy metering IDs across France. [More info](https://www.bleepingcomputer.com/news/security/energy-giant-engie-discloses-data-breach-affecting-customers/)

---

[⬅ Back to Archive](https://pranakn.github.io)
