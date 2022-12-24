---
description: |
 ## <font color="#E94D84">Lin</font><font color="#BA14F4">WinPwn</font>
 is a bash script that automates a number of Active Directory Enumeration and Vulnerability checks. The script uses a number of tools and serves as wrapper of them. Tools include- impacket, bloodhound, crackmapexec, ldapdomaindump, lsassy, smbmap, kerbrute, adidnsdump, certipy, silenthound, and others.

 linWinPwn is particularly useful when you have access to an Active Directory environment for a limited time only, and you wish to automate the enumeration process and collect evidence efficiently. In addition, linWinPwn can replace the use of enumeration tools on Windows in the aim of reducing the number of created artifacts (e.g., PowerShell commands, Windows Events, created files on disk), and bypassing certain Anti-Virus or EDRs. This can be achieved by performing remote dynamic port forwarding through the creation of an SSH tunnel from the Windows host (e.g., VDI machine or workstation or laptop) to a remote Linux machine (e.g., Pentest laptop or VPS), and running linWinPwn with proxychains.

attack_types:
  
  - Enumeration
  - Exploitation
  

items:
  - ActiveDirectory
  - HostSys
  - Networks 
  
  
OS:
  - Linux
  - Bash
  - Windows  
  
  
services:
  - Offensive
  - Free
  - OpenSource

  
links: |
  ### <font color="#22EF87">References:</font>
  - [LinWinPwn official Page](https://github.com/lefayjey/linWinPwn)
  - [LinWinPwn Installation Steps](https://github.com/lefayjey/linWinPwn#setup)


useful: |
  ### <font color="#22EF87">Useful:</font>
  - [LinWinPwn Example Commands](https://github.com/lefayjey/linWinPwn#usage)

videos: | 
  ### <font color="#22EF87">Videos:</font>
  - [LinWinPwn Interactive Mode](https://asciinema.org/a/499893)
  - [LinWinPwn Automated Mode](https://asciinema.org/a/464904)


---


