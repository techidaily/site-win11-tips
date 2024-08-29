---
title: Streamline Your PowerShell Workflow with Script Policy Controls
date: 2024-08-28T01:13:53.208Z
updated: 2024-08-29T01:13:53.208Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamline Your PowerShell Workflow with Script Policy Controls
excerpt: This Article Describes Streamline Your PowerShell Workflow with Script Policy Controls
keywords: PowerShell Efficiency,Policy-Based Execution,Automated Tasks,Script Management,Security Compliance,Workflow Simplification,Controlled Scripting
thumbnail: https://thmb.techidaily.com/92459487433dd8191ecb6f79f9b025b7d93038fc1418a5a54e50bbd98af412de.jpg
---

## Streamline Your PowerShell Workflow with Script Policy Controls

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

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Remove Script Execution Policy Using PowerShell

![set-execution-policy-undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-execution-polify-undefined.jpg)

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
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

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-support.techidaily.com/new-maximizing-engagement-best-video-optimizers/"><u>[New] Maximizing Engagement  Best Video Optimizers</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-boost-your-channels-crafting-captivating-yt-descriptions-using-custom-templates/"><u>[Updated] 2024 Approved  Boost Your Channels  Crafting Captivating YT Descriptions Using Custom Templates</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-integrating-external-websites-into-instagrams-ecosystem-for-2024/"><u>[Updated] Integrating External Websites Into Instagram's Ecosystem for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-slug-line-creation-techniques-for-online-copy/"><u>[Updated] Slug Line Creation Techniques for Online Copy</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-income-from-video-how-to-profit-on-vimeo-platform/"><u>2024 Approved  Income From Video  How to Profit on Vimeo Platform</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/compendium-of-video-camera-classifications-for-2024/"><u>Compendium of Video Camera Classifications for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/connecting-in-real-time-advanced-tips-for-streaming-screens-via-fb/"><u>Connecting in Real Time  Advanced Tips for Streaming Screens via Fb</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-editing-the-8-pinnacle-software-titles-for-windows-users/"><u>Conquer Editing: The 8 Pinnacle Software Titles for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-video-quality-chrome-and-youtube-optimization/"><u>Elevating Video Quality: Chrome and YouTube Optimization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-wows-catastrophic-glitch-in-windows-11/"><u>Fixing WoW’s Catastrophic Glitch in Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlink-apple-id-from-iphone-13-by-drfone-ios/"><u>In 2024, How To Unlink Apple ID From iPhone 13</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-watch-hulu-outside-us-on-gionee-f3-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Watch Hulu Outside US On Gionee F3 Pro | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-snap-into-action-a-compelling-ig-gallery-of-inspiration/"><u>In 2024, Snap Into Action! A Compelling IG Gallery of Inspiration</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-10-password-cracking-tools-for-infinix-note-30-pro-by-drfone-android/"><u>In 2024, Top 10 Password Cracking Tools For Infinix Note 30 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inside-the-role-of-ai-in-microsofts-store/"><u>Inside: The Role of AI in Microsoft's Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-efficiency-with-concurrent-subfolder-creation-on-windows-pcs/"><u>Maximize Your Efficiency with Concurrent Subfolder Creation on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-productivity-with-reimagined-windows-11-widgets/"><u>Maximizing Productivity with Reimagined Windows 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-experience-outlook-preview-for-windows-11-enthusiasts/"><u>Optimize Your Experience: Outlook Preview for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-disconnecting-woes-essential-fixes-for-windows-usb-wifi/"><u>Overcome Disconnecting Woes – Essential Fixes for Windows USB Wifi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-share-denial-in-microsoft-os/"><u>Overcome Share Denial in Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establishing-ethernet-connectivity-on-windows/"><u>Re-Establishing Ethernet Connectivity on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-default-view-configurations-in-windows/"><u>Reinstating Default View Configurations in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-non-transferring-usb-cases-in-the-windows-environment/"><u>Remedying Non-Transferring USB Cases in the Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-your-invisible-connection-on-microsofts-new-os/"><u>Resurrecting Your Invisible Connection on Microsoft's New OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sneaky-storage-concealing-drives-on-windows-os/"><u>Sneaky Storage: Concealing Drives on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-fix-for-windows-error-0x80071a90/"><u>Step-by-Step Fix for Windows Error 0X80071A90</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-11-login-processes/"><u>Streamlining Windows 11 Login Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-blocking-insecure-device-connections-on-windows/"><u>Tips for Blocking Insecure Device Connections on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-fixing-drivers-that-wont-load-in-win11/"><u>Tips for Fixing Drivers that Won't Load in Win11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-imei-unlokers-for-your-vivo-phone-by-drfone-android/"><u>Top IMEI Unlokers for Your Vivo Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncover-the-secrets-to-flawless-subtitle-display-on-windows-11/"><u>Uncover the Secrets to Flawless Subtitle Display on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/undoing-greyed-out-bin-fixes-on-win11/"><u>Undoing Greyed Out Bin Fixes on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unifying-your-windows-serial-with-ms-accounts/"><u>Unifying Your Windows Serial with MS Accounts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-productivity-with-w11s-quick-actions/"><u>Unleash Productivity with W11's Quick Actions</u></a></li>
</ul></div>
