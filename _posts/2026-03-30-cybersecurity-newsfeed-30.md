---
title: "Cybersecurity Newsfeed - 30/03/26"
date: 2026-03-29 20:00:00 -0300
categories: [News]
permalink: /posts/news-30-03/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-03-30.png
  alt: Cybersecurity Newsfeed - 30/03/26
---

# Cybersecurity Newsfeed

## 📅 30/03/26

## 🛡️ Vulnerabilities

- **Smart Slider 3 Local File Inclusion**: The WordPress plugin (500k+ installs) contains a critical flaw allowing authenticated contributors to read sensitive files like `wp-config.php`. Administrators should update to version 3.5.1.22 immediately. [More info](https://www.bleepingcomputer.com/news/security/file-read-flaw-in-smart-slider-plugin-impacts-500k-wordpress-sites/)

- **Citrix NetScaler Reconnaissance (CVE-2026-3055)**: Threat actors are actively probing NetScaler ADC and Gateway instances for a high-severity memory leak vulnerability. Urgent firmware updates are available to prevent sensitive data disclosure. [More info](https://securityaffairs.com/190131/hacking/urgent-alert-netscaler-bug-cve-2026-3055-probed-by-attackers-could-leak-sensitive-data.html)

- **Apple Lock Screen Bypass**: Urgent warnings have been issued for unpatched iPhones and iPads regarding a flaw that allows physical attackers to view photos or contacts without a passcode. [More info](https://securityaffairs.com/190109/security-apple-issues-urgent-lock-screen-warnings-for-unpatched-iphones-and-ipads.html)

- **F5 Big-IP APM Exploitation (CVE-2025-53521)**: An authentication bypass vulnerability in Big-IP APM is being exploited in the wild. Organizations must prioritize patching this gateway flaw to prevent lateral movement. [More info](https://www.helpnetsecurity.com/2026/03/28/big-ip-apm-vulnerability-cve-2025-53521-exploited/)

- **TP-Link Router Patches**: High-severity vulnerabilities affecting popular TP-Link router models could allow remote code execution or DoS. Users are urged to update firmware to mitigate botnet risks. [More info](https://www.securityweek.com/tp-link-patches-high-severity-router-vulnerabilities/)

- **CISA Adds New Flaw to KEV**: CISA has added a high-severity vulnerability to its Known Exploited Vulnerabilities catalog, mandating federal agencies to patch the widely used component by the specified deadline. [More info](https://www.cisa.gov/news-events/alerts/2026/03/27/cisa-adds-one-known-exploited-vulnerability-catalog)

## 🎯 Adversaries

- **Handala Breaches FBI Director's Email**: The Iranian-linked group Handala bypassed MFA to compromise Kash Patel’s personal Gmail, leaking 350GB of data. The breach highlights persistent targeting of US officials via sophisticated phishing. [More info](https://www.bleepingcomputer.com/news/security/fbi-confirms-hack-of-director-patels-personal-email-inbox/) | [More info](https://thehackernews.com/2026/03/iran-linked-hackers-breach-fbi.html)

- **ShinyHunters Hits European Commission**: The group claims to have stolen 350GB of data from the Commission's AWS environment, including internal documents and credentials, via a compromised admin account. [More info](https://hackread.com/shinyhunters-350gb-data-breach-european-commission/)

- **"Infinity Stealer" via ClickFix**: A new macOS malware is spreading through deceptive "ClickFix" lures, tricking users into pasting terminal commands that exfiltrate keychain data and browser cookies. [More info](https://www.bleepingcomputer.com/news/security/new-infinity-stealer-malware-grabs-macos-data-via-clickfix-lures/) | [More info](https://www.securityweek.com/cloudflare-themed-clickfix-attack-drops-infiniti-stealer-on-macs/)

- **Silver Fox Targets Japanese Firms**: This threat actor is using tax-season phishing lures to target corporate employees in Japan with malware designed for financial espionage and credential theft. [More info](https://www.welivesecurity.com/en/business-security/cunning-predator-how-silver-fox-preys-japanese-firms-tax-season/)

- **Chinese State-Sponsored Telco Backdoors**: Attackers have upgraded malware targeting telecommunications providers with improved stealth and C2 protocols for long-term espionage. [More info](https://www.darkreading.com/threat-intelligence/china-upgrades-backdoor-spy-telcos)

- **BianLian Shifts to SVG Invoices**: The ransomware group is now using SVG images with embedded malicious scripts to bypass email filters and deliver their custom backdoor. [More info](https://www.bleepingcomputer.com/news/security/fake-vs-code-alerts-on-github-spread-malware-to-developers/)

- **Fake VS Code Alerts on GitHub**: A sophisticated campaign targets developers with malicious repositories and fake update alerts to steal source code and credentials. [More info](https://www.bleepingcomputer.com/news/security/fake-vs-code-alerts-on-github-spread-malware-to-developers/)

- **Backdoored Telnyx Library on PyPI**: A malicious Python package used steganography in WAV files to hide a reverse shell payload. PyPI has since removed the package. [More info](https://www.bleepingcomputer.com/news/security/backdoored-telnyx-pypi-package-pushes-malware-hidden-in-wav-audio/)

- **TikTok Phishing Campaign**: Attackers are targeting TikTok users with fake violation notices and verification offers to harvest account credentials and personal data. [More info](https://www.infosecurity-magazine.com/news/phishing-targets-tiktok-for/)

## 📈 Trends

- **RSAC 2026 AI Focus**: The RSA Conference concluded with heavy emphasis on AI-driven phishing, automated exploit generation, and the shift toward "secure by design" principles in the age of autonomous threats. [More info](https://www.welivesecurity.com/en/videos/rsac-2026-wrap-up-week-security-tony-anscombe/)

- **The Emergence of "Agentic GRC"**: AI-driven Governance, Risk, and Compliance is rising, but experts warn that a cultural mindset shift toward trusting autonomous agents is still missing in many teams. [More info](https://www.bleepingcomputer.com/news/security/agentic-grc-teams-get-the-tech-the-mindset-shift-is-whats-missing/)

- **Weaponization of IP Cameras in Conflict**: Hacked IP cameras are being used in real-time for troop tracking and intelligence gathering, highlighting the physical dangers of unsecured IoT devices. [More info](https://www.darkreading.com/cyber-risk/wartime-usage-of-compromised-ip-cameras-highlight-their-danger)

## 💥 Breaches & Leaks

- **BreachForums User Leak**: ShinyHunters reportedly leaked a database of 300,000 BreachForums users, including emails and hashed passwords, signaling a power struggle in the underground community. [More info](https://hackread.com/shinyhunters-breachforums-leak-300000-user-database/)

- **Lloyds Bank App Glitch**: A technical malfunction inadvertently allowed customers to view the account details and balances of other individuals; the bank has announced compensation for those affected. [More info](https://hackread.com/lloyds-compensate-customers-app-glitch-exposed-data/)

- **Dutch Police Phishing Breach**: An employee's credential leak via phishing allowed attackers to access internal systems, prompting a full review of security protocols and staff training. [More info](https://www.bleepingcomputer.com/news/security/dutch-police-discloses-security-breach-after-phishing-attack/)

## 📚 Others

- **AnimePlay App Takedown**: An international coalition dismantled the infrastructure of AnimePlay, a piracy app with 5 million users, citing both copyright and user security risks. [More info](https://www.bleepingcomputer.com/news/security/anti-piracy-coalition-takes-down-animeplay-app-with-5-million-users/)

---

[⬅ Back to Archive](https://pranakn.github.io)
