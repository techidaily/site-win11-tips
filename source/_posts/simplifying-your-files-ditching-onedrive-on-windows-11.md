---
title: "Simplifying Your Files: Ditching OneDrive on Windows 11"
date: 2024-10-27T18:56:56.197Z
updated: 2024-11-01T18:04:30.503Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Simplifying Your Files: Ditching OneDrive on Windows 11"
excerpt: "This Article Describes Simplifying Your Files: Ditching OneDrive on Windows 11"
keywords: File Simplicity Windows,Drop OneDrive Windows,Opt Out Windows 11,Discard OneDrive Files,Easy Windows File Management,Ditching Cloud Storage,Win11 File Centralization
thumbnail: https://thmb.techidaily.com/f7696c4ac1037e72f31c6b328a12ea085bd4635182093dadda40d9b14071da58.jpg
---

## Simplifying Your Files: Ditching OneDrive on Windows 11

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on[removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you[create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  
![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139108/17108" target="_top" id="2139108">
  <img src="//a.impactradius-go.com/display-ad/17108-2139108" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139108/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484909/16446" target="_top" id="1484909">
  <img src="//a.impactradius-go.com/display-ad/16446-1484909" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484909/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2145009/26400" target="_top" id="2145009">
  <img src="//a.impactradius-go.com/display-ad/26400-2145009" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2145009/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Remove OneDrive Icon Without Uninstalling OneDrive

 This registry hack is a handy way to make the OneDrive icon disappear without deleting the app entirely from your PC. Alternatively, if you don’t use the service, you can completely remove OneDrive on Windows 11 or disable the service using Group Policy Editor.

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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-audio-capture-for-post-review/"><u>[New] 2024 Approved Audio Capture for Post-Review</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-revolutionary-process-to-blend-gopro-videos-into-360-degree-panoramas/"><u>[New] In 2024, Revolutionary Process to Blend GoPro Videos Into 360-Degree Panoramas</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-peeling-back-the-layers-of-visual-past-a-guide-to-fb-image-searching-reversed-for-2024/"><u>[Updated] Peeling Back the Layers of Visual Past A Guide to FB Image Searching (Reversed) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-fix-a-reappearing-deleted-file-or-folder-on-windows/"><u>8 Ways to Fix a Reappearing Deleted File or Folder on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-clickable-items-in-the-latest-os-update/"><u>Addressing Non-Clickable Items in the Latest OS Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-fun-integrating-games-into-windows-11-through-google-play/"><u>Android Fun: Integrating Games Into Windows 11 Through Google Play</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-unwanted-bios-access-during-windows-initialization/"><u>Avoiding Unwanted BIOS Access During Windows Initialization</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-13-to-other-iphone-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 13 to other iPhone devices? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-will-the-ipogo-get-you-banned-and-how-to-solve-it-on-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>In 2024, Will the iPogo Get You Banned and How to Solve It On Samsung Galaxy S23 FE | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/larger-pictures-same-sharpness-levels/"><u>Larger Pictures, Same Sharpness Levels</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unveiling-the-value-contender-apple-ipad-air-4-as-an-alternative-to-ipad-pro-explored/"><u>Unveiling the Value Contender: Apple iPad Air 4 as an Alternative to iPad Pro Explored</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/upgrading-your-apple-studio-display-step-by-step-guide-to-the-latest-firmware-enhancements-techradar/"><u>Upgrading Your Apple Studio Display: Step-by-Step Guide to the Latest Firmware Enhancements - TechRadar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719376942389-windows-gptmimicry-a-costless-local-edition-via-gpt4all/"><u>Windows GPTMimicry: A Costless Local Edition via GPT4All.</u></a></li>
</ul></div>

