---
title: Fixing Failed Windows Update Due to 0X800f0845
date: 2024-10-08T19:27:35.223Z
updated: 2024-10-14T16:44:04.015Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Failed Windows Update Due to 0X800f0845
excerpt: This Article Describes Fixing Failed Windows Update Due to 0X800f0845
keywords: Windows Update Failure Fix,Windows Error Code 0X800F0845,Troubleshoot Windows Updates,Resolve Update Error X800F,Corrupt Windows Update FIX,Uninstall Failed Updates,Repair Windows Updates Issues
thumbnail: https://thmb.techidaily.com/f5bde08083c297970b9e93f509911df9c27588c391ed27c568746499c49e24b7.jpg
---

## Fixing Failed Windows Update Due to 0X800f0845

 Windows Update brings new features to your PC while installing important security updates and bug fixes. So it's vital to keep your system updated to work and play hassle-free on Windows.

 However, some unexpected errors occur, resulting in updates failing to install on your system. And 0x800f0845 is one such error.

 But you can get past the 0x800f0845 error and continue to install essential updates by trying the following fixes.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is the Windows Update 0x800f0845 Error?

 0x800f0845 is an error that mostly occurs while installing cumulative updates on your Windows PC. You may experience this update error if Windows components and services are corrupted or if there are damaged or missing system files. Sometimes, this error happens by the interactions of third-party apps with the system apps.

 You may not come to know of the error while updating, as Windows will appear to be updating normally with messages of the updates installing—such as**Updates are underway. Please keep your computer on** .

 However, just before your PC reboots, the following message on your computer screen may appear: **Something didn't go as planned. No need to worry—undoing changes. Please keep your computer on** . This message indicates a problem with the update. When your computer restarts, the cumulative update would have failed to install.

 You can check for the same by going to**Settings > Windows Update** and then clicking**Update history** . In**Update history** , you will get the message that the cumulative update has failed to install with the error code**0x800f0845** like the screenshot below.

![0x800f0845 Error in Windows Update History](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/0x800f0845-error-update-history.jpg)

 So what can you do now? Cumulative updates are quality updates, so these must be installed. Fortunately, as there are ways to get past the 0x800f0845 error and install the failed updates.

## 1\. Run the Windows Update Troubleshooter

 It's always better to try fixing Windows update errors first by using the Windows Update Troubleshooter. It scans your PC for problems, attempts to resolve them, and then applies the fixes.

1. Right-click the**Windows icon** on the taskbar and select**Settings** . Or use the[many ways to open Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. On the left pane in**Settings** , click**System** . On the**System** page, click**Troubleshoot** on the right pane.
3. In the**Troubleshoot** page, select**Other troubleshooters** .  
![Select Other Trouble-shooters in Troubleshoot Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/troubleshoot-other-trouble-shooters.jpg)
4. Then click**Run** on the**Windows Update** troubleshooter.  
![Run Windows Update Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-windows-update-troubleshooter.jpg)

 The Windows Update troubleshooter will automatically run its scans to diagnose problems. After troubleshooting completes, you'll get the message that changes have been made to your system and you should try attempting the tasks you were doing earlier.

![Windows Update Troubleshooting Complete Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-troubleshooting-complete.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997643/19272" target="_top" id="1997643">
  <img src="//a.impactradius-go.com/display-ad/19272-1997643" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997643/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 So close the troubleshooter and restart your computer. Then try updating Windows again and check if the failed update gets installed.

## 2\. Temporarily Disable Your Antivirus Software

 Sometimes, third-party antivirus installed on your PC may cause problems when you're updating Windows. So try temporarily disabling it and then installing updates.

 Your antivirus may have options to disable it temporarily. Or right-click on the Windows icon on the taskbar and select**Task Manager** .

 In**Task Manager** , click the**Startup** tab and look for your antivirus software. Then, right-click on it and choose**Disable** .

Try updating Windows now and see if the update gets installed.

## 3\. Run the System File Checker and the DISM Tool

 Corrupted Windows system files could also be the cause of the 0x800f0845 error. To scan, repair, and replace such damaged files, run the System File Checker or SFC scan.

 And if the SFC doesn't work properly, and can’t repair your system files, you should run the DISM or Deployment Image Servicing and Management tool. DISM is a command-line tool that can be used to service and repair Windows images, including those used for Windows Recovery and Windows Setup.

 To know how to run the SFC and DSIM, you can explore our guide on[CHKSDK, SFC, and DISM, and how they work](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) .

 These scans will take a few minutes to run. If the 0x800f0845 error was caused by corrupted files, it should have been fixed. So try updating Windows again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918666/19272" target="_top" id="1918666">
  <img src="//a.impactradius-go.com/display-ad/19272-1918666" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918666/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Reset Windows Update Components

 Error 0x800f0845 could occur if some Windows Update components have got corrupted. You could reset Windows components to get the Windows update running fine again. Here's how:

[Open Windows Terminal](https://www.makeuseof.com/windows-11-open-windows-terminal/) using one of the many ways. Or type**Windows Terminal** in**Windows Search** . Then, right-click**Windows Terminal** under**Best match** and select**Run as administrator.**

 First, you need to stop the update services. In the Windows Terminal window, type the following four commands one by one, making sure that you press**enter** after each command:

`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc`

 Then to set up a new SoftwareDistribution folder, you need to rename it. So enter the following command and press**enter** :

`Ren %systemroot%\SoftwareDistribution SoftwareDistribution.old`

 Next, rename the catroot2 folder for Windows to set up a new one. Type the following command and press**enter** :

`Ren %systemroot%\System32\catroot2 catroot2.old`

 Finally, you need to restart the stopped services. Type the following four commands one after the other, while pressing**enter** after each command:

`net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`

 Once you have run all the commands, the update error should have got fixed. Restart your PC and try installing the updates again.

## 5\. Install the Update Manually via the Microsoft Update Catalog

 What if none of the above solutions works for you? No worries, just install the update manually from the Microsoft Update Catalog.

1. Open your browser to search for and visit the[Microsoft Update Catalog website](https://www.catalog.update.microsoft.com/Home.aspx) .
2. Copy the number of the cumulative update or any other update that failed to install from the**Windows Update history** page. Type the update number in the**Search bar** on the**Microsoft Update Catalog** page and hit the**Search** button.  
![Search For Update On Microsoft Update Catalog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/search-on-microsoft-update-catalog.jpg)
3. The matching updates will show up on the results page. Check the update that applies to your Windows PC—whether it is for Windows 10 or 11, and whether it is for an ARM64-based system or an x64-based system.  
![Microsoft Update Catalog Search Results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/microsoft-update-catalog-search-results.jpg)
4. To know the build of your PC, search for**About** in**Windows Search** and click on**About your PC** under**Best match** . In the**About** page, under**Device specifications** , check your**System type** to know whether it is x64-based or another.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918698/19272" target="_top" id="1918698">
  <img src="//a.impactradius-go.com/display-ad/19272-1918698" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918698/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Device Specifications in About Your PC Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/screenshot-10065.jpg)  
 Select the update that matches your system in Microsoft Update Catalog and click the**Download** button.
5. The**Download** page will open with the file download link. Click on the link to download the update.  
![Download Update From Microsoft Update Catalog Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/download-update-from-link.jpg)
6. Double-click on the downloaded file to open the**Windows Update Standalone Installer** and click**Yes** when prompted to download the update.  
![Windows Update Standalone Installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-standalone-installer.jpg)  
 The update will begin installing and this could take some time.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896510/19272" target="_top" id="1896510">
  <img src="//a.impactradius-go.com/display-ad/19272-1896510" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896510/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Cumulative Update Installation in Progress](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/cumulative-update-installing-progress.jpg)  
 Finally, the**Installation complete** window will appear.  

<!-- affiliate ads begin -->
<span id="1444782">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1444782.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1444782">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1444782.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1444782%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1444782/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Click Restart Now to Complete Installation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restart-now-to-complete-installation.jpg)
7. Just click the**Restart Now** button to complete the installation.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2148619/17108" target="_top" id="2148619">
  <img src="//a.impactradius-go.com/display-ad/17108-2148619" border="0" alt="https://techidaily.com" width="100" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2148619/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. After your PC restarts, go to the**Windows Update history** page.  
![Cumulative Update Successfully Installed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/cumulative-update-successfully-installed.jpg)  
 The update that failed to install would have been successfully installed—as you can see in the screenshot above, the KB5023706 update was installed.

## Stay Updated for a Secure and Smooth Windows Experience

 Update errors like 0x800fo845 can be annoying, especially when you've spent considerable time on an update that fails to install. Try the fixes discussed above to install important updates and enjoy a smooth, secure, and hassle-free Windows experience.

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
<li><a href="https://youtube-tips.techidaily.com/ownload-youtube-icons-quickly-web-os-specific-options-explained-for-2024/"><u>[New] Download YouTube Icons Quickly Web, OS-Specific Options Explained for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-grading-inshot-does-it-reign-supreme/"><u>[Updated] In 2024, Grading InShot Does It Reign Supreme?</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-the-art-of-persuasion-on-facebook-a-beginners-and-expert-playbook-for-2024/"><u>[Updated] The Art of Persuasion on Facebook A Beginner’s & Expert Playbook for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-leading-list-where-to-find-gamers-music-without-costs/"><u>[Updated] The Leading List Where to Find Gamers' Music Without Costs</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-oneplus-11-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on OnePlus 11 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-conflicts-for-print-job-success/"><u>Eradicating Conflicts for Print Job Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/four-steps-for-pausing-windows-update/"><u>Four Steps for Pausing Windows Update</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-your-epson-wf-2630-driver-for-a-smooth-printing-experience-on-win7win81win10/"><u>Get Your Epson WF 2630 Driver for a Smooth Printing Experience on Win7/Win8.1/Win10</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-can-i-recover-corrupted-excel-file-2013-stellar-by-stellar-guide/"><u>How Can I Recover Corrupted Excel File 2013 | Stellar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-the-windows-safe-mode-limitation-on-office-suite/"><u>Resolving the Windows-Safe Mode Limitation on Office Suite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simple-techniques-transform-mkv-videos-into-windows-mp4-files/"><u>Simple Techniques: Transform MKV Videos Into Windows MP4 Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-security-with-new-passwords-in-win-11/"><u>Streamline Security with New Passwords in Win 11</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/tropico-n-game-review-governing-a-paradise-in-chaos/"><u>Tropico N Game Review: Governing a Paradise in Chaos</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-oneplus-11-5g-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My OnePlus 11 5G Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-valorant-on-pc-overcoming-frames-drops/"><u>Winning Valorant on PC: Overcoming Frames Drops</u></a></li>
</ul></div>

