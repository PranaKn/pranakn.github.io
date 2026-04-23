---
title: "The SOC Anatomy Part 1: What is a SOC?"
date: 2026-04-22 21:00:00 -0300
categories: [BlueTeam, SOC]
permalink: /posts/soc-part1/
tags: [soc, infosec, beginners, risk-management]
pin: false
toc: true
comments: true
description: An introduction to the Security Operations Center, covering the CIA triad, security controls, and the roles within a modern SOC.
image:
  path: assets/img/posts/soc-2026-04-22.png
  alt: BlueTeam SOC - 22/04/26
---

> **Disclaimer:** Images were generated with AI. The written content is entirely my own.

# What is a SOC ? Where does it live? What does it eat?

## Introduction

Security Operation Center - or SOC, because cybersecurity loves acronyms (as you might already know or soon will) - is the place where a peculiar species known as information security (or cybersecurity, if we want to be precise and slightly dramatic) professionals live, breathe, and occasionally argue with dashboards and queries. 

The SOC is responsible for continuously monitoring and evaluating the security posture of an environment. In other words, that means tracking everything that happens across the infrastructure and responding when something looks weird, wrong, or very, very wrong. It’s where ongoing security operations are managed, incidents are investigated and sleep schedules go to die. 

This is achieved by collecting logs from a wide range of sources - routers, endpoints, servers, firewalls, cloud services, and that one legacy system nobody dares to touch. This logs are transformed into events and fed into a centralized, always-hungry, log-eating beast known as Security Information and Event Management system, or (SIEM). Don’t worry, we’ll dissect it’s anatomy later. 

If we had to summarize the functions of a SOC in one sentence, it would be: 

protect the CIA triad - Confidentiality, Integrity and Availability - of the data in cyberspace. 

Now that we’re past the opening statement, it’s time to dust off your hard drive - or SSD, if you are younger - and lay the groundwork for some once forgotten (or ignored) information security concepts and important keywords. Before alerts, incidents, and on-call rotations, we need a quick INFOSEC refresher: risk, access control, trust, policies, controls, and the frameworks that quietly hold the whole SOC together.

And yes - this part matters more than people like to admit it.

## Information Security Refresher

Information Security is the area that encompasses the protection of all data and information systems from unauthorized access, use, disclosure, disruption, modification or destruction. It primary objective is the CIA Triad, which we will explain in a moment. Whereas cybersecurity is a subset of InfoSec, which focuses specifically on protecting data that is in electronic form. It encompasses technologies, processes, and practices designed to protect networks, devices, programs, and data from attack, damage, or unauthorized access via digital means.

To make it easier to understand, information security is like guarding a pizza from your roommate. You lock the door, hide the slices and set rules for who can have a slice. While cybersecurity is the cameras, sticky note saying “Do Not Touch”, digital lock and maybe some ninja AI robot trying to stop the person from getting the prize… until it gets prompt-injected and lets them take a slice anyway.

Circling back to the CIA Triad, let’s dig deeper. The concept is built on three principles: confidentiality, integrity and availability. 

Confidentiality means protecting data from unauthorized access. Only users with proper authorization get a pizza slice.

Integrity focuses on maintaining the accuracy, reliability and consistency of data. It ensures that when someone goes for a slice, the pizza hasn’t turned into an apple pie. 

Finally, availability ensures that data and resources are accessible when needed. In other words, authorized users can get their pizza slice whenever they are hungry.

![CIATriad.png](assets/img/posts/CIATriad.png)

### Enforcing CIA Triad

Now that we understand the core concepts that information security uses to protect a business, let’s dwell into a way to actually enforce it. That’s where AAA framework comes in: Authentication, Authorization and Accounting.

Authentication verifies who you are (are you allowed to have a pizza slice ?), Authorization determines what you can do (can you take a slice or just look at it?), and Accounting tracks what happened (who ate how many slices and when). AAA turns the goals of confidentiality, integrity, and availability into something we can actually control and monitor in practice.

### What are we protecting against?

![LogsEventsAlertsIncidents.png](assets/img/posts/LogsEventsAlertsIncidents.png)

In the real world, systems, people and processes aren’t perfect, they have vulnerabilities, which are weaknesses that can be targeted by threats. When a threats meets a vulnerability, we get risks - the chance that our CIA principles are compromised. In simple terms: how easy is it for our arch-enemy to get a slice of pizza? 

Vulnerability, as mentioned earlier, is the weakness in a system, network or process that can be exploited to compromise on of the CIA principles. It exposes the organization to threats. For example, leaving the door to the room where the pizza is stored unlocked. 

A threat is the potential danger to the information or systems. In the real world, this could be malware, phishing, denial-of-service attacks. In our metaphor, it’s the suspicious person watching the room with binoculars, the weak password protecting the pizza safe, or even the rusty door hinges that might fail.

When a threat and vulnerability come together, they create Risk - the likelihood of exploiting and the potential impact. In other words, is that person with binoculars actually planning to steal the pizza, or just birdwatching? 

To monitor what’s happening in an environment, we rely on logs. Logs are records  action within a system. They help with troubleshooting, visibility, and security. If the safe could record who accessed it, when the door was opened, and whether anything unusual happened, those records would be logs.

From these logs, we identify security events. Occurrences that may be relevant to safeguarding information. For example, a message saying the pizza is still warm is an event, but not security-relevant. However, a record showing someone accessed the safe is.

When an event causes harms or represents a confirmed compromise, it becomes a security incident. For example, if Bob was in Japan a few minutes ago and is now accessing the pizza safe in New York, that’s an incident.

Finally, alerts are notifications generated by the devices or personnel indicating a potential security issue or suspicious activity. If someone fails to enter the pizza safe password 50 times, that should trigger an alert.

### Security Controls

To manage this lifecycle, we implement security controls to prevent, detect and respond to threats. These controls are layered through a defense-in-depth strategy. Many people compare this to slices of Swiss cheese - each layer has holes, but when stacked together, the gaps are covered. 

But you could also think of it like layers of an onion, an artichoke - or any food you like, as long as it has layers or holes you can stack to cover each other’s gap. These analogies change over time, so maybe swiss cheese get replaced one day. Maybe it becomes a dragon fruit…although at that point, we’ve probably lost the plot, and the pizza.

![SwissCheese.png](assets/img/posts/SwissCheese.png)

We have a few different types of controls which help structure our defenses. 

**Administrative controls** are policies and procedures that guide how the organization operates. This includes security policies, management procedures, incident response plans - or how to get coffee securely from the new coffee machine. 

Next we have **Technical Controls**. These are technology-based protections such as firewalls, EDRs, IDS and 2FA. Think of them as the extra safeguards on the coffee machine to prevent a coffee junkie form taking over and producing unlimited coffee.

**Physical controls** include  surveillance cameras, biometrics, fences and locks - anything that prevents physically access. In our example, this is the door protecting the room where the coffee machine is located.

Additionally, we also classify controls based on what they do. 

**Preventive controls** aim to stop incidents from happening. For example, only IT staff access to the coffee machine - since, clearly, they need it the most. Examples include IPS, ACLs and, Firewalls.

**Detective controls** help identify suspicious or malicious activities. Imagine a bell that rings every time someone tries to access the coffee room. IDS, SIEM, logs and cameras fall into this category.

**Corrective controls** reduce the impact of an intrusion and help restore systems. This includes backups, incident response plans, patch management - and, of course, an emergency reserve of coffee beans. 

**Deterrent controls** discourage attackers from attempting or continuing an attack. This could be warning signs, visible cameras, physical barriers, or even an HR announcement reminding not to leave the coffee machine on after hours.

Finally, we have **compensation controls**. These are alternative measures used when primary controls fail or aren’t feasible. For example, if the main access control system for the coffee room fails, an alarm might trigger when the door is force open.

### Risk

Now that we understand the controls we can implement, the next question should be: how do we decide what to prioritize? Not everything has the same importance. 

Risk is defined as the combination of probability (likelihood) and the impact, often represented in a matrix where these two elements form the axes. An example can be seen in the image below.

![Image 1: Risk Matrix](assets/img/posts/RiskImage_downsized.png)

To illustrate, imagine a web server with a moderate probability (likelihood) of compromise  due to its technologies and patch management practices. If the impact is minor (low) - because it does not represent significant loss to the company - then, based on the above risk matrix, the overall risk would be classified as moderate. 

This process is applied across the organization’s entire attack surface, assigning different risk levels to systems and assets, which helps prioritize security efforts and resource allocation. 

This leads us to risk treatment strategies. Based on the calculated risk, we can choose one of the following approaches:

**Acceptance**

We acknowledge the risk and decide not to act on it, usually because the potential impact is low or the cost of mitigation would be higher than the damage.

**Transference**

We shift the risk to a third party. For example, moving a local service to a SaaS solution transfers part of  the infrastructure risks to the provider.

**Avoidance** 

We eliminate the risk by removing the vulnerable element. For instance, replacing a system that is constantly exposed to vulnerabilities with a more secure alternative. 

**Mitigation** 

We reduce the risk to an acceptable level. For example, replacing password-based authentication with SAML - both carry risk, but at different levels.

A dedicated section on risk will be covered later, but for a SOC-focused context, this level of understanding is sufficient. 

Now, let’s move on to **Security Policies**.

### Security Policies

Security policies can be implemented at any stage of an organizations lifecycle, but they should be dynamic, evolving as the environment changes and as new technology and processes are adopted.

Ideally, they should be introduced early - alongside the growth of the organization. The earlier they are established, the easier and more cost-effective they are to design and enforce. Delaying their implementation often leads to increased complexity and higher costs later on.

With that in mind, there are many different types of security policies that can be implemented, depending on the organizations needs. Some of the most common include: 

**Acceptable Use Policy**

Defines what is allowed within the organization when using company resources. For example, are the customer service employees allowed to use the company computers to stream their favorite movies? If so, are there restrictions - like limiting content to appropriate material, or making sure Sponge Bob keeps his pants on? 

**Password Policy**

Defines how authentication should be handled, including password length, complexity, and rotation requirements. For example, can Bob from finance use “1234password” or “M0masboy” ? (Spolier: no, and Bob needs a talk.)

**Data Classification Policy**

Determines how data should be categorized and handled within the organization. Should we follow a standard like Traffic Light Protocol (TLP), or define our own model? How many classifications levels do we need - and do really need one just for pizza night ?

As a rule of thumb, organizations typically define at least the following levels: **Public** (can be shared freely), **Internal** (restricted to employees), Restricted/Need-to-know (limited to a specific group) and **Confidential/tops secret** (highly sensitive, limited to key personnel). 

It’s also important to use clear and intuitive naming. So, calling your classifications “mountain-white”, “cat-orange,” “grass-green”, and “deep-black” might sound creative, but it’s not very helpful.

### Access Control List (ACLs)

Now that we’ve been through a many of the basics of information security, let’s finish strong with Access Control List (ACLs). These define who can access what, when and under which conditions - whether systems, physical locations or data. Simplifying it: who gets the pizza, when and where. 

Let’s review a few models.

**Discretionary Access Control (DAC)**

 The owner of the resource decides who gets access. This provides flexibility, but has weaker security. Linux file permission is an example. “I bought the pizza. I decide who eats it”.

**Mandatory Access Control (MAC)**

Access is enforced by a central authority using classifications that users can’t override. Common in Military and government environments. “The pizza council has spoken. Only people in the third circle and above can eat pizza. The fourth circle may observe… from a safe distance.”

**Role-based Access Control (RBAC)**

Access is based on roles (admin, analyst, user, Karen), and users inherit permissions from those roles. Widely used in enterprise and IAM systems like AWS and Azure. “Pizza for all cybersecurity analysts. No pizza for marketing”

**Attribute-based access control (ABAC)**

Access decisions are based on attributes such as user, resource, and context. This allows very granular and dynamic control, but can be complex to manage. “Finance AND location = office AND time = business hours → Pizza slice”

**Rule-based Access Control**

Access is determined by system-enforced rules, often combined with other models. Examples include firewall rules, time-based access, and geolocation restriction. “10 minutes of pizza access for anyone wearing a blue t-shirt”

**Identity-based Access Control (IBAC)**

Permissions assigned directly to individual users. Simple, but hard to scale. “Bob is the only one who can get pizza”

Finally, while not an access control model itself, the principle of Least Privilege should be applied across all models. The idea is to grant only the access necessary - no more, no less. 

**Just Enough Access (JEA):** only minimal permissions is given to the users.

**Just-In-Time (JIT):** Privilege are granted only for the time needed to perform a task.

**Separations of Duties:** no single user has full control over critical processes.

**Privilege Creep:** the gradual accumulation of unnecessary access over time (and something we want to avoid).

## Back to the SOC

After this refresher and reviewing the basics of information security, it’s time to bring everything back to where everything actually happens - the SOC - and the main topic of this first blog post. 

All concepts we’ve discussed so far don’t live in isolation. They are actively used, monitored, and enforced inside the Security Operations Center. The SOC is where theory meets reality - and where things rarely go according to plan. 

To first understand how SOC operates, we first have to understand the people behind it. 

### SOC Roles

SOC is typically structured in tiers or levels, where each one has different responsibilities, expertise, and caffeine intake. 

**Tier 1 - Analyst (L1)**

First line of defense. Responsible for monitoring alerts, reviewing logs, and performing initial triage. Their job is to determine whether something is a false positive or requires further investigation. Other activities that encompass their responsibilities are incident triage, first-line analysis and investigation, documenting and reporting, escalation and collaboration, continuous improvement and cross-training. 

In pizza terms: they are the ones watching the pizza room cameras, noticing something suspicious, and asking, “Is that Bob… again?”.

**Tier 2 - Analyst (L2)**

First escalation point for cases the tier 1 analyst couldn’t solve. L2 analysts perform deeper investigations, correlate events, and determine whether an incident is actually occurring. 

L1: “Something looks weird” 

L2 “Yep, this is definitely a problem.” 

They are responsible for analyzing logs, verifying anomalies - if Bob was really in Japan five minutes ago, and confirming whether the pizza is actually under attack.

While responsibilities vary between organizations, Tier 2 analysts are typically more senior  and often take ownership of the Incident Response activities, escalated alerts, identifying patterns and trends, and developing mitigation strategies. 

**Tier 3 - Analyst (L3)**

At this level, the approach shifts from reactive to proactive. Tier 3 analyst are the threat hunters, responsible for handling complex security incidents, developing detection rules, and integrating threat intelligence to improve defenses. 

Think of them as detectives who start asking questions before a compromise happens. They investigate behaviors, track patterns, and study attacker techniques - essentially watching the suspicious person outside the pizza room before they even try the door.

**SPECIALIZED ROLES**

**Incident Responder**

The specialist who knows the environment inside out - and the pizza… I mean, the systems and devices. 
They operate in the middle of chaos and are responsible for containing, eradicating, and recovering from incidents. They understand the tools, the processes, and how everything connects, helping improve defenses and response capabilities over time.

**Malware Analyst**

Responsible for analyzing malicious programs, files and the awkward looking olive on the pizza. He understands how the executables work in a lower level and reverse engineer malware to identify behavior, and help develop detection and protections. 

They don’t just see the pizza stolen - they figure out how the thief picked the locked, what tools were used and how to stop it next time.

**Threat Intel Analyst**
Focuses on studying the external threat landscape to track adversaries, campaigns, tools, and techniques, providing context that helps the SOC anticipate attacks.

They are the ones reading about types of pizza thefts across the campus and warn the security teams before it happens here.

**Security Engineer**

Bob the builder. Builds, configures, maintains security tools and infrastructure (SIEM, EDR, IDS, etc.). They ensure everything runs properly and that detections are effective.

“If the SOC is the kitchen, they are the ones installing and fixing the oven.”

**Vulnerability Manager**

Identifies, prioritizes, and tracks vulnerabilities across the environment. Works closely with teams to ensure remediation happens.

“They make sure the door to the pizza room isn’t left unlocked - or at least that someone fixes it quickly”

**Forensic Analyst**

Investigates incidents after they occur, collecting and analyzing evidence to understand what happened.

“They reconstruct the crime scene and explain exactly how the pizza disappeared.” 

**Compliance and Governance**

Ensures the organization follows regulatory requirements, standards, and internal policies.

“They make sure there are rules about pizza - and that people actually follow them”

**Security Awareness and Training**

Educates users, creates training programs, and reinforces security policies across the organization. 

“They teach people not to accept free pizza coupons in exchange for opening the door.”

**MANAGEMENT**

**SOC Team Lead**

Oversees SOC operations, manages analysts, and ensures processes are followed. Keeps the tam aligned and operations running smoothly. 

“Let’s all do their job to protect the pizza, and Steve, don’t eat it this time”

**Director of Security**

Responsible for broader security strategy, aligning SOC operations with business goals.

“They decide how important the pizza really is to the company”

**CISO (Chief Information Security Officer)**

The executive responsible for the overall security posture of the organization. Defines strategy, risk appetite, and long-term direction. And sometimes, provides the pizza.

“They decide if the company invests in protecting the pizza…or accepts the risk of losing it”

![SOCRoles.png](assets/img/posts/SOCRoles.png)

### SOC Functions

SOC functions can be broadly divided into two groups: **Reactive** and **Proactive.**

Reactive functions focus on responding to threats that have already been detected, while proactive functions tries to anticipate, prevent, and improve defenses before incidents occur.

Acting when someone is already trying to get a slice of pizza is reactive. Verifying everyone’s background before they enter the pizza room is proactive.

**REACTIVE FUNCTIONS**

Day-to-day operations of most SOC teams. Responding to alerts, investigating incidents, and dealing with whatever is currently on fire.

**Monitoring and Detection**

Continuous monitoring of systems, networks, and logs to identify suspicious activity. Alerts are generated and the SOC becomes aware of potential threats.

**Incident Response**

A confirmed threat that may impact the company needs to be handled. The action to contain, eradicate, and recover from the incident fits here.

**Forensic Analysis**

Throughout investigation after an incident to understand what happened, how it happened, and what was affected.

**Malware Analysis** 

Reversing a malicious binary, code or file to understand behavior, impact and collect IoCs for further investigation

**PROACTIVE FUNCTIONS**

Aim to improve the SOC’s ability to detect and prevent attacks before they happen. Nothing beats predicting the attackers before they act right?! If only we could apply the same logic to lottery numbers.

**Threat Intelligence**

The art of collecting and analyzing information from various sources to track threats, trends, attackers, and campaigns. It provides context and help improve detection capabilities.

“There have been multiple pizza thefts in other finance offices, where a blue-shirt individual was seen before the compromise. We might be next… maybe keep an eye on that guy watching birds”

**Threat Hunting** 

The hunters of the blue team. They proactively search for threats that have not triggered alerts, using hypothesis and behavioral analysis, often supported by the threat intelligence.

**Vulnerability Management**

The process of identifying, prioritizing, and remediating weaknesses in systems before they can be exploited. 

**Security Awareness Training**

Educate users to reduce human-related risks. Because sometimes the biggest vulnerability is not the system, but the users using it.

“Teach user well, and most threats won’t even get the chance to say ‘surprise, surprise’”

A mature SOC doesn’t just react to pizza theft, it learns from it, predicts it, and eventually stops it before it even starts.

The section is already long. Let’s stop here and continue with SOC cycle at part 2. See you there = )
