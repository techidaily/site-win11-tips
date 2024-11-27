---
title: Diagnosing and Repairing Defrag Glitch in OS
date: 2024-11-26T17:55:42.194Z
updated: 2024-11-27T17:42:25.594Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Diagnosing and Repairing Defrag Glitch in OS
excerpt: This Article Describes Diagnosing and Repairing Defrag Glitch in OS
keywords: Fix OS Defrag Issues,Diagnose Defrag Errors,Repair OS Fragmentation,Resolve Defrag Problems,Detect OS Defrag Glitches,Address OS Defrag Faults,Correct OS File Organization
thumbnail: https://thmb.techidaily.com/1ee4d598dddce3a6246087c27cdd3992445e17b0d9a8038ff04440aee38e00e3.jpg
---

## Diagnosing and Repairing Defrag Glitch in OS

 The Disk Defragmenter tool is a Windows user's best friend. This tool fixes fragmentation issues so that your hard drive runs smoother, but it itself sometimes comes across problems of its own. If you're having trouble with your disk defragmenter, there are a few things you can do to resolve the problem.

 In this article, you will learn how to fix the Disk Defragmenter so it works properly again.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is the Disk Defragmenter? Why Does It Stop Working?

 The Disk Defragmenter tool rearranges files on your hard drive so that they are stored in a contiguous manner. This helps to improve file access speed and overall system performance. Disk fragmentation can occur over time as you add, remove, and modify files on your hard drive.

 Although a disk defragmenter is an important tool for keeping your computer running smoothly, sometimes it does not work as it should. Here are a few things that can cause the disk defragmenter to stop working:

1. The tool won't work if you have a solid-state drive (SSD). SSDs don't need to be defragmented because they don't have the same type of moving parts that traditional hard drives do.
2. Another possibility is that you have a virus or malware on your computer that's interfering with the disk defragmenter. You can try running a virus scan to see if that fixes the problem.
3. Corrupt system files can also cause the service to malfunction. In such a case, it may be worthwhile running an SFC (System File Checker) scan as a way to diagnose the problem.

 Now we know what causes the Disk Defragmenter to stop working, it's time to look at some solutions that may help you fix the problem.

## 1\. Check Disk Defragmenter's Status

 If your computer is running slowly, one potential reason could be that the Disk Defragmenter service is not running properly. This service helps to optimize your hard drive by rearranging files so that they can be read more quickly and efficiently.

 To check if the Disk Defragmenter service is running properly, follow the steps:

1. Open the Services app (see[ways to open the Services app on Windows](https://www.makeuseof.com/windows-11-open-services-app/) ).
2. Scroll down to the "Optimise drives" service and double-click on it.
3. Click on the drop-down menu and set the Start type to "Manual."
4. Make sure the Service status is "Running." If it is not, then click on**Start** to run it.  
![Set Optimise drives Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Set-Optimise-drives-Properties.jpg)
5. Click**Apply > OK** to save it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After making the above changes, check if it solves the problem. If not, move on to the next solution.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Run the System File Checker tool

 Another way to fix your disk defragmenter is to run the System File Checker tool. This tool will scan all of your system files and replace any that are corrupt or missing.

To run the System File Checker, follow these steps:

1. Press**Win + X** on your keyboard to open the Power User menu.
2. Select the**Run** option from the menu list.
3. In the Run command dialog box, type "cmd" and press**Ctrl + Shift + Enter** at the same time.
4. When UAC appears on the screen, select**Yes** to approve administrator access.
5. Once you're in the Command Prompt window, type "sfc /scannow", and press**Enter** .

 It may take a while for the scan to complete, so be patient. Once the scan is complete, restart your computer and try running Disk Defragmenter again. It should now work properly.

![SFC and DISM Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/SFC-and-DISM-Scan.jpg)

 If you're still having trouble with your Disk Defragmenter tool after running an SFC scan, you may need to use the DISM utility. To do this, open the Command Prompt as an administrator and run the below command line:

`DISM /Online /Cleanup-Image /ScanHealth\nDism.exe /online /cleanup-image /restorehealth`

 Once the scan is complete, restart your computer and try defragmenting again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aRMCbJxLuwE?si=E5sfJvoqkv1qCMWz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Run the CHKDSK Utility

 If your computer's Disk Defragmenter is still not working, you can try[running the CHKDSK utility](http://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) . This is a computer program designed to check the integrity of your hard drive, identify errors, and fix them.

To run the CHKDSK utility, follow the below steps:

1. Press the Windows key and search for "Command Prompt".
2. Right-click on the search result and select**Run as administrator** .
3. Click**Yes** if UAC prompts on your computer screen. This will open a Command Prompt with admin access.  
![Run chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-chkdsk-command.jpg)
4. When you're in Command Prompt, type the following command and press Enter:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`chkdsk C: /f`

 In the command above,**"C:"** represents your drive, so you should replace it with the letter that refers to your drive.

 Once the scanning process is completed, and you have been informed that your drive has been scanned, try to defragment it again.

 As it turns out, it may take several minutes for the scan to complete, depending on the size of your partition and sometimes it seems to get stuck. However, you should let it complete its task uninterrupted.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Close All Third-Party Applications

 Some third-party applications may interfere with Disk Defragmenter if they are running. In such a case, close all third-party programs and see if that helps the defragmenter to run properly.

 If you close all active windows and find that the defragmenter is still having issues, there might be a background process interfering with it. As such, you can try ending some third-party processes and see if that fixes it.

1. Press**Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
2. On the Processes tab, find a non-essential third-party service and right-click on it.
3. Then select**End task** from the context menu.  
![Close Programs Via Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Close-Programs-Via-Task-Manager.jpg)

 After closing one, check if the disk defragmenter works again. If it does, the service you just closed is the culprit. Now you can either update, re-install, or even uninstall the problematic app so it stops interfering with Disk Defragmenter.

## Fixing Windows Disk Defragmenter's Opening Issues

 Disk defragmentation can improve the situation by rearranging files so that they can be evenly distributed throughout the drive. However, sometimes the Disk Defragmenter tool doesn't work as expected. If you encounter this problem, the methods described above should help you resolve it.

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-17-easy-ways-grab-your-webinars-without-financial-investment-for-2024/"><u>[New] 17 Easy Ways Grab Your Webinars Without Financial Investment for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-evaluating-best-youtube-extractors-available-on-android/"><u>[New] 2024 Approved Evaluating Best YouTube Extractors Available on Android</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-freecam-x-live-streaming-software-reviewed/"><u>[New] In 2024, FreeCam X Live Streaming Software Reviewed</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-leading-tips-for-mute-video-capture/"><u>[Updated] Leading Tips for Mute Video Capture</u></a></li>
<li><a href="https://technical-tips.techidaily.com/find-your-perfect-match-with-these-adered-by-free-and-html-editor-but-also-include-relevant-keywords-like-windows-code-editing-tools-or-webpage-builders-her14/"><u>Find Your Perfect Match with These Adered by Free and HTML Editor, but Also Include Relevant Keywords Like Windows, Code Editing Tools, or Webpage Builders. Here Are Five Examples of New SEO Titles that Convey a Similar Meaning to the Original Phrase</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-failing-display-connection-on-pcs/"><u>How to Rectify Failing Display Connection on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unblock-lunar-client-launch-failure-on-pc/"><u>How to Unblock Lunar Client Launch Failure on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improving-windows-non-responsive-performance-chart/"><u>Improving Windows' Non-Responsive Performance Chart</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-essential-list-of-premium-cost-free-webm-streaming-services/"><u>In 2024, Essential List of Premium, Cost-Free WebM Streaming Services</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-10-fingerprint-lock-apps-to-lock-your-vivo-s17-phone-by-drfone-android/"><u>In 2024, Top 10 Fingerprint Lock Apps to Lock Your Vivo S17 Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/invisible-file-thumbnails-in-windows-11-how-to-repair/"><u>Invisible File Thumbnails in Windows 11 – How to Repair</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-no-installed-devices-message-on-pcs/"><u>Overcoming 'No Installed Devices' Message on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-ms-defenders-record-top-strategies-for-windows-users/"><u>Overcoming MS Defender's Record: Top Strategies for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-obstacles-to-unique-printer-id/"><u>Removing Obstacles to Unique Printer ID</u></a></li>
<li><a href="https://techtrends.techidaily.com/resolving-no-internet-secured-issues-in-windows-a-step-by-step-guide/"><u>Resolving 'No Internet, Secured' Issues in Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/seamless-graphics-transition-in-windows-10-with-nvidiaintel/"><u>Seamless Graphics Transition in Windows 10 with Nvidia/Intel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-restoring-windows-google-nearby-share/"><u>Step-By-Step Guide to Restoring Windows Google Nearby Share</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/step-by-step-tutorial-for-getting-back-permanently-erased-photos-from-your-iphone-securely/"><u>Step-by-Step Tutorial for Getting Back Permanently Erased Photos From Your iPhone Securely</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wins-wired-woes-here-are-6-steps-for-getting-your-network-up-and-running/"><u>Win's Wired Woes? Here Are 6 Steps for Getting Your Network Up and Running</u></a></li>
</ul></div>

