---
title: Regain Your Lost Screen Symbols in Win 11
date: 2024-07-12T16:46:20.734Z
updated: 2024-07-13T16:46:20.734Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Regain Your Lost Screen Symbols in Win 11
excerpt: This Article Describes Regain Your Lost Screen Symbols in Win 11
keywords: Lose Symbol Recovery Windows,Restore Window Characters,Find Missing Icons W11,Clear W11 Icon Glitches,Fix Windows Symbol Errors,Resolve Icon Issues W11,Reinstate Lost W11 Symbols
thumbnail: https://thmb.techidaily.com/2667f52774b221737f5b40cebcdbe6bd28a1a07909c05b7a4646323bdf667e48.jpg
---

## Regain Your Lost Screen Symbols in Win 11

 Desktop icons on Windows 11 give you quick access to your favorite apps, files, folders, and more. But what if these desktop icons vanish without a trace? How do you get the icons back?

 If you're facing this baffling problem, this guide will help you restore the missing desktop icons in Windows 11.

## 1\. Enable Show Desktop Icons

 On Windows 11, you can show or hide desktop icons with a couple of clicks. So, if you’ve accidentally hidden your desktop icons, getting them back is fairly easy.

 Right-click anywhere on an empty spot on your desktop and select**View > Show desktop icons** . Once you do that, all your hidden desktop icons should reappear.

![Show Desktop Icons on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Show-Desktop-Icons-on-Windows-11.jpg)

## 2\. Check Desktop Icon Settings

 If you're only missing a few desktop icons, such as This PC, Recycle Bin, Control Panel, and others, you may have disabled them in the "Desktop Icon Settings" window. In that case, you can use the following steps to re-enable those desktop icons.

1. Open the**Start menu** and click the**gear icon** to launch the Settings app.
2. Select**Personalization** from the left sidebar.
3. Select**Themes** .
4. Under**Related settings** , click on**Desktop icon settings** .
5. Under the**Desktop icons** section, use the checkboxes to enable the icons you want on your desktop.
6. Click**Apply** followed by**OK** to save the changes.  
![Desktop Icon Settings Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Desktop-Icon-Settings-Window.jpg)

 Once you complete the above steps, your icons should appear on the desktop.

## 3\. Restart Windows Explorer

 The Windows Explorer process handles the Graphical User Interface (GUI) for a number of utilities, including the desktop. If this service encounters any issues, your desktop and taskbar icons may disappear. If this is the case, you can restart the Windows Explorer process to fix the problem.

1. Right-click on the Start icon or press**Win + X** to open the Power User menu.
2. Select**Task Manager** from the list.
3. In the**Processes** tab, locate**Windows Explorer** . Right-click on it and select**Restart** .  
![Restart Windows Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Restart-Windows-Explorer.jpg)

 Your taskbar will disappear for a brief moment and then reappear. Following this, your desktop icons should be visible.

## 4\. Rebuild Icon Cache

 Another reason why desktop icons on Windows may appear broken or go missing is if the existing icon cache data is corrupt. In that case, you can try clearing the corrupted icon cache data. This will force Windows to rebuild the icon cache from scratch and resolve your problem.

To rebuild icon cache on Windows 11:

1. Press**Win + S** to open the search menu.
2. Type**command prompt** in the box and select**Run as administrator** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Paste the following command in the console and press**Enter** to navigate to the directory where Windows stores the icon cache.  
`cd /d %userprofile%\AppData\Local\Microsoft\Windows\Explorer`
5. Run the following command to terminate the Explorer process:  
`taskkill /f /im explorer.exe`
6. Paste this command and press**Enter** to delete icon cache files:  
`del iconcache*`  
![Rebuild Icon Cache Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Rebuild-Icon-Cache-Windows.jpg)
7. Finally, type in the following text and hit**Enter** to restart Explorer:  
`Explorer.exe`

 Once you complete the above steps, restart your PC and see if the desktop icons appear.

## 5\. Update Your PC’s Graphics Driver

 An outdated graphics driver on Windows can also lead to such anomalies. You can try updating the faulty driver using Device Manager to see if that helps. Here's how to do it.

1. Press**Win + S** to open the search menu.
2. Type**device manager** in the search box and select the first result that appears.
3. Expand**Display adapters** .
4. Right-click on your graphics driver and select**Update driver** .
5. Select**Search automatically for drivers** to let Windows find and install the best drivers.  
![Update Graphics Driver on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Update-Graphics-Driver-on-Windows.jpg)

 If the issue persists even after updating the driver, your graphics driver may be corrupt. In that case, you'll need to reinstall the graphics driver on your PC. Refer to our guide on [how to fix corrupt drivers on Windows](https://www.makeuseof.com/how-to-fix-corrupt-drivers-on-windows-10/) for more instructions on how to fix this.

## 6\. Check the Group Policy Settings

 The Group Policy Editor lets you make various system-wide changes on your Windows computer. If desktop icons are disabled from the Group Policy Editor, you won’t be able to add or remove desktop icons no matter what you do. To fix this, you must disable this “Hide and disable all items on the desktop” from the Group Policy Editor.

 Note that you can only access the Group Policy Editor on Windows 11 Professional, Enterprise, and Education editions. If you’re running Windows 11 Home, check our guide on [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Click the magnifying icon on the taskbar to open the search menu.
2. Type**gpedit.msc** in the box and press**Enter** . This will open the Local Group Policy Editor.
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Desktop** .
4. Double-click the**Hide and disable all items on the desktop** policy on your right.
5. Select**Not configured** or**Disabled** .
6. Click**Apply** followed by**OK** .  
![Enable Desktop Icons on Windows 11 via Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Enable-Deskop-Icons-on-Windows-11-via-Group-Policy-Editor-1.jpg)

## 7\. Perform a System Restore

 There's a chance that a recent system change is to blame for the missing desktop icons in Windows 11\. If you can't figure out what it is, you can use System Restore to restore Windows to a previous state.

Follow these steps to perform a system restore on Windows:

1. Press**Win + R** to open the Run dialog box.
2. Type**sysdm.cpl** in the box and press**Enter** .
3. Under the**System Protection** tab, click on**System Restore** .
4. Click**Next** .
5. Select a restore point before the issue first appeared and hit**Next** .
6. Click on**Finish** .  
![System Restore Dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/System-Restore-Dialog.jpg)

 Wait for Windows to reboot and revert to the specified restore point. Following that, your desktop icons should appear.

## 8\. Manually Restore the Desktop Shortcut Icons

 If your desktop icons are still missing at this point, you can try restoring them manually.

 To add an icon to the desktop in Windows 11, open the**Start menu** and click on**All apps** . Scroll down to the app you want to add to the desktop. Finally, drag the app shortcut to your desktop.

![Create Desktop Shortcut From Start Menu in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Create-Desktop-Shortcut-From-Start-Menu-in-Windows.jpg)

 Alternatively, you can create a shortcut on your desktop by using the Create Shortcut wizard. To do so, right-click anywhere on the desktop and select**New > Shortcut** . Then, click the**Browse** button to locate the file, folder, or app you want to add to your desktop. Then, click**Next** followed by**Finish** .

 We covered this topic in more detail in our guide to [how to add icons to the desktop on Windows](https://www.makeuseof.com/how-to-add-icon-to-desktop-windows/) .

## Restore the Missing Desktop Icons on Windows 11

 Hopefully, the above-mentioned solutions have helped you restore the missing desktop icons on Windows 11 and things are back to normal. However, if none of the above solutions work, you may have to reset your Windows 11 PC as a last resort.


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
<li><a href="https://win11-tips.techidaily.com/the-essentials-of-win11-personalized-volume-shortcuts/"><u>The Essentials of Win11 Personalized Volume Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-workday-woes-into-productivity-peaks-using-windows-11s-tools/"><u>Transform Workday Woes Into Productivity Peaks Using Windows 11'S Tools</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-guide-to-visualizing-sound-integrating-audio-waves-and-enhancing-them-with-motion-effects-in-adobe-premiere-pro/"><u>New Guide to Visualizing Sound Integrating Audio Waves and Enhancing Them with Motion Effects in Adobe Premiere Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-must-haves-alerts-windows-10-and-11-troubleshooting/"><u>Avoiding 'Must-Haves' Alerts: Windows 10 & 11 Troubleshooting</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-champions-of-3d-spatial-displays/"><u>[Updated] Champions of 3D Spatial Displays</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-tweet-transformation-techniques-for-free-gifs/"><u>[Updated] In 2024, Tweet Transformation Techniques for Free GIFs</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-device-compatibility-mf4770n-update-in-w11win8w7-os/"><u>Enhance Device Compatibility: MF4770n Update in W11/Win8/W7 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-management-navigating-taskbar-with-windows-hotkeys/"><u>Effortless Management: Navigating Taskbar with Windows Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-your-pcs-visual-fidelity-with-updated-radeon-drivers-windows-edition/"><u>Elevating Your PC's Visual Fidelity with Updated Radeon Drivers, Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/engage-with-windows-11s-screen-snip-functionality/"><u>Engage with Windows 11'S Screen Snip Functionality</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/eling-your-yt-playlist-quick-methods-for-reversal-for-2024/"><u>Unraveling Your YT Playlist  Quick Methods for Reversal for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-perfect-your-content-with-tiktoks-number-manipulation-tricks-for-2024/"><u>[New] Perfect Your Content with TikTok's Number Manipulation Tricks for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/different-methods-to-unlock-your-iphone-11-pro-max-by-drfone-ios/"><u>Different Methods To Unlock Your iPhone 11 Pro Max</u></a></li>
<li><a href="https://activate-lock.techidaily.com/unlock-your-device-icloud-dns-bypass-explained-and-tested-plus-easy-alternatives-from-apple-iphone-12-mini-by-drfone-ios/"><u>Unlock Your Device iCloud DNS Bypass Explained and Tested, Plus Easy Alternatives From Apple iPhone 12 mini</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/3-ways-to-unlock-apple-iphone-7-without-passcode-or-face-id-drfone-by-drfone-ios/"><u>3 Ways to Unlock Apple iPhone 7 without Passcode or Face ID | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-lightning-leap-fame-mastering-instagram-with-these-15-essential-easy-tips-for-overnight-success/"><u>2024 Approved  Lightning Leap Fame  Mastering Instagram with These 15 Essential, Easy Tips for Overnight Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-remove-black-display-on-pc-webcam/"><u>Tips to Remove Black Display on PC Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unnoticed-slowdown-agents-innocent-looking-apps-for-windows-11/"><u>Unnoticed Slowdown Agents: Innocent-Looking Apps for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chocolatey-vs-wm-top-tools-for-windows-software-downloads/"><u>Chocolatey vs WM: Top Tools for Windows Software Downloads</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-vivo-y100-5g-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Vivo Y100 5G to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-capture-and-amplify-no-cost-digital-picture-upgrades/"><u>2024 Approved  Capture & Amplify - No Cost Digital Picture Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-performance-replacing-aged-technology/"><u>Streamlining Windows Performance: Replacing Aged Technology</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-htc-u23-pro-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from HTC U23 Pro Phones with/without a PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/become-a-cmd-guru-understand-these-20-crucial-commands/"><u>Become a CMD Guru: Understand These 20 Crucial Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-from-starting-spotify-by-default/"><u>Stop Windows From Starting Spotify by Default</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-honor-magic-vs-2-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Honor Magic Vs 2 Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-identifying-the-swift-growing-triumphs-in-todays-youtube-landscape/"><u>[New] Identifying the Swift-Growing Triumphs in Today's YouTube Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-error-0x80131500-on-microsoft-store/"><u>Disabling Error 0X80131500 on Microsoft Store</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713949590611-do-you-want-to-slow-down-your-tiktok-video-and-zoom-on-a-specific-part-this-is-no-longer-a-difficult-task-as-this-video-comes-up-with-the-right-set-of-metho/"><u>Do You Want to Slow Down Your TikTok Video and Zoom on a Specific Part? This Is No Longer a Difficult Task as This Video Comes up with the Right Set of Methods that Can Be Used to Implement the Slow Zoom Effect TikTok for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-resume-windows-netflix-playback/"><u>Strategies to Resume Windows Netflix Playback</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-vivo-v29-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On Vivo V29 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-checklist-for-dolby-atmos-installation-in-windows/"><u>The Essential Checklist for Dolby Atmos Installation in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-result-visibility-for-windows-1011s-search/"><u>Enhancing Result Visibility for Windows 10/11'S Search</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-win11s-reversion-of-files-to-read-only/"><u>Tackling Win11's Reversion of Files to Read-Only</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-windows-11-faces-a-slow-uptake-from-users/"><u>Why Windows 11 Faces a Slow Uptake From Users</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-top-8-best-video-grabbers-for-windows-11-for-2024/"><u>[New] Top 8 Best Video Grabbers for Windows 11 for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-the-ultimate-slomo-recording-tool-assessment-guide/"><u>[Updated] 2024 Approved  The Ultimate SloMo Recording Tool Assessment Guide</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-hit-parade-the-top-10-songs-on-spotify/"><u>[Updated] Hit Parade  The Top 10 Songs on Spotify</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-pokemon-go-no-gps-signal-heres-every-possible-solution-on-poco-c50-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go No GPS Signal? Heres Every Possible Solution On Poco C50 | Dr.fone</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-prime-vr-options-enhancing-drone-operations/"><u>[Updated] In 2024, Prime VR Options Enhancing Drone Operations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-share-cant-be-opened-issues-in-geforce/"><u>Eliminating Share Can't Be Opened Issues in GeForce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/charting-your-course-in-windows-preload-land/"><u>Charting Your Course in Windows Preload Land</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-disconnected-pc-from-wireless-lan/"><u>Steps to Fix Disconnected PC From Wireless LAN</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-smart-video-editing-tools-with-auto-reframing-capabilities/"><u>New Smart Video Editing Tools with Auto-Reframing Capabilities</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-art-of-selecting-podcasts-for-iphone-devices-for-2024/"><u>The Art of Selecting Podcasts for iPhone Devices for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-pc-performance-insider-tips-on-wintools/"><u>Elevate PC Performance: Insider Tips on WinTools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-windows-storage-the-top-free-volume-boosters-list/"><u>Enhance Your Windows Storage: The Top Free Volume Boosters List</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-unlocking-voice-functionality-in-tiktok-videos/"><u>[New] Unlocking Voice Functionality in TikTok Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automating-power-indicators-full-charges-notify-you-in-win11/"><u>Automating Power Indicators: Full Charges Notify You in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-web-pace-unify-phone-and-laptop-connectivity/"><u>Balancing Web Pace: Unify Phone & Laptop Connectivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfolding-windows-11s-enigma-insights-into-the-registry/"><u>Unfolding Windows 11'S Enigma: Insights Into the Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-the-benefits-in-not-muting-wins-11-pushes/"><u>Uncovering the Benefits in Not Muting Wins 11 Pushes</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-mastering-bandicam-key-takeaways-and-tips/"><u>[New] 2024 Approved  Mastering Bandicam - Key Takeaways and Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-turning-onoff-secure-boot-in-virtualbox/"><u>Step-by-Step Guide: Turning On/Off Secure Boot in VirtualBox</u></a></li>
</ul></div>
