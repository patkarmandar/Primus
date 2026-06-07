
# Using Academy Effectively

## Introduction to the Penetration Tester Path

### Penetration Tester Path Syllabus

> The path culminates in an in-depth module on critical soft skills such as notetaking, organization, documentation, reporting, and client communication, and then a full-blown mock penetration test to practice all of our skills in one large, simulated company network. The modules that comprise the path are laid out as follows:

#### Introduction
1. Penetration Testing Process
2. Getting Started

#### Reconnaissance, Enumeration & Attack Planning
3. Network Enumeration with Nmap
4. Footprinting
5. Information Gathering - Web Edition
6. Vulnerability Assessment
7. File Transfers
8. Shells & Payloads
9. Using the Metasploit Framework

#### Exploitation & Lateral Movement
10. Password Attacks
11. Attacking Common Services
12. Pivoting, Tunneling, and Port Forwarding
13. Active Directory Enumeration & Attacks

#### Web Exploitation
14. Using Web Proxies
15. Attacking Web Applications with Ffuf
16. Login Brute Forcing
17. SQL Injection Fundamentals
18. SQLMap Essentials
19. Cross-Site Scripting (XSS)
20. File Inclusion
21. File Upload Attacks
22. Command Injections
23. Web Attacks
24. Attacking Common Applications

#### Post-Exploitation
25. Linux Privilege Escalation
26. Windows Privilege Escalation

#### Reporting & Capstone
27. Documentation & Reporting
28. Attacking Enterprise Networks

---

## Academy Modules Layout

> The module listing shown corresponds to the sequence we recommend for beginners or advanced users who are 'stuck' to follow, in order to improve in specific areas at each stage of the penetration testing process.

```
                                                                Post-Exploitation
                                                                      |
Pre-Engagement -> Information Gathering <-> Vulneribility Assessment <-> Lateral Movement -> Proof-of-Concept -> Post-Engagement
                                                                      |
                                                                  Exploitation
```

### Pre-Engagement
The pre-engagement stage is where the main commitments, tasks, scope, limitations, and related agreements are documented in writing. During this stage, contractual documents are drawn up, and essential information is exchanged that is relevant for penetration testers and the client, depending on the type of assessment.

At this stage in the process, we should have a strong foundation that can be built through the following fundamental modules:
1. Learning Process
2. Linux Fundamentals
3. Windows Fundamentals
4. Introduction to Networking
5. Introduction to Web Applications
6. Web Requests
7. JavaScript Deobfuscation
8. Introduction to Active Directory
9. Getting Started

### Information Gathering
Information gathering is an essential part of any assessment. Because information, the knowledge gained from it, the conclusions we draw, and the steps we take are based on the information available. This information must be obtained from somewhere, so it is critical to know how to retrieve it and best leverage it based on our assessment goals.

10. Network Enumeration with Nmap
11. Footprinting
12. Information Gathering - Web Edition
13. OSINT: Corporate Recon

### Vulnerability Assessment
The vulnerability assessment stage is divided into two areas. On the one hand, it is an approach to scan for known vulnerabilities using automated tools. On the other hand, it is analyzing for potential vulnerabilities through the information found. Many companies conduct regular vulnerability assessment audits to check their infrastructure for new known vulnerabilities and compare them with the latest entries in these tools' databases.
An analysis is more about thinking outside the box. We try to discover gaps and opportunities to trick the systems and applications to our advantage and gain unintended access or privileges. This requires creativity and a deep technical understanding. We must connect the various information points we obtain and understand its processes.

14. Vulnerability Assessment
15. File Transfers
16. Shells & Payloads
17. Using the Metasploit-Framework

### Exploitation
Exploitation is the attack performed against a system or application based on the potential vulnerability discovered during our information gathering and enumeration. We use the information from the Information Gathering stage, analyze it in the Vulnerability Assessment stage, and prepare the potential attacks. Often many companies and systems use the same applications but make different decisions about their configuration. This is because the same application can often be used for various purposes, and each organization will have different objectives.

18. Password Attacks
19. Attacking Common Services
20. Pivoting, Tunneling & Port Forwarding
21. Active Directory Enumeration & Attacks
22. Using Web Proxies
23. Attacking Web Applications with Ffuf
24. Login Brute Forcing
25. SQL Injection Fundamentals
26. SQLMap Essentials
27. Cross-Site Scripting (XSS)
28. File Inclusion
29. Command Injections
30. Web Attacks
31. Attacking Common Applications

### Post-Exploitation
In most cases, when we exploit certain services for our purposes to gain access to the system, we usually do not obtain the highest possible privileges. Because services are typically configured in a certain way "isolated" to stop potential attackers, bypassing these restrictions is the next step we take in this stage. However, it is not always easy to escalate the privileges. After gaining in-depth knowledge about how these operating systems function, we must adapt our techniques to the particular operating system and carefully study how Linux Privilege Escalation and Windows Privilege Escalation work.

32. Linux Privilege Escalation
33. Windows Privilege Escalation

### Lateral Movement
Lateral movement is one of the essential components for moving through a corporate network. We can use it to overlap with other internal hosts and further escalate our privileges within the current subnet or another part of the network. However, just like Pillaging, the Lateral Movement stage requires access to at least one of the systems in the corporate network. In the Exploitation stage, the privileges gained do not play a critical role in the first instance since we can also move through the network without administrator rights.
Since both Lateral Movement and Pillaging require access to an already exploited system, these techniques and methods are covered in different modules, such as Getting Started, Linux Privilege Escalation, and Windows Privilege Escalation, and many others.

### Proof-of-Concept
The Proof-Of-Concept (POC) is merely proof that a vulnerability found exists. As soon as the administrators receive our report, they will try to confirm the vulnerabilities found by reproducing them. After all, no administrator will change business-critical processes without confirming the existence of a given vulnerability. A large network may have many interoperating systems and dependencies that must be checked after making a change, which can take a considerable amount of time and money. Just because a pentester found a given flaw, it doesn't mean that the organization can easily remediate it by just changing one system, as this could negatively affect the business. Administrators must carefully test fixes to ensure no other system is negatively impacted when a change is introduced. PoCs are sent along with the documentation as part of a high-quality penetration test, allowing administrators to use them to confirm the issues themselves.

34. Introduction to Python 3

### Post-Engagement
The Post-Engagement stage also includes cleaning up the systems we exploit so that none of these systems can be exploited using our tools. For example, leaving a bind shell on a web server that does not require authentication and is easy to find will do the opposite of what we are trying to do. In this way, we endanger the network through our carelessness. Therefore, it is essential to remove all content that we have transferred to the systems during our penetration test so that the corporate network is left in the same state as before our penetration test. We also should note down any system changes, successful exploitation attempts, captured credentials, and uploaded files in the appendices of our report so our clients can cross-check this against any alerts they receive to prove that they were a result of our testing actions and not an actual attacker in the network.
In addition, we have to reconcile all our notes with the documentation we have written in the meantime to make sure we have not skipped any steps and can provide a comprehensive, well-formatted and neat report to our clients.

35. Documentation & Reporting
36. Attacking Enterprise Networks
