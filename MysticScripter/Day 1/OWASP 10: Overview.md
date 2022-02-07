# OWASP Top 10: 2021

![owasp](https://github.com/MysticScripter/HNGi8/blob/main/owasp.webp)

The OWASP Top 10 is a publicly shared standard awareness document for developes and application security researchers. The document provides information on the 10 most critical web vulnerabilities, according to the OWASP Foundation. This article gives a brief overview of the OWASP Top 10 based on the 2021 report.

## 1. Broken Access Control

Access control provides policies such that users cannot act beyond what they are permitted.This vulnerability allows attackers to masquerade as legitimate users. It was rated number one in the OWASP Top 10 2021 report.It leads to unauthorized access, data exposure, privilege excalation and DDOS.

## 2. Cryptographic failures

This category, previously known as Sensitive data exposure, focuses on failures related to cryptography. The vulnerability leads to sensitive data exposure and system compromise.

## 3. Injection

Injection vulnerabilities allow an attacker to relay malicious code through an application into another system. This group consists of SQL injection, XSS, Command injection, Code injection, LDAP injection, HTML injection, SMTP/IMAP command injection, etc. The injection attacks can lead to system and data compromise, session hijacking and ATOs.

## 4. Insecure design

This is a category that has appeared in the reports for the first time in 2021. This class of vulnerability is brought about by design flaws and problems in the application design architecture. Insecure design gives attackers the chance to exploit the application's logic leading to sensitive information disclosure or even application compromise.

## 5. Security Misconfiguration

The previous class of vulnerability, XXE, has been included in this group. The vulnerability occurs majorly due to security misconfigurations in the applications and at time use of weak/default passwords. This vulnerability places the system as well as its data at a risk.

## 6. Vulnerable and Outdated Components 

This kind of threat occurs when the components such as libraries and frameworks used within the app almost always execute with full privileges. If a vulnerable component is exploited, it makes the hacker's job easier to cause a serious data loss or server takeover.

## 7. Identification and Authentication Failures 

These issues can happen when an application: doesn't prevents automated attacks like credential stuff or bruteforcing to guess passwords. has flaws in the password reset or recovery flows. doesn't handles (invalidates or rotates) session identifiers after email/password update, logout, inactivity, re-login.

## 8. Software and Data Integrity Failures 

Software and data integrity failures may lead to the execution of the the attacker's code or prying open a backdoor via combined measures. The category also entails the insecure decentralization vulnerability and is deemed to be as a result of faulty assumptions and misguided mechanisms during development.

## 9. Security Logging and Monitoring Failures

Security event logging and monitoring is a process that organizations perform by examining electronic audit logs for indications that unauthorized security-related activities have been attempted or performed on a system or application that processes, transmits or stores confidential information. This vulnerability was previously known as Insecure logging and monitoring and is known to lead to allow unsanitized input to log files, thereby giving attackers the freedom to tamper with log files and corrupt, inject unexpected inputs or change entries.

## 10. Server-Side Request Forgery

Server-Side Request Forgery, also known as SSRF refers to an attack which lets an attacker send crafted requests from the back-end server of a vulnerable web application. SSRF is commonly used by attackers to target internal networks that are behind firewalls and can not be reached from the external network.

# References

+ [OWASP](https://owasp.org/Top10/).
+ [Portswigger](https://portswigger.net/daily-swig/owasp-toasts-20th-anniversary-with-revised-top-10-for-2021).
