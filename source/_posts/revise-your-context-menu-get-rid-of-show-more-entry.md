---
title: "Revise Your Context Menu: Get Rid of Show More Entry"
date: 2024-12-22T20:33:37.394Z
updated: 2024-12-27T20:04:39.260Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Revise Your Context Menu: Get Rid of Show More Entry"
excerpt: "This Article Describes Revise Your Context Menu: Get Rid of Show More Entry"
keywords: Context Menu Trim,Hide Show More,Menubar Cleanup,Reduce Menu Size,Conciseness Tips,Minimize Menu,Simplify Menu Entry
thumbnail: https://thmb.techidaily.com/b1dd8faa0beaf2c68ee22b112a11d419910d65751f8e67cea228594ebc93d2a9.jpg
---

## Revise Your Context Menu: Get Rid of Show More Entry

 Windows 11 comes with a fresh new look and has mainly got a positive response for its new interface. However, there are a couple of features that are not being welcomed by the users. For instance, the addition of the "show more options" entry to the right-click context menu.

 Although it was introduced to simplify things, many users still prefer the old context menu from Windows 10\. Fortunately, you can remove Show more options from the context menu on Windows 11 by following the below methods.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaGNHfAT92w?si=bvHo1iYK2JBIPtRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## 4\. Remove the "Show More Options" Entry From the Context Menu Using Winaero Tweaker

 There are plenty of third-party tools using which you can customize the look of your Windows 11 computer. For this guide, we will use Winaero Tweaker.

 Here's how to download Winaero Tweaker and use it to remove the "show more options" entry from the context menu:

1. Download the[Winaero Tweaker zip file](https://winaero.com/downloads/winaerotweaker.zip) on your computer.
2. Unzip the file, open the executable, and then follow the on-screen instructions to install it on your computer.
3. Launch Winaero Tweaker and choose the**Classic Full Context Menus** option from the left sidebar.  
![Classic Full Context Menus option of Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/classic-full-context-menus-option.jpg)
4. Check the**Enable classic full context menus** box.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable classic full context menus option in Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-classic-full-context-menus.jpg)
5. Click the**Restart Explorer** button that appears.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-video-files.techidaily.com/new-making-mp3-from-instagram-visual-content-for-2024/"><u>[New] Making MP3 From Instagram Visual Content for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-brand-your-content-download-complimentary-templates-for-youtube-makers/"><u>[Updated] Brand Your Content Download Complimentary Templates for YouTube Makers</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-reviving-past-joy-on-fb-the-look-back-video-editing-path-for-2024/"><u>[Updated] Reviving Past Joy on FB The Look Back Video Editing Path for 2024</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/comprehensive-review-petsafes-innovative-automatic-pet-food-dispenser-ensuring-healthy-weight-in-pets/"><u>Comprehensive Review: PetSafe's Innovative Automatic Pet Food Dispenser Ensuring Healthy Weight in Pets</u></a></li>
<li><a href="https://win-solutions.techidaily.com/defeat-the-blue-screen-curse-in-helldivers-2-with-these-fixes/"><u>Defeat the Blue Screen Curse in Helldivers 2 with These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/digital-camouflage-burying-archives-in-images-for-win-users/"><u>Digital Camouflage: Burying Archives in Images for WIN Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-active-printer-service-errors-in-windows/"><u>Fixing Non-Active Printer Service Errors in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reset-all-user-permissions-to-default-in-windows-11/"><u>How to Reset All User Permissions to Default in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improving-copypaste-action-reliability-in-windows-11/"><u>Improving Copy/Paste Action Reliability in Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-itel-p55t-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Itel P55T? | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/install-newest-tp-link-ub400-usb-bluetooth-adapter-software/"><u>Install Newest TP-Link UB400 USB Bluetooth Adapter Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-5-best-free-driver-updaters-for-windows/"><u>The 5 Best Free Driver Updaters for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-resolve-severe-js-failure-issues-within-discord-specifically-for-win-oses/"><u>Tips to Resolve Severe JS Failure Issues Within Discord, Specifically for Win OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-hypervisor-blue-screen-in-windows/"><u>Troubleshoot Hypervisor Blue Screen in Windows</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-techniques-for-tackling-and-correcting-stop-code-0x0000003d-issues/"><u>Troubleshooting Techniques for Tackling and Correcting STOP Code 0X0000003D Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-unresponsive-gamepad-on-windows/"><u>Troubleshooting Unresponsive Gamepad on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207576089-uncover-your-missing-wi-fi-adapter-choices-in-windows-11-now-solved/"><u>Uncover Your Missing Wi-Fi Adapter Choices in Windows 11 - Now Solved!</u></a></li>
</ul></div>

