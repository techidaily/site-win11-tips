---
title: 3 Ways to Check for Open TCP/IP Ports on Windows
date: 2024-08-16T01:41:17.657Z
updated: 2024-08-17T01:41:17.657Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 3 Ways to Check for Open TCP/IP Ports on Windows
excerpt: This Article Describes 3 Ways to Check for Open TCP/IP Ports on Windows
keywords: Windows TCP/IP Port Check,Security Windows Port Scan,Open TCP Ports Detection,Windows IP Connectivity Test,Identify Windows Network Leaks,Detect Unsecured TCP Windows,Windows Port Vulnerability Spot
thumbnail: https://thmb.techidaily.com/b0e0b3709f1348652118c2459af9389796059e0f6579c4e1ae20b05da950739b.jpg
---

## 3 Ways to Check for Open TCP/IP Ports on Windows

 Sometimes it's worth finding out which TCP/IP ports are open on your device. For example, let’s say your device is communicating with another PC, but the connection suddenly gets interrupted. In this case, you can check all the open TCP/IP ports. From there, you could try to resolve the issue at hand by troubleshooting any faulty port.

 This article covers the various ways to check active TCP/IP ports on Windows. But first, let’s find out how these ports work.

## What Are TCP/IP Ports, and How Do They Work?

![An illustration of questions and answers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/An-illustration-of-questions-and-answers.jpg)

 Let’s break down the “TCP/IP” term and explain what it means.

 TCP (Transmission Control Protocol) refers to a connection-oriented protocol. And in simple terms, protocols are the rules that determine how data is transferred between devices.

 Meanwhile, the "IP" (Internet Protocol) part refers to the internet protocol address. This is a unique value assigned to a network device, and it’s used to identify that particular device.

 Now, TCP/IP ports are simply the ports that ensure that all the data you send reaches its recipient. These ports ensure that internet-connected devices can communicate with each other. Some examples of TCP/IP ports include the IMAP port (143) for emails and the File Transfer Protocol ports (20 and 21).

 Let's now explore the various ways to check active TCP/IP ports.

## 1\. Check the Open TCP/IP Ports and Their Process Names Using the Command Prompt
![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Check the Open TCP/IP Ports and the Process Identifiers Using the Command Prompt
![Person using a Windows PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/Person-using-a-Windows-PC.jpg)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In some instances, you might want to check out the TCP/IP ports along with their Process Identifiers (the unique numbers that identify processes). This method could be useful if you can’t find the process names using the previous method.

 When you’re done [searching for the Process Identifier (PID) on Windows](https://www.makeuseof.com/ways-to-find-application-process-id-in-windows-10/), you can check out the task name linked to the PID in the Task Manager.

 Let’s start by checking out how to check the open TCP/IP ports and their PIDs:

1. Press **Win + R** to open the Run command dialog box.
2. Type **CMD** and press **Ctrl + Shift + Enter** to open an elevated Command Prompt.
3. Type the following command and press **Enter**.

netstat -aon

 Your screen should display five columns: **Proto, Local Address, Foreign Address, State,** and **PID**.

![Checking TCP-IP ports and process identifiers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/checking-tcp-ip-ports-and-process-identifiers.jpg)
<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you've found the PID of a certain port, here’s how you can use the Task Manager to find the task linked to that PID:

1. Type **Task Manager** in the Start menu search bar and select the **Best match**.
2. Navigate to the **Details** tab.
3. Look for your PID value in the **PID section** and locate the task name from the results on the left.

![Checking the PID value and task name on the Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/checking-the-pid-value-and-task-name-on-the-task-manager.jpg)

## 3\. Check Which TCP/IP Ports Are Open Using Third-Party Apps

 If you’re a fan of third-party apps, here are some tools that can help you check active TCP/IP ports on your device.

### TCPView
![The TCPView Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-tcpview-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The TCPView app shows a detailed list of all the [TCP and UDP (User Datagram Protocol) ports](https://www.makeuseof.com/what-are-tcp-and-udp-ports/). It also shows you the Process Name, Process IDs (PIDs), the Local Address, the Remote Address, the Local Port, the Remote Port, and more.

 You can customize the TCPView screen by clicking the **View** tab and selecting the relevant option.

 If you’d like to change the window to dark mode, head to the **Options** tab, select **Theme**, and then pick the **Dark** option. You can also tweak other settings (such as changing the font size) on the Options tab.

 And if you’d like to close one of the processes on the screen, select the process in question, click the **Process** tab, and then select the **Kill…** option.

 If you want to edit a process, click on the process in question, click the **Edit** tab, and then select the relevant option. And if you need some assistance, head to the **Help** tab.

**Download**: TCPView for [Windows](https://learn.microsoft.com/en-us/sysinternals/downloads/tcpview) (Free)

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-epic-martial-arts-arcade-classics-revisited/"><u>[New] 2024 Approved  Epic Martial Arts Arcade Classics Revisited</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-ace-the-game-crafting-a-pro-gaming-channels-success-story-for-2024/"><u>[New] Ace the Game  Crafting a Pro Gaming Channels Success Story for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-from-casual-to-expert-your-path-with-obs-gaming-capture/"><u>[New] From Casual to Expert  Your Path with OBS Gaming Capture</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-how-to-turn-off-youtube-video-preview-all-platform-solution/"><u>[New] How to Turn Off YouTube Video Preview? [All Platform Solution]</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-navigating-towards-excellent-free-photography-choices/"><u>[New] Navigating Towards Excellent Free Photography Choices</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-inside-look-obs-as-a-premier-screen-recorder/"><u>[Updated] In 2024, Inside Look  OBS as a Premier Screen Recorder</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-on-screen-recording-assistant-for-2024/"><u>[Updated] On-Screen Recording Assistant for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-lava-blaze-curve-5g-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Lava Blaze Curve 5G to Roku | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-deals-bf-black-friday-612-win10-for-life/"><u>Best Deals: BF Black Friday - $6.12 Win10 for Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/browsing-lightly-identifying-minimal-resource-using-software-across-windowsmacoschromeos/"><u>Browsing Lightly: Identifying Minimal Resource-Using Software Across Windows/macOS/ChromeOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chrome-opening-woes-resolved-fast-fixed-for-windows-11-users/"><u>Chrome Opening Woes Resolved: Fast Fixed for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crucial-software-aid-the-best-windows-apps-that-facilitate-mac-switch/"><u>Crucial Software Aid: The Best Windows Apps That Facilitate MAC Switch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-dissolving-ms-teams-error-80080300-on-win11-platform/"><u>Deciphering and Dissolving MS Teams Error 80080300 on Win11 Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-folder-management-resetting-critical-components-on-ws11/"><u>Effortless Folder Management: Resetting Critical Components on WS11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-internal-rdp-problems-on-windows-os/"><u>Eliminating Internal RDP Problems on Windows OS</u></a></li>
<li><a href="https://tech-hub.techidaily.com/envisioning-virtual-vigilance-projected-trends-in-security/"><u>Envisioning Virtual Vigilance: Projected Trends in Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-iomap64-syscall-failures-on-windows-pcs/"><u>Essential Fixes for IOMap64 Syscall Failures on Windows PCs</u></a></li>
<li><a href="https://fox-that.techidaily.com/experiencing-facetime-problems-here-are-15-remedies-to-restore-connection/"><u>Experiencing FaceTime Problems? Here Are 15 Remedies to Restore Connection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harmonize-window-11-settings-for-clear-prime-video-texts/"><u>Harmonize Window 11 Settings for Clear Prime Video Texts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-bypass-win11s-alarming-zero-error-alerts/"><u>How to Bypass Win11’s Alarming Zero Error Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-microsoft-edges-from-popping-up/"><u>How to Stop Microsoft Edges From Popping Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-actions-for-local-security-not-functioning-warning/"><u>Immediate Actions for 'Local Security Not Functioning' Warning</u></a></li>
<li><a href="https://extra-hints.techidaily.com/impressive-array-of-mobile-text-options/"><u>Impressive Array of Mobile Text Options</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-apple-iphone-xs-drfone-by-drfone-virtual-ios/"><u>In 2024, Complete Tutorial to Use GPS Joystick to Fake GPS Location On Apple iPhone XS | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-xiaomi-redmi-note-12-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Xiaomi Redmi Note 12 4G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insight-into-the-workings-of-windows-odbc-tools/"><u>Insight Into the Workings of Windows ODBC Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-books-8-effective-studying-tips-on-windows/"><u>Mastering the Books: 8 Effective Studying Tips on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-utorrent-install-issues-on-a-windows-laptop/"><u>Navigating uTorrent Install Issues on a Windows Laptop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-to-record-windows-uac-notifications/"><u>Quick Steps to Record Windows UAC Notifications</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/remove-device-supervision-from-your-iphone-xr-drfone-by-drfone-ios/"><u>Remove Device Supervision From your iPhone XR | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snip-and-sketch-vs-prtsc-which-screen-capture-wins/"><u>Snip & Sketch Vs. PrtSc: Which Screen Capture Wins?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-windows-administrator-security-configs/"><u>Steps to Tackle Windows Administrator Security Configs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-removing-signature-rejection-on-pcs/"><u>Strategies for Removing Signature Rejection on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-savvy-tips-restarting-windows-11-apps/"><u>Tech Savvy Tips: Restarting Windows 11 Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-shutdown-playbook-avoiding-windows-11-activities/"><u>The Shutdown Playbook: Avoiding Windows 11 Activities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-notepads-display-from-light-to-dark-theme-win-11/"><u>Transitioning Notepad's Display From Light to Dark Theme (Win 11)</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshooting-steps-when-dota-2-wont-load-past-initial-screen/"><u>Troubleshooting Steps When Dota 2 Won't Load Past Initial Screen</u></a></li>
<li><a href="https://extra-information.techidaily.com/ultimate-selection-of-cameras-for-film-production/"><u>Ultimate Selection of Cameras for Film Production</u></a></li>
</ul></div>
