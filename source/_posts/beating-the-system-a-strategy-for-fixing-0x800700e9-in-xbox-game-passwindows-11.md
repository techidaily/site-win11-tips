---
title: "Beating the System: A Strategy for Fixing 0X800700E9 in Xbox Game Pass/Windows 11"
date: 2024-07-12T18:01:00.329Z
updated: 2024-07-13T18:01:00.329Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Beating the System: A Strategy for Fixing 0X800700E9 in Xbox Game Pass/Windows 11"
excerpt: "This Article Describes Beating the System: A Strategy for Fixing 0X800700E9 in Xbox Game Pass/Windows 11"
keywords: Zero Error Code 0X800700E9 Xbox,Xbox Fix Strategy,Windows 11 Gaming Issues,Game Pass Troubleshooting,System Glitch Resolution,Xbox Games Compatibility,Win11 Gaming Problems
thumbnail: https://thmb.techidaily.com/98061f90f0702266772c41039bf7505ea26afb88709675b4845f86d9c07123c1.jpg
---

## Beating the System: A Strategy for Fixing 0X800700E9 in Xbox Game Pass/Windows 11

 The Xbox Game Pass is a popular Microsoft subscription service for games. However, some users encounter a 0x800700e9 error when they try to download and install Xbox Game Pass titles via the Xbox app or Microsoft Store. The 0x800700e9 error code message says “Something unexpected happened,” which provides no clue as to how to resolve that issue.

 Users can’t download and install Xbox Game Pass content because of error 0x800700e9\. However, you can fix error 0x800700e9 with these potential resolutions.

## 1\. Run the Microsoft Store App Troubleshooter

 The Windows Store App troubleshooter might help fix the error 0x800700e9\. This is how you can access the Windows Store App troubleshooter in Windows 11:

1. Use one of the many [ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Click the**Troubleshoot** box that has a spanner icon.
3. Next, click**Other-troubleshooters** to access the Settings app’s list of troubleshooting tools.
4. Select**Run** for activating the Windows Store Apps.  
![The Run button for the Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-button-for-windows-store-apps-troubleshooter.jpg)
5. Apply any suggestions the troubleshooter provides.

 The Windows 10 troubleshooters are available within the**Update & Security** category of Settings. Click the**Troubleshoot** tab in that category and select**Additional troubleshooters** . Then you can select Windows Store Apps from there and click**Run** to access the tool.

## 2\. Turn Delivery Optimization On in Settings

 Delivery Optimization is a service that enables Windows Update downloads from other PCs. Error 0x800700e9 often arises when Delivery Optimization is disabled in Windows. You can turn on Delivery Optimization via Settings like this:

1. Open the**Windows Update** tab in Settings.
2. Click**Advanced options** to view more settings.
3. Select the**Delivery Optimization** navigation option.  
![The Delivery Optimization navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delivery-optimization-navigation-option.jpg)
4. Turn on the**Allow downloads from other PCs** option to enable Delivery Optimization.  
![The Allow downloads from other PCs option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/allow-downloads-from-other-pcs-option.jpg)
5. Click the**Devices on my local network** radio button.

 You can enable Delivery Optimization in Windows 10’s Settings app much the same. However, you’ll need to select the**Windows Update** category. Then click the**Deliver Optimization** tab in the**Windows Update** category to access and turn on the same**Allow downloads from other PCs** setting.

## 3\. Enable the Delivery Optimization and BITS Services

 Some Xbox Game Pass users have resolved error 0x800700e9 by enabling and running the Delivery Optimization and BITS services. You can enable and start those services via that app as follows:

1. To access Run, press**Win + R** .
2. Type**services.msc** inside Run’s**Open** command box.
3. Select**OK** to open Services.
4. Double-click the Delivery Optimization service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/services-window2.jpg)
5. Select**Start** if it’s not running.
6. Click**Automatic** on Delivery Optimization’s**Startup type** menu.  
![The Delivery Optimization Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delivery-optimization-properties-window.jpg)
7. Select**Apply** \>**OK** to save the service’s new settings.
8. Repeat steps four to seven for the Background Intelligent Transfer service.

 If the services are already running, try restarting them. Right-click the services and select their**Stop** options. Then you can start those services again by right-clicking them and selecting**Restart** .

## 4\. Enable Delivery Optimization via the Windows Registry

 If the above methods didn't work for you, try enabling Delivery Optimization service by editing the registry. You can back up the registry or set up a restore point before editing the registry if you want to be extra careful. To apply this potential solution, edit the**DoSvc** key like this:

1. First, bring up Registry Editor, which you can open with one of the methods in our guide on [how to open Regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click inside the address bar at the top of Registry Editor and erase the current key location.
3. Input this**DoSvc** key location in the address bar and hit**Return** :  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\DoSvc`  
![The DoSvc key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dovsc-key.jpg)
4. Select the**DoSvc** key, and right-click the**Start** DWORD to select**Modify** .  
![The Modify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/modify-option.jpg)
5. Input**3** in the**Value** box and click**OK** .  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/start-dword-key.jpg)
6. Exit Regedit, and restart the PC.

## 5\. Reset or Repair the Xbox App

 Many users go through the Xbox app to get at their Xbox Game Pass titles on Windows. As such, you might be able to fix error 0x800700e9 by selecting**Reset and Repair** options for the Xbox app inside Settings.

 Check out our guide on [resetting apps in Windows 11 and 10](https://www.makeuseof.com/windows-reset-app/) to clear the Xbox app’s data. The**Repair** option for the Xbox app in Settings is available just above its**Reset** button.

![The Reset option for the Xbox app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-option.jpg)

## 6\. Reset the Microsoft Store Cache

 A corrupted Microsoft Store cache data can cause download and installation issues to arise for apps available on Microsoft’s online store. So, resetting the Store’s cache could be another potential solution for the 0x800700e9 error. Try resetting Microsoft Store’s cache in the following steps:

1. Bring up the Windows Search by clicking the magnifying glass or**Search** box on your taskbar.
2. Type**WSReset.exe** within the search box to find that Run command file.
3. Click**WSReset.exe** to run the command.  
![The wsreset.exe Run command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/wsreset-exe-command.jpg)
4. Wait for MS Store to open automatically, and then try downloading Xbox Game Pass titles again.

## 7\. Reinstall the Microsoft Store

 Reinstalling the Microsoft Store can fix deeper issues with that app that could be causing error 0x800700e9\. Although you can’t select to uninstall Microsoft Store, you can still reinstall that app with a PowerShell command. Here are the steps for reinstalling the Microsoft Store via PowerShell:

1. Bring up Run with the**Win + R** keyboard shortcut, and input**PowerShell** within the text box.
2. Right-click PowerShell to bring up a context menu, and select the**Run as administrator** option.
3. Execute this PowerShell command for reinstalling Microsoft Store:  
`Get-AppxPackage -allusers Microsoft.WindowsStore | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Microsoft Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reinstall-microsoft-store-command.jpg)
4. Wait for the command to finish, and then exit the command app.

## 8\. Reset Your Network

![The Network reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-reset-option.jpg)

 Error 0x800700e9 can also sometimes occur because of network issues. Performing a network reset is a good way to troubleshoot issues in this area; however, do note that this will restore your network components to their factory defaults and erase your Wi-Fi and Ethernet connections.

 Have a look at our [how to reset your network settings on Windows](https://www.makeuseof.com/reset-network-settings-windows-11/) guide for details about how to apply this troubleshooting method.

## Enjoy Your Xbox Game Pass Games Again

 Fortunately, you don’t have to cancel your Xbox Game Pass subscription because of error 0x800700e9\. A lot of users have fixed this installation issue for Xbox Game Pass titles with the resolutions in this guide.

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
<li><a href="https://win11-tips.techidaily.com/analyzing-the-strengths-of-win11-in-compare-with-macos/"><u>Analyzing the Strengths of Win11 in Compare with MacOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-black-remote-desktop-display/"><u>Addressing Window's Black Remote Desktop Display</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/navigating-the-world-of-video-screen-capture/"><u>Navigating the World of Video Screen Capture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balance-performance-with-media-consumption-in-windows/"><u>Balance Performance with Media Consumption in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-pitfalls-with-microsoft-teams-how-to-conquer-error-80080300/"><u>Avoiding Pitfalls with Microsoft Teams: How to Conquer Error 80080300</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-add-meaningful-context-a-guide-to-video-captions-on-tiktok-for-2024/"><u>[New] Add Meaningful Context  A Guide to Video Captions on TikTok for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-insider-look-at-microsofts-revolutionary-copilot-tool/"><u>An Insider Look at Microsoft's Revolutionary Copilot Tool</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-realme-12-proplus-5g-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Realme 12 Pro+ 5G to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-11-protection-with-new-firewall-add-ons-in-the-context-menu/"><u>Boost Windows 11 Protection with New Firewall Add-Ons in the Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augment-windows-security-incorporating-advanced-firewalls-in-the-context-menu/"><u>Augment Windows Security: Incorporating Advanced Firewalls in the Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-frustration-curing-win-error-1-in-minecraft/"><u>Avoiding Frustration: Curing Win Error 1 in Minecraft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-fresh-installation-displays-fail-to-start/"><u>Addressing Windows' Fresh Installation: Displays Fail To Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitlock-cracked-staying-secure-yet-unmoved/"><u>BitLock Cracked: Staying Secure Yet Unmoved</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-windows-single-board-gadgets/"><u>Best Windows Single-Board Gadgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-soon-will-expire-warning-on-microsoft-os/"><u>Avoiding Soon Will Expire Warning on Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-capture-for-underpowered-computers/"><u>Adjusting Windows Capture for Underpowered Computers</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-in-2024-read-on-to-learn-about-opencv-object-tracking-what-it-is-and-how-to-implement-it-in-python-and-opencv/"><u>Updated In 2024, Read on to Learn About OpenCV Object Tracking, What It Is, and How to Implement It in Python, and OpenCV</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-want-to-find-the-best-alternatives-of-windows-movie-maker-for-mac-here-is-a-quick-rundown-of-five-of-the-best-movie-maker-for-mac/"><u>In 2024, Want to Find the Best Alternatives of Windows Movie Maker for Mac? Here Is a Quick Rundown of Five of the Best Movie Maker for Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-assistants-impact-on-windows-11-experience/"><u>AI Assistant's Impact on Windows 11 Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/batch-rename-made-easy-the-powerof-tools-guide/"><u>Batch-Rename Made Easy: The PowerOf Tools Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/become-a-speech-converter-transcribe-talk-with-whisper-in-windows/"><u>Become a Speech Converter: Transcribe Talk with Whisper in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-graphical-performance-in-windows-11s-safeguard-feature/"><u>Amplifying Graphical Performance in Windows 11'S Safeguard Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adobe-validation-skip-pop-ups-on-pc/"><u>Adobe Validation: Skip Pop-Ups on PC</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-top-15-windows-11-tools-for-video-capture/"><u>[Updated] 2024 Approved  Top 15 Windows 11 Tools for Video Capture</u></a></li>
<li><a href="https://extra-tips.techidaily.com/ranking-the-ultimate-vr-fun-on-mobile-devices/"><u>Ranking the Ultimate VR Fun on Mobile Devices</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-free-video-fiddling-unleash-potential-with-vimeo-editing/"><u>[New] Free Video Fiddling  Unleash Potential with Vimeo Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-windows-in-a-chip-size-world/"><u>Best Windows in a Chip Size World</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-tips-for-adding-mp4-files-from-windows-movie-maker-onto-vimeo/"><u>In 2024, Tips for Adding MP4 Files From Windows Movie Maker Onto Vimeo</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/cutting-it-up-a-beginners-guide-to-splitting-videos-in-windows-live-movie-maker-for-2024/"><u>Cutting It Up A Beginners Guide to Splitting Videos in Windows Live Movie Maker for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-windows-11-highlighted-icons-for-tidy-desktop/"><u>Banish Windows 11 Highlighted Icons for Tidy Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-persistent-edge-shortcuts/"><u>Avoiding Persistent Edge Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-creating-efficient-troubleshooter-tools-shortcuts/"><u>Boost Productivity: Creating Efficient Troubleshooter Tools Shortcuts</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-getting-started-guide-to-instagrams-live-feature-for-2024/"><u>[New] Getting Started Guide to Instagram's Live Feature for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-docx-to-pdf-conversion-on-modern-windows/"><u>Advanced Tips for Docx-to-PDF Conversion on Modern Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-realme-gt-5-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On Realme GT 5 For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-generated-windows-keys-unveiling-potential-perils/"><u>AI-Generated Windows Keys: Unveiling Potential Perils</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-unwanted-bios-access-during-windows-initialization/"><u>Avoiding Unwanted BIOS Access During Windows Initialization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-workflow-the-ultimate-guide-to-wpm-in-windows-11/"><u>Boost Your Workflow: The Ultimate Guide to WPM in Windows 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/top-10-companion-apps-for-seamless-video-to-mp3-conversions-for-2024/"><u>Top 10 Companion Apps for Seamless Video to Mp3 Conversions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-sfx-strategies-for-windows-11-users/"><u>Advanced SFX Strategies for Windows 11 Users</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/capturing-adrenaline-with-the-latest-yi-technology-for-2024/"><u>Capturing Adrenaline with the Latest Yi Technology for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-windows-11-start-menu-preferences/"><u>Altering Windows 11 Start Menu Preferences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-windows-11-outputs-with-savvy-techniques/"><u>Amplify Windows 11 Outputs with Savvy Techniques</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-the-social-media-savant-writes-on-mastering-brand-promotion/"><u>[New] The Social Media Savant' Writes on Mastering Brand Promotion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginners-guide-efficient-w11-microphone-use/"><u>Beginner's Guide: Efficient W11 Microphone Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-mouse-pointer-style-in-winxpvista7/"><u>Adjusting Mouse Pointer Style in WinXP/Vista/7</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-streamline-your-videos-a-guide-to-igtv-posting/"><u>[Updated] 2024 Approved  Streamline Your Videos  A Guide to IGTV Posting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-boot-on-windows-sound-service-efficiency/"><u>Boosting Boot-On Windows Sound Service Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-efficiency-the-ultimate-guide-to-wintools/"><u>Boost Windows Efficiency: The Ultimate Guide to Wintools</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-how-to-animate-designs-with-canva-gif-for-2024/"><u>New How to Animate Designs With Canva GIF for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/elevating-your-youtube-experience-tips-on-channel-art-and-sizes-for-2024/"><u>Elevating Your YouTube Experience  Tips on Channel Art and Sizes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/backup-plan-for-windows-users-when-bitlocker-isnt-an-option/"><u>Backup Plan for Windows Users When BitLocker Isn't an Option</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-beginners-backstage-pass-to-photo-tricks/"><u>2024 Approved  Beginner's Backstage Pass to Photo Tricks</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-6-ways-to-change-spotify-location-on-your-nokia-g22-drfone-by-drfone-virtual-android/"><u>In 2024, 6 Ways to Change Spotify Location On Your Nokia G22 | Dr.fone</u></a></li>
</ul></div>
