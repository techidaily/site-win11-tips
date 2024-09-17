---
title: Deciphering Min/Max CPU Values Through Windows Menus
date: 2024-09-11T01:24:17.365Z
updated: 2024-09-17T03:29:32.861Z
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-elevate-your-content-with-these-25-powerful-instagram-tags/"><u>[New] In 2024, Elevate Your Content with These 25 Powerful Instagram Tags</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-index-of-varied-photographic-and-videography-instruments/"><u>[New] Index of Varied Photographic and Videography Instruments</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-interactive-twit-narratives-a-compendium-for-23-for-2024/"><u>[New] Interactive Twit-Narratives - A Compendium for '23 for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-turn-your-mobile-into-a-professional-webcam-for-video/"><u>[Updated] 2024 Approved Turn Your Mobile Into a Professional Webcam for Video</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/best-online-cameras-for-video-chat-and-streaming-experience/"><u>Best Online Cameras for Video Chat & Streaming Experience</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/elevate-storytelling-modifying-video-speed-on-instagram/"><u>Elevate Storytelling Modifying Video Speed on Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-functionality-to-flair-windows-10s-transition-to-11/"><u>From Functionality to Flair: Windows 10'S Transition to 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-your-dream-laptop-with-these-ifa-2023-picks/"><u>Get Your Dream Laptop with These IFA 2023 Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-an-end-task-option-on-the-windows-11-taskbar/"><u>How to Enable an End Task Option on the Windows 11 Taskbar</u></a></li>
<li><a href="https://change-location.techidaily.com/latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-vivo-y78plus-t1-edition-drfone-by-drfone-virtual-android/"><u>Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Vivo Y78+ (T1) Edition | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-rectify-windows-11-search-woes/"><u>Quick Guide to Rectify Windows 11 Search Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguard-your-pc-without-bitlockers-help-on-windows/"><u>Safeguard Your PC Without BitLocker's Help on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shortcuts-for-skipping-windows-sign-in-requirements/"><u>Shortcuts for Skipping Windows Sign-In Requirements</u></a></li>
<li><a href="https://vp-tips.techidaily.com/snapseed-101-basic-editing-techniques-unveiled-for-2024/"><u>Snapseed 101 Basic Editing Techniques Unveiled for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/top-stock-photos-their-journey-to-internet-fame/"><u>Top Stock Photos Their Journey to Internet Fame</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-unanticipated-security-alerts-in-win10win11/"><u>Troubleshooting Unanticipated Security Alerts in Win10/Win11</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1983549">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983549.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983549">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983549.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983549%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983549/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

