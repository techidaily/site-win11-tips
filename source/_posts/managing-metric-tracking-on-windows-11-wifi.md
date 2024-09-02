---
title: Managing Metric Tracking on Windows 11 Wifi
date: 2024-09-01T05:14:11.244Z
updated: 2024-09-02T05:14:11.244Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Managing Metric Tracking on Windows 11 Wifi
excerpt: This Article Describes Managing Metric Tracking on Windows 11 Wifi
keywords: WiFi Usage Tracker,W11 Performance Analyzer,Network Signal Monitoring,Data Transmission Insight,Connectivity Efficiency Track,System Wifi Diagnostics,GPS Position Logging
thumbnail: https://thmb.techidaily.com/5b7228f82dd55952004c9e54eccc979f0193c694cfbf96a3723eb54169ea5205.jpg
---

## Managing Metric Tracking on Windows 11 Wifi

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to[launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the[Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.
6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
## Efficiently Manage Your Data With Metered Connection

 Enabling or disabling the metered connection option for Wi-Fi networks in Windows is relatively simple, regardless of the method you use.

 If you have a limited data plan, you can also set a data usage limit for your Wi-Fi connection. This way, Windows will notify you when you approach the set data limit.


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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-digital-broadcasting-battle-comparing-facebook-live-youtube-live-and-twitter-spaces/"><u>[New] 2024 Approved  Digital Broadcasting Battle  Comparing Facebook LIVE, YouTube Live, & Twitter Spaces</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-exclusive-guide-to-priceless-cam-screen-recorders/"><u>[New] 2024 Approved  Exclusive Guide to Priceless Cam Screen Recorders</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-thrifty-approaches-to-youtube-video-card-production/"><u>[New] 2024 Approved  Thrifty Approaches to YouTube Video Card Production</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-ultimate-list-free-best-ios-video-editor-tools/"><u>[New] 2024 Approved  Ultimate List  Free, Best iOS Video Editor Tools</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-ideal-ict-equipment-educators-top-10-lecture-capturers/"><u>[New] Ideal ICT Equipment  Educators' Top 10 Lecture Capturers</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-discovering-top-tools-the-2023-guide-to-browser-capture-tech/"><u>[New] In 2024, Discovering Top Tools  The 2023 Guide to Browser Capture Tech</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-elite-8-films-on-facebook/"><u>[New] In 2024, Elite 8 Films on Facebook</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-precision-at-a-glance-elevate-your-hp-laptop-recording-skills/"><u>[New] Precision at a Glance  Elevate Your HP Laptop Recording Skills</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-rev-up-your-earnings-a-deep-dive-into-vimeo-profits-for-2024/"><u>[New] Rev Up Your Earnings  A Deep Dive Into Vimeo Profits for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-streamlining-multi-camera-setup-with-obs/"><u>[New] Streamlining Multi-Camera Setup with OBS</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-subtle-sounds-clear-vision-audio-cleanup-methods-reviewed/"><u>[New] Subtle Sounds, Clear Vision  Audio Cleanup Methods Reviewed</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-easy-steps-how-to-master-the-best-of-9-free-youtube-logomakers/"><u>[Updated] 2024 Approved  Easy Steps  How to Master the Best of 9 Free YouTube Logomakers</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-how-to-captivate-viewers-using-multiple-perspectives-on-fb-live/"><u>[Updated] 2024 Approved  How to Captivate Viewers Using Multiple Perspectives on FB Live</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-the-complete-guide-to-crafting-youtube-masterpieces/"><u>[Updated] 2024 Approved  The Complete Guide to Crafting YouTube Masterpieces</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-audible-mac-visual-record-functionality-for-2024/"><u>[Updated] Audible Mac Visual Record Functionality for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-crafting-unique-ps3-gameplay-presentations-with-screen-recordings-for-2024/"><u>[Updated] Crafting Unique PS3 Gameplay Presentations with Screen Recordings for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-dji-flying-tech-experiment-with-color-luts-at-no-extra-charge/"><u>[Updated] DJI Flying Tech  Experiment with Color LUTs at No Extra Charge</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-understanding-zooms-participant-clusters/"><u>[Updated] In 2024, Understanding Zoom's Participant Clusters</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-the-key-steps-effective-obs-streaming-directly-to-facebook-users/"><u>[Updated] The Key Steps  Effective OBS Streaming Directly to Facebook Users</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-navigating-noise-free-auditory-shifts/"><u>2024 Approved  Navigating Noise-Free Auditory Shifts</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-budding-filmmakers-companion-understanding-display-quality-101/"><u>2024 Approved  The Budding Filmmaker’s Companion  Understanding Display Quality 101</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/a-concierge-guide-for-monitoring-facebook-livestreams/"><u>A Concierge Guide for Monitoring Facebook Livestreams</u></a></li>
<li><a href="https://audio-editing.techidaily.com/best-online-mp3-cutter-and-joiner/"><u>Best Online MP3 Cutter And Joiner</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-breakdown-understanding-windows-odbc-system/"><u>Comprehensive Breakdown: Understanding Windows' ODBC System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-main-panel-of-windows-11-task-manager/"><u>Customizing Main Panel of Windows 11 Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-download-methods-for-newcomers-to-windows/"><u>Direct Download Methods for Newcomers to Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-4-paths-to-protect-windows-post-bitlocker/"><u>Discover 4 Paths to Protect Windows Post-BitLocker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ease-of-access-disabling-security-interrogation-for-windows-11-admin/"><u>Ease of Access: Disabling Security Interrogation for Windows 11 Admin</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-newest-graphics-card-software-quick-guide-to-downloading-and-updating-your-amd-rx-480/"><u>Get the Newest Graphics Card Software: Quick Guide to Downloading & Updating Your AMD RX ([4]80)</u></a></li>
<li><a href="https://facebook.techidaily.com/how-to-evaluate-the-real-life-impact-before-deleting-accounts/"><u>How to Evaluate the Real-Life Impact Before Deleting Accounts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-quash-disconnecting-drama-in-discord-on-windows-11-pcs/"><u>How to Quash Disconnecting Drama in Discord on Windows 11 PCs</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-videos-from-your-htc-u23-by-fonelab-android-recover-video/"><u>How to recover old videos from your HTC U23</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-xs-to-other-iphone-13-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone XS To Other iPhone 13 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-maximizing-spotifys-playback-rate-without-sacrificing-sound/"><u>In 2024, Maximizing Spotify's Playback Rate Without Sacrificing Sound</u></a></li>
<li><a href="https://extra-information.techidaily.com/iphones-role-in-creating-immersive-vr-content/"><u>IPhone's Role in Creating Immersive VR Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-creativity-opening-ms-paint-on-win11/"><u>Jumpstart Creativity: Opening MS Paint on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterclass-creating-multiple-subfolders-with-ease-in-windows/"><u>Masterclass: Creating Multiple Subfolders with Ease in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-window-11s-help-service-disruption/"><u>Mending Window 11'S Help Service Disruption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11s-elevation-conflict-overcoming-error-740/"><u>Navigating Windows 11'S Elevation Conflict: Overcoming Error #740</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-visuals-on-win1011-by-driver-rebooting/"><u>Optimizing Visuals on Win10/11 by Driver Rebooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-error-windows-cant-stop-volume-device/"><u>Overcoming Error: Windows Can’t Stop Volume Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-printmanagement-not-found-issue-quickly/"><u>Overcoming Windows Printmanagement Not Found Issue Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prevent-snipping-tool-start-with-print-key-in-windows-11-os/"><u>Prevent Snipping Tool Start with Print Key in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-vanished-recorded-run-events/"><u>Preventing Vanished Recorded Run Events</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propel-your-productivity-key-strategies-with-windows-11/"><u>Propel Your Productivity: Key Strategies with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/protecting-game-progress-with-epic-saves/"><u>Protecting Game Progress with Epic Saves</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/quash-unwanted-youtube-suggested-videos-for-2024/"><u>Quash Unwanted YouTube Suggested Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-reactivate-your-preferred-microsoft-store-apps/"><u>Quick Fix: Reactivate Your Preferred Microsoft Store Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-folder-interruption-noise-in-win11/"><u>Reducing Folder Interruption Noise in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-windows-paperwork-handler/"><u>Refreshing Windows Paperwork Handler</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-off-screen-windows-6-steps-for-win11/"><u>Resurrecting Off-Screen Windows: 6 Steps for Win11</u></a></li>
<li><a href="https://buynow-help.techidaily.com/shedding-light-on-nighttime-reading-with-the-barnes-and-noble-nook-glowlight-3-a-detailed-expert-review/"><u>Shedding Light on Nighttime Reading with the Barnes & Noble Nook GlowLight 3 - A Detailed Expert Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-windows-files-with-top-tricks-max-156/"><u>Simplify Windows Files with Top Tricks (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-driver-not-supported-errors-in-windows-11/"><u>Solving Driver Not Supported Errors in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-prevalent-anydesk-glitches-in-windows-os/"><u>Solving Prevalent AnyDesk Glitches in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stabilizing-the-sweep-of-your-cursor-deactivating-mouse-accel-in-win-11/"><u>Stabilizing the Sweep of Your Cursor: Deactivating Mouse Accel in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-resolve-failing-windows-discord-updates/"><u>Step by Step to Resolve Failing Windows Discord Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-critical-javascript-failure-in-discord-on-windows/"><u>Steps to Address Critical JavaScript Failure in Discord on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-correct-token-misreference-errors-on-win10win11/"><u>Strategies to Correct Token Misreference Errors on Win10/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-powershell-workflow-with-script-policy-controls/"><u>Streamline Your PowerShell Workflow with Script Policy Controls</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-blueprint-for-successful-individual-podcasts/"><u>The Blueprint for Successful Individual Podcasts</u></a></li>
<li><a href="https://fox-direct.techidaily.com/the-essential-meme-template-toolkit-for-2024/"><u>The Essential Meme Template Toolkit for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-value-proposition-of-windows-11s-interactive-elements/"><u>The Value Proposition of Windows 11'S Interactive Elements</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/transform-youtube-soundtracks-on-iphone-with-these-6-choices-for-2024/"><u>Transform YouTube Soundtracks on iPhone with These 6 Choices for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-to-enhanced-widget-display-interface-in-windows-11/"><u>Transitioning to Enhanced Widget Display Interface in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triple-threat-tweaks-for-personalized-win11-preferences/"><u>Triple-Threat Tweaks for Personalized Win11 Preferences</u></a></li>
<li><a href="https://activate-lock.techidaily.com/unlock-your-device-icloud-dns-bypass-explained-and-tested-plus-easy-alternatives-from-iphone-6s-by-drfone-ios/"><u>Unlock Your Device iCloud DNS Bypass Explained and Tested, Plus Easy Alternatives From iPhone 6s</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-office-solving-windows-activation-issues/"><u>Unlocking Office: Solving Windows Activation Issues</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-the-power-of-chatgpt-a-comprehensive-guide-by-openai/"><u>Unlocking the Power of ChatGPT: A Comprehensive Guide by OpenAI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-taskbars-hidden-features/"><u>Unveiling Windows Taskbar's Hidden Features</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/what-to-do-when-microsoft-word-files-wont-open/"><u>What to Do When Microsoft Word Files Won't Open</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-hack-abruptly-delete-non-responsive-printers/"><u>Windows 10/11 Hack: Abruptly Delete Non-Responsive Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-sound-system-enhancement-through-drivers-update-tutorial/"><u>Windows Sound System Enhancement Through Drivers Update Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/xbox-not-launching-regain-control-with-these-tricks/"><u>Xbox Not Launching? Regain Control with These Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-pathway-to-elevated-settings-windows-11s-higher-power/"><u>Your Pathway to Elevated Settings: Windows 11'S Higher Power</u></a></li>
</ul></div>
