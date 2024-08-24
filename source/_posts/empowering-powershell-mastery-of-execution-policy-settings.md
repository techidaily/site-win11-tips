---
title: "Empowering PowerShell: Mastery of Execution Policy Settings"
date: 2024-08-23T07:00:21.333Z
updated: 2024-08-24T07:00:21.333Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Empowering PowerShell: Mastery of Execution Policy Settings"
excerpt: "This Article Describes Empowering PowerShell: Mastery of Execution Policy Settings"
keywords: PowerShell Controls,ExecPolicy Mastery,Scripting Authority,Secure Run Asmsgs,Exec Policy Management,Enhance PowerShell,Policy Configuration Skills
thumbnail: https://thmb.techidaily.com/c40243a18120050792e9b2a35c08e8c187a7242ae42c21363a9149298cc2eac3.jpg
---

## Empowering PowerShell: Mastery of Execution Policy Settings

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
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Allow Scripts to Run in PowerShell using PowerShell

![Powershell set execcution policy remotesigned](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-remotesigned.jpg)

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
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
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
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
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-record-video-directly-from-webcam-using-vlc-media-player/"><u>[New] 2024 Approved  Record Video Directly From Webcam Using VLC Media Player</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-how-to-create-a-square-video-for-instragram-in-imovie-for-2024/"><u>[New] How to Create a Square Video for Instragram in iMovie for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-novice-film-capture-scrutiny-report/"><u>[New] In 2024, Novice Film Capture Scrutiny Report</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-revolutionize-your-content-a-step-by-step-guide-to-tiktoks-audio-amplification/"><u>[New] In 2024, Revolutionize Your Content  A Step-by-Step Guide to TikTok's Audio Amplification</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-streamlined-processes-for-effective-apple-display-recording/"><u>[New] In 2024, Streamlined Processes for Effective Apple Display Recording</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-transform-your-podcasts-identity-with-ai-name-makers-for-2024/"><u>[New] Transform Your Podcast's Identity with AI Name Makers for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-fresh-footage-frequent-flows-dos-and-donts-for-streamlining-video-content/"><u>[Updated] 2024 Approved  Fresh Footage, Frequent Flows  Do's & Don'ts for Streamlining Video Content</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-a-detailed-examination-of-mycam-for-smart-home-setups/"><u>[Updated] A Detailed Examination of MyCam for Smart Home Setups</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-flavorful-faves-top-online-chefs-and-culinary-stars-for-2024/"><u>[Updated] Flavorful Faves  Top Online Chefs & Culinary Stars for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-innovative-and-simple-18-vlogging-projects/"><u>2024 Approved  Innovative & Simple  18 Vlogging Projects</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-innovative-scripting-for-advanced-typography-in-after-effects/"><u>2024 Approved  Innovative Scripting for Advanced Typography in After Effects</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-photos-from-realme-narzo-60-pro-5g-by-fonelab-android-recover-photos/"><u>Best Android Data Recovery - Retrieve Lost Photos from Realme Narzo 60 Pro 5G.</u></a></li>
<li><a href="https://extra-tips.techidaily.com/classic-chimes-catalogue-websites-of-worth/"><u>Classic Chimes Catalogue  Websites of Worth</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curtail-extra-audio-boost-in-windows/"><u>Curtail Extra Audio Boost in Windows</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-updated-hp-scanjet-driver-for-enhanced-performance-on-windows-1187-devices/"><u>Download Updated HP Scanjet Driver for Enhanced Performance on Windows 11/8/7 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-workflow-with-process-management-and-aesthetic-overhaul-in-w11/"><u>Elevate Workflow with Process Management & Aesthetic Overhaul in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-geforce-nows-xc0f1103f-hitch-in-windows-11/"><u>Eliminate GeForce Now's Xc0f1103f Hitch in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-chromiums-network-access-over-windows-security-barrier/"><u>Enabling Chromium's Network Access Over Windows Security Barrier</u></a></li>
<li><a href="https://win11-tips.techidaily.com/express-guide-to-determine-windows-11-gpu-variant/"><u>Express Guide to Determine Windows 11 GPU Variant</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-the-most-out-of-windows-backup-features/"><u>Get the Most Out of Windows Backup Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-add-a-portable-software-menu-to-windows-11-and-11/"><u>How to Add a Portable Software Menu to Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-screen-flickering-and-flashing-on-windows-10-and-11/"><u>How to Fix Screen Flickering and Flashing on Windows 10 and 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-fix-the-lagging-issues-in-valheim-on-your-pc/"><u>How to Fix the Lagging Issues in Valheim on Your PC</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-touch-screen-on-realme-c55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Realme C55 | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-realme-narzo-60-5g-to-mac-drfone-by-drfone-android/"><u>How to Mirror Realme Narzo 60 5G to Mac? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-apple-iphone-12-data-from-ios-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How to Recover Apple iPhone 12 Data From iOS iCloud? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-special-features-virtual-location-on-itel-a05s-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Itel A05s? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-honor-100-drfone-by-drfone-virtual-android/"><u>In 2024, How to get the dragon scale and evolution-enabled pokemon On Honor 100? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-larger-pictures-same-sharpness-levels/"><u>In 2024, Larger Pictures, Same Sharpness Levels</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-ultimate-guide-from-xiaomi-13t-pro-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide from Xiaomi 13T Pro FRP Bypass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-machine-11-ways-to-open-control-panel/"><u>Master Your Machine: 11 Ways to Open Control Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-words-best-windows-apps-for-writers/"><u>Mastering Words: Best Windows Apps for Writers</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-elevate-your-footage-expert-advice-for-stunning-home-videos/"><u>New 2024 Approved Elevate Your Footage Expert Advice for Stunning Home Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-your-win-11-experience-game-changing-advice-for-the-winning-side/"><u>Optimizing Your Win 11 Experience: Game-Changing Advice for the Winning Side</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-secure-authentication-problems-with-the-epic-launcher/"><u>Overcoming Secure Authentication Problems with the Epic Launcher</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/photos-come-alive-with-accompanied-melodies-for-2024/"><u>Photos Come Alive with Accompanied Melodies for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-bing-chat-integration-in-windows-11/"><u>Quick Guide to Bing Chat Integration in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-outlook-responses-a-windows-fix-guide/"><u>Quick Outlook Responses: A Windows Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-reviving-a-sluggish-windows-11-experience/"><u>Quick Tips: Reviving a Sluggish Windows 11 Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-syncopation-combining-dropbox-and-googledrive-driveletters/"><u>Simplifying Syncopation: Combining Dropbox and GoogleDrive DriveLetters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealthy-setups-mastering-the-invisible-menu-features/"><u>Stealthy Setups: Mastering the Invisible Menu Features</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-correcting-missing-sound-device-issues-in-windows-1011/"><u>Step-by-Step Guide: Correcting Missing Sound Device Issues in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-fingerprint-scanner-unsupported-problems/"><u>Steps to Resolve 'Fingerprint Scanner Unsupported' Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-commence-quickly-open-windows-and-sticky-notes/"><u>Streamlined Commence: Quickly Open Windows and Sticky Notes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-qr-code-processes-with-windows-os/"><u>Streamlining QR Code Processes with Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-efficiency-in-windows-using-smart-launcher-tech/"><u>Supercharge Efficiency in Windows Using Smart Launcher Tech</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/the-netgear-powerline-av-1200-assessment-how-heavy-design-impacts-connection-speed/"><u>The Netgear Powerline AV 1200 Assessment: How Heavy Design Impacts Connection Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-real-deal-on-applecareplus-does-the-extra-security-make-financial-sense/"><u>The Real Deal on AppleCare+ – Does the Extra Security Make Financial Sense?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-automated-file-deletion-on-windows/"><u>The Ultimate Guide to Automated File Deletion on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/timeless-traits-windows-11s-retained-7-classic-characteristics/"><u>Timeless Traits: Windows 11'S Retained 7 Classic Characteristics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-strategies-enhancing-productivity-using-wsl-2/"><u>Top Strategies: Enhancing Productivity Using WSL 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-to-emulate-macos-the-top-5-approaches/"><u>Transforming Windows to Emulate macOS: The Top 5 Approaches</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-xiaomi-redmi-note-12-pro-4g-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Xiaomi Redmi Note 12 Pro 4G Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/untangling-the-mystery-guide-to-accessing-and-moving-hidden-window-panes/"><u>Untangling the Mystery: Guide to Accessing and Moving Hidden Window Panes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-modern-standby-a-critical-analysis/"><u>Unveiling Modern Standby: A Critical Analysis</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-top-picks-for-4k-proxy-video-editing-8-essential-apps/"><u>Updated Top Picks for 4K Proxy Video Editing 8 Essential Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgraded-performance-ahead-steps-to-amplify-virtual-memory-in-windows-11/"><u>Upgraded Performance Ahead: Steps to Amplify Virtual Memory in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-should-i-do-if-i-cant-upgrade-my-pc-to-windows-11/"><u>What Should I Do If I Can't Upgrade My PC to Windows 11?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-to-do-if-windows-wont-show-notification-badges-on-taskbar-icons/"><u>What to Do if Windows Won’t Show Notification Badges on Taskbar Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-warning-signs-is-a-restart-needed/"><u>Windows Warning Signs: Is a Restart Needed?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-live-streaming-intel-graphics-recording-tips/"><u>Winning at Live Streaming: Intel Graphics Recording Tips</u></a></li>
</ul></div>
