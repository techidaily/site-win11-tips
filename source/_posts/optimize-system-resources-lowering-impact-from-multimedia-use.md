---
title: "Optimize System Resources: Lowering Impact From Multimedia Use"
date: 2025-03-01T17:58:47.918Z
updated: 2025-03-04T19:35:28.268Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimize System Resources: Lowering Impact From Multimedia Use"
excerpt: "This Article Describes Optimize System Resources: Lowering Impact From Multimedia Use"
keywords: MultiMedia Optimization,Resource Efficiency,Reduce System Load,Media Streaming Saves,Enhance Performance,Minimize Multimedia Impact,Effective Resource Management
thumbnail: https://thmb.techidaily.com/3e9db891de75640d42280dabbfbbc511c64f55b10c2c6cccea4046ea3f8adbe3.jpg
---

## Optimize System Resources: Lowering Impact From Multimedia Use

 News and Interests is a Windows 11 and 10 widget on your taskbar to show weather, sports, and news events at a glance. While it seems like a harmlessly unwanted feature, it can sometimes cause high memory usage on your computer.

 This News and Interests issue occurs due to a potential memory leak and can make your computer run slow. So, if you want to make your computer run fast again, follow these steps to fix the News and Interests high memory usage problem.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Install Windows Update Hotfix

![windows 11 update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update.jpg)

 Reportedly, the problem occurs due to a Windows bug. To fix the problem, Microsoft released cumulative update KB5010415 for Windows 11 and 10\. So, check if you have any pending updates for your computer and install them to see if that helps resolve the error.

To install a Windows 11 update:

1. Press**Win + I** to open**Settings** .
2. Open the**Windows Update** tab in the left pane. Check if a new update is available. If not, click on**Check for updates** .
3. Windows will scan the Microsoft servers for newer updates. If available, click on**Download & install** . Once installed, restart your computer and check for any improvements.

 You can also learn how to[manage Windows 10 updates](https://www.makeuseof.com/tag/manage-windows-update-windows-10/) to ensure your computer is constantly updated. However, if you can find this specific update on your computer, go to[Microsoft Update Catalog](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and search for the update. If available, download the update and run the installer to install it manually.

## 2\. Turn Off News and Interests

 If you don't really use the News and Interests feature, you're better off turning it off. That way, you can save on hardware resources and help your computer run faster.

### Turn Off News and Interests on Windows 10

 If you don't use News and Interests, you can turn off the feature from the Taskbar on Windows 10\. To turn off News and Interests on Windows 10:

1. Right-click on the**Taskbar** to open the context menu.  
![turn off news and interests](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interestsjpg.jpg)
2. Next, go to**News and Interests** and select**Turn Off** .

 That's it. With the**News and Interests** feature disabled, your memory usage should return to its normal range.

### Disable News and Interests on Windows 11

![disable widgets Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/disable-widgets-windows-11.jpg)

 Unfortunately, News and Interests is a core feature of Windows 11 widgets. If the lack of Widgets isn't a concern, you can[disable the Windows 11 Widget app](https://www.makeuseof.com/windows-11-disable-widgets/) to get rid of the resource-hog news feed on your computer. However, if you find the widgets useful, you must endure the News and Interests feature.

 The easiest way to disable Widgets is from the Taskbar settings. If that does not work or if your Windows 11 isn't activated, you can use Registry Editor to disable the Widgets icon from the taskbar.

 If the issue persists even after disabling News and Interest, try to[perform a Windows 11 repair reinstall](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) . During a repair reinstall, Windows will reinstall the operating system without removing your personal files and apps.

## 3\. Disable News and Interests Using the Group Policy Editor

 On Windows 11, you can configure News and Interests on the taskbar policy to disable the feature and prevent high memory usage. Group Policy Editor (GPEdit) is a Windows component and is not only available on the OS's Pro, Enterprise, and Education editions.

 If you are on Windows 11 Home, follow these steps to[enable gpedit on Windows Home](https://www.catalog.update.microsoft.com/) and then proceed with the steps below:

1. Press**Win + R** to open**Run** .
2. Type**gpedit.msc** and click**OK** to open**Group Policy Editor** .
3. In Group Policy Editor, navigate to the following location:  
`Computer Configuration > Administrative Templates > Windows Components > News and Interests`
4. In the right pane, right-click on**Enable News and Interests** **on the taskbar** policy and select**Edit** .  
![turn off news and interest disabled 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interest-disabled-1.jpg)
5. Select**Disabled** and click**Apply** and**OK** to save the changes.  

![turn off news and interest disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interest-disabled.jpg)
6. Close Group Policy Editor and restart your computer.

 After restarting your computer, the News and Interests feature should no longer appear. Launch the task manager and check for improvements in your PC's CPU and memory usage.

## 4\. Disable News and Interests Using the Registry Editor on Windows 10

 You can disable the feed feature using the Windows Registry if you don't have Group Policy Editor. For this, you'll need to create an EnableFeeds value and set it to 0 to disable it.

 Incorrect modifications to the Windows Registry can cause your system to malfunction. We recommend[creating a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before making any changes to the registry entries.

To disable the news feed feature using Windows Registry:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open**Registry Editor** .  
![registry editor new key Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows.jpg)
3. In Registry Editor, navigate to the following location. You can copy and paste the registry path for quicker navigation:  

`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows`
4. Right-click on the**Windows** key in the left pane.
5. Select**New > Key** . Rename the key as**Windows Feeds** .  
![registry editor new key Windows new DWORd value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows-new-dword-value.jpg)

1. Next, right-click the**Windows Feeds** key and select**New > DWORD (32-bit) Value** .
2. Rename the new value as**EnableFeeds** .
3. Double-click on the**EnableFeeds** value to edit it.  
![registry editor new key Windows new DWORd value 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows-new-dword-value-0.jpg)
4. Type**0** in the**Value data** field and click**OK** to save the changes.

5. Close the Registry Editor and restart your computer to apply the changes.

## 5\. Add and Disable EnableFeeds Using PowerShell

![powershell add registry key value Windows feeds Enable feeds](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/powershell-add-registry-key-value-windows-feeds-enable-feeds.jpg)

 You can also add and modify the EnableFeeds value in the Windows Registry using PowerShell. To do this:

1. Press the**Win** key and type**powershell** .
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell terminal, copy and paste the following entry and press Enter:  
`REG ADD "HKLM\SOFTWARE\Policies\Microsoft\Windows\Windows Feeds" /v "EnableFeeds" /t REG_DWORD /d 0 /f`
4. The above command will create a new**Windows Feeds** subkey and contain the value**EnableFeeds** set to disabled.
5. If there are no errors, type**exit** and press**Enter** to close PowerShell. Restart your Computer and check for any improvements.

## Fix the News and Interests Feature's High Memory Usage on Windows

 Memory leakage is a common cause for the News and Interests high memory usage issue. While a hotfix is available, you'll need to disable the News and Interests widget item to resolve the problem if the issue persists.

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
<li><a href="https://screen-recording.techidaily.com/new-elite-list-of-mac-tech-for-live-recording/"><u>[New] Elite List of Mac Tech for Live Recording</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-unveiling-8-exceptional-mirrorless-cameras-for-vloggers/"><u>[New] In 2024, Unveiling 8 Exceptional Mirrorless Cameras for Vloggers</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-comprehensive-insights-into-polarr-photo-enhancer/"><u>[Updated] In 2024, Comprehensive Insights Into Polarr Photo Enhancer</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-quick-click-quest-the-art-of-facebook-id-reconnaissance/"><u>2024 Approved Quick Click Quest The Art of Facebook ID Reconnaissance</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-zte-blade-a73-5g-drfone-by-drfone-virtual-android/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On ZTE Blade A73 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-jotting-down-made-simple-in-win11/"><u>Effortless Jotting Down Made Simple in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-voice-activation-failures-in-the-latest-windows-os/"><u>Fixing Voice Activation Failures in the Latest Windows OS</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-overcome-cannot-log-onto-user-error-in-counter-strike-global-offensive/"><u>How to Overcome 'Cannot Log Onto User' Error in Counter-Strike Global Offensive</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-disabling-apple-iphone-se-2020-parental-restrictions-withwithout-password-by-drfone-ios/"><u>In 2024, Disabling Apple iPhone SE (2020) Parental Restrictions With/Without Password</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-transform-your-streaming-experience-with-these-9-filter-power-ups/"><u>In 2024, Transform Your Streaming Experience with These 9 Filter Power-Ups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-away-from-blocked-router-configuration/"><u>Navigating Away From Blocked Router Configuration</u></a></li>
<li><a href="https://techtrends.techidaily.com/navigating-your-options-crucial-questions-about-smartwatches-answered/"><u>Navigating Your Options: Crucial Questions About Smartwatches Answered</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-forgotten-windows-11-pin-post-corruption/"><u>Reinstating Forgotten Windows 11 PIN Post-Corruption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-systemsettingsexe-glitch-in-windows-11/"><u>Remedying SystemSettings.exe Glitch in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shifting-initial-home-page-away-from-settings-app/"><u>Shifting Initial Home Page Away From Settings App</u></a></li>
<li><a href="https://driver-error.techidaily.com/tackle-pci-controller-loss-on-win-1011/"><u>Tackle PCI Controller Loss on Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-realignment-of-window-widgets-separation-in-winos/"><u>Title: Realignment of Window Widgets' Separation in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unclickers-manual-for-win11-users-facing-issues/"><u>Unclicker's Manual for Win11 Users Facing Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wake-up-dormant-headsets-overcoming-no-sound-hurdles/"><u>Wake Up Dormant Headsets: Overcoming No Sound Hurdles</u></a></li>
</ul></div>

