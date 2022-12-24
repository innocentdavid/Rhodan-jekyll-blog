---
description: |
 ## <font color="#E94D84">Ninja</font><font color="#BA14F4">C2</font>
 is an Open source C2 server created by Purple Team to do stealthy computer and Active directoty enumeration without being detected by SIEM and AVs , Ninja still in beta version and when the stable version released it will contains many more stealthy techinques and anti-forensic to create a real challenge for blue team to make sure all the defenses configured correctly and they can detect sophisticated attacks.

  Ninja use python to server the payload and control the agents . the agents are based on C# and powershell which can bypass leading AVs . Ninja comunicate with the agents in secure channel encrpyted with AES-256 and the key is not hard coded but randomly generated on the campaign start , every agent connect to the C2 get the key and if the C2 restarted a new key will be used by all old agents and the new. Ninja also randomize the callback URLs for every campaign to bypass static detection. 

  Ninja is packed with a number of features that allows you to gain an insight into your upcoming engagement before you actually need to deploy your full aresenal or tools and techniques, such as-

  - Defense Analysis
  - Automation for kerberoast attack from generating the kerberos tickets to extracting the SPN hashes  into hashcat format.
  - Automation for dc_sync to get hashes for a list of users or domain admin group.
  - Undetected Automation to get groups the user belong to and the users member in a group. 
  - Automation for bloodhound AD data collection .
  - Customized c# payloads that encrypt strings to bypass static detection.
  - Encode any command you want to unicode base64 to be used in powershell encoded commands.
  - Full encryption of all communications between Agent and command and control to bypass AV and IPS detection.
  - Dynamic URLs for all function , just place your list of url names and the c2 will use it randomly to bypass any static detection.
  - Get random encryption key on the fly ( not hard coded ) every time the agent connect ( even reconnection needs a new key )
  - Take screenshots and send it encrypted to C2
  - Upload files from C2 to victim encrypted to bypass AV and IPS
  - Download files from the victim encrypted to bypass AV and IPS
  - Staged payloads to bypass detection ( base64 and base52 )
  - Bypasses AVs ( tested on kaspersky and trendmicro )
  - Bypasses SIEM detection ( tested on splunk collecting usual event logs along with sysmon logs ) not tested on powershell v5 script block and module logging ( will be done in the next release ).
  - Set the beacon interval dynamically even after the agent connected and provide a starting beacon interval in the campaign start configurations
  - Logging for all commands and results in order to return to any data you missed in your operation.
  - Set the configuration one time when you start the campaign and enjoy.
  - Global kill switch to end campaigns.
  - Delete table entries.
  - All the payload written to payloads folder for easy access and further customization.
  - Easy to add automation for any command you want.

attack_types: |
  - AVEvasion
  - Exploitation
  - C2C

items:
  - HostSys
  - ActiveDirectory
  - Networks
OS:
  - Linux
  - Windows
  - PowerShell
  - Python
services:
  - Free
  - OpenSource
  - Offensive
  - PurpleTeam


links: |
  ### <font color="#22EF87">References:</font>
  - [Ninja C2 official page](https://github.com/ahmedkhlief/Ninja)
  - [Ninja C2 Requirements](https://github.com/ahmedkhlief/Ninja#requirement)
  - [Ninja C2 Installation steps](https://github.com/ahmedkhlief/Ninja#installation)


useful: |
  ### <font color="#22EF87">Blogs:</font>
  - [Introducing Ninja C2 : the C2 built for stealth red team Operations](https://shells.systems/introducing-ninja-c2-the-c2-built-for-stealth-red-team-operations/)
  - [NinjaC2 V2.2 Released with New Features](https://shells.systems/ninjac2-v2-2-released-with-new-features/)
---

