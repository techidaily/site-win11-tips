---
title: Corrective Measures for Disabled Lock Screen Timer
date: 2024-08-16T02:04:55.370Z
updated: 2024-08-17T02:04:55.370Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Corrective Measures for Disabled Lock Screen Timer
excerpt: This Article Describes Corrective Measures for Disabled Lock Screen Timer
keywords: Disabled Lock Timeout Fixes,Accessibility Lock Timer Solution,Timed Locks for Handicapped Users,Enhance Lock Screen Timer Functionality,Overcoming Lock Issue Accessibility,Remedy Delayed Lock Feature,Adjusting Lock Timer for Disabled Access
thumbnail: https://thmb.techidaily.com/b3641ebe2988ec7265ef07a79816e61c990d023d2c0afe9a3bce0644ce087752.jpg
---

## Corrective Measures for Disabled Lock Screen Timer

 Have you ever left your computer unattended for a while, only to return and find that it was still unlocked? Several users have reported problems getting their Windows computers to lock automatically after a certain period of inactivity.

 To help out, we have listed some useful tips that should get the lock screen timeout to work on your Windows 10 or 11 PC.

## 1\. Check Screen Timeout Settings

 Before we get to any advanced troubleshooting tips, it’s a good idea to double-check the screen timeout settings on Windows. Here are the steps for the same.

1. Press **Win + I** to open the Settings app.
2. Navigate to **System > Power & battery**.
3. Click on **Screen and sleep** to expand it.
4. Click the drop-down menus next to **On battery power, turn off my screen after** and **When plugged in, turn off my screen after** to select your preferred timeout.  
![Screen and Sleep Settings in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/screen-and-sleep-settings-in-windows.jpg)

 After setting your preferred timeout, observe if Windows locks your PC after the specified period.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Configure Screen Saver Settings

 Incorrectly configured screen saver settings on Windows can also be the cause of this issue. Here's how you can configure Windows to display the lock screen after you resume from a screensaver.

1. Press **Win + S** to open the search menu.
2. Type **change screen saver** in the box and select the first result that appears.
3. In the Screen Saver Settings window, set the preferred wait time.
4. Tick the **On resume, display logon screen** checkbox.
5. Hit **Apply** followed by **OK**.  
![Screen Saver Settings on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/screen-saver-settings-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->

 Once you complete the above steps, Windows should lock your system once the screen saver activates.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Check Screen Saver Settings in the Local Group Policy

 If the issue remains even after you configure the screen saver settings, you will need to check the policies related to the screen saver and make sure they are configured correctly.

 As you may be aware, the Local Group Policy Editor is only available on Windows Pro, Enterprise, and Education editions. However, if you are using the Home edition, you can use a workaround to [access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To modify group policies related to screen saver, use these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **gpedit.msc** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
5. Double-click the **Enable Screen Saver** policy on your right.
6. Select the **Enabled** option.
7. Hit **Apply** and then click **OK**.
8. Similarly, enable the **Password protect the screen saver** policy as well.  
![Password Protect Screen Saver Policy in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/password-protect-screen-saver-policy-in-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC after applying the above changes and check if the issue is still there.

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
## 4\. Other Generic Fixes to Try

 If the above solutions do not work, you can try some generic Windows fixes to get the lock screen timeout working on Windows.

* **Disconnect External Devices:** It is possible that an external device connected to your system is keeping Windows awake. To test this, disconnect all external devices and see if the problem persists.
* **Reset Your Power Plan:** Issues with the power plan settings could also cause such problems. To fix this, you can try [resetting the power plan to default on Windows](https://www.makeuseof.com/reset-power-plans-to-default-in-windows/).
* **Install Windows Updates:** It's possible that the lock screen timeout problem is occurring due to a bug within the Windows build your PC is running. If that's the case, [installing Windows updates](https://www.makeuseof.com/update-windows-manually/) should help.
* **Try a Clean Boot:**[Performing a clean boot on Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/) can help you determine whether a third-party program or service is causing issues with the lock screen timeout. Once you find the problematic program, consider removing it from your system to avoid such issues in the future.
* **Perform a System Restore:** If the issue has only started occurring recently, you can [perform a system restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) to undo recent changes and fix the problem.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
## Get the Lock Screen Timeout Working Again on Windows

 When the lock screen timeout fails to work as expected, it can potentially put your Windows computer at risk. Hopefully, one or more of the above tips have helped you solve the problem and you are at peace.

 To help out, we have listed some useful tips that should get the lock screen timeout to work on your Windows 10 or 11 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-2023s-elite-fb-content-collectors-ranked-8/"><u>[New] 2024 Approved  2023'S Elite FB Content Collectors Ranked 8</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-create-compelling-images-on-iphone-with-these-10-principles/"><u>[New] 2024 Approved  Create Compelling Images on iPhone with These 10 Principles</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-highspeed-slowscene-videograph/"><u>[New] 2024 Approved  HighSpeed SlowScene Videograph</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-snorkel-ready-tech-the-finest-waterproof-camcorders-of-the-year/"><u>[New] 2024 Approved  Snorkel-Ready Tech  The Finest Waterproof Camcorders of the Year</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-examining-the-breadth-of-features-in-obs-studio/"><u>[New] In 2024, Examining the Breadth of Features in OBS Studio</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-innovative-14-examples-of-moving-text-art/"><u>[New] In 2024, Innovative 14 Examples of Moving Text Art</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-simplified-approach-to-download-youtube-captions-3-proven-methods/"><u>[New] In 2024, Simplified Approach to Download YouTube Captions  3 Proven Methods</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-unveiling-synergy-youtube-content-on-facebook-network/"><u>[New] In 2024, Unveiling Synergy  YouTube Content on Facebook Network</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-leading-picture-holding-portals/"><u>[New] Leading Picture Holding Portals</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-cultivating-productive-collaboration-a-pathway-to-effective-collab-videos/"><u>[Updated] 2024 Approved  Cultivating Productive Collaboration  A Pathway to Effective Collab Videos</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-cutting-edge-techniques-for-captivate-content/"><u>[Updated] 2024 Approved  Cutting-Edge Techniques for Captivate Content</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-mastering-aspect-ratio-rules-for-twitter-content/"><u>[Updated] 2024 Approved  Mastering Aspect Ratio Rules for Twitter Content</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-maximizing-velocity-in-real-time-periscope-livestreams/"><u>[Updated] Maximizing Velocity in Real-Time Periscope Livestreams</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-premier-portals-to-retro-playstation-gaming-on-your-desktop/"><u>[Updated] Premier Portals to Retro PlayStation Gaming on Your Desktop</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-the-editors-edge-advanced-tactics-for-youtube-video-spins-guide/"><u>[Updated] The Editor's Edge  Advanced Tactics for YouTube Video Spins (Guide)</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-xbox-chronicles-unveiled-mastering-4-techniques-to-record-playthroughs-for-2024/"><u>[Updated] Xbox Chronicles Unveiled  Mastering 4 Techniques to Record Playthroughs for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-harmonious-updates-musical-whatsapp-statues/"><u>2024 Approved  Harmonious Updates  Musical WhatsApp Statues</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-rapid-windows-review-a-step-by-step-approach/"><u>2024 Approved  Rapid Windows Review  A Step-by-Step Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-warning-indicators-that-call-for-a-full-reboot/"><u>5 Warning Indicators That Call For a Full Reboot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-chrome-clock-error-ahead-or-behind-windows-edition/"><u>Adjusting Chrome Clock Error: Ahead or Behind? (Windows Edition)</u></a></li>
<li><a href="https://facebook.techidaily.com/behind-the-walls-facebooks-policies-now-visible-via-new-hq/"><u>Behind the Walls: Facebook's Policies Now Visible via New HQ</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/best-pokemons-for-pvp-matches-in-pokemon-go-for-apple-iphone-7-plus-drfone-by-drfone-virtual-ios/"><u>Best Pokemons for PVP Matches in Pokemon Go For Apple iPhone 7 Plus | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-prose-with-these-5-pc-apps/"><u>Boost Your Prose with These 5 PC Apps</u></a></li>
<li><a href="https://win11.techidaily.com/ceasing-auto-opens-on-microsofts-marketplace-app/"><u>Ceasing Auto-Opens on Microsoft's Marketplace App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-office-365-issue-code-30015-26/"><u>Correcting Office 365 Issue: Code 30015-26</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disable-default-settings-keep-your-usb-running-on-windows-11/"><u>Disable Default Settings - Keep Your USB Running on Windows 11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/easy-steps-to-archive-vimeo-video-recordings-for-2024/"><u>Easy Steps to Archive Vimeo Video Recordings for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-system-monitoring-ram-gpu-and-cpu-status-guide/"><u>Efficient System Monitoring: RAM, GPU, and CPU Status Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-note-taking-with-obsidians-artistic-touch/"><u>Elevate Note-Taking with Obsidian's Artistic Touch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-communication-translate-foreign-words-with-hotkeys/"><u>Enhance Communication: Translate Foreign Words with Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-webp-visualization-with-these-excellent-tools/"><u>Enhance WebP Visualization with These Excellent Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-digital-desktop-with-engaging-time-themed-screensavers-using-these-5-tools/"><u>Enhance Your Digital Desktop with Engaging Time-Themed Screensavers Using These 5 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-the-finest-windows-11-drawers-here/"><u>Explore the Finest Windows 11 Drawers Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-csgo-start-problems-on-w11/"><u>Fixing CS:GO Start Problems on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-failed-message-display-on-discord-desktop/"><u>Fixing Failed Message Display on Discord Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-add-a-move-and-copy-to-folder-context-menu-options-in-windows-11-and-11/"><u>How to Add a Move and Copy to Folder Context Menu Options in Windows 11 & 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-delete-icloud-account-from-iphone-se-2020-without-password-by-drfone-ios/"><u>How to Delete iCloud Account From iPhone SE (2020) without Password?</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-fix-bad-pool-header-bsod-error-on-windows-10/"><u>How to Fix Bad Pool Header BSOD Error on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-bluetooth-pin-verification-hitch-on-win11w10-pcs/"><u>How To Fix Bluetooth PIN Verification Hitch on Win11/W10 PCs</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-motorola-moto-g34-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Motorola Moto G34 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-unopened-sharing-error-on-w10w11/"><u>How to Rectify Unopened Sharing Error on W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/impact-analysis-removal-of-windows-11-taskbars-chatting-function/"><u>Impact Analysis: Removal of Windows 11 Taskbar's Chatting Function</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-motorola-razr-40-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Motorola Razr 40 Location on Skout | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-no-cost-screen-recording-tricks-for-pc-users/"><u>In 2024, No-Cost Screen Recording Tricks for PC Users</u></a></li>
<li><a href="https://fox-access.techidaily.com/integrated-sound-and-vision-workspace/"><u>Integrated Sound & Vision Workspace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-machine-how-to-optimize-windows-11-settings/"><u>Master Your Machine: How to Optimize Windows 11 Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-to-uninstall-quickly-in-windows-11/"><u>Navigating to Uninstall Quickly in Windows 11</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-the-top-10-ai-avatar-generators-for-2024/"><u>New The Top 10 AI Avatar Generators for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-non-signed-file-barrier-for-system-upgrades/"><u>Overcoming Non-Signed File Barrier for System Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-window-11-mails-default-html-settings-for-clarity/"><u>Overhauling Window 11 Mail's Default HTML Settings for Clarity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-languages-change-navigating-hotkeys-in-windows-11-and-11-pro/"><u>Quick Languages Change: Navigating Hotkeys in Windows 11 & 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedies-for-not-enough-memory-available-problem-windows-vmware/"><u>Remedies for 'Not Enough Memory Available' Problem (Windows VmWare)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-overlapping-app-images-in-os-interface/"><u>Removing Overlapping App Images in OS Interface</u></a></li>
<li><a href="https://win-forum.techidaily.com/revo-uninstallers-top-tips-for-a-speedy-windows-11-startup-experience/"><u>Revo Uninstaller's Top Tips for a Speedy Windows 11 Startup Experience</u></a></li>
<li><a href="https://win-able.techidaily.com/smooth-gameplay-ahead-prevent-world-of-warships-pc-freezes-and-glitches-using-our-top-easy-strategies/"><u>Smooth Gameplay Ahead! Prevent World of Warships PC Freezes and Glitches Using Our Top Easy Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-correctly-installing-an-ms-store-app/"><u>Steps for Correctly Installing an MS Store App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/syncing-up-with-microsoft-sql-on-malwarebytes-after-disconnect/"><u>Syncing Up with Microsoft SQL on Malwarebytes After Disconnect</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-mystery-of-win11s-disconnected-5g-wi-fi/"><u>Tackling the Mystery of Win11's Disconnected 5G Wi-Fi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-your-pcs-display-lock-settings/"><u>Tailor Your PC's Display Lock Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-clear-microsofts-watchdog-logs-on-windows/"><u>Techniques to Clear Microsoft's Watchdog Logs on Windows</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/the-ace-screen-recorders-list-for-the-winning-setup-for-2024/"><u>The Ace Screen Recorders List - For the Winning Setup for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-synchronized-note-taking-in-windows-11/"><u>The Art of Synchronized Note-Taking in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-rise-of-autonomous-computing-with-windows/"><u>The Rise of Autonomous Computing with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformative-windows-tips-top-20-cmd-commands/"><u>Transformative Windows Tips: Top 20 CMD Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-potential-of-policy-editor-in-windows-11/"><u>Unlock the Full Potential of Policy Editor in Windows 11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-honor-90-lite-drfone-by-drfone-virtual-android/"><u>What is the best Pokemon for pokemon pvp ranking On Honor 90 Lite? | Dr.fone</u></a></li>
</ul></div>
