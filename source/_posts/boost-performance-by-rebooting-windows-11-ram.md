---
title: Boost Performance by Rebooting Windows 11 RAM
date: 2024-07-12T18:08:04.406Z
updated: 2024-07-13T18:08:04.406Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Boost Performance by Rebooting Windows 11 RAM
excerpt: This Article Describes Boost Performance by Rebooting Windows 11 RAM
keywords: Boost PC Speed,Win11 RAM Optimize,System Reboot Benefits,RAM Enhancement Tips,Windows 11 Performance,Recharge Computer,RAM Performance Boost
thumbnail: https://thmb.techidaily.com/c5a835a587cbde63390ec7ae0f646f52f65cc154a66fb89768e9cd878c5a4c7b.jpg
---

## Boost Performance by Rebooting Windows 11 RAM

 Are you having trouble with virtual memory on Windows 11? Resetting virtual memory on Windows can improve system performance or free up extra hard drive space. So, we'll show you exactly how to reset the virtual memory on your Windows 11 computer.

## What Is Virtual Memory and How Does It Work?

 Virtual memory, also known as a paging file, is a technology used in computers to allow programs to use more memory than what's physically available on it. When you run out of RAM, your operating system relies on virtual memory to continue running programs.

 The computer creates a special file called a page or swap file on the hard drive. It stores some data temporarily removed from RAM and written to the hard drive. This way, the computer can access more memory than what's installed.

 Although virtual memory allows programs to operate smoothly, it can also hurt overall performance. For example, if your computer runs out of RAM, it will use more of the hard drive to store data. This also significantly slows overall performance as HDDs and SSDs are much slower than RAM.

 Let's now see how to reset Virtual Memory on Windows.

## 1\. Use the System Properties window

 If you want to reset virtual memory settings on your Windows device, you can use the System Properties window. To do this, press **Win + R** on your keyboard to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).

 In the text box, type **sysdm.cpl**, and hit Enter. A system properties window will open up. Then, go to the **Advanced** tab and click the **Settings** button in the Performance section.

![How to Reset Virtual Memory on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-reset-virtual-memory-on-windows-11.jpg)

 This will open up the Performance Options window, where you can manage virtual memory settings. For this, switch to the **Advanced** tab and click on **Change** in the Virtual Memory section.

![Reset Page Size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-page-size.jpg)

 On the next screen, uncheck the **Automatically manage paging file size for all drives** checkbox and select the drive you want to configure virtual memory. Normally, this will be the drive on which Windows is installed.

 Set the custom size for virtual memory. Then, check the **No paging file** radio button and click **Set**. If you see a warning message, click **Yes** to confirm.

 After following the above steps, click **OK** to save your changes. Now close the System Properties and Settings windows and restart your computer. The new virtual memory settings should now be in effect.

## 2\. Use Group Policy Editor

 You can also use the Local Group Policy Editor to reset virtual memory settings on your Windows device. But remember that this method is only available on Pro and Enterprise editions.

 If you're using a Home edition, you should first [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To get started, open the Run dialog box and type **gpedit.msc** into the text box. Then click **OK** or press Enter to open the Local Group Policy Editor window.

![Clear virtual memory pagefile Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clear-virtual-memory-pagefile-using-group-policy.jpg)

 Then navigate to the following location:

Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Option

 Scroll down and double-click **Shutdown: Clear virtual memory pagefile** policy. In the Properties window, select Enabled and then click **Apply**. Next, click **OK** to save it.

## 3\. Use Registry Editor

 If you don't have access to the Local Group Policy Editor, you can also use the Registry Editor to reset virtual memory settings on Windows. Before proceeding, you should [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) in case something gets wrong.

![Reset Virtual Memory Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-virtual-memory-using-registry.jpg)

 To get started, search for **Registry Editor** in the Start menu and click on it. Once you open the Registry Editor, navigate to the following path:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management

 Next, double-click on the **ClearPageFileAtShutdown** key and set its value to **1**. Click on the **OK** button to save your changes.

## Reset Virtual Memory To Get Better Performance

 Resetting virtual memory settings improves Windows computer performance. This guide introduces three methods to learn how to reset virtual memory on Windows. Give it a try and see which methods work best for you. If you face any issues while doing this, you can always use system restore to revert to the previous settings.


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
<li><a href="https://some-approaches.techidaily.com/new-ultimate-funny-photo-tinkering-tool/"><u>[New] Ultimate Funny Photo Tinkering Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-windows-fn-key-behavior-for-efficiency/"><u>Altering Windows Fn Key Behavior for Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-minipc-size-upgrade-speed-downgrade/"><u>Blackview MiniPC: Size Upgrade, Speed Downgrade</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-entry-level-camera-reviews-2024-for-beginners/"><u>Best Entry-Level Camera Reviews 2024 | for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-default-screen-saver-in-windows-11/"><u>Adjusting Default Screen Saver in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-buffer-rates-to-minimize-lag-with-vlc/"><u>Adjusting Buffer Rates to Minimize Lag with VLC</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-your-ipad-as-a-creative-tool-for-time-lapse-for-2024/"><u>[New] Your iPad as a Creative Tool for Time Lapse for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/what-is-the-best-fps-for-youtube-videos-in-2024/"><u>What Is the Best FPS for YouTube Videos, In 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-securing-your-audio-library-the-top-5-steps-for-internet-radio-storage/"><u>In 2024, Securing Your Audio Library  The Top 5 Steps for Internet Radio Storage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alter-the-default-display-on-task-manager-windows-11/"><u>Alter the Default Display on Task Manager (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-your-windows-search-and-highlight-settings/"><u>Adjusting Your Window's Search and Highlight Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-taskbar-performance-on-win11/"><u>Boosting Taskbar Performance on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-the-basics-excellent-replacements-for-windows-11-defaults/"><u>Beyond the Basics: Excellent Replacements for Windows 11 Defaults</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-reset-iphone-8-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Reset iPhone 8? | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-instant-social-interaction-tweetplusfb-guide/"><u>[Updated] 2024 Approved  Instant Social Interaction  Tweet+FB Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-with-these-12-unneeded-windows-programs/"><u>Boost Performance with These 12 Unneeded Windows Programs</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-tecno-spark-go-2023-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Tecno Spark Go (2023) | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-teamsters-crashes-on-windows-11-10/"><u>Avoiding Teamsters Crashes on Windows 11, 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/app-aesthetics-the-hidden-culprits-in-windows-11-performance-drop/"><u>App Aesthetics: The Hidden Culprits in Windows 11 Performance Drop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-startup-efficiency-altering-boot-menu-delay/"><u>Boosting Startup Efficiency: Altering Boot Menu Delay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-cpu-temp-in-windows-11-systems/"><u>Balancing CPU Temp in Windows 11 Systems</u></a></li>
<li><a href="https://android-location-track.techidaily.com/two-ways-to-track-my-boyfriends-xiaomi-redmi-a2plus-without-him-knowing-drfone-by-drfone-virtual-android/"><u>Two Ways to Track My Boyfriends Xiaomi Redmi A2+ without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artificinas-intelligence-microsofts-innovative-ai-addition-to-windows-11-taskbar/"><u>Artificinas Intelligence: Microsoft’s Innovative AI Addition to Windows 11 Taskbar</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-unveiling-the-top-6-tiktok-to-mp3-converters-free-for-2024/"><u>[Updated] Unveiling the Top 6 TikTok-to-MP3 Converters - FREE for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/configure-your-computer-for-seamless-premiere-pro-performance/"><u>Configure Your Computer for Seamless Premiere Pro Performance</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/network-locked-sim-card-inserted-on-your-oppo-k11-5g-phone-unlock-it-now-by-drfone-android/"><u>Network Locked SIM Card Inserted On Your Oppo K11 5G Phone? Unlock It Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-the-past-erasing-defenders-track-of-security-efforts/"><u>Banish the Past: Erasing Defender’s Track of Security Efforts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-unauthorized-profiles-on-pcs-win1011-guide/"><u>Addressing Unauthorized Profiles on PCs: Win10/11 Guide</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/fcp-x-visual-effects-how-to-create-seamless-green-screen-composites/"><u>FCP X Visual Effects How to Create Seamless Green Screen Composites</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-storytelling-mastery-scriptwriting-secrets-revealed/"><u>In 2024, Storytelling Mastery  Scriptwriting Secrets Revealed</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/decisive-content-reduction-find-the-best-video-cutters/"><u>Decisive Content Reduction  Find the Best Video Cutters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augmenting-desktop-interactivity-the-widget-approach-in-win-11/"><u>Augmenting Desktop Interactivity: The Widget Approach in Win 11</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oneplus-nord-n30-5g-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass OnePlus Nord N30 5G FRP</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-free-mod-video-editor-roundup-top-picks/"><u>New Free MOD Video Editor Roundup Top Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/battle-bugs-tackling-skyrims-extension-failure/"><u>Battle Bugs: Tackling Skyrim's Extension Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitlocker-free-windows-4-effective-security-measures/"><u>BitLocker-Free Windows: 4 Effective Security Measures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-the-blues-swift-remedies-to-hypervisor-bsos-in-winxose/"><u>Beat the Blues: Swift Remedies to Hypervisor BSOS in WINXOSE</u></a></li>
<li><a href="https://some-tips.techidaily.com/unveiling-the-top-text-styling-portals-for-creatives-for-2024/"><u>Unveiling the Top Text Styling Portals for Creatives for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-captivating-your-audience-youtube-intro-excellence-with-imovie/"><u>[Updated] Captivating Your Audience  YouTube Intro Excellence with iMovie</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-file-management-in-windows-11/"><u>Boosting File Management in Windows 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-startup-strategy-guide-affordable-channels-to-monetize/"><u>2024 Approved  Startup Strategy Guide  Affordable Channels to Monetize</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-making-money-from-youtube-shorts-key-elements-and-profit-possibilities/"><u>2024 Approved  Making Money From YouTube Shorts  Key Elements & Profit Possibilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-efficiency-in-win11-with-custom-cmd-commands/"><u>Boosting Efficiency in Win11 with Custom Cmd Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-steam-authentication-setbacks-in-rust-for-windows-users/"><u>Avoiding Steam Authentication Setbacks in Rust for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-cortana-microsofts-four-future-plans/"><u>Beyond Cortana: Microsoft's Four Future Plans</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-from-script-to-screen-efficient-voice-over-recording-with-final-cut-pro-for-2024/"><u>New From Script to Screen Efficient Voice Over Recording with Final Cut Pro for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-fun-frenzy-youtube-writers-of-joyful-entertainment/"><u>[Updated] 2024 Approved  Fun Frenzy  YouTube’ Writers of Joyful Entertainment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-crashing-keep-your-file-explorer-fixed-in-windows-11/"><u>Avoid Crashing: Keep Your File Explorer Fixed in Windows 11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-vsg-screen-snapshots-review-thorough-examination-for-2024/"><u>[New] VSG Screen Snapshots Review  Thorough Examination for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unveiling-top-tier-displays-optimize-your-xbox-series-x-gaming/"><u>2024 Approved  Unveiling Top-Tier Displays - Optimize Your Xbox Series X Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-your-quake-experience-via-terminal/"><u>Beginning Your Quake Experience via Terminal</u></a></li>
</ul></div>
