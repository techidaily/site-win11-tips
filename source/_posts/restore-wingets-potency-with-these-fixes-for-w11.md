---
title: Restore Winget's Potency with These Fixes for W11
date: 2024-10-01T00:36:32.276Z
updated: 2024-10-04T00:39:28.873Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restore Winget's Potency with These Fixes for W11
excerpt: This Article Describes Restore Winget's Potency with These Fixes for W11
keywords: Winget Power Restoration,W11 Fix Tips,Revive W11 Performance,Improve Winget Efficiency,Optimize W11 Version,Enhance Winget Functionality,Strengthen W11 Capabilities
thumbnail: https://thmb.techidaily.com/046b51c249713a58e7f91807e73ec08e3a40b03e4add7fe4a3b9657a9796ae66.jpg
---

## Restore Winget's Potency with These Fixes for W11

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

## 2\. Check if the Winget Servers Are Down

 Winget is an online tool that needs a robust internet connection to search for a package in various repositories and then download and install them. If the Winget servers are down or inactive, it won’t be able to fetch results from repositories. So, check if Winget servers are down using [DownDetector](https://redirect.viglink.com/?format=go&jsonp=vglnk%5F168667664973511&key=eac202ea7a96cf485281d6c4ffa2069e&libId=liuggg0i0103es17000ULlmtlntd&loc=https%3A%2F%2Fwww.makeuseof.com%2Fhow-to-fix-0x8004def5-onedrive-error-code-windows-11%2F&ccpaConsent=1---&v=1&opt=true&optExText=false&out=https%3A%2F%2Fdowndetector.com%2F&ref=https%3A%2F%2Fwww.makeuseof.com%2Fauthor%2Fabhishekkumar-mishra%2F&title=9%20Ways%20to%20Fix%20the%200x8004def5%20OneDrive%20Error%20Code%20on%20Windows%2011&txt=DownDetector) or a similar website.

 You can also check if your Windows PC can connect to the internet. Simply open a web browser and access a website or run a web-based app to confirm internet connectivity. If the servers are down, you will have to wait until they come up live again to use Winget.

## 3\. Perform a Complete System Shutdown

 Windows uses Fast Startup to hibernate kernel-level processes and if any of these glitch, they remain in that state after your power on the system. So, perform a complete shutdown to close and relaunch all the core services and then try to run Winget. Here’s how to do it:

1. Press **Win + R** to open the Run dialog box. Type **cmd** and press **Ctrl + Shift + Enter** keys to [open the Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Now, type the following command and press the Enter key: **shutdown /s /f /t 0**  
![Completely Shutdown your PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/completely-shutdown-your-pc.jpg)
3. Your system will shut down. It will take longer than a usual shutdown because Windows will close everything.
4. Power on your system and try to run Winget using the Terminal app to check if it works now.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049390/7443" target="_top" id="2049390">
  <img src="//a.impactradius-go.com/display-ad/7443-2049390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049390/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Update App Installer

 Winget is a part of Windows 10 and 11 now and is shipped to PCs using the App Installer application. If you haven’t updated the App Installer in a while, you can face issues in running Winget and managing packages. Winget is included only in version 1.11.11451 or higher of the App Installer. If you have a version older than that, you cannot use Winget from the terminal.

![Update App Installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/update-app-installer.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115916/19272" target="_top" id="2115916">
  <img src="//a.impactradius-go.com/display-ad/19272-2115916" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115916/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 So, open Microsoft Store and check the library section for any pending updates for the App Installer. Manually search and install the update and check if Winget works now.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130531/26400" target="_top" id="2130531">
  <img src="//a.impactradius-go.com/display-ad/26400-2130531" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130531/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1166360/14483" target="_top" id="1166360">
  <img src="//a.impactradius-go.com/display-ad/14483-1166360" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://electronicx.pxf.io/i/5597632/1166360/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Open the Terminal app and check if Winget works or not.

## 7\. Re-register Winget Using PowerShell

 If Winget isn’t working on your PC, you can re-register it using PowerShell. Since it is a part of the App Installer which is a system app, it is possible to re-register it. Repeat the following steps:

1. Press **Win + R** to open the Run dialog box. Type **PowerShell** and press the **Ctrl + Shift + Enter** keys at once.
2. The PowerShell window will launch with admin rights. Paste the following code and press the **Enter** key to execute it:  
`Add-AppxPackage -DisableDevelopmentMode -Register "C:\Program Files\WindowsApps\Microsoft.Winget.Source_2021.718.1322.843_neutral__8wekyb3d8bbwe\AppXManifest.xml" -Verbose`
3. You won’t see any confirmation message after the command executes successfully. Close the PowerShell window and restart your PC.  
![Re-register Winget Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/re-register-winget-using-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557743/17382" target="_top" id="1557743">
  <img src="//a.impactradius-go.com/display-ad/17382-1557743" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557743/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Try Some Generic Windows Fixes

 If none of the methods work for you, try our generic fixes like SFC and DISM scans that find and fix the system file corruption and service Windows Image components. You must [run the SFC scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) first and allow it to find and replace the corrupt system files, if any. After that, [run the DISM scan](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) in online mode.

 After running these scans, you can use System Restore to revert the PC to a point in time when everything worked fine. Lastly, you can perform a complete system reset. You can choose the Keep my files option to preserve all your files while [factory resetting Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/).

## Make Winget Functional Again

 Winget is a fantastic package manager that helps you control and manage app packages from the terminal. Ensure robust internet connectivity and check if the app execution alias is active for Winget. Manually reconfigure the PATH for Winget and re-register the App Installer using PowerShell. If you want a GUI version of Winget, you can try Winstall which helps you batch-install apps.

 But some users report that Winget is not working on their PC. They face a "The system cannot execute the specified program" and cannot run any commands, This post will discuss multiple methods to resolve the issue and restore Winget to its working state. Let’s begin.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/new-pioneering-performance-exclusive-insights-into-oculus-headsets/"><u>[New] Pioneering Performance Exclusive Insights Into Oculus Headsets</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-zooming-in-on-clarity-an-essential-guide-to-professional-quality-audio-recordings/"><u>[Updated] In 2024, Zooming In On Clarity An Essential Guide to Professional-Quality Audio Recordings</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-unleash-the-fun-of-jumping-into-tiktok-lives-for-2024/"><u>[Updated] Unleash the Fun of Jumping Into TikTok Lives for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-dynamic-directionality-prime-phone-friendly-tripods/"><u>2024 Approved Dynamic Directionality Prime Phone-Friendly Tripods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-the-hidden-addresses-of-installed-pc-apps/"><u>Demystifying the Hidden Addresses of Installed PC Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-the-user-experience-with-drive-views/"><u>Enhancing the User Experience with Drive Views</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/raphic-social-strategies-for-budget-brands-for-2024/"><u>Infographic Social Strategies for Budget Brands for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/online-zet-mp4-in-m4b-volledig-gratuit-movavi/"><u>Online Zet MP4 in M4B Volledig Gratuït - Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-non-working-cut-and-paste-on-win-11/"><u>Remedying Non-Working Cut & Paste on Win 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722874973773-resolve-your-issues-with-missing-python24dll-error-messages-here/"><u>Resolve Your Issues with Missing Python24.dll Error Messages Here!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safety-switch-stopping-windows-11-tasks/"><u>Safety Switch: Stopping Windows 11 Tasks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/1726222473845-avi-mp4-movavi/"><u>비용 없는 원피사 AVI 데이터를 MP4로 전환하기: Movavi의 가이드</u></a></li>
</ul></div>

