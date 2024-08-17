---
title: How to Disrupt a Persistent Dark Theme on Windows
date: 2024-08-16T01:34:32.916Z
updated: 2024-08-17T01:34:32.916Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Disrupt a Persistent Dark Theme on Windows
excerpt: This Article Describes How to Disrupt a Persistent Dark Theme on Windows
keywords: WinDarkModeStop,BreakWindowsTheme,EndPersistentDark,RemoveWinThemes,UnlockOSColor,DisableDarkFeature,LightenWindowsUI
thumbnail: https://thmb.techidaily.com/637640ea893a93e111b973883d0f05d3166b54a33cafa8864cd2873a58b515ce.png
---

## How to Disrupt a Persistent Dark Theme on Windows

 You might often enable dark mode on Windows to reduce eye strain, but it’s quite frustrating when you suddenly can’t switch from dark to normal mode again

 If you’re experiencing this issue, then we’ve got solutions for you. In this article, we’ll explore the five ways to fix your Windows PC when it’s stuck in dark mode.

## 1\. Configure Settings in the Local Group Policy Editor

 The Local Group Policy Editor (LGPE) is a tool that allows you to configure various settings on your device. Interestingly, you can also use the LGPE to troubleshoot various system issues.

 Now, let’s check out how this tool can help you when your device is stuck in dark mode:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
4. Double-click on the **Prevent changing theme** option on the right-hand side pane.

![Using the Local Group Policy Editor to Prevent Others From Changing the Desktop Theme](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Local-Group-Policy-Editor-to-Prevent-Others-From-Changing-the-Desktop-Theme.jpg)

 Next, select the **Not Configured** or **Disabled** option on the pop-up screen. From there, click **Apply** and then click **OK** to disable the **Prevent changing theme** option.

 If the issue persists, navigate to the **Personalization** folder as per the previous steps and then disable the following options:

* Prevent changing color and appearance
* Prevent changing desktop background
* Prevent changing screen saver
* Prevent changing color scheme
* Load a specific theme
* Force specific screen saver
* Force a specific visual style file or force Windows Classic

 Finally, restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
## 2\. Tweak the Contrast Theme Settings

 You might be stuck in dark mode simply because you’ve enabled the "High contrast" option on Windows. So, let’s check out how you can resolve this problem:

1. Press **Win + I** to open the system settings.
2. Select **Ease of Access** from the options.
3. Click **High contrast** on the left.
4. **Turn off** the button below the **Turn on high contrast** option and check if this resolves the issue.

![Turning off the button below the Turn on high contrast option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/turning-off-the-button-below-the-turn-on-high-contrast-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Edit the Relevant Registry Files

 Editing some Registry files could also help you tackle the issue at hand. But to be on the safe side, [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before you proceed. This tool is sensitive and could wreak havoc on your PC if you tweak the wrong keys.

 Now, here’s how to fix the “dark mode” problem using the Registry Editor:

1. Press **Win + R** to open the Run command dialog box.
2. Type **regedit** and press **Enter** to open the Registry Editor. Alternatively, check out [the various ways to access the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Type the following command into the address bar:

HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Themes\Personalize

 Next, double-click on the **AppsUseLightTheme** value on the right-hand side pane.

![Clicking the AppsUseLightTheme value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-appsuselighttheme-value.jpg)

 Type **0** in the **Value data** box and then click **OK**.

 From there, set the **Value data** as **0** for the **ColorPrevalence**, **EnableTransparency**, and **SystemUsesLightTheme** values. When you finish, restart your device and check if this resolves the problem.

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Disable Third-Party Apps Like the Auto Dark Mode Tool

 Apps like the [Microsoft Auto Dark Mode](https://apps.microsoft.com/store/detail/auto-dark-mode/XP8JK4HZBVF435) tool switch between dark and light modes at scheduled times. If you’ve configured its settings unknowingly, then it might end up enabling the dark mode feature unexpectedly.

 To resolve the issue, the best solution would be to disable this tool (and any other similar third-party app). Alternatively, you can configure the tool’s settings to your liking. That way, your device will only go into dark mode when you want it to.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
## 5\. Perform Some Generic Windows-Based Fixes

 Still struggling to resolve the issue? Perhaps the error is caused by corrupted system files. In this case, the best solution is to [repair corrupted Windows files using its built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

 And if all else fails, [update your Windows device](https://www.makeuseof.com/update-windows-manually/) and see if that helps.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## No More Getting Stuck in Dark Mode

 There’s no denying that the Windows dark mode option is quite convenient. However, being unable to switch from dark to normal mode is quite unpleasant. If your device is stuck in dark mode, try any of the solutions we’ve covered.


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
<li><a href="https://youtube-tips.techidaily.com/avigating-payment-options-for-youtube-tv-for-2024/"><u>[New] Navigating Payment Options for YouTube TV for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/rotect-your-data-while-converting-youtube-videos-to-mp3-tracks/"><u>[New] Protect Your Data While Converting YouTube Videos to MP3 Tracks</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-explore-classic-ps3-games-through-best-emulators-2023-for-2024/"><u>[Updated] Explore Classic PS3 Games Through Best Emulators 2023 for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-going-against-gravity-innovative-ways-to-rewind-youtube-content/"><u>[Updated] Going Against Gravity  Innovative Ways to Rewind YouTube Content</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-mastering-aiseesofts-capture-tech-screen-recording-basics-for-2024/"><u>[Updated] Mastering Aiseesoft's Capture Tech  Screen Recording Basics for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-low-volume-settings-in-os-xwindows/"><u>[Updated] Mastering Low-Volume Settings in OS X/Windows</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-oneplus-12-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on OnePlus 12 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-infinix-smart-8-plus-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Infinix Smart 8 Plus to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/charger-free-solutions-for-keeping-your-phone-battery-full/"><u>Charger-Free Solutions for Keeping Your Phone Battery Full</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-windows-dns-cache-via-steam-settings/"><u>Clearing Windows DNS Cache via Steam Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/compute-disk-space-efficiently-via-powershell-commands/"><u>Compute Disk Space Efficiently via PowerShell Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/corrective-measures-for-copy-pasting-malfunction/"><u>Corrective Measures for Copy-Pasting Malfunction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cross-pc-qbittorrent-migration-tips-and-techniques/"><u>Cross-PC qBittorrent Migration Tips & Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-audio-recording-the-windows-11-handbook/"><u>Easy Audio Recording: The Windows 11 Handbook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-packaged-photo-errors-on-windows-11-and-11-pro/"><u>Eliminating Packaged Photo Errors on Windows 11 & 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-secure-data-movement-in-microsoft-edge-shield-for-w11/"><u>Enabling Secure Data Movement in Microsoft Edge Shield for W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-archived-media-madvr-for-windows-enthusiasts/"><u>Enhance Archived Media: MadVR for Windows Enthusiasts</u></a></li>
<li><a href="https://driver-install.techidaily.com/enhance-your-pc-display-updating-hdmi-drivers-in-w10w11/"><u>Enhance Your PC Display: Updating HDMI Drivers in W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-computer-functionality-post-intel-hardware-violation/"><u>Enhancing Computer Functionality Post-Intel Hardware Violation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-file-visibility-strategic-application-of-descriptions/"><u>Enhancing File Visibility: Strategic Application of Descriptions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-disk-read-windows-error-immediately/"><u>Fixing 'Disk Read' Windows Error Immediately</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-turn-off-microsofts-voice-assistant/"><u>Guide to Turn Off Microsoft's Voice Assistant</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ideal-webp-vision-tools-for-windows-enthusiasts/"><u>Ideal WebP Vision Tools for Windows Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-spool-service-relaunch/"><u>Instant Spool Service Relaunch</u></a></li>
<li><a href="https://review-topics.techidaily.com/issues-playing-h-265-hevc-video-on-galaxy-a14-4g-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Issues playing H.265 HEVC video on Galaxy A14 4G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/latency-logic-how-to-quickly-examine-ethernet-performance/"><u>Latency Logic: How to Quickly Examine Ethernet Performance</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/leading-animals-in-play-androids-favorites-list-for-2024/"><u>Leading Animals in Play  Android's Favorites List for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-cross-language-dialogues-with-windows-11-keyboard-combinations/"><u>Mastering Cross-Language Dialogues with Windows 11 Keyboard Combinations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-directory-management-without-renaming-feature-in-win-11/"><u>Mastering the Art of Directory Management without Renaming Feature in Win 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/mastering-twitter-archives-for-analysis-for-2024/"><u>Mastering Twitter Archives for Analysis for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-from-amateur-to-expert-mastering-the-art-of-professional-movie-making/"><u>New From Amateur to Expert Mastering the Art of Professional Movie Making</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-playtime-configuring-amd-card-in-windows-games/"><u>Perfecting Playtime: Configuring AMD Card in Windows Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalize-your-cmd-window-set-as-default/"><u>Personalize Your CMD Window: Set as Default</u></a></li>
<li><a href="https://win11-tips.techidaily.com/powerful-scripts-to-detect-pcs-ip-and-mac/"><u>Powerful Scripts to Detect PC's IP and MAC</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/projector-buying-101-key-aspects-to-assess-before-making-your-decision/"><u>Projector Buying 101: Key Aspects to Assess Before Making Your Decision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-lost-steam-connections-on-pc/"><u>Quick Fixes for Lost Steam Connections on PC</u></a></li>
<li><a href="https://win-able.techidaily.com/1723006358908-resolve-your-dead-by-daylight-crash-issues-with-these-simple-fixes-for-2n4/"><u>Resolve Your Dead By Daylight Crash Issues with These Simple Fixes for 2N4!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-reds-greens-and-blues-avoiding-windows-color-confusion/"><u>Resolving Reds, Greens & Blues: Avoiding Windows' Color Confusion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-success-unleash-potential-using-these-top-8-studying-techniques-for-windows/"><u>Skyrocket Success: Unleash Potential Using These Top 8 Studying Techniques for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-sync-path-for-android-plus-windows-duo/"><u>Step-by-Step Sync Path for Android + Windows Duo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-correct-windows-alt-key-problems/"><u>Strategies to Correct Windows ALT Key Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-temporary-file-extraction-in-windows-os/"><u>Streamlining Temporary File Extraction in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-addressing-faulty-or-missing-device-alerts-win1011/"><u>Tips for Addressing Faulty or Missing Device Alerts, Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-network-potential-through-dns-on-windows-11/"><u>Unlocking Network Potential Through DNS on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-nvidia-written-out-errors-guide-to-recovery/"><u>Unlocking NVIDIA' Written Out Errors - Guide to Recovery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-nas-on-smartphones-and-tablets/"><u>Utilizing NAS on Smartphones and Tablets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1110-resolving-code-xc0000142-failure/"><u>Windows 11/10: Resolving Code XC0000142 Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-photo-shortcut-insights/"><u>Windows Photo Shortcut Insights</u></a></li>
</ul></div>
