---
title: Expand/Reduce Win11 Taskbar Dimensions
date: 2024-10-11T05:53:50.113Z
updated: 2024-10-14T19:17:51.888Z
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
<a href="https://appsumo.8odi.net/c/5597632/2037358/7443" target="_top" id="2037358">
  <img src="//a.impactradius-go.com/display-ad/7443-2037358" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037358/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-maximizing-tweet-control-15-premier-unfollow-utilities/"><u>[New] 2024 Approved Maximizing Tweet Control 15 Premier Unfollow Utilities</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-internal-recorder-usage-for-capturing-screens-on-mate-series-and-p-series-mate-1020-p2010/"><u>[Updated] 2024 Approved Internal Recorder Usage for Capturing Screens on Mate Series & P Series (Mate 10/20; P20/10)</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/calculating-the-storage-space-of-24-hour-videos/"><u>Calculating the Storage Space of 24-Hour Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-policy-settings-for-users-a-guide-to-windows-11-and-11/"><u>Personalizing Policy Settings for Users: A Guide to Windows 11 & 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-vivo-v30-pro-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Vivo V30 Pro Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stabilizing-windows-display-issues-expert-tips/"><u>Stabilizing Windows Display Issues: Expert Tips</u></a></li>
<li><a href="https://fox-links.techidaily.com/strategic-pricing-analysis-cloud-services-financial-face/"><u>Strategic Pricing Analysis Cloud Services' Financial Face</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-a-nonfunctional-shift-key/"><u>Troubleshooting Guide: Fixing a Nonfunctional Shift Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-secrets-of-bluescreenview-usage/"><u>Unlocking the Secrets of BlueScreenView Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workaround-for-windows-unlaunchable-lunar-client-issue/"><u>Workaround for Windows' Unlaunchable Lunar Client Issue</u></a></li>
</ul></div>

