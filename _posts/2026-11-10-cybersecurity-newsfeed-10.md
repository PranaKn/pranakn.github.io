---
title: "Cybersecurity Newsfeed - 10/11/26"
date: 2026-11-09 09:00:00 -0300
categories: [News]
permalink: /posts/news-10-11-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-11-10.png
  alt: Cybersecurity Newsfeed - 10/11/26
---

# Cybersecurity Newsfeed

## 📅 10/11/26

## 🛡️ Vulnerabilities

- **GPUstack Authentication Bypass (CVE-2026-102895)**: CISA added this critical vulnerability (CWE-287, CWE-290, CWE-346) to its KEV catalog following active exploitation. Affecting GPUstack versions prior to 2.2.0, the flaw allows unauthenticated remote attackers to bypass access controls, spoof identities, and achieve complete system compromise. Security teams must patch by November 12, 2026. [More info](https://www.cisa.gov/known-exploited-vulnerabilities-catalog?search_api_fulltext=CVE-2026-102895)

- **OpenSSH "SSHole" Authentication Bypass (CVE-2026-123158)**: CISA added CVE-2026-123158 to the KEV catalog as threat actors actively exploit it in the wild. The flaw (CWE-394) affects OpenSSH on Linux distributions using the musl C library without PAM (e.g., Alpine Linux). Unauthenticated attackers can supply long passwords exceeding 1024 bytes to bypass authentication on password-disabled accounts, drop C2 implants like TAC Agent, and gain root access. Organizations are advised to upgrade to OpenSSH 10.6p2 or patched distribution packages immediately. [More info](https://www.cisa.gov/known-exploited-vulnerabilities-catalog?search_api_fulltext=CVE-2026-123158) | [More info](https://www.bleepingcomputer.com/news/security/hackers-exploit-sshole-openssh-flaw-to-breach-linux-systems/)

- **SignalWire FreeSWITCH Remote Code Execution (CVE-2026-116779)**: CISA added CVE-2026-116779 to its KEV catalog following active exploitation. The flaw stems from improper input neutralization (CWE-77, CWE-78, CWE-749) in FreeSWITCH version 1.11.2 and earlier within `mod_sofia` SIP MESSAGE handling. Unauthenticated remote attackers sending SIP messages starting with `api+` can execute arbitrary system commands. Defenders should upgrade to version 1.11.3 or disable inbound chat routing. [More info](https://www.cisa.gov/known-exploited-vulnerabilities-catalog?search_api_fulltext=CVE-2026-116779)

- **Web3Auth Integration Vulnerability**: Keplr wallet users logging in via Google or Apple single sign-on were targeted in unauthorized cryptocurrency thefts due to a flaw in Web3Auth. In response, Web3Auth initiated emergency asset transfers to recovery addresses for protection, while Keplr temporarily disabled social sign-in features during investigation. [More info](https://thehackernews.com/2026/11/web3auth-flaw-exploited-to-steal-keplr.html)

## 🎯 Adversaries

- **Iranian Hackers Target Supermarket Refrigeration Systems**: French authorities officially attributed cyberattacks against European supermarket cold-chain systems to Iranian state-backed threat actors. Attackers tampered with temperature controls (raising them up to 50°C) to spoil food, spark electrical fires, and disrupt emergency blood storage facilities. [More info](https://www.bleepingcomputer.com/news/security/france-blames-iranian-hackers-for-supermarket-attacks-that-sparked-fires/)

- **Russian Cloud Provider Beget Suffers Wiper Attack**: Russian cloud provider Beget was forced to rebuild its cloud infrastructure from scratch after threat actors deployed data-wiping malware across its network, destroying VPS host data and backups aimed at maximum operational disruption. [More info](https://www.bleepingcomputer.com/news/security/russian-cloud-firm-beget-rebuilds-from-scratch-after-data-wiper-attack/)

- **Cerber Ransomware Targets Exposed Synology NAS**: Kaspersky researchers documented active Cerber (C3RB3R) ransomware campaigns exploiting known vulnerabilities and weak credentials on public-facing Synology DiskStation Manager (DSM) instances to encrypt files and demand cryptocurrency payments. [More info](https://www.kaspersky.com/blog/synology-c3rb3r-attack/56663/)

- **Bitter APT Group Deploys PapRAT Backdoor**: South Asian organizations are being targeted by the Bitter cyberespionage group (APT-C-08) using a new backdoor named PapRAT. Delivered via malicious VHDX images and WebDAV shortcuts, the malware uses C++ and Rust variants to support full remote access, directory enumeration, and arbitrary payload execution. [More info](https://thehackernews.com/2026/11/bitter-hackers-deploy-new-paprat.html)

- **Taiwan-Based Hacker Uses Custom "BOSSAI" AI Framework**: Threat actors deployed a custom framework of twelve local, uncensored AI agents to conduct automated targeting, vulnerability scanning, and data extraction against Taipei emergency management and medical infrastructure. [More info](https://thehackernews.com/2026/11/taiwan-based-hacker-used-bossai-ai.html)

## 📈 Trends

- **"Operation Snowball" Autonomous AI Telecom Cyberattack**: Researchers documented a two-week cyberattack on a European telecommunications provider driven by an autonomous, jailbroken AI agent. Believed to originate from a Chinese operator, the AI agent independently performed vulnerability scans, adapted to security blocks, and authored custom tunneling tools without human intervention. [More info](https://www.infosecurity-magazine.com/news/operation-snowball-ai-telecom/)

- **AI Automation Reshaping GRC Roles**: Governance, Risk, and Compliance (GRC) roles are shifting as AI tools automate routine control testing and evidence collection. Experts warn that ignoring AI adoption poses a greater risk than AI itself, advising managers to transition toward supervising software agents and managing AI permissions. [More info](https://www.bleepingcomputer.com/news/security/the-biggest-threat-to-your-grc-job-isnt-ai-its-ignoring-ai/)

- **Gaps in Telco Data Breach Reporting vs. Actual Risk**: Recent data breach incidents involving New Zealand telecom providers (Compass Communications and Spark) highlight discrepancies between headline file numbers and true customer risk, emphasizing the need for granular reporting on specific data categories rather than overall file counts. [More info](https://hackread.com/inside-new-zealands-telco-data-breaches/)

## 💥 Breaches & Leaks

- **Qubole IAM Credential Compromise Exploits Cross-Account Trust**: Threat actors compromised IAM credentials linked to Qubole's AWS account, capitalizing on trusted cross-account integrations to access customer cloud environments and exfiltrate sensitive secrets. Security teams are advised to audit cross-account roles and enforce least privilege. [More info](https://www.theregister.com/security/2026/11/09/attackers-backdoor-trusted-aws-integrations-to-steal-secrets/5308553)

- **Malicious npm and Desktop Releases Target Ethersphere**: Attackers used stolen CI credentials to publish tampered versions of Ethersphere's `bee-js` package (v13.3.0) and Swarm Desktop application (v0.56.2). The releases contained wallet-stealing malware to exfiltrate seed phrases and crypto credentials before maintainers revoked credentials and pulled the packages. [More info](https://thehackernews.com/2026/11/hackers-compromise-etherspheres-bee-js.html)

- **GitHub Actions Supply-Chain Attack Hits Enterprise Repos**: A supply-chain campaign compromised tens of thousands of GitHub repositories, including projects owned by companies such as Uber. Injected GitHub Actions workflows scanned code files and commit histories to extract cloud and AI API credentials. [More info](https://www.infosecurity-magazine.com/news/supply-chain-attack-thousands/)

- **Binance Denies Alleged 335M User Record Data Breach**: Binance refuted claims by threat actor ShinyHunters regarding a breach of 335 million records, confirming after investigation that sample data sets were scraped/recycled from old third-party dumps and no core systems were accessed. [More info](https://www.bleepingcomputer.com/news/security/binance-denies-data-breach-after-alleged-shinyhunters-claims/)

## 📚 Others

- **US FinCEN Bans Transactions with MEXC Global**: FinCEN prohibited financial transactions with cryptocurrency exchange MEXC Global following regulatory findings of over $1 billion in transfers with sanctioned Iranian entities, subjecting violators to secondary sanctions. [More info](https://www.bleepingcomputer.com/news/security/us-bans-mexc-crypto-exchange-over-sanctions-evasion-cybercrime-links/)

- **Ukraine Dismantles €4.3M Crypto Scam Call-Center Network**: Ukrainian authorities arrested four suspects and dismantled a fraudulent call-center network responsible for stealing €4.3 million from European victims using fake crypto investment platforms and "pig-butchering" tactics. [More info](https://www.bleepingcomputer.com/news/security/ukraine-dismantles-crypto-scam-network-that-stole-43-million/)

- **Technical Overview of JADX Android Decompiler**: A technical guide covers JADX, an open-source Android decompiler operating on Java 11+ used by malware analysts to decode Dalvik bytecode, AndroidManifest files, and app resources from APK, DEX, and AAB packages into readable Java code. [More info](https://www.darknet.org.uk/2026/11/jadx-decompile-android-apk-to-java/)

--

[⬅ Back to Archive](https://pranakn.github.io)
