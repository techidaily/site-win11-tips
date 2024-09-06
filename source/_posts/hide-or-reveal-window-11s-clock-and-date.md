---
title: Hide or Reveal Window 11'S Clock & Date
date: 2024-09-05T19:34:07.038Z
updated: 2024-09-06T19:34:07.038Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Hide or Reveal Window 11'S Clock & Date
excerpt: This Article Describes Hide or Reveal Window 11'S Clock & Date
keywords: Hide Clock Window 11,Reveal Dates Window 11,Hide Time Windows,Unhide Clocks 11,Show Date Windows 11,Concealed Clock 11,Expose Dates 11
thumbnail: https://thmb.techidaily.com/6368130d53d4726baee2d761c0d301b46230227e22c8ccd434c4356090bf9d54.jpg
---

## Hide or Reveal Window 11'S Clock & Date

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115934/19272" target="_top" id="2115934">
  <img src="//a.impactradius-go.com/display-ad/19272-2115934" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115934/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005184/22899" target="_top" id="2005184">
  <img src="//a.impactradius-go.com/display-ad/22899-2005184" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005184/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123471/16836" target="_top" id="2123471">
  <img src="//a.impactradius-go.com/display-ad/16836-2123471" border="0" alt="https://techidaily.com" width="234" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123471/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

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
<a href="https://aligracehair.sjv.io/c/5597632/2135402/19272" target="_top" id="2135402">
  <img src="//a.impactradius-go.com/display-ad/19272-2135402" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135402/19272" style="position:absolute;visibility:hidden;" border="0" />
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
6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

<!-- affiliate ads begin -->
<span id="1982499">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982499.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982499">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982499.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982499%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982499/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115932/19272" target="_top" id="2115932">
  <img src="//a.impactradius-go.com/display-ad/19272-2115932" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-mastering-desktop-merging-images-seamlessly/"><u>[New] 2024 Approved Mastering Desktop Merging Images Seamlessly</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-boosting-youtube-traffic-outsmarting-automated-viewers-for-2024/"><u>[New] Boosting YouTube Traffic Outsmarting Automated Viewers for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-experts-guide-swift-and-effective-sticker-removal-from-videos/"><u>[New] Expert's Guide Swift and Effective Sticker Removal From Videos</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-chordcatcher-software-insight/"><u>[New] In 2024, ChordCatcher Software Insight</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-the-5-prime-apps-for-clandestine-story-viewers/"><u>[New] The 5 Prime Apps for Clandestine Story Viewers</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-effortless-no-cost-screening-of-android-gadgets-for-2024/"><u>[Updated] Effortless, No-Cost Screening of Android Gadgets for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-evaluating-the-superiority-of-splitcams-recording/"><u>[Updated] Evaluating the Superiority of SplitCam's Recording</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-how-to-buy-youtube-views-everything-you-need-to-know/"><u>[Updated] How to Buy YouTube Views - Everything You Need To Know</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-restoring-iphone-x-identity-check-reviving-face-recognition/"><u>[Updated] Restoring iPhone X Identity Check Reviving Face Recognition</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-seize-control-of-your-viewing-experience-these-top-6-free-youtube-short-downloaders/"><u>[Updated] Seize Control of Your Viewing Experience These Top 6 Free YouTube Short Downloaders</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-youtube-rankings-secrets-enhancing-video-visibility/"><u>[Updated] YouTube Rankings Secrets Enhancing Video Visibility</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-advanced-tips-for-smooth-transitions-and-effects-in-gopro-studio/"><u>2024 Approved Advanced Tips for Smooth Transitions and Effects in GoPro Studio</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-iphone-photo-excellence-simple-tips-and-tricks/"><u>2024 Approved IPhone Photo Excellence Simple Tips & Tricks</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-motorola-razr-40-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Motorola Razr 40 | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/boosting-clarity-in-web-exhibits-and-presentations-for-2024/"><u>Boosting Clarity in Web Exhibits and Presentations for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/discover-the-best-3d-animation-makers-for-stunning-videos/"><u>Discover the Best 3D Animation Makers for Stunning Videos</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/disqus-poster-pixel-arrangement-for-2024/"><u>Disqus Poster Pixel Arrangement for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dual-virus-scanners-think-twice-windows/"><u>Dual Virus Scanners? Think Twice, Windows!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/first-aid-starting-with-windows-canary-channel/"><u>First Aid: Starting with Windows' Canary Channel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-zoom-glitches-mitigating-code-1132-in-windows-11/"><u>Fixing Zoom Glitches: Mitigating Code #1132 in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/frame-to-frame-focus-top-tactics-for-smooth-windows-streaming/"><u>Frame-to-Frame Focus: Top Tactics for Smooth Windows Streaming</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-nokia-c12-plus-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the Nokia C12 Plus Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-restore-a-pc-from-windows-11-installation-failure/"><u>How To Restore a PC From Windows 11 Installation Failure</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-poco-c55-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Poco C55 | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-tecno-spark-10-4g-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Tecno Spark 10 4G | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-expert-techniques-for-adding-borders-to-your-instagram-images/"><u>In 2024, Expert Techniques for Adding Borders to Your Instagram Images</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-list-of-pokemon-go-joysticks-on-xiaomi-redmi-note-13-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, List of Pokémon Go Joysticks On Xiaomi Redmi Note 13 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-quickening-instagram-video-streams-on-mobile-devices/"><u>In 2024, Quickening Instagram Video Streams on Mobile Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-computer-efficiency-explore-10-best-powertoys-uses/"><u>Master Your Computer Efficiency: Explore 10 Best PowerToys Uses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-credential-management-fix/"><u>Mastering the Art of Credential Management Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-missing-file-updates-on-windows-os/"><u>Mastering the Art of Fixing Missing File Updates on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-windows-10-value-with-expert-key-tips/"><u>Maximize Windows 10 Value with Expert Key Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mend-your-operatic-install-delays-with-window-wise-fixes/"><u>Mend Your Operatic Install Delays with Window Wise Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-disruptions-caused-by-windows-update-installations/"><u>Navigating Disruptions Caused by Windows Update Installations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-path-to-windows-assistant-activation/"><u>Navigating the Path to Windows Assistant Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precise-note-taking-apps-the-seven-windows-stars/"><u>Precise Note-Taking Apps: The Seven Windows Stars</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prioritizing-key-elements-in-procuring-your-ideal-windows-device/"><u>Prioritizing Key Elements in Procuring Your Ideal Windows Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-efficient-powertoys-setup-in-win11/"><u>Quick Guide: Efficient PowerToys Setup in Win11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reliable-user-guide-to-fix-vivo-t2x-5g-running-slow-and-freezing-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reliable User Guide to Fix Vivo T2x 5G Running Slow and Freezing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-your-agenda-linking-to-dot-to-ifttt/"><u>Simplify Your Agenda: Linking To-Dot to IFTTT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-update-failure-code-windows-1011-error-0x80246007/"><u>Solving Update Failure Code: Windows 10/11 Error 0X80246007</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speeding-up-windows-edge-steps-for-w10-and-w11/"><u>Speeding up Windows Edge: Steps for W10 & W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-regain-smooth-operation-of-asana-on-desktop-computers/"><u>Steps to Regain Smooth Operation of Asana on Desktop Computers</u></a></li>
<li><a href="https://some-approaches.techidaily.com/strategies-for-itunes-podcast-enrollment-success-for-2024/"><u>Strategies for iTunes Podcast Enrollment Success for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-privilege-issues-in-windows-installer-errors/"><u>Strategies to Overcome Privilege Issues in Windows Installer Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tablet-writes-transcribes-find-the-winning-seven-on-pc/"><u>Tablet' Writes, Transcribes: Find the Winning Seven on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-checklist-for-selecting-the-best-windows-pc/"><u>The Essential Checklist for Selecting the Best Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-smart-way-to-ascertain-your-windows-systems-make/"><u>The Smart Way to Ascertain Your Windows System's Make</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-window-bar-timeline-from-85-to-now/"><u>The Window Bar Timeline: From '85 to Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-ways-win11-gathers-your-digital-footprint/"><u>Top 5 Ways Win11 Gathers Your Digital Footprint</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/understanding-the-impact-of-unwanted-vibrations-on-mobile-phone-cameras-tips-for-iphones-and-androids/"><u>Understanding the Impact of Unwanted Vibrations on Mobile Phone Cameras: Tips for iPhones and Androids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11s-spotlight-icons-a-guide-to-removal/"><u>Windows 11'S Spotlight Icons: A Guide to Removal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-chatgpt-integration-steps/"><u>Windows ChatGPT Integration Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winfixer-how-to-rectify-unreachable-network-on-windows-11/"><u>Winfixer: How to Rectify Unreachable Network on Windows 11</u></a></li>
</ul></div>
