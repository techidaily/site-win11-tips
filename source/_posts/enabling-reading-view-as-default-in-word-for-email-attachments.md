---
title: Enabling Reading View as Default in Word for Email Attachments
date: 2024-09-01T05:12:43.754Z
updated: 2024-09-02T05:12:43.754Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling Reading View as Default in Word for Email Attachments
excerpt: This Article Describes Enabling Reading View as Default in Word for Email Attachments
keywords: Default Reading Mode,Word Email Attachment,Inline Mail Content,Set As Standard Read,Word Preview Settings,Attachment Display View,Optimize Reading in Word
thumbnail: https://thmb.techidaily.com/855eb1fbf7971ff96081545be670b71dd8396e6ecbde85afd3575d8478b3848e.jpg
---

## Enabling Reading View as Default in Word for Email Attachments

 Microsoft Word comes with a lot of security features that protect your computer from malicious files. One of these options allows you to open all email attachments in Word's reading view by default.

 If you want an extra layer of protection against email attachments, there are several ways to always open attached Word documents in reading view on Windows. Let’s go over them one by one.

## 1\. How to Change Microsoft Word Startup Settings to Always Open Email Attachments in Reading View

 You can modify Word's startup settings to specify how your documents are handled. From there, you can set Word to open all email attachments in reading mode by default. Here's how:

1. Open Microsoft Word on your PC using the search menu.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left pane. This will open the**Word Options** window.
4. In the**General** tab, scroll down to**Start up options** .
5. Check the box that reads **Open e-mail attachments and other uneditable files in reading view** and click on**OK** .  
![Word Startup Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Word-Startup-Options.jpg)

 Once you complete the above steps, Word will open email attachments in reading view by default.

## 2\. How to Change the Local Group Policy to Open Email Attachments in Reading View in Microsoft Word

 Another way to configure Word to open email attachments in reading view is to use the Group Policy Editor. It’s worth noting that you can only access the Group Policy Editor if you’re running the Professional, Education, or Enterprise edition of Windows. If you're on Windows Home, be sure to check out[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will[open the Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/) .
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Microsoft Word 2016 > Word Options > General** .
4. Double-click the**Open e-mail attachments in Reading View** policy on your right.
5. Select the**Enabled** option.
6. Hit**Apply** followed by**OK** .  
![Configure Word to Open Email Attachments in Reading View Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Group-Policy-Editor.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. How to Tweak the Windows Registry to Open Email Attachments in Reading View in Microsoft Word

 The Registry Editor in Windows stores important settings for Windows and its apps. If you're comfortable editing registry files, you can also use the following method to configure Word to open email attachments in reading view.

 Since modifying registry files is risky, you should proceed with caution. Also, make sure you back up all the registry files first. If you need help, refer to our guide on[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

 Once you’ve done that, here’s what you need to configure Word to open email attachments in reading view.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > Software > Microsoft > Office > 16.0 > Word > Options** .
5. Right-click on the**Options** key and select**New > DWORD (32-bit) Value** . Name it**AutoReadingMode** .
6. Double-click the newly created DWORD and set the**Value data** to**1** .
7. Click**OK** .  
![Configure Word to Open Email Attachments in Reading View Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Registry-Editor.jpg)

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
## Opening Email Attachments in Microsoft Word's Reading View

 Email remains a prominent attack vector for hackers and cybercriminals. Configuring Microsoft Word to open email attachments in reading view is just one of many methods for avoiding malware. Another option is to check suspicious files for malware before opening them.


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
<li><a href="https://youtube-blog.techidaily.com/024-approved-innovative-approaches-to-enhance-the-impact-of-your-youtube-intro/"><u>[New] 2024 Approved  Innovative Approaches to Enhance the Impact of Your YouTube Intro</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-select-your-dreams-best-vr-bike-trails/"><u>[New] Select Your Dreams  Best VR Bike Trails</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-top-10-free-game-recording-software-2024/"><u>[New] Top 10 Free Game Recording Software 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-ultimate-gopro-studio-steps-for-time-lapse-magic/"><u>[New] Ultimate GoPro Studio Steps for Time Lapse Magic</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-10-record-screen-and-upload-to-youtube-tools-pc-mac-online-for-2024/"><u>[Updated] 10 Record Screen and Upload to YouTube Tools [PC, Mac, Online] for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-how-to-record-skype-calls/"><u>[Updated] 2024 Approved  How to Record Skype Calls</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-hybridmix-pro-for-dual-os/"><u>[Updated] 2024 Approved  HybridMix Pro for Dual OS</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-fine-tune-your-cinematography-mastering-kinemaster-zoom-features/"><u>[Updated] Fine-Tune Your Cinematography  Mastering Kinemaster Zoom Features</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-how-to-block-someone-on-instagram-in-2024/"><u>[Updated] How to Block Someone on Instagram, In 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-the-pathway-to-captivating-audio-on-macos-via-audacity/"><u>[Updated] In 2024, The Pathway to Captivating Audio on MacOS via Audacity</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-maximize-video-clarity-with-obs-tweaks/"><u>[Updated] Maximize Video Clarity with OBS Tweaks</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-learn-from-the-best-youtubes-top-green-screen-techniques/"><u>2024 Approved  Learn From The Best  Youtube’s Top Green Screen Techniques</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-recording-revolution-ranking-the-top-10-budget-apps/"><u>2024 Approved  Recording Revolution  Ranking the Top 10 Budget Apps</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-virtual-reality-therapy-breakthroughs/"><u>2024 Approved  Virtual Reality Therapy Breakthroughs</u></a></li>
<li><a href="https://buynow-help.techidaily.com/affordable-excellence-in-comfort-and-design-a-closer-look-at-microsofts-sculpt-ergonomic-keyboard/"><u>Affordable Excellence in Comfort and Design: A Closer Look at Microsoft's Sculpt Ergonomic Keyboard</u></a></li>
<li><a href="https://extra-information.techidaily.com/basics-of-animated-infographics-and-signage/"><u>Basics of Animated Infographics and Signage</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/best-10-tikfilters-for-viral-video-success/"><u>Best 10 TikFilters for Viral Video Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-email-service-failures-on-windows-error-0x800713f/"><u>Correcting Email Service Failures on Windows (Error 0X800713F)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-execution-slang-for-software-deployment/"><u>Discovering Execution Slang for Software Deployment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dynamic-wallpaper-integration-a-windows-11-essential-tutorial/"><u>Dynamic Wallpaper Integration: A Windows 11 Essential Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-techniques-to-extract-large-amounts-of-data-at-once/"><u>Efficient Techniques to Extract Large Amounts of Data at Once</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-overcoming-the-most-common-update-issues/"><u>Expert Advice: Overcoming the Most Common Update Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-reboot-windows-update-components/"><u>Guidelines to Reboot Windows Update Components</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-from-infinix-zero-5g-2023-turbo-by-drfone-android/"><u>How to Bypass FRP from Infinix Zero 5G 2023 Turbo?</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-vivo-x100-drfone-by-drfone-virtual-android/"><u>How to Change Location on TikTok to See More Content On your Vivo X100 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-open-the-system32-folder-in-windows-11/"><u>How to Open the System32 Folder in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-system-issues-of-iphone-se-2022-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair System Issues of iPhone SE (2022)? | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-digital-revolution-todays-vr-landscape-and-tomorrows-trials/"><u>In 2024, The Digital Revolution  Today's VR Landscape & Tomorrow's Trials</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-uncomplicated-video-logging-tool-w10/"><u>In 2024, Uncomplicated Video Logging Tool  W10</u></a></li>
<li><a href="https://driver-error.techidaily.com/intels-opengl-driver-a-quest-for-its-name/"><u>Intel's OpenGL Driver, A Quest for Its Name</u></a></li>
<li><a href="https://win11-tips.techidaily.com/joyous-jingles-tickling-tech-with-windows-software/"><u>Joyous Jingles: Tickling Tech with Windows Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-profits-with-windows-11-a-closer-look/"><u>Making Profits with Windows 11 - A Closer Look</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-filters-for-safe-browsing/"><u>Mastering Windows Filters for Safe Browsing</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/new-how-to-make-an-emoji-of-yourself-on-android-and-iphone-emoji-yourself/"><u>New How to Make an Emoji of Yourself on Android and iPhone Emoji Yourself</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-more-hassle-fixing-11-common-windows-11-anomalies/"><u>No More Hassle: Fixing 11 Common Windows 11 Anomalies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-time-settings-in-windows-manual-configuration-steps/"><u>Personalizing Time Settings in Windows: Manual Configuration Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/power-through-pc-problems-master-these-20-cmd-commands/"><u>Power Through PC Problems: Master These 20 CMD Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propel-windows-systems-into-high-efficiency-video-land-with-tdarr-tools/"><u>Propel Windows Systems Into High-Efficiency Video Land with Tdarr Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-unreliable-keys-on-the-windows-snipper/"><u>Quick Fixes for Unreliable Keys on the Window's Snipper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-to-address-windows-task-sequence-fails-0x8007000f/"><u>Quick Fixes to Address Windows Task Sequence Fails 0X8007000F</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-solution-for-local-sam-service-error-signal/"><u>Quick Solution for 'Local SAM Service' Error Signal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-driver-failure-error-on-pcs-running-windows-1011/"><u>Resolving Driver Failure Error on PCs Running Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-energy-levels-after-high-living-in-windows/"><u>Reviving Energy Levels After High Living in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-your-setup-achieving-batch-software-updates-with-winstall-in-windows-11/"><u>Revolutionize Your Setup: Achieving Batch Software Updates with Winstall in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-windows-11-temp-directory-functionality/"><u>Secure Windows 11 Temp Directory Functionality</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/simplified-approaches-to-insta-photovideo-resharing-for-2024/"><u>Simplified Approaches to Insta Photo/Video Resharing for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-non-respectful-windows-11-sticky-notes-sync/"><u>Solving Non-Respectful Windows 11 Sticky Notes Sync</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-pc-control-hotkey-heroes-of-the-auto-world/"><u>Speedy PC Control: Hotkey Heroes of the Auto World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-unauthorized-nvidia-control-panel-errors/"><u>Steps to Fix Unauthorized Nvidia Control Panel Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-implement-spatial-sound-on-windows-11/"><u>Strategies to Implement Spatial Sound on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-system-for-optimal-performance-with-new-windows-and-linux-blend/"><u>Tailoring Your System for Optimal Performance With New Windows and Linux Blend</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-users-guide-to-task-filtering-and-theme-tweaking-in-windows-11/"><u>The Complete User's Guide to Task Filtering & Theme Tweaking in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essence-of-windows-cab-files-and-execution-procedures/"><u>The Essence of Windows Cab Files & Execution Procedures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricks-to-manipulate-windows-11-search-highlights/"><u>Tricks to Manipulate Windows 11 Search Highlights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-code-0x800f0831-the-troubleshoot-tome/"><u>Unraveling Code 0X800f0831: The Troubleshoot Tome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-another-users-ms-error-issue/"><u>Unraveling the Another User’s MS Error Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-1011-overcoming-the-hypervisor-bsod-crash/"><u>Win 10/11: Overcoming the HYPERVISOR BSOD Crash</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-notes-problem-solver-steps-to-reopen-your-missing-notepad/"><u>Windows Notes Problem Solver: Steps to Reopen Your Missing Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workaround-for-admin-restricted-windows-software/"><u>Workaround for Admin-Restricted Windows Software</u></a></li>
</ul></div>
