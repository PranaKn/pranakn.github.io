---
title: "Cybersecurity Newsfeed - 27/07/26"
date: 2026-07-26 09:00:00 -0300
categories: [News]
permalink: /posts/news-27-07-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-07-27.png
  alt: Cybersecurity Newsfeed - 27/07/26
---

# Cybersecurity Newsfeed

## 📅 27/07/26

## 🛡️ Vulnerabilities

- **Check Point SmartConsole Zero-Day**: Check Point released emergency out-of-band hotfixes for a critical zero-day vulnerability in its SmartConsole management application currently under active exploitation. The flaw permits authenticated attackers to achieve remote code execution and gain full administrative control over firewall management servers. [More info](https://www.bleepingcomputer.com/news/security/check-point-patches-smartconsole-zero-day-exploited-in-attacks/)

- **Linux Kernel Team Publishes 432 CVEs**: The Linux Kernel maintainer team released an unprecedented 432 Common Vulnerabilities and Exposures across a compressed two-day window. The updates address memory corruption flaws, privilege escalation vectors, and denial-of-service risks across multiple kernel subsystems and drivers. [More info](https://www.theregister.com/security/2026/07/22/linux-kernel-team-publishes-432-cves-in-two-days/5276497)

- **Google Dialogflow CX Flaw**: Google patched a critical vulnerability within its Dialogflow CX conversational AI platform caused by improper access controls in agent routing mechanisms, which could allow unauthorized interception or manipulation of enterprise chatbot interactions and tenant data. [More info](https://www.cysecurity.news/2026/07/google-fixes-dialogflow-cx-flaw-that.html)

- **RefluxFS Linux File System Local Privilege Escalation**: A critical flaw in the new RefluxFS Linux file system allows unprivileged local attackers to manipulate kernel memory structures and gain full root access due to improper handling of user namespaces and memory-mapped file operations. [More info](https://www.bleepingcomputer.com/news/linux/new-refluxfs-linux-flaw-lets-attackers-gain-root-privileges/)

- **Active RCE Exploitation of Legacy Fastjson 1.x**: Threat actors are actively scanning for and exploiting unpatched legacy Fastjson 1.x Java library deployments to execute arbitrary code via deserialization flaws, deploying ransomware and persistent backdoors. [More info](https://thehackernews.com/2026/07/fastjson-1x-rce-vulnerability-targeted.html)

- **Rockwell Arena Simulation Software Code Execution Flaws**: Rockwell Automation issued security updates for Arena simulation software to fix multiple high-severity code execution vulnerabilities that could allow local authenticated users to escalate privileges on engineering workstations. [More info](https://www.securityweek.com/rockwell-patches-code-execution-flaws-in-arena-simulation-software/)

- **NodeBB Fixes 8 Flaws Uncovered by Autonomous AI**: Community forum platform NodeBB released patches for eight security vulnerabilities—ranging from cross-site scripting to privilege escalation—discovered entirely through autonomous AI code analysis tools. [More info](https://thehackernews.com/2026/07/nodebb-patches-eight-ai-found-flaws.html)

- **macOS "Evil Twin" Binary Replacement Flaw**: Researchers demonstrated a race-condition flaw in macOS where downloaded applications can be silently swapped with malicious binaries immediately after installation before Apple Gatekeeper signature verification completes. [More info](https://www.theregister.com/security/2026/07/24/researchers-replace-downloaded-macos-apps-with-evil-twins-apple-shrugs/5277858)

- **Rogue AI Agent Infiltration via ChatGPT Links**: A zero-click attack vector allows malicious actors to embed prompt injection payloads within shared ChatGPT conversation links, smuggling autonomous AI agents into corporate environments to exfiltrate data. [More info](https://www.theregister.com/security/2026/07/23/one-chatgpt-link-could-smuggle-a-rogue-ai-agent-into-your-company/5275116)

- **"Claude Mythos" Prompt Injection Vector**: Cybersecurity researchers identified esoteric prompt injection techniques capable of tricking large language models like Claude into bypassing safety guardrails and exposing internal system information. [More info](https://www.cysecurity.news/2026/07/claude-mythos-just-caught-attention-of.html)

## 🎯 Adversaries

- **Steam Forum ClickFix Campaign Spreads XMRig**: Threat actors are using the ClickFix social engineering tactic on Steam community forums, tricking gamers into executing malicious commands under the guise of patch or error fixes to silently install XMRig cryptominers. [More info](https://www.cysecurity.news/2026/07/steam-forum-scam-uses-clickfix.html) | [More info](https://www.bleepingcomputer.com/news/security/steam-forum-clickfix-attacks-infect-gamers-with-xmrig-cryptominers/)

- **Autonomous Hermes AI Agent Targets Thai Ministry**: Threat actors deployed an autonomous AI agent dubbed Hermes to conduct reconnaissance and execute real-time adaptive attacks against the Thai Finance Ministry to steal economic data. [More info](https://www.bleepingcomputer.com/news/security/hermes-ai-agent-used-to-automate-attack-on-thai-finance-ministry/)

- **Russian Cyber Spies Exploit Critical Vulnerability**: Russian state-sponsored cyber espionage groups are actively exploiting a critical remote code execution vulnerability to establish persistent footholds and gather intelligence across target government and infrastructure networks. [More info](https://www.cysecurity.news/2026/07/russian-cyber-spies-exploited-critical.html)

- **Autonomous Kimi K3 Agents Exploit Redis Zero-Days**: AI-driven Kimi K3 agents are actively scanning for internet-exposed Redis databases and exploiting zero-day remote code execution flaws to deploy cryptominers and botnet modules. [More info](https://thehackernews.com/2026/07/kimi-k3-agents-found-redis-zero-days.html)

- **Cl0p Syndicate Targets File Transfer & Windchill FlexPLM**: Cl0p ransomware affiliates are targeting unpatched internet-facing file transfer software and PTC Windchill FlexPLM systems to exfiltrate proprietary corporate intellectual property for double-extortion schemes. [More info](https://thehackernews.com/2026/07/cl0p-affiliates-target-internet-exposed.html) | [More info](https://www.bleepingcomputer.com/news/security/clop-ransomware-targets-windchill-flexplm-in-data-theft-attacks/)

- **UAC-0099 Hides Malware in Fake Notepad++ Plugins**: Ukrainian critical infrastructure is being targeted by state-aligned group UAC-0099 using malicious, trojanized Notepad++ plugins distributed through spear-phishing campaigns. [More info](https://securityaffairs.com/195923/cyber-warfare-2/uac-0099-is-now-hiding-malware-inside-a-fake-notepad-plugin-to-target-ukrainian-organizations.html) | [More info](https://thehackernews.com/2026/07/fake-notepad-plugin-delivers.html)

- **Chaos Ransomware Deploys Browser-Based MSARAT**: Chaos ransomware affiliates are utilizing MSARAT, a web browser-based remote access trojan that uses encrypted WebSockets to bypass firewalls and EDR detection while exfiltrating sensitive files. [More info](https://securityaffairs.com/195876/malware/chaos-ransomware-deploys-browser-based-msarat-to-evade-network-detection.html)

- **Golden Chickens Group Returns with Four New Strains**: Financial malware provider Golden Chickens resurfaced with four new heavily obfuscated malware strains that utilize fileless execution and legitimate binaries to evade EDR systems. [More info](https://thehackernews.com/2026/07/golden-chickens-resurfaces-with-four.html)

- **Hotel Wi-Fi Compromised to Steal M365 Credentials**: Cybercriminals are setting up rogue access points and man-in-the-middle captive portals on hotel Wi-Fi networks to harvest Microsoft 365 login credentials from traveling executives. [More info](https://securityaffairs.com/196017/security/hackers-hijack-hotel-wi-fi-to-steal-microsoft-365-credentials.html)

- **Boko Haram Weaponizes AI Chatbots for Recruitment**: Intelligence reports reveal militant group Boko Haram is using conversational AI across encrypted messaging platforms to scale radicalization efforts and deliver interactive propaganda. [More info](https://www.cysecurity.news/2026/07/boko-haram-used-ai-chatbots-to-support.html)

- **DevMan Ransomware-as-a-Service Portal Launches**: A new dark web platform named DevMan centralizes payload creation, negotiation, and payment tracking for cybercriminals, lowering technical barriers to entry. [More info](https://thehackernews.com/2026/07/devman-raas-portal-centralizes-payload.html)

- **Evasive Windows Stealer Integrates AI Profiler**: A stealthy Windows infostealer targeting over 300 desktop applications uses an onboard AI engine to analyze stolen data in real time and prioritize high-value assets for monetization. [More info](https://www.theregister.com/security/2026/07/22/sneaky-windows-stealer-targets-300-apps-gives-crims-an-ai-profiler-to-maximize-profits/5275962)

## 📈 Trends

- **Generative AI Accelerates Cybercrime Operations**: Adversaries are increasingly leveraging generative AI tools to scale phishing operations, automate social engineering campaigns, and construct evasive malware at unprecedented speed. [More info](https://www.cysecurity.news/2026/07/ai-is-fueling-new-wave-of-cybercrime.html)

- **Fragmented Malvertising Delivery Bypasses Signature Scans**: Malvertising networks are serving malware payloads split into localized JavaScript fragments that reassemble directly in browser memory, evading traditional perimeter and endpoint signature checks. [More info](https://thehackernews.com/2026/07/malvertising-sends-malware-in-pieces.html)

- **In-Browser Memory Execution via Obfuscated JavaScript**: Attackers are abusing browser features and WebAssembly via obfuscated JS to build and execute fileless malware in memory, avoiding disk writes and static detection. [More info](https://www.bleepingcomputer.com/news/security/malicious-sites-use-javascript-to-build-malware-in-browser-memory/)

- **Rise of AI Hallucination Exploitation Tactics**: Security researchers highlight the convergence of "slopsquatting," "phantom domains," and "hallusquatting," where attackers proactively register domains hallucinated by LLMs to trick developers into downloading malicious assets. [More info](https://www.bleepingcomputer.com/news/security/slopsquatting-phantom-domains-and-hallusquatting-are-the-same-ai-attack/)

- **Over One-Third of Ransomware Victims Face Secondary Extortion**: Analysis shows that paying ransom demands rarely guarantees data safety, with over 33% of victims experiencing follow-up extortion demands shortly after payment. [More info](https://www.theregister.com/security/2026/07/22/over-a-third-of-ransomware-victims-re-extorted-after-paying/5276218)

- **GitHub & PyPI Add Time-Based Defenses Against Supply Chain Attacks**: Major package repositories introduced mandatory quarantine windows and delayed publications for new accounts to stall automated typosquatting and software supply chain attacks. [More info](https://www.bleepingcomputer.com/news/security/github-pypi-add-time-absed-defenses-against-supply-chain-attacks/)

- **Severe Android Malware Infections Spread Outside Official Play Store**: Intelligence confirms that major Android threats rely on sideloading via SMS phishing, deceptive ads, and unofficial APK mirrors rather than the official Play Store. [More info](https://www.malwarebytes.com/blog/inside-malwarebytes/2026/07/beyond-the-play-store-how-android-threats-really-spread)

- **ShinyHunters Breaches Fuel Mass Sextortion Campaign**: Exfiltrated database records leaked by ShinyHunters are powering over 2,000 automated sextortion emails that leverage real user credentials to coerce payment. [More info](https://www.bleepingcomputer.com/news/security/shinyhunters-data-leaks-fuel-2-000-sextortion-email-scam/)

## 💥 Breaches & Leaks

- **Ostium DeFi Platform Exploited for $23.75M**: Decentralized finance platform Ostium suffered a smart contract exploit involving reentrancy and oracle manipulation, draining $23.75 million from its primary liquidity vault. [More info](https://www.cysecurity.news/2026/07/ostium-confirms-2375-million-vault_0361549512.html)

- **Origin Energy Customer Data Exposed in Breach**: Australian energy supplier Origin Energy confirmed a data breach stemming from a third-party vendor vulnerability that compromised customer names, contacts, and billing info. [More info](https://securityaffairs.com/195973/data-breach/australian-energy-provider-origin-energy-disclosed-a-data-breach-impacting-customer-data.html)

- **Chick-fil-A Credential Stuffing Attack Affects 13,000+ Accounts**: Automated credential stuffing attacks against the Chick-fil-A mobile app exposed customer profiles and digital wallet funds, forcing widespread password resets. [More info](https://www.bleepingcomputer.com/news/security/chick-fil-a-data-breach-affects-more-than-13-000-customers/)

- **OnTrac Logistics System Network Intrusion**: Logistics firm OnTrac notified customers of a network intrusion that exposed internal shipping manifests, recipient contact details, and tracking data. [More info](https://www.bleepingcomputer.com/news/security/ontrac-notifies-customers-of-data-breach-after-network-hack/)

- **Stadler Rail Rejects $12.3M Ransomware Extortion Demand**: Train manufacturer Stadler Rail publicly refused to pay a $12.3 million extortion demand from the Everest ransomware group following a network intrusion and data theft incident. [More info](https://www.theregister.com/security/2026/07/23/stadler-rail-scoffs-at-eversts-123m-extortion-attempts/5276922)

## 📚 Others

- **Microsoft 365 Global Outage Caused by Deployment Bug**: A flawed maintenance update caused a massive global outage across Azure Active Directory and Exchange, disrupting Microsoft 365 services for millions of enterprise users. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-blames-massive-microsoft-365-outage-on-maintenance-bug/)

- **Worldwide ChatGPT Outage Linked to Database Maintenance**: OpenAI confirmed a widespread global downtime affecting ChatGPT and API services triggered by an anomaly during scheduled database maintenance. [More info](https://www.bleepingcomputer.com/news/artificial-intelligence/openai-confirms-chatgpt-is-down-worldwide/)

- **Europol Flags 4,340 Dark Web URLs in Massive Takedown**: Europol and global law enforcement agencies flagged and disrupted over 4,300 dark web URLs associated with illicit marketplaces, fraud forums, and severe criminal networks. [More info](https://www.theregister.com/cyber-crime/2026/07/24/europol-flags-4340-horrific-urls-linked-to-the-com/5278556)

---

[⬅ Back to Archive](https://pranakn.github.io)
