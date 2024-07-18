# Keylogger Demo

## Background and Disclosure
The purpose of this lab is to demonstrate a foundational understanding of keylogging, how keyloggers are written, executed, and how logged information can be sent to a threat actor. This demonstration was done in a virtual machine operated by me alone and was not distributed outside of the virtual machine. This demo is meant for educational and informational purposes only, and is not meant to encourage or instruct others to take this information and use it for harmful purposes.<br />
<br />
The progress of this lab is outlined in the Description and displayed in the Screenshots sections below.

## Description
- Set up a virtual machine for testing a keylogger program run by Windows Visual Studio 2022.
- Whitelisted keylogger file in Windows Defender to allow for testing and execution.
- Configured a C# keylogger template to meet custom parameters.
-	Linked a test Gmail account to the C# using a uniquely generated app password for third-party connections.
-	Set keylogger to record 150 bytes before sending the log to the test Gmail address.
-	Modified the Output Type of the script so the keylogger will run discretely in the background.
-	Demonstrated the keylogger harvesting login credentials to a banking website and sending those logs to the test email address.
-	Located the executable file for this project to show that it could theoretically be shared with others or installed on other machines.
-	Created a task in Task Scheduler for the keylogger to run upon machine startup.
-	Removed keylogger files from Defender whitelist, then tried running executable file to simulate real-time protection from such threats.

## Skills Learned
- Spyware Functionality
- Windows Task Schedueler Setup
- C# Scripting
- Third party app setup with Gmail

## Tools & Technology Used
- Oracle VirtualBox
- Microsoft Visual Studio 2022
- Gmail
- Windows Task Scheduler
- Windows Defender

## Screenshots

<p align="center">
Figure 1: C# script used in Windows Visual Studio. The test Gmail address seen here is linked to the script. 
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/Keylogger%20Demo%201.%20C%23%20Script.PNG"/> <br />
<br />
<p align="center">
Figure 2: Viewer window showing keystrokes being logged and sent to the test email. <br/>
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/Keylogger%20Demo%202.%20Log%20File%20Demo%20Screen.PNG"/> <br />
<br />
<p align="center">
Figure 3: Logs emailed to the test email once they reach the maximum byte length.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/Keylogger%20Demo%203.%20Logs%20Sent%20To%20Test%20Email.PNG"/> <br />
<br />
<p align="center">
Figure 4: Logs sent in the body and as an attachment to the email.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/Keylogger%20Demo%204.%20Logs%20Sent%20In%20Body%20of%20Email%20And%20As%20Attacment.PNG"/> <br />
<br />
<p align="center">
Figure 5: By modifying the Output Type, the keylogger will run discretely in the background.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/Keylogger%20Demo%204.%20Configured%20OutPut%20Type.PNG"/> <br />
<br />
<p align="center">
Figure 6: Example of the keylogger harvesting login credentials on a banking website.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/Keylogger%20Demo%206.%20Sample%20Login%20Banking%20Capture.PNG"/> <br />
<br />
<p align="center">
Figure 7: The same harvested credentials from Figure 6 are emailed to the test email address.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/Keylogger%20Demo%207.%20Sample%20Credentials%20Sent%20To%20Test%20Email.PNG"/> <br />
<br />
<p align="center">
Figure 8: Keylogger executeable file shown in File Explorer that could theoretically be shared with others or installed on other machines.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/Keylogger%20Demo%208.%20Shareable%20File%20With%20Custom%20Code.PNG"/> <br />
<br />
<p align="center">
Figure 9: Task setup to automatically start the keylogger in the background upon user logon.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/Keylogger%20Demo%209.%20Task%20Scheduler%20Main%20Page.PNG"/> <br />
<br />
<p align="center">
Figure 10: Task Scheduler view showing the trigger and the action of the keylogger task.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/Keylogger%20Demo%2010.%20Task%20Scheduler%20Trigger%20and%20Action.PNG"/> <br />
<br />
<p align="center">
Figure 11: Defender blocking the keylogger from running.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/Keylogger%20Demo%2011.%20Defender%20Blocking%20Keylogger%20Execution.PNG"/> <br />
<br />
<p align="center">
Figure 12: Keylogger quarantined by Defender.
<img src="https://github.com/bryanotoole/Project-Pictures/blob/main/Keylogger%20Demo%2012.%20Defender%20Blocked%20Keylogger%20Executeable.PNG"/> <br />
<br />
