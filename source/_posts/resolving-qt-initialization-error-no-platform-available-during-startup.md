---
title: "Resolving Qt Initialization Error: No Platform Available During Startup"
date: 2024-11-22T16:09:50.911Z
updated: 2024-11-27T17:39:55.743Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resolving Qt Initialization Error: No Platform Available During Startup"
excerpt: "This Article Describes Resolving Qt Initialization Error: No Platform Available During Startup"
keywords: QtStartErrorNoPlatform,ResolveQtInitFail,QTInitializationFailure,QtLaunchIssueDetected,QtSetupErrorHandling,NoPlatfromInQtStartup,CorrectQtInitialization
thumbnail: https://thmb.techidaily.com/c71f8b11a9475a90b96c899fdeade9228f855c7ed46c02973b8fefdc10e6507c.jpg
---

## Resolving Qt Initialization Error: No Platform Available During Startup

 Have you recently run into the “Application failed to start because no Qt platform plugin could be initialized” error? QT is a cross-platform app that is used to generate graphical user interfaces. Even if QT support for Windows platforms is extensive, your system might display the error message when you try to open OneDrive, OBS Studio, Python, or even video games.

 While this isn’t one of the common errors on Windows, you can still fix it using the tips below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Change the QT Files Location

 Sometimes, a simple trick such as changing the QT files location is enough to get rid of the error. Here’s how you can do it:

1. Launch File Explorer and open**This PC** .
2. Using the**Search** field, search for**pyqt5\_tools** .
3. When Windows finishes the search, right-click the**pyqt5\_tools** and head to**Open folder location** .
4. Head to**PyQt5 > Qt > bin** . Copy the**platforms** folder.  
![Fix qt error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/platforms-folder-1.jpg)
5. Make a new search for**site-packages** and open the folder.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. There, paste the**platforms** folder.
7. Windows will warn you there’s already a folder with the same name. Click**Replace the files in the destination** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Run an SFC Scan

 There’s a chance Windows display the “Application failed because no QT platform plugin could be initialized” error due to corrupt system files. Fortunately, Windows has a built-in tool to help you fix the problem.

 In the Start menu search bar, search for**command prompt** and select**Run as administrator** . Then, run the**sfc /scannow** command line. Windows will scan and automatically replace any corrupted system file.

![sfc-scan-1-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sfc-scan-1-1.jpg)

 If the System File Checker didn’t fix the problem, there are[more built-in tools to repair corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Perform a Clean Boot

 One of the installed third-party apps might be the reason why you get the “Application failed because no QT platform plugin could be initialized” error. To test it,[perform a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) , which will force it to boot with a minimal list of programs and drivers.

 If Windows stops displaying the error, it means something you've installed on your PC is causing the problem. Take a look at your installed apps, and remove any software that might be causing the problem. If you're unsure as to what might be doing it, slowly re-enable apps through the clean boot until the issue reappears.

## 4\. Update the Malfunctioning App

 An outdated version of the app you're trying to use might be the reason for the QT error. In this case, simply updating the app should solve the issue.

 If you’ve downloaded the app from Microsoft Store, launch it and head to**Library** . There, you’ll see a list of available updates. You can update the apps individually, or click**Get updates** to update them all.

![Update Microsoft Store apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mcirosoft-store-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/May-pLCUkEA?si=PGlcFZAlsp3S3beI&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Reinstall the Troublesome App

 As the error message hints, reinstalling the app might fix the problem. When reinstalling the app, make sure you get it from its official website, to avoid any future problems.

 If you're having issues getting rid of the app, check out[how to fix Windows when it won't allow you to uninstall a program](https://www.makeuseof.com/windows-cant-uninstall-program-fix/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Uninstall Any Recent Windows Updates

 Sometimes, Windows display the “Application failed because no QT platform plugin could be initialized” error after a system update. In this case, you can load a restore point to undo the change and get rid of the error.

 But if there’s no restore point available, you can manually uninstall Windows updates.

1. Launch Windows Settings by pressing**Win + I** .
2. From the left pane, click**Windows Update > Update History** .
3. Head to**Related Settings** and click**Uninstall updates** .
4. Right-click the latest update and select**Uninstall** .

![Uninstall recent Windows updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-updates-1.jpg)

## Get Rid of the QT Error on Windows

 Hopefully, one or more of the above solutions helped you fix the “Application failed to start because no Qt platform plugin could be initialized” error.

 Sometimes, it’s difficult to figure out the exact cause of a Windows error, and reinstalling the app every time might not be the most efficient solution. To speed up the troubleshooting process, you should use one of the many Windows repair tools.

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
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-a-practical-pathway-for-profit-tracking-the-straightforward-steps-to-analyze-youtube-earnings/"><u>[Updated] 2024 Approved A Practical Pathway for Profit Tracking The Straightforward Steps to Analyze YouTube Earnings</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-tiktok-user-birthday-visualization-pixels-type-elapsed/"><u>[Updated] In 2024, TikTok User Birthday Visualization Pixels, Type, Elapsed</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-snapshotstop-screen-shot-on-demand-guide/"><u>2024 Approved SnapshotStop Screen Shot on Demand Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-your-windows-experience-effective-cmd-shortcuts-in-win11/"><u>Command Your Windows Experience: Effective Cmd Shortcuts in Win11</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-tech-innovations-at-ces-2024-a-review-of-leading-laptops-and-more-zdnet/"><u>Exploring Tech Innovations at CES 2024: A Review of Leading Laptops and More - ZDNet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-windows-10-dual-software-compatibility-error/"><u>Fix 'Windows 10: Dual Software Compatibility Error'</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-track-imei-number-of-nokia-130-music-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of Nokia 130 Music Through Google Earth?</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-8-plus-to-other-iphone-12-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 8 Plus to other iPhone 12 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/1715860018230-in-2024-the-ultimate-cut-for-quality-offline-ipad-gaming/"><u>In 2024, The Ultimate Cut for Quality Offline iPad Gaming!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimalist-web-expeditions-top-7-browser-options-with-lower-ram-demands/"><u>Minimalist Web Expeditions: Top 7 Browser Options With Lower RAM Demands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mp3-to-cd-transforming-music-with-windows-and-imgburn-technique/"><u>Mp3 to CD: Transforming Music with Windows and ImgBurn Technique</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-workflow-with-essential-command-shortcuts-for-win11-users/"><u>Optimize Workflow with Essential Command Shortcuts for Win11 Users</u></a></li>
<li><a href="https://win-blog.techidaily.com/optimizing-performance-for-cyberpunk-2077-how-to-reduce-excessive-cpu-use/"><u>Optimizing Performance for Cyberpunk 2077: How to Reduce Excessive CPU Use</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolving-backward-panel-distortion-in-windows-10/"><u>Resolving Backward Panel Distortion in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-microsoft-store-error-0x80073cf3-on-win1111/"><u>Troubleshooting Microsoft Store Error 0X80073cf3 on Win11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-power-of-powershell-4-fixes-to-disable-policy-error/"><u>Unlocking the Power of PowerShell: 4 Fixes to Disable Policy Error</u></a></li>
</ul></div>

