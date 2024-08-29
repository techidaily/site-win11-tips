---
title: Resolving Excessive CPU Consumption by Vanguard's UMS in Windows
date: 2024-08-28T01:12:17.212Z
updated: 2024-08-29T01:12:17.212Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Excessive CPU Consumption by Vanguard's UMS in Windows
excerpt: This Article Describes Resolving Excessive CPU Consumption by Vanguard's UMS in Windows
keywords: HighCPUUsageVanguard,UMSWindowsOverload,ResolveCPUVanguard,CPUIntensiveUMS,UMSPerformanceIssue,ReduceUMSConsumption,WindowsCPUExcessFix
thumbnail: https://thmb.techidaily.com/128a52db05a06f83263e58b5a6a26485493e4674a4560940aaffe08f0a59ec40.jpg
---

## Resolving Excessive CPU Consumption by Vanguard's UMS in Windows

 Is the "Vanguard user-mode service" process consuming too much of your CPU resources when playing Valorant? This indicates that Riot Vanguard, an anti-cheat software that prevents unfair gameplay in Valorant, isn't working as it should. High CPU usage can cause lag and stutter in Valorant, completely ruining its performance.

 If you want to reduce the CPU usage of the Vanguard user-mode service process and play Valorant seamlessly, here are some fixes you can try.

## 1\. Apply Some Preliminary Checks

 Start de-stressing your CPU by taking the following basic steps, as they may reduce resource usage immediately:

* Restart Valorant or any other game that spikes the Vanguard user-mode service's CPU consumption.
* Whitelist Vanguard from Windows Defender (see [how to allow apps through the Microsoft firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/)) and the antivirus software you use to ensure your security suites don't cause Vanguard to consume more CPU resources than necessary.
* Be sure to turn off any cheat software you're using to manipulate Valorant or any other Riot Games game.
* Use the Task Manager to filter the processes consuming the most CPU resources by descending order to determine if Vanguard overstresses the CPU the most. If another process turns out to be more burdensome, turn it off.

 If none of the above checks fixes the problem, apply the remaining fixes.

## 2\. Disable and Restart Valorant and Vanguard Processes

 First off, ensure that a temporary glitch hasn't fueled the high CPU usage by the Vanguard user-mode service process. The easiest way to rule out this possibility is to close Valorant, turn off the Vanguard services, and restart them.

 To disable them, right-click the Windows **Start** button and open the **Task Manager**. Here, locate the Vanguard and Valorant-related processes, right-click on each process, and select **End task**.

![Disable Vanguard-Related Processes From Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-disable-vanguard-related-processes-from-windows-task-manager.jpg)

 Once these processes are disabled, give Valorant a fresh start, which will automatically restart Vanguard. If restarting the processes doesn't make a difference and the process continues to overstretch the CPU, move on to the next step.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
## 3\. Make the Vanguard User-Mode Service Process a Low Priority

 Windows allows users to limit the CPU resource usage of processes in two different ways. The first is to change the priority of the process, and the second is to turn on the efficiency mode. Using either of these methods limits the allocation of CPU resources to less essential processes, limiting their CPU usage.

 To change the priority of Vanguard-related processes, go to the **Details** tab, right-click on the **vgc.exe** or any other process, and select **Low** from the **Set Priority** menu.

![Change the Priority of the Vanguard User Mode Service Process in the Set Priority Menu in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-set-the-vanguard-user-mode-service-process-a-low-priority-in-the-set-priority-menu-in-windows-task-manager.jpg)

 If you choose the latter option to control CPU resource consumption, right-click on the same process and choose **Efficiency mode**.

![Enable the Efficiency Mode of Vgc in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-go-to-efficiency-mode-of-vgc-in-windows-task-manage.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Change the Processor Affinity

 The processor affinity setting in Task Manager allows you to limit the number of processors a process can use. Using this setting, you can instruct the process to use only a few processors while leaving others free. In general, the fewer processors a process is permitted to use, the lower its overall resource consumption will be.

 In light of that, changing the processor affinity for the Vanguard process may resolve the issue at hand. To do that, right-click the **vgc.exe** or any other process you want to change the affinity for, then click **Set affinity**.

![Click on Set Affinity Option of Vgc exe in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/5-click-on-set-affinity-option-of-vgc-exe-in-windows-task-manager.jpg)

 Here, uncheck the boxes besides most of the **CPUs** and keep only a few of them checked.

![Disable Unnecessary CPUs From Processor Affinity Settings in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/6-disable-unnecessary-cpus-from-processor-affinity-settings-in-windows-task-manager.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 5\. Stop the Vanguard Service and Restart It

 You may also be able to fix the high CPU resource usage of the Vanguard user-mode service by stopping and starting the Vgc service. Follow these steps to do that:

1. Type **"Services"** in Windows Search and open the **Services** app.
2. Locate the **Vgc** service, right-click on it, and hit **Properties**.  
![Go to Properties of Vgc Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/7-go-to-properties-of-vgc-service-in-windows-services-app.jpg)
3. Navigate to the **General** tab, and click on the **Stop** button.
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. After that, restart the service by clicking on the **Start** button again.  
![Stop the Vgc Service in the General Tab of Properties Window in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/8-stop-the-vgc-service-in-the-general-tab-of-properties-window-in-windows-services-app.jpg)
5. Also, choose **Automatic** from the dropdown menu next to **Startup type**.  
![Choose Automatic From the Dropdown Menu Next to Startup Type in General Tab of Properties Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/9-choose-automatic-from-the-dropdown-menu-next-to-startup-type-in-general-tab-of-properties-window.jpg)

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Disable Third-Party Overlays

 Riot Vanguard is an anti-cheat program. It prevents cheating and bans users who attempt to hack into the game. It does this by detecting unauthorized changes made to the game files and settings using third-party cheat software.

 As reported by some users, using the in-game overlays can also spike CPU resource usage for the Vanguard user-mode service process. Turning off the third-party overlays resulted in a reduction in resource consumption for those users.

 Therefore, if you're using any third-party app to enable in-game overlay, especially Discord, turn it off. Hopefully, this will reduce CPU usage.

![Check the Assigned Hotkey Under Toggle Overlay Lock in the Discord's Game Overlay Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/7-check-the-assigned-hotkey-under-toggle-overlay-lock-in-the-discord-s-game-overlay-settings.jpg)

## 7\. Move Valorant to a Different Drive

 Installing Valorant on the same drive as your operating system has been reported to cause problems. If you've also installed the game on the same drive where your OS resides, it's possible that Windows security could be hindering Vanguard's activity, making it consume more resources.

 To ensure that's not the case, you should move Valorant to a different drive. Not sure how to do that? Refer to our guide on [how to move the installed apps and programs in Windows 10 or 11.](https://www.makeuseof.com/tag/move-installed-apps-programs-windows-10/)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Install a Fresh Copy of Vanguard

 If none of the potential fixes have worked, you can use the least desirable option; uninstall Vanguard and reinstall it. However, you need to stop the Vgc service first, as described in the above step; otherwise, you may encounter issues when uninstalling the software. You should also close Valorant and exit Vanguard from the system tray before uninstallation.

 Once that's done, follow the instructions in our [guide on uninstalling software on Windows 11](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) and uninstall Vanguard. Afterward, rerun Valorant and Riot Vanguard will be installed automatically.

![installing riot vanguard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/installing-riot-vanguard-1.jpg)

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Valorant and other Riot Games products require Vanguard to function. If Valorant (or any other game) fails to install Vanguard on its own after uninstallation, restart your device once and then run the game again.

## Don't Let Vanguard Overstress Your CPU

 The consumption of excessive CPU resources by a single process can affect the game's performance and degrade the overall system performance. Hopefully, you now better understand what causes the CPU spike for the Vanguard user-mode service process and the best ways to bring it down to a normal level.

 If none of the fixes above lower CPU consumption, your last resort should be to uninstall Valorant (or any other game) and reinstall it fresh.

 If you want to reduce the CPU usage of the Vanguard user-mode service process and play Valorant seamlessly, here are some fixes you can try.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/new-from-hd-to-breathtaking-eizos-newest-4k-display-for-2024/"><u>[New] From HD to Breathtaking  EIZO's Newest 4K Display for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-how-to-archive-video-discussions-with-ease-and-security/"><u>[New] How to Archive Video Discussions with Ease & Security</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-2023s-top-contenders-gopro-hero5-vs-yi-4k-action-cameras/"><u>[New] In 2024, 2023'S Top Contenders  GoPro Hero5 Vs. Yi 4K Action Cameras</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-enhancing-mobile-broadcasting-via-obs-strategies/"><u>[New] In 2024, Enhancing Mobile Broadcasting via OBS  Strategies</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-instagram-lost-and-found-follower-hunt/"><u>[New] In 2024, Instagram Lost and Found Follower Hunt</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-apex-producers-blending-photography-and-music/"><u>[Updated] 2024 Approved  Apex Producers Blending Photography & Music</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-the-ultimate-selection-of-androids-most-innovative-music-videography-tools/"><u>2024 Approved  The Ultimate Selection of Android's Most Innovative Music Videography Tools</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-twitter-video-requirements-how-to-upload-a-video-on-twitter/"><u>2024 Approved  Twitter Video Requirements | How to Upload a Video on Twitter?</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-honor-x9b-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Honor X9b | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/clearing-out-custom-suggestions-for-you-on-your-instagram-profile/"><u>Clearing Out Custom 'Suggestions for You' On Your Instagram Profile</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deactivating-random-openings-of-file-explorer/"><u>Deactivating Random Openings of File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-computer-chronology-windows-edition/"><u>Deciphering Computer Chronology - Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decrypting-secure-connections-windows-11s-hidden-tricks/"><u>Decrypting Secure Connections: Windows 11'S Hidden Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/digital-duo-dynamics-syncing-your-mobile-and-computer/"><u>Digital Duo Dynamics: Syncing Your Mobile & Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enlightening-on-high-fidelity-window-images/"><u>Enlightening on High-Fidelity Window Images</u></a></li>
<li><a href="https://extra-resources.techidaily.com/essential-guide-to-zoom-video-aesthetics-via-filters/"><u>Essential Guide to Zoom Video Aesthetics via Filters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-temperature-tracker-guide/"><u>Essential Windows Temperature Tracker Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-your-windows-ssd-with-win-plus-ssfresh-techniques/"><u>Fast-Track Your Windows SSD with Win + SSFresh Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-elusive-obs-recording-error-in-windows-11/"><u>Fixing Elusive OBS Recording Error in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-geforce-now-glitch-xc0f1103f-in-win-1011-oses/"><u>Fixing GeForce Now Glitch XC0F1103F in Win 10/11 OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-glitches-on-windows-11-sound-error-code-0xc00d36b4/"><u>Fixing Glitches on Windows 11: Sound Error, Code 0xC00D36B4</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-default-search-window-action-windows-11-guide/"><u>Halt Default Search Window Action, Windows 11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/handling-error-other-software-misusing-your-pc-speakers/"><u>Handling Error: Other Software Misusing Your PC Speakers</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-tecno-camon-20-premier-5g-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Tecno Camon 20 Premier 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-windows-search-illustration/"><u>How to Remove Windows Search Illustration</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-vivo-y56-5g-mirror-screen-to-pc-drfone-by-drfone-android/"><u>In 2024, How Vivo Y56 5G Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-quip-collection-event-specific-jest-compilation/"><u>In 2024, Quip Collection  Event-Specific Jest Compilation</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-youtube-optimization-for-new-vloggers/"><u>In 2024, YouTube Optimization for New Vloggers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intels-unison-and-microsofts-phone-link-for-wp-which-is-better/"><u>Intel's Unison and Microsoft's Phone Link for WP: Which Is Better?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/locate-the-unseen-control-settings-on-new-windows-win11/"><u>Locate the Unseen: Control Settings on New Windows Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-removing-epic-games-from-w11/"><u>Mastering the Art of Removing Epic Games From W11</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-windows-solutions-for-video-file-editing-and-conversion/"><u>Optimal Windows Solutions for Video File Editing & Conversion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/opting-out-of-built-in-pc-graphics-on-windows-os/"><u>Opting Out of Built-In PC Graphics on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-pen-pad-glitches/"><u>Overcoming Windows Pen-Pad Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/push-beyond-the-limits-yuzu-emulator-speed/"><u>Push Beyond the Limits: Yuzu Emulator Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-low-usb-port-space-on-desktops/"><u>Rectifying Low USB Port Space on Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-the-shortcomings-of-discord-search-on-windows-devices/"><u>Rectifying the Shortcomings of Discord Search on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigniting-your-computers-print-functionality-with-effective-wwin-solutions/"><u>Reigniting Your Computer's Print Functionality with Effective WWin Solutions.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstall-success-fixing-clipchamp-on-windows-11/"><u>Reinstall Success: Fixing ClipChamp on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-nvidia-display-issue-in-control-panel/"><u>Resolving Nvidia Display Issue in Control Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-optimal-operation-of-windows-metrics-tool/"><u>Restoring Optimal Operation of Windows Metrics Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/saving-the-day-with-win1011s-recycle-bin-corruption-fixed/"><u>Saving the Day with Win10/11's Recycle Bin Corruption Fixed!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-scanning-condensed-viewing-for-file-finder/"><u>Simplified Scanning: Condensed Viewing for File Finder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-restore-non-functional-network-in-win-os/"><u>Solutions to Restore Non-Functional Network in Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-ease-through-the-waiting-gpsvc/"><u>Strategies to Ease Through the Waiting GPSVC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-thumbnails-on-your-pc-a-guide/"><u>Tailoring Thumbnails on Your PC: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-path-to-high-end-audio-installing-dolby-atmos-on-pc/"><u>The Path to High-End Audio: Installing Dolby Atmos on PC</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/the-ultimate-guide-to-mastering-graphics-with-the-pixio-px277-oled-monitor-for-gamers/"><u>The Ultimate Guide to Mastering Graphics with the Pixio PX277 OLED Monitor for Gamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-repairing-iomap64-syscall-issues-on-windows-devices/"><u>Tips for Repairing IOMap64 SysCall Issues on Windows Devices</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/1723070955380-top-apple-offers-on-prime-day-exclusive-discounts-and-savings/"><u>Top Apple Offers on Prime Day: Exclusive Discounts & Savings!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-missing-graphics-driver-on-windows-overwatch-2/"><u>Troubleshooting Missing Graphics Driver on Windows (Overwatch 2)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-generic-volume-control-fix-guide/"><u>Unblocking Windows Generic Volume Control: Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-wintoys-a-primer-on-windows-powerhouse-tool/"><u>Understanding 'WinToys': A Primer on Windows' Powerhouse Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-password-power-mastering-the-11-methods-for-credential-management-on-win11/"><u>Unleash Password Power: Mastering the 11 Methods for Credential Management on Win11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unlocking-the-academic-advantage-finding-and-using-tidals-student-offers/"><u>Unlocking the Academic Advantage: Finding and Using Tidal’s Student Offers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-steps-to-engage-wordpad-in-win-os/"><u>Unveiling the Steps to Engage WordPad in Win OS</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/r-recognition-the-play-button-reward-ribbon/"><u>Viewer Recognition  The Play Button Reward Ribbon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-10-fix-overcoming-null-audio-device-problems/"><u>Win 10 Fix: Overcoming Null Audio Device Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-10-artists-choice-best-7-drawing-apps-ranked/"><u>Windows 10 Artists' Choice: Best 7 Drawing Apps Ranked</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>