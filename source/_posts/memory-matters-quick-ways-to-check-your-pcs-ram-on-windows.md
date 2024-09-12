---
title: "Memory Matters: Quick Ways to Check Your PC's RAM on Windows"
date: 2024-09-11T01:27:14.919Z
updated: 2024-09-12T01:27:14.919Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Memory Matters: Quick Ways to Check Your PC's RAM on Windows"
excerpt: "This Article Describes Memory Matters: Quick Ways to Check Your PC's RAM on Windows"
keywords: PC RAM Check,RAM Verification,Windows RAM Test,Quick RAM Status,Memory Diagnostics,RAM Health Check,RAM Monitoring Windows
thumbnail: https://thmb.techidaily.com/4ddb75c55f41c22a4f3ada299a0f1a1093c8ca9e10e43f8a8e61a1ff732d1283.jpg
---

## Memory Matters: Quick Ways to Check Your PC's RAM on Windows

 Knowing the type of RAM installed on your Windows PC can help you make more informed decisions when upgrading or diagnosing performance issues. Thankfully, it’s possible to check the RAM type on your Windows PC without opening the computer case and getting your hands dirty.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>







<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134489/18498" target="_top" id="2134489">
  <img src="//a.impactradius-go.com/display-ad/18498-2134489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134489/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 1\. How to Check the RAM Type With Command Prompt

 The most straightforward to check the RAM type on your Windows PC is via Command Prompt. You can use this method even [if you're a beginner with the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/), as it only requires you to run a single command.

 Here's how you can check the RAM type on Windows using the Command Prompt:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the menu that appears.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. In the console, type the command mentioned below and press **Enter**.  
`wmic memorychip get devicelocator, memorytype`
4. Note down the code number under the **MemoryType** column.  
![Check Memory Type Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-command-prompt.jpg)

 Compare the numerical value from the **MemoryType** column with the following table to identify the RAM type. For instance, if the code number is **24**, it means your computer has **DDR3** RAM.

![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)





<!-- affiliate ads begin -->
<span id="1498635">
					<video width="320" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1498635.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17326-1498635">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1498635.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:200px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fancheer.sjv.io%2Fc%2F5597632%2F1498635%2F17326'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1498635/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 2\. How to Check the RAM Type With PowerShell

 Like Command Prompt, you can use PowerShell to find out the type of RAM installed on your Windows computer. Here are the steps for the same.

1. Press **Win + S** to open the search menu.
2. Type **powershell** in the box.
3. Select **Run as administrator**.
4. When the User Account Control (UAC) prompt appears, select **Yes** to continue.
5. Type the following command in the PowerShell window and hit **Enter**.  
`Get-CimInstance -ClassName Win32_PhysicalMemory | Format-Table SMBIOSMemoryType`  
![Check RAM Type Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-ram-type-using-powershell.jpg)

 Under the **SMBIOSMemoryType** column, note down the code number and compare it with the following table to determine the RAM type.

![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134491/18498" target="_top" id="2134491">
  <img src="//a.impactradius-go.com/display-ad/18498-2134491" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134491/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 3\. How to Check the RAM Type Using the Task Manager App

 Windows Task Manager can provide you with all the necessary hardware information you need about your PC, including the type of RAM installed. However, it's important to note that Task Manager does not show the memory type if your PC has [DDR4 or DDR5 RAM](https://www.makeuseof.com/ddr4-vs-ddr5-should-you-upgrade/). So, this method will only work for PCs with DDR3 or lower-generation RAM.

 To check the RAM type using Windows Task Manager, follow these steps:

1. Press **Ctrl + Shift + Esc** to open the Task Manager.
2. Switch to the **Performance** tab.
3. Select **Memory** from the left pane. You should see the amount and type of RAM your PC has in the top right corner of the screen.  
![Check Memory Type Using Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-windows-task-manager.jpg)





<!-- affiliate ads begin -->
<span id="2127886">
					<video width="576" height="1024" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2127886.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2127886">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2127886.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2127886%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2127886/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 The Windows Task Manager does more than show hardware information. You also use it to manage running programs, end tasks, and view resource usage. To learn more, read our guide on the best [Windows Task Manager tips that you may not know](https://www.makeuseof.com/tag/10-windows-task-manager-tricks-didnt-know/).





<!-- affiliate ads begin -->
<span id="1444782">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1444782.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1444782">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1444782.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1444782%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1444782/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 4\. How to Check the RAM Type Using CPU-Z

 If you're seeking a relatively uncomplicated method to check the RAM type along with other hardware details, you can use a third-party app like CPU-Z. It is available for free and allows you to access various sets of information about your computer, including details about both the CPU and the RAM.

 Download and open the [CPU-Z](https://www.cpuid.com/softwares/cpu-z.html) app on your PC. Click on the **Memory** tab to get a detailed breakdown of the installed RAM. Under the **General** section, look for the value in the **Type** field to know the type of RAM installed on your PC.

![Check Memory Type Using CPU-Z App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-cpu-z-app.jpg)





<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134502/19576" target="_top" id="2134502">
  <img src="//a.impactradius-go.com/display-ad/19576-2134502" border="0" alt="https://techidaily.com" width="672" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134502/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Know the Type of RAM Installed on Your Windows PC

 The performance of your computer is affected not only by the amount of RAM installed but also by the type of RAM. Fortunately, identifying the RAM type on your Windows PC is a quick and painless process with the methods mentioned above.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-actors-insight-crafting-engaging-online-reactions-on-youtube-3-pro-tips/"><u>[New] 2024 Approved Actor's Insight Crafting Engaging Online Reactions on YouTube (3 Pro Tips)</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-guide-to-prime-church-livestreaming-services-for-2024/"><u>[New] Guide to Prime Church Livestreaming Services for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-navigating-the-seas-of-sponsorships-a-youtubers-playbook/"><u>[New] In 2024, Navigating the Seas of Sponsorships A Youtuber's Playbook</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-overcoming-screen-blackouts-in-recording-tools/"><u>[New] In 2024, Overcoming Screen Blackouts in Recording Tools</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-rise-to-success-with-these-essential-15-fb-sales-insights/"><u>[New] In 2024, Rise to Success with These Essential 15 FB Sales Insights</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-unlocking-xboxs-video-call-potential-with-zoom/"><u>[Updated] 2024 Approved Unlocking Xbox's Video Call Potential with Zoom</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-secure-and-ethical-methods-for-capturing-chat-calls/"><u>[Updated] In 2024, Secure and Ethical Methods for Capturing Chat Calls</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-synchronized-singing-in-a-single-take/"><u>[Updated] Synchronized Singing in a Single Take</u></a></li>
<li><a href="https://fake-location.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-vivo-x-flip-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Vivo X Flip | Dr.fone</u></a></li>
<li><a href="https://buynow-help.techidaily.com/beginners-guide-to-staying-active-how-nintendo-systems-make-exercise-fun-and-accessible/"><u>Beginner's Guide to Staying Active: How Nintendo Systems Make Exercise Fun and Accessible</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparable-digital-painting-and-sketching-for-pc-users/"><u>Comparable Digital Painting & Sketching for PC Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-through-windows-11s-sticky-note-barrier/"><u>Cutting Through Windows 11'S Sticky Note Barrier</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-the-red-x-meaning-in-file-organization/"><u>Dissecting the Red “X” Meaning in File Organization</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-to-vivo-y56-5g-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Vivo Y56 5G FRP Bypass With Best Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-protection-five-changes-to-the-windows-firewall/"><u>Enhance Protection: Five Changes to the Windows Firewall</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-geforce-experience-failure-in-windows-11-and-11-systems/"><u>Fixing GeForce Experience Failure in Windows 11 & 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-fix-required-parts-not-found-error-in-win11/"><u>Guide to Fix Required Parts Not Found Error in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-copy-and-paste-in-application-guard-for-edge-in-windows-11/"><u>How to Enable Copy and Paste in Application Guard for Edge in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-modify-file-permissions-in-windows/"><u>How to Modify File Permissions in Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-your-motorola-moto-g24-lock-screen-password-by-drfone-android/"><u>How to Reset your Motorola Moto G24 Lock Screen Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-system-limits-on-pc/"><u>Identifying System Limits on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-fixes-to-stranded-error-on-windows-1011-xbox-app/"><u>Immediate Fixes to 'Stranded' Error on Windows 10/11 Xbox App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-frequent-wallpaper-alterations-in-windows/"><u>Implementing Frequent Wallpaper Alterations in Windows</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-live-viewers-choice-obs-or-shadowtoolkit/"><u>In 2024, Live Viewers' Choice OBS or ShadowToolkit</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Google Pixel 8 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterclass-in-security-crafting-original-patterns-for-windows-users/"><u>Masterclass in Security: Crafting Original Patterns for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-space-available-for-pin-listings/"><u>Maximizing Space Available for Pin Listings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-disconnected-remotes-in-windows-operating-system/"><u>Mending Disconnected Remotes in Windows Operating System</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-troubleshooting-speed-mastering-sound-integration-in-adobe-premiere-pro/"><u>New 2024 Approved Troubleshooting Speed Mastering Sound Integration in Adobe Premiere Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimal-tools-for-notetakers-and-pc-slates-alike/"><u>Optimal Tools for Notetakers & PC Slates Alike</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-workflows-nircmds-win-shortcut-guide/"><u>Simplified Workflows: NirCmd's Win Shortcut Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-windows-with-wintoys-your-quick-reference-manual/"><u>Simplifying Windows With WinToys: Your Quick Reference Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snip-and-save-malfunction-resolve-it-with-ease/"><u>Snip-and-Save Malfunction? Resolve It with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepping-up-security-edges-camera-and-mic-guidance/"><u>Stepping Up Security: Edge's Camera & Mic Guidance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-tackle-xbox-game-pass-failures-in-windows/"><u>Strategies to Tackle Xbox Game Pass Failures in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/success-strategies-fixing-driver-not-supported-issue-in-win11/"><u>Success Strategies: Fixing Driver Not Supported Issue in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-ready-your-pc-with-these-startup-speedups-on-win11/"><u>Swiftly Ready Your PC with These Startup Speedups on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-everyday-scenes-to-dynamic-windows-wallpaper/"><u>Turn Everyday Scenes to Dynamic Windows Wallpaper</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-create-epic-music-videos-with-these-10-top-rated-tools/"><u>Updated Create Epic Music Videos with These 10 Top-Rated Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-fix-eradicating-the-0x80246007-update-hurdle/"><u>Win11 Fix: Eradicating the 0X80246007 Update Hurdle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-file-fixes-erase-temp-files-effortlessly/"><u>Windows File Fixes: Erase Temp Files Effortlessly</u></a></li>
</ul></div>







<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    