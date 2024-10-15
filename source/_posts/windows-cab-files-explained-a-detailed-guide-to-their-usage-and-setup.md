---
title: "Windows Cab Files Explained: A Detailed Guide to Their Usage & Setup"
date: 2024-10-13T05:22:47.900Z
updated: 2024-10-14T17:14:26.798Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Cab Files Explained: A Detailed Guide to Their Usage & Setup"
excerpt: "This Article Describes Windows Cab Files Explained: A Detailed Guide to Their Usage & Setup"
keywords: Windows CAB Files Guide,File Setup in Windows,CAB Format Usage,Windows File Explanation,Cabinet File Info,Windows Data Compression,Installing CAB Files
thumbnail: https://thmb.techidaily.com/d208efb0315dc3e80b4d5a8f4b751d30ee62ca28dd2151c249d15e615be6f528.jpg
---

## Windows Cab Files Explained: A Detailed Guide to Their Usage & Setup

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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528685/16446" target="_top" id="1528685">
  <img src="//a.impactradius-go.com/display-ad/16446-1528685" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528685/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Press **Win + X** hotkey to open the Power User menu and choose **Device Manager**.
5. Right-click the device for which you have downloaded the driver update and choose **Update driver**.  
![Update driver option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/update-driver.jpg)
6. Click **Browse my computer for drivers**.  
![Browse my computer for drivers in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/browse-my-computer-for-drivers.jpg)
7. Click **Browse** and navigate to the location where you have extracted the CAB file.
8. Select the folder that contains the extracted file and click **OK**.  
![OK option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/ok-option.jpg)
9. Click **Next**.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2044585/7443" target="_top" id="2044585">
  <img src="//a.impactradius-go.com/display-ad/7443-2044585" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044585/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Next option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/next-option.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/857869/11832" target="_top" id="857869">
  <img src="//a.impactradius-go.com/display-ad/11832-857869" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/857869/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Device Manager will now install the driver update on your computer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144297/7443" target="_top" id="2144297">
  <img src="//a.impactradius-go.com/display-ad/7443-2144297" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144297/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## CAB Files: Everything You Need to Know

 You may sometimes come across a CAB file and wonder what it is and how to install it. After reading the above explanation, hopefully, you now have a basic understanding of CAB files. You now also know how to install driver updates that are in the form of CAB files.

 But what exactly is a Windows CAB file, and how do you install it on your computer? Here's everything you need to know.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-unlock-10-passport-images-at-no-cost-desktopweb/"><u>[New] In 2024, Unlock 10 Passport Images at No Cost – Desktop/Web</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-top-5-best-fluid-simulation-games-for-you/"><u>[Updated] 2024 Approved Top 5 Best Fluid Simulation Games for You</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-oppo-find-x7-ultra-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Oppo Find X7 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choose-freedom-for-windows-chatai-freedomgpt/"><u>Choose Freedom for Windows ChatAI: FreedomGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-narrative-voice-with-windows-11-tools/"><u>Crafting Narrative Voice with Windows 11 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciding-the-best-drive-for-your-xbox-games/"><u>Deciding the Best Drive for Your Xbox Games</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-windows-n-series-pros-and-cons/"><u>Deciphering Windows N Series: Pros & Cons</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/demystifying-the-workings-of-gptzero-in-ai-authenticity/"><u>Demystifying the Workings of GPTZero in AI Authenticity</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-hidefake-snapchat-location-on-your-realme-11x-5g-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Realme 11X 5G | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/installing-canon-ip25-printer-drivers-on-windows-10-8-and-seven-versions/"><u>Installing Canon iP25 Printer Drivers on Windows 10, 8 and Seven Versions</u></a></li>
<li><a href="https://win-answers.techidaily.com/mastering-apex-legends-effective-strategies-to-correct-error-code-leaf/"><u>Mastering Apex Legends: Effective Strategies to Correct Error Code Leaf</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-windows-11-taskbar-for-optimal-datetime-view/"><u>Tailoring Windows 11 Taskbar for Optimal Date/Time View</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    