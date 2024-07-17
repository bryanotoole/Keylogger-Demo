# KeyloggerDemo

## Purpose and Disclosure
The purpose of this lab is to demonstrate a foundational understanding of keylogging, how keyloggers are written, executed, and how logged information can be sent to a threat actor. This demonstration was done in a virtual machine operated by me alone and was not distributed outside of the virtual machine. This demo is meant for educational and informational purposes only, and is not meant to encourage or instruct others to take this information and use it for harmful purposes.

## Description
- 	Set up a virtual machine for testing a keylogger program run by Windows Visual Studio 2022.
- Whitelisted keylogger file in Windows Defender to allow for testing and execution.
- Configured a C# keylogger template to meet custom parameters.
-	Linked a test Gmail account to the C# using a uniquely generated app password.
-	Set keylogger to record 150 bytes before sending the log to the test Gmail address.
-	Modified the Output Type of the script so the log screen is not visible as the keylogger is running.
-	Demonstrated the keylogger harvesting login credentials to a banking website and having those logs sent to the test email address.
-	Located executable file for this project to show that it could theoretically be shared with others or installed on other machines.
-	Created a task in Task Scheduler for the keylogger to run upon machine startup.
-	Removed keylogger files from Defender whitelist, then tried running executable file to simulate real time protection from such threats.



## Skills Learned
- Virtual network setup
- Active Directory management
- PowerShell syntax
- Account and Password Policy Configuration


## Tools & Technology Used
- Oracle VirtualBox
- Microsoft Server 2019
- Microsoft Active Directory
- PowerShell

##  Background
The purpose of this lab is to simulate setting up a basic virtual network for an organization and managing its users within Active Directory. This lab demonstrates a basic understanding of virtual network setup and Active Directory functionality. The progress of this lab is outlined in the Description above and displayed in the Screenshots below.
  
## Screenshots

<p align="center">
Figure 1: Virtual machine setup in Oracle VirtualBox.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%2025.%20Virtual%20Machines%20Used.PNG"/> <br />
<br />
<p align="center">
Figure 2: Virtual network diagram serving as the foundational setup for this lab. <br/>
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%20Network%20Diagram.PNG"/> <br />
<br />
<p align="center">
Figure 3: Admin user created within the Domain Controller virtual machine.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%202.%20Admin%20User%20Created%20Within%20Domain%20Controller%20Virtual%20Machine.PNG"/> <br />
<br />
<p align="center">
Figure 4: Successful admin login to Domain Controller after creation within AD.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%201.%20Admin%20User%20Domain%20Controller%20Login%20Screen.PNG"/> <br />
<br />
<p align="center">
Figure 5: PowerShell script used to upload organizational 1,000 users into the domain.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%204.%20PowerShell%20Script%20to%20Create%201000%20Users.PNG"/> <br />
<br />
<p align="center">
Figure 6: PowerShell view of user creation files before running.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%205.%20PowerShell%20View%20of%20User%20Creation%20Files%20Before%20Running.PNG"/> <br />
<br />
<p align="center">
Figure 7: Users shown in AD after PowerShell upload.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%206.%20Users%20Shown%20In%20AD%20After%20PowerShell%20Upload.PNG"/> <br />
<br />
<p align="center">
Figure 8: CLIENT1 virtual machine Command Prompt showing confirmed connection with mydomain.com.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%207.%20CLIENT1%20Host%20VM%20IPConig%20Setup.PNG"/> <br />
<br />
<p align="center">
Figure 9: Lease for CLIENT1 confirmed from DHCP within the Domain Controller.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%208.%20Lease%20For%20CLIENT1%20User%20From%20DHCP%20View%20In%20Domain%20Controller.PNG"/> <br />
<br />
<p align="center">
Figure 10: Password Policy settings configured to meet organizational requirements.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%2021.%20Changed%20Default%20Password%20Policies.PNG"/> <br />
<br />
<p align="center">
Figure 11: Account Lockout Policy setting configured to meet organizational requirements.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%2020.%20Configured%20Account%20Lockout%20Attempts.PNG"/> <br />
<br />
<p align="center">
Figure 12: New user Humbleton Fouse created within AD.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%2011.%20New%20User%20Humbleton%20Fouse.PNG"/> <br />
<br />
<p align="center">
Figure 13: Humbleton Fouse next logon password change setting enabled.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%2012.%20Humbleton%20Fouse%20Next%20Logon%20Password%20Change%20Setting%20Enabled.PNG"/> <br />
<br />
<p align="center">
Figure 14: Humbleton Fouse password change prompt when attempting to login to CLIENT1.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%2014.%20Humbleton%20Fouse%20Password%20Change%20Prompt.PNG"/> <br />
<br />
<p align="center">
Figure 15: Successful password change for Humbleton Fouse while attempting to login to CLIENT1.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%2015.%20Successful%20Password%20Change%20For%20Humbleton%20Fouse.PNG"/> <br />
<br />
<p align="center">
Figure 16: Successful logon for Humbleton Fouse into CLIENT1.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%2016.%20Humbleton%20Fouse%20Successful%20Signon%20After%20Password%20Change.PNG"/> <br />
<br />
<p align="center">
Figure 17: Leonel Cavalier account lockout after too many failed login attempts.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%2022.%20Leonel%20Cavalier%20Account%20Lockout.PNG"/> <br />
<br />
<p align="center">
Figure 18: Leonel Cavalier password reset and account unlocked in AD.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%2023.%20Leonel%20Cavalier%20Password%20Reset%20%26%20Account%20Unlocked%20AD%20Settings.PNG"/> <br />
<br />
<p align="center">
Figure 19: Leonel Cavalier successfully logging into CLIENT1 after password reset and account unlock.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/AD%2024.%20Leonel%20Cavalier%20Successful%20Logon%20After%20Account%20Unlock.PNG"/> <br />
<br />
