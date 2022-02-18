# Server Side Includes Injection

SSI injection (Server-side Include) is a server-side exploit that lets an attacker send code into an application to be executed later, locally, by the web server. SSI injection attacks can only be successful when the web server permits SSI execution without proper validation. 

# Exploitation

n attacker could detect possible SSI functionality on the target server by searching for key file extensions (.stm, .shtm, shtml), or if there is a server misconfiguration such that they are able to fetch the .htaccess file located on a SSI-enabled directory. Although SSI attacks are more limited in scope compared to XSS (full scripting with Javascript) or SQL injection (database manipulation), they remain a high severity vulnerability if exploited since an attacker could be able to execute arbitrary shell commands or gain access to sensitive files (e.g. password files).

# Impact

The attacker can access sensitive information such as password files, and execute shell commands. The SSI directives are injected in input fields and sent to the web server.

# Useful links

+ [OWASP](https://owasp.org/www-community/attacks/Server-Side_Includes_(SSI)_Injection).
+ [Portswigger](https://portswigger.net/kb/issues/00101100_ssi-injection).

# Practice
+ bWapp
