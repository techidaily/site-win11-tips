---
title: "Restoring Roots: User Permissions Back to Basics in Win11"
date: 2024-07-12T16:36:49.817Z
updated: 2024-07-13T16:36:49.817Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Restoring Roots: User Permissions Back to Basics in Win11"
excerpt: "This Article Describes Restoring Roots: User Permissions Back to Basics in Win11"
keywords: Win11 User Roles,Basic Permissions Win11,Windows Permissions Guide,Win11 Access Control,Rooting Users Win11,Basics of Win11 Security,Root Management in Win11
thumbnail: https://thmb.techidaily.com/58d6990fb1aba3befeda20029d053fd2dc8e67729321f3227eadd737a516d064.jpg
---

## Restoring Roots: User Permissions Back to Basics in Win11

 Having issues with apps or programs not running properly on your Windows computer? Resetting Windows Update permissions could be the solution you need. Similarly, if you're troubleshooting user profile problems, you can restore user permissions.

 This article covers three different methods to reset all user permissions – using the Icacls command, the Secedit command, and the Subinacl tool.

Let's now explore them in detail.

## 1\. Run the Icacls Command

 The Icacls command allows you to view, modify, and reset file system permissions on files and folders. To reset Windows Update permissions using this command, you will first have to [take ownership of the folders on Windows](https://www.makeuseof.com/windows-10-11-own-folder/) . Then [open an elevated Command Prompt on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) and type in the following command:

`icacls * /t /q /c /reset`

 Now press Enter on your keyboard to execute the command. This will reset all user permissions to default for every folder, subfolder, and file within the current working directory.

In the above command, here are the parameters explained:

* \* – This is a wildcard character that includes all folders within the current directory.
* /t – It targets all the subfolders and files within the current folder.
* /q – Run command without displaying success messages.
* /c – Continues the operation even if errors occur.
* /reset – This parameter resets the permission options to their default values.

## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
3. Click on**Next** and then accept the license agreement terms.  
![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
4. Next, copy and paste the following path into the Destination folder:  
`C:\Windows\System32`  
 Note: If you have installed Windows on a different drive, use that path instead.
5. Now click on**Install now** and wait for the Subinacl tool to be installed. This may take several minutes, so be patient.

1. When the installation is complete,[open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and type in the following commands:  
`subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=administrators=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=administrators=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=administrators=f  
subinacl /subdirectories %SystemDrive% /grant=administrators=f  
subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=system=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=system=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=system=f  
subinacl /subdirectories %SystemDrive% /grant=system=f`
2. On the Save As window, set the File name to**Reset.cmd** and then select**All Files** from the drop-down menu next to it.  
![Reset Windows Update permissions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-update-permissions.jpg)
3. Next, select**Desktop** from the left pane and click on**Save** .
4. Now double-click on it to reset the user permissions to default.
5. This may take a while to complete the procedure, so wait for it to finish.

 Once done, close any running program, and then restart your computer. Your Windows Update permissions will be reset to their default settings. These are three different methods you can use to reset the user permission settings on Windows.

## Restore User Permissions to Default on Windows

 User permissions play a crucial role in computer security. If you're experiencing user permission issues, you must reset them to their default settings. This guide helps you reset all user permissions on Windows using three different methods. You can use the ICACLS command, Secedit command, or Subinacl tool, depending on your preference.


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
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-sonicsilence-eliminator-achieve-pristine-sound-quality/"><u>New 2024 Approved SonicSilence Eliminator Achieve Pristine Sound Quality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correct-primes-textual-missteps-on-windows-11-desktops/"><u>Correct Prime's Textual Missteps on Windows 11 Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-productivity-integrating-flow-launcher-into-daily-routine/"><u>Amplify Productivity: Integrating Flow Launcher Into Daily Routine</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-flashstoppage-instant-video-quit-guide/"><u>[Updated] FlashStoppage  Instant Video Quit Guide</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-on-xiaomi-redmi-12-5g-frp-bypass-by-drfone-android/"><u>Ultimate Guide on Xiaomi Redmi 12 5G FRP Bypass</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/in-2024-tiktok-and-twittersphere-crossover-the-viral-vids/"><u>In 2024, TikTok and Twittersphere Crossover  The Viral Vids</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-5-affordable-pinterest-video-downloaders-unveiled/"><u>[New] Top 5 Affordable, Pinterest Video Downloaders Unveiled</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-accidental-tiktok-reset-how-to-restore-content/"><u>[Updated] 2024 Approved  Accidental TikTok Reset  How to Restore Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719268439990-chrome-freeze-no-more-top-solutions-for-windows-11-users/"><u>Chrome Freeze No More: Top Solutions for Windows 11 Users!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/take-full-advantage-of-windows-11-features/"><u>Take Full Advantage of Windows 11 Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamlessly-switching-on-updated-widget-selection-interface-in-windows-11/"><u>Seamlessly Switching on Updated Widget Selection Interface in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-stuck-battlenet-login-screen/"><u>Solutions for Stuck Battle.net Login Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-operations-7-easy-tips-for-advanced-windows-11-users/"><u>Streamline Operations: 7 Easy Tips for Advanced Windows 11 Users</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-cutting-edge-webcam-editing-emphasize-focus-not-the-fence/"><u>[Updated] 2024 Approved  Cutting Edge Webcam Editing – Emphasize Focus, Not the Fence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-common-captioning-hurdles-on-windows-10-devices/"><u>Solving Common Captioning Hurdles on Windows 10 Devices</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/how-to-live-stream-360-videos-on-facebook-for-2024/"><u>How to Live Stream 360 Videos on Facebook for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-myvidhub-testing-a-quest-for-more-features-in-2024/"><u>[New] MyVidHub Testing  A Quest for More Features, In 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-a-network-locked-samsung-galaxy-s23plus-phone-by-drfone-android/"><u>In 2024, How to Unlock a Network Locked Samsung Galaxy S23+ Phone?</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-how-to-blur-background-of-your-youtube-video/"><u>[New] 2024 Approved  How to Blur Background of Your YouTube Video</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-unlocking-hidden-potential-how-to-use-video-filters-on-zoom/"><u>[Updated] 2024 Approved  Unlocking Hidden Potential  How To Use Video Filters on Zoom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-system-editor-access-control-on-windows-11/"><u>Techniques for System Editor Access Control on Windows 11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-social-sharing-simplified-uploading-immersive-mobile-photography/"><u>In 2024, Social Sharing Simplified  Uploading Immersive Mobile Photography</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-restore-colorful-screen-on-windows-pc-via-remote-access/"><u>Steps to Restore Colorful Screen on Window's PC via Remote Access</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-top-mobile-experiences-ios-and-androids-vr-hits/"><u>[Updated] Top Mobile Experiences  IOS & Android's VR Hits</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-turn-daily-life-into-a-comedy-meme/"><u>In 2024, Turn Daily Life Into a Comedy Meme</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-honor-magic-6-lite-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Honor Magic 6 Lite? | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-fast-track-to-short-video-treasure-troves-free-access/"><u>[Updated] Fast Track to Short Video Treasure Troves (Free Access)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-fixes-for-cant-access-mail-alert-on-windows-11s-mail-app/"><u>Unveiling Fixes for Can't Access Mail Alert on Windows 11'S Mail App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-recording-basics-for-newcomers-on-win-11/"><u>Audio Recording Basics for Newcomers on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-your-onedrive-to-a-desired-spot-on-win10/"><u>Transitioning Your OneDrive to a Desired Spot on Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-fix-the-hypervisorerror-blue-screen-on-windows-10-and-11/"><u>5 Ways to Fix the HYPERVISOR_ERROR Blue Screen on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-data-flow-from-non-responsive-usb-devices-win-os/"><u>Restoring Data Flow From Non-Responsive USB Devices (Win OS)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-manual-timezone-setting-in-microsoft-os/"><u>Troubleshoot Manual Timezone Setting in Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-11s-fatal-0xf0831-bug/"><u>Resolving Windows 11'S Fatal 0xF0831 Bug</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-system-image-creation-on-windows/"><u>Simplified System Image Creation on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/window-management-adding-this-pc-to-windows-desktop/"><u>Window Management: Adding 'This PC' To Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-11s-0x800f0922-error-quick-fixed-guide/"><u>Solving Windows 11'S 0X800F0922 Error - Quick Fixed Guide</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/must-have-3d-model-systems-in-animation-for-2024/"><u>Must-Have 3D Model Systems in Animation for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-tips-for-effective-game-playback-on-microsoft-os/"><u>[New] In 2024, Tips for Effective Game Playback on Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-setup-guide-for-steam-deck-owners/"><u>Windows Setup Guide for Steam Deck Owners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-windows-users-should-anticipate-sudo/"><u>Why Windows Users Should Anticipate Sudo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-high-dpi-displays-a-windows-guide/"><u>Dealing with High DPI Displays: A Windows Guide</u></a></li>
<li><a href="https://extra-tips.techidaily.com/laugh-ledger-a-treasure-trove-of-free-meme-creations/"><u>Laugh Ledger  A Treasure Trove of FREE Meme Creations</u></a></li>
<li><a href="https://win11.techidaily.com/cure-for-mcuicntexe-entry-point-loss-in-windows-systems/"><u>Cure for McUICnt.exe Entry Point Loss in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/say-no-to-incompatibility-quick-solutions-for-vistawindows-7-users/"><u>Say No to Incompatibility: Quick Solutions for Vista/Windows 7 Users</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-a-guide-to-establishing-a-vlog-centered-on-merchandise-assessments-for-2024/"><u>[New] A Guide to Establishing a Vlog Centered on Merchandise Assessments for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-warriors-epic-valhallas-endgame/"><u>2024 Approved  Warriors' Epic  Valhalla's Endgame</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-missing-d3dx939-dll-in-win11/"><u>Addressing Missing D3DX9_39 DLL in Win11</u></a></li>
</ul></div>
