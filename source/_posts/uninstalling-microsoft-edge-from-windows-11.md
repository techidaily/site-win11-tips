---
title: Uninstalling Microsoft Edge From Windows 11
date: 2024-08-16T02:28:07.549Z
updated: 2024-08-17T02:28:07.549Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Uninstalling Microsoft Edge From Windows 11
excerpt: This Article Describes Uninstalling Microsoft Edge From Windows 11
keywords: Uninstall Edge Browser,Removing Microsoft Edge,Delete Edge App,Disable Edge on Win11,Remove Edge From PC,Stop Microsoft Edge,End Microsoft Edge Usage
thumbnail: https://thmb.techidaily.com/6fa8c212e32cacf403b164cddaa0641d8c8c9740158f0e616afbd57801dea413.jpg
---

## Uninstalling Microsoft Edge From Windows 11

 Although Microsoft Edge has made significant progress in recent years, it still lags far behind its biggest rival—Google Chrome. If you’re someone who does not like using Microsoft Edge, you may want to get rid of the browser entirely.

 It’s no secret that Microsoft wants users to use its own browser on Windows 11\. To that end, the company has made it difficult to remove the browser from Windows 11\. However, it’s still possible to do so. Here we'll show you three different ways to uninstall Microsoft Edge from your Windows 11 PC.

## 1\. How to Uninstall Microsoft Edge Using the Command Prompt

 You can uninstall Microsoft Edge from your PC by running a few commands in the command prompt. The process requires you to know the version number of Microsoft Edge on your computer. Once you have that, you can get rid of the browser.

Here are the steps you need to follow.

1. Open Microsoft Edge on your PC.
2. Click the**three-dot menu icon** in the top right corner and select**Help and feedback > About Microsoft Edge** .
3. Copy Microsoft Edge's version number from the**About** section.  
![Check Microsoft Edge Version Number](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Microsoft-Edge-Version-Number.jpg)
4. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
5. Select**Yes** when the User Account Control (UAC) prompt shows up.
6. In the console, run the following commands to navigate to the directory where Microsoft Edge is installed:  
`cd/  
cd %Program Files (x86)%\Microsoft\Edge\Application\EdgeVersion\Installer`  
 Replace**EdgeVersion** in the above command with the actual version number noted earlier.
7. Paste the following command and press**Enter** to uninstall Microsoft Edge.  
`setup --uninstall --force-uninstall --system-level`  
![Uninstall Microsoft Edge Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Command-Prompt.jpg)

 Once you run the above commands, Microsoft Edge will be removed from your PC. If you want to install the browser in the future, you can do so by downloading it from the Microsoft Store.

 If you'd like to get more out of this tool, be sure to check out [the Windows Command Prompt commands you must know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) .

## 2\. How to Uninstall Microsoft Edge Using Windows PowerShell

 Like Command Prompt, you can also use Windows PowerShell to uninstall Microsoft Edge from your Windows 11 PC. Unlike the previous method, this one does not require you to know Microsoft Edge's version number. Here's how it works.

1. Press**Win + S** to open the search menu. Type in**Windows PowerShell** and select**Run as administrator** .
2. Select**Yes** when the [User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears.
3. Paste the following command and press**Enter** .  
`get-appxpackage *edge*`  
![Uninstall Microsoft Edge With Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Windows-PowerShell-1.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Highlight the text next to**PackageFullName** and press**Ctrl + C** to copy it.
5. Run the following command to uninstall Microsoft Edge.  
`Remove-appxpackage <PackageFullName>`  
 Replace**<PackageFullName>** in the above command with the package name copied earlier.

 Once you execute the above command, Microsoft Edge will be uninstalled.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Uninstall Microsoft Edge Beta, Dev, or Canary Channel Builds Using the Settings App

 Unlike the stable version, removing a preview build of Microsoft Edge is relatively simple. You can uninstall it just like any other app. Here's how to do it using [Windows 11 Settings app](https://www.makeuseof.com/windows-11-settings-whats-new/) .

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab and click on**Installed apps** .
3. Scroll down to locate Microsoft Edge's preview build.
4. Click the**three-dot menu icon** next to it and select**Uninstall** .
5. Select**Uninstall** again when the confirmation pop-up appears.  
![Uninstall Microsoft Edge Beta From Windows 11 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Beta-From-Windows-11-1.jpg)
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Aside from the Settings app, you can uninstall the browser from the Start menu or the Control Panel. See our guide to learn different [ways to uninstall built-in apps on Windows 11](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/) .

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
## How to Stop Microsoft Edge From Reinstalling on Windows 11

 Although uninstalling Edge from your computer is easy, it does not prevent newer Windows updates from potentially reinstalling the browser. To get around this, you need to [edit a few registry files](https://www.makeuseof.com/windows-registry-file-guide/) on your PC. For that, use the following steps:

1. Press**Win + R** to open the Run dialog box.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window that appears, navigate to**HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft** key.
5. Right-click on the**Microsoft** key, go to**New** , and select**Key** from the submenu. Rename the key to**EdgeUpdate** .
6. Right-click on the**EdgeUpdate** key and select**New > DWORD (32-bit) Value** . Rename the DWORD to**DoNotUpdateToEdgeWithChromium** .
7. Double-click on the newly created DWORD and change its value data to**1** . Then, hit**OK** .  
![Edit DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-dword-in-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you complete the above steps, Windows will not reinstall Microsoft Edge with future updates.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
## Get Rid of Microsoft Edge

 With Windows 11, Microsoft tried everything possible to entice users to switch to Microsoft Edge. Unfortunately, it hasn't worked out very well, as many people still prefer to use alternatives like Google Chrome. If you are one of them, you can get rid of Microsoft Edge using the steps outlined above.

 Now that you've uninstalled Microsoft Edge, you might want to make your preferred web browser the default option on Windows 11.


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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-patience-pays-off-the-art-of-slow-motion-video-crafting/"><u>[New] 2024 Approved  Patience Pays Off  The Art of Slow-Motion Video Crafting</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-best-mac-screen-grabbers-compiled-here/"><u>[New] Best Mac Screen Grabbers Compiled Here</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-audible-magic-studio-techniques-on-mac/"><u>[New] In 2024, Audible Magic  Studio Techniques on Mac</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-viral-velocity-15-dynamic-steps-to-skyrocketing-follower-count-and-fame-on-instagram/"><u>[New] In 2024, Viral Velocity  15 Dynamic Steps to Skyrocketing Follower Count and Fame on Instagram</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-seamless-integration-of-obs-and-zoom-services-for-2024/"><u>[New] Seamless Integration of OBS and Zoom Services for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-pro-vision-enhancement-top-ranked-4k-displays-for-editing-for-2024/"><u>[Updated] Pro Vision Enhancement  Top-Ranked 4K Displays for Editing for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-unlock-and-save-your-favorite-fb-videos-for-2024/"><u>[Updated] Unlock and Save Your Favorite FB Videos for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unveiling-profits-how-much-do-creators-earn-from-each-ad/"><u>[Updated] Unveiling Profits  How Much Do Creators Earn From Each Ad?</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-viral-anime-themed-videos-for-tiktok-success/"><u>[Updated] Viral Anime-Themed Videos for TikTok Success</u></a></li>
<li><a href="https://android-unlock.techidaily.com/6-proven-ways-to-unlock-samsung-galaxy-a14-4g-phone-when-you-forget-the-password-by-drfone-android/"><u>6 Proven Ways to Unlock Samsung Galaxy A14 4G Phone When You Forget the Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/countering-sudden-invisibility-in-win-based-gaming/"><u>Countering Sudden Invisibility in Win-Based Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphraning-the-message-of-crossed-out-icons-on-files/"><u>Deciphraning: The Message of Crossed-Out Icons on Files</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/designing-balanced-dietary-patterns-with-gpt-aid/"><u>Designing Balanced Dietary Patterns with GPT Aid</u></a></li>
<li><a href="https://win11-tips.techidaily.com/displaying-removable-drives-in-explorer-interface/"><u>Displaying Removable Drives in Explorer Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enable-high-contrast-mode-go-to-ease-of-access-settings-and-enable-high-contrast-mode-if-it-improves-visibility/"><u>Enable High Contrast Mode: Go to 'Ease of Access' Settings and Enable High Contrast Mode if It Improves Visibility</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-advice-on-implementing-and-using-the-revo-application-manager-effectively/"><u>Expert Advice on Implementing and Using the Revo Application Manager Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-selecthighlight-issues-in-pdfs-on-windows-pcs/"><u>Fix Select/Highlight Issues in PDFs on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-steam-folder-permissions-on-windows-11/"><u>Fixing Steam Folder Permissions on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-procedure-calls-failure-in-malwarebytes-on-win10win11/"><u>How to Correct Procedure Calls Failure in Malwarebytes on Win10/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-override-microsofts-antivirus-exclusivity-measures/"><u>How to Override Microsoft's Antivirus Exclusivity Measures</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-edit-and-send-fake-location-on-telegram-for-your-lava-blaze-curve-5g-in-3-ways-drfone-by-drfone-virtual-android/"><u>In 2024, Edit and Send Fake Location on Telegram For your Lava Blaze Curve 5G in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-xiaomi-redmi-note-13-5g-phone-without-pin-by-drfone-android/"><u>In 2024, How to Unlock Xiaomi Redmi Note 13 5G Phone without PIN</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-must-have-gear-for-road-trip-documentaries/"><u>In 2024, Must-Have Gear for Road Trip Documentaries</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-oculus-favorites-the-8-highest-selling-games/"><u>In 2024, Oculus Favorites  The 8 Highest-Selling Games</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-top-10-telegram-spy-tools-on-apple-iphone-14-pro-for-parents-drfone-by-drfone-virtual-ios/"><u>In 2024, Top 10 Telegram Spy Tools On Apple iPhone 14 Pro for Parents | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-approaches-to-adding-items-to-win-11-contextual-menu/"><u>Innovative Approaches to Adding Items to Win 11 Contextual Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-guide-streamlining-file-conversions-in-win-11-with-docx/"><u>Innovative Guide: Streamlining File Conversions in Win 11 with Docx</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-tools-aiding-the-laptops-operating-system-swap/"><u>Innovative Tools Aiding the Laptop's Operating System Swap</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intuitive-exploration-the-minimalist-approach-to-windows-explorer/"><u>Intuitive Exploration: The Minimalist Approach to Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mouse-settings-in-windows-11-with-minimal-hassle/"><u>Mastering Mouse Settings in Windows 11 with Minimal Hassle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-fix-a-non-reactive-windows-download-folder/"><u>Methods to Fix a Non-Reactive Windows Download Folder</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-the-ultimate-final-cut-pro-slideshow-creation-guide-for-beginners/"><u>New 2024 Approved The Ultimate Final Cut Pro Slideshow Creation Guide for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-full-screen-problems-in-windows-11-sonics/"><u>Overcoming Full-Screen Problems in Windows 11 Sonics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preempt-potential-problems-installing-virtualbox-on-win-with-care/"><u>Preempt Potential Problems: Installing VirtualBox on Win with Care</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-to-spur-up-your-printers-speed/"><u>Quick Fixes to Spur Up Your Printer's Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-graphics-drivers-on-windows-11-systems/"><u>Refreshing Graphics Drivers on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-resetting-user-defined-search-in-win11/"><u>Regaining Control: Resetting User-Defined Search in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-original-windows-backup-configurations/"><u>Regaining Original Windows Backup Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-working-activation-numbers-in-win11/"><u>Reinstating Working Activation Numbers in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-windows-device-conflicts-no-more-in-use-name-woes/"><u>Resolve Windows Device Conflicts: No More In-Use Name Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-excel-files-unreadable-in-windows-notepad/"><u>Resolve: Excel Files Unreadable in Windows Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-not-enough-resources-for-usb-on-windows/"><u>Resolving “Not Enough Resources” For USB on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-sign-out-error-caused-by-intrusive-windows-software/"><u>Resolving Sign Out Error Caused by Intrusive Windows Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-the-puzzle-overcoming-a-blank-login-window-on-win1011/"><u>Solving the Puzzle: Overcoming a Blank Login Window on Win10/11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/step-by-step-process-for-deleting-stickers-from-tiktok-for-2024/"><u>Step-by-Step Process for Deleting Stickers From TikTok for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-sound-issue-in-audacity-on-windows-1111/"><u>Steps to Resolve Sound Issue in Audacity on Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-language-barriers-use-windows-hotkeys-for-translation/"><u>Streamline Language Barriers: Use Windows Hotkeys for Translation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-leading-windows-brightness-management-apps-and-utilities/"><u>The Leading Windows Brightness Management Apps & Utilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-computere-clock-display-top-5-windows-screensaver-apps-for-dynamic-visuals/"><u>Transform Your Computer’e Clock Display: Top 5 Windows Screensaver Apps for Dynamic Visuals</u></a></li>
<li><a href="https://win-dash.techidaily.com/troubleshoot-and-enhance-the-complete-guide-to-downloading-and-updating-d-link-drivers-windows/"><u>Troubleshoot and Enhance: The Complete Guide to Downloading & Updating D-Link Drivers (Windows)</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/turn-the-clock-back-reverse-video-mastery-in-instagram-for-2024/"><u>Turn the Clock Back  Reverse Video Mastery in Instagram for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreezing-and-restoring-itunes-on-windows-devices/"><u>Unfreezing and Restoring iTunes on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-insight-using-the-lookup-tool-for-window-crashes/"><u>Unlocking Insight: Using the Lookup Tool for Window Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unpacking-error-0x80070522-in-windows-restore-client-access-rights/"><u>Unpacking Error 0X80070522 in Windows: Restore Client Access Rights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-your-pcs-onedrive-mysteries-solutions-here/"><u>Unraveling Your PC's OneDrive Mysteries: Solutions Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-security-protocol-concealing-firewall-areas/"><u>Window’s Security Protocol: Concealing Firewall Areas</u></a></li>
</ul></div>
