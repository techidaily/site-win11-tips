---
title: Fix Window Updates Blocked by Error 2E
date: 2024-07-12T16:40:35.853Z
updated: 2024-07-13T16:40:35.853Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fix Window Updates Blocked by Error 2E
excerpt: This Article Describes Fix Window Updates Blocked by Error 2E
keywords: Fix Windows Update Error,Unblock Windows Update,Stop Update Error 2E,Resolve Windows Update Issue,Clear Update Block Error,Disable Updater Restriction,Remove Update Failure 2E
thumbnail: https://thmb.techidaily.com/89da125ea493abc275649c1f57ef017273ab0d0d83c11a51da5e1af69c65adca.png
---

## Fix Window Updates Blocked by Error 2E

 Windows Update is generally reliable, but it can sometimes surprise you with the error 0x8024002e. This unfortunate glitch could leave your device's operating system open to potential security threats and stop it from downloading further updates.

 Fortunately, we've identified the steps needed to quickly resolve this issue - so be sure to take action now for smooth sailing with Windows Updates in the future.

## What Causes Windows Update Error 0x8024002e?

 If you're dealing with Windows Update error 0x8024002e, there are a variety of potential causes, ranging from corrupted files and incompatible hardware settings to incorrect network configurations. Other possible culprits include outdated drivers and limited storage space.

 It usually includes an error message that states, "There were some problems installing updates, but we'll try again later. If you keep seeing this and want to search the web or contact support for information, this may help: (0x8024002e)."

Let's now see how to fix this error code on Windows:

## 1\. Restart Your Computer

 Restarting your computer is an easy way to resolve many Windows Update errors. By restarting, you're resetting the memory of your device and clearing out any pesky bugs that may be causing trouble with error 0x8024002e. Give it a try - after rebooting, check if the issue has been resolved.

## 2\. Restart the Windows Update Services

 If you're still facing Windows Update errors such as error 0x8024002e, then it may be a result of one or more defective services or processes. You can try restarting the Windows Update service to ensure that all your essential services are operating properly and without issue.

To restart the Windows Update service, follow these steps:

1. Press**Win + R** on your keyboard to open the Run dialog.
2. Type**services.msc** into the text box and click**OK** .
3. Next, scroll down to**Windows Update** and double-click on it.
4. In the Properties window, set the Startup type to**Automatic** .
5. Then go to Service status and click**Start** .  
![Restart Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restart-windows-update-service.jpg)
6. Now click**Apply > OK** to save the changes.

 After you have started the Windows Update service, repeat this same process with several other services provided below:

* Background Intelligent Transfer Service.
* Cryptographic Service.
* Windows Update Medic Service.
* DCOM Server Process Launcher
* Windows Installer.

 Once you've completed the process, check Windows Update again to see if the error is still occurring.

## 3\. Tweak the Registry Editor

 This solution might work if you're dealing with a corrupt or missing Windows Update setting in your registry. Be very cautious when accessing and modifying your registry, as you could be exposed to a range of unwanted issues if done incorrectly.

 Always [back up the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes, just in case something goes wrong so that it can easily and quickly be restored.

 To adjust the Windows Update setting in your registry, follow these steps:

1. [Open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the Open field and click**OK** .
3. If UAC prompts appear on the screen, click**Yes** .
4. Once you're in the Registry Editor window, navigate to the following location:  
HKEY_LOCAL_MACHINE\Software\Policies\Microsoft\Windows\WindowsUpdate
5. Double-click**DisableWindowsUpdateAccess** in the right pane.
6. If the Value data in the popup window is**1** , change it to**0** .
7. Click**Apply > OK** to save the changes.  
![Adjust the Windows Update setting in the registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/adjust-the-windows-update-setting-in-the-registry-editor.jpg)
8. Now close the Registry Editor window and restart your computer.

 After you follow these steps, you should check to see if the 0x8024002e error has been resolved.

## 4\. Reset All Relevant Windows Update Components

 Sometimes, the components responsible for Windows Update may get corrupted. If this occurs, you can try resetting the components to resolve the issue.

Follow these steps to reset your Windows Update Components:

1. First, open Notepad on your Windows computer. In case you need help, see our guide on [how to open Notepad on Windows](https://www.makeuseof.com/windows-11-open-notepad/) .
2. Copy and paste the following commands into the Notepad window:  
`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir%  
system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
3. Now click**File** and select**Save as** from the option list.
4. In the**Save as type** field, choose**All Files** .  
![Reset Windows Update Components](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reset-windows-update-components.jpg)
5. Name the file**ResetWindowsUpdate.bat** and save it to your desktop.
6. Now right-click on the batch file and select**Run as administrator** from the context menu.
7. If UAC window pops up on the screen, click**Yes** to continue.

 Wait for the process to complete and then restart your computer. After you follow these steps, check to see if the 0x8024002e error is resolved.

## 5\. Apply Generic Windows Update Fixes

 If all else fails, it's time to try some more general fixes. These have had good track records for fixing Windows Update errors, regardless of the error code it gives you.

 Check out [the ways to fix Windows Update errors on Windows 11](https://www.makeuseof.com/windows-11-update-error-fixes/) for more. Most of them should also work on Windows 10 machines.

## Resolving Windows Update Error 0x8024002e

 It's easy to solve Windows Update error 0x8024002e with the fixes mentioned above. Most of the time, this issue is related to corrupted or missing system files in your Windows Update service. In case you still experience problems afterward, then a system restore should do the trick.


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
<li><a href="https://fox-helps.techidaily.com/new-full-analysis-and-how-to-the-ultimate-picsart-experience/"><u>[New] Full Analysis and How-To  The Ultimate PicsArt Experience</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-in-2024-5-tips-about-youtube-shorts-to-grow-your-business/"><u>Updated In 2024, 5 Tips About YouTube Shorts to Grow Your Business</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-permanent-file-disposal-via-custom-trash-bin-setup/"><u>Windows 10/11: Permanent File Disposal via Custom Trash Bin Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-installation-issues-with-windows-11-troubleshooter/"><u>Solving Installation Issues with Windows 11 Troubleshooter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-enhancing-performance-in-your-new-windows-11-setup/"><u>A Quick Guide to Enhancing Performance in Your New Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correct-invalid-profiles-in-windows-operating-systems/"><u>Steps to Correct Invalid Profiles in Windows Operating Systems</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-windows-10-webcam-recording-the-top-10-software-options/"><u>New 2024 Approved Windows 10 Webcam Recording The Top 10 Software Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/verifying-microphone-function-on-windows/"><u>Verifying Microphone Function on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-eradicate-0x800713f-error-on-windows-11/"><u>Strategies to Eradicate 0X800713F Error on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disentangling-stacked-icons-on-operating-system-ui/"><u>Disentangling Stacked Icons on Operating System UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-print-bridge-trouble-shooting-guide/"><u>Windows Print Bridge: Trouble Shooting Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-component-services-interface-quickly/"><u>Accessing Windows' Component Services Interface Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-server-disruptions-and-ms-store-issues-on-windows-11-and-11/"><u>Remedy for Server Disruptions and MS Store Issues on Windows 11 & 11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-about-vivo-y78-5g-frp-bypass-by-drfone-android/"><u>In 2024, About Vivo Y78 5G FRP Bypass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-tips-for-playing-old-championship-manager-on-pc/"><u>Top Tips for Playing Old Championship Manager on PC</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlock-apple-iphone-13-pro-max-without-passcode-easily-drfone-by-drfone-ios/"><u>Unlock Apple iPhone 13 Pro Max Without Passcode Easily | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-for-operational-windows-desktop-context-menus/"><u>Tactics for Operational Windows Desktop Context Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winfixing-comprehensive-steps-for-repairing-windows-filesystem-issues/"><u>Winfixing: Comprehensive Steps for Repairing Windows Filesystem Issues</u></a></li>
<li><a href="https://change-location.techidaily.com/latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-vivo-v29e-drfone-by-drfone-virtual-android/"><u>Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Vivo V29e | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pushing-the-limits-of-solid-state-drives-on-windows-with-ssdfresh/"><u>Pushing the Limits of Solid State Drives on Windows with SSDFresh</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719380879608-speedy-outlook-on-windows-heres-how/"><u>Speedy Outlook on Windows? Here's How!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-the-most-effective-win-video-codecs/"><u>Demystifying the Most Effective Win Video Codecs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-frozen-wastebin-symbol-on-win11/"><u>Reactivating Frozen Wastebin Symbol on Win11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/youtubes-rules-the-creators-perspective/"><u>YouTube’s Rules  The Creator's Perspective</u></a></li>
<li><a href="https://win11-tips.techidaily.com/teams-upgrade-fast-memory-conscious-solution/"><u>Teams Upgrade: Fast, Memory-Conscious Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-items-to-windows-11-desktop-menu-hierarchy/"><u>Adding Items to Windows 11 Desktop Menu Hierarchy</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-top-11-budget-friendly-audio-enhancement-software-options-for-your-pc-and-mac/"><u>Updated In 2024, Top 11 Budget-Friendly Audio Enhancement Software Options for Your PC and Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-onedrive-errors-an-easy-guide/"><u>Overcoming Windows OneDrive Errors: An Easy Guide</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-free-game-video-editing-software-the-ultimate-guide-for-2024/"><u>Updated Free Game Video Editing Software The Ultimate Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steering-clear-of-low-performance-pitfalls-intel-gpu-resolution/"><u>Steering Clear of Low-Performance Pitfalls: Intel GPU Resolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tap-out-of-high-contrast-in-windows-environment/"><u>Tap Out of High Contrast in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breakthrough-programs-facilitating-switch-from-mac-to-windows/"><u>Breakthrough Programs Facilitating Switch From MAC to WINDOWS</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-ever-heard-of-text-to-speech-how-about-speech-to-text-learn-more-about-it-in-this-article/"><u>Updated Ever Heard of Text-to-Speech? How About Speech-to-Text? Learn More About It in This Article</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strengthening-game-accessibility-winning-over-ea-errors/"><u>Strengthening Game Accessibility: Winning Over EA Errors</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-breathing-life-into-bios-a-zodiac-perspective/"><u>2024 Approved  Breathing Life Into Bios  A Zodiac Perspective</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silence-missed-specification-alert-on-windows-11/"><u>Silence Missed Specification Alert on Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/smooth-shifts-audio-transition-wisdom-from-sonar-by-platinum/"><u>Smooth Shifts  Audio Transition Wisdom From Sonar by Platinum</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-hacks-for-instantaneous-iis-server-management-entry/"><u>8 Hacks for Instantaneous IIS Server Management Entry</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/clear-voice-clarity-conquering-hard-lexical-barriers/"><u>Clear Voice Clarity: Conquering Hard Lexical Barriers</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-simple-strategies-to-craft-amazing-instagram-collages/"><u>2024 Approved  Simple Strategies to Craft Amazing Instagram Collages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-discord-install-failure/"><u>Overcoming Windows 11 Discord Install Failure</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-enhance-your-profile-with-free-imagery/"><u>[Updated] Enhance Your Profile with Free Imagery</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-filmmaking-made-simple-crafting-an-impactful-youtube-subscribe-button/"><u>[Updated] 2024 Approved  Filmmaking Made Simple  Crafting an Impactful YouTube Subscribe Button</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-supernatural-video-slowdown-handbook/"><u>2024 Approved  Supernatural Video Slowdown Handbook</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-choosing-the-right-tool-for-your-youtube-to-avi-desire/"><u>[New] 2024 Approved  Choosing the Right Tool for Your YouTube-to-AVI Desire</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-re-listing-bluetooth-on-windows-pc/"><u>Strategies for Re-Listing Bluetooth on Windows PC</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-ultimate-guide-the-leading-7-nft-conversion-services/"><u>[New] Ultimate Guide  The Leading 7 NFT Conversion Services</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-a-vivo-t2x-5g-phone-that-is-locked-by-drfone-android/"><u>In 2024, How to Reset a Vivo T2x 5G Phone that is Locked?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-function-keys-actions-on-windows-1011/"><u>Adjusting Function Keys' Actions on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-customize-windows-11s-search-via-settings/"><u>5 Ways to Customize Windows 11'S Search via Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unresponsive-windows-outlook-conditional-rules/"><u>Overcoming Unresponsive Windows Outlook Conditional Rules</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-olympic-sprint-spotlight-year-2022/"><u>2024 Approved  Olympic Sprint Spotlight  Year 2022</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-pioneering-visual-storytelling-uploading-to-youtube/"><u>[Updated] Pioneering Visual Storytelling  Uploading to YouTube</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-honor-100-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Honor 100 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-and-resolving-issues-with-registry-editor-missing/"><u>Uncovering and Resolving Issues with 'Registry Editor' Missing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-update-failures-strategies-for-error-0x30017/"><u>Overcoming Windows Update Failures: Strategies for Error 0X30017</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-aesthetic-annotations-on-photos-the-top-20-snap-filters-selection/"><u>[New] In 2024, Aesthetic Annotations on Photos  The Top 20 Snap Filters Selection</u></a></li>
</ul></div>
