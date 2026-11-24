---
title: "Cybersecurity Newsfeed - 25/11/26"
date: 2026-11-24 09:00:00 -0300
categories: [News]
permalink: /posts/news-25-11-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-11-25.png
  alt: Cybersecurity Newsfeed - 25/11/26
---

# Cybersecurity Newsfeed

## 📅 25/11/26

## 🛡️ Vulnerabilities

  - **CISA Adds Three Exploited Flaws to KEV Catalog**: CISA added three actively exploited vulnerabilities to its Known Exploited Vulnerabilities catalog: CVE-2026-131914, an insecure deserialization remote code execution bug in Idunno.AntiCsrf affecting ASP.NET WebForms applications; CVE-2026-132165, a critical Drupal Core installer flaw allowing unauthenticated attackers to trigger reinstallation and execute arbitrary code; and CVE-2026-132224, an actively exploited flaw impacting Optimizely. Federal agencies must remediate or mitigate these exposures immediately, as Idunno.AntiCsrf currently lacks an official patch, requiring organizations to audit legacy web servers and apply compensating controls. [More info](https://www.cisa.gov/news-events/alerts/2026/11/24/cisa-adds-three-known-exploited-vulnerabilities-catalog)

  - **VMware Patches Critical ESX and vCenter Flaws**: Broadcom released urgent security updates addressing 23 vulnerabilities across VMware ESX and vCenter Server. The patches resolve CVE-2026-123903, a critical CVSS 9.8 authentication bypass in the VMware Directory Service (`vmdir`), alongside heap out-of-bounds write flaws (CVE-2026-123910, CVE-2026-123911) enabling code execution in ESX. Administrators must prioritize patching virtualization management planes to prevent unauthenticated administrative takeover and hypervisor compromise. [More info](https://www.securityweek.com/vmware-updates-patch-critical-esx-vcenter-vulnerabilities/)

  - **Microsoft Fixes Azure API Management Classic Flaw**: Microsoft remediated a critical vulnerability affecting Azure API Management Classic tiers that threat actors actively exploited to harvest customer credentials. The flaw allowed unauthorized access to sensitive Named Values secrets and API credentials stored within affected instances, impacting major enterprise environments. Cloud defenders using Classic tiers should audit access logs for anomalous retrieval activity and rotate all stored API keys and secrets immediately. [More info](https://thehackernews.com/2026/11/microsoft-fixes-azure-api-management.html)

  - **"God Mode" Flaws Exposed Border-Control Systems**: Researchers uncovered severe vulnerabilities in online visa and border-control portals used by Nigeria, Ethiopia, Zambia, Sri Lanka, Fiji, and Ghana. Dubbed "God Mode" flaws, the bugs granted unauthorized administrative access capable of disrupting traveler entry, altering visa statuses, and exposing sensitive border-crossing data. While authorities were notified to remediate the issues, the findings highlight systemic security gaps in critical government travel infrastructure. [More info](https://www.darkreading.com/vulnerabilities-threats/god-mode-flaws-wreak-border-control-havoc)

  - **Elecbrakes Bluetooth Flaws Expose Trailers to Forced Braking**: Critical Bluetooth vulnerabilities, including CVE-2026-125273 and CVE-2026-96805 (CVSS 9.6), affect Elecbrakes EB2, VM1, and legacy ELBC 2000 trailer brake controllers. Because the devices lack authentication and pairing protections, nearby attackers within Bluetooth range can replay commands, disable brakes, or apply sudden braking force while vehicles are at highway speeds. Owners should immediately apply available firmware updates for EB2 and VM1 models. [More info](https://www.securityweek.com/elecbrakes-bluetooth-vulnerabilities-expose-trailers-to-forced-braking/)

## 🎯 Adversaries

  - **Webworm Customizes SoftEther VPN for Stealth Espionage**: The China-aligned espionage group Webworm is deploying a modified build of the open-source SoftEther VPN Bridge, rebranded internally as "NtMonitor VPN," to maintain covert remote access inside compromised networks. By stripping identifying signatures and altering network traffic fingerprints, the operators evade standard perimeter detection and blend command-and-control communications with legitimate administrative traffic. Defenders should inspect endpoints for unauthorized VPN bridge binaries and anomalous outbound tunnel behavior. [More info](https://www.darkreading.com/perimeter/webworm-slithers-customized-softether-vpn)

  - **Inception Extortion Gang Launches Large-Scale SSO Vishing**: A newly tracked extortion operation dubbed Inception is conducting aggressive voice-phishing campaigns targeting corporate single sign-on credentials. Threat actors impersonate IT support personnel over the phone to trick employees into authenticating on phishing kits across dozens of decoy domains, bypassing multi-factor authentication. Once inside identity providers, attackers pivot into cloud SaaS repositories to exfiltrate sensitive corporate data for extortion. [More info](https://www.bleepingcomputer.com/news/security/new-inception-extortion-gang-launches-large-scale-vishing-campaign/) | [More info](https://www.infosecurity-magazine.com/news/inception-extortion-sso-vishing/)

  - **Iran-Aligned Volant Manticore Uses IPFS C2 Backdoor**: Iranian threat actor Volant Manticore is targeting organizations in Cyprus and Saudi Arabia—particularly within the healthcare sector—using a 64-bit Windows backdoor named KuboShell alongside a reworked MuddyWater framework. Delivered via PowerShell stagers, KuboShell abuses the decentralized InterPlanetary File System (IPFS) network as a resilient command-and-control channel. Utilizing peer-to-peer IPFS nodes allows operators to obscure infrastructure and bypass traditional domain-based firewall blocking. [More info](https://thehackernews.com/2026/11/iran-aligned-volant-manticore-uses-ipfs.html)

  - **ShinyHunters Resurfaces Using Legacy PGP Keys**: Following recent FBI arrests targeting suspected members, the notorious ShinyHunters extortion group resurfaced on a new data leak site claiming operational continuity. The operators signed their announcement using original 2020 RaidForums and Empire Market PGP keys and announced plans to migrate stolen data onto a new content delivery network. However, analysts caution that because those older keys were reportedly shared among multiple associates, impersonators could be attempting to revive the brand. [More info](https://www.bleepingcomputer.com/news/security/shinyhunters-resurfaces-after-fbi-arrests-uses-old-pgp-keys-as-proof/)

  - **Hackers Compromise Check Point Servers at 22 Organizations**: Threat cluster GT13 compromised 24 Check Point Security Management servers across 22 organizations in 17 countries by exploiting authentication bypass flaws, including CVE-2026-16232. Attackers obtained administrative tokens to steal firewall databases, internal certificate authority files, and credentials while unloading firewall policies to probe downstream Windows Domain Controllers. Administrators must restrict SmartConsole trusted client access and audit logs for unauthorized application-token logins. [More info](https://www.bleepingcomputer.com/news/security/hackers-compromise-check-point-servers-in-22-organizations/)

## 📈 Trends

  - **Autonomous AI Agents Automate Multi-Platform Intrusions**: Palo Alto Networks Unit 42 tracked over ten global intrusion campaigns where threat actors deployed autonomous AI agents to execute end-to-end attacks. These agentic systems automate reconnaissance, vulnerability exploitation, and lateral movement across hybrid environments using standard administrative utilities. Defenders must adapt detection engineering to spot machine-speed execution anomalies and behavioral patterns characteristic of AI-orchestrated intrusions. [More info](https://unit42.paloaltonetworks.com/autonomous-ai-agent-threat-campaigns/)

  - **Automated Bots Test Exposed AWS Keys Within 8 Seconds**: New threat telemetry reveals that automated credential-harvesting bots scan public repositories and test leaked AWS access keys within just eight seconds of exposure. This near-instantaneous exploitation window renders manual incident response or delayed key revocation ineffective once secrets hit public code platforms. Organizations must enforce pre-commit secret scanning, short-lived IAM credentials, and automated key revocation workflows. [More info](https://www.malwarebytes.com/blog/ai/2026/11/a-bot-tested-an-aws-key-within-8-seconds-of-exposure)

  - **Researchers Uncover AI Agent Instruction Hijacking Path**: Security researchers at Ox Security identified a new attack vector that manipulates autonomous AI agents by poisoning their instruction sets rather than deploying traditional executable malware. By injecting malicious directives into context files or automated remediation workflows, attackers can hijack agent privileges to exfiltrate data or alter configurations. Organizations deploying agentic tools must strictly validate instruction sources and enforce least-privilege guardrails. [More info](https://www.infosecurity-magazine.com/news/researchers-new-ai-attack-path/)

## 💥 Breaches & Leaks

  - **Radware Breach Exposes Customer Cloud Access Keys**: Cloud security provider Radware disclosed a security incident that exposed customer cloud access keys stored within its infrastructure. While the company is investigating the scope of unauthorized access, exposed cloud credentials create immediate downstream risks of lateral movement and resource hijacking across customer environments. Radware has urged all affected customers to immediately revoke and rotate any cloud access keys shared with its services. [More info](https://www.bleepingcomputer.com/news/security/radware-discloses-breach-exposing-customer-cloud-access-keys/)

  - **Researchers Hijack Five US Treasury Subdomains for $3 Each**: Security researchers demonstrated how dangling DNS records allowed them to claim five abandoned US Treasury subdomains for roughly three dollars apiece. By registering expired cloud endpoints still referenced by official government DNS entries, an attacker could host convincing phishing pages or intercept sensitive session cookies under trusted `.gov` domains. The incident underscores the necessity of continuous attack surface monitoring and DNS hygiene. [More info](https://hackread.com/researchers-take-over-5-us-treasury-subdomains/)

  - **UK Retailer Next Discloses Supplier Cyber Incident**: British fashion retailer Next confirmed that a cyberattack targeting an online third-party supplier exposed internal company information. Next clarified that its core corporate networks were not breached and found no evidence that customer personal or financial records were compromised. However, the company warned customers to remain vigilant against targeted phishing lures exploiting news of the supply-chain incident. [More info](https://hackread.com/uk-retailer-next-cyber-incident-online-supplier/)

## 📚 Others

  - **International Police Disrupt 57 Illegal Streaming Services**: Law enforcement agencies across 11 countries, coordinated by Europol, dismantled 57 illegal IPTV and streaming operations spanning 321 domains that attracted over 7.3 million annual visits. Working alongside cryptocurrency firms, investigators traced $28.5 million in illicit crypto payments to dismantle the underlying financial networks. The crackdown highlights intensified cross-border enforcement against digital piracy infrastructure. [More info](https://www.bleepingcomputer.com/news/security/police-disrupt-57-illegal-streaming-services-with-73-million-visits/)

  - **OpenAI and Cisco Launch Shirudo AI Linux Shield Tool**: OpenAI and Cisco introduced Shirudo, an open-source runtime defense tool combining AI-generated micropatches with Linux eBPF and TPM attestation to block exploit attempts on unpatched systems without service restarts. Distributed as cryptographically signed packages, Shirudo acts as a temporary buffer against zero-day flaws until official vendor patches can be deployed. Currently, the tool remains limited to Linux environments with compatible kernel hooks. [More info](https://www.bleepingcomputer.com/news/security/new-shirudo-tool-uses-ai-to-shield-unpatched-linux-systems-from-exploits/)

  - **Microsoft Previews Consolidated Windows Baseline Security Checks**: Microsoft announced plans to unify eight existing Windows security checks—including kernel debugger and vulnerable driver protections—into a single baseline health evaluation slated for 2027. The feature will flag missing OS safeguards for one-click remediation while exposing device posture signals to third-party applications. Consequently, enterprise apps, anti-cheat engines, or exam platforms may soon block access if a Windows PC fails baseline checks. [More info](https://www.malwarebytes.com/blog/news/2026/11/new-windows-security-check-could-let-apps-block-access)

---

[⬅ Back to Archive](https://pranakn.github.io)
