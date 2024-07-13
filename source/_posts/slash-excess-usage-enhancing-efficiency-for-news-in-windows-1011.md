---
title: "Slash Excess Usage: Enhancing Efficiency for News in Windows 10/11"
date: 2024-07-12T17:20:45.702Z
updated: 2024-07-13T17:20:45.702Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Slash Excess Usage: Enhancing Efficiency for News in Windows 10/11"
excerpt: "This Article Describes Slash Excess Usage: Enhancing Efficiency for News in Windows 10/11"
keywords: WinNewsEfficiencyBoost,SlashExcessWindowsTech,EfficientWinNewsUpgrade,OptimizeWindowsNewsg,ReduceMediaUsageWin10,EnhanceWinNewsProductivity,StreamlineWindowsNewsUse
thumbnail: https://thmb.techidaily.com/94266fd2abffa49379e11298094d126f869b761cee72b14ccd455aec2a0df5c4.jpg
---

## Slash Excess Usage: Enhancing Efficiency for News in Windows 10/11

 News and Interests is a Windows 11 and 10 widget on your taskbar to show weather, sports, and news events at a glance. While it seems like a harmlessly unwanted feature, it can sometimes cause high memory usage on your computer.

 This News and Interests issue occurs due to a potential memory leak and can make your computer run slow. So, if you want to make your computer run fast again, follow these steps to fix the News and Interests high memory usage problem.

## 1\. Install Windows Update Hotfix
![windows 11 update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update.jpg)

 Reportedly, the problem occurs due to a Windows bug. To fix the problem, Microsoft released cumulative update KB5010415 for Windows 11 and 10\. So, check if you have any pending updates for your computer and install them to see if that helps resolve the error.

To install a Windows 11 update:

1. Press**Win + I** to open**Settings** .
2. Open the**Windows Update** tab in the left pane. Check if a new update is available. If not, click on**Check for updates** .
3. Windows will scan the Microsoft servers for newer updates. If available, click on**Download & install** . Once installed, restart your computer and check for any improvements.

 You can also learn how to [manage Windows 10 updates](https://www.makeuseof.com/tag/manage-windows-update-windows-10/) to ensure your computer is constantly updated. However, if you can find this specific update on your computer, go to [Microsoft Update Catalog](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and search for the update. If available, download the update and run the installer to install it manually.

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

 Unfortunately, News and Interests is a core feature of Windows 11 widgets. If the lack of Widgets isn't a concern, you can [disable the Windows 11 Widget app](https://www.makeuseof.com/windows-11-disable-widgets/) to get rid of the resource-hog news feed on your computer. However, if you find the widgets useful, you must endure the News and Interests feature.

 The easiest way to disable Widgets is from the Taskbar settings. If that does not work or if your Windows 11 isn't activated, you can use Registry Editor to disable the Widgets icon from the taskbar.

 If the issue persists even after disabling News and Interest, try to [perform a Windows 11 repair reinstall](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) . During a repair reinstall, Windows will reinstall the operating system without removing your personal files and apps.

## 3\. Disable News and Interests Using the Group Policy Editor

 On Windows 11, you can configure News and Interests on the taskbar policy to disable the feature and prevent high memory usage. Group Policy Editor (GPEdit) is a Windows component and is not only available on the OS's Pro, Enterprise, and Education editions.

 If you are on Windows 11 Home, follow these steps to [enable gpedit on Windows Home](https://www.catalog.update.microsoft.com/) and then proceed with the steps below:

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

 Incorrect modifications to the Windows Registry can cause your system to malfunction. We recommend [creating a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before making any changes to the registry entries.

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
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-windows-11-safe-mode-access/"><u>Step-by-Step Guide to Windows 11 Safe Mode Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-in-device-coexistence-utilize-dex-for-galaxy-on-pc/"><u>Mastery in Device Coexistence: Utilize DeX for Galaxy on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refining-windows-11-for-superior-usability/"><u>Refining Windows 11 for Superior Usability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-overcoming-windows-onedrives-cant-add-now-error/"><u>Step-by-Step Guide: Overcoming Windows OneDrive's 'Can’t Add Now' Error</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-data-from-apple-iphone-15-pro-to-new-iphone-15-drfone-by-drfone-transfer-from-ios/"><u>How To Transfer Data from Apple iPhone 15 Pro to New iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-if-you-know-the-magic-of-social-media-and-want-to-create-social-media-video-content-then-have-a-look-on-all-the-essential-things-that-are-needed-for/"><u>Updated If You Know the Magic of Social Media and Want to Create Social Media Video Content, Then Have a Look on All the Essential Things that Are Needed for Making Perfect Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-0xc0000142-in-win7win8/"><u>Resolving Error 0XC0000142 in Win7/Win8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-swordsmans-secrets-tackle-windows-lag-in-star-wars-battlefront-2/"><u>Swift Swordsman's Secrets: Tackle Windows Lag in Star Wars Battlefront 2</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-video-framing-mastery-letterbox-technique-for-social-media-content/"><u>[Updated] Video Framing Mastery  Letterbox Technique for Social Media Content</u></a></li>
<li><a href="https://screen-recording.techidaily.com/efficient-techniques-saving-google-meets-on-phones/"><u>Efficient Techniques  Saving Google Meets on Phones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-challenges-a-guide-to-fixing-your-manager-tool-in-windows-11/"><u>Navigating Challenges: A Guide to Fixing Your Manager Tool in Windows 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-vivo-y17s-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Vivo Y17s | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-guide-for-outdated-pcs-on-their-way-to-windows-11/"><u>The Guide for Outdated PCs on Their Way to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-downloading-and-installing-windows-11-arm-from-iso/"><u>Step by Step: Downloading and Installing Windows 11 ARM From ISO</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-macs-finest-top-rated-mp3-converter-software-for-2024/"><u>New Macs Finest Top-Rated MP3 Converter Software for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-a-comprehensive-approach-to-video-assisted-instruction/"><u>[New] A Comprehensive Approach to Video-Assisted Instruction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-cooling-policies-in-microsofts-os-environment/"><u>Navigating Cooling Policies in Microsoft's OS Environment</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mastering-stream-selection-a-top-10-tips-guide-for-2024/"><u>Mastering Stream Selection  A Top 10 Tips Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-video-cutting-solutions-on-your-windows-11-system/"><u>Masterful Video Cutting Solutions on Your Windows 11 System</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-elite-5-youtube-channel-power-players/"><u>[New] The Elite 5  YouTube Channel Power Players</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-pin-removal-functionality-in-windows-11-os/"><u>Restoring PIN Removal Functionality in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-techniques-for-troubled-windows-11-calendars/"><u>Resetting Techniques for Troubled Windows 11 Calendars</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-right-pace-for-your-cursor-how-to-turn-off-acceleration-win-11/"><u>The Right Pace for Your Cursor: How to Turn Off Acceleration Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-hyper-v-installation-on-w11-home-systems/"><u>Master the Art of Hyper-V Installation on W11 Home Systems</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-hdr-tvs-explored-is-aurora-at-the-forefront/"><u>In 2024, HDR TVs Explored  Is Aurora at the Forefront?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methodical-approach-to-reviving-frozen-start-button/"><u>Methodical Approach to Reviving Frozen Start Button</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11-the-8-most-common-mistakes-for-beginners-to-skip/"><u>Navigating Windows 11: The 8 Most Common Mistakes for Beginners to Skip</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/-in-motion-a-guide-to-lively-animation-methods-for-2024/"><u>Words in Motion  A Guide to Lively Animation Methods for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-analysis-creating-and-interpreting-data/"><u>Navigating Windows Analysis: Creating & Interpreting Data</u></a></li>
<li><a href="https://extra-resources.techidaily.com/boost-your-game-presence-with-free-voice-alteration-tips-for-free-fire/"><u>Boost Your Game Presence with Free Voice Alteration Tips for Free Fire</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-unlock-ig-success-with-expert-insights-on-loop-videos-for-2024/"><u>[Updated] Unlock IG Success with Expert Insights on Loop Videos for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-2023-fb-link-collection-access-8-free-and-online-downloads/"><u>[New] In 2024, 2023 FB Link Collection  Access 8 Free & Online Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategy-to-eradicate-error-0x80300024-on-pcs/"><u>Strategy to Eradicate Error 0X80300024 on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-your-hard-drives-terrain-a-guide-to-diskusage-in-windows/"><u>Navigating Through Your Hard Drive's Terrain: A Guide to DiskUsage in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-for-generating-flawless-ai-images-on-windows-11-through-paint-tool-sai/"><u>The Ultimate Guide for Generating Flawless AI Images on Windows 11 Through Paint Tool SAI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-output-with-windows-streamlined-launcher/"><u>Maximize Output with Windows' Streamlined Launcher</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-implement-without-obstacles-win11-version-22h2-update/"><u>Tactics to Implement Without Obstacles: Win11 Version 22H2 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quelling-win1011-screen-glitches-with-ease/"><u>Quelling WIN10/11 Screen Glitches with Ease</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-what-does-pfp-mean-in-tiktok/"><u>[Updated] In 2024, What Does PFP Mean in TikTok?</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-rise-in-popularity-top-10-instagram-hashtags-for-now-for-2024/"><u>[Updated] Rise in Popularity  Top 10 Instagram Hashtags for Now for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-from-setup-to-screening-wirecasts-role-in-facebook-streaming/"><u>[New] In 2024, From Setup to Screening  Wirecast’s Role in Facebook Streaming</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-tecno-camon-20-premier-5g-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Tecno Camon 20 Premier 5G Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-navigation-tips-on-using-narrator-commands/"><u>Streamlining Windows Navigation: Tips on Using Narrator Commands</u></a></li>
</ul></div>
