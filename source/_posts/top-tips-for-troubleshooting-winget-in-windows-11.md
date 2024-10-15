---
title: Top Tips for Troubleshooting Winget in Windows 11
date: 2024-10-12T21:08:18.749Z
updated: 2024-10-15T00:14:10.816Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Top Tips for Troubleshooting Winget in Windows 11
excerpt: This Article Describes Top Tips for Troubleshooting Winget in Windows 11
keywords: Windows 11 Wireless Tools,Winget Troubleshoot Guide,Fixing Winget Issues,Winget Install Tips,Winget Command Line,Win11 Winget Solutions,Winget Errors in Win11
thumbnail: https://thmb.techidaily.com/ccf2cd6688a4adcaeda8d922b0b91ea561ec3cf2936a8b4a71d20d4455d103fb.jpg
---

## Top Tips for Troubleshooting Winget in Windows 11

 Winget is a command-line tool that can download and install app packages from MS Store and the apps listed in its repository. It saves a lot of time that would be otherwise wasted in searching the Microsoft Store or the web for a particular app, downloading it, and then manually installing it.

 But some users report that Winget is not working on their PC. They face a "The system cannot execute the specified program" and cannot run any commands, This post will discuss multiple methods to resolve the issue and restore Winget to its working state. Let’s begin.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Reasons Why Winget Stops Working on Windows

 Here are the following reasons why Winget is not working on your Windows PC:

1. You are running an outdated version of the App Installer.
2. Winget servers are down, or you don’t have an active internet connection.
3. The app execution alias is not configured or inactive for Winget.
4. App Installer failed to add the PATH environment variable automatically while installing.

 Now, you know the reasons behind Winget not working issue. Try out these eight methods to resolve the issue and use your favorite package manager again.

## 1\. Close and Reopen Winget in the Terminal App

 Before moving on to advanced fixes, completely close the Command Prompt or PowerShell instance you are running on the PC. You can use the Task Manager to stop an unresponsive instance of either of these command-line tools.

 After that, open Command Prompt or PowerShell with administrator privileges on your system. Type Winget and press the **Enter** key to check if Winget works now.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528689/16446" target="_top" id="1528689">
  <img src="//a.impactradius-go.com/display-ad/16446-1528689" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528689/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Check if the Winget Servers Are Down

 Winget is an online tool that needs a robust internet connection to search for a package in various repositories and then download and install them. If the Winget servers are down or inactive, it won’t be able to fetch results from repositories. So, check if Winget servers are down using [DownDetector](https://redirect.viglink.com/?format=go&jsonp=vglnk%5F168667664973511&key=eac202ea7a96cf485281d6c4ffa2069e&libId=liuggg0i0103es17000ULlmtlntd&loc=https%3A%2F%2Fwww.makeuseof.com%2Fhow-to-fix-0x8004def5-onedrive-error-code-windows-11%2F&ccpaConsent=1---&v=1&opt=true&optExText=false&out=https%3A%2F%2Fdowndetector.com%2F&ref=https%3A%2F%2Fwww.makeuseof.com%2Fauthor%2Fabhishekkumar-mishra%2F&title=9%20Ways%20to%20Fix%20the%200x8004def5%20OneDrive%20Error%20Code%20on%20Windows%2011&txt=DownDetector) or a similar website.

 You can also check if your Windows PC can connect to the internet. Simply open a web browser and access a website or run a web-based app to confirm internet connectivity. If the servers are down, you will have to wait until they come up live again to use Winget.

## 3\. Perform a Complete System Shutdown

 Windows uses Fast Startup to hibernate kernel-level processes and if any of these glitch, they remain in that state after your power on the system. So, perform a complete shutdown to close and relaunch all the core services and then try to run Winget. Here’s how to do it:

1. Press **Win + R** to open the Run dialog box. Type **cmd** and press **Ctrl + Shift + Enter** keys to [open the Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Now, type the following command and press the Enter key: **shutdown /s /f /t 0**  
![Completely Shutdown your PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/completely-shutdown-your-pc.jpg)
3. Your system will shut down. It will take longer than a usual shutdown because Windows will close everything.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135403/19272" target="_top" id="2135403">
  <img src="//a.impactradius-go.com/display-ad/19272-2135403" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135403/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Power on your system and try to run Winget using the Terminal app to check if it works now.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938721/19272" target="_top" id="1938721">
  <img src="//a.impactradius-go.com/display-ad/19272-1938721" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938721/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Update App Installer

 Winget is a part of Windows 10 and 11 now and is shipped to PCs using the App Installer application. If you haven’t updated the App Installer in a while, you can face issues in running Winget and managing packages. Winget is included only in version 1.11.11451 or higher of the App Installer. If you have a version older than that, you cannot use Winget from the terminal.

![Update App Installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/update-app-installer.jpg)

 So, open Microsoft Store and check the library section for any pending updates for the App Installer. Manually search and install the update and check if Winget works now.

## 5\. Enable the App Execution Alias

 If the App Execution Alias for Winget is disabled, it won’t work when you try accessing Winget from the terminal. So, you must enable it in the app settings. Repeat the following steps:

1. Right-click on the **Start** button to open the **Power User** menu. Click on the **Settings** app.
2. Navigate to the left-hand side menu and click on the **Apps** option.
3. Now, click on the **Advanced app settings** option. Then click on the **App execution aliases** option.
4. Locate the **Windows Package Manager Client** option. Check the toggle next to it. If it is disabled, click on it to **enable** the app execution alias for the app.  
![Enable the App Execution Alias-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-the-app-execution-alias-1.jpg)
5. Close the Settings app.

## 6\. Manually Add the Path Environment Variable

 Ae wrongly configured Winget path can also produce errors. So, you must manually add the correct path in Environment Variables using the Advanced System Properties window. Repeat the following steps:

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **sysdm.cpl ,3** in the text box and press the **Enter** key to open **Advanced System Properties**.
2. Click on the **Environment Variables** button. Click on the **Path** entry and then click on the **Edit** button.
3. Now, click on the New button and paste the following path: **%UserProfile%\\AppData\\Local\\Microsoft\\WindowsApps**  
![Manually Add the Path Environment Variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/manually-add-the-path-environment-variable.jpg)
4. Click on the **OK** button. Restart your PC.
5. Open the Terminal app and check if Winget works or not.

## 7\. Re-register Winget Using PowerShell

 If Winget isn’t working on your PC, you can re-register it using PowerShell. Since it is a part of the App Installer which is a system app, it is possible to re-register it. Repeat the following steps:

1. Press **Win + R** to open the Run dialog box. Type **PowerShell** and press the **Ctrl + Shift + Enter** keys at once.
2. The PowerShell window will launch with admin rights. Paste the following code and press the **Enter** key to execute it:  
`Add-AppxPackage -DisableDevelopmentMode -Register "C:\Program Files\WindowsApps\Microsoft.Winget.Source_2021.718.1322.843_neutral__8wekyb3d8bbwe\AppXManifest.xml" -Verbose`
3. You won’t see any confirmation message after the command executes successfully. Close the PowerShell window and restart your PC.  
![Re-register Winget Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/re-register-winget-using-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135407/19272" target="_top" id="2135407">
  <img src="//a.impactradius-go.com/display-ad/19272-2135407" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135407/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657400/16446" target="_top" id="1657400">
  <img src="//a.impactradius-go.com/display-ad/16446-1657400" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657400/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Try Some Generic Windows Fixes

 If none of the methods work for you, try our generic fixes like SFC and DISM scans that find and fix the system file corruption and service Windows Image components. You must [run the SFC scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) first and allow it to find and replace the corrupt system files, if any. After that, [run the DISM scan](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) in online mode.

 After running these scans, you can use System Restore to revert the PC to a point in time when everything worked fine. Lastly, you can perform a complete system reset. You can choose the Keep my files option to preserve all your files while [factory resetting Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/).

## Make Winget Functional Again

 Winget is a fantastic package manager that helps you control and manage app packages from the terminal. Ensure robust internet connectivity and check if the app execution alias is active for Winget. Manually reconfigure the PATH for Winget and re-register the App Installer using PowerShell. If you want a GUI version of Winget, you can try Winstall which helps you batch-install apps.

 But some users report that Winget is not working on their PC. They face a "The system cannot execute the specified program" and cannot run any commands, This post will discuss multiple methods to resolve the issue and restore Winget to its working state. Let’s begin.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-cost-free-creative-conversion-twitter-to-tweeple-gifs/"><u>[New] 2024 Approved Cost-Free Creative Conversion Twitter to Tweeple GIFs</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-enhancing-video-content-step-by-step-cropping-and-export-guide-for-2024/"><u>[New] Enhancing Video Content Step-by-Step Cropping & Export Guide for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-chronocapture-expert-time-lapse-techniques-for-samsung-users/"><u>[Updated] ChronoCapture Expert Time-Lapse Techniques for Samsung Users</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-transformative-tips-to-take-your-lunapic-skills-up/"><u>2024 Approved Transformative Tips to Take Your LunaPic Skills Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-simple-steps-for-overcoming-windows-onedrive-glitches/"><u>5 Simple Steps for Overcoming Windows OneDrive Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-gaming-power-drain-from-wm/"><u>Cutting Down Gaming Power Drain From WM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-non-successful-updates-in-windows-discord/"><u>Dealing with Non-Successful Updates in Windows Discord</u></a></li>
<li><a href="https://buynow-info.techidaily.com/great-shots-grumpy-setup-nikon-coolpix-a10-experience/"><u>Great Shots, Grumpy Setup: Nikon COOLPIX A10 Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-speed-up-epic-games-launcher-downloads-on-windows/"><u>How to Speed Up Epic Games Launcher Downloads on Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-pro-max-to-other-iphone-12-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 Pro Max To Other iPhone 12 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-poco-m6-pro-4g-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Poco M6 Pro 4G to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-quick-thumbs-up-creating-your-own-google-image-mosaic/"><u>In 2024, Quick Thumbs Up Creating Your Own Google Image Mosaic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-stuck-battlenet-login-screen/"><u>Solutions for Stuck Battle.net Login Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-operations-7-easy-tips-for-advanced-windows-11-users/"><u>Streamline Operations: 7 Easy Tips for Advanced Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-your-onedrive-to-a-desired-spot-on-win10/"><u>Transitioning Your OneDrive to a Desired Spot on Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-windows-users-should-anticipate-sudo/"><u>Why Windows Users Should Anticipate Sudo</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    