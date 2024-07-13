---
title: 3 Ways to Check for Open TCP/IP Ports on Windows
date: 2024-07-12T17:25:14.478Z
updated: 2024-07-13T17:25:14.478Z
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

![Checking the PID value and task name on the Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/checking-the-pid-value-and-task-name-on-the-task-manager.jpg)

## 3\. Check Which TCP/IP Ports Are Open Using Third-Party Apps

 If you’re a fan of third-party apps, here are some tools that can help you check active TCP/IP ports on your device.

### TCPView
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
<li><a href="https://win11-tips.techidaily.com/unleash-flawless-gameplay-combat-apex-legends-freezes/"><u>Unleash Flawless Gameplay: Combat Apex Legends Freezes</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-essential-screen-capture-tips-for-mi-11-users-for-2024/"><u>[New] Essential Screen Capture Tips for Mi 11 Users for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-calculator-crash-course-mastering-the-16x9-aspect-ratio-for-2024/"><u>New Calculator Crash Course Mastering the 16X9 Aspect Ratio for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/full-financial-forecast-the-podcast-inception-price-tag/"><u>Full Financial Forecast  The Podcast Inception Price Tag</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-explore-the-sonic-depiction-of-a-bell-peal/"><u>New 2024 Approved Explore the Sonic Depiction of a Bell Peal</u></a></li>
<li><a href="https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-infinix-hot-30i-drfone-by-drfone-virtual/"><u>How to Fake GPS on Android without Mock Location For your Infinix Hot 30i | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-excellence-in-emoji-creation-leading-discotools/"><u>2024 Approved  Excellence in Emoji Creation  Leading DiscoTools</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unveiling-the-best-storytelling-schools-1-8-guide/"><u>[New] Unveiling the Best Storytelling Schools - #1-#8 Guide</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-smooth-operator-3-techniques-to-steady-unstable-footage-in-ae/"><u>In 2024, Smooth Operator 3 Techniques to Steady Unstable Footage in AE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-asks-for-credentials-error-message/"><u>Bypassing Windows Asks for Credentials Error Message</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-controlling-sounds-on-windows-11/"><u>The Ultimate Guide to Controlling Sounds on Windows 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-top-12-stand-alone-screen-capture-apps/"><u>[New] In 2024, Top 12 Stand-Alone Screen Capture Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-when-and-how-to-leverage-ping-on-windows/"><u>Expert Advice: When and How to Leverage Ping on Windows</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-decoding-the-art-of-persuasive-tiktok-marketing-and-advertising/"><u>2024 Approved  Decoding the Art of Persuasive TikTok Marketing & Advertising</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-10-users-reasons-for-skipping-version-11/"><u>Windows 10 Users – Reasons for Skipping Version 11?</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-conquer-profits-on-the-go-youtube-studio-monetization-explained/"><u>In 2024, Conquer Profits On-the-Go  YouTube Studio Monetization Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-non-displayed-results-in-windows-11/"><u>Clearing Up Non-Displayed Results in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-win-11-taskbar-power/"><u>The Ultimate Guide to Win 11 Taskbar Power</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-direct-video-access-top-5-ways-to-transfer-igtv-content/"><u>[Updated] Direct Video Access  Top 5 Ways to Transfer IGTV Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-taskbar-with-win11-tips/"><u>Enhance Your Taskbar with Win11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-through-windows-marketplace-fails-error-0x80073cf3/"><u>Guiding Through Windows Marketplace Fails (Error 0X80073CF3)</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-vivo-y78plus-t1-edition-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Vivo Y78+ (T1) Edition Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/where-are-windows-photo-repositories/"><u>Where Are Window's Photo Repositories?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-mouse-gurus-autoclick-wonders-on-windows-pcs/"><u>Top 5 Mouse Gurus: Autoclick Wonders on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicate-scandisk-errors-for-a-smooth-run/"><u>Eradicate ScanDisk Errors for a Smooth Run</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-size-matters-mastering-facebook-video-cover-dimensions-for-maximum-impact/"><u>2024 Approved Size Matters Mastering Facebook Video Cover Dimensions for Maximum Impact</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-best-10-spotify-recorders/"><u>2024 Approved  Best 10 Spotify Recorders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-fix-your-backlit-keyboard-when-its-not-working-on-windows/"><u>5 Ways to Fix Your Backlit Keyboard When It’s Not Working on Windows</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-samsung-galaxy-m34-5g-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ization-marvels-worldwide-youtuber-winners/"><u>Monetization Marvels - Worldwide Youtuber Winners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-apk-setup-with-a-single-click-for-w11-users/"><u>Effortless APK Setup with a Single Click for W11 Users</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/best-youtube-video-into-text-converters-a-comprehensive-guide/"><u>Best YouTube Video Into Text Converters A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-to-do-if-microsoft-outlook-only-opens-in-safe-mode-on-windows/"><u>What to Do if Microsoft Outlook Only Opens in Safe Mode on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-window-tricks-to-unlock-facebook-chats/"><u>Winning Window Tricks to Unlock Facebook Chats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-your-deleted-content-8-tactics/"><u>Winning Back Your Deleted Content: 8 Tactics</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-honor-70-lite-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Honor 70 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/craft-intense-conversations-on-discord-learn-effective-message-pinning-for-2024/"><u>Craft Intense Conversations on Discord  Learn Effective Message Pinning for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-to-fixed-windows-itunes-applications/"><u>Swift Solutions to Fixed Windows iTunes Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-to-follow-plan-starting-over-with-windows-updates/"><u>Easy-to-Follow Plan: Starting Over with Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-avoid-dark-screen-while-playing-winos-titles/"><u>Tips to Avoid Dark Screen While Playing WINOS Titles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11s-gpo-settings-quickly/"><u>Unlocking Windows 11'S GPO Settings Quickly</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-broadcasting-showdown-deciding-between-obs-and-twitch-studio/"><u>[Updated] In 2024, Broadcasting Showdown  Deciding Between OBS and Twitch Studio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninstalling-microsoft-edge-from-windows-11/"><u>Uninstalling Microsoft Edge From Windows 11</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-educational-videos-cutting-and-assembly-techniques/"><u>2024 Approved  Educational Videos  Cutting & Assembly Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-effective-methods-to-align-security-keys-in-windows-11-systems/"><u>Five Effective Methods to Align Security Keys in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-upgrade-in-a-flash-streamlining-windows-driver-updates/"><u>Audio Upgrade in a Flash: Streamlining Windows Driver Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-mechanism-behind-windows-sound-graph-isolation/"><u>The Mechanism Behind Windows Sound Graph Isolation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-users-through-device-driver-installation-issues-in-win11/"><u>Guiding Users Through Device Driver Installation Issues in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-0x80072af9-failure/"><u>Unraveling the Mystery of 0X80072AF9 Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-remedying-full-screen-troubles-in-sonic-games/"><u>Understanding and Remedying Full-Screen Troubles in Sonic Games</u></a></li>
<li><a href="https://extra-resources.techidaily.com/cinemas-best-hope-fueled-film-selections-for-2024/"><u>Cinema's Best  Hope-Fueled Film Selections for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-can-we-bypass-vivo-y78t-frp-by-drfone-android/"><u>How Can We Bypass Vivo Y78t FRP?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-motorola-edge-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your Motorola Edge 2023 | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/driver-update-for-u-are-u-fpr-v450/"><u>Driver Update for U-Are-U FPR V4.50</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-fixes-for-no-server-found-on-apex-legends-tips-and-tricks-(156-chars/"><u>8 Fixes for 'No Server Found' On Apex Legends: Tips and Tricks (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-user-interface-with-mouse-click-lock-mcl-on-win-os/"><u>Enhancing User Interface with Mouse Click Lock (MCL) on Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-fixing-windows-11-unreachable-5ghz-wi-fi/"><u>Guide to Fixing Windows 11 - Unreachable 5GHz Wi-Fi</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-from-raw-footage-to-instagram-gold-top-10-editor-shortlists/"><u>[New] 2024 Approved  From Raw Footage to Instagram Gold - Top 10 Editor Shortlists</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-samsung-galaxy-s23plus-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Samsung Galaxy S23+ | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/supercharge-your-farming-fun-in-stardew-valley-top-7-upgrades/"><u>Supercharge Your Farming Fun in Stardew Valley (Top 7 Upgrades)</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ips-for-youtube-video-shooting/"><u>[New] Tips for YouTube Video Shooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-disk-errors-with-advanced-windows-tools/"><u>Fixing Disk Errors with Advanced Windows Tools</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-crafting-compelling-narratives-in-tiktok-the-top-5-caption-techniques-to-try-for-2024/"><u>[New] Crafting Compelling Narratives in TikTok  The Top 5 Caption Techniques to Try for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-for-taskbar-implementation-in-windows-11-tablets/"><u>Essential Steps for Taskbar Implementation in Windows 11 (Tablets)</u></a></li>
</ul></div>
