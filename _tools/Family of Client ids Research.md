---
description: |
 ## <font color="#E94D84">Family of Client</font><font color="#BA14F4"> ids Research</font>

 Research into Undocumented Behavior of Azure AD Refresh Tokens. Abusing Family Refresh Tokens for Unauthorized Access and Persistence in Azure Active Directory.
 
 - Ryan Marcotte Cobb, CTU Special Operations
 - Tony Gore, CTU Special Operations
 
 Undocumented functionality in Azure Active Directory allows a group of Microsoft OAuth client applications to obtain special “family refresh tokens,” which can be redeemed for bearer tokens as any other client in the family. We will discuss how this functionality was uncovered, the mechanism behind it, and various attack paths to obtain family refresh tokens. We will demonstrate how this functionality can be abused to access sensitive data. Lastly, we will share relevant information to mitigate the theft of family refresh tokens.



attack_types:
  
  - Exploitation
  - Persistence
  - Impact
  - CredentialAccess
  - Phishing

items:
  - ActiveDirectory
  - Cloud
  - HostSys
  - Networks
  
  
OS:
  
  - Python
  - Bash

  
services:
  
  - Offensive
  - RedTeam
  - PurpleTeam
  - POCS
  - Free
  - OpenSource
  - Blog

  
links: |
  ### <font color="#22EF87">References:</font>
  - [Family of Client ids Research](https://github.com/secureworks/family-of-client-ids-research)


useful: |
  ### <font color="#22EF87">Useful:</font>
  - [Part 3 - Attack Paths](https://github.com/secureworks/family-of-client-ids-research#part-3---attack-paths)

similar: | 
  ### <font color="#22EF87">Similar Tools:</font>
  - [PhishInSuits: OAuth Device Code Phishing with Verified Apps](https://github.com/secureworks/PhishInSuits)

---


