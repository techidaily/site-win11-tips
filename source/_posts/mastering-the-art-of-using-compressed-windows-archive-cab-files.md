---
title: Mastering the Art of Using Compressed Windows Archive (CAB) Files
date: 2024-10-02T02:33:43.985Z
updated: 2024-10-09T01:47:59.389Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Art of Using Compressed Windows Archive (CAB) Files
excerpt: This Article Describes Mastering the Art of Using Compressed Windows Archive (CAB) Files
keywords: CAB File Mastery,Archiving Wiz,CAB Extraction Guide,Cabfile Techniques,Zip64 Solutions,Compression Best Practices,Windows Archive Skills
thumbnail: https://thmb.techidaily.com/d70a53087560a098bb105b6da250ee7a060b663d95025554525e6d2ddaef6a7e.jpg
---

## Mastering the Art of Using Compressed Windows Archive (CAB) Files

 There are many ways to download driver and Windows updates, one of which is by visiting the Microsoft Update Catalog. The files downloaded from the Microsoft Update Catalog have a .CAB extension. Microsoft uses these files because they use lossless compression, which means that the original files remain unchanged when they are compressed.

 But what exactly is a Windows CAB file, and how do you install it on your computer? Here's everything you need to know.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is a Windows CAB File?

 A CAB file or Cabinet file is a common archive file format used by Microsoft. It contains the compressed version of different files, folders, and even other cabinet files. Microsoft uses these files to distribute Windows, drivers, and UWP app updates. However, you can also use it to store other forms of data, such as images, videos, and documents.

 A CAB file is compressed using the Microsoft Cabinets Compression Format (MCF), which ensures that you can easily decompress it without losing the data stored in it. It can also be signed with digital certificates, allowing to maintain the authenticity and integrity of the file.

 CAB files are recognized by their first four bytes, which are the [ASCII characters](https://www.makeuseof.com/what-is-ascii-text/) MSCF. You can store up to 65,535 folders in a CAB file, with each folder having a storage capacity of 65,535 files.

 Now that you have a brief understanding of CAB files, let's check out how you can install it on Windows 11\.

## How to Install a CAB File on Windows 11

 You can easily install a CAB file on Windows 11 using Command Prompt and Windows PowerShell. In the Command Prompt method, you'll have to use the [DISM command](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/). Whereas, in the PowerShell method, you'll use the Add-WindowsPackage command.

 Here's how to install a CAB file using Command Prompt.

1. Navigate to the CAB file location on your computer.
2. Right-click the CAB file, and choose **Copy as path**.  
![Copy as path option in context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/copy-as-path-option.jpg)
3. Press **Win** key to open the **Start Menu**, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane.
4. In the elevated Command Prompt window, type the following command and press Enter. Make sure to replace "**CAB location**" with the copied path.  
`dism /Online /Add-Package /PackagePath:"CAB location"`  
![CMD window with command to install a CAB file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cmd-window.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151859/7443" target="_top" id="2151859">
  <img src="//a.impactradius-go.com/display-ad/7443-2151859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151859/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once the installation is complete, [restart your computer](https://www.makeuseof.com/windows-restart-methods/) to see the changes.

 If you want to install a CAB file using Windows PowerShell, follow these instructions:

1. Open the Start Menu, type **Windows PowerShell**, and choose **Run as administrator** from the right pane.
2. Type the following command and press Enter. Make sure to replace "**CAB location**" with the copied path.  
`Add-WindowsPackage -Online -PackagePath "CAB location"  
`  
![Powershell window with command to install a CAB file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/powershell-window.jpg)

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098700/14409" target="_top" id="2098700">
  <img src="//a.impactradius-go.com/display-ad/14409-2098700" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098700/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 That's it. PowerShell will install the content of the CAB file on your computer.

## How to Install Driver Updates From a CAB File

 If you have downloaded a driver update, which is a CAB file, you can install it using the following instructions:

1. Double-click the CAB file to view its contents.
2. Press **Ctrl + A** to select all the files, right-click, and choose **Extract**.  
![Extract option in context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/extract-option.jpg)
3. Choose the location where you want to extract the contents of the CAB file and click **Extract**.
4. Press **Win + X** hotkey to open the Power User menu and choose **Device Manager**.
5. Right-click the device for which you have downloaded the driver update and choose **Update driver**.  
![Update driver option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/update-driver.jpg)
6. Click **Browse my computer for drivers**.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526">
  <img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Browse my computer for drivers in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/browse-my-computer-for-drivers.jpg)
7. Click **Browse** and navigate to the location where you have extracted the CAB file.
8. Select the folder that contains the extracted file and click **OK**.  
![OK option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/ok-option.jpg)
9. Click **Next**.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918719/19272" target="_top" id="1918719">
  <img src="//a.impactradius-go.com/display-ad/19272-1918719" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918719/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Next option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/next-option.jpg)

 The Device Manager will now install the driver update on your computer.

## CAB Files: Everything You Need to Know

 You may sometimes come across a CAB file and wonder what it is and how to install it. After reading the above explanation, hopefully, you now have a basic understanding of CAB files. You now also know how to install driver updates that are in the form of CAB files.

 But what exactly is a Windows CAB file, and how do you install it on your computer? Here's everything you need to know.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/updated-capture-your-best-side-tips-for-effective-talking-head-shots-for-2024/"><u>[Updated] Capture Your Best Side Tips for Effective Talking-Head Shots for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-comprehensive-step-by-step-on-zooms-video-broadcasting-for-2024/"><u>[Updated] Comprehensive Step-by-Step on Zoom's Video Broadcasting for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-iphone-tips-free-techniques-to-incorporate-music-in-video-projects/"><u>2024 Approved IPhone Tips Free Techniques to Incorporate Music in Video Projects</u></a></li>
<li><a href="https://fox-that.techidaily.com/diagnosing-and-fixing-persistent-camera-zoom-issues-on-whatsapp/"><u>Diagnosing and Fixing Persistent Camera Zoom Issues on WhatsApp</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empowering-your-windows-mastery-of-lav-filters-application/"><u>Empowering Your Windows: Mastery of LAV Filters Application</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-keep-screen-distractions-at-bay-folders/"><u>How to Keep Screen Distractions at Bay: Folders</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-realme-gt-3-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Realme GT 3 to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-stop-and-start-strategies-fb-livestream-recovery-methods/"><u>In 2024, Stop and Start Strategies FB Livestream Recovery Methods</u></a></li>
<li><a href="https://video-capture.techidaily.com/navigating-the-basics-of-multi-os-skype-chatting/"><u>Navigating the Basics of Multi-OS Skype Chatting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-chrome-profile-woes-on-windows-pcs/"><u>Overcoming Chrome Profile Woes on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-routing-failed-files-download-on-windows-11-and-11-pcs/"><u>Re-Routing Failed Files Download on Windows 11 & 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-stubborn-windows-exe-non-opener/"><u>Resolving Stubborn Windows EXE Non-Opener</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-7-web-based-resources-enhancing-your-ability-in-crafting-effective-prompts/"><u>Top 7 Web-Based Resources Enhancing Your Ability in Crafting Effective Prompts</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/forming-youtube-sounds-into-high-quality-wav-files/"><u>Transforming YouTube Sounds Into High-Quality WAV Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-diverse-nvidia-driver-options-gaming-studio/"><u>Understanding Diverse Nvidia Driver Options: Gaming, Studio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-your-sound-potential-in-windows-11/"><u>Unlock Your Sound Potential in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/usb-wi-fi-woes-heres-a-quick-guide-to-reclaiming-connection-on-windows/"><u>USB Wi-Fi Woes? Here's a Quick Guide to Reclaiming Connection on Windows</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    