# Multi-Channel SIM Swap Fraud – Crypto + Banking Exploit Case Study

## Overview

This case study outlines a real-world SIM swap exploit observed in a UK-based telecoms environment. The attack led to unauthorized access to multiple financial platforms, including traditional bank accounts and crypto exchanges. The incident demonstrates how a single point of compromise—mobile number takeover—can escalate into a multi-platform financial breach.

---

## 1. Attack Chain Summary

- **Attack Type**: SIM Swap → Account Takeover  
- **Primary Objective**: Gain control of phone number to access 2FA and identity recovery flows  
- **Secondary Objectives**:
  - Add stolen cards to mobile wallets (Apple Pay)  
  - Access crypto exchange platforms via SMS/KYC bypass  
  - Steal funds through linked bank accounts and crypto wallets

---

## 2. Fraud Workflow

| Phase             | Description                                                        |
|------------------|--------------------------------------------------------------------|
| **Impersonation**| Fraudster impersonated telecom staff during phone call to victim  |
| **Verification Bypass** | Mimicked standard security checks to gain victim’s trust   |
| **SIM Swap Executed** | Mobile number ported to attacker’s eSIM, cutting off victim |
| **2FA Hijack**   | Used phone access to intercept OTPs and reset credentials         |
| **Monetization** | £20,000 stolen from bank via Apple Pay / £2,000 via crypto wallets |

---

## 3. Response Actions Taken

- **SIM Swap Reversal**: Issued new physical SIM to void attacker’s eSIM  
- **Account Remediation**: Secured telecom account and reviewed logs  
- **Incident Documentation**: Logged internally for regulatory and audit purposes  
- **Customer Support**:
  - Sent fraud confirmation letter for victim use  
  - Provided recovery advice for crypto and banking platforms

---

## 4. Learnings & Gaps

| Weakness                        | Risk                                              |
|----------------------------------|---------------------------------------------------|
| No real-time SIM swap alerts     | Delay in detection allows full takeover          |
| Lack of crypto-focused protocols | Telecoms unprepared for financial crossover risk |
| eSIM fraud detection is limited  | Attackers favor eSIMs for instant hijack         |

---

## 5. Opportunity for Innovation

This case reveals a cross-sector blind spot between telecoms, banking, and crypto. Future integrations to explore:

- Real-time device/IP risk scoring  
- High-risk SIM swap behavior alerts  
- Fraud API flags to notify financial & crypto platforms in real-time  

---

## 6. About This Repo

This documentation contributes to a broader knowledge base for real-world fraud prevention. By combining operational experience with modern detection tools, we aim to build scalable, adaptive defenses.

*Submitted by:*  
**Michael K.**  
Fraud Operations Analyst | Emerging Cybersecurity Strategist  
