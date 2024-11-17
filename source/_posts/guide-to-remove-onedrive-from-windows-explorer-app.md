---
title: Guide to Remove OneDrive From Windows Explorer App
date: 2024-11-11T18:37:00.814Z
updated: 2024-11-17T17:54:41.740Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Remove OneDrive From Windows Explorer App
excerpt: This Article Describes Guide to Remove OneDrive From Windows Explorer App
keywords: Removing OneDrive Explorer,Unlink OneDrive Explorer,DropOneDrive Windows,Exclude OneDrive Folder,Disable OneDrive Explorer,Turn Off OneDrive Sync,Hide OneDrive Icon Windows
thumbnail: https://thmb.techidaily.com/6889b29c9a1ca37c06d96850359e16ed975462ec122694d578843a25c7f44c71.jpg
---

## Guide to Remove OneDrive From Windows Explorer App

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
<a href="https://appsumo.8odi.net/c/5597632/2105860/7443" target="_top" id="2105860">
  <img src="//a.impactradius-go.com/display-ad/7443-2105860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105860/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1061528/11832" target="_top" id="1061528">
  <img src="//a.impactradius-go.com/display-ad/11832-1061528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1061528/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2141684/17092" target="_top" id="2141684">
  <img src="//a.impactradius-go.com/display-ad/17092-2141684" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettide.pxf.io/i/5597632/2141684/17092" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-seamless-obs-integration-on-your-mac-a-detailed-walkthrough/"><u>[New] In 2024, Seamless OBS Integration on Your Mac A Detailed Walkthrough</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-itel-p55plus-fix-now-drfone-by-drfone-virtual-android/"><u>3uTools Virtual Location Not Working On Itel P55+? Fix Now | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-samsung-galaxy-a14-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Samsung Galaxy A14 4G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-speed-keyboard-mastery-through-powertoys/"><u>Elevate Speed: Keyboard Mastery Through PowerToys</u></a></li>
<li><a href="https://games-able.techidaily.com/elite-game-collectives-victory-villages/"><u>Elite Game Collectives: Victory Villages</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/exclusive-dive-into-the-2024-fb-ad-landscape/"><u>Exclusive Dive Into the 2024 FB Ad Landscape</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-prevent-f1-2021-pc-crashes-and-enjoy-the-full-racing-thrill/"><u>How to Prevent F1 2021 PC Crashes & Enjoy the Full Racing Thrill</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-a-non-operational-win11-code/"><u>How to Reactivate a Non-Operational Win11 Code</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-navigating-backward-image-hunt-on-the-worlds-largest-social-site/"><u>In 2024, Navigating Backward Image Hunt on the World's Largest Social Site</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-vocal-to-text-conversion-with-windows-whisper/"><u>Master the Art of Vocal to Text Conversion with Windows Whisper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-steam-file-sync-in-windows-environment/"><u>Mastering Steam File Sync in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-the-unexpected-token-call-on-win10-devices/"><u>Solutions for the “Unexpected Token Call” On Win10 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solve-your-microsoft-store-sign-in-problems-today/"><u>Solve Your Microsoft Store Sign-In Problems Today</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-honor-play-8t-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Honor Play 8T? Here is How | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721103778364-your-pc-graphics-issues-let-us-fix-your-nvidia-rtx-gaming-woes/"><u>Your PC Graphics Issues? Let Us Fix Your Nvidia RTX Gaming Woes</u></a></li>
</ul></div>

