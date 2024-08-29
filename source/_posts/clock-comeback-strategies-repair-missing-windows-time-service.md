---
title: "Clock Comeback Strategies: Repair Missing Windows Time Service"
date: 2024-08-28T01:16:29.491Z
updated: 2024-08-29T01:16:29.491Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Clock Comeback Strategies: Repair Missing Windows Time Service"
excerpt: "This Article Describes Clock Comeback Strategies: Repair Missing Windows Time Service"
keywords: Clock Recovery Tips,Fix Windows Time Error,System Time Restoration,Reestablish Network Time,Patch TimeService Fix,NTP Service Repair Guide,TimeSync Troubleshooting
thumbnail: https://thmb.techidaily.com/4278a11dc73e1c0d6c218af281491c5ebbfcb593f38d324f2ddde851d89b6bd2.jpeg
---

## Clock Comeback Strategies: Repair Missing Windows Time Service

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
6. Name the new value **Server N**, and replace **N** with a number starting from 1.  
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
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
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Repair Corrupted System Files

![SFC Command Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sfc-command-preview.jpg)

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Corrupt system files can also cause Windows services to fail. So, if the Windows Time Service is still missing, try repairing corrupt system files. You can do this using the System File Checker tool. This tool scans your system for missing files and repairs the errors it finds.

 Wait for the scan to complete, and restart your computer. After that, check if the Windows Time Service is still missing. If it is, try running the Deployment Image Servicing and Management tool. This tool repairs corrupted system files and restores your Windows installation's health.

 If you're not sure how to run either of these tools, check out how to repair corrupt Windows files with its built-in tools for instructions.

## 6\. Scan for Malware

 Sometimes, malware is to blame for Windows services acting a little odd. As such, it's worth [running a full system scan](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and removing all detected threats.

![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
 If you feel your PC isn't as secure as it could be, you could try downloading one of the [best antivirus apps for Windows](http://www.makeuseof.com/windows-11-antivirus-apps/). These will both actively block malicious program from installing themselves on your PC, and remove any that are currently infesting your computer.

 For those who prefer a command-line approach, you can [use Windows PowerShell to scan Windows for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/).

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## Restore the Missing Windows Time Service

 Hopefully, one or more of these tips worked for you. Missing Windows services can be a huge pain, but hopefully, one of these methods has brought back the Windows Time Service back to working order.

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-enhanced-team-collaboration-with-slack-plus-filmora-timelines/"><u>[New] 2024 Approved  Enhanced Team Collaboration with Slack + Filmora Timelines</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-revolutionize-your-designs-incorporating-3d-text-psx/"><u>[New] 2024 Approved  Revolutionize Your Designs  Incorporating 3D Text PSX</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-icy-inspirations-top-olympic-triumphs/"><u>[New] Icy Inspirations  Top Olympic Triumphs</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-innovating-highest-quality-canon-sequences/"><u>[New] Innovating Highest Quality Canon Sequences</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-sony-fdr-x1000-videography-complete-review-edition/"><u>[New] Sony FDR-X1000 Videography - Complete Review Edition</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-streamers-dilemma-revisited-obs-vs-twitch-channel-space/"><u>[New] Streamers' Dilemma Revisited  OBS vs Twitch Channel Space</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-create-memorable-thumbnails-discover-these-8-youtube-aids/"><u>[Updated] 2024 Approved  Create Memorable Thumbnails - Discover These 8 YouTube Aids</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-premium-accessible-stopwatch-services/"><u>[Updated] Premium Accessible Stopwatch Services</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-crafting-a-blended-media-experience-with-tunes/"><u>2024 Approved  Crafting a Blended Media Experience with Tunes</u></a></li>
<li><a href="https://win-forum.techidaily.com/a-guide-to-the-big-4-of-social-networks-mastering-interaction-on-facebook-twitter-instagram-and-youtube/"><u>A Guide to the Big 4 of Social Networks: Mastering Interaction on Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/a-treasure-trove-of-9-complete-holiday-flicks-free-streaming/"><u>A Treasure Trove of 9 Complete Holiday Flicks, Free Streaming</u></a></li>
<li><a href="https://games-able.techidaily.com/achieve-seamless-gaming-experience-on-steam-by-clearing-titles/"><u>Achieve Seamless Gaming Experience on Steam by Clearing Titles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparing-windows-n-releases-tech-enthusiasts-guide/"><u>Comparing Windows N Releases: Tech Enthusiast's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-approach-to-unhandled-exception-in-windows-apps/"><u>Comprehensive Approach to Unhandled Exception in Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-and-mending-windows-audio-glitch-code-9999/"><u>Demystifying and Mending Windows Audio Glitch: Code 9999</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-folder-size-evaluation-using-powershell-commands/"><u>Demystifying Folder Size Evaluation Using PowerShell Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-quick-and-efficient-ways-to-access-windows-11-sounds/"><u>Discover Quick and Efficient Ways to Access Windows 11 Sounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-media-player-server-issue/"><u>Eliminating Media Player Server Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-readwrite-errors-in-windows-systems/"><u>Eliminating Read/Write Errors in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-smooth-xbox-microphone-integration-in-windows-11-ecosystem/"><u>Ensuring Smooth Xbox Microphone Integration in Windows 11 Ecosystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-for-google-maps-setup-on-pc/"><u>Essential Steps for Google Maps Setup on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-alternatives-to-cortana-in-windows-10/"><u>Exploring Alternatives to Cortana in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/final-version-dragon-ball-z-kakarot-with-all-prior-glitches-corrected/"><u>Final Version Dragon Ball Z: Kakarot with All Prior Glitches Corrected</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-windows-flashing-screen-in-windows-11-pcs/"><u>Fix Window's Flashing Screen in Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-gamepad-that-wont-respond/"><u>Fixing Windows Gamepad that Won't Respond</u></a></li>
<li><a href="https://win11-tips.techidaily.com/focusing-on-fixing-the-failed-to-initiate-lunar-client-issue/"><u>Focusing on Fixing the Failed to Initiate Lunar Client Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-troubleshooting-display-with-windows-drivers/"><u>Guide to Troubleshooting Display with Windows Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-world-of-warcraft-update-stuck-on-initializing-on-windows/"><u>How to Fix a World of Warcraft Update Stuck on Initializing on Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-oppo-a1-5g-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Oppo A1 5G? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-successfully-bypass-icloud-activation-lock-from-apple-iphone-13-by-drfone-ios/"><u>How to Successfully Bypass iCloud Activation Lock from Apple iPhone 13</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-6-methods-for-switching-from-apple-iphone-xs-to-samsung-drfone-by-drfone-transfer-from-ios/"><u>In 2024, 6 Methods for Switching from Apple iPhone XS to Samsung | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-realme-narzo-n53-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Realme Narzo N53? | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-apple-iphone-8-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Apple iPhone 8 Plus? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-step-into-better-imaging-with-these-gopro-extras/"><u>In 2024, Step Into Better Imaging with These GoPro Extras</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-the-ultimate-ipad-slow-motion-techniques-for-filming-and-video-modification/"><u>In 2024, The Ultimate iPad Slow Motion Techniques for Filming and Video Modification</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ingenious-tactics-to-outwit-windows-sign-in-prompts/"><u>Ingenious Tactics to Outwit Windows Sign-In Prompts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-edge-written-for-optimal-system-performance/"><u>Managing Edge' Written for Optimal System Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-pc-troubles-try-our-top-10-tools/"><u>Navigating PC Troubles? Try Our Top 10 Tools</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-top-7-converting-audio-to-text-tools/"><u>New 2024 Approved Top 7 Converting Audio to Text Tools</u></a></li>
<li><a href="https://driver-error.techidaily.com/no-vehicle-load-for-this-equipment/"><u>No Vehicle Load for This Equipment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/podcast-perfection-on-pc-win-five-no-cost-filters/"><u>Podcast Perfection on PC: Win Five No-Cost Filters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prioritizing-productivity-make-terminal-first/"><u>Prioritizing Productivity: Make Terminal First</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-guide-resurrect-your-chrome-browser-in-w11/"><u>Quick Fix Guide: Resurrect Your Chrome Browser in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quieten-the-high-contrast-in-windows-ui/"><u>Quieten the High Contrast in Windows UI</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/radeon-relive-download/"><u>Radeon Relive Download</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-control-over-your-text-editor-fixing-windows-notepad-open-issues/"><u>Regain Control Over Your Text Editor: Fixing Windows Notepad Open Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reverting-windows-errors-curb-dwarf-fortress-haltings/"><u>Reverting Windows Errors: Curb Dwarf Fortress Haltings</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/seamless-transition-moving-your-memories-from-google-photos-to-icloud/"><u>Seamless Transition: Moving Your Memories From Google Photos to iCloud</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-system-changes-mastery-of-cli-and-registry-modifications/"><u>Simplifying System Changes: Mastery of CLI and Registry Modifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-fixes-to-steam-logins-in-rust-on-your-windows-machine/"><u>Step-by-Step Fixes to Steam Logins in Rust on Your Windows Machine</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-to-getting-your-qualcomm-atheros-bluetooth-driver-working-again-on-windows-11/"><u>Step-by-Step Guide to Getting Your Qualcomm Atheros Bluetooth Driver Working Again on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-system-5-must-have-pc-tools/"><u>Streamline Your System: 5 Must-Have PC Tools</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-vivo-y100i-power-5g-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Vivo Y100i Power 5G Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-offon-windows-11s-online-scan-feature/"><u>Switching Off/On Windows 11'S Online Scan Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-inaccessible-game-sessions-due-to-steams-vac/"><u>Tackling Inaccessible Game Sessions Due to Steam’s VAC</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-pros-guide-to-efficient-win11-use-for-2024/"><u>The Pro's Guide to Efficient Win11 Use for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-a-brighter-bolder-cursor-on-windows/"><u>The Ultimate Guide to a Brighter, Bolder Cursor on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-powershell-security-controls/"><u>The Ultimate Guide to PowerShell Security Controls</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/thriving-in-the-facebook-ecosystem-money-making-strategies-for-2024/"><u>Thriving in the Facebook Ecosystem  Money-Making Strategies for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-workflow-top-7-methods-for-windows-11-excellence/"><u>Transform Your Workflow: Top 7 Methods for Windows 11 Excellence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-o365-sync-issues-on-windows/"><u>Troubleshooting O365 Sync Issues on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tweaking-security-settings-for-general-pc-users-in-windows/"><u>Tweaking Security Settings for General PC Users in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/undo-customization-reverting-win11-user-permissions/"><u>Undo Customization: Reverting Win11 User Permissions</u></a></li>
<li><a href="https://techtrends.techidaily.com/unveiling-the-ultimate-collection-of-imessage-games-top-7-listed-here/"><u>Unveiling the Ultimate Collection of iMessage Games – Top 7 Listed Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11s-5-fixes-rectifying-secure-key-mismatch-errors/"><u>Win11's 5 Fixes: Rectifying Secure Key Mismatch Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-apps-to-supercharge-your-windows/"><u>Winning Apps to Supercharge Your Windows</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>