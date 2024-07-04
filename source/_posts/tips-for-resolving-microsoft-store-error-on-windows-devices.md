---
title: Tips for Resolving Microsoft Store Error on Windows Devices
date: 2024-06-25T16:19:56.942Z
updated: 2024-06-26T16:19:56.942Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips for Resolving Microsoft Store Error on Windows Devices
excerpt: This Article Describes Tips for Resolving Microsoft Store Error on Windows Devices
keywords: Fixing MSStore Errors,Resolve MSStore Crashes,Troubleshoot MSStore Issues,MSStore Error Remedies,Stop MSStore Failures,Windows Store Fault Fix,Overcome MSDWindows Error
thumbnail: https://thmb.techidaily.com/6ba823e70571284a0c45a2acec26bb9d28a4fab8bdde6a1d84cbac37f185e31d.jpg
---

## Tips for Resolving Microsoft Store Error on Windows Devices

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

### Repair System Files ![The Reset button for Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button-1.jpg)

 To begin with, try repairing system files to see if there are any issues. You can do that by executing a System File Checker scan within the Command Prompt. That tool will check for and repair corrupted system files detected when you run its command. To apply this potential fix, follow the instructions in our [how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide.

### Set Windows to Clean Boot ![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-services-tab.jpg)

 Another possibility is that a software conflict might be causing error 0x80073D26 to occur on your PC. Setting Windows to clean boot by disabling third-party startup items will likely eliminate such a potential cause. That will stop third-party apps and services that could be conflicting with the Microsoft Store from automatically starting.

 To apply this fix, check out this guide about [clean-booting Windows 10 or 11](https://www.makeuseof.com/clean-boot-windows-11/). Disable startup programs in Task Manager and services in MS Config as covered within that guide; then restart your PC and try installing Microsoft Store games again to see if the issue persists.

### Reinstall the Microsoft Store ![The remove Microsoft Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-microsoft-store-command.jpg)

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-reactivating-windows-11s-diagnostic-features/"><u>Quick Fixes: Reactivating Windows 11'S Diagnostic Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-turn-off-the-mobile-interface-win-11/"><u>Quick Fix: Turn Off the Mobile Interface (Win 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-restoring-icon-order-in-windows/"><u>Tips for Restoring Icon Order in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaiming-missing-power-configurations-in-win-11-os/"><u>Reclaiming Missing Power Configurations in Win 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-speech-output-in-windows-environment/"><u>Mastering Speech Output in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-your-pc-top-5-windows-speed-solutions/"><u>Supercharge Your PC: Top 5 Windows Speed Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-tricks-for-resolving-active-directory-printer-issues-on-win11/"><u>Tips & Tricks for Resolving Active Directory Printer Issues on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-guide-to-overcoming-steam-auth-problems-with-rust-on-windows/"><u>Detailed Guide to Overcoming Steam Auth Problems with Rust on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-advantages-of-using-dxvk-on-your-windows-system/"><u>The Advantages of Using DXVK on Your Windows System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/can-pressing-prtscn-launch-snipping-tool-steps-to-halt/"><u>Can Pressing PrtScn Launch Snipping Tool? Steps to Halt</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-stock-strategy-streams-the-most-valuable-online-sources/"><u>2024 Approved  Stock Strategy Streams  The Most Valuable Online Sources</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-is-a-sim-network-unlock-pin-get-your-oppo-find-x6-phone-network-ready-by-drfone-android/"><u>In 2024, What Is a SIM Network Unlock PIN? Get Your Oppo Find X6 Phone Network-Ready</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-mastering-music-creation-at-home-ranking-the-top-10-digital-audio-environments-for-2024/"><u>New Mastering Music Creation at Home Ranking the Top 10 Digital Audio Environments for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-content-distribution-showdown-vimeo-vs-youtubes-and-dailymotions/"><u>In 2024, Content Distribution Showdown  Vimeo vs YouTubes and DailyMotions</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-hacks-to-do-pokemon-go-trainer-battles-for-samsung-galaxy-s23-drfone-by-drfone-virtual-android/"><u>In 2024, Hacks to do pokemon go trainer battles For Samsung Galaxy S23 | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-vivo-s18-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Additional Tips About Sinnoh Stone For Vivo S18 Pro | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-ultimate-guide-to-free-youtube-intros-and-templates/"><u>[New] The Ultimate Guide to Free YouTube Intros & Templates</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-facts-you-need-to-know-about-screen-mirroring-motorola-moto-g23-drfone-by-drfone-android/"><u>In 2024, 3 Facts You Need to Know about Screen Mirroring Motorola Moto G23 | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-the-art-of-changing-your-voice-a-guide-to-vocal-adaptability/"><u>Updated 2024 Approved The Art of Changing Your Voice A Guide to Vocal Adaptability</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-how-to-effortlessly-download-and-setup-movie-maker-6/"><u>2024 Approved  How to Effortlessly Download and Setup Movie Maker 6</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>