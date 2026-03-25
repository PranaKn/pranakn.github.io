---
title: "Cybersecurity Newsfeed - 25/03/26"
date: 2026-03-24 09:00:00 -0300
categories: [News]
permalink: /posts/news-25-03/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware, supply-chain]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-03-25.png
  alt: Cybersecurity Newsfeed - 25/03/26
---

# Cybersecurity Newsfeed

## 📅 25/03/26

## 🛡️ Vulnerabilities

- **Critical VPN Session Management Flaw (577436)**: CERT/CC issued an advisory for a critical flaw in multiple VPN implementations involving improper handling of session termination. Attackers can maintain persistent access or hijack active sessions. Organizations are urged to apply vendor patches and audit session logs. [More info](https://kb.cert.org/vuls/id/577436)

- **PTC Windchill & FlexPLM RCE (CVE-2026-2580)**: PTC issued an urgent warning regarding a critical remote code execution vulnerability. The flaw allows unauthenticated attackers to execute arbitrary code with elevated privileges, potentially leading to full system compromise. [More info](https://www.bleepingcomputer.com/news/security/ptc-warns-of-imminent-threat-from-critical-windchill-flexplm-rce-bug/)

- **NetScaler ADC and Gateway (CVE-2026-3055)**: Cloud Software Group released critical updates to address a high-severity vulnerability allowing unauthorized data disclosure or DoS conditions. Administrators should apply patches immediately to protect remote access infrastructure. [More info](https://www.helpnetsecurity.com/2026/03/24/netscaler-adc-gateway-cve-2026-3055/)

- **Citrix NetScaler System Access Patches**: Citrix issued an urgent patch for vulnerabilities affecting ADC and Gateway components that could lead to unauthorized system access. These devices are prime targets for initial access brokers. [More info](https://www.infosecurity-magazine.com/news/citrix-patch-netscaler/)

## 🎯 Adversaries

- **Silver Fox Conducts Dual-Purpose Ops**: A new threat actor is conducting hybrid operations involving both traditional espionage and financial gain. The group targets government and financial institutions using custom malware and living-off-the-land techniques. [More info](https://www.infosecurity-magazine.com/news/silver-fox-cyber-dual-espionage/)

- **North Korean Actors Abuse VS Code Auto-Run**: Threat actors are exploiting the "auto-run" feature in Visual Studio Code to distribute StoatWaffle malware. Opening malicious project folders triggers automated tasks that execute second-stage payloads. [More info](https://securityaffairs.com/189880/security-u-s-cisa-adds-a-flaw-in-wing-ftp-server-to-its-known-exploited-vulnerabilities-catalog.html)

- **TeamPCP Hits LiteLLM in Supply Chain Attack**: The popular LiteLLM PyPI package was compromised to exfiltrate environment variables and API keys from developers. Users are urged to rotate credentials and check installed versions. [More info](https://www.bleepingcomputer.com/news/security/popular-litellm-pypi-package-compromised-in-teampcp-supply-chain-attack/)

- **TeamPCP Targets Checkmarx & GitHub Actions**: Attackers exploited misconfigured CI/CD pipelines and compromised GitHub Actions to inject malicious code into development projects, focusing on exfiltrating secrets. [More info](https://thehackernews.com/2026/03/teampcp-hacks-checkmarx-github-actions/)

- **Russian Initial Access Broker Identified**: A major supplier of network credentials has been linked to various cybercriminal organizations, providing "ready-to-use" entry points into global enterprise networks via phishing and credential stuffing. [More info](https://www.infosecurity-magazine.com/news/russian-initial-access-broker/)

## 📈 Trends

- **Mandiant: Global Dwell Time Hits Record Low**: Global median dwell time has reached a record low, indicating improved detection capabilities and a shift toward more disruptive, rapid-impact operations like ransomware. [More info](https://taosecurity.blogspot.com/2026/03/mandiant-global-median-dwell-time.html)

- **150% Surge in DDoS Attacks**: The Gcore Radar report highlights a massive year-on-year spike in DDoS activity, driven by cheap booter services and complex multi-vector botnets targeting gaming and finance. [More info](https://hackread.com/gcore-radar-report-reveals-150-surge-in-ddos-attacks-year-on-year/)

- **Fake Resumes Used for Network Infiltration**: Cybercriminals are embedding malware in fake resumes distributed via LinkedIn. These documents target HR departments to install infostealers or remote access trojans. [More info](https://thehackernews.com/2026/03/hackers-use-fake-resumes-to-steal.html)

- **"Ghost" Campaign Pollutes npm Registry**: Hundreds of malicious packages are using typosquatting and "starjacking" to trick developers into installing persistent backdoors and stealing sensitive environment variables. [More info](https://www.infosecurity-magazine.com/news/npm-ghost-campaign-fake-install/)

- **FCC Bans Non-US Manufactured Routers**: Citing national security risks, the FCC has implemented a ban on new routers made outside the USA to prevent potential backdoors or vulnerabilities exploitable by adversarial states. [More info](https://www.bleepingcomputer.com/news/security/fcc-bans-new-routers-made-outside-the-usa-over-security-risks/)

- **NCSC Urges "Vibe Coding" for Security**: At RSAC, the UK NCSC encouraged an agile, culturally aware approach to security, arguing that rigid frameworks often fail to keep pace with evolving modern threats. [More info](https://www.infosecurity-magazine.com/news/rsac-uk-ncsc-urges-vibe-coding/)

## 💥 Breaches & Leaks

- **HackerOne Discloses Breach via Third-Party**: Employee data, including SSNs, was exposed following a cyberattack on Navia Benefit Solutions. HackerOne clarified its core platform and bug bounty data remain secure. [More info](https://www.bleepingcomputer.com/news/security/hackerone-discloses-employee-data-breach-after-navia-hack/)

- **OVHcloud Denies 590TB Data Breach Claims**: The founder of OVHcloud has officially denied claims of a massive data breach surfacing on dark web forums, suggesting the claims are part of a disinformation campaign. [More info](https://hackread.com/ovhcloud-founder-denies-590tb-data-breach-claims/)

## ⚖️ Legal & Law Enforcement

- **Yanluowang Access Broker Sentenced**: A high-profile initial access broker associated with the Yanluowang ransomware group has been sentenced to 81 months in prison for facilitating corporate network compromises. [More info](https://www.bleepingcomputer.com/news/security/yanluowang-ransomware-access-broker-gets-81-months-in-prison/)

## 📚 Others

- **"OpenClaw Deployer" Repo Delivers Trojan**: A malicious GitHub repository masquerading as a deployment tool was found delivering a Trojan designed to steal browser data, crypto wallets, and SSH keys. [More info](https://www.darkreading.com/application-security/github-openclaw-deployer-repo-delivers-trojan)

---

[⬅ Back to Archive](https://pranakn.github.io)
