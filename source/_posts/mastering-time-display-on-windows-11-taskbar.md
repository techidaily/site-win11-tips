---
title: Mastering Time Display on Windows 11 Taskbar
date: 2024-08-16T01:51:50.295Z
updated: 2024-08-17T01:51:50.295Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Time Display on Windows 11 Taskbar
excerpt: This Article Describes Mastering Time Display on Windows 11 Taskbar
keywords: Win11 Taskbar Time Showcase,Mastering Windows Timers,Taskbar Time Display Tips,Time Widget in Windows 11,Windows 11 Update Monitor,Adjusting Taskbar Clock,Windows 11 Taskbar Customization
thumbnail: https://thmb.techidaily.com/d1a4704b31151e9550e9b3ab1b575cfa25b0e8f640c5b81b3310074251149c70.jpg
---

## Mastering Time Display on Windows 11 Taskbar

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to [access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The [Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .
6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-building-a-successful-livestream-empire-youtube-edition/"><u>[New] 2024 Approved  Building a Successful Livestream Empire  YouTube Edition</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-decoding-the-art-of-capturing-live-streaming-windowsmaciosandroid/"><u>[New] In 2024, Decoding the Art of Capturing Live Streaming - Windows/Mac/iOS/Android</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-nextgen-codec-battle-is-av1-trumping-vp9-quality/"><u>[New] In 2024, NextGen Codec Battle  Is AV1 Trumping VP9 Quality?</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-no-more-troubles-mastering-ipad-video-captures-now/"><u>[New] No More Troubles? Mastering iPad Video Captures Now</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-action-cam-reimagined-an-extensive-review-of-the-sj-cam-s6/"><u>[Updated] Action Cam Reimagined  An Extensive Review of the SJ-CAM S6</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-amplify-viewership-with-these-top-10-youtube-reaction-strategies-for-2024/"><u>[Updated] Amplify Viewership with These Top 10 YouTube Reaction Strategies for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-guide-to-optimal-vr-headset-selection-freedom-or-connection/"><u>[Updated] Guide to Optimal VR Headset Selection  Freedom or Connection?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-fix-the-sorry-there-is-a-problem-with-the-onedrive-servers-error-on-windows/"><u>6 Ways to Fix the “Sorry, There Is a Problem With the OneDrive Servers” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-using-the-netstat-command-in-win11/"><u>A Step-by-Step Approach: Using the Netstat Command in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-try-now-bluetooth-hurdle-on-pcs-and-tablets/"><u>Bypass 'Try Now' Bluetooth Hurdle on PCs & Tablets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparative-analysis-understanding-the-variance-between-non-microsoft-and-microsoft-account-in-os/"><u>Comparative Analysis: Understanding the Variance Between Non-Microsoft and Microsoft Account in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-the-reset-failure-count-for-incorrect-login-attempts-on-windows-11/"><u>Configuring the Reset Failure Count for Incorrect Login Attempts on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-overcapacity-alerts-for-gpt-service/"><u>Counteracting Overcapacity Alerts for GPT Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-storage-activating-windows-11s-compression/"><u>Efficient Storage: Activating Windows 11’S Compression</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/ensuring-authenticity-as-you-aspire-for-one-million-video-watches/"><u>Ensuring Authenticity as You Aspire for One Million Video Watches</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-turn-off-the-screen-lock-on-my-infinix-hot-40i-by-drfone-android-unlock-android-unlock/"><u>How to turn off the screen lock on my Infinix Hot 40i</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-zte-nubia-z60-ultra-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your ZTE Nubia Z60 Ultra | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-ghostly-movie-editing-hacks/"><u>In 2024, Ghostly Movie Editing Hacks</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-detect-and-remove-spyware-on-vivo-y200-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Remove Spyware on Vivo Y200? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-lock-your-samsung-galaxy-s23plus-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Samsung Galaxy S23+ Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-stepwise-strategies-for-unique-youtube-openers/"><u>In 2024, Stepwise Strategies for Unique YouTube Openers</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-ultimate-guide-from-xiaomi-redmi-note-12-proplus-5g-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide from Xiaomi Redmi Note 12 Pro+ 5G FRP Bypass</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unlocking-full-potential-saving-and-playing-gifs-on-iphones/"><u>In 2024, Unlocking Full Potential  Saving & Playing GIFs on iPhones</u></a></li>
<li><a href="https://android-frp.techidaily.com/latest-guide-how-to-bypass-lava-blaze-pro-5g-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Lava Blaze Pro 5G FRP Without Computer</u></a></li>
<li><a href="https://win-answers.techidaily.com/master-the-fixes-avoid-crashes-of-hogwarts-legacy-on-initial-pc-boot-using-this-easy-guide-8-methods/"><u>Master the Fixes: Avoid Crashes of Hogwarts Legacy on Initial PC Boot Using This Easy Guide (8 Methods)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-service-setups-for-an-immaculate-windows-11-launch-experience/"><u>Mastering Service Setups for an Immaculate Windows 11 Launch Experience</u></a></li>
<li><a href="https://win-able.techidaily.com/masterminds-mute-fix-restoring-audio-to-evil-genius-2/"><u>Mastermind's Mute Fix: Restoring Audio to Evil Genius 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-of-inactive-pc-device-engagement/"><u>Mastery of Inactive PC Device Engagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/network-barricades-implement-these-7-windows-protections/"><u>Network Barricades: Implement These 7 Windows Protections</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-from-fast-to-slow-a-comprehensive-guide-to-slow-motion-effects-in-windows-live-movie-maker-for-2024/"><u>New From Fast to Slow A Comprehensive Guide to Slow Motion Effects in Windows Live Movie Maker for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-windows-free-software-your-safety-priority-list/"><u>Secure Windows Free Software: Your Safety Priority List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-ineffective-windowed-discord-searches/"><u>Solutions for Ineffective Windowed Discord Searches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-inaccessible-folder-issue-fix-steps-for-windows-based-pcs/"><u>Solving 'Inaccessible Folder' Issue: Fix Steps for Windows-Based PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-music-librarys-mp3-files-to-windows-audible-cds-with-imgburn/"><u>Streamlining Your Music Library's MP3 Files to Windows' Audible CDs with ImgBurn</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-overcome-flaws-with-non-working-ccleaner-in-win1011/"><u>Techniques to Overcome Flaws with Non-Working CCleaner in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-perplexity-of-non-existent-drive-letters-in-windows-systems/"><u>The Perplexity of Non-Existent Drive Letters in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-strategies-to-eradicate-failed-rpc-in-windows/"><u>Top 5 Strategies to Eradicate Failed RPC in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-how-you-use-the-mouse-cross-border-efficiency-via-powertoys/"><u>Transforming How You Use the Mouse: Cross-Border Efficiency via PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unseen-storage-hiding-files-via-image-camouflage-windows-11-style/"><u>Unseen Storage: Hiding Files via Image Camouflage, Windows 11 Style</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-merge-videos-without-a-trace-7-best-options/"><u>Updated In 2024, Merge Videos Without a Trace 7 Best Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-kali-perfectly-integrating-linux/"><u>Win-Kali: Perfectly Integrating Linux</u></a></li>
<li><a href="https://win11-tips.techidaily.com/yourphoneexe-on-windows-benefits-and-risks-explored/"><u>YourPhone.exe on Windows - Benefits & Risks Explored</u></a></li>
</ul></div>
