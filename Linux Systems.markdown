---
layout: page
title: Linux Systems
permalink: /Linux Systems/
---

## Some fixes and tricks for Linux

1. If you struggle to make use of the Terminal while using a remote Linux system, and your objective is to transfer files, make extensive use of FileZilla.
It's a free, open Source software <a href = "https://filezilla-project.org"> Check it out here </a> , distributed under the terms of the GNU General Public License.  
It presents an extremely simple user interface to the user for making a transfer of files.  
Along similar lines is WinSCP <a href ="https://winscp.net/eng/download.php"> Check it out here </a>. The functionality is very similar, however the difference is that WinSCP is available solely for Windows Systems, while FileZilla is for anyone.  
Also, according to the online commmunity, FileZilla is a faster solution and is suitable even for larger files.  


2. If you plan on using Virtual Box for running a Linux System on your MacOS or Windows, you may have encountered errors where the Virtual machine simply stops and aborts.
The message that you gets looks something like "The VM session was aborted."
In my case, since I use a Mac system, my report log was "00:01:02.858811 CoreAudio: macOS 10.14+ detected, checking audio input permissions".    

This prompts something along the lines of the sound card not being recognised correctly. My fix was 
- Turning off the sound card or audio controller of the VM. This instantly solved the problem for me.  

Given that this is not your case, you can check out these links <a href =" https://stackoverflow.com/questions/31736495/virtualbox-windows-10-64-bit-host-the-vm-session-was-aborted"> Stack Overflow </a>  or <a href = "https://forums.virtualbox.org/viewtopic.php?f=7&t=77663"> VM Forums </a>