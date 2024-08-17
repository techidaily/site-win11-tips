---
title: Navigating Date & Time Settings on Desktop Toolbars
date: 2024-08-16T02:35:24.648Z
updated: 2024-08-17T02:35:24.648Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Date & Time Settings on Desktop Toolbars
excerpt: This Article Describes Navigating Date & Time Settings on Desktop Toolbars
keywords: Date & Time Settings Guide,Desktop Toolbar Customization,Adjusting Timers Quickly,Calendar Icon Management,Time Format Changes Ease,Schedule Control in Tools,UI Layout for Dates/Times
thumbnail: https://thmb.techidaily.com/c2ff7acd78dea76e7429574a96f5d83925797a8b18bf953373ef1ee065acd190.jpg
---

## Navigating Date & Time Settings on Desktop Toolbars

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
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
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .
6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)
<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-sneak-peek-to-secrecy-how-to-create-hidden-stories/"><u>[New] 2024 Approved  Sneak Peek to Secrecy  How to Create Hidden Stories</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-social-media-strategy-broadcasting-twitch-to-facebook-for-2024/"><u>[New] Social Media Strategy  Broadcasting Twitch to Facebook for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-bushido-code-continuation-top-similar-game-experiences/"><u>[Updated] 2024 Approved  Bushido Code Continuation - Top Similar Game Experiences</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-the-silent-watchers-best-instagram-apps/"><u>[Updated] 2024 Approved  The Silent Watchers' Best Instagram Apps</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-expert-guide-to-optimizing-solo-play-in-apex-legends-for-2024/"><u>[Updated] Expert Guide to Optimizing Solo Play in Apex Legends for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-avoiding-youtubes-controversial-scrutiny/"><u>[Updated] In 2024, Avoiding YouTube's Controversial Scrutiny</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-essential-tools-for-efficient-mp4-segmentation-on-mac/"><u>[Updated] In 2024, Essential Tools for Efficient MP4 Segmentation on Mac</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-tips-to-counteract-obs-fullscreen-woes-for-2024/"><u>[Updated] Tips to Counteract OBS Fullscreen Woes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-ways-to-open-the-control-panel-on-windows/"><u>11 Ways to Open the Control Panel on Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-unleash-your-potential-with-these-top-12-pc-clickers/"><u>2024 Approved  Unleash Your Potential with These Top 12 PC Clickers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-essential-steps-to-clear-overflowing-c-drive-data/"><u>3 Essential Steps to Clear Overflowing C: Drive Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-calendar-revolution-customizing-your-scheduling-tool-on-windows-pc/"><u>A Calendar Revolution: Customizing Your Scheduling Tool on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-fresh-windows-beginning-navigating-3-reset-routes/"><u>A Fresh Windows Beginning: Navigating 3 Reset Routes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-eliminate-hardware-detection-faults/"><u>A Quick Guide to Eliminate Hardware Detection Faults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-windows-11-desk-drawings/"><u>A Step-by-Step Guide to Windows 11 Desk Drawings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-file-management-with-seamless-multi-folder-crafting-on-windows-pcs/"><u>Accelerate File Management with Seamless Multi-Folder Crafting on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-access-boosting-morning-routine-and-note-openings/"><u>Accelerated Access: Boosting Morning Routine & Note Openings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-recently-used-windows-with-ease/"><u>Accessing Recently Used Windows with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-academic-excellence-winning-strategies-for-efficient-windows-learning/"><u>Achieve Academic Excellence: Winning Strategies for Efficient Windows Learning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-optimal-performance-with-powertoys-win11/"><u>Achieving Optimal Performance with PowerToys (Win11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-end-task-bar-functionality-in-windows-11/"><u>Activating End Task Bar Functionality in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/address-vanishing-hardware-problems-in-dm/"><u>Address Vanishing Hardware Problems In DM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incorrect-side-by-side-setup-on-windows-os/"><u>Addressing 'Incorrect Side-by-Side Setup' On Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-directx-update-problems-in-windows-os/"><u>Addressing DirectX Update Problems in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-insufficient-installation-privilege-issue-on-win-1011/"><u>Addressing Insufficient Installation Privilege Issue on Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-spooler-service-error-on-windows-systems/"><u>Addressing Spooler Service Error on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-taskbar-icon-glitches-in-win-108/"><u>Addressing Taskbar Icon Glitches in Win 10/8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-fresh-installation-displays-fail-to-start/"><u>Addressing Windows' Fresh Installation: Displays Fail To Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-guidelines-integrating-latest-intel-wireless-tech-in-os-x/"><u>Advanced Guidelines: Integrating Latest Intel Wireless Tech in OS X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tactics-for-superior-windows-navigation-eliminating-ls/"><u>Advanced Tactics for Superior Windows Navigation: Eliminating LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amend-f-key-malfunctions-restore-control-in-windows-11/"><u>Amend: F Key Malfunctions - Restore Control in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/antivirus-alert-7-significant-windows-functions-under-scrutiny/"><u>Antivirus Alert: 7 Significant Windows Functions Under Scrutiny</u></a></li>
<li><a href="https://win11-tips.techidaily.com/are-some-websites-not-opening-in-any-browser-on-windows-7-ways-to-fix-it/"><u>Are Some Websites Not Opening in Any Browser on Windows? 7 Ways to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-deadlock-in-windows-desktop-menu-navigation/"><u>Avoiding Deadlock in Windows Desktop Menu Navigation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-high-temperature-troubleshooting-tips-w11/"><u>Avoiding High-Temperature Troubleshooting Tips: W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-unwanted-termination-messages-in-roblox-games/"><u>Avoiding Unwanted Termination Messages in Roblox Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windowed-app-movement-windows-task-managing-tips/"><u>Avoiding Windowed App Movement: Windows Task Managing Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windows-11-lock-screen-effortlessly/"><u>Avoiding Windows 11 Lock Screen Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-the-black-glare-from-window-8-displays/"><u>Banishing the Black Glare From Window 8 Displays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-code-ai-reshaping-windows-tech-landscape/"><u>Beyond Code: AI Reshaping Windows Tech Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-setting-up-automatic-deletions-in-win11/"><u>Boost Productivity: Setting Up Automatic Deletions in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-system-management-via-cmd/"><u>Boost Your System Management via CMD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-performance-on-windows-11-top-seven-tweaks-for-game-enthusiasts/"><u>Boosting Performance on Windows 11: Top Seven Tweaks for Game Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-error-e8024002e-for-updates/"><u>Bypassing Windows Error E:8024002E for Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363006980-discover-solutions-for-programs-that-dont-work-on-vistawindows-7/"><u>Discover Solutions for Programs that Don't Work on Vista/Windows 7</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortless-guide-to-finding-and-updating-konica-minolta-printing-software/"><u>Effortless Guide to Finding & Updating Konica Minolta Printing Software</u></a></li>
<li><a href="https://extra-information.techidaily.com/enter-the-world-of-games-with-a-single-funimate-apk-download/"><u>Enter the World of Games with a Single Funimate APK Download</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719192555427-environment-variables-configuration/"><u>Environment Variables Configuration:</u></a></li>
<li><a href="https://some-techniques.techidaily.com/gimbal-guide-to-pro-video-shooting-with-dslrs-and-mirrorless-for-2024/"><u>Gimbal Guide to Pro Video Shooting with DSLRs & Mirrorless for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/hidden-shotsnappers-advanced-techniques-for-invisible-image-capturing-on-snapchat/"><u>Hidden ShotSnappers  Advanced Techniques for Invisible Image Capturing on Snapchat</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-or-downgrade-iphone-8-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade iPhone 8 Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-realme-gt-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Dose Life360 Notify Me When Someone Checks My Location On Realme GT 5 Pro? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-easy-fixes-how-to-recover-forgotten-icloud-password-from-your-apple-iphone-15-pro-max-by-drfone-ios/"><u>In 2024, Easy Fixes How To Recover Forgotten iCloud Password From your Apple iPhone 15 Pro Max</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-fly-high-with-gopro-karma-an-insiders-review/"><u>In 2024, Fly High with GoPro Karma  An Insider's Review</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-quick-guide-resolving-obs-skipping-problems/"><u>In 2024, Quick Guide  Resolving OBS Skipping Problems</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-drone-enthusiasts-compendium-of-must-haves/"><u>In 2024, The Drone Enthusiast's Compendium of Must-Haves</u></a></li>
<li><a href="https://win-solutions.techidaily.com/mass-effect-legendary-edition-performance-fixed-no-more-freezing-frames/"><u>Mass Effect Legendary Edition Performance Fixed - No More Freezing Frames</u></a></li>
<li><a href="https://fix-guide.techidaily.com/my-videos-arent-playing-on-vivo-y100i-power-5g-what-can-i-do-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>My Videos Arent Playing on Vivo Y100i Power 5G – What Can I Do? | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-best-4k-proxy-video-editing-software-for-creators/"><u>New 2024 Approved Best 4K Proxy Video Editing Software for Creators</u></a></li>
<li><a href="https://extra-resources.techidaily.com/raspberry-router-image-maker/"><u>Raspberry Router  Image Maker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719353940627-resolve-icloud-install-issues-on-windows-quickly/"><u>Resolve iCloud Install Issues on Windows Quickly!</u></a></li>
<li><a href="https://some-skills.techidaily.com/superior-titles-for-live-game-broadcasting-for-2024/"><u>Superior Titles for Live Game Broadcasting for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719332049172-swiftly-addressing-windows-faults-with-easy-fixes/"><u>Swiftly Addressing Windows Faults with Easy Fixes!</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-fixing-no-audio-on-your-hp-laptop-running-windows-10/"><u>Troubleshooting: Fixing No Audio on Your HP Laptop Running Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719358153094-unlocking-cloud-storage-integrating-dropbox-and-google-drive-via-c/"><u>Unlocking Cloud Storage: Integrating Dropbox and Google Drive via C:</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-beginners-guide-to-enhancing-imovie-productions-with-audio-for-2024/"><u>Updated Beginners Guide to Enhancing iMovie Productions with Audio for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722965613141-usb-connectivity-woes-resolve-your-260ci-wia-driver-problem-today/"><u>USB Connectivity Woes? Resolve Your 260Ci WiA Driver Problem Today</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/why-the-macbook-pro-16-inch-with-m1-chip-202n-is-apples-finest-laptop-yet/"><u>Why the MacBook Pro 16-Inch with M1 Chip (202N) Is Apple's Finest Laptop Yet</u></a></li>
</ul></div>
