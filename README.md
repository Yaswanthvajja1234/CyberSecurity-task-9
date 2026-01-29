# CyberSecurity-task-9

**CYBER SECURITY INTERNSHIP
Task 9: Network Vulnerability Scanning using Nmap (Practical)
Name: Yaswanth Vajja
Organization: Elevate Labs
Internship: Cyber Security Internship
Date: January 2026**
1. Introduction
Network vulnerability scanning helps identify open ports, running services, and potential security
risks in a network. Nmap is a widely used tool for network reconnaissance and security
assessment.
2. Tool Used
Nmap (Network Mapper) is an open-source tool used for network discovery, port scanning, service
detection, and operating system identification.
3. Practical Objective
The objective of this practical is to perform basic network scanning using Nmap to identify open
ports, services, and possible security risks on a permitted target system.
4. Scan Target
Target used for scanning: 127.0.0.1 (Localhost). This scan was performed on the local system for
learning purposes only.
5. Nmap Commands Used
Basic Port Scan: nmap 127.0.0.1
Service Version Detection: nmap -sV 127.0.0.1
Operating System Detection: nmap -O 127.0.0.1
Aggressive Scan: nmap -A 127.0.0.1
Saving Output: nmap -sV 127.0.0.1 -oN scan_results.txt
6. Observations
The scan identified open ports and services running on the local system. Each open port represents
a possible entry point that must be properly secured to prevent unauthorized access.
7. Risk Analysis
Open ports with outdated or unnecessary services increase the attack surface. Attackers may
exploit vulnerable services to gain access to the system.
8. Mitigation Measures
Recommended mitigation steps include closing unused ports, enabling firewall rules, updating
services, and restricting access to critical services.
9. Conclusion
This practical demonstrated how Nmap can be used for basic network vulnerability scanning.
Understanding scan results and applying proper mitigation measures helps improve overall network
security.
