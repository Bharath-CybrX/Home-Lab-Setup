# Home Lab Setup

## Objective

Configure a simple home lab setup comprising of Kali Linux OS installed on a virtual machine within VirtualBox to conduct pentesting simulations using tools like Metasploit , Burp Suite etc.

### Skills Learned

- Explored and enhanced  skills in various tools like Nmap , Wireshark , Burpsuite , HashCat , Sqlmap , 
Metasploit , Nikto etc. 
- Gained valuable insights regarding knowledge of the linux environment and command line interface . 
- Practiced in a controlled environment inorder master penetration testing techniques, from 
reconnaissance to post-exploitation using several VMs available from TryHackMe , VulnHub etc. 
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

- Kali Linux
- Burp Suite Community Edition (Intercept, modify, and test web requests)
- Metasploit (Modular framework used to identify, exploit, and validate vulnerabilities in systems and networks)
- Nmap (Network discovery and port scanning)
- Wireshark (network protocol analyzer for capturing and examining network traffic in real time)
- Netcat (Reverse shell, pivoting)
- Nikto (Web server scanner and reconnaisance)
- Hashcat (GPU-accelerated password cracker)
- Hydra (Brute-force remote login services (SSH, FTP, etc.))
- John the ripper  (Local password cracker)
- Sqlmap (Automated SQL injection tool)

## Insights on my learnings

## KALI LINUX

![image](https://github.com/user-attachments/assets/ebf74492-2ca8-463e-807e-e4405b7bd307)

My journey into penetration testing began with the installation and initial use of Kali Linux. This experience provided foundational insights into the architecture of a specialized security operating system and the practical application of its tools. 

•	I familiarized myself with this Debian-based Linux distro , including package management (apt) for installing, updating, and removing software.
•	Learned to navigate the Linux system using terminal cli and also gained valuable insights regarding tool familiarization and scripting.
•	Understood the concept of root privileges and sudo was critical for performing security-related tasks that require elevated permissions.
•	Encountering errors during installations, tool execution, or network configurations forced me to develop basic troubleshooting skills, relying on documentation, community forums, and error message analysis.

I will discuss a few tools in brief 

## NMAP

![image](https://github.com/user-attachments/assets/33f4edc1-4467-4974-a85d-23b449c33eaa)

Nmap tool is one of the most integral part of vapt and broader cybersecurity . It is a powerful network reconnaisance tool that allows network discovery and mapping , port scanning , OS detection etc .

I was able to conduct and plan my exploitation attacks based on data regarding running services on each ports of a network host and also whether the software versions running on the open ports are outdated or not .

## BURP SUITE

![image](https://github.com/user-attachments/assets/897a5da2-787b-46df-8d18-b924e60a8e66)

Burp suite is the swiss army knife of web application security . It allows us to intercept, inspect, modify, and replay web traffic, making it indispensable for identifying and exploiting web vulnerabilities.
I was able to leverage my knowledge of OWASP top 10 vulnerabilities to test the security of web application primarily through use of manual testing methods.

## WIRESHARK

![image](https://github.com/user-attachments/assets/d2776dce-618b-4f72-b089-c357e306ac41)

Wireshark is a network protocol based analyzer tool used for capturing and interactively browsing the traffic on a computer network .It is used for deep inspection and analysis of network communications.
This tool gave me an insight on network packet level capture and inspection including protocol analysis and vulnerability identification ( like unencrypted credentials send over HTTP protocols).

### SQLMAP

![image](https://github.com/user-attachments/assets/938cfc90-2bd2-452a-8ce9-1820b5f3e270)

Sqlmap is an automated tool for detecting and exploiting sql injection vulnerabilities in web applications and databases.

## NIKTO

![image](https://github.com/user-attachments/assets/2e59a362-6fcb-4fac-8b18-71212e443735)

Nikto specializes in identifying known vulnerabilities and misconfigurations specifically on the web server itself, as well as common issues with web applications.
I used this tool to detect outdated software , misconfigurations , insecure permissions , ssl tls checks and common vulnerability checks . It was also useful in directory enumeration which was key to identify sub domains of a website that might be vulnerable .

## NETCAT

![image](https://github.com/user-attachments/assets/1b76db2b-8e22-4a02-869b-8c67d7498228)

Netcat (nc) is an extremely versatile and simple command-line utility for reading from and writing to network connections using TCP or UDP. 
I employed this tool for basic port scans and primarily used it for setting up reverse shells , for data transfers etc by setting up a specific port for listening on incoming connections.

## HYDRA

![image](https://github.com/user-attachments/assets/ace01ec8-a7bc-40fd-8e5a-93b0f9f9ba46)

Hydra is a versatile and fast brute-force password cracking tool that supports numerous network protocols. It's used in VAPT to test the strength of authentication mechanisms and identify weak or default credentials.
This tool was instrumental in identifying weak credentials and using dictionary and brute-force attacks due to its wide protocol support . 
