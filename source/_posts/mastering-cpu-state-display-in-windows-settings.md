---
title: Mastering CPU State Display in Windows Settings
date: 2024-10-30T16:14:29.378Z
updated: 2024-11-01T18:53:44.961Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering CPU State Display in Windows Settings
excerpt: This Article Describes Mastering CPU State Display in Windows Settings
keywords: WinCPUDisplayTechniques,PCStateDisplayWindows,CPUStatusWindowsView,MasteryInCPUStateWin,WindowsCPUDisplaysMaster,OptimizeWinCPUShowing,AdvancedCPUStateWins
thumbnail: https://thmb.techidaily.com/d20682484ee39b27689e93ff94b9b7638592055fcb925a693073d87e930189fb.jpg
---

## Mastering CPU State Display in Windows Settings

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
<a href="https://appsumo.8odi.net/c/5597632/2137395/7443" target="_top" id="2137395">
  <img src="//a.impactradius-go.com/display-ad/7443-2137395" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137395/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<span id="1983584">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983584.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983584">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983584.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983584%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983584/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2141676/17091" target="_top" id="2141676">
  <img src="//a.impactradius-go.com/display-ad/17091-2141676" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141676/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135412/19272" target="_top" id="2135412">
  <img src="//a.impactradius-go.com/display-ad/19272-2135412" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135412/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-exclusive-downloads-top-8-stealthy-tools/"><u>[New] In 2024, Exclusive Downloads Top 8 Stealthy Tools</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-quantum-realms-unraveling-new-worlds-with-10-sci-fi-titles/"><u>2024 Approved Quantum Realms Unraveling New Worlds with 10 Sci-Fi Titles</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-the-future-in-your-hand-top-10-cutting-edge-recorder-apps/"><u>2024 Approved The Future in Your Hand Top 10 Cutting-Edge Recorder Apps</u></a></li>
<li><a href="https://blog-min.techidaily.com/movavirawjpg/"><u>利用Movavi在線自由改變RAW成JPG - 無損影像編碼器</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/easing-excessive-encoding-of-obs-media-for-2024/"><u>Easing Excessive Encoding of OBS Media for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-scheduling-combining-to-do-and-ifttt-services/"><u>Efficient Scheduling: Combining To-Do and IFTTT Services</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/expert-tips-to-deal-with-storahcisys-blue-screen-of-death-bsod/"><u>Expert Tips to Deal with Storahci.sys Blue Screen of Death (BSoD)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reset-power-schemes-back-to-windows-default/"><u>How To Reset Power Schemes Back to Window's Default</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-tips-for-setting-windows-time-locally/"><u>Instant Tips for Setting Windows Time Locally</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-your-windows-11-temporary-files-reliable-and-valid/"><u>Keeping Your Windows 11 Temporary Files Reliable & Valid</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-disk-space-via-archiving-in-windows-11/"><u>Maximize Disk Space via Archiving in Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/quick-and-easy-methods-for-changing-mkv-videos-into-high-quality-divx-format/"><u>Quick and Easy Methods for Changing MKV Videos Into High-Quality DivX Format</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-to-unblock-valorants-in-game-voice-channel-windows/"><u>Quick Steps to Unblock Valorant's In-Game Voice Channel (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-functional-lock-screen-wait-period-in-windows/"><u>Reinstating Functional Lock Screen Wait Period in Windows</u></a></li>
<li><a href="https://win-amazing.techidaily.com/simple-steps-to-successfully-update-your-amd-graphics-driver/"><u>Simple Steps to Successfully Update Your AMD Graphics Driver</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-windows-11-way-mastery-of-software-uninstallation/"><u>The Windows 11 Way: Mastery of Software Uninstallation</u></a></li>
<li><a href="https://win-luxury.techidaily.com/ultimate-guide-to-crafting-engaging-fb-video-content-expert-tips-and-techniques/"><u>Ultimate Guide to Crafting Engaging FB Video Content: Expert Tips & Techniques</u></a></li>
</ul></div>

