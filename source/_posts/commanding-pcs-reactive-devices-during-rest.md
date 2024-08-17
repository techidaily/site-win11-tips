---
title: Commanding PC's Reactive Devices During Rest
date: 2024-08-16T02:34:06.381Z
updated: 2024-08-17T02:34:06.381Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Commanding PC's Reactive Devices During Rest
excerpt: This Article Describes Commanding PC's Reactive Devices During Rest
keywords: Pcs React Device Command,PC Device Response,Active Pc Control,Rest Mode Device Commands,Pc Device Restore,Reactive Devices in Pc,PCs Manage Device Idle
thumbnail: https://thmb.techidaily.com/50cbd8d07e0873a4343caac1afaca4ba3bdd492ab0995e73547b18cbc746d1e9.png
---

## Commanding PC's Reactive Devices During Rest

 When not in use, putting your Windows PC to sleep is an excellent way to preserve its battery life. You can wake your computer at any time by simply wiggling the mouse, pressing the power button, or pressing a key on your keyboard.

 Windows gives you complete control over devices that can wake your computer from a sleep state. In this guide, we will discuss how you can manage those devices.

## How to Check Which Devices Are Capable of Waking Your Windows PC From Sleep Mode

 Not every device connected to your system can wake Windows from sleep mode. You can use Command Prompt or Windows PowerShell to determine which of your devices supports waking the computer.

1. Press**Win + S** to open the search menu.
2. Type in**Windows PowerShell** and select**Run as administrator** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command and press**Enter** to view a list of devices on your system that can wake Windows from any sleep state.  
`powercfg -devicequery wake_from_any`  
![Devices That Can Wake Windows From Sleep Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Devices-That-Can-Wake-Windows-From-Sleep-Mode.jpg)

 On this list, you'll see devices like your keyboard, mouse, network adapter, and more.

## How to Check Which Devices Are Allowed to Wake Your Windows PC From Sleep Mode

 Command Prompt or PowerShell can also tell you which devices are permitted to wake your Windows PC from sleep mode. Here's how to find out.

1. [Open Command Prompt or Windows PowerShell](https://www.makeuseof.com/windows-open-command-prompt-powershell/) on your PC.
2. Type the following command and press**Enter** to view a list of devices that are allowed to wake your computer from sleep mode.  
`powercfg -devicequery wake_armed`  
![Devices Are Allowed to Wake Your Windows PC From Sleep Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Devices-Are-Allowed-to-Wake-Your-Windows-PC-From-Sleep-Mode.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Find Out What Woke Your Windows PC From Sleep Mode

 Many times, you may find that your Windows computer wakes from sleep mode on its own. Often, it's one of the connected devices or processes that causes your computer to wake up. Windows can tell you exactly what woke your computer from sleep mode.

1. Press**Win + R** to open the Run dialog.
2. Type**cmd** in the box and press**Ctrl + Shift + Enter** to[launch Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
3. Input the following command and press**Enter** .  
`powercfg -lastwake`  
![Check What Woke Windows From Sleep](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-What-Woke-Windows-From-Sleep.jpg)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you run the above command, Windows will tell you which device or process woke your computer from sleep mode.

 If you see something like**Wake History Count - 0** , it means that Windows doesn't have a record of wake history. This can happen if you've recently rebooted your computer.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
## How to Allow or Deny a Device Permission to Wake Your Windows PC From Sleep Mode

 Once you know which devices are waking up your computer without your consent, you can take the necessary steps to prevent them from doing so.

To allow or deny a device permission to wake your computer:

1. Press**Win + X** to open the Power User menu.
2. Select**Device Manager** from the list.
3. Locate the device you want to configure. Right-click on it and select**Properties** .
4. In the Properties window, switch to the**Power Management** tab.
5. Check or uncheck the**Allow this device to wake the computer** checkbox to allow or disallow the permission.
6. Click**OK** to save the changes.  
![Allow or Disallow Device to Wake Computer on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Allow-or-Disallow-Device-to-Wake-Computer-on-Windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->

 You can repeat the above steps to configure power management settings for more devices if you want.

 Aside from your devices, your network connections, scheduled tasks, and background wake timers can also wake Windows from sleep mode. If you want to stop that from happening, check our guide on[how to prevent your Windows computer from waking up randomly](https://www.makeuseof.com/tag/stop-windows-computer-randomly-waking/) .

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Manage Your Computer’s Sleep

 Now you know what devices can wake your computer from a sleep state and how to prevent them from doing so. That said, putting your computer in sleep mode may not always be the best option for your laptop. Sometimes, it’s better to shut it down completely.


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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-earning-in-a-world-dominated-by-youtubers/"><u>[New] 2024 Approved  Earning in a World Dominated by YouTubers</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-streamlined-processes-from-camera-roll-to-snapchat-posting/"><u>[New] 2024 Approved  Streamlined Processes  From Camera Roll to Snapchat Posting</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-ace-your-social-media-game-essential-video-marketing-techniques-on-facebook/"><u>[New] In 2024, Ace Your Social Media Game  Essential Video Marketing Techniques on Facebook</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-facebooks-approach-for-automatic-youtube-video-playback/"><u>[Updated] 2024 Approved  Facebook's Approach for Automatic YouTube Video Playback</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-transform-your-feed-a-comprehensive-guide-to-videos/"><u>[Updated] Transform Your Feed  A Comprehensive Guide to Videos</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-ultimate-guide-to-closer-insight-in-roblox-games/"><u>2024 Approved  The Ultimate Guide to Closer Insight in Roblox Games</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-ultimate-tune-master-app-for-android/"><u>2024 Approved  Ultimate Tune Master App for Android</u></a></li>
<li><a href="https://program-issues.techidaily.com/2024-ultimate-solution-overcoming-path-of-exiles-instance-connection-problems/"><u>2024 Ultimate Solution: Overcoming Path of Exile's Instance Connection Problems</u></a></li>
<li><a href="https://extra-hints.techidaily.com/boosting-your-stream-quality-with-zoom-and-fb-live/"><u>Boosting Your Stream Quality with ZOOM & FB Live</u></a></li>
<li><a href="https://unlock-android.techidaily.com/can-i-bypass-a-forgotten-phone-password-of-honor-90-lite-by-drfone-android/"><u>Can I Bypass a Forgotten Phone Password Of Honor 90 Lite?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-change-the-brightness-of-your-windows-11-pc-here-are-8-ways-to-fix-it/"><u>Can't Change the Brightness of Your Windows 11 PC? Here Are 8 Ways to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphered-defense-dont-shift-too-suddenly/"><u>Deciphered Defense? Don't Shift Too Suddenly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-dilemran-of-winscripterrors/"><u>Deciphering the Dilemran of WinScriptErrors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-how-to-access-mspaint-in-windows-11/"><u>Discovering How to Access MSPaint in Windows 11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/discovering-the-best-music-playback-on-youtube-2023-for-2024/"><u>Discovering the Best Music Playback on YouTube, 2023 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/displaying-caps-lock-and-numeric-status-on-taskbar-tray-of-win11/"><u>Displaying Caps Lock & Numeric Status on Taskbar Tray of Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-full-use-of-the-control-key-in-windows-11/"><u>Enabling Full Use of the Control Key in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-smooth-background-operations-with-edge-in-win11/"><u>Ensuring Smooth Background Operations with Edge in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essentials-of-windows-diagnostics-compiling-and-analyzing-data/"><u>Essentials of Windows Diagnostics: Compiling & Analyzing Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-versatile-applications-top-10-ways-to-use-powertoys/"><u>Explore Versatile Applications: Top 10 Ways to Use PowerToys</u></a></li>
<li><a href="https://facebook.techidaily.com/fb-breathes-easier-entire-energy-sourced-from-nature/"><u>FB Breathes Easier: Entire Energy Sourced From Nature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/file-system-exploration-in-win11-6-keyways-to-duplicating-file-and-folder-paths/"><u>File System Exploration in Win11: 6 Keyways to Duplicating File and Folder Paths</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-unsolicited-opens-in-ms-store-on-windows-10/"><u>Halt Unsolicited Opens in MS Store on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-copy-paste-not-working-in-chrome-edge-and-firefox-on-windows/"><u>How to Fix Copy-Paste Not Working in Chrome, Edge, and Firefox on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manage-access-to-registry-tools-in-win11/"><u>How to Manage Access to Registry Tools in Win11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-honor-100-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Honor 100? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-guide-for-installing-windows-11-arm-via-iso-download/"><u>How-To Guide for Installing Windows 11 ARM via ISO Download</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-14-passcode-without-computer-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 14 Passcode without Computer?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-tips-of-transferring-messages-from-poco-x6-to-iphone-1415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Tips of Transferring Messages from Poco X6 to iPhone 14/15 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-your-pc-with-hyper-v-on-windows-11/"><u>Jumpstart Your PC with Hyper-V on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-windows-startup-the-comprehensive-guidebook/"><u>Master Your Windows Startup: The Comprehensive Guidebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-model-names-unraveling-your-device-in-six-easy-ways/"><u>Mastering Model Names: Unraveling Your Device in Six Easy Ways</u></a></li>
<li><a href="https://howto.techidaily.com/reasons-for-lava-blaze-2-5g-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Lava Blaze 2 5G Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/recording-rivals-meet/"><u>Recording Rivals, Meet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-smooth-asana-operations-on-pcs/"><u>Restoring Smooth Asana Operations on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-to-effortless-transitions-into-game-fullscreen/"><u>Secrets to Effortless Transitions Into Game FullScreen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shift-key-woes-try-these-fixes-now/"><u>Shift Key Woes? Try These Fixes Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steering-clear-of-stuck-warcraft-patches/"><u>Steering Clear of Stuck Warcraft Patches</u></a></li>
<li><a href="https://media-tips.techidaily.com/step-by-step-guide-transforming-mxf-files-into-editable-formats-for-imovie-using-a-reliable-mxf-converter-on-your-mac/"><u>Step-by-Step Guide: Transforming MXF Files Into Editable Formats for iMovie Using a Reliable MXF Converter on Your Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-enable-digital-supervision-in-windows-11-pcs/"><u>Steps to Enable Digital Supervision in Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-prevent-date-changes-on-windows-pcs/"><u>Steps to Prevent Date Changes on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-playback-launching-windows-media-player/"><u>Streamline Playback: Launching Windows Media Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-typing-snippets-and-hotkeys-on-windows/"><u>Streamline Your Typing: Snippets & Hotkeys on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-non-definable-error-in-windows-environment/"><u>Tackling 'Non-Definable' Error in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-frozen-volume-shadows-in-operating-systems/"><u>Tackling Frozen Volume Shadows in Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-optimize-msi-startstop-functionality/"><u>Tactics to Optimize MSI Start/Stop Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-innovators-guide-leveraging-windows-11-widgets/"><u>Tech Innovators Guide: Leveraging Windows 11 Widgets</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-three-faces-of-microsofts-language-model-exploring-gpt-4-turbo-and-advanced-editions/"><u>The Three Faces of Microsoft's Language Model: Exploring GPT-4, Turbo & Advanced Editions</u></a></li>
<li><a href="https://fox-blue.techidaily.com/transforming-views-to-interactions-a-telegram-strategy-guide/"><u>Transforming Views to Interactions  A Telegram Strategy Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-write-file-access-issue-on-windows-1011/"><u>Troubleshooting Write File Access Issue on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-why-files-carry-an-x-marking/"><u>Understanding Why Files Carry an X Marking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-ftdibussys-its-impact-on-windows-memory-protocols/"><u>Unraveling ftdibus.sys: Its Impact on Windows Memory Protocols</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-typical-windows-rainmeter-setbacks-and-how-to-overcome-them/"><u>Unraveling Typical Windows Rainmeter Setbacks and How to Overcome Them</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-the-cyber-game-top-7-techniques-for-uac-safety/"><u>Winning the Cyber Game: Top 7 Techniques for UAC Safety</u></a></li>
<li><a href="https://techidaily.com/xiaomi-won-t-play-hevc-h-265-media-how-to-fix-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Xiaomi won’t play HEVC H.265 media, how to fix?</u></a></li>
</ul></div>
