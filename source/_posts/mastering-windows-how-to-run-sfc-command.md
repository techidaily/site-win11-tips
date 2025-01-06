---
title: "Mastering Windows: How to Run SFC Command"
date: 2024-12-30T01:52:11.079Z
updated: 2025-01-06T07:55:31.831Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Windows: How to Run SFC Command"
excerpt: "This Article Describes Mastering Windows: How to Run SFC Command"
keywords: Run SFC Command,System File Checker,Windows Repair Tool,Fixing Windows Errors,Optimize OS Performance,Troubleshoot Windows Issues,Enhance System Stability
thumbnail: https://thmb.techidaily.com/e9bfba9f2cfc27dda62a022203f7d3d74b3b40178416607e8e0046420c189dda.jpg
---

## Mastering Windows: How to Run SFC Command

 Your Windows computer depends on operating system files to get the information it needs to run smoothly. But sometimes, these files can become corrupted or go missing from your PC, affecting your system negatively in various ways. For example, when something’s wrong with a critical system file, your computer might become slow or crash frequently.

 An easy way to fix problematic system files is to use the System File Checker (SFC). This tool will scan your computer, check the integrity of each system file, and repair those that are damaged or missing.

 Here’s what you need to know about running the SFC tool on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Run a System File Checker Scan on Windows

 To use the SFC, you need to run a single command in Command Prompt. Here’s how:

1. Press**Win + S** to open Windows Search and type**command prompt** in the search box.
2. This will bring up**Command Prompt** in the search result. Click on the**Run as administrator** option.  
![Run Command Prompt Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-Command-Prompt-Using-Windows-Search.jpg)
3. Click**Yes** in the UAC prompt to allow Command Prompt to make changes to your computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. In Command Prompt, enter the below command, and then hit the**Enter** key:  
`SFC /scannow`

 If you’re unfamiliar with operating system files, please read our guide on[what system files are on Windows](https://www.makeuseof.com/windows-system-files-guide/) . And to learn everything you need to know about Command Prompt, you can check out our[beginner's guide to Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) .

## What Happens After I Run the System File Checker?

 After the System File Checker completes its scan, it will display a message in the Command Prompt window with the results.

 If your system files are okay, you’ll see a message that says "Windows Resource Protection did not find any integrity violations." If SFC found and fixed all problematic files, the message will read "Windows Resource Protection found corrupt files and successfully repaired them."

![the results of an sfc scan in Command Prompt on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-scan-results.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 On the other hand, if it found corrupted files but couldn’t repair any or all of them, the message will read "Windows Resource Protection found corrupt files but was unable to fix some of them." And if SFC encounters a problem, the message will say "Windows Resource Protection could not perform the requested operation."

## Other SFC Commands You Can Run on Windows

 The**SFC /scannow** isn’t the only System File Checker Command you can run. Here are a couple more and what they do:

| SFC Command | Description                                                                                                                                                                                                                                                                       |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| /verifyonly | Run this command if you want SFC to check for problematic operating system files without fixing them.                                                                                                                                                                             |
| /scanfile   | Run this command if you want SFC to check a specific file for problems and fix it if it does have them. For example, Here’s the full command for checking and fixing the**user32.dll** file:**SFC /scanfile=c:\\windows\\system32\\user32.dll**                                   |
| /verifyfile | Run this command if you only want to check a particular system file for problems. Even if SFC finds an issue with the file, it will not repair it. For example, Here’s the full command for checking the**user32.dll** file:**SFC /verifyfile=c:\\windows\\system32\\user32.dll** |
| /offbootdir | Run this command to tell the SFC which directory contains a bootable version of Windows. You need to do this every time you use the tool outside of Windows. For example, to select the**E:** drive on your PC, enter**/offbootdir=e:\\**                                         |
| /offwindir  | Run this command to tell the SFC which folder in the directory — the one you specified with the**SFC /offbootdir** command — contains Windows. For example, enter**/offwindir=e:\\windows** to tell the System File Checker that Windows is on the**E:** drive.                   |

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Run an Offline SFC Scan on Windows

 There are a few scenarios that warrant the use of the SFC without logging into Windows. One such scenario is if the operating system files are so corrupted that Windows cannot start.

 In that case, you can run SFC by[creating a bootable Windows disc or drive](https://www.makeuseof.com/tag/make-bootable-usb-cd-dvd-install-windows-using-iso-file/) and using it to fix damaged system files. This is called an offline scan.

 The important thing to remember about an offline scan is that you need to tell the SFC where to find Windows on the bootable drive. Here’s what a**/scannow** command would look like if you ran it offline:

`SFC /scannow /offbootdir=d:\ /offwindir=d:\windows`

 That above command will tell SFC to look for Windows in the**Windows** folder on the**D:** drive. But keep in mind that the Windows version on the bootable media needs to be the same as the one installed on your PC for the scan and repair to be successful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Find the SFC Log File On Windows

 After the SFC does its thing, it will log the results of the scan and any repairs it made into a text file called**CBS.log** . To open it, press**Win + R** to open Windows Run, enter the below text, and click**OK** :

`%windir%\logs\cbs\cbs.log`

 The CBS.log file contains other logs besides those from the System File Checker. When looking through the entries, look for those that have an**\[SR\]** tag on them. Each entry will contain the date and time of the scan, along with the details of what happened.

![cbs log file on Windows that has been opened in Notepad with the SR tag part showing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/cbs-log-sfc-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you don’t want to bother with searching through the**CBS.log** file for the entries with the**\[SR\]** tag, you can extract them to a file called**sfcdetails.txt** . To do that, open Command Prompt as an administrator, and run the below command:

`findstr /c:"[SR]" %windir%\logs\cbs\cbs.log >sfcdetails.txt`

 You can find**sfcdetails.txt** by heading to**This PC > Local Disk (C:) > Windows > System32** .

![the sfc details text file in File Explorer on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-details-file.jpg)

 You’ll see that the log file contains entries from the System File Checker only.

![the sfc details text file on Windows opened in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-detail-txt.jpg)

 If you’re doing an offline scan, you can enable logging by simply specifying the file path with the following command structure:

`/offlogfile=[offline log file path]`

 Just replace**offline log file path** in the square brackets with the actual path you want to store the offline log file in the offline directory. Then, insert this entire command after the**/windir** command when running an offline SFC scan.

## Running the System File Checker, Demystified

 We have only just begun to scratch the surface of what you can do with the System File Checker on Windows 10 and 11\. However, now that you know**how to run SFC** (both in and out of Windows), you can use the tool effectively to troubleshoot problems with operating system files.

 Using the SFC effectively is a necessary skill for every Windows user, and it’s just one of the many tools you can use to fix problems on your Windows computer.

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
<li><a href="https://youtube-docs.techidaily.com/he-ultimate-guide-to-free-multimedia-content-creation/"><u>[New] The Ultimate Guide to Free Multimedia Content Creation</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-use-google-trends-to-come-up-with-video-ideas-for-2024/"><u>[Updated] How to Use Google Trends to Come up with Video Ideas for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-depth-study-of-video-tech-outside-manycam-for-2024/"><u>[Updated] In-Depth Study of Video Tech Outside ManyCam for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-professional-workshop-embedding-countdown-features-in-obs/"><u>[Updated] Professional Workshop Embedding Countdown Features in OBS</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-htc-u23-pro-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My HTC U23 Pro Wont Charge | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-variants-of-moviemaker-pro-on-windows/"><u>2024 Approved Variants of MovieMaker Pro on WIndows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-store-hiccups-the-0x00000000-guide/"><u>Correcting Windows Store Hiccups: The 0X00000000 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-your-windows-lookup-an-ms-store-approach/"><u>Customizing Your Window's Lookup: An MS Store Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-engage-rapid-repair-service-w11s-qa/"><u>How to Engage Rapid Repair Service: W11's QA</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-best-vimeo-video-downloaders/"><u>In 2024, Best Vimeo Video Downloaders</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-mirthful-melodies-curated-list-of-funny-phone-sounds/"><u>In 2024, Mirthful Melodies Curated List of Funny Phone Sounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11s-security-controlling-folder-permissions/"><u>Mastering Windows 11'S Security: Controlling Folder Permissions</u></a></li>
<li><a href="https://some-approaches.techidaily.com/movaviden-oncut-pc-icin-mp4-film-rehberi-and-online-uygulama/"><u>Movavi'den Öncüt: PC Için MP4 Film Rehberi & Online Uygulama</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinvigorating-windows-group-policy-configurations/"><u>Reinvigorating Windows Group Policy Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-navigate-through-microsofts-safe-access-restriction/"><u>Strategies to Navigate Through Microsoft's Safe Access Restriction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/syncing-wireless-and-cable-on-windows-a-step-by-step-tutorial/"><u>Syncing Wireless and Cable on Windows: A Step-by-Step Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-existent-windows-dll-mfc71udll/"><u>Troubleshooting Non-Existent Windows DLL: Mfc71u.dll</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-selection-of-no-cost-publicly-available-dns-servers/"><u>Ultimate Selection of No-Cost, Publicly Available DNS Servers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-restricted-organizational-browser-settings-on-windows-machines/"><u>Unlocking Restricted Organizational Browser Settings on Windows Machines</u></a></li>
</ul></div>

