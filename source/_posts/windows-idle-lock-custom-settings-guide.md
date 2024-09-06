---
title: "Windows Idle Lock: Custom Settings Guide"
date: 2024-09-05T19:32:03.952Z
updated: 2024-09-06T19:32:03.952Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Idle Lock: Custom Settings Guide"
excerpt: "This Article Describes Windows Idle Lock: Custom Settings Guide"
keywords: Windows Locking Mode,Custom PC Configurations,Idle Screen Controls,System Performance Tuning,Windows Security Features,Optimizing Windows Sleep,Idle Time Management
thumbnail: https://thmb.techidaily.com/08702778e13a63a51dde09a4b23ab862a68808a42d3ab8c5759ae25bd6bbada4.jpg
---

## Windows Idle Lock: Custom Settings Guide

 PC security is not just about having antivirus software on your computer. You should also restrict access to your documents on your PC while you're away from your machine.

 Read on to explore how you can automatically lock your PC after a set time, even when you leave it unattended.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135401/19272" target="_top" id="2135401">
  <img src="//a.impactradius-go.com/display-ad/19272-2135401" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135401/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Keep Your Windows PC Inaccessible While Your Gone

 There are lots of places you could use a PC or laptop. It could be in the office, at a conference venue, or on the go at your favorite café. And there'll be times you just need to get up to attend to something pressing.

 Fortunately, you can set your PC to lock automatically after a custom amount of time without activity. This means you can safely leave your work desk, knowing your work is safe from prying eyes.

 Of course, you can also lock your PC manually when you walk away from it—just press the**Win + L** keys together or**Ctrl + Alt + Del** and then sign out. But you could miss doing that in a rush, or if you're distracted.

 Instead, check out these methods to configure your Windows PC to lock automatically when there is no activity after a specific amount of time.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135369/19272" target="_top" id="2135369">
  <img src="//a.impactradius-go.com/display-ad/19272-2135369" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135369/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. How to Lock Your Windows PC After a Set Time via the Local Security Policy

 Using the Local Security Policy, you can set the exact time in seconds after which your PC will lock itself automatically. Make sure you're signed in as an administrator to automatically lock your PC.

 Local Security Policy is only available in the Windows 10 and 11 Pro, Education, and Enterprise editions. If you're using the Home version, skip to method two.

1. Type**Local Security Policy** in Windows Search. Click the**Local Security Policy** under**Best match** to open it. Alternatively, press the**Win + R** keys together to open the**Run** box. Type**secpol.msc** in the**Open** navigation bar and click**OK** or hit**Enter** to launch it.  
![Open Local Security Policy via Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-local-security-policy-via-run.jpg)
2. Click the down arrow next to**Local Policies** in the left pane to expand it.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136623/26400" target="_top" id="2136623">
  <img src="//a.impactradius-go.com/display-ad/26400-2136623" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136623/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Click on**Security Options** to open it.
4. The Security Options will open up in the right pane. Now scroll down to the policy named**Interactive logon: Machine inactivity limit** and double-click on it to open its properties.  
![Machine Inactivity Limit Selected in Security Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-machine-inactivity-limit-in-security-options.jpg)
5. Under the section**Machine will be locked after** , enter the time in seconds after which you want your PC to get locked automatically. This time is the time of machine inactivity or the time when your PC is idle. You can enter the time between**0** to**599940** seconds. For this tutorial, we'll enter**300 seconds** which is five minutes. Now click on**Apply** and then**OK** .
6. Finally, close the Local Security Policy window and restart your computer for the change to take effect.

 Now, when you use your PC, you will experience that your PC will lock itself after your custom timer expires. And if someone tries to unlock your PC while you're gone, it'll ask them for your password, which should keep them at bay until you get back.

 If you ever want to reverse this action and not have your PC lock automatically, just open the**Interactive logon: Machine inactivity limit** policy in**Local Security Policy** . Then just change the time or seconds to**0** —this is the default setting and will not lock your PC automatically.

## 2\. How to Lock Your Windows PC After a Specific Amount of Inactivity via the Registry Editor

 You can tweak settings in the Registry Editor to configure your PC to lock automatically after a set time. And you can do this in Windows Home and all the other Windows editions.

 However, you must be careful while making changes in the registry and should only make the changes as detailed below and not change anything else. It'd be a good idea to create a restore point in Windows before you change your registry settings. If something goes wrong, you can revert your PC to its last working state.

 Now let's go ahead and explore how to lock your PC automatically via the Registry Editor.

1. Type**Registry Editor** in**Windows Search** and select**Registry Editor** under**Best match** . Or use one of the many[ways to open the Registry Editor in Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click on**Yes** on the UAC prompt.
3. In the left pane, use the following path to reach the**System** registry key: **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System**  
![Navigate to System Key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/navigate-to-system-key-in-registry-editor.jpg)
4. Click on the**System** key in the left pane and its components will open up in the right pane. Now scroll down to get to the**InactivityTimeoutSecs** DWORD.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118315/7443" target="_top" id="2118315">
  <img src="//a.impactradius-go.com/display-ad/7443-2118315" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118315/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Scroll to InactivityTimeoutSecs in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/scroll-to-inactivitytimeoutsecs.jpg)
5. Double-click on the**InactivityTimeoutSecs** DWORD to modify its value. Select**Decimal** under**Base** , and under**Value data** , enter a number between**0** to**599940** —this is the time in seconds after which your PC will get locked automatically. Like in the Local Security Policy method, we'll give it a time of**300 seconds** or five minutes. Now tap on**OK** .
<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014853/22899" target="_top" id="2014853">
  <img src="//a.impactradius-go.com/display-ad/22899-2014853" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014853/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. In case you do not find the**InactivityTimeoutSecs** DWORD in your registry, you can create it. Right-click on the**System** key folder in the left pane or right-click on a space in the right pane of the**System** key. Select**New** , then select**DWORD (32-bit) Value** .  
![Create InactivityTimeoutSecs DWORD in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-inactivitytimeoutsecs-dword.jpg)  
 A new value will be created in the right pane. Name it**InactivityTimeoutSecs** . Then press**Enter** .
7. Now double-click on**InactivityTimeoutSecs** DWORD, and enter the time after which you want your PC to get locked.
8. Finally, close the Registry Editor and restart your PC to apply the changes.

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also[explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

 To stop your PC from getting locked automatically, modify the**InactivityTimeoutSecs** DWORD value in the Registry Editor by changing the time to**0** seconds.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135402/19272" target="_top" id="2135402">
  <img src="//a.impactradius-go.com/display-ad/19272-2135402" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135402/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-capture.techidaily.com/new-fives-best-quick-reliable-time-lapse-tools/"><u>[New] Five's Best  Quick, Reliable Time-Lapse Tools</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-a-step-by-step-guide-for-effective-use-of-luts-in-adobe-suite/"><u>[Updated] A Step-by-Step Guide for Effective Use of LUTs in Adobe Suite</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-keeping-memories-above-ground-selecting-the-best-cloud-storage/"><u>[Updated] Keeping Memories Above Ground  Selecting the Best Cloud Storage</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-massive-subscriber-jump-for-a-sensible-5-investment-for-2024/"><u>[Updated] Massive Subscriber Jump for a Sensible $5 Investment for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-hearing-the-norths-call-top-spots-to-download-tts-files/"><u>2024 Approved  Hearing the North's Call  Top Spots to Download TTS Files</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/affordable-laptop-friendly-software-for-dvd-viewing-for-2024/"><u>Affordable, Laptop-Friendly Software for DVD Viewing for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/bridging-the-gap-mondlys-tech-for-student-success/"><u>Bridging the Gap: Mondly's Tech for Student Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-and-rectifying-windowss-c0000005-complication/"><u>Demystifying and Rectifying Windows's C0000005 Complication</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-and-repairing-error-0xc0000001/"><u>Diagnosing and Repairing Error 0xC0000001</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-audiovisual-data-flow-in-windows/"><u>Dissecting Audiovisual Data Flow in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-insights-budgeted-windows-11-codes/"><u>Exclusive Insights: Budgeted Windows 11 Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-to-windows-11-safe-mode-via-easy-methods/"><u>Fast Track to Windows 11 Safe Mode via Easy Methods</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-latest-version-of-broadcoms-bluetooth-software-for-windows-1087-users/"><u>Get the Latest Version of Broadcom's Bluetooth Software for Windows 10/8/7 Users</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-lost-data-from-infinix-smart-7-hd-by-fonelab-android-recover-data/"><u>How to recover lost data from Infinix Smart 7 HD?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-samsung-galaxy-xcover-6-pro-tactical-edition-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Samsung Galaxy XCover 6 Pro Tactical Edition? | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-depth-guide-to-frozen-pleasure-viewing-tools/"><u>In-Depth Guide to Frozen Pleasure Viewing Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-your-game-running-fixes-for-roblox-on-windows-pcs/"><u>Keeping Your Game Running: Fixes for Roblox on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-recovering-without-admin-creds/"><u>Mastering Windows 11: Recovering without Admin Creds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-in-maintaining-reliable-windows-notepad-performance/"><u>Mastery in Maintaining Reliable Windows Notepad Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-of-fast-windows-11-app-accessing-techniques/"><u>Mastery of Fast Windows 11 App Accessing Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimization-techniques-for-quick-epic-game-access/"><u>Optimization Techniques for Quick Epic Game Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-activation-error-0x8007251d-a-step-by-step-guide/"><u>Resolving Windows Activation Error 0X8007251D: A Step-by-Step Guide</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solution-steps-for-silent-hearthstone-reviving-your-game-audio/"><u>Solution Steps for Silent Hearthstone - Reviving Your Game Audio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-pcs-safety-audit-with-wins-11-tactics/"><u>Streamline Your PC's Safety Audit with Wins 11 Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-the-pointers-pace-turn-off-acceleration-in-windows-11/"><u>Taming the Pointer's Pace: Turn Off Acceleration In Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-silent-voice-finding-expression-in-a-muted-world/"><u>The Silent Voice: Finding Expression in a Muted World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-palette-of-digital-artistic-possibilities-on-win10/"><u>The Ultimate Palette of Digital Artistic Possibilities on Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-recover-from-lost-connection-error-in-win/"><u>Tips to Recover From Lost Connection Error in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-loadlibrary-err-87-misstep/"><u>Troubleshooting LoadLibrary Err 87 Misstep</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-headset-with-single-side-functioning/"><u>Troubleshooting Windows Headset with Single Side Functioning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-and-fixing-0x0000004e-in-windows-1011/"><u>Unraveling and Fixing 0X0000004E in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-isnt-my-usb-mouse-working-on-my-laptop-top-repair-strategies-inside/"><u>Why Isn't My USB Mouse Working on My Laptop? Top Repair Strategies Inside</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-secrets-automating-selective-file-shifts/"><u>Windows 11 Secrets: Automating Selective File Shifts</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-sony-xperia-10-v-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Sony Xperia 10 V | Dr.fone</u></a></li>
</ul></div>
