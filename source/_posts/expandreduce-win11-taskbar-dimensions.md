---
title: Expand/Reduce Win11 Taskbar Dimensions
date: 2024-10-02T02:12:55.487Z
updated: 2024-10-09T03:50:24.804Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expand/Reduce Win11 Taskbar Dimensions
excerpt: This Article Describes Expand/Reduce Win11 Taskbar Dimensions
keywords: Reduce Win11 Bar Size,Widen Windows Control Panel,Tighten Win11 Toolbar,Minimize Win11 Dock Distance,Adjust Taskbar Width,Slash Win11 UI Space,Constrict Windows Bar Dimension
thumbnail: https://thmb.techidaily.com/b77f4a1b111b54e2805878ed9aa3d1afc9409a9f5cc36ff257194dcf6821d1ac.jpg
---

## Expand/Reduce Win11 Taskbar Dimensions

 Ever looked at the Windows 11 Taskbar and thought it looks too small for your liking? Or maybe you feel it could be a little smaller? If that’s the case, you can change its size to suit your needs by making it bigger or smaller.

 Unlike Windows 10, you can’t just unlock the Taskbar and adjust its size freely in Windows 11\. While Microsoft has removed this way of going about it in Windows 11, there is a workaround that you can use, although it’s not as elegant.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<span id="1531879">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531879.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531879">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531879.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531879%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531879/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-top-6-tools-to-download-lite-videos-from-facebook/"><u>[Updated] In 2024, Top 6 Tools to Download Lite Videos From Facebook</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/4-ways-to-unlock-iphone-xr-to-use-usb-accessories-without-passcode-by-drfone-ios/"><u>4 Ways to Unlock iPhone XR to Use USB Accessories Without Passcode</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/e-audiences-writing-magical-youtube-description-templates-for-higher-views/"><u>Engage Audiences Writing Magical YouTube Description Templates for Higher Views</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-local-users-and-groups-management-in-windows-11-and-10-home/"><u>How to Enable Local Users and Groups Management in Windows 11 and 10 Home</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-errors-interpreting-bsod-with-code-0x0e00000b/"><u>Mastering Windows Errors: Interpreting BSOD with Code 0X0e00000b</u></a></li>
<li><a href="https://fake-location.techidaily.com/methods-to-change-gps-location-on-lava-blaze-2-5g-drfone-by-drfone-virtual-android/"><u>Methods to Change GPS Location On Lava Blaze 2 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-in-compression-rectifying-checksum-errors-with-winrar/"><u>Precision in Compression: Rectifying Checksum Errors with WinRAR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-system-call-failed-on-windows-1011/"><u>Quick Fixes: System Call Failed on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-hypervisor-errors-with-these-5-strategies/"><u>Stop HYPERVISOR Errors with These 5 Strategies</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/strategies-for-boosting-your-youtube-shorts-audience/"><u>Strategies for Boosting Your YouTube Shorts Audience</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-persistent-audio-drops-on-windows-10-solutions-revealed/"><u>Troubleshooting Persistent Audio Drops on Windows 10 – Solutions Revealed</u></a></li>
</ul></div>

