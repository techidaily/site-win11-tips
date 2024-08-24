---
title: Understanding & Reducing High CPU/RAM Demand From UnrealCEFSubprocess
date: 2024-08-23T07:08:50.650Z
updated: 2024-08-24T07:08:50.650Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding & Reducing High CPU/RAM Demand From UnrealCEFSubprocess
excerpt: This Article Describes Understanding & Reducing High CPU/RAM Demand From UnrealCEFSubprocess
keywords: Unreal CEF Sub Low Resource,Reduce CPU Usage UE4,RAM Optimization UE4,CEFSub Process Efficiency,Unreal CEF Resource Management,Minimize UE4 Memory Use,Lowering Unreal CPU Load
thumbnail: https://thmb.techidaily.com/99131a0c0da4530303a8f3d5a541a1cf2cb9af3e3d24fd391ca764cff18f1395.jpg
---

## Understanding & Reducing High CPU/RAM Demand From UnrealCEFSubprocess

 Is the UnrealCEFSubprocess process consuming hefty CPU and RAM resources in the Task Manager, causing your games to crash? Does it keep straining your hardware even after you close all the active programs and apps? You may also have seen it multiply in the Task Manager, which might have made you believe it's a virus.

 There's no need to worry; it's not a virus but a legitimate process belonging to Valorant. Below, we'll discuss why this process consumes many system resources and how you can reduce its resource usage to relieve the strain on your hardware.

## Why Does the UnrealCEFSubprocess Process Consume High CPU and RAM Resources?

 UnrealCEFSubprocess is a legitimate Valorant process, so it shouldn't overload your system resources. If this process starts to strain your hardware and cause CPU, RAM, or GPU usage to spike in the Task Manager, it's either not functioning correctly, or other processes are interfering with it.

 As many users pointed out in a[Reddit thread](https://www.reddit.com/r/ValorantTechSupport/comments/z66n1b/unrealcefsubprocessexe%5Fmultiplying%5Fand%5Fputting/) , one of the major causes of high resource consumption by this process is the interference from Windows' built-in security suite, Windows Defender, and third-party antivirus software, primarily AVG antivirus and Avast antivirus. If you are using security software, then it might be causing the issue.

## Can You Disable the UnrealCEFSubprocess Process via the Task Manager?

 Disabling the UnrealCEFSubprocess process could adversely affect your active gaming session in Valorant. The gaming elements this process controls or handles will crash and behave abnormally. Because of this, we do not advocate closing it down.

 Furthermore, Valorant or the Riot client will automatically relaunch this process the next time you open them, so disabling only the process won't solve the issue. Therefore, we recommend that you fix the underlying problem rather than only disabling this process.

## How to Stop the UnrealCEFSubprocess Process From Taking Up Too Much RAM and CPU

 The easiest way to reduce UnrealCEFSubprocess's CPU and RAM consumption is to[permanently disable Windows Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/) , the built-in security software in Windows, and uninstall any third-party antivirus software you currently use. Even though doing this is easy and quick, we don't recommend it. Why is that?

 The Windows Defender and third-party antivirus software installed on your laptop are a solid defense against viruses and malware. They prevent any potentially harmful agents from wreaking havoc on your device. If you delete or disable them, you will remove your frontline fighters and allow enemies to attack your territory with no fear.

 These security suites would likely have already quarantined many threats and blocked potentially harmful files from affecting your computer. Disabling or deleting them can release these threats and remove restrictions on malicious files. Consequently, this could negatively affect your computer in the long run.

 Considering the risks associated with it, it would be wise not to disable security software right away. Instead of that, you can whitelist the UnrealCEFSubprocess process in them. Whitelisting any file instructs security software not to interfere with it. Therefore, whitelisting the file associated with this process will prevent antivirus programs from interfering with it.

 Consequently, you will be successful in reducing resource consumption without compromising your security.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
### How to Whitelist UnrealCEFSubprocess From Windows Defender

 Follow these steps to whitelist UnrealCEFSubprocess from Windows Defender:

1. Type**"Windows Security"** in Windows Search and open the**Windows Security** app.  
![Open Windows Security from Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/1-open-windows-security-from-windows-search.jpg)
2. Go to the**Firewall and network protection** tab on the left.
3. Click on the**Allow an app through the firewall** link on the right side of the screen.  
![Click on the Allow an App Through the Firewall Link in Windows Security App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/2-click-on-the-allow-an-app-through-the-firewall-link-in-windows-security-app.jpg)
4. Click on**Change settings** .
5. Click on**Allow another app** .  
![Click on Allow Another App in the Windows Defender Firewall Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3-click-on-allow-another-app-in-the-windows-defender-firewall-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
1. In the**Add an app** window, click on the**Browse** button.  
![Click on the Browse Button in the Add an App Window in the Windows Defender Firewall Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/4-click-on-the-browse-button-in-the-add-an-app-window-in-the-windows-defender-firewall-settings.jpg)
2. Then, go to the following path:  
`C:\Program Files\Riot Games\VALORANT\live\Engine\Binaries\Win64`
3. Here, select**UnrealCEFSubProcess** from the list.  
![Select UnrealCEFSubprocess to Create an Exclusion for It](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-select-unrealcefsubprocess-to-create-an-exclusion-for-it.jpg)
4. Then, click on**Add** .  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Click on the Add Button After Selecting the Relevant Process](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/6-click-on-the-add-button-after-selecting-the-relevant-process.jpg)
5. After that, check the**Public** and**Private** boxes next to the**UnrealCEFSubProcess** process and click**OK** .  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Click OK After Checking the Public and Private Boxes Next to the UnrealCEFSubprocess in the Windows Firewall Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/7-click-ok-after-checking-the-public-and-private-boxes-next-to-the-unrealcefsubprocess-in-the-windows-firewall-settings.jpg)
6. Restart your computer after whitelisting this process.

**I** f you have installed Valorant in a different folder or your operating system resides on a different drive, change the path above to reflect the proper location.

### How to Whitelist UnrealCEFSubprocess From Avast Antivirus

 Follow these steps to whitelist UnrealCEFSubprocess from Avast Antivirus:

1. Launch Avast Antivirus.
2. Click the**Menu** button (represented by three horizontal lines stacked over each other) in the top-right of the screen.
3. Go to**Settings** .  
![Go to Settings in Avast Antivirus App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/8-go-to-settings-in-avast-antivirus-app.jpg)
4. Go to the**Exceptions** tab in the**General** settings.
5. Click on**Add Exception** .  
![Click on Add Exception in the General Settings in Avast Antivirus App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/9-click-on-add-exception-in-the-general-settings-in-avast-antivirus-app.jpg)
6. Click**Browse** in the**Add exception** window.  
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
![Click Browse in the Add Exception Window in Avast Antivirus App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/10-click-browse-in-the-add-exception-window-in-avast-antivirus-app.jpg)
7. Navigate to the following path if you haven't changed the default installation path when installing Valorant:  
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`C:\Program Files\Riot Games\VALORANT\live\Engine\Binaries\Win64`
8. Check the box beside**UnrealCEFSubprocess** and click**OK** .  
![Click OK After Checking the Box Beside UnrealCEFSubprocess in Avast Antivirus App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/11-click-ok-after-checking-the-box-beside-unrealcefsubprocess-in-avast-antivirus-app.jpg)
9. After that, restart your computer once, and hopefully, the process won't overtax your computer's resources anymore.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->

### How to Whitelist UnrealCEFSubprocess From AVG Antivirus

 The interface of AVG antivirus is almost identical to Avast antivirus. So, you can whitelist UnrealCEFSubprocess from it by following the steps outlined above. Once you have whitelisted the file,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) once, and hopefully, the resource consumption by this process will decrease significantly.

 According to some users, whitelisting the UnrealCEFSubprocess file from AVG antivirus doesn't always reduce its resource consumption. Due to this, users had to delete AVG antivirus from their computers. So, if whitelisting the file doesn't reduce the load on your hardware, you can delete the AVG antivirus.

 Before doing that,[turn on Windows Defender](https://www.makeuseof.com/turn-on-microsoft-defender/) if it's off, or install alternative antivirus software to replace AVG and keep your computer safe from incoming threats.

 If you use an antivirus software other than the two listed above and the UnrealCEFSubprocess process consumes more than half of your system resources, you need to whitelist the UnrealCEFSubprocess file there as well. If you are not familiar with the whitelisting process, visit the antivirus software's official website.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
## Don't Let the UnrealCEFSubprocess Process Overburden Your Hardware

 The UnrealCEFSubprocess process consumes a lot of resources, which leaves barely any resources for other processes. Consequently, your games and apps will take a long time to load and crash frequently—enough to ruin your gaming experience.

 You should now better understand why this process consumes a lot of resources and what you can do to fix it. Therefore, whitelist the UnrealCEFSubprocess process in your security program, and if that does not solve the issue, disable or uninstall your antivirus.


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
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-breaking-through-virtual-barriers-crafting-engaging-metaverse-content/"><u>[New] 2024 Approved  Breaking Through Virtual Barriers  Crafting Engaging Metaverse Content</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-giggle-gang-exploring-the-best-memetic-apps/"><u>[New] Giggle Gang  Exploring the Best Memetic Apps</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-discovering-charismatic-faces-on-your-snaps/"><u>[New] In 2024, Discovering Charismatic Faces on Your Snaps</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-optimal-sonic-selections-android-centric/"><u>[Updated] 2024 Approved  Optimal Sonic Selections, Android-Centric</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-epic-martial-arts-arcade-classics-revisited-for-2024/"><u>[Updated] Epic Martial Arts Arcade Classics Revisited for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/accelerating-your-workflow-with-lexar-ssds-the-sl500-and-professional-sl600-breakdown-for-speeds-beyond-20gbps/"><u>Accelerating Your Workflow with Lexar SSDs: The SL500 & Professional SL600 Breakdown for Speeds Beyond 20Gbps</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/boost-engagement-with-the-power-of-cookiebot-automation/"><u>Boost Engagement with the Power of Cookiebot Automation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-and-resolving-zero-x-eight-oh-three-one-f-errors-on-windows/"><u>Demystifying and Resolving Zero X Eight Oh Three One F Errors on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-analysis-of-windows-11s-automated-data-management-system/"><u>Detailed Analysis of Windows 11'S Automated Data Management System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disarming-webcam-error-code-a00f4289-in-windows-11-panorama/"><u>Disarming Webcam Error Code A00F4289 in Windows 11 Panorama</u></a></li>
<li><a href="https://program-issues.techidaily.com/enjoy-uninterrupted-gaming-addressed-and-fixed-total-war-saga-troy-pc-errors/"><u>Enjoy Uninterrupted Gaming: Addressed and Fixed Total War Saga - Troy PC Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/escape-s-mode-confinement-on-win-1011-systems/"><u>Escape S Mode Confinement on Win 10/11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-approach-for-windows-error-management/"><u>Essential Approach for Windows Error Management</u></a></li>
<li><a href="https://tech-haven.techidaily.com/establishing-daily-zen-utilizing-chatgpt-for-effective-meditation-routines/"><u>Establishing Daily Zen: Utilizing ChatGPT for Effective Meditation Routines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-to-windows-initialization-points/"><u>Fast Track to Windows' Initialization Points</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-file-types-on-windows/"><u>How to Change File Types on Windows</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-enhancing-your-youtube-content-basic-premiere-pro-edits/"><u>In 2024, Enhancing Your YouTube Content  Basic Premiere Pro Edits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/initiating-the-driver-verifier-in-win11-pro/"><u>Initiating the Driver Verifier in Win11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/journey-to-the-core-understanding-sids-on-windows-11/"><u>Journey to the Core: Understanding SIDs on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-edges-steady-presence-in-windows-11/"><u>Managing Edge's Steady Presence in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-office-error-0x80041015-on-windows/"><u>Mastering the Art of Fixing Office Error: 0X80041015 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-taskbar-icon-size-in-win11-a-guide/"><u>Maximizing Taskbar Icon Size in Win11: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/method-for-limiting-user-permissions-in-windows-10-filesystem/"><u>Method for Limiting User Permissions in Windows 10 Filesystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11-webcam-failure-code-a00f4289-resolution/"><u>Navigating Windows 11 Webcam Failure - Code A00F4289 Resolution</u></a></li>
<li><a href="https://sound-issues.techidaily.com/no-output-from-airpods-step-by-step-guide-for-playing-audio-via-windows-11-and-10-systems/"><u>No Output From AirPods? Step-by-Step Guide for Playing Audio via Windows 11 and 10 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-sticky-menu-issues-in-windows-11/"><u>Overcoming Sticky Menu Issues in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalized-taskbar-scaling-in-windows-11/"><u>Personalized Taskbar Scaling in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rekindle-festive-spirit-with-enchanting-pane-decor/"><u>Rekindle Festive Spirit with Enchanting Pane Decor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-freezing-problems-microsoft-teams-win11-and-win10-guide/"><u>Resolving Freezing Problems: Microsoft Teams Win11 & Win10 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-failed-login-to-game-pass-service-on-windows-1011/"><u>Reversing Failed Login to Game Pass Service on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-google-maps-installation-for-windows-users/"><u>Seamless Google Maps Installation for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-file-installation-with-microsofts-windows-cab-format/"><u>Streamlining File Installation with Microsoft's Windows CAB Format</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-settings-application-one-user-many-options-in-windows-1011/"><u>Tailored Settings Application: One User, Many Options in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-digital-landscape-with-windows-11-features/"><u>Tailoring Your Digital Landscape with Windows 11 Features</u></a></li>
<li><a href="https://driver-error.techidaily.com/uncomplicating-windows-ndis-challenges/"><u>Uncomplicating Windows' NDIS Challenges</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-resolving-rdp-connectivity-woes/"><u>Understanding and Resolving RDP Connectivity Woes</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/unlocking-professional-filming-on-windows-macos-ios/"><u>Unlocking Professional Filming on Windows, macOS, iOS</u></a></li>
<li><a href="https://howto.techidaily.com/vivo-y100i-power-5g-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Vivo Y100i Power 5G Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-file-finder-the-latest-entries-guide/"><u>Windows File Finder: The Latest Entries Guide</u></a></li>
</ul></div>
