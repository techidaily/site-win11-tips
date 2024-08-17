---
title: How to Fix the Windows Sandbox No Hypervisor Was Found 0XC0351000 Error
date: 2024-08-16T01:26:17.210Z
updated: 2024-08-17T01:26:17.210Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the Windows Sandbox No Hypervisor Was Found 0XC0351000 Error
excerpt: This Article Describes How to Fix the Windows Sandbox No Hypervisor Was Found 0XC0351000 Error
keywords: Windows Sandbox Error 0XC0351000,Fixing Windows Sandbox Hypervisor Missing,Resolve Windows Sandbox No Hypervisor,Windows Sandbox ZeroError,Troubleshoot Windows Sandbox Failure,Windows Sandbox Hyperlink Issue,Curing 0XC0351000 Error in Sandbox
thumbnail: https://thmb.techidaily.com/14af88c4727edfc68754682f8d9e5a16b4632ead51b56f451896cf5d83dd52e4.jpg
---

## How to Fix the Windows Sandbox No Hypervisor Was Found 0XC0351000 Error

 Windows Sandbox is a handy utility to test untrusted apps and files in a secure virtual environment. The setup process is pretty straightforward for Windows Sandbox. However, when you try to launch the app, you may encounter the "No Hypervisor was found code 0XC0351000" error.

 The error message indicates that Windows Sandbox was unable to detect Hypervisor. This can happen due to many reasons, including incorrectly configured virtual machine-related features in Windows Features.

 Follow the steps in the article below to troubleshoot this error on your Windows PC.

## 1\. Check and Enable Virtualization Technology in BIOS
![virtualization status windows task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/virtualization-status-windows-task-manager.jpg)

 All the virtualization-based tools need hardware virtualization enabled in BIOS to work. If you haven’t configured your hardware virtualization, check if it is enabled in Task Manager. If not, you can manually enable it in BIOS to support virtualization tools.

To check the virtualization status:

1. Right-click on**Start** and open**Task Manager.**
2. In Task Manager, open the**Performance** tab.
3. Next, make sure the**CPU** tab is selected.
4. Locate the**Virtualization** section. If**Enabled** , skip to the next method.
5. If**Disabled** , follow the steps below to enable hardware virtualization on your computer.

 Now we'll cover how to enable Hardware Virtualization in BISO on an HP computer. The instructions to enable hardware virtualization may vary depending on your computer manufacturer. You can find specific instructions on your computer manufacturer's website, or check out [how to enter the BIOS in Windows 10/11](https://www.makeuseof.com/tag/enter-bios-computer/) .

1. Shut down your PC.
2. Press the**Power** button and then start pressing the**Esc** key to view the**Start menu** .
3. Press**F10** to enter**BIOS Setup.**  
![startup menu bios setup utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/startup-menu-bios-setup-utility.jpg)
4. In the**BIOS Setup Utility,** use the right-left arrow keys to locate and open the**Configuration** tab.
5. Next, use the down-up arrow keys to select**Virtualization Technology** or anything with similar terms.  
![enable hardware virtualization bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-hardware-virtualization-bios.jpg)
6. With the option highlighted, press**Enter** and select**Enabled** from the options. Now the Virtualization Technology status will show as**Enabled** .
7. Press**F10** again to save the changes and exit BIOS.

 Wait for your computer to restart. Open Task Manager to see the Virtualization status in the CPU tab. If it says "Enabled," try to open Windows Sandbox to see if it works without the error.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
## 2\. Enable Virtual Machine Platform Features

 Windows Sandbox is available as an optional feature that you can install from the Windows Features dialog, and we've covered how to do this in our guide on [how to enable and set up Windows Sandbox in Windows 11](https://www.makeuseof.com/enable-set-up-windows-sandbox-windows-11/) . Similarly, you may need to enable a few additional optional features essential to run the virtualization tool successfully.

 The two optional features you need to enable are**Virtual Machine Platform** and**Windows Hypervisor Platform** . These tools enable platform support for virtual machines and provide the necessary API to run virtualization software on Windows.

To enable virtualization features:

1. Press**Win + I** to open**Settings** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**  
![turn windows features on off windows 11 control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-windows-featureson-off-windows-11-control-panel.jpg)
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. In the left pane, click on**Turn Windows features on or off.**  
![turn on virtual machine platform windows hypervisor platform](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-on-virtual-machine-platform-windows-hypervisor-platform.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
4. In the**Windows Features** dialogue, scroll down and locate**Virtual Machine Platform** and**Windows Hypervisor Platform.**
5. Select both options and click**OK** .
6. Windows will start installing the necessary files. So, wait for the process to complete. Once done, click on**Restart Now** to restart your system and apply the changes.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Set Hypervisor to Run at System Startup

 Windows Sandbox may not work if Hypervisor fails to start during system startup. To fix this issue, you can modify your Boot Configuration Data (BCD) file to launch Hypervisor automatically at system startup.

To set Hypervisor to launch at system startup:

1. Press the**Win** key and type**cmd** . Then, right-click on**Command Prompt** and select**Run as administrator.**
2. In the Command Prompt window, type the following command and press Enter:  
`BCDEDIT /Set {current} hypervisorlaunchtype auto`
3. Wait for the success message and restart your PC.
4. After the restart, open Command Prompt as administrator and run the following command:  
`bcdedit`
5. Next, scroll down to the**Hypervisorlaunchtype** entry and make sure it is set to**Auto** .
6. Try to launch Windows Sandbox and check if the No Hypervisor was found error is resolved.

 Note that with the Hypervisor set to launch at startup, virtual machines running on third-party virtualization tools such as VMWare may not work correctly.

 To disable Hypervisor at startup, type the following command in the elevated Command Prompt:

`bcdedit /set hypervisorlaunchtype off`

Once done, restart your computer to apply the changes.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## Get Set With Your Sandbox Again

 While only available on the Pro, Enterprise, and Education editions of the Windows 10 and 11 running systems, Sandbox is an excellent lightweight virtualization solution to test unsafe files and apps on your PC.

 However, if this virtualization option is unavailable, consider using a Windows Sandbox alternative such as Sandboxie-Plus. It is free to use and works on all the editions of Windows OS.


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
<li><a href="https://youtube-webster.techidaily.com/024-approved-access-youtube-tracks-without-spending-a-dime-25plus-no-cost-audio-extractors/"><u>[New] 2024 Approved  Access YouTube Tracks Without Spending a Dime  25+ No-Cost Audio Extractors</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-how-to-legally-access-game-music-without-spending-money/"><u>[New] How to Legally Access Game Music Without Spending Money</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-navigating-subtitle-files-like-a-pro-in-macos/"><u>[New] Navigating Subtitle Files Like a Pro in macOS</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-stepwise-approach-to-perfect-videography-adding-filters-on-devices/"><u>[New] Stepwise Approach to Perfect Videography  Adding Filters on Devices</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-constructive-communication-leads-to-more-subscribers/"><u>[Updated] In 2024, Constructive Communication Leads to More Subscribers</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-ingenious-tactics-to-elevate-customer-feedback-visual-content/"><u>[Updated] Ingenious Tactics to Elevate Customer Feedback Visual Content</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-tecno-pova-5-pro-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Tecno Pova 5 Pro? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tactics-to-eliminate-isdonedll-errors/"><u>Expert Tactics to Eliminate ISDone.dll Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-empty-folder-alerts-for-windows-users/"><u>Fixing Empty Folder Alerts for Windows Users</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-lock-screen-wallpaper-on-itel-a05s-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Itel A05s</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-forbidden-you-dont-have-permission-to-access-on-this-server-error-on-windows/"><u>How to Fix the “Forbidden: You Don’t Have Permission to Access / On This Server” Error on Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-turn-off-find-my-iphone-13-when-phone-is-broken-by-drfone-ios/"><u>How to Turn Off Find My iPhone 13 when Phone is Broken?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-influencer-innovation-the-top-5-instagram-tactics-for-maximum-impact/"><u>In 2024, Influencer Innovation  The Top 5 Instagram Tactics for Maximum Impact</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/master-the-art-of-airpod-resetting-fix-connectivity-issues-in-minutes/"><u>Master the Art of AirPod Resetting: Fix Connectivity Issues in Minutes!</u></a></li>
<li><a href="https://extra-skills.techidaily.com/mastering-file-shift-quick-and-easy-transfer-tactics-for-the-computer-for-2024/"><u>Mastering File Shift  Quick and Easy Transfer Tactics for the Computer for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-system-security-turning-on-controlled-access-in-windows-11/"><u>Mastering System Security: Turning On Controlled Access in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-pin-gallery-space-in-windows-11/"><u>Maximize Your Pin Gallery Space in Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/most-effective-5-image-editing-programs-on-iphone-x-7-8/"><u>Most Effective 5 Image Editing Programs on iPhone (X, 7, 8)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-random-shortcut-activation-in-windows/"><u>Overcoming Random Shortcut Activation in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-failure-to-detect-powershell/"><u>Overcoming Windows Failure to Detect PowerShell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-for-reactivating-fixed-menu-options-on-pc/"><u>Quick Steps for Reactivating Fixed Menu Options on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restart-your-path-ccleaner-woes-on-win11/"><u>Restart Your Path: CCleaner Woes on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reverting-window-11s-search-functionality-back-to-icons/"><u>Reverting Window 11'S Search Functionality Back to Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-file-storage-implementing-windows-folder-restrictions/"><u>Secure File Storage: Implementing Window's Folder Restrictions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snooze-techniques-for-efficient-computers/"><u>Snooze Techniques for Efficient Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-overcome-chrome-freeze-in-windows/"><u>Steps to Overcome Chrome Freeze in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-delete-dialogs-on-windows-systems/"><u>Streamlining Delete Dialogs on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-20-essential-cmd-tricks-for-beginners/"><u>Top 20 Essential CMD Tricks for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-documents-innovative-text-edits-with-snipt-tool/"><u>Transform Your Documents: Innovative Text Edits with Snipt Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-gaming-mastering-playstation-1-titles-on-win-with-duckstations-tips/"><u>Transform Your Gaming: Mastering PlayStation 1 Titles on WIN with Duckstation's Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-a-faulty-windows-enter-keysystem/"><u>Troubleshooting a Faulty Windows 'Enter' Keysystem</u></a></li>
<li><a href="https://win-able.techidaily.com/ultimate-guide-how-to-fix-when-zoom-doesnt-play-your-video/"><u>Ultimate Guide: How To Fix When Zoom Doesn't Play Your Video</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-folder-confluence-techniques-for-users/"><u>Windows Folder Confluence: Techniques for Users</u></a></li>
</ul></div>
