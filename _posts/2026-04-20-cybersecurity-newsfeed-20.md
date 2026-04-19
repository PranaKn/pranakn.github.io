---
title: "Cybersecurity Newsfeed - 20/04/26"
date: 2026-04-19 09:00:00 -0300
categories: [News]
permalink: /posts/news-20-04/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware, AI]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-04-20.png
  alt: Cybersecurity Newsfeed - 20/04/26
---

# Cybersecurity Newsfeed

## 📅 20/04/26

## 🛡️ Vulnerabilities

- **Critical Flaw in Google Protocol Buffers (protobuf.js)**: A prototype pollution vulnerability in the `protobuf.js` library could allow attackers to execute arbitrary JavaScript code. Given its widespread use in Node.js and cloud-native services, developers are urged to update immediately to prevent RCE. [More info](https://www.bleepingcomputer.com/news/security/critical-flaw-in-protobuf-library-enables-javascript-code-execution/)

- **NIST to Stop Rating Non-Priority Flaws**: Due to a massive backlog in the National Vulnerability Database (NVD), NIST will stop assigning severity ratings to lower-priority vulnerabilities. Experts worry this shift may hinder automated patch management for many organizations. [More info](https://www.bleepingcomputer.com/news/security/nist-to-stop-rating-non-priority-flaws-due-to-volume-increase/)

- **CISA Issues Urgent Patch Directive**: CISA has added several high-risk vulnerabilities to its KEV catalog, ordering federal agencies to remediate flaws being actively exploited in the wild to prevent unauthorized access and data exfiltration. [More info](https://www.theregister.com/2026/04/17/cisa_tells_feds_to_patch/)

- **Microsoft Defender Targeted by Three Zero-Days**: Threat actors are exploiting three privilege escalation vulnerabilities in Microsoft Defender, two of which remain unpatched. These flaws allow attackers to neutralize security protections to deploy ransomware. [More info](https://securityaffairs.com/190961/hacking/microsoft-defender-under-attack-as-three-zero-days-two-of-them-still-unpatched-enable-elevated-access/)

- **Exploitation of CVE-2023-33538 Observed**: Unit 42 researchers report active use of this RCE flaw to facilitate credential theft and internal reconnaissance, often initiated via targeted phishing campaigns. [More info](https://origin-unit42.paloaltonetworks.com/exploitation-of-cve-2023-33538/)

## 🎯 Adversaries

- **Cross-Tenant Helpdesk Impersonation**: Microsoft has released a playbook on a sophisticated intrusion trend where attackers compromise one M365 tenant to pose as support staff to target other organizations, exploiting human trust to gain admin access. [More info](https://www.microsoft.com/en-us/security/blog/2026/04/18/crosstenant-helpdesk-impersonation-data-exfiltration-human-operated-intrusion-playbook/)

- **Apple Account Change Phishing**: Attackers are abusing Apple's legitimate notification system to trigger "MFA fatigue." By sending authentic password reset alerts, they coerce users into entering credentials on fraudulent landing pages. [More info](https://www.bleepingcomputer.com/news/security/apple-account-change-alerts-abused-to-send-phishing-emails/)

- **Nexcorium Mirai Variant Targeting DVRs**: A new Mirai variant is exploiting CVE-2018-9995 in TBK DVR devices to build a massive DDoS botnet. The malware bypasses authentication to gain root access to unpatched legacy IoT hardware. [More info](https://thehackernews.com/2026/04/mirai-variant-nexcorium-exploits-cve.html)

- **CGrabber Malware Uses GitHub ZIPs**: A new campaign delivers malware via GitHub ZIP files using "Direct-Sys" calls to bypass EDR and antivirus API hooks, complicating traditional behavioral detection. [More info](https://hackread.com/cgrabber-direct-sys-malware-github-zip-files/)

- **New Android RATs Target Job Seekers**: Malware variants like RecruitRat and Astrinox are masquerading as productivity tools in fake recruitment campaigns to steal personal data and intercept MFA codes via SMS. [More info](https://hackread.com/recruitrat-saferrat-astrinox-massiv-android-malware/)

- **QEMU Used for Stealthy Virtual Machines**: Hackers are leveraging the QEMU emulator to create hidden VMs on target hosts. This abstraction allows them to run malicious workloads undetected by the host's EDR tools. [More info](https://securityaffairs.com/190982/security/hidden-vms-how-hackers-leverage-qemu-to-stealthily-steal-data-and-spread-malware/)

## 📈 Trends

- **AI Accelerates Legacy Exploitation**: Analysis suggests that legacy flaws are effectively becoming "AI vulnerabilities" as threat actors use LLMs to automate the development of functional exploits for old, unpatched code. [More info](https://www.darkreading.com/vulnerabilities-threats/every-old-vulnerability-ai-vulnerability)

- **Claude 3 Opus Writes Functional Chrome Exploit**: Researchers demonstrated that the AI model could autonomously write an exploit for a Chrome vulnerability, highlighting the growing capability of AI in complex security research and potential misuse. [More info](https://www.theregister.com/2026/04/17/claude_opus_wrote_chrome_exploit/)

- **Tycoon 2FA Phishing Kit Loses Dominance**: Previously a market leader, Tycoon 2FA is being overtaken by newer PhaaS (Phishing-as-a-Service) providers offering more advanced bypasses for modern MFA protections. [More info](https://www.securityweek.com/tycoon-2fa-loses-phishing-kit-crown-amid-surge-in-attacks/)

- **Cyber-Attacks Fuel Cargo Theft**: The logistics industry is seeing a surge in theft driven by digital manipulation. Attackers hack shipping platforms to orchestrate "fictitious pickups," diverting high-value goods like electronics and food. [More info](https://securityaffairs.com/191008/security/cyber-attacks-fuel-surge-in-cargo-theft-across-logistics-industry.html)

- **Spike in Web Server Misconfiguration Attacks**: SANS ISC report details an increase in automated scans targeting directory traversal and file inclusion flaws, reminding admins that basic security hygiene remains critical. [More info](https://isc.sans.edu/diary/32904)

## 💥 Breaches & Leaks

- **Vercel Confirms Security Breach**: Vercel confirmed a breach involving stolen corporate data after a third-party account was compromised. While employee info was accessed, customer production data and source code remain secure. [More info](https://www.bleepingcomputer.com/news/security/vercel-confirms-breach-as-hackers-claim-to-be-selling-data/)

## 📚 Others

- **Operation PowerOff Dismantles DDoS Services**: An international law enforcement effort seized 53 domains associated with "booter" services, dealing a major blow to the commercialized DDoS-for-hire ecosystem. [More info](https://hackread.com/operation-poweroff-ddos-for-hire-services-identified/)

- **Nakivo v11.2 Adds Ransomware Defenses**: The latest update for Nakivo Backup & Replication introduces immutable storage and support for vSphere 9 and Proxmox VE 9.0 to bolster disaster recovery. [More info](https://www.bleepingcomputer.com/news/security/nakivo-v112-ransomware-defense-faster-replication-vsphere-9-and-proxmox-ve-90-support/)

---

[⬅ Back to Archive](https://pranakn.github.io)
