---
title: How to Cut Out OneDrive From Your PC's File Explorer Screenshot
date: 2024-06-25T16:35:40.155Z
updated: 2024-06-26T16:35:40.155Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Cut Out OneDrive From Your PC's File Explorer Screenshot
excerpt: This Article Describes How to Cut Out OneDrive From Your PC's File Explorer Screenshot
keywords: Removing OneDrive From File Explorer,Disable OneDrive in Windows,Exclude OneDrive From Explorer Screenshots,Remove OneDrive Icon From PC Explorer,Screenshot without OneDrive,Screen Capture Excluding OneDrive,Exclude OneDrive when Capturing Files
thumbnail: https://thmb.techidaily.com/c465b3961d0e8ae791649e84e8128b1614e8e09e935ed979e13eb915c45489fc.jpg
---

## How to Cut Out OneDrive From Your PC's File Explorer Screenshot

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on [removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you [create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

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

## How to Show the OneDrive Icon Again in File Explorer ![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

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
<li><a href="https://win11-tips.techidaily.com/preventing-and-fixing-system-call-error-on-windows-11/"><u>Preventing and Fixing System Call Error on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-for-a-functional-windows-11-search-interface/"><u>Quick Steps for a Functional Windows 11 Search Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-windows-error-code-0xc00000f-strategies-for-success/"><u>Mastery over Windows Error Code 0Xc00000f: Strategies for Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mouse-navigation-turn-off-acceleration-windows-1011/"><u>Mastering Mouse Navigation: Turn Off Acceleration Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-mastery-building-hotkeys-for-repetitive-text-snapping-tasks/"><u>Windows 11 Mastery: Building Hotkeys for Repetitive Text Snapping Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-unsuccessful-nvidia-connect-attempts-in-windows-11/"><u>Resolving Unsuccessful Nvidia Connect Attempts in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-downloads-for-windows-top-10-choices-revealed/"><u>Secure Downloads for Windows: Top 10 Choices Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-steam-ui-error-on-windows-os-platform/"><u>Mending Steam UI Error on Windows OS Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-copilot-from-your-windows-environment/"><u>Removing Copilot From Your Windows Environment</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-screeneasew11-simplified-windows-11-recording-software/"><u>[Updated] ScreenEaseW11  Simplified Windows 11 Recording Software</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/bass-brilliance-recording-review-for-2024/"><u>Bass Brilliance  Recording Review for 2024</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-xiaomi-redmi-note-12-5g-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Xiaomi Redmi Note 12 5G | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/come-and-pick-best-mov-to-gif-converters/"><u>Come And Pick! Best MOV to GIF Converters</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-top-8-yt-thumbnails-that-increase-watch-time-and-interests/"><u>In 2024, The Top 8 YT Thumbnails that Increase Watch Time and Interests</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-discovering-the-best-8-daw-apps-on-android-a-production-boost/"><u>2024 Approved Discovering the Best 8 DAW Apps on Android A Production Boost</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-transforming-industries-via-vr/"><u>In 2024, Transforming Industries via VR</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-adding-drama-to-videos-strikethrough-for-emphasis-and-clarity/"><u>[New] 2024 Approved  Adding Drama to Videos  Strikethrough for Emphasis and Clarity</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/ultimate-win10-screen-and-video-recording-tool-for-2024/"><u>Ultimate Win10 Screen & Video Recording Tool for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-unlocking-an-icloud-locked-ipad-and-iphone-14-by-drfone-ios/"><u>In 2024, Unlocking an iCloud Locked iPad and iPhone 14</u></a></li>
</ul></div>
