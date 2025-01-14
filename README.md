<h1>Common Software Troubleshooting Steps </h1>

<h2>Description</h2>
A detailed guide covering common software troubleshooting steps for Windows systems. It includes solutions for operating system performance issues, driver conflicts, application errors, and startup problems. The guide provides step-by-step instructions for using built-in tools like Windows Update, Device Manager, and System File Checker (SFC) to diagnose and resolve software-related issues effectively.
<h2>Languages and Utilities Used</h2>

- Windows Troubleshooting Utilities: Task Manager, Device Manager, Disk Cleanup, Windows Defender
- Command-Line Tools: sfc /scannow, chkdsk
- Windows Safe Mode, Startup Repair, and System Restore
- Windows Update
- Event Viewer
- Batch Scripting
- PowerShell

<h2>Environments Used </h2>

- Windows 10

<h2>1) Operating System Issues</h2>

- Slow performance or freezing
- Blue Screen of Death(BSOD)
- System won't boot
  
<h2>Troubleshoot walk-through:</h2>

- Slow performance or freezing
<br/>

<p align="center"> 
  Check for system updates <br/>
  Settings > Update & Security > Windows Update > Check for updates

<img src="https://i.imgur.com/hjrDDXI.png" height="80%" width="80%" alt="jj"/>
<br/>
<br/>
<p align="center"> 
  Run Disk Cleanup <br/>
  Open Disk Cleanup > Select Files to Delete > Clean Up System Files (Optional) > OK > Delete Files
<img src="https://i.imgur.com/xBz55BQ.png" height="80%" width="80%" alt="jj"/>
<br/>
<br/>  
<p align="center"> 
  End Unnecessary Tasks in Task Manager <br/>
  Open Task Manager > Process Tab > End High-Usage Tasks (Carefully) or Unused tasks
<img src="https://i.imgur.com/afAr2aa.png" height="80%" width="80%" alt="jj"/>
<br/>
<br/>
<p align="center"> 
  Scan for Malware with Windows Defender or Antivirus Software<br/>
  Open Windows Security > Virus & Threat Protection > Scan Options > Run a Quick or Full Scan
<img src="https://i.imgur.com/wspD6tk.png" height="80%" width="80%" alt="jj"/>
<br/>
<br/>
  
- Blue Screen of Death(BSOD) 

<p align="center"> 
  Note the error code <br/>
  (Do online research to find out more about it)

<img src="https://i.imgur.com/Z9uApf2.png" height="80%" width="80%" alt="BSOD"/>
<br/>
<p align="center"> 
  Enter Advanced Startup: Do Startup Repair First <br/>
  Shit+Restart > Troubleshoot > Advanced Options > Startup Repair 

<img src="https://i.imgur.com/pbimleT.png" height="80%" width="80%" alt="jj"/>
<br/>
<p align="center"> 
  Use Command Prompt <br/>
  Troubleshoot > Advanced Options > Command Prompt
 <br align="center">

 <br/>
 
  <img src="https://i.imgur.com/hmpBzV7.png" height="60%" width="80%" alt="jj"/>
  
<br/>
</p>
<p align="center"> 
  Execute Commands in CMD <br/>
Close The Prompt After You Done > Then Continue
 <br align="center">

 <br/>
 
  <img src="https://i.imgur.com/4s42DOu.png" height="60%" width="80%" alt="jj"/>
  <img src="https://i.imgur.com/fJgnUns.png" height="60%" width="80%" alt="jj"/>
  
  
<br/>
</p>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
