---
title: Deciphering Min/Max CPU Values Through Windows Menus
date: 2024-10-14T04:43:37.309Z
updated: 2024-10-14T16:10:46.932Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deciphering Min/Max CPU Values Through Windows Menus
excerpt: This Article Describes Deciphering Min/Max CPU Values Through Windows Menus
keywords: CPU Min Max Values,CPU Performance Metrics,Min Max CPU Settings,Windows CPU Configs,Optimize CPU Usage,Uncover CPU Limits,Explore CPU Thresholds
thumbnail: https://thmb.techidaily.com/dcd52c68a0261301dc49a434565ff933798115ab3a2be4caf338af3c874b626b.jpg
---

## Deciphering Min/Max CPU Values Through Windows Menus

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many[ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

To show the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c -ATTRIB_HIDE`

To hide the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c +ATTRIB_HIDE`

To show the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec -ATTRIB_HIDE`

To hide the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec +ATTRIB_HIDE`

 After you have typed in the command you want in the CMD window, hit the**Enter** key on your keyboard to run it.

<!-- affiliate ads begin -->
<a href="https://smilemakers.pxf.io/c/5597632/2123901/26106" target="_top" id="2123901">
  <img src="//a.impactradius-go.com/display-ad/26106-2123901" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123901/26106" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<span id="1743243">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1743243.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19272-1743243">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1743243.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Faligracehair.sjv.io%2Fc%2F5597632%2F1743243%2F19272'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1743243/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043639/7443" target="_top" id="2043639">
  <img src="//a.impactradius-go.com/display-ad/7443-2043639" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043639/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139563/4704" target="_top" id="2139563">
  <img src="//a.impactradius-go.com/display-ad/4704-2139563" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139563/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

## Add or Remove the Minimum and Maximum Processor States From Power Options

 Setting the minimum or maximum processor state on your Windows computer is vital to helping you get the performance you want from it. If you can’t see these options in the Power Options menu, you can easily reveal them with either Command Prompt or the Registry Editor. And after you’re done tweaking the states, you can hide them for their protection.

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
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-downloader-essentials-the-best-tools-for-offline-viewing/"><u>[Updated] 2024 Approved Downloader Essentials The Best Tools For Offline Viewing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensure-permanent-file-elimination-with-customizable-trash-setup-in-windows-pcs-11/"><u>Ensure Permanent File Elimination with Customizable Trash Setup in Windows PCs (11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-mend-caught-by-exception-point-windows-glitch/"><u>Guide to Mend Caught by Exception Point Windows Glitch</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-vivo-y100i-power-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Vivo Y100i Power 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/intel-310-processor-shows-dual-p-cores-still-got-game-a-look-at-its-geekbench-performance/"><u>Intel 310 Processor Shows Dual-P Cores Still Got Game: A Look at Its Geekbench Performance</u></a></li>
<li><a href="https://extra-tips.techidaily.com/jpegpng-to-pdf-on-iphone-step-by-step-approach/"><u>JPEG/PNG to PDF on iPhone - Step-by-Step Approach</u></a></li>
<li><a href="https://win-amazing.techidaily.com/latest-driver-release-nvidias-geforce-rtx-2080-for-enhanced-gaming-experience-in-windows-10-7-and-8/"><u>Latest Driver Release: NVIDIA's GeForce RTX #2080 for Enhanced Gaming Experience in Windows 10, 7 & 8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sidestep-immediate-edge-tabs-on-win11/"><u>Sidestep Immediate Edge Tabs on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-finding-your-hidden-pin-after-updating-windows-11/"><u>Strategies for Finding Your Hidden PIN After Updating Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-remedying-the-non-registered-package-issue/"><u>Understanding and Remedying the Non-Registered Package Issue</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-samsung-galaxy-a05-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Samsung Galaxy A05 | Dr.fone</u></a></li>
</ul></div>

