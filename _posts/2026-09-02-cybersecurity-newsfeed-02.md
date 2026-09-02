---
title: "Cybersecurity Newsfeed - 02/09/26"
date: 2026-09-01 09:00:00 -0300
categories: [News]
permalink: /posts/news-02-09-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-09-02.png
  alt: Cybersecurity Newsfeed - 02/09/26
---

# Cybersecurity Newsfeed

## 📅 02/09/26

## 🛡️ Vulnerabilities

- **Active Exploitation of Critical JFrog Artifactory Flaw (CVE-2026-82329)**: Attackers are actively exploiting an authentication bypass flaw in self-managed JFrog Artifactory instances (versions prior to 7.161.20). Caused by improper join key handling in JFrog Access, unauthenticated remote attackers can forge administrative tokens to enumerate users, credential sets, and federated topologies, posing severe supply chain risks. [More info](https://www.darkreading.com/application-security/attackers-pounce-critical-artifactory-flaw-disclosure) | [More info](https://thehackernews.com/2026/09/attackers-exploit-critical-jfrog.html)

- **Critical Langflow RCE Flaw Exploited (CVE-2026-0768)**: A critical remote code execution vulnerability (CVSS 9.8) in Langflow—an open-source framework for building AI agents—is seeing active exploitation. Unauthenticated attackers are executing arbitrary code on exposed instances to harvest cloud API keys and perform lateral movement. [More info](https://www.darkreading.com/vulnerabilities-threats/critical-langflow-flaw-exploited-attacks-rise)

- **22,000 Microsoft Exchange Servers Unpatched**: Tens of thousands of internet-exposed Microsoft Exchange servers remain vulnerable to remote code execution and session hijacking due to missing Cumulative Updates and security patches. Attackers are actively scanning to breach mail environments. [More info](https://www.bleepingcomputer.com/news/security/nearly-22-000-microsoft-exchange-servers-vulnerable-to-hijack-attacks/)

- **PaperCut Zero-Days Abused in Data Exfiltration (CVE-2026-81578 & CVE-2026-82078)**: Adversaries are chaining recently patched authentication bypass and RCE zero-days in PaperCut NG and MF to breach internet-facing servers and directly exfiltrate internal database tables. [More info](https://www.bleepingcomputer.com/news/security/recently-patched-papercut-zero-days-used-in-data-theft-attacks/)

## 🎯 Adversaries

- **Silver Fox Impersonates Major Brands**: Microsoft Defender Experts is tracking a Silver Fox (Yinhu) campaign delivering malicious installer archives via counterfeit sites masquerading as Razer, Microsoft Edge, and Kaspersky to target Chinese-speaking users across tech, healthcare, and manufacturing sectors. [More info](https://www.microsoft.com/en-us/security/blog/2026/09/01/counterfeit-installers-system-compromise-tracking-deceptive-software-download-campaign/)

- **Breeze Comet Targets Brazilian Financial Sectors**: Financially motivated actor Breeze Comet (formerly UNC5669) is targeting internal payment systems (Pix, STR, Boleto) in Brazil using voice phishing, LLM-generated scripts, and custom tools like COBALTSPIN, LIGHTPAINT, and MILDFROST to execute unauthorized transfers. [More info](https://thehackernews.com/2026/09/breeze-comet-executes-hundreds-of.html)

- **Iranian Group Nimbus Manticore Targets Developers**: Poseurs pretending to be recruiters on LinkedIn are delivering trojanized npm packages (`colorized_terminal`, `pretty-log`) to infect Windows, Linux, and macOS systems with NodeRabbit and PollCat RATs, harvesting credentials from Git and VS Code. [More info](https://thehackernews.com/2026/09/iranian-hackers-pose-as-recruiters-to.html)

- **Physical ATM Jackpotting Attacks in US**: Five Venezuelan nationals pleaded guilty to conspiracy following attempts to physically access Kansas ATMs and install specialized malware like Ploutus to force machines into dispensing cash. [More info](https://www.bleepingcomputer.com/news/security/five-venezuelans-plead-guilty-to-atm-jackpotting-attacks-in-us/)

- **Steganography Campaign Drops Reverse Tunnels**: AClickFix campaign uses hidden code inside PNG image files executed via PowerShell to install a custom reverse tunnel on victim machines, circumventing firewalls and NAT configurations. [More info](https://www.theregister.com/security/2026/08/31/attack-hides-malware-in-pngs-and-drops-custom-reverse-tunnel-on-victims-machines/5293480)

## 📈 Trends

- **Ransomware Groups Recruit Corporate Insiders Directly**: Driven by tighter perimeter defenses and MFA implementation, ransomware operators are shifting tactics to directly offer monetary incentives to corporate employees for access and credentials. [More info](https://www.darkreading.com/cyber-risk/stronger-security-drives-ransomware-groups-to-recruit-from-within)

- **Edge Security Limitations Against Advanced Sessions**: Traditional perimeter controls like WAFs and CDNs frequently miss high-risk sessions due to attackers using residential proxies and VPNs. Real-time infrastructure enrichment is becoming crucial to flag anonymized threats. [More info](https://www.bleepingcomputer.com/news/security/why-even-the-best-edge-security-still-misses-high-risk-sessions/)

- **OpenClaw 2.0 Draws Criticism Over Ecosystem Safety**: Security experts warn that OpenClaw 2.0 fails to address core supply chain vulnerabilities like dependency confusion and unvetted third-party packages despite repository management updates. [More info](https://www.theregister.com/ai-and-ml/2026/08/31/openclaw-20-pours-glitter-on-slow-burning-security-dumpster-fire/5293492)

## 💥 Breaches & Leaks

- **Aesto Health Data Breach Impacts 9.5M Patients**: A major breach of Aesto Health's AWS infrastructure exposed the protected health information (PHI), financial details, and Social Security numbers of over 9.5 million patients across 29 healthcare entity clients. [More info](https://www.bleepingcomputer.com/news/security/aesto-health-says-data-breach-affects-over-95-million-patients/)

- **Novocure Discloses Breach Impacting Cancer Patients**: Medical tech firm Novocure suffered a network intrusion exposing the personal, insurance, and medical data of 1,438 cancer patients, though operational device systems remained unaffected. [More info](https://www.bleepingcomputer.com/news/security/novocure-data-breach-affects-more-than-1-400-cancer-patients/)

## 🔗 Supply Chain & Web

- **Packagist PHP Packages Target Unpatched iOS Devices**: Thirteen malicious PHP packages were removed from Packagist after being found targeting connected iOS devices with legacy WebKit exploits to steal cryptocurrency wallet seeds and private keys. [More info](https://thehackernews.com/2026/09/13-malicious-packagist-packages-target.html)

- **BGP Hijacking Hijacks Softaculous Updates**: Threat actors executed a BGP hijacking attack against Hetzner-hosted routes to push a rogue Virtualizor update that installed a persistent backdoor service (`java-jre-update.service`). [More info](https://www.bleepingcomputer.com/news/security/hackers-push-malicious-virtualizor-update-in-bgp-hijacking-attack/)

## 💰 Web3 & Crypto

- **Cronos Blockchain Halts and Restarts After $74M Exploit**: Cronos validators executed an emergency chain rollback to reverse a price-manipulation attack on Tectonic lending protocol where an attacker inflated TONIC token prices to borrow millions in collateral. [More info](https://www.bleepingcomputer.com/news/security/cronos-blockchain-restarts-after-74-million-tectonic-exploit/)

---

[⬅ Back to Archive](https://pranakn.github.io)
