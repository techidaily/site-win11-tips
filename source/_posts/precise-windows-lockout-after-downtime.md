---
title: Precise Windows Lockout After Downtime
date: 2024-08-28T01:09:52.409Z
updated: 2024-08-29T01:09:52.409Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Precise Windows Lockout After Downtime
excerpt: This Article Describes Precise Windows Lockout After Downtime
keywords: Window Lockdown,Downtime Security,Safe Windows Exit,Immediate Lockdown,Secure Window Exit,Timely Window Protection,Lockout Precision
thumbnail: https://thmb.techidaily.com/6ae69a61ee431cd865eb63071b7e7dab33df662eeb4d068d44c620780bca6c82.jpeg
---

## Precise Windows Lockout After Downtime

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
5. Under the section**Machine will be locked after** , enter the time in seconds after which you want your PC to get locked automatically. This time is the time of machine inactivity or the time when your PC is idle. You can enter the time between**0** to**599940** seconds. For this tutorial, we'll enter**300 seconds** which is five minutes. Now click on**Apply** and then**OK** .
6. Finally, close the Local Security Policy window and restart your computer for the change to take effect.

 Now, when you use your PC, you will experience that your PC will lock itself after your custom timer expires. And if someone tries to unlock your PC while you're gone, it'll ask them for your password, which should keep them at bay until you get back.

 If you ever want to reverse this action and not have your PC lock automatically, just open the**Interactive logon: Machine inactivity limit** policy in**Local Security Policy** . Then just change the time or seconds to**0** —this is the default setting and will not lock your PC automatically.

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
![Scroll to InactivityTimeoutSecs in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/scroll-to-inactivitytimeoutsecs.jpg)
5. Double-click on the**InactivityTimeoutSecs** DWORD to modify its value. Select**Decimal** under**Base** , and under**Value data** , enter a number between**0** to**599940** —this is the time in seconds after which your PC will get locked automatically. Like in the Local Security Policy method, we'll give it a time of**300 seconds** or five minutes. Now tap on**OK** .
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
6. In case you do not find the**InactivityTimeoutSecs** DWORD in your registry, you can create it. Right-click on the**System** key folder in the left pane or right-click on a space in the right pane of the**System** key. Select**New** , then select**DWORD (32-bit) Value** .  
![Create InactivityTimeoutSecs DWORD in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-inactivitytimeoutsecs-dword.jpg)  
 A new value will be created in the right pane. Name it**InactivityTimeoutSecs** . Then press**Enter** .
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
7. Now double-click on**InactivityTimeoutSecs** DWORD, and enter the time after which you want your PC to get locked.
8. Finally, close the Registry Editor and restart your PC to apply the changes.

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also[explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

 To stop your PC from getting locked automatically, modify the**InactivityTimeoutSecs** DWORD value in the Registry Editor by changing the time to**0** seconds.

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-enhance-video-quality-by-cutting-out-background-sounds/"><u>[New] 2024 Approved  Enhance Video Quality by Cutting Out Background Sounds</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-smart-social-media-strategies-from-youtube-to-facebook/"><u>[New] In 2024, Smart Social Media Strategies  From YouTube To Facebook</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-top-10-apps-for-creating-spectacular-instagram-reels-for-2024/"><u>[New] Top 10 Apps for Creating Spectacular Instagram Reels for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-ultimate-list-of-youtube-entrance-software/"><u>[Updated] Ultimate List of YouTube Entrance Software</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-immerse-in-vocal-customization-for-playstation-devices/"><u>2024 Approved  Immerse in Vocal Customization for PlayStation Devices</u></a></li>
<li><a href="https://network-issues.techidaily.com/correcting-failed-save-of-display-preferences/"><u>Correcting Failed Save of Display Preferences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deactivating-random-openings-of-file-explorer/"><u>Deactivating Random Openings of File Explorer</u></a></li>
<li><a href="https://fox-http.techidaily.com/decoding-shake-reduction-in-photoshop-does-it-matter/"><u>Decoding Shake Reduction in Photoshop  Does It Matter?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decrypting-secure-connections-windows-11s-hidden-tricks/"><u>Decrypting Secure Connections: Windows 11'S Hidden Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/digital-duo-dynamics-syncing-your-mobile-and-computer/"><u>Digital Duo Dynamics: Syncing Your Mobile & Computer</u></a></li>
<li><a href="https://extra-resources.techidaily.com/dreamscape-films-entering-vr-worlds/"><u>Dreamscape Films  Entering VR Worlds</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/enhancing-your-content-10-exceptional-reacting-techniques-for-2024/"><u>Enhancing Your Content  10 Exceptional Reacting Techniques for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enlightening-on-high-fidelity-window-images/"><u>Enlightening on High-Fidelity Window Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-temperature-tracker-guide/"><u>Essential Windows Temperature Tracker Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/explore-our-selection-of-top-rated-free-roku-platforms-2024-edition/"><u>Explore Our Selection of Top-Rated Free Roku Platforms - 2024 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-your-windows-ssd-with-win-plus-ssfresh-techniques/"><u>Fast-Track Your Windows SSD with Win + SSFresh Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-elusive-obs-recording-error-in-windows-11/"><u>Fixing Elusive OBS Recording Error in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-glitches-on-windows-11-sound-error-code-0xc00d36b4/"><u>Fixing Glitches on Windows 11: Sound Error, Code 0xC00D36B4</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-too-little-memory-warning-for-virtual-machines/"><u>Fixing Too Little Memory Warning for Virtual Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guides-to-overcome-camera-error-on-win11-system/"><u>Guides to Overcome Camera Error on Win11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-default-search-window-action-windows-11-guide/"><u>Halt Default Search Window Action, Windows 11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/handling-error-other-software-misusing-your-pc-speakers/"><u>Handling Error: Other Software Misusing Your PC Speakers</u></a></li>
<li><a href="https://youtube-help.techidaily.com/harmonize-your-preferences-how-to-create-an-engaging-youtube-playlist-for-2024/"><u>Harmonize Your Preferences  How to Create an Engaging YouTube Playlist for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-windows-search-illustration/"><u>How to Remove Windows Search Illustration</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-honor-magic-6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Honor Magic 6 Pro? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-infinix-smart-8-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Infinix Smart 8 Phone Hassle-Free</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-thrive-with-1000-new-followers-each-month/"><u>In 2024, Thrive with 1,000 New Followers Each Month</u></a></li>
<li><a href="https://win11-tips.techidaily.com/locate-the-unseen-control-settings-on-new-windows-win11/"><u>Locate the Unseen: Control Settings on New Windows Win11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-oneplus-12r-device-by-drfone-android/"><u>Mastering Android Device Manager The Ultimate Guide to Unlocking Your OnePlus 12R Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-removing-epic-games-from-w11/"><u>Mastering the Art of Removing Epic Games From W11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/mastery-in-gameye-advanced-recording-tips/"><u>Mastery in GamEye  Advanced Recording Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-your-hardware-space-w10-and-w11-insights/"><u>Navigating Your Hardware Space: W10 & W11 Insights</u></a></li>
<li><a href="https://howto.techidaily.com/nokia-g310-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Nokia G310 Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/opting-out-of-built-in-pc-graphics-on-windows-os/"><u>Opting Out of Built-In PC Graphics on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/push-beyond-the-limits-yuzu-emulator-speed/"><u>Push Beyond the Limits: Yuzu Emulator Speed</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/reconciling-windows-10-visual-discrepancies/"><u>Reconciling Windows 10 Visual Discrepancies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-low-usb-port-space-on-desktops/"><u>Rectifying Low USB Port Space on Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-the-shortcomings-of-discord-search-on-windows-devices/"><u>Rectifying the Shortcomings of Discord Search on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstall-success-fixing-clipchamp-on-windows-11/"><u>Reinstall Success: Fixing ClipChamp on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-nvidia-display-issue-in-control-panel/"><u>Resolving Nvidia Display Issue in Control Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-optimal-operation-of-windows-metrics-tool/"><u>Restoring Optimal Operation of Windows Metrics Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/saving-the-day-with-win1011s-recycle-bin-corruption-fixed/"><u>Saving the Day with Win10/11's Recycle Bin Corruption Fixed!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-restore-non-functional-network-in-win-os/"><u>Solutions to Restore Non-Functional Network in Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-ease-through-the-waiting-gpsvc/"><u>Strategies to Ease Through the Waiting GPSVC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-thumbnails-on-your-pc-a-guide/"><u>Tailoring Thumbnails on Your PC: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-path-to-high-end-audio-installing-dolby-atmos-on-pc/"><u>The Path to High-End Audio: Installing Dolby Atmos on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-missing-graphics-driver-on-windows-overwatch-2/"><u>Troubleshooting Missing Graphics Driver on Windows (Overwatch 2)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-generic-volume-control-fix-guide/"><u>Unblocking Windows Generic Volume Control: Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-wintoys-a-primer-on-windows-powerhouse-tool/"><u>Understanding 'WinToys': A Primer on Windows' Powerhouse Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-password-power-mastering-the-11-methods-for-credential-management-on-win11/"><u>Unleash Password Power: Mastering the 11 Methods for Credential Management on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-steps-to-engage-wordpad-in-win-os/"><u>Unveiling the Steps to Engage WordPad in Win OS</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-slow-down-your-footage-10-video-editing-software-for-stunning-results/"><u>Updated Slow Down Your Footage 10 Video Editing Software for Stunning Results</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-10-artists-choice-best-7-drawing-apps-ranked/"><u>Windows 10 Artists' Choice: Best 7 Drawing Apps Ranked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-s-mode-functionality-and-purpose/"><u>Windows 11 S Mode: Functionality and Purpose?</u></a></li>
</ul></div>
