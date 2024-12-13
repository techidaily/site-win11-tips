---
title: Steps to Address Windows Update Hiccup X712
date: 2024-12-10T00:00:11.292Z
updated: 2024-12-12T23:48:30.537Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Address Windows Update Hiccup X712
excerpt: This Article Describes Steps to Address Windows Update Hiccup X712
keywords: Fixing X712 Updates,Resolve X712 Errors,Windows Update Issue X712,Address Windows Hiccups X712,Solving Windows X712 Problems,Overcoming X712 Update Issues,XP712 Fix Steps
thumbnail: https://thmb.techidaily.com/8ac81d16fe79fad30026aca67e023b34a8f1d9b49b75551b82236c5ce76daa3d
---

## Steps to Address Windows Update Hiccup X712

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

## 2\. Perform a Complete system shutdown

 Windows OS enables the fast startup option by default. Even if you restart your system, or shut it down, it preserves the system state using hibernate. So, you need to perform a complete system shutdown and then power it back on to close and restart all background services.

Here’s how to perform a complete system shutdown:

1. Press**Win + X** to launch the Power user menu. Scroll down and select the**Terminal (Admin)** option from the list.
2. The Terminal app will open with an instance of a command prompt with admin privileges.
3. Type the**shutdown /s /f /t 0** command and press the**enter** key.
4. Your system will power off. It will take a tad bit longer that a normal shutdown procedure.
5. Now, restart your Windows PC and try to install the Windows update.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Restart Windows Update services

 Windows Update uses a bunch of background services to fetch and download updates. If these services aren’t running automatically, you will encounter an error. These include**Windows Update Service** ,**Windows Installer Service** ,**Cryptographic Services** , and**Background Intelligent Transfer Service** .

Repeat the following steps to start the necessary services:

1. Press**Win + R** to[launch the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**services.msc** and press the**enter** key
2. Services utility will launch on your system. Now locate the**Background Intelligent Transfer** service in the list.
3. Double-click on the BITS service to open the**properties** window. Set the**Startup Type** as**Automatic** and click on the**Apply** button.  
![Disabling Windows Update Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disabling-windows-update-services.jpg)
4. Click on the**OK** button and close the Properties windows. Now, right-click on the service and select the**Start** option from the context menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 ren C:\\Windows\\SoftwareDistribution SoftwareDistribution.old ren C:\\Windows\\System32\\catroot2 Catroot2.old  
![Rename the SoftwareDistribution Folder 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder-2.jpg)
4. Both the above commands rename the**SoftwareDistribution** folder and**Catroot2** folder.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## 7\. Manually Download Windows Updates

 If you are unable to download a specific Windows update using the Settings page, consider a direct download and install approach. Visit the Microsoft Update Catalog website and search for the KB update you want to download. However, you first have to check the corresponding update number which is failing to download and install on your system.

![Manually Download Windows Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/manually-download-windows-updates.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-record-videos.techidaily.com/updated-distinguishing-between-youtube-content-control-and-creative-commons-flexibility-for-2024/"><u>[Updated] Distinguishing Between YouTube Content Control and Creative Commons Flexibility for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-from-concrete-jungles-to-eco-havens-rethinking-urban-living/"><u>[Updated] In 2024, From Concrete Jungles to Eco Havens Rethinking Urban Living</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-mastering-pip-google-chrome-across-devices/"><u>[Updated] Mastering PIP Google Chrome Across Devices</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-oneplus-open-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from OnePlus Open to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-tailored-lock-patterns-for-windows-11-devices/"><u>Creating Tailored Lock Patterns for Windows 11 Devices</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/expert-moves-for-sharing-youtube-and-twitter-on-whatsapp-platform-for-2024/"><u>Expert Moves for Sharing YouTube and Twitter on WhatsApp Platform for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harmonizing-chromes-time-with-system-settings-windows/"><u>Harmonizing Chrome's Time with System Settings (Windows)</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-seamless-navigation-to-your-individual-playlist-library-on-youtube/"><u>In 2024, Seamless Navigation to Your Individual Playlist Library on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-edge-deletion-in-win11/"><u>Mastering Edge Deletion in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-mandatory-requirements-issue-in-windows-1111/"><u>Quick Fix for Mandatory Requirements Issue in Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-disabled-windows-11-mobile-hotspot-connection/"><u>Solutions for Disabled Windows 11 Mobile Hotspot Connection</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/strategic-showdowns-unleashed-exploring-7-best-games/"><u>Strategic Showdowns Unleashed Exploring 7 Best Games</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/streamline-your-videos-acoustic-appeal-on-youtube/"><u>Streamline Your Video's Acoustic Appeal on YouTube</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-vivo-s18-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Vivo S18? Here is How | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-boot-management-101-complete-configuration-guide/"><u>Windows Boot Management 101: Complete Configuration Guide</u></a></li>
</ul></div>

