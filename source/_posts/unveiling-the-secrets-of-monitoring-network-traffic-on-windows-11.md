---
title: Unveiling the Secrets of Monitoring Network Traffic on Windows 11
date: 2024-08-08T11:06:40.383Z
updated: 2024-08-09T11:06:40.383Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unveiling the Secrets of Monitoring Network Traffic on Windows 11
excerpt: This Article Describes Unveiling the Secrets of Monitoring Network Traffic on Windows 11
keywords: WinTrafficMonitoring,WinNetWatcher,WindowsNetworkSurveillance,TrafficInspectorWin,NetDataTrackingWin11,WinPCTrafficAnalysis,Windows11NetworkView
thumbnail: https://thmb.techidaily.com/d64a92b374563fd7f8dd564ef2b564a68a3b72b9d9892ee74121db7b4e7f60bc.jpg
---

## Unveiling the Secrets of Monitoring Network Traffic on Windows 11

 Netstat is a command-line utility that helps you monitor all the technical properties of your active network connections. It provides a quick way to see all your open ports, active connections, and network services running on your system.

 If all this sounds too technical to you, don't worry; we'll explain everything simply as you read further in the article. First, let's take a look at what netstat is and how to use netstat on Windows to monitor your network.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
## What is the Netstat Command on Windows?

 The netstat command is mainly used by IT experts or network troubleshooters on Windows and Linux systems. The command, when executed, displays a list of the active TCP connections, ports that are listening, Ethernet statistics, addresses and ports being used by your system, and more.

 In simple terms, this command lets you see what network connections are active and what applications are using them in the background at any given time.

 To give you clarity, below are some examples of what netstat can show you:

* All inbound and outbound connections are on your PC.
* Information about which ports are open or listening for connections.
* Connections and processes using the internet.
* Any suspicious connections from unknown applications or services.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
## How to Use the Netstat Command on Windows

 As mentioned before, the netstat command is accessible only from the Command Prompt. If you don't know the steps, follow the ones given below to run netstat from the Command Prompt:

1. Click on the **Search** button on your taskbar and search for the **Command Prompt** app.
2. Next to the matching search result, click on **Run as administrator**. This will launch Command Prompt with advanced-user permissions.  
![Command Prompt In Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/command-prompt-in-windows-search.jpg)
3. On the Command Prompt, type **netstat** and press **Enter**. The command, after executing, will output a list of active connections along with their status.  
![netstat Command Output](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netstat-command-output.jpg)
4. If you need to share the output with a tech support team, for example, use this command to copy the results in a text file: "**netstat > Path\\FileName.txt**". In this command, **Path** is any folder's location where you want to save the file and **FileName.txt** is your exported file's name.  
![netstat Output Export Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netstat-output-export-command-1.jpg)

 The highlighting part of netstat is that you can further use it with some parameters (or syntaxes) to filter the generated output. We'll show you some useful parameters that you can use with the "**netstat -parameter**" format in the next section.

 If you're eager to learn more about other such commands, check our list of useful [Windows commands to manage your network](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/).

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
## Useful Netstat Parameters for Windows Users

 In layman's terms, parameters mean some symbols or alphabets that allow you to modify what the netstat command displays. When you use a parameter with the "netstat -parameter" format, it helps you view detailed information about the traffic and different connections on a local area network.

 Let's look at some useful netstat parameters to receive more specific and filtered information from netstat:

* **netstat -a:** It displays all the running TCP and UDP connections and the listening ports. If there are any failed connection attempts, they will be displayed here too. Besides the **\-a** parameter, check the other [alternative ways to check open TCP ports](https://www.makeuseof.com/check-open-tcpip-ports-windows/).  
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![netstat -a Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netstat-a-command.jpg)
* **netstat -b:** The **\-b** parameter displays the executable (.EXE) involved in creating each connection or listening port. It is mainly useful for those who deal with network troubleshooting in a Windows server or a computer part of a domain.  
![netstat -b Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netstat-b-command.jpg)
* **netstat -e:** If you use an Ethernet connection rather than Wi-Fi, the **\-e** parameter can show you detailed Ethernet statistics, like link speed, total send/receive bytes, and some other technical statistics.  
![netstat -e Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netstat-e-command.jpg)
* **netstat -o:** Suppose you installed an application (from an untrusted website), in that case, you can check whether the application is doing something suspicious with the connection or not. This is because the **\-o** parameter shows the Process ID (PID) of every connection that you can match from the Task Manager.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
![netstat -o Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netstat-o-command.jpg)
* **netstat -s:** This shows statistics by a protocol like packets sent/received, errors, discarded packets, etc. It's useful if you want to understand per-protocol-based bandwidth usage.  
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
![netstat -s Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netstat-s-command.jpg)

 Now that you have an idea of some useful commands, try running them in the Command Prompt. Note that we recommend running Command Prompt as an administrator only as some connections are only visible with admin privileges.

 If you don't like to enter the commands repeatedly, combine the parameters. For example, **netstat -e -s** will show you your Ethernet network details along with the per-protocol-based bandwidth usage in one view.

 Above all, netstat is just one command for troubleshooting. If you're interested, check the [Windows network connections tool](https://www.makeuseof.com/windows-open-network-connections-tool/) to learn about another handy tool.

## Troubleshooting Your Networks Made Easy With Netstat

 Unlike utilities you need to download separately, netstat is ready to use in Command Prompt on all Windows versions. This makes it the go-to tool for getting a snapshot of network status right from your PC.

 Additionally, from checking incoming and outgoing connections to sniffing out potential malicious activities, you can use it easily even if you're not a professional network expert.

 If all this sounds too technical to you, don't worry; we'll explain everything simply as you read further in the article. First, let's take a look at what netstat is and how to use netstat on Windows to monitor your network.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-find-the-top-8-video-communication-apps-for-android-groups/"><u>[New] 2024 Approved  Find the Top 8 Video Communication Apps for Android Groups</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-quick-start-guide-to-recording-remote-meetings-with-ease-windows-mac/"><u>[New] 2024 Approved  Quick-Start Guide to Recording Remote Meetings with Ease (Windows, Mac)</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-hot-yt-videos-best-music-dance-and-responses-23/"><u>[New] In 2024, Hot YT Videos  Best Music Dance & Responses '23</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-re-watch-lost-youtube-scenes-online-simple-steps/"><u>[New] In 2024, How to Re-Watch Lost YouTube Scenes Online  Simple Steps</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-maximizing-the-impact-the-art-of-using-whiteboards-on-zoom-for-2024/"><u>[New] Maximizing the Impact  The Art of Using Whiteboards on Zoom for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-render-your-social-media-footage-for-2024/"><u>[New] Render Your Social Media Footage for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/niting-music-and-media-with-precision-using-youtube-video-editor-for-2024/"><u>[New] Uniting Music & Media with Precision Using YouTube Video Editor for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-cutting-edge-webcam-utilization-at-home/"><u>[Updated] 2024 Approved  Cutting-Edge Webcam Utilization at Home</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-collective-wisdom-on-easeus-products/"><u>[Updated] In 2024, Collective Wisdom on EaseUS Products</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-understanding-your-twitter-archives-potential/"><u>[Updated] Understanding Your Twitter Archive's Potential</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-advanced-techniques-for-using-the-instagram-sticker-question-mark/"><u>2024 Approved  Advanced Techniques for Using the Instagram Sticker Question Mark</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-complete-guide-to-video-studios-focusing-on-xvideo/"><u>2024 Approved  Complete Guide to Video Studios  Focusing on XVideo</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-mastering-youtube-trailer-creation-with-filmora/"><u>2024 Approved  Mastering YouTube Trailer Creation with Filmora</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-recording-made-easy-tips-for-youtube-vids/"><u>2024 Approved  Recording Made Easy  Tips for YouTube Vids</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-seamless-transition-for-extracting-facebooks-graphic-gems-anywhere/"><u>2024 Approved  Seamless Transition for Extracting Facebook's Graphic Gems Anywhere</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-top-hd-cameras-for-elk-and-mule-deer/"><u>2024 Approved  Top HD Cameras for Elk and Mule Deer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-how-to-for-customizing-windows-11-with-widgets/"><u>A Comprehensive How-To for Customizing Windows 11 with Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-network-adapter-error-31-quickly/"><u>Addressing Windows Network Adapter Error 31 Quickly</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/avi-video-editing-essentials-top-t-for-2024/"><u>AVI Video Editing Essentials Top T for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-and-remediation-for-a-frozen-resource-monitor-app-in-windows-11/"><u>Avoidance and Remediation for a Frozen Resource Monitor App in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/can-pressing-prtscn-launch-snipping-tool-steps-to-halt/"><u>Can Pressing PrtScn Launch Snipping Tool? Steps to Halt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ceasing-windows-notification-for-updates/"><u>Ceasing Windows Notification for Updates</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-xiaomi-redmi-a2plus-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Xiaomi Redmi A2+ to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-printer-busy-message-in-win11/"><u>Eliminating Printer Busy Message in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/embedding-ical-into-your-windows-system-without-hassle/"><u>Embedding iCal Into Your Windows System without Hassle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-insights-employing-law-filters-within-windows/"><u>Essential Insights: Employing LAW Filters Within Windows</u></a></li>
<li><a href="https://video-capture.techidaily.com/essential-tips-for-adding-visual-impact-in-google-meet/"><u>Essential Tips for Adding Visual Impact in Google Meet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploiting-windows-11s-error-diagnostic-solutions/"><u>Exploiting Windows 11'S Error Diagnostic Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-hidden-options-mastery-of-lost-control-configurations/"><u>Explore Hidden Options: Mastery of Lost Control Configurations</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/exploring-facebooks-newest-feature-evolution-for-2024/"><u>Exploring Facebook's Newest Feature Evolution for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722974470948-get-ready-for-superior-sound-quality-easy-nahimic-drivers-update-today/"><u>Get Ready for Superior Sound Quality - Easy Nahimic Drivers Update Today!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-the-haste-of-edges-tabs-in-w11/"><u>Halt the Haste of Edge's Tabs in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-clear-the-focus-wallpaper-icon-on-windows-11/"><u>How to Clear the Focus Wallpaper Icon on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-examine-excel-data-in-notepad/"><u>How to Examine Excel Data in Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-dxgierrordeviceremoved-error-in-windows-10-and-11/"><u>How to Fix the DXGI_ERROR_DEVICE_REMOVED Error in Windows 10 & 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-oppo-find-x6-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Oppo Find X6 Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-strategies-against-locked-out-windows-pin/"><u>Immediate Strategies Against Locked-Out Windows PIN</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-11-best-pokemon-go-spoofers-for-gps-spoofing-on-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>In 2024, 11 Best Pokemon Go Spoofers for GPS Spoofing on Apple iPhone 6 | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-delete-gmail-account-withwithout-password-on-nokia-105-classic-by-drfone-android/"><u>In 2024, Delete Gmail Account With/Without Password On Nokia 105 Classic</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-top-15-augmented-reality-games-like-pokemon-go-to-play-on-realme-v30t-drfone-by-drfone-virtual-android/"><u>In 2024, Top 15 Augmented Reality Games Like Pokémon GO To Play On Realme V30T | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-top-5-oppo-k11-5g-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Oppo K11 5G Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-which-pokemon-can-evolve-with-a-moon-stone-for-vivo-y56-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Which Pokémon can Evolve with a Moon Stone For Vivo Y56 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-apk-deployment-for-win-11-users/"><u>Instant APK Deployment for Win 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-yourphoneexe-malware-insights-on-windows-87/"><u>Is YourPhone.exe Malware? Insights on Windows 8/7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-dropbox-cpu-utilization-on-windows-machines/"><u>Lowering Dropbox CPU Utilization on Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masteringdarkmodesettingforwindowstexteditor/"><u>MasteringDarkModeSettingForWindowsTextEditor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multiple-routes-for-opening-utilities-on-windows-systems/"><u>Multiple Routes for Opening Utilities on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-error-0x0000004e-in-windows-devices/"><u>Navigating Error 0X0000004E in Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-hazards-of-cheap-windows-key-purchases/"><u>Navigating the Hazards of Cheap Windows Key Purchases</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-alternatives-to-gopro-quik-for-pc-video-editing-made-easy/"><u>New 2024 Approved Alternatives to GoPro Quik for PC Video Editing Made Easy</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-unleash-your-creativity-top-1080p-video-editing-programs/"><u>New Unleash Your Creativity Top 1080P Video Editing Programs</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/online-phone-search-strategies-finding-contact-details-safely-and-effectively/"><u>Online Phone Search Strategies: Finding Contact Details Safely and Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-windows-11-search-top-5-expert-methods/"><u>Optimize Your Windows 11 Search: Top 5 Expert Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-account-security-changing-reset-counter-after-failed-logins/"><u>Optimizing Account Security: Changing Reset Counter After Failed Logins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-ignoring-soon-expiring-licenses-alerts-in-windows/"><u>Quick Fix for Ignoring Soon Expiring Licenses Alerts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-this-pc-cant-run-post-windows-11-setup/"><u>Rectifying 'This PC Can't Run' Post-Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-access-reactivating-ms-store-apps-in-windows-11/"><u>Regaining Access: Reactivating MS Store Apps in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remediation-steps-for-windows-sandboxs-hypervisor-not-found/"><u>Remediation Steps for Windows Sandbox's Hypervisor Not Found</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-internal-errors-quickly-with-windows-rdp-connections/"><u>Resolving Internal Errors Quickly with Windows RDP Connections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/running-state-of-the-art-ai-windows-edition/"><u>Running State-of-the-Art AI: Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-file-organization-in-windows-11/"><u>Simplifying File Organization in Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/sonic-shakers-the-ultimate-audio-rippers-list-for-2024/"><u>Sonic Shakers  The Ultimate Audio Rippers List for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-cant-get-mail-errors-windows-11-edition/"><u>Strategies to Overcome Can’t Get Mail Errors, Windows 11 Edition</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/top-5-car-locator-apps-for-apple-iphone-8-drfone-by-drfone-virtual-ios/"><u>Top 5 Car Locator Apps for Apple iPhone 8 | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-7-effective-substitutes-for-the-chatgpt-mobile-application/"><u>Top 7 Effective Substitutes for the ChatGPT Mobile Application</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-8-cross-platform-tools-for-microsoft-enthusiasts/"><u>Top 8 Cross-Platform Tools for Microsoft Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-approach-to-allocated-ram/"><u>Understanding Windows' Approach to Allocated RAM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-windows-11-potential-via-powertoys-install/"><u>Unleashing Windows 11 Potential via PowerToys Install</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-ways-for-swift-epic-game-loading/"><u>Unveiling Windows Ways for Swift Epic Game Loading</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/video-valedictions-sign-off-strategies-for-online-platforms-for-2024/"><u>Video Valedictions  Sign-Off Strategies for Online Platforms for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-volume-control-fix-guide/"><u>Windows 10/11 Volume Control Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-history-hiccup-quick-fixes-in-3-steps/"><u>Windows History Hiccup - Quick Fixes in 3 Steps</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>