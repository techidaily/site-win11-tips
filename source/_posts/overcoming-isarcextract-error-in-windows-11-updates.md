---
title: Overcoming ISArcExtract Error in Windows 11 Updates
date: 2024-07-12T16:32:42.996Z
updated: 2024-07-13T16:32:42.996Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming ISArcExtract Error in Windows 11 Updates
excerpt: This Article Describes Overcoming ISArcExtract Error in Windows 11 Updates
keywords: Fixing ArcExtract Error,Resolving Win11 Update Issues,ArcExtract Troubleshooting Guide,Overcoming ISArcError,Windows 11 Upgrade Tips,ArcExtract Installation Help,Dealing with Update Failures
thumbnail: https://thmb.techidaily.com/c9771ef48189c5657c46cc55dbf30e5b22c5c13c4b41b02a192204985e15f302.jpg
---

## Overcoming ISArcExtract Error in Windows 11 Updates

 Some players have reported an ISDone.dll installation error for Windows games. That issue can arise when players try to install certain games with setup wizards. The message in the ISDone.dll error window says, “It is not found any file specified for ISAarcExtract.”

 Users can’t install games on Windows 10 or 11 when the ISDone.dll error appears. Is the same error stopping you from installing a PC game? If it is, this is how you can fix the ISDone.dll installation issue in Windows 11 and 10.

## 1\. Run the Game’s Installer With Admin Rights

 First, run the game’s setup file with elevated rights to ensure admin restrictions can’t cause the issue. As you’ll only need to install the game once, it’s not necessary to set the installer to [always run as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) . Open the folder that includes the game’s setup.exe. Right-click the game’s installer (setup) file and select its**Run as administrator** context menu option.

![The Run as administrator context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-run-as-administrator-context-menu-option.jpg)

## 2\. Run the Game’s Installer in Compatibility Mode

 Some players have confirmed they’ve fixed the ISDone.dll error by setting the setup wizards for their games to run in compatibility mode. That potential resolution is more likely to work for older games released before Windows 10's own. You can set a setup file to run in compatibility mode like this:

1. First, press Explorer’s**Win + E** key combination to open the File Manager.
2. Navigate to the directory that includes the game setup wizard for which you need to fix the ISDone.dll error.
3. Right-click the setup.exe file for the game and select**Properties** .
4. Select**Compatibility** along the top of the properties window.
5. Next, select the**Run this program in compatibility** mode box.
6. Select the**Windows 7** platform option on the drop-down menu. If your game predates that platform, you can also try selecting Vista or XP.  
![The Run this program in compatibility mode for option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-run-this-program-in-compatibility-mode-setting.jpg)
7. Click**Apply** to save the compatibility settings.
8. Select**OK** to close the setup properties window.

## 3\. Set the Game’s Setup Wizard at High Priority

 Increasing the priority for a game’s setup wizard will raise the system resources allocated to its process. Our article about [setting a priority level for a program](https://www.makeuseof.com/windows-11-set-program-priority/) includes step-by-step instructions for how to apply this potential fix. Open the game’s setup wizard and set its priority level to High in Task Manager as outlined within that guide.

![The Set priority option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-set-priority-option.jpg)

## 4\. Run System File and Image Scans

 System file corruption is another potential cause for the ISDone.dll error in Windows 11/10\. So, we recommend users run a System File Checker scan to address that possible cause. Check out our [guide about running the SFC tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) for further details about how to apply this solution.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-sfc-command.jpg)

 In addition, you can also run a Deployment Image Servicing Management scan on top. That scan can resolve issues with the system image. You can run that utility in the Command Prompt by executing this command:

`DISM /Online /Cleanup-Image /RestoreHealth`

## 5\. Increase Virtual Memory Allocation

 As the ISDone.dll error sometimes arises due to insufficient system memory, increasing virtual memory allocation can be a viable solution. Virtual memory is extra memory reallocated from hard drive storage when your PC’s RAM utilization is at maximum. Expanding the paging file will increase the virtual memory.

 You can apply this solution by following the steps in our [how to increase virtual memory](https://www.makeuseof.com/how-increase-virtual-memory-windows-11/) guide. Enter custom megabyte values in the**Initial** and**Maximum size** boxes on the Virtual Memory window. It’s recommended to enter an initial value 1.5 times higher than your PC’s total RAM amount in megabytes. Input a maximum value three times higher than the total RAM on your PC.

![The Virtual Memory window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/custom-radio-button.jpg)

 For example, a PC with four GB RAM would have 4096 megabytes of memory. Then you would need to multiply 1.5 by 4096 to input a value of 6144 in the**Initial** box. Three times 4096 amounts to 12288, which would be the value to enter the**Maximum size** box.

## 6\. Install Any Missing Visual C++ Redistributables

 The ISDone.dll error could be occurring because some required Visual C++ Redistributable runtimes are missing on your PC. The solution in such a scenario is to install the required C++ runtime libraries that are missing. You can install missing Visual C++ runtimes in the following steps:

1. Open Microsoft’s download page for [Visual C++ Redistributable packs](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170) in your browser.
2. Then click the X64 link for the Visual Studio 2015-2022 package.  
![The X64 download link for Visual Studio 2015-2022](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-download-link-for-visual-c.jpg)
3. Double-click the**VC\_redist.x64.exe** file to open an installer window.
4. Select the checkbox for agreeing to the license terms.  
![The Microsoft Visual C++ 2015-2022 runtime installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-visual-c-installer-window.jpg)
5. Click the Visual C++**Install** option.

 If the ISDone.dll installation issue arises for an old game, you might need to install missing Visual C++ runtimes that predate 2015\. In this case, you’ll need to repeat the above steps for older Visual C++ packs. Try downloading the 64-bit Visual Studio 2013 and 2012 packs from the same Microsoft page to install older missing runtime libraries.

## 7\. Re-Register the Referenced ISDone DLL File

 The ISDone.dll error references an ISDone DLL file, which might not be correctly registered. Reregistering that file could resolve the issue for some users. This is how to register the ISDone DLL file:

1. Press**Win + S** to open Windows Search
2. Type in**Command Prompt** to find that app.
3. Click**Run as administrator** for the Command Prompt app within the search results.
4. Input this command for reregistering ISDone.dll and hit**Enter** :  
`regsvr32 isdone.dll`  
![The regsvr32 command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-regsvr-command.jpg)

## 8\. Temporarily Switch Off Your PC’s Antivirus Shield

 It’s not entirely unusual for antivirus apps to cause installation issues like the ISDone.dll error. You can ensure your antivirus tool isn’t interfering with the installation process by temporarily disabling its shield before attempting to install the game. Our [guide to disabling Microsoft Defender](https://www.makeuseof.com/how-to-turn-off-microsoft-defender-windows-11/) explains how to turn off the antivirus shield for the default Windows Security app.

![The Real-time protection option in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-real-time-protection-option.jpg)

 Users who’ve installed alternative security software packages on PCs will need to disable the third-party antivirus shields. To do that, click a system tray icon for an antivirus app to bring up its context menu. Then, select an option for turning off (or disabling) the antivirus shield.

 However, don’t leave your antivirus software disabled. Instead, turn it off and then try to install whatever game the ISDone.dll error occurs for. Then make sure you re-enable the antivirus shield afterward.

## 9\. Clean Boot the Windows PC

 To minimize potential conflicting processes, try clean booting your PC. Setting a clean boot involves disabling all third-party startup apps and services. That will reduce the number of background services and apps that start with Windows, which could eliminate a process causing the ISDone.dll error.

![The Services tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-services-tab.jpg)

 Our guide to [configuring a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) tells you how to disable third-party startup apps and services with Task Manager and MSConfig. When you’ve set the clean boot and restarted Windows, try installing the game the ISDone.dll error occurs for. Then you can restore the original boot configuration afterward.

## Enjoy Your Windows Games Again

 Players have widely confirmed those resolutions fix the ISDone.dll error. So, applying the potential ISDone.dll error resolutions above will probably resolve that game installation issue in most cases. Yet, they might not work for everyone, and you can contact support services for affected game titles if further potential fixes are needed.

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
<li><a href="https://video-ai-editor.techidaily.com/new-auto-reframe-video-editing-tools-top-picks-for-2024/"><u>New Auto-Reframe Video Editing Tools Top Picks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-editing-the-windows-registry-via-terminal/"><u>Essential Tips for Editing the Windows Registry via Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/character-discovery-windows-11-pathway/"><u>Character Discovery: Windows 11 Pathway</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-quick-tips-solve-obss-blackout-during-live-captures/"><u>[New] 2024 Approved  Quick Tips  Solve OBS's Blackout During Live Captures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-with-style-adding-emoji-15-to-win11-setup/"><u>Navigate with Style: Adding Emoji 15 to Win11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-data-security-activating-controlled-folder-access/"><u>Achieve Data Security: Activating Controlled Folder Access</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/learn-how-to-slow-down-time-lapse-videos-on-iphone-to-make-detailed-and-captivating-slow-motion-effects-in-your-time-lapse-captures-for-2024/"><u>Learn How to Slow Down Time-Lapse Videos on iPhone to Make Detailed and Captivating Slow-Motion Effects in Your Time-Lapse Captures for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-user-name-changes-for-w11-enthusiasts/"><u>Direct User Name Changes for W11 Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-prevent-steam-file-sync-failures-in-windows/"><u>Methods to Prevent Steam File Sync Failures in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-terminal-settings-on-windows-pc/"><u>Optimizing Terminal Settings on Windows PC</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-guide-to-mirror-your-vivo-v29e-to-other-android-devices-drfone-by-drfone-android/"><u>In 2024, Guide to Mirror Your Vivo V29e to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-launch-chrome-in-your-newest-windows-11-pc/"><u>How to Launch Chrome in Your Newest Windows 11 PC</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-freenoweb-recorder-app-evaluation-insights-for-2024/"><u>[Updated] FreenoWeb Recorder App Evaluation Insights for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-with-improved-windows-tiling/"><u>Boost Productivity with Improved Windows Tiling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-files-essential-pitfalls-prevention-in-windows-11/"><u>Navigating Files: Essential Pitfalls Prevention in Windows 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-ultimate-screen-capture-review-obs-vs-fraps-for-2024/"><u>[New] Ultimate Screen Capture Review  OBS vs Fraps for 2024</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-oppo-k11-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Oppo K11 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-quick-tips-for-twitter-video-uploads-on-instagram-for-2024/"><u>[New] Quick Tips for Twitter Video Uploads on Instagram for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-fullscreen-crashes-in-sonic-adventure-for-windows-11/"><u>Combatting Fullscreen Crashes in Sonic Adventure for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-network-address-translation-win1110-edition-explained/"><u>Navigating Network Address Translation: Win11/10 Edition Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-methods-to-revive-windows-desktop-icons/"><u>Efficient Methods to Revive Windows Desktop Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-controller-reviving-it-from-steams-oblivion/"><u>Master the Controller: Reviving It From Steam's Oblivion</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/streamline-communications-with-these-best-5-capture-tools/"><u>Streamline Communications with These Best 5 Capture Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-latency-windows-discord-tweaks-for-speed/"><u>Clearing Up Latency: Windows Discord Tweaks for Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-directory-capacity-assessment-via-windows-powershell/"><u>Demystifying Directory Capacity Assessment via Windows PowerShell</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-make-a-splash-impressive-video-edits-with-windows-10s-tools/"><u>[New] Make a Splash  Impressive Video Edits with Windows 10'S Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combat-oculus-setup-issues-windows-11-and-10-solutions/"><u>Combat Oculus Setup Issues: Windows 11 & 10 Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-unbootable-windows-vms-via-vmware-in-win11/"><u>Eliminating Unbootable Windows VMs via VMware in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-revert-windows-settings-after-restart/"><u>Methods to Revert Windows Settings After Restart</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-routines-to-reactivate-window-explorer/"><u>Easy Routines to Reactivate Window Explorer</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-streamlining-your-watch-time-on-instagram-mobiledesktop/"><u>[Updated] In 2024, Streamlining Your Watch Time on Instagram (Mobile/Desktop)</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-my-top-criteria-for-selecting-the-best-video-to-audio-converter/"><u>New In 2024, My Top Criteria for Selecting the Best Video to Audio Converter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-w11-issues-with-csgo/"><u>Addressing W11 Issues with CS:GO</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-mail-alert-failures-with-9-practical-tips-for-windows-users/"><u>Fixing Mail Alert Failures with 9 Practical Tips for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-steps-enable-and-customize-widgets-on-win11/"><u>Easy Steps: Enable and Customize Widgets on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-window-11-style-hacks-and-themes/"><u>Exclusive Window 11 Style Hacks & Themes</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-samsung-galaxy-f04-drfone-by-drfone-virtual-android/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Samsung Galaxy F04 | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-6-best-sim-unlock-services-that-actually-work-on-your-oppo-a1x-5g-device-by-drfone-android/"><u>The 6 Best SIM Unlock Services That Actually Work On Your Oppo A1x 5G Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-manage-your-windows-11-administrative-credentials/"><u>Efficiently Manage Your Windows 11 Administrative Credentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-interface-quick-menu-install/"><u>Enhancing Windows Interface: Quick Menu Install</u></a></li>
</ul></div>
