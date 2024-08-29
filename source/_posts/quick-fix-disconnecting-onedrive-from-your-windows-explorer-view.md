---
title: "Quick Fix: Disconnecting OneDrive From Your Windows Explorer View"
date: 2024-08-28T01:18:02.381Z
updated: 2024-08-29T01:18:02.381Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Fix: Disconnecting OneDrive From Your Windows Explorer View"
excerpt: "This Article Describes Quick Fix: Disconnecting OneDrive From Your Windows Explorer View"
keywords: Quick Ditch OneDrive,Disconnect OneDrive,Remove OneDrive Folder,Stop OneDrive in Explorer,Exclude OneDrive Windows,Turn Off OneDrive View,Halt OneDrive Explorer Link
thumbnail: https://thmb.techidaily.com/bd9bfd190306deb90b91d858667c2c41b78982227d8d0c9a830c7fb7735e577b.jpg
---

## Quick Fix: Disconnecting OneDrive From Your Windows Explorer View

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

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

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-behind-closed-doors-of-youtube-a-discovery-manual/"><u>[New] 2024 Approved  Behind Closed Doors of YouTube  A Discovery Manual</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-comparing-core-titles-oculus-htc-vive-and-ps-vr-in-gaming/"><u>[New] Comparing Core Titles  Oculus, HTC Vive & PS VR in Gaming</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-decoding-social-media-success-navigate-the-best-and-hidden-tiktok-glyphs/"><u>[Updated] Decoding Social Media Success - Navigate the Best & Hidden TikTok Glyphs</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-earn-on-tiktok-explore-8-effective-money-making-techniques/"><u>[Updated] Earn on TikTok  Explore 8 Effective Money-Making Techniques</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-elevate-iphone-snapshots-with-these-hacks/"><u>2024 Approved  Elevate iPhone Snapshots with These Hacks</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/best-video-makers-with-music-and-photos/"><u>Best Video Makers with Music and Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-out-clutter-celebrate-pure-win11/"><u>Clear Out Clutter: Celebrate Pure Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delay-windows-11-shutdown-dealing-with-live-applications/"><u>Delay Windows 11 Shutdown: Dealing with Live Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/earnings-explored-microsoft-and-its-windows-11-model/"><u>Earnings Explored: Microsoft & Its Windows 11 Model</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-gaming-experience-using-intel-graphics-hub/"><u>Enhance Your Gaming Experience: Using Intel Graphics Hub</u></a></li>
<li><a href="https://facebook.techidaily.com/experimental-meta-drop-support-for-social-media-users/"><u>Experimental Meta Drop Support for Social Media Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-google-chrome-aw-snap-error-on-windows/"><u>How to Fix the Google Chrome “Aw, Snap!” Error on Windows</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-essential-insights-into-top-10-no-cost-open-source-video-communication-tools/"><u>In 2024, Essential Insights Into Top 10 No-Cost, Open Source Video Communication Tools</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-facebook-in-flashes-sharing-briefly/"><u>In 2024, Facebook in Flashes  Sharing Briefly</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-silly-sphere-the-most-amusing-youtuber-shows-today/"><u>In 2024, Silly Sphere  The Most Amusing YouTuber Shows Today</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-solutions-to-spy-on-tecno-pop-8-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>In 2024, Solutions to Spy on Tecno Pop 8 with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-methods-to-shift-beyond-s-mode-confinement/"><u>Mastering Methods to Shift Beyond S Mode Confinement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-pink-screen-repair-on-windows-os/"><u>Mastering Pink Screen Repair on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-missing-windows-logins-with-ease/"><u>Navigating Through Missing Windows Logins with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-blue-screen-mysteries/"><u>Navigating Through Windows' Blue Screen Mysteries</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11s-lost-d3dx939dll-issue/"><u>Overcoming Windows 11'S Lost D3DX9_39.dll Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-adobe-auth-issue/"><u>Overcoming Windows Adobe Auth Issue</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ssional-recordings-at-home-10-key-strategies-for-excellence-for-2024/"><u>Professional Recordings at Home  10 Key Strategies for Excellence for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/quick-fit-enhance-your-photo-posts-with-automated-mac-video-scaling-for-2024/"><u>Quick Fit  Enhance Your Photo Posts with Automated Mac Video Scaling for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quickening-steam-download-speed-on-your-windows-system/"><u>Quickening Steam Download Speed on Your Windows System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-resolution-quick-tips-for-a-stable-wwe-gameplay/"><u>Rapid Resolution: Quick Tips for a Stable WWE Gameplay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ready-for-the-future-top-laptops-of-ifa-2023/"><u>Ready for the Future? Top Laptops of IFA 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reveal-your-pcs-intel-core-gen-via-8-windows-tips/"><u>Reveal Your PC's Intel Core Gen via 8 Windows Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shifting-onedrive-folder-a-windows-10-guide/"><u>Shifting OneDrive Folder: A Windows 10 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speeding-up-your-pc-adjusting-boot-sequence-timer-in-win11/"><u>Speeding Up Your PC: Adjusting Boot Sequence Timer in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-hiding-task-view-in-win-11/"><u>Strategies for Hiding Task View in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-resolving-steam-login-errors/"><u>Strategies for Resolving Steam Login Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-workflow-set-microsoft-words-preference-for-text-only-attachment-viewing/"><u>Streamline Your Workflow: Set Microsoft Word's Preference for Text-Only Attachment Viewing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-note-visibility-with-tips-for-modern-windows-users/"><u>Streamlining Note Visibility with Tips for Modern Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-video-conversion-mkv-to-mp4-on-pcs/"><u>Streamlining Video Conversion: MKV to MP4 on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/telnet-configuration-made-simple-for-win11-users/"><u>Telnet Configuration Made Simple: For Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocked-accessibility-for-non-functional-applications-on-ms-store/"><u>Unblocked Accessibility for Non-Functional Applications on MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninterrupted-powertoys-experience-with-system-switch-up/"><u>Uninterrupted PowerToys Experience with System Switch-Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uniting-cloud-storage-seamless-onedrive-plus-microsoft-login/"><u>Uniting Cloud Storage: Seamless OneDrive + Microsoft Login</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-woes-how-to-re-enable-the-hidden-enhancement-panel/"><u>Windows 11 Woes: How to Re-Enable the Hidden Enhancement Panel</u></a></li>
</ul></div>
