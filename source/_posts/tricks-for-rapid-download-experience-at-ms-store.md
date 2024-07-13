---
title: Tricks for Rapid Download Experience at MS Store
date: 2024-07-12T17:22:01.975Z
updated: 2024-07-13T17:22:01.975Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tricks for Rapid Download Experience at MS Store
excerpt: This Article Describes Tricks for Rapid Download Experience at MS Store
keywords: Fast MS Store Downloads,Quick MS File Loading,Speedy MS Purchases,Faster MS Apps Install,Rapid MS Product Access,Swifter MS Digital Content,Accelerated MS Shopping Experience
thumbnail: https://thmb.techidaily.com/5c86eead36fe273b4ffc3fa6b58927f405a2b86a9e9fd87736937318bdb673f7.jpg
---

## Tricks for Rapid Download Experience at MS Store

 Do games and apps take forever to download on the Microsoft Store? If so, you don't need to suffer; there are plenty of ways to speed up your downloads.

 In this article, we'll share a few different things you can try to increase your download speeds on the Microsoft Store.

## 1\. Check Your Internet Connection

 Before making any major changes in the Windows settings, ensure your internet connection isn't responsible for slow downloading on the Microsoft Store. You can confirm this by testing your internet speed using one of the [best speed test websites](https://www.makeuseof.com/best-free-websites-test-internet-speed/) .

 If you are getting a slower download speed across all your internet-based apps, check out our guide on [how to boost your internet speed](https://www.makeuseof.com/tag/10-ways-to-improve-the-speed-of-your-current-router/) . If this guide resolves the slow downloading issue, you're good to go. But if you're still facing the problem, contact your internet service provider (ISP).

## 2\. Close Network-Consuming Applications

 To get the best downloading speed on the Microsoft Store, you must close all the network-consuming applications running in the background. You can do that by following the below instructions:

1. Open the**Task Manager** by pressing the**Ctrl + Shift + Esc** hotkeys.
2. In the**Processes** tab, look in the**Network** column, and close all non-essential applications that are consuming a lot of data.

 Additionally, make sure the Microsoft Store is not running in [Efficiency mode](https://www.makeuseof.com/windows-11-task-manager-efficiency-mode/) , which makes it a less-priority process. To remove the Microsoft Store from efficiency mode, follow the below steps:

1. In the Task Manager, right-click on the Microsoft Store.
2. Click on the**Efficiency mode** option from the context menu.  
![Disabling the Efficiency Mode of the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disabling-the-efficiency-mode.jpg)

 Next, restart your computer and check if there's any improvement in the downloading speed.

## 3\. Turn Off Windows' Metered Connection

 Windows metered connection feature lets users save data. This feature becomes really useful when you are under a data cap, but on the negative side, it can limit how apps use the available bandwidth.

 You must disable the metered connection feature if you are on an unlimited data plan or don't want to restrict apps from using a certain amount of bandwidth. Here's how to do it:

1. Open the**Settings menu** by pressing the**Win + I** hotkeys.
2. Click the**Network** **& internet** option in the left panel.
3. Choose**Wi-Fi** and then select your Wi-Fi connection.
4. Disable the toggle next to the**Metered connection** option.  
![Disable Metered Connection in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/metered-connection.jpg)

## 4\. Change the Background Download Bandwidth

 The next thing you can try to get better speeds on the Microsoft Store is to increase the background download bandwidth. Here's how:

1. Open the Settings menu, and choose**Windows Update** from the left panel.
2. Choose**Advanced options.**
3. Under**Additional options,** choose**Delivery Optimization.**
4. Choose**Advanced options.**
5. Under**Download settings,** select the **Percentage of measured bandwidth (measured against the updates source)** option.  
![Percentage of measured bandwidth (measured against the updates source) option in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/percentage-of-measured-bandwidth-measured-against-the-updates-source.jpg)
6. Check the **Limit how much bandwidth is used for downloading updates in the background** option, and drag the slider to**100%.**
7. Then, check the **Limit how much bandwidth is used for downloading updates in the foreground** option and drag the slider to**100%.**  
![Limit how much bandwidth is used for downloading updates in the foreground option in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/limit-how-much-bandwidth-is-used-for-downloading-updates-in-the-foreground.jpg)

 That's it. Check if there is an improvement in the downloading speed.

## 5\. Clear the Microsoft Store Cache Data

 Microsoft Store stores cache data to offer a better user experience. But if the cache data gets corrupted, it might adversely affect the downloading speed.

 The solution, in this case, is to clear the Microsoft Store cache data. To do this, follow the below steps:

1. Launch the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane.
3. In the elevated Command Prompt window, type**wsreset** and press**Enter** .  
![wsreset command in the Command Prompt window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/wsreset-command.jpg)

## 6\. Switch to the Google Public DNS

 By default, the [DNS server](https://www.makeuseof.com/tag/what-is-dns-server/) is set to automatic, which can be the reason behind the slow downloading speed on the Microsoft Store. You will have to switch to an open-source DNS server like Google Public DNS to get a better downloading speed. Here's how to do it:

1. Launch the Start Menu, type**Control Panel** and press Enter.
2. In the Control Panel, change the**View by** to**Category.**
3. Choose the**Network and Internet** option.
4. Click on**Network and Sharing Center,** and then click on**Change adapter settings** in the left panel.  
![Change Adapter settings option in Windows 11 Network and Sharing center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/Change-Adapter-settings.jpg)
5. Right-click on the connected network and choose**Properties.**
6. Double-click on the**Internet Protocol Version 4 (TCP/IPv4)** and select the**Use the following DNS server addresses** bulletin.
7. Type**8.8.8.8** in the**Preferred DNS** **server** box and**8.8.4.4** in the**Alternate DNS** **server** box.  
![Configuring the Google Public DNS in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/google-public-dns.jpg)
8. Click**OK** to save the settings.

## 7\. Re-register the Microsoft Store

 Sometimes, a temporary glitch can be the reason behind slow downloads on the Microsoft Store. To get rid of such a glitch, you'll have to re-register the Microsoft Store.

 You can't uninstall the Microsoft Store using the Control Panel or any other method used for uninstalling the standard apps. Instead, you will have to execute a command in the PowerShell window to re-register the Microsoft Store.

1. Launch the Start Menu, type**PowerShell,** and choose**Run as administrator** from the right pane.
2. In the PowerShell window, type the following command:  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. Press**Enter** to re-register the Microsoft Store.

 After that, restart your computer and check if the download speed has increased. If not, then you might have to reset the network settings of your computer.

## 8\. Reset the Network Settings

 Is there still no improvement in the Microsoft Store download speed? Probably there's something wrong with your current network settings.

 To fix this, you'll have to reset the network settings, which will remove and then reinstall network adapters and set other network components back to their default values. Here's how:

1. Open the Settings menu, and choose Network & Internet from the left panel.
2. Select**Advanced network settings** and then choose**Network reset.**
3. Click the**Reset now** button.  
![Reset now button to reset the network settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-now-button.jpg)
4. Click**Yes** to the confirmation box that appears.

## Improve Your Microsoft Store Download Speed

 Microsoft Store is the go-to place to download games and apps on a Windows computer. But sometimes, misconfigured Windows settings, a temporary glitch, or network-hogging applications running in the background can slow down the download speed on the Microsoft Store. Fortunately, you can quickly fix this issue by applying the above fixes.


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
<li><a href="https://win11-tips.techidaily.com/bypassing-updater-setback-error-0x800f080a-on-windows-systems/"><u>Bypassing Updater Setback Error 0X800F080A on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-device-diversity-into-a-single-note-world/"><u>Transforming Device Diversity Into a Single Note World</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-vector-insight-for-beginners-basic-forms-and-choice-tools/"><u>[Updated] Vector Insight for Beginners  Basic Forms and Choice Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-share-failures-on-geforce-experience-for-w10w11/"><u>Tackling Share Failures on GeForce Experience for W10/W11</u></a></li>
<li><a href="https://network-issues.techidaily.com/cutting-out-pauses-perfect-video-performance-on-new-os/"><u>Cutting Out Pauses: Perfect Video Performance on New OS</u></a></li>
<li><a href="https://extra-information.techidaily.com/leap-into-fitness-a-curated-selection-of-vr-treadmill-pros/"><u>Leap Into Fitness  A Curated Selection of VR Treadmill Pros</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-internal-audio-error-in-audacity-win-11-and-11/"><u>Tackling Internal Audio Error in Audacity, Win 11 & 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-virtual-voyage-unlimited-the-ultimate-selection-of-free-roleplayers-for-2024/"><u>[New] Virtual Voyage Unlimited  The Ultimate Selection of Free Roleplayers for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-audience-approval-acoustic-amplifier/"><u>Updated Audience Approval Acoustic Amplifier</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-tour-to-windows-booting-point/"><u>A Quick Tour to Windows' Booting Point</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-adopting-sudo-can-transform-your-windows-experience/"><u>Why Adopting Sudo Can Transform Your Windows Experience</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-explore-the-8-premier-zero-cost-video-editors-for-social-media-pros/"><u>In 2024, Explore the 8 Premier Zero-Cost Video Editors for Social Media Pros</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-how-to-convert-aiff-to-mp3/"><u>New How to Convert AIFF to MP3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-security-settings-through-gpo/"><u>Unveiling Windows Security Settings Through GPO</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-be-moved-by-motivation-top-15-tiktok-talents-today/"><u>[New] In 2024, Be Moved by Motivation  Top 15 TikTok Talents Today</u></a></li>
<li><a href="https://screen-recording.techidaily.com/simultaneous-screen-and-camera-capture-guide/"><u>Simultaneous Screen & Camera Capture Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-wasd-isolation-necessity-or-concern/"><u>Understanding WASD Isolation: Necessity or Concern?</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-expert-tips-maximizing-your-win11-conference-capabilities/"><u>2024 Approved  Expert Tips  Maximizing Your Win11 Conference Capabilities</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-top-ae-scripting-tools-and-plug-ins/"><u>In 2024, Top AE Scripting Tools & Plug-Ins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wizardry-learn-hotkeys-to-manage-your-pc/"><u>Windows Wizardry: Learn Hotkeys to Manage Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-tricks-to-fix-error-0x800700e1-in-windows-11/"><u>Tips & Tricks to Fix Error 0X800700E1 in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-windows-package-unopenable-issue-effectively/"><u>Steps to Tackle Windows Package Unopenable Issue Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-dims-handbook-for-windows-11-repair/"><u>The Complete DIMS Handbook for Windows 11 Repair</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-mouseclicklock-usability-on-windows-systems/"><u>Boosting MouseClickLock Usability on Windows Systems</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-samsung-galaxy-m14-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Samsung Galaxy M14 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-best-video-editing-software-for-adding-music-and-soundtracks-for-2024/"><u>New Best Video Editing Software for Adding Music and Soundtracks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-tactics-reactivating-windows-defender-protection-mechanism/"><u>Top 5 Tactics: Reactivating Windows Defender Protection Mechanism</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-splitcam-review/"><u>[Updated] 2024 Approved  SplitCam Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-display-embrace-tiled-workspace/"><u>Streamline Your Display: Embrace Tiled Workspace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-clean-boot-a-beginners-approach/"><u>Windows 11 Clean Boot: A Beginner's Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-steam-online-connectivity-failures-w11/"><u>Addressing Steam Online Connectivity Failures W11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-comprehensive-list-of-top-9-free-video-channel-branding-aids/"><u>[Updated] 2024 Approved  Comprehensive List of Top 9 Free Video Channel Branding Aids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-app-start-issue-qt-plugin-not-available/"><u>Troubleshooting App Start Issue: Qt Plugin Not Available</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-capability-of-windows-11-with-multi-display-setup/"><u>Unlock the Full Capability of Windows 11 With Multi-Display Setup</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/cut-screen-claims-is-splitcam-supreme-for-2024/"><u>Cut Screen Claims  Is SplitCam Supreme for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-2024-approved-how-to-make-vintage-film-effect-1980s/"><u>Updated 2024 Approved How to Make Vintage Film Effect 1980S</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/latest-guide-how-to-bypass-xiaomi-13-ultra-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Xiaomi 13 Ultra FRP Without Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-detailed-manual-for-individualized-keybindings-in-win11/"><u>A Detailed Manual for Individualized Keybindings in Win11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-honor-magic-v2-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Honor Magic V2 in Minutes | Dr.fone</u></a></li>
</ul></div>
