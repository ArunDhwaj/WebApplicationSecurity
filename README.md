# WebApplicationSecurity

Web Application Security
=========================

References: https://www.owasp.org/images/7/72/OWASP_Top_10-2017_%28en%29.pdf.pdf

OWASP (Open Web Application Security Project): 2016

Top 10: Security Vuneralbilities
=================================

A1: Injection,
A2: Broken Authentication and Session Management,
A3: Cross-Site Scripting (XSS),
A4: Insecure Direct Object References,
A5: Security misconfigurations,
A6: Sensitive Data exposure,
A7: Missing Functional Level Access Control,
A8: Cross-Sire Request Forgery (CSRF)
A9: Using components with unknown vunerabilities,
A10: Unvalidated Request Redirects and Forwards, 

-----------------*******---------------------------------------

        A1: Injection
        ===============

Types of Injection / Preventation 
-----------------------------------------

i) SQL --> Preventation --> Parametrized Queries
ii) LDAP --> Preventation --> SIP
iii) Log --> Preventation --> Don't log all the user inputs, SIP
iv) XMLPath --> Preventation --> SIP
v) OS Command --> Preventation --> User inputs used as OS command, SIP
vi) XSS (JavaScript) --> Preventation --> SIP

General SQL Injection Preventation (SIP): By validating the user input data and have the safe list of characters, and only allow those characters, and don't let user input anything else.

-----------------*******---------------------------------------

        A2: Broken Authentication and Session Management
        =================================================
        

