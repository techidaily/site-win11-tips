---
title: "Overcoming Update Problem: ZeroError 80073712"
date: 2024-10-31T17:26:58.749Z
updated: 2024-11-01T18:19:06.151Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overcoming Update Problem: ZeroError 80073712"
excerpt: "This Article Describes Overcoming Update Problem: ZeroError 80073712"
keywords: Fix Update Error 80073712,Solve Windows Update Failure,Unlock Windows Updates,Stop ZeroError Update Issue,Resolve Update Crash 80073712,Bypass Update Error 73712,Overcome Update Failures
thumbnail: https://thmb.techidaily.com/d6f225de23330f252c6d5195ffc58e836dfeb5e08b530725208b4f5fec9ae8dd.JPG
---

## Overcoming Update Problem: ZeroError 80073712

 Microsoft frequently releases updates to fix security issues, and introduce new features and stability to the Windows OS. But not all updates install smoothly on your system and trigger an error code while doing so. Many users share their woes with the 0x80073712 update error code with the error message that some files are missing from the system.

 If you experience the same update error code and are unable to install the latest Windows update, don’t worry. We will list out all the possible fixes that you can try to resolve the 0x80073712 error code.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Use the Windows Troubleshooter

 Before jumping onto major fixes, leverage the in-built troubleshooter on Windows 10 and 11\. It tries to find out existing problems with Windows Update and try to fix them. Repeat the following steps:

1. Press**Win + I** to launch the settings app.
2. Navigate to the**System > Troubleshoot** section.
3. Click on the**Other Troubleshooter** option.
4. Locate the**Windows Update troubleshooter** option from the list.
5. Then, click on the**Run** button to start the troubleshooter.  
![Windows Update Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-update-troubleshooter.jpg)
6. Wait for the Windows Update troubleshooter to identify problems. Click on the**Next** button.
7. Close the troubleshooter window and reattempt the Windows update installation.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135368/19272" target="_top" id="2135368">
  <img src="//a.impactradius-go.com/display-ad/19272-2135368" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135368/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Perform a Complete system shutdown

 Windows OS enables the fast startup option by default. Even if you restart your system, or shut it down, it preserves the system state using hibernate. So, you need to perform a complete system shutdown and then power it back on to close and restart all background services.

Here’s how to perform a complete system shutdown:

1. Press**Win + X** to launch the Power user menu. Scroll down and select the**Terminal (Admin)** option from the list.
2. The Terminal app will open with an instance of a command prompt with admin privileges.
3. Type the**shutdown /s /f /t 0** command and press the**enter** key.
4. Your system will power off. It will take a tad bit longer that a normal shutdown procedure.
5. Now, restart your Windows PC and try to install the Windows update.

## 3\. Restart Windows Update services

 Windows Update uses a bunch of background services to fetch and download updates. If these services aren’t running automatically, you will encounter an error. These include**Windows Update Service** ,**Windows Installer Service** ,**Cryptographic Services** , and**Background Intelligent Transfer Service** .

Repeat the following steps to start the necessary services:

1. Press**Win + R** to[launch the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**services.msc** and press the**enter** key
2. Services utility will launch on your system. Now locate the**Background Intelligent Transfer** service in the list.
3. Double-click on the BITS service to open the**properties** window. Set the**Startup Type** as**Automatic** and click on the**Apply** button.  
![Disabling Windows Update Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disabling-windows-update-services.jpg)
4. Click on the**OK** button and close the Properties windows. Now, right-click on the service and select the**Start** option from the context menu.
5. Similarly, set all the services as automatic and manually start them.
6. **Close** the Services window and reattempt the Windows update.

## 4\. Run the Disk Cleanup Tool

 Disk Cleanup can wipe the delivery optimization files, old Windows update files as well as the Temp folder. If files in these locations are corrupted, they can interfere with the normal update process. Here’s how to run disk cleanup on Windows:

1. Press**Win + S** to open the search utility in Windows.
2. Type**cleanmgr.exe** and press the enter key to open the Disk Cleanup tool.
3. It will select the system drive (C) by default. Click on the**OK** button to continue.
4. Select the checkboxes of files that you want the tool to clean up. Then, click on the**Clean up system files** button.  
![Disk Cleanup App in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disk-cleanup-app-in-windows-11.jpg)
5. Disk Cleanup will close and redirect you to pick the appropriate drive. Click on the**OK** button.
6. Lastly, click on the**Delete files** button.

## 5\. Rename the SoftwareDistribution Folder

 Windows update stores its content in the SoftwareDistribution folder. Since it is located inside the Windows folder in the C drive, you mustn’t delete it. Instead, you can rename the folder to force the update service to recreate the folder again.

Repeat the following steps:

1. Open the Start menu and search CMD. Press Ctrl + Shift + Enter to open the command prompt with admin privileges.
2. Type the following commands to stop all the Windows update-related services:  
 net stop wuauserv net stop cryptSvc net stop bits net stop msiserver  
![Rename the SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder.jpg)
3. Once these services stop running, type**cls** in the command prompt windows. Then enter the following commands:  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134497/18498" target="_top" id="2134497">
  <img src="//a.impactradius-go.com/display-ad/18498-2134497" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134497/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 ren C:\\Windows\\SoftwareDistribution SoftwareDistribution.old ren C:\\Windows\\System32\\catroot2 Catroot2.old  
![Rename the SoftwareDistribution Folder 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder-2.jpg)
4. Both the above commands rename the**SoftwareDistribution** folder and**Catroot2** folder.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134228/18498" target="_top" id="2134228">
  <img src="//a.impactradius-go.com/display-ad/18498-2134228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134228/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Now, you need to restart all the Windows services you stopped in step 3\. Enter the following commands:  
net start wuauserv net start cryptSvc net start bits net start msiserver  
![Rename the SoftwareDistribution Folder 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder-3.jpg)
6. Lastly,**restart** your system and visit the following folder location:**C:\\Windows** . You will notice that there is a new SoftwareDistribution folder in that location.
7. Open the Windows update in Settings and try to download and install updates.

## 6\. Delete the Pending.xml file

 The pending.xml file contains all the pending Windows update tasks. Oftentimes, it can interfere with installing new updates because there are already multiple incomplete old update tasks. So, you must delete this file and proceed with the Windows update.

Retrace the following steps to delete the pending.xml file:

1. Log in with an administrator account. Then, press**Win + E** to launch the file explorer.
2. Navigate to the**C:\\Windows\\WinSxS** folder.
3. Locate the**pending.xml** in the**WinSxS** folder and right-click on it.
4. Press the**Shift** key and click on the**Delete** option.
5. Restart your computer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132162/7443" target="_top" id="2132162">
  <img src="//a.impactradius-go.com/display-ad/7443-2132162" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132162/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Manually Download Windows Updates

 If you are unable to download a specific Windows update using the Settings page, consider a direct download and install approach. Visit the Microsoft Update Catalog website and search for the KB update you want to download. However, you first have to check the corresponding update number which is failing to download and install on your system.

![Manually Download Windows Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/manually-download-windows-updates.jpg)

<!-- affiliate ads begin -->
<span id="1976998">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1976998.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1976998">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1976998.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1976998%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1976998/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Reset Windows

 Resetting Windows is the last resort you have if none of the above methods work in your favor. However, before learning[how to perform a Windows system reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) , try out general fixes such as[SFC, CHKDSK, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) scans on your system. Also,[disable Windows Defender](https://www.makeuseof.com/how-to-turn-off-windows-defender/) and try updating your system before hitting the reset button.

## Update Windows Without Hiccups

 Windows updates can be tricky to install sometimes. Use the inbuilt troubleshooter to identify and fix problems. After that restart, all the crucial Windows update services and run the Disk Cleanup tool. If everything else fails, try doing a manual update or performing a Windows Reset.

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
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-explore-the-journey-creating-a-one-of-a-kind-tiktok-hash/"><u>[New] 2024 Approved Explore the Journey Creating a One-of-a-Kind TikTok Hash</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-capturing-pc-gaming-moments-6-innovative-techniques/"><u>[New] Capturing PC Gaming Moments 6 Innovative Techniques</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-inside-look-at-youtubes-creator-studio-interface/"><u>[New] In 2024, Inside Look at YouTube's Creator Studio Interface</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-accolades-across-platforms-for-video-creators/"><u>[Updated] In 2024, Accolades Across Platforms for Video Creators</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-oneplus-ace-3-drfone-by-drfone-virtual-android/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On OnePlus Ace 3? | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/erase-wisely-strategies-using-photoshops-eraser-for-2024/"><u>Erase Wisely Strategies Using Photoshop's Eraser for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-creative-wallpapers-for-each-windows-11-monitor/"><u>Explore Creative Wallpapers for Each Windows 11 Monitor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-handling-breakpoint-error-in-windows/"><u>Mastering the Art of Handling 'Breakpoint Error' In Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/methods-to-fix-desktop-missing-under-cwindowssystem32config/"><u>Methods to Fix 'Desktop Missing' Under C: Windows System32 Config</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-black-and-white-errors-in-microsoft-shop/"><u>Remedy Black and White Errors in Microsoft Shop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-switch-toggle-microsofts-window-integrated-chat-support/"><u>Swift Switch: Toggle Microsoft’s Window-Integrated Chat Support</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-fixers-manual-for-installer-errors-on-win11/"><u>The Ultimate Fixer's Manual for Installer Errors on Win11</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/understanding-and-fixing-windows-blue-screen-error-0x0000001e/"><u>Understanding and Fixing Windows Blue Screen Error 0X0000001E</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-potential-mastering-the-function-fn-key/"><u>Unlocking Potential: Mastering the Function (Fn) Key</u></a></li>
</ul></div>

