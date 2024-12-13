---
title: Discover Solutions for Programs that Don't Work on Vista/Windows 7.
date: 2024-12-06T22:29:05.844Z
updated: 2024-12-12T19:40:22.754Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Check For Corrupted System Files

 Corrupted system files can cause the Program Compatibility Troubleshooter not to work correctly. To ensure all your system files are functioning properly, run the built-in System File Checker utility on Windows. Here's how to do it:

1. Right-click on**Start** and select**Run** from the menu list.
2. Type**cmd** in the text box and press**Ctrl + Shift + Enter** on your keyboard.
3. If UAC appears on the screen, click**Yes** to grant privileges.  
![Run SFC Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-sfc-command.jpg)
4. In Command Prompt type the below command and hit Enter:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`sfc /scannow`

 Wait for the scan to finish. This may take several minutes and your PC may restart once or twice during the process. Once the scan is completed, check if the Program Compatibility Troubleshooter works now.

## 2\. Repair Corrupted System Image

 If the System File Checker was unable to repair corrupt system files, you can use the DISM tool from Command Prompt to fix them. Here's how to do it:

1. Use one of the many[ways to run Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) to get an elevated prompt running.  
![Run DISM Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-dism-command.jpg)
2. In Command Prompt, type the below command and hit**Enter** :  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`DISM /Online /Cleanup-Image /RestoreHealth`

 The DISM tool will start scanning the system for corruption. It can take up to 20 minutes, but it is worth waiting because it can repair a lot of system issues. Once the scan is completed, restart your computer and check if the issue is fixed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

## 6\. Reset Windows

 If all else fails, you can try[resetting Windows to its default settings](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) . This will reinstall Windows and get rid of any potential issues that may be causing the troubleshooter to not work.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-helps.techidaily.com/new-innovative-approaches-to-achieve-stunning-gopro-time-lapse-for-2024/"><u>[New] Innovative Approaches to Achieve Stunning GoPro Time Lapse for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-maximize-content-impact-three-methods-for-effective-ig-captioning-for-2024/"><u>[New] Maximize Content Impact Three Methods for Effective IG Captioning for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-why-av1-matters-enabling-it-for-youtube-videos/"><u>[Updated] 2024 Approved Why AV1 Matters Enabling It for YouTube Videos</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-giggles-on-iphones/"><u>[Updated] Giggles on iPhones</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-music-mastery-essentials-high-quality-dj-video-samples/"><u>[Updated] Music Mastery Essentials High-Quality DJ Video Samples</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-ultimate-samsung-gear-vr-game-collection/"><u>[Updated] Ultimate Samsung Gear VR Game Collection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-windows-11-cannot-open-file-issue-for-writing/"><u>Counteracting Windows 11: Cannot Open File Issue for Writing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-space-management-in-windows-revealed/"><u>Efficient Space Management in Windows, Revealed</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-downloading-samfw-frp-tool-30-for-itel-a70-by-drfone-android/"><u>In 2024, Downloading SamFw FRP Tool 3.0 for Itel A70</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unreachable-error-from-geforce-experience-on-pc/"><u>Overcoming Unreachable Error From GeForce Experience on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prioritizing-safety-in-windows-11-service-management/"><u>Prioritizing Safety in Windows 11 Service Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-for-win11s-5ghz-wi-fi-disconnection-fixes/"><u>Quick Tips for Win11's 5GHz Wi-Fi Disconnection Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-internal-system-configurations-on-windows-11/"><u>Steps to Rectify Internal System Configurations on Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723006688273-the-kiln-should-be-loaded-with-care-ensuring-tiles-do-not-touch-each-other-and-theres-enough-space-for-heat-circulation/"><u>The Kiln Should Be Loaded with Care, Ensuring Tiles Do Not Touch Each Other and There's Enough Space for Heat Circulation</u></a></li>
</ul></div>

