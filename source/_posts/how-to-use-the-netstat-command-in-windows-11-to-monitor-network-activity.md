---
title: How to Use the Netstat Command in Windows 11 to Monitor Network Activity
date: 2024-08-16T02:47:52.726Z
updated: 2024-08-17T02:47:52.726Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Use the Netstat Command in Windows 11 to Monitor Network Activity
excerpt: This Article Describes How to Use the Netstat Command in Windows 11 to Monitor Network Activity
keywords: Netstat Windows 11,Network Activity Monitoring,Using Netstat Commands,Windows Netstat Usage,Tracking Connections Windows,Monitoring PC Networks,IP Address Listing Command
thumbnail: https://thmb.techidaily.com/f3b5fbbb41ff3e0e15766362f9082ba5609c00b8437978e5e3317dc5d76ea72c.jpg
---

## How to Use the Netstat Command in Windows 11 to Monitor Network Activity

 Netstat is a command-line utility that helps you monitor all the technical properties of your active network connections. It provides a quick way to see all your open ports, active connections, and network services running on your system.

 If all this sounds too technical to you, don't worry; we'll explain everything simply as you read further in the article. First, let's take a look at what netstat is and how to use netstat on Windows to monitor your network.

## What is the Netstat Command on Windows?

 The netstat command is mainly used by IT experts or network troubleshooters on Windows and Linux systems. The command, when executed, displays a list of the active TCP connections, ports that are listening, Ethernet statistics, addresses and ports being used by your system, and more.

 In simple terms, this command lets you see what network connections are active and what applications are using them in the background at any given time.

 To give you clarity, below are some examples of what netstat can show you:

* All inbound and outbound connections are on your PC.
* Information about which ports are open or listening for connections.
* Connections and processes using the internet.
* Any suspicious connections from unknown applications or services.

## How to Use the Netstat Command on Windows

 As mentioned before, the netstat command is accessible only from the Command Prompt. If you don't know the steps, follow the ones given below to run netstat from the Command Prompt:

1. Click on the **Search** button on your taskbar and search for the **Command Prompt** app.
2. Next to the matching search result, click on **Run as administrator**. This will launch Command Prompt with advanced-user permissions.  
![Command Prompt In Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/command-prompt-in-windows-search.jpg)
<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. On the Command Prompt, type **netstat** and press **Enter**. The command, after executing, will output a list of active connections along with their status.  
![netstat Command Output](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netstat-command-output.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
4. If you need to share the output with a tech support team, for example, use this command to copy the results in a text file: "**netstat > Path\\FileName.txt**". In this command, **Path** is any folder's location where you want to save the file and **FileName.txt** is your exported file's name.  
![netstat Output Export Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netstat-output-export-command-1.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The highlighting part of netstat is that you can further use it with some parameters (or syntaxes) to filter the generated output. We'll show you some useful parameters that you can use with the "**netstat -parameter**" format in the next section.

 If you're eager to learn more about other such commands, check our list of useful [Windows commands to manage your network](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
## Useful Netstat Parameters for Windows Users

 In layman's terms, parameters mean some symbols or alphabets that allow you to modify what the netstat command displays. When you use a parameter with the "netstat -parameter" format, it helps you view detailed information about the traffic and different connections on a local area network.

 Let's look at some useful netstat parameters to receive more specific and filtered information from netstat:

* **netstat -a:** It displays all the running TCP and UDP connections and the listening ports. If there are any failed connection attempts, they will be displayed here too. Besides the **\-a** parameter, check the other [alternative ways to check open TCP ports](https://www.makeuseof.com/check-open-tcpip-ports-windows/).  
![netstat -a Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netstat-a-command.jpg)
* **netstat -b:** The **\-b** parameter displays the executable (.EXE) involved in creating each connection or listening port. It is mainly useful for those who deal with network troubleshooting in a Windows server or a computer part of a domain.  
![netstat -b Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netstat-b-command.jpg)
* **netstat -e:** If you use an Ethernet connection rather than Wi-Fi, the **\-e** parameter can show you detailed Ethernet statistics, like link speed, total send/receive bytes, and some other technical statistics.  
![netstat -e Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netstat-e-command.jpg)
* **netstat -o:** Suppose you installed an application (from an untrusted website), in that case, you can check whether the application is doing something suspicious with the connection or not. This is because the **\-o** parameter shows the Process ID (PID) of every connection that you can match from the Task Manager.  
![netstat -o Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netstat-o-command.jpg)
* **netstat -s:** This shows statistics by a protocol like packets sent/received, errors, discarded packets, etc. It's useful if you want to understand per-protocol-based bandwidth usage.  
![netstat -s Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netstat-s-command.jpg)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->

 Now that you have an idea of some useful commands, try running them in the Command Prompt. Note that we recommend running Command Prompt as an administrator only as some connections are only visible with admin privileges.

 If you don't like to enter the commands repeatedly, combine the parameters. For example, **netstat -e -s** will show you your Ethernet network details along with the per-protocol-based bandwidth usage in one view.

 Above all, netstat is just one command for troubleshooting. If you're interested, check the [Windows network connections tool](https://www.makeuseof.com/windows-open-network-connections-tool/) to learn about another handy tool.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## Troubleshooting Your Networks Made Easy With Netstat

 Unlike utilities you need to download separately, netstat is ready to use in Command Prompt on all Windows versions. This makes it the go-to tool for getting a snapshot of network status right from your PC.

 Additionally, from checking incoming and outgoing connections to sniffing out potential malicious activities, you can use it easily even if you're not a professional network expert.

 If all this sounds too technical to you, don't worry; we'll explain everything simply as you read further in the article. First, let's take a look at what netstat is and how to use netstat on Windows to monitor your network.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-pro-film-quality-the-seven-top-cameras-for-action/"><u>[New] 2024 Approved  Pro Film Quality  The Seven Top Cameras for Action</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-the-essential-guide-to-capturing-skype-conversations-on-windowsmac/"><u>[New] In 2024, The Essential Guide to Capturing Skype Conversations on Windows/Mac</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-masterclasses-in-livestreaming-and-recording-sport-views/"><u>[New] Masterclasses in Livestreaming and Recording Sport Views</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-unlocking-the-secrets-of-instagrams-video-capsule-for-2024/"><u>[New] Unlocking the Secrets of Instagram's Video Capsule for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-mastering-pip-features-on-ms-edge/"><u>2024 Approved  Mastering PIP Features on MS Edge</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-velocity-for-the-visionary-quick-frame-android-tools/"><u>2024 Approved  Velocity for the Visionary  Quick-Frame Android Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-cool-folder-tips-youll-love-using-on-windows/"><u>5 Cool Folder Tips You'll Love Using on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-walkthrough-to-establish-java-development-kit-in-windows-11/"><u>A Complete Walkthrough to Establish Java Development Kit in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-disabling-chrome-tab-clones/"><u>A Step-by-Step Approach to Disabling Chrome Tab Clones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-using-the-mspcm-bar-tools-windows-11-style/"><u>A Step-by-Step Guide to Using the MSPCM Bar Tools, Windows 11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-tale-of-time-the-windows-taskbar-saga-19852023/"><u>A Tale of Time: The Windows Taskbar Saga (1985–2023)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-system-insights-step-by-step/"><u>Accessing Windows System Insights Step-by-Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-oculus-quest-2-for-windows-vr-software/"><u>Adapting Oculus Quest 2 for Windows VR Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-fatal-wow-bug-on-latest-windows-11-version/"><u>Addressing Fatal WoW Bug on Latest Windows 11 Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-hello-compatible-scanner-glitch/"><u>Addressing Windows Hello Compatible Scanner Glitch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-in-depth-look-at-windows-cab-and-its-functionality/"><u>An In-Depth Look at Windows CAB and Its Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-insight-into-runtime-brokers-role-on-your-machine/"><u>An Insight Into Runtime Broker's Role on Your Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-common-fails-keeping-your-temp-folder-valid-in-win11/"><u>Avoiding Common Fails: Keeping Your Temp Folder Valid in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-steam-authentication-setbacks-in-rust-for-windows-users/"><u>Avoiding Steam Authentication Setbacks in Rust for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-windows-store-crash-code-error-0x80072efd/"><u>Banishing Windows Store Crash Code: Error 0X80072EFD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/batch-heic-image-transformation-into-jpeg-using-w11-features/"><u>Batch Heic Image Transformation Into JPEG Using W11 Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginner-friendly-guide-setting-up-the-jdk-on-windows-11/"><u>Beginner-Friendly Guide: Setting Up the JDK on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beneath-the-facade-programs-pause-your-pcs-prowess/"><u>Beneath the Facade, Programs Pause Your PC's Prowess</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-efficiency-activating-search-bar-on-windows-11-tm/"><u>Boost Your Efficiency: Activating Search Bar on Windows 11 TM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-productivity-with-windows-command-shortcuts/"><u>Boost Your Productivity with Windows Command Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-task-handling-a-guide-to-windows-11-mastery/"><u>Boosting Task Handling - A Guide to Windows 11 Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719306648168-fix-your-windows-onedrive-hurdles-now/"><u>Fix Your Windows OneDrive Hurdles Now!</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-infinix-smart-8-pro-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Infinix Smart 8 Pro | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-the-newest-nvidia-quadro-graphics-drivers-for-your-windows-10-system/"><u>Get the Newest Nvidia Quadro Graphics Drivers for Your Windows 10 System</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-call-logs-from-nokia-150-2023-by-fonelab-android-recover-call-logs/"><u>How to rescue lost call logs from Nokia 150 (2023)</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/smooth-steam-gaming-recordings-guide-for-2024/"><u>Smooth Steam Gaming Recordings Guide for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>