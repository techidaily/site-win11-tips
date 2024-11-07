---
title: How to Make the Taskbar Bigger or Smaller on Windows 11
date: 2024-11-02T03:00:03.553Z
updated: 2024-11-07T05:37:22.791Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Make the Taskbar Bigger or Smaller on Windows 11
excerpt: This Article Describes How to Make the Taskbar Bigger or Smaller on Windows 11
keywords: Windows Taskbar Size Control,Resize Taskbar Windows 11,Adjusting Taskbar Width,Increase Taskbar Size Windows,Decrease Windows Taskbar,Enlarge WinTaskbar,Reduce Windows Bar Dimensions
thumbnail: https://thmb.techidaily.com/826e213581d156558e6f234936866c0f136b901791e5cc9453b472a1e6024dd2.jpeg
---

## How to Make the Taskbar Bigger or Smaller on Windows 11

 Ever looked at the Windows 11 Taskbar and thought it looks too small for your liking? Or maybe you feel it could be a little smaller? If that’s the case, you can change its size to suit your needs by making it bigger or smaller.

 Unlike Windows 10, you can’t just unlock the Taskbar and adjust its size freely in Windows 11\. While Microsoft has removed this way of going about it in Windows 11, there is a workaround that you can use, although it’s not as elegant.

## How Do I Make the Windows 11 Taskbar Bigger or Smaller?

 The only way to change the size of the Taskbar is to use the Registry Editor. However, we advise caution when dealing with the Windows Registry because if something goes wrong, you might experience performance issues on your Windows 11 PC. If you’re unfamiliar with it, we recommend reading our guides on[what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) and[how to not mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) .

 Once you’re all caught up or are already familiar with the Windows Registry, and you know what you’re doing, you can make the Taskbar bigger or smaller. To do that:

1. Start by pressing**Win + R** to open Windows Run.
2. Type**regedit** in the text box and hit the**Enter** key.
3. Then, click**Yes** on the UAC prompt to launch the Registry Editor.
4. Copy and paste the below text in the address bar of the Registry Editor and hit the**Enter** key:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the**Advanced** key, look for a value called**TaskbarSi** . If it’s not there, right-click**Advanced** , select**New > DWORD (32-bit) Value** , and name that value**TaskbarSi.**  
![creating a new dword in the advanced key in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/new-dword-advanced-regedit.jpg)
6. Double-click**TaskbarSi** to edit it, and then enter**2** in the**Value data** text box and click**OK** to make the Taskbar bigger.  

![changing the taskbarsi value to 2 in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/taskbarsi-value-2.jpg)

 Once you restart your computer, you will see the result: an enlarged Taskbar.

![an enlarged Taskbar on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-enlarged-taskbar.jpg)

 To make the Taskbar smaller, enter**0** in the**Value data** text box, click**OK** , and then restart your computer. You will then see that the Taskbar has shrunk.

![a smaller taskbar in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-small-taskbar.jpg)

 If you decide to go back to the Taskbar’s default size, you can easily set**Value data** to**1** or simply delete the**TaskbarSi** value.

<!-- affiliate ads begin -->
<span id="1834906">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834906.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834906">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834906.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834906%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834906/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Adjust the Taskbar’s Size to Suit Your Needs on Windows 11

 Even though you can’t make the Taskbar bigger or smaller on Windows 11 as easily as you can on Windows 10, a little know-how can help. And as long as you followed the instructions mentioned above correctly, you shouldn’t worry about messing up the Windows Registry. However, we still recommend that you use this method only if you know what you’re doing.

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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-demystifying-the-apple-m1-prodigy/"><u>[New] 2024 Approved Demystifying the Apple M1 Prodigy</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-adding-music-mini-banners-on-instagram-profiles-for-2024/"><u>[New] Adding Music Mini-Banners on Instagram Profiles for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-ultimate-software-guide-for-video-game-shows/"><u>[New] In 2024, Ultimate Software Guide for Video Game Shows</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-melodic-moments-curating-the-best-10-sounds-for-podcasts/"><u>[New] Melodic Moments Curating the Best 10 Sounds for Podcasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-invisible-results-from-windows-1011s-search-feature/"><u>Fixing Invisible Results From Windows 10/11'S Search Feature</u></a></li>
<li><a href="https://extra-tips.techidaily.com/for-experts-only-top-5-best-drones-to-buy/"><u>For Experts Only – Top 5 Best Drones to Buy</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-realme-gt-5-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Realme GT 5 via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-solutions-to-spy-on-itel-p55plus-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>In 2024, Solutions to Spy on Itel P55+ with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/joby-wavo-pro-mic-evaluation-a-top-choice-for-camera-and-phone-shooters/"><u>Joby Wavo Pro Mic Evaluation - A Top Choice for Camera & Phone Shooters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lifting-the-curse-of-monochrome-screens-in-winx/"><u>Lifting the Curse of Monochrome Screens in WinX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-microsoft-store-glitches-via-server-corrections-on-win-1111/"><u>Overcoming Microsoft Store Glitches via Server Corrections on Win 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-reducing-latency-on-dual-monitors/"><u>Solutions for Reducing Latency on Dual Monitors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-quick-access-for-the-snipping-tool-on-win-11/"><u>Utilizing Quick Access for the Snipping Tool on Win 11</u></a></li>
</ul></div>

