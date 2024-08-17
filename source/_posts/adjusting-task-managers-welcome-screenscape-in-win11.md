---
title: Adjusting Task Manager's Welcome Screenscape in Win11
date: 2024-08-16T02:28:18.118Z
updated: 2024-08-17T02:28:18.118Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Task Manager's Welcome Screenscape in Win11
excerpt: This Article Describes Adjusting Task Manager's Welcome Screenscape in Win11
keywords: Win11 Task Screensaver Update,Manage WM11 Taskbar Title,Windows 11 Task Manager Tweak,Set WM11 Welcome Screen,Customize WM11 TaskBar,Change WM11 Startup Image,Modify WM11 Task Preview
thumbnail: https://thmb.techidaily.com/b43da9b8fec14dde01c0becd6729005fd0db59f099a461c4a5b1f228776ffdea.jpg
---

## Adjusting Task Manager's Welcome Screenscape in Win11

 The Task Manager provides a quick overview of your system's current status and shows essential information. Its Start page displays useful details such as currently running background processes, applications, CPU, and memory utilization. If you'd like to customize its appearance, change the Start page. In this article, we’ll look at how to change the Task Manager Start page in Windows 11\.

## 1\. Use Task Manager Settings

 If you want to quickly change the Task Manager Start page, you can use its Settings tab. This option requires no modification to the registry editor or additional scripts to run.

 To change the Task Manager Start page using Task Manager settings, do the following.

1. Press **Win + R** to open the Run dialog box.
2. Type **taskmgr** and press **Enter** to launch Task Manager.
3. Once in Task Manager, click on **Settings** (the gear icon).
4. You'll see a **Default Start Page** drop-down menu at the top. This is where you can select the page to display when Task Manager opens.  
![Use Settings to Change Task Manager Start Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-settings-to-change-task-manager-start-page.jpg)

 The options available are the following:

1. Processes
2. Performance
3. App history
4. Startup apps
5. Users
6. Details
7. Services ​​​​

 Once you make a selection, Task Manager will remember the setting and open the page you chose from now on.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
## 2\. Tweak the Registry Editor

 The Registry Editor is another way to change the default Start page for Task Manager. The procedure is slightly more complex than using Task Manager Settings, but it offers more customization options. Be careful when modifying entries in the Registry Editor, as incorrect changes can cause errors or system instability. To avoid losing data, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To change the Task Manager Start page using the Registry Editor, follow these steps.

1. [Open the Registry Editor window](https://www.makeuseof.com/windows-11-open-registry-editor/).
2. If the UAC prompt pops up, click **Yes** to grant administrative rights.
3. In the left pane, navigate to the following key.  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\TaskManager`
4. Double-click **StartUpTab** in the right pane. If there is no such entry, then right-click on the Task Manager key.
5. From the context menu, select **New > DWORD (32-bit) Value**.
6. Now name the value **StartUpTab** and double-click on it.  
![Modify Registry to Change Task Manager Start Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modify-registry-to-change-task-manager-start-page.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
7. Set its **Value data** to one of the following numbers to change the default start page:  
`0 = Processes  

1 = Performance  

2 = App history  

3 = Startup apps  

4 = Users  

5 = Details  

6 = Services`
8. Click **OK** to save the changes and close the Registry Editor window.

 Next time you open Task Manager, it will display a page according to your preferences.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Use a REG File

 If the registry editor isn't your thing, you can use a REG file to modify the Task Manager start page. The process does not require registry tweaking and is straightforward.

 To create a .reg file, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and type the following:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\TaskManager]  
  
"StartUpTab"=dword:00000000`

 Here, the last digit reflects the type of Start page.

 For example, if you want to set **Processes** as your default start page, use **0** (**00000000**). Similarly, if you want the **Details** page to display as default, set it to **5** (**00000005**).

 The other options are:

`00000001 - Performance  
  
00000002 - App history  
  
00000003 - Startup apps  
  
00000004 - Users  
  
00000006 - Services`

 Now, click **File** and select **Save as**. In the Save as dialog box, click the Save as type drop-down menu and select **All files**. Name the file with the **.reg** extension. For example, **TaskManagerStartPage.reg**.

![Use a REG File to Change Task Manager Start Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-a-reg-file-to-change-task-manager-start-page.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->

 Next, select **Desktop** from the left pane and click **Save**. Once saved, double-click on this newly created REG file. This adds the required details to the Registry Editor and changes the Task Manager start page.

 If you ever want to revert the changes, delete the REG file and restart your computer.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Changing the Task Manager Start Page on Windows

 It’s easy to customize Task Manager and change its Start page according to your preference. You can use Task Manager Settings, the Registry Editor, or a REG file to set the desired page. Once you have set the Start page, Task Manager will remember it and open that page when you launch it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-bringing-youtube-home-to-your-instagram-story/"><u>[New] 2024 Approved  Bringing YouTube Home to Your Instagram Story</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-quick-guide-to-troubleshoot-instagram-videos/"><u>[New] 2024 Approved  Quick Guide to Troubleshoot Instagram Videos</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-step-by-step-guide-countdown-timer-setup-for-broadcasts/"><u>[New] In 2024, Step-by-Step Guide  Countdown Timer Setup for Broadcasts</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-time-saving-strategies-for-gotomeeting-audiovideo-logging/"><u>[New] In 2024, Time-Saving Strategies for GoToMeeting Audio/Video Logging</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-macbook-cam-tutorial-for-smooth-video-capture-for-2024/"><u>[New] MacBook Cam Tutorial for Smooth Video Capture for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-top-strategies-for-ps4-video-game-preservation-for-2024/"><u>[New] Top Strategies for PS4 Video Game Preservation for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-become-the-brand-you-want-with-our-exclusive-set-of-free-graphics/"><u>[Updated] 2024 Approved  Become the Brand You Want With Our Exclusive Set of FREE Graphics!</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-exclusive-catalogue-free-to-use-stock-media-sites/"><u>[Updated] 2024 Approved  Exclusive Catalogue  Free-to-Use Stock Media Sites</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-facebook-live-video-downloaders-how-to-download-live-videos-for-2024/"><u>[Updated] Facebook Live Video Downloaders | How to Download Live Videos for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-fb-video-grabber-win-mac-and-mobile/"><u>[Updated] FB Video Grabber - Win, Mac & Mobile</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-launchpad-gear-list-enhance-your-beginners-gopro-journey-for-2024/"><u>[Updated] Launchpad Gear List - Enhance Your Beginner's GoPro Journey for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-overcoming-full-screen-issues-in-obs-for-2024/"><u>[Updated] Overcoming Full Screen Issues in Obs for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-pro-tips-for-capturing-stunning-igtv-content-on-mobile-and-dslr-for-2024/"><u>[Updated] Pro Tips for Capturing Stunning IGTV Content on Mobile & DSLR for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-stream-to-record-essential-know-how-for-tv-capture-for-2024/"><u>[Updated] Stream to Record  Essential Know-How for TV Capture for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-next-gen-learning-vrs-educational-impact/"><u>2024 Approved  Next-Gen Learning  VR's Educational Impact</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-the-ultimate-glossary-of-youtube-shorts-terms/"><u>2024 Approved  The Ultimate Glossary of YouTube Shorts Terms</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-poco-m6-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Poco M6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/acknowledging-talent-free-to-own-outro-templates/"><u>Acknowledging Talent  Free-to-Own Outro Templates</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/apples-wwdc-2025-spotlight-unveiling-the-next-generation-of-ios-and-beyond/"><u>Apple's WWDC 2025 Spotlight: Unveiling the Next Generation of iOS & Beyond</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/best-alarm-app-selection-a-list-of-the-7-highest-rated-options/"><u>Best Alarm App Selection: A List of the 7 Highest-Rated Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-error-0xca00a009-from-windows-update-logs/"><u>Clearing Error 0xCA00A009 From Windows Update Logs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-0x8007045d-failure-on-microsoft-oses/"><u>Correcting 0X8007045D Failure on Microsoft OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/craft-secure-quick-access-button-in-windows-11-for-hardware-unhook/"><u>Craft Secure, Quick Access Button in Windows 11 for Hardware Unhook</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/craft-viral-instagram-moments-by-incorporating-tiktok-wisdom/"><u>Craft Viral Instagram Moments by Incorporating TikTok Wisdom</u></a></li>
<li><a href="https://games-able.techidaily.com/deciding-on-a-cpu-cooler-the-must-know-8-factors/"><u>Deciding on a CPU Cooler: The Must-Know 8 Factors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-your-pcs-intel-processor-gen-through-windows/"><u>Deciphering Your PC's Intel Processor Gen Through Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-resolving-win11-installation-anomalies-quickly/"><u>Decoding and Resolving Win11 Installation Anomalies Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/device-disconnection-remedy-with-dxgi-error-solution/"><u>Device Disconnection Remedy with DXGI Error Solution</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/discover-the-latest-in-pc-hardware-expert-insights-from-toms-tech-corner/"><u>Discover the Latest in PC Hardware: Expert Insights From Tom's Tech Corner</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-steps-to-stabilize-screen-flickering-in-windows/"><u>Effective Steps to Stabilize Screen Flickering in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-system-fixes-via-hotkey-configurations-in-w1011/"><u>Efficient System Fixes via Hotkey Configurations in W10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-collaboration-with-these-5-innovative-windows-folder-techniques/"><u>Enhance Collaboration with These 5 Innovative Windows Folder Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explaining-and-solving-the-problem-of-missing-windows-drive-letters/"><u>Explaining and Solving The Problem Of Missing Windows Drive Letters</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-infinix-zero-30-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Infinix Zero 30 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidance-to-overcome-same-user-account-error-on-pc/"><u>Guidance to Overcome Same-User Account Error on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-minimize-explore-tab-noise-in-windows/"><u>How to Minimize Explore Tab Noise in Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-sharefake-location-on-whatsapp-for-tecno-spark-20-pro-drfone-by-drfone-virtual-android/"><u>How to Share/Fake Location on WhatsApp for Tecno Spark 20 Pro | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-oppo-a1x-5g-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Oppo A1x 5G? | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/improve-printer-functionality-hp-laserjet-driver-updates-for-win10/"><u>Improve Printer Functionality: HP Laserjet Driver Updates for WIN10</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-gps-location-on-realme-12-5g-easily-and-safely-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change GPS Location on Realme 12 5G Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-how-to-change-your-xiaomi-redmi-13c-5g-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Your Xiaomi Redmi 13C 5G Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-is-your-apple-iphone-6-plus-in-security-lockout-proper-ways-to-unlock-by-drfone-ios/"><u>In 2024, Is Your Apple iPhone 6 Plus in Security Lockout? Proper Ways To Unlock</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-navigating-online-broadcasts-expertise-in-onestream-use/"><u>In 2024, Navigating Online Broadcasts  Expertise in OneStream Use</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-new-guide-how-to-check-icloud-activation-lock-status-on-your-apple-iphone-15-pro-max-by-drfone-ios/"><u>In 2024, New Guide How To Check iCloud Activation Lock Status On Your Apple iPhone 15 Pro Max</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-quickscreencapture-mastery-for-everyday-use/"><u>In 2024, QuickScreenCapture Mastery for Everyday Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-out-invaders-effective-windows-access-blockers/"><u>Keeping Out Invaders: Effective Windows Access Blockers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-high-gpu-activity-in-windows-desktop-window/"><u>Managing High GPU Activity in Windows Desktop Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-full-hd-classics-proven-scummvm-strategies-for-the-windows-aficionado/"><u>Mastering Full HD Classics: Proven ScummVM Strategies for the Windows Aficionado</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-formatting-essential-disk-error-on-pc/"><u>Navigating the 'Formatting Essential' Disk Error on PC</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-get-noticed-top-rated-free-animated-logo-creators-plus-creative-insights/"><u>New 2024 Approved Get Noticed Top-Rated Free Animated Logo Creators + Creative Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimum-virtual-options-tailored-for-windows-11-systems/"><u>Optimum Virtual Options Tailored for Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x80242016-error-in-windows-updates/"><u>Overcoming 0X80242016 Error in Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-buffering-issues-on-chrome-and-youtube/"><u>Overcoming Buffering Issues on Chrome & YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-obstacles-in-package-registration-on-windows-1011/"><u>Overcoming Obstacles in Package Registration on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventive-tips-the-top-7-windows-activities-that-could-be-risky/"><u>Preventive Tips: The Top 7 Windows Activities That Could Be Risky</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-your-pc-resetting-windows-11-applications/"><u>Refreshing Your PC: Resetting Windows 11 Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-wi-fi-harmony-top-solutions-to-cure-non-functioning-usb-on-windows/"><u>Regain Wi-Fi Harmony: Top Solutions to Cure Non-Functioning USB on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-device-opens-on-audacity-in-windows-os/"><u>Remedying Device Opens on Audacity in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sketchmasters-roundup-top-7-drawing-tools-for-windows/"><u>SketchMasters Roundup: Top 7 Drawing Tools for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smarter-operating-systems-ais-role-in-windows-revolution/"><u>Smarter Operating Systems: AI's Role in Windows Revolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-launch-into-lotr-world-lol/"><u>Smooth Launch Into LOTR World (LOL)</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/snapcutmaster-insights-full-video-editor-evaluation-for-2024/"><u>SnapCutMaster Insights – Full Video Editor Evaluation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-cross-language-switching-hotkeys-in-windows-1011/"><u>Speedy Cross-Language Switching: Hotkeys in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-audacity-audio-error-win1011/"><u>Strategies to Overcome Audacity Audio Error (Win10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/time-traveling-computers-into-the-windows-11-era-with-old-tools/"><u>Time Traveling Computers Into the Windows 11 Era with Old Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-preventing-unwanted-command-window-activation/"><u>Tips for Preventing Unwanted Command Window Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transferring-older-pc-tools-from-legacy-systems-to-windows-11/"><u>Transferring Older PC Tools: From Legacy Systems to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unified-workspace-managing-windows-folders-and-files/"><u>Unified Workspace: Managing Windows Folders & Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unison-and-phone-link-debate-best-windows-phone-app-evaluation/"><u>Unison & Phone Link Debate: Best Windows Phone App Evaluation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-assistive-features-a-quick-guide/"><u>Unlocking Windows' Assistive Features: A Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-windows-software-to-supercharge-macos-functionality/"><u>Utilizing Windows Software to Supercharge macOS Functionality</u></a></li>
<li><a href="https://win-blog.techidaily.com/warframe-wont-start-heres-how-you-can-fix-it/"><u>Warframe Won't Start? Here's How You Can Fix It!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-yourphoneexe-necessary-or-not-for-security/"><u>Windows' YourPhone.exe - Necessary or Not for Security?</u></a></li>
</ul></div>
