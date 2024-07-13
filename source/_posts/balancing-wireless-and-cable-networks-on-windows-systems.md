---
title: Balancing Wireless & Cable Networks on Windows Systems
date: 2024-07-12T18:06:04.295Z
updated: 2024-07-13T18:06:04.295Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Balancing Wireless & Cable Networks on Windows Systems
excerpt: This Article Describes Balancing Wireless & Cable Networks on Windows Systems
keywords: Balance Wireless/Cable,Network Integration Win,Mixing Protocols,Hybrid Net Setup,Cross-Platform Connectivity,Windows Network Harmony,Seamless Wired/Wireless
thumbnail: https://thmb.techidaily.com/a26306e3d205a36c4a6b9d44bd1cf9f948f504e389465c9417b498ad1381c72e.jpg
---

## Balancing Wireless & Cable Networks on Windows Systems

 You can have your Windows computer connected to Wi-Fi and Ethernet simultaneously, but the system won't use both connections at the same. Windows automatically configures the network adapter order priority to provide the best Internet connection via Ethernet or Wi-Fi.

 However, if you have multiple ISP connections or have a local media server, you can configure your Windows laptop to use Wi-Fi and Ethernet simultaneously. To do this, you must disable packet priority for both Wi-Fi and Ethernet network adapter.

## Why You May Need to Use Both the Wi-Fi and Ethernet Connections Simultaneously

 While you may not get an additional speed advantage when using the same ISP for your Wi-Fi and Ethernet, you can have both connections up and running as a backup for critical Internet-dependent services. Also, if you have access to multiple ISP connections, you can [merge multiple connections to increase your internet speed](https://www.makeuseof.com/how-to-merge-internet-connections/) .

 Additionally, it is also useful if you have a local server and want to be connected to both the Internet and the local server simultaneously. You can connect to the local media server via Ethernet and access the internet over Wi-Fi without dropping the connection.

 On the flip side, there are chances of packet loss due to duplicate packets being transmitted via both the Wi-Fi and Ethernet connection. Lower-end routers may also notice decreased speed due to increased load on your network device. This is part of the reasons [why you may want to replace your ISP's router](http://www.makeuseof.com/tag/reasons-replace-isp-router/) .

## How to Configure Windows to Use Wi-Fi and Ethernet Connections Simultaneously

 Since Windows automatically prioritizes the network adapter to use only one adapter at a time, you'll need to disable the packet priority option in the network adapter's network configuration. Doing so will allow Windows to use multiple connections simultaneously.

To disable packet priority and VLAN on Windows:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel** .
3. Next, go to**Network and Internet** and click on**Network and Sharing Center.**  
![control panel network change adapter settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/control-panel-network-change-adapter-settings.jpg)
4. In the left pane, click on**Change adapter settings.**
5. Right-click on your**Ethernet network adapter** and select**Properties** . Alternatively, double-click on the**Ethernet adapter** and then click on**Properties** .  
![ethernet properties configure networking control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ethernet-properties-configure-networking-control-panel.jpg)

1. In the**Networking** tab, click the**Configure** button.
2. Next, open the**Advanced** tab.
3. Select**Priority and VLAN** under the**Property** section.
4. Click the drop-down under**Value** .  
![priority vlan disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/priority-vlan-disabled.jpg)
5. Select**Priority and VLAN Disabled.**
6. Click**OK** to save the changes.
7. Next, you need to repeat the steps for your Wi-Fi adapter. So, open Properties for your Wi-Fi adapter and set its**Priority and VLAN** value to**Priority & VLAN Disabled** .
8. Click**OK** to save the changes.

 With the network adapter priority option disabled, Windows will now use both network connections simultaneously.

## How to Set the Network Priority for Wi-Fi or Ethernet Using Interface Metric

 By default, Windows uses an automatic metric to detect and use the best network connectivity option available. However, if you need, you can manually set network priority to force Windows to use Ethernet or Wi-Fi as the preferred connectivity option.

To change network priority on Windows:

1. Press**Win + R** to open**Run** .
2. Type**ncpa.cpl** and click**OK** .  
![ncpa cpl open control panel network and sharing center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ncpa-cpl.jpg)
3. Right-click on your Ethernet adapter and select**Properties** . If you want to prioritize your Wi-Fi adapter, choose that instead.
4. Next, select**Internet Protocol Version 4 (TCP/IPv4)** and click on**Properties** .  
![tcp ip v4 properties control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tcp-ip-v4-properties-control-panel.jpg)
5. Click the**Advanced** button in the**Properties** dialog.
6. Next, uncheck**Automatic metric** and type**5** in the**Interface metric** field.
7. Click**OK** on all the open windows to save the changes.
8. Note that if you use Internet Protocol Version 6 (IPv6) protocol, you’ll need to assign an interface metric for it as well.

 With the changes saved, Windows will prioritize your preference when multiple network adapters are connected to your computer. To undo the changes, open**Advanced TCP/IP Settings** and check the**Automatic** **metric** option. Then, click**OK** to save the changes.

## Make Your Computer Use Your Wi-Fi and Ethernet at the Same Time

 You can configure the network adapter on your computer to use both Wi-Fi and Ethernet connection simultaneously. While it has many advantages, it won't increase your Internet speed. Instead, you’ll need multiple Internet connections powering your Wi-Fi and Ethernet networks to see increased speed.

 Alternatively, if you have multiple Wi-Fi connections at home or office, you can configure your Windows computer to automatically switch to the strongest Wi-Fi network available when you move around.


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
<li><a href="https://win11-tips.techidaily.com/boosting-browser-performance-fix-youtube-delays/"><u>Boosting Browser Performance: Fix YouTube Delays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-practices-unveiled-supercharge-wsl-2-with-windows-dev-tools/"><u>Best Practices Unveiled: Supercharge WSL 2 with Windows Dev Tools</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-the-speakers-guide-to-voiceover-on-microsoft-ppt/"><u>[Updated] The Speaker's Guide to Voiceover on Microsoft PPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-alternatives-to-windows-snipping-quick-reliable-capture-techniques/"><u>Best Alternatives to Windows Snipping: Quick, Reliable Capture Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-speed-the-best-windows-mouse-drivers/"><u>Boosting Speed: The Best Windows Mouse Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-requires-ancient-login-details/"><u>Addressing Windows Requires Ancient Login Details</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-iphone-podcast-listening-experiences/"><u>2024 Approved  Top iPhone Podcast Listening Experiences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackviews-big-hard-drive-performance-lacks-pep/"><u>Blackview's Big Hard Drive, Performance Lacks Pep</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-hand-tracking-explained-types-and-applications-for-2024/"><u>[New] Hand Tracking Explained  Types and Applications for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bar-of-time-the-windows-taskbars-journey/"><u>Bar of Time: The Windows Taskbar's Journey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bestowing-wondrous-widgets-onto-context-menu/"><u>Bestowing Wondrous Widgets Onto Context Menu</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-uncovering-budget-friendly-video-communication-apps-pcmac/"><u>[Updated] In 2024, Uncovering Budget-Friendly Video Communication Apps  PC/MAC</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/cutting-edge-marketing-anticipating-fbs-trends-of-the-new-decade-for-2024/"><u>Cutting-Edge Marketing  Anticipating FB's Trends of the New Decade for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/how-to-dominate-tiktoks-trending-topics-for-more-engagement/"><u>How to Dominate TikTok's Trending Topics for More Engagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-access-to-win11s-system-editor/"><u>Adjusting Access to Win11's System Editor</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-secrets-to-effective-vr-game-playback/"><u>[New] In 2024, Secrets to Effective VR Game Playback</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-fixing-irq-for-clear-audio/"><u>Balancing Act: Fixing IRQ for Clear Audio</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/inverted-playback-the-hidden-technique-for-a-reversed-youtube-list/"><u>Inverted Playback  The Hidden Technique for a Reversed YouTube List</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-harnessing-windows-11-for-high-impact-visually-striking-videos/"><u>2024 Approved  Harnessing Windows 11 for High-Impact, Visually Striking Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-windows-customization-adding-directories-to-context-menu/"><u>Advanced Windows Customization - Adding Directories to Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-clutter-boost-clarity-keeping-your-notifications-centered-in-windows-11/"><u>Avoid Clutter, Boost Clarity: Keeping Your Notifications Centered in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-ephemeral-backgrounds-on-win11/"><u>Avoid Ephemeral Backgrounds on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-using-powertoys-copy-pasting-features/"><u>Boost Efficiency: Using PowerToys' Copy-Pasting Features</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-essential-techniques-for-striking-podcast-cover-designs-your-step-by-step-guide/"><u>2024 Approved Essential Techniques for Striking Podcast Cover Designs Your Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-utilizing-box-for-file-selections-in-win11/"><u>Boost Efficiency: Utilizing Box for File Selections in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/are-some-websites-not-opening-in-any-browser-on-windows-7-ways-to-fix-it/"><u>Are Some Websites Not Opening in Any Browser on Windows? 7 Ways to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aid-for-absconded-hardware-recognition-in-winos/"><u>Aid for Absconded Hardware Recognition in WinOS</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-picking-between-filmora-and-democracy-creator-for-edits/"><u>[Updated] Picking Between Filmora and Democracy Creator for Edits</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-mastering-instagrams-newest-feature-reels-explained/"><u>In 2024, Mastering Instagram's Newest Feature  Reels Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-settings-for-continuous-save-support-in-nvidia-control-center/"><u>Adjusting Settings for Continuous Save Support in NVidia Control Center</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unlocking-success-the-essentials-of-crafting-great-reddit-threads/"><u>[Updated] Unlocking Success  The Essentials of Crafting Great Reddit Threads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-zooming-anomalies-fix-7-way-for-mouse-wheels/"><u>Banish Zooming Anomalies: Fix 7 Way for Mouse Wheels</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-discovering-dormant-dialogues-among-youtube-watchers/"><u>2024 Approved  Discovering Dormant Dialogues Among YouTube Watchers</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/how-to-watch-vr-video-on-iphone-ios/"><u>How to Watch VR Video on Iphone (Ios)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-hypervisorerr-blues-in-win-10-and-11/"><u>Beating HYPERVISOR_ERR Blues in Win 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-frame-rates-cutting-latency-roblox-tips-for-pcs/"><u>Boosting Frame Rates, Cutting Latency: Roblox Tips for PCs</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-a-locked-vivo-y56-5g-phone-by-drfone-android/"><u>In 2024, How to Reset a Locked Vivo Y56 5G Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-windows-media-player-activation-process/"><u>Beginning Windows Media Player Activation Process</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-top-10-free-android-video-editors-with-no-watermark/"><u>New 2024 Approved Top 10 Free Android Video Editors with No Watermark</u></a></li>
<li><a href="https://win11-tips.techidaily.com/batch-to-executable-guide-for-windows-users/"><u>Batch-to-Executable Guide for Windows Users</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-zte-axon-40-lite-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On ZTE Axon 40 Lite | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-streamline-your-workflow-40-essential-fcpx-keyboard-shortcuts/"><u>Updated 2024 Approved Streamline Your Workflow 40 Essential FCPX Keyboard Shortcuts</u></a></li>
</ul></div>
