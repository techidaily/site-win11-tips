---
title: Exploring Actions & Activation Labels in Dev Tools
date: 2024-08-16T01:59:56.125Z
updated: 2024-08-17T01:59:56.125Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Exploring Actions & Activation Labels in Dev Tools
excerpt: This Article Describes Exploring Actions & Activation Labels in Dev Tools
keywords: Actions Insight,Dev Tool Annotations,Activation Labelling,Developer Debugging,Code Action Tracking,Task Execution Labels,Functional Diagnostics
thumbnail: https://thmb.techidaily.com/a5249e9b13fd437412102feed5c7841b8ccf98fdf0188fbbf3a215fd35680a08.JPG
---

## Exploring Actions & Activation Labels in Dev Tools

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several [Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## Create App Execution Aliases in Registry Editor

 Before editing or creating registry keys, it is advisable to [create a full backup of the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . Of course, you should also ensure you understand how to restore the Registry from that backup.

 The process below for creating app execution aliases in the Registry Editor should be the same in both Windows 10 and 11.

1. Open**Windows Search** , type**Registry Editor** , and click on the search result to open it.
2. In the editor, navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\App Paths** .
3. Next, right-click on the**App Paths** key in the left-hand pane, and select**New > Key** .
4. Give the new key an alias name that relates to the app and ends with .exe. For example, if the alias is for Calendar, call it something like cal.exe.
5. With the alias selected, double-click the**Default** value in the right-hand pane.  
![editing app aliases in registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-regedit.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
6. In the Value data field, you will need to enter the full path to the app executable file. For example**C:\\Program Files (x86)\\Calendar.exe** .
7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
## Using and Creating App Execution Aliases

 Entering commands into tools such as Command Prompt and PowerShell can be laborious. You can streamline that process by enabling or creating aliases for apps that commonly feature in those commands. Why type out a full path to an executable file when you can point to it with a few keystrokes?


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
<li><a href="https://facebook-record-videos.techidaily.com/new-behind-the-curtains-a-guide-to-youtubes-hidden-videos-for-2024/"><u>[New] Behind the Curtains  A Guide to YouTube’s Hidden Videos for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-earnings-from-a-million-youtube-globals/"><u>[Updated] In 2024, Earnings From a Million YouTube Globals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-photo-preview-boards-in-win-11/"><u>Adjusting Photo Preview Boards in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-introduction-to-windows-exepe-file-formats/"><u>An Introduction to Windows EXE/PE File Formats</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/beyondbasics-the-futurepost-mycam-cameras-for-2024/"><u>BeyondBasics  The FuturePost-MyCam Cameras for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/can-pressing-prtscn-launch-snipping-tool-steps-to-halt/"><u>Can Pressing PrtScn Launch Snipping Tool? Steps to Halt</u></a></li>
<li><a href="https://facebook.techidaily.com/creating-an-online-persona-with-a-facebook-image/"><u>Creating an Online Persona with a Facebook Image</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-approaches-to-adjacent-and-distinct-windows-partition-merging/"><u>Cutting-Edge Approaches to Adjacent and Distinct Windows Partition Merging</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-subnet-tweak-for-experienced-users-win11/"><u>Effortless Subnet Tweak for Experienced Users, Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-terminal-usage-make-it-primary-choice/"><u>Elevate Your Terminal Usage: Make It Primary Choice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/envisioning-the-ideal-user-experience-in-windows-11/"><u>Envisioning the Ideal User Experience in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploiting-windows-11s-error-diagnostic-solutions/"><u>Exploiting Windows 11'S Error Diagnostic Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-hidden-options-mastery-of-lost-control-configurations/"><u>Explore Hidden Options: Mastery of Lost Control Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-the-haste-of-edges-tabs-in-w11/"><u>Halt the Haste of Edge's Tabs in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-clear-the-focus-wallpaper-icon-on-windows-11/"><u>How to Clear the Focus Wallpaper Icon on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-dxgierrordeviceremoved-error-in-windows-10-and-11/"><u>How to Fix the DXGI_ERROR_DEVICE_REMOVED Error in Windows 10 & 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-iphone-xs-ios-system-issues-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iPhone XS iOS System Issues? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-google-chrome-from-tracking-your-location-on-oppo-a18-drfone-by-drfone-virtual-android/"><u>How to Stop Google Chrome from Tracking Your Location On Oppo A18? | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-photos-from-apple-iphone-13-pro-max-to-other-iphone-without-icloud-drfone-by-drfone-transfer-from-ios/"><u>How to Transfer Photos from Apple iPhone 13 Pro Max to other iPhone without iCloud | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unlock-your-onedrive-on-a-windows-machine/"><u>How To Unlock Your OneDrive on a Windows Machine</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-elite-9-directors-cuts-downloader/"><u>In 2024, Elite 9 Directors' Cuts Downloader</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-do-realme-c51-screen-sharing-drfone-by-drfone-android/"><u>In 2024, How To Do Realme C51 Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-premium-mobile-podcast-sources/"><u>In 2024, Premium Mobile Podcast Sources</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-apk-deployment-for-win-11-users/"><u>Instant APK Deployment for Win 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-yourphoneexe-malware-insights-on-windows-87/"><u>Is YourPhone.exe Malware? Insights on Windows 8/7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leap-forward-in-windows-video-management-integrate-tdarrs-distributed-capabilities/"><u>Leap Forward in Windows Video Management: Integrate Tdarr's Distributed Capabilities</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/locked-out-of-apple-iphone-7-plus-5-ways-to-get-into-a-locked-apple-iphone-7-plus-by-drfone-ios/"><u>Locked Out of Apple iPhone 7 Plus? 5 Ways to get into a Locked Apple iPhone 7 Plus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/manipulating-windows-files-disabling-read-only-status/"><u>Manipulating Windows Files: Disabling Read-Only Status</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/master-youtube-sound-playback-variations/"><u>Master YouTube Sound Playback Variations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-epic-launcher-sign-in-on-pc/"><u>Mastering the Art of Epic Launcher Sign-In on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multiple-routes-for-opening-utilities-on-windows-systems/"><u>Multiple Routes for Opening Utilities on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-hazards-of-cheap-windows-key-purchases/"><u>Navigating the Hazards of Cheap Windows Key Purchases</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-windows-11-search-top-5-expert-methods/"><u>Optimize Your Windows 11 Search: Top 5 Expert Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-discord-launch-and-update-check-with-windows-startup/"><u>Preventing Discord Launch and Update Check with Windows Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-access-reactivating-ms-store-apps-in-windows-11/"><u>Regaining Access: Reactivating MS Store Apps in Windows 11</u></a></li>
<li><a href="https://driver-download.techidaily.com/1722977211194-seamless-compatibility-with-windows-cuarto-how-to-obtain-and-install-sandisk-drivers-now/"><u>Seamless Compatibility with Windows Cuarto: How To Obtain And Install SanDisk Drivers Now!</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-process-for-creating-deleting-and-tweaking-registry-keys/"><u>Step-by-Step Process for Creating, Deleting & Tweaking Registry Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-eliminate-error-0xa00f425d-in-windows-camera/"><u>Steps to Eliminate Error 0xA00F425D in Windows Camera</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-reduce-cpu-and-ram-overuse-by-unrealcefsubprocess-on-systems/"><u>Strategies to Reduce CPU and RAM Overuse by UnrealCEFSubprocess on Systems</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-507-instagram-caption-ideas-for-hitting-the-high-notes/"><u>Top 507 Instagram Caption Ideas for Hitting the High Notes</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-madden-nfl-20-pc-malfunctions-easy-fixes-to-try-now/"><u>Troubleshooting Madden NFL 20 PC Malfunctions: Easy Fixes to Try Now</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-messages-from-motorola-edge-40-by-fonelab-android-recover-messages/"><u>Undelete lost messages from Motorola Edge 40</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-approach-to-allocated-ram/"><u>Understanding Windows' Approach to Allocated RAM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-windows-11-potential-via-powertoys-install/"><u>Unleashing Windows 11 Potential via PowerToys Install</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unraveling-the-distinctions-machine-learning-versus-natural-language-processing/"><u>Unraveling the Distinctions: Machine Learning Versus Natural Language Processing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-ways-for-swift-epic-game-loading/"><u>Unveiling Windows Ways for Swift Epic Game Loading</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/visual-virtuosos-popular-ig-effects-for-2024/"><u>Visual Virtuosos  Popular IG Effects for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/what-does-jailbreaking-apple-iphone-6-plus-i-do-get-answers-here-by-drfone-ios/"><u>What Does Jailbreaking Apple iPhone 6 Plus i Do? Get Answers here</u></a></li>
</ul></div>
