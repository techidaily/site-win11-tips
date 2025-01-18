---
title: "Curbing CPU Fatigue: Adjusting the Workload of Vanguard's Sleep Service"
date: 2025-01-11T17:53:21.763Z
updated: 2025-01-18T17:29:47.662Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Curbing CPU Fatigue: Adjusting the Workload of Vanguard's Sleep Service"
excerpt: "This Article Describes Curbing CPU Fatigue: Adjusting the Workload of Vanguard's Sleep Service"
keywords: CPU Fatigue Relief,Vanguard Sleep Service Workload Adjustment,Optimize Processor Rest Period,Managing Tech Weariness,Sleep Service for Computers,Reduce Computer Strain,Tech Rejuvenation Cycle
thumbnail: https://thmb.techidaily.com/e77b802386df347968174243d9eec6b1ff5aaa13a757fb94ecaebe8d1775e8b5.jpg
---

## Curbing CPU Fatigue: Adjusting the Workload of Vanguard's Sleep Service

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

## 3\. Make the Vanguard User-Mode Service Process a Low Priority

 Windows allows users to limit the CPU resource usage of processes in two different ways. The first is to change the priority of the process, and the second is to turn on the efficiency mode. Using either of these methods limits the allocation of CPU resources to less essential processes, limiting their CPU usage.

 To change the priority of Vanguard-related processes, go to the **Details** tab, right-click on the **vgc.exe** or any other process, and select **Low** from the **Set Priority** menu.

![Change the Priority of the Vanguard User Mode Service Process in the Set Priority Menu in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-set-the-vanguard-user-mode-service-process-a-low-priority-in-the-set-priority-menu-in-windows-task-manager.jpg)

 If you choose the latter option to control CPU resource consumption, right-click on the same process and choose **Efficiency mode**.

![Enable the Efficiency Mode of Vgc in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-go-to-efficiency-mode-of-vgc-in-windows-task-manage.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9ECz3oZ8NrQ?si=86vkwkDJo9HQXpzt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Change the Processor Affinity

 The processor affinity setting in Task Manager allows you to limit the number of processors a process can use. Using this setting, you can instruct the process to use only a few processors while leaving others free. In general, the fewer processors a process is permitted to use, the lower its overall resource consumption will be.

 In light of that, changing the processor affinity for the Vanguard process may resolve the issue at hand. To do that, right-click the **vgc.exe** or any other process you want to change the affinity for, then click **Set affinity**.

![Click on Set Affinity Option of Vgc exe in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/5-click-on-set-affinity-option-of-vgc-exe-in-windows-task-manager.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Here, uncheck the boxes besides most of the **CPUs** and keep only a few of them checked.

![Disable Unnecessary CPUs From Processor Affinity Settings in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/6-disable-unnecessary-cpus-from-processor-affinity-settings-in-windows-task-manager.jpg)

## 5\. Stop the Vanguard Service and Restart It

 You may also be able to fix the high CPU resource usage of the Vanguard user-mode service by stopping and starting the Vgc service. Follow these steps to do that:

1. Type **"Services"** in Windows Search and open the **Services** app.
2. Locate the **Vgc** service, right-click on it, and hit **Properties**.  
![Go to Properties of Vgc Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/7-go-to-properties-of-vgc-service-in-windows-services-app.jpg)
3. Navigate to the **General** tab, and click on the **Stop** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. After that, restart the service by clicking on the **Start** button again.  
![Stop the Vgc Service in the General Tab of Properties Window in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/8-stop-the-vgc-service-in-the-general-tab-of-properties-window-in-windows-services-app.jpg)
5. Also, choose **Automatic** from the dropdown menu next to **Startup type**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Choose Automatic From the Dropdown Menu Next to Startup Type in General Tab of Properties Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/9-choose-automatic-from-the-dropdown-menu-next-to-startup-type-in-general-tab-of-properties-window.jpg)

## 6\. Disable Third-Party Overlays

 Riot Vanguard is an anti-cheat program. It prevents cheating and bans users who attempt to hack into the game. It does this by detecting unauthorized changes made to the game files and settings using third-party cheat software.

 As reported by some users, using the in-game overlays can also spike CPU resource usage for the Vanguard user-mode service process. Turning off the third-party overlays resulted in a reduction in resource consumption for those users.

 Therefore, if you're using any third-party app to enable in-game overlay, especially Discord, turn it off. Hopefully, this will reduce CPU usage.

![Check the Assigned Hotkey Under Toggle Overlay Lock in the Discord's Game Overlay Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/7-check-the-assigned-hotkey-under-toggle-overlay-lock-in-the-discord-s-game-overlay-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PNw3Lb26wFA?si=5NR1XRVSp41EQYMy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 7\. Move Valorant to a Different Drive

 Installing Valorant on the same drive as your operating system has been reported to cause problems. If you've also installed the game on the same drive where your OS resides, it's possible that Windows security could be hindering Vanguard's activity, making it consume more resources.

 To ensure that's not the case, you should move Valorant to a different drive. Not sure how to do that? Refer to our guide on [how to move the installed apps and programs in Windows 10 or 11.](https://www.makeuseof.com/tag/move-installed-apps-programs-windows-10/)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 8\. Install a Fresh Copy of Vanguard

 If none of the potential fixes have worked, you can use the least desirable option; uninstall Vanguard and reinstall it. However, you need to stop the Vgc service first, as described in the above step; otherwise, you may encounter issues when uninstalling the software. You should also close Valorant and exit Vanguard from the system tray before uninstallation.

 Once that's done, follow the instructions in our [guide on uninstalling software on Windows 11](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) and uninstall Vanguard. Afterward, rerun Valorant and Riot Vanguard will be installed automatically.

![installing riot vanguard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/installing-riot-vanguard-1.jpg)

 Valorant and other Riot Games products require Vanguard to function. If Valorant (or any other game) fails to install Vanguard on its own after uninstallation, restart your device once and then run the game again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Don't Let Vanguard Overstress Your CPU

 The consumption of excessive CPU resources by a single process can affect the game's performance and degrade the overall system performance. Hopefully, you now better understand what causes the CPU spike for the Vanguard user-mode service process and the best ways to bring it down to a normal level.

 If none of the fixes above lower CPU consumption, your last resort should be to uninstall Valorant (or any other game) and reinstall it fresh.

 If you want to reduce the CPU usage of the Vanguard user-mode service process and play Valorant seamlessly, here are some fixes you can try.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-navigating-the-best-practices-for-fb-video-advertising/"><u>[New] 2024 Approved Navigating the Best Practices for FB Video Advertising</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-essential-guide-for-youtube-video-clips-for-2024/"><u>[New] Essential Guide for YouTube Video Clips for 2024</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210221023-9781506471204-dimming-the-day-evening-meditations-for-quiet-wonder/"><u>Dimming the Day: Evening Meditations for Quiet Wonder | Free Book</u></a></li>
<li><a href="https://fox-info.techidaily.com/dynamic-duo-of-dialogue-for-podcasters-for-2024/"><u>Dynamic Duo of Dialogue For Podcasters for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-access-issues-with-nvidia-cp/"><u>Fixing Windows Access Issues with NVIDIA CP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-the-most-of-jdk-steps-for-windows-11-users/"><u>Making the Most of JDK: Steps for Windows 11 Users</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-top-rated-free-dailymotion-video-converter/"><u>New 2024 Approved Top-Rated Free Dailymotion Video Converter</u></a></li>
<li><a href="https://change-location.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-xiaomi-civi-3-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Xiaomi Civi 3? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restarting-the-difficulty-of-launching-photoshop-in-modern-oses/"><u>Restarting the Difficulty of Launching Photoshop in Modern OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-seamless-play-eliminate-windows-xbox-error/"><u>Restoring Seamless Play: Eliminate Windows Xbox Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-demos-winning-keyboard-cars-for-windows-pc/"><u>Speed Demos: Winning Keyboard Cars for Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-thought-process-adopting-visually-organized-notetaking-via-obsidian-canvas/"><u>Streamline Your Thought Process: Adopting Visually Organized Notetaking via Obsidian Canvas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-bypassing-no-permission-windows-errors/"><u>Techniques for Bypassing 'No Permission' Windows Errors</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-list-best-7-note-taking-tools-for-apples-ipad-series/"><u>The Ultimate List: Best 7 Note-Taking Tools for Apple's iPad Series</u></a></li>
<li><a href="https://some-tips.techidaily.com/unleashing-the-power-of-tunes-simplified-control-with-the-new-sonos-s2-app-yet-beware-of-hidden-drawbacks-explored-by-tech-guru/"><u>Unleashing the Power of Tunes: Simplified Control with the New Sonos S2 App, Yet Beware of Hidden Drawbacks Explored by Tech Guru</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-purpose-does-the-windows-bt-directory-serve/"><u>What Purpose Does the Windows ~BT Directory Serve?</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-infinix-smart-8-pro-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Infinix Smart 8 Pro | Dr.fone</u></a></li>
</ul></div>

