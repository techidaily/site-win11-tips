---
title: Personalized Inactive Screen Time Windows
date: 2024-07-12T17:10:09.035Z
updated: 2024-07-13T17:10:09.035Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Personalized Inactive Screen Time Windows
excerpt: This Article Describes Personalized Inactive Screen Time Windows
keywords: Personalized Sleep Windows,Active Screen Time Custom,Inactive Usage Alerts,Tailored Downtime Hours,Individual Tech Breaks,Smart Rest Intervals,Unique Idle Periods
thumbnail: https://thmb.techidaily.com/c225407e5eb523ea35626965d7952f3e8eff461a435028604a3c634507f598f5.png
---

## Personalized Inactive Screen Time Windows

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

## 2\. How to Lock Your Windows PC After a Specific Amount of Inactivity via the Registry Editor

 You can tweak settings in the Registry Editor to configure your PC to lock automatically after a set time. And you can do this in Windows Home and all the other Windows editions.

 However, you must be careful while making changes in the registry and should only make the changes as detailed below and not change anything else. It'd be a good idea to create a restore point in Windows before you change your registry settings. If something goes wrong, you can revert your PC to its last working state.

 Now let's go ahead and explore how to lock your PC automatically via the Registry Editor.

1. Type**Registry Editor** in**Windows Search** and select**Registry Editor** under**Best match** . Or use one of the many [ways to open the Registry Editor in Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click on**Yes** on the UAC prompt.
3. In the left pane, use the following path to reach the**System** registry key: **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System**  
![Navigate to System Key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/navigate-to-system-key-in-registry-editor.jpg)
4. Click on the**System** key in the left pane and its components will open up in the right pane. Now scroll down to get to the**InactivityTimeoutSecs** DWORD.  
![Scroll to InactivityTimeoutSecs in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/scroll-to-inactivitytimeoutsecs.jpg)
5. Double-click on the**InactivityTimeoutSecs** DWORD to modify its value. Select**Decimal** under**Base** , and under**Value data** , enter a number between**0** to**599940** —this is the time in seconds after which your PC will get locked automatically. Like in the Local Security Policy method, we'll give it a time of**300 seconds** or five minutes. Now tap on**OK** .
6. In case you do not find the**InactivityTimeoutSecs** DWORD in your registry, you can create it. Right-click on the**System** key folder in the left pane or right-click on a space in the right pane of the**System** key. Select**New** , then select**DWORD (32-bit) Value** .  
![Create InactivityTimeoutSecs DWORD in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-inactivitytimeoutsecs-dword.jpg)  
 A new value will be created in the right pane. Name it**InactivityTimeoutSecs** . Then press**Enter** .
7. Now double-click on**InactivityTimeoutSecs** DWORD, and enter the time after which you want your PC to get locked.
8. Finally, close the Registry Editor and restart your PC to apply the changes.

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also [explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

 To stop your PC from getting locked automatically, modify the**InactivityTimeoutSecs** DWORD value in the Registry Editor by changing the time to**0** seconds.

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
<li><a href="https://video-content-creator.techidaily.com/new-voice-over-mastery-essential-fcp-recording-hacks/"><u>New Voice Over Mastery Essential FCP Recording Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-graphic-memory-in-windows-11-systems/"><u>Upgrading Graphic Memory in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-text-selection-in-windows-compatible-pdfs/"><u>Mastering Text Selection in Windows-Compatible PDFs</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-approaches-to-retaining-musical-pitch-while-diminishing-song-speed/"><u>Updated 2024 Approved Approaches to Retaining Musical Pitch While Diminishing Song Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-altering-window-icons-distance-on-11plus-windows/"><u>Title: Altering Window Icons' Distance on 11+ Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-popular-rainmeter-problems-in-windows-systems/"><u>Troubleshooting Popular Rainmeter Problems in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-guide-to-instant-uninstalling-via-windows-shortcuts/"><u>The Guide to Instant Uninstalling via Windows Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-persistent-microsoft-edge-shortcuts/"><u>Preventing Persistent Microsoft Edge Shortcuts</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-can-i-get-more-stardust-in-pokemon-go-on-realme-11-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How can I get more stardust in pokemon go On Realme 11 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-aid-unlocking-essential-assistive-tech/"><u>Windows Aid: Unlocking Essential Assistive Tech</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-mastering-the-use-and-maintenance-of-m1-max-clips/"><u>[Updated] In 2024, Mastering the Use and Maintenance of M1 Max Clips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-vlc-unrecognized-media-issue/"><u>Overcoming Windows VLC Unrecognized Media Issue</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-transforming-ideas-into-viral-video-hits-on-youtube/"><u>In 2024, Transforming Ideas Into Viral Video Hits on YouTube</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-8-plus-to-android-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 8 Plus to Android? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-runtime-brokers-in-computing/"><u>Unraveling the Mystery of Runtime Brokers in Computing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-of-windows-photo-viewer-in-win11/"><u>Restoring Functionality of Windows Photo Viewer in Win11</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-wave-for-sonys-s6700-blu-ray-player/"><u>New Wave for Sony's S6700 Blu-Ray Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-surface-computer-firmware-update-manual/"><u>The Ultimate Surface Computer Firmware Update Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-file-explorer-in-windows-10plus/"><u>Jumpstart File Explorer in Windows 10+</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-best-free-and-open-source-video-editing-tools-for-linux/"><u>In 2024, Best Free and Open-Source Video Editing Tools for Linux</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-clis-for-efficient-task-management-windows-11/"><u>Integrating CLIs for Efficient Task Management (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-directdraw-crashes-in-win11-a-step-by-step-guide/"><u>Solving DirectDraw Crashes in Win11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-missing-data-from-windows-1011s-search-feature/"><u>Restoring Missing Data From Windows 10/11'S Search Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-identity-under-threat-are-biometrics-safe/"><u>Windows Identity Under Threat: Are Biometrics Safe?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-bypassing-ssi-and-installing-unverified-drivers/"><u>Mastering Windows: Bypassing SSI & Installing Unverified Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correcting-file-errors-in-windows-11/"><u>Steps to Correcting File Errors in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-tackling-steam-disk-errors/"><u>Understanding and Tackling Steam Disk Errors</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-top-10-hilarious-tweets-galore/"><u>[Updated] Top 10 Hilarious Tweets Galore</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-default-sound-level-configurations-in-windows/"><u>Restoring Default Sound Level Configurations in Windows</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-the-ultimate-guide-to-free-mod-video-editors-top-5/"><u>2024 Approved The Ultimate Guide to Free MOD Video Editors Top 5</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-oppo-reno-10-proplus-5g-drfone-by-drfone-virtual-android/"><u>How to Change Location on TikTok to See More Content On your Oppo Reno 10 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-explorer-onedrive-as-a-launchpad/"><u>Mastering File Explorer: OneDrive as a Launchpad</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/direct-download-of-youtube-content-for-2024/"><u>Direct Download of YouTube Content for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/nextgencams-investigation-pushing-the-envelope-further-for-2024/"><u>NextGenCams Investigation  Pushing the Envelope Further for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-motorola-edge-40-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Motorola Edge 40? Fixed | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-your-go-to-list-asmr-on-phone-platforms/"><u>[New] Your Go-To List  ASMR on Phone Platforms</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-flash-dead-motorola-moto-g34-5g-safely-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Flash Dead Motorola Moto G34 5G Safely | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-no-write-error-a-guide-for-windows-users/"><u>Tackling the No Write Error: A Guide for Windows Users</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-realme-narzo-n53-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Realme Narzo N53 | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-windows-8-video-editor-edit-mp4-files-with-ease/"><u>Updated In 2024, Windows 8 Video Editor Edit MP4 Files with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-5-best-pc-optimization-tools-on-a-windows-pc/"><u>The 5 Best PC Optimization Tools on a Windows PC</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-intro-to-using-snap-camera-effectively-in-meetings/"><u>[Updated] 2024 Approved  Intro to Using Snap Camera Effectively in Meetings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unison-vs-phone-link-for-windows-phone-users-explored/"><u>Unison Vs. Phone Link for Windows Phone Users Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-perils-behind-budget-windows-activation-codes/"><u>The Hidden Perils Behind Budget Windows Activation Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-code-0x80070091-empty-directories-unveiled/"><u>Tackling Windows Error Code 0X80070091 - Empty Directories Unveiled</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/infographic-forecast-the-2023-social-landscape-for-2024/"><u>Infographic Forecast  The 2023 Social Landscape for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-the-elite-selection-of-instagram-image-boosters/"><u>In 2024, The Elite Selection of Instagram Image Boosters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-charging-windows-printer-performance/"><u>Turbo-Charging WIndows Printer Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-route-to-your-windows-disk-space-win-1011/"><u>Quick Route to Your Windows Disk Space (Win 10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-microsoft-store-error-x80072f30-in-windows/"><u>Resolving Microsoft Store Error X80072F30 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-the-calendar-app-on-windows-11/"><u>How to Use the Calendar App on Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-honor-x50i-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Honor X50i to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-samsung-galaxy-s23-tactical-edition-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Samsung Galaxy S23 Tactical Edition Is Unlocked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-the-endless-cycle-of-windows-ui-issues/"><u>Stop the Endless Cycle of Windows UI Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wrinkle-free-up-operator-installation/"><u>Windows Wrinkle? Free Up Operator Installation</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-vivo-y78t-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Vivo Y78t Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-sleek-design-and-stunning-video-quality-in-sony-xperia-xz/"><u>[New] Sleek Design and Stunning Video Quality in Sony Xperia XZ</u></a></li>
<li><a href="https://techidaily.com/hard-reset-lava-blaze-2-5g-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Lava Blaze 2 5G in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/immersive-virtue-verse-selection-for-ar-vr-worlds-for-2024/"><u>Immersive Virtue Verse Selection for AR-VR Worlds for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-advanced-shortcuts-into-windows-explorer-menus/"><u>Integrating Advanced Shortcuts Into Windows Explorer Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-shortage-of-physical-storage-space-vm-errors/"><u>Resolving Shortage of Physical Storage Space (VM) Errors</u></a></li>
<li><a href="https://fox-http.techidaily.com/demystifying-syncopated-soundscapes-via-crossfading/"><u>Demystifying Syncopated Soundscapes via Crossfading</u></a></li>
</ul></div>
