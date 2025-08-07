# Task3

 Vulnerability scanning, risk assessment, CVSS, remediation, security tools

 # Vulnerabilities by Host

##  What I Learn

- How to find security weaknesses on your system
- Which free tools you can use safely
- Basic steps to improve your computer's security

# Vulnerability Assessment Report

# Objective

Conduct a vulnerability assessment using free tools to identify common security issues on a personal or test computer system.

# Tools Used

OpenVAS Community Edition – Free and open-source vulnerability scanner.

Nessus Essentials – Free version of the Nessus vulnerability scanner for personal use (up to 16 IPs).

# Target System
 
## Host Information
 
 Netbios Name:KIOPTRIX
 
 IP:10.0.2.18
 
 MAC Address: 08:00:27:99:FF:A2
 
 OS: Linux Kernel 2.4

 # Scan Configuration
 
Scan Type: Full system scan

Authentication: Unauthenticated scan

Port Range: All ports (TCP/UDP)

Plugins Enabled: Default set (including OS-specific checks, CVE detection, and misconfiguration analysis)

# Vulnerability Summary

 <img width="544" height="611" alt="111" src="https://github.com/user-attachments/assets/8b37fc41-7015-4d8b-81ee-272e2d478244" />

 <img width="548" height="320" alt="1111" src="https://github.com/user-attachments/assets/6407676a-7da9-42ac-b0d2-2a9b12a634e2" />


 # Notable Findings

 Vulnerabilities : 12255 - mod_ssl ssl_util_uuencode_binary Remote Overflow

  SOLUTION:  Upgrade to version 2.8.18 (Apache 1.3) or to Apache 2.0.50.

 #  Remote Code Execution Vulnerability 
 
  Risk:           Allows attackers to gain domain admin privileges.
  
  Recommendation: UPGRADE TO Apache 2.0.50.

  #  References
  
 BID :  10355
 
 CVE :  CVE-2004-0488

# Conclusion

The vulnerability scan revealed several critical and high-risk issues that require immediate attention. Remediation steps have been outlined to improve the system’s security posture. Regular scans and patch management are recommended to maintain a secure environment.
 
 
  



 


