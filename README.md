<h1>Common Software Troubleshooting Steps </h1>

- Full troubleshoot details will be uploaded on a note later on...
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
 
  <img src="https://i.imgur.com/0Zvage4.jpeg" height="60%" width="80%" alt="jj"/>
  <img src="https://i.imgur.com/IfwG5Df.jpeg" height="60%" width="80%" alt="jj"/>
  <img src="https://i.imgur.com/U3r0Y09.jpeg" height="60%" width="80%" alt="jj"/>
  
  
  
<br/>
<br/>
<h2>2) Driver Issues</h2>

- Audio not working
- Device not recognized
<h2>Troubleshoot walk-through:</h2>

- Audio not working
- Device not recognized
<br/>
<p align="center"> 
  Update or Reinstall Drivers <br/>
  Device Manager > Audio or Device > Update Driver or Roll Back To Previous Driver
 <br align="center">

 <br/>
 
  <img src="https://i.imgur.com/7wftLHD.jpeg" height="60%" width="80%" alt="jj"/>
  </br>
  <br/>
<h2>3) Application Software Issues</h2>

- Application won't open
- Crashes frequently
<h2>Troubleshoot walk-through:</h2>

- Application won't open
  
<br/>
<p align="center"> 
  Run Troubleshoot: <br/>
  Open Troubleshoot Setting
 <br align="center">

 <br/>
 
  <img src="https://i.imgur.com/BqAS2GD.jpeg" height="60%" width="80%" alt="jj"/>
  <br/>
<p align="center"> 
  Troubleshoot Setting > Additional Troubleshooters <br/>
  
 <br align="center">

 <br/>
 
  <img src="https://i.imgur.com/l7622Am.jpeg" height="60%" width="80%" alt="jj"/>
  <br/>
<p align="center"> 
  Troubleshoot Setting > Additional Troubleshooters > Run The Troubleshooter > Fix it >  <br/>
  
 <br align="center">

 <br/>
 
  <img src="https://i.imgur.com/MzjMOC4.jpeg" height="60%" width="80%" alt="jj"/>
  <br/>
<p align="center"> 
  Reset Apps:  <br/>
  Apps & Features > Click on the app > Advanced Options > Reset
  
 <br align="center">

 <br/>
  <img src="https://i.imgur.com/E7kzQNB.jpeg" height="60%" width="80%" alt="jj"/>
  <br/>
<p align="center"> 
  Run PowerShell Commands:  <br/>
  Windows Powershell (Run it as administrator) > Execute Command > Restart device after it's completed!
  
 <br align="center">
COMMAND: Get-AppxPackage -AllUsers| Foreach {Add-AppxPackage -DisableDevelopmentMode -Register “$($_.InstallLocation)\AppXManifest.xml”}
 <br/>
  <img src="https://i.imgur.com/SZ5Gxq6.jpeg" height="60%" width="80%" alt="jj"/>
   <br/>
<p align="center"> 
  Run DISM Tools:  <br/>
  CMD Prompt (Run it as administrator) > Execute All Commands > Close > Restart Device
  
 <br align="center">

 <br/>
  <img src="https://i.imgur.com/uTyY2gp.jpeg" height="60%" width="80%" alt="jj"/>
  <br/>
<p align="center"> 
  Run SFC:  <br/>
  CMD Prompt (Run it as administrator) > Execute Command > Close > Restart Device
  
 <br align="center">

 <br/>
  <img src="https://i.imgur.com/CAAsULU.jpeg" height="60%" width="80%" alt="jj"/>
  
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
