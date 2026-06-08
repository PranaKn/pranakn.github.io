---
title: "Cybersecurity Newsfeed - 08/06/26"
date: 2026-06-07 21:00:00 -0300
categories: [News]
permalink: /posts/news-08-06-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-06-08.png
  alt: Cybersecurity Newsfeed - 08/06/26
---

# Cybersecurity Newsfeed

## 📅 08/06/26

## 🛡️ Vulnerabilities

- **Critical Everest Forms Pro Vulnerability Exploited (CVE-2026-3300)**: Threat actors are actively exploiting a critical remote code execution vulnerability within the Everest Forms Pro WordPress plugin. Sporting a maximum CVSS severity score of 9.8, the flaw resides in the plugin's Calculation Addon, which concatenates user input into a PHP code string inside an unescaped eval function. Unauthenticated attackers leverage this flaw to execute arbitrary PHP code, inject malicious web shells, and achieve complete compromise of vulnerable WordPress sites. [More info](https://www.bleepingcomputer.com/news/security/critical-everest-forms-pro-flaw-exploited-to-take-over-wordpress-sites/)

- **SolarWinds Serv-U Exploitation (CVE-2026-0294)**: CISA has issued an urgent warning regarding the active exploitation of a high-severity vulnerability in SolarWinds Serv-U. Threat actors are leveraging this flaw to trigger buffer overflows, enabling remote code execution that results in immediate server crashes and potential root-level system takeover. The vulnerability resides in the application’s file transfer processing mechanism, which lacks adequate input validation. [More info](https://www.bleepingcomputer.com/news/security/cisa-hackers-now-exploit-solarwinds-serv-u-flaw-to-crash-servers/)

- **PAN-OS Vulnerability Exploitation (CVE-2026-0257)**: Palo Alto Networks has confirmed active exploitation of a critical vulnerability affecting its PAN-OS firewall software. The flaw allows unauthenticated remote attackers to bypass authentication mechanisms, granting them administrative control over impacted devices. Exploitation poses a severe risk to network security, as attackers could intercept traffic, modify firewall policies, or deploy secondary malware. [More info](https://unit42.paloaltonetworks.com/active-exploitation-of-pan-os-cve-2026-0257/)

- **Cisco SD-WAN Zero-Day**: Cisco has confirmed a new zero-day vulnerability in its SD-WAN software that is currently being exploited in the wild to gain root-level access to network appliances. Threat actors are chaining this flaw with a secondary authentication bypass to circumvent perimeter defenses and establish persistent control over targeted systems, creating a high potential for widespread network disruption. [More info](https://www.bleepingcomputer.com/news/security/new-cisco-sd-wan-flaw-exploited-in-zero-day-attacks-to-gain-root/)

- **Chrome Vulnerability Remediation**: Google has released Chrome version 149, which addresses 429 individual vulnerabilities, significantly hardening the browser against modern exploitation techniques. This extensive security update includes critical patches for memory corruption flaws, use-after-free bugs, and side-channel vulnerabilities that could be leveraged by attackers to execute arbitrary code or bypass security sandboxes. [More info](https://www.securityweek.com/chrome-149-patches-429-vulnerabilities/)

- **CISA Known Exploited Vulnerabilities Catalog Update (CVE-2026-28318)**: CISA has added a critical entry to its KEV catalog, identifying an uncontrolled resource consumption vulnerability affecting SolarWinds Serv-U. This flaw is actively being exploited in the wild by threat actors to execute denial-of-service attacks, resulting in severe server crashes. [More info](https://www.cisa.gov/news-events/alerts/2026/06/05/cisa-adds-one-known-exploited-vulnerability-catalog)

## 🎯 Adversaries

- **Silent Ransom Group Social Engineering Campaign**: The Silent Ransom Group (also known as Luna Moth) is actively executing social engineering campaigns targeting U.S. law firms to extort organizations without deploying traditional encryption malware. Attackers use callback phishing emails and phone calls to impersonate IT support. In highly sophisticated escalations, threat actors have physically visited target locations under the guise of technical support to directly exfiltrate files via USB storage. [More info](https://www.bleepingcomputer.com/news/security/silent-ransom-group-targets-law-firms-with-fake-it-support-calls/)

- **Miasma Worm GitHub Incident**: The Miasma worm has successfully compromised 73 Microsoft GitHub repositories, leveraging automated exploit chains to inject malicious scripts into open-source codebases. Threat actors utilized compromised developer tokens to gain unauthorized repository access and append obfuscated payloads to core project files for credential harvesting and persistence. [More info](https://thehackernews.com/2026/06/miasma-worm-hits-73-microsoft-github.html)

- **Polyfill Supply Chain Attack**: Suspicious login prompts have been detected on the official websites of Toshiba and Muji, linked to a malicious compromise of the popular Polyfill.io supply chain. Threat actors successfully injected obfuscated JavaScript into the Polyfill library to intercept user credentials by redirecting traffic to fraudulent servers during authentication attempts. [More info](https://www.bleepingcomputer.com/news/security/suspicious-polyfill-login-prompts-pop-up-on-toshiba-muji-websites/)

- **Chinese APT Persistence Malware**: A China-linked advanced persistent threat group has deployed a sophisticated new modular malware strain designed to maintain long-term access within compromised enterprise networks. The malware employs advanced anti-forensic techniques, including memory-only execution and dynamic API resolution, to evade detection by traditional endpoint security solutions. [More info](https://www.bleepingcomputer.com/news/security/chinese-apt-deploys-new-malware-to-keep-access-to-hacked-networks/)

- **Reaper macOS Infostealer**: A new macOS-focused infostealer dubbed Reaper has been discovered targeting cryptocurrency wallets and stored browser passwords. Distributed via malicious modifications to legitimate Script Editor applications, Reaper utilizes clever obfuscation to bypass macOS Gatekeeper protections and exfiltrate sensitive keys to remote servers. [More info](https://hackread.com/reaper-macos-infostealer-script-editor-crypto-passwords/)

- **C0XMO Botnet Propagation (CVE-2021-27137)**: A sophisticated new Gafgyt malware variant named C0XMO is actively propagating by exploiting a critical stack buffer overflow vulnerability found in the UPnP service of DD-WRT router firmware. The botnet scans active processes to aggressively terminate rival malware binaries, ensuring exclusive control over the infected host. [More info](https://www.bleepingcomputer.com/news/security/c0xmo-botnet-spreads-via-dd-wrt-router-flaw-kills-rival-malware/)

## 📈 Trends

- **Silent Ransom Group Infrastructure Shift**: The Silent Ransom Group has migrated its command-and-control infrastructure to a complex DNS Fast Flux network, significantly complicating mitigation efforts. By rapidly rotating the IP addresses associated with their domains, the group effectively evades traditional blocklists and security monitoring tools used by enterprise defenders. [More info](https://securityaffairs.com/193215/cyber-crime/silent-ransom-group-srg-switching-to-dns-fast-flux-infrastructure.html)

## 💥 Breaches & Leaks

- **DentaQuest Data Breach**: The dental benefits administrator DentaQuest suffered a significant data breach impacting approximately 2.6 million individuals. The extortion group ShinyHunters claimed responsibility for the incident, publishing over 234 gigabytes of exfiltrated data including names, dates of birth, telephone numbers, home addresses, Medicaid IDs, and health insurance details. [More info](https://securityaffairs.com/193274/data-breach/dentaquest-breach-shinyhunters-publish-data-impacting-2-6m-people.html)

## 📚 Others

- **Nemesis Market Vendor Sentencing**: A dark web vendor formerly operating on the Nemesis Market has been sentenced to 26 years in prison for extensive illegal drug distribution. The sentencing follows a multi-agency international investigation that successfully deanonymized the vendor’s operations and mapped their logistics network despite the use of cryptocurrency obfuscation techniques. [More info](https://www.bleepingcomputer.com/news/security/dark-web-nemesis-market-vendor-gets-26-years-for-selling-drugs/)

---

[⬅ Back to Archive](https://pranakn.github.io)
