---
title: Methods to Retrieve Windows Backup Default State
date: 2024-09-11T01:26:51.770Z
updated: 2024-09-12T01:26:51.770Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Methods to Retrieve Windows Backup Default State
excerpt: This Article Describes Methods to Retrieve Windows Backup Default State
keywords: Windows Recovery Options,Default Backup Restore,WinBackup Command Line,System Image Backups,WBExec Utility Use,CMD for Backup Retrieval,Windows System Image Scripts
thumbnail: https://thmb.techidaily.com/e937e68a5b9ec03875dd350ca4501bcb740dbcf769458408d36b67b305252021.jpg
---

## Methods to Retrieve Windows Backup Default State

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>







<!-- affiliate ads begin -->
<span id="1975636">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975636.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975636">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975636.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975636%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975636/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2135474/26400" target="_top" id="2135474">
  <img src="//a.impactradius-go.com/display-ad/26400-2135474" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2135474/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118322/7443" target="_top" id="2118322">
  <img src="//a.impactradius-go.com/display-ad/7443-2118322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118322/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.





<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014849/22899" target="_top" id="2014849">
  <img src="//a.impactradius-go.com/display-ad/22899-2014849" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014849/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




### 1\. Using Command Prompt

 If your current backup configuration isn't working, reset Windows Backup to its default settings. To get started, [run the Command Prompt with admin access](https://www.makeuseof.com/windows-run-command-prompt-admin/). In the Command Prompt window, run the following command:

`reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f`

 This will reset to the default configuration and remove all existing backups.

 After that, copy and paste the following command into the Command Prompt window and press **Enter**:

`reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup`

 This will recreate the WindowsBackup entry in the registry editor. Next, type in and run the below command to delete the Automatic Backup scheduled task on Windows:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f`

 Finally, execute the below command to delete the backup monitor scheduled task:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 After executing the above commands, restart your computer. This will reset Windows Backup to its default settings.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135418/19272" target="_top" id="2135418">
  <img src="//a.impactradius-go.com/display-ad/19272-2135418" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135418/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




### 2\. Creating a Batch File

 If you're not comfortable with the command line interface, reset Windows Backup by creating a batch file.

 To do this, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and paste the below code.

`<code>reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f  
reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 Click the **File** menu and select **Save as**. On the Save as dialog, type **reset-backup.bat** as the file name. Then choose **All Files** from the drop-down menu next to the Save as type. From the left panel, select **Desktop** and click the **Save** button.

 Now, close the Notepad window and right-click on the batch file. From the context menu, select **Run as administrator**. This will reset Windows Backup to its default settings.

 Lastly, restart your computer and you're done. These are two methods to reset Windows Backup to its default settings.





<!-- affiliate ads begin -->
<span id="1912746">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1912746.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20231-1912746">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1912746.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmindmanager.sjv.io%2Fc%2F5597632%2F1912746%2F20231'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1912746/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-unusual-message-content-finding-myself-online/"><u>[New] 2024 Approved Unusual Message Content Finding Myself Online</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/rom-novice-to-notable-top-course-recommendations-for-youtubers/"><u>[New] From Novice to Notable Top Course Recommendations for YouTubers</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/nleash-potential-with-optimal-hashtags-for-gaming-vids-for-2024/"><u>[New] Unleash Potential with Optimal Hashtags for Gaming Vids for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unleashing-potential-enhancing-your-tiktok-videos/"><u>[New] Unleashing Potential Enhancing Your TikTok Videos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-videos-that-stand-out-the-perfect-size-for-insta/"><u>[New] Videos That Stand Out The Perfect Size for Insta</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-creative-compassion-best-10-drawing-tools-free-and-simple/"><u>[Updated] Creative Compassion Best 10 Drawing Tools, Free and Simple</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-exploring-the-top-7-voice-customization-applications/"><u>[Updated] Exploring the Top 7 Voice Customization Applications</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-prime-skating-moments-from-the-world-cup-22/"><u>[Updated] Prime Skating Moments From the World Cup '22</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-best-windows-video-communicators-list-1-8/"><u>2024 Approved Best Windows Video Communicators List #1-8</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-mastering-the-art-of-shorts-imagery-quick-smart-updates/"><u>2024 Approved Mastering the Art of Shorts Imagery Quick, Smart Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dispatching-win11-camera-troubles-with-error-code-a00f4289/"><u>Dispatching Win11 Camera Troubles with Error Code A00F4289</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-creative-wallpapers-for-each-windows-11-monitor/"><u>Explore Creative Wallpapers for Each Windows 11 Monitor</u></a></li>
<li><a href="https://hardware-help.techidaily.com/getting-started-downloading-and-installing-steelseries-graphics-card-drivers-for-windows-systems/"><u>Getting Started: Downloading and Installing SteelSeries Graphics Card Drivers for Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-the-reset-account-lockout-counter-after-failed-logon-attempts-in-windows-10-and-11/"><u>How to Change the Reset Account Lockout Counter After Failed Logon Attempts in Windows 10 and 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-usb-device-not-recognized-error-a-comprehensive-guide/"><u>How to Fix 'USB Device Not Recognized' Error: A Comprehensive Guide</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-fix-a-non-responsive-elder-scrolls-online-game-startup/"><u>How to Fix a Non-Responsive Elder Scrolls Online Game Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-hide-the-task-view-button-from-the-windows-11-taskbar/"><u>How to Hide the Task View Button From the Windows 11 Taskbar</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-12-without-passcode-drfone-by-drfone-ios/"><u>How to Unlock iPhone 12 Without Passcode? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-efficient-data-management-techniques/"><u>Implementing Efficient Data Management Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-notification-for-full-batteries-on-windows/"><u>Improve Notification for Full Batteries on Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-10-best-fake-gps-location-spoofers-for-apple-iphone-12-drfone-by-drfone-virtual-ios/"><u>In 2024, 10 Best Fake GPS Location Spoofers for Apple iPhone 12 | Dr.fone</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-finding-the-central-node-of-youtube-video-management/"><u>In 2024, Finding the Central Node of YouTube Video Management</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-to-get-and-use-pokemon-go-promo-codes-on-apple-iphone-14-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Get and Use Pokemon Go Promo Codes On Apple iPhone 14 Plus | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-masterful-viewing-for-artists-best-monitor-guide/"><u>In 2024, Masterful Viewing for Artists – Best Monitor Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-of-pcs-performance-spectrum/"><u>In-Depth Analysis of PC's Performance Spectrum</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-the-most-of-windows-outlook-a-calendar-customization-tutorial/"><u>Making the Most of Windows Outlook - A Calendar Customization Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-installation-package-openness-in-ws11ws10-environments/"><u>Mastering Installation Package Openness in WS11/WS10 Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-handling-breakpoint-error-in-windows/"><u>Mastering the Art of Handling 'Breakpoint Error' In Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-fix-excel-notation-on-windows-notepad/"><u>Methods to Fix Excel Notation on Windows Notepad</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-tunewizard-pro-expertly-organize-your-music-library-across-windowsmac-platforms/"><u>New In 2024, TuneWizard Pro Expertly Organize Your Music Library Across Windows/Mac Platforms</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/nook-glowlight-3-by-barnes-and-noble-ultimate-review-for-evening-readers/"><u>Nook GlowLight 3 by Barnes & Noble: Ultimate Review for Evening Readers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-summation-issues-in-winrar-archives-with-six-tactics/"><u>Overcoming Summation Issues in WinRAR Archives With Six Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-camera-app-glitch-a00f425d/"><u>Overcoming Windows Camera App Glitch: A00F425D</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pivot-point-shifting-your-onedrive-save-destination-on-pc/"><u>Pivot Point: Shifting Your OneDrive Save Destination on PC</u></a></li>
<li><a href="https://location-social.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-apple-iphone-14-plus-drfone-by-drfone-virtual-ios/"><u>Proven Ways in How To Hide Location on Life360 For Apple iPhone 14 Plus | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-fading-frames-enhancing-vlc-performance/"><u>Quick Fix for Fading Frames: Enhancing VLC Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivate-dormant-slack-notifications-a-quick-fix-guide-for-win-11/"><u>Reactivate Dormant Slack Notifications: A Quick Fix Guide for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-the-issue-of-one-channel-playback-with-windows-bluetooth/"><u>Rectifying the Issue of One-Channel Playback with Windows Bluetooth</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-black-and-white-errors-in-microsoft-shop/"><u>Remedy Black and White Errors in Microsoft Shop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-non-appearing-windows-11-sign-ins/"><u>Resolving Non-Appearing Windows 11 Sign-Ins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-windows-11-performing-an-uncluttered-reboot/"><u>Reviving Windows 11: Performing an Uncluttered Reboot</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/revolutionize-user-engagement-on-your-website-through-cookiebot-solutions/"><u>Revolutionize User Engagement on Your Website Through Cookiebot Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sketch-it-up-your-ultimate-guide-to-the-best-drawing-software-on-win10/"><u>Sketch It Up: Your Ultimate Guide to the Best Drawing Software on Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-11s-microsoft-store-error-0x80073cf3/"><u>Solving Windows 11'S Microsoft Store Error 0X80073cf3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-experience-with-emoji-15-in-windows-11/"><u>Streamline Your Experience with Emoji 15 in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strengthen-your-gpu-ranked-1-6-tools-for-windows-users/"><u>Strengthen Your GPU: Ranked #1-#6 Tools for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-switch-toggle-microsofts-window-integrated-chat-support/"><u>Swift Switch: Toggle Microsoft’s Window-Integrated Chat Support</u></a></li>
<li><a href="https://driver-error.techidaily.com/systems-untapped-resource-potential/"><u>System's Untapped Resource Potential</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-halting-automatic-bios-entry-after-reboot/"><u>Techniques for Halting Automatic BIOS Entry After Reboot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-fixers-manual-for-installer-errors-on-win11/"><u>The Ultimate Fixer's Manual for Installer Errors on Win11</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-insights-in-depth-guides-on-hardware-and-pc-building/"><u>Tom's Tech Insights: In-Depth Guides on Hardware and PC Building</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharge-windows-downloads-for-a-smoother-valorant-experience/"><u>Turbocharge Windows Downloads for a Smoother Valorant Experience</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/unlocking-ig-potential-strategies-for-accumulating-1000plus-likesmonth-for-2024/"><u>Unlocking IG Potential Strategies for Accumulating 1,000+ Likes/Month for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-potential-mastering-the-function-fn-key/"><u>Unlocking Potential: Mastering the Function (Fn) Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-printer-networking-hurdles-in-windows/"><u>Unraveling Printer Networking Hurdles in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-stop-default-search-menu-activation/"><u>Windows 11: Stop Default Search Menu Activation</u></a></li>
<li><a href="https://tools.techidaily.com/winxdvd/products/"><u>Winxdvd's Products</u></a></li>
</ul></div>







<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    