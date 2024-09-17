---
title: "Enabling PowerShell Scripts: A Step-by-Step Guide"
date: 2024-09-16T04:34:55.065Z
updated: 2024-09-17T06:50:30.697Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enabling PowerShell Scripts: A Step-by-Step Guide"
excerpt: "This Article Describes Enabling PowerShell Scripts: A Step-by-Step Guide"
keywords: PowerShell Automation,Step-By-Step PS Scripting,PowerShell Basics,PS Script Creation Guide,Execute PowerShell Commands,Advanced PowerShell Techniques,Learn PowerShell Effectively
thumbnail: https://thmb.techidaily.com/7ac27936311540a3f6119be289d1db9f62edf4aff3e40a9a411ddbf297922d42.png
---

## Enabling PowerShell Scripts: A Step-by-Step Guide

 iPowerShell, by default, lets you run commands (cmdlets) via its console. To execute a script, you can create a notepad file with the script code, save it with a .ps1 file extension, and execute it via the PowerShell console. You can also directly paste the script onto the console for execution.

 However, if it’s your first time executing a script via PowerShell, you’ll encounter the "running script is disabled" error. By default, script execution on PowerShell is disabled as a security measure to prevent malicious scripts from running on your system. Here we show you the two ways to enable the scrip execution policy on Windows PowerShell.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Check Your Existing Execution Policy

![Powershell set execution policy undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-undefined.jpg)

 You can use a PowerShell cmdlet to get your current execution policy. Knowing your current execution policy is necessary to know if you need a policy change or not.

To get your current execution policy for the current user:

1. [Open Windows PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Type the following command in the PowerShell console and hit Enter:  
`get-executionpolicy`
3. Since you have encountered an error when executing the script, the return will likely show**Restricted** as your current execution policy.
4. If you need to view the execution policy for all the supported scopes:  
`get-executionpolicy -list`

 You’ll need to change the execution policy to RemoteSigned to run local scripts without the error. You can change the execution policy from the Settings app and PowerShell.

## How to Enable PowerShell Execution Policy Using the Settings App

 You can change and set the PowerShell execution policy to RemoteSigned using the Settings app. All you have to do is tweak the PowerShell settings in the developers' section to change the execution policy to enable PowerShell script execution.

To change execution policy using Settings:

1. Press**Win + I** to open Se**t** tings.
2. Open the**Privacy & Security** tab in the left pane.
3. Next, click on**For developers.**  
![windows 11 for developers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-for-developers.jpg)
4. Click to expand the**PowerShell** section.
5. Toggle the switch to **change the execution policy to allow local PowerShell scripts to run without signing - Require signing for remote scripts** .  
![enable powershell script execution windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-powershell-script-execution-windows-11-settings.jpg)
6. Once done, open PowerShell, type get**executionpolicy,** and press**Enter** . The execution policy for the current user is now set to**RemoteSigned.**
7. If you need to disable the execution policy, toggle the PowerShell switch and set it to**Off** .

## How to Allow Scripts to Run in PowerShell using PowerShell

![Powershell set execcution policy remotesigned](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-remotesigned.jpg)

 You can use a[PowerShell cmdlet](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) to set the execution policy to RemoteSigned. The command-line interface makes it easy to change execution policy quickly without using the Settings app.

 Also, the Settings app can only enable or disable the RemoteSigned execution policy. Whereas PowerShell lets you set other policies and scopes as well.

To change the execution policy using PowerShell:

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Set-ExecutionPolicy RemoteSigned`
3. If prompted, press**A** to confirm the action. This will set the**RemoteSigned** execution policy for all users. If you want to set the execution policy for the**Current User** only, use the Scope parameter followed by the username.
4. For example, to set the**RemoteSigned** execution policy for**CurrentUser** , use the following command:  
`Set-ExecutionPolicy RemoteSgined -Scope CurrentUser`
5. Replace**CurrentUser** in the above command with other users (Scope) as per your requirement.

## How to Remove Script Execution Policy Using PowerShell

![set-execution-policy-undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-execution-polify-undefined.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118304/7443" target="_top" id="2118304">
  <img src="//a.impactradius-go.com/display-ad/7443-2118304" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118304/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to disable script execution, set the execution policy to**Undefined** using th**e Set\_ExecutionPolicy** cmdlet. This is a default state and prevents PowerShell from executing any scripts.

To disable script execution using PowerShell:

1. Open PowerShell with elevated permission.
2. Next, type the following command and press enter to disable script execution for all users:  
`Set-ExecutionPolicy undefined`
3. The above command will set the execution policy default (undefined) for all the users. If you want to disable script execution for a specific scope, use the following command:  
`Set-ExecutionPolicy undefined -Scope CurrentUser`
4. The above command will disable script execution for**CurrentUser** .

## Understanding Execution Policies and Scopes

 Simply put, PowerShell’s execution policy is a policy that controls how PowerShell executes config files and scripts. The intended purpose is to prevent users from accidentally running malicious scripts. The seven PowerShell execution policies are **Default, Restricted, RemoteSigned, AllSigned, Unrestricted, Bypass, and Undefined** .

 The below table briefly explains all the PowerShell execution policies:

| Execution Policy | Enforcement                                                                                                    |
| ---------------- | -------------------------------------------------------------------------------------------------------------- |
| Default          | Sets the default execution policy as Restricted on Windows Client and RemoteSigned on Windows Server.          |
| AllSigned        | Allows execution of publisher signed scripts.                                                                  |
| Bypass           | Unrestricted execution of scripts for larger applications.                                                     |
| RemoteSigned     | Allows locally written script execution. Requires digital signatures for scripts downloaded from the internet. |
| Restricted       | Doesn’t allow script execution, but only individual PowerShell commands.                                       |
| Undefined        | Sets execution policy to Restricted for Windows clients and RemoteSigned for Windows Server.                   |
| Unrestricted     | Allow unsigned script execution with a warning for the scripts downloaded from the internet.                   |

### Execution Policy Scope

 You can set execution policy for a particular scope in PowerShell. The five execution policy scopes are**MachinePolicy, UserPolicy, Process, CurrentUser,** and**LocalMachine** .

The below table briefly explains all the execution policy scopes:

| Execution Policy Scope | Enforcement                                                                              |
| ---------------------- | ---------------------------------------------------------------------------------------- |
| UserPolicy             | Configured by a Group Policy for the current user.                                       |
| Machine Policy         | Configured by a Group Policy for all the users.                                          |
| CurrenUser             | Configured for the current user and stored in HKEY\_CURRENT\_MACHINE registry subkey.    |
| LocalMachine           | Configured for all users and stored in HKEY\_CURRENT\_MACHINE registry subkey.           |
| Process                | Affects current PowerShell session and automatically deleted when the session is closed. |

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135366/19272" target="_top" id="2135366">
  <img src="//a.impactradius-go.com/display-ad/19272-2135366" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Add or Remove PowerShell Script Execution Policy on Windows

 Script execution on PowerShell is disabled by default for Windows clients and set to RemoteSigned for Windows server. Power users, however, can change execution policies to run local, signed, and unsigned PowerShell scripts.

 Alternatively, you can bypass the PowerShell execution policy by pasting the script into a PowerShell console or ECHO your script into PowerShell standard input. This is useful if you want to execute scripts without changing the execution policy.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/024-approved-the-ultimate-guide-to-android-9-youtube-download-apps/"><u>[New] 2024 Approved The Ultimate Guide to Android 9 YouTube Download Apps</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-are-reviews-on-merchandise-streamed-for-cash/"><u>2024 Approved Are Reviews on Merchandise Streamed for Cash?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-windows-11-camera-crash-zero-a00f-problem/"><u>Clearing Up Windows 11 Camera Crash: Zero-A00F Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/corrective-measures-for-overcoming-windows-errors/"><u>Corrective Measures for Overcoming Windows Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dispatched-guide-to-deciphering-and-dismantling-error-code-a00f4289-on-win11/"><u>Dispatched Guide to Deciphering & Dismantling Error Code A00F4289 on Win11</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/est-beats-newly-trending-music-for-youtube-short-videos/"><u>Freshest Beats Newly Trending Music for YouTube Short Videos</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-guide-on-how-to-change-your-apple-id-email-address-on-apple-iphone-12-by-drfone-ios/"><u>In 2024, Guide on How To Change Your Apple ID Email Address On Apple iPhone 12</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-realme-11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Read This Guide to Find a Reliable Alternative to Fake GPS On Realme 11 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-obstacles-during-utorrent-setup-on-windows-systems/"><u>Overcoming Obstacles During uTorrent Setup on Windows Systems</u></a></li>
<li><a href="https://vp-tips.techidaily.com/premium-cloud-apps-for-android-the-most-reliable/"><u>Premium Cloud Apps for Android The Most Reliable</u></a></li>
<li><a href="https://fox-helps.techidaily.com/simple-way-to-blur-faces-in-picsart/"><u>Simple Way To Blur Faces in Picsart</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-limiting-user-access-in-windows-folders/"><u>Techniques for Limiting User Access in Windows Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-error-0xca00a009-in-windows-update/"><u>Troubleshooting Error 0xCA00A009 in Windows Update</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ultimate-aquatic-enhancements-for-gopro-footage/"><u>Ultimate Aquatic Enhancements for GoPro Footage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-data-potential-four-ways-to-tap-into-disk-editor-settings-on-windows-11/"><u>Unlock Data Potential: Four Ways to Tap Into Disk Editor Settings on Windows 11</u></a></li>
</ul></div>

