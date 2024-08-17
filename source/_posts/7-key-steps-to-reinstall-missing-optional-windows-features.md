---
title: 7 Key Steps to Reinstall Missing Optional Windows Features
date: 2024-08-16T01:19:00.371Z
updated: 2024-08-17T01:19:00.371Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 7 Key Steps to Reinstall Missing Optional Windows Features
excerpt: This Article Describes 7 Key Steps to Reinstall Missing Optional Windows Features
keywords: Windows Feature Installation,Optimal Windows Steps,Feature Recovery Guide,Optional Windows Fixes,Enhancing Windows Functions,Missing Windows Updates,Feature Reinstallation Tips
thumbnail: https://thmb.techidaily.com/32e2647cfec7540fd7d33c1c66a7dde730efec2830801400ac767081505a0953.jpg
---

## 7 Key Steps to Reinstall Missing Optional Windows Features

 Optional features are those that you can add to get more functionality or support for certain file formats. For example, you can install different font packs or old Windows utilities like Paint and WordPad.

 If you're having trouble installing optional features, you're not alone. Sometimes optional features may fail to install due to corrupt system files, an outdated Windows version, or incorrect configuration settings.

 Fortunately, there are several ways to fix this problem and get the optional features running again. So, how can you fix the optional features not installing issue?

## 1\. Use the DISM Tool

 One of the first things you can try is using the Deployment Image Servicing and Management (DISM) tool. This tool is part of Windows, and you can use it to fix corrupt system files, including ones that could be causing problems when installing optional features.

To use the DISM tool, follow these steps:

1. Press**Win + Q** to bring up the Windows search dialogue box.
2. Type**cmd** and click**Run as administrator** to open the Command Prompt.
3. Type**dism /online /cleanup-image /restorehealth** and press**Enter** .  
![DISM Windows Utility Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/dism-windows-utility.jpg)

 This will start the DISM tool and begin scanning your system for any corrupt or missing files. If it finds any issues with your computer, it will automatically repair them.

 Once the process is complete, you can restart your computer and try installing the optional feature again. If DISM does not work or throws an error code, make sure to go through the [DISM not working fixes](https://www.makeuseof.com/windows-11-dism-error-2-fix/) .

<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Run the System File Checker or SFC Utility

 Another tool you can use to fix issues with optional feature installation is the System File Checker (SFC) utility.

 SFC is a command-line utility on Windows, which means you can use it from the Command Prompt itself. It is a useful tool for troubleshooting and repairing problems with the system files on your computer, similar to the DISM tool.

To check your system using SFC, follow these steps:

1. Open the Command Prompt with administrative rights using any of the [ways to open CMD as an admin on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. Type**sfc /scannow** and press**Enter** .  
![SFC Utility In Windows Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-utility-in-windows.jpg)
3. Once SFC scans for errors, make sure to restart your computer.

Want to know the best part?

 The best part is that the System File Checker not only helps you fix the optional features problem but also any other Windows issues. In fact, it's one of the best [ways to repair corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Reset the Windows Update Components

 Windows Update Components include all the services, tasks, and programs that work together to make sure your Windows system is up-to-date and secure.

 Resetting the Windows Update components might help solve the issue with optional feature installation. Here's how you can reset the Windows Update components easily:

1. Open the Command Prompt utility as an administrator.
2. Type the following commands one after the other, pressing**Enter** after each one:

`net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver  
ren C:\Windows\SoftwareDistribution SoftwareDistribution.old  
ren C:\Windows\System32\catroot2 catroot2.old  
net start wuauserv  
net start cryptSvc  
net start bits  
net start msiserver`

 This command will stop the Windows Update services, rename the**SoftwareDistribution** and**catroot2** folders, and then restart the services. This can help reset the update process and fix any issues that might be causing problems with optional feature installation.

![Update Components Reset In CMD Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/update-components-reset-in-cmd.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->

 While the commands may look intimidating, you don't need to worry, as all the commands mentioned above will not cause any harm to your system.​​​​

## 4\. Run the Windows Update Troubleshooter

 If the Command Prompt method did not work for you, you can use the Windows Update Troubleshooter to reset update components. This tool can help identify and fix problems with the update process, including issues that might be preventing optional features from installing.

Follow these steps to run the update troubleshooter on Windows:

1. Press**Win + I** to launch the Settings app.
2. Scroll down and click**Troubleshoot > Other troubleshooters.**  
![Troubleshooter Settings In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/troubleshooter-settings-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Click**Run** next to**Windows Update** to run the troubleshooter.  
![Other Troubleshooters In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/other-troubleshooters-in-windows.jpg)
4. Follow the prompts to complete the troubleshooting process.

 If you're using Windows 10, the Windows Update Troubleshooter is in**Settings > Update & Security >** **Troubleshoot > Windows Update** .

 The troubleshooter will begin scanning your system for any issues with the update process and will offer suggestions for how to fix them. So, you just need to follow the prompts, and then try [installing the optional features](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) again.

## 5\. Update Windows to the Latest Version

 If the issue with optional feature installation is related to outdated system files, you may be able to fix it by updating Windows to the latest version.

 Updating Windows can help ensure that you have the latest security patches, bug fixes, and system files, which can help resolve any issues you may be experiencing.

Here's how you can update Windows to the latest version:

1. Press**Win + I** to open the Settings app.
2. Click on**Windows** **Update > Check for updates** on Windows 11\. For Windows 10, click on **Update & Security > Windows Update > Check for Updates** .  
![Windows Update In Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-update-in-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->

 That's it. Now, you can install any update that is available for your computer.

 By default, Windows automatically downloads and installs updates, but you can also check for updates manually by following the steps above.

## 6\. Restart the Windows Module Installer Service

 The Windows Module Installer service allows you to install, change, and remove Windows features and optional components. If it is not working properly, it can make it difficult to install optional features.

 Follow the below-given steps to restart the Windows Module Installer service:

1. Open Windows search and type**services** .
2. Select the best match to open the**Services** app.
3. Scroll down and find the**Windows Module Installer** service.
4. Right-click on the service and select**Restart** .  
![Windows Modules Installer Service In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-modules-installer-service.jpg)

 When you reset the module installer service, Windows tries to stop it and then start it again, which can help reset the installation process of optional features and fix any issues that might be causing problems.

 Once the service restarts, try installing the optional feature again, and it should work now.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
## 7\. Restore Windows Features Using PowerShell

 If all the above methods fail to work, restoring Windows features is your last resort. So, if you are unable to use or install an optional Windows feature, you might be able to fix the problem by using PowerShell to restore a particular feature.

 Here are the steps for restoring Windows features using the PowerShell:

1. Press**Win + X** to open the Power User menu.
2. Click on**Windows PowerShell (Admin)** or**Terminal (Admin)** .
3. Type the following command and press**Enter** :  
Get-WindowsOptionalFeature -Online  
![Get Optional Feature Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/get-optional-feature-command.jpg)  
 This command will show you the**FeatureName** and**State** of every optional Windows feature that you can use. Make sure to copy the "**FeatureName** " of the feature that you want to enable on Windows.
4. To turn on a certain feature, use the following command and replace "**FEATURENAME** " with the feature's name that you copied earlier:  
Enable-WindowsOptionalFeature -Online -FeatureName FEATURENAME  
![Enable Optional Feature Command In PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/optional-feature-in-powershell.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Restart your computer for the changes to take effect.

 This will add the feature back to your system and should make it available for you to enable or disable in the features window.

 This method only allows you to restore a specific feature and, not all the features at once. So, you need to copy and paste the same command and edit the**FEATURENAME** every time.

 If these steps don't fix the problem, you may need to ask Microsoft or a technical support professional for more help.

## Get Back the Windows Optional Features

 Hopefully, the issue with optional features not installing on your system should be fixed now. In any case, it is important to keep your system up-to-date and to follow best practices for maintaining your computer properly to help prevent issues like this from occurring.


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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-top-picks-for-free-virtual-conferencing-and-screensharing-software/"><u>[New] 2024 Approved  Top Picks for FREE Virtual Conferencing & Screensharing Software</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-9-youtube-video-extraction-tools-for-android-reviewed/"><u>[New] 9 YouTube Video Extraction Tools for Android Reviewed</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-navigating-the-insider-features-of-zoom-software-for-windows-11/"><u>[New] Navigating the Insider Features of Zoom Software for Windows 11</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-starter-steps-to-wealthy-streaming-in-periscope/"><u>2024 Approved  Starter Steps to Wealthy Streaming in Periscope</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-innovative-methods-to-improve-your-windows-update-process/"><u>7 Innovative Methods to Improve Your Windows Update Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-start-screen-links-in-win11s-options/"><u>Adjusting Start Screen Links in Win11's Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-leading-winners-for-windows/"><u>Boost Performance: Leading Winners for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choose-freedom-for-windows-chatai-freedomgpt/"><u>Choose Freedom for Windows ChatAI: FreedomGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cloak-the-ctrl-secure-settings-in-win-1011/"><u>Cloak the CTRL - Secure Settings in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-narrative-voice-with-windows-11-tools/"><u>Crafting Narrative Voice with Windows 11 Tools</u></a></li>
<li><a href="https://win-blog.techidaily.com/eliminating-graphics-glitches-in-fifa-20-your-directx-error-solutions-and-fixes/"><u>Eliminating Graphics Glitches in FIFA 20 - Your DirectX Error Solutions and Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-snipbox-bugs-immediate-steps-for-resolution/"><u>Fix SnipBox Bugs: Immediate Steps for Resolution</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-vivo-v29-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on Vivo V29 | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-unlocking-apple-iphone-14-pro-lock-screen-3-foolproof-methods-that-actually-work-drfone-by-drfone-ios/"><u>In 2024, Unlocking Apple iPhone 14 Pro Lock Screen 3 Foolproof Methods that Actually Work | Dr.fone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/marvels-spider-man-rebooted-with-miles-morales-a-fresh-take-on-a-classic/"><u>Marvel's Spider-Man Rebooted with Miles Morales – A Fresh Take on a Classic</u></a></li>
<li><a href="https://extra-tips.techidaily.com/mastering-visual-storytelling-key-shot-techniques-for-beginners/"><u>Mastering Visual Storytelling  Key Shot Techniques for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-productivity-with-both-wireless-and-cable-connections-on-windows/"><u>Maximizing Productivity with Both Wireless and Cable Connections on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/professional-notetaking-with-simple-windows-hacks/"><u>Professional Notetaking with Simple Windows Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-of-participating-in-the-windows-11-trials/"><u>Secrets of Participating in the Windows 11 Trials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-transitions-with-windows-11-task-switching/"><u>Smooth Transitions with Windows 11 Task Switching</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snipcam-issues-quick-solutions-for-troubleshooting/"><u>SnipCam Issues: Quick Solutions for Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-outlook-cannot-be-opened-issue-on-windows-desktop/"><u>Solving Outlook Cannot Be Opened Issue on Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speeding-up-battlenet-game-transfers-on-win-pc/"><u>Speeding Up Battle.net Game Transfers on Win-PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealthy-exchange-protecting-files-during-cross-network-moves/"><u>Stealthy Exchange: Protecting Files During Cross-Network Moves</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-youtube-videos-a-chrome-fix-guide/"><u>Streamlining YouTube Videos: A Chrome Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-windows-11-taskbar-for-optimal-datetime-view/"><u>Tailoring Windows 11 Taskbar for Optimal Date/Time View</u></a></li>
<li><a href="https://win11.techidaily.com/teams-growth-without-the-heavy-load/"><u>Teams Growth Without the Heavy Load</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-easy-paths-to-windows-help-and-hands-on-center/"><u>The Easy Paths To Windows Help and Hands-On Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-failed-speech-recognition-launch-in-windows/"><u>Troubleshooting Failed Speech Recognition Launch in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-potential-of-your-powershell-scripts/"><u>Unlock the Full Potential of Your PowerShell Scripts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-aggregatorhostexe-on-windows-exploring-its-functionality-and-safety/"><u>What Is AggregatorHost.exe on Windows? Exploring Its Functionality and Safety</u></a></li>
</ul></div>
