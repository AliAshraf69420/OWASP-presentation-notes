
open web application security project - non profit organization, goal is to improve web application security and software security 

---
Top 10 
1. Injection flaws: most famous is sql injections to bypass logging 
	 To check, try using single quotes to see if app will crash
	 there are many types 
2. Broken authentication 
	weak password policies, insufficient authentication and session management flaws
3. Sensitive data exposure 
	 in 3 forms; storage, transmission, API security 
4. XML external entities (XXE)
	 Risks: SSRF attacks, reading local files on server, DoS attacks [because XML parser process]
5. Broken access control
	insufficient authorization, insufficient authentication, horizontal privilege escalation, vertical privilege escalation (mainly social engineering)
6. security misconfiguration 
	 mainly by: using default configurations, incomplete or outdated patches, insecure permissions, cloud misconfigurations
7. closed site scripting (XSS)
	similar to sql injection but with JS, steals cookies (& user credentials). Prevent by using up to date libraries. DOM represents HTML & XML code in Tree structure 
8. Insecure deserialization 
	 attackers exploit deserialization code and gain access on the objects
9. Using components with known vulnerabilities
	examples: Outdated software, Third-Party libraries and using open source components 
10. Insufficient logging and Monitoring 
	like delayed detections, should do real time monitoring 
---
Kevin metnick 

