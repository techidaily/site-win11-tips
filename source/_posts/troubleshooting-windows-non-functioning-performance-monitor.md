---
title: "Troubleshooting Windows: Non-Functioning Performance Monitor"
date: 2024-10-22T19:01:57.275Z
updated: 2024-10-26T16:04:53.222Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting Windows: Non-Functioning Performance Monitor"
excerpt: "This Article Describes Troubleshooting Windows: Non-Functioning Performance Monitor"
keywords: WinMonitor Fix Guide,Poor PC Speed Issue,PM Troubleshoot Steps,Error PM in Windows,Optimize System PM,Rescue Non-PM Windows,Enhance Performance Monitor
thumbnail: https://thmb.techidaily.com/fe074f06665304f02bb44d59a2cf2f7a7e742cf6a430b43148a19a35d32e38f9.jpg
---

## Troubleshooting Windows: Non-Functioning Performance Monitor

 Performance Monitor is a system monitoring tool on Windows that you can use to view real-time statistics about the applications you are running. But sometimes this tool fails to work correctly. If you're facing such a problem on your computer, here are a few fixes you can try to solve it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Reboot your Computer

 Whether you're experiencing performance issues such as slow startup times, or if Performance Monitor isn't working on your system, a simple reboot might do the trick.

 Rebooting Windows clears out any conflicting programs or services that may be causing PerfMon to not work properly. It removes any unnecessary data stored in memory that might be responsible for the issue.

To restart your computer, follow these steps:

1. Open the**Start** menu.
2. Click on the Power button, then select**Restart** .

 Once the computer has restarted, open Performance Monitor and check if the issue has been resolved.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136622/26400" target="_top" id="2136622">
  <img src="//a.impactradius-go.com/display-ad/26400-2136622" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136622/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Restart the Performance Logs and Alerts service

 If rebooting your computer doesn't fix the problem, you can try restarting the Performance Logs and Alerts service. This service is responsible for monitoring system performance settings and generating alert messages when something is wrong.

To restart this service, follow these steps:

1. Press**Win + R** on your keyboard to open the Run command
2. Type**services.msc** in the dialog box and press**Enter** .
3. In the Services window, scroll down to**Performance Logs & Alerts** service.
4. Right-click on the service and select the**Restart** option.  
![Restart Performance service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/restart-performance-service.jpg)

 After you follow the above steps, check if Performance Monitor is working correctly.

## 3\. Run the System File Checker

 The System File Checker is a handy Windows tool that can scan for and fix corrupted system files. It is useful when the Performance Monitor isn't working due to a corrupt system file.

To run the System File Checker, follow these steps:

1. Click on the Start menu.
2. Type**cmd** in the search bar, then press**Ctrl + Shift + Enter** to open an elevated Command Prompt.
3. If UAC appears on the screen, click**Yes** to grant access. You can learn more about this handy tool with our[beginner's guide to the Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) .  
![Run SFC Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-sfc-command.jpg)
4. In the Command Prompt, type the following command and press**Enter** :  

<!-- affiliate ads begin -->
<span id="1993654">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993654.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993654">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993654.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993654%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993654/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

sfc /scannow
5. The scan will check for any corrupted system files and repair them.

 After the scan is complete, restart your computer and check if Performance Monitor is working properly.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100527/7443" target="_top" id="2100527">
  <img src="//a.impactradius-go.com/display-ad/7443-2100527" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100527/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Check for a Windows Update

 In some cases, outdated versions of Windows can cause Performance Monitor problems. To ensure your system is running the latest version of Windows, follow these steps:

1. Press**Win + I** on your keyboard to open System Settings. We also have an in-depth tutorial on[accessing the Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Click**Windows Update** in the left pane.  
![Check for Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/check-for-updates.jpg)
3. Then click the**Check for updates** button.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137225/26400" target="_top" id="2137225">
  <img src="//a.impactradius-go.com/display-ad/26400-2137225" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137225/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If any available updates are found, Windows will download and install them automatically. After the updates have been installed, restart your computer and check if Performance Monitor is now working correctly.

## 5\. Perform a System Restore

 In case you have run out of options, you may want to try a system restore. This way, your computer will be restored to the state it was in before the program stopped working.

To perform a system restore, follow these steps:

1. Press**Win + Q** on your keyboard.
2. Type**System Restore** in the search bar and click on**Create a restore point** .
3. In the System Properties window, click the**System Restore** button.  
![Run System Restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-system-restore.jpg)
4. Choose a restore point, then click**Next** .
5. Follow the on-screen instructions to perform a system restore.

 Upon completion of the restoration process, make sure Performance Monitor is working properly.

## Get Hassle Free Performance and Health Monitoring

 Like any other program, Performance Monitor can have glitches and other issues that prevent it from working correctly. The steps in this article will help you fix these issues and get Performance Monitor up and running again.

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
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-visualsnitch-capture-and-save-tweets-images-and-videos/"><u>[New] In 2024, VisualSnitch Capture and Save Tweets' Images & Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-instagram-guide-to-uploading-podcast-episodes/"><u>[New] Instagram Guide to Uploading Podcast Episodes</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-syncing-vimeo-and-instagram-the-ultimate-guide-for-2024/"><u>[New] Syncing Vimeo and Instagram The Ultimate Guide for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-how-to-make-the-most-out-of-spotifys-advertising-features/"><u>[Updated] In 2024, How to Make the Most Out of Spotify's Advertising Features</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-how-to-remove-signature-background-in-seconds/"><u>2024 Approved How to Remove Signature Background in Seconds</u></a></li>
<li><a href="https://discover-able.techidaily.com/best-free-utilities-for-system-backuprestoration-on-windows-versions-11-10-8-and-7/"><u>Best Free Utilities for System Backup/Restoration on Windows (Versions 11, 10, 8 & 7)</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/crafting-memorable-content-on-snapchat-top-tips-for-2024/"><u>Crafting Memorable Content on Snapchat (Top Tips) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-hdr-on-windows-11-an-in-depth-explanation/"><u>Decoding HDR on Windows 11: An In-Depth Explanation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-conflicts-for-print-job-success/"><u>Eradicating Conflicts for Print Job Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/four-steps-for-pausing-windows-update/"><u>Four Steps for Pausing Windows Update</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-bypass-android-lock-screen-using-emergency-call-on-samsung-galaxy-a25-5g-by-drfone-android/"><u>In 2024, How to Bypass Android Lock Screen Using Emergency Call On Samsung Galaxy A25 5G?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-the-windows-safe-mode-limitation-on-office-suite/"><u>Resolving the Windows-Safe Mode Limitation on Office Suite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simple-techniques-transform-mkv-videos-into-windows-mp4-files/"><u>Simple Techniques: Transform MKV Videos Into Windows MP4 Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-security-with-new-passwords-in-win-11/"><u>Streamline Security with New Passwords in Win 11</u></a></li>
<li><a href="https://win-solutions.techidaily.com/unlock-smooth-gameplay-permanent-solution-for-tf2s-endless-crashes/"><u>Unlock Smooth Gameplay: Permanent Solution for TF2's Endless Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-define-your-own-idle-time/"><u>Windows: Define Your Own Idle Time</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-valorant-on-pc-overcoming-frames-drops/"><u>Winning Valorant on PC: Overcoming Frames Drops</u></a></li>
</ul></div>

