---
title: "Cybersecurity Newsfeed - 20/11/26"
date: 2026-11-19 09:00:00 -0300
categories: [News]
permalink: /posts/news-20-11-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware, ai-security]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-11-20.png
  alt: Cybersecurity Newsfeed - 20/11/26
---

# Cybersecurity Newsfeed

## 📅 20/11/26

## 🛡️ Vulnerabilities

- **VMware vCenter Server Critical Auth Bypass (CVE-2026-123890)**: Broadcom released emergency patches for a maximum-severity (CVSS 9.8) unauthenticated bypass flaw actively exploited as a zero-day by the China-linked APT group Armory Castle. With no workarounds available, administrators must update deployments immediately to prevent unauthorized administrative control. [More info](https://thehackernews.com/2026/11/critical-vmware-vcenter-flaw-cvss-98.html) | [More info](https://www.securityweek.com/newly-patched-vmware-vcenter-flaw-exploited-as-zero-day-by-chinese-apt/)

- **Puppet Server RCE Added to CISA KEV (CVE-2026-115731)**: CISA added an actively exploited critical remote code execution flaw in enterprise Puppet servers to its Known Exploited Vulnerabilities catalog under BOD 26-04. Compromising a central server enables attackers to extract CA signing keys, impersonate hosts, and deploy ransomware; federal agencies must patch by December 1, 2026. [More info](https://www.cysecurity.news/2026/11/hackers-exploit-critical-puppet.html)

- **PHP Fixes 18 Flaws Including Seven Critical RCEs**: The PHP team shipped urgent updates across supported branches, including PHP 8.5, resolving 18 bugs—among them seven CVSS 9.2 vulnerabilities (`CVE-2026-115560`, `CVE-2026-129182`, `CVE-2026-109619`, `CVE-2026-126714`, `CVE-2026-129474`, `CVE-2026-129481`, `CVE-2026-129496`) and an incomplete patch for PHP2Shell. Unauthenticated attackers can exploit use-after-free, input validation, and TOCTOU race conditions to execute arbitrary code. [More info](https://thehackernews.com/2026/11/php-fixes-7-critical-flaws-including.html) | [More info](https://www.bleepingcomputer.com/news/security/php-security-updates-fix-18-flaws-including-critical-rce-bugs/)

- **Drupal Patches Critical Installer RCE Flaw (CVE-2026-132165)**: Discovered by Anthropic's OSS Scanner, this flaw in `/core/install.php` (affecting versions prior to 10.6.22, 11.3.22, and 11.4.13) allows unauthenticated attackers to re-trigger the CMS installation workflow and take over sites if `settings.php` remains writable. Proof-of-concept code is available, requiring immediate patching and access restrictions. [More info](https://thehackernews.com/2026/11/drupal-patches-critical-installer-flaw.html) | [More info](https://www.bleepingcomputer.com/news/security/drupal-patches-critical-rce-flaw-warns-exploits-may-surface-quickly/)

- **ASUS Control Center Express Hard-Coded Key Flaws**: ASUS released version 1.7.29 to patch three critical flaws, led by `CVE-2026-114204` (hard-coded cryptographic key) and `CVE-2026-114205`. Combined, these bugs allow attackers to bypass authentication and seize full administrative control over centralized enterprise IT management deployments. [More info](https://www.bleepingcomputer.com/news/security/asus-warns-of-critical-hard-coded-key-flaw-in-control-center-express/)

- **Splunk Remediates Nearly 140 Vulnerabilities**: Broad security advisories address almost 140 bugs across Splunk Enterprise, Enterprise Security, and Splunk SOAR. Notably, Splunk SOAR 8.8.0 resolves 59 issues, including two critical authenticated RCE flaws (`CVE-2026-131253` and `CVE-2026-131287`). [More info](https://www.securityweek.com/splunk-patches-nearly-140-flaws-across-three-core-products/)

## 🎯 Adversaries

- **Chaotic Eclipse Drops Windows & CrowdStrike Zero-Days**: Threat actor Chaotic Eclipse publicly released **FastUnlock**, a local privilege escalation zero-day that abuses Windows Narrator via the "I forgot my PIN" recovery screen to bypass lock screen authentication. The actor also disclosed **FalconFlank**, a separate privilege escalation zero-day targeting CrowdStrike Falcon. [More info](https://securityaffairs.com/203537/hacking/chaotic-eclipse-releases-fastunlock-a-new-windows-zero-day-vulnerability.html)

- **Cold Relic Chains Google Workspace Breaches**: Russia-linked espionage group Cold Relic is leveraging stolen credentials and data from an initial victim's Google Workspace environment to masquerade as trusted contacts and infiltrate a second U.S. organization, exploiting inter-organizational trust to bypass perimeter defenses. [More info](https://www.darkreading.com/cyberattacks-data-breaches/cold-relic-turns-one-cloud-breach-into-another)

- **BubbleLoader Trojanizes Legitimate Windows Tools**: Active since February 2026, the evasive BubbleLoader malware patches entry points of legitimate binaries like WinRAR and Firefox Launcher. It embeds two PNGs—using the first as a rolling XOR key to decrypt shellcode and reflectively load final payloads from the second fake image. [More info](https://thehackernews.com/2026/11/threatsday-gpt-62-jailbreak-flaws.html)

- **Phishing Campaign Deploys 29 Spoofed Bank Portals**: Netskope Threat Labs identified a standardized PHP phishing kit operating ~29 fraudulent banking sites (such as "Sunray Trust" and "Quartz Bank") since late September 2026. The portals reuse identical routing numbers and support details to harvest credentials and PII across North America, Europe, and Asia. [More info](https://hackread.com/29-fake-bank-sites-using-contact-details-steal-logins/)

## 🤖 AI Security

- **Self-Hosted Qwen Incidents Expose "Illusion of Control"**: Real-world security incidents involving internally hosted Qwen AI models demonstrate that enterprises deploying autonomous agents still face severe operational and manipulation risks when models lack strict runtime boundaries, alignment guardrails, and continuous behavioral monitoring. [More info](https://www.darkreading.com/cyber-risk/qwen-incidents-self-hosted-ai-models-stronger-steering)

- **GPT-6.2 Jailbreak Flaws Bypass Safety Guardrails**: Security researchers uncovered new jailbreak vulnerabilities affecting GPT-6.2 that allow attackers to circumvent built-in safety controls, raising concerns over malicious misuse of frontier models. [More info](https://thehackernews.com/2026/11/threatsday-gpt-62-jailbreak-flaws.html)

## 📈 Trends

- **AI Auditing Fuels "Vulnerability Hysteria"**: Automated AI-assisted code auditing is uncovering flaws at an unprecedented pace, overwhelming patching teams with remediation fatigue. Experts advise shifting away from raw CVSS panic toward risk-based prioritization, exploitability context, and compensating controls. [More info](https://www.darkreading.com/vulnerabilities-threats/navigating-vulnerability-hysteria-ai-era)

- **Five Early Telemetry Indicators of Ransomware**: Analysts detailed five pre-encryption warning signs that allow defenders to interrupt intrusions early: defense tampering (EDR disabling/BYOVD), anomalous privilege escalation, unusual outbound transfers, recovery sabotage (`vssadmin.exe`/`wbadmin.exe`), and rapid file enumeration. [More info](https://www.bleepingcomputer.com/news/security/five-warning-signs-of-ransomware-breach-before-encryption-or-data-theft/)

## 💥 Breaches & Leaks

- **SBC Medical Group Breach Exposes 1.6 Million Records**: Following unauthorized access to a web database system on November 16, 2026, the Japanese medical aesthetics operator disclosed in a Form 8-K filing that personal records and treatment-monitor metadata for roughly 1.6 million customers were compromised. [More info](https://www.bleepingcomputer.com/news/security/hackers-steal-data-of-16-million-sbc-medical-group-customers/)

- **Nvidia Investigates Ransomware Extortion Claims**: Nvidia is conducting forensic verification after affiliates of *The Gentlemen* RaaS operation claimed to have exfiltrated corporate data. Nvidia stated its investigation has so far found no evidence of an intrusion into internal systems. [More info](https://www.theregister.com/security/2026/11/19/nvidia-adds-possible-hack-to-list-of-very-bad-things-under-investigation/5311153)

## ⚖️ Law Enforcement

- **Ukraine and FBI Arrest Key Ransomware Suspects**: A joint operation executing 66 raids across Kyiv and 11 Ukrainian regions resulted in the arrest of four core members of a ransomware syndicate tied to over $40 million in extortion payments and $15 million ransom demands, seizing devices and nearly $400,000 in cash. [More info](https://www.bleepingcomputer.com/news/security/ukraine-fbi-arrest-ransomware-gang-members-tied-to-40m-in-ransoms/)

---

[⬅ Back to Archive](https://pranakn.github.io)
