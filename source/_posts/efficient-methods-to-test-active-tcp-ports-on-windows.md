---
title: Efficient Methods to Test Active TCP Ports on Windows
date: 2024-08-08T11:01:54.601Z
updated: 2024-08-09T11:01:54.601Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Efficient Methods to Test Active TCP Ports on Windows
excerpt: This Article Describes Efficient Methods to Test Active TCP Ports on Windows
keywords: Windows TCP Testing,Active Port Scanning,TCP Vulnerability Check,Win TCP Health Audit,Network Security Test,Active Connections Diagnostics,Port Analysis Tools
thumbnail: https://thmb.techidaily.com/8f59b16f9ed7024a23cc6f18f766904b6f418e4c5b8df6a84d93cf668a943550.jpg
---

## Efficient Methods to Test Active TCP Ports on Windows

 Sometimes it's worth finding out which TCP/IP ports are open on your device. For example, let’s say your device is communicating with another PC, but the connection suddenly gets interrupted. In this case, you can check all the open TCP/IP ports. From there, you could try to resolve the issue at hand by troubleshooting any faulty port.

 This article covers the various ways to check active TCP/IP ports on Windows. But first, let’s find out how these ports work.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
## What Are TCP/IP Ports, and How Do They Work?

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![An illustration of questions and answers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/An-illustration-of-questions-and-answers.jpg)

 Let’s break down the “TCP/IP” term and explain what it means.

 TCP (Transmission Control Protocol) refers to a connection-oriented protocol. And in simple terms, protocols are the rules that determine how data is transferred between devices.

 Meanwhile, the "IP" (Internet Protocol) part refers to the internet protocol address. This is a unique value assigned to a network device, and it’s used to identify that particular device.

 Now, TCP/IP ports are simply the ports that ensure that all the data you send reaches its recipient. These ports ensure that internet-connected devices can communicate with each other. Some examples of TCP/IP ports include the IMAP port (143) for emails and the File Transfer Protocol ports (20 and 21).

 Let's now explore the various ways to check active TCP/IP ports.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
## 1\. Check the Open TCP/IP Ports and Their Process Names Using the Command Prompt

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 When checking the TCP/IP ports that are open, you might also want to discover some additional information.

 For example, let’s say you want to check out active TCP/IP ports along with their process names. In such an instance, you can apply these methods:

1. Press **Win + R** to open the Run command dialog box.
2. Type **CMD** and press **Ctrl + Shift + Enter** to open an elevated Command Prompt.
3. Type the following command and press **Enter**.

netstat -ab

 The results will display four columns: **Proto, Local Address, Foreign Address,** and **State**.

![Checking the TCP-IP ports that are open](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/checking-the-tcp-ip-ports-that-are-open.jpg)

 The process names are the values displayed in square brackets below the port names.

 For example, you might see the “\[svchost.exe\]” process name under one of the TCP ports.

## 2\. Check the Open TCP/IP Ports and the Process Identifiers Using the Command Prompt

![Person using a Windows PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/Person-using-a-Windows-PC.jpg)

 In some instances, you might want to check out the TCP/IP ports along with their Process Identifiers (the unique numbers that identify processes). This method could be useful if you can’t find the process names using the previous method.

 When you’re done [searching for the Process Identifier (PID) on Windows](https://www.makeuseof.com/ways-to-find-application-process-id-in-windows-10/), you can check out the task name linked to the PID in the Task Manager.

 Let’s start by checking out how to check the open TCP/IP ports and their PIDs:

1. Press **Win + R** to open the Run command dialog box.
2. Type **CMD** and press **Ctrl + Shift + Enter** to open an elevated Command Prompt.
3. Type the following command and press **Enter**.

netstat -aon

 Your screen should display five columns: **Proto, Local Address, Foreign Address, State,** and **PID**.

![Checking TCP-IP ports and process identifiers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/checking-tcp-ip-ports-and-process-identifiers.jpg)

 Once you've found the PID of a certain port, here’s how you can use the Task Manager to find the task linked to that PID:

1. Type **Task Manager** in the Start menu search bar and select the **Best match**.
2. Navigate to the **Details** tab.
3. Look for your PID value in the **PID section** and locate the task name from the results on the left.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![Checking the PID value and task name on the Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/checking-the-pid-value-and-task-name-on-the-task-manager.jpg)

## 3\. Check Which TCP/IP Ports Are Open Using Third-Party Apps

 If you’re a fan of third-party apps, here are some tools that can help you check active TCP/IP ports on your device.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
### TCPView

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
![The TCPView Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-tcpview-tool.jpg)

 The TCPView app shows a detailed list of all the [TCP and UDP (User Datagram Protocol) ports](https://www.makeuseof.com/what-are-tcp-and-udp-ports/). It also shows you the Process Name, Process IDs (PIDs), the Local Address, the Remote Address, the Local Port, the Remote Port, and more.

 You can customize the TCPView screen by clicking the **View** tab and selecting the relevant option.

 If you’d like to change the window to dark mode, head to the **Options** tab, select **Theme**, and then pick the **Dark** option. You can also tweak other settings (such as changing the font size) on the Options tab.

 And if you’d like to close one of the processes on the screen, select the process in question, click the **Process** tab, and then select the **Kill…** option.

 If you want to edit a process, click on the process in question, click the **Edit** tab, and then select the relevant option. And if you need some assistance, head to the **Help** tab.

**Download**: TCPView for [Windows](https://learn.microsoft.com/en-us/sysinternals/downloads/tcpview) (Free)

### CurrPorts

![The CurrPorts Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-currports-tool.jpg)

 CurrPorts almost looks similar to TCPView, but it has a couple of additional tabs that display critical information. For example, this tool also shows you the Process Path (file path), the Product Name, the File Description, and the File Version (for apps).

 The tool displays all the open TCP/IP and UDP ports on your PC.

 If you want to close some ports, highlight them and then click the “close” icon. To filter your results, click the “filter” icon, select your filter, and then click **OK**.

 If you want to search for specific ports, click the “find” icon, type the name of the port, and then click **Find Next**.

 To edit your ports, navigate to the **Edit** tab and then select the relevant option.

 If you want to customize the CurrPorts tool, click the **View** tab and select the relevant option. And if you want to discover more customization features, head to the **Options** tab.

**Download**: CurrPorts for [Windows](https://www.nirsoft.net/utils/cports.html) (Free)

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### TCP Monitor Plus

![The TCP Monitor Plus Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-tcp-monitor-plus-tool.jpg)

 TCP Monitor Plus comprises 11 tabs that you can use for various purposes. But in this case, we’ll focus on the Session Monitor tab because that’s where the TCP/IP information is located.

 Once you’re on the Session Monitor tab, you should see various sections containing information about the TCP/IP ports. The "Status" tab tells you whether the ports are open or connecting. The other tabs display information such as the IP address, hostname, process name, and more.

 If you want to make changes to a specific port, right-click on it and select a relevant option.

**Download**: TCP Monitor Plus for [Windows](https://www.softpedia.com/get/Network-Tools/Network-Monitoring/TCP-Monitor-Plus.shtml) (Free)

## Finding All Your Active TCP/IP Ports Shouldn't Be Difficult

 Are you communicating with a remote computer but suddenly run into connection issues? Maybe the problem comes from TCP/IP ports. In this case, you can simply check which TCP/IP ports are open using the tips we’ve covered. From there, you can apply the relevant troubleshooting steps to fix the faulty port.

 And if you run into other problems while connecting to a remote device, check out some common remote desktop connection issues and their fixes.


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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-fullscape-synergy-the-smart-mcn-picking-game/"><u>[New] 2024 Approved  FullScape Synergy  The Smart MCN Picking Game</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-av1-vs-vp9-which-video-codec-wins/"><u>[New] AV1 Vs. VP9  Which Video Codec Wins?</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-digital-drama-videoviral-sagas-unfold-online/"><u>[New] In 2024, Digital Drama  #VideoViral Sagas Unfold Online</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-a-step-by-step-approach-to-editing-titles-and-descriptions-for-igtv/"><u>[Updated] 2024 Approved  A Step-by-Step Approach to Editing Titles and Descriptions for IGTV</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-unveiling-top-asmr-for-iphone-users/"><u>[Updated] 2024 Approved  Unveiling Top ASMR for iPhone Users</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-premium-tools-for-virtual-meeting-efficiency/"><u>[Updated] In 2024, Premium Tools for Virtual Meeting Efficiency</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-instant-improvement-in-visuals-the-canva-technique-for-borderless-images-for-2024/"><u>[Updated] Instant Improvement in Visuals  The Canva Technique for Borderless Images for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-lost-footage-immediate-removal-impacts/"><u>[Updated] Lost Footage  Immediate Removal Impacts</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-ultimate-3-fb-movie-extractors/"><u>[Updated] Ultimate 3 Fb Movie Extractors</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unleash-potential-our-picks-for-the-most-inspiring-films/"><u>[Updated] Unleash Potential  Our Picks for the Most Inspiring Films</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-no-spend-high-repeat-leading-apps-for-your-pinterest-vids/"><u>2024 Approved  No Spend, High Repeat! Leading Apps for Your Pinterest Vids</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-ultimate-handbook-for-vr-travelers/"><u>2024 Approved  The Ultimate Handbook for VR Travelers</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-unlock-your-potential-best-video-editing-hacks/"><u>2024 Approved  Unlock Your Potential  Best Video Editing Hacks</u></a></li>
<li><a href="https://facebook.techidaily.com/app-economics-how-twitter-tracks-users-for-zero-cost-access/"><u>App Economics: How Twitter Tracks Users for Zero Cost Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-practices-for-cleaning-up-the-icon-cache/"><u>Best Practices for Cleaning Up the Icon Cache</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combat-exception-interrupted-glitches-in-windows-systems/"><u>Combat 'Exception Interrupted' Glitches in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-the-ideal-placement-for-onedrive-on-windows-11/"><u>Crafting the Ideal Placement for OneDrive on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-out-the-webp-savings-in-google-chrome-for-windows/"><u>Cutting Out the WebP Savings in Google Chrome for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-batch-script-execution-power/"><u>Elevate Your Batch Script Execution Power</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-empty-directory-error-code-0x80070091-in-win11/"><u>Eliminating Empty Directory Error Code 0X80070091 in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-full-screen-freezes-in-sonic-on-w11/"><u>Eliminating Full-Screen Freezes in Sonic on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-inactive-push-notifications-for-outlook/"><u>Enabling Inactive Push Notifications for Outlook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-windows-defender-shield-unresponsiveness/"><u>Essential Fixes for Windows Defender Shield Unresponsiveness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-friendly-forecast-tools/"><u>Essential Windows-Friendly Forecast Tools</u></a></li>
<li><a href="https://hardware-help.techidaily.com/free-upgrade-to-latest-amd-radeon-hd-drivers-on-windows-8-systems/"><u>Free Upgrade to Latest AMD Radeon HD Drivers on Windows 8 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-sandbox-no-hypervisor-was-found-0xc0351000-error/"><u>How to Fix the Windows Sandbox No Hypervisor Was Found 0XC0351000 Error</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-dial-up-the-impact-with-50-free-branding-graphics/"><u>In 2024, Dial Up the Impact with 50 FREE Branding Graphics!</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-from-beginner-to-champion-essential-drone-races-tips-and-best-models/"><u>In 2024, From Beginner to Champion  Essential Drone Races Tips and Best Models</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-frostbound-feats-olympic-ice-innovations/"><u>In 2024, Frostbound Feats  Olympic Ice Innovations</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-global-communicators-guide-to-the-best-19-translation-apps/"><u>In 2024, The Global Communicator’s Guide to the Best 19 Translation Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructingdarkmodeonwindowsnotepad/"><u>InstructingDarkModeOnWindowsNotepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-a-toolbar-update-check-feature-into-windows-11plus11-interface/"><u>Integrating a Toolbar Update Check Feature Into Windows 11+11 Interface</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ipogo-will-be-the-new-ispoofer-on-honor-x9a-drfone-by-drfone-virtual-android/"><u>iPogo will be the new iSpoofer On Honor X9a? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-edge-always-active-on-windows-11-guide/"><u>Is Edge Always Active on Windows 11? Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-audio-cd-production-from-mp3-files-an-efficient-guide-to-using-imgburn-in-windows/"><u>Mastering Audio CD Production From MP3 Files: An Efficient Guide to Using ImgBurn in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-of-minimizing-cpu-load-on-computers/"><u>Mastery of Minimizing CPU Load on Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methodical-approach-fixing-nvidia-cp-error-in-ws1110/"><u>Methodical Approach: Fixing Nvidia CP Error in WS11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-dxgi-error-messages-windows-1011/"><u>Navigating Through DXGI Error Messages (Windows 10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/office-integration-a-concise-guide-to-windows-1011/"><u>Office Integration: A Concise Guide to Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x80070522-resolving-client-permissions-issue-on-windows-systems/"><u>Overcoming 0X80070522: Resolving Client Permissions Issue on Windows Systems</u></a></li>
<li><a href="https://fake-location.techidaily.com/prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Lava Blaze Curve 5G | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-oppo-reno-8t-5g-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Oppo Reno 8T 5G | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reliable-user-guide-to-fix-asus-rog-phone-7-ultimate-running-slow-and-freezing-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reliable User Guide to Fix Asus ROG Phone 7 Ultimate Running Slow and Freezing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-windows-updater-error-0xca00a009/"><u>Repairing Windows Updater Error #0xCA00A009</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-up-your-pc-mastering-the-art-of-program-minimization/"><u>Speed Up Your PC: Mastering the Art of Program Minimization</u></a></li>
<li><a href="https://driver-install.techidaily.com/steps-for-resolving-driver-setup-issues-in-windows/"><u>Steps for Resolving Driver Setup Issues in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-windows-11-transparent-taskbar-creation/"><u>Steps for Windows 11 Transparent Taskbar Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stronger-defense-through-longer-passcodes-windows-11-and-11-tips/"><u>Stronger Defense Through Longer Passcodes: Windows 11 and 11 Tips</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ring-thumbnail-lengths-for-youtube-audience-focus-for-2024/"><u>Tailoring Thumbnail Lengths for YouTube Audience Focus for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-needs-user-id-login-failures/"><u>Troubleshooting Windows Needs User ID Login Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultra-quick-turn-off-windows-11-dings/"><u>Ultra-Quick Turn Off Windows 11 Dings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719283991472-update-windows-11-ensure-your-system-is-up-to-date-for-any-built-in-improvements-and-fixes-regarding-display-settings/"><u>Update Windows 11: Ensure Your System Is up to Date for Any Built-In Improvements and Fixes Regarding Display Settings.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719233145490-win-plus-print-problem-heres-your-quick-windows-fix-guide/"><u>Win + Print Problem? Here's Your Quick Windows Fix Guide.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-app-usage-a-comprehensive-review/"><u>Window's App Usage: A Comprehensive Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-efficient-temperature-management-strategy/"><u>Windows' Efficient Temperature Management Strategy</u></a></li>
</ul></div>
