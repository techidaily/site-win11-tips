---
title: Easy Routines for Preventing VSCode Freeze on W11
date: 2024-10-05T17:33:42.571Z
updated: 2024-10-09T07:47:27.669Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Easy Routines for Preventing VSCode Freeze on W11
excerpt: This Article Describes Easy Routines for Preventing VSCode Freeze on W11
keywords: Avoid VSCode Crash,No Freeze VSCode,W11 Code Ease,Preventing VSCode Glitches,Fix W11 VSCode Freezes,Optimize VSCode Usage,Stable W11 VSCode Sessions
thumbnail: https://thmb.techidaily.com/dcfda18db33cd62e49e998a15226cf50935f6371594750217f925e9fab66f62b.jpg
---

## Easy Routines for Preventing VSCode Freeze on W11

 Visual Studio Code is a popular IDE widely preferred by programming enthusiasts. Microsoft revamped its user interface and made it available on Microsoft Store as well. You can even install multiple extensions in Visual Studio Code to make your programming experience better.

 But many users face abrupt crashes in the Visual Studio Code app which impedes their workflow. If you face the same issue repeatedly, don't worry. We will list out multiple fixes so that you can try and resolve the issue on your computer. Let's dive into the post.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Terminate Visual Studio Code and Restart

 Before moving on to more complex fixes for the app, completely close Visual Studio Code using Task Manager and restart it. Here's how to do it:

1. Right-click on the**Start** button to open the[Power User menu](https://www.makeuseof.com/windows-power-menu-guide/) . Click on the**Task Manager** option.
2. Locate the Visual Studio Code process in the list of active processes.
3. Right-click on it and click on the**End Task** option from the context menu. It will close Visual Studio Code app and all its associated processes.  
![Terminate Visual Studio Code and Restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/terminate-visual-studio-code-and-restart.jpg)
4. Close the Task Manager window and open the Start menu.
5. Type Visual Studio Code and run the app with administrator privileges. Check if it encounters a crash now.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012415/19272" target="_top" id="2012415">
  <img src="//a.impactradius-go.com/display-ad/19272-2012415" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Reboot your System

 Restarting the system is the oldest trick in the book. It might not sound effective but resolves most of the system issues. Restarting a system helps in closing all the active processes and services, clearing the system memory, and relaunching them. Due to this, any services or apps that aren't working will also restart afresh.

**Right-click** on the Start button and select the**Restart** option from the Power user menu. After the system restarts, run the Visual Studio Code with administrator permissions and check if it crashes.

## 3\. Disable Hardware Acceleration

 Hardware acceleration can cause problems on the low-spec system running the Visual Studio app. There isn’t an option for this feature in the app settings. So, you must modify the argv.json file to disable it. Here's how:

1. Launch Visual Studio Code and click on the**Settings** icon in the bottom left corner.
2. Select the**Command Palette** option from the settings menu and click on the**Preferences: Configure Runtime Arguments** option.
3. Now, enter the following command in the argv.json file:**"disable-hardware-acceleration": true**  
![Disable Hardware Acceleration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-hardware-acceleration.jpg)
4. Press**Ctrl+ S** to save the changes to the file.
5. Restart the app and check if it crashes now.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134243/18498" target="_top" id="2134243">
  <img src="//a.impactradius-go.com/display-ad/18498-2134243" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134243/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Perform a Clean Boot

 Often, third-party apps and services can interfere with other apps and cause app freezes and crashes. So, to rule out this possibility, do a[clean boot of your Window system](https://www.makeuseof.com/clean-boot-windows-11/) with only Microsoft-related services enabled on startup.

 If Visual Studio Code works fine after a clean boot, retry the clean boot while enabling some third-party service. Repeat this process until you find the problematic service or app.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134502/19576" target="_top" id="2134502">
  <img src="//a.impactradius-go.com/display-ad/19576-2134502" border="0" alt="https://techidaily.com" width="672" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134502/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Disable Visual Studio Code Extensions

 Visual Studio Code needs extensions to extend language and debugger support for various programming languages. If you use extensions, you must find and remove the troublesome ones. Here's how to do it:

1. Launch Visual Studio Code and press**Ctrl+ Shift + X** to open the extensions settings.
2. Click on the**Installed** option to display all the extensions installed in the Visual Studio Code app.
3. Right-click on any extension and select the**Disable** option from the context menu.  
![Disable Visual Studio Code Extensions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-visual-studio-code-extensions.jpg)
4. Repeat this process for all extensions to disable them.
5. Now restart the Visual Studio Code app and run it for some time without any extensions. If it doesn't crash, an extension is probably the reason behind the crash.
6. To identify the extension, revisit the Extension settings in the app and right-click on a disabled extension. Select the**Enable** option.
7. Check if Visual Studio Code encounters a crash when this extension is active. Repeat the process to find the culprit extension and remove it from the app.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144298/7443" target="_top" id="2144298">
  <img src="//a.impactradius-go.com/display-ad/7443-2144298" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144298/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Exclude Visual Studio Code in Windows Defender

 Antivirus programs do not play nicely with apps and programs and often wrongly flag them. So, add an exclusion for the Visual Studio Code app. If you use a third-party antivirus on your system, add an exclusion for the Visual Studio Code app directory by accessing its settings. You can even[temporarily disable Windows Security](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and run the app to check if it crashes now.

## 7\. Update Visual Studio Code

 If you are using a very old version of Visual Studio Code and are facing abrupt crashes, then you must update the app. A new app update brings security improvements and bug fixes which could exist in the old version of the app. Here’s how to update the app:

1. Open Visual Studio Code and click on the**Settings** icon.
2. Select the**Check for updates** option from the context menu.  
![Update the Visual Studio Code](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/update-the-visual-studio-code.jpg)
3. If there is an update available, download and install it and restart your computer.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484909/16446" target="_top" id="1484909">
  <img src="//a.impactradius-go.com/display-ad/16446-1484909" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484909/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Launch the app again and use it for some time while keeping an eye out for crashes.

## 8\. Roll Back the Last Windows Update

 Windows updates can break system features or not sit well with third-party apps. If you encounter the app crash issue after a recent update,[manually uninstall the most recent Windows update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) on your computer. It will revert all the new changes made to your system.

## 9\. Reinstall Visual Studio Code

 If the app installation is severely corrupt and unfixable, then a simple app reset won’t be effective. Instead, you must completely remove Visual Studio Code from your system and then reinstall it.

 Repeat the following steps to reinstall Visual Studio Code using Winget:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**cmd** in the text input box and press**Ctrl + Shift + Enter** to launch the command prompt with administrator rights.
3. Accept the UAC prompt and click on the**Yes** button.
4. Type the following command and press enter key:**Winget list**
5. Copy the ID of the Visual Studio Code app and paste it after the following command:**winget uninstall \[App ID\]**  
winget uninstall Microsoft.VisualStudioCode
6. Wait for the uninstallation to complete. Restart your system.  
![Reinstall Visual Studio Code 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-visual-studio-code-1.jpg)
7. Launch the Command Prompt with admin privileges again.
8. Then type the following command and press the enter key:**winget install Microsoft.VisualStudioCode**  
![Reinstall Visual Studio Code 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-visual-studio-code-2.jpg)
9. It will take a while to download and install the app on your system. You won’t need to interact with the installer window or grant any permissions.
10. Run Visual Studio Code now and check if the app encounters any crashes now.

## 10\. Use the Web Version

 Microsoft even offers a[web version of Visual Studio Code](https://vscode.dev/) which you can use as a temporary solution. You can sign in to the web version and sync your files and settings. Moreover, you can install a PWA from the browser of Visual Studio Code and launch it directly from your desktop.

## Visual Studio Code Won’t Crash Anymore on Windows 11

 Microsoft’s popular IDE is the go-to tool of programmers. If its crashes abruptly, the projects can get delayed by quite a bit. Start with basic troubleshooting and then disable hardware acceleration on your system. After that, disable extensions and perform a clean boot. Add an exclusion for the app in the antivirus program. Lastly, if nothing works, reinstall the Visual Studio Code app on your system.

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
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-assemble-photos-for-a-captivating-storyboard-experience/"><u>[New] In 2024, Assemble Photos for a Captivating Storyboard Experience</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-learn-photoshops-core-techniques-for-shade-adjustment/"><u>[New] Learn Photoshop's Core Techniques for Shade Adjustment</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/6-game-changing-tactics-to-increase-watch-time-and-reduce-churn-rate-for-2024/"><u>6 Game-Changing Tactics to Increase Watch Time and Reduce Churn Rate for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-oppo-reno-10-pro-5g-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Oppo Reno 10 Pro 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-email-service-failures-on-windows-error-0x800713f/"><u>Correcting Email Service Failures on Windows (Error 0X800713F)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-techniques-to-extract-large-amounts-of-data-at-once/"><u>Efficient Techniques to Extract Large Amounts of Data at Once</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-overcoming-the-most-common-update-issues/"><u>Expert Advice: Overcoming the Most Common Update Issues</u></a></li>
<li><a href="https://win-answers.techidaily.com/expert-tips-to-resolve-your-computers-screen-turning-black-on-zoom-webinars-and-meetings-updated-2e-guide-2024/"><u>Expert Tips to Resolve Your Computer's Screen Turning Black on Zoom Webinars and Meetings (Updated 2E Guide, 2024)</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-flash-dead-nokia-c12-pro-safely-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Flash Dead Nokia C12 Pro Safely | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-modify-aspect-ratio-of-a-video-in-different-formats-for-youtube/"><u>How to Modify Aspect Ratio of a Video in Different Formats for YouTube</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-lost-data-from-zte-blade-a73-5g-by-fonelab-android-recover-data/"><u>Recover lost data from ZTE Blade A73 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-energy-levels-after-high-living-in-windows/"><u>Reviving Energy Levels After High Living in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-windows-11-temp-directory-functionality/"><u>Secure Windows 11 Temp Directory Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essence-of-windows-cab-files-and-execution-procedures/"><u>The Essence of Windows Cab Files & Execution Procedures</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-essential-guide-to-blur-techniques-for-dynamic-artwork/"><u>The Essential Guide to Blur Techniques for Dynamic Artwork</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-code-0x800f0831-the-troubleshoot-tome/"><u>Unraveling Code 0X800f0831: The Troubleshoot Tome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-another-users-ms-error-issue/"><u>Unraveling the Another User’s MS Error Issue</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/uploading-finesse-imovie-videos-meeting-youtube-standards/"><u>Uploading Finesse IMovie Videos Meeting YouTube Standards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-1011-overcoming-the-hypervisor-bsod-crash/"><u>Win 10/11: Overcoming the HYPERVISOR BSOD Crash</u></a></li>
</ul></div>

