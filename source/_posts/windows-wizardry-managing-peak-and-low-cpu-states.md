---
title: "Windows Wizardry: Managing Peak and Low CPU States"
date: 2024-09-20T19:52:06.426Z
updated: 2024-09-21T20:41:43.910Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Wizardry: Managing Peak and Low CPU States"
excerpt: "This Article Describes Windows Wizardry: Managing Peak and Low CPU States"
keywords: WinCPU Management,Windows Optimization,Peak CPU Control,Low CPU Handling,CPU State Balance,System Efficiency Guide,Cooling Processes in PCs
thumbnail: https://thmb.techidaily.com/56c09995c4310ae28019d3390616d9116d70341b815aee65c7667ed39de0e4c8.jpg
---

## Windows Wizardry: Managing Peak and Low CPU States

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

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

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
<li><a href="https://youtube-data.techidaily.com/024-approved-10-second-teasers-explained/"><u>[New] 2024 Approved 10-Second Teasers Explained</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-apple-media-access-and-download-youtube-videos-on-iphoneipad/"><u>[New] Apple Media Access and Download YouTube Videos on iPhone/iPad</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-mastering-the-art-of-pro-grade-gopro-videography/"><u>[New] In 2024, Mastering the Art of Pro-Grade Gopro Videography</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solved-apex-legends-no-sound/"><u>[SOLVED] Apex Legends No Sound</u></a></li>
<li><a href="https://activate-lock.techidaily.com/4-things-you-must-know-about-iphone-15-pro-activation-lock-by-drfone-ios/"><u>4 Things You Must Know About iPhone 15 Pro Activation Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-underperforming-machines-addressing-intel-hd-specs-issues/"><u>Correcting Underperforming Machines: Addressing Intel HD Specs Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-read-only-windows-file-constraints/"><u>Easing Read-Only Windows File Constraints</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-xiaomi-redmi-k70-pro-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Xiaomi Redmi K70 Pro Phone | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-premier-20-anime-series-theme-music/"><u>In 2024, Premier 20 Anime Series Theme Music</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-unlocking-screen-record-features-in-hp-computers/"><u>In 2024, Unlocking Screen Record Features in HP Computers</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unraveling-the-mystery-of-iphone-based-podcast-access/"><u>In 2024, Unraveling the Mystery of iPhone-Based Podcast Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-photography-in-windows-11-building-impressive-slide-shows-and-fixes/"><u>Mastering the Art of Photography in Windows 11: Building Impressive Slide Shows & Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-vanished-5ghz-connection-link-in-windows-11-swiftly/"><u>Restore Vanished 5GHz Connection Link in Windows 11 Swiftly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slash-clutter-a-fast-way-to-remove-bloatware-in-win11/"><u>Slash Clutter: A Fast Way to Remove Bloatware in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-against-steam-login-time-outs-in-rust-on-pc/"><u>Winning Strategies Against Steam Login Time-Outs in Rust on PC</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/977686/11832" target="_top" id="977686">
  <img src="//a.impactradius-go.com/display-ad/11832-977686" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/977686/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

