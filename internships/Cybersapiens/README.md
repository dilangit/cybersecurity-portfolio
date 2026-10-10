# Cybersapiens — Web Application Penetration Testing Internship

## Overview

**Organisation:** Cybersapiens  
**Role:** Cybersecurity Intern — Penetration Testing  
**Specialisation:** Web Application Security | Vulnerability Assessment | Offensive Security  
**Assessment Type:** Authorised Black-Box Web Application Penetration Testing

During my cybersecurity internship at **Cybersapiens**, I gained practical experience in web application penetration testing, vulnerability identification, manual security testing and technical security reporting.

My primary assignment involved conducting an authorised black-box Vulnerability Assessment and Penetration Testing (VAPT) exercise against a web application.

The internship allowed me to apply cybersecurity concepts in a practical environment, investigate real application behaviours and develop a structured approach to identifying and documenting security weaknesses.

---

## Internship Objectives

The primary objectives of my internship were to:

- Identify potential security vulnerabilities in a web application.
- Perform reconnaissance and attack surface enumeration.
- Assess authentication, authorisation and session management controls.
- Investigate web application and API security weaknesses.
- Validate identified vulnerabilities through manual testing.
- Assess potential security and business impacts.
- Document findings and recommend remediation measures.
- Prepare a professional penetration testing report.

---

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Burp Suite | HTTP interception, request manipulation and vulnerability validation |
| Postman | API security testing |
| Nmap | Network and service enumeration |
| Gobuster | Directory and endpoint discovery |
| Subfinder | Subdomain enumeration |
| Amass | Attack surface discovery |
| Assetfinder | Subdomain discovery |
| crt.sh | Certificate transparency reconnaissance |
| cURL | HTTP request testing |
| Kali Linux | Penetration testing environment |

---

## Penetration Testing Methodology

My assessment followed a structured approach informed by OWASP web application security testing principles.

### 1. Reconnaissance and Information Gathering

- Identified the application's exposed attack surface.
- Investigated accessible endpoints and directories.
- Performed subdomain and asset enumeration.
- Analysed HTTP requests and responses.
- Identified areas requiring further security testing.

### 2. Vulnerability Assessment

Conducted manual security testing focused on:

- Broken access control
- Insecure Direct Object References (IDOR)
- Authentication weaknesses
- Session management vulnerabilities
- Insecure file upload functionality
- Business logic flaws
- Input validation weaknesses
- API security

### 3. Vulnerability Validation

Used Burp Suite Proxy and Repeater, Postman and manual HTTP requests to investigate application behaviour.

This included modifying requests, analysing responses, checking authorisation boundaries and reproducing suspected security weaknesses within the authorised assessment scope.

### 4. Risk Assessment and Reporting

Documented validated security findings using:

- Vulnerability descriptions
- Technical evidence
- Proof-of-concept demonstrations
- CWE classifications
- CVSS severity assessments
- Business impact explanations
- Remediation recommendations

---

## Key Vulnerabilities Investigated

### Broken Access Control — IDOR / BOLA

Investigated authorisation weaknesses that could allow a user to access resources belonging to another account.

**Key learning:** Understanding the importance of server-side authorisation checks and object-level access control.

### Insecure File Upload

Identified weaknesses in file upload validation, including the acceptance of potentially unsafe executable file types.

**Key learning:** Understanding file type restrictions, server-side validation and secure upload handling.

### Authentication and Session Management

Investigated session handling weaknesses, including session identifier behaviour and potential session reuse.

**Key learning:** Understanding secure session lifecycle management, authentication controls and session invalidation.

### Business Logic Vulnerabilities

Investigated application workflows, including password reset functionality, to identify opportunities for unintended behaviour or security control bypass.

**Key learning:** Understanding how weaknesses in application workflows can introduce security risks even when traditional technical controls are present.

### Additional Security Testing

Explored other vulnerability categories, including:

- SQL Injection (SQLi)
- Server-Side Request Forgery (SSRF)
- XML External Entity (XXE) Injection
- HTML Injection
- Input validation weaknesses

Some testing attempts were blocked or inconclusive. These are included as testing areas rather than confirmed vulnerabilities.

---

## Penetration Testing Deliverables

My internship involved preparing a structured Vulnerability Assessment and Penetration Testing report containing:

1. Executive summary
2. Assessment scope
3. Testing methodology
4. Tools and techniques
5. Vulnerability findings
6. Technical evidence and proof-of-concept demonstrations
7. CWE and CVSS classifications
8. Risk and business impact
9. Remediation recommendations

---

## Skills Developed

**Technical Skills**
- Manual web application penetration testing
- Black-box security assessment
- HTTP request and response analysis
- Web application and API testing
- Authentication and authorisation testing
- Vulnerability validation
- Security reconnaissance

**Professional Skills**
- Technical documentation
- Security risk communication
- Vulnerability reporting
- Analytical problem-solving
- Structured security assessment methodology
- Remediation recommendation development

---

## Key Learning Outcomes

My Cybersapiens internship was a significant milestone in my practical cybersecurity development.

It strengthened my ability to move beyond theoretical knowledge and apply security testing techniques to identify, investigate and document web application vulnerabilities.

The experience also improved my understanding of how attackers exploit weaknesses in authentication, access control, session management and application business logic.

This internship supports my continued professional development in penetration testing, application security, vulnerability management and security operations.

---

## Future Portfolio Documentation

I plan to expand this section with sanitised examples of:

- Vulnerability findings and remediation recommendations
- Web application penetration testing methodology
- Security testing techniques
- Lessons learned from practical assessments

All examples will exclude confidential application information and sensitive testing evidence.

---
## Technical Presentation — Business Logic Vulnerabilities

As part of my Cybersapiens cybersecurity internship, I prepared a technical presentation titled **"Business Logic Vulnerabilities — Theory, Practical Demonstration & Mitigation."**

The presentation explored how weaknesses in application workflows and business rules can be exploited even when an application appears to function correctly.

### Topics Covered

- Understanding business logic vulnerabilities
- Price manipulation and coupon abuse
- Workflow bypass and quantity manipulation
- Race conditions
- Authentication and authorisation logic flaws
- Business impact, including financial loss and fraud
- Manual vulnerability testing and detection techniques
- Secure development and mitigation strategies

### Practical Demonstration

I used the PortSwigger Web Security Academy lab **"Excessive trust in client-side controls"** to demonstrate a business logic weakness involving manipulation of a product's purchase price.

The demonstration covered:

1. Browsing the application's shopping functionality.
2. Capturing an HTTP request using Burp Suite.
3. Modifying request parameters.
4. Replaying the modified request.
5. Verifying the business logic weakness.

### Mitigation Strategies Discussed

- Server-side validation of security-sensitive values
- Enforcement of application workflow states
- Rate limiting
- Transaction integrity checks
- Security testing of unusual application behaviours

### Skills Demonstrated

**Web Application Security | Burp Suite | HTTP Request Manipulation | Business Logic Testing | Vulnerability Analysis | Technical Presentation | Security Awareness**

**Lab Reference:** [PortSwigger — Excessive trust in client-side controls](https://portswigger.net/web-security/logic-flaws/examples/lab-logic-flaws-excessive-trust-in-client-side-controls)

This project demonstrates my ability to research cybersecurity vulnerabilities, explain their potential business impact and communicate practical security testing and remediation concepts.

## Confidentiality and Responsible Disclosure

This repository provides a high-level overview of my authorised cybersecurity internship activities.

Confidential target information, credentials, private application endpoints, sensitive screenshots and undisclosed technical findings are intentionally excluded.

The content is intended to demonstrate my cybersecurity knowledge, practical experience and professional development.
