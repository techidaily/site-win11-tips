---
title: How to Open and Use the Windows Terminal in Quake Mode
date: 2024-08-16T01:31:23.964Z
updated: 2024-08-17T01:31:23.964Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Open and Use the Windows Terminal in Quake Mode
excerpt: This Article Describes How to Open and Use the Windows Terminal in Quake Mode
keywords: TerminalsQuakeModeBasics,WindowsTerminalUseTutorial,EnableWindowsTerminal,LaunchTerminalWindows,TerminalOptionsInWin,QuakeModeSetupWin,AccessWinTerminalUI
thumbnail: https://thmb.techidaily.com/3a8d29dc752129bc6cecd890184a07ba60927370b95afc8af67003c49b108b72.jpg
---

## How to Open and Use the Windows Terminal in Quake Mode

 The Windows Terminal is a Microsoft app used for working in command-line tools like PowerShell, Command Prompt, and WSL. It includes several useful features, including Quake Mode. And if you regularly need to enter command lines, Quake Mode is an efficient way to do it.

Here's how to enable and use Quake mode in Windows Terminal.

## What Is Quake Mode, and Why Should You Use It?

 Windows Terminal is a fast and efficient way to make using command-line tools easier. You can download it from the Microsoft Store.

![multiple tabs in the windows terminal app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/window-terminal-app.jpg)

 The key features of Windows Terminal include multiple tabs, panes, and a GPU-accelerated text rendering engine. There are also custom themes, styles, and configurations. And, of course, Quake mode which was added in version 1.9.

 When enabled, Quake mode lets you quickly open a new terminal instance from within any app. The terminal window opens from the top of the screen and fills the full-screen width. You can then hide the terminal window, keeping it ready to be opened whenever you need it.

 The name Quake mode refers to the similar-looking terminal window you could open in the iD Software game, Quake.

 If you don't know what Quake is, why not check out some [classic PC FPS games?](https://www.makeuseof.com/tag/play-classic-shooters-on-modern-computer/) Great fun, even if you have a modern PC.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Open Windows Terminal in Quake Mode

There are two ways to open the Windows Terminal in Quake mode.

 The first is to press**Win + R** to open the**Run dialog** . In the text field, type**wt -w \_quake** . Make sure you include the spaces after the t and before the underscore.

 You can also open the Windows Terminal app in the normal way. You can find it in the main Start Menu apps list if you are new to the app. With the app open in standard mode, press**Win + \`** (the grave accent button below Esc on the keyboard).

![The windows terminal in quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-terminal-quake.jpg)

 If you want the command-line tool to be run as an administrator, you will need to use the second method. Learn how to open [Windows PowerShell or Command Prompt as an administrator](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
## Hiding and Restoring the Terminal Window

 The idea of the Quake mode is to give the ability to have a terminal window always available. Even when in a full-screen app or if you can't click a terminal shortcut in the Taskbar.

 Once the Windows Terminal is in Quake mode, you can hide it by pressing**Win + \`** . It remains active but is hidden off-screen.

To reveal the window again, press the same keyboard shortcut.

 The Quake mode terminal window stretches the entire width of the screen. By default, it will fill about half the height of the screen. Unfortunately, you can't change the width, but you can click and drag the bottom edge of the panel to make it less intrusive.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
## Closing the Quake Mode Terminal Window

 As mentioned, the**Windows Key + \`** shortcut doesn't close the terminal window; it only hides it. Even closing the original Windows Terminal window won't remove the Quake mode window.

 When the Quake mode terminal window is on-screen, a terminal icon will appear in the Taskbar. You can hover over this icon and click the**X** on the peek preview window.

![The peek window for the Windows Terminal in quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/closing-quake-mode-window.jpg)

 If you don't see a peek preview, you can right-click on the terminal icon in the Taskbar and select**Close Window** .

 If the [Windows Taskbar is not working](https://www.makeuseof.com/tag/5-steps-fix-windows-10-taskbar-issues/) for some reason, these options won't be available. Instead, you can close the Quake mode terminal window by typing**EXIT** in the terminal and pressing**Return** .

## Start Windows Terminal in Quake Mode at Logon

 You can set the Terminal to open at logon in the PowerShell settings. But even if you have previously used Quake mode, the terminal will start in a normal window. You can get around this by creating a modified shortcut in shell:startup.

1. Type**Run** into Windows Search and open the Run Dialog.
2. Open the startup items folder by typing**shell:startup** , then click**Ok** .  
![creating a shortcut to quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/auto-open-quake-mode.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
3. Right-click anywhere in the folder and select**New > Shortcut** .
4. For the location of the item, type:**wt.exe -w \_quake** . Click**Next** .  
![shortcut to automatically open quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/quake-mode-shortcut.jpg)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Give the shortcut a name you will recognize, such as**Terminal Quake** . Then click**Finish** .

 The next time you log on to Windows, the terminal will open automatically in Quake Mode. You can then use it, or press the**Windows + \`** shortcut to minimize it.

 If you have [disabled app execution aliases](https://www.makeuseof.com/app-execution-aliases-guide/) , you will have to type or browse to the full path for the Windows Terminal. So instead of typing**wt.exe -w \_quake** , enter **C:\\Users\\\[username\]\\AppData\\Local\\Microsoft\\WindowssApps\\wt.exe -w \_quake** .

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Using the Windows Terminal's Quake Mode

 The Windows Terminal is a great way to work in command-line apps such as PowerShell and Windows Subsystem for Linux. Being able to run it in Quake mode means that you always have access to the terminal you need, no matter what you do on your PC.


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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-comprehensively-reviews-easeus-experts-unite/"><u>[New] 2024 Approved  Comprehensively Reviews EaseUS, Experts Unite</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-embedded-epicness-galaxy-games-chronicle/"><u>[New] Embedded Epicness  Galaxy Games Chronicle</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-fine-tune-video-quality-for-instagram-excellence-for-2024/"><u>[New] Fine-Tune Video Quality for Instagram Excellence for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-tiktok-top-ten-for-cutting-edge-content-creation/"><u>[New] TikTok Top Ten for Cutting-Edge Content Creation</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-top-8-gratis-video-cutting-tools-for-online-content-creation/"><u>[New] Top 8 Gratis Video Cutting Tools For Online Content Creation</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-advanced-5-cloud-view-recorder/"><u>[Updated] In 2024, Advanced 5 Cloud View Recorder</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-easy-steps-for-tempo-control-in-instagram-videos/"><u>[Updated] In 2024, Easy Steps for Tempo Control in Instagram Videos</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-comprehensive-overview-dji-inspire-2/"><u>2024 Approved  Comprehensive Overview - DJI Inspire 2</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-missing-link-prime-free-speech-to-text-on-macos/"><u>2024 Approved  Missing Link  Prime Free Speech to Text on macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-apps-to-increase-the-volume-beyond-100-percent-in-windows/"><u>4 Apps to Increase the Volume Beyond 100 Percent in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-win-hardware-testing-with-these-premier-graphics-tools/"><u>Ace Win Hardware Testing with These Premier Graphics Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-file-locks-turn-off-read-only-windows-mode/"><u>Altering File Locks: Turn Off Read-Only Windows Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-the-digital-snare-spotting-invisible-threats/"><u>Avoid the Digital Snare: Spotting Invisible Threats</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-htc-u23-pro-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For HTC U23 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-saved-audio-configurations-winvolume-hacks/"><u>Bring Back Saved Audio Configurations: WinVolume Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-amongst-windows-n-versions-key-considerations/"><u>Choosing Amongst Windows N Versions: Key Considerations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chrome-compatibility-with-windows-11-explained/"><u>Chrome Compatibility with Windows 11 Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-microsoft-teams-crashes-in-win11-and-win10-pcs/"><u>Combatting Microsoft Teams Crashes in Win11 & Win10 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cross-os-synergy-creating-a-linux-vm-inside-windows-using-hyper-v/"><u>Cross-OS Synergy: Creating a Linux VM Inside Windows Using Hyper-V</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cryptographic-shielding-data-safety-in-networked-drives/"><u>Cryptographic Shielding: Data Safety in Networked Drives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curing-wont-start-spotify-on-windows-1011-platforms/"><u>Curing Won't Start Spotify on Windows 10/11 Platforms</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/debunking-myths-how-environmentally-friendly-are-evs-really/"><u>Debunking Myths: How Environmentally Friendly Are EVs Really?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-code-effective-techniques-to-neutralize-wacatacbml/"><u>Deciphering the Code: Effective Techniques to Neutralize Wacatac.B!ml</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-airplane-mode-turn-off-gps-location-on-infinix-hot-30i-drfone-by-drfone-virtual-android/"><u>Does Airplane Mode Turn off GPS Location On Infinix Hot 30i? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-windows-terminals-quake-setting/"><u>Enabling Windows Terminal's Quake Setting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-performance-new-tech-in-microsoft-teams/"><u>Enhancing Performance: New Tech in Microsoft Teams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-reminders-before-overhauling-your-windows/"><u>Essential Reminders Before Overhauling Your Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-strategies-for-winning-with-the-windows-11-bar/"><u>Essential Strategies for Winning with the Windows 11 Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-commands-learn-the-top-20-cmd-tricks/"><u>Essential Windows Commands: Learn the Top 20 CMD Tricks</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-honor-magic-6-pro-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Honor Magic 6 Pro to iPhone | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-keywords-in-the-realm-of-virtual-reality/"><u>In 2024, Keywords in the Realm of Virtual Reality</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-new-look-samsungs-k850-ultrablade-review-2023/"><u>In 2024, New Look  Samsung's K850 UltraBlade Review 2023</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-troubleshooting-error-connecting-to-the-apple-id-server-from-apple-iphone-6s-plus-by-drfone-ios/"><u>In 2024, Troubleshooting Error Connecting to the Apple ID Server From Apple iPhone 6s Plus</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tutorial-to-change-samsung-galaxy-a05s-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>In 2024, Tutorial to Change Samsung Galaxy A05s IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://extra-information.techidaily.com/join-anytime-easy-zoom-integration-with-android-devices/"><u>Join Anytime  Easy Zoom Integration with Android Devices</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-landscapes-understanding-youtube-and-cc-divergences/"><u>Legal Landscapes  Understanding YouTube & CC Divergences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-privacy-activating-controlled-folder-access-in-windows-11/"><u>Mastering Privacy: Activating Controlled Folder Access in Windows 11</u></a></li>
<li><a href="https://extra-support.techidaily.com/maximize-your-laptops-dvd-potential-easily-for-2024/"><u>Maximize Your Laptop's DVD Potential Easily for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-windows-onedrive-crashes-effortlessly/"><u>Navigate Through Windows OneDrive Crashes Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-virtual-memory-settings-for-peak-windows-performance/"><u>Navigating Through Virtual Memory Settings for Peak Windows Performance</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-enhancing-musical-journeys-implementing-softening-effects-in-soundtracks/"><u>New Enhancing Musical Journeys Implementing Softening Effects in Soundtracks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/notepad-woes-on-pc-7-steps-to-reopen-the-favorite-text-editor/"><u>Notepad Woes on PC: 7 Steps to Reopen the Favorite Text Editor</u></a></li>
<li><a href="https://tech-revival.techidaily.com/pioneering-personalized-ais-crafting-your-own-chatgpt/"><u>Pioneering Personalized AIs: Crafting Your Own ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rebooting-lost-connectivity-winos-strategies/"><u>Rebooting Lost Connectivity: WinOS Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-and-render-vintage-videos-with-windows-madvr/"><u>Revamp and Render Vintage Videos with Windows MadVR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-the-malfunction-of-windows-delete-operation/"><u>Reversing the Malfunction of Windows Delete Operation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-data-sorting-adding-text-to-windows-11-folders/"><u>Simplifying Data Sorting: Adding Text to Windows 11 Folders</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/srt-deep-dive-core-principles-and-details-for-2024/"><u>SRT Deep Dive  Core Principles and Details for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stay-alert-stay-up-the-top-5-ways-to-monitor-win11-uptime/"><u>Stay Alert, Stay Up: The Top 5 Ways to Monitor Win11 Uptime</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-swashbucklers-overcome-delayed-gameplay-in-sw-bf2/"><u>Swift Swashbucklers: Overcome Delayed Gameplay in SW BF2</u></a></li>
<li><a href="https://facebook.techidaily.com/the-covert-elements-filtering-your-fb-timeline/"><u>The Covert Elements Filtering Your Fb Timeline</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/the-right-move-copyright-validation-before-posting-on-tiktok-for-2024/"><u>The Right Move  Copyright Validation Before Posting on TikTok for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-computing-the-ai-enhanced-windows/"><u>Transforming Computing: The AI-Enhanced Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-infinix-note-30-vip-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Infinix Note 30 VIP? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-preparedness-generate-boot-media-in-three-steps/"><u>Windows 11 Preparedness: Generate Boot Media in Three Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-playnite-integrating-virtual-game-archives/"><u>Winning Playnite: Integrating Virtual Game Archives</u></a></li>
</ul></div>
