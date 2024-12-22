---
title: Discover Solutions for Programs that Don't Work on Vista/Windows 7.
date: 2024-12-16T00:45:39.364Z
updated: 2024-12-22T00:03:32.167Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Discover Solutions for Programs that Don't Work on Vista/Windows 7.
excerpt: This Article Describes Discover Solutions for Programs that Don't Work on Vista/Windows 7.
keywords: Fix Windows 7 Glitches,Vista Error Resolution,Unstable Program Remedies,Optimize Vista Performance,Windows XP Compatibility Tips,Enhance Windows 7 Stability,Address OS-Related Issues
thumbnail: https://thmb.techidaily.com/581e555a79746fa6146e452431e04adcc0fe595ec9a8fe5547dd855a218b2d27.jpg
---

## Discover Solutions for Programs that Don't Work on Vista/Windows 7

 The Program Compatibility Troubleshooter is a tool from Microsoft that checks for and resolves compatibility issues when running older applications on newer versions of Windows. However, sometimes the troubleshooter fails to work as expected.

 If you're facing this issue, there are several possible causes and ways to fix it. Let's look into them below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Check For Corrupted System Files

 Corrupted system files can cause the Program Compatibility Troubleshooter not to work correctly. To ensure all your system files are functioning properly, run the built-in System File Checker utility on Windows. Here's how to do it:

1. Right-click on**Start** and select**Run** from the menu list.
2. Type**cmd** in the text box and press**Ctrl + Shift + Enter** on your keyboard.
3. If UAC appears on the screen, click**Yes** to grant privileges.  
![Run SFC Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-sfc-command.jpg)
4. In Command Prompt type the below command and hit Enter:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aG3NRuHrIJg?si=HwzwD0RXmrzIXX1V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`sfc /scannow`

 Wait for the scan to finish. This may take several minutes and your PC may restart once or twice during the process. Once the scan is completed, check if the Program Compatibility Troubleshooter works now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Repair Corrupted System Image

 If the System File Checker was unable to repair corrupt system files, you can use the DISM tool from Command Prompt to fix them. Here's how to do it:

1. Use one of the many[ways to run Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) to get an elevated prompt running.  
![Run DISM Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-dism-command.jpg)
2. In Command Prompt, type the below command and hit**Enter** :  

`DISM /Online /Cleanup-Image /RestoreHealth`

 The DISM tool will start scanning the system for corruption. It can take up to 20 minutes, but it is worth waiting because it can repair a lot of system issues. Once the scan is completed, restart your computer and check if the issue is fixed.

## 3\. Uninstall Third-Party Security Software

 Sometimes, certain third-party security software can interfere with the Program Compatibility Troubleshooter and cause it to not work. Uninstalling these programs should help.

1. Right-click on Start and select**Installed apps** .
2. Search for your security software in the list of installed programs.
3. Then click the three dots and select**Uninstall** .

 Follow the on-screen instructions to remove the program from your PC. Once done, restart your PC and try running the Program Compatibility Troubleshooter again.

## 4\. Restart the Diagnostic Policy Service

 The Diagnostic Policy Service is responsible for allowing the Program Compatibility Troubleshooter to work properly. If it's not running, restarting it should help the troubleshooter function normally.

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type**services.msc** in the text box and click**OK** .
3. Look for the**Diagnostic Policy Service** and double-click it.  
![Restart Diagnostic Policy Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-diagnostic-policy-service.jpg)
4. In the Diagnostic Policy Service Properties window, set the Startup type to**Automatic** and click**Start** .
5. Next, click**Apply** and**OK** to save the changes.

 Now restart your PC and try running the Program Compatibility Troubleshooter again to see if it works.

## 5\. Run the Troubleshooter in Safe Mode

 If you are still experiencing this issue, try running the Program Compatibility Troubleshooter in safe mode. This will help you troubleshoot any compatibility issues more effectively.

To do this, follow the below steps:

1. Start your PC in safe mode (see[how to start Windows in safe mode](https://www.makeuseof.com/windows-11-boot-safe-mode/) for instructions).
2. Once in safe mode,[run the Program Compatibility Troubleshooter](https://www.makeuseof.com/run-program-compatibility-troubleshooter-windows/) and check if it works. If so, it means that one of your installed programs is causing the issue. Try uninstalling them and see if the issue is fixed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Reset Windows

 If all else fails, you can try[resetting Windows to its default settings](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) . This will reinstall Windows and get rid of any potential issues that may be causing the troubleshooter to not work.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fixing Program Compatibility Troubleshooter Problems on Windows

 If the Program Compatibility Troubleshooter is not working on your computer, read this guide. The steps here will help you fix this issue and have the tool working and running again.

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-5-essential-steps-to-prevent-blank-screen-issues-in-obs/"><u>[New] In 2024, 5 Essential Steps to Prevent Blank-Screen Issues in OBS</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-best-free-cloud-options-get-unlimited-storage-1tbplus/"><u>[New] In 2024, Best Free Cloud Options Get Unlimited Storage (1TB+)</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-perfecting-auto-captioned-content-in-instagram-reels/"><u>[Updated] 2024 Approved Perfecting Auto-Captioned Content in Instagram Reels</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-elevating-content-strategy-with-effective-youtube-partnerships/"><u>2024 Approved Elevating Content Strategy with Effective YouTube Partnerships</u></a></li>
<li><a href="https://solve-hot.techidaily.com/1732516421973-yl-software/"><u>解析武则天统治期间的重大历史事件及其影响力：一个关于中国宫廷政治的深度研究 - YL Software</u></a></li>
<li><a href="https://screen-capture.techidaily.com/best-offline-ios-game-selection-for-screen-time-savor/"><u>Best Offline iOS Game Selection for Screen Time Savor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-open-the-authorization-manager-in-windows-11/"><u>How to Open the Authorization Manager in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-overcome-windows-installation-mishap-0xc004f050/"><u>How to Overcome Windows Installation Mishap 0xC004F050</u></a></li>
<li><a href="https://fox-place.techidaily.com/how-to-use-protected-mode-for-file-sharing-on-microsoft-windows-windows-11-10-8-and-7-explained/"><u>How to Use Protected Mode for File Sharing on Microsoft Windows - Windows 11, 10, 8, and 7 Explained</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-poco-x6-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Poco X6 to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/innocns-budget-friendly-gamers-choice/"><u>InnoCN's Budget-Friendly Gamer's Choice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-management-of-windows-credentials-11/"><u>Mastering the Management of Windows Credentials (11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-potential-unlock-the-most-innovative-windows-powertoy-tips/"><u>Maximize Potential: Unlock the Most Innovative Windows PowerToy Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-obstacles-reinstate-mspm-in-windows-7/"><u>Overcome Obstacles: Reinstate MSPM in Windows 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-headset-mic-connectivity-issues/"><u>Resolving Windows Headset Mic Connectivity Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slow-sell-of-windows-11-why-users-prefer-the-oldie/"><u>Slow Sell of Windows 11: Why Users Prefer the Oldie</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-arrange-bunched-up-taskbar-icons/"><u>Strategies to Arrange Bunched-Up Taskbar Icons</u></a></li>
</ul></div>

