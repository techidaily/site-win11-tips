---
title: "Windows: Define Your Own Idle Time"
date: 2024-08-16T01:45:17.226Z
updated: 2024-08-17T01:45:17.226Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows: Define Your Own Idle Time"
excerpt: "This Article Describes Windows: Define Your Own Idle Time"
keywords: Windows Idle Settings,Personalize Idle Time,Custom Idle in Windows,Window's Power Options,Optimize Computer Idle,Adjust Windows Sleep Timer,Manage System Standby
thumbnail: https://thmb.techidaily.com/4f408d1e600338fdfbc4fe3abf110c58fed31529d9f9f53c6cd72af0ec21a5e5.jpg
---

## Windows: Define Your Own Idle Time

 PC security is not just about having antivirus software on your computer. You should also restrict access to your documents on your PC while you're away from your machine.

 Read on to explore how you can automatically lock your PC after a set time, even when you leave it unattended.

## How to Keep Your Windows PC Inaccessible While Your Gone

 There are lots of places you could use a PC or laptop. It could be in the office, at a conference venue, or on the go at your favorite café. And there'll be times you just need to get up to attend to something pressing.

 Fortunately, you can set your PC to lock automatically after a custom amount of time without activity. This means you can safely leave your work desk, knowing your work is safe from prying eyes.

 Of course, you can also lock your PC manually when you walk away from it—just press the**Win + L** keys together or**Ctrl + Alt + Del** and then sign out. But you could miss doing that in a rush, or if you're distracted.

 Instead, check out these methods to configure your Windows PC to lock automatically when there is no activity after a specific amount of time.

## 1\. How to Lock Your Windows PC After a Set Time via the Local Security Policy

 Using the Local Security Policy, you can set the exact time in seconds after which your PC will lock itself automatically. Make sure you're signed in as an administrator to automatically lock your PC.

 Local Security Policy is only available in the Windows 10 and 11 Pro, Education, and Enterprise editions. If you're using the Home version, skip to method two.

1. Type**Local Security Policy** in Windows Search. Click the**Local Security Policy** under**Best match** to open it. Alternatively, press the**Win + R** keys together to open the**Run** box. Type**secpol.msc** in the**Open** navigation bar and click**OK** or hit**Enter** to launch it.  
![Open Local Security Policy via Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-local-security-policy-via-run.jpg)
2. Click the down arrow next to**Local Policies** in the left pane to expand it.
3. Click on**Security Options** to open it.
4. The Security Options will open up in the right pane. Now scroll down to the policy named**Interactive logon: Machine inactivity limit** and double-click on it to open its properties.  
![Machine Inactivity Limit Selected in Security Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-machine-inactivity-limit-in-security-options.jpg)
<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Under the section**Machine will be locked after** , enter the time in seconds after which you want your PC to get locked automatically. This time is the time of machine inactivity or the time when your PC is idle. You can enter the time between**0** to**599940** seconds. For this tutorial, we'll enter**300 seconds** which is five minutes. Now click on**Apply** and then**OK** .
6. Finally, close the Local Security Policy window and restart your computer for the change to take effect.

 Now, when you use your PC, you will experience that your PC will lock itself after your custom timer expires. And if someone tries to unlock your PC while you're gone, it'll ask them for your password, which should keep them at bay until you get back.

 If you ever want to reverse this action and not have your PC lock automatically, just open the**Interactive logon: Machine inactivity limit** policy in**Local Security Policy** . Then just change the time or seconds to**0** —this is the default setting and will not lock your PC automatically.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
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
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click on the**System** key in the left pane and its components will open up in the right pane. Now scroll down to get to the**InactivityTimeoutSecs** DWORD.  
![Scroll to InactivityTimeoutSecs in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/scroll-to-inactivitytimeoutsecs.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Double-click on the**InactivityTimeoutSecs** DWORD to modify its value. Select**Decimal** under**Base** , and under**Value data** , enter a number between**0** to**599940** —this is the time in seconds after which your PC will get locked automatically. Like in the Local Security Policy method, we'll give it a time of**300 seconds** or five minutes. Now tap on**OK** .
6. In case you do not find the**InactivityTimeoutSecs** DWORD in your registry, you can create it. Right-click on the**System** key folder in the left pane or right-click on a space in the right pane of the**System** key. Select**New** , then select**DWORD (32-bit) Value** .  
![Create InactivityTimeoutSecs DWORD in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-inactivitytimeoutsecs-dword.jpg)  
<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 A new value will be created in the right pane. Name it**InactivityTimeoutSecs** . Then press**Enter** .
7. Now double-click on**InactivityTimeoutSecs** DWORD, and enter the time after which you want your PC to get locked.
8. Finally, close the Registry Editor and restart your PC to apply the changes.

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also [explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

 To stop your PC from getting locked automatically, modify the**InactivityTimeoutSecs** DWORD value in the Registry Editor by changing the time to**0** seconds.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://snapchat-videos.techidaily.com/updated-screen-capturing-on-snapchat-a-guide-for-smartphones-for-2024/"><u>[Updated] Screen Capturing on Snapchat - A Guide for Smartphones for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-navigate-macs-screen-capture-like-a-pro-with-simple-keys/"><u>2024 Approved  Navigate Mac's Screen Capture Like a Pro with Simple Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-reasons-to-use-the-new-outlook-app-on-windows/"><u>9 Reasons to Use the New Outlook App on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-fresh-windows-11-approach-to-system-cleanliness/"><u>A Fresh Windows 11 Approach to System Cleanliness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-event-viewer-breakdowns/"><u>Addressing Windows Event Viewer Breakdowns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automating-iphones-calendar-into-windows-os/"><u>Automating iPhone's Calendar Into Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaching-windows-login-restrictions-a-quick-guide/"><u>Breaching Windows Login Restrictions: A Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-a-global-keyboard-downloading-windows-fonts/"><u>Crafting a Global Keyboard: Downloading Windows Fonts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-oculus-quest-to-function-in-windows-vr/"><u>Customizing Oculus Quest to Function in Windows VR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dial-up-decibels-the-top-4-programs-to-increase-volume-on-windows/"><u>Dial Up Decibels: The Top 4 Programs to Increase Volume on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-pathway-to-create-high-quality-audio-cds-from-mp3-files-using-imgburn-windows/"><u>Easy Pathway to Create High Quality Audio Cds From MP3 Files Using ImgBurn (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-method-integrating-airpods-with-windows/"><u>Efficient Method: Integrating AirPods with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/error-code-0x80242016-stopping-windows-updates/"><u>Error Code 0X80242016 Stopping Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/excellent-windows-apps-transforming-videos/"><u>Excellent Windows Apps Transforming Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-self-scrolled-windows-with-ease-and-precision/"><u>Fix Self-Scrolled Windows with Ease and Precision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-improving-win11-point-accuracy-and-size/"><u>Guide to Improving Win11' Point Accuracy & Size</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reinstate-your-devices-access-post-error-22/"><u>Guide to Reinstate Your Device's Access Post Error 22</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mend-flickering-screens-in-windows-11/"><u>How to Mend Flickering Screens in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rescue-your-vscode-session-w11/"><u>How to Rescue Your VSCode Session W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-0x0000011b-failures-in-windows-os/"><u>How to Stop 0X0000011B Failures in Windows OS</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-mastering-visual-effects-on-a-budget-essential-tutorials-and-techniques-from-4-vfx-experts-videos/"><u>In 2024, Mastering Visual Effects on a Budget  Essential Tutorials and Techniques From 4 VFX Experts' Videos</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-vivo-y27-4g-drfone-by-drfone-virtual-android/"><u>In 2024, The Best iSpoofer Alternative to Try On Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-realme-12plus-5g-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Realme 12+ 5G</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-itel-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost Itel Device</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-triggering-instant-play-for-youtube-videos-on-social-media/"><u>In 2024, Triggering Instant Play for YouTube Videos on Social Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-moves-for-unlocking-the-calculator-in-windows-11/"><u>Key Moves for Unlocking the Calculator in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-adding-wordpad-shortcut-accessibility/"><u>Mastering Windows 11: Adding WordPad Shortcut Accessibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-0x00000001-barrier-in-game-access/"><u>Overcoming the 0X00000001 Barrier in Game Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-captcha-troubles-in-steam/"><u>Overcoming Windows CAPTCHA Troubles in Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-effortless-transition-in-windows-terminals-attention-mode/"><u>Quick Fix: Effortless Transition in Windows Terminal’s Attention Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamping-gpos-a-step-by-step-guide-for-windows-users/"><u>Revamping GPOs: A Step-by-Step Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-bypass-windows-admin-installation-restriction-error/"><u>Steps to Bypass Windows 'Admin Installation Restriction' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-file-backup-with-windows-11/"><u>Streamlining File Backup with Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/supercharge-videos-download-premium-effs-in-2024/"><u>Supercharge Videos - Download Premium Effs, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-prevent-unintentional-erasure-of-panel-settings-by-cp/"><u>Techniques to Prevent Unintentional Erasure of Panel Settings by CP</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-12-prominent-vivo-y56-5g-fingerprint-not-working-solutions-by-drfone-android/"><u>Top 12 Prominent Vivo Y56 5G Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-workspace-win-11s-finest-productivity-tools/"><u>Transform Your Workspace: Win 11'S Finest Productivity Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tweak-windows-11-shutdown-procedure-for-active-operations/"><u>Tweak Windows 11 Shutdown Procedure for Active Operations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-11-bluescreen-mastery-through-11-fixes/"><u>Unraveling Windows 11 Bluescreen: Mastery Through 11 Fixes</u></a></li>
<li><a href="https://techidaily.com/useful-ways-that-can-help-to-effectively-recover-deleted-files-from-samsung-galaxy-s21-fe-5g-2023-by-fonelab-android-recover-data/"><u>Useful ways that can help to effectively recover deleted files from Samsung Galaxy S21 FE 5G (2023)</u></a></li>
<li><a href="https://facebook.techidaily.com/1719152117996-will-the-verdict-fall-soon-facebooks-governance-on-trump-ban/"><u>Will the Verdict Fall Soon? Facebook's Governance on Trump Ban.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win10win11-troubleshooting-hardware-recognition-issues/"><u>Win10/Win11: Troubleshooting Hardware Recognition Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-and-artificial-intelligence-generating-vibrant-ai-graphics-paint-cocreator/"><u>Windows 11 & Artificial Intelligence: Generating Vibrant AI Graphics (Paint Cocreator)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workaround-cease-discord-startup-and-update-checks-in-windows/"><u>Workaround: Cease Discord Startup and Update Checks in Windows</u></a></li>
</ul></div>
