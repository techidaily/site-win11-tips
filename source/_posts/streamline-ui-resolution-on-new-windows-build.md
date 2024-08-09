---
title: Streamline UI Resolution on New Windows Build
date: 2024-08-08T11:10:05.217Z
updated: 2024-08-09T11:10:05.217Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamline UI Resolution on New Windows Build
excerpt: This Article Describes Streamline UI Resolution on New Windows Build
keywords: Streamlined WinUI Fix,Window Build UI Enhance,New OS UI Optimization,Quick WinResolution Update,Efficient UI for Windows,Improved Windows User Interface,Resolve WinUI on NewOS
thumbnail: https://thmb.techidaily.com/d16299364ff8a12ac1730983e510ad0f5d027390038abb94b7b607447c1cc871.jpg
---

## Streamline UI Resolution on New Windows Build

 If you're looking to customize your computer experience, or just make things easier on the eyes, then changing the display DPI scaling on Windows is a great way to do that. In this helpful article, we'll provide you with an easy step-by-step guide for both registry tweaks and Windows settings so that customizing your computer can be done quickly and easily.

 Whether it's due to vision problems or if you simply want more control over how things look onscreen, these solutions are sure to help.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
## What Is DPI Scaling on Windows?

 DPI stands for "dots per inch" and it refers to the number of individual dots that can be packed into an inch of space on your screen. The higher the number, the sharper and clearer the display. But here's the thing, sometimes you might want your text and images to be bigger, while at other times, you might want them smaller. That's where DPI scaling comes in; it's your very own personal adjustment tool.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
## How to Change Display DPI Scaling via Windows Settings

 The Settings app is the simplest and easiest way to change display scaling in Windows 11\. Here's how to do it.

1. Press**Win + I** on your keyboard to open the Settings menu.
2. From the left pane of the window, click the**System** tab.
3. Click**Display** on the right side.
4. Scroll down to the**Scale and layout** section.
5. Next to the**Scale** option, click the dropdown menu and change the scaling.  
<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Change DPI Scale in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-dpi-scale-in-settings.jpg)
6. Select the one that best fits your needs.

 After you've made your changes, close the window and restart your computer, so the changes take effect.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
## How to Change Display DPI Scaling Using the Registry Editor

 If the Settings app isn't working, or you don't have access to it, you can change the scaling through the Registry Editor. But keep in mind that it can be a bit tricky, and you should[back up your registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes.

 To change Display DPI Scaling using Registry Editor, follow these steps:

1. Press**Win + R** on your keyboard to[open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the dialog box and hit Enter.
3. If UAC prompts on your screen, click**Yes** to continue.
4. Once you're in the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Control Panel\Desktop
5. In the right pane, right-click on**LogPixels** and select**Modify** from the context menu.  
 If you don't see the LogPixels DWORD key, you need to manually create it. For this, right-click on the empty space in the right pane and select**New > DWORD (32-bit) Value** . Upon creating the DWORD key, give it the name**LogPixels** and save it. Now click twice on the key you just created, and a pop-up will appear.

1. Choose one of the following Value data fields and set the base to**Decimal** .  
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
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
![Change Display DPI Scaling Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-display-dpi-scaling-using-registry.jpg)
4. In the pop-up menu, set the Value data to**0** if you set Logpixels to 96, or**1** if you used any other value.
5. Select**Hexadecimal** as the base and click**OK** .

 After performing the above steps, restart your computer to take effect the changes. If you ever need to restore the default settings, just open Registry Editor and go to the same location. Then double-click on Win8DpiScaling and change the Value data to 0.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://driver-error.techidaily.com/fixed-the-driver-driverwudfrd-failed-to-load-for-the-device-event-id-219/"><u>[Fixed] The Driver DriverWudfRd Failed to Load for the Device Event ID 219</u></a></li>
<li><a href="https://article-files.techidaily.com/new-2024-approved-the-ultimate-free-resource-pack-high-quality-pp-samples/"><u>[New] 2024 Approved  The Ultimate Free Resource Pack  High-Quality PP Samples</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-exploring-the-creme-de-la-creme-of-android-mobas-10-for-2024/"><u>[New] Exploring the Crème De La Crème of Android MOBAs (#10) for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-m1-pro-vs-m1-max-examining-the-advancements-in-apples-cpu-technology/"><u>[New] M1 Pro Vs. M1 Max  Examining the Advancements in Apple's CPU Technology</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/iral-vortex-keywords-that-propel-you-into-social-media-spotlight/"><u>[New] Viral Vortex  Keywords that Propel You Into Social Media Spotlight</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-spectacular-hooks-title-crafter/"><u>[Updated] 2024 Approved  Spectacular Hooks Title Crafter</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-optimal-accessories-for-your-high-quality-gopro/"><u>[Updated] Optimal Accessories for Your High-Quality GoPro</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-power-play-joining-a-music-company-network-in-the-age-of-streaming/"><u>[Updated] The Power Play  Joining a Music Company Network in the Age of Streaming</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-elitemac-hd-video-and-sound-recordist/"><u>2024 Approved  EliteMac HD Video & Sound Recordist</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-exploring-the-metaphysics-of-metaverse-selling/"><u>2024 Approved  Exploring the Metaphysics of Metaverse Selling</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-go-incognito-with-instagram-live-streaming-tips/"><u>2024 Approved  Go Incognito with Instagram Live Streaming Tips</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-harmonizing-workplay-by-incorporating-podcast-listening/"><u>2024 Approved  Harmonizing Work/Play by Incorporating Podcast Listening</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-closer-look-at-ais-individuality-and-innovation/"><u>A Closer Look at AI's Individuality and Innovation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-denied-secure-your-windows-environment-with-these-4-tactics/"><u>Access Denied: Secure Your Windows Environment with These 4 Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ancient-pc-modern-atlasos/"><u>Ancient PC, Modern AtlasOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automating-lock-on-time-for-windows-users/"><u>Automating Lock-On Time for Windows Users</u></a></li>
<li><a href="https://extra-information.techidaily.com/creating-videography-magic-from-photos-and-beats/"><u>Creating Videography Magic From Photos & Beats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciph-written-as-a-dialogue-between-two-characters-user-and-assistant-in-an-online-forum-setting-discussing-the-topic-of-what-is-aggregatorhostexe-on-windo37/"><u>Deciph Written as a Dialogue Between Two Characters (User and Assistant) in an Online Forum Setting Discussing the Topic of What Is AggregatorHost.exe on Windows, and Is It Safe?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/defend-with-confidence-top-4-password-protectors-for-win-11-users/"><u>Defend With Confidence: Top 4 Password Protectors for Win 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directives-for-managing-setup-service-state-in-windows/"><u>Directives for Managing Setup Service State in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directly-engage-with-images-in-windows-explorer/"><u>Directly Engage with Images in Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discreet-deletion-of-email-after-signing-in-windows/"><u>Discreet Deletion of Email After Signing In Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disentangle-onedrive-and-microsoft-account-on-windows-machine/"><u>Disentangle OneDrive & Microsoft Account on Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easily-overcome-response-incorrect-message/"><u>Easily Overcome Response Incorrect Message</u></a></li>
<li><a href="https://activate-lock.techidaily.com/effective-ways-to-fix-checkra1n-error-31-on-iphone-13-pro-by-drfone-ios/"><u>Effective Ways To Fix Checkra1n Error 31 On iPhone 13 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-11s-non-functional-function-keys-for-brightness/"><u>Fixing Windows 11'S Non-Functional Function Keys for Brightness</u></a></li>
<li><a href="https://apple-account.techidaily.com/forgot-your-apple-id-password-and-email-from-iphone-12-pro-heres-the-best-fixes-by-drfone-ios/"><u>Forgot Your Apple ID Password and Email From iPhone 12 Pro? Heres the Best Fixes</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/groundbreaking-insights-into-asmr-recordings-for-2024/"><u>Groundbreaking Insights Into ASMR Recordings for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-bypass-disruptions-caused-by-new-windows-updates/"><u>How to Bypass Disruptions Caused by New Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-outlook-rules-not-working-on-windows/"><u>How to Fix Outlook Rules Not Working on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reset-affected-device-access-post-error-code-22/"><u>How to Reset Affected Device Access Post-Error Code 22</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-samsung-galaxy-f04-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Samsung Galaxy F04 to New Android? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-the-calendar-app-on-windows-11/"><u>How to Use the Calendar App on Windows 11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-high-definition-recording-mastering-live-footage-using-logitech-cam/"><u>In 2024, High Definition Recording  Mastering Live Footage Using Logitech Cam</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-do-tecno-camon-30-pro-5g-screen-sharing-drfone-by-drfone-android/"><u>In 2024, How To Do Tecno Camon 30 Pro 5G Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-factory-reset-ipad-or-apple-iphone-11-pro-max-without-icloud-password-or-apple-id-by-drfone-ios/"><u>In 2024, How to Factory Reset iPad or Apple iPhone 11 Pro Max without iCloud Password or Apple ID?</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-phone-number-from-your-apple-id-on-your-apple-iphone-12-pro-max-by-drfone-ios/"><u>In 2024, How To Remove Phone Number From Your Apple ID on Your Apple iPhone 12 Pro Max?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mastering-windows-11-media-with-movie-maker-tools/"><u>In 2024, Mastering Windows 11 Media with Movie Maker Tools</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-streamlined-approach-to-role-assignments-on-discord-servers/"><u>In 2024, Streamlined Approach to Role Assignments on Discord Servers</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-ultimate-guide-on-gionee-f3-pro-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide on Gionee F3 Pro FRP Bypass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-clis-for-efficient-task-management-windows-11/"><u>Integrating CLIs for Efficient Task Management (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-file-explorer-in-windows-10plus/"><u>Jumpstart File Explorer in Windows 10+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-reinstalling-microsofts-mspm/"><u>Master the Art: Reinstalling Microsoft's MSPM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-explorer-onedrive-as-a-launchpad/"><u>Mastering File Explorer: OneDrive as a Launchpad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-bypassing-ssi-and-installing-unverified-drivers/"><u>Mastering Windows: Bypassing SSI & Installing Unverified Drivers</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-top-3-mkv-trimmer-for-mac-2023/"><u>New 2024 Approved Top 3 MKV Trimmer for Mac 2023</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-call-logs-from-realme-11-pro-by-fonelab-android-recover-call-logs/"><u>Possible solutions to restore deleted call logs from Realme 11 Pro</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/premier-recommendations-the-top-10-sports-apps-for-live-tennis-games-for-2024/"><u>Premier Recommendations  The Top 10 Sports Apps for Live Tennis Games for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-route-to-your-windows-disk-space-win-1011/"><u>Quick Route to Your Windows Disk Space (Win 10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-microsoft-store-error-x80072f30-in-windows/"><u>Resolving Microsoft Store Error X80072F30 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-shortage-of-physical-storage-space-vm-errors/"><u>Resolving Shortage of Physical Storage Space (VM) Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-default-sound-level-configurations-in-windows/"><u>Restoring Default Sound Level Configurations in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-peaceful-sleep-windows-1011-automatic-shutdown/"><u>Securing Peaceful Sleep: Windows 10/11 Automatic Shutdown</u></a></li>
<li><a href="https://extra-skills.techidaily.com/snapshots-of-progress-windows-10s-new-features-for-2024/"><u>Snapshots of Progress  Windows 10'S New Features for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-directdraw-crashes-in-win11-a-step-by-step-guide/"><u>Solving DirectDraw Crashes in Win11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-the-endless-cycle-of-windows-ui-issues/"><u>Stop the Endless Cycle of Windows UI Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-no-write-error-a-guide-for-windows-users/"><u>Tackling the No Write Error: A Guide for Windows Users</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-experts-manual-to-windows-10-prowess-for-2024/"><u>The Expert's Manual to WINDOWS 10 Prowess for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-guide-to-instant-uninstalling-via-windows-shortcuts/"><u>The Guide to Instant Uninstalling via Windows Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-personalized-window-pin-creation/"><u>The Ultimate Guide to Personalized Window PIN Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-ancient-game-visuals-using-retroarch-shader-magic/"><u>Transforming Ancient Game Visuals Using RetroArch Shader Magic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-popular-rainmeter-problems-in-windows-systems/"><u>Troubleshooting Popular Rainmeter Problems in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-charging-windows-printer-performance/"><u>Turbo-Charging WIndows Printer Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unison-vs-phone-link-for-windows-phone-users-explored/"><u>Unison Vs. Phone Link for Windows Phone Users Explored</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-is-more-fitting-for-you-tiktok-or-youtubes-micro-video-channels-for-2024/"><u>Which Is More Fitting for You  TikTok or YouTube's Micro-Video Channels for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-aid-unlocking-essential-assistive-tech/"><u>Windows Aid: Unlocking Essential Assistive Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-identity-under-threat-are-biometrics-safe/"><u>Windows Identity Under Threat: Are Biometrics Safe?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-the-battle-against-freezes-in-apex-legends/"><u>Winning the Battle Against Freezes in Apex Legends</u></a></li>
</ul></div>
