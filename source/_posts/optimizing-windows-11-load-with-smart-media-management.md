---
title: Optimizing Windows 11 Load with Smart Media Management
date: 2024-11-04T21:36:24.189Z
updated: 2024-11-07T01:13:59.057Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Optimizing Windows 11 Load with Smart Media Management
excerpt: This Article Describes Optimizing Windows 11 Load with Smart Media Management
keywords: WinLoadBoost,OptiWin11,MediaSmartWin,FastLoadWin11,MediaOptimizeWin,SmartMediaWin11,EfficientWindows11
thumbnail: https://thmb.techidaily.com/8761d7ab814205b2f88e7841689a57f834d49b25e2e76dad4d19bc3d0f2882d9.jpg
---

## Optimizing Windows 11 Load with Smart Media Management

 News and Interests is a Windows 11 and 10 widget on your taskbar to show weather, sports, and news events at a glance. While it seems like a harmlessly unwanted feature, it can sometimes cause high memory usage on your computer.

 This News and Interests issue occurs due to a potential memory leak and can make your computer run slow. So, if you want to make your computer run fast again, follow these steps to fix the News and Interests high memory usage problem.

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880927/19272" target="_top" id="1880927">
  <img src="//a.impactradius-go.com/display-ad/19272-1880927" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880927/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557747/17382" target="_top" id="1557747">
  <img src="//a.impactradius-go.com/display-ad/17382-1557747" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557747/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123728/7443" target="_top" id="2123728">
  <img src="//a.impactradius-go.com/display-ad/7443-2123728" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123728/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Close the Registry Editor and restart your computer to apply the changes.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137222/26400" target="_top" id="2137222">
  <img src="//a.impactradius-go.com/display-ad/26400-2137222" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137222/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Add and Disable EnableFeeds Using PowerShell

![powershell add registry key value Windows feeds Enable feeds](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/powershell-add-registry-key-value-windows-feeds-enable-feeds.jpg)

 You can also add and modify the EnableFeeds value in the Windows Registry using PowerShell. To do this:

1. Press the**Win** key and type**powershell** .
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell terminal, copy and paste the following entry and press Enter:  
`REG ADD "HKLM\SOFTWARE\Policies\Microsoft\Windows\Windows Feeds" /v "EnableFeeds" /t REG_DWORD /d 0 /f`
4. The above command will create a new**Windows Feeds** subkey and contain the value**EnableFeeds** set to disabled.
5. If there are no errors, type**exit** and press**Enter** to close PowerShell. Restart your Computer and check for any improvements.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134221/18498" target="_top" id="2134221">
  <img src="//a.impactradius-go.com/display-ad/18498-2134221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134221/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://eaxpv-info.techidaily.com/new-from-idea-to-execution-creating-youtube-trailers-in-filmora-for-2024/"><u>[New] From Idea to Execution Creating YouTube Trailers in Filmora for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-unlocking-fullscreen-potential-in-adobe-premiere-for-2024/"><u>[New] Unlocking Fullscreen Potential in Adobe Premiere for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-affordable-video-capture-maximum-potential-via-obs/"><u>[Updated] Affordable Video Capture - Maximum Potential via OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-exception-breakpoint-reached-message-on-pcs/"><u>Correcting Exception Breakpoint Reached Message on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-extend-volume-functionality-in-diskmgmt/"><u>Enhance Extend Volume Functionality in DiskMgmt</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-bring-your-camera-life-into-your-instagram-world/"><u>In 2024, Bring Your Camera Life Into Your Instagram World</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-f14-5g-phone-with-broken-screen-by-drfone-android/"><u>In 2024, How to Unlock Samsung Galaxy F14 5G Phone with Broken Screen</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-stream-wars-unveiled-which-wins-obs-or-twitch/"><u>In 2024, Stream Wars Unveiled Which Wins, OBS or Twitch?</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/is-the-hp-omen-obelisk-your-ideal-gaming-machine-insights-from-our-in-depth-review/"><u>Is the HP OMEN Obelisk Your Ideal Gaming Machine? Insights From Our In-Depth Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/old-video-resurrection-mastering-madvr-techniques-windows-style/"><u>Old Video Resurrection: Mastering MadVR Techniques, Windows Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-server-related-errors-in-microsoft-store-windows-1111-edition/"><u>Overcoming Server-Related Errors in Microsoft Store, Windows 11/11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfect-text-adjustments-with-ease-the-modern-windows-11s-snipt-guide/"><u>Perfect Text Adjustments with Ease: The Modern Windows 11'S Snipt Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-your-w11-device-with-google-play/"><u>Setting Up Your W11 Device with Google Play</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-simple-reverting-windows-11-user-privileges/"><u>Steps to Simple: Reverting Windows 11 User Privileges</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trimmed-tamed-files-adopt-compact-display-in-windows-11/"><u>Trimmed, Tamed Files: Adopt Compact Display in Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/ultimate-guide-15-great-online-photo-editing-tools-2023-free/"><u>Ultimate Guide 15 Great Online Photo Editing Tools 2023 (Free)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-11s-proxy-settings-path/"><u>Unveiling Windows 11'S Proxy Settings Path</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-free-and-fabulous-20-adobe-premiere-intro-templates/"><u>Updated In 2024, Free and Fabulous 20 Adobe Premiere Intro Templates</u></a></li>
<li><a href="https://ai-topics.techidaily.com/updated-what-is-an-ai-artist/"><u>Updated What Is an AI Artist?</u></a></li>
</ul></div>

