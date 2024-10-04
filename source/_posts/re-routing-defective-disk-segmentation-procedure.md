---
title: Re-Routing Defective Disk Segmentation Procedure
date: 2024-10-02T21:59:10.406Z
updated: 2024-10-03T23:52:09.921Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Re-Routing Defective Disk Segmentation Procedure
excerpt: This Article Describes Re-Routing Defective Disk Segmentation Procedure
keywords: Defective Disk Repair,Segmentation Re-Routing,Data Corruption Fix,Disk Error Handling,Fragmented Disk Recovery,Storage Segmentation,Invalid Sector Removal
thumbnail: https://thmb.techidaily.com/5565177be356d6fd1f6d2b58dc2046c46dae913812fa6d796b06a5e79fd2f303.jpg
---

## Re-Routing Defective Disk Segmentation Procedure

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
<a href="https://appsumo.8odi.net/c/5597632/2049378/7443" target="_top" id="2049378">
  <img src="//a.impactradius-go.com/display-ad/7443-2049378" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049378/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After making the above changes, check if it solves the problem. If not, move on to the next solution.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541">
  <img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047346/19272" target="_top" id="2047346">
  <img src="//a.impactradius-go.com/display-ad/19272-2047346" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047346/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you're still having trouble with your Disk Defragmenter tool after running an SFC scan, you may need to use the DISM utility. To do this, open the Command Prompt as an administrator and run the below command line:

`DISM /Online /Cleanup-Image /ScanHealth\nDism.exe /online /cleanup-image /restorehealth`

 Once the scan is complete, restart your computer and try defragmenting again.

## 3\. Run the CHKDSK Utility

 If your computer's Disk Defragmenter is still not working, you can try[running the CHKDSK utility](http://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) . This is a computer program designed to check the integrity of your hard drive, identify errors, and fix them.

To run the CHKDSK utility, follow the below steps:

1. Press the Windows key and search for "Command Prompt".
2. Right-click on the search result and select**Run as administrator** .
3. Click**Yes** if UAC prompts on your computer screen. This will open a Command Prompt with admin access.  
![Run chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-chkdsk-command.jpg)
4. When you're in Command Prompt, type the following command and press Enter:  
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100541/7443" target="_top" id="2100541">
  <img src="//a.impactradius-go.com/display-ad/7443-2100541" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-syncopating-youtube-melodies-with-visuals/"><u>[New] 2024 Approved Syncopating YouTube Melodies with Visuals</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-top-5-online-youtube-mp3-converters-free-and-easy/"><u>[New] 2024 Approved Top 5 Online YouTube-MP3 Converters, Free and Easy!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavioggflac/"><u>「音質を上げるためのフリーコネクト: MovaviでOGG形式をFLACに簡単変換する方法」</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-breakthrough-techniques-in-youtube-content-creation/"><u>2024 Approved Breakthrough Techniques in YouTube Content Creation</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-chronicles-of-time-student-approved-historical-yt-content/"><u>2024 Approved Chronicles of Time Student-Approved Historical YT Content</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-cutting-edge-zoom-recording-techniques/"><u>2024 Approved Cutting-Edge Zoom Recording Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/answer-cortical-remapping-involves-changes-in-the-brains-motor-cortex-allowing-patients-to-regain-movement-by-learning-new-ways-to-perform-tasks-with-affect1/"><u>Answer: Cortical Remapping Involves Changes in the Brain's Motor Cortex, Allowing Patients to Regain Movement by Learning New Ways to Perform Tasks with Affected Limbs or Using Other Muscles.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-oggmp3-video-converter-by-movavi-convert-your-files-easily/"><u>Free Online OGG/MP3 Video Converter by Movavi - Convert Your Files Easily</u></a></li>
<li><a href="https://change-location.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Xiaomi Redmi Note 12 5G? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-asus-rog-phone-8-lock-screen-password-by-drfone-android/"><u>How To Change Asus ROG Phone 8 Lock Screen Password?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/los-10-lideres-indiscutibles-programas-mas-eficaces-de-voz-en-off-libre-y-pago-del-2024/"><u>Los 10 Líderes Indiscutibles: Programas Más Eficaces De Voz en Off Libre Y Pago Del 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavis-no-cost-web-service-easily-convert-your-wma-audio-to-m4b-format/"><u>Movavi's No-Cost Web Service: Easily Convert Your WMA Audio to M4B Format</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-tech-bargains-during-amazon-prime-day/"><u>Top Tech Bargains During Amazon Prime Day</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformez-votre-image-tiff-en-format-jpeg-faites-le-sans-frais-online-avec-movavi/"><u>Transformez Votre Image TIFF en Format JPEG Faites-Le Sans Frais - Online Avec Movavi</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-from-glitch-to-glory-how-to-reset-final-cut-pro-x-and-resolve-issues/"><u>Updated From Glitch to Glory How to Reset Final Cut Pro X and Resolve Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amv-mpeg-movavi/"><u>무료 AMV MPEG 이미지 크론 원자 바이트로 직막 전환 - Movavi</u></a></li>
</ul></div>

