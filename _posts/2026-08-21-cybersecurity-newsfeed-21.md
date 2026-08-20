---
title: "Cybersecurity Newsfeed - 21/08/26"
date: 2026-08-20 09:00:00 -0300
categories: [News]
permalink: /posts/news-21-08-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-08-21.png
  alt: Cybersecurity Newsfeed - 21/08/26
---

# Cybersecurity Newsfeed

## 📅 21/08/26

## 🛡️ Vulnerabilities

- **MLflow SSRF Flaw Under Active Attack (CVE-2026-64849)**: CISA added a critical DNS-rebinding server-side request forgery (SSRF) flaw in MLflow's unauthenticated model-registry webhooks API to its KEV catalog. Remote attackers are scanning exposed instances to query internal endpoints and exfiltrate cloud IAM credentials from metadata services like AWS IMDS. [More info](https://www.bleepingcomputer.com/news/security/cisa-warns-of-hackers-exploiting-critical-mlflow-vulnerability/) | [More info](https://www.cisa.gov/news-events/alerts/2026/08/20/cisa-adds-two-known-exploited-vulnerabilities-catalog)

- **Critical Unauthenticated RCE in Elementor Pro (CVE-2026-32475)**: A CVSS 9.0 flaw in the Elementor Pro WordPress plugin (versions prior to 4.2.2) stems from inconsistent early-exit logic in its Forms module file upload processing. Unauthenticated attackers can bypass file extension blocklists using multi-part requests to write arbitrary PHP scripts into public directories for remote code execution. [More info](https://www.bleepingcomputer.com/news/security/critical-elementor-pro-bug-exposes-wordpress-sites-to-rce-attacks/) | [More info](https://thehackernews.com/2026/08/elementor-pro-flaw-could-let.html)

- **Auth Bypass and Memory Overflow in Citrix NetScaler (CVE-2026-19490 / CVE-2026-19489)**: Citrix issued urgent fixes for NetScaler ADC and Gateway. CVE-2026-19490 (CVSS 9.3) allows unauthenticated access on AAA virtual servers/Gateways with SAML enabled, while CVE-2026-19489 (CVSS 8.8) causes memory overflow and DoS condition via SIP ALG configurations. [More info](https://thehackernews.com/2026/08/critical-netscaler-flaw-can-bypass.html)

- **JFrog Artifactory Supply Chain Flaws**: Oligo Security uncovered two flaws in JFrog Artifactory: CVE-2026-69106 (CVSS 8.8), which abuses `X-Orig-Client-Uri` headers to enable cross-user cache poisoning, and CVE-2026-65922 (CVSS 5.4), which lets authenticated users bypass controls via REST APIs to alter metadata, npm signing keys, and OCI referrers. [More info](https://www.infosecurity-magazine.com/news/jfrog-flaws-software-supply-chain/)

- **VM Escape and RCE in Node.js isolated-vm (GHSA-864f-rcv7-6rh4)**: A type confusion bug during object serialization in the C++ binding layer of `isolated-vm` allows sandboxed guest JavaScript code to corrupt host process memory. Attackers can leverage this to break out of Google V8 isolation instances and execute host code. [More info](https://thehackernews.com/2026/08/isolated-vm-flaw-lets-sandboxed.html)

- **Active Exploitation of Zimbra SNMP Flaw (CVE-2026-73570)**: CERT Polska warned that threat actors are actively exploiting a command injection vulnerability (CVSS 8.9) in Zimbra Collaboration Suite versions prior to 10.1.20 when `zimbra-snmp` is enabled. Crafting specific SMTP requests triggers OS command execution under the Zimbra context. [More info](https://thehackernews.com/2026/08/attackers-exploit-zimbra-snmp-flaw-for.html)

- **Cisco ASA/FTD Denial of Service Added to KEV (CVE-2026-20349)**: CISA updated its KEV catalog to mandate remediation for a Cisco Adaptive Security Appliance and Firepower Threat Defense DoS bug following active exploitation in enterprise networks. [More info](https://www.cisa.gov/news-events/alerts/2026/08/20/cisa-adds-two-known-exploited-vulnerabilities-catalog)

## 🎯 Adversaries

- **Russian Espionage Clusters Target Western Defense & OAuth (UNC6293/UNC5976/UNC7005)**: Google TIG detailed Russian threat activity abusing Google OAuth flows, WhatsApp device-linking prompts, and custom tools (HEADRUSH, ChocoShell, CornFlake RAT) to target government and academic sectors. The CaptiveCrunch campaign also compromised MSPs and hotel Wi-Fi to intercept session tokens via DNS poisoning. [More info](https://thehackernews.com/2026/08/suspected-russian-hackers-abuse-google.html)

- **UAT-10147 Deploys SPECTRE Implant and Integrates Agentic AI**: Chinese-speaking actor UAT-10147 was observed deploying "SPECTRE"—a cross-platform C backdoor featuring process hollowing, BYOVD EDR unhooking on Windows, and a custom Linux kernel rootkit. Simultaneously, the group is integrating agentic AI frameworks (DeepAudit, PentestGPT) to automate post-compromise exploitation and privilege escalation. [More info](https://blog.talosintelligence.com/uat-10147-deploys-spectre-a-cross-platform-implant-with-linux-rootkit-and-byovd-capabilities/) | [More info](https://blog.talosintelligence.com/uat-10147-chinese-speaking-adversary-integrates-agentic-ai-into-post-compromise-operations/)

- **Manic Android Malware Uses Mesh Relays for Offline Exfiltration**: ThreatFabric uncovered "Manic," a new banking malware targeting Ukrainian users that abuses Accessibility Services to log UI inputs and capture screen PINs. Crucially, Manic uses Wi-Fi Direct, Bluetooth RFCOMM, and BLE GATT to pass stolen data up to four hops across nearby infected devices when direct internet connectivity is lost. [More info](https://securityaffairs.com/197570/malware/manic-the-android-malware-that-exfiltrates-data-even-when-the-phone-is-offline.html) | [More info](https://www.bleepingcomputer.com/news/security/new-manic-android-malware-can-exfiltrate-data-through-nearby-devices/)

- **ToxicPanda 2.0 and GoldDigger Expand Mobile Banking Targets**: ToxicPanda 2.0 updated its operations to target 140 banking and crypto applications globally, abusing Accessibility Services to enable ADB Wireless Debugging and run elevated shell commands. Meanwhile, GoldDigger campaigns in the UK and South Africa rely on "dpt-shell" packing to conduct automated real-time fraud. [More info](https://thehackernews.com/2026/08/toxicpanda-20-and-golddigger-expand.html) | [More info](https://www.infosecurity-magazine.com/news/updated-toxicpanda-140-banking/)

- **Fake Google Gemini Installer Delivers Vidar Infostealer**: Attackers engineered a social engineering campaign routing users via Google Colab pages to a fake Windows Software Hub. The malicious `Download_Google_Gemini_For_Windows.exe` installer drops a Go-based Vidar variant that steals browser credentials and exfiltrates data through Telegram. [More info](https://www.helpnetsecurity.com/2026/08/20/fake-google-gemini-installer-vidar-infostealer/)

## 📈 Trends

- **Poisoned Rust Crates Target Build Pipelines (arrayref)**: A supply-chain compromise of the popular `arrayref` crate maintainer account led to malicious updates for `arrayref` (0.3.10), `append-only-vec` (0.1.9), and `internment` (0.8.7). The packages injected a build-time dependency on typosquatted `proc-macro1` to drop cross-platform infostealers during `cargo build` compilation steps before being yanked by Rust admins. [More info](https://thehackernews.com/2026/08/rust-supply-chain-attack-puts-build.html) | [More info](https://www.bleepingcomputer.com/news/security/hackers-poison-arrayref-rust-crate-to-push-infostealer-malware/)

- **ThreatsDay Roundup: Gogs 10.0 RCE, n8n, and EDR Bypasses**: The latest security roundup covers critical vulnerabilities including a path-traversal RCE in Gogs (CVE-2026-52813), prototype pollution in n8n (CVE-2026-33696), weaponization of Microsoft Defender's `BTR.sys` driver for EDR bypass, and DoJ indictments targeting 17 Iranian actors. [More info](https://thehackernews.com/2026/08/threatsday-gogs-100-rce-n8n-workflow-to.html)

- **"Zombie Card" Attack Bypasses Expired Contactless Cards**: UMass Amherst researchers demonstrated a flaw in Visa Kernel 3 architecture where NFC relays can modify the unauthenticated Application Expiration Date (tag 5F24) while preserving Track 2 data, tricking terminals and issuers into approving expired physical payment cards. [More info](https://thehackernews.com/2026/08/zombie-card-attack-can-revive-expired.html)

## 📚 Others

- **CUSTODY Framework Released to Restrain Autonomous AI Agents**: Cybersecurity expert Jake Williams published "CUSTODY," an open-source framework outlining condition-of-release rules, temporary authority constraints, and stop triggers to prevent enterprise AI agents from performing unmonitored external network operations or reward-hacking. [More info](https://www.darkreading.com/perimeter/new-custody-framework-constrains-ai-agents-inside-network)

---

[⬅ Back to Archive](https://pranakn.github.io)
