---
title: A Practical Approach to Setting PowerShell Policies
date: 2024-08-16T01:58:39.133Z
updated: 2024-08-17T01:58:39.133Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Practical Approach to Setting PowerShell Policies
excerpt: This Article Describes A Practical Approach to Setting PowerShell Policies
keywords: PowerShell Policy Basics,Policy Enforcement in PS,Secure PS Configurations,Implementing PS Rules,PowerShell Governance Tips,Effective PS Guidelines,Mastering PS Security Settings
thumbnail: https://thmb.techidaily.com/c6cef7d8d098cc3ec193ea28736f5c8bb8a150dde0b8653330eff8897000d29a.jpeg
---

## A Practical Approach to Setting PowerShell Policies

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
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
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
6. Once done, open PowerShell, type get**executionpolicy,** and press**Enter** . The execution policy for the current user is now set to**RemoteSigned.**
7. If you need to disable the execution policy, toggle the PowerShell switch and set it to**Off** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Allow Scripts to Run in PowerShell using PowerShell
![Powershell set execcution policy remotesigned](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-remotesigned.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
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

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-zero.techidaily.com/0-recording-tips-to-record-audio-in-high-quality-for-2024/"><u>[New] 10 Recording Tips to Record Audio in High Quality for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-correct-iosandroid-video-failures-on-fb-for-2024/"><u>[New] Correct iOS/Android Video Failures on FB for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-cross-platform-video-sharing-tiktok-and-twitter-for-2024/"><u>[New] Cross-Platform Video Sharing  TikTok & Twitter for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-ideal-screen-recorder-picks-for-digital-educators/"><u>[New] Ideal Screen Recorder Picks for Digital Educators</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-itunes-masterclass-maximizing-video-outputs/"><u>[Updated] In 2024, ITunes Masterclass  Maximizing Video Outputs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-fast-passes-to-the-control-settings-hub/"><u>11 Fast Passes to the Control Settings Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-routes-to-activate-telnet-in-windows-11-os/"><u>3 Routes to Activate Telnet in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-improve-your-gaming-experience-on-a-windows-11-pc/"><u>7 Ways to Improve Your Gaming Experience on a Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compreenasolutiontowindowss-lsass-problem-step-by-step-guide/"><u>A CompreenasolutiontoWindows's Lsass Problem: Step by Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensible-approach-to-batch-installations-on-windows-11-via-winstall/"><u>A Comprehensible Approach to Batch Installations on Windows 11 via Winstall</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensible-windows-screentime-intermission/"><u>A Comprehensible Window's Screentime Intermission</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-plan-for-installing-win11-version-22h2-updater/"><u>A Step-by-Step Plan for Installing WIN11 Version 22H2 Updater</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-pcs-problems-4-top-pct-strategies/"><u>Ace Your PC's Problems: 4 Top PCT Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-peak-performance-tweaking-amd-radeon-windows-settings/"><u>Achieve Peak Performance: Tweaking AMD Radeon Windows Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-oculus-quest-2-for-windows-vr-compatibility/"><u>Adapting Oculus Quest 2 for Windows VR Compatibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absent-file-application-linkages-in-win10/"><u>Addressing Absent File Application Linkages in Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-x80049dd3-for-smooth-typing-on-windows-11/"><u>Addressing Error X80049DD3 for Smooth Typing on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719365401948-addressing-windows-printer-issues-a-guide-for-unresponsive-print-commands/"><u>Addressing Windows Printer Issues: A Guide for Unresponsive Print Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-terminal-background-for-custom-aesthetics/"><u>Adjust Terminal Background for Custom Aesthetics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-words-settings-for-consistent-openness-of-email-attachments-as-text/"><u>Adjust Word's Settings for Consistent Openness of Email Attachments as Text</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-settings-for-continuous-save-support-in-nvidia-control-center/"><u>Adjusting Settings for Continuous Save Support in NVidia Control Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-outlook-speed-for-a-smooth-win-experience/"><u>Amplify Outlook Speed for a Smooth WIN Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-your-digital-experience-adding-directories-to-taskbar-menu/"><u>Amplify Your Digital Experience: Adding Directories to Taskbar Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-overview-of-the-windows-canary-security-feature/"><u>An Overview of the Windows Canary Security Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-connectivity-boost-for-windows-11-webcams/"><u>Android Connectivity Boost for Windows 11 Webcams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automatic-restart-the-windows-10-and-11-power-down-protocol/"><u>Automatic Restart: The Windows 10 & 11 Power-Down Protocol</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-a-blank-desktop-win-11-icon-fixes/"><u>Avoid a Blank Desktop: Win 11 Icon Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-disruptions-how-to-mend-broken-windows-registry-items/"><u>Avoiding Disruptions: How to Mend Broken Windows Registry Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bid-farewell-to-your-drives-segmentation-with-these-windows-methods/"><u>Bid Farewell to Your Drive's Segmentation with These Windows Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-with-these-5-unique-windows-pc-time-saver-tools/"><u>Boost Productivity with These 5 Unique Windows PC Time Saver Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-edge-safety-implement-windows-11-defender-application-guard/"><u>Boosting Edge Safety: Implement Windows 11 Defender Application Guard</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-tecno-spark-10-pro-drfone-by-drfone-virtual-android/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Tecno Spark 10 Pro | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-to-oneplus-nord-n30-se-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to OnePlus Nord N30 SE FRP Bypass With Best Methods</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/edit-like-a-pro-the-5-best-iphone-video-editing-apps/"><u>Edit Like a Pro The 5 Best iPhone Video Editing Apps</u></a></li>
<li><a href="https://program-issues.techidaily.com/end-gm-crash-dilemma-proven-solutions-to-stabilize-your-game/"><u>End GM Crash Dilemma: Proven Solutions to Stabilize Your Game</u></a></li>
<li><a href="https://hardware-help.techidaily.com/free-xbox-nxplorer-program-how-to-drive-games-with-an-xbox-360-pad/"><u>Free Xbox nXplorer Program - How to Drive Games with an Xbox 360 Pad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719204304616-gpt4all-free-chatbot-clones-at-home-for-windows/"><u>GPT4All: Free ChatBot Clones at Home for Windows.</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-zoom-mastery-for-selfie-success-in-instagram-stories/"><u>In 2024, Zoom Mastery for Selfie Success in Instagram Stories</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719348868755-is-your-pc-compatible-with-windows-11-see-here/"><u>Is Your PC Compatible with Windows 11? See Here</u></a></li>
<li><a href="https://driver-download.techidaily.com/1722968936708-quick-fix-how-to-update-the-surface-dock-drivers-with-speed/"><u>Quick Fix: How to Update the Surface Dock Drivers with Speed!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719370071964-resolve-wwin-plus-p-non-functionality-in-windows-systems/"><u>Resolve WWin + P Non-Functionality in Windows Systems.</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/steady-visual-storytelling-techniques/"><u>Steady Visual Storytelling Techniques</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-battle-between-github-copilot-and-chatgpt-which-is-a-better-programming-assistant/"><u>The Battle Between GitHub Copilot and ChatGPT: Which Is a Better Programming Assistant?</u></a></li>
</ul></div>
