## Lab: File path travrsal - simple case

**Platform:** PortSwigger Web Security Academy 
**Vulnerability:** Path Traversal 
**Tool Used:** Burp Suite (Repeater) 

### Objective 
Access a sensitive file on the server. 

### Key Payload
../../../../etc/passwd 

### Result 
Successfully accessed the /etc/passwd file, confirming a path traversal vulnerability. 

### Learning 
User-controlled file paths must be strictly validated and restricted to prevent unauthorized file access.
