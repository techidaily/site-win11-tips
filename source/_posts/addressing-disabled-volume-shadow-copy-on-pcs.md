---
title: Addressing Disabled Volume Shadow Copy on PCs
date: 2024-08-16T01:15:02.316Z
updated: 2024-08-17T01:15:02.316Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Disabled Volume Shadow Copy on PCs
excerpt: This Article Describes Addressing Disabled Volume Shadow Copy on PCs
keywords: Accessible VSS (Volume),Enable VSS for Disabled,Restore Previous System State,VSS Compliance Check,PC Shadow Copy Issue,Configure VSS Services,Re-Enable Shadow Copies
thumbnail: https://thmb.techidaily.com/7dae447899f95c82a6cf6fb6c187f3946b55a92e5def14d160bc07a7e668b288.jpg
---

## Addressing Disabled Volume Shadow Copy on PCs

 If the Volume Shadow Copy service isn't working, you'll see error messages when you try to use Backup and Restore or System Restore in Windows. We'll show you how you can fix Volume Shadow Copy when it's not working on a Windows PC, so you can get your backups going once more.

## 1\. Enable and Start Volume Shadow Copy Services

 VSS errors can often arise because the Volume Shadow Copy and Microsoft Software Shadow Copy Provider services aren’t enabled or running. For example, many users have confirmed enabling those services can fix VSS error codes 0x81000202 and 0x81000203, which affect the System Restore tool. So, you may be able to resolve numerous Volume Shadow Copy errors by enabling VSS services like this:

1. First, press the **Windows** logo key + **S** and enter a Services search phrase to find that app.
2. Click **Services** inside the search results.
3. Double-click the **Volume Shadow Copy Service**.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/services-window.jpg)
4. Click the drop-down menu labeled **Startup type** and select **Automatic** if the service is set differently.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-type-drop-down-menu.jpg)
5. Press **Start** in the Volume Shadow Copy Service window.
6. Click on the service window’s **Apply** and **OK** buttons to set the changed options.
7. Repeat steps three to six for the Microsoft Software Shadow Copy Provider service.
8. Also, check that the RPC Endpoint Mapper and DCOM Server Process dependency services for Volume Shadow Copy are enabled and running.

 Restart those shadow copy services if they’re already set as required. You can do that by right-clicking on those services and selecting the Restart context menu options for them.

## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)
<!-- affiliate ads begin -->

<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->

## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Conflicting background apps or services are another potential cause of Volume Shadow Copy errors. Third-party backup utilities with snapshot managers are the most likely software packages to conflict with the Volume Shadow Copy Service. If you know you’ve installed a third-party backup manager, uninstalling it could be the best way to ensure it doesn’t cause any conflicts.

 However, you can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to stop third-party apps and services from starting with Windows to prevent conflicts from arising. This involves disabling startup items and services with Task Manager and MSConfig and restarting Windows. Then try utilizing the Windows Backup and Restore or System Restore tools after clean booting your PC to see if the VSS error persists.

 If it does, this means something you disabled during the clean boot is causing the problem. Now you can slowly re-enable each app until the problem reappears, then either uninstall or update the offending app.

## Back up and Restore Windows Again

 These solutions can potentially resolve many variable Volume Shadow Copy Service error messages and codes that pop up during system backup and restore operations. With Volume Shadow Copy fixed, you can back up and restore Windows with built-in system tools again.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-boosting-your-profile-top-25-high-gainning-instagram-tags/"><u>[New] 2024 Approved  Boosting Your Profile  Top 25 High-Gainning Instagram Tags</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-crafting-a-pro-sports-youtube-feed-on-macos/"><u>[New] 2024 Approved  Crafting a Pro Sports YouTube Feed on MacOS</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-chime-connoisseurs-curated-list-of-download-websites/"><u>[New] Chime Connoisseurs  Curated List of Download Websites</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-how-to-enable-or-disable-pip-in-youtube-for-mobile-phones/"><u>[Updated] How to Enable or Disable PIP in YouTube for Mobile Phones</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-ultimate-rotation-video-mounting/"><u>[Updated] Ultimate Rotation Video Mounting</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-unlock-chromes-full-potential-with-pip-across-devices-for-2024/"><u>[Updated] Unlock Chrome's Full Potential with PIP Across Devices for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-expert-iphone-software-roundup-selecting-ideal-watermark-tools/"><u>2024 Approved  Expert iPhone Software Roundup  Selecting Ideal Watermark Tools</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-ultimate-5-iphone-x87-photoshoot-background-swappers/"><u>2024 Approved  Ultimate 5 iPhone X/8/7 Photoshoot Background Swappers</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-vintage-tech-upgrade/"><u>2024 Approved  Vintage Tech Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-your-non-operational-windows-11-hotspot/"><u>Activating Your Non-Operational Windows 11 Hotspot</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-locked-or-disabled-on-iphone-7-plus-7-mehtods-you-cant-miss-by-drfone-ios/"><u>Apple ID Locked or Disabled On iPhone 7 Plus? 7 Mehtods You Cant-Miss</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/breaking-down-madden-19-standout-modes-marred-by-ageing-formula/"><u>Breaking Down Madden '19: Standout Modes Marred by Ageing Formula</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-security-implementing-controlled-access-in-windows/"><u>Command Security: Implementing Controlled Access in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-error-0x8000ffff-in-windows-based-printers/"><u>Conquering Error 0X8000FFFF in Windows-Based Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/craft-the-perfect-christmas-look-in-windows-11/"><u>Craft the Perfect Christmas Look in Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/demystifying-youtube-shorts-content-strategy-guide-for-2024/"><u>Demystifying YouTube Shorts Content Strategy Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-the-depth-of-complete-screenshots-via-windows-snipping-tool/"><u>Dive Into the Depth of Complete Screenshots via Windows' Snipping Tool</u></a></li>
<li><a href="https://location-social.techidaily.com/does-vivo-g2-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>Does Vivo G2 Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-chrome-freeze-and-blank-screens/"><u>Fixing the Chrome Freeze and Blank Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-updates-and-error-windows-0x800f0845/"><u>Fixing Updates and Error: Windows 0X800F0845</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-engage-window-management-feature-in-windows-11-end-task/"><u>How to Engage Window Management Feature in Windows 11 (End Task)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-audacitys-internal-portaudio-error-in-windows-10-and-11/"><u>How to Fix Audacity’s Internal PortAudio Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-lock-windows-safescreen-state-against-user-change/"><u>How to Lock Windows SafeScreen State Against User Change</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-suppression-of-windows-11-notifications/"><u>Immediate Suppression of Windows 11 Notifications</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-complete-guide-on-unlocking-iphone-8-with-a-broken-screen-drfone-by-drfone-ios/"><u>In 2024, Complete Guide on Unlocking iPhone 8 with a Broken Screen? | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-elevate-streams-to-next-level-with-av1-on-youtube/"><u>In 2024, Elevate Streams to Next Level with AV1 on YouTube</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-navigating-the-world-of-ppc-advertising-essential-guidance-for-newbies-on-social-platforms/"><u>In 2024, Navigating the World of PPC Advertising  Essential Guidance for Newbies on Social Platforms</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-lava-yuva-3-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Lava Yuva 3 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-your-usb-wi-fi-adapter-not-connecting-or-working-on-windows-8-ways-to-fix-it/"><u>Is Your USB Wi-Fi Adapter Not Connecting or Working on Windows? 8 Ways to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jolt-from-hibernation-freeze-on-your-pc/"><u>Jolt From Hibernation Freeze on Your PC</u></a></li>
<li><a href="https://extra-support.techidaily.com/master-the-switch-making-your-graphic-style-a-sticker-on-every-platform-for-2024/"><u>Master the Switch  Making Your Graphic Style a Sticker on Every Platform for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-greyed-out-unlock-pin-function-in-windows-11/"><u>Overcoming Greyed Out Unlock Pin Function in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quelling-irregular-beats-soundcard-irq-solutions/"><u>Quelling Irregular Beats: Soundcard IRQ Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaim-your-discord-interface-fixing-a-dormant-overlay/"><u>Reclaim Your Discord Interface: Fixing a Dormant Overlay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719365826035-resolve-camera-woes-in-windows-heres-how/"><u>Resolve Camera Woes in Windows, Here’s How!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sculpt-sketch-and-color-like-never-before-microsoft-paint-enhancements/"><u>Sculpt, Sketch & Color Like Never Before: Microsoft Paint Enhancements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-administrator-privileges-denial-in-cmd-prompt/"><u>Solving Administrator Privileges Denial in Cmd Prompt</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-tutorial-on-updating-your-hp-laserjet-m506-driver-software/"><u>Step-by-Step Tutorial on Updating Your HP LaserJet M506 Driver Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-overcome-insufficient-access-during-uninstall/"><u>Steps to Overcome Insufficient Access During Uninstall</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-amend-out-of-memory-issues-in-hogwarts-adventures/"><u>Strategies to Amend Out of Memory Issues in Hogwarts Adventures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-unusual-wsl-error-4294967295-on-pcs/"><u>Tackling Unusual WSL Error 4294967295 on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-from-s-mode-essential-tips-for-windows-1011/"><u>Transitioning From S Mode: Essential Tips for Windows 10/11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlocking-apple-iphone-8-passcode-without-a-computer-by-drfone-ios/"><u>Unlocking Apple iPhone 8 Passcode without a Computer</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-streamline-your-workflow-6-productivity-boosting-adobe-premiere-pro-tips/"><u>Updated In 2024, Streamline Your Workflow 6 Productivity-Boosting Adobe Premiere Pro Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-simplification-recapturing-default-rights/"><u>Windows 11 Simplification: Recapturing Default Rights</u></a></li>
</ul></div>
