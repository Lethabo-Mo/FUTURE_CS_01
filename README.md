# Cyber Security Task 1 (2026)
## Vulnerability Assessment Report for a Live Website (Read-Only Scope)

**Internship Program:** Future Interns  
**Domain:** Cyber Security  
**Task:** 1 – Vulnerability Assessment  
**Assessment Type:** Passive / Read-Only Security Review  

---

## About the Task

Every business today owns a website — but many websites contain security misconfigurations that may expose them to risks if left unaddressed.

This task focuses on identifying **common web security weaknesses** and presenting them in a **clear, business-friendly manner**. The goal is not to exploit vulnerabilities, but to assess risk, explain impact, and recommend practical remediation steps.

This task simulates the role of a **security auditor or consultant**, following ethical and professional standards.

---

## Objective

The objectives of this task are to:

- Analyze a public website for common security weaknesses
- Perform only **read-only and passive analysis**
- Classify risks using Low / Medium severity levels
- Explain findings in simple, non-technical language
- Provide clear and practical remediation recommendations
- Produce a professional vulnerability assessment report

---

## Target Website & Scope

- **Website Tested:** http://demo.testfire.net  
- **Scope:** Publicly accessible pages only  
- **Assessment Type:** Passive vulnerability assessment  

The selected website is a **public security testing demo platform** commonly used for training and educational purposes.

---

## Scope & Ethics

This assessment was conducted in strict accordance with ethical guidelines.

### Allowed
- Public pages only  
- Passive scanning  
- HTTP header and cookie inspection  
- Configuration analysis  

### Not Allowed
- Login bypass attempts  
- Exploitation of vulnerabilities  
- Brute-force attacks  
- Denial-of-Service (DoS) testing  
- Any activity that could damage or disrupt the system  

No authenticated areas or backend systems were tested.

---

## Tools Used

- **OWASP ZAP (Passive Scan)** – Identifying passive security issues such as missing headers and insecure cookies  
- **Browser Developer Tools** – Inspecting HTTP headers, cookies, and client-side configurations  
- **Nmap (Basic Scan)** – Limited visibility into exposed services without intrusive testing  
- **Canva** – Designing a professional, client-ready vulnerability assessment report  

---

## Summary of Findings & Risk Ratings

| Vulnerability | Risk Level |
|---------------|-----------|
| Missing Content Security Policy (CSP) | Medium |
| Missing X-Frame-Options | Low |
| Missing X-Content-Type-Options | Low |
| Missing HSTS / HTTPS Not Enforced | Medium |
| Insecure Cookie Flags | Medium |
| Server Version Disclosure | Low |
| Missing Referrer Policy | Low |

No critical or high-risk vulnerabilities were identified during this read-only assessment.

---

## Deliverables

This repository contains:

- A professionally designed **Vulnerability Assessment Report (PDF)**  
- Supporting **screenshots** as evidence  
- Documentation explaining the scope, tools, and methodology  

