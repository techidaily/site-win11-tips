---
title: How to Engage Clipboard Utility Within Microsoft Edge's App Guard for Windows 11
date: 2024-10-30T20:09:31.377Z
updated: 2024-11-07T06:51:26.191Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Engage Clipboard Utility Within Microsoft Edge's App Guard for Windows 11
excerpt: This Article Describes How to Engage Clipboard Utility Within Microsoft Edge's App Guard for Windows 11
keywords: Edge App Guard Tips,Windows 11 Security,Clipboard Usage,Edge App Guards,Utility Engagement,Microsoft Protection,Secure Data Transfer
thumbnail: https://thmb.techidaily.com/fea6185edc685da72ba963a46eed57a3a71d461697393364ab3bd89b9977de72.jpg
---

## How to Engage Clipboard Utility Within Microsoft Edge's App Guard for Windows 11

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

## 1\. How to Enable Copy and Paste via Windows Settings

 To enable copy and paste in Application Guard for Edge, follow the steps below:

1. Right-click on Start and select**Settings** from the menu list. For more information, check out our guide on[how to open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Privacy & security** from the left pane.
3. Then click the**Windows Security** option on the right-hand side.
4. On the following screen, select**App & browser control** .
5. Go to the Isolated browsing section and click the link "Change Applications Guard settings."  
![Change Application Guard Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-application-guard-settings.jpg)
6. Search for the**Copy and paste** option, then click the toggle to enable it.  

![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137206/26400" target="_top" id="2137206">
  <img src="//a.impactradius-go.com/display-ad/26400-2137206" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137206/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Enable Copy and Paste Using Registry Editor

 The Windows Registry is another method you can use to copy and paste within Application Guard for Edge on your Windows 11 PC. But, please be aware that editing the registry can have severe consequences if done incorrectly. To be safe,[back up the registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you begin making any changes.

 Follow these steps to enable copy and paste using the Windows Registry Editor:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type "regedit" in the text box and press the Enter key.
3. If UAC prompts appear on the screen, click**Yes** to confirm your action.
4. In the Registry Editor window, navigate to the following location:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi`
5. If you don't find the Hvsi key there, you will need to create it. To do this, right-click on Microsoft and select**New > Key** .

1. In the box that appears, give it the name**Hvsi** , and then hit Enter to save the file.
2. Now right-click on**Hvsi** and select**New > DWORD (32-bit) Value** .  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
3. Put**EnableClipboard** as the name for the new DWORD key, then press Enter.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135415/19272" target="_top" id="2135415">
  <img src="//a.impactradius-go.com/display-ad/19272-2135415" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

<!-- affiliate ads begin -->
<span id="1770526">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770526.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770526">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770526.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770526%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770526/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<span id="1938141">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938141.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938141">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938141.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938141%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938141/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Copy and Paste Now Works With Edge Application Guard

 With Application Guard for Edge, your device can remain secure while browsing the web. Unfortunately, certain functionalities such as copy and paste are disabled by default - but don't worry! This guide will explain two methods to activate them quickly and easily.

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
<li><a href="https://youtube-zero.techidaily.com/024-approved-video-platform-profiles-vimeo-vs-youtube-comparison/"><u>[New] 2024 Approved Video Platform Profiles Vimeo vs YouTube Comparison</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-transforming-digital-media-expert-advice-for-macs-dvd-creation/"><u>[Updated] 2024 Approved Transforming Digital Media Expert Advice for Mac's DVD Creation</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-complete-process-for-customizing-video-game-channels/"><u>2024 Approved The Complete Process for Customizing Video Game Channels</u></a></li>
<li><a href="https://win11.techidaily.com/adapting-windows-lockscreen-for-user-preferences/"><u>Adapting Windows Lockscreen for User Preferences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-internet-constraints-on-windows-11-devices/"><u>Configuring Internet Constraints on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-esd-files-and-their-conversion-into-iso-on-windows-os/"><u>Decoding ESD Files and Their Conversion Into ISO on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/digital-disguise-mastering-the-art-of-hiding-on-windows-11/"><u>Digital Disguise: Mastering the Art of Hiding on Windows 11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/from-one-to-many-making-the-leap-in-content-design/"><u>From One to Many: Making the Leap in Content Design</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-finding-the-right-sound-top-asmrists-advice/"><u>In 2024, Finding the Right Sound Top ASMRists Advice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-error-0xc0000001-on-windows/"><u>Mastering the Art of Fixing Error 0XC0000001 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/retrace-your-files-accessing-windows-11s-historical-data/"><u>Retrace Your Files: Accessing Windows 11'S Historical Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-immediate-fix-boot-sound-service-reset/"><u>Step-by-Step to Immediate Fix: Boot Sound Service Reset</u></a></li>
<li><a href="https://buynow-info.techidaily.com/ultimate-selection-of-premier-smartwatches-unveiled/"><u>Ultimate Selection of Premier Smartwatches Unveiled</u></a></li>
<li><a href="https://media-tips.techidaily.com/universal-video-codec-compatibility-with-windows-media-player-in-windows-11-8-and-7/"><u>Universal Video Codec Compatibility with Windows Media Player in Windows 11, 8 & 7</u></a></li>
</ul></div>

