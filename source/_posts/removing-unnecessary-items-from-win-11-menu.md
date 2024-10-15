---
title: Removing Unnecessary Items From Win 11 Menu
date: 2024-10-08T23:17:07.540Z
updated: 2024-10-15T10:34:33.398Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918679/19272" target="_top" id="1918679">
  <img src="//a.impactradius-go.com/display-ad/19272-1918679" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918679/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Remove Show More Options From the Context Menu Using the Command Prompt

 If you're a power user, you can use Command Prompt to remove the "show more options" entry from the context menu. Here's how:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane.
3. Click**Yes** to the UAC that crops up.
4. In the elevated Command Prompt window, type the following command and press**Enter** :  
`reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve`

![Command to Remove Context menu in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-to-remove-context-menu.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425">
  <img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<span id="1982485">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982485.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982485">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982485.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982485%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982485/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Remove the "Show More Options" Entry From the Context Menu Using Winaero Tweaker

 There are plenty of third-party tools using which you can customize the look of your Windows 11 computer. For this guide, we will use Winaero Tweaker.

 Here's how to download Winaero Tweaker and use it to remove the "show more options" entry from the context menu:

1. Download the[Winaero Tweaker zip file](https://winaero.com/downloads/winaerotweaker.zip) on your computer.
2. Unzip the file, open the executable, and then follow the on-screen instructions to install it on your computer.
3. Launch Winaero Tweaker and choose the**Classic Full Context Menus** option from the left sidebar.  
![Classic Full Context Menus option of Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/classic-full-context-menus-option.jpg)
4. Check the**Enable classic full context menus** box.  

![Enable classic full context menus option in Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-classic-full-context-menus.jpg)
5. Click the**Restart Explorer** button that appears.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137229/26400" target="_top" id="2137229">
  <img src="//a.impactradius-go.com/display-ad/26400-2137229" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137229/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://discover-comparisons.techidaily.com/deshacerte-de-documentos-importantes-sin-querer-recupere-sus-archivos-urgentemente-ahora-mismo/"><u>¡Deshacerte De Documentos Importantes Sin Querer? ¡Recupere Sus Archivos Urgentemente Ahora Mismo!</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-the-complete-guide-to-selecting-high-performance-fpv-drone-propellers/"><u>[New] The Complete Guide to Selecting High-Performance FPV Drone Propellers</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-revolutionize-your-intellect-with-these-15-yt-channels/"><u>[Updated] 2024 Approved Revolutionize Your Intellect with These 15 YT Channels</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-game-capture-software-rivalry-obs-vs-shadowplay/"><u>[Updated] In 2024, Game Capture Software Rivalry OBS Vs. ShadowPlay</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1-superior-wmv-merger-ultimate-guide-to-fusing-various-wmv-videos-into-a-single-file/"><u>1. Superior WMV Merger: Ultimate Guide to Fusing Various WMV Videos Into a Single File</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/a-complete-rundown-on-excellent-screen-recording-of-facetime-calls/"><u>A Complete Rundown on Excellent Screen-Recording of FaceTime Calls</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-latest-dell-wireless-network-drivers-for-windows-7-systems/"><u>Download Latest Dell Wireless Network Drivers for Windows 7 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-set-up-permadelete-features-using-customizable-windows-11-and-11-trash/"><u>How to Set Up PermaDelete Features Using Customizable Windows 11 & 11 Trash</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-with-location-spoofer-on-nubia-red-magic-9-proplus-drfone-by-drfone-virtual-android/"><u>How To Simulate GPS Movement With Location Spoofer On Nubia Red Magic 9 Pro+? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-non-functional-resource-monitor-apps-on-win11/"><u>How to Tackle Non-Functional Resource Monitor Apps on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-directory-restarts-for-distro-and-catroot2-in-ws11/"><u>Navigating Directory Restarts for Distro & Catroot2 in WS11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-fn-button-actions-in-windows-11/"><u>Personalizing FN Button Actions in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pinpointing-and-ameliorating-unilateral-windows-audio-glitches/"><u>Pinpointing and Ameliorating Unilateral Windows Audio Glitches</u></a></li>
<li><a href="https://driver-install.techidaily.com/realign-correcting-hp-laserjet-pro-400-windows-drivers/"><u>Realign: Correcting HP LaserJet Pro 400 Windows Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-adjustments-for-enhanced-devices-with-windows-11/"><u>Streamlined Adjustments for Enhanced Devices with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stylish-practicality-asus-vivobook-s-15s-perfect-fusion/"><u>Stylish Practicality - ASUS Vivobook S 15'S Perfect Fusion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-11s-power-saving-features-for-swift-wake-up-times/"><u>Unveiling Windows 11'S Power-Saving Features for Swift Wake-Up Times</u></a></li>
</ul></div>

