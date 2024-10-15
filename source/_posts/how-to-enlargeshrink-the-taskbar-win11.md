---
title: How to Enlarge/Shrink the Taskbar Win11
date: 2024-10-10T20:26:21.274Z
updated: 2024-10-15T15:20:21.120Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Enlarge/Shrink the Taskbar Win11
excerpt: This Article Describes How to Enlarge/Shrink the Taskbar Win11
keywords: Windows 11 Taskbar Resize,Adjust Taskbar Size Win11,Change Win11 Bar Dimensions,Enlarge/Shrink Win11 Bar,Win11 Taskbar Width Control,Alter Taskbar Size in Win11,Maximize/Minimize Win11 Taskbar
thumbnail: https://thmb.techidaily.com/a6232b975632e43de71e5ab6217eebf552fc531569d56d79c1b10e2acedb4321.png
---

## How to Enlarge/Shrink the Taskbar Win11

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
<a href="https://aligracehair.sjv.io/c/5597632/2135362/19272" target="_top" id="2135362">
  <img src="//a.impactradius-go.com/display-ad/19272-2135362" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135362/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-web.techidaily.com/ed-a-list-films-must-watch-channel-compilation-for-2024/"><u>[Updated] A-List Films Must-Watch Channel Compilation for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-exclusive-selections-free-vs-paid-hd-playback-software/"><u>[Updated] Exclusive Selections Free vs Paid HD Playback Software</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-old-world-wonders-iphone-x-portraits/"><u>2024 Approved Old World Wonders – iPhone X Portraits</u></a></li>
<li><a href="https://android-unlock.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-meizu-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Meizu</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-poco-m6-pro-4g-drfone-by-drfone-virtual-android/"><u>Can I use iTools gpx file to catch the rare Pokemon On Poco M6 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/erase-microsoft-defender-record-trail-windows-edition-guide/"><u>Erase Microsoft Defender Record Trail: Windows Edition Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-download-to-use-chrome-in-windows-11-world/"><u>From Download to Use: Chrome in Windows 11 World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-through-audacitys-unresponsive-error-in-win-oses/"><u>Guiding Through Audacity's Unresponsive Error in Win OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-and-fix-windows-operating-pause-issues/"><u>How to Stop and Fix Windows Operating Pause Issues</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/in-2024-perfecting-aerial-images-key-factors-in-picking-a-gimbal/"><u>In 2024, Perfecting Aerial Images Key Factors in Picking a Gimbal</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-seekingsuperiorcameraspost-mycam/"><u>In 2024, SeekingSuperiorCamerasPost-MyCam</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-car-locator-apps-for-motorola-moto-g-stylus-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Car Locator Apps for Motorola Moto G Stylus (2023) | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/infusing-life-into-text-instagram-story-animations-tips/"><u>Infusing Life Into Text Instagram Story Animations Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instantaneous-application-termination-in-windows/"><u>Instantaneous Application Termination in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-microsofts-artificomedial-intelligence-hub/"><u>Navigating Through Microsoft's Artificomedial Intelligence Hub</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolving-stability-issues-a-guide-to-preventing-house-flipper-2-crashes-on-your-computer/"><u>Resolving Stability Issues: A Guide to Preventing House Flipper 2 Crashes on Your Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correct-m365-error-code-30015-26-on-computers/"><u>Steps to Correct M365 Error Code 30015-26 on Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-error-0x8007251d-in-microsofts-activation-process/"><u>Tackling Error 0X8007251D in Microsoft's Activation Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-secrets-of-silent-sleep-in-w10w11-machines/"><u>Unlock the Secrets of Silent Sleep in W10/W11 Machines</u></a></li>
</ul></div>

