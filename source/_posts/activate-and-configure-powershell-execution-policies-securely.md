---
title: Activate & Configure PowerShell Execution Policies Securely
date: 2024-07-12T17:57:58.398Z
updated: 2024-07-13T17:57:58.398Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Activate & Configure PowerShell Execution Policies Securely
excerpt: This Article Describes Activate & Configure PowerShell Execution Policies Securely
keywords: Secure PowerShell Policy,Execution Policy Activation,Configure PowerShell Security,PowerShell Settings Configuration,Safe PowerShell Execution,Policies for PowerShell Control,Enhancing PowerShell Safety
thumbnail: https://thmb.techidaily.com/d24f731fb7d4e16e9e3dad20fbd83add26d8b00ef3415c454c76fbd282fafbfc.jpg
---

## Activate & Configure PowerShell Execution Policies Securely

 iPowerShell, by default, lets you run commands (cmdlets) via its console. To execute a script, you can create a notepad file with the script code, save it with a .ps1 file extension, and execute it via the PowerShell console. You can also directly paste the script onto the console for execution.

 However, if it’s your first time executing a script via PowerShell, you’ll encounter the "running script is disabled" error. By default, script execution on PowerShell is disabled as a security measure to prevent malicious scripts from running on your system. Here we show you the two ways to enable the scrip execution policy on Windows PowerShell.

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

 You can use a [PowerShell cmdlet](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) to set the execution policy to RemoteSigned. The command-line interface makes it easy to change execution policy quickly without using the Settings app.

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
<li><a href="https://tiktok-video-recordings.techidaily.com/10-must-haves-to-optimize-and-enrich-your-discord-experience/"><u>10 Must-Haves to Optimize and Enrich Your Discord Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-open-disk-management-in-windows-11-and-11/"><u>4 Ways to Open Disk Management in Windows 11 and 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ai-infused-title-engine-your-ultimate-video-marketing-tool/"><u>AI-Infused Title Engine  Your Ultimate Video Marketing Tool</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-gain-ground-by-generating-earnings-on-your-youtube-channel-like-ajay/"><u>In 2024, Gain Ground by Generating Earnings on Your Youtube Channel Like Ajay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-windows-store-clearing-error-code-x80072f30/"><u>Troubleshoot Windows Store: Clearing Error Code X80072F30</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-microsofts-phone-link-application-functionality/"><u>Decoding Microsoft's Phone Link Application Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-auto-time-zone-switches-in-microsofts-operating-system/"><u>Bypassing Auto Time Zone Switches in Microsoft's Operating System</u></a></li>
<li><a href="https://extra-tips.techidaily.com/next-gen-heroism-gopro-hero5-black-vs-hero4-silver/"><u>Next-Gen HEROism  GoPro Hero5 Black vs Hero4 Silver</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-honor-magic-5-lite-drfone-by-drfone-virtual-android/"><u>5 Easy Ways to Change Location on YouTube TV On Honor Magic 5 Lite | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-desktop-tips-for-a-win11-masterpiece/"><u>Transform Your Desktop: Tips for a Win11 Masterpiece</u></a></li>
<li><a href="https://win11-tips.techidaily.com/timely-changes-essential-windows-programs-for-editing-file-dates/"><u>Timely Changes: Essential Windows Programs for Editing File Dates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/visual-search-enhancements-in-windows-11-file-explorer/"><u>Visual Search Enhancements in Windows 11 File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-the-tyranny-of-inconsistent-colors-in-windows/"><u>Taming the Tyranny of Inconsistent Colors in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-error-0x80131500-on-microsoft-shop/"><u>Unlocking Error #0X80131500 on Microsoft Shop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-drag-recover-lost-functionality-fast/"><u>Win11 Drag: Recover Lost Functionality Fast</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-effective-ways-to-archive-webcam-discussions/"><u>[Updated] 2024 Approved  Effective Ways to Archive Webcam Discussions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-troubleshooting-msvcr120-deficiency-windows-wise/"><u>Tips for Troubleshooting Msvcr120 Deficiency Windows-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-admin-restrictions-on-windows-safety-settings/"><u>Bypassing Admin Restrictions on Windows Safety Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-your-onedrive-save-point-on-windows-10/"><u>Altering Your OneDrive Save Point on Windows 10</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-data-from-broken-iphone-8-plus-screen-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Data from Broken iPhone 8 Plus Screen | Stellar</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-fast-tracking-visual-storytelling-with-google-collages/"><u>[Updated] Fast-Tracking Visual Storytelling with Google Collages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unmasking-your-worldwide-address-through-cmd-windows/"><u>Unmasking Your Worldwide Address Through CMD, Windows</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-save-instagram-videos-as-mp3-files-easy-methods/"><u>Updated Save Instagram Videos as MP3 Files Easy Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-command-center-for-app-and-browser-authority/"><u>Windows Command Center for App and Browser Authority</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-minitool-movie-maker-review-and-alternatives/"><u>New In 2024, Minitool Movie Maker Review and Alternatives</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-downloading-your-youtube-watch-lists-step-by-step/"><u>[New] 2024 Approved  Downloading Your YouTube Watch Lists  Step by Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trimming-down-excessive-cpu-usage-in-windows-hosts/"><u>Trimming Down Excessive CPU Usage in Windows Hosts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-method-for-heic-to-jpeg-conversion/"><u>Windows Method for Heic to Jpeg Conversion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-obstacles-for-secure-memory-settings-in-new-windows-11/"><u>Clearing Obstacles for Secure Memory Settings in New Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-xiaomi-redmi-note-12t-pro-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Xiaomi Redmi Note 12T Pro Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-boosting-vimeo-streams-tips-and-tricks/"><u>[New] In 2024, Boosting Vimeo Streams  Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-telnet-on-windows-11-systems/"><u>Unlocking Telnet on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-list-of-apps-facilitating-the-switch-from-macos-to-windows/"><u>The Ultimate List of Apps Facilitating the Switch From MACOS to WINDOWS</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-leverage-tubebuddy-for-top-tier-youtube-management/"><u>[New] Leverage TubeBuddy for Top-Tier YouTube Management</u></a></li>
</ul></div>
