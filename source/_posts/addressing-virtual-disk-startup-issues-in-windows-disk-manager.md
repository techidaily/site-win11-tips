---
title: Addressing Virtual Disk Startup Issues in Windows Disk Manager
date: 2024-08-08T10:53:41.355Z
updated: 2024-08-09T10:53:41.355Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Virtual Disk Startup Issues in Windows Disk Manager
excerpt: This Article Describes Addressing Virtual Disk Startup Issues in Windows Disk Manager
keywords: Fixing Disk Start-Up,VM Boot Failures,Windows Disk Repair,Manage Disk Operations,Resolve Disk Errors,Windows Storage Diagnostics,Boot Drive Troubleshooting
thumbnail: https://thmb.techidaily.com/2dd4d8c9b9a89a48c334c5f220a58a13ed27cebc631991e7d2875a1b4897165f.jpg
---

## Addressing Virtual Disk Startup Issues in Windows Disk Manager

 Disk Management is a Windows utility with which users can partition and rename drives. However, some users have reported this Windows error message pops up when they try to access Disk Management: “Disk Management could not start Virtual Disk Service (VDS).” A variation of that error message also says, “Unable to connect to Virtual Disk Service.”

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

## 1\. Disconnect External Drives From Your PC

 First, try disconnecting all non-essential USB devices from your PC. Make sure there aren’t any external drives, USB sticks, mobile phones, or card readers connected to your PC. Then try [opening the Disk Management utility](https://www.makeuseof.com/ways-open-disk-management-windows-10/) again.

## 2\. Run System File and Image Repair Scans

 System file corruption could feasibly cause the Disk Management Virtual Disk Service error. So, check the integrity of system files on your PC with the Windows System File Checker command-line tool. That utility will also usually repair corrupted system files detected. This [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide includes instructions for utilizing that tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command.jpg)

 If SFC detects corrupted system files but can’t repair them, you may need to run a Deployment Image Service Management scan. That’s a tool for fixing issues with the Windows system image. You can run that utility by executing this Deployment Image command within the Command Prompt:

`DISM /Online /Cleanup-Image /RestoreHealth`

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Enable and Run the Virtual Disk Service

 A disabled Virtual Disk service is a common cause of the Disk Management VDS error. Disk Management can’t connect to VDS when the Virtual Disk service is disabled. So, try enabling and running the Virtual Disk service like this:

1. To access Run, press **Win + R**.
2. Enter **services.msc** inside the Run command dialog and press **Return**.
3. Scroll down and double-click on **Virtual Disk** within the Services window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/services-window.jpg)
4. Select the **Automatic** setting on the **Startup type** menu.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-type-drop-down-menu.jpg)
5. Press **Start** within the Virtual Disk Properties window.

1. Select the window’s **Log on** tab.
2. Next, click the **Allow service to interact with desktop** checkbox to select that option.  
![The Log On tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/log-on-tab.jpg)
3. Click **Apply** to save your new Virtual Disk service settings.
4. Select the Virtual Disk Properties window’s **OK** option.
5. If you encounter the Disk Management VDS error within a remote connection environment, repeat the above steps to check the Virtual Disk service is enabled on both the local and remote PCs.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Allow Remote Volume Management Through Windows Defender Firewall

 Windows Defender Firewall can cause the Disk Management VDS error by blocking that utility from connecting with Virtual Disk. So, make sure Remote Volume Management is allowed through that firewall on both local and remote PCs. Our [guide to allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) includes instructions for applying this resolution.

![The allowed apps firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/firewall-options.jpg)

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## 5\. Turn Off Third-Party Security Software

 If your PC includes a third-party security (antivirus) app, that software could be blocking Disk Management from establishing a VDS connection. Remember that many third-party security apps also incorporate firewalls along with antivirus components. So, try temporarily disabling both the firewall and antivirus module within your third-party security software.

 To disable the firewall part, look for a turn-off firewall option within the settings tab of your antivirus software. You can usually turn off antivirus shields by right-clicking on security apps’ system tray icons and selecting disable options on their context menus. Select to turn off the antivirus shield for about an hour if you can, and try accessing Disk Management again to see if the issue persists.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Manage Your Drives With Disk Management Again

 The potential solutions in this guide aren’t totally guaranteed, but they’re the most likely ways to fix the Disk Management VDS error on a Windows PC. So, maybe one will get the Disk Management VDS issue sorted on your PC. Then you can manage and partition your drives with Disk Management again.

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-hints.techidaily.com/new-achieve-color-mastery-with-canons-freepaid-lut-variety/"><u>[New] Achieve Color Mastery with Canon's Free/Paid LUT Variety</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-expert-iphone-software-roundup-selecting-ideal-watermark-tools/"><u>[New] Expert iPhone Software Roundup  Selecting Ideal Watermark Tools</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-instagram-edge-advanced-photo-editing-strategies/"><u>[New] In 2024, Instagram Edge  Advanced Photo Editing Strategies</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-realities-redefined-the-metaverse-vs-omniverse-showdown-explained/"><u>[New] In 2024, Realities Redefined  The Metaverse Vs. Omniverse Showdown Explained</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-transitioning-instagram-video-to-mp3-format/"><u>[New] In 2024, Transitioning Instagram Video to Mp3 Format</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-ios-leading-ps2-simulators-top-picks/"><u>[New] IOS Leading PS2 Simulators  Top Picks</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-music-for-instagram-videos-here-is-all-you-need-to-know/"><u>[New] Music for Instagram Videos - Here Is All You Need to Know</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-reel-your-best-footage-from-instagram-with-these-aids/"><u>[New] Reel Your Best Footage From Instagram With These Aids</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-top-5-best-lightweight-action-cameras-for-backpacking-or-hiking-for-2024/"><u>[New] Top 5 Best Lightweight Action Cameras For Backpacking Or Hiking for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-battle-for-asgard-the-ragnarok-chronicles/"><u>[Updated] 2024 Approved  Battle for Asgard  The Ragnarök Chronicles</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-everyones-guide-to-youtube-success-10-straightforward-video-tips/"><u>[Updated] Everyone's Guide to YouTube Success  10 Straightforward Video Tips</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-from-good-quality-to-great-optimal-hd-fb-streaming-for-2024/"><u>[Updated] From Good Quality to Great  Optimal HD FB Streaming for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-peering-at-starred-online-chatter/"><u>[Updated] Peering at Starred Online Chatter</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-perfecting-your-tone-techniques-for-zoom-podcast-sessions-for-2024/"><u>[Updated] Perfecting Your Tone  Techniques for ZOOM Podcast Sessions for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-best-practices-apps-and-sites-mastering-photo-framing/"><u>2024 Approved  Best Practices Apps & Sites - Mastering Photo Framing</u></a></li>
<li><a href="https://extra-hints.techidaily.com/apex-craftsman-studio-evaluation/"><u>Apex Craftsman Studio Evaluation</u></a></li>
<li><a href="https://facebook.techidaily.com/app-economics-how-twitter-tracks-users-for-zero-cost-access/"><u>App Economics: How Twitter Tracks Users for Zero Cost Access</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/best-movie-makers-for-windows-10-for-2024/"><u>Best Movie Makers for Windows 10 for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/best-pokemons-for-pvp-matches-in-pokemon-go-for-realme-c67-4g-drfone-by-drfone-virtual-android/"><u>Best Pokemons for PVP Matches in Pokemon Go For Realme C67 4G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-volume-on-bluetooth-headphonesspeakers-a-win11-guide/"><u>Boosting Volume on Bluetooth Headphones/Speakers: A Win11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boot-camp-backing-up-your-hard-drive-solo/"><u>Boot Camp: Backing up Your Hard Drive Solo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/break-away-from-grouped-icons-in-win-11/"><u>Break Away From Grouped Icons in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-barriers-in-operating-systems-post-windows-11/"><u>Breaking Barriers in Operating Systems: Post-Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-the-fix-for-xbox-game-pass-error-0-on-windows-11-pcs/"><u>Breaking Down the Fix for Xbox Game Pass Error 0 on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-windows-1011s-s-mode-bond-quickly/"><u>Breaking Windows 10/11’S S Mode Bond Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breatenticating-healthy-windows-and-dotnet-status-max-156/"><u>Breatenticating Healthy Windows & DotNet Status (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathing-life-into-inactive-apps-in-windows-11/"><u>Breathing Life Into Inactive Apps in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-devices-a-practical-guide-to-android-and-pc-synchro/"><u>Bridging Devices: A Practical Guide to Android & PC Synchro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-dual-windows-mastering-data-consistency-using-aoemi/"><u>Bridging Dual Windows: Mastering Data Consistency Using AOEMi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-gaps-of-lost-connectivity-in-windows/"><u>Bridging Gaps of Lost Connectivity in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-the-gap-for-faulty-windows-batch-file-operations/"><u>Bridging the Gap for Faulty Windows Batch File Operations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-whats-lost-recovering-windows-11s-disappearing-bluetooth/"><u>Bring Back What's Lost: Recovering Windows 11’S Disappearing Bluetooth</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-command-prompt-to-windows-11s-task-manager/"><u>Bring Command Prompt to Windows 11'S Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-your-games-home-integrating-android-into-windows-11s-ecosystem/"><u>Bring Your Games Home: Integrating Android Into Windows 11'S Ecosystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brisk-startups-in-win11-adjusting-boot-delay-period/"><u>Brisk Startups in Win11: Adjusting Boot Delay Period</u></a></li>
<li><a href="https://win11-tips.techidaily.com/building-a-flask-based-python-server-for-networked-file-transfers/"><u>Building a Flask-Based Python Server for Networked File Transfers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-genuineness-warning-in-adobe-software/"><u>Bypass Genuineness Warning in Adobe Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-incompatible-system-mark-on-windows-11/"><u>Bypass Incompatible System Mark on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-the-frozen-pause-of-windows-update-fails/"><u>Bypass the Frozen Pause of Windows Update Fails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-browser-requirement-a-new-user-guide/"><u>Bypassing Browser Requirement: A New User Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-content-unavailable-on-steam-client/"><u>Bypassing Content Unavailable on Steam Client</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-disabled-accounts-fixing-windows-login-fails/"><u>Bypassing Disabled Accounts: Fixing Windows Login Fails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-freeze-windows-update-savior-guide/"><u>Bypassing Freeze: Windows Update Savior Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-http-overload-in-win-based-software-0x80860010/"><u>Bypassing HTTP Overload in Win-Based Software (0X80860010)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-incompatibility-with-latest-windows-version/"><u>Bypassing Incompatibility with Latest Windows Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-misleading-anti-virus-alerts-in-chrome-browser-for-pc-users/"><u>Bypassing Misleading Anti-Virus Alerts in Chrome Browser for PC Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-permission-denied-window-message/"><u>Bypassing Permission Denied Window Message</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-cant-add-your-folder-now-hiccup-in-windows-onedrive/"><u>Bypassing the 'Can't Add Your Folder Now' Hiccup in Windows OneDrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-update-failure-error-code-0x800f0845/"><u>Bypassing Update Failure - Error Code: 0X800F0845</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-read-only-settings-for-file-access/"><u>Bypassing Windows Read-Only Settings for File Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-use-the-program-compatibility-troubleshooter-on-windows-try-these-fixes/"><u>Can't Use the Program Compatibility Troubleshooter on Windows? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ceasing-cortana-on-windows-11/"><u>Ceasing Cortana on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/celestial-mastery-revealed-unlocking-god-mode-in-windows-11/"><u>Celestial Mastery Revealed: Unlocking God Mode in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/change-display-axis-in-windows-interface/"><u>Change Display Axis in Windows Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/changing-windows-11-summary-sizes-efficiently/"><u>Changing Windows 11 Summary Sizes Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/charting-new-territories-top-7-updates-from-windows-11s-filesystem/"><u>Charting New Territories: Top 7 Updates From Windows 11'S Filesystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-preferred-pdf-application-on-windows/"><u>Choosing Preferred PDF Application on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/christmas-magic-for-your-windows-11-setup/"><u>Christmas Magic for Your Windows 11 Setup</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/culinary-comrades-youtubes-best-food-blogs/"><u>Culinary Comrades  YouTube's Best Food Blogs</u></a></li>
<li><a href="https://tech-revival.techidaily.com/daily-assistant-showdown-claude-or-chatgpt-the-premier-choice-for-your-routine-needs/"><u>Daily Assistant Showdown: Claude or ChatGPT - The Premier Choice for Your Routine Needs</u></a></li>
<li><a href="https://fox-access.techidaily.com/enhancing-visual-storytelling-with-picture-in-picture-techniques-on-mac/"><u>Enhancing Visual Storytelling with Picture In Picture Techniques on Mac</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-change-credit-card-on-your-iphone-6-plus-apple-id-and-apple-pay-by-drfone-ios/"><u>In 2024, How to Change Credit Card on Your iPhone 6 Plus Apple ID and Apple Pay</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-influencer-insights-the-top-5-instagram-moves-for-viral-content/"><u>In 2024, Influencer Insights  The Top 5 Instagram Moves for Viral Content</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-intro-to-photo-editing-mastering-lunapic-basics/"><u>In 2024, Intro to Photo Editing  Mastering LunaPic Basics</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-perfecting-zoom-sound-a-dual-strategy-approach/"><u>In 2024, Perfecting Zoom Sound  A Dual Strategy Approach</u></a></li>
<li><a href="https://win-able.techidaily.com/mastering-smooth-play-say-goodbye-to-warframe-glitches-and-hiccups/"><u>Mastering Smooth Play: Say Goodbye to Warframe Glitches and Hiccups</u></a></li>
<li><a href="https://fix-guide.techidaily.com/proven-ways-to-fix-there-was-a-problem-parsing-the-package-on-realme-c55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Proven Ways to Fix There Was A Problem Parsing the Package on Realme C55 | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/rx-fanfare-update-pack/"><u>RX Fanfare Update Pack</u></a></li>
</ul></div>
