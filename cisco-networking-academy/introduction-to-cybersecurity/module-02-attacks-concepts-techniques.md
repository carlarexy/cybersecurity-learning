# Module 02 — Attacks, Concepts & Techniques

## 📌 Overview

This document records my learning from **Module 2 of Cisco Networking Academy's Introduction to Cybersecurity course**.

This module focused on common cybersecurity threats, attack methods, techniques used by attackers, and the different ways systems, networks, devices, and users can be targeted.

The module helped me understand that cyberattacks can take many forms. Attackers can use malicious software, deception, exploitation of vulnerabilities, wireless and mobile techniques, and other methods to gain unauthorized access, steal information, disrupt services, or cause damage.

For me, this module was particularly useful for connecting cybersecurity theory with the practical question of **how attacks actually happen and what defenders need to look for**.

---

## 🎯 Learning Objectives

Through this module, I focused on understanding:

- Common cybersecurity threats
- Common attack techniques
- How attackers use deception to target victims
- How vulnerabilities can be exploited
- Different forms of malware
- Wireless and mobile device attacks
- Other common types of cyberattacks
- The potential impact of successful attacks
- Why understanding attack methods is important for cybersecurity professionals

---

## ⚠️ 1. Common Cybersecurity Threats

A cybersecurity threat is a potential action, event, or situation that can negatively affect a system, network, device, user, or information.

Threats can come from different sources and can involve different methods of attack.

| Threat Category | Description |
|---|---|
| Malware | Malicious software designed to compromise, damage, disrupt, or gain unauthorized access to systems |
| Phishing | Deceptive communication designed to trick users into revealing information or performing an unsafe action |
| Social Engineering | Manipulating people into providing information, access, or assistance to an attacker |
| Password Attacks | Attempts to obtain, guess, or compromise account credentials |
| Denial-of-Service | Attempts to make systems or services unavailable to legitimate users |
| Man-in-the-Middle | Intercepting or interfering with communication between parties |
| Exploitation | Taking advantage of weaknesses in systems, applications, devices, or networks |
| Wireless Attacks | Attacks targeting wireless communications, devices, or networks |

Understanding these categories gives me a framework for recognizing the different ways an organization can be targeted.

---

## 🦠 2. Malware

Malware is software created with malicious intent.

Different types of malware can behave differently depending on the attacker's objectives.

| Malware Type | General Purpose |
|---|---|
| Virus | Malicious code that attaches itself to files or programs and can spread when the infected file is executed |
| Worm | Malware that can replicate and spread across systems or networks |
| Trojan | Malicious software disguised as legitimate software or files |
| Ransomware | Malware that restricts access to systems or data and is commonly associated with extortion |
| Spyware | Software designed to secretly monitor activity or collect information |
| Adware | Software that displays unwanted advertisements and may also track user activity |
| Rootkit | Malware designed to maintain privileged access while attempting to hide its presence |
| Bot | A compromised device that can be controlled remotely, potentially as part of a larger botnet |

One of the main things I took away from this section is that **malware is a broad category rather than a single type of threat**.

Different malware behaves differently, which means defenders need to understand the indicators and risks associated with different forms.

---

## 🎭 3. Deception & Social Engineering

Not every cyberattack begins with a technical vulnerability.

Attackers can also target people by manipulating them into revealing information, opening malicious files, clicking unsafe links, or performing actions that benefit the attacker.

This is commonly associated with **social engineering**.

### Phishing

Phishing involves deceptive communication designed to trick a target.

A phishing message may attempt to convince someone to:

- Reveal login credentials
- Open a malicious attachment
- Click a malicious link
- Transfer money
- Provide sensitive information
- Install malicious software

### Why Social Engineering Works

Social engineering often takes advantage of human behaviour.

Attackers may create a sense of:

- Urgency
- Fear
- Curiosity
- Trust
- Authority

This reinforced for me that cybersecurity is not only about protecting technical systems.

**People are also part of an organization's security environment.**

---

## 🔓 4. Vulnerabilities and Exploitation

A vulnerability is a weakness that can potentially be used to compromise a system, application, device, or network.

Attackers look for vulnerabilities because exploiting them may allow unauthorized access or other malicious actions.

A simplified relationship is:

**Vulnerability → Exploitation → Compromise → Impact**

Examples of weaknesses that can create security risks include:

- Outdated software
- Weak passwords
- Misconfigured systems
- Unpatched vulnerabilities
- Insecure services
- Poor access controls
- Human error

This helped me understand why identifying and reducing vulnerabilities is an important part of cybersecurity.

A vulnerability may exist for a long time without being exploited, but once an attacker discovers and successfully exploits it, the consequences can become serious.

---

## 💻 5. Cyberattacks

A cyberattack is an attempt to compromise the confidentiality, integrity, or availability of systems, networks, devices, or information.

Attackers may use different techniques depending on their target and objectives.

| Attack Type | Potential Objective |
|---|---|
| Credential Attacks | Obtain unauthorized access to accounts |
| Malware Attacks | Infect systems and perform malicious actions |
| Denial-of-Service | Disrupt access to systems or services |
| Exploitation | Take advantage of a technical vulnerability |
| Phishing | Trick users into revealing information or taking an unsafe action |
| Data Theft | Obtain sensitive or valuable information |
| Network Attacks | Target network communication, devices, or services |

The same organization can potentially face multiple attack types at the same time.

This means cybersecurity teams need a layered approach to protection rather than relying on one defensive control.

---

## 📡 6. Wireless & Mobile Device Attacks

Wireless networks and mobile devices introduce additional security considerations.

Wireless communications can be targeted because devices communicate over radio signals rather than through a physical cable.

Mobile devices can also contain sensitive information and provide access to organizational services and systems.

Potential risks include:

- Unauthorized wireless access
- Weak wireless security
- Rogue access points
- Device theft
- Malicious applications
- Unsecured connections
- Compromised mobile devices

This section reinforced the idea that cybersecurity needs to account for the full environment in which users and systems operate.

Modern organizations are not protecting only desktop computers and servers. They also need to consider laptops, smartphones, wireless networks, applications, and other connected devices.

---

## 🌐 7. Other Forms of Attack

Cyberattacks can involve many different techniques, and some do not fit neatly into a single category.

Examples include:

- Denial-of-Service attacks
- Man-in-the-Middle attacks
- Password attacks
- Web-based attacks
- Network-based attacks
- Physical attacks against devices or infrastructure

The technique selected by an attacker depends on factors such as:

- The target
- The attacker's access
- Available vulnerabilities
- Technical capability
- Resources
- Final objective

This helped me understand why cybersecurity professionals need broad knowledge of attack techniques rather than focusing on only one type of threat.

---

## 🧩 8. Understanding the Attack Process

A useful way for me to think about an attack is as a sequence of events.

A simplified representation is:

**Target → Weakness → Attack Technique → Compromise → Impact**

For example:

**Target → Weak Authentication → Credential Attack → Unauthorized Account Access → Potential Data Exposure**

Thinking about attacks in stages can help a security professional identify:

- Where the attack started
- Which weakness was involved
- How the attacker gained access
- What systems or information were affected
- Where defensive controls could have interrupted the attack

This way of thinking will become increasingly important as I progress into practical security monitoring and incident investigation.

---

## 🔐 9. Relationship to the CIA Triad

The attacks discussed in this module can affect one or more parts of the **CIA Triad**.

| Security Principle | Meaning | Example Impact |
|---|---|---|
| Confidentiality | Preventing unauthorized access to information | Sensitive data is stolen or exposed |
| Integrity | Preventing unauthorized modification of information | Records or system data are altered |
| Availability | Keeping systems and information accessible when needed | A service becomes unavailable |

For example:

- Data theft primarily affects **confidentiality**.
- Unauthorized modification affects **integrity**.
- A denial-of-service attack affects **availability**.

Understanding the potential impact of an attack helps security professionals determine what needs to be protected and monitored.

---

## 🧠 10. What I Learned

The main concepts I took away from this module include:

1. Cybersecurity threats can target technology, people, applications, networks, and information.
2. Malware comes in different forms and can have different objectives and behaviours.
3. Social engineering demonstrates that people can be targeted just as effectively as technical systems.
4. Vulnerabilities can become serious security risks when attackers are able to exploit them.
5. Cyberattacks can affect confidentiality, integrity, availability, or multiple parts of the CIA Triad at the same time.
6. Attackers can use different methods depending on their objectives, capabilities, and access to the target.
7. Understanding attack techniques is an important part of developing effective defensive security skills.
8. Networking knowledge is important for understanding many types of cyberattacks and suspicious activity.

---

## 🔗 11. Connection to Networking

This module strengthened my understanding of why networking knowledge is important in cybersecurity.

Many cyberattacks involve communication between:

**Devices → Networks → Applications → Services → Data**

Understanding how these components communicate can help security professionals recognize:

- Unauthorized connections
- Suspicious traffic
- Unusual communication patterns
- Network-based attacks
- Communication with potentially malicious systems
- Indicators that a device may have been compromised

This is especially relevant to my next stage of learning because I am about to begin **Networking Basics** on Cisco Networking Academy.

Strengthening my networking knowledge will give me a stronger technical foundation for understanding security monitoring and network-based investigations.

---

## 🎓 12. Connection to My Previous Learning

Many of the concepts in this module were familiar because of my previous **Level 6 Diploma in Cyber Security**.

However, revisiting them through Cisco helped me reinforce the relationship between:

**Threats → Vulnerabilities → Attacks → Impact → Defense**

My previous studies gave me foundational knowledge in:

- Computer networking
- Network security
- Cybersecurity fundamentals
- Data protection
- Computer maintenance
- Troubleshooting
- IT support

The Cisco course helped me revisit these concepts in a structured way and connect them to the broader cybersecurity environment.

---

## 💡 13. My Key Takeaways

### Attackers have different methods

There is no single technique used for every cyberattack.

Attackers can target:

- Technology
- People
- Applications
- Networks
- Devices
- Credentials
- Vulnerabilities

### Humans can be a security target

Technical controls are important, but users can also be manipulated through phishing and other social-engineering techniques.

### Vulnerability management matters

A vulnerability can become a serious security problem when an attacker is able to exploit it.

Keeping systems updated, securely configured, and properly managed is therefore an important part of reducing risk.

### Understanding attacks supports defense

Security professionals need to understand how attacks work in order to recognize suspicious behaviour, investigate incidents, and implement appropriate defensive controls.

---

## 🛠️ 14. Skills Strengthened

| Skill Area | Development |
|---|---|
| Threat Awareness | ✅ Strengthened |
| Malware Awareness | ✅ Strengthened |
| Attack Recognition | ✅ Strengthened |
| Vulnerability Awareness | ✅ Strengthened |
| Social Engineering Awareness | ✅ Strengthened |
| Network Security Awareness | ✅ Strengthened |
| Security Analysis Foundation | ✅ Strengthened |
| Defensive Security Awareness | ✅ Strengthened |

---

## 🚀 15. What I Want to Explore Further

This module introduced several areas that I want to study more deeply through practical training.

My future areas of focus include:

- Vulnerability scanning
- Network traffic analysis
- Malware analysis
- Phishing analysis
- Threat detection
- Security logs
- SIEM
- Endpoint security
- Incident response
- Network security controls

These topics will help me move from understanding attack concepts to developing practical skills for detecting and responding to threats.

---

## ✅ 16. Module Completion

| Item | Status |
|---|---|
| Module 02 — Attacks, Concepts & Techniques | ✅ Completed |
| Introduction to Cybersecurity Course | ✅ Completed |
| Module Badge | 🏅 Earned |
