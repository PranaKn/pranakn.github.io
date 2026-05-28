---
title: "Cybersecurity Newsfeed - 29/05/26"
date: 2026-05-28 19:00:00 -0300
categories: [News]
permalink: /posts/news-29-05-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-05-29.png
  alt: Cybersecurity Newsfeed - 29/05/26
---

# Cybersecurity Newsfeed

## 📅 29/05/26

## 🛡️ Vulnerabilities

- **FortiClient EMS Exploited in the Wild (CVE-2026-35616)**: Threat actors are actively exploiting a critical vulnerability in Fortinet’s FortiClient Endpoint Management Server (EMS) to deploy infostealer malware. The flaw, carrying a CVSS score of 9.1, allows unauthenticated remote code execution via improper access control in the EMS API. Attackers utilize crafted requests to manipulate endpoint policies and push payloads across corporate networks. CISA has officially added this to its Known Exploited Vulnerabilities (KEV) catalog, and organizations are urged to apply the available hotfix immediately. [More info](https://www.bleepingcomputer.com/news/security/hackers-exploit-forticlient-ems-flaw-to-push-infostealer-malware/)

- **Critical Gogs RCE Vulnerability**: A critical remote code execution (RCE) flaw has been identified in Gogs, a popular self-hosted Git service. The vulnerability allows authenticated users to execute arbitrary commands on the underlying server by exploiting an improper input validation issue during the repository migration process. Given its widespread deployment in private DevOps environments, administrators are urged to update to the latest patched version immediately. [More info](https://thehackernews.com/2026/05/critical-gogs-rce-vulnerability-lets.html)

---

## 📦 Supply Chain Attacks

- **Nx Console VS Code Extension Compromised**: A malicious version of the Nx Console VS Code extension (v18.95.0) was published to the Visual Studio Marketplace for an 18-minute window on May 18, 2026. Attributed to the threat group TeamPCP, this supply chain attack originated from a compromised TanStack npm package. The payload executed hidden shell commands disguised as routine Model Context Protocol (MCP) setup tasks to harvest GitHub tokens, AWS keys, and SSH credentials, resulting in the exfiltration of approximately 3,800 internal GitHub repositories. [More info](https://www.cisa.gov/news-events/alerts/2026/05/28/supply-chain-compromises-impact-nx-console-and-github-repositories)

---

## 🎯 Adversaries

- **BTMOB Android RAT Emerging as MaaS Threat**: The BTMOB Android Remote Access Trojan (RAT), an evolution of SpySolr, has emerged as a significant Malware-as-a-Service (MaaS) threat targeting users in Brazil and Latin America. It enables adversaries to exfiltrate sensitive data, capture screenshots, and take full remote control of devices by abusing Android Accessibility Services. It is marketed with a user-friendly APK builder, allowing low-skilled threat actors to rapidly generate custom payloads and regionalized phishing lures. [More info](https://www.bleepingcomputer.com/news/security/btmob-android-malware-service-generates-custom-phishing-payloads/) | [More info](https://www.darkreading.com/cyberattacks-data-breaches/btmob-rat-brazil-latam-maas-model)

- **Russia-Linked GreyVibe Supercharging Attacks with GenAI**: A Russia-linked threat actor designated as GreyVibe is utilizing advanced generative AI automation to significantly accelerate the creation of highly convincing phishing lures and malicious scripts. Bypassing traditional security filters, the group is primarily targeting critical infrastructure and government sectors, demonstrating a distinct shift toward AI-supercharged offensive social engineering operations. [More info](https://www.securityweek.com/russia-linked-greyvibe-attackers-use-ai-to-supercharge-cyberattacks/)

- **"The Gentlemen" Self-Propagating Go Ransomware**: Microsoft security researchers have detailed "The Gentlemen," a sophisticated self-propagating ransomware strain developed in Go. The malware stands out for its ability to autonomously spread through local networks by exploiting common vulnerabilities and weak credentials. The use of the Go language facilitates cross-platform execution and complicates traditional signature-based detection, compressing the timeline between initial access and network-wide encryption. [More info](https://www.microsoft.com/en-us/security/blog/2026/05/28/the-gentlemen-ransomware-dissecting-a-self-propagating-go-encryptor/)

- **Jinx-0164 Campaign Targets Crypto Firms**: A new cyber espionage campaign tracked as Jinx-0164 is specifically targeting cryptocurrency and decentralized finance firms. Utilizing tailored spear-phishing lures and high-precision social engineering, the actors deliver a custom backdoor designed for stealthy data exfiltration and credential theft, incorporating advanced evasion techniques to bypass standard Endpoint Detection and Response (EDR) systems. [More info](https://thehackernews.com/2026/05/jinx-0164-targets-cryptocurrency-firms.html)

- **Nimbus Manticore Targets U.S. Aviation with MiniFast Backdoor**: The Iranian-affiliated threat actor Nimbus Manticore (UNC1549) is running a cyber campaign targeting U.S. aviation and software firms. The group is leveraging Trojanized Zoom installers and SEO poisoning to deploy a previously undocumented backdoor named "MiniFast." This operation highlights the actor's first known integration of AI-assisted development practices to rapidly iterate its offensive tooling. [More info](https://hackread.com/iran-nimbus-manticore-trojan-zoom-installers-us-firms/)

---

## 📈 Trends

- **GPU Mining Malware Spreading via SEO Poisoning and Chatbots**: Microsoft Defender Experts have uncovered a cryptojacking campaign that leverages SEO poisoning and AI chatbot interactions to distribute GPU mining malware. Impersonating hardware utilities like CrystalDiskInfo and FurMark, malicious links are uniquely surfaced through LLM-based chatbot responses. The infection chain utilizes DLL sideloading and abused ScreenConnect deployments to establish persistence on high-performance systems. [More info](https://www.bleepingcomputer.com/news/security/gpu-mining-malware-spreads-via-seo-poisoning-ai-chatbots/)

- **Qumulo Launches AI-Driven NeuralProtect**: Qumulo has launched NeuralProtect, an AI-driven ransomware resilience solution built to detect and halt attacks at the storage layer before encryption occurs. The tool utilizes statistical and temporal AI models to perform Deep File Inspection on write operations, instantly terminating compromised user sessions and isolating data when anomalies are detected. [More info](https://www.helpnetsecurity.com/2026/05/28/qumulo-neuralprotect-uses-ai-to-detect-and-stop-ransomware-before-encryption/)

- **Qevlar Introduces Autonomous SOC AI Agents**: Qevlar has introduced a new suite of autonomous AI agents designed to unify Security Operations Centers (SOCs) and vulnerability management workflows. The platform correlates live incident signals with CVE data to prioritize risks in real-time, translating vulnerability data directly into proactive threat hunting queries to combat shrinking exploitation windows. [More info](https://www.helpnetsecurity.com/2026/05/28/qevlar-ai-agents/)

- **FBI Warns of 2026 FIFA World Cup Typosquatting**: The FBI has issued an urgent warning regarding a surge in typosquatting schemes targeting fans of the 2026 FIFA World Cup. Cybercriminals are deploying fraudulent websites with lookalike URLs that closely mimic official FIFA domains to harvest personally identifiable information (PII) and financial credentials from users looking for tickets or tournament details. [More info](https://www.bleepingcomputer.com/news/security/fbi-warns-of-fake-fifa-websites-running-world-cup-fraud-schemes/)

---

## 💥 Breaches & Leaks

- **ShinyHunters Steals 6 Million Carnival Corporation Records**: The threat group ShinyHunters has reportedly exfiltrated over 6 million customer records from Carnival Corporation following a sophisticated breach targeting cloud-based storage infrastructure. The stolen data includes sensitive personal info, booking details, and financial identifiers, which the group has threatened to leak on illicit forums. [More info](https://www.theregister.com/cyber-crime/2026/05/28/carnival-shinyhunters-cruised-off-with-6m-customer-records/5247808)

---

## 📚 Others

- **Access Broker Sentenced to 5 Years for Oregon Gov Hacking**: Romanian national Catalin Dragomir has been sentenced to 56 months in U.S. federal prison for his role in a 2021 cyberattack on an Oregon state government network. Operating under dark web aliases, Dragomir obtained unauthorized access and sold it to other cybercriminals as an access broker, causing over $250,000 in losses. [More info](https://www.bleepingcomputer.com/news/security/romanian-gets-5-years-in-prison-for-hacking-oregon-govt-network/)

---

[⬅ Back to Archive](https://pranakn.github.io)
