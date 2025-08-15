## Project 2: SQL Injection to Bypass Authentication

**Description:** Conducted a web application penetration test against the OWASP Juice Shop, a deliberately insecure web application. The primary objective was to identify and exploit an authentication vulnerability to gain unauthorized access to a privileged account.

**Vulnerability Analysis:** The application's login form was found to be vulnerable to a classic SQL Injection attack. By injecting a crafted SQL statement (`' or 1=1--`) into the email parameter, the backend database query was manipulated to always return a true condition. This bypassed the password check entirely and granted access to the first user in the database, which was the administrator account. This vulnerability represents a critical risk, as it allows any unauthenticated attacker to gain full administrative control over the application.

### Skills Demonstrated:

* **Web Application Pentesting:** Executed a targeted test against a live web application in a controlled lab environment.
* **SQL Injection (SQLi):** Identified and manually exploited an authentication bypass vulnerability.
* **Vulnerability Analysis:** Analyzed the application's response to malicious input to understand the backend query structure and formulate a successful payload.
* **Privilege Escalation:** Escalated from an unauthenticated user to a full-access administrator.
* **Evidence Curation:** Captured and documented evidence of successful exploitation for reporting.

### Evidence of Access:

The following screenshot shows the success message displayed immediately after the malicious payload was submitted, confirming a successful login as the administrator.

**![Admin Login Success](images/admin-login.png)**
