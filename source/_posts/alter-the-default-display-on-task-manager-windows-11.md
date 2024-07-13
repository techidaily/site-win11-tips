---
title: Alter the Default Display on Task Manager (Windows 11)
date: 2024-07-12T18:07:50.727Z
updated: 2024-07-13T18:07:50.727Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Alter the Default Display on Task Manager (Windows 11)
excerpt: This Article Describes Alter the Default Display on Task Manager (Windows 11)
keywords: Windows Task Manager Customize View,Change Task Manager Display,Alter Task Manager Layout,Task Manager Settings Edit,Adjust Windows 11 TaskView,Customize TaskManager Appearance,Rearrange Task Manager Icons
thumbnail: https://thmb.techidaily.com/669bc1413d235f8908afbf69f357ad5578fda1c3066e7cdb610eb41a93c8a8ff.jpeg
---

## Alter the Default Display on Task Manager (Windows 11)

 The Task Manager provides a quick overview of your system's current status and shows essential information. Its Start page displays useful details such as currently running background processes, applications, CPU, and memory utilization. If you'd like to customize its appearance, change the Start page. In this article, we’ll look at how to change the Task Manager Start page in Windows 11\.

## 1\. Use Task Manager Settings

 If you want to quickly change the Task Manager Start page, you can use its Settings tab. This option requires no modification to the registry editor or additional scripts to run.

 To change the Task Manager Start page using Task Manager settings, do the following.

1. Press **Win + R** to open the Run dialog box.
2. Type **taskmgr** and press **Enter** to launch Task Manager.
3. Once in Task Manager, click on **Settings** (the gear icon).
4. You'll see a **Default Start Page** drop-down menu at the top. This is where you can select the page to display when Task Manager opens.  
![Use Settings to Change Task Manager Start Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-settings-to-change-task-manager-start-page.jpg)

 The options available are the following:

1. Processes
2. Performance
3. App history
4. Startup apps
5. Users
6. Details
7. Services ​​​​

 Once you make a selection, Task Manager will remember the setting and open the page you chose from now on.

## 2\. Tweak the Registry Editor

 The Registry Editor is another way to change the default Start page for Task Manager. The procedure is slightly more complex than using Task Manager Settings, but it offers more customization options. Be careful when modifying entries in the Registry Editor, as incorrect changes can cause errors or system instability. To avoid losing data, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To change the Task Manager Start page using the Registry Editor, follow these steps.

1. [Open the Registry Editor window](https://www.makeuseof.com/windows-11-open-registry-editor/).
2. If the UAC prompt pops up, click **Yes** to grant administrative rights.
3. In the left pane, navigate to the following key.  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\TaskManager`
4. Double-click **StartUpTab** in the right pane. If there is no such entry, then right-click on the Task Manager key.
5. From the context menu, select **New > DWORD (32-bit) Value**.
6. Now name the value **StartUpTab** and double-click on it.  
![Modify Registry to Change Task Manager Start Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modify-registry-to-change-task-manager-start-page.jpg)
7. Set its **Value data** to one of the following numbers to change the default start page:  
`0 = Processes  

1 = Performance  

2 = App history  

3 = Startup apps  

4 = Users  

5 = Details  

6 = Services`
8. Click **OK** to save the changes and close the Registry Editor window.

 Next time you open Task Manager, it will display a page according to your preferences.

## 3\. Use a REG File

 If the registry editor isn't your thing, you can use a REG file to modify the Task Manager start page. The process does not require registry tweaking and is straightforward.

 To create a .reg file, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and type the following:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\TaskManager]  
  
"StartUpTab"=dword:00000000`

 Here, the last digit reflects the type of Start page.

 For example, if you want to set **Processes** as your default start page, use **0** (**00000000**). Similarly, if you want the **Details** page to display as default, set it to **5** (**00000005**).

 The other options are:

`00000001 - Performance  
  
00000002 - App history  
  
00000003 - Startup apps  
  
00000004 - Users  
  
00000006 - Services`

 Now, click **File** and select **Save as**. In the Save as dialog box, click the Save as type drop-down menu and select **All files**. Name the file with the **.reg** extension. For example, **TaskManagerStartPage.reg**.

![Use a REG File to Change Task Manager Start Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-a-reg-file-to-change-task-manager-start-page.jpg)

 Next, select **Desktop** from the left pane and click **Save**. Once saved, double-click on this newly created REG file. This adds the required details to the Registry Editor and changes the Task Manager start page.

 If you ever want to revert the changes, delete the REG file and restart your computer.

## Changing the Task Manager Start Page on Windows

 It’s easy to customize Task Manager and change its Start page according to your preference. You can use Task Manager Settings, the Registry Editor, or a REG file to set the desired page. Once you have set the Start page, Task Manager will remember it and open that page when you launch it.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-quick-fixes-for-missing-sound-in-obs-for-2024/"><u>[New] Quick Fixes for Missing Sound in OBS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-startup-efficiency-altering-boot-menu-delay/"><u>Boosting Startup Efficiency: Altering Boot Menu Delay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-with-these-12-unneeded-windows-programs/"><u>Boost Performance with These 12 Unneeded Windows Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-windows-11s-default-silent-camera-alert-setting/"><u>Altering Windows 11'S Default Silent Camera Alert Setting</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/what-is-filmora-certified-creative-program-and-how-to-become-an-fcc-in-2024/"><u>What Is Filmora Certified Creative Program and How to Become an FCC, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-cortana-microsofts-four-future-plans/"><u>Beyond Cortana: Microsoft's Four Future Plans</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitlocker-free-windows-4-effective-security-measures/"><u>BitLocker-Free Windows: 4 Effective Security Measures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alternative-techniques-to-initiate-software-on-a-windows-machine/"><u>Alternative Techniques to Initiate Software on a Windows Machine</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-nokia-130-music-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Transfer Music from Nokia 130 Music to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/harnessing-the-power-of-youtubes-seo-keywords/"><u>Harnessing the Power of YouTube's SEO Keywords</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/forgot-locked-iphone-15-pro-password-learn-the-best-methods-to-unlock-by-drfone-ios/"><u>Forgot Locked iPhone 15 Pro Password? Learn the Best Methods To Unlock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-the-blues-swift-remedies-to-hypervisor-bsos-in-winxose/"><u>Beat the Blues: Swift Remedies to Hypervisor BSOS in WINXOSE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-teamsters-crashes-on-windows-11-10/"><u>Avoiding Teamsters Crashes on Windows 11, 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-minipc-size-upgrade-speed-downgrade/"><u>Blackview MiniPC: Size Upgrade, Speed Downgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-output-the-best-apps-to-maximize-windows-efficiency/"><u>Boost Your Output: The Best Apps to Maximize Windows Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-file-management-in-windows-11/"><u>Boosting File Management in Windows 11</u></a></li>
<li><a href="https://youtube-web.techidaily.com/egizing-for-success-the-essential-guide-to-online-individuality-for-2024/"><u>Strategizing for Success  The Essential Guide to Online Individuality for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-buffer-rates-to-minimize-lag-with-vlc/"><u>Adjusting Buffer Rates to Minimize Lag with VLC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-system-insights-with-resource-tracking-tiles/"><u>Boost System Insights with Resource Tracking Tiles</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-how-to-get-verified-on-instagram-6-tips-to-grow-followers/"><u>In 2024, How to Get Verified on Instagram  6 Tips to Grow Followers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augmenting-desktop-interactivity-the-widget-approach-in-win-11/"><u>Augmenting Desktop Interactivity: The Widget Approach in Win 11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-free-online-video-editors-with-music-and-effects/"><u>New 2024 Approved Free Online Video Editors with Music and Effects</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-following-review-innovative-outlooks/"><u>2024 Approved  Following Review  Innovative Outlooks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-the-past-erasing-defenders-track-of-security-efforts/"><u>Banish the Past: Erasing Defender’s Track of Security Efforts</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-elevate-your-content-top-rated-cameras-for-youtubers/"><u>[New] In 2024, Elevate Your Content  Top-Rated Cameras for YouTubers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-visual-capture-mastery-snipping-tools-latest-recording-features-explained-max-156/"><u>Audio-Visual Capture Mastery: Snipping Tool's Latest Recording Features Explained (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-the-media-playback-windows-media-player/"><u>Beginning the Media Playback: Windows Media Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-the-basics-excellent-replacements-for-windows-11-defaults/"><u>Beyond the Basics: Excellent Replacements for Windows 11 Defaults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-taskbar-performance-on-win11/"><u>Boosting Taskbar Performance on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/battle-bugs-tackling-skyrims-extension-failure/"><u>Battle Bugs: Tackling Skyrim's Extension Failure</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unveiling-the-secrets-of-iphone-podcast-integration/"><u>[Updated] Unveiling the Secrets of iPhone Podcast Integration</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-the-ultimate-list-of-top-tier-facebook-profile-picture-designers/"><u>[Updated] 2024 Approved  The Ultimate List of Top-Tier Facebook Profile Picture Designers</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>