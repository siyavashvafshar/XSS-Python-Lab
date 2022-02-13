# XSS Python


simple Flask app that contains an example of multiple Injection (XSS) vulnerabilities and its main goal is to describe how a malicious user could exploit them on this purposefully vulnerable app.


## What is Cross-Site Scripting?

XSS flaws occur whenever an application includes untrusted data in a new web page without proper validation or escaping, or updates an existing web page with user-supplied data using a browser API that can create HTML or JavaScript. XSS allows attackers to execute scripts in the victim’s browser which can hijack user sessions, deface web sites, or redirect the user to malicious sites.

      https://owasp.org/www-community/attacks/xss/


## Setup


      make install


Then simply visit [localhost:10007][app] ! 😆


## Attack narrative

    <script>alert(1)</script>
    
## Find With SAST Tools

      SonarQube : 
