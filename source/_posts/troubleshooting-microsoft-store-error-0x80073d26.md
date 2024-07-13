---
title: Troubleshooting Microsoft Store Error 0X80073D26
date: 2024-07-12T17:33:23.424Z
updated: 2024-07-13T17:33:23.424Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Microsoft Store Error 0X80073D26
excerpt: This Article Describes Troubleshooting Microsoft Store Error 0X80073D26
keywords: Store Error X80073D26 Fix,Microsoft Store Crash Code 0X80073D26,Resolve Microsoft Store Error 0X80073D26,0X80073D26 MS Error Troubleshooting,Microsoft Store Update Failure 0X80073D26,Fixing Microsoft Store 0X80073D26,Overcome X80073D26 Microsoft Error
thumbnail: https://thmb.techidaily.com/8c5008233da724661a30d3225b0be351e1d277e0e18468f4536db088e3157824.jpg
---

## Troubleshooting Microsoft Store Error 0X80073D26

 Error 0x80073D26 is an issue that users have widely reported occurring when trying to install or play Xbox Game Pass titles via Microsoft Store. When this issue arises, users get redirected to install the Gaming Services app in the Microsoft Store. Users then see the “Something unexpected happened” error 0x80073D26 message when they try to install (or update) Gaming Services.

 Players can’t enjoy their Xbox Game Pass titles because of error 0x80073D26, which makes this an annoying issue for Xbox Game Pass users. This is how you can fix the Microsoft Store error 0x80073D26 in Windows

## 1\. Run the Windows Store App Troubleshooting Tool

 This isn’t the most likely solution for error 0x80073D26, but it’s worth trying since Microsoft Store is a UWP app. Running the Windows Store App troubleshooter might detect a Microsoft Store issue and provide a fix. These are the steps for running the Windows Store App troubleshooting utility:

1. Open Settings and click **System** to view that tab.
2. Next, select **Troubleshoot** to reach three troubleshooting navigation options.
3. Bring up the list of troubleshooting tools by clicking **Other trouble-shooters**.
4. Then click **Run** to launch the Windows Store Apps troubleshooting tool.  
![The Run button for the Windows App Store troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-app-store-troubleshooter.jpg)
5. Apply all troubleshooting suggestions provided within Windows Store Apps window.  
![The Windows Store Apps window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-store-app-troubleshooter.jpg)

 You can run the same troubleshooter tool in Windows 10, but the steps for accessing it are a bit different. Click **Update & Security** \> **Troubleshoot** \> **Additional troubleshooters** in Windows 10’s Settings app. Then select **Windows Store Apps** \> **Run the troubleshooter** to get troubleshooting.

## 2\. Repair and Reset the Microsoft Store App

 Accumulated and corrupted Microsoft Store cache data is a potential cause for error 0x80073D26\. Resetting the Microsoft Store app via Settings or the Command Prompt will clear the app’s data. Try applying both methods in this guide to resetting Microsoft Store. Also, select the **Repair** option for the Microsoft Store just above its **Reset** button in Settings to see if that resolves the issue.

![The Reset button for Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button-1.jpg)

## 3\. Edit the Registry

 One of the most widely confirmed fixes for error 0x80073D26 is to enter the Registry and delete the GamingServices and GamingServicesNet Registry keys. Although confirmed to work, we still recommend users [back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before deleting keys. Then follow these steps for editing the registry:

1. Open the Windows Run accessory by right-clicking **Start** on your taskbar and selecting the **Run** option.
2. Input the **regedit** Run command and click **OK** to [launch the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Copy and paste this key location in the registry address bar:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services`
4. Right-click the **GamingServices** subkey within the Services key to select **Delete** \> **Yes**.  
![The Delete registry key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/delete-option-1.jpg)
5. Click the **GamingServicesNet** key with the mouse’s right button and select the **Delete** \> **Yes** options.
6. Exit Registry Editor and restart your PC.

## 5\. Reinstall the Microsoft Gaming Service

 One of Microsoft’s official resolutions for error 0x80073D26 is to reinstall Gaming Service. This potential solution involves entering three PowerShell commands that will remove the Gaming Service app along with associated registry entries. These are the steps for applying this potential fix:

1. Activate Windows Search by pressing **Win + S**.
2. Enter **PowerShell** inside the file search tool.
3. Open PowerShell with admin rights by right-clicking that app in the search results and selecting **Run as Administrator**.
4. Next, remove the Gaming Service app by entering this command and hitting **Enter**:  
`Get-AppxPackage *gaming services* -allusers | remove-appxpackage -allusers`  
![The remove-app package command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-app-package-command.jpg)
5. Then input these separate commands, pressing **Return** after each:  
`Remove-Item -Path "HKLM:\System\CurrentControlSet\Services\GamingServices" -recurse  

Remove-Item -Path "HKLM:\System\CurrentControlSet\Services\GamingServicesNet" -recurse` 
![The remove-app package command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-app-package-command.jpg)
6. Close out of PowerShell to restart Windows.
7. Reopen Powershell and execute the following command:  
`start ms-windows-store://pdp/?productid=9MWPM2CQNLHN`
8. Then click the **Get** button for installing Gaming Service.

## 5\. Perform Some Generic Windows Fixes for Errors

 Windows is by no means impervious to errors. Fortunately, there are some tricks you can apply to almost every error, including this one.

### Repair System Files
![The Reset button for Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button-1.jpg)

 To begin with, try repairing system files to see if there are any issues. You can do that by executing a System File Checker scan within the Command Prompt. That tool will check for and repair corrupted system files detected when you run its command. To apply this potential fix, follow the instructions in our [how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide.

### Set Windows to Clean Boot
![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-services-tab.jpg)

 Another possibility is that a software conflict might be causing error 0x80073D26 to occur on your PC. Setting Windows to clean boot by disabling third-party startup items will likely eliminate such a potential cause. That will stop third-party apps and services that could be conflicting with the Microsoft Store from automatically starting.

 To apply this fix, check out this guide about [clean-booting Windows 10 or 11](https://www.makeuseof.com/clean-boot-windows-11/). Disable startup programs in Task Manager and services in MS Config as covered within that guide; then restart your PC and try installing Microsoft Store games again to see if the issue persists.

### Reinstall the Microsoft Store
![The remove Microsoft Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-microsoft-store-command.jpg)

 Some users might need to reinstall the Microsoft Store to fix error 0x80073D26\. Such a resolution might be necessary for fixing wider issues with the Microsoft Store app other potential solutions don’t address.

 There isn’t a standard uninstall option available for Microsoft Store. So, you’ll have to reinstall that app with two PowerShell commands. Our guide about [how to reinstall the Microsoft Store](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) tells you how to apply this potential fix.

### Perform an In-Place Windows Upgrade

 Some Microsoft Store users have also fixed error 0x80073D26 by performing an in-place Windows upgrade. An in-place upgrade is a method for installing the latest Windows 11/10 version without losing any installed software or user files.

 This will likely fix the 0x80073D26 error because it will refresh all of the system's registry entries, the system files, and also upgrade Windows to the latest version.

 Performing a Windows 11 in-place upgrade is relatively straightforward. All you need to do is download the latest Windows 11 ISO file, open it up, and launch the setup wizard from there. Our article about [performing an in-place upgrade of Windows 11](https://www.makeuseof.com/in-place-upgrade-windows-11/) includes full guidelines for how to do this.

![The Windows 11 Setup window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-11-setup-window2.jpg)

 You can also perform a Windows 10 in-place upgrade much the same. One difference is that you’ll need to download a Windows 10 Setup file by clicking **Download tool** on the [Microsoft Windows 10 download webpage](https://www.microsoft.com/en-gb/software-download/windows10). Then select **Upgrade this PC** now in the Windows 10 Setup wizard to install the latest version of the OS.

## Enjoy the Best Xbox Game Pass Games Available on the Microsoft Store

 It’s very likely the potential resolutions covered in this guide will fix error 0x80073D26, as some of them are widely confirmed to work. Hopefully, you can get this error fixed and get back into gaming.

 Players can’t enjoy their Xbox Game Pass titles because of error 0x80073D26, which makes this an annoying issue for Xbox Game Pass users. This is how you can fix the Microsoft Store error 0x80073D26 in Windows



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-music-files-from-oppo-reno-9a-by-fonelab-android-recover-music/"><u>How To  Restore Missing Music Files from Oppo Reno 9A</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-outlook-crashed-with-simple-solutions-windows-edition/"><u>Conquering Outlook Crashed with Simple Solutions, Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-back-your-game-fixing-lol-connection-failure/"><u>Bringing Back Your Game: Fixing LoL Connection Failure</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/2024-approved-a-comprehensive-list-of-the-top-spongebob-voice-generators/"><u>2024 Approved A Comprehensive List of The Top SpongeBob Voice Generators</u></a></li>
<li><a href="https://extra-resources.techidaily.com/enhance-images-androidandiphones-top-10-freeware-overlays/"><u>Enhance Images  Android&iPhone's Top 10 Freeware Overlays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-installation-failure-in-discord-for-win-1011/"><u>Troubleshooting Installation Failure in Discord for Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-text-hotkeys-setup-for-custom-snip-tapping-in-win11/"><u>Advanced Text Hotkeys Setup for Custom Snip Tapping in Win11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/audiophiles-guide-to-mac-voice-recorders-the-cream-of-the-crop/"><u>Audiophile's Guide to Mac Voice Recorders  The Cream of the Crop</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-streamline-your-video-collection-best-mp4-tag-editors-for-2024/"><u>New Streamline Your Video Collection Best MP4 Tag Editors for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathe-life-back-into-your-pcs-arrow-keys/"><u>Breathe Life Back Into Your PC's Arrow Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-finding-files-in-windows-11-with-the-search-bar/"><u>Accelerate Finding Files in Windows 11 with the Search Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-profits-via-windows-11-pro-key-offers/"><u>Elevate Profits via Windows 11 Pro Key Offers</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-amplify-your-voice-on-twitter-top-video-uploading-solutions/"><u>2024 Approved  Amplify Your Voice on Twitter  Top Video Uploading Solutions</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-boost-your-income-with-effective-vimeo-monetization-techniques/"><u>[Updated] In 2024, Boost Your Income with Effective Vimeo Monetization Techniques</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-pros-verdict-4-superior-fullscreen-capture-applications/"><u>[New] Pro's Verdict  4 Superior Fullscreen Capture Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-spooler-not-running-issue-in-microsoft-os/"><u>Correcting Spooler Not Running Issue in Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-common-nvidia-geforce-error-x0001-on-w10w11/"><u>Addressing Common Nvidia GeForce Error X0001 on W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-pc-data-collection-using-everywhereapp/"><u>Accelerated PC Data Collection Using EverywhereApp</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/unleash-the-power-of-pause-tips-for-instas-next-viral-slow-motion-reels/"><u>Unleash the Power of Pause  Tips for Insta's Next Viral Slow-Motion Reels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-and-fixing-closed-caption-failures-in-windows-11/"><u>Avoiding and Fixing Closed Caption Failures in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-endless-login-prompts-on-windows-os/"><u>Bypassing Endless Login Prompts on Windows OS</u></a></li>
<li><a href="https://animation-videos.techidaily.com/in-2024-5-different-animation-styles-a-simple-but-complete-guide/"><u>In 2024, 5 Different Animation Styles A Simple but Complete Guide</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-quick-clicks-big-grins-the-kinemaster-way/"><u>[New] In 2024, Quick Clicks, Big Grins  The KineMaster Way</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-hidden-recycling-bin-icon-on-windows-11/"><u>Activating Hidden Recycling Bin Icon on Windows 11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-elite-set-precision-tiktok-extractor-tools-watermark-free/"><u>In 2024, Elite Set  Precision TikTok Extractor Tools (Watermark-Free)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-real-time-response-on-windows-discord/"><u>Enhancing Real-Time Response on Windows Discord</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-xiaomi-redmi-note-12-pro-5g-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Xiaomi Redmi Note 12 Pro 5G Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/captivating-christmas-vistas-with-window-artistry/"><u>Captivating Christmas Vistas with Window Artistry</u></a></li>
<li><a href="https://facebook.techidaily.com/leveraging-alternative-text-to-enhance-your-fb-profile/"><u>Leveraging Alternative Text to Enhance Your Fb Profile</u></a></li>
<li><a href="https://extra-information.techidaily.com/altered-realities-image-warping-insights/"><u>Altered Realities  Image Warping Insights</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-speech-file-extract-and-critical-assessment/"><u>[New] 2024 Approved  Speech File Extract & Critical Assessment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-storage-disks-in-windows-os/"><u>Deciphering Storage Disks in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-system-integration-windows-plus-kali-linux-setup/"><u>Conquering System Integration: Windows + Kali Linux Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-desktop-arrangement-including-this-pc-icons/"><u>Efficient Desktop Arrangement: Including 'This PC' Icons</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-quick-start-to-smooth-volume-increase/"><u>In 2024, Quick Start to Smooth Volume Increase</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-the-basics-elite-apps-to-dethrone-windows-11/"><u>Beyond the Basics: Elite Apps to Dethrone Windows 11</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-top-notch-meme-editing-suite/"><u>[New] Top-Notch Meme Editing Suite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-and-remedying-0x80072af9-issues/"><u>Breaking Down and Remedying 0X80072AF9 Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beware-deception-secrets-to-identifying-genuine-windows-store-apps/"><u>Beware Deception: Secrets to Identifying Genuine Windows Store Apps</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-stand-out-on-discord-choosing-striking-banners-and-profile-graphics/"><u>[Updated] In 2024, Stand Out on Discord  Choosing Striking Banners & Profile Graphics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-workflow-essential-wsl-2-strategies-for-dev-enthusiasts/"><u>Boost Your Workflow: Essential WSL 2 Strategies for Dev Enthusiasts</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-craft-stellar-youtube-thumbnails-with-these-8-software-alternatives/"><u>[Updated] 2024 Approved  Craft Stellar YouTube Thumbnails with These 8 Software Alternatives</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024s-superior-camera-gear-roundup/"><u>2024'S Superior Camera Gear Roundup</u></a></li>
</ul></div>
