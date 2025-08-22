# Christopher Kokoski's Cybersecurity Portfolio

This portfolio showcases hands-on applications of cybersecurity principles in vulnerability analysis, system hardening, and threat mitigation. The projects documented here reflect a practitioner's approach to security, emphasizing that a robust understanding of defense (Blue Team) is critical to executing effective offensive (Red Team) operations.

---

## Portfolio Projects
Below is a collection of projects demonstrating my practical, hands-on cybersecurity skills.

### Defense (Blue Team) & System Hardening

#### [Project 1: Live Web Application Security Audit & Hardening](blue-team/01-webapp-audit/README.md)
**Description:** Performed a full "Scan -> Remediate -> Verify" lifecycle audit on a live web server. Used Nmap and Qualys SSL Labs to identify vulnerabilities, analyzed results, and diagnosed a complex server misconfiguration that was not apparent to the hosting provider's support team.

**Skills Demonstrated:**
* Vulnerability Management
* Vendor Communication
* Root Cause Analysis
* TLS/SSL Hardening
* Nmap
* Qualys SSL Labs

#### [Project 2: Web Application Vulnerability Scan & Remediation](blue-team/02-webapp-vulnerability-scan/README.md)

**Description:** Conducted a dynamic application security test (DAST) using OWASP ZAP. Identified a missing Content Security Policy (CSP) header, troubleshooted WAF and plugin blocks, and remediated the finding by deploying a custom PHP snippet.

**Skills Demonstrated:**
* DAST Scanning (OWASP ZAP)
* Vulnerability Analysis
* WAF Evasion
* Technical Remediation (PHP)
* Verification

#### [Project 3: Attack Surface Management (ASM)](blue-team/03-attack-surface-management/README.md)

**Description:** Developed and executed a custom Bash script to perform automated reconnaissance against a large-scale public target. The script systematically discovers subdomains, identifies live hosts, and scans for known vulnerabilities to map the potential attack surface.

**Skills Demonstrated:**
* Attack Surface Management (ASM)
* Automated Reconnaissance
* Scripting (Bash)
* Asset Discovery (amass)
* Live Host Probing (httpx)
* Vulnerability Scanning (nuclei)

### Offense (Red Team) & Penetration Testing

#### [Project 1: Network Penetration Test](red-team/01-network-penetration-test/README.md)

**Description:** Conducted a network penetration test against a Metasploitable2 server. Used Nmap for reconnaissance to identify a vulnerable FTP service and exploited it with the Metasploit Framework to gain root-level system access.

**Skills Demonstrated:**
- Penetration Testing Methodology
- Reconnaissance (Nmap)
- Vulnerability Identification
- Exploitation (Metasploit)
- Post-Exploitation

#### [Project 2: Exploiting the OWASP Top 10](red-team/O2-owasp-top-10-exploitations/README.md)

**Description:** Conducted a comprehensive security assessment of the OWASP Juice Shop web application. Systematically identified and exploited the full range of the OWASP Top 10 vulnerabilities, demonstrating a practical understanding of the most critical security risks facing modern web applications.

**Skills Demonstrated:**
 - **Web Application Pentesting:** Executing the end-to-end testing process, from reconnaissance to exploitation and privilege escalation.
- **Vulnerability Analysis:** Identifying and assessing security weaknesses in application logic, configuration, and design.
- **Injection Flaw Exploitation:** Crafting and executing payloads for various injection types, including:
  - SQL Injection (SQLi)
  - Cross-Site Scripting (XSS)
- **Authentication & Session Management Testing:** Identifying weaknesses in user identity verification, including authentication bypass and session hijacking.
- **Broken Access Control Exploitation:** Discovering and leveraging flaws like Insecure Direct Object References (IDOR) to access unauthorized data and functions.
- **Security Misconfiguration Identification:** Detecting insecure server and application settings, such as default credentials, verbose error messages, and directory listing.
- **Sensitive Data Exposure Analysis:** Identifying cryptographic failures and instances where sensitive data (PII, credentials) is improperly stored or transmitted.
- **Server-Side Request Forgery (SSRF):** Forcing the server to make unintended requests to internal or external resources.

*(More projects, including more advanced defensive and offensive security exercises, will be added here as they are completed.)*

---

## Connect With Me
I am always open to connecting with fellow security professionals and enthusiasts.

- **LinkedIn:** [https://www.linkedin.com/in/christopher-kokoski-9542441b6/](https://www.linkedin.com/in/christopher-kokoski-9542441b6/)
