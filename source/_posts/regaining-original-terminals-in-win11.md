---
title: Regaining Original Terminals in Win11
date: 2024-08-16T01:30:48.637Z
updated: 2024-08-17T01:30:48.637Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Regaining Original Terminals in Win11
excerpt: This Article Describes Regaining Original Terminals in Win11
keywords: Win11 Terminal Reinstallation,Win11 Restore Hardware Settings,Win11 Revive Default Ports,Win11 Reset Network Terminals,Win11 Original Mode Reclamation,Win11 Initialization Restoration,Win11 Standard Terminal Setup
thumbnail: https://thmb.techidaily.com/d8236c8823bf190018d4a9a0035905199e51992e3c45e7b977770451483aa69d.jpg
---

## Regaining Original Terminals in Win11

 Windows Terminal is the next-generation command line platform in Windows 11\. It provides an improved user experience with modern command line tools that enable you to access multiple command lines in a single window. The tool is essential for developers and administrators alike, but sometimes your terminal settings need to be reset to default.

 In this article, we will explain how to reset your Windows Terminal settings back to their original state.

## Why Would You Reset Your Windows Terminal?

 Windows Terminal is an amazing tool for power users and developers. It allows you to access a variety of tools, all in one place, with custom settings and themes that make it easy to work from anywhere. But over time, your Windows Terminal may become cluttered with old settings or themes that have become redundant or are no longer relevant.

 It also helps clear out any potentially harmful malware or corrupt files that might be lurking in the background of your system, hindering your productivity. By doing so, you will ensure that your computer works as fast and as smoothly as possible - giving you the most optimal experience when using this powerful tool.

 Let's now move to the below sections and see how it can be reset.

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Reset Windows Terminal Settings by Clearing JSON Files

 In order to reset the settings back to the original defaults, you will need to delete the settings.json file. Here's how to do it.

1. Right click on Start and select**Terminal** from the menu list.
2. Next, click the down-arrow icon and select**Settings** .
3. From the left pane of the Settings page, click**Open JSON file** .  
![Open JSON file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-json-file.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
4. If you're asked which app to use to open the file, then double-click on**Notepad** .
5. On the next page, select all the contents and**Delete** them.
6. Now press**Ctrl + S** on your keyboard to save it.

 Next time you open the app, a new configuration with all the default settings will be created automatically.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Reset Windows Terminal Settings Using Command Prompt

 The Command Prompt is a command line tool that can help you accomplish a number of tasks on your computer. It lets you run programs, manage files, and even troubleshoot problems with the operating system. We covered a lot of its functionality in our [beginner's guide to the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) , but for now, we'll just explore resetting the Windows Terminal settings.

 To reset Windows Terminal Settings back to their defaults, follow these steps:

1. Open the Command Prompt. For this, use the Taskbar search or type "cmd" in the Run dialog.
2. In the Command Prompt window, copy and paste the following command:  
![Reset Windows Terminal Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-command-prompt.jpg)  
del /f /s /q /a "%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json"
3. Now press the**Enter** key to delete the settings.json file.
4. You can now exit the command prompt.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
## How to Reset Windows Terminal Settings Using Windows PowerShell

 Windows PowerShell is another command line application that you can use to restore Windows Terminal Settings to their default state. To figure out how, follow these steps:

1. Open Windows PowerShell. You can do this by pressing**Win + R** , typing "PowerShell", and then pressing**Enter** . You can also one of the other [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
2. In the PowerShell window, copy and paste the following command:  
![Reset Windows Terminal Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-powershell.jpg)  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
Remove-Item -Path "$env:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json" -Force
3. Press**Enter** to execute the command.

## How to Reset Windows Terminal Settings From File Explorer

 If you don't prefer the command line process, you can use Windows File Explorer to reset the settings. In this way, the Terminal will be reset to its default settings, and you can continue using it. Here's how to do it:

1. Open Windows File Explorer. For this, right-click Start and choose**File Explorer** , or press**Win + E** on your keyboard.
2. Copy and paste the following path into the address bar:  
![Reset Windows Terminal Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-file-explorer.jpg)  
<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState
3. On the next page, right-click on**settings.json** and select**Delete** from the context menu.

 Once you perform the above steps, Settings.json will automatically be created with the default settings.

## Resetting the Windows Terminal, Made Easy

 After reading this post, you now know some useful tips that will help you reset the terminal to default settings in Windows 11\. Try them out and find out which one works best for you.


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
<li><a href="https://youtube-webster.techidaily.com/0-unique-video-reaction-strategies-for-online-enthusiasts/"><u>[New] 10 Unique Video Reaction Strategies for Online Enthusiasts</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-quick-ways-to-retain-live-chat-transcripts/"><u>[New] 2024 Approved  Quick Ways to Retain Live Chat Transcripts</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-top-5-zero-price-screen-capture-software-for-windows-10-users/"><u>[New] 2024 Approved  Top 5 Zero Price Screen Capture Software for Windows 10 Users</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-a-beginners-guide-to-instagram-story-feature/"><u>[New] A Beginner's Guide to Instagram Story Feature</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-bridging-the-gap-between-individual-images-using-picshot/"><u>[New] Bridging the Gap Between Individual Images Using Picshot</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-avoiding-common-pitfalls-in-rl-gameplay-recordings/"><u>[New] In 2024, Avoiding Common Pitfalls in RL Gameplay Recordings</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-best-4k-screen-recorder-applications/"><u>[New] In 2024, Best 4K Screen Recorder Applications</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-most-popular-tiktok-filters-enhancing-video-quality/"><u>[New] Most Popular TikTok Filters Enhancing Video Quality</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-unblock-videos-from-twitter-in-chrome/"><u>[Updated] In 2024, Unblock  Videos From Twitter in Chrome</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-leveraging-dual-screen-capabilities-to-boost-your-facebook-presence/"><u>[Updated] Leveraging Dual-Screen Capabilities to Boost Your Facebook Presence</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-comedic-calls-ringtones-best-picks-online/"><u>2024 Approved  Comedic Calls  Ringtones' Best Picks Online</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/3-ways-to-export-contacts-from-apple-iphone-12-to-excel-csv-and-vcard-easily-drfone-by-drfone-transfer-from-ios/"><u>3 Ways to Export Contacts from Apple iPhone 12 to Excel CSV & vCard Easily | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disrupted-microphone-input-in-valorant-windows/"><u>Addressing Disrupted Microphone Input in Valorant (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-admin-username-on-windows-11-step-by-step-guide/"><u>Altering Admin Username on Windows 11: Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-language-skills-using-windows-1011-hotkeys/"><u>Boost Your Language Skills Using Windows 10/11 Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-system-startup-with-auto-auditory-restart-mechanism/"><u>Boosting System Startup with Auto Auditory Restart Mechanism</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breakdown-of-microsofts-earnings-through-windows-11/"><u>Breakdown of Microsoft's Earnings Through Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-no-wi-fi-in-windows-network/"><u>Breaking Down No Wi-Fi in Windows Network</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-windows-11-theme-barriers-using-registry/"><u>Breaking Through Windows 11 Theme Barriers Using Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diminish-noise-restoring-your-keys-sound-functionality/"><u>Diminish Noise: Restoring Your Key's Sound Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-reasons-to-never-turn-off-your-windows-11-push-notifications/"><u>Discover Reasons to Never Turn Off Your Windows 11 Push Notifications</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-airplane-mode-turn-off-gps-location-on-xiaomi-redmi-a2plus-drfone-by-drfone-virtual-android/"><u>Does Airplane Mode Turn off GPS Location On Xiaomi Redmi A2+? | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/1722975497375-easy-installation-get-your-latest-drivers-for-hp-devices-now/"><u>Easy Installation: Get Your Latest Drivers for HP Devices Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-device-safety-increase-win11-pin-length/"><u>Elevate Your Device Safety: Increase Win11 PIN Length</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-firewall-essential-fixes-for-a-shutdown-system/"><u>Enabling Firewall: Essential Fixes for a Shutdown System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-file-sharing-capabilities-in-geforce/"><u>Enhancing File-Sharing Capabilities in GeForce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-usability-faster-uninstall-options-in-win/"><u>Enhancing Usability: Faster Uninstall Options in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11-taskbar-responsiveness/"><u>Enhancing Windows 11 Taskbar Responsiveness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-updating-username-on-windows-11/"><u>Essential Guide to Updating Username on Windows 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/expert-guide-navigating-through-the-502-bad-gateway-mishap/"><u>Expert Guide: Navigating Through the 502 Bad Gateway Mishap</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-cut-down-on-menus-in-windows-11/"><u>How to Cut Down on Menus in Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-gmail-password-on-oppo-find-x7-ultra-devices-by-drfone-android/"><u>How to Reset Gmail Password on Oppo Find X7 Ultra Devices</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-do-honor-x50-gt-screen-sharing-drfone-by-drfone-android/"><u>In 2024, How To Do Honor X50 GT Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-lava-blaze-2-5g-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Lava Blaze 2 5G by Phone Number | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-oppo-a2-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Oppo A2? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/incorporating-external-disk-into-explorer-nav-pane/"><u>Incorporating External Disk Into Explorer Nav Pane</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-terminal-configuration-basics/"><u>Mastering Windows Terminal Configuration Basics</u></a></li>
<li><a href="https://change-location.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-samsung-galaxy-s21-fe-5g-2023-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Samsung Galaxy S21 FE 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/power-up-your-device-instantly-mastering-win-11s-double-clicked-apk-method/"><u>Power Up Your Device Instantly: Mastering Win 11'S Double-Clicked APK Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/put-a-halt-on-application-start-tracking-in-windows/"><u>Put a Halt on Application Start-Tracking in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-your-lost-dxgidll-with-these-win11-hacks/"><u>Restore Your Lost Dxgi.dll with These Win11 Hacks</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-files-back-from-infinix-smart-7-hd-by-fonelab-android-recover-data/"><u>Simple ways to get lost files back from Infinix Smart 7 HD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-resetting-windows-settings-on-reboot/"><u>Steps for Resetting Windows Settings on Reboot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-file-denial-in-steam-for-windows-11-users/"><u>Tackling File Denial in Steam for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-pathways-open-directory-games-in-windows/"><u>The Hidden Pathways: Open Directory Games in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-csgo-launch-failures-on-w11/"><u>Troubleshooting CS:GO Launch Failures on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-door-on-stuck-wow-61-patches/"><u>Unlocking the Door on Stuck WoW 6.1 Patches</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-best-free-green-screen-apps-for-mobile-devices-updated-2023/"><u>Updated 2024 Approved Best Free Green Screen Apps for Mobile Devices (Updated 2023)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-widely-used-directx-classics-through-dxvk/"><u>Upgrading Widely-Used DirectX Classics Through DXVK</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-xperia-1-v-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of Xperia 1 V on Mac?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-oneplus-11-5g-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On OnePlus 11 5G? | Dr.fone</u></a></li>
</ul></div>
