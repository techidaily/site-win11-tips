---
title: Optimizing File Operations in PowerShell & Command Prompt
date: 2024-08-16T01:27:36.484Z
updated: 2024-08-17T01:27:36.484Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Optimizing File Operations in PowerShell & Command Prompt
excerpt: This Article Describes Optimizing File Operations in PowerShell & Command Prompt
keywords: PowerShell File Optimization,PS Command Speed,Efficient PS Scripts,Command Prompt Performance,Enhance File Access,Streamlined Data Transfers,PowerShell File Operations
thumbnail: https://thmb.techidaily.com/9be334cdafc76019f9e5ad788ad6c3507c69da5b07f01ac5528173fed7156fb9.jpg
---

## Optimizing File Operations in PowerShell & Command Prompt

 Are you running out of space on your Windows PC? The best thing you can do to free up some space is to compress big files through zipping. There are plenty of third-party tools that can come in handy in this situation.

 However, if you prefer to use Command Prompt or Windows PowerShell over anything else, there are commands you can use in these utilities to zip or unzip files. So, let's check out how to zip or unzip files using Command Prompt and Windows PowerShell.

## How to Zip Files Using Command Prompt

 You can zip files through Command Prompt using the tar command. It's a command line tool that helps you to extract files and create archives. However, this command only works in Windows 10 or later.

Here's how to zip files using Command Prompt:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and**Run as administrator** from the right pane.
3. In the console, type the following command and press**Enter** . Replace**'Place'** with the location of the file.  
`cd Place`  
![Place of the file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/place.jpg)
4. Type**dir** and press**Enter** . It'll show the files inside the selected folder.  
![Dir command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dir.jpg)
5. To zip all the files inside the selected folder, type the following command and press**Enter** . Replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored. Also, replace '**FileExt** ' with the extension of the file you're zipping.  
`tar -a -c -f Compressed.zip *.FileExt`  
![Tar command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tar.jpg)
6. To zip a single file, execute the following command. Again, replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored, '**FileExt** ' with your file's extension, and '**FileName** ' with the name of the file you want to zip.  
`tar -a -c -f Compressed.zip FileName.FileExt`  
![Compressing one file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/compressing-one-file.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Zip Files Using Windows PowerShell

 There are several viable ways to [create zip files on Windows](https://www.makeuseof.com/easy-ways-create-zip-file-windows-10/) . One of these is through Windows PowerShell. However, the**tar** command doesn't work in Windows PowerShell; we'll use another command to get the work done.

Here's how to zip files using Windows PowerShell:

1. Open the Start Menu, type**Windows PowerShell,** and choose Run as administrator from the right pane.
2. In the console, type the following command and press**Enter** . Ensure to replace**file destination** and**target location** with the location of the file and the place where you want the file to be zipped, respectively. Also, replace**file name** with the name of the file you want to zip and**destination name** with the destination folder name.  
`Compress-Archive -LiteralPath 'file destination\file name' -DestinationPath 'target location\destination name'`  
![Zipping command in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping.jpg)

 If you want to zip multiple files, execute the following command. Replace**file destination** and**file destination 1** with the location of the first and second files, respectively. And replace**file name** and**file name 2** with the first and second file names.

`Compress-Archive -LiteralPath 'file destination\file name', 'file destination 1\file name 2 -DestinationPath 'target location\destination name'  
`

![Zipping 2 files at once](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping-2.jpg)
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
## How to Unzip Files Using Command Prompt

 There may be situations where you want to [unzip files on your Windows computer](https://www.makeuseof.com/unzip-files-windows-10/) . Fortunately, you can do that as well using Command Prompt. Here's how:

1. Launch Command Prompt with admin privileges.
2. Use the**cd** command to head toward the zip file's location.
3. Type the following command and press**Enter** . Replace '**Name** ' with the name of the zip file.  
`tar -xf Name.zip`  
![Unzipping file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping-file.jpg)

You've successfully unzipped the file.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
## How to Unzip Files Using Windows PowerShell

 Windows PowerShell lets you quickly unzip files on your computer. Here's how to do that:

1. Open Windows PowerShell with admin rights.
2. Type the following command and press**Enter** . Make sure to replace <**file** **destination** \> and <**target** **location** \> with the location of the zip file and the place where you want the file to be unzipped, respectively.  
`Expand-Archive -LiteralPath <file destination> -DestinationPath <target location>`  
![Unzipping file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
## Save Up Space on Windows 11 by Zipping Your Files

 As a Windows user, you will always come across situations where you want to zip or unzip files. However, if you don't want to use a third-party tool, you can use Command Prompt and Windows PowerShell to quickly zip and unzip files on Windows using the above methods.

 Meanwhile, you might be interested in learning a few important Command Prompt commands.


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
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-easy-steam-recordings-with-team-fortress-2s-latest-update/"><u>[New] In 2024, Easy Steam Recordings with Team Fortress 2'S Latest Update</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-unveiling-top-10-trending-tweets-of-2023/"><u>[New] In 2024, Unveiling Top 10 Trending Tweets of 2023</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-deciphering-instagram-stories-what-youre-not-seeing-as-a-viewer/"><u>[Updated] Deciphering Instagram Stories  What You're Not Seeing as a Viewer</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-decreasing-obs-stream-quality/"><u>[Updated] Decreasing OBS Stream Quality</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-highpoint-artist-toolkit-review/"><u>[Updated] Highpoint Artist Toolkit Review</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-maximizing-visibility-with-smart-hashtag-use-in-fb-advertising/"><u>[Updated] Maximizing Visibility with Smart Hashtag Use in FB Advertising</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-tips-and-insights-for-successful-spotify-marketing-for-2024/"><u>[Updated] Tips and Insights for Successful Spotify Marketing for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-key-clues-suggesting-windows-reboot-required/"><u>3 Key Clues Suggesting Windows Reboot Required</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-productivity-the-essentials-of-using-flow-launcher/"><u>Accelerate Productivity: The Essentials of Using Flow Launcher</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-robust-defense-how-to-upgrade-your-pin-in-windows-11/"><u>Achieving Robust Defense: How to Upgrade Your Pin in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-3-fix-for-windows-10-nvidia-opengl/"><u>Addressing Error 3: Fix for Windows 10 Nvidia OpenGL</u></a></li>
<li><a href="https://program-issues.techidaily.com/beat-saber-freezing-woes-heres-how-to-keep-your-game-running-smoothly/"><u>Beat Saber Freezing Woes? Here's How to Keep Your Game Running Smoothly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-task-managers-dynamic-speed-in-windows-11/"><u>Boost Task Manager's Dynamic Speed in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-macos-performance-through-windows-innovations/"><u>Boosting macOS Performance Through Windows Innovations</u></a></li>
<li><a href="https://android-unlock.techidaily.com/can-i-bypass-a-forgotten-phone-password-of-motorola-by-drfone-android/"><u>Can I Bypass a Forgotten Phone Password Of Motorola?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-windows-11-with-these-top-6-android-apps/"><u>Elevate Your Windows 11 with These Top 6 Android Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-workflow-advanced-filters-and-theme-changes-in-task-manager-windows-11/"><u>Elevate Your Workflow: Advanced Filters & Theme Changes in Task Manager (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-and-disabling-windows-key-in-windows-os/"><u>Enabling and Disabling Windows Key in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-resolve-rpc-fails-on-windows-os/"><u>Essential Steps to Resolve RPC Fails on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-netstat-on-windows-11-a-guide-to-tracking-data-flow/"><u>Explore Netstat on Windows 11: A Guide to Tracking Data Flow</u></a></li>
<li><a href="https://apple-account.techidaily.com/forgot-your-apple-id-password-and-email-from-iphone-11-pro-max-heres-the-best-fixes-by-drfone-ios/"><u>Forgot Your Apple ID Password and Email From iPhone 11 Pro Max? Heres the Best Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-add-a-full-battery-charge-notification-to-windows-10-and-11/"><u>How to Add a Full Battery Charge Notification to Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-lockout-duration-after-failed-logon-attempts-in-windows-11-and-11/"><u>How to Change Lockout Duration After Failed Logon Attempts in Windows 11 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-print-spooler-service-is-not-running-error-in-windows/"><u>How to Fix “The Print Spooler Service Is Not Running” Error in Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-meizu-21-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On Meizu 21? | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-uninstall-windows-11-update/"><u>How to Uninstall Windows 11 Update</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-samsung-galaxy-f15-5g-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Samsung Galaxy F15 5G Phone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-the-ultimate-visual-strategy-for-podcast-branding/"><u>In 2024, The Ultimate Visual Strategy for Podcast Branding</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-transforming-team-conversation-windows-pre-and-post-calls/"><u>In 2024, Transforming Team Conversation Windows  Pre & Post-Calls</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/instagram-excellence-professional-editing-techniques-revealed-for-2024/"><u>Instagram Excellence  Professional Editing Techniques Revealed for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructing-on-windows-copilot-through-vivetool/"><u>Instructing on Windows Copilot Through ViveTool</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/master-iphone-selfies-naturally-10-best-no-cost-enhancing-apps-for-2024/"><u>Master iPhone Selfies Naturally  10 Best No-Cost Enhancing Apps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-customization-in-windows-11-adding-directories/"><u>Mastering Customization in Windows 11: Adding Directories</u></a></li>
<li><a href="https://win11-tips.techidaily.com/obsolete-windows-aesthetics-gone-for-good/"><u>Obsolete Windows Aesthetics, Gone for Good</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-compression-errors-a-guide-to-fixed-zip-files-in-windows-11/"><u>Overcoming Compression Errors: A Guide to Fixed ZIP Files in Windows 11</u></a></li>
<li><a href="https://driver-install.techidaily.com/quick-lenovo-z50-70-firmware-patches-here/"><u>Quick Lenovo Z50-70 Firmware Patches Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-your-windows-headset-mic-functionality/"><u>Restore Your Windows Headset Mic Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-failed-signal-for-windows-steam-link/"><u>Reviving Failed Signal for Windows Steam Link</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-file-ordering-with-these-7-photo-apps/"><u>Seamless File Ordering with These 7 Photo Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-the-steps-msoffice-installation-on-windows-11/"><u>Simplifying the Steps: MSOffice Installation on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-stranded-xbox-on-win11-quick-troubleshooting-guide/"><u>Solving Stranded Xbox on Win11: Quick Troubleshooting Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-unresponsive-delete-button-issue-on-pcs/"><u>Solving Unresponsive Delete Button Issue on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-how-to-alter-file-extensions-on-windows/"><u>Step by Step: How to Alter File Extensions on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-your-windows-experience-with-customized-fn-keys-settings/"><u>Tailor Your Windows Experience with Customized FN Keys Settings</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/the-essential-guide-to-affordable-video-conferencing-tools-for-corporateeducational-use/"><u>The Essential Guide to Affordable Video Conferencing Tools  For Corporate/Educational Use</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-data-from-honor-100-by-fonelab-android-recover-data/"><u>Undelete lost data from Honor 100</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-managing-wins-ram-cache/"><u>Understanding and Managing Win's RAM Cache</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-diablo-secrets-basic-techniques/"><u>Unlocking Diablo Secrets: Basic Techniques</u></a></li>
<li><a href="https://some-tips.techidaily.com/unveiling-hidden-youtube-comments-for-2024/"><u>Unveiling Hidden YouTube Comments for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-power-of-placement-comments-in-windows-explorer/"><u>Unveiling the Power of Placement Comments in Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-process-chrome-windows-11-link-up/"><u>Unveiling the Process: Chrome, Windows 11 Link-Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-ethernet-restoring-lost-internet-signal/"><u>Win Ethernet: Restoring Lost Internet Signal</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-personalization-transforming-ordinary-into-extraordinary/"><u>Windows 11 Personalization: Transforming Ordinary Into Extraordinary</u></a></li>
</ul></div>
