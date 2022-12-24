---
description: |
  ## <font color="#E94D84">Sauron</font><font color="#BA14F4">Eye</font>

  Search tool to find specific files containing specific words, i.e. files containing passwords..
  SauronEye is a search tool built to aid red teams in finding files containing specific keywords.

  Features -

  - Search multiple (network) drives
  - Search contents of files
  - Search contents of Microsoft Office files (.doc, .docx, .xls, .xlsx)
  - Find VBA macros in old 2003 .xls and .doc files
  - Search multiple drives multi-threaded for increased performance
  - Supports regular expressions in search keywords
  - Compatible with Cobalt Strike's execute-assembly
   
   It's also quite fast, can do 50k files, totaling 1.3 TB on a network drive in under a minute (with - realistic file filters). Searches a C:\ (on a cheap SATA SSD) in about 15 seconds.



attack_types:
  - Enumeration

items:
  - HostSys
  
OS:
 - C#
 - Windows

services:
  - Offensive
  - RedTeam
  - Free
  - OpenSource
  
  
links: |
  ### <font color="#22EF87">References:</font>
  - [SauronEye official Page](https://github.com/vivami/SauronEye)
  - [SauronEye Usage](https://github.com/vivami/SauronEye#usage-examples)

---


