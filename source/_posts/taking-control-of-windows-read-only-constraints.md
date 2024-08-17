---
title: Taking Control of Windows Read-Only Constraints
date: 2024-08-16T02:32:14.372Z
updated: 2024-08-17T02:32:14.372Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Taking Control of Windows Read-Only Constraints
excerpt: This Article Describes Taking Control of Windows Read-Only Constraints
keywords: Manage REOs,Control REO,Windows REO Fix,Bypass REOs,Windows REO Bypass,Remove Read-Only Window,Unlock Windows REOs
thumbnail: https://thmb.techidaily.com/b5e9ddde4e68e5c468b12c2fce264f22eb978dc955e335250b1f4d060c7be8f8.jpg
---

## Taking Control of Windows Read-Only Constraints

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on [how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Change the Read-Only Attribute for Files Using the Command Prompt

 Command Prompt is one of two command-line tools available on Windows. You can use it to run batch files, troubleshoot errors, and perform various other tasks. It also lets you change a file's read-only attribute with a single command. Here are the steps you need to follow.

1. Right-click on the file for which you want to modify the read-only attribute and select**Copy as path** .
2. Press**Win + X** to open the Power User menu.
3. Select**Terminal (Admin)** from the list.
4. Select**Yes** when the User Account Control (UAC) prompt appears.
5. In the console, type the following command and press**Enter** to set your file as read-only.  
`attrib +r "FilePath"`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-Command-Prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn [how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
## 3\. How to Change the Read-Only Attribute for Files Using Windows PowerShell

 You can also run a command in [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to change the read-only attribute for a file.

To change the read-only attribute using PowerShell:

1. Right-click on the file for which you want to change the read-only attribute and select**Copy as path** .
2. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
3. Type**Windows PowerShell** and select**Run as Administrator** .
4. Select**Yes** when the User Account Control (UAC) prompt shows up.
5. Paste the following command and press**Enter** to set your file as read-only.  
`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $True`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-PowerShell.jpg)
<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Modifying the Read-Only Attribute for Files on Windows

 It’s worth noting that most system files on Windows will have the read-only attribute by default. So, make sure you don't modify them by mistake. For your other files, you can pick any of the above methods listed above to set or unset their read-only attribute.

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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-simplified-techniques-for-capturing-vimeo-content/"><u>[New] 2024 Approved  Simplified Techniques for Capturing Vimeo Content</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-growth-strategies-for-youtube-videos-6-effortless-approaches-for-2024/"><u>[New] Growth Strategies for YouTube Videos  6 Effortless Approaches for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-deconstructing-the-revenue-stream-of-tseries-in-youtube-economy/"><u>[New] In 2024, Deconstructing the Revenue Stream of TSeries in YouTube Economy</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-breakthrough-tools-an-analysis-of-the-top-10-cost-effective-video-design-schools-on-youtube/"><u>[Updated] 2024 Approved  Breakthrough Tools  An Analysis of the Top 10 Cost-Effective Video Design Schools on YouTube</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-5-ways-to-fix-obs-black-screen-game-capture-for-2024/"><u>[Updated] 5 Ways to Fix OBS Black Screen Game Capture for 2024</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-apple-iphone-x-drfone-by-drfone-virtual-ios/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Apple iPhone X | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-prime-mp4-conversion-for-seamless-facebook-sharing/"><u>2024 Approved  Prime MP4 Conversion for Seamless Facebook Sharing</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-vdl-pro-recorder-summary-detailed-breakdown/"><u>2024 Approved  VDL Pro Recorder Summary  Detailed Breakdown</u></a></li>
<li><a href="https://facebook.techidaily.com/digital-dissent-whatsapp-questions-legality-of-new-privacy-laws/"><u>Digital Dissent: WhatsApp Questions Legality of New Privacy Laws</u></a></li>
<li><a href="https://win11-tips.techidaily.com/displaying-removable-drives-in-explorer-interface/"><u>Displaying Removable Drives in Explorer Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enable-high-contrast-mode-go-to-ease-of-access-settings-and-enable-high-contrast-mode-if-it-improves-visibility/"><u>Enable High Contrast Mode: Go to 'Ease of Access' Settings and Enable High Contrast Mode if It Improves Visibility</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/exhaustive-overview-insights-into-googles-podcast-application-for-2024/"><u>Exhaustive Overview  Insights Into Google's Podcast Application for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-selecthighlight-issues-in-pdfs-on-windows-pcs/"><u>Fix Select/Highlight Issues in PDFs on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-steam-folder-permissions-on-windows-11/"><u>Fixing Steam Folder Permissions on Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/harnessing-techniques-for-superior-pics-free-of-charge/"><u>Harnessing Techniques for Superior Pics, Free of Charge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-procedure-calls-failure-in-malwarebytes-on-win10win11/"><u>How to Correct Procedure Calls Failure in Malwarebytes on Win10/Win11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-intercept-text-messages-on-oppo-a38-drfone-by-drfone-virtual-android/"><u>How to Intercept Text Messages on Oppo A38 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-override-microsofts-antivirus-exclusivity-measures/"><u>How to Override Microsoft's Antivirus Exclusivity Measures</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-apple-iphone-14-plus-drfone-by-drfone-virtual-ios/"><u>How to share/fake gps on Uber for Apple iPhone 14 Plus | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-ranking-of-free-easy-to-use-image-overlay-apps-on-smartphones/"><u>In 2024, Ranking of Free, Easy-to-Use Image Overlay Apps on Smartphones</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-ultimate-list-6-videos-that-grab-attention/"><u>In 2024, The Ultimate List  6 Videos That Grab Attention</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-approaches-to-adding-items-to-win-11-contextual-menu/"><u>Innovative Approaches to Adding Items to Win 11 Contextual Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-guide-streamlining-file-conversions-in-win-11-with-docx/"><u>Innovative Guide: Streamlining File Conversions in Win 11 with Docx</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-tools-aiding-the-laptops-operating-system-swap/"><u>Innovative Tools Aiding the Laptop's Operating System Swap</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intuitive-exploration-the-minimalist-approach-to-windows-explorer/"><u>Intuitive Exploration: The Minimalist Approach to Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-fix-a-non-reactive-windows-download-folder/"><u>Methods to Fix a Non-Reactive Windows Download Folder</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-3gp-file-cutter-extract-specific-parts-of-your-video/"><u>New 2024 Approved 3GP File Cutter Extract Specific Parts of Your Video</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-online-collage-creators-make-stunning-photo-and-video-montages/"><u>New Online Collage Creators Make Stunning Photo and Video Montages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-full-screen-problems-in-windows-11-sonics/"><u>Overcoming Full-Screen Problems in Windows 11 Sonics</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-rotated-interface-issue-on-windows-10/"><u>Overcoming Rotated Interface Issue on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preempt-potential-problems-installing-virtualbox-on-win-with-care/"><u>Preempt Potential Problems: Installing VirtualBox on Win with Care</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-to-spur-up-your-printers-speed/"><u>Quick Fixes to Spur Up Your Printer's Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-graphics-drivers-on-windows-11-systems/"><u>Refreshing Graphics Drivers on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-resetting-user-defined-search-in-win11/"><u>Regaining Control: Resetting User-Defined Search in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-working-activation-numbers-in-win11/"><u>Reinstating Working Activation Numbers in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-windows-device-conflicts-no-more-in-use-name-woes/"><u>Resolve Windows Device Conflicts: No More In-Use Name Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-excel-files-unreadable-in-windows-notepad/"><u>Resolve: Excel Files Unreadable in Windows Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-not-enough-resources-for-usb-on-windows/"><u>Resolving “Not Enough Resources” For USB on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-sign-out-error-caused-by-intrusive-windows-software/"><u>Resolving Sign Out Error Caused by Intrusive Windows Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-the-puzzle-overcoming-a-blank-login-window-on-win1011/"><u>Solving the Puzzle: Overcoming a Blank Login Window on Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-sound-issue-in-audacity-on-windows-1111/"><u>Steps to Resolve Sound Issue in Audacity on Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-language-barriers-use-windows-hotkeys-for-translation/"><u>Streamline Language Barriers: Use Windows Hotkeys for Translation</u></a></li>
<li><a href="https://common-error.techidaily.com/syncing-valorant-gameplay-post-restart/"><u>Syncing Valorant Gameplay Post-Restart</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-computere-clock-display-top-5-windows-screensaver-apps-for-dynamic-visuals/"><u>Transform Your Computer’e Clock Display: Top 5 Windows Screensaver Apps for Dynamic Visuals</u></a></li>
<li><a href="https://apple-account.techidaily.com/troubleshooting-error-connecting-to-the-apple-id-server-from-iphone-7-by-drfone-ios/"><u>Troubleshooting Error Connecting to the Apple ID Server From iPhone 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreezing-and-restoring-itunes-on-windows-devices/"><u>Unfreezing and Restoring iTunes on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-insight-using-the-lookup-tool-for-window-crashes/"><u>Unlocking Insight: Using the Lookup Tool for Window Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unpacking-error-0x80070522-in-windows-restore-client-access-rights/"><u>Unpacking Error 0X80070522 in Windows: Restore Client Access Rights</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unraveling-the-mystery-of-non-exporting-srt-in-premiere-for-2024/"><u>Unraveling the Mystery of Non-Exporting SRT in Premiere for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/win-7810-overcoming-common-startech-driver-challenges/"><u>Win 7/8/10: Overcoming Common StarTech Driver Challenges</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-security-protocol-concealing-firewall-areas/"><u>Window’s Security Protocol: Concealing Firewall Areas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-walks-unlocking-your-gaming-archives/"><u>Windows Walks: Unlocking Your Gaming Archives</u></a></li>
</ul></div>
