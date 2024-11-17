---
title: Troubleshooting Non-Functional File Consolidation Tool
date: 2024-11-15T17:32:39.921Z
updated: 2024-11-17T16:17:52.093Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Non-Functional File Consolidation Tool
excerpt: This Article Describes Troubleshooting Non-Functional File Consolidation Tool
keywords: Fix Consolidate Files Error,Unblock File Merge Issue,Resolve File Aggregator Failure,Stop Duplicate File Problems,Correct File Combination Mishaps,End File Sync Glitches,Clear Concat File Issues
thumbnail: https://thmb.techidaily.com/934c09a684ad314c00e00ed21a2e7539ae4858551b2266da80c837988bee503d.jpg
---

## Troubleshooting Non-Functional File Consolidation Tool

 The Disk Defragmenter tool is a Windows user's best friend. This tool fixes fragmentation issues so that your hard drive runs smoother, but it itself sometimes comes across problems of its own. If you're having trouble with your disk defragmenter, there are a few things you can do to resolve the problem.

 In this article, you will learn how to fix the Disk Defragmenter so it works properly again.

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

 After making the above changes, check if it solves the problem. If not, move on to the next solution.

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

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2148127/17093" target="_top" id="2148127">
  <img src="//a.impactradius-go.com/display-ad/17093-2148127" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2148127/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you're still having trouble with your Disk Defragmenter tool after running an SFC scan, you may need to use the DISM utility. To do this, open the Command Prompt as an administrator and run the below command line:

`DISM /Online /Cleanup-Image /ScanHealth\nDism.exe /online /cleanup-image /restorehealth`

 Once the scan is complete, restart your computer and try defragmenting again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972670/19272" target="_top" id="1972670">
  <img src="//a.impactradius-go.com/display-ad/19272-1972670" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972670/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://bluettieu.pxf.io/c/5597632/2141680/17091" target="_top" id="2141680">
  <img src="//a.impactradius-go.com/display-ad/17091-2141680" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141680/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`chkdsk C: /f`

 In the command above,**"C:"** represents your drive, so you should replace it with the letter that refers to your drive.

 Once the scanning process is completed, and you have been informed that your drive has been scanned, try to defragment it again.

 As it turns out, it may take several minutes for the scan to complete, depending on the size of your partition and sometimes it seems to get stuck. However, you should let it complete its task uninterrupted.

## 4\. Close All Third-Party Applications

 Some third-party applications may interfere with Disk Defragmenter if they are running. In such a case, close all third-party programs and see if that helps the defragmenter to run properly.

 If you close all active windows and find that the defragmenter is still having issues, there might be a background process interfering with it. As such, you can try ending some third-party processes and see if that fixes it.

1. Press**Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
2. On the Processes tab, find a non-essential third-party service and right-click on it.
3. Then select**End task** from the context menu.  
![Close Programs Via Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Close-Programs-Via-Task-Manager.jpg)

 After closing one, check if the disk defragmenter works again. If it does, the service you just closed is the culprit. Now you can either update, re-install, or even uninstall the problematic app so it stops interfering with Disk Defragmenter.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915870/19272" target="_top" id="1915870">
  <img src="//a.impactradius-go.com/display-ad/19272-1915870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915870/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://article-knowledge.techidaily.com/new-in-depth-slomo-video-software-review-year-2024/"><u>[New] In-Depth SloMo Video Software Review - Year 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-elevating-the-cold-with-five-cozy-cinematic-elements/"><u>[Updated] 2024 Approved Elevating the Cold with Five Cozy Cinematic Elements</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-the-blueprint-for-selecting-exceptional-hdr-cameras/"><u>[Updated] The Blueprint for Selecting Exceptional HDR Cameras</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-the-art-of-effective-online-engagement-on-fb/"><u>2024 Approved The Art of Effective Online Engagement on FB</u></a></li>
<li><a href="https://android-frp.techidaily.com/about-realme-12-pro-5g-frp-bypass-by-drfone-android/"><u>About Realme 12 Pro 5G FRP Bypass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-your-win-os-window-snapping-paradigm/"><u>Crafting Your Win OS Window Snapping Paradigm</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-hidden-windows-bar-when-edges-are-expanded/"><u>Dealing With Hidden Windows Bar when Edges Are Expanded</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-pc-performance-reducing-extraneous-tasks/"><u>Enhancing PC Performance: Reducing Extraneous Tasks</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-to-intercept-text-messages-on-apple-iphone-11-pro-drfone-by-drfone-virtual-ios/"><u>How to Intercept Text Messages on Apple iPhone 11 Pro | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-forgot-pattern-lock-heres-how-you-can-unlock-realme-narzo-n53-pattern-lock-screen-by-drfone-android/"><u>In 2024, Forgot Pattern Lock? Heres How You Can Unlock Realme Narzo N53 Pattern Lock Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mysterious-menu-moves-win11s-vanishing-power-option/"><u>Mysterious Menu Moves: Win11's Vanishing Power Option</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/openai-launches-game-changing-gpt-4-artificial-intelligence-model/"><u>OpenAI Launches Game-Changing GPT-4 Artificial Intelligence Model</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silent-system-switches-win11s-undetectable-power-feature/"><u>Silent System Switches: Win11's Undetectable Power Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-x80246007-in-windows-updates/"><u>Troubleshooting X80246007 in Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-diagnostic-skills-using-command-prompt-for-pinpointing-and-correcting-windows-errors/"><u>Unlocking Diagnostic Skills: Using Command Prompt for Pinpointing & Correcting Windows Errors</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-edit-and-organize-your-mp4-videos-with-these-tag-editors/"><u>Updated 2024 Approved Edit and Organize Your MP4 Videos with These Tag Editors</u></a></li>
</ul></div>

