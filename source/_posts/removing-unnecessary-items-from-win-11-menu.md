---
title: Removing Unnecessary Items From Win 11 Menu
date: 2024-09-11T08:51:08.652Z
updated: 2024-09-17T08:31:52.466Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Removing Unnecessary Items From Win 11 Menu
excerpt: This Article Describes Removing Unnecessary Items From Win 11 Menu
keywords: Win 11 Cleanup Guide,Remove Win 11 Clutter,Streamline Windows 11 Menu,Simplify Win 11 Interface,Tidy Up Windows 11,Optimize Win 11 Tools,Declutter Windows 11 Settings
thumbnail: https://thmb.techidaily.com/e35da50e74d4ad42a2d4ca6cbb01ed721572402298c4b208ceac1efbbaaf58d4.png
---

## Removing Unnecessary Items From Win 11 Menu

 Windows 11 comes with a fresh new look and has mainly got a positive response for its new interface. However, there are a couple of features that are not being welcomed by the users. For instance, the addition of the "show more options" entry to the right-click context menu.

 Although it was introduced to simplify things, many users still prefer the old context menu from Windows 10\. Fortunately, you can remove Show more options from the context menu on Windows 11 by following the below methods.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Remove "Show More Options" From the Context Menu With Folder Options

 The[Windows Folder Options](https://www.makeuseof.com/windows-folder-options-guide/) in File Explorer is the go-to place to view and manage File Explorer settings. You can use it to[enable compact view in File Explorer on Windows 11](https://www.makeuseof.com/how-to-enable-compact-view-windows-11-file-explorer/) , manage file thumbnails, remove the "show more options" entry, and much more.

 Here's how to use the folder option to remove the "show more options" entry from the context menu:

1. Press the**Win + E** hotkey to open the**File Explorer.**
2. Click the three horizontal dots at the top bar and choose**Options.**
3. In the**Folder Options,** switch to the**View** tab.
4. Check the**Launch folder** **windows in a separate process** box.  
![Launch folder windows in a separate process box in the Folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/launch-folder-windows-in-a-separate-process-box.jpg)
5. Click**Apply** \>**OK** to save the changes.

Next, restart your computer for the changes to take effect.

## 2\. Remove Show More Options From the Context Menu Using the Command Prompt

 If you're a power user, you can use Command Prompt to remove the "show more options" entry from the context menu. Here's how:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane.
3. Click**Yes** to the UAC that crops up.
4. In the elevated Command Prompt window, type the following command and press**Enter** :  
`reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve`

![Command to Remove Context menu in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-to-remove-context-menu.jpg)

 After executing the command, you'll see the "The operation completed successfully" message to confirm that it went through.

 Now, you will have to restart Windows Explorer to see the changes. To do that, open the**Task Manager** (see how to[launch the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) ), right-click on**Windows Explorer,** and choose**Restart.**

 Check if you can see the changes. If not, then you will have to restart your computer for the changes to take effect.

 In the future, if you want to add the "show more options" entry to the context menu, then open Command Prompt with admin rights and run the following command:

`reg delete "HKEY_CURRENT_USER\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f​`

## 3\. Remove Show More Options From the Context Menu Using the Registry Editor

 Another quick way to remove the "show more options" entry is through the Registry Editor. Here's what you need to do:

 Before making any changes to the registry, ensure you've[created a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) or[back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . This will ensure your system settings and files are secure, and you can quickly access them if something goes wrong.

1. Open the Start Menu, type**Registry Editor** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID`
3. Right-click on the empty space on the right pane, click**New,** and then select**DWORD** **(32-bit) Value** from the context menu.
4. Name the value as**"UndockingDisabled"** and press**Enter** .  
![UndockingDisabled entry in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/undockingdisabled-entry.jpg)
5. Double-click on the UndockingDisabled key, type**1** in the**Value data,** and click**OK** to save the changes.  
![Editing UndockingDisabled in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-undockingdisabled.jpg)

## 4\. Remove the "Show More Options" Entry From the Context Menu Using Winaero Tweaker

 There are plenty of third-party tools using which you can customize the look of your Windows 11 computer. For this guide, we will use Winaero Tweaker.

 Here's how to download Winaero Tweaker and use it to remove the "show more options" entry from the context menu:

1. Download the[Winaero Tweaker zip file](https://winaero.com/downloads/winaerotweaker.zip) on your computer.
2. Unzip the file, open the executable, and then follow the on-screen instructions to install it on your computer.
3. Launch Winaero Tweaker and choose the**Classic Full Context Menus** option from the left sidebar.  
![Classic Full Context Menus option of Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/classic-full-context-menus-option.jpg)
4. Check the**Enable classic full context menus** box.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137412/7443" target="_top" id="2137412">
  <img src="//a.impactradius-go.com/display-ad/7443-2137412" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137412/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Enable classic full context menus option in Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-classic-full-context-menus.jpg)
5. Click the**Restart Explorer** button that appears.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115918/19272" target="_top" id="2115918">
  <img src="//a.impactradius-go.com/display-ad/19272-2115918" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115918/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Enjoy an Old School Context Menu on Windows 11

 The desktop context menu lets you quickly access areas like the personalization menu, display settings, and much more. In Windows 11, you get the new "Show more options" entry in the context menu. But if you prefer the old design, you can quickly disable the "Show more options" entry from the context using either of the above methods.

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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-easy-techniques-perfect-your-idevice-screen-shots/"><u>[New] 2024 Approved Easy Techniques Perfect Your iDevice Screen Shots</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-audio-harmony-seekers-perfecting-video-moods/"><u>2024 Approved Audio Harmony Seekers Perfecting Video Moods</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-update-hp-officejet-pro-8720-drivers-latest-version-guide-for-pc-users/"><u>Download & Update HP OfficeJet Pro 8720 Drivers: Latest Version Guide for PC Users</u></a></li>
<li><a href="https://fox-info.techidaily.com/edit-like-a-pro-with-top-android-apps/"><u>Edit Like a Pro with Top Android Apps</u></a></li>
<li><a href="https://vp-tips.techidaily.com/executive-challenges-in-navigating-digital-shifts-c-suite-faces-25x-higher-disruption-levels-reveals-abbyy-research/"><u>Executive Challenges in Navigating Digital Shifts: C-Suite Faces 2.5X Higher Disruption Levels, Reveals ABBYY Research</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-nubia-red-magic-9-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Nubia Red Magic 9 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disable-conversational-ai-on-win11/"><u>How to Disable Conversational AI on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-failed-to-run-task-sequence-error-0x8007000f-in-windows/"><u>How to Fix the Failed to Run Task Sequence Error 0X8007000f in Windows</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-exploring-top-20-anime-opener-hits/"><u>In 2024, Exploring Top 20 Anime Opener Hits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-size-limits-a-win11-guide-to-overcoming-stuck-on-size-error-in-discord/"><u>Mastery over Size Limits: A Win11 Guide to Overcoming Stuck-On-Size Error in Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-windows-hiccups-with-top-4-pct-solutions/"><u>Navigate Windows' Hiccups with Top 4 PCT Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-server-woes-no-more-12-solutions-for-pc-apex-users-(156-chars/"><u>No-Server Woes, No More! 12 Solutions for PC Apex Users (<156 Chars)</u></a></li>
<li><a href="https://extra-resources.techidaily.com/pioneering-creations-cutting-edge-tips-for-gifs/"><u>Pioneering Creations Cutting-Edge Tips for GIFs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sly-startup-settings-concealing-the-shutdown-option/"><u>Sly Startup Settings: Concealing the Shutdown Option</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-4-twitter-apps-for-efficiently-tracking-trending-hashtags/"><u>Top 4 Twitter Apps for Efficiently Tracking Trending Hashtags</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-potential-of-past-play-retroarch-for-enhanced-gaming-achievements/"><u>Unlock Potential of Past Play: Retroarch for Enhanced Gaming Achievements</u></a></li>
</ul></div>

