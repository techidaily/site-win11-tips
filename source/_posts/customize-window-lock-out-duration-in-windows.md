---
title: Customize Window Lock-Out Duration in Windows
date: 2024-08-16T01:46:31.276Z
updated: 2024-08-17T01:46:31.276Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customize Window Lock-Out Duration in Windows
excerpt: This Article Describes Customize Window Lock-Out Duration in Windows
keywords: Customizable Window Security,Set Lockout Time Windows,Adjust Windows Lock Timer,Personalized Window Lock Settings,Window Lock Out Controls,Dynamic Window Lock Duration,Fine-Tune Window Lock Period
thumbnail: https://thmb.techidaily.com/9e54865f3f57ec57dc69d69631538169245afb52f02b58f105955b7146a11c16.jpg
---

## Customize Window Lock-Out Duration in Windows

 PC security is not just about having antivirus software on your computer. You should also restrict access to your documents on your PC while you're away from your machine.

 Read on to explore how you can automatically lock your PC after a set time, even when you leave it unattended.

## How to Keep Your Windows PC Inaccessible While Your Gone

 There are lots of places you could use a PC or laptop. It could be in the office, at a conference venue, or on the go at your favorite café. And there'll be times you just need to get up to attend to something pressing.

 Fortunately, you can set your PC to lock automatically after a custom amount of time without activity. This means you can safely leave your work desk, knowing your work is safe from prying eyes.

 Of course, you can also lock your PC manually when you walk away from it—just press the**Win + L** keys together or**Ctrl + Alt + Del** and then sign out. But you could miss doing that in a rush, or if you're distracted.

 Instead, check out these methods to configure your Windows PC to lock automatically when there is no activity after a specific amount of time.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. How to Lock Your Windows PC After a Set Time via the Local Security Policy

 Using the Local Security Policy, you can set the exact time in seconds after which your PC will lock itself automatically. Make sure you're signed in as an administrator to automatically lock your PC.

 Local Security Policy is only available in the Windows 10 and 11 Pro, Education, and Enterprise editions. If you're using the Home version, skip to method two.

1. Type**Local Security Policy** in Windows Search. Click the**Local Security Policy** under**Best match** to open it. Alternatively, press the**Win + R** keys together to open the**Run** box. Type**secpol.msc** in the**Open** navigation bar and click**OK** or hit**Enter** to launch it.  
![Open Local Security Policy via Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-local-security-policy-via-run.jpg)
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Click the down arrow next to**Local Policies** in the left pane to expand it.
3. Click on**Security Options** to open it.
4. The Security Options will open up in the right pane. Now scroll down to the policy named**Interactive logon: Machine inactivity limit** and double-click on it to open its properties.  
![Machine Inactivity Limit Selected in Security Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-machine-inactivity-limit-in-security-options.jpg)
5. Under the section**Machine will be locked after** , enter the time in seconds after which you want your PC to get locked automatically. This time is the time of machine inactivity or the time when your PC is idle. You can enter the time between**0** to**599940** seconds. For this tutorial, we'll enter**300 seconds** which is five minutes. Now click on**Apply** and then**OK** .
6. Finally, close the Local Security Policy window and restart your computer for the change to take effect.

 Now, when you use your PC, you will experience that your PC will lock itself after your custom timer expires. And if someone tries to unlock your PC while you're gone, it'll ask them for your password, which should keep them at bay until you get back.

 If you ever want to reverse this action and not have your PC lock automatically, just open the**Interactive logon: Machine inactivity limit** policy in**Local Security Policy** . Then just change the time or seconds to**0** —this is the default setting and will not lock your PC automatically.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Lock Your Windows PC After a Specific Amount of Inactivity via the Registry Editor

 You can tweak settings in the Registry Editor to configure your PC to lock automatically after a set time. And you can do this in Windows Home and all the other Windows editions.

 However, you must be careful while making changes in the registry and should only make the changes as detailed below and not change anything else. It'd be a good idea to create a restore point in Windows before you change your registry settings. If something goes wrong, you can revert your PC to its last working state.

 Now let's go ahead and explore how to lock your PC automatically via the Registry Editor.

1. Type**Registry Editor** in**Windows Search** and select**Registry Editor** under**Best match** . Or use one of the many [ways to open the Registry Editor in Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click on**Yes** on the UAC prompt.
3. In the left pane, use the following path to reach the**System** registry key: **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System**  
![Navigate to System Key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/navigate-to-system-key-in-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
4. Click on the**System** key in the left pane and its components will open up in the right pane. Now scroll down to get to the**InactivityTimeoutSecs** DWORD.  
![Scroll to InactivityTimeoutSecs in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/scroll-to-inactivitytimeoutsecs.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
5. Double-click on the**InactivityTimeoutSecs** DWORD to modify its value. Select**Decimal** under**Base** , and under**Value data** , enter a number between**0** to**599940** —this is the time in seconds after which your PC will get locked automatically. Like in the Local Security Policy method, we'll give it a time of**300 seconds** or five minutes. Now tap on**OK** .
6. In case you do not find the**InactivityTimeoutSecs** DWORD in your registry, you can create it. Right-click on the**System** key folder in the left pane or right-click on a space in the right pane of the**System** key. Select**New** , then select**DWORD (32-bit) Value** .  
![Create InactivityTimeoutSecs DWORD in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-inactivitytimeoutsecs-dword.jpg)  
 A new value will be created in the right pane. Name it**InactivityTimeoutSecs** . Then press**Enter** .
7. Now double-click on**InactivityTimeoutSecs** DWORD, and enter the time after which you want your PC to get locked.
8. Finally, close the Registry Editor and restart your PC to apply the changes.

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also [explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

 To stop your PC from getting locked automatically, modify the**InactivityTimeoutSecs** DWORD value in the Registry Editor by changing the time to**0** seconds.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Work Worry-Free on Your Windows PC With a Custom Time-Out Lock

 Now never be tense about someone getting access to your PC or your work getting stolen while you're away from your PC. Use one of the above methods to automatically lock your PC after a set time.

 You can also explore how to set up Dynamic Lock using your phone to automatically lock your PC when you move away from it.


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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-academic-anchors-identifying-top-10-lecture-preservation-tools/"><u>[New] 2024 Approved  Academic Anchors  Identifying Top 10 Lecture Preservation Tools</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-leading-e-conference-headline-generator/"><u>[Updated] Leading E-Conference Headline Generator</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-macs-best-choices-for-mkv-file-viewing/"><u>[Updated] Mac's Best Choices for MKV File Viewing</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-step-by-step-guide-to-recording-on-your-macbook-for-2024/"><u>[Updated] Step-By-Step Guide to Recording on Your MacBook for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-unparalleled-asmr-channel-selection-for-2024/"><u>[Updated] Unparalleled ASMR Channel Selection for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-roadmap-to-irresistible-podcast-intros-and-exits/"><u>2024 Approved  The Roadmap to Irresistible Podcast Intros and Exits</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/blurry-video-woes-solved-fix-on-mobile-devices/"><u>Blurry Video Woes Solved  Fix on Mobile Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-win-valorant-resolving-01kbs-downloads/"><u>Boosting Win-Valorant: Resolving 0.1KB/S Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-window-cursor-significance-win1011-guide/"><u>Boosting Window Cursor Significance - Win10/11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-1011-functionality-add-diskspace-analyzer-menu-feature/"><u>Boosting Windows 10/11 Functionality: Add DiskSpace Analyzer Menu Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-cars-a-guide-to-free-upgrade-titans/"><u>Boosting Windows Cars: A Guide to Free Upgrade Titans</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-drive-space-without-deletion/"><u>Boosting Windows Drive Space Without Deletion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bouncing-back-from-excessive-life-enthusiasm-on-windows-systems/"><u>Bouncing Back From Excessive Life Enthusiasm on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-barriers-for-opening-photoshop-in-windows-1011/"><u>Breaking Down Barriers for Opening Photoshop in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-steam-error-dealing-with-content-restrictions/"><u>Breaking Through Steam Error: Dealing with Content Restrictions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathing-new-life-into-wt-color-schemes/"><u>Breathing New Life Into WT: Color Schemes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breezing-through-telnet-configuration-in-win11/"><u>Breezing Through Telnet Configuration in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-data-gaps-the-art-of-file-integration/"><u>Bridging Data Gaps: The Art of File Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-ios-and-windows-utilizing-apple-maps/"><u>Bridging iOS and Windows: Utilizing Apple Maps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/building-a-safe-window-shortcut-for-easy-hardware-disconnect-on-win11/"><u>Building a Safe Window Shortcut for Easy Hardware Disconnect on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-file-save-obstacles-quick-fixes-to-overcome-win11-issues/"><u>Bypass File Save Obstacles: Quick Fixes to Overcome WIN11 Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-the-brick-wall-top-fixes-for-windows-install-verification-pause/"><u>Bypass the Brick Wall: Top Fixes for Windows Install Verification Pause</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-the-worst-8-bad-habits-in-windows-11-life/"><u>Bypass the Worst: 8 Bad Habits in Windows 11 Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-extract-error-1152-in-windows-oses/"><u>Bypassing 'Extract Error 1152 in Windows OSes'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-blocks-to-your-windows-shared-stash/"><u>Bypassing Blocks to Your Window's Shared Stash</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-obstacles-solutions-for-uninstalled-optional-functions-on-windows-os/"><u>Bypassing Obstacles: Solutions for Uninstalled Optional Functions on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-past-trials-revisiting-game-accomplishments-on-steam/"><u>Bypassing Past Trials: Revisiting Game Accomplishments on Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-pin-locks-fixes-for-windows-os/"><u>Bypassing PIN Locks: Fixes for Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-quick-access-go-straight-to-file-explorer-via-onedrive/"><u>Bypassing Quick Access: Go Straight to File Explorer via OneDrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-read-only-steam-library-errors-on-windows-11/"><u>Bypassing Read-Only Steam Library Errors on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-windows-time-limited-lock/"><u>Bypassing the Window's Time-Limited Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-11-error-code-0x8004def5/"><u>Bypassing Windows 11 Error Code: 0X8004DEF5</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-update-obstacle-uptime-failure-code-0x80246007/"><u>Bypassing Windows Update Obstacle: Uptime Failure, Code 0X80246007</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capturing-sound-with-snipping-tools-screen-recorder-feature-max-156/"><u>Capturing Sound with Snipping Tool's Screen Recorder Feature (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capturing-uac-notifications-with-precision/"><u>Capturing UAC Notifications with Precision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cast-your-canvas-into-the-night-with-paints-dark-mode/"><u>Cast Your Canvas Into the Night with Paint's Dark Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-the-intrusive-windows-update-alerts/"><u>Cease the Intrusive Windows Update Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/changing-defaults-optimize-your-windows-11-device-use/"><u>Changing Defaults: Optimize Your Windows 11 Device Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-your-cutting-edge-for-windows-screenshots/"><u>Choosing Your Cutting Edge for Windows Screenshots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chrome-banners-silenced-windows-notification-guide/"><u>Chrome Banners Silenced: Windows Notification Guide</u></a></li>
<li><a href="https://media-tips.techidaily.com/easy-guide-how-to-turn-any-video-into-mp3-aac-flac-or-m4a-files/"><u>Easy Guide: How to Turn Any Video Into MP3, AAC, FLAC, or M4A Files</u></a></li>
<li><a href="https://win-answers.techidaily.com/effortless-fixes-resolve-your-lol-crashes-in-no-time/"><u>Effortless Fixes: Resolve Your LoL Crashes in No Time</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-nokia-c12-pro-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Nokia C12 Pro? | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/revamping-your-gaming-experience-resolving-risk-of-rain-2-sudden-shutdowns/"><u>Revamping Your Gaming Experience: Resolving 'Risk of Rain 2' Sudden Shutdowns</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-easy-way-to-enable-bluetooth-on-windows-11-and-10-your-complete-solution/"><u>The Easy Way to Enable Bluetooth on Windows 11 and 10 - Your Complete Solution</u></a></li>
</ul></div>
