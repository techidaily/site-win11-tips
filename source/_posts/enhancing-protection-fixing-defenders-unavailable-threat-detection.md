---
title: "Enhancing Protection: Fixing Defender's Unavailable Threat Detection"
date: 2024-10-03T18:23:50.225Z
updated: 2024-10-08T22:16:54.391Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enhancing Protection: Fixing Defender's Unavailable Threat Detection"
excerpt: "This Article Describes Enhancing Protection: Fixing Defender's Unavailable Threat Detection"
keywords: Threat Detection Improvement,Enhanced Security Features,Protecting From Hidden Threats,Upgraded Defense Mechanisms,Boosting Safety Systems,Advanced Threat Identification,Strengthening Cybersecurity
thumbnail: https://thmb.techidaily.com/290fdfbe7988bc73a9658535e5e89697be7bda898900fabab3b9425630194609.jpg
---

## Enhancing Protection: Fixing Defender's Unavailable Threat Detection

 Windows Defender is a crucial built-in antivirus software that helps protect your computer from various types of malware and security threats. However, users might encounter a common issue where the Virus & threat protection feature in Windows Defender displays an error message saying "Engine Unavailable" which prevents it from scanning for viruses and leaving your system vulnerable.

 In this article, we will explore the solutions that can help fix this issue and restore the full functionality of this important security feature.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Is the Engine Unavailable in Windows Defender?

 The Virus & Threat Protection engine typically becomes unavailable after a Windows Defender update fails to install in the system. This can happen due to a number of reasons, and we have listed the most common ones below:

* **The r** **elevant services are disabled** \- the essential services required to install the Windows Defender updates might be disabled, preventing the system from updating it.
* **Windows Security's files are corrupt** \- there can be an issue with the Windows Security utility itself. A temporary bug or a corruption error might have infected it, causing it to act up.
* **Conflicting software** \- software offering similar functionalities could be conflicting with Windows Defender and its relevant procedures.
* **Corrupted Windows files or malware** \- the critical system files might be corrupt, which is affecting the update functionality of Windows. Your system might also be infected with malware.

 Regardless of what might be leading to the problem, the solutions we have listed below are sure to help you get the Virus & Threat Protection engine up and running for good. We suggest that before you proceed, restart your computer and retry installing the update. In some cases, a temporary system glitch can lead to the problem and a simple reboot can clear it.

<!-- affiliate ads begin -->
<span id="2135471">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135471%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135471/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Restart the Security Center Service

 The Security Center service in Windows is responsible for managing security-related services, including Windows Defender. If the service is not functioning properly, it can prevent you from updating the Defender or using it at all

 Fortunately, service issues are easy to resolve. Most of the time, restarting the service can get it running properly again.

Here is how you can restart the Security Center Service:

1. Press the**Win + R** keys together to open Run.
2. Type "services.ms" in Run and press**Enter** .
3. In the following dialog, scroll down to locate the Security Center service and right-click on it.
4. Choose**Properties** from the context menu.  
![Launch the properties of Security Center service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/security-center-properties.jpg)
5. Now, click on the**Stop** button, wait for a few seconds, and click**Start** .
6. Expand the dropdown for Startup type and choose**Automatic** .
7. Click**Apply** \>**OK** to save the changes and then close the Services utility.

 You can now retry installing the Defender update and check if restarting the service fixed the issue.

## 2\. Edit the Relevant Registry Keys

 You can also enable the Windows Defender services using the Registry Editor. In this method, we will disable the DisableAntiSpyware and DisableAntiVirus values. Then, we will delete any corrupt Registry entries that malware may have introduced in the system.

 However, before we proceed, we recommend[creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , just to be safe.

Once that is done, proceed with the steps below:

1. Press the**Win + R** keys together to open Run.
2. Type "regedit" in the text field of Run and press**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Registry Editor, navigate to the location mentioned below:  
`HKEY_LOCAL_MACHINE\\SOFTWARE\\Policies\\Microsoft\\Windows Defender`
5. Move to the right pane and locate the**DisableAntiSpyware** value.

1. Double-click on it and under Value data, type**0** .  
![Change the value data to 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/disableantispyware-key.jpg)
2. Do the same with the**DisableAntiVirus** value in the same window.
3. After this, navigate to the following location in the Registry Editor:  
`HKEY_LOCAL_MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Image File Execution Options`
4. Here, right-click on the MSASCui.exe, MpCmdRun.exe, and MsMpEng.exe values one by one and choose**Delete** .  
![Delete the Registry entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/delete-the-key.jpg)
5. Finally, close the Registry Editor and restart your computer. Upon reboot check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068412/7443" target="_top" id="2068412">
  <img src="//a.impactradius-go.com/display-ad/7443-2068412" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068412/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Manually Install the Update

 If the system cannot install the Windows Defender update automatically, you can also manually install it.

 This can be done by heading over to the[Microsoft security updates](https://www.microsoft.com/en-us/wdsi/defenderupdates) page and finding the required update in the "manually download the update" section. You can then select the appropriate version based on your system and install it.

 You can also use the Powershell utility to install the update manually. We have discussed the[different methods of manually updating Windows Defender](https://www.makeuseof.com/microsoft-defender-manually-update/) , so be sure to check it out.

<!-- affiliate ads begin -->
<span id="1983539">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983539.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983539">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983539.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983539%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983539/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Reset Windows Security

 As we mentioned earlier, there can be an issue with Windows Security itself. This problem can be resolved by resetting the utility, which will clear all of its settings and configurations, restoring the default state.

Here is how you can reset the Windows Security app:

1. Press the**Win + S** keys together to open the Windows Search utility.
2. Type Powershell in the search bar and click on**Run as administrator** .
3. In the Powershell window, type the command mentioned below and hit**Enter** .  
`Get-AppxPackage Microsoft.SecHealthUI -AllUsers | Reset-AppxPackage`  
![Command to Reset Windows Security in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Command-to-Reset-Windows-Security-.jpg)
4. Once the command is executed, exit Powershell and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484909/16446" target="_top" id="1484909">
  <img src="//a.impactradius-go.com/display-ad/16446-1484909" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484909/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Remove Any Conflicting Software

 In case you have a third party installed on the system, it might be interfering with the processes of Windows Defender, preventing it from updating or functioning properly.

 If this applies to you, we recommend temporarily disabling the security program or uninstalling it. You can do this using the Control Panel or the Settings app. We have a detailed guide that discusses[how to remove programs in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) that you can refer to if you need help.

 If you can successfully update Windows Defender after removing the third-party software, then it implies that the program was indeed the culprit. In this case, you can switch to a better third-party alternative. Here are some[best free antivirus programs](https://www.makeuseof.com/tag/ten-best-antivirus-programs/) that you can consider installing.

## Get Windows Defender Up and Running Again

 Issues with the Windows Defender can be frustrating and expose your system to security threats. Hopefully, the solutions we have described above will help you fix the engine unavailable problem and use the security program to its full potential. If the problem occurs repeatedly in the future, you can report the issue to the official Microsoft support team and switch to a third-party solution until an official fix is released.

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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-twitters-top-10-giggle-generators/"><u>[New] 2024 Approved Twitter's Top 10 Giggle Generators</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-continuous-connection-avoiding-streak-breakers-on-snapchat/"><u>[New] Continuous Connection Avoiding Streak Breakers on Snapchat</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-mind-mavens-top-10-educational-youtube-hubs/"><u>[New] Mind Mavens Top 10 Educational YouTube Hubs</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-skybound-streaming-engaging-your-audience-on-facebook-for-2024/"><u>[New] Skybound Streaming Engaging Your Audience on Facebook for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-pigments-and-palettes-the-artists-guidebook/"><u>[Updated] In 2024, Pigments & Palettes The Artist's Guidebook</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/comprehensive-evaluation-of-the-google-pixel-4a-the-ideal-choice-for-casual-users/"><u>Comprehensive Evaluation of the Google Pixel 4A: The Ideal Choice for Casual Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-top-6-computer-utilization-monitors-on-pcs/"><u>Discover the Top 6 Computer Utilization Monitors on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-persistence-of-user-defined-volume-mixer/"><u>Ensuring Persistence of User-Defined Volume Mixer</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-planning-to-use-a-pokemon-go-joystick-on-apple-iphone-12-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, Planning to Use a Pokemon Go Joystick on Apple iPhone 12 Pro? | Dr.fone</u></a></li>
<li><a href="https://discover-blog.techidaily.com/mastering-the-art-of-photography-the-comprehensive-rolling-shutter-manual-by-movavi/"><u>Mastering the Art of Photography: The Comprehensive Rolling Shutter Manual by Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstate-missing-dxgidll-streamline-your-win11/"><u>Reinstate Missing Dxgi.dll, Streamline Your Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-the-backbone-softwaredistribution-and-catroot2-on-ws11/"><u>Resetting the Backbone: SoftwareDistribution and Catroot2 on WS11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-your-full-screen-capture-predicament-with-snip-and-sketch/"><u>Solving Your Full-Screen Capture Predicament with Snip & Sketch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-error-0xc00d36b4-sound-fixes/"><u>Unraveling Windows Error 0XC00D36B4: Sound Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-wintoys-a-short-guide-to-a-powerful-windows-tool/"><u>What Is Wintoys? A Short Guide to a Powerful Windows Tool</u></a></li>
</ul></div>

