---
title: Simple Steps to Deactivate Windows 11 Screensaver
date: 2024-09-05T19:40:03.697Z
updated: 2024-09-06T19:40:03.697Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Simple Steps to Deactivate Windows 11 Screensaver
excerpt: This Article Describes Simple Steps to Deactivate Windows 11 Screensaver
keywords: Deactivate Screen Saver,Disable Windows 11 Screensaver,Turn Off Screensaver,Remove Windows Screensaver,Stop Windows Screensaver,End Screensaver Feature,Cease Windows SafeScreen
thumbnail: https://thmb.techidaily.com/a6017269d4c04c5e1e1b5dd34c08e1f92a0a41c1ec409bdbe7a0807e99cdc6f4.jpg
---

## Simple Steps to Deactivate Windows 11 Screensaver

 Windows 11 has a gorgeous lock screen that serves as a gateway to the system. After that, you encounter the logon screen, which requires a password/PIN/fingerprint. But not everyone needs a lock screen and beautiful wallpaper every time they boot up their system.

 Call it a personal observation, but the lock screen adds an extra step to the login process. So, if you want to remove the lock screen and go directly to the logon screen in Windows 11, this post will offer many methods to do it.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134238/18498" target="_top" id="2134238">
  <img src="//a.impactradius-go.com/display-ad/18498-2134238" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134238/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Why Consider Disabling Your Lock Screen?

 The Windows lock screen is the first barrier to getting to the desktop. It displays a background image, date and time, and app notifications. But if you don't want to see any of those things, then disabling it makes sense. After removing the lock screen, you can go straight to the desktop after entering your PIN/Password. You can also set up a lock screen-free computer for a public computer.

 Disabling the lock screen doesn't remove the logon screen. You still have to input the PIN/Password to enter the system. You can also remove the PIN/Password requirement on the logon screen to go to the desktop faster (and if privacy isn't a concern).

 Now, you are aware of the pros and cons of disabling the lock screen. Here are the four easy methods to disable the lock screen on Windows 11.

## 1\. Use the Group Policy Editor

 The Group Policy Editor is an essential Windows administration tool. You can adjust password requirements, startup programs, and other features. Note that GPE is only available for the Professional, Ultimate, and Enterprise Windows versions. You can refer to our complete[Group Policy Editor guide](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

Here's how to disable the lock screen using Group Policy:

1. Press**Win + R** to launch the**Run** command box on your system.
2. Now, type**gpedit.msc** and hit the**Enter** key to open the**Group Policy Editor** .
3. Then go to the left-hand side panel. Navigate to **Computer Configuration > Administrative Templates > Control Panel > Personalization** .
4. Double-click on the**Do not display the lock screen** option in the Personalization options.  
![Group policy editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/Group-policy-editor-1-1.jpg)
5. A new window with detailed settings for the option will open. The**enabled** option will be active by default which means that the lock screen is active.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136615/26400" target="_top" id="2136615">
  <img src="//a.impactradius-go.com/display-ad/26400-2136615" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136615/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click on the**Disabled** Radio button to disable the lock screen on your system.  
![Disable lock screen settings in Group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/Group-policy-editor-2.jpg)
7. Now, click on the**Apply** button and click the**OK** button to finalize the changes.
8. You need to restart your system. You will notice that there is no lock screen, and you enter the login screen straight away.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115912/19272" target="_top" id="2115912">
  <img src="//a.impactradius-go.com/display-ad/19272-2115912" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115912/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Use the Registry Editor

 You can also disable the lock screen on Windows by tweaking the registry settings. But make sure to export a copy of your registry for safety purposes. It will help you revert to the previous registry settings in case of corruption. Check our detailed guide on[how to perform a registry backup](https://www.makeuseof.com/windows-11-automatic-registry-backups/) for more info.

Here's how to remove the lock screen through the registry:

1. Press the**Win key + R** to launch the**Run** command box. Now, type**regedit** in the text input box and hit the**Enter** key to launch Registry Editor.
2. Now, paste the following path in the text input area and then hit the enter key: **Computer\\HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Policies\\Microsoft\\Windows**
3. Navigate to the left-hand panel and right-click on the**Windows** key. Then select**New > Key** and name it**Personalization** .  
![Creating a new key in Registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/Registry-editor-lockscreen-1.jpg)
4. Right-click on Personalization and select**New > DWORD (32-bit) Value** . Name it as**NoLockScreen** .
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135406/19272" target="_top" id="2135406">
  <img src="//a.impactradius-go.com/display-ad/19272-2135406" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135406/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Double-click on the**NoLockScreen** value and set the**Value Data** to**1** . Keep the base hexadecimal.
6. Click on**OK** to apply changes and**Restart** your system. You won't see the lock screen when your computer boots up.  
![Adding a DWORD value in Registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/Registry-editor-lockscreen-2.jpg)
7. To bring back the lock screen, revert the**NoLockScreen** key value to**0** .

## 3\. Use Winaero Tweaker

 You can try the Winaero Tweaker app if you find registry tweaking cumbersome. It is a free app that allows you to customize Windows beyond the basic options. The app offers a GUI interface with detailed information about what each option does.

Follow these steps to remove the lock screen with this tool:

1. Go to the[Winaero website](http://winaero.com/download-winaero-tweaker/) and download the app.**Install** the app and launch it.  
![Winaero tweaker home window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/Winaero-tweaker-1.jpg)
2. Now, go to the**Boot and Logon** option on the left-hand side menu.
3. Find the**Disable Lock Screen** option under the**Boot and Logon** section. Click on the**Disable Lock Screen** checkbox.  
![Disable lock screen in Winaero Tweaker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/Winaero-tweaker-2.jpg)
4. Now,**Restart** your system to apply the changes. You will notice that the lock screen doesn't appear anymore.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132160/7443" target="_top" id="2132160">
  <img src="//a.impactradius-go.com/display-ad/7443-2132160" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132160/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Use Ultimate Windows Tweaker

 Like Winaero Tweaker, Ultimate Windows Tweaker is a Windows customization app with a GUI interface. You can disable Windows 11 lock screen with this app with just one click. However, make sure to create a system restore point to avoid breaking an operating system feature.

 Here's how to disable the lock screen on Windows 11 using Ultimate Windows Tweaker:

1. Visit the[Ultimate Windows Tweaker website](https://www.thewindowsclub.com/ultimate-windows-tweaker-4-windows-10) and download the app.
2. Extract the Ultimate Windows Tweaker archive to a new folder.
3. Now, right-click on the**UltimateWindowsTweaker.exe** file, and select the**Run as administrator** option.
4. Click on the**Search for Tweaks** option. Type**disable lock screen** and press the**Enter** key.  
![Ultimate Windows Tweaker Search tool running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/ultimate-windows-tweaker-search-tool.jpg)
5. Double-click on the search result and the corresponding setting will appear in the app. Close the search window.
6. Click on the**Disable Lock Screen** checkbox. Then, click on the**Apply Tweaks** button and close the program.  
![Disabling Lock Screen in Ultimate Windows Tweaker on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disabling-lock-screen-in-ultimate-windows-tweaker.jpg)
7. Press**Win + L** to log off. The Windows logon screen will appear instead of the usual lock screen.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123739/7443" target="_top" id="2123739">
  <img src="//a.impactradius-go.com/display-ad/7443-2123739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123739/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114267/17093" target="_top" id="2114267">
  <img src="//a.impactradius-go.com/display-ad/17093-2114267" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114267/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Disable the Lock Screen and Log In Faster

 Using the Group Policy Editor is a bit of a learning curve. Moreover, Windows Home users do not have access to it. So, you can try out the registry tweak to disable the lock screen on Windows 11\. But if you want a GUI tool that helps you customize Windows, then Winaero Tweaker and Ultimate Windows Tweaker are both useful free app alternatives.

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
<li><a href="https://screen-video-capture.techidaily.com/new-efficient-remote-recording-a-step-by-step-guide-for-2024/"><u>[New] Efficient Remote Recording A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-dimensions-of-dreaming-vrs-story/"><u>[New] In 2024, Dimensions of Dreaming VR's Story</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-instagram-live-via-obs-technology-for-2024/"><u>[New] Instagram Live via OBS Technology for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-vsr-video-vaulter-reviews-comprehensive-guide-for-2024/"><u>[New] VSR Video Vaulter Reviews Comprehensive Guide for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-bridge-gaps-in-generations-of-viewers-6-interactive-tests-to-find-your-youtube-match/"><u>[Updated] Bridge Gaps in Generations of Viewers 6 Interactive Tests to Find Your YouTube Match</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-instagram-enhancement-the-top-tactics-for-better-storytelling/"><u>[Updated] In 2024, Instagram Enhancement The Top Tactics for Better Storytelling</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-is-sns-hdr-the-best-for-your-hdr-needs-insights/"><u>[Updated] Is SNS HDR the Best for Your HDR Needs? Insights</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-expert-recommendations-free-and-paid-hd-playback-for-pcmacos/"><u>2024 Approved Expert Recommendations Free & Paid HD Playback for PC/macOS</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-youtube-hacked-mastery-over-skipping-video-startup-techniques/"><u>2024 Approved YouTube Hacked Mastery Over Skipping Video Startup Techniques</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/beneath-the-oceans-veil-tips-for-recording-top-notch-underwater-gopro-videos-for-2024/"><u>Beneath the Ocean’s Veil Tips for Recording Top-Notch Underwater GoPro Videos for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/best-6-multilingual-video-decoders-for-2024/"><u>Best 6 Multilingual Video Decoders for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/classic-refresh-a-modern-take-on-windows-98-vibe/"><u>Classic Refresh: A Modern Take on Windows 98 Vibe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-error-e1-for-surface-go-win10/"><u>Correcting Error E1 for Surface Go (Win10)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-powerhouse-exes-from-windows-bat-files/"><u>Crafting Powerhouse EXEs From Windows .bat Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-memory-the-easy-way-to-identify-ram/"><u>Decoding Windows Memory: The Easy Way to Identify RAM</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortless-installation-of-bcm20702a0-drivers-on-your-pc-download-now/"><u>Effortless Installation of BCM20702A0 Drivers on Your PC: Download Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-apples-messaging-protocol-in-windows-10/"><u>Enabling Apple's Messaging Protocol in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-efficiency-best-windows-to-dos-uncovered/"><u>Enhancing Efficiency: Best Windows To-Dos Uncovered</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-knowledge-on-vcplusplus-distribution/"><u>Essential Knowledge on VC++ Distribution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-theme-options-a-comprehensive-guide-for-windows-users/"><u>Exploring Theme Options: A Comprehensive Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-and-fortify-dotnet-windows-style-max-156/"><u>Fix & Fortify DotNet, Windows Style (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-to-your-capture-application-fast-in-windows-11/"><u>Getting to Your Capture Application Fast in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/guides-to-solve-unplayable-video-files-on-windows/"><u>Guides to Solve Unplayable Video Files on Windows</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-on-xiaomi-redmi-12-5g-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Xiaomi Redmi 12 5G Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-eliminate-non-playable-video-files-on-pc/"><u>How to Eliminate Non-Playable Video Files on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-separate-graphic-card-on-win-1011/"><u>How To Enable Separate Graphic Card on Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-disabled-firewall-in-windows-os/"><u>How to Reactivate Disabled Firewall in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-recover-pasting-functionality-in-top-browsers/"><u>How to Recover Pasting Functionality in Top Browsers</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-mov-files-of-phantom-v-fold-using-video-repair-utility-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and MOV files of Phantom V Fold using Video Repair Utility on Windows?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-delete-gmail-account-withwithout-password-on-google-pixel-8-by-drfone-android/"><u>In 2024, Delete Gmail Account With/Without Password On Google Pixel 8</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-realme-10t-5g-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Realme 10T 5G Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inside-the-windows-n-enigma-which-version-to-purchase/"><u>Inside the Windows N Enigma: Which Version to Purchase?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/installing-windows-11-arm-detailed-iso-based-guide/"><u>Installing Windows 11 ARM: Detailed ISO-Based Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-premium-sound-experience-windows-11-and-dolby-atmos/"><u>Integrating Premium Sound Experience: Windows 11 & Dolby Atmos</u></a></li>
<li><a href="https://extra-support.techidaily.com/prodigy-ai-image-editing-arsenal-for-2024/"><u>Prodigy AI Image Editing Arsenal for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/propel-interactive-platforms-with-stories-and-page-polling/"><u>Propel Interactive Platforms with Stories & Page Polling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovering-missing-enter-action-from-keyboard/"><u>Recovering Missing 'Enter' Action From Keyboard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-update-failure-code-0x8019/"><u>Rectifying Update Failure: Code 0X8019</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-the-point-of-interest-with-new-cursor-style/"><u>Redefine the Point of Interest with New Cursor Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-system-recovery-activation-in-the-latest-windows-os/"><u>Simplifying System Recovery Activation in the Latest Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skytop-techniques-for-elevated-fps-in-roblox/"><u>Skytop Techniques for Elevated FPS in Roblox</u></a></li>
<li><a href="https://vp-tips.techidaily.com/stay-tuned-the-release-date-for-google-pixel-9-is-set-for-august-13th/"><u>Stay Tuned! The Release Date for Google Pixel 9 Is Set for August 13Th</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-enhanced-win1011-system-graphics-memory/"><u>Step-by-Step to Enhanced Win10/11 System Graphics Memory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-instruction-office-works-installation-on-w11/"><u>Stepwise Instruction: Office Works Installation on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-transformation-from-a-simple-pin-to-a-stronger-passphrase-in-windows-11/"><u>Tackling the Transformation: From a Simple PIN to a Stronger Passphrase in Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-power-of-digital-connection-mastering-facebook-twitter-instagram-and-youtube/"><u>The Power of Digital Connection: Mastering Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-installing-and-using-outlook-preview/"><u>The Ultimate Guide to Installing and Using Outlook Preview</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/transform-your-raw-captures-into-masterpieces-with-darktable-the-ultimate-no-cost-image-editor-for-mac-and-linux-enthusiasts/"><u>Transform Your Raw Captures Into Masterpieces with Darktable, The Ultimate No-Cost Image Editor for Mac and Linux Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-window-11s-default-search-settings/"><u>Transforming Window 11'S Default Search Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-and-restore-bluetooth-devices-on-win/"><u>Troubleshoot and Restore Bluetooth Devices on WIN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-full-potential-of-wsl-2-with-docker-integration/"><u>Unlock Full Potential of WSL 2 with Docker Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-secrets-how-to-fix-the-no-server-error-in-pc-apex-legends-(156-chars/"><u>Unveiling Secrets: How to Fix the No-Server Error in PC Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-video-editing-app-can-inspire-your-children-to-make-short-moviesin-this-article-you-will-learn-more-about-some-best-video-editing-apps-for-k/"><u>Updated In 2024, Video Editing App Can Inspire Your Children to Make Short Movies,in This Article, You Will Learn More About some Best Video Editing Apps for Kids and Decide Which Video Editing App Is the Right Choice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-gamers-should-prioritize-dxvk-in-their-win-based-setup/"><u>Why Gamers Should Prioritize DXVK in Their Win-Based Setup?</u></a></li>
</ul></div>
