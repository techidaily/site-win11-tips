---
title: "Windows Wizardry: Managing Peak and Low CPU States"
date: 2024-09-30T20:52:15.581Z
updated: 2024-10-03T18:48:06.718Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/1062447/7443" target="_top" id="1062447">
  <img src="//a.impactradius-go.com/display-ad/7443-1062447" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/1062447/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082530/7443" target="_top" id="2082530">
  <img src="//a.impactradius-go.com/display-ad/7443-2082530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082530/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144283/7443" target="_top" id="2144283">
  <img src="//a.impactradius-go.com/display-ad/7443-2144283" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144283/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<span id="1936838">
					<video width="374" height="48" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1936838.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18409-1936838">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1936838.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:234px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcoinrule.sjv.io%2Fc%2F5597632%2F1936838%2F18409'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1936838/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://screen-activity-recording.techidaily.com/new-10-premier-ios-games-fully-enjoyable-without-wireless-connection-for-2024/"><u>[New] 10 Premier iOS Games, Fully Enjoyable without Wireless Connection for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-essential-guide-incorporating-visual-annotations-in-edits/"><u>[New] 2024 Approved Essential Guide Incorporating Visual Annotations in Edits</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-examining-usb-type-cs-impact-on-modern-display-technology/"><u>[Updated] Examining USB Type-C's Impact on Modern Display Technology</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-motorola-moto-g24-drfone-by-drfone-virtual-android/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Motorola Moto G24 | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/dvd-mastering-and-protection-tips-for-windows-and-macos-users/"><u>DVD Mastering and Protection Tips for Windows and macOS Users</u></a></li>
<li><a href="https://extra-tips.techidaily.com/explore-best-speech-recognition-software-on-your-mac/"><u>Explore Best Speech Recognition Software on Your Mac</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/polish-language-jumpstarting-guide/"><u>Polish Language Jumpstarting Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-unhandled-exception-error-on-windows-systems/"><u>Quick Fix for Unhandled Exception Error on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-start-windows-11-home-menu-unlocking/"><u>Quick Start: Windows 11 Home Menu Unlocking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinvigorating-ancient-computers-win11-22h2-guide/"><u>Reinvigorating Ancient Computers: Win11 22H2 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revenue-sources-for-windows-11-microsofts-strategy/"><u>Revenue Sources for Windows 11: Microsoft's Strategy</u></a></li>
<li><a href="https://fox-that.techidaily.com/top-7-solutions-when-your-iphone-cant-get-sms-messages/"><u>Top 7 Solutions When Your iPhone Can't Get SMS Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-your-inner-hero-basic-diablo-play-mechanics/"><u>Unleashing Your Inner Hero: Basic Diablo Play Mechanics</u></a></li>
</ul></div>

