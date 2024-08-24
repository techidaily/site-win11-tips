---
title: "Overcome Xbox App Store Crash: Fixing Error 0X80073D26"
date: 2024-08-23T07:09:01.079Z
updated: 2024-08-24T07:09:01.079Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overcome Xbox App Store Crash: Fixing Error 0X80073D26"
excerpt: "This Article Describes Overcome Xbox App Store Crash: Fixing Error 0X80073D26"
keywords: Xbox Store Recovery,Xbox Error Repair,Error 0X80073D26 Fix,App Crash Solutions,Xbox App Issue Resolve,Xbox Update Troubleshoot,Game Store Glitch Fix
thumbnail: https://thmb.techidaily.com/029ba41f4072a625a12663e242fe0241f864e3cc7e4fb5de060add9d7faf8df5.jpg
---

## Overcome Xbox App Store Crash: Fixing Error 0X80073D26

 Error 0x80073D26 is an issue that users have widely reported occurring when trying to install or play Xbox Game Pass titles via Microsoft Store. When this issue arises, users get redirected to install the Gaming Services app in the Microsoft Store. Users then see the “Something unexpected happened” error 0x80073D26 message when they try to install (or update) Gaming Services.

 Players can’t enjoy their Xbox Game Pass titles because of error 0x80073D26, which makes this an annoying issue for Xbox Game Pass users. This is how you can fix the Microsoft Store error 0x80073D26 in Windows

## 1\. Run the Windows Store App Troubleshooting Tool

 This isn’t the most likely solution for error 0x80073D26, but it’s worth trying since Microsoft Store is a UWP app. Running the Windows Store App troubleshooter might detect a Microsoft Store issue and provide a fix. These are the steps for running the Windows Store App troubleshooting utility:

1. Open Settings and click **System** to view that tab.
2. Next, select **Troubleshoot** to reach three troubleshooting navigation options.
3. Bring up the list of troubleshooting tools by clicking **Other trouble-shooters**.
4. Then click **Run** to launch the Windows Store Apps troubleshooting tool.  
![The Run button for the Windows App Store troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-app-store-troubleshooter.jpg)
5. Apply all troubleshooting suggestions provided within Windows Store Apps window.  
![The Windows Store Apps window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-store-app-troubleshooter.jpg)

 You can run the same troubleshooter tool in Windows 10, but the steps for accessing it are a bit different. Click **Update & Security** \> **Troubleshoot** \> **Additional troubleshooters** in Windows 10’s Settings app. Then select **Windows Store Apps** \> **Run the troubleshooter** to get troubleshooting.

## 2\. Repair and Reset the Microsoft Store App

 Accumulated and corrupted Microsoft Store cache data is a potential cause for error 0x80073D26\. Resetting the Microsoft Store app via Settings or the Command Prompt will clear the app’s data. Try applying both methods in this guide to resetting Microsoft Store. Also, select the **Repair** option for the Microsoft Store just above its **Reset** button in Settings to see if that resolves the issue.

![The Reset button for Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button-1.jpg)

## 3\. Edit the Registry

 One of the most widely confirmed fixes for error 0x80073D26 is to enter the Registry and delete the GamingServices and GamingServicesNet Registry keys. Although confirmed to work, we still recommend users [back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before deleting keys. Then follow these steps for editing the registry:

1. Open the Windows Run accessory by right-clicking **Start** on your taskbar and selecting the **Run** option.
2. Input the **regedit** Run command and click **OK** to [launch the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Copy and paste this key location in the registry address bar:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services`
4. Right-click the **GamingServices** subkey within the Services key to select **Delete** \> **Yes**.  
![The Delete registry key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/delete-option-1.jpg)
5. Click the **GamingServicesNet** key with the mouse’s right button and select the **Delete** \> **Yes** options.
6. Exit Registry Editor and restart your PC.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Reinstall the Microsoft Gaming Service

 One of Microsoft’s official resolutions for error 0x80073D26 is to reinstall Gaming Service. This potential solution involves entering three PowerShell commands that will remove the Gaming Service app along with associated registry entries. These are the steps for applying this potential fix:

1. Activate Windows Search by pressing **Win + S**.
2. Enter **PowerShell** inside the file search tool.
3. Open PowerShell with admin rights by right-clicking that app in the search results and selecting **Run as Administrator**.
4. Next, remove the Gaming Service app by entering this command and hitting **Enter**:  
`Get-AppxPackage *gaming services* -allusers | remove-appxpackage -allusers`  
![The remove-app package command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-app-package-command.jpg)
5. Then input these separate commands, pressing **Return** after each:  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`Remove-Item -Path "HKLM:\System\CurrentControlSet\Services\GamingServices" -recurse  

Remove-Item -Path "HKLM:\System\CurrentControlSet\Services\GamingServicesNet" -recurse` 
![The remove-app package command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-app-package-command.jpg)
6. Close out of PowerShell to restart Windows.
7. Reopen Powershell and execute the following command:  
`start ms-windows-store://pdp/?productid=9MWPM2CQNLHN`
8. Then click the **Get** button for installing Gaming Service.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## 5\. Perform Some Generic Windows Fixes for Errors

 Windows is by no means impervious to errors. Fortunately, there are some tricks you can apply to almost every error, including this one.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Repair System Files

![The Reset button for Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button-1.jpg)

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To begin with, try repairing system files to see if there are any issues. You can do that by executing a System File Checker scan within the Command Prompt. That tool will check for and repair corrupted system files detected when you run its command. To apply this potential fix, follow the instructions in our [how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
### Set Windows to Clean Boot

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-services-tab.jpg)

 Another possibility is that a software conflict might be causing error 0x80073D26 to occur on your PC. Setting Windows to clean boot by disabling third-party startup items will likely eliminate such a potential cause. That will stop third-party apps and services that could be conflicting with the Microsoft Store from automatically starting.

 To apply this fix, check out this guide about [clean-booting Windows 10 or 11](https://www.makeuseof.com/clean-boot-windows-11/). Disable startup programs in Task Manager and services in MS Config as covered within that guide; then restart your PC and try installing Microsoft Store games again to see if the issue persists.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
### Reinstall the Microsoft Store

![The remove Microsoft Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-microsoft-store-command.jpg)

 Some users might need to reinstall the Microsoft Store to fix error 0x80073D26\. Such a resolution might be necessary for fixing wider issues with the Microsoft Store app other potential solutions don’t address.

 There isn’t a standard uninstall option available for Microsoft Store. So, you’ll have to reinstall that app with two PowerShell commands. Our guide about [how to reinstall the Microsoft Store](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) tells you how to apply this potential fix.

### Perform an In-Place Windows Upgrade

 Some Microsoft Store users have also fixed error 0x80073D26 by performing an in-place Windows upgrade. An in-place upgrade is a method for installing the latest Windows 11/10 version without losing any installed software or user files.

 This will likely fix the 0x80073D26 error because it will refresh all of the system's registry entries, the system files, and also upgrade Windows to the latest version.

 Performing a Windows 11 in-place upgrade is relatively straightforward. All you need to do is download the latest Windows 11 ISO file, open it up, and launch the setup wizard from there. Our article about [performing an in-place upgrade of Windows 11](https://www.makeuseof.com/in-place-upgrade-windows-11/) includes full guidelines for how to do this.

![The Windows 11 Setup window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-11-setup-window2.jpg)

 You can also perform a Windows 10 in-place upgrade much the same. One difference is that you’ll need to download a Windows 10 Setup file by clicking **Download tool** on the [Microsoft Windows 10 download webpage](https://www.microsoft.com/en-gb/software-download/windows10). Then select **Upgrade this PC** now in the Windows 10 Setup wizard to install the latest version of the OS.

## Enjoy the Best Xbox Game Pass Games Available on the Microsoft Store

 It’s very likely the potential resolutions covered in this guide will fix error 0x80073D26, as some of them are widely confirmed to work. Hopefully, you can get this error fixed and get back into gaming.

 Players can’t enjoy their Xbox Game Pass titles because of error 0x80073D26, which makes this an annoying issue for Xbox Game Pass users. This is how you can fix the Microsoft Store error 0x80073D26 in Windows

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-blog.techidaily.com/024-approved-harness-your-contents-potential-with-ideal-post-days/"><u>[New] 2024 Approved  Harness Your Content's Potential with Ideal Post Days</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-infinite-views-looping-videos-on-your-iphone/"><u>[New] 2024 Approved  Infinite Views  Looping Videos on Your iPhone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-step-by-step-process-for-making-a-stellar-podcast-launch-video-for-2024/"><u>[New] Step-By-Step Process for Making a Stellar Podcast Launch Video for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-industry-standards-in-digital-media-capture/"><u>[Updated] 2024 Approved  Industry Standards in Digital Media Capture</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-conquer-xbox-gameplay-with-efficient-recording-tools/"><u>[Updated] Conquer Xbox Gameplay with Efficient Recording Tools</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-comprehensive-guide-record-webcam-in-hd-via-vlc/"><u>[Updated] In 2024, Comprehensive Guide  Record Webcam in HD via VLC</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-simplescreensaver-easy-app-for-windows-10/"><u>2024 Approved  SimpleScreenSaver  Easy App for Windows 10</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/achieving-clear-focus-blurring-videos-on-teams/"><u>Achieving Clear Focus  Blurring Videos on Teams</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-vivo-y100i-power-5g-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Vivo Y100i Power 5G Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-tecno-spark-10-pro-drfone-by-drfone-virtual-android/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Tecno Spark 10 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-windows-smartscreen-filters-and-alerts/"><u>Configuring Windows' SmartScreen Filters and Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-tech-controlling-appbrowser/"><u>Decoding Windows Tech: Controlling App/Browser</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/different-methods-to-unlock-your-apple-iphone-7-plus-by-drfone-ios/"><u>Different Methods To Unlock Your Apple iPhone 7 Plus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-system-call-failure-in-win11/"><u>Eliminating System Call Failure in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensure-win11-stay-up-to-date-essential-uptime-checks/"><u>Ensure Win11 Stay Up-to-Date: Essential Uptime Checks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-and-solving-roblox-error-403-for-windows-devices/"><u>Exploring & Solving Roblox Error 403 for Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-server-crashes-in-media-software/"><u>Fixing Server Crashes in Media Software</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/free-family-film-fun-the-ultimate-list-of-6-kids-movie-streaming-sites/"><u>Free Family Film Fun: The Ultimate List of 6 Kids’ Movie Streaming Sites</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-lsassexe-unable-to-locate-component-error-in-windows/"><u>How to Fix the lsass.exe Unable to Locate Component Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-keep-your-desktop-spotless-with-windows-self-clean-feature/"><u>How to Keep Your Desktop Spotless with Windows Self-Clean Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-force-remove-a-print-spooler-from-pc/"><u>How to Swiftly Force Remove a Print Spooler From PC</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-realme-narzo-60-5g-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Realme Narzo 60 5G? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-go-joystick-on-nokia-c110-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Nokia C110? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-causes-behind-missing-regedit-application/"><u>Identifying Causes Behind Missing Regedit Application</u></a></li>
<li><a href="https://win11-tips.techidaily.com/illuminate-interruption-5-solutions-to-bring-back-keyboard-glow/"><u>Illuminate Interruption: 5 Solutions to Bring Back Keyboard Glow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jump-over-jerks-top-techniques-to-address-win-11s-typing-latency/"><u>Jump Over Jerks: Top Techniques to Address Win 11'S Typing Latency</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/live-chat-with-woocommerce-leading-into-the-live-selling-world-for-2024/"><u>Live Chat With WooCommerce Leading Into the Live Selling World for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-absent-items-from-file-explorer-list/"><u>Mending Absent Items From File Explorer List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-error-0x80070570s-maze-of-corruption/"><u>Navigating Through Windows Error 0X80070570's Maze of Corruption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-widows-handbrake-freeze-woes/"><u>Overcome Widows' HandBrake Freeze Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-opengl-error-code-3-with-nvidia/"><u>Overcoming OpenGL Error Code 3 with NVIDIA</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pc-awakening-guide-navigating-windows-8-revival-strategies/"><u>PC Awakening Guide: Navigating Windows' 8 Revival Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-find-functionality-a-step-by-step-guide-for-win11-users/"><u>Quick Find Functionality – A Step-by-Step Guide for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-rearranged-keystrokes-in-operating-systems/"><u>Remedying Rearranged Keystrokes in Operating Systems</u></a></li>
<li><a href="https://win-forum.techidaily.com/reviving-your-pc-the-comprehensive-how-to-for-a-complete-windows-11-factory-reset/"><u>Reviving Your PC: The Comprehensive How-To for a Complete Windows 11 Factory Reset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-your-digital-label-changing-username-in-windows-11/"><u>Revolutionize Your Digital Label: Changing UserName in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-windows-partition-union-explained/"><u>Seamless Windows Partition Union Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-file-distribution-the-ultimate-sefx-guide-for-win11/"><u>Streamlining File Distribution: The Ultimate SEFx Guide for Win11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/syma-x8c-mastering-advanced-maneuvers/"><u>Syma X8C  Mastering Advanced Maneuvers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-tutorial-review-and-purge-windows-activity-records/"><u>Tech Tutorial: Review & Purge Windows Activity Records</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-complete-guide-to-purchasing-virtual-reality-games-for-your-meta-quest-2/"><u>The Complete Guide to Purchasing Virtual Reality Games for Your Meta Quest 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-low-adoption-rate-of-windows-11-seven-points/"><u>The Low Adoption Rate of Windows 11: Seven Points</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-controlling-content-filter-on-windows-11/"><u>Tips for Controlling Content Filter on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-additional-options-with-the-widget-bar-in-windows-11/"><u>Unlocking Additional Options with the Widget Bar in Windows 11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>