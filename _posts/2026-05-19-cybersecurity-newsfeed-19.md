---
title: "Cybersecurity Newsfeed - 19/05/26"
date: 2026-05-18 17:00:00 -0300
categories: [News]
permalink: /posts/news-19-05-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-05-19.png
  alt: Cybersecurity Newsfeed - 19/05/26
---

# Cybersecurity Newsfeed

## 📅 19/05/26

## 🛡️ Vulnerabilities

- **Linux Kernel Privilege Escalation**: A critical Linux kernel vulnerability has been discovered that allows unprivileged local users to gain unauthorized access to root-only files. The flaw resides in the filesystem handling logic, specifically during certain system calls, enabling attackers to read or modify sensitive system configurations and password files. Proof-of-concept exploits are already circulating. [More info](https://www.theregister.com/security/2026/05/18/linux-kernel-flaw-opens-root-only-files-to-unprivileged-users/5241950)

- **Nginx Remote Code Execution (CVE-2026-42945)**: Threat actors are actively exploiting an integer overflow vulnerability in Nginx's HTTP/3 processing logic. Triggering a memory corruption state allows attackers to achieve remote code execution on vulnerable web servers. Organizations are advised to update immediately or temporarily disable HTTP/3 support. [More info](https://www.helpnetsecurity.com/2026/05/18/ngnix-vulnerability-exploited-cve-2026-42945/)

- **SmartBear ReadyAPI Flaw**: SmartBear has addressed a critical security vulnerability involving insecure deserialization of untrusted data in its ReadyAPI testing platform. The flaw enables remote code execution with application privileges, posing a major risk to automated testing pipelines handling external inputs. [More info](https://www.helpnetsecurity.com/2026/05/18/smartbear-readyapi/)

- **Claw-Chain OpenClaw Weaknesses**: Researchers have uncovered "Claw-Chain," a series of vulnerabilities in the OpenClaw framework that allow for sandbox escape and the delivery of persistent backdoors. By chaining architectural weaknesses in memory and process execution, malware can bypass isolation barriers and gain elevated privileges. [More info](https://www.securityweek.com/claw-chain-openclaw-flaws-allow-sandbox-escape-backdoor-delivery/)

- **Critical Enterprise Patches (Ivanti, Fortinet, SAP, VMware, n8n)**: High-severity patches have been issued for multiple enterprise platforms to mitigate remote code execution, authentication bypass, and sensitive data exposure risks. VPN and virtualization platforms are highly targeted, and rapid deployment is urged. [More info](https://thehackernews.com/2026/05/ivanti-fortinet-sap-vmware-n8n-patch.html)

- **Windows BitLocker Zero-Day**: A new zero-day exploit targeting Windows BitLocker allows local attackers to bypass full disk encryption by abusing the encryption key handling mechanism during specific recovery boot sequences. Experts recommend using additional pre-boot authentication measures until a patch arrives. [More info](https://www.schneier.com/blog/archives/2026/05/zero-day-exploit-against-windows-bitlocker.html)

- **MiniPlasma Windows Print Spooler Exploit**: A functional exploit named "MiniPlasma" has been released, targeting a legacy 2020 logic flaw in the Windows Print Spooler service. The exploit bypasses previous mitigation attempts, allowing local privilege escalation to SYSTEM level on modern Windows installations. [More info](https://www.securityweek.com/researcher-drops-miniplasma-windows-exploit-for-unpatched-2020-cve/)

## 🎯 Adversaries

- **Reaper Malware Targeting macOS**: A new malware strain named Reaper is targeting macOS ecosystems through social engineering. Utilizing a deceptive Microsoft-themed domain, the campaign prompts users to install a malicious package masquerading as a productivity update to exfiltrate system passwords and keychain data. [More info](https://hackread.com/reaper-malware-fake-microsoft-domain-macos-passwords/)

- **Government-Backed Espionage Targets Cloudflare Users in Malaysia**: Nation-state hacking groups are conducting a targeted campaign against Cloudflare users in Malaysia. Using custom malware and sophisticated phishing lures to compromise administrative accounts, the threat actors aim to intercept sensitive traffic and gather intelligence. [More info](https://hackread.com/government-backed-hackers-cloudflare-malaysia-espionage/)

- **The Gentlemen Ransomware Disrupted**: A law enforcement operation successfully compromised the command-and-control servers of "The Gentlemen" ransomware gang. Investigators recovered decryption keys and identified real-world identities of key members, heavily disrupting their affiliate-based extortion ring. [More info](https://hackread.com/the-gentlemen-ransomware-gang-breach-op-exposed/)

- **Pre-Stuxnet "Fast16" Malware Uncovered**: Security researchers analyzed a legacy, pre-Stuxnet era malware named "Fast16." Designed to tamper with Siemens PLCs, the malware altered industrial process timings without alerting operators, providing new insights into the history of offensive cyber-sabotage programs. [More info](https://thehackernews.com/2026/05/pre-stuxnet-fast16-malware-tampered.html)

## 📦 Supply Chain & Developer Security

- **Leaked Shai Hulud Malware Fuels npm Campaigns**: A leaked version of the Shai Hulud malware is being used in a surge of malicious npm packages. Utilizing dependency confusion and typosquatting, the infostealer targets software developers to harvest environment variables, SSH keys, and cloud credentials. [More info](https://www.bleepingcomputer.com/news/security/leaked-shai-hulud-malware-fuels-new-npm-infostealer-campaign/)

- **Developer Workstations heavily Targeted**: Security experts warn that developer workstations are an extension of the enterprise attack surface. Due to high-level repository access and production keys, threat actors are leveraging malicious IDE extensions and poisoned dependencies to compromise these systems, making Zero Trust architecture essential. [More info](https://thehackernews.com/2026/05/developer-workstations-are-now-part-of.html)

## 📈 Trends & Frameworks

- **Continuous Detection and Continuous Response (CDCR)**: Mate Security has introduced the CDCR framework to automate validation and remediation phases within Security Operations Centers (SOCs). Leveraging machine learning to execute pre-defined playbooks, it aims to combat alert fatigue and decrease Mean Time to Respond (MTTR). [More info](https://hackread.com/continuous-detection-continuous-response-mate-security-soc/)

## 💥 Breaches & Leaks

- **Grafana Labs Confirms Source Code Theft via GitHub Token**: Grafana Labs confirmed that a cybercrime group used a stolen developer Personal Access Token (PAT) to access and download internal Git repositories. Production environments, cloud services, and customer data remain unaffected. Grafana has revoked the token, rotated internal secrets, and is conducting a code audit to ensure no backdoors were planted. [More info](https://securityaffairs.com/192347/breaking-news/grafana-confirms-github-token-breach-cybercrime-group-claims-the-attack.html)

## 📚 Others

- **Windows 11 Introduces Resizable Taskbar & Start Menu**: Microsoft is rolling out a highly requested customization update allowing users to resize the taskbar and Start menu. Currently available for Windows Insiders, researchers note that UI modifications affecting core system infrastructure must be thoroughly evaluated to prevent stability regressions. [More info](https://www.bleepingcomputer.com/news/microsoft/windows-11-finally-gets-a-resizable-taskbar-and-start-menu/)

- **Interpol's Operation Ramz Nets 201 Arrests**: A major coordinated effort by Interpol has disrupted a massive cybercrime network in the Middle East and North Africa (MENA) region. The operation resulted in 201 arrests, the seizure of over $50 million in assets, and the takedown of thousands of malicious servers used for ransomware, BEC, and phishing. [More info](https://thehackernews.com/2026/05/interpol-operation-ramz-disrupts-mena.html)

- **Dutch Police Launch "Game Over" Campaign**: The Dutch National Police have initiated an aggressive campaign targeting local online fraud syndicates. Partnering with ISPs and financial institutions, the initiative has closed hundreds of fraudulent webshops, disrupted money mule networks, and resulted in numerous high-profile arrests. [More info](https://www.helpnetsecurity.com/2026/05/18/dutch-police-game-over-fraudsters-campaign/)


---

[⬅ Back to Archive](https://pranakn.github.io)
