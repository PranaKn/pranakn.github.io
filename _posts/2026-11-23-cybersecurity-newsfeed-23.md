---
title: "Cybersecurity Newsfeed - 23/11/26"
date: 2026-11-22 09:00:00 -0300
categories: [News]
permalink: /posts/news-23-11-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-11-23.png
  alt: Cybersecurity Newsfeed - 23/11/26
---

# Cybersecurity Newsfeed

## 📅 23/11/26

## 🛡️ Vulnerabilities

- **Ghostscript "Upload2Shell" Sandbox Escape (CVE-2026-125396)**: Security researchers demonstrated a critical RCE flaw in Ghostscript versions prior to 10.08.0 that bypasses `-dSAFER` protections via crafted PostScript or PDF uploads. Organizations using Ghostscript in CMS or image-processing pipelines must upgrade to 10.08.0 immediately to prevent server command execution. [More info](https://thehackernews.com/2026/11/researchers-demonstrate-ghostscript.html)

- **Critical GnuPG Made Easy Flaw (CVE-2026-129975)**: GnuPG developers released an urgent patch for GPGME after discovering that malicious OpenPGP keys can trigger unintended behavior during processing. Because GPGME underpins numerous Linux email clients, package managers, and Flatpak apps, administrators should deploy updates immediately. [More info](https://thehackernews.com/2026/11/gnupg-warns-critical-gpgme-flaw-could.html)

- **CISA Adds Four Flaws to KEV Catalog**: CISA added four actively exploited bugs to its catalog, including a Cisco Expressway hard-coded credentials RCE (CVE-2026-76466), a VMware vCenter auth bypass exploited by ARMORY CASTLE (CVE-2026-123890), an Apache Roller pre-auth deserialization bug (CVE-2026-129448), and an SAP NetWeaver flaw (CVE-2025-42884). [More info](https://www.cisa.gov/news-events/alerts/2026/11/20/cisa-adds-four-known-exploited-vulnerabilities-catalog)

- **Linux KVM Hypervisor VM Escape (CVE-2026-99312)**: A high-severity use-after-free vulnerability in the Linux KVM hypervisor allows malicious guest VMs on AMD processors with nested virtualization to read or overwrite host RAM. Researchers demonstrated extracting 127 GB of host memory on cloud servers; operators should patch kernels or disable nested virtualization. [More info](https://thehackernews.com/2026/11/new-linux-kvm-flaw-cve-2026-99312-lets.html)

## 🎯 Adversaries

- **GL.iNet GoodCloud Flaw Exploited for Router Implants**: Threat actors exploited a command injection bug in `gl-sdk4-cloud` to establish netcat reverse shells and deploy masqueraded `crond` implants on enrolled routers and KVM devices. GL.iNet released emergency updates and advised administrators to inspect processes and reset affected hardware. [More info](https://www.bleepingcomputer.com/news/security/hackers-exploit-glinet-cloud-flaw-to-infect-routers-kvm-devices/)

- **Autonomous AI Framework Weaponized for Zero-Day Exploits**: Amazon Threat Intelligence and Gambit Security reported that threat actors—including a suspected Chinese-nexus group—used the open-source AI pentesting tool Cairn to autonomously discover and exploit a zero-day in medical imaging software, breaching university and retail networks within minutes. [More info](https://securityaffairs.com/203664/ai/cairn-ai-framework-used-in-autonomous-zero-day-exploitation.html)

- **BadBox 3.0 Botnet Hits Record 40 Billion Daily Ad Requests**: Human Security revealed that the resurgent BadBox 3.0 botnet has infected uncertified Android TV streaming boxes to generate 40 billion daily bid requests, accounting for over 4% of connected TV traffic while turning victim networks into residential proxies. [More info](https://www.bleepingcomputer.com/news/security/badbox-30-botnet-returns-with-record-breaking-40-billion-daily-ad-requests/)

- **Email Bombing Paired with Microsoft Teams Vishing**: Fortra warned of an escalating social engineering campaign where attackers flood corporate inboxes with newsletter spam before calling victims on Teams posing as IT support to trick them into granting remote access or running malicious commands. [More info](https://hackread.com/hackers-email-bombing-it-support-microsoft-teams/)

- **Fake GTA VI Streaming Client Delivers Rust Stealer**: Bitdefender uncovered a ClickFix campaign luring PC gamers with a fake Grand Theft Auto VI streaming client that instructs users to execute a PowerShell command via `Win+R`, sideloading the `PhotoCache.exe` Rust infostealer to harvest credentials, wallets, and API keys. [More info](https://hackread.com/fake-gta-vi-streaming-client-malware-windows-pc/)

- **Bazuka Android Malware Integrates C2 LLM Agents**: ThreatFabric discovered Bazuka, an Android malware framework using fake overlays and Accessibility Services to enable Wireless Debugging and disable Google Play Protect. Notably, it integrates LLM agents in its C2 panel to analyze stolen data and prioritize high-value victims. [More info](https://thehackernews.com/2026/11/bazuka-android-malware-uses-fake-screen.html)

## 📈 Trends

- **Spreadsheet Password Tracking Leaves Firms Exposed**: Citing data showing credential abuse drives 13% of investigated incidents, NordPass Business warns that storing corporate passwords in unsecured spreadsheets eliminates audit trails and visibility, urging adoption of enterprise password managers with MFA and role-based access. [More info](https://www.bleepingcomputer.com/news/security/still-tracking-company-passwords-in-spreadsheets-youre-flying-blind/)

- **SOCs Accelerate Shift Toward Autonomous AI Agents**: An Andreessen Horowitz (a16z) survey of enterprise CISOs found that 36% already allow AI agents to execute autonomous actions on low-risk alerts, reflecting a broader push to combat alert fatigue and match the speed of AI-driven attacks using deterministic guardrails. [More info](https://thehackernews.com/2026/11/the-path-to-ai-autonomy-in-soc.html)

## 💥 Breaches & Leaks

- **Cleverbridge Breach Exposes Customer Payment Cards**: E-commerce platform Cleverbridge disclosed a security breach after attackers compromised its systems and stole full customer credit card numbers and CVVs. While other PII was reportedly untouched, affected buyers face high card-not-present fraud risks and are urged to replace cards. [More info](https://www.bleepingcomputer.com/news/security/cleverbridge-warns-hackers-stole-credit-card-numbers-cvvs-in-data-breach/)

- **USDA Cyber Incident Disrupts Farmer Payment Systems**: A cybersecurity incident at the U.S. Department of Agriculture forced IT staff to take multiple applications offline, disrupting employee access to loan and agricultural aid systems across the Farm Service Agency and Natural Resources Conservation Service. [More info](https://hackread.com/usda-cyber-incident-disrupts-farmer-payments/)

- **OpenRouter Off-Boards Providers Over Prompt Theft**: AI routing platform OpenRouter removed three inference providers and revoked Zero Data Retention status from 125 endpoints after compromised credentials enabled months-long harvesting of stored user prompts, API keys, and canary tokens across MiniMax, GLM, and Kimi models. [More info](https://thehackernews.com/2026/11/openrouter-drops-3-providers-after.html)

- **Rackspace Spot Breach Exposes Kubernetes Secrets**: Rackspace confirmed attackers used leaked credentials to access its Spot managed Kubernetes platform, deploying unauthorized pods (`i1`, `glm-`, `probe`) and reading customer Kubernetes Secrets. Rackspace revoked tokens and purged malicious containers, urging customers to rotate credentials immediately. [More info](https://www.bleepingcomputer.com/news/security/rackspace-spot-breach-let-hackers-access-customer-kubernetes-secrets/)

- **N-able Hosted Cloud Breach Triggers Global Service Outage**: IT management provider N-able confirmed that unauthorized access to a Hosted Cloud server forced it to disable admin panels, APIs, and quarantine controls across its Mail Assure and SpamExperts platforms during remediation, though tenant mailboxes were reportedly unaffected. [More info](https://www.bleepingcomputer.com/news/microsoft/n-able-says-recent-security-breach-led-to-major-service-outage/)

---

[⬅ Back to Archive](https://pranakn.github.io)
