---
title: Balance Performance with Media Consumption in Windows
date: 2024-08-16T01:07:28.094Z
updated: 2024-08-17T01:07:28.094Z
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

<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
## 3\. Disable News and Interests Using the Group Policy Editor

 On Windows 11, you can configure News and Interests on the taskbar policy to disable the feature and prevent high memory usage. Group Policy Editor (GPEdit) is a Windows component and is not only available on the OS's Pro, Enterprise, and Education editions.

 If you are on Windows 11 Home, follow these steps to [enable gpedit on Windows Home](https://www.catalog.update.microsoft.com/) and then proceed with the steps below:

1. Press**Win + R** to open**Run** .
2. Type**gpedit.msc** and click**OK** to open**Group Policy Editor** .
3. In Group Policy Editor, navigate to the following location:  
`Computer Configuration > Administrative Templates > Windows Components > News and Interests`
4. In the right pane, right-click on**Enable News and Interests** **on the taskbar** policy and select**Edit** .  
![turn off news and interest disabled 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interest-disabled-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->

1. Next, right-click the**Windows Feeds** key and select**New > DWORD (32-bit) Value** .
2. Rename the new value as**EnableFeeds** .
3. Double-click on the**EnableFeeds** value to edit it.  
![registry editor new key Windows new DWORd value 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows-new-dword-value-0.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
4. Type**0** in the**Value data** field and click**OK** to save the changes.
5. Close the Registry Editor and restart your computer to apply the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Add and Disable EnableFeeds Using PowerShell

![powershell add registry key value Windows feeds Enable feeds](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/powershell-add-registry-key-value-windows-feeds-enable-feeds.jpg)
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-reimagining-ppts-with-todays-webcam-capabilities/"><u>[New] 2024 Approved  Reimagining PPTs with Today's Webcam Capabilities</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-step-by-step-elevating-your-instagram-engagement-through-hashtags/"><u>[New] 2024 Approved  Step-by-Step  Elevating Your Instagram Engagement Through Hashtags</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-inside-out-the-true-significance-behind-snapchats-emojis-for-2024/"><u>[New] Inside Out  The True Significance Behind Snapchat's Emojis for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-the-ultimate-list-8-key-steps-for-irresistible-unboxing-reels/"><u>[New] The Ultimate List  8 Key Steps for Irresistible Unboxing Reels</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-optimizing-skype-call-audio-environment/"><u>[Updated] In 2024, Optimizing Skype Call Audio Environment</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-unraveling-kinemasters-gs-mastery-for-pro-video-editors/"><u>[Updated] In 2024, Unraveling KineMaster’s GS Mastery for Pro Video Editors</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/aesthetic-windowscape-top-picks-for-stunning-laptop-screen-designs-for-2024/"><u>Aesthetic Windowscape  Top Picks for Stunning Laptop Screen Designs for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-the-noise-wake-on-idle-restarts-in-w10w11/"><u>Cutting the Noise: Wake on Idle Restarts in W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-rectifying-windows-steam-e84-problems/"><u>Decoding and Rectifying Windows Steam E84 Problems</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-hp-laserjet-5200-printer-drivers-compatible-with-windows-11-10-and-8/"><u>Download HP LaserJet 5200 Printer Drivers: Compatible with Windows 11, 10 & 8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-system-unveiling-best-apps-of-the-year/"><u>Elevate Your System: Unveiling Best Apps of the Year</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-keystroke-efficiency-via-typingaid/"><u>Enhance Keystroke Efficiency via TypingAid</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exposing-windows-11s-data-collection-strategies/"><u>Exposing Windows 11'S Data Collection Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-selecthighlight-issues-in-pdfs-on-windows-pcs/"><u>Fix Select/Highlight Issues in PDFs on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-steam-folder-permissions-on-windows-11/"><u>Fixing Steam Folder Permissions on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-service-did-not-respond-errors-a-compreranble-solution/"><u>Fixing Windows Service Did Not Respond Errors: A Compreranble Solution</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-honor-x50i-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Honor X50i to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-zte-blade-a73-5g-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on ZTE Blade A73 5G? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-procedure-calls-failure-in-malwarebytes-on-win10win11/"><u>How to Correct Procedure Calls Failure in Malwarebytes on Win10/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-override-microsofts-antivirus-exclusivity-measures/"><u>How to Override Microsoft's Antivirus Exclusivity Measures</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-samsung-galaxy-f14-5g-drfone-by-drfone-virtual-android/"><u>How to Share Location in Messenger On Samsung Galaxy F14 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-file-corruption-problems-error-0x80070570-on-windows-11/"><u>How to Tackle File Corruption Problems (Error 0X80070570) on Windows 11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-11-pro-max-passcode-without-itunes-without-knowing-passcode-by-drfone-ios/"><u>How to Unlock Apple iPhone 11 Pro Max Passcode without iTunes without Knowing Passcode?</u></a></li>
<li><a href="https://win-dash.techidaily.com/improve-your-printing-with-updated-dell-2330d-and-2330dn-driver-patches/"><u>Improve Your Printing with Updated Dell 2330D and 2330Dn Driver Patches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insights-into-artificial-intelligence-computers-uniqueness/"><u>Insights Into Artificial Intelligence Computers' Uniqueness</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/mastering-urdu-fast-one-short-session-daily/"><u>Mastering Urdu Fast: One Short Session Daily</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-the-tech-universe-with-toms-hardware-guides/"><u>Navigating the Tech Universe with Tom's Hardware Guides</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-microsofts-xbox-sound-setup/"><u>Optimizing Microsoft's Xbox Sound Setup</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/platform-precision-examining-obs-against-twitch-hub/"><u>Platform Precision  Examining OBS Against Twitch Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preempt-potential-problems-installing-virtualbox-on-win-with-care/"><u>Preempt Potential Problems: Installing VirtualBox on Win with Care</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-methods-to-fix-file-or-directory-is-corrupt-error-x70-in-windows/"><u>Proven Methods To Fix 'File or Directory Is Corrupt' Error X70 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-rectify-0x80072af9-on-windows-os/"><u>Quick Guide to Rectify 0X80072AF9 on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-working-activation-numbers-in-win11/"><u>Reinstating Working Activation Numbers in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedies-for-black-screen-crisis-in-win-based-playing/"><u>Remedies for Black Screen Crisis in Win-Based Playing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-excel-files-unreadable-in-windows-notepad/"><u>Resolve: Excel Files Unreadable in Windows Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-sign-out-error-caused-by-intrusive-windows-software/"><u>Resolving Sign Out Error Caused by Intrusive Windows Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-your-win1011s-recycle-bin-with-these-fixes/"><u>Revive Your WIN10/11's Recycle Bin with These Fixes</u></a></li>
<li><a href="https://extra-support.techidaily.com/securing-yourself-from-motion-sickness-in-vr-for-2024/"><u>Securing Yourself From Motion Sickness in VR for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sky-high-output-with-these-top-7-masterful-win-11-widgets/"><u>Sky-High Output with These Top 7 Masterful Win 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealthy-apps-in-disguise-hurt-your-windows-11-performance/"><u>Stealthy Apps in Disguise Hurt Your Windows 11 Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-language-barriers-use-windows-hotkeys-for-translation/"><u>Streamline Language Barriers: Use Windows Hotkeys for Translation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-data-exchange-with-python-and-windows-server/"><u>Streamlining Data Exchange with Python and Windows Server</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-action-for-spotify-error-4-windows-11-fixes/"><u>Swift Action for Spotify Error 4: Windows 11 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solution-for-handling-windows-update-failures-and-errors-0x80070003/"><u>Swift Solution for Handling Windows Update Failures & Errors: 0X80070003</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-media-creation-tool-error-x90017/"><u>Unblocking Windows' Media Creation Tool Error X.90017</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-cdrive-and-ddrive-distinctions/"><u>Understanding C:Drive & D:Drive Distinctions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-importance-of-winservicesexe/"><u>Understanding the Importance of WinServices.exe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-fuller-sounds-4-tools-to-exceed-windows-limit/"><u>Unleash Fuller Sounds: 4 Tools to Exceed Windows' Limit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-error-0xc00d36b4-on-windows/"><u>Unraveling the Mystery of Error 0xC00D36B4 on Windows</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-elegant-acoustic-tunes-for-digital-blogging-audio/"><u>Updated 2024 Approved Elegant Acoustic Tunes for Digital Blogging Audio</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-the-mini-moviemaker-a-fun-guide-for-kids-to-make-their-own-movies/"><u>Updated 2024 Approved The Mini Moviemaker A Fun Guide for Kids to Make Their Own Movies</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/warning-avoid-suspicious-win-chatgpt-software/"><u>Warning: Avoid Suspicious Win ChatGPT Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-walks-unlocking-your-gaming-archives/"><u>Windows Walks: Unlocking Your Gaming Archives</u></a></li>
</ul></div>
