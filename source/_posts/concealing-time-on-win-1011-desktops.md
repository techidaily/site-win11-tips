---
title: Concealing Time on Win 10/11 Desktops
date: 2024-09-26T16:54:34.859Z
updated: 2024-09-28T18:21:55.948Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Concealing Time on Win 10/11 Desktops
excerpt: This Article Describes Concealing Time on Win 10/11 Desktops
keywords: Windows Hide Taskbar,PC Freeze Timer,Win10 Screen Blur,XP Hidden Clock,Win7 Time Disguise,Desktop Time Cloak,OS Conceal Clock
thumbnail: https://thmb.techidaily.com/be7eb26b929d376d352a2b6560c781f129b853a9868bdf923c96ee4b76c8aaef.jpg
---

## Concealing Time on Win 10/11 Desktops

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Hide or Show the Clock and Date from the Taskbar by Using Windows System Settings

 The System Settings is the central hub of a Windows PC. You can use it to update Windows, manage privacy settings,[customize the taskbar](https://www.makeuseof.com/windows-11-customize-taskbar/) , and more.

 It's also one of the places from where you can configure the taskbar to hide or show the clock and date. You can do this by following the below instructions:

 This method only works for Windows 10\. If you are using Windows 11, you can try any other method in this article.

1. Open the**Settings** menu by pressing the**Win + I** hotkeys.
2. Choose the**Personalization** option.
3. Select**Taskbar** from the left panel.
4. Scroll down and click the**Turn system icon on or off** option under the**Notification** area.  
![Turn system icons on or off option in Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-system-icons-on-or-off.png)
5. In the new window that crops up, disable the toggle next to**Clock.**  
![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134240/18498" target="_top" id="2134240">
  <img src="//a.impactradius-go.com/display-ad/18498-2134240" border="0" alt="https://techidaily.com" width="540" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134240/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to[access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<span id="1983588">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983588.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983588">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983588.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983588%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983588/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The[Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll[open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .

<!-- affiliate ads begin -->
<span id="1983471">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983471%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983471/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902273/19272" target="_top" id="1902273">
  <img src="//a.impactradius-go.com/display-ad/19272-1902273" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902273/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

## Remove Any Distraction from the Taskbar

 The system tray clock helps you to keep track of the date and time. But if it has become a distraction or you want to keep the taskbar clean, you can use either of the above methods to configure the taskbar to hide the clock and date.

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
<li><a href="https://fox-helps.techidaily.com/new-in-2024-advanced-tips-for-zoom-meetings-on-chromebooks/"><u>[New] In 2024, Advanced Tips for Zoom Meetings on ChromeBooks</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-ideal-blueprint-top-6-fresh-mojave-homes/"><u>[Updated] In 2024, Ideal Blueprint Top 6 Fresh Mojave Homes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-defective-gestures-in-microsofts-os/"><u>Fixing Defective Gestures in Microsoft's OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-video-lag-in-vlc-media-player-on-windows/"><u>How to Fix Video Lag in VLC Media Player on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-repair-image-id-0x80780119-on-windows-os/"><u>How To Repair Image ID: 0X80780119 on Windows OS</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-oppo-a38-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Oppo A38 in Minutes | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-vivo-v27e-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Vivo V27e to Outlook | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-premier-top-selections-affordable-sbd-applications/"><u>In 2024, Premier Top Selections Affordable SBD Applications</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-tactics-for-boosting-vhs-quality-through-digital-tools/"><u>In 2024, Top Tactics for Boosting VHS Quality Through Digital Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/selective-vmm-recommendations-for-windows-11-success/"><u>Selective VMM Recommendations for Windows 11 Success</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-art-of-photo-edits-a-newcomers-guide-to-lunapic/"><u>The Art of Photo Edits A Newcomer’s Guide to LunaPic</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-guide-to-fixing-microsofts-screen-mirroring-glitches-on-windows-11/"><u>The Ultimate Guide to Fixing Microsoft's Screen Mirroring Glitches on Windows 11</u></a></li>
</ul></div>

