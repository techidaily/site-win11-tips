---
title: "Easing the Heat: Cutting Down Vanguard’ Writes on Your Computer"
date: 2024-07-12T17:27:28.884Z
updated: 2024-07-13T17:27:28.884Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Easing the Heat: Cutting Down Vanguard’ Writes on Your Computer"
excerpt: "This Article Describes Easing the Heat: Cutting Down Vanguard’ Writes on Your Computer"
keywords: Reduce Vanguard's CPU Usage,Lower System Overheating,Decrease Computing Power Consumption,Minimize Tech Heat Generation,Optimize Computer Performance,Cut Energy Waste in PC,Efficient PC Thermal Management
thumbnail: https://thmb.techidaily.com/0c48024453358ef6a98b286edd181eb113a17b3521d6666287ecd3868dbe5cda.jpg
---

## Easing the Heat: Cutting Down Vanguard’ Writes on Your Computer

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

## 4\. Change the Processor Affinity

 The processor affinity setting in Task Manager allows you to limit the number of processors a process can use. Using this setting, you can instruct the process to use only a few processors while leaving others free. In general, the fewer processors a process is permitted to use, the lower its overall resource consumption will be.

 In light of that, changing the processor affinity for the Vanguard process may resolve the issue at hand. To do that, right-click the **vgc.exe** or any other process you want to change the affinity for, then click **Set affinity**.

![Click on Set Affinity Option of Vgc exe in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/5-click-on-set-affinity-option-of-vgc-exe-in-windows-task-manager.jpg)

 Here, uncheck the boxes besides most of the **CPUs** and keep only a few of them checked.

![Disable Unnecessary CPUs From Processor Affinity Settings in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/6-disable-unnecessary-cpus-from-processor-affinity-settings-in-windows-task-manager.jpg)

## 5\. Stop the Vanguard Service and Restart It

 You may also be able to fix the high CPU resource usage of the Vanguard user-mode service by stopping and starting the Vgc service. Follow these steps to do that:

1. Type **"Services"** in Windows Search and open the **Services** app.
2. Locate the **Vgc** service, right-click on it, and hit **Properties**.  
![Go to Properties of Vgc Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/7-go-to-properties-of-vgc-service-in-windows-services-app.jpg)
3. Navigate to the **General** tab, and click on the **Stop** button.
4. After that, restart the service by clicking on the **Start** button again.  
![Stop the Vgc Service in the General Tab of Properties Window in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/8-stop-the-vgc-service-in-the-general-tab-of-properties-window-in-windows-services-app.jpg)
5. Also, choose **Automatic** from the dropdown menu next to **Startup type**.  
![Choose Automatic From the Dropdown Menu Next to Startup Type in General Tab of Properties Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/9-choose-automatic-from-the-dropdown-menu-next-to-startup-type-in-general-tab-of-properties-window.jpg)

## 6\. Disable Third-Party Overlays

 Riot Vanguard is an anti-cheat program. It prevents cheating and bans users who attempt to hack into the game. It does this by detecting unauthorized changes made to the game files and settings using third-party cheat software.

 As reported by some users, using the in-game overlays can also spike CPU resource usage for the Vanguard user-mode service process. Turning off the third-party overlays resulted in a reduction in resource consumption for those users.

 Therefore, if you're using any third-party app to enable in-game overlay, especially Discord, turn it off. Hopefully, this will reduce CPU usage.

![Check the Assigned Hotkey Under Toggle Overlay Lock in the Discord's Game Overlay Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/7-check-the-assigned-hotkey-under-toggle-overlay-lock-in-the-discord-s-game-overlay-settings.jpg)

## 7\. Move Valorant to a Different Drive

 Installing Valorant on the same drive as your operating system has been reported to cause problems. If you've also installed the game on the same drive where your OS resides, it's possible that Windows security could be hindering Vanguard's activity, making it consume more resources.

 To ensure that's not the case, you should move Valorant to a different drive. Not sure how to do that? Refer to our guide on [how to move the installed apps and programs in Windows 10 or 11.](https://www.makeuseof.com/tag/move-installed-apps-programs-windows-10/)

## 8\. Install a Fresh Copy of Vanguard

 If none of the potential fixes have worked, you can use the least desirable option; uninstall Vanguard and reinstall it. However, you need to stop the Vgc service first, as described in the above step; otherwise, you may encounter issues when uninstalling the software. You should also close Valorant and exit Vanguard from the system tray before uninstallation.

 Once that's done, follow the instructions in our [guide on uninstalling software on Windows 11](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) and uninstall Vanguard. Afterward, rerun Valorant and Riot Vanguard will be installed automatically.

![installing riot vanguard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/installing-riot-vanguard-1.jpg)

 Valorant and other Riot Games products require Vanguard to function. If Valorant (or any other game) fails to install Vanguard on its own after uninstallation, restart your device once and then run the game again.

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
<li><a href="https://win11-tips.techidaily.com/analyzing-the-edge-why-a-pc-outmatches-a-mac-in-9-key-aspects/"><u>Analyzing the Edge: Why a PC Outmatches a Mac in 9 Key Aspects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-win-based-steam-internet-connectivity-issues/"><u>Fixing Win-Based Steam Internet Connectivity Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-win1011-context-menu-integrate-disk-space-viewer/"><u>Customizing Win10/11 Context Menu: Integrate Disk Space Viewer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-control-over-group-policy-in-windows-11/"><u>Enhance Control over Group Policy in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-up-microsoft-store-restrictions-on-windows-11/"><u>Easing Up Microsoft Store Restrictions on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-zoom-crash-code-1132-on-windows-devices/"><u>Eliminating Zoom Crash Code 1132 on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-the-challenge-the-ultimate-fix-for-xbox-game-passs-error-code-0x800700e9/"><u>Conquering the Challenge: The Ultimate Fix for Xbox Game Pass’s Error Code 0X800700E9</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-the-art-of-voiceover-thriving-in-the-tiktok-arena/"><u>[Updated] The Art of Voiceover  Thriving in the TikTok Arena</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-tweaking-win11-connectivity-options/"><u>Guide to Tweaking Win11 Connectivity Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-language-potential-with-windows-1011-hotkey-techniques/"><u>Unleash Language Potential with Windows 10/11 Hotkey Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719342757489-commanding-your-digital-files-linking-dropbox-googledrive-to-c/"><u>Commanding Your Digital Files: Linking Dropbox, GoogleDrive to C:</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brightening-dull-cursors-in-uefi/"><u>Brightening Dull Cursors in UEFI</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-best-platforms-maximizing-your-youtube-reach/"><u>[Updated] In 2024, Best Platforms  Maximizing Your YouTube Reach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-prime-screenshot-substitutes-beyond-the-windows-ecosystem/"><u>5 Prime Screenshot Substitutes Beyond the Windows Ecosystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-set-of-folders-cannot-be-opened-error-in-outlook-on-windows/"><u>How to Fix “The Set of Folders Cannot Be Opened” Error in Outlook on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafted-canvas-in-windows-desk-decor-tutorials/"><u>Crafted Canvas in Windows: Desk Decor Tutorials</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-send-and-fake-live-location-on-facebook-messenger-of-your-oppo-a78-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Send and Fake Live Location on Facebook Messenger Of your Oppo A78 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-the-essential-user-manual-for-music-licensing-on-insta/"><u>[New] In 2024, The Essential User Manual for Music Licensing on Insta</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-7-ways-to-lock-apps-on-apple-iphone-6s-and-ipad-securely-drfone-by-drfone-ios/"><u>In 2024, 7 Ways to Lock Apps on Apple iPhone 6s and iPad Securely | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-lsass-unable-to-locate-components-error/"><u>Troubleshooting Lsass Unable to Locate Components Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-steps-for-perfect-directx-setup-and-updates/"><u>Easy Steps for Perfect DirectX Setup & Updates</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/access-royalty-free-beats-for-your-vlog-and-more/"><u>Access Royalty-Free Beats for Your Vlog & More</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-utorrent-stalled-peer-connections-on-win/"><u>Addressing uTorrent Stalled Peer Connections on Win</u></a></li>
<li><a href="https://article-posts.techidaily.com/magix-vision-enhancement-a-detailed-review/"><u>MAGIX Vision Enhancement  A Detailed Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-seamless-workflows-ifttt-for-task-management/"><u>Crafting Seamless Workflows: IFTTT for Task Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-and-11-pro-mastery-a-guide-to-successfully-uninstall-and-reinstall-extras/"><u>Windows 11 & 11 Pro Mastery: A Guide to Successfully Uninstall and Reinstall Extras</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-unlocking-your-potential-multiplatform-studio-use-for-profit/"><u>In 2024, Unlocking Your Potential  Multiplatform Studio Use for Profit</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-expert-tiktok-editing-simplified-methods-for-bold-video-makeovers/"><u>[New] Expert TikTok Editing  Simplified Methods for Bold Video Makeovers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-photo-editing-experience-with-photoshop/"><u>Enhancing Photo Editing Experience with Photoshop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-lsa-errors/"><u>Troubleshooting Windows LSA Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-your-potential-top-7-efficiency-enhancing-widgets-for-win-11/"><u>Unleashing Your Potential: Top 7 Efficiency Enhancing Widgets for Win 11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-top-5-best-audio-video-mixers/"><u>Updated Top 5 Best Audio Video Mixers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-vlc-input-compatibility-faults/"><u>Correcting Windows VLC Input Compatibility Faults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-potential-of-sfxs-for-windows-11/"><u>Unlocking the Potential of SFXs for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-over-windows-updater-failure-x712/"><u>Winning Over Windows Updater Failure X712</u></a></li>
<li><a href="https://location-social.techidaily.com/does-honor-x7b-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>Does Honor X7b Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-best-free-speech-to-text-apps-on-mac-you-might-missed/"><u>[Updated] The Best Free Speech to Text Apps on Mac You Might Missed</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-iphone-13-pro-max-official-method-to-unlock-your-iphone-13-pro-max-by-drfone-ios/"><u>How To Unlock iPhone 13 Pro Max Official Method to Unlock Your iPhone 13 Pro Max</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-elevating-your-tiktok-game-with-effective-use-of-hashes/"><u>[New] Elevating Your TikTok Game with Effective Use of Hashes</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-ultimate-guide-to-prime-3ds-reproduction-software/"><u>[New] 2024 Approved  Ultimate Guide to Prime 3Ds Reproduction Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-and-dxgidll-fix-for-a-missing-crucial-file/"><u>Win11 & Dxgi.dll: Fix for a Missing Crucial File</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-network-errors-a-guide-for-windows-11-users/"><u>Eliminating Network Errors: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-7-tricks-for-resolving-obs-studios-disconnect-issue-on-windows-pcs/"><u>Top 7 Tricks for Resolving OBS Studio's Disconnect Issue on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-solving-the-enigmatic-windows-c0000022-hurdle/"><u>Decoding and Solving the Enigmatic Window's C0000022 Hurdle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-correcting-xbox-game-pass-fatal-error-in-windows-11/"><u>Guide to Correcting Xbox Game Pass Fatal Error in Windows 11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-free-image-resources-for-entrepreneurs-and-small-businesses/"><u>2024 Approved Free Image Resources for Entrepreneurs and Small Businesses</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/free-online-photo-blur-effects-top-websites-and-tools-for-2024/"><u>Free Online Photo Blur Effects Top Websites and Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/error-resolution-at-your-fingertips-top-10-tools/"><u>Error Resolution at Your Fingertips: Top 10 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-not-found-rockalldll-on-windows-pc/"><u>How to Fix 'Not Found' Rockalldll on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-screener-a-step-by-step-customization-guide/"><u>Windows 11 Screener: A Step-by-Step Customization Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designing-a-lasting-deletion-feature-for-windows-desktop-trash/"><u>Designing a Lasting Deletion Feature for Windows Desktop Trash</u></a></li>
</ul></div>
