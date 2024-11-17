---
title: Three Techniques to Delete Windows 11 Store
date: 2024-11-10T19:34:02.587Z
updated: 2024-11-17T19:44:16.853Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Three Techniques to Delete Windows 11 Store
excerpt: This Article Describes Three Techniques to Delete Windows 11 Store
keywords: W11 Store Uninstall Guide,Remove Windows Apps,Disable Microsoft Store,Deleting Windows Updates,Unlink Microsoft Services,Wipe Windows 11 Apps,Clear Microsoft Shop
thumbnail: https://thmb.techidaily.com/6395a405feac0920efaceeee04a9b0803cb7c1fce78f830a62381ffd05e1b2e3.jpg
---

## Three Techniques to Delete Windows 11 Store

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094414/7443" target="_top" id="2094414">
  <img src="//a.impactradius-go.com/display-ad/7443-2094414" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094414/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

### 1\. Using Winget

 Winget is a handy Windows package manager tool available with the newer releases of Windows 10 and 11\. It makes it ridiculously easy to search and manage applications on your system. You can use it to remove any application, even the Microsoft Store app from your system. Here’s how:

1. Press the**Win + R** key to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press the**Ctrl + Shift + Enter** keys to launch the Command Prompt with administrator privileges.
2. Now, we need to locate the ID of the Microsoft Store app installed on the system. Type the following command in the command prompt window and press the enter key:**Winget list Store**
3. Winget will list all the installed programs on your system containing the string “store” in their name. Find the Microsoft Store app in the list and**copy** its**ID** .
4. After that, you need to run the uninstall command using winget. The syntax is**winget uninstall \[app ID\]** . So, the command will be:  
winget uninstall Microsoft.WindowsStore_8wekyb3d8bb
5. Press enter to execute the command and wait for it to execute successfully.  
![Uninstall Microsoft Store App using winget](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-winget.jpg)
6. Type**exit** in the command prompt window and press enter to close it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902309/19272" target="_top" id="1902309">
  <img src="//a.impactradius-go.com/display-ad/19272-1902309" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902309/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to[remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
4. Click on the**Save** button. Close the Notepad window.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016143/19272" target="_top" id="2016143">
  <img src="//a.impactradius-go.com/display-ad/19272-2016143" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016143/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123731/7443" target="_top" id="2123731">
  <img src="//a.impactradius-go.com/display-ad/7443-2123731" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123731/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Easily Remove the Microsoft Store From Windows

 Windows 10 and 11 don’t offer an option to uninstall Microsoft Store. So, you are only left at the mercy of a system restore or reset. However, you can now uninstall the Microsoft Store app from your system using any of the three methods mentioned above. You can also reinstall it using the PowerShell cmdlet and continue using the app again.

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
<li><a href="https://youtube-data.techidaily.com/n-2024-rapid-rendering-of-epic-battle-royale-tiles/"><u>[New] In 2024, Rapid Rendering of Epic Battle Royale Tiles</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-guide-to-podcast-cover-design-10-core-insights-for-2024/"><u>[Updated] Guide to Podcast Cover Design 10 Core Insights for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-guide-repairing-windows-error-0x80040610-in-outlook/"><u>Comprehensive Guide: Repairing Windows Error 0X80040610 in Outlook</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-nokia-c22-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Nokia C22 | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-your-sennheiser-gamers-mic-a-comprehensive-troubleshooting-tutorial/"><u>Fixing Your Sennheiser Gamer's Mic: A Comprehensive Troubleshooting Tutorial</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-in-depth-skype-audio-capture-guide-with-obs-software/"><u>In 2024, In-Depth Skype Audio Capture Guide with OBS Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-unconnect-error-for-windows-nvidia-applications/"><u>Removing Unconnect Error for Windows' Nvidia Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shed-light-on-dark-windows-11-desktops-tips-inside/"><u>Shed Light on Dark Windows 11 Desktops - Tips Inside!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-amd-graphics-drivers-update-for-windows-11-pcs/"><u>Step-by-Step AMD Graphics Drivers Update for Windows 11 PCs</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-data-from-sony-xperia-5-v-by-fonelab-android-recover-data/"><u>The way to get back lost data from Sony Xperia 5 V</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-best-windows-photo-organizers-listed-here/"><u>Unveiling the Best Windows Photo Organizers Listed Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-ancient-pcs-for-modern-operations-using-windows-to-go-and-rufus/"><u>Upgrading Ancient PCs for Modern Operations: Using Windows To Go and Rufus</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-harmony-essential-soundtracks-for-popular-video-shorts/"><u>Viral Harmony Essential Soundtracks For Popular Video Shorts</u></a></li>
</ul></div>

