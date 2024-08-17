---
title: 6 Ways to Restore Missing Windows Time Service
date: 2024-08-16T01:13:04.138Z
updated: 2024-08-17T01:13:04.138Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 6 Ways to Restore Missing Windows Time Service
excerpt: This Article Describes 6 Ways to Restore Missing Windows Time Service
keywords: WinTimeRestore101,TimeServiceRepairTips,MissingWindowsTimeSolutions,ReinstateWTS,TimeServiceRecoveryMethods,WindowsTimeServiceFix,ServiceWTS6Steps
thumbnail: https://thmb.techidaily.com/9b6181d7d07722f8a9a54201f128a4424f9e657e4070376880c0b424223e6faa.jpg
---

## 6 Ways to Restore Missing Windows Time Service

 Start your Windows computer and notice that the time is wrong. It might be a minor issue, or you accidentally changed the setting. But what if Windows Time Service is missing entirely?

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

## 1\. Reboot Your PC

 Restart your computer before attempting any major troubleshooting. While it may sound simple, restarting the computer resolves minor errors and glitches that prevent the service from running. It flushes out temporary files and refreshes the operating system to ensure everything works correctly.

1. Press **Alt + F4** to bring up the Shutdown dialog
2. Select **Restart** from the drop-down menu and then hit **OK**.

 Once the computer restarts, check if Windows Time Service is available. If it's still missing, move on to the next step.

## 2\. Change the Time Server

 If restarting the computer does not work, you must change the time server. Changing the time server synchronizes your system clock with an online one, displaying your computer's correct date and time.

 Follow the steps to change the time server:

1. Press the **Windows key** to open the Start Menu.
2. Type **control panel** in the search box and click the result. This opens the Control Panel window.
3. Select **View by: Large icons** and click **Date and Time**.
4. Switch to the **Internet Time** tab and click **Change settings**.
5. Check the **Synchronize with an Internet time server** box and select a time server from the drop-down menu.  
![Change the Time Server](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-the-time-server.jpg)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click the **Update now** button to synchronize your computer with the time server.
7. Once completed, click **OK** to save the changes and exit.

 After these steps, you should see the Windows Time Service running on your system. Check the time to ensure it is correct and make further adjustments.

## 3\. Add More Time Servers

 If the Windows Time Service is still missing, you can try adding more time servers to the list. Multiple time servers increase the chance of finding an active server and keeping your system in sync. If one server goes down, your computer can automatically switch to another.

 The solution requires editing the Windows registry. Even a small mistake can damage your system, so proceed with caution. To avoid data loss, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing.

 To add time servers, do the following:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and click **OK**.
3. If the UAC window pops up on the screen, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following directory.  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DateTime\Servers  
 Copy and paste the path into the Registry Editor address bar and press Enter. This will take you to the Location key.
5. From the left navigation panel, right-click the Servers folder and select **New** \> **String Value**.  
![Add More Time Servers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-more-time-servers.jpg)
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Name the new value **Server N**, and replace **N** with a number starting from 1.  
 You can't have the same number twice. That means if there are already 3 values named _Server 1_, _Server 2_, and _Server 3_, you must call the new one as **Server 4**.
7. Double-click the newly created value and add a time server address in the Value data field.
8. Here are some time server addresses:  
`time.windows.com  

time.nist.gov  

time-a-wwv.nist.gov  

time-c-wwv.nist.gov  

ntp-wwv.nist.gov`

 After adding the time server, click **OK** and close the Registry Editor window. Now restart your computer to apply the changes and check if Windows Time Service is available.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
## 4\. Re-register the Windows Time Service

 If the above steps fail, you can try re-registering the Windows Time Service. Re-registering a service refreshes its configuration and forces it to start again. Doing this may fix the missing Windows Time Service and recover clock synchronization.

 To re-register the Windows Time Service, follow these steps:

1. Press the **Win + S** keys to open the Windows Search.
2. Type **cmd** in the search box and simultaneously press **Ctrl + Shift + Enter**. This opens the Command Prompt with administrative privileges.
3. If the UAC window pops up, click **Yes** to grant permission.
4. Type the following command in the Command Prompt and press Enter:  
net stop w32time
5. This command will stop the Windows Time Service. Now type the following command to unregister the service and press **Enter**:  
w32tm /unregister
6. After that, run the following command to register the service:  
w32tm /register
7. Next, type the following command and hit **Enter**. This starts the Windows Time Service.  
net start w32time

 After performing these steps, close the Command Prompt window and restart your system. You should see that the Windows Time Service is running, and your clock syncs with the time server.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Repair Corrupted System Files

![SFC Command Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sfc-command-preview.jpg)
<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Corrupt system files can also cause Windows services to fail. So, if the Windows Time Service is still missing, try repairing corrupt system files. You can do this using the System File Checker tool. This tool scans your system for missing files and repairs the errors it finds.

 Wait for the scan to complete, and restart your computer. After that, check if the Windows Time Service is still missing. If it is, try running the Deployment Image Servicing and Management tool. This tool repairs corrupted system files and restores your Windows installation's health.

 If you're not sure how to run either of these tools, check out how to repair corrupt Windows files with its built-in tools for instructions.

## 6\. Scan for Malware

 Sometimes, malware is to blame for Windows services acting a little odd. As such, it's worth [running a full system scan](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and removing all detected threats.

![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)

 If you feel your PC isn't as secure as it could be, you could try downloading one of the [best antivirus apps for Windows](http://www.makeuseof.com/windows-11-antivirus-apps/). These will both actively block malicious program from installing themselves on your PC, and remove any that are currently infesting your computer.

 For those who prefer a command-line approach, you can [use Windows PowerShell to scan Windows for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
## Restore the Missing Windows Time Service

 Hopefully, one or more of these tips worked for you. Missing Windows services can be a huge pain, but hopefully, one of these methods has brought back the Windows Time Service back to working order.

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-information.techidaily.com/new-boost-zoom-audio-solutions-for-waveform-woes/"><u>[New] Boost Zoom Audio  Solutions for Waveform Woes</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-experts-choice-extracting-youtube-video-intros-online-for-2024/"><u>[New] Expert's Choice  Extracting Youtube Video Intros Online for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/lavorful-follows-top-food-vloggers-to-track/"><u>[New] Flavorful Follows  Top Food Vloggers to Track</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-premium-no-cost-slow-motion-video-capture-options-for-iphonesandroid/"><u>[New] Premium No-Cost Slow Motion Video Capture Options for iPhones/Android</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-seasons-finest-ice-artistry-2022-highlights/"><u>[New] Season's Finest Ice Artistry - 2022 Highlights</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-art-of-video-storytelling-integrating-audio-narration/"><u>[New] The Art of Video Storytelling  Integrating Audio Narration</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-4-ways-to-record-facebook-live-stream/"><u>[Updated] 2024 Approved  4 Ways to Record Facebook Live Stream</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-full-breakdown-gopro-slr4-silver-edition/"><u>[Updated] Full Breakdown  GoPro SLR4 Silver Edition</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-get-tiktoks-best-videos-in-a-flash/"><u>[Updated] Get TikTok's Best Videos in a Flash</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-guided-process-importing-snapchats-into-local-gallery/"><u>[Updated] Guided Process  Importing Snapchats Into Local Gallery</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-imovie-soundscapes-enrich-your-visual-symphony/"><u>[Updated] IMovie Soundscapes  Enrich Your Visual Symphony</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-detailed-analysis-tunefab-screen-tools/"><u>[Updated] In 2024, Detailed Analysis  Tunefab Screen Tools</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-vlc-recordings-tips-and-tricks/"><u>[Updated] In 2024, VLC Recordings  Tips and Tricks</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-luminous-android-video-editing-hacks/"><u>[Updated] Luminous Android Video Editing Hacks</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-virtual-victory-the-leading-ladies-of-gaming/"><u>[Updated] Virtual Victory  The Leading Ladies of Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-proven-strategies-to-solve-windows-update-woes/"><u>10 Proven Strategies to Solve Windows Update Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-tips-to-help-you-fix-the-windows-10-blue-screen-error/"><u>11 Tips to Help You Fix the Windows 10 Blue Screen Error</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-the-ultimate-color-correctors-handbook/"><u>2024 Approved  The Ultimate Color Corrector's Handbook</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-itel-s23-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Itel S23 to Roku | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-common-complaints-users-have-about-windows-11/"><u>5 Common Complaints Users Have About Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-key-strategies-for-optimizing-windows-11s-bar/"><u>5 Key Strategies for Optimizing Windows 11'S Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-secure-windows-strategies-when-bitlocker-fails/"><u>5 Secure Windows Strategies When Bitlocker Fails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/50plus-innovative-ideas-to-customize-your-windows-11-layout/"><u>50+ Innovative Ideas to Customize Your Windows 11 Layout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-walkthrough-to-setting-up-dns-on-windows-11/"><u>A Complete Walkthrough to Setting Up DNS on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-android-powered-webcams-in-windows-11-environments/"><u>A Guide to Android-Powered Webcams in Windows 11 Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-altering-lockout-frequency-in-windows-11-successor/"><u>A Step-by-Step Guide to Altering Lockout Frequency in Windows 11 Successor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-using-windows-iscsi-initiator/"><u>A Step-by-Step Guide to Using Windows iSCSI Initiator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-thoroughly-detailed-guide-to-windows-boot-options/"><u>A Thoroughly Detailed Guide to Windows Boot Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-compute-with-essential-wintoy-tech/"><u>Accelerate Your Compute with Essential WinToy Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-ui-skills-with-windows-11-widgets/"><u>Accelerate Your UI Skills with Windows 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-denied-reconnecting-to-windows-shared-items/"><u>Access Denied: Reconnecting to Windows Shared Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-academic-success-winning-strategies-for-windows/"><u>Achieve Academic Success: Winning Strategies for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-lunar-client-startup-failures-on-windows-systems/"><u>Addressing “Lunar Client Startup Failures” On Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-glitch-nvidias-x0001-on-windows-w11/"><u>Addressing Glitch: Nvidia's X0001 on Windows W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-vscode-shutdown-problems-on-windows-11/"><u>Addressing VSCode Shutdown Problems on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aesthetic-arcade-adventures-old-classics-in-dosbox-x/"><u>Aesthetic Arcade Adventures: Old Classics in DOSBox-X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/apple-maps-integration-guide-for-windows-devices/"><u>Apple Maps Integration Guide for Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/asus-zenbook-14-oled-ux3405-review-is-this-the-macbook-of-windows/"><u>ASUS Zenbook 14 OLED (UX3405) Review: Is This the MacBook of Windows?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-unexpected-shutdowns-in-windows-11-pro/"><u>Avoid Unexpected Shutdowns in Windows 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/batch-processing-closure-for-busy-windows-users/"><u>Batch-Processing Closure for Busy Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-the-blues-swift-remedies-to-hypervisor-bsos-in-winxose/"><u>Beat the Blues: Swift Remedies to Hypervisor BSOS in WINXOSE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-immediate-help-tool-on-windows-modern-os/"><u>Beginning Immediate Help Tool on Windows Modern OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitlock-cracked-staying-secure-yet-unmoved/"><u>BitLock Cracked: Staying Secure Yet Unmoved</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-pc-safety-change-your-windows-11-password/"><u>Boost PC Safety: Change Your Windows 11 Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-amd-graphics-efficiency-windows-11-updates-guide/"><u>Boosting AMD Graphics Efficiency: Windows 11 Updates Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-call-productivity-on-windows-11-with-the-intel-unison-app/"><u>Boosting Call Productivity on Windows 11 with the Intel Unison App</u></a></li>
<li><a href="https://tech-haven.techidaily.com/clearing-past-interactions-how-to-remove-your-chat-history-on-chatgpt/"><u>Clearing Past Interactions: How to Remove Your Chat History on ChatGPT</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/designing-striking-valorant-thumbnails-for-online-platforms-for-2024/"><u>Designing Striking Valorant Thumbnails for Online Platforms for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719244514852-enhancing-your-windows-snipping-experience-with-proven-fixes/"><u>Enhancing Your Windows Snipping Experience with Proven Fixes</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-asus-rog-phone-8-pro-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Asus ROG Phone 8 Pro Quickly | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-vivo-x100-to-mac-drfone-by-drfone-android/"><u>How to Mirror Vivo X100 to Mac? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-play-avchd-mts-files-on-samsung-galaxy-s23-ultra-by-aiseesoft-video-converter-play-mts-on-android/"><u>How to play AVCHD MTS files on Samsung Galaxy S23 Ultra?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Lava Blaze 2 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719294305886-ignite-performance-gains-in-winoutlook-today/"><u>Ignite Performance Gains in WinOutlook, Today</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-honor-v-purse-drfone-by-drfone-virtual-android/"><u>In 2024, Can I use iTools gpx file to catch the rare Pokemon On Honor V Purse | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-embrace-cold-choosing-heated-backdrops-for-youtube/"><u>In 2024, Embrace Cold  Choosing Heated Backdrops for YouTube</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-here-are-some-of-the-best-pokemon-discord-servers-to-join-on-tecno-pova-6-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some of the Best Pokemon Discord Servers to Join On Tecno Pova 6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unleashing-creativity-with-mobile-melodies-on-iphone/"><u>In 2024, Unleashing Creativity with Mobile Melodies on iPhone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-unlocking-iphone-12-passcode-without-a-computer-drfone-by-drfone-ios/"><u>In 2024, Unlocking iPhone 12 Passcode without a Computer | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719367478733-overcome-windows-obstacles-expert-advice-awaits/"><u>Overcome Windows Obstacles: Expert Advice Awaits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719266622683-rejuvenate-your-locked-shift-key-in-windows/"><u>Rejuvenate Your Locked Shift Key in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719276426207-saving-the-day-with-win1011s-recycle-bin-corruption-fixed/"><u>Saving the Day with Win10/11's Recycle Bin Corruption Fixed</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/scaling-down-obs-video-quality/"><u>Scaling Down OBS Video Quality</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/speedy-upgrade-leading-android-video-tuners/"><u>Speedy Upgrade  Leading Android Video Tuners</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/the-insiders-guide-adding-borders-in-instagram-footage-for-2024/"><u>The Insider's Guide  Adding Borders in Instagram Footage for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/travel-in-timeless-style-a-comprehensive-review-of-powershot-g9x-mark-ii-camera/"><u>Travel in Timeless Style: A Comprehensive Review of PowerShot G9X Mark II Camera</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-motorola-edge-40-neo-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Live Location is Not Updating and How to Fix on your Motorola Edge 40 Neo | Dr.fone</u></a></li>
</ul></div>
