---
title: 7 Ways to Fix Optional Features Not Installing on Windows 10 & 11
date: 2024-08-16T01:13:24.709Z
updated: 2024-08-17T01:13:24.709Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 7 Ways to Fix Optional Features Not Installing on Windows 10 & 11
excerpt: This Article Describes 7 Ways to Fix Optional Features Not Installing on Windows 10 & 11
keywords: Windows Feature Fix Guide,Enable Missing Windows Options,Windows 10/11 Option Installation,Activate Windows Optional Components,Essential Features Troubleshooting,Windows Updates Issue Solver,Fixing Uninstalled Windows Extras
thumbnail: https://thmb.techidaily.com/f7eb32e30dabd1ecde240ae4f390a8ba724185aa17a13d5ef1b9d86c145dc8b7.jpg
---

## 7 Ways to Fix Optional Features Not Installing on Windows 10 & 11

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

## 2\. Run the System File Checker or SFC Utility

 Another tool you can use to fix issues with optional feature installation is the System File Checker (SFC) utility.

 SFC is a command-line utility on Windows, which means you can use it from the Command Prompt itself. It is a useful tool for troubleshooting and repairing problems with the system files on your computer, similar to the DISM tool.

To check your system using SFC, follow these steps:

1. Open the Command Prompt with administrative rights using any of the [ways to open CMD as an admin on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. Type**sfc /scannow** and press**Enter** .  
![SFC Utility In Windows Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-utility-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
3. Once SFC scans for errors, make sure to restart your computer.

Want to know the best part?

 The best part is that the System File Checker not only helps you fix the optional features problem but also any other Windows issues. In fact, it's one of the best [ways to repair corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 While the commands may look intimidating, you don't need to worry, as all the commands mentioned above will not cause any harm to your system.​​​​

## 4\. Run the Windows Update Troubleshooter

 If the Command Prompt method did not work for you, you can use the Windows Update Troubleshooter to reset update components. This tool can help identify and fix problems with the update process, including issues that might be preventing optional features from installing.

Follow these steps to run the update troubleshooter on Windows:

1. Press**Win + I** to launch the Settings app.
2. Scroll down and click**Troubleshoot > Other troubleshooters.**  
![Troubleshooter Settings In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/troubleshooter-settings-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
3. Click**Run** next to**Windows Update** to run the troubleshooter.  
![Other Troubleshooters In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/other-troubleshooters-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
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
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
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
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-web.techidaily.com/024-approved-the-art-of-playback-anarchy-youtube-playlists-unordered-again/"><u>[New] 2024 Approved  The Art of Playback Anarchy  YouTube Playlists Unordered Again</u></a></li>
<li><a href="https://article-tips.techidaily.com/10-best-wedding-countdown-clock-apps-for-android-and-ios-for-2024/"><u>10 Best Wedding Countdown Clock Apps for Android & iOS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-routes-to-activate-telnet-in-windows-11-os/"><u>3 Routes to Activate Telnet in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-improve-your-gaming-experience-on-a-windows-11-pc/"><u>7 Ways to Improve Your Gaming Experience on a Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensible-approach-to-batch-installations-on-windows-11-via-winstall/"><u>A Comprehensible Approach to Batch Installations on Windows 11 via Winstall</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-plan-for-installing-win11-version-22h2-updater/"><u>A Step-by-Step Plan for Installing WIN11 Version 22H2 Updater</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-pcs-problems-4-top-pct-strategies/"><u>Ace Your PC's Problems: 4 Top PCT Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absent-file-application-linkages-in-win10/"><u>Addressing Absent File Application Linkages in Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-terminal-background-for-custom-aesthetics/"><u>Adjust Terminal Background for Custom Aesthetics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-words-settings-for-consistent-openness-of-email-attachments-as-text/"><u>Adjust Word's Settings for Consistent Openness of Email Attachments as Text</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-settings-for-continuous-save-support-in-nvidia-control-center/"><u>Adjusting Settings for Continuous Save Support in NVidia Control Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-outlook-speed-for-a-smooth-win-experience/"><u>Amplify Outlook Speed for a Smooth WIN Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-your-digital-experience-adding-directories-to-taskbar-menu/"><u>Amplify Your Digital Experience: Adding Directories to Taskbar Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-overview-of-the-windows-canary-security-feature/"><u>An Overview of the Windows Canary Security Feature</u></a></li>
<li><a href="https://extra-information.techidaily.com/an-ultimate-guide-about-video-resolution-for-beginners/"><u>An Ultimate Guide About Video Resolution for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-connectivity-boost-for-windows-11-webcams/"><u>Android Connectivity Boost for Windows 11 Webcams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automatic-restart-the-windows-10-and-11-power-down-protocol/"><u>Automatic Restart: The Windows 10 & 11 Power-Down Protocol</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-disruptions-how-to-mend-broken-windows-registry-items/"><u>Avoiding Disruptions: How to Mend Broken Windows Registry Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-with-these-5-unique-windows-pc-time-saver-tools/"><u>Boost Productivity with These 5 Unique Windows PC Time Saver Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-edge-safety-implement-windows-11-defender-application-guard/"><u>Boosting Edge Safety: Implement Windows 11 Defender Application Guard</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/exploring-the-world-of-animated-lenses-in-snapchat/"><u>Exploring the World of Animated Lenses in Snapchat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719204304616-gpt4all-free-chatbot-clones-at-home-for-windows/"><u>GPT4All: Free ChatBot Clones at Home for Windows.</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-resolve-unsupported-status-of-your-iphone-attachment/"><u>How to Resolve 'Unsupported' Status of Your iPhone Attachment</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-6-to-other-iphone-11-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 6 To Other iPhone 11 devices? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-iphone-8-plus-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade iPhone 8 Plus without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/integrating-hp-laser-jet-pro-m128dn-into-home-networks/"><u>Integrating HP Laser Jet Pro M128dn Into Home Networks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719348868755-is-your-pc-compatible-with-windows-11-see-here/"><u>Is Your PC Compatible with Windows 11? See Here</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-take-your-editing-to-the-next-level-5-final-cut-pro-hacks/"><u>New Take Your Editing to the Next Level 5 Final Cut Pro Hacks</u></a></li>
<li><a href="https://techidaily.com/remove-lock-screen-without-password-c210-by-drfone-android-unlock-android-unlock/"><u>Remove Lock Screen without Password(C210)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719370071964-resolve-wwin-plus-p-non-functionality-in-windows-systems/"><u>Resolve WWin + P Non-Functionality in Windows Systems.</u></a></li>
<li><a href="https://games-able.techidaily.com/the-lasting-impact-of-eas-recent-price-surge/"><u>The Lasting Impact of EA's Recent Price Surge</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-technology-secrets-with-toms-review-panel/"><u>Unveiling Technology Secrets with Tom's Review Panel</u></a></li>
</ul></div>
