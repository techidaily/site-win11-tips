---
title: "Enabling PowerShell Scripts: A Step-by-Step Guide"
date: 2024-10-02T02:58:15.680Z
updated: 2024-10-09T07:19:38.376Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135405/19272" target="_top" id="2135405">
  <img src="//a.impactradius-go.com/display-ad/19272-2135405" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135405/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528696/16446" target="_top" id="1528696">
  <img src="//a.impactradius-go.com/display-ad/16446-1528696" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528696/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Remove Script Execution Policy Using PowerShell

![set-execution-policy-undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-execution-polify-undefined.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134493/18498" target="_top" id="2134493">
  <img src="//a.impactradius-go.com/display-ad/18498-2134493" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134493/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to disable script execution, set the execution policy to**Undefined** using th**e Set\_ExecutionPolicy** cmdlet. This is a default state and prevents PowerShell from executing any scripts.

To disable script execution using PowerShell:

1. Open PowerShell with elevated permission.
2. Next, type the following command and press enter to disable script execution for all users:  
`Set-ExecutionPolicy undefined`
3. The above command will set the execution policy default (undefined) for all the users. If you want to disable script execution for a specific scope, use the following command:  
`Set-ExecutionPolicy undefined -Scope CurrentUser`
4. The above command will disable script execution for**CurrentUser** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135396/19272" target="_top" id="2135396">
  <img src="//a.impactradius-go.com/display-ad/19272-2135396" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135396/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-infographic-8-ways-to-make-money-on-youtube-for-beginners/"><u>[New] 2024 Approved Infographic - 8 Ways to Make Money on YouTube for Beginners</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-window-capture-suite-pro-xp/"><u>[Updated] In 2024, Window Capture Suite Pro XP</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/10-free-legal-chants-and-sounds-for-meditation-practice/"><u>10 Free Legal Chants and Sounds for Meditation Practice</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-hps-color-expertise-in-full-display-the-z32x-review/"><u>2024 Approved HP's Color Expertise in Full Display The Z32X Review</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/advance-your-tech-comparisons-utilizing-geekbenchs-cutting-edge-benchmarking-features-for-devices/"><u>Advance Your Tech Comparisons: Utilizing Geekbench's Cutting-Edge Benchmarking Features for Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-internal-failure-in-win11win10-connections/"><u>Correcting Internal Failure in Win11/Win10 Connections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-taskbar-functionality-with-new-contextual-folders/"><u>Enhancing Taskbar Functionality with New Contextual Folders</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-lock-on-your-apple-iphone-11-pro-max-and-ipad-by-drfone-ios/"><u>How to Unlock iCloud lock on your Apple iPhone 11 Pro Max and iPad?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-your-xiaomi-13-ultra-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Xiaomi 13 Ultra Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-full-load-in-windows-chatgpt/"><u>Mitigating Full Load in Windows ChatGPT</u></a></li>
<li><a href="https://fox-useful.techidaily.com/mobile-access-made-easy-how-to-enjoy-your-digital-albums-on-smartphones-via-flipbuilders-platform/"><u>Mobile Access Made Easy: How to Enjoy Your Digital Albums on Smartphones via FlipBuilder's Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-the-100-obstacle-in-windows-update-processes/"><u>Overcome the 100% Obstacle in Windows Update Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-address-phantom-devices-in-pcs/"><u>Strategies to Address Phantom Devices in PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-strategies-for-tackling-windows-camera-errors/"><u>Swift Strategies for Tackling Windows Camera Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-reigniting-winget-in-windows-11/"><u>Troubleshooting: Reigniting Winget in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unsticking-windows-update-quick-repair-tips/"><u>Unsticking Windows Update: Quick Repair Tips</u></a></li>
<li><a href="https://apple-account.techidaily.com/visionary-auto-crypto-analysts-2024-prospectus/"><u>Visionary Auto Crypto Analysts, 2024 Prospectus</u></a></li>
</ul></div>

