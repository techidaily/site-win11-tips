---
title: "Eliminate Microsoft Store: Win11 Edition Guide"
date: 2024-11-14T17:50:02.449Z
updated: 2024-11-17T18:07:01.458Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Eliminate Microsoft Store: Win11 Edition Guide"
excerpt: "This Article Describes Eliminate Microsoft Store: Win11 Edition Guide"
keywords: Eliminate MSStore,Win11 WinRemove,Win11 Guide,FreeOSGuide,BypassMSStores,OSFreedomTips,Win11Portable
thumbnail: https://thmb.techidaily.com/583e140408c2ec351f3efcf4716a6b87c865b3b8a448b26c52bfccdf2d778b7a.png
---

## Eliminate Microsoft Store: Win11 Edition Guide

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
<a href="https://appsumo.8odi.net/c/5597632/2151856/7443" target="_top" id="2151856">
  <img src="//a.impactradius-go.com/display-ad/7443-2151856" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151856/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997657/19272" target="_top" id="1997657">
  <img src="//a.impactradius-go.com/display-ad/19272-1997657" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997657/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://unicoeye.pxf.io/c/5597632/2134490/18498" target="_top" id="2134490">
  <img src="//a.impactradius-go.com/display-ad/18498-2134490" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134490/18498" style="position:absolute;visibility:hidden;" border="0" />
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
5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136624/26400" target="_top" id="2136624">
  <img src="//a.impactradius-go.com/display-ad/26400-2136624" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136624/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://program-issues.techidaily.com/fixed-new-world-keeps-freezing/"><u>[FIXED] New World Keeps Freezing</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-mastering-the-art-of-uploading-and-sharing-videos-on-instagram/"><u>[New] 2024 Approved Mastering the Art of Uploading and Sharing Videos on Instagram</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-top-rated-apps-for-taking-screenshots-in-windows-8-for-2024/"><u>[New] Top-Rated Apps for Taking Screenshots in Windows 8 for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-best-live-video-streaming-software/"><u>[Updated] Best Live Video Streaming Software</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-adding-divisions-to-vimeos-media-shows/"><u>2024 Approved Adding Divisions to Vimeo's Media Shows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-clear-the-microsoft-defender-protection-history-on-windows-10-and-11/"><u>4 Ways to Clear the Microsoft Defender Protection History on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-alternative-protection-strategies-for-missing-bitlocker-in-winoss/"><u>5 Alternative Protection Strategies for Missing Bitlocker in WinOSs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-secrets-the-fastest-ways-to-uncover-windows-11s-credential-manager/"><u>Accessing Secrets: The Fastest Ways to Uncover Windows 11'S Credential Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-digital-dreamland-with-windows-pcs/"><u>Achieving Digital Dreamland with Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-10-and-11s-phishing-protection-settings/"><u>Adjusting Windows 10 & 11'S Phishing Protection Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artificial-intelligence-windows-future-trailblazer/"><u>Artificial Intelligence: Windows' Future Trailblazer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-keeping-high-vitality-in-check-on-windows/"><u>Balancing Act: Keeping High Vitality in Check on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-practices-unveiled-supercharge-wsl-2-with-windows-dev-tools/"><u>Best Practices Unveiled: Supercharge WSL 2 with Windows Dev Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-boundaries-artificinas-intelligence-in-windows-11/"><u>Beyond Boundaries: Artificinas Intelligence in Windows 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-forgotten-pin-of-your-realme-c51-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Realme C51</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-precision-evaluation-a-vll-approach-to-apps/"><u>In 2024, Precision Evaluation A VLL Approach to Apps</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/quick-guide-altering-screen-colors-on-google-meet/"><u>Quick Guide Altering Screen Colors on Google Meet</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/splitcam-assessment-best-video-recorder-ranking/"><u>SplitCam Assessment Best Video Recorder Ranking?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-great-ai-debate-whos-best-gpt-vs-microsoftgoogles-innovations/"><u>The Great AI Debate: Who's Best? GPT Vs. Microsoft/Google's Innovations</u></a></li>
</ul></div>

