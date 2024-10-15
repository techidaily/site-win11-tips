---
title: Mastering the Art of Using Compressed Windows Archive (CAB) Files
date: 2024-10-11T01:07:20.003Z
updated: 2024-10-15T08:25:19.166Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135366/19272" target="_top" id="2135366">
  <img src="//a.impactradius-go.com/display-ad/19272-2135366" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

 Once the installation is complete, [restart your computer](https://www.makeuseof.com/windows-restart-methods/) to see the changes.

 If you want to install a CAB file using Windows PowerShell, follow these instructions:

1. Open the Start Menu, type **Windows PowerShell**, and choose **Run as administrator** from the right pane.
2. Type the following command and press Enter. Make sure to replace "**CAB location**" with the copied path.  
`Add-WindowsPackage -Online -PackagePath "CAB location"  
`  
![Powershell window with command to install a CAB file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/powershell-window.jpg)

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
<a href="https://aligracehair.sjv.io/c/5597632/1915825/19272" target="_top" id="1915825">
  <img src="//a.impactradius-go.com/display-ad/19272-1915825" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915825/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Browse my computer for drivers in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/browse-my-computer-for-drivers.jpg)
7. Click **Browse** and navigate to the location where you have extracted the CAB file.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006960/19272" target="_top" id="2006960">
  <img src="//a.impactradius-go.com/display-ad/19272-2006960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006960/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Select the folder that contains the extracted file and click **OK**.  
![OK option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/ok-option.jpg)
9. Click **Next**.  

![Next option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/next-option.jpg)

 The Device Manager will now install the driver update on your computer.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047346/19272" target="_top" id="2047346">
  <img src="//a.impactradius-go.com/display-ad/19272-2047346" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047346/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## CAB Files: Everything You Need to Know

 You may sometimes come across a CAB file and wonder what it is and how to install it. After reading the above explanation, hopefully, you now have a basic understanding of CAB files. You now also know how to install driver updates that are in the form of CAB files.

 But what exactly is a Windows CAB file, and how do you install it on your computer? Here's everything you need to know.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-affordable-hardware-excellent-obs-setup-for-2024/"><u>[New] Affordable Hardware Excellent OBS Setup for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-best-matches-ultimate-websites-for-acquiring-snapchat-ringtones/"><u>[New] Best Matches Ultimate Websites for Acquiring Snapchat Ringtones</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-androids-latest-advancements-for-immersive-video-viewing/"><u>[Updated] 2024 Approved Android's Latest Advancements for Immersive Video Viewing</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-techniques-in-archiving-web-based-music-tracks/"><u>[Updated] 2024 Approved Techniques in Archiving Web-Based Music Tracks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-xbox-gaming-avoid-drive-selection-stress/"><u>Effortless Xbox Gaming: Avoid Drive Selection Stress</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elusive-disappearance-of-taskbars-control-in-win-11/"><u>Elusive Disappearance of TaskBar's Control in Win 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-vivo-y27-5g-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Vivo Y27 5G? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-from-infinix-note-30-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock from Infinix Note 30 Devices</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-nokia-c210-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Nokia C210 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-typing-mastery-through-typingaid/"><u>Rapid Typing Mastery Through TypingAid</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovering-deleted-execution-records-on-windows/"><u>Recovering Deleted Execution Records on Windows</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolved-overcoming-stuck-issues-during-dota-2-game-startup/"><u>Resolved: Overcoming 'Stuck' Issues During Dota 2 Game Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-start-csgo-in-windows-11-successfully/"><u>Strategies to Start CS:GO in Windows 11 Successfully</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-settings-through-alomware-applications/"><u>Transforming Windows Settings Through AlomWare Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-the-msvcr110dll-missing-error-and-how-do-you-fix-it/"><u>What Is the Msvcr110.dll Missing Error and How Do You Fix It?</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>Will Pokémon Go Ban the Account if You Use PGSharp On Realme GT Neo 5 SE | Dr.fone</u></a></li>
</ul></div>

