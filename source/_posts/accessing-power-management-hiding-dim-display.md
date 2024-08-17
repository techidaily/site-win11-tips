---
title: "Accessing Power Management: Hiding 'Dim Display'"
date: 2024-08-16T01:19:40.147Z
updated: 2024-08-17T01:19:40.147Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Accessing Power Management: Hiding 'Dim Display'"
excerpt: "This Article Describes Accessing Power Management: Hiding 'Dim Display'"
keywords: Dim Display Control,Manage Screen Brightness,Power Saving Mode Access,Reduce Display Usage,Low Energy Settings,Hidden Power Mgmt,Save Battery Life
thumbnail: https://thmb.techidaily.com/b02903fae7318467ee1d2a7ec684be197bec9e28a2f1680afb2687afaf4dfa29.jpg
---

## Accessing Power Management: Hiding 'Dim Display'

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
## Controlling the “Dim Display After” Option in the Power Options Menu

 Now that you know how to show or hide **Dim display after**, you know what to do when you can’t find it in the Power Options menu or need to remove it. We recommend keeping it hidden and then bringing it up whenever you need it. This will make sure that no one messes with this important display setting when you’ve set it up perfectly.

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
<li><a href="https://some-skills.techidaily.com/new-unravel-the-mysteries-of-morphvox-the-ultimate-guide-to-voice-modification/"><u>[New] Unravel the Mysteries of MorphVOX  The Ultimate Guide to Voice Modification</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-unbeatable-freefire-gaming-hashtag-and-strategy-insights/"><u>[Updated] Unbeatable FreeFire Gaming  Hashtag & Strategy Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-fix-the-steam-must-be-running-to-play-this-game-error-in-windows-11/"><u>7 Ways to Fix the Steam Must Be Running to Play This Game Error in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-11s-resolution-settings/"><u>Adjusting Windows 11'S Resolution Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-virtual-machine-security-with-vboxs-secure-boot-toggle/"><u>Boost Virtual Machine Security with VBox's Secure Boot Toggle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boot-into-peace-five-tactics-to-overcome-windows-security-failures/"><u>Boot Into Peace: Five Tactics to Overcome Windows Security Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-windows-11-blackout-with-easy-tips-and-tricks/"><u>Bypass Windows 11 Blackout with Easy Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-privilege-needed-blue-screen-windows-fix-guide/"><u>Bypassing 'Privilege Needed' Blue Screen: Windows Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-your-windows-11-experience-with-nircmd-tips/"><u>Command Your Windows 11 Experience with NirCmd Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-rectify-cant-add-your-folder-now-in-onedrive/"><u>Essential Steps to Rectify 'Can't Add Your Folder Now' In OneDrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-disparities-in-cloud-and-offline-windows-updates/"><u>Exploring Disparities in Cloud and Offline Windows Updates</u></a></li>
<li><a href="https://win-solutions.techidaily.com/fixing-microsoft-edge-crashes-troubleshooting-tips-for-windows-11-users/"><u>Fixing Microsoft Edge Crashes: Troubleshooting Tips for Windows 11 Users</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/harness-online-tools-for-free-fb-video-conversion-to-1080p720p-mp4-for-2024/"><u>Harness Online Tools for Free FB Video Conversion to 1080P/720p MP4 for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-overcome-hp-laserjet-p2035-printer-drivers-error-on-microsoft-windows/"><u>How to Overcome HP LaserJet P2035 Printer Drivers Error on Microsoft Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-reset-iphone-13-mini-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Reset iPhone 13 mini? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-keygen-malware-on-windows-recognition-and-eradication-steps/"><u>Identifying Keygen Malware on Windows: Recognition and Eradication Steps</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/in-2024-google-translate-video-a-complete-guide-to-translate-video-with-google/"><u>In 2024, Google Translate Video A Complete Guide To Translate Video With Google</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-highest-rated-video-call-software-not-zoom-for-pcs-and-phones/"><u>In 2024, Highest-Rated Video Call Software (Not Zoom) for PCs & Phones</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-insider-guide-to-efficient-windows-10-usage/"><u>In 2024, The Insider Guide to Efficient Windows 10 Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lighter-browsing-experience-on-the-desktop-top-7-test-results/"><u>Lighter Browsing Experience on the Desktop: Top 7 Test Results</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-net-restoration-on-your-machine-max-156/"><u>Mastering .NET Restoration on Your Machine (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-pc-storage-identifying-excess-disk-usage-in-windows/"><u>Maximizing PC Storage: Identifying Excess Disk Usage in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-challenging-c0000022-failure-in-windows/"><u>Navigating Through the Challenging C0000022 Failure in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/organize-windows-icons-harmoniously/"><u>Organize Windows Icons Harmoniously</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-nvidia-connect-error-in-windows-oses/"><u>Overcoming NVIDIA Connect Error in Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-win11s-security-measures-through-rufus-mastery/"><u>Overcoming Win11's Security Measures Through Rufus Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-unreachable-network-paths/"><u>Overcoming Windows' Unreachable Network Paths</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-dive-into-your-pcs-core-settings/"><u>Quick Dive Into Your PC's Core Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-absent-system-cooling-policy-in-pcs/"><u>Reinstating Absent System Cooling Policy in PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-chrome-profiles-issues-on-windows-devices/"><u>Resolving Chrome Profiles Issues on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/say-goodbye-to-old-files-enabling-the-autodelete-option-on-windows-11/"><u>Say Goodbye to Old Files: Enabling the Autodelete Option on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-wirelessly-link-dualshock-3-and-win/"><u>Seamless Integration: Wirelessly Link DualShock 3 & Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stay-connected-disable-usb-sleep-on-windows-11-pc/"><u>Stay Connected: Disable USB Sleep on Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-error-0x00000709/"><u>Steps to Rectify Error 0X00000709</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-revitalize-stuck-and-slow-downloads-in-windows-directory/"><u>Steps to Revitalize Stuck and Slow Downloads in Windows Directory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-unlocking-screen-pin-free-windows-projection/"><u>Stop Unlocking Screen: PIN-Free Windows Projection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-address-unsuccessful-onedrive-procedures/"><u>Strategies to Address Unsuccessful OneDrive Procedures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-lcd-panels-simplified-guide/"><u>Switching LCD Panels Simplified Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-free-gaming-setup-dualshock-for-windows-users/"><u>Tech-Free Gaming Setup: DualShock for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-5-best-torrent-clients-for-windows/"><u>The 5 Best Torrent Clients for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/thriving-without-11-upgrade-boost-your-pc-health/"><u>Thriving Without 11 Upgrade: Boost Your PC Health</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-dark-displays-during-win-games/"><u>Troubleshooting Dark Displays During Win Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turning-spoken-words-into-written-phrases-a-guide-for-windows-users/"><u>Turning Spoken Words Into Written Phrases: A Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-full-potential-of-the-windows-key/"><u>Unlocking Full Potential of the Windows Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-content-restricted-in-windows-steam/"><u>Unraveling Content Restricted in Windows Steam</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-infinix-hot-40-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Infinix Hot 40 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-activate-educational-themes/"><u>Win 11: Activate Educational Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-troubleshooting-for-elusive-temp-files/"><u>Windows Troubleshooting for Elusive Temp Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-customization-increasing-icon-dimensions-in-w11/"><u>Winning at Customization: Increasing Icon Dimensions in W11</u></a></li>
</ul></div>
