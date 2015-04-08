# Tutorial-Gruyere
Web Application Exploits and Defenses, A Codelab by Bruce Leban, Mugdha Bendre, and Parisa Tabriz, Google Code University

ID: 797417039425

Cross-Site Scripting (XSS)
  - injecting code into a website's content you dont control
  - reflected XSS: the attack is in the request itself (aka url) "http://www.google.com/search?q=flowers+%3Cscript%3Eevil_script()%3C/script%3E"
  - stored XSS: attack is stored in the application (snippet) attack is triggered by browsing to a page
  - 
  escape or sanitize the stored data

 - alert() works as a simple test for a XSS vulnerability wether it is possible to execute Javascript on a page when it's viewed by another user
 - 
