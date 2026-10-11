# PortSwigger Web Security Academy — Practical Penetration Testing Labs

## Overview

This section documents my hands-on cybersecurity learning through **PortSwigger Web Security Academy**, with a focus on web application penetration testing, vulnerability identification, exploitation techniques and security remediation.

Through practical labs, I have developed experience investigating common web application vulnerabilities, analysing HTTP requests and responses, manipulating application behaviour and understanding how security weaknesses can be exploited.

These exercises complement my Master's degree in Cybersecurity and my practical penetration testing internship at Cybersapiens.

## Practical Lab Experience

My hands-on learning has covered the following web application security areas:

| Vulnerability Category | Practical Topics |
|---|---|
| Business Logic Vulnerabilities | Price manipulation, workflow bypass, weak isolation, flawed state machines |
| SQL Injection (SQLi) | Hidden data retrieval, SQL query manipulation, login bypass |
| Cross-Site Request Forgery (CSRF) | Exploiting insufficient anti-CSRF protections |
| Authentication | Authentication bypass, two-factor authentication weaknesses, password reset flaws |
| Access Control | Broken access controls and authorisation weaknesses |
| JSON Web Tokens (JWT) | Insecure token verification and signature validation |
| Cross-Origin Resource Sharing (CORS) | Origin reflection and insecure CORS configurations |
| Host Header Injection | Host header manipulation and password reset poisoning |
| Clickjacking | Frame-based attacks and UI redressing |
| Information Disclosure | Exposed application files and directory access |

## Tools and Technologies

| Tool | Application |
|---|---|
| Burp Suite Proxy | Intercepting and inspecting HTTP requests |
| Burp Suite Repeater | Modifying and replaying HTTP requests |
| Web Browser | Analysing application functionality |
| Browser Developer Tools | Inspecting network activity and application behaviour |
| PortSwigger Web Security Academy | Authorised vulnerability testing environment |

## Practical Testing Methodology

My general approach to completing PortSwigger labs includes:

1. **Understand the vulnerability:** Study the security weakness and its potential impact.
2. **Analyse the application:** Explore its functionality, authentication mechanisms and workflows.
3. **Intercept traffic:** Use Burp Suite to capture and examine HTTP requests and responses.
4. **Test security controls:** Modify parameters, headers, cookies or request bodies within the lab.
5. **Validate the weakness:** Observe application behaviour and confirm the lab objective.
6. **Document findings:** Record the root cause, security impact and remediation recommendations.

## Featured Practical Exercise — Business Logic Vulnerabilities

### Excessive Trust in Client-Side Controls

**Platform:** PortSwigger Web Security Academy  
**Category:** Business Logic Vulnerabilities  
**Tool:** Burp Suite

In this exercise, I explored how an application can become vulnerable when it trusts security-sensitive values supplied by the client.

The scenario involved manipulating a product purchase request to change the price of a leather jacket.

### Testing Approach

- Examined the application's shopping functionality.
- Intercepted the relevant HTTP request using Burp Suite.
- Identified a client-controlled price parameter.
- Modified the parameter and replayed the request.
- Observed how the application handled the modified transaction.

### Security Impact

Insufficient server-side validation of product prices can enable unauthorised price manipulation, potentially resulting in financial losses and fraudulent transactions.

### Recommended Mitigation

- Calculate and validate product prices on the server.
- Never trust client-supplied values for security-sensitive transactions.
- Enforce transaction integrity checks.
- Validate business rules throughout application workflows.

**Lab Reference:** [Excessive trust in client-side controls](https://portswigger.net/web-security/logic-flaws/examples/lab-logic-flaws-excessive-trust-in-client-side-controls)

## Skills Developed

- Manual web application penetration testing
- HTTP request and response analysis
- Burp Suite Proxy and Repeater
- Vulnerability identification and validation
- Authentication and authorisation testing
- Business logic security testing
- Web application risk assessment
- Vulnerability documentation
- Security remediation recommendations

## Lab Write-Ups

This repository will be expanded with individual write-ups covering:

- Business Logic Vulnerabilities
- SQL Injection
- Cross-Site Request Forgery
- Authentication Vulnerabilities
- Access Control
- JSON Web Token Security
- CORS Misconfigurations
- Host Header Injection
- Clickjacking

Each write-up will document the lab objective, testing methodology, observations, security impact and recommended mitigation.

## Learning Outcomes

PortSwigger Web Security Academy has helped me strengthen my practical understanding of web application security and the importance of manual security testing.

These exercises have improved my ability to investigate application behaviour, identify security weaknesses and explain how vulnerabilities can affect confidentiality, integrity and availability.

My ongoing goal is to build deeper proficiency in application security, vulnerability assessment and penetration testing.

## Disclaimer

All security testing documented in this section was conducted in authorised educational lab environments.

This repository is intended for cybersecurity learning, technical skill development and professional portfolio demonstration.
