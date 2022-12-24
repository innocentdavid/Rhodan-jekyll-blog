---
description: |
 ## <font color="#E94D84">Inception</font><font color="#BA14F4"> Framework</font>

  provides In-memory compilation and reflective loading of C# apps for AV evasion. Payloads are AES encrypted before transmission and are decrypted in memory. The payload server ensures that payloads can only be fetched a pre-determined number of times. Once decrypted, Roslyn is used to build the C# payload in memory, which is then executed using reflection.

  Inception has been successful in bypassing a number of AV products. These tests were conducted on a fully patched, 64-bit Windows 10 host using Metasploit Meterpreter shellcode.

items:
  - ActiveDirectory
  - HostSys
OS:
  - Windows
  - Python
  - C#

services:
  - Free
  - OpenSource
  - Offensive
  - RedTeam

attack_types: 
  - Exploitation
  - AVEvasion


links: |
  ### <font color="#22EF87">References:</font>
  - [Inception official Page](https://github.com/two06/Inception)
  - [Inception Components](https://github.com/two06/Inception#overview)

useful: |
  ### <font color="#22EF87">Blogs:</font>
  - [Java-Stager – Hide from AV in Memory](https://cornerpirate.com/2018/08/06/java-stager-hide-from-av-in-memory/)

videos: | 
  ### <font color="#22EF87">Videos:</font>
  - [BSidesMCR 2018: Next Gen AV vs My Shitty Code by James Williams](https://www.youtube.com/watch?v=BYEbhDXgElQ)
  - [SteelCon 2018 Next Gen AV vs My Shitty Code by James Williams](https://www.youtube.com/watch?v=247m2dwLlO4)



---


