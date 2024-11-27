---
title: "Slashing Processor Load: Effective Ways to Reduce UMS Overuse by Vanguard"
date: 2024-11-20T16:01:19.602Z
updated: 2024-11-27T18:12:48.252Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Slashing Processor Load: Effective Ways to Reduce UMS Overuse by Vanguard"
excerpt: "This Article Describes Slashing Processor Load: Effective Ways to Reduce UMS Overuse by Vanguard"
keywords: Slash Processor Load,UMS Overuse Tips,Vanguard Efficiency,Reducing UMS Usage,Effective Performance Boost,Minimize System Stress,Optimizing Resource Management
thumbnail: https://thmb.techidaily.com/77bfb2c7f1c1fe0360a8a12d5582bbafa6a377d533d7c690d2e56cf6d1507405.jpg
---

## Slashing Processor Load: Effective Ways to Reduce UMS Overuse by Vanguard

 Is the "Vanguard user-mode service" process consuming too much of your CPU resources when playing Valorant? This indicates that Riot Vanguard, an anti-cheat software that prevents unfair gameplay in Valorant, isn't working as it should. High CPU usage can cause lag and stutter in Valorant, completely ruining its performance.

 If you want to reduce the CPU usage of the Vanguard user-mode service process and play Valorant seamlessly, here are some fixes you can try.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Apply Some Preliminary Checks

 Start de-stressing your CPU by taking the following basic steps, as they may reduce resource usage immediately:

* Restart Valorant or any other game that spikes the Vanguard user-mode service's CPU consumption.
* Whitelist Vanguard from Windows Defender (see [how to allow apps through the Microsoft firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/)) and the antivirus software you use to ensure your security suites don't cause Vanguard to consume more CPU resources than necessary.
* Be sure to turn off any cheat software you're using to manipulate Valorant or any other Riot Games game.
* Use the Task Manager to filter the processes consuming the most CPU resources by descending order to determine if Vanguard overstresses the CPU the most. If another process turns out to be more burdensome, turn it off.

 If none of the above checks fixes the problem, apply the remaining fixes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Disable and Restart Valorant and Vanguard Processes

 First off, ensure that a temporary glitch hasn't fueled the high CPU usage by the Vanguard user-mode service process. The easiest way to rule out this possibility is to close Valorant, turn off the Vanguard services, and restart them.

 To disable them, right-click the Windows **Start** button and open the **Task Manager**. Here, locate the Vanguard and Valorant-related processes, right-click on each process, and select **End task**.

![Disable Vanguard-Related Processes From Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-disable-vanguard-related-processes-from-windows-task-manager.jpg)

 Once these processes are disabled, give Valorant a fresh start, which will automatically restart Vanguard. If restarting the processes doesn't make a difference and the process continues to overstretch the CPU, move on to the next step.

## 3\. Make the Vanguard User-Mode Service Process a Low Priority

 Windows allows users to limit the CPU resource usage of processes in two different ways. The first is to change the priority of the process, and the second is to turn on the efficiency mode. Using either of these methods limits the allocation of CPU resources to less essential processes, limiting their CPU usage.

 To change the priority of Vanguard-related processes, go to the **Details** tab, right-click on the **vgc.exe** or any other process, and select **Low** from the **Set Priority** menu.

![Change the Priority of the Vanguard User Mode Service Process in the Set Priority Menu in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-set-the-vanguard-user-mode-service-process-a-low-priority-in-the-set-priority-menu-in-windows-task-manager.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you choose the latter option to control CPU resource consumption, right-click on the same process and choose **Efficiency mode**.

![Enable the Efficiency Mode of Vgc in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-go-to-efficiency-mode-of-vgc-in-windows-task-manage.jpg)

## 4\. Change the Processor Affinity

 The processor affinity setting in Task Manager allows you to limit the number of processors a process can use. Using this setting, you can instruct the process to use only a few processors while leaving others free. In general, the fewer processors a process is permitted to use, the lower its overall resource consumption will be.

 In light of that, changing the processor affinity for the Vanguard process may resolve the issue at hand. To do that, right-click the **vgc.exe** or any other process you want to change the affinity for, then click **Set affinity**.

![Click on Set Affinity Option of Vgc exe in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/5-click-on-set-affinity-option-of-vgc-exe-in-windows-task-manager.jpg)

 Here, uncheck the boxes besides most of the **CPUs** and keep only a few of them checked.

![Disable Unnecessary CPUs From Processor Affinity Settings in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/6-disable-unnecessary-cpus-from-processor-affinity-settings-in-windows-task-manager.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Stop the Vanguard Service and Restart It

 You may also be able to fix the high CPU resource usage of the Vanguard user-mode service by stopping and starting the Vgc service. Follow these steps to do that:

1. Type **"Services"** in Windows Search and open the **Services** app.
2. Locate the **Vgc** service, right-click on it, and hit **Properties**.  
![Go to Properties of Vgc Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/7-go-to-properties-of-vgc-service-in-windows-services-app.jpg)
3. Navigate to the **General** tab, and click on the **Stop** button.
4. After that, restart the service by clicking on the **Start** button again.  
![Stop the Vgc Service in the General Tab of Properties Window in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/8-stop-the-vgc-service-in-the-general-tab-of-properties-window-in-windows-services-app.jpg)
5. Also, choose **Automatic** from the dropdown menu next to **Startup type**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Choose Automatic From the Dropdown Menu Next to Startup Type in General Tab of Properties Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/9-choose-automatic-from-the-dropdown-menu-next-to-startup-type-in-general-tab-of-properties-window.jpg)

## 6\. Disable Third-Party Overlays

 Riot Vanguard is an anti-cheat program. It prevents cheating and bans users who attempt to hack into the game. It does this by detecting unauthorized changes made to the game files and settings using third-party cheat software.

 As reported by some users, using the in-game overlays can also spike CPU resource usage for the Vanguard user-mode service process. Turning off the third-party overlays resulted in a reduction in resource consumption for those users.

 Therefore, if you're using any third-party app to enable in-game overlay, especially Discord, turn it off. Hopefully, this will reduce CPU usage.

![Check the Assigned Hotkey Under Toggle Overlay Lock in the Discord's Game Overlay Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/7-check-the-assigned-hotkey-under-toggle-overlay-lock-in-the-discord-s-game-overlay-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 7\. Move Valorant to a Different Drive

 Installing Valorant on the same drive as your operating system has been reported to cause problems. If you've also installed the game on the same drive where your OS resides, it's possible that Windows security could be hindering Vanguard's activity, making it consume more resources.

 To ensure that's not the case, you should move Valorant to a different drive. Not sure how to do that? Refer to our guide on [how to move the installed apps and programs in Windows 10 or 11.](https://www.makeuseof.com/tag/move-installed-apps-programs-windows-10/)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 8\. Install a Fresh Copy of Vanguard

 If none of the potential fixes have worked, you can use the least desirable option; uninstall Vanguard and reinstall it. However, you need to stop the Vgc service first, as described in the above step; otherwise, you may encounter issues when uninstalling the software. You should also close Valorant and exit Vanguard from the system tray before uninstallation.

 Once that's done, follow the instructions in our [guide on uninstalling software on Windows 11](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) and uninstall Vanguard. Afterward, rerun Valorant and Riot Vanguard will be installed automatically.

![installing riot vanguard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/installing-riot-vanguard-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Valorant and other Riot Games products require Vanguard to function. If Valorant (or any other game) fails to install Vanguard on its own after uninstallation, restart your device once and then run the game again.

## Don't Let Vanguard Overstress Your CPU

 The consumption of excessive CPU resources by a single process can affect the game's performance and degrade the overall system performance. Hopefully, you now better understand what causes the CPU spike for the Vanguard user-mode service process and the best ways to bring it down to a normal level.

 If none of the fixes above lower CPU consumption, your last resort should be to uninstall Valorant (or any other game) and reinstall it fresh.

 If you want to reduce the CPU usage of the Vanguard user-mode service process and play Valorant seamlessly, here are some fixes you can try.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-sure.techidaily.com/roven-youtube-seo-methods-for-video-rankings/"><u>[New] Proven YouTube SEO Methods for Video Rankings</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-virtual-swordplay-showdown-find-your-match-in-these-games-for-2024/"><u>[New] Virtual Swordplay Showdown Find Your Match in These Games for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-ensemble-moves-syncing-your-song-collections/"><u>[Updated] 2024 Approved Ensemble Moves Syncing Your Song Collections</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-finding-the-free-visual-trove-online/"><u>2024 Approved Finding the Free Visual Trove Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curb-windows-lag-when-using-an-additional-screen/"><u>Curb Windows Lag when Using an Additional Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-into-advanced-net-config-on-win11/"><u>Easing Into Advanced Net Config on Win11</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-activate-beats-audio-driver-seamlessly-on-your-pcmac/"><u>How to Activate Beats Audio Driver Seamlessly on Your PC/Mac</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-8-plus-ios-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 8 Plus iOS? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-limiting-video-size-the-mac-way-to-insta-cutting/"><u>In 2024, Limiting Video Size The Mac Way to Insta-Cutting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-fix-for-error-0x0000004e-in-win11/"><u>Mastering Fix for Error 0X0000004E in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimizing-windows-memory-impact-from-edges-view2/"><u>Minimizing Windows Memory Impact From Edge's View2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-nookles-lol-initial-load-woes/"><u>Navigating Nookles' (LOL) Initial Load Woes</u></a></li>
<li><a href="https://extra-support.techidaily.com/optimal-aspect-ratios-for-video-production-for-2024/"><u>Optimal Aspect Ratios for Video Production for 2024</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/premium-storage-solutions-the-ultimate-guide-to-the-most-high-quality-sd-cards-of-2023/"><u>Premium Storage Solutions: The Ultimate Guide to the Most High-Quality SD Cards of 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quicker-quarantine-four-easy-ways-to-cut-off-a-user-on-win11/"><u>Quicker Quarantine: Four Easy Ways to Cut Off a User on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-user-experience-adopting-themes-from-the-microsoft-store/"><u>Revolutionize User Experience: Adopting Themes From The Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-activation-failure-code-0x803f700f/"><u>Solving Windows Activation Failure Code 0X803f700f</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-remedies-addressing-windows-11s-package-problems-immediately/"><u>Swift Remedies: Addressing Windows 11'S Package Problems Immediately</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-5-critical-questions-everyone-should-ask-about-smartwatches-before-buying/"><u>The 5 Critical Questions Everyone Should Ask About Smartwatches Before Buying</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    