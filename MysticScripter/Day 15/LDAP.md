# Lightweight  Directory  Access  Protocol (Injection) Injection

![LDAP](https://github.com/MysticScripter/HNGi8/blob/main/ldap.png)

Lightweight Directory Access Protocol (LDAP) is a common software protocol designed to enable anyone on a network to find resources such as other individuals, files, and devices. Directory services such as LDAP are useful for intranets. It can also be used to store usernames and passwords as part of a single sign-on (SSO) system.

## LDAP Injection

LDAP injection is a vulnerability in which queries are constructed from untrusted input without prior validation or sanitization. LDAP uses queries constructed from predicates that involve the use of special characters (e.g., brackets, asterisks, ampersands, or quotes). Metacharacters such as these control the meaning of the query; thereby, affecting the type and number of objects retrieved from the underlying directory. If an attacker can submit input containing these control characters, they can alter the query and change the intended behavior.

## Useful links

+ [Owasp Cheatsheet](https://cheatsheetseries.owasp.org/cheatsheets/LDAP_Injection_Prevention_Cheat_Sheet.html).
+ [Netsparker](https://www.netsparker.com/blog/web-security/ldap-injection-how-to-prevent/).
+ [LDAP Payloads](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/LDAP%20Injection/README.md).

