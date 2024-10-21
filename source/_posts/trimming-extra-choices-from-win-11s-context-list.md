---
title: Trimming Extra Choices From Win 11'S Context List
date: 2024-10-16T19:32:13.648Z
updated: 2024-10-20T17:23:42.305Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Trimming Extra Choices From Win 11'S Context List
excerpt: This Article Describes Trimming Extra Choices From Win 11'S Context List
keywords: Win11ContextListTrim,Win11ChoicesReduce,RemoveWin11Options,Win11ContextCleanup,ExtractWin11Data,CutWin11ListItems,EditWin11ContextMenu
thumbnail: https://thmb.techidaily.com/f3acba4ab3a16a6eb071b7ad05fb5dc6bcda3ad9bf54bc2e5b6e949de6c9c500.jpg
---

## Trimming Extra Choices From Win 11'S Context List

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151858/7443" target="_top" id="2151858">
  <img src="//a.impactradius-go.com/display-ad/7443-2151858" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151858/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://laganoo.pxf.io/c/5597632/1484945/16446" target="_top" id="1484945">
  <img src="//a.impactradius-go.com/display-ad/16446-1484945" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484945/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://unicoeye.pxf.io/c/5597632/2134229/18498" target="_top" id="2134229">
  <img src="//a.impactradius-go.com/display-ad/18498-2134229" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134229/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Enable classic full context menus option in Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-classic-full-context-menus.jpg)
5. Click the**Restart Explorer** button that appears.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135419/19272" target="_top" id="2135419">
  <img src="//a.impactradius-go.com/display-ad/19272-2135419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135419/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-helps.techidaily.com/new-navigate-high-speed-stories-on-instagram-effectively/"><u>[New] Navigate High-Speed Stories on Instagram Effectively</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-tweaking-image-previews-for-youtube-like-experience-in-twitter-videos/"><u>[Updated] 2024 Approved Tweaking Image Previews for YouTube-Like Experience in Twitter Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/coordinating-devices-in-power-save-windows-states/"><u>Coordinating Devices in Power-Save Windows States</u></a></li>
<li><a href="https://win11-tips.techidaily.com/corrective-measures-for-virtual-disks-not-starting/"><u>Corrective Measures for Virtual Disks Not Starting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-windows-media-storage-hurdles/"><u>Demystifying Windows Media Storage Hurdles</u></a></li>
<li><a href="https://buynow-info.techidaily.com/guide-to-conserve-preview-pics-within-microsoft-word-projects/"><u>Guide to Conserve Preview Pics Within Microsoft Word Projects</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-tecno-camon-20-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-revive-blackened-webcam-on-windows-os/"><u>How to Revive Blackened Webcam on Windows OS</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-xiaomi-redmi-note-12r-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Xiaomi Redmi Note 12R to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-do-i-stop-someone-from-tracking-my-zte-blade-a73-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Do I Stop Someone From Tracking My ZTE Blade A73 5G? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-fix-apple-iphone-12-pro-could-not-be-activatedreached-issue-by-drfone-ios/"><u>In 2024, How To Fix Apple iPhone 12 Pro Could Not Be Activated/Reached Issue</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/oming-obscured-viewing-fix-for-youtube-for-2024/"><u>Overcoming Obscured Viewing Fix for Youtube for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-approach-to-discerning-hard-drive-from-solid-state-drive-in-windows/"><u>Streamlined Approach to Discerning Hard Drive From Solid State Drive in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-1011-updates-eliminate-x080246007/"><u>Streamlining Windows 10/11 Updates: Eliminate X080246007</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-on-overcoming-installation-hurdles-in-windows-os/"><u>Tips on Overcoming Installation Hurdles in Windows OS</u></a></li>
</ul></div>

