---
title: "Cybersecurity Newsfeed - 15/06/26"
date: 2026-06-14 19:00:00 -0300
categories: [News]
permalink: /posts/news-15-06-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware, supply-chain, ai-security]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-06-15.png
  alt: Cybersecurity Newsfeed - 15/06/26
---

# Cybersecurity Newsfeed

## 📅 15/06/26

## 🛡️ Vulnerabilities

- **CISA Adds Oracle PeopleSoft Zero-Day to KEV (CVE-2026-35273)**: CISA officially expanded its Known Exploited Vulnerabilities catalog by adding a maximum-tier CVSS score 9.8 flaw impacting Oracle PeopleSoft Enterprise PeopleTools (versions 8.61 and 8.62). The missing-authentication bug allows remote, unauthenticated attackers to target exposed Environment Management Hub (PSEMHUB) endpoints, executing arbitrary code to achieve full system takeover while evading database monitoring tools. [More info](https://www.cisa.gov/news-events/alerts/2026/06/12/cisa-adds-one-known-exploited-vulnerability-catalog)

- **Critical Splunk Enterprise Flaw Allows RCE**: A critical security vulnerability has been identified in Splunk Enterprise that allows remote unauthenticated attackers to execute arbitrary code. The flaw stems from insufficient validation of user-supplied input within internal endpoint components, enabling parameter manipulation that bypasses systemic access controls and risks full system compromise. [More info](https://www.cysecurity.news/2026/06/critical-splunk-enterprise-flaw-lets.html)

- **Decade-Old phpBB Authentication Bypass Patched**: Security researchers identified a ten-year-old authentication bypass vulnerability affecting phpBB forum software branches 3.x and 4.x. The flaw allows remote attackers to log in as any user, including administrators, via a single unauthenticated HTTP request. A patch was issued in version 3.3.17, though a safe release for the 4.x branch remains unavailable. [More info](https://www.bleepingcomputer.com/news/security/phpbb-forum-fixes-auth-bypass-bug-lurking-for-a-decade)

- **Critical Flaw Chain Exposes LangGraph AI Agents**: Researchers disclosed a critical three-flaw vulnerability chain within the open-source LangGraph framework. By combining CVE-2025-67644 (SQL injection) and CVE-2026-28277 (unsafe msgpack deserialization) with a third query injection flaw (CVE-2026-27022), remote attackers can achieve arbitrary code execution on self-hosted AI agent deployments. [More info](https://thehackernews.com/2026/06/langgraph-flaw-chain-exposes-self-hosted-ai-agents to-remote-code-execution.html)

## 🎯 Adversaries

- **ShinyHunters Zero-Day Blitz Targets Universities**: The ShinyHunters cybercrime group targeted over 100 global organizations, exploiting the recent Oracle PeopleSoft zero-day (CVE-2026-35273). The campaign resulted in a massive data breach at the University of Nottingham, exfiltrating 40 GB of sensitive personal and financial data belonging to 450,000 students and staff members. [More info](https://hackread.com/shinyhunters-universities-oracle-peoplesoft-zero-day-attack/)

- **Chinese State Actors Hijack Auth Flow for Decade-Long Spy Op**: In a cyberespionage campaign dubbed Operation Highland, the China-linked threat group Velvet Ant maintained undetected persistence within an isolated critical infrastructure network for ten years. Initiated in 2016, the attackers trojanized OpenSSH components and replaced Linux Pluggable Authentication Modules (PAM) with backdoored variants to harvest administrative credentials. [More info](https://www.bleepingcomputer.com/news/security/chinese-hackers-hijack-auth-flow-spy-on-isolated-network-for-a-decade/)

- **Argamal Malware Disguised inside Hentai Games**: Kaspersky discovered a new remote access Trojan named Argamal distributed via adult gaming sites and torrent trackers. Hidden inside fully functional hentai game installers, the malware uses a rigged version of the FFmpeg DLL library to trigger a PowerShell script, granting threat actors complete remote control of compromised endpoints. [More info](https://hackread.com/hackers-hide-argamal-malware-hentai-games/)

- **Thai Users Target of Large-Scale SEO Poisoning**: A massive search engine optimization poisoning campaign has targeted Thai users to redirect search results toward illicit gambling networks. Threat actors compromise legitimate web infrastructure and inject malicious scripts to manipulate search algorithms, exposing visitors to fraudulent betting schemes and potential drive-by malware downloads. [More info](https://www.cysecurity.news/2026/06/thai-gambling-seo-poisoning-campaign.html)

- **Ex-IT Specialist Jailed for School District Sabotage**: Former senior IT specialist Ezekiel Dean Potter was sentenced to 21 months in prison for a 21-month cyberattack campaign against the Saydel Community School District. Following his termination, Potter used retained administrative credentials to delete the district's Facebook page, wipe employee Gmail accounts, and disable device management profiles. [More info](https://www.bleepingcomputer.com/news/security/ex-school-district-employee-jailed-for-hacks-on-former-employer/)

## 📈 Trends

- **NPM 12 Blocks Default Script Execution to Fight Supply Chain Attacks**: In response to surging supply chain attacks, GitHub announced that NPM version 12 will block script execution from dependencies by default during package installation. This preventative change stops preinstall, install, and postinstall routines, which have been heavily abused by malware campaigns like TeamPCP and the Shai-Hulud worm. [More info](https://www.securityweek.com/npm-12-will-change-script-execution-behavior-to-prevent-supply-chain-attacks/)

- **US Restricts Anthropic Fable 5 and Mythos 5 Models**: The U.S. Department of Commerce placed Anthropic’s Fable 5 and Mythos 5 AI models under strict export controls, suspending foreign access worldwide. The emergency decree cited national security concerns over a narrow jailbreak technique that allowed users to bypass safety guardrails and force the models to identify software flaws. [More info](https://cyberscoop.com/us-government-anthropic-fable-5-mythos-5-export-controls/)

- **NanoClaw and JFrog Partner to Secure AI Agents**: Secure agent framework NanoClaw integrated its infrastructure with the JFrog platform to secure AI agent software downloads. By routing autonomous asset requests through JFrog's reviewed registries, developers ensure that dynamic dependencies are pulled exclusively from vetted, uncompromised sources. [More info](https://www.theregister.com/ai-and-ml/2026/06/13/nanoclaw-integrates-jfrog-registries-to-secure-ai-agent-downloads/5255189)

- **Dark Web Intelligence Highlights Supply Chain Trading**: An underground intelligence report from Flare revealed an extensive paper trail of software supply chain attacks propagating across dark web marketplaces. Threat actors frequently trade stolen GitHub access, private repositories, and cloud credentials, exposing systemic build logic without explicit supply chain labels. [More info](https://www.bleepingcomputer.com/news/security/early-warning-signs-of-supply-chain-attacks-live-in-the-dark-web/)

## 💥 Breaches & Leaks

- **Novo Nordisk Discloses Data Breach Affecting Clinical Trials**: Danish pharmaceutical giant Novo Nordisk disclosed a security breach affecting internal IT systems. Exfiltrated data includes pseudonymized patient IDs, trial participation records, biomarkers, and non-public data belonging to healthcare professionals. Core business operations and insulin manufacturing remain unaffected. [More info](https://www.bleepingcomputer.com/news/security/pharmaceutical-giant-novo-nordisk-discloses-security-breach/)

- **Over 400 Arch Linux Packages Compromised via Rootkit**: A supply chain attack compromised over 400 packages within the Arch User Repository, distributing an eBPF-powered Linux rootkit and credential stealer. Threat actors hijacked orphaned repositories to execute a malicious NPM payload named atomic-lockfile, harvesting developer SSH artifacts, access credentials, and HashiCorp Vault tokens. [More info](https://www.bleepingcomputer.com/news/security/over-400-arch-linux-packages-compromised-to-push-rootkit-infostealer/)

## 📚 Others

- **FBI-Led Operation Riptide Disrupts Massive Phishing Service**: The FBI, alongside Google and Black Lotus Labs, dismantled an AI-driven Chinese phishing-as-a-service operation named Outsider Enterprise. Active since 2023, the platform utilized over a million fraudulent URLs to compromise hundreds of thousands of victims, stealing 3.8 million credit card records and causing 1.9 billion dollars in losses. [More info](https://www.bleepingcomputer.com/news/security/fbi-disrupts-massive-ai-powered-phishing-service-using-a-million-urls/)

- **INTERPOL Dismantles Prolific Sniper Dz Phishing Platform**: An INTERPOL-led initiative named Operation Ramz dismantled Sniper Dz, a prolific phishing-as-a-service platform operational since 2015. The international crackdown spanned 13 countries and culminated in 201 arrests. The infrastructure utilized over 20,000 unique domains and compromised 45,000 victims. [More info](https://thehackernews.com/2026/06/interpol-takes-down-sniper-dz-phishing.html)

---

[⬅ Back to Archive](https://pranakn.github.io)
