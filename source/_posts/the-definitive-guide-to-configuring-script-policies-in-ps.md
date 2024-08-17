---
title: The Definitive Guide to Configuring Script Policies in PS
date: 2024-08-16T01:32:48.941Z
updated: 2024-08-17T01:32:48.941Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Definitive Guide to Configuring Script Policies in PS
excerpt: This Article Describes The Definitive Guide to Configuring Script Policies in PS
keywords: Policy Configuration PS Guide,Script Settings Guide PS,PS Policy Management Tips,Setting Script Rules PS,Mastering PS Policy Configure,PS Script Policies Expertise,Configuring PS Scripts Definitive
thumbnail: https://thmb.techidaily.com/e12562333e85045ab9221a99e913b83b793150ee785e5f59fee7c9f18bec3976.png
---

## The Definitive Guide to Configuring Script Policies in PS

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

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Enable PowerShell Execution Policy Using the Settings App

 You can change and set the PowerShell execution policy to RemoteSigned using the Settings app. All you have to do is tweak the PowerShell settings in the developers' section to change the execution policy to enable PowerShell script execution.

To change execution policy using Settings:

1. Press**Win + I** to open Se**t** tings.
2. Open the**Privacy & Security** tab in the left pane.
3. Next, click on**For developers.**  
![windows 11 for developers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-for-developers.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
4. Click to expand the**PowerShell** section.
5. Toggle the switch to **change the execution policy to allow local PowerShell scripts to run without signing - Require signing for remote scripts** .  
![enable powershell script execution windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-powershell-script-execution-windows-11-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
6. Once done, open PowerShell, type get**executionpolicy,** and press**Enter** . The execution policy for the current user is now set to**RemoteSigned.**
7. If you need to disable the execution policy, toggle the PowerShell switch and set it to**Off** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-video-capture.techidaily.com/new-the-definitive-guide-to-live-streaming-platforms-obs-edition-for-2024/"><u>[New] The Definitive Guide to Live Streaming Platforms - OBS Edition for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-top-5-gaming-monitors-to-perfect-ps5-and-xbox-experience/"><u>[New] Top 5 Gaming Monitors to Perfect PS5 and Xbox Experience</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-image-all-screen-website-view/"><u>[Updated] Image All-Screen Website View</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-adobe-photostability-effective-or-fanciful/"><u>2024 Approved  Adobe PhotoStability  Effective or Fanciful?</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-infinix-note-30i-drfone-by-drfone-virtual-android/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Infinix Note 30i | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alternate-routes-to-open-the-latest-windows-apps/"><u>Alternate Routes to Open the Latest Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brightness-boost-for-windows-11-control-your-pcs-glow/"><u>Brightness Boost for Windows 11: Control Your PC's Glow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curtailing-premature-windows-edge-tabs/"><u>Curtailing Premature Windows Edge Tabs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-task-manager-with-finesse/"><u>Elevating Task Manager with Finesse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-file-organization-grouped-directories-at-a-glance-on-windows-11/"><u>Enhance File Organization - Grouped Directories at a Glance on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-vigilance-tracking-top-7-potential-infection-pathways/"><u>Essential Windows Vigilance: Tracking Top 7 Potential Infection Pathways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-a-windows-11-recycle-bin-malfunction/"><u>Fixing a Windows 11 Recycle Bin Malfunction</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-oppo-find-x7-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Oppo Find X7 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-11-command-not-working-issue/"><u>Fixing Windows 11 Command Not Working Issue</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-honor-x50iplus-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your Honor X50i+ FRP Locks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-a-tidy-desktop-unnecessary-windows-software-list/"><u>Get a Tidy Desktop: Unnecessary Windows Software List</u></a></li>
<li><a href="https://network-issues.techidaily.com/graphics-malfunction-resolved-and-system-stable/"><u>Graphics Malfunction Resolved and System Stable</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-apple-photo-imports-that-go-wrong-on-pcs-windows/"><u>How to Handle Apple Photo Imports That Go Wrong on PCs (Windows)</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-a-gamers-guide-to-twisting-videos-on-youtube-2e/"><u>In 2024, A Gamer's Guide to Twisting Videos on YouTube (2E)</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-huntings-top-5-high-quality-video-recorders/"><u>In 2024, Hunting's Top 5 High-Quality Video Recorders</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-oppo-a78-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Simple and Effective Ways to Change Your Country on YouTube App Of your Oppo A78 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insight-into-the-functionality-of-windows-component-services/"><u>Insight Into the Functionality of Windows Component Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jump-from-smartphone-to-desktop-android-gameplay-in-windows-11-with-google/"><u>Jump From Smartphone to Desktop: Android Gameplay in Windows 11 with Google</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-challenges-a-guide-to-fixing-your-manager-tool-in-windows-11/"><u>Navigating Challenges: A Guide to Fixing Your Manager Tool in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-cooling-policies-in-microsofts-os-environment/"><u>Navigating Cooling Policies in Microsoft's OS Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-keyboard-functionality-embedding-commands-for-wordpad-into-context-bar/"><u>Optimizing Keyboard Functionality: Embedding Commands for Wordpad Into Context Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-net-core-not-installed-app-issue-in-windows/"><u>Overcoming .NET Core Not Installed App Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-operation-failure-in-windows-11-error-0x0000011b/"><u>Overcoming Operation Failure in Windows 11 (Error 0X0000011B)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11s-sudden-security-hurdles/"><u>Overcoming Windows 11'S Sudden Security Hurdles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-pin-removal-functionality-in-windows-11-os/"><u>Restoring PIN Removal Functionality in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-windows-11-safe-mode-access/"><u>Step-by-Step Guide to Windows 11 Safe Mode Access</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/subscription-sensation-top-10-youtube-personalities-by-counts-for-2024/"><u>Subscription Sensation  Top 10 YouTube Personalities by Counts for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/tactics-to-maximize-vimeo-viewership/"><u>Tactics to Maximize Vimeo Viewership</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722878173815-the-future-is-here-with-the-rumored-nothing-phone-amidst-speculation-on-release-dates-pricing-and-features/"><u>The Future Is Here with the Rumored Nothing Phone Amidst Speculation on Release Dates, Pricing & Features.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-guide-for-outdated-pcs-on-their-way-to-windows-11/"><u>The Guide for Outdated PCs on Their Way to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-right-pace-for-your-cursor-how-to-turn-off-acceleration-win-11/"><u>The Right Pace for Your Cursor: How to Turn Off Acceleration Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-subtle-art-of-windows-11s-user-information-extraction/"><u>The Subtle Art of Windows 11'S User Information Extraction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-for-generating-flawless-ai-images-on-windows-11-through-paint-tool-sai/"><u>The Ultimate Guide for Generating Flawless AI Images on Windows 11 Through Paint Tool SAI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-grandmas-old-computer-for-better-use/"><u>Transform Your Grandma’s Old Computer for Better Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-eliminating-no-servers-found-in-apex-legends-(156-chars/"><u>Troubleshooting: Eliminating 'No Servers Found' In Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-adobes-secrets-ms-store-version-acquisition/"><u>Unlocking Adobe's Secrets: MS Store Version Acquisition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-how-to-engage-telnet-securely/"><u>Windows 11: How to Engage Telnet Securely</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-ui-evolution-focusing-on-the-taskbar/"><u>Windows UI Evolution - Focusing on the Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wisdom-three-routes-to-your-games-data/"><u>Windows Wisdom: Three Routes to Your Games' Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-against-zero-x-eight-oh-three-one-f-failures-in-mail-apps/"><u>Winning Against Zero X Eight Oh Three One F Failures in Mail Apps</u></a></li>
</ul></div>
