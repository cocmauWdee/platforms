# How to enable concurrent remote desktop sessions on Windows Server 2012 R2 with termsrv.dll patch
 
If you want to allow multiple users to access your Windows Server 2012 R2 machine remotely at the same time, you may need to patch the termsrv.dll file. This file is responsible for limiting the number of remote desktop sessions to one per user. By modifying some bytes in this file, you can enable concurrent remote desktop sessions on non-server Windows editions.
 
However, patching the termsrv.dll file manually can be tricky and risky. You need to stop the Remote Desktop Service, take ownership of the file, grant yourself full permissions, find and replace the correct bytes, and restart the service. Moreover, you may need to repeat this process after every Windows update that changes the termsrv.dll file.
 
**DOWNLOAD ✺✺✺ [https://www.google.com/url?q=https%3A%2F%2Furlin.us%2F2uM4Kw&sa=D&sntz=1&usg=AOvVaw3E1hYE9JY5MRzBwrsrCp8y](https://www.google.com/url?q=https%3A%2F%2Furlin.us%2F2uM4Kw&sa=D&sntz=1&usg=AOvVaw3E1hYE9JY5MRzBwrsrCp8y)**


 
Fortunately, there are some tools that can simplify this process and automate it for you. One of them is TermsrvPatcher[^2^], a free and open source application that can patch the termsrv.dll file with a few clicks. It also allows you to configure some additional settings for remote desktop, such as enabling blank password logon or multiple sessions per user. It can even create a scheduled task that runs the patcher at startup in unattended mode, so you don't have to worry about Windows updates breaking your concurrent remote desktop sessions.
 
In this article, we will show you how to use TermsrvPatcher to enable concurrent remote desktop sessions on Windows Server 2012 R2 with termsrv.dll patch.
 
## Step 1: Download and run TermsrvPatcher
 
You can download TermsrvPatcher from its GitHub page[^2^]. The latest version at the time of writing is 1.0.0.0. You will need .NET Framework 4.7.2 or newer to run it.
 
Once you have downloaded the zip file, extract it to a folder of your choice and run TermsrvPatcher.exe as administrator. You should see a window like this:
 
windows server 2012 r2 termsrv.dll patch 53,  how to fix termsrv.dll error 53 on windows server 2012,  termsrv.dll version 53 for windows server 2012 download,  windows server 2012 termsrv.dll multiple rdp sessions 53,  termsrv.dll access denied error code 53 windows server 2012,  windows server 2012 termsrv.dll location 53,  termsrv.dll missing or corrupt windows server 2012 53,  windows server 2012 termsrv.dll hack 53,  termsrv.dll update for windows server 2012 rdp wrapper 53,  windows server 2012 termsrv.dll remote desktop services 53,  termsrv.dll blue screen of death windows server 2012 53,  windows server 2012 termsrv.dll concurrent sessions 53,  termsrv.dll registry settings for windows server 2012 rdp 53,  windows server 2012 termsrv.dll crack 53,  termsrv.dll file size for windows server 2012 rdp limit 53,  windows server 2012 termsrv.dll exploit 53,  termsrv.dll backup and restore for windows server 2012 rdp port change 53,  windows server 2012 termsrv.dll disable nla 53,  termsrv.dll permissions for windows server 2012 rdp users group policy 53,  windows server 2012 termsrv.dll enable multiple monitors 53,  termsrv.dll compatibility for windows server 2012 rdp client versions 53,  windows server 2012 termsrv.dll firewall settings 53,  termsrv.dll replacement for windows server 2012 rdp encryption level change 53,  windows server 2012 termsrv.dll group policy settings 53,  termsrv.dll modification for windows server 2012 rdp timeout configuration change
 ![TermsrvPatcher screenshot](screenshot100percent.png) 
## Step 2: Patch termsrv.dll
 
Before you patch the termsrv.dll file, you need to make sure that the Remote Desktop Service is running and that remote desktop is enabled on your machine. You can check these settings from the RDP Settings tab of TermsrvPatcher.
 
If everything is OK, go to the Patch tab and click on Patch termsrv.dll. The application will stop the Remote Desktop Service, take ownership of the file, grant full permissions, apply the patch from the Patches.txt file (which contains example patches for different versions of termsrv.dll), and restart the service.
 
If the patching is successful, you should see a message like this:

    Patching successful
    termsrv.dll version: 6.3.9600.20165
    Patch applied: [6.3.*] Single User Offset x64

If the patching fails, you may need to find a different patch for your version of termsrv.dll or try another tool such as RDP Wrapper[^1^].
 
## Step 3: Configure additional settings (optional)
 
If you want to customize some additional settings for remote desktop, such as enabling blank password logon or multiple sessions per user, you can do so from the RDP Settings tab of TermsrvPatcher.
 
For example, if you want to allow users to log on remotely with blank passwords, you need to check the Enable blank password logon option and click on Apply settings.
 
If you want to allow multiple sessions per user, you need to check the Enable multiple sessions per user option and click on Apply settings.
 
## Step 4: Create a scheduled task (optional)
 
If you want to make sure that your concurrent remote desktop sessions are not affected by Windows updates that change the termsrv.dll file, you can create a scheduled task that runs TermsrvPatcher at startup in unattended mode.
 
To do this, go to the Scheduled Task tab of TermsrvPatcher and click on Create scheduled task. The application will create a task named
 8cf37b1e13
 
