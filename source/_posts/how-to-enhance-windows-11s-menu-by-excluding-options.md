---
title: How to Enhance Windows 11'S Menu by Excluding Options
date: 2024-10-07T22:11:21.341Z
updated: 2024-10-14T16:41:02.530Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Enhance Windows 11'S Menu by Excluding Options
excerpt: This Article Describes How to Enhance Windows 11'S Menu by Excluding Options
keywords: Win11 Menu Optimize,Exclude WinMenu Items,Streamline Win11 UI,Reduce WinMenu Clutter,Tidy Up Windows Menu,Minimize WinUI Elements,Simplify Win11 Interface
thumbnail: https://thmb.techidaily.com/50d4bf6106cc2e789648c53429943f049229011e6f572fe9945c7d91985d72b7.jpg
---

## How to Enhance Windows 11'S Menu by Excluding Options

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137393/7443" target="_top" id="2137393">
  <img src="//a.impactradius-go.com/display-ad/7443-2137393" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137393/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://dhgate.sjv.io/c/5597632/1172027/12108" target="_top" id="1172027">
  <img src="//a.impactradius-go.com/display-ad/12108-1172027" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1172027/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Enable classic full context menus option in Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-classic-full-context-menus.jpg)
5. Click the**Restart Explorer** button that appears.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135360/19272" target="_top" id="2135360">
  <img src="//a.impactradius-go.com/display-ad/19272-2135360" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135360/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2044586/7443" target="_top" id="2044586">
  <img src="//a.impactradius-go.com/display-ad/7443-2044586" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044586/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-data.techidaily.com/approved-mastering-background-replacement-get-cost-free-lessons-in-green-screen-effects-from-youtubes-best/"><u>2024 Approved Mastering Background Replacement Get Cost-Free Lessons in Green Screen Effects From YouTube's Best</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/addressing-hearing-gaps-in-video-content-sharing/"><u>Addressing Hearing Gaps in Video Content Sharing</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-undelete-lost-call-logs-from-oppo-find-n3-by-fonelab-android-recover-call-logs/"><u>Best Android Data Recovery - undelete lost call logs from Oppo Find N3</u></a></li>
<li><a href="https://media-tips.techidaily.com/erfahren-sie-wie-sie-mit-dieser-anleitung-windows-11-computer-zu-einem-einfachen-dlna-streaming-server-machen-konnen/"><u>Erfahren Sie Wie Sie Mit Dieser Anleitung Windows 11 Computer Zu Einem Einfachen DLNA Streaming Server Machen Können</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-defective-gestures-in-microsofts-os/"><u>Fixing Defective Gestures in Microsoft's OS</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/guffaw-glory-top-downloads-of-jingles-for-2024/"><u>Guffaw Glory Top Downloads of Jingles for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-video-lag-in-vlc-media-player-on-windows/"><u>How to Fix Video Lag in VLC Media Player on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-repair-image-id-0x80780119-on-windows-os/"><u>How To Repair Image ID: 0X80780119 on Windows OS</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-vivo-y100-5g-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Vivo Y100 5G FRP Android 10/11/12/13</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-remove-device-supervision-from-your-iphone-xs-by-drfone-ios/"><u>In 2024, Remove Device Supervision From your iPhone XS</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/install-logitech-brio-hd-camera-drivers-on-windows-11-complete-guide-and-links/"><u>Install Logitech BRIO HD Camera Drivers on Windows 11: Complete Guide and Links</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reworking-records-6-windows-applications-for-date-revision/"><u>Reworking Records: 6 Windows Applications for Date Revision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/selective-vmm-recommendations-for-windows-11-success/"><u>Selective VMM Recommendations for Windows 11 Success</u></a></li>
<li><a href="https://discover-dash.techidaily.com/step-by-step-tutorial-for-screen-recording-and-voice-inputs-on-windows-8/"><u>Step-by-Step Tutorial for Screen Recording and Voice Inputs on Windows 8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-solve-systemsettings-issue-on-win11/"><u>Strategies to Solve SystemSettings Issue on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-woes-8-strategies-for-neutralizing-pink-displays/"><u>Windows Woes: 8 Strategies for Neutralizing Pink Displays</u></a></li>
</ul></div>

