---
title: "Reducing Resource Grab: Taming Windows' UMS Consumption by Vanguard"
date: 2024-10-03T22:31:49.938Z
updated: 2024-10-08T19:29:07.240Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reducing Resource Grab: Taming Windows' UMS Consumption by Vanguard"
excerpt: "This Article Describes Reducing Resource Grab: Taming Windows' UMS Consumption by Vanguard"
keywords: Taming Windows Usage,Reducing Resource Use,Limiting Vanguard Power,Minimize Windows Energy,Cutting UMS Consumption,Lessen UMS Waste,Lower UMS Demand
thumbnail: https://thmb.techidaily.com/3c3e9aebd6b49c0af91473b8783124a08a04e227f020283ad8022a46d57974e6.jpg
---

## Reducing Resource Grab: Taming Windows' UMS Consumption by Vanguard

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

## 2\. Disable and Restart Valorant and Vanguard Processes

 First off, ensure that a temporary glitch hasn't fueled the high CPU usage by the Vanguard user-mode service process. The easiest way to rule out this possibility is to close Valorant, turn off the Vanguard services, and restart them.

 To disable them, right-click the Windows **Start** button and open the **Task Manager**. Here, locate the Vanguard and Valorant-related processes, right-click on each process, and select **End task**.

![Disable Vanguard-Related Processes From Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-disable-vanguard-related-processes-from-windows-task-manager.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123511/26400" target="_top" id="2123511">
  <img src="//a.impactradius-go.com/display-ad/26400-2123511" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123511/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once these processes are disabled, give Valorant a fresh start, which will automatically restart Vanguard. If restarting the processes doesn't make a difference and the process continues to overstretch the CPU, move on to the next step.

## 3\. Make the Vanguard User-Mode Service Process a Low Priority

 Windows allows users to limit the CPU resource usage of processes in two different ways. The first is to change the priority of the process, and the second is to turn on the efficiency mode. Using either of these methods limits the allocation of CPU resources to less essential processes, limiting their CPU usage.

 To change the priority of Vanguard-related processes, go to the **Details** tab, right-click on the **vgc.exe** or any other process, and select **Low** from the **Set Priority** menu.

![Change the Priority of the Vanguard User Mode Service Process in the Set Priority Menu in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-set-the-vanguard-user-mode-service-process-a-low-priority-in-the-set-priority-menu-in-windows-task-manager.jpg)

<!-- affiliate ads begin -->
<span id="1495277">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1495277.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17189-1495277">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1495277.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ffunwhole.sjv.io%2Fc%2F5597632%2F1495277%2F17189'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1495277/17189" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137210/26400" target="_top" id="2137210">
  <img src="//a.impactradius-go.com/display-ad/26400-2137210" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137210/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Stop the Vanguard Service and Restart It

 You may also be able to fix the high CPU resource usage of the Vanguard user-mode service by stopping and starting the Vgc service. Follow these steps to do that:

1. Type **"Services"** in Windows Search and open the **Services** app.
2. Locate the **Vgc** service, right-click on it, and hit **Properties**.  
![Go to Properties of Vgc Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/7-go-to-properties-of-vgc-service-in-windows-services-app.jpg)
3. Navigate to the **General** tab, and click on the **Stop** button.

<!-- affiliate ads begin -->
<span id="1912746">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1912746.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20231-1912746">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1912746.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmindmanager.sjv.io%2Fc%2F5597632%2F1912746%2F20231'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1912746/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. After that, restart the service by clicking on the **Start** button again.  
![Stop the Vgc Service in the General Tab of Properties Window in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/8-stop-the-vgc-service-in-the-general-tab-of-properties-window-in-windows-services-app.jpg)
5. Also, choose **Automatic** from the dropdown menu next to **Startup type**.  
![Choose Automatic From the Dropdown Menu Next to Startup Type in General Tab of Properties Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/9-choose-automatic-from-the-dropdown-menu-next-to-startup-type-in-general-tab-of-properties-window.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082539/7443" target="_top" id="2082539">
  <img src="//a.impactradius-go.com/display-ad/7443-2082539" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082539/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135374/19272" target="_top" id="2135374">
  <img src="//a.impactradius-go.com/display-ad/19272-2135374" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135374/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Install a Fresh Copy of Vanguard

 If none of the potential fixes have worked, you can use the least desirable option; uninstall Vanguard and reinstall it. However, you need to stop the Vgc service first, as described in the above step; otherwise, you may encounter issues when uninstalling the software. You should also close Valorant and exit Vanguard from the system tray before uninstallation.

 Once that's done, follow the instructions in our [guide on uninstalling software on Windows 11](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) and uninstall Vanguard. Afterward, rerun Valorant and Riot Vanguard will be installed automatically.

![installing riot vanguard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/installing-riot-vanguard-1.jpg)

 Valorant and other Riot Games products require Vanguard to function. If Valorant (or any other game) fails to install Vanguard on its own after uninstallation, restart your device once and then run the game again.

## Don't Let Vanguard Overstress Your CPU

 The consumption of excessive CPU resources by a single process can affect the game's performance and degrade the overall system performance. Hopefully, you now better understand what causes the CPU spike for the Vanguard user-mode service process and the best ways to bring it down to a normal level.

 If none of the fixes above lower CPU consumption, your last resort should be to uninstall Valorant (or any other game) and reinstall it fresh.

 If you want to reduce the CPU usage of the Vanguard user-mode service process and play Valorant seamlessly, here are some fixes you can try.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-mastering-your-content-choose-these-top-10-reel-apps/"><u>[New] 2024 Approved Mastering Your Content Choose These Top 10 Reel Apps</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-affordable-skybanking-for-heavy-data-hoarding/"><u>[New] In 2024, Affordable SkyBanking for Heavy Data Hoarding</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-sweeping-vistas-with-your-iphone-social-media-360-tips/"><u>[New] In 2024, Sweeping Vistas with Your iPhone Social Media 360 Tips</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-facebook-group-video-downloader/"><u>[Updated] Facebook Group Video Downloader</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-unveiling-the-top-4-fullscreen-recorder-for-pc-and-mac-users/"><u>[Updated] In 2024, Unveiling the Top 4 Fullscreen Recorder for PC & Mac Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-ais-special-properties-a-comparative-study/"><u>Deciphering AI's Special Properties: A Comparative Study</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-and-repairing-app-f429f-crash-in-windows-11/"><u>Diagnosing and Repairing APP F429F Crash in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-security-enable-controlled-access-in-windows-11/"><u>Elevate Security: Enable Controlled Access in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-insights-uncharted-wonders-in-windows-11/"><u>Essential Insights: Uncharted Wonders in Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-show-wi-fi-password-on-tecno-spark-10-pro-by-drfone-android/"><u>In 2024, How to Show Wi-Fi Password on Tecno Spark 10 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insightful-approaches-to-tackling-robloxs-error-262/"><u>Insightful Approaches to Tackling Roblox's Error 262</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-smooth-video-transitions-in-vlc/"><u>Mastering Smooth Video Transitions in VLC</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/mastering-speech-recording-top-apps-for-your-ipad-for-2024/"><u>Mastering Speech Recording Top Apps for Your iPad for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-productivity-with-custom-winkeys/"><u>Maximize Productivity with Custom WinKeys</u></a></li>
<li><a href="https://tech-revival.techidaily.com/movavigsm/"><u>Movaviで無料オンラインでGSMファイル変換し簡単にアクセス！</u></a></li>
<li><a href="https://facebook.techidaily.com/setting-strict-rules-to-govern-online-communities/"><u>Setting Strict Rules to Govern Online Communities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-correct-password-discrepancies-top-5-methods-for-win11-network-security/"><u>Swiftly Correct Password Discrepancies: Top 5 Methods for Win11 Network Security</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    