---
title: Balance Performance with Media Consumption in Windows
date: 2024-07-12T18:00:50.592Z
updated: 2024-07-13T18:00:50.592Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Balance Performance with Media Consumption in Windows
excerpt: This Article Describes Balance Performance with Media Consumption in Windows
keywords: Windows Balance Usage,WinMedia Consumption Optimize,Media Control Windows Performance,Window Gaming Efficiency,Media Impact on PC Speed,Enhance Windows Playback,Streaming Balance in Windows
thumbnail: https://thmb.techidaily.com/4815bdc4b07f62378c934e8844c6ab3ed5ccd8bb0ecbd12c41105ddecee78795.jpg
---

## Balance Performance with Media Consumption in Windows

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
<li><a href="https://visual-screen-recording.techidaily.com/new-ultimate-guide-for-sustainable-visual-recording-for-2024/"><u>[New] Ultimate Guide for Sustainable Visual Recording for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-from-novice-to-pro-your-journey-with-the-io-screener/"><u>2024 Approved  From Novice to Pro  Your Journey with the IO Screener</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-top-30-camcorders-recommended-for-snow-activities/"><u>[New] In 2024, Top 30 Camcorders Recommended for Snow Activities</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-vivo-v27e-drfone-by-drfone-virtual-android/"><u>5 Easy Ways to Change Location on YouTube TV On Vivo V27e | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-windows-single-board-gadgets/"><u>Best Windows Single-Board Gadgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-persistent-edge-shortcuts/"><u>Avoiding Persistent Edge Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-graphical-performance-in-windows-11s-safeguard-feature/"><u>Amplifying Graphical Performance in Windows 11'S Safeguard Feature</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/laugh-labs-free-comedy-creation-for-creative-souls/"><u>Laugh Labs  Free Comedy Creation for Creative Souls</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-a-vivo-y55s-5g-2023-easily-by-drfone-android/"><u>How To Unlock a Vivo Y55s 5G (2023) Easily?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-sfx-strategies-for-windows-11-users/"><u>Advanced SFX Strategies for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-capture-for-underpowered-computers/"><u>Adjusting Windows Capture for Underpowered Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-fresh-installation-displays-fail-to-start/"><u>Addressing Windows' Fresh Installation: Displays Fail To Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-outlook-speed-quick-tricks-for-win/"><u>Boost Your Outlook Speed: Quick Tricks for WIN</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/altering-your-voice-for-stories-and-reels-on-instagram/"><u>Altering Your Voice for Stories & Reels on Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-auto-lock-on-windows-tips-and-tricks/"><u>Avoiding Auto-Lock on Windows: Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/batch-rename-made-easy-the-powerof-tools-guide/"><u>Batch-Rename Made Easy: The PowerOf Tools Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-windows-11-outputs-with-savvy-techniques/"><u>Amplify Windows 11 Outputs with Savvy Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-docx-to-pdf-conversion-on-modern-windows/"><u>Advanced Tips for Docx-to-PDF Conversion on Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-soon-will-expire-warning-on-microsoft-os/"><u>Avoiding Soon Will Expire Warning on Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-windows-11-start-menu-preferences/"><u>Altering Windows 11 Start Menu Preferences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-frustration-curing-win-error-1-in-minecraft/"><u>Avoiding Frustration: Curing Win Error 1 in Minecraft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-conversion-of-high-efficiency-image-coding-heic-photos-to-jpeg-format/"><u>Automate Conversion of High-Efficiency Image Coding (HEIC) Photos to JPEG Format</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-mobile-connectivity-in-windows-11/"><u>Boosting Mobile Connectivity in Windows 11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-vimeo-profits-unleashed-strategies-for-creative-entrepreneurs/"><u>In 2024, Vimeo Profits Unleashed  Strategies for Creative Entrepreneurs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-lighter-browsing-options-best-in-class-for-ram-consumption/"><u>Assessing Lighter Browsing Options: Best in Class for RAM Consumption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-pitfalls-with-microsoft-teams-how-to-conquer-error-80080300/"><u>Avoiding Pitfalls with Microsoft Teams: How to Conquer Error 80080300</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-rise-to-stardom-secrets-to-viral-video-success/"><u>2024 Approved  Rise to Stardom  Secrets to Viral Video Success</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-exploring-income-derived-from-each-watch-on-video-platforms/"><u>2024 Approved  Exploring Income Derived From Each Watch on Video Platforms</u></a></li>
<li><a href="https://review-topics.techidaily.com/mov-playback-issues-on-galaxy-z-flip-5-by-aiseesoft-video-converter-play-mov-on-android/"><u>MOV playback issues on Galaxy Z Flip 5</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-functionality-and-visual-impact-of-win11-taskbar-icons/"><u>Boosting Functionality & Visual Impact of Win11 Taskbar Icons</u></a></li>
<li><a href="https://extra-hints.techidaily.com/novices-navigate-for-speedy-snapchat-videos/"><u>Novice's Navigate for Speedy Snapchat Videos</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-giggle-guild-creepy-cybernetic-comedians/"><u>In 2024, Giggle Guild  Creepy Cybernetic Comedians</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-elusive-obs-recording-glitches-on-windows-operating-system/"><u>Beating Elusive OBS Recording Glitches on Windows Operating System</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-best-android-video-stabilization-apps-that-wont-cost-you-a-dime/"><u>New 2024 Approved Best Android Video Stabilization Apps That Wont Cost You a Dime</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-crafting-captivating-campaigns-elevating-roi-in-fbs-animation-space/"><u>[Updated] In 2024, Crafting Captivating Campaigns  Elevating ROI in FB's Animation Space</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-firecapture-plugins-for-firefox/"><u>In 2024, FireCapture Plugins for Firefox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-creating-efficient-troubleshooter-tools-shortcuts/"><u>Boost Productivity: Creating Efficient Troubleshooter Tools Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-black-remote-desktop-display/"><u>Addressing Window's Black Remote Desktop Display</u></a></li>
<li><a href="https://extra-hints.techidaily.com/action-filming-elevated-in-depth-review-of-sj-cam-s6/"><u>Action Filming Elevated  In-Depth Review of SJ-CAM S6</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-maximizing-impact-with-google-based-podcast-uploads/"><u>2024 Approved  Maximizing Impact with Google-Based Podcast Uploads</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-optimize-viewership-with-proficient-timestamp-placement-on-youtube/"><u>2024 Approved  Optimize Viewership with Proficient Timestamp Placement on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-strengths-of-win11-in-compare-with-macos/"><u>Analyzing the Strengths of Win11 in Compare with MacOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-screen-glitches-in-modern-operating-systems/"><u>Banishing Screen Glitches in Modern Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginners-guide-efficient-w11-microphone-use/"><u>Beginner's Guide: Efficient W11 Microphone Use</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-affordable-high-definition-top-mirrorless-cameras-(1k/"><u>[Updated] Affordable High-Definition  Top Mirrorless Cameras (<$1K)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unexpected-print-problem-discovered/"><u>Unexpected Print Problem Discovered</u></a></li>
<li><a href="https://facebook.techidaily.com/revised-tips-youngsters-advised-against-insta-use/"><u>Revised Tips: Youngsters Advised Against Insta Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-game-interruption-preventing-frequent-ps4-controller-drop-outs-in-windows/"><u>Avoid Game Interruption: Preventing Frequent PS4 Controller Drop-Outs in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/backup-plan-for-windows-users-when-bitlocker-isnt-an-option/"><u>Backup Plan for Windows Users When BitLocker Isn't an Option</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-terminals-user-privilege-settings/"><u>Adjusting Windows Terminal's User Privilege Settings</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-navigating-the-world-of-9gag-memes-made-easy/"><u>[Updated] Navigating the World of 9GAG Memes Made Easy</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-itel-p40plus-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Itel P40+ to Roku | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-master-digital-design-integrating-text-with-visuals-for-improved-clarity/"><u>[New] Master Digital Design  Integrating Text with Visuals for Improved Clarity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approach-to-reveal-hidden-drives-on-windows/"><u>Approach to Reveal Hidden Drives on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-mouse-pointer-style-in-winxpvista7/"><u>Adjusting Mouse Pointer Style in WinXP/Vista/7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitlock-cracked-staying-secure-yet-unmoved/"><u>BitLock Cracked: Staying Secure Yet Unmoved</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-discover-the-top-30-free-intro-creators-on-youtube/"><u>2024 Approved  Discover the Top 30 Free Intro Creators on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-overlapping-defenses-opt-for-a-singular-antivirus-on-windows/"><u>Avoid Overlapping Defenses: Opt for a Singular Antivirus on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-assistants-impact-on-windows-11-experience/"><u>AI Assistant's Impact on Windows 11 Experience</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-optimized-vimeo-video-exporting-apps-for-2024/"><u>[Updated] Optimized Vimeo Video Exporting Apps for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-ideal-tools-for-group-online-communication/"><u>[New] Ideal Tools for Group Online Communication</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-geo-blocking-and-how-to-bypass-it-on-vivo-y100-drfone-by-drfone-virtual-android/"><u>What is Geo-Blocking and How to Bypass it On Vivo Y100? | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-leveraging-free-audio-sources-in-your-photos-a-guide-for-windows-and-ios-users/"><u>New 2024 Approved Leveraging Free Audio Sources in Your Photos A Guide for Windows and iOS Users</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-pioneering-strategies-in-instavid-world-design-an-optimal-marketing-approach/"><u>In 2024, Pioneering Strategies in InstaVid World  Design an Optimal Marketing Approach</u></a></li>
<li><a href="https://some-guidance.techidaily.com/tech-analysis-elite-parrot-ar-drone-20-for-2024/"><u>Tech Analysis  Elite Parrot AR Drone 2.0 for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/n-2024-from-individual-to-institutional-growth-in-youtube-space/"><u>[New] In 2024, From Individual to Institutional Growth in YouTube Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-11-protection-with-new-firewall-add-ons-in-the-context-menu/"><u>Boost Windows 11 Protection with New Firewall Add-Ons in the Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-windows-11-highlighted-icons-for-tidy-desktop/"><u>Banish Windows 11 Highlighted Icons for Tidy Desktop</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-choosing-your-gopro-an-exhaustive-comparison/"><u>2024 Approved  Choosing Your GoPro  An Exhaustive Comparison</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-icon-sizes-in-windows-interface/"><u>Altering Icon Sizes in Windows Interface</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-pictures-from-a18-by-fonelab-android-recover-pictures/"><u>Possible solutions to restore deleted pictures from A18.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-workflow-the-ultimate-guide-to-wpm-in-windows-11/"><u>Boost Your Workflow: The Ultimate Guide to WPM in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-insider-look-at-microsofts-revolutionary-copilot-tool/"><u>An Insider Look at Microsoft's Revolutionary Copilot Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-wows-endless-loop-fix-error-132-in-win-editions/"><u>Avoid WoW's Endless Loop: Fix Error 132 in Win Editions</u></a></li>
</ul></div>
