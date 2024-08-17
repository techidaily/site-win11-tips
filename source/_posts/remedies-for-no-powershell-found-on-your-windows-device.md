---
title: Remedies for No PowerShell Found on Your Windows Device
date: 2024-08-16T02:19:45.053Z
updated: 2024-08-17T02:19:45.053Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedies for No PowerShell Found on Your Windows Device
excerpt: This Article Describes Remedies for No PowerShell Found on Your Windows Device
keywords: PowerShell Woes,Fixing No PowerShell,PowerShell Not Available,Resolve PowerShell Errors,Enable PowerShell,Troubleshoot Missing PowerShell,Restore Windows Powershell
thumbnail: https://thmb.techidaily.com/046b51c249713a58e7f91807e73ec08e3a40b03e4add7fe4a3b9657a9796ae66.jpg
---

## Remedies for No PowerShell Found on Your Windows Device

 PowerShell is a handy tool that lets you automate tasks, troubleshoot various errors, and manage a variety of Windows settings. But what if it suddenly goes missing from your computer?

 If you use PowerShell frequently, it can be aggravating when Windows cannot find it. Thankfully, it’s possible to restore the missing PowerShell with a few troubleshooting tips. In this post, we'll walk you through all of them.

## 1\. Make Sure Windows PowerShell Is Enabled

 On Windows, you can enable or disable optional features and programs from the Control Panel. To start, you need to ensure that PowerShell isn’t disabled on your computer. Here’s how to check.

1. Press**Win + R** to open the Run dialog.
2. Type**control** in the box and press**Enter** to open Control Panel.
3. Click the drop-down menu in the top right corner to select**Large icons** .
4. Go to**Programs and Features** .
5. Click the**Turn Windows features on or off** link from the left pane.
6. When the User Account Control (UAC) prompt appears, select**Yes** to continue.
7. In the Windows Features dialog, locate**Windows PowerShell** and select its checkbox.
8. Click**OK** to save the changes.  
![Enable PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Enable-PowerShell-on-Windows.jpg)

 Restart your computer after this (see [how to restart a Windows computer](https://www.makeuseof.com/windows-restart-methods/) ) and then try to launch PowerShell using the search menu.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Launch PowerShell Using Run Command or File Explorer

 If you are unable to open PowerShell via the search menu, you can try using the Run dialog box. Press**Win + R** to open the Run dialog. Type**powershell** in the box and press**Enter** . If you want to launch PowerShell with admin rights, press**Ctrl + Shift + Enter** instead.

![Open PowerShell via Run Command on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Open-PowerShell-via-Run-Command-on-Windows.jpg)

 You can also open PowerShell from the File Explorer address bar. To do so, press**Win + E** to open File Explorer. Type**PowerShell** in the address bar and press**Enter** .

## 3\. Create a Desktop Shortcut for PowerShell

 Windows may fail to open PowerShell if it does not know the exact file path to the PowerShell executable file. If that’s the case, you can manually locate the PowerShell executable file on your computer and create a desktop shortcut for it. Here are the steps for doing the same.

1. Right-click on the**Start icon** to open the Power User menu and select**File Explorer** from the list.
2. Navigate to**This PC** .
3. Head over to**C: > Windows > SysWOW64** and locate**WindowsPowerShell** folder.
4. Open the WindowsPowerShell folder and go to the**v1.0** folder.
5. Double-click on the PowerShell executable file and see if it works. If it does, right-click on it and select**Send to > Desktop (create shortcut)** .  
![Create Desktop Shortcut for PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Create-Desktop-Shortcut-for-PowerShell-on-Windows.jpg)
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can then use the newly created desktop shortcut to launch PowerShell. For added convenience, you can assign a keyboard shortcut to PowerShell. To learn more about this, check our guide on [how to assign keyboard shortcuts to programs in Windows](https://www.makeuseof.com/windows-keyboard-shortcuts-programs/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
## 4\. Scan Your Computer for Corrupted System Files

 Damaged or corrupted system files can also interfere with Windows operations and prevent PowerShell from launching. Fortunately, your Windows PC comes with a few built-in tools, such as SFC (System File Checker) and DISM (or Deployment Image Servicing and Management) that can help you with such issues. If Windows suffers from system file corruption, running these tools will fix the problem.

To run the SFC scan on Windows:

1. Click the magnifying glass icon on the taskbar or press**Win + S** to open the search menu.
2. Type**command prompt** in the search box and select**Run as administrator** from the right panel.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Type**SFC /scannow** in the console and press**Enter** .

 The SFC scan will start verifying the integrity of your system files and fix any issues with them. The scan might take a while, so be patient.

 Next, you need to run the DISM scan. This is another diagnostic tool that Windows offers. It can automatically detect any issues with the system image and fix them. If you want to learn more about them, check out our guide on the [differences between CHKDSK, SFC, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) .

 To run DISM,[open Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) again. Paste the following command in the console and press**Enter** .

`DISM.exe /Online /Cleanup-image /Restorehealth`

![DISM Scan Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/DISM-Scan-Windows.jpg)

 Wait for the command to execute successfully, and then restart your PC. Following that, see if Windows can find PowerShell on your computer.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 5\. Update Windows PowerShell

 If Windows still can't find PowerShell at this point, there could be a problem with the PowerShell app itself. You can try updating the PowerShell app to see if that makes any difference.

To update PowerShell on Windows:

1. Press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. When the User Account Control (UAC) prompt shows up, select**Yes** .
4. Type the following command and press**Enter** .  
`winget install --id Microsoft.Powershell --source winget`  
![Update PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Update-PowerShell-on-Windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->

 Windows will download and install the most recent version of PowerShell. Following that, you should be able to access PowerShell.

 Using Command Prompt isn't the only way to update PowerShell on Windows. If you want to learn other methods, check our guide on [how to install or update PowerShell on Windows](https://www.makeuseof.com/windows-11-powershell-install-update/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## 6\. Create a New User Account

 It's possible that the PowerShell not opening problem is limited to your current user account. In that case, you can create and switch to a new user account and see if that works.

To create a new user account on Windows, use these steps.

1. Open the start menu and click the**gear icon** to open the Settings app.
2. Navigate to**Accounts** .
3. Select**Other users** .
4. Click the**Add account** button.
5. Click on **I don't have this person's sign-in information** and follow the on-screen prompts to create a new user account.  
![Microsoft Account Sign-In](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Microsoft-Account-Sign-In.jpg)

 Sign in with your newly created account, and see if Windows can find PowerShell now.

## Access Windows PowerShell Again

 Hopefully, one of the above fixes has proven useful, and you're able to access PowerShell once again. If not, you may have to consider resetting your Windows computer as a last resort.

 PowerShell isn't the only command-line tool available on Windows. You can also use the Command Prompt to communicate with your system.


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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-crafting-dynamic-web-pages-with-php-and-html/"><u>[New] 2024 Approved  Crafting Dynamic Web Pages with PHP and HTML</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-youtube-snippets-get-high-quality-images-without-a-penny-paid/"><u>[New] 2024 Approved  YouTube Snippets  Get High-Quality Images Without a Penny Paid</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-how-to-use-the-blending-modes-to-composite-clips-for-2024/"><u>[New] How to Use The Blending Modes To Composite Clips for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-fast-track-choosing-best-pc-game-speed-extensions/"><u>[New] In 2024, Fast Track  Choosing Best PC Game Speed Extensions</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-acid-pro-alternatives-a-comprehensive-guide-for-2024/"><u>[Updated] ACID Pro Alternatives  A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-expert-tips-for-mastering-iphones-sound-capture/"><u>[Updated] In 2024, Expert Tips for Mastering iPhone's Sound Capture</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-tweetbite-download-twitter-vids-with-mobile-app/"><u>[Updated] In 2024, TweetBite  Download Twitter Vids with Mobile App</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-optimizing-your-chromebooks-zoom-capabilities/"><u>[Updated] Optimizing Your Chromebook's Zoom Capabilities</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-pinnacle-creations-synopsis-in-depth-studio-scrutiny/"><u>[Updated] Pinnacle Creations Synopsis  In-Depth Studio Scrutiny</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/best-infinix-frp-bypass-guide-by-drfone-android/"><u>Best Infinix FRP Bypass Guide</u></a></li>
<li><a href="https://win-blog.techidaily.com/bypassing-the-blockade-how-to-successfully-launch-your-adobe-app-after-encountering-error-0xc0000-(b)c(b)22/"><u>Bypassing the Blockade: How to Successfully Launch Your Adobe App After Encountering Error 0xC0000 <B>c</B>22</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-windows-dns-cache-via-steam-settings/"><u>Clearing Windows DNS Cache via Steam Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/compute-disk-space-efficiently-via-powershell-commands/"><u>Compute Disk Space Efficiently via PowerShell Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/corrective-measures-for-copy-pasting-malfunction/"><u>Corrective Measures for Copy-Pasting Malfunction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-audio-recording-the-windows-11-handbook/"><u>Easy Audio Recording: The Windows 11 Handbook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-secure-data-movement-in-microsoft-edge-shield-for-w11/"><u>Enabling Secure Data Movement in Microsoft Edge Shield for W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-archived-media-madvr-for-windows-enthusiasts/"><u>Enhance Archived Media: MadVR for Windows Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-computer-functionality-post-intel-hardware-violation/"><u>Enhancing Computer Functionality Post-Intel Hardware Violation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-disk-read-windows-error-immediately/"><u>Fixing 'Disk Read' Windows Error Immediately</u></a></li>
<li><a href="https://screen-recording.techidaily.com/from-pixels-to-perfection-selecting-the-premier-screen-recording-software/"><u>From Pixels to Perfection  Selecting the Premier Screen Recording Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-turn-off-microsofts-voice-assistant/"><u>Guide to Turn Off Microsoft's Voice Assistant</u></a></li>
<li><a href="https://driver-download.techidaily.com/how-to-easily-update-your-sound-card-drivers-with-the-latest-realtek-alc892aic7380-software-on-windows-11/"><u>How to Easily Update Your Sound Card Drivers with the Latest Realtek ALC892/AIC7380 Software on Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-oppo-find-x6-pro-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Oppo Find X6 Pro PC | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-honor-90-lite-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Honor 90 Lite | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-list-of-pokemon-go-joysticks-on-vivo-v30-lite-5g-drfone-by-drfone-virtual-android/"><u>In 2024, List of Pokémon Go Joysticks On Vivo V30 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/latency-logic-how-to-quickly-examine-ethernet-performance/"><u>Latency Logic: How to Quickly Examine Ethernet Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-directory-management-without-renaming-feature-in-win-11/"><u>Mastering the Art of Directory Management without Renaming Feature in Win 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-elevating-audio-standards-top-10-sound-upgraders-for-smartphones-androidios-for-2024/"><u>New Elevating Audio Standards Top 10 Sound Upgraders for Smartphones (Android/iOS) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-playtime-configuring-amd-card-in-windows-games/"><u>Perfecting Playtime: Configuring AMD Card in Windows Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/powerful-scripts-to-detect-pcs-ip-and-mac/"><u>Powerful Scripts to Detect PC's IP and MAC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-lost-steam-connections-on-pc/"><u>Quick Fixes for Lost Steam Connections on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-reds-greens-and-blues-avoiding-windows-color-confusion/"><u>Resolving Reds, Greens & Blues: Avoiding Windows' Color Confusion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-sync-path-for-android-plus-windows-duo/"><u>Step-by-Step Sync Path for Android + Windows Duo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-correct-windows-alt-key-problems/"><u>Strategies to Correct Windows ALT Key Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-temporary-file-extraction-in-windows-os/"><u>Streamlining Temporary File Extraction in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-addressing-faulty-or-missing-device-alerts-win1011/"><u>Tips for Addressing Faulty or Missing Device Alerts, Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-from-thx-spatial-issues/"><u>Unblocking Windows From THX Spatial Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-network-potential-through-dns-on-windows-11/"><u>Unlocking Network Potential Through DNS on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-nas-on-smartphones-and-tablets/"><u>Utilizing NAS on Smartphones and Tablets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1110-resolving-code-xc0000142-failure/"><u>Windows 11/10: Resolving Code XC0000142 Failure</u></a></li>
</ul></div>
