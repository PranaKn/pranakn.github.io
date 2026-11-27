---
title: "Cybersecurity Newsfeed - 27/11/26"
date: 2026-11-26 21:40:00 -0300
categories: [News]
permalink: /posts/news-27-11-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-11-27.png
  alt: Cybersecurity Newsfeed - 27/11/26
---

# Cybersecurity Newsfeed

## 📅 27/11/26

## 🛡️ Vulnerabilities

  - **Unpatched Critical Danfoss Refrigeration Flaw (CVE-2026-129713)**: CISA issued an ICS advisory warning of a critical unauthenticated stack-based buffer overflow (CVSS 9.8) in the CGI handler of Danfoss AK-SM 8xxA Series refrigeration controllers (versions 5.4.0 and earlier). Remote attackers can send crafted HTTP/S POST requests to trigger memory corruption, web server restarts, or arbitrary code execution without authentication. No patch is currently available until upcoming firmware version 5.5.x; administrators must isolate units behind VPNs, enable Strict mode, and enforce strong passwords. [More info](https://www.infosecurity-magazine.com/news/cisa-alert-danfoss-critical-flaw/)

  - **Critical Juniper Session Smart Conductor Flaw Exploited (CVE-2026-103406)**: Juniper Networks and CISA confirmed active exploitation of a critical OS command injection vulnerability (CVSS 9.8) in Session Smart Conductor's AutomatedProvisioner service. Remote attackers can execute arbitrary root commands via a crafted Salt minion ID. Added to CISA's KEV catalog under BOD 26-04, organizations must urgently upgrade to patched versions 7.2.3, 7.1.7, or 7.0.5. [More info](https://www.securityweek.com/critical-juniper-session-smart-conductor-flaw-exploited-in-attacks/)

  - **Drupal Site Takeover Flaw Under Active Attack (CVE-2026-136716)**: Drupal warned of an actively exploited, highly critical vulnerability stemming from improper condition checks in incomplete or unusual installation states left exposed after the recent Fail2Install (CVE-2026-132165) patch. Attackers can abuse accessible `install.php` endpoints to achieve full site takeover. Administrators must upgrade to Drupal 11.4.14, 11.3.23, or 10.6.23, execute `update.php`, and audit user 1 account integrity. [More info](https://thehackernews.com/2026/11/drupal-warns-of-new-highly-critical.html)

  - **CISA Adds 10 Actively Exploited Flaws to KEV Catalog**: CISA added ten vulnerabilities to its Known Exploited Vulnerabilities catalog, including five Mitel MiCollab AWV flaws (CVE-2026-133275, CVE-2026-133303, CVE-2026-133311, CVE-2026-133323, CVE-2026-133324) weaponized in rapid AI-assisted intrusions to achieve root and domain controller access within 32 minutes. The update also covers Vates Xen Orchestra auth bypass (CVE-2026-133469), Juniper Session Smart Conductor (CVE-2026-103406), and three Danfoss AK-SM 800A flaws (CVE-2023-25914, CVE-2023-25915, CVE-2025-41450) linked to Iranian attacks on European supermarkets. [More info](https://thehackernews.com/2026/11/hackers-exploit-10-vulnerabilities.html)

## 🎯 Adversaries

  - **China and North Korea Adopt ARTEX AI Offensive Tool**: Microsoft disclosed that state-backed threat actors in China—including Salt Typhoon—and North Korea have integrated the ARTEX artificial intelligence offensive framework into their attack toolkits to breach global technology systems, accelerating reconnaissance and intrusion workflows. [More info](https://www.theregister.com/security/2026/11/26/microsoft-hackers-in-china-n-korea-using-artex-ai-tool-to-break-into-global-tech-systems/5312433)

  - **North Korea's PolinRider Poisons Over 7,600 GitHub Repos**: North Korean threat actors behind PolinRider injected obfuscated Python and JavaScript loaders into over 7,600 GitHub repositories and compromised npm packages using stolen developer tokens and fake hiring assessments. Leveraging the NullReceiver technique, the malware reads Ethereum blockchain transactions to dynamically resolve C2 servers and deliver infostealers targeting developer tools like VS Code and Cursor. [More info](https://thehackernews.com/2026/11/north-korea-linked-polinrider-poisons.html)

  - **Cyberattack Halts Wyoming Uranium Mining Operations**: Peninsula Energy suspended trading and shut down operations at its Lance uranium project in Wyoming following a disruptive cyber incident affecting operational systems, though administrative networks reportedly remained unaffected. [More info](https://www.theregister.com/security/2026/11/26/wyoming-uranium-operation-shuts-down-after-cyberattack/5312323)

  - **SYS010 Malware Abuses Facebook Ads and Browser Policies**: Bitdefender uncovered the SYS010 campaign using malicious Facebook ads impersonating wallpaper software to distribute Trojanized MeisterTask installers. The malware enrolls Chrome, Firefox, and Edge into attacker-controlled management policies to force-install extensions that hijack Meta Business session cookies and read or delete Gmail and Outlook messages to hide security alerts. [More info](https://hackread.com/facebook-ads-fake-wallpapers-sys010-malware-windows/)

  - **GoodGuys Phishing Impersonates Brands via Fake Expert Interviews**: Push Security detailed the "GoodGuys" phishing campaign impersonating brands like Google Cloud, Nvidia, and SpaceX via legitimate platforms such as HireVue and SendGrid. Offering up to $600 for fake interviews, AI-built credential harvesting pages relay real-time Google and Okta MFA prompts to hijack corporate SSO accounts. [More info](https://www.bleepingcomputer.com/news/apple/fake-paid-expert-interviews-impersonate-brands-to-steal-google-logins/)

  - **Remus Infostealer Masquerades as Google Sheets Extension**: GenDigital revealed that Remus malware's advertised "Gmail zero-day" is actually a malicious unpacked Chrome extension disguised as "Google Sheets." By modifying Chrome profiles and enabling Developer Mode to bypass Chrome 137+ restrictions, the add-on persistently scrapes unread emails across ten account slots even after password resets. [More info](https://www.bleepingcomputer.com/news/security/remus-malware-steals-gmail-messages-via-fake-google-sheets-extension/)

## 📈 Trends

  - **DOM Mirroring Phishing Kits Lead Security Bypasses**: Push Security reported that DOMDIFFER, an Adversary-in-the-Middle phishing kit utilizing real-time DOM mirroring from an attacker's browser, achieved the highest breakthrough rate against email, web gateway, and safe browsing controls from August to October 2026, frequently leveraging fake Google Voice calendar lures to bypass MFA. [More info](https://thehackernews.com/2026/11/most-wanted-phishing-kits-and.html)

  - **Preinstalled Keenadu Malware Found on 220,000+ Android Devices**: Kaspersky warned that supply-chain firmware infections grew over 2.5x in 2026, with the modular Keenadu backdoor discovered preinstalled in the system partition of over 220,000 Android devices. Remaining dormant for months before activation, Keenadu and Triada account for 88% of preinstalled mobile malware and cannot be removed by standard antivirus tools. [More info](https://www.helpnetsecurity.com/2026/11/26/keenadu-malware-android-devices/)

  - **Over 4,400 Malicious Domains Target Holiday Shoppers**: FortiGuard Labs' 2026 Holiday Season Cyber Threats Report identified over 4,400 newly registered malicious shopping and delivery domains, alongside 1.72 million retail-related infostealer logs circulating underground, AI-assisted fraud tools, and active exploitation of e-commerce platforms like Magento and PrestaShop. [More info](https://www.helpnetsecurity.com/2026/11/26/fortinet-holiday-shopping-cyber-threats-report/)

  - **2026 Counter-Strike 2 Scam Tactics Target Steam Traders**: Cybercriminals are targeting CS2 players using fake tournament voting pages to hijack Steam API keys for automated bot trade swaps, alongside abusing Valve's seven-day trade reversal feature to reclaim skins after receiving off-platform payments. [More info](https://hackread.com/cs2-scams-2026-what-players-should-watch-out-for/)

  - **ThreatsDay Bulletin: 250+ Sleeper Extensions & Exposed AI Servers**: Weekly threat highlights include Microsoft uncovering 250+ "SleeperWidget" browser extensions that activate adware and data theft only when installed via paid search ads, Rapid7 finding thousands of unauthenticated Ollama AI servers vulnerable to LLMjacking, a fake Minecraft Fabric mod delivering a Polygon-backed Python stealer, and CrowdStrike's record $43.9B acquisition of Zscaler. [More info](https://thehackernews.com/2026/11/threatsday-250-rogue-extensions-10m.html)

## 💥 Breaches & Leaks

  - **1Password Discloses Source Code and Customer Data Breach**: 1Password confirmed a security incident after attackers compromised an employee's corporate GitHub account on November 19, 2026, accessing private repositories, CI/CD systems, and backend services. While encrypted customer vaults and secret keys remained uncompromised, attackers exfiltrated customer names, emails, user IDs, SRP parameters, and recovery tokens. [More info](https://www.theregister.com/security/2026/11/26/hackers-help-themselves-to-1passwords-source-code-and-customer-data/5312317)

## 📚 Others

  - **OpenAI Fixes GPT-6.2 Astra Billing Bug, Increasing Limit Speed**: OpenAI resolved a billing bug that previously undercounted token usage on GPT-6.2 Astra and Sol, warning subscribers that usage limits will now deplete 40% and 25% faster respectively, while issuing a one-time banked usage reset to affected tiers. [More info](https://www.bleepingcomputer.com/news/artificial-intelligence/openai-warns-gpt-62-astra-will-hit-usage-limits-40-percent-faster-because-it-fixed-a-bug/)

  - **NordVPN Launches 2026 Black Friday VPN Promotion**: NordVPN rolled out its 2026 Black Friday and Cyber Monday promotion, offering up to 78% off two-year subscription plans plus three additional months of service across its 6,900-server WireGuard-based network. [More info](https://www.bleepingcomputer.com/news/security/nordvpn-black-friday-deal-get-78-percent-off-vpn-plans-in-2026/)

---

[⬅ Back to Archive](https://pranakn.github.io)
