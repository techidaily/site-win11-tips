---
title: Quick Tips for Wi-Fi Management in Win 11
date: 2024-09-05T19:41:54.412Z
updated: 2024-09-06T19:41:54.412Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Tips for Wi-Fi Management in Win 11
excerpt: This Article Describes Quick Tips for Wi-Fi Management in Win 11
keywords: Win 11 Wi-Fi Control,Win 11 Speed Boost,Win 11 Network Optimization,Win 11 Security Updates,Win 11 Connectivity Tips,Win 11 Router Setup Guide,Win 11 Bandwidth Management
thumbnail: https://thmb.techidaily.com/d568502deceace8c4ecf36ae07d16a3133e76d13956dfbeb425d156edf1af5a5.png
---

## Quick Tips for Wi-Fi Management in Win 11

 By default, Windows 11 remembers any Wi-Fi network you connect to. This allows Windows to automatically connect to the network whenever it is in range. If you don’t want that to happen, you can simply remove the network from your PC.

 From time to time, you may want to remove some old Wi-Fi networks that you once connected to but never will again. In this guide, we'll show you four different ways to remove a saved Wi-Fi network from Windows 11.

<!-- affiliate ads begin -->
<span id="1834906">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834906.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834906">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834906.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834906%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834906/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## The Benefits of Removing Old Wi-Fi Networks From Windows 11

 While having a long list of saved Wi-Fi networks isn’t necessarily a bad thing, there may be times when you want to remove specific Wi-Fi networks from your PC.

 For example, if you previously connected your PC to a free public network but do not intend to use it again, it is best to simply remove the network. Or perhaps you don't want your PC to automatically connect to a specific network when it’s in range. Besides, forgetting and rejoining a network also happens to be an effective solution for fixing minor connection issues.

 Over time, your PC may accumulate a long list of Wi-Fi networks that you won't be connecting to. In such cases, it makes sense to remove old and unused Wi-Fi networks from your PC.

## 1\. Remove a Saved Wi-Fi Network Using the Quick Settings Panel

 The Quick Settings panel on Windows provides access to some commonly used settings. It also makes it simple to remove a saved Wi-Fi network from Windows 11.

 Press**Win + A** to open the Quick Settings panel. Click the sideways-facing arrow next to the**Wi-Fi** button. You'll see a list of Wi-Fi networks, including the one to which you're currently connected. Right-click on the network you want to remove and select**Forget** .

![Remove Wi-Fi Network From Quick Settings Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-From-Quick-Settings-Panel.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135349/19272" target="_top" id="2135349">
  <img src="//a.impactradius-go.com/display-ad/19272-2135349" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135349/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Like using the Quick Settings on Windows? Check out[how to customize the Quick Settings panel on your Windows 11 computer](http://www.makeuseof.com/windows-11-customize-quick-settings-menu/) .

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123466/16836" target="_top" id="2123466">
  <img src="//a.impactradius-go.com/display-ad/16836-2123466" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123466/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Remove a Saved Wi-Fi Network via the Settings App

 If the Wi-Fi network you want to remove is not nearby, it will not appear in the Quick Settings panel. In that case, you can use the Windows 11 Settings app to remove it.

To forget a Wi-Fi network via the Settings app:

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Network & internet** tab and click on**Wi-Fi** .
3. Click on**Manage known networks** .
4. Click the**Forget** button next to a network to delete it.  
![Remove Wi-Fi Network on Windows From the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-on-Windows-From-the-Settings-App.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139122/17108" target="_top" id="2139122">
  <img src="//a.impactradius-go.com/display-ad/17108-2139122" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139122/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 And that's about it. Once you click the**Forget** button, Windows will remove the network profile associated with that network.

## 3\. Remove a Saved Wi-Fi Network With Command Prompt or PowerShell

 Another option for removing a saved Wi-Fi network is to use a command-line tool such as Command Prompt or Windows PowerShell. You can easily forget a Wi-Fi network by running a couple of commands in the terminal window. Here’s how you can go about it.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**command prompt** or**windows powershell** and select**Run as administrator** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the console, type the following command and press**Enter** to view a list of saved Wi-Fi networks on your PC.  
`netsh wlan show profiles`
5. Note down the name of the network profile you want to remove.
6. Paste the following command, replace**WIFIName** with the network name, and press**Enter** .  
`netsh wlan delete profile name="WIFIName"`  
![Delete a Saved Wi-Fi Profile Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Delete-a-Saved-Wi-Fi-Profile-Using-Command-Prompt.jpg)

 You can repeat the above command to remove as many networks as you want. Conveniently, the command-line tool also lets you remove all the saved Wi-Fi networks at once. To do so, use this command:

`netsh wlan delete profile name=* i=*`

## 4\. Remove a Saved Wi-Fi Network Using Registry Editor

 If you’re feeling adventurous, you can also use the Registry Editor to remove a saved Wi-Fi network from Windows. Since deleting registry files is risky, you should only use this method if the other ones do not work.

 If you decide to use this method, make sure you back up all your registry files just in case. If you need help, check our guide on[how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

To remove a Wi-Fi network using the Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** and press**Enter** . This will open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **Computer > HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows NT > CurrentVersion > NetworkList > Profiles** .
5. Within the**Profiles** key, you’ll find several subkeys. Each key represents a network profile.
6. Select a subkey and look for the**ProfileName** DWORD on your right to identify the name of the network.
7. Once you find the key corresponding to your network, right-click on it and select**Delete** .
8. Select**Yes** to confirm.  
![Remove Wi-Fi Network on Windows Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-on-Windows-Using-Registry-Editor.jpg)

 Once you complete the above steps, the saved profile will be removed from your system.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132162/7443" target="_top" id="2132162">
  <img src="//a.impactradius-go.com/display-ad/7443-2132162" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132162/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Reconnect to a Forgotten Wi-Fi Network on Windows 11

 You can always reconnect to a Wi-Fi network later after forgetting it. For that, you'll need to manually select the network and enter the password for authentication.

 To connect to a Wi-Fi network on Windows 11, press**Win + A** to open the Quick Settings panel. Click the arrow next to the Wi-Fi button to view a list of nearby networks. Select the network you want to connect to and click the**Connect** button. Enter the password for that network and you should be good.

![Connect to a Wi-Fi Network Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Connect-to-a-Wi-Fi-Network-Windows-11.jpg)

<!-- affiliate ads begin -->
<span id="1265663">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1265663.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/4482-1265663">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1265663.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmartinic.evyy.net%2Fc%2F5597632%2F1265663%2F4482'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1265663/4482" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Of course, this isn't the only way to connect to a Wi-Fi network on Windows. Refer to our guide on[different ways to connect to Wi-Fi on Windows](https://www.makeuseof.com/windows-ways-to-connect-to-wifi/) to learn more.

## Removing Saved Wi-Fi Networks From Windows 11

 Although there are no significant disadvantages to keeping old Wi-Fi networks on your PC, you may want to delete some of them just to keep things tidy. Luckily, Windows 11 offers ample ways to remove unused Wi-Fi networks.

 Aside from deleting old Wi-Fi networks, you can also manage wireless network profiles on Windows in a few different ways.


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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-ensuring-data-privacy-while-transforming-youtube-video-audio-to-mp3/"><u>[New] 2024 Approved Ensuring Data Privacy While Transforming YouTube Video Audio to MP3</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-best-picks-no-charging-high-definition-video-players-for-pcmacos/"><u>[New] Best Picks No-Charging, High Definition Video Players for PC/MacOS</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-decoding-the-divergence-360-film-vs-virtual-reality-for-2024/"><u>[New] Decoding the Divergence 360° Film Vs. Virtual Reality for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-irreversible-termination-of-youtubes-brevity-mode/"><u>[New] Irreversible Termination of YouTube’s Brevity Mode</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-affiliate-acquaintanceships-elevating-budget-channels-with-ease-for-2024/"><u>[Updated] Affiliate Acquaintanceships Elevating Budget Channels with Ease for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-comprehensive-morphvox-modification-handbook/"><u>[Updated] In 2024, Comprehensive MorphVOX Modification Handbook</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-syncing-visual-elements-across-platforms/"><u>2024 Approved Syncing Visual Elements Across Platforms</u></a></li>
<li><a href="https://driver-install.techidaily.com/breeze-through-m-audio-track-troubles/"><u>Breeze Through M-Audio Track Troubles</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/bridging-realities-the-art-of-using-luts-in-vfx-and-ar-for-2024/"><u>Bridging Realities The Art of Using LUTs in VFX & AR for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-forbidden-save-messages-on-windows-pcs/"><u>Clearing Up 'Forbidden Save' Messages on Windows PCs</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/comprehensive-app-audit-by-az-recorder/"><u>Comprehensive App Audit by AZ Recorder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-world-of-warcrafts-fatal-problem-132-on-windows/"><u>Conquering World of Warcraft's Fatal Problem #132 on Windows</u></a></li>
<li><a href="https://solve-hot.techidaily.com/cookiebot-driven-success-elevate-your-website-engagement-and-rankings/"><u>Cookiebot-Driven Success: Elevate Your Website Engagement and Rankings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-failed-task-sequences-fixing-error-0x8007000f/"><u>Dealing with Failed Task Sequences: Fixing Error 0X8007000f</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-steps-to-access-and-manage-printers-efficiently/"><u>Decoding Windows: Steps to Access and Manage Printers Efficiently</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/discovering-those-who-left-my-instagram-circle-for-2024/"><u>Discovering Those Who Left My Instagram Circle for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/download-and-save-your-cortana-activity-log/"><u>Download and Save Your Cortana Activity Log</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-windows-update-requests/"><u>Eliminating Windows Update Requests</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/explore-how-you-can-do-speech-to-text-in-powerpoint-for-2024/"><u>Explore How You Can Do Speech-To-Text in Powerpoint for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/first-steps-in-the-field-of-prompt-creation/"><u>First Steps in the Field of Prompt Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-update-error-a-step-by-step-guide/"><u>Fixing Windows Update Error: A Step-By-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-zero-to-hero-hyper-v-setup-for-w11-home-users/"><u>From Zero to Hero: Hyper-V Setup for W11 Home Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-past-the-roadblock-solutions-for-unpreviewable-files-in-email-apps/"><u>Getting Past the Roadblock: Solutions for Unpreviewable Files in Email Apps</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/harmonic-horizons-mac-sound-exploration-guide/"><u>Harmonic Horizons Mac Sound Exploration Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-safeguard-your-pc-by-altering-password-on-win-11/"><u>How to Safeguard Your PC by Altering Password on Win 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-text-messages-from-poco-m6-pro-4g-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Text Messages from Poco M6 Pro 4G to New Phone | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-samsung-galaxy-a25-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Samsung Galaxy A25 5G | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-xiaomi-redmi-note-12-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Xiaomi Redmi Note 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-vivo-y28-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Vivo Y28 5G? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-recommended-best-applications-for-mirroring-your-vivo-y17s-screen-drfone-by-drfone-android/"><u>In 2024, Recommended Best Applications for Mirroring Your Vivo Y17s Screen | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-seamless-strategy-integrating-linktree-into-your-tiktok-bio/"><u>In 2024, Seamless Strategy Integrating Linktree Into Your TikTok Bio</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-tecno-spark-10c-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Tecno Spark 10C Phone Hassle-Free</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-what-does-jailbreaking-iphone-6s-i-do-get-answers-here-by-drfone-ios/"><u>In 2024, What Does Jailbreaking iPhone 6s i Do? Get Answers here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-approaches-to-maximize-windows-11s-beginning/"><u>Innovative Approaches to Maximize Windows 11'S Beginning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-savings-techniques-for-thrifty-windows-10-enthusiasts/"><u>Key Savings Techniques for Thrifty Windows 10 Enthusiasts</u></a></li>
<li><a href="https://win-amazing.techidaily.com/make-windows-11-detect-your-usb-device-easy-fixes-and-solutions/"><u>Make Windows 11 Detect Your USB Device: Easy Fixes and Solutions</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-join-avi-files-for-free-top-10-reliable-avi-joiner-software/"><u>New In 2024, Join AVI Files for Free Top 10 Reliable AVI Joiner Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-mysterious-obs-error-a-step-by-step-approach/"><u>Overcoming Mysterious OBS Error: A Step-by-Step Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-wi-fi-setup-obstacles-bridging-actions-on-windows-os/"><u>Overcoming Wi-Fi Setup Obstacles: Bridging Actions on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-clock-anomalies-in-google-chrome/"><u>Overcoming Windows Clock Anomalies in Google Chrome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-disconnecting-onedrive-from-your-windows-explorer-view/"><u>Quick Fix: Disconnecting OneDrive From Your Windows Explorer View</u></a></li>
<li><a href="https://driver-download.techidaily.com/quick-tutorial-getting-your-sound-blaster-z-up-and-running-in-windows-10/"><u>Quick Tutorial: Getting Your Sound Blaster Z Up and Running in WINDOWS 10!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-text-display-issue-on-win11-msresouce/"><u>Rectifying Text Display Issue on Win11: MsResouce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-accessible-wastecan-icon-on-windows-11/"><u>Reinstating Accessible Wastecan Icon on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reliable-re-boot-methods-your-explore-experience-win-11/"><u>Reliable Re-Boot Methods: Your Explore Experience, Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-legacy-systems-for-grandparent-users/"><u>Simplifying Legacy Systems for Grandparent Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simultaneous-file-release-techniques-for-windows-enthusiasts/"><u>Simultaneous File Release Techniques for Windows Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-locating-and-using-the-component-services-tool/"><u>Step-by-Step: Locating and Using the Component Services Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-into-snap-mastery-configuring-windows-with-powertoys/"><u>Step-Into Snap Mastery: Configuring Windows with PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-no-detected-fingerprint-on-windows-systems/"><u>Tackling No Detected Fingerprint on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-1011-error-0x0000004e-quick-guide/"><u>Tackling Windows 10/11 Error 0X0000004E Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-win11-mouse-settings-and-controls/"><u>The Ultimate Guide to Win11 Mouse Settings & Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-system-speed-with-enhanced-window-run-utility/"><u>Transforming System Speed with Enhanced Window Run Utility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-guide-stop-vmfreeze-and-freezes-in-windows-11/"><u>Troubleshooting Guide: Stop VMfreeze & Freezes in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-printing-woes-a-guide-to-windows-11/"><u>Troubleshooting Printing Woes: A Guide to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-notepad-freeze-issues/"><u>Troubleshooting Windows Notepad Freeze Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-the-calculator-a-windows-11-primer/"><u>Uncovering the Calculator: A Windows 11 Primer</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/vidma-screen-recorder-unveiled-in-depth-review-insights/"><u>Vidma Screen Recorder Unveiled In-Depth Review Insights</u></a></li>
</ul></div>
