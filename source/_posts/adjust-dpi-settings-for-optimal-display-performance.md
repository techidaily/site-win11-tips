---
title: Adjust DPI Settings for Optimal Display Performance
date: 2024-08-08T10:55:34.652Z
updated: 2024-08-09T10:55:34.652Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjust DPI Settings for Optimal Display Performance
excerpt: This Article Describes Adjust DPI Settings for Optimal Display Performance
keywords: DPI Adjustment Guide,Display Performance Tips,Optimal Screen Quality,High Res Mode Enable,Resolution Settings Update,Image Clarity Boost,Display Settings Tuning
thumbnail: https://thmb.techidaily.com/8761d7ab814205b2f88e7841689a57f834d49b25e2e76dad4d19bc3d0f2882d9.jpg
---

## Adjust DPI Settings for Optimal Display Performance

 If you're looking to customize your computer experience, or just make things easier on the eyes, then changing the display DPI scaling on Windows is a great way to do that. In this helpful article, we'll provide you with an easy step-by-step guide for both registry tweaks and Windows settings so that customizing your computer can be done quickly and easily.

 Whether it's due to vision problems or if you simply want more control over how things look onscreen, these solutions are sure to help.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
## What Is DPI Scaling on Windows?

 DPI stands for "dots per inch" and it refers to the number of individual dots that can be packed into an inch of space on your screen. The higher the number, the sharper and clearer the display. But here's the thing, sometimes you might want your text and images to be bigger, while at other times, you might want them smaller. That's where DPI scaling comes in; it's your very own personal adjustment tool.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
## How to Change Display DPI Scaling via Windows Settings

 The Settings app is the simplest and easiest way to change display scaling in Windows 11\. Here's how to do it.

1. Press**Win + I** on your keyboard to open the Settings menu.
2. From the left pane of the window, click the**System** tab.
3. Click**Display** on the right side.
4. Scroll down to the**Scale and layout** section.
5. Next to the**Scale** option, click the dropdown menu and change the scaling.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
![Change DPI Scale in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-dpi-scale-in-settings.jpg)
6. Select the one that best fits your needs.

 After you've made your changes, close the window and restart your computer, so the changes take effect.

## How to Change Display DPI Scaling Using the Registry Editor

 If the Settings app isn't working, or you don't have access to it, you can change the scaling through the Registry Editor. But keep in mind that it can be a bit tricky, and you should [back up your registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes.

 To change Display DPI Scaling using Registry Editor, follow these steps:

1. Press**Win + R** on your keyboard to [open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the dialog box and hit Enter.
3. If UAC prompts on your screen, click**Yes** to continue.
4. Once you're in the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Control Panel\Desktop
5. In the right pane, right-click on**LogPixels** and select**Modify** from the context menu.  
 If you don't see the LogPixels DWORD key, you need to manually create it. For this, right-click on the empty space in the right pane and select**New > DWORD (32-bit) Value** . Upon creating the DWORD key, give it the name**LogPixels** and save it. Now click twice on the key you just created, and a pop-up will appear.

1. Choose one of the following Value data fields and set the base to**Decimal** .  
<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Change Display DPI Scaling in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-display-dpi-scaling-in-windows.jpg)  
| Value data | DPI scale                  |  
| ---------- | -------------------------- |  
| 96         | Smaller 100% (Recommended) |  
| 120        | Medium 125%                |  
| 144        | Larger 150%                |  
| 192        | Extra Large 200%           |  
| 240        | Custom 250%                |  
| 288        | Custom 300%                |  
| 384        | Custom 400%                |  
| 480        | Custom 500%                |
2. When you're done making these changes, click**OK** to save them.
3. Next, double-click**Win8DpiScaling** in the right pane. If you don't see the Win8DpiScaling DWORD key there, you must create it manually in the same way as you created LogPixels.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
![Change Display DPI Scaling Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-display-dpi-scaling-using-registry.jpg)
4. In the pop-up menu, set the Value data to**0** if you set Logpixels to 96, or**1** if you used any other value.
5. Select**Hexadecimal** as the base and click**OK** .

 After performing the above steps, restart your computer to take effect the changes. If you ever need to restore the default settings, just open Registry Editor and go to the same location. Then double-click on Win8DpiScaling and change the Value data to 0.

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Scale the Display DPI on Windows

 If you're in search of ways to give your screen a sharper and crisper look, change the DPI scaling! You can customize different elements displayed on your device like text size, icons, and more so that it's easier for you to read and navigate.


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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-forecasting-facebooks-video-trajectory-with-a-focus-on-brevity/"><u>[New] 2024 Approved  Forecasting Facebook's Video Trajectory with a Focus on Brevity</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-elevate-views-prime-seo-equipment-for-videos/"><u>[New] In 2024, Elevate Views  Prime SEO Equipment for Videos</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-share-and-celebrate-with-instagram-videos/"><u>[New] In 2024, Share & Celebrate with Instagram Videos</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-total-byte-requirement-for-24-hours-of-movie-viewing/"><u>[New] Total Byte Requirement for 24 Hours of Movie Viewing</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-essential-sandbox-experiences-for-gamers/"><u>[Updated] Essential Sandbox Experiences for Gamers</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-the-ultimate-guide-to-your-first-adobe-presenter-video-for-2024/"><u>[Updated] The Ultimate Guide to Your First Adobe Presenter Video for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-utilizing-in-device-recording-on-huawei-mate-series-phones-mate-10-mate-20-and-p-series-p20-p10/"><u>[Updated] Utilizing In-Device Recording on Huawei Mate Series Phones (Mate 10, Mate 20) & P Series (P20, P10)</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-quick-quirky-qs-how-to-save-funny-tweets-as-gifs/"><u>2024 Approved  Quick, Quirky Qs  How To Save Funny Tweets as GIFs</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-tech-savvy-strategies-recording-gotomeeting-on-any-gear/"><u>2024 Approved  Tech-Savvy Strategies  Recording GoToMeeting on Any Gear</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-fix-a-windows-device-thats-stuck-in-dark-mode/"><u>5 Ways to Fix a Windows Device That's Stuck in Dark Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-android-apps-that-youd-actually-want-to-install-on-windows-11/"><u>6 Android Apps That You’d Actually Want to Install on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-precise-methods-to-resolve-onedrive-errors/"><u>6 Precise Methods to Resolve OneDrive Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-look-at-addressing-error-code-262-on-roblox/"><u>A Comprehensive Look at Addressing Error Code 262 on Roblox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-gaining-entry-into-windows-11s-application-repository/"><u>A Guide to Gaining Entry Into Windows 11'S Application Repository</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-fixing-steam-contact-issues-on-win11/"><u>A Step-by-Step Guide to Fixing Steam Contact Issues on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-gameplay-9-tricks-to-end-wwe-2k23-freezes-in-windows/"><u>Accelerate Gameplay: 9 Tricks to End WWE 2K23 Freezes in Windows</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/ace-your-communication-discover-our-number-one-selection-of-the-8-greatest-sms-backup-software-for-iphones/"><u>Ace Your Communication: Discover Our Number One Selection of the 8 Greatest SMS Backup Software for iPhones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-optimum-ssd-speed-on-windows-via-ssdfresh/"><u>Achieve Optimum SSD Speed on Windows via SSDFresh</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-gmail-to-windows-outlook-seamless-integration-method/"><u>Adding Gmail to Windows Outlook: Seamless Integration Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-insufficient-ram-in-windows-vm-hosting-platforms/"><u>Addressing Insufficient RAM in Windows VM Hosting Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-system-id-inaccuracy-in-windows-11/"><u>Addressing System ID Inaccuracy in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-reset-account-lockouts-after-failed-logins-in-windows-11/"><u>Adjusting Reset Account Lockouts After Failed Logins in Windows 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/advance-repair-for-bad-and-corrupt-video-files-of-smart-8-pro-by-stellar-video-repair-mobile-video-repair/"><u>Advance Repair for Bad and Corrupt Video Files of Smart 8 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-task-management-adding-cli-toolbar-in-win11-taskmgr/"><u>Advanced Task Management: Adding CLI Toolbar in Win11 TaskMgr</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alteration-of-login-failure-counter-windows-11-user-guide/"><u>Alteration of Login Failure Counter: Windows 11 User Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/are-your-computer-speakers-not-working-how-to-fix-having-no-sound/"><u>Are Your Computer Speakers Not Working? How to Fix Having No Sound</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-mobility-center-activation-in-w11-systems/"><u>Avoid Mobility Center Activation in W11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-of-crashes-in-the-epic-launcher-for-win-users/"><u>Avoidance of Crashes in the Epic Launcher for Win Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-nvidia-writes-of-error-3-in-win1011/"><u>Avoiding NVIDIA' Writes of Error 3 in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-screen-glitches-in-modern-operating-systems/"><u>Banishing Screen Glitches in Modern Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-delay-in-sw-top-tips-to-speed-up-your-bf2-gameplay/"><u>Beat Delay in SW: Top Tips to Speed Up Your BF2 Gameplay</u></a></li>
<li><a href="https://fox-http.techidaily.com/bedtime-tales-in-motion-reviews-of-storytelling-videos-for-2024/"><u>Bedtime Tales in Motion  Reviews of Storytelling Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-windows-tools-for-mp4-and-mov-clips/"><u>Best Windows Tools for MP4 and MOV Clips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-minipc-extended-storage-mediocre-execution/"><u>Blackview MiniPC: Extended Storage, Mediocre Execution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-with-automated-folder-pairings-in-new-windows-os/"><u>Boost Efficiency with Automated Folder Pairings in New Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-hotkeys-for-instantaneous-windows-redos/"><u>Boost Efficiency: Hotkeys for Instantaneous Windows Redos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-with-terminal-as-favorite-app/"><u>Boost Productivity with Terminal as Favorite App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719320045015-clean-and-tailor-your-w11-desktop-now/"><u>Clean & Tailor Your W11 Desktop, Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719359374237-combat-window-settings-malfunctions-now/"><u>Combat Window Settings Malfunctions Now!</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/digital-asset-management-implementing-watermarks-on-instagram/"><u>Digital Asset Management  Implementing Watermarks on Instagram</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/everyday-online-chronicles-a-handy-tip-for-digging-up-fbs-vids/"><u>Everyday Online Chronicles  A Handy Tip for Digging Up FB's Vids</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-poco-c50-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Poco C50? | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/how-to-create-metaverse-avatar-easily-an-ultimate-guide/"><u>How to Create Metaverse Avatar Easily  An Ultimate Guide</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-cricket-apple-iphone-x-for-free-by-drfone-ios/"><u>How To Unlock Cricket Apple iPhone X for Free</u></a></li>
<li><a href="https://games-able.techidaily.com/ideal-multiplayer-console-titles-best-16-for-game-nights/"><u>Ideal Multiplayer Console Titles - Best 16 for Game Nights</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-poco-f5-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Poco F5 5G | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-a-comprehensive-guide-to-icloud-unlock-from-apple-iphone-se-online-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to iCloud Unlock From Apple iPhone SE Online</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-easy-steps-on-how-to-create-a-new-apple-id-account-on-iphone-14-plus-drfone-by-drfone-ios/"><u>In 2024, Easy Steps on How To Create a New Apple ID Account On iPhone 14 Plus | Dr.fone</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-eliminate-blur-in-zoom-calls-actionable-strategies/"><u>In 2024, Eliminate Blur in Zoom Calls – Actionable Strategies</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-enhancing-your-youtube-content-basic-premiere-pro-edits/"><u>In 2024, Enhancing Your YouTube Content  Basic Premiere Pro Edits</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-itel-p40-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Itel P40 to iPod | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-professional-livestream-tools-outside-of-standard-obs/"><u>In 2024, Professional Livestream Tools Outside of Standard OBS</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-webcam-filming-made-professional-in-no-time/"><u>In 2024, Webcam Filming Made Professional in No Time</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-is-a-sim-network-unlock-pin-get-your-nokia-c300-phone-network-ready-by-drfone-android/"><u>In 2024, What Is a SIM Network Unlock PIN? Get Your Nokia C300 Phone Network-Ready</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719338441167-navigating-through-the-hurdles-winplusprint-mishaps-in-windows/"><u>Navigating Through the Hurdles: Win+Print Mishaps in Windows.</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/nine-essential-considerations-for-chatbot-subscription-success/"><u>Nine Essential Considerations for Chatbot Subscription Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719298161302-overcoming-grayed-out-screensaver-in-win-os-top-fixes/"><u>Overcoming Grayed-Out Screensaver in Win OS: Top Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719349707624-resurrect-your-xbox-on-a-slow-pc-steps-to-take/"><u>Resurrect Your Xbox on a Slow PC: Steps to Take!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-tutorial-on-setting-up-2fa-for-your-twitch-account/"><u>Step-by-Step Tutorial on Setting Up 2FA for Your Twitch Account</u></a></li>
<li><a href="https://program-issues.techidaily.com/ultimate-expert-advice-top-6-tricks-to-boost-your-fps-in-escape-from-tarkov/"><u>Ultimate Expert Advice: Top 6 Tricks to Boost Your FPS in Escape From Tarkov</u></a></li>
</ul></div>
