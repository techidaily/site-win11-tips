---
title: Rectify Corner Design in Win11
date: 2024-07-12T16:58:37.030Z
updated: 2024-07-13T16:58:37.030Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rectify Corner Design in Win11
excerpt: This Article Describes Rectify Corner Design in Win11
keywords: Win11 Layouts,Win11 UI Fix,Windows 11 Corrections,Win11 Space Optimization,Rectify Win11 Design,Win11 Edge Alignment,Win11 Interface Enhancement
thumbnail: https://thmb.techidaily.com/9c704c9ab8ca818eb8c547f35c543ea321e006214fab450eba00af5408d5f618.jpg
---

## Rectify Corner Design in Win11

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

## 1\. How to Disable Rounded Corners in Windows 11 Using a Third-Party Tool

**Win11DisableOrRestoreRoundedCorners** is an open-source tool available on GitHub that can help you disable rounded corners on your Windows 11 PC. Since this tool modifies your PC's system files to remove the rounded corners, it's a good idea to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before using it.

1. Head over to GitHub’s website to [download the Win11DisableOrRestoreRoundedCorners tool](https://github.com/valinet/Win11DisableRoundedCorners/releases).
2. Double-click the downloaded executable file to run it.
3. If you see the Microsoft Defender SmartScreen window, click on **More info** and then select **Run anyway**.
4. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Microsoft Defender SmartScreen Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-smartscreen-window.jpg)

 Once you complete the above steps, a PowerShell window should appear and disable rounded corners on your PC. Here’s a glimpse of how your windows will look once the rounded corners are disabled.

![Square Corners in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/square-corners-in-windows-11.jpg)

 Note that this tool will not disable rounded corners in the Start menu or some modern apps. If you want to revert the changes later, simply run the downloaded EXE file again.

## 2\. How to Disable Rounded Corners in Windows 11 Using the Registry Editor

 Don't want to use a third-party tool? No problem. You can also disable rounded corners in Windows 11 by making changes to the Windows Registry. However, it's crucial to exercise caution, as modifying registry files without proper knowledge can be risky.

 Before you proceed, consider [backing up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just in case. After that, use these steps to disable rounded corners via the Registry Editor:

1. Press **Win + S** to open the search menu.
2. Type in **registry editor** and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Navigate to **Computer > HKEY\_CURRENT\_USER > Software > Microsoft > Windows > DWM**.
5. Right-click on the **DWM** key and select **New > DWORD (32-bit) Value**. Rename it to **UseWindowFrameStagingBuffer**.
6. Double-click the newly created DWORD and enter **0** in the **Value data** field. Then, click **OK**.
7. [Restart your PC](https://www.makeuseof.com/windows-restart-methods/) to apply the changes.  
![Disable Rounded Corners in Windows 11 via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-rounded-corners-in-windows-11-via-registry-editor.jpg)

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

## 3\. How to Disable Rounded Corners in Windows 11 via Device Manager

 Another way to remove rounded corners in Windows 11 is by disabling the graphics driver on your PC. However, it is important to consider a few caveats. Firstly, disabling the graphics driver will result in reduced display performance, lower screen resolutions, and the deactivation of any visual effects. Secondly, this will also prevent you from running any graphics-intensive applications or games on your PC.

 If you are fine with these trade-offs, use these steps to disable rounded corners via Device Manager.

1. Press **Win + X** to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Display adapters** to expand it.
4. Right-click on your display driver and select **Disable device**.  
![Disable Graphics Driver on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-graphics-driver-on-windows-11.jpg)

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/tech-tip-how-to-turn-off-nvidia-ui/"><u>Tech Tip: How to Turn Off NVIDIA UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-engineering-the-taskbar-key-steps-to-better-windows-11-ux/"><u>Re-Engineering the Taskbar: Key Steps to Better Windows 11 UX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x800704cf-error-in-win11-marketplace/"><u>Overcoming 0X800704CF Error in Win11 Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-headset-microphone-blockage/"><u>Unblocking Windows Headset Microphone Blockage</u></a></li>
<li><a href="https://extra-tips.techidaily.com/uncover-the-best-15-free-web-based-image-editing-tools-of-2023/"><u>Uncover the Best 15 Free Web-Based Image Editing Tools of 2023</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-a-vivo-v30-lite-5g-easily-by-drfone-android/"><u>How To Unlock a Vivo V30 Lite 5G Easily?</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-oppo-find-x6-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Oppo Find X6 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-winterminals-bg-pic/"><u>Setting WinTerminal's Bg Pic</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/how-to-cut-audio-in-imovie-on-mac-and-iphone-in-2024/"><u>How to Cut Audio in iMovie on Mac & iPhone, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-steam-library-accessibility-on-win-11-pcs/"><u>Troubleshooting Steam Library Accessibility on Win 11 PCs</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-reclaim-lively-sounds-in-muted-video-tweets/"><u>[New] 2024 Approved  Reclaim Lively Sounds in Muted Video Tweets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revealing-the-hidden-search-bar-in-win11s-task-manager/"><u>Revealing the Hidden Search Bar in Win11's Task Manager</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/elevate-your-visual-storytelling-advanced-zooming-on-snapchat/"><u>Elevate Your Visual Storytelling  Advanced Zooming on Snapchat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-roblox-error-262-instantly/"><u>Overcoming Roblox Error 262 Instantly</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-ioss-best-ps2-emulation-software-guide/"><u>In 2024, IOS’s Best PS2 Emulation Software Guide</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-oneplus-ace-2v-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of OnePlus Ace 2V Without PUK Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinvigorating-faulty-troubleshooters-in-windows-os/"><u>Reinvigorating Faulty Troubleshooters in Windows OS</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-uncover-linguistic-groan-phenomenon/"><u>New Uncover Linguistic Groan Phenomenon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-winget-in-windows-11-environments/"><u>Reactivating Winget in Windows 11 Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-onedrive-errors-on-windows-effective-fixes/"><u>Tackling OneDrive Errors on Windows: Effective Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-your-muted-windows-start-button-icon/"><u>Resurrecting Your Muted Windows Start Button Icon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-role-of-windows-print-management-interface/"><u>Understanding the Role of Windows Print Management Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-software-windows-best-photo-arrangers-reviewed/"><u>Winning Software: Windows' Best Photo Arrangers Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-banishing-the-persistent-pink-error-on-windows/"><u>The Ultimate Guide to Banishing the Persistent Pink Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-and-utilizing-widgets-in-windows-11/"><u>Accessing and Utilizing Widgets in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-snap-uac-dialogues/"><u>A Step-by-Step Guide to Snap UAC Dialogues</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-viral-content-showdown-is-the-time-for-likee-to-surpass-tiktok-nearing-for-2024/"><u>[New] Viral Content Showdown  Is the Time for Likee to Surpass TikTok Nearing for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-top-10-free-whiteboard-video-makers-for-windows-and-mac-for-2024/"><u>New Top 10 Free Whiteboard Video Makers for Windows and Mac for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-windows-11-defense-enhanced-filter-options-via-context-menu/"><u>Upgrade Your Windows 11 Defense: Enhanced Filter Options via Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-configurations-restarted-a-triad-of-tips/"><u>Win11 Configurations Restarted: A Triad of Tips</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-the-ultimate-guide-to-nokia-c12-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Nokia C12 Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-transforming-vision-into-action-building-a-successful-fb-reel-channel/"><u>2024 Approved  Transforming Vision Into Action  Building a Successful FB Reel Channel</u></a></li>
<li><a href="https://screen-recording.techidaily.com/unlocking-the-potential-of-ez-grabber-for-2024/"><u>Unlocking the Potential of EZ Grabber for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-blocking-self-starting-windows-store/"><u>Strategies for Blocking Self-Starting Windows Store</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-expert-tips-to-enhance-your-adobe-presentation-videos-for-2024/"><u>[New] Expert Tips to Enhance Your Adobe Presentation Videos for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-instaloops-unleashed-the-ultimate-guide-to-engagement/"><u>[Updated] InstaLoops Unleashed  The Ultimate Guide to Engagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-hyper-v-setup-process-for-windows-11-home-edition/"><u>Navigating the Hyper-V Setup Process for Windows 11 Home Edition</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/wave-goodbye-to-costs-with-our-50-free-banners-offer-in-2024/"><u>Wave Goodbye to Costs with Our 50 Free Banners Offer, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-modern-standby-gets-a-bad-rap-in-windows/"><u>Why Modern Standby Gets a Bad Rap in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-mouse-response-time-on-windows-devices/"><u>Optimizing Mouse Response Time on Windows Devices</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-poco-m6-pro-4g-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Poco M6 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-vivo-v27e-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Vivo V27e? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-cutting-the-fat-in-windows-11/"><u>The Ultimate Guide to Cutting the Fat in Windows 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-the-essential-directory-of-fee-free-high-quality-audio-player-applications-for-android-and-ios-devices/"><u>Updated The Essential Directory of Fee-Free, High-Quality Audio Player Applications for Android and iOS Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-running-sfc-on-windows/"><u>Understanding and Running SFC on Windows</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-discover-5-trustworthy-websites-offering-humorous-background-sounds-legally/"><u>New 2024 Approved Discover 5 Trustworthy Websites Offering Humorous Background Sounds Legally</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-the-essential-how-to-guide-for-filming-anywhere-anytime/"><u>In 2024, The Essential How-To Guide for Filming Anywhere, Anytime</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-premium-playlist-manager-for-android-users/"><u>In 2024, Premium Playlist Manager for Android Users</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-unmasked-influence-introducing-the-power-players-of-insta/"><u>2024 Approved  Unmasked Influence  Introducing the Power Players of Insta</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-s-mode-a-safe-choice-for-beginners/"><u>Windows 11 S Mode: A Safe Choice for Beginners?</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-best-online-video-saving-tools-reviewed-and-ranked/"><u>[New] In 2024, Best Online Video Saving Tools Reviewed & Ranked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-oculus-quest-2-as-a-windows-vr-device/"><u>Adapting Oculus Quest 2 as a Windows VR Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swivel-your-snaps-with-these-6-steps-for-windows-11-users/"><u>Swivel Your Snaps with These 6 Steps for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-hack-design-your-own-unique-pin-pattern/"><u>Windows 10/11 Hack: Design Your Own Unique Pin Pattern</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-multiscreen-woes/"><u>Understanding Windows Multiscreen Woes</u></a></li>
</ul></div>
