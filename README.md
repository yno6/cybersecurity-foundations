# Cybersecurity Foundations

> Hands-on cybersecurity training, documentation, and analysis completed through **MyFirstHack**.

**Training/Course Period:** June – September 2026

---

## Overview

This repository documents my learning throughout the **MyFirstHack Cybersecurity Foundations** training program.

The training covered foundational cybersecurity concepts, security frameworks, network security, reconnaissance, authentication, password security, cloud security, and threat detection.

Each section contains my written documentation, analysis, observations, and key takeaways from the corresponding training topics.

---

## Topics Covered

| Category                       | Topics                                            |
| ------------------------------ | ------------------------------------------------- |
| **Cybersecurity Fundamentals** | CIA Triad, Security Principles                    |
| **Security Frameworks**        | Cyber Kill Chain, MITRE ATT&CK                    |
| **Network Security**           | Firewalls, IDS/IPS, Proxies                       |
| **Security Monitoring**        | SIEM, Threat Detection                            |
| **Authentication**             | MFA, Authentication Security                      |
| **Reconnaissance**             | OSINT, Shodan, Information Gathering              |
| **Cloud Security**             | AWS, EC2, S3, IAM, VPC, CloudTrail                |
| **Social Engineering**         | Phishing, Suspicious Messages, Security Awareness |

---

## Cybersecurity Fundamentals

### CIA Triad

The **CIA Triad** provides a foundation for understanding information security through three core principles:

* **Confidentiality** — protecting information from unauthorized access
* **Integrity** — ensuring information remains accurate and unaltered
* **Availability** — ensuring systems and information remain accessible when needed

[Read Documentation →](./concepts/cia-triad.md)

---

## Security Frameworks

### Cyber Kill Chain

The **Cyber Kill Chain** is a framework used to understand the stages of a cyber attack, from initial reconnaissance through actions taken against a target.

**Topics:**

* Reconnaissance
* Weaponization
* Delivery
* Exploitation
* Installation
* Command and Control
* Actions on Objectives

[Read Documentation →](./concepts/cyber-kill-chain.md)

### MITRE ATT&CK

**MITRE ATT&CK** provides a structured knowledge base of adversary tactics and techniques used to understand and analyze real-world attack behavior.

**Topics:**

* Tactics
* Techniques
* Sub-techniques
* Adversary behavior
* Threat detection

[Read Documentation →](./concepts/mitre-attack.md)

---

## Network Security

### Firewalls

Documentation covering the purpose of firewalls, traffic filtering, access control, and their role in network security.

[Read Documentation →](./concepts/firewalls.md)

### IDS/IPS

Documentation covering intrusion detection and prevention systems, their differences, and how they can be used to identify or prevent suspicious network activity.

[Read Documentation →](./concepts/ids-ips.md)

### Proxies

Documentation covering proxy servers, intermediary network communication, traffic inspection, and security use cases.

[Read Documentation →](./concepts/proxies.md)

---

## Security Monitoring

### SIEM

**Security Information and Event Management (SIEM)** systems collect and analyze security-related events and logs to support monitoring, investigation, and incident response.

**Topics:**

* Log collection
* Event correlation
* Security monitoring
* Alerting
* Incident investigation

[Read Documentation →](./concepts/siem.md)

### Threat Detection

Documentation covering indicators of suspicious activity, security monitoring, and identifying potential threats.

[Read Documentation →](./concepts/threat-detection.md)

---

## Authentication & Password Security

### Authentication & MFA

Documentation covering authentication methods, multi-factor authentication, and the importance of protecting account credentials.

[Read Documentation →](./concepts/authentication.md)

### Password Security

Documentation covering password storage, password hashing, password recovery techniques, and the security implications of weak passwords.

**Tools explored:**

* John the Ripper
* `pdf2john`
* Hash Calculator
* Password Cracker

[Read Documentation →](./concepts/password-security.md)

---

## Reconnaissance

### Information Gathering

Documentation covering reconnaissance techniques and the role of information gathering during security assessments.

**Topics:**

* Reconnaissance
* OSINT
* Information gathering
* Attack surface awareness

### Shodan

Exploration of **Shodan** and how internet-connected systems and services can be discovered through publicly available information.

[Read Documentation →](./concepts/reconnaissance.md)

---

## Cloud Security

### AWS

Documentation covering foundational AWS services and their relevance to cloud security.

**Services explored:**

| Service        | Security Focus                               |
| -------------- | -------------------------------------------- |
| **EC2**        | Compute instances and security configuration |
| **S3**         | Storage and access control                   |
| **IAM**        | Identity and permissions                     |
| **VPC**        | Network isolation and access                 |
| **CloudTrail** | Activity logging and monitoring              |

[Read Documentation →](./concepts/cloud-security.md)

---

## Social Engineering

### Phishing

Documentation covering phishing techniques, indicators of suspicious messages, and approaches for identifying potential phishing attempts.

### Suspicious Messages

Analysis of suspicious SMS messages, links, and common indicators that can be used to identify potentially malicious communication.

[Read Documentation →](./concepts/social-engineering.md)

---

## Concepts

The following concepts are documented throughout the repository:

```text
Cybersecurity Fundamentals
├── CIA Triad
│
Security Frameworks
├── Cyber Kill Chain
└── MITRE ATT&CK
│
Network Security
├── Firewalls
├── IDS/IPS
└── Proxies
│
Security Monitoring
├── SIEM
└── Threat Detection
│
Authentication
├── Authentication
└── MFA
│
Reconnaissance
├── OSINT
├── Information Gathering
└── Shodan
│
Cloud Security
├── AWS
├── EC2
├── S3
├── IAM
├── VPC
└── CloudTrail
│
Social Engineering
├── Phishing
└── Suspicious Messages
```

---

## Repository Structure

```text
cybersecurity-foundations/
│
├── concepts/
│   ├── cia-triad.md
│   ├── cyber-kill-chain.md
│   ├── mitre-attack.md
│   ├── firewalls.md
│   ├── ids-ips.md
│   ├── proxies.md
│   ├── siem.md
│   ├── authentication.md
│   ├── reconnaissance.md
│   ├── cloud-security.md
│   ├── threat-detection.md
│   └── social-engineering.md
│
└── README.md
```

---

## Learning Focus

This training helped build my understanding of how cybersecurity concepts connect to practical security scenarios.

My focus throughout the training was on understanding **why** security controls and techniques are used, how they fit into broader security frameworks, and how different tools can be applied to identify, analyze, and respond to security-related activity.

---

## Disclaimer

All activities documented in this repository were completed for educational and training purposes.

The techniques and tools discussed are intended for use in authorized environments, security testing, and cybersecurity education.
