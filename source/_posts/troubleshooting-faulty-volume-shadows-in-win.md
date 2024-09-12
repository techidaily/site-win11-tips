---
title: Troubleshooting Faulty Volume Shadows in Win
date: 2024-09-11T01:25:11.304Z
updated: 2024-09-12T01:25:11.304Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Faulty Volume Shadows in Win
excerpt: This Article Describes Troubleshooting Faulty Volume Shadows in Win
keywords: Fix Volume Shadow Issues Windows,Resolve Win Volume Errors,Troubleshoot Win Sound Problems,Solve Audio Distortion Win,Adjust Win Volume Glitches,Correct Sound Overlay Failures,Address Win Shadow Volume Faults
thumbnail: https://thmb.techidaily.com/25814137ff2b0c0573cec745d5d0a7576d58b816448c60f70b991c5a0f3d865d.jpeg
---

## Troubleshooting Faulty Volume Shadows in Win

 If the Volume Shadow Copy service isn't working, you'll see error messages when you try to use Backup and Restore or System Restore in Windows. We'll show you how you can fix Volume Shadow Copy when it's not working on a Windows PC, so you can get your backups going once more.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>







<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135363/19272" target="_top" id="2135363">
  <img src="//a.impactradius-go.com/display-ad/19272-2135363" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135363/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 1\. Enable and Start Volume Shadow Copy Services

 VSS errors can often arise because the Volume Shadow Copy and Microsoft Software Shadow Copy Provider services aren’t enabled or running. For example, many users have confirmed enabling those services can fix VSS error codes 0x81000202 and 0x81000203, which affect the System Restore tool. So, you may be able to resolve numerous Volume Shadow Copy errors by enabling VSS services like this:

1. First, press the **Windows** logo key + **S** and enter a Services search phrase to find that app.
2. Click **Services** inside the search results.
3. Double-click the **Volume Shadow Copy Service**.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/services-window.jpg)
4. Click the drop-down menu labeled **Startup type** and select **Automatic** if the service is set differently.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-type-drop-down-menu.jpg)
5. Press **Start** in the Volume Shadow Copy Service window.




<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115933/19272" target="_top" id="2115933">
  <img src="//a.impactradius-go.com/display-ad/19272-2115933" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115933/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




6. Click on the service window’s **Apply** and **OK** buttons to set the changed options.
7. Repeat steps three to six for the Microsoft Software Shadow Copy Provider service.
8. Also, check that the RPC Endpoint Mapper and DCOM Server Process dependency services for Volume Shadow Copy are enabled and running.

 Restart those shadow copy services if they’re already set as required. You can do that by right-clicking on those services and selecting the Restart context menu options for them.





<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139563/4704" target="_top" id="2139563">
  <img src="//a.impactradius-go.com/display-ad/4704-2139563" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139563/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134243/18498" target="_top" id="2134243">
  <img src="//a.impactradius-go.com/display-ad/18498-2134243" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134243/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->








<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137393/7443" target="_top" id="2137393">
  <img src="//a.impactradius-go.com/display-ad/7443-2137393" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137393/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)





<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098702/14409" target="_top" id="2098702">
  <img src="//a.impactradius-go.com/display-ad/14409-2098702" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098702/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

 Conflicting background apps or services are another potential cause of Volume Shadow Copy errors. Third-party backup utilities with snapshot managers are the most likely software packages to conflict with the Volume Shadow Copy Service. If you know you’ve installed a third-party backup manager, uninstalling it could be the best way to ensure it doesn’t cause any conflicts.

 However, you can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to stop third-party apps and services from starting with Windows to prevent conflicts from arising. This involves disabling startup items and services with Task Manager and MSConfig and restarting Windows. Then try utilizing the Windows Backup and Restore or System Restore tools after clean booting your PC to see if the VSS error persists.

 If it does, this means something you disabled during the clean boot is causing the problem. Now you can slowly re-enable each app until the problem reappears, then either uninstall or update the offending app.





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118313/7443" target="_top" id="2118313">
  <img src="//a.impactradius-go.com/display-ad/7443-2118313" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118313/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Back up and Restore Windows Again

 These solutions can potentially resolve many variable Volume Shadow Copy Service error messages and codes that pop up during system backup and restore operations. With Volume Shadow Copy fixed, you can back up and restore Windows with built-in system tools again.





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-enhancing-team-dynamics-through-effective-video-calls/"><u>[New] 2024 Approved Enhancing Team Dynamics Through Effective Video Calls</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-elevate-your-portraits-with-hdr-techniques/"><u>[New] Elevate Your Portraits with HDR Techniques</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-novices-compendium-understanding-pixel-perfection/"><u>[New] Novice's Compendium Understanding Pixel Perfection</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-from-script-to-screen-animating-stories-using-wmm/"><u>[Updated] 2024 Approved From Script to Screen Animating Stories Using WMM</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-rip-audio-from-youtube-in-3-ways-free-and-safe/"><u>[Updated] 2024 Approved How to Rip Audio From YouTube in 3 Ways [Free and Safe]</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-quick-fixes-the-hands-on-guide-to-generating-timely-captions-on-fb-media/"><u>[Updated] 2024 Approved Quick Fixes The Hands-On Guide to Generating Timely Captions on FB Media</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-the-ultimate-guide-to-snapchat-video-opposites/"><u>[Updated] 2024 Approved The Ultimate Guide to Snapchat Video Opposites</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-navigating-screen-capture-in-google-video-conferencing-for-2024/"><u>[Updated] Navigating Screen Capture in Google Video Conferencing for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-tiktok-mastery-the-art-of-editing-your-number/"><u>[Updated] TikTok Mastery The Art of Editing Your Number</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/3-ways-to-unlock-your-apple-iphone-6s-plus-for-free-by-drfone-ios/"><u>3 Ways to Unlock Your Apple iPhone 6s Plus for Free</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/broad-reach-strategy-share-your-twitch-channel-on-facebook-for-2024/"><u>Broad Reach Strategy Share Your Twitch Channel on Facebook for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/channel-charisma-standing-out-with-strategic-telegram-promotion/"><u>Channel Charisma Standing Out with Strategic Telegram Promotion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/complete-windows-11-clean-install-tutorial/"><u>Complete Windows 11 Clean Install Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decode-wacatacbml-symptoms-and-solutions-for-windows-malware-woes/"><u>Decode Wacatac.B!ml: Symptoms & Solutions for Windows Malware Woes</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-honor-magic-5-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Honor Magic 5? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiency-in-file-handling-windows-edition-max-156/"><u>Efficiency in File Handling: Windows Edition (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-life-with-premium-windows-software/"><u>Enhance Life with Premium Windows Software</u></a></li>
<li><a href="https://fox-that.techidaily.com/escape-iphone-headset-mode-stuck-try-these-8-effective-fixes-now/"><u>Escape iPhone Headset Mode Stuck? Try These 8 Effective Fixes Now</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/"><u>How to Change Netflix Location to Get More Country Version On Apple iPhone 11 Pro Max | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-high-cpu-usage-from-vanguard-user-mode-service-on-windows/"><u>How to Fix High CPU Usage From Vanguard User-Mode Service on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-hide-or-block-other-wi-fi-networks-on-windows/"><u>How to Hide or Block Other Wi-Fi Networks on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-locate-and-restore-missing-pin-on-windows-11-system/"><u>How To Locate and Restore Missing PIN on Windows 11 System</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-a-honor-90-pro-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Honor 90 Pro Phone that is Locked?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-causes-and-solutions-for-a-non-responsive-discord-overlay/"><u>Identifying Causes and Solutions for a Non-Responsive Discord Overlay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-low-resource-browsers-for-windows-macos-chromeos-users/"><u>Identifying Low Resource Browsers for Windows, macOS, ChromeOS Users</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-honor-100-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Honor 100 Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-comprehensive-tutorial-for-periscope-proficiency/"><u>In 2024, Comprehensive Tutorial for Periscope Proficiency</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-greatest-action-packed-gaming-escapades-top-10/"><u>In 2024, Greatest Action-Packed Gaming Escapades (Top 10)</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-netflix-location-to-get-more-country-version-on-vivo-y17s-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Netflix Location to Get More Country Version On Vivo Y17s | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-phone-number-from-your-apple-id-on-your-apple-iphone-x-by-drfone-ios/"><u>In 2024, How To Remove Phone Number From Your Apple ID on Your Apple iPhone X?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-spoofing-life360-how-to-do-it-on-motorola-moto-g-5g-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Spoofing Life360 How to Do it on Motorola Moto G 5G (2023)? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-most-useful-tips-for-pokemon-go-ultra-league-on-tecno-spark-10-5g-drfone-by-drfone-virtual-android/"><u>In 2024, The Most Useful Tips for Pokemon Go Ultra League On Tecno Spark 10 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-unlock-youtube-broadcast-google-meet-tutorial-steps/"><u>In 2024, Unlock YouTube Broadcast Google Meet Tutorial Steps</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-infinix-note-30-vip-racing-edition-phone-frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Infinix Note 30 VIP Racing Edition Phone FRP Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-the-system-level-driver-monitor-w11/"><u>Launching the System-Level Driver Monitor W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-error-x-solutions-for-windows-mail-mistakes/"><u>Mastering Error X: Solutions for Windows Mail Mistakes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-restarting-non-operational-obs/"><u>Mastering the Art of Restarting Non-Operational OBS</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-virtualdub-vs-the-competition-a-comprehensive-review-and-alternative-options-for-2024/"><u>New Virtualdub Vs. The Competition A Comprehensive Review and Alternative Options for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-absence-of-monitor-at-startup/"><u>Overcoming Absence of Monitor at Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-steam-installation-hurdles-in-windows-11/"><u>Overcoming Steam Installation Hurdles in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11s-zerox-error-at-keyboard-input/"><u>Overcoming Windows 11'S Zerox Error at Keyboard Input</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-error-0x800700e1/"><u>Overcoming Windows Error 0X800700E1</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-huawei-nova-y71-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Huawei Nova Y71 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-operation-requirements-and-error-740-on-windows-11/"><u>Quick Fixes for Operation Requirements and Error 740 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedies-to-resolve-screen-size-settings-issues-on-pcs/"><u>Remedies to Resolve Screen Size Settings Issues on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-accessible-nvidia-display-settings/"><u>Restoring Accessible Nvidia Display Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-failed-attempts-office-activation-troubleshooting/"><u>Reversing Failed Attempts: Office Activation Troubleshooting</u></a></li>
<li><a href="https://tech-hub.techidaily.com/slowdown-analysis-how-chatgpt-4-trails-behind-gpt-35-speed/"><u>Slowdown Analysis: How ChatGPT-4 Trails Behind GPT-3.5 Speed</u></a></li>
<li><a href="https://win-blog.techidaily.com/solution-found-pc-version-of-resident-evil-5-wont-launch-problems-resolved/"><u>Solution Found: PC Version of Resident Evil 5 Won't Launch Problems Resolved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-for-malfunctioning-keyboard-during-user-authentication-phase/"><u>Step-by-Step Fix for Malfunctioning Keyboard During User Authentication Phase</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-dxgierrordeviceremoved-in-oses/"><u>Steps to Address DXGI_ERROR_DEVICE_REMOVED in OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-windows-sandboxs-zero-error-hypervisor-missing/"><u>Steps to Resolve Windows Sandbox's Zero Error Hypervisor Missing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-permanent-delete-on-windows-pcs-with-the-power-of-your-desktop-bin-11/"><u>Streamlining Permanent Delete on Windows PCs with the Power of Your Desktop Bin (11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/students-new-tech-ally-asus-s15-oled-review-revealed/"><u>Students' New Tech Ally: Asus S15 OLED Review Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-intersection-of-ai-and-windows-11-user-experience/"><u>The Intersection of AI and Windows 11 User Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-camouflaging-search-on-11/"><u>The Ultimate Guide to Camouflaging Search on 11</u></a></li>
<li><a href="https://games-able.techidaily.com/tips-to-correctly-identify-gaming-software-on-steam/"><u>Tips to Correctly Identify Gaming Software on Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-after-windows-update-installation/"><u>Troubleshooting After Windows Update Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-accelerate-your-windows-printer-pace/"><u>Turbo-Accelerate Your WIndows Printer Pace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-covert-software-on-your-pc/"><u>Uncovering Covert Software on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/visual-diskspace-analyzer-tool-a-new-feature-for-windows-explorer/"><u>Visual Diskspace Analyzer Tool: A New Feature for Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/which-nvidia-driver-suits-you-gameplay-or-studio/"><u>Which Nvidia Driver Suits You? - Gameplay or Studio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-you-should-stick-with-windows-over-linux-for-gaming/"><u>Why You Should Stick With Windows Over Linux for Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/win-wise-utorrent-speeding-up-downloads-made-simple/"><u>Win-Wise uTorrent: Speeding Up Downloads Made Simple</u></a></li>
</ul></div>







<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    