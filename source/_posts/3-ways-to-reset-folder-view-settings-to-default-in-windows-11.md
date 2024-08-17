---
title: 3 Ways to Reset Folder View Settings to Default in Windows 11
date: 2024-08-16T01:15:14.375Z
updated: 2024-08-17T01:15:14.375Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 3 Ways to Reset Folder View Settings to Default in Windows 11
excerpt: This Article Describes 3 Ways to Reset Folder View Settings to Default in Windows 11
keywords: Set Folder View Default,Windows 11 Reset Settings,Folder Options Reset Guide,Windows Config Folder Display,View Folders Default State,Reset Windows Folder Layout,Revert View Settings Windows
thumbnail: https://thmb.techidaily.com/84dab43ab035d91cb56a4eae408b40758af9a9a2b096c95f61afee80ed15090c.jpg
---

## 3 Ways to Reset Folder View Settings to Default in Windows 11

 Folder View Settings in Windows help you control how the contents of a particular folder are displayed and organized. If you’ve changed these settings, but now want to reset them to the default view, it’s easy. Read this guide to learn how to reset Folder View settings on your Windows 11 PC.

## How to Reset Folder View Settings to Default on Windows

 There are three ways to reset your Folder View Settings to the default view. The first method is to run a batch file, the second using File Explorer, whereas the third and final method involves tweaking the registry editor. This post explains each method in detail. Let's dive into it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Run a Batch File to Reset Folder View Settings to Default

 Resetting the Folder View Settings with this method requires creating and running a batch file. This will reset the settings for all folders across your computer. Here's how to do it:

1. Right-click on your desktop and select**New > Text Document** .
2. Name it**ResetFolderViewSettings** and press Enter to save it.
3. Open the newly created text file in Notepad or any other text editor of your choice.
4. Now copy and paste the following code into the file:  
`@echo off  

:: Resets folder view settings, window size and position of all folders  
Reg Delete "HKCU\SOFTWARE\Classes\Local Settings\Software\Microsoft\Windows\Shell\BagMRU" /F  
Reg Delete "HKCU\SOFTWARE\Classes\Local Settings\Software\Microsoft\Windows\Shell\Bags" /F  

:: To reset "Apply to Folders" views to default for all folder types  
REG Delete "HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Streams\Defaults" /F  

:: To reset size of details, navigation, preview panes to default for all folders  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Modules\GlobalSettings\Sizer" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Modules\NavPane" /F  

:: To reset size of Save as amd Open dialogs to default for all folders  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CIDOpen" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CIDSave" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\ComDlg32" /F  

:: To kill and restart explorer process  
taskkill /f /im explorer.exe  
start explorer.exe`
5. After adding the code, click**File** in the top menu, then select**Save As** .
6. Now select**All Files** in the Save as type menu, and add**.bat** to the end of the file’s name.  
![Run a Batch File to Reset Folder View Settings to Default](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-a-batch-file-to-reset-folder-view-settings-to-default.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
7. From the left pane, select**Desktop** as the location.
8. Then click**Save** and close the text editor window.
9. Finally, double-click the batch file you created, and it will reset your Folder View Settings to the default view.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on [how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
<!-- affiliate ads begin -->

<!-- affiliate ads end -->
3. Click**Yes** when prompted to confirm your action.
4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
### 3\. Reset Folder View Settings to Default Using Registry Editor

 The last method to reset Folder View settings involves using the Windows Registry Editor. You should only use this method if you are an experienced user and know how it works, since messing with its keys could cause serious problems. To avoid data loss, you must [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before continuing.

 To reset folder view settings using the registry editor, do the following:

1. Press**Win + R** on your keyboard to [open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the text box and press Enter. This will [open the Registry Editor window](https://www.makeuseof.com/windows-11-open-registry-editor/) .
3. Navigate to the following location:  
HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\Shell
4. In the left sidebar, right-click on the**BagMRU** folder and select**Delete.**  
![Reset Folder View Settings to Default Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-using-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
5. Click**Yes** when asked to confirm your action.
6. Similarly, delete the**Bags** folder and close the Registry window.

## Reset Folder View Settings to Default

 Folder View on Windows allows users to customize their view of files and folders. This includes settings such as the file size information, restoring the previous folder when logging in, and automatically entering words when searching.

 However, if you have changed the View settings, this guide will help you reset Folder Options to its default.


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
<li><a href="https://twitter-videos.techidaily.com/new-a-tweet-to-snap-showcase-video-posting-techniques/"><u>[New] A Tweet-to-Snap Showcase  Video Posting Techniques</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-critical-analysis-of-the-best-free-video-chat-software-suitable-for-businesses-and-educators/"><u>[New] Critical Analysis of the Best Free Video Chat Software Suitable for Businesses & Educators</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-discover-the-most-reliable-royalty-free-audio-libraries-for-2024/"><u>[New] Discover the Most Reliable Royalty-Free Audio Libraries for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-download-premium-video-covers-free-fast-and-easy/"><u>[New] Download Premium Video Covers - Free, Fast & Easy!</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-from-pre-windows-10-era-to-windows-11-now/"><u>[New] From Pre-Windows 10 Era  To Windows 11 Now</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-sound-spectrum-listing-websites-for-legal-ringtones/"><u>[New] Sound Spectrum  Listing Websites for Legal Ringtones</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-transformative-visuals-unleash-the-power-of-6-video-types/"><u>[New] Transformative Visuals  Unleash the Power of 6 Video Types</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-bringing-anime-characters-to-life-jujutsu-kaisen-for-tiktok/"><u>[Updated] 2024 Approved  Bringing Anime Characters to Life  Jujutsu Kaisen for TikTok</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-deciding-on-live-stream-xsplit-or-obs-pros-and-cons/"><u>[Updated] 2024 Approved  Deciding on Live Stream  XSplit or OBS Pros and Cons</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-transforming-gameplay-discovering-the-seven-stars-of-stardew-updates/"><u>[Updated] In 2024, Transforming Gameplay  Discovering the Seven Stars of Stardew Updates</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-step-by-step-setting-up-your-first-xbox-record-session-for-2024/"><u>[Updated] Step-by-Step  Setting Up Your First Xbox Record Session for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-strategizing-success-the-open-door-approach-for-2024/"><u>[Updated] Strategizing Success  The Open Door Approach for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-synergistic-campaigns-brands-and-youtube-hand-in-hand/"><u>[Updated] Synergistic Campaigns  Brands & YouTube Hand in Hand</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-views-for-livelihood-mastering-youtubes-true-numbers/"><u>[Updated] Views for Livelihood  Mastering YouTube's True Numbers</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-elevate-listener-engagement-seo-strategies-for-podcasts/"><u>2024 Approved  Elevate Listener Engagement  Seo Strategies for Podcasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-using-windows-11-calendar/"><u>A Practical Approach to Using Windows 11 Calendar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapt-calc-app-for-night-time-viewing-dark-mode-tutorial/"><u>Adapt Calc App for Night-Time Viewing: Dark Mode Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-inactive-windows-system-voices/"><u>Addressing Inactive Windows System Voices</u></a></li>
<li><a href="https://facebook.techidaily.com/analyzing-the-authenticity-of-security-email-at-facebookmailcom-for-fb-safety/"><u>Analyzing the Authenticity of Security Email at facebookmail.com for FB Safety</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bf-price-war-save-612-on-endless-win10-lifetime-life/"><u>BF Price War: Save $6.12 on Endless Win10 Lifetime Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-loop-of-0xf0831-error-in-win11-os/"><u>Breaking the Loop of 0XF0831 Error in Win11 OS</u></a></li>
<li><a href="https://fox-access.techidaily.com/bringing-stories-to-life-adding-effective-narration/"><u>Bringing Stories to Life  Adding Effective Narration</u></a></li>
<li><a href="https://tech-revival.techidaily.com/charting-new-territories-the-evolution-and-future-of-generative-ai-post-chatgpt/"><u>Charting New Territories: The Evolution and Future of Generative AI Post-ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-guide-to-implementing-bluescreenview-strategies/"><u>Detailed Guide to Implementing BlueScreenView Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dismantling-barriers-to-running-powershell-scripts-in-windows/"><u>Dismantling Barriers to Running PowerShell Scripts in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortless-link-to-your-printer/"><u>Effortless Link to Your Printer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-yuzu-fps-on-pc-systems/"><u>Enhancing Yuzu FPS on PC Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-fixes-for-nvidia-gl-driver-issue-3-on-win11/"><u>Expert Fixes for NVIDIA GL Driver Issue #3 on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-ahead-with-windows-11-integrating-outlook-preview/"><u>Get Ahead with Windows 11: Integrating Outlook Preview</u></a></li>
<li><a href="https://driver-download.techidaily.com/hassle-free-process-to-download-and-update-microsoft-surface-drivers/"><u>Hassle-Free Process to Download and Update Microsoft Surface Drivers</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-on-gionee-by-drfone-android/"><u>How to Bypass FRP on Gionee?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-the-lock-screen-and-screen-saver-timeout-settings-on-windows/"><u>How to Change the Lock Screen and Screen Saver Timeout Settings on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-upgrade-to-windows-11-22h2-on-unsupported-hardware/"><u>How to Upgrade to Windows 11 22H2 on Unsupported Hardware</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-itel-a60s-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Itel A60s to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-track-imei-number-of-xiaomi-redmi-note-13-pro-5g-through-google-earth-by-drfone-android/"><u>In 2024, How To Track IMEI Number Of Xiaomi Redmi Note 13 Pro 5G Through Google Earth?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-lock-your-xiaomi-redmi-note-12-proplus-5g-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Xiaomi Redmi Note 12 Pro+ 5G Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-master-list-top-free-photo-stockpile-locales/"><u>In 2024, Master List  Top Free Photo Stockpile Locales</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-windows-error-code-0xc00000f-strategies-for-success/"><u>Mastery over Windows Error Code 0Xc00000f: Strategies for Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-your-way-a-guide-to-mapping-drives-on-windows-11/"><u>Navigate Your Way: A Guide to Mapping Drives on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-absence-of-tab-functionality-in-os-x/"><u>Navigating the Absence of Tab Functionality in OS X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-hidden-paths-of-window-menus-on-pc/"><u>Navigating the Hidden Paths of Window Menus on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-complexities-of-onedrive-errors/"><u>Navigating Through the Complexities of OneDrive Errors</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-tiktok-watermark-removal-made-easy-top-picks-and-reviews/"><u>New TikTok Watermark Removal Made Easy Top Picks and Reviews</u></a></li>
<li><a href="https://win-blog.techidaily.com/pacific-drive-crash-prevention-and-recovery-methods-for-personal-computers/"><u>Pacific Drive Crash Prevention and Recovery Methods for Personal Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/practical-guide-to-disregarding-false-security-alarms-in-chrome/"><u>Practical Guide to Disregarding False Security Alarms in Chrome</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-oneplus-open-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on OnePlus Open and Browser | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/preventing-non-displayed-images-in-youtubes-shorts-for-2024/"><u>Preventing Non-Displayed Images in YouTubes Shorts for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconciling-system-with-a-fresh-net-framework-max-156/"><u>Reconciling System with a Fresh .NET Framework (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-steam-network-error-in-windows-11-systems/"><u>Remedying Steam Network Error in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-page-load-failure-on-microsoft-store-windows-app/"><u>Resolving 'Page Load Failure' On Microsoft Store Windows App</u></a></li>
<li><a href="https://extra-hints.techidaily.com/revolutionizing-your-digital-presence-through-strategic-social-media-mastery/"><u>Revolutionizing Your Digital Presence Through Strategic Social Media Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-gmaps-windows-pc-guide/"><u>Setting Up GMaps: Windows PC Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-screen-splitting-problems-in-win-10/"><u>Solutions for Screen Splitting Problems in Win 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-unrecoverable-windows-errors/"><u>Solutions to Unrecoverable Windows Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-changing-proxies-on-windows-11/"><u>Step-by-Step: Changing Proxies on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-fixing-windows-11-help-menu-failure/"><u>Steps for Fixing Windows 11 Help Menu Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-windows-11-error-code-22-lockout/"><u>Steps to Rectify Windows 11 Error Code 22 Lockout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stops-repeated-edge-icons-on-workspace/"><u>Stops Repeated Edge Icons on Workspace</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/straightforward-methods-for-recording-iphone-display-for-2024/"><u>Straightforward Methods for Recording iPhone Display for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-scheduling-in-windows-11-calendar/"><u>Streamlining Scheduling in Windows 11 Calendar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-c0000005-failure-on-windows-108/"><u>Tackling C0000005 Failure on Windows 10/8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-path-failure-on-pc-operating-systems/"><u>Tackling PATH Failure on PC Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-winning-playbook-strategies-to-eliminate-stutter-in-videos/"><u>The Winning Playbook: Strategies to Eliminate Stutter in Videos</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-5-free-online-platforms-for-live-sporting-events/"><u>Top 5 Free Online Platforms for Live Sporting Events</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-slow-downloads-in-steam-a-windows-guide/"><u>Troubleshoot Slow Downloads in Steam - A Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-synapse-unidentified-razer-peripherals-on-win-11/"><u>Troubleshooting Synapse: Unidentified Razer Peripherals on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-vscode-instability-in-windows-11/"><u>Troubleshooting VSCode Instability in Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/ultimate-guide-to-easy-youtube-subtitle-and-closed-caption-addition-for-2024/"><u>Ultimate Guide to Easy YouTube Subtitle and Closed Caption Addition for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-full-potential-multitasking-with-windows-11-in-mac-os-using-parallels/"><u>Unlock Full Potential: Multitasking with Windows 11 in Mac OS Using Parallels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-end-task-control-for-window-management/"><u>Utilizing End Task Control for Window Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-over-controller-woes-a-guide-to-steam-detection/"><u>Win Over Controller Woes: A Guide to Steam Detection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-ahead-mastering-upcoming-tools-through-vivetool/"><u>Windows Ahead: Mastering Upcoming Tools Through ViVeTool</u></a></li>
</ul></div>
