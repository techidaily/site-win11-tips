---
title: TCP Port Identification on Windows Devices
date: 2024-08-28T01:20:07.191Z
updated: 2024-08-29T01:20:07.191Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes TCP Port Identification on Windows Devices
excerpt: This Article Describes TCP Port Identification on Windows Devices
keywords: Windows TCP PORTS,Device Port Identify,Windows OS Networking,Identifying Windows Ports,Windows Network Ports,OS Tech,Pinpoint Windows NetP
thumbnail: https://thmb.techidaily.com/8e153531bfb1cc2249d2aa88119afd6c59e7a577b57f16e2feb19e964db9e9c8.jpg
---

## TCP Port Identification on Windows Devices

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## 2\. Check the Open TCP/IP Ports and the Process Identifiers Using the Command Prompt

![Person using a Windows PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/Person-using-a-Windows-PC.jpg)

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
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

 Once you've found the PID of a certain port, here’s how you can use the Task Manager to find the task linked to that PID:

1. Type **Task Manager** in the Start menu search bar and select the **Best match**.
2. Navigate to the **Details** tab.
3. Look for your PID value in the **PID section** and locate the task name from the results on the left.

![Checking the PID value and task name on the Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/checking-the-pid-value-and-task-name-on-the-task-manager.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
## 3\. Check Which TCP/IP Ports Are Open Using Third-Party Apps

 If you’re a fan of third-party apps, here are some tools that can help you check active TCP/IP ports on your device.

### TCPView

![The TCPView Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-tcpview-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The TCPView app shows a detailed list of all the [TCP and UDP (User Datagram Protocol) ports](https://www.makeuseof.com/what-are-tcp-and-udp-ports/). It also shows you the Process Name, Process IDs (PIDs), the Local Address, the Remote Address, the Local Port, the Remote Port, and more.

 You can customize the TCPView screen by clicking the **View** tab and selecting the relevant option.

 If you’d like to change the window to dark mode, head to the **Options** tab, select **Theme**, and then pick the **Dark** option. You can also tweak other settings (such as changing the font size) on the Options tab.

 And if you’d like to close one of the processes on the screen, select the process in question, click the **Process** tab, and then select the **Kill…** option.

 If you want to edit a process, click on the process in question, click the **Edit** tab, and then select the relevant option. And if you need some assistance, head to the **Help** tab.

**Download**: TCPView for [Windows](https://learn.microsoft.com/en-us/sysinternals/downloads/tcpview) (Free)

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
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

### TCP Monitor Plus

![The TCP Monitor Plus Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-tcp-monitor-plus-tool.jpg)

 TCP Monitor Plus comprises 11 tabs that you can use for various purposes. But in this case, we’ll focus on the Session Monitor tab because that’s where the TCP/IP information is located.

 Once you’re on the Session Monitor tab, you should see various sections containing information about the TCP/IP ports. The "Status" tab tells you whether the ports are open or connecting. The other tabs display information such as the IP address, hostname, process name, and more.

 If you want to make changes to a specific port, right-click on it and select a relevant option.

**Download**: TCP Monitor Plus for [Windows](https://www.softpedia.com/get/Network-Tools/Network-Monitoring/TCP-Monitor-Plus.shtml) (Free)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-footage.techidaily.com/new-binge-watch-with-ease-best-playlist-extractors-reviewed-and-rated-for-2024/"><u>[New] Binge-Watch With Ease  Best Playlist Extractors Reviewed & Rated for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-extracting-images-from-videos-in-windows-11-photos/"><u>[New] Extracting Images From Videos in Windows 11 Photos</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-core-techniques-for-capturing-smartphone-content/"><u>[Updated] Core Techniques for Capturing Smartphone Content</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-interactive-presenters-synopsis-update-8/"><u>[Updated] In 2024, Interactive Presenter's Synopsis, Update 8</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-transform-your-stream-embrace-obs-for-youtube-and-twitch/"><u>[Updated] In 2024, Transform Your Stream  Embrace OBS for YouTube & Twitch</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-samsung-galaxy-a34-5g-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Samsung Galaxy A34 5G without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/ascend-your-earning-game-executing-a-three-part-blueprint-for-youtube-revenue-analysis/"><u>Ascend Your Earning Game  Executing a Three-Part Blueprint for YouTube Revenue Analysis</u></a></li>
<li><a href="https://fox-helps.techidaily.com/bikes-viewing-experience-5050-of-the-ultimate-helmet-cam-tech/"><u>Bike's Viewing Experience - 50/50 of the Ultimate Helmet Cam Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clandestine-file-storage-win11s-image-encryption-tricks/"><u>Clandestine File Storage: Win11's Image Encryption Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-access-blocked-steam-game-messages/"><u>Clearing Up Access Blocked Steam Game Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-security-turn-on-controlled-folder-access-in-windows-11/"><u>Command Security: Turn on Controlled Folder Access in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-tips-to-control-the-fn-key-functionality/"><u>Effective Tips to Control the Fn Key Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-windows-1011-ui-with-portable-apps-icons/"><u>Elevate Windows 10/11 UI with Portable Apps Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-hiccups-fixing-slow-playback-in-vlc/"><u>Eliminating Hiccups: Fixing Slow Playback in VLC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empowering-powershell-mastery-of-execution-policy-settings/"><u>Empowering PowerShell: Mastery of Execution Policy Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-insight-on-locating-windows-1110-product-key/"><u>Exclusive Insight on Locating Windows 11/10 Product Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-zero-to-dev-windows-11s-jdk-integration/"><u>From Zero to Dev: Windows 11'S JDK Integration</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-tecno-spark-20c-is-unlocked-by-drfone-android/"><u>How To Check if Your Tecno Spark 20C Is Unlocked</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-oneplus-nord-ce-3-5g-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide OnePlus Nord CE 3 5G Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-share-location-in-messenger-on-apple-iphone-14-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Share Location in Messenger On Apple iPhone 14 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-mastering-audio-streams-apple-podcasts-downloading/"><u>In 2024, Mastering Audio Streams  Apple Podcasts Downloading</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/maximize-performance-with-cooler-masters-breakthrough-in-thermal-management-aio-and-air-coolers-designed-to-handle-300wplus-heat-load/"><u>Maximize Performance with Cooler Master's Breakthrough in Thermal Management: AIO and Air Coolers Designed to Handle 300W+ Heat Load</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-directx-installation-hurdles/"><u>Mending DirectX Installation Hurdles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/monitoring-computer-power-a-windows-perspective/"><u>Monitoring Computer Power: A Windows Perspective</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-double-click-quickness-on-pc-three-key-settings/"><u>Optimize Double-Click Quickness on PC: Three Key Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-lags-streamlining-vlc-playback-speed/"><u>Overcoming Lags: Streamlining VLC Playback Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-adjusting-windows-locksleep-timer/"><u>Precision: Adjusting Windows Lock/Sleep Timer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-smoothly-sync-with-onedrive-even-when-failed-windows-11/"><u>Quick Guide to Smoothly Sync with OneDrive, Even When Failed (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-over-disabled-router-settings-on-windows/"><u>Regaining Control over Disabled Router Settings on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-disappearing-iconage-for-windows-apps/"><u>Restore Disappearing Iconage for Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-faulty-ports-the-windows-way-to-reclaim-usb-health/"><u>Restoring Faulty Ports - The Windows Way to Reclaim USB Health</u></a></li>
<li><a href="https://win11-tips.techidaily.com/set-windows-calculator-display-to-dark/"><u>Set Windows Calculator Display to Dark</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-inaccessible-file-permissions/"><u>Troubleshooting Windows' Inaccessible File Permissions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-wex-windows-exe-structure/"><u>Understanding WEX: Windows EXE Structure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-your-devices-full-internet-potential-in-windows-11/"><u>Unlock Your Device’s Full Internet Potential in Windows 11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/unlocking-full-potential-steam-and-your-switch-pro-controller-for-2024/"><u>Unlocking Full Potential  Steam and Your Switch Pro Controller for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-hidden-power-of-your-computers-windows-key/"><u>Unveiling the Hidden Power of Your Computer's Windows Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-are-windows-update-and-update-orchestrator-services/"><u>What Are Windows Update and Update Orchestrator Services?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-system-deciphering-ram-cache-dynamics/"><u>Windows System: Deciphering RAM Cache Dynamics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-terminal-innovative-color-design/"><u>Windows Terminal: Innovative Color Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wonderland-how-to-identify-your-computers-brand-and-model/"><u>Windows Wonderland: How To Identify Your Computer's Brand & Model</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winos-tricks-for-program-stability/"><u>WinOS Tricks for Program Stability</u></a></li>
</ul></div>
