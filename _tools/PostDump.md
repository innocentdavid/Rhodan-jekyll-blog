---
description: |
 ## <font color="#E94D84">Post</font><font color="#BA14F4">Dump</font>
 is a C# tool developt by COS team (Cyber Offensive and Security) of POST Luxembourg.

 It is yet another simple tool to perform a memory dump (lsass) using several technics to bypass EDR hooking and lsass protection.

 Unlike tools like EDRSandBlast, it focused on unhooking only functions stricly required in order to dump the memory, thus done by using DInvoke to map required unhooked DLL. With an exception for NtReadVirtualMemory which is dynamicly patched if hook is detected.

 Project in constant improvement (hook detection, direct syscalls).

 Techniques used - 
 - DInvoke -> Credit to TheWover for its C# implementation C# DInvoke
 - PssCaptureSnapshot Duplicate Handle -> Credit to Inf0SecRabbit for its C# implementation MiniDumpSnapshot
 - NtReadVirtualMemory hook patching (Patch instead of DInvoke call due to MiniDumpWriteDump "underthehood" call to NtReadVirtualMemory)
 - MiniDumpWriteDump to dump memory


attack_types:
  
  - Exploitation
  - AVEvasion
  - CredentialAccess

items:
  - ActiveDirectory
  - HostSys
  - Networks

  
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
  - [PostDump official Page](https://github.com/post-cyberlabs/Offensive_tools/tree/main/PostDump)
  - [PostDump Usage Example](https://github.com/post-cyberlabs/Offensive_tools/tree/main/PostDump#usage)


useful: |
  ### <font color="#22EF87">Useful:</font>
  - [PostDump Compile Instruction](https://github.com/post-cyberlabs/Offensive_tools/tree/main/PostDump#compile-instructions)


---


