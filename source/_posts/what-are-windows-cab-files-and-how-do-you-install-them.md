---
title: What Are Windows CAB Files and How Do You Install Them?
date: 2024-06-25T16:36:13.811Z
updated: 2024-06-26T16:36:13.811Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes What Are Windows CAB Files and How Do You Install Them?
excerpt: This Article Describes What Are Windows CAB Files and How Do You Install Them?
keywords: WinCAB Files Basics,Installing CAB on WIN,CAB File Usage Guide,Windows Software Installation,How to Install CAB Files,Understanding CAB Archives,CAB File Format in Windows
thumbnail: https://thmb.techidaily.com/0c231e30e1cde65144bf91e6e96a309bb581e79a51b0603eaf2331d2401d5ca6.jpg
---

## What Are Windows CAB Files and How Do You Install Them?

 There are many ways to download driver and Windows updates, one of which is by visiting the Microsoft Update Catalog. The files downloaded from the Microsoft Update Catalog have a .CAB extension. Microsoft uses these files because they use lossless compression, which means that the original files remain unchanged when they are compressed.

 But what exactly is a Windows CAB file, and how do you install it on your computer? Here's everything you need to know.

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
![Browse my computer for drivers in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/browse-my-computer-for-drivers.jpg)
7. Click **Browse** and navigate to the location where you have extracted the CAB file.
8. Select the folder that contains the extracted file and click **OK**.  
![OK option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/ok-option.jpg)
9. Click **Next**.  
![Next option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/next-option.jpg)

 The Device Manager will now install the driver update on your computer.

## CAB Files: Everything You Need to Know

 You may sometimes come across a CAB file and wonder what it is and how to install it. After reading the above explanation, hopefully, you now have a basic understanding of CAB files. You now also know how to install driver updates that are in the form of CAB files.

 But what exactly is a Windows CAB file, and how do you install it on your computer? Here's everything you need to know.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/mastering-file-syncing-on-windows-the-most-rated-apps/"><u>Mastering File Syncing on Windows: The Most Rated Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-download-and-install-msixbundle-and-appxappxbundle-files-from-the-microsoft-store/"><u>How to Download and Install Msixbundle and Appx/Appxbundle Files From the Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-windowtop-calculator-stays-on-top/"><u>Ensuring Windowtop Calculator Stays on Top</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-login-error-compatibility-issue-with-scanner/"><u>Overcoming Windows Login Error: Compatibility Issue with Scanner</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unreachable-issues-fixing-mb-service-disconnect-in-windows-11/"><u>Overcoming Unreachable Issues: Fixing MB Service Disconnect in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-system-performance-by-adding-disk-space-analyzer-tool/"><u>Streamline System Performance by Adding Disk Space Analyzer Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-keep-lol-playtime-uninterrupted-in-windows/"><u>Strategies to Keep LoL Playtime Uninterrupted in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-your-system-advanced-techniques-to-revise-the-windows-registry-in-command-prompt/"><u>Unlock Your System: Advanced Techniques to Revise the Windows Registry in Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-fix-geforce-experience-on-windows-pcs/"><u>Quick Guide to Fix GeForce Experience on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-files-directories-for-game-access/"><u>Winning at Files: Directories for Game Access</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-any-realme-gt-3-phone-password-using-emergency-call-by-drfone-android/"><u>How To Unlock Any Realme GT 3 Phone Password Using Emergency Call</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-realme-c53-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Realme C53 | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-oppo-find-n3-flip-pin-codepattern-lockpassword-by-drfone-android/"><u>In 2024, How to Unlock Oppo Find N3 Flip PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-htc-vives-diving-into-depth-a-vr-experience-review/"><u>In 2024, HTC Vive's Diving Into Depth  A VR Experience Review</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-lava-blaze-2-5g-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Lava Blaze 2 5G Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-crafting-link-driven-success-a-backlink-blueprint-for-channels-for-2024/"><u>[Updated] Crafting Link-Driven Success  A Backlink Blueprint for Channels for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-samsung-galaxy-m34-5g-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-excellent-screen-grabber-aid-for-youtube-content-creators/"><u>In 2024, Excellent Screen Grabber Aid for YouTube Content Creators</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-honor-x9a-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Honor X9a | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/top-12-self-contained-screen-recording-tools-for-2024/"><u>Top 12 Self-Contained Screen Recording Tools for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>