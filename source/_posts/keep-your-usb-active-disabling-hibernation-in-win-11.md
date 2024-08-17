---
title: "Keep Your USB Active: Disabling Hibernation in Win 11"
date: 2024-08-16T02:37:09.597Z
updated: 2024-08-17T02:37:09.597Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Keep Your USB Active: Disabling Hibernation in Win 11"
excerpt: "This Article Describes Keep Your USB Active: Disabling Hibernation in Win 11"
keywords: Win 11 Hibernate Off,Keep USB On,Stop PC Sleep,USB Device Activate,Hibernation Disable,Active USB in Win 11,Prevent System Suspend
thumbnail: https://thmb.techidaily.com/731e7d95cb104fd0f2b4a441263b2d39fb916acbe1dcf99883081e6f54b5961f.jpg
---

## Keep Your USB Active: Disabling Hibernation in Win 11

 Windows' USB selective suspend feature puts USB devices in a low-power state when not in use. While this can enhance battery life, it may cause problems with peripherals that require constant power.

 If you encounter issues with USB devices on your Windows 11 computer, consider disabling the USB selective suspend feature. Here’s how to do so on Windows 11\.

## Why You Might Want to Disable USB Selective Suspend

 Windows has various features to [prolong your laptop's battery life](https://www.makeuseof.com/windows-11-improve-battery-life/), one of which is USB selective suspend. While this feature is great, below are a few situations where you should disable it:

* If Windows fails to recognize a USB device, try turning off USB selective suspend and check if it makes any difference.
* USB selective suspend sometimes adds a small amount of latency, especially in gaming peripherals. So, you can turn it off to get immediate and responsive input from your gaming device.
* USB selective suspend might occasionally conflict with other power management settings, potentially leading to computer instability. If you've been experiencing power-related problems, disabling USB selective suspend could help.

 Now that you know the reason, let’s check out different ways to disable USB selective suspend on Windows 11\.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 1\. Using the Device Manager

 The Device Manager on Windows is the go-to place to manage USB devices connected to your system. You can use it to [update outdated drivers](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/), uninstall devices, and much more. It can also help you turn off the USB selective suspend feature.

 Follow these steps to disable USB selective suspend via the Device Manager:

1. Press the **Win + X** hotkey and choose **Device Manager** from the context menu.
2. Double-click on the **Universal Serial Bus controllers** node.  
![Universal Serial Bus controllers node in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/universal-serial-bus-controllers-node.jpg)
3. Right-click on any **Generic USB Hub** or **USB Root Hub** drivers and choose **Properties**.  
![USB Root Hub driver in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-root-hub.jpg)
<!-- affiliate ads begin -->

<!-- affiliate ads end -->
4. Switch to the **Power** **Management** tab and uncheck the **Allow the computer to turn off this device to save power** option. Then, click **OK** to save the changes.  
![Allow the computer to turn off this device to save power option in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/allow-the-computer-to-turn-off-this-device-to-save-power-option.jpg)

 Now, repeat the above steps for all the USB drivers for which you want to disable USB selective suspend.

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Using the Control Panel

 The Control Panel serves as the central hub of a Windows operating system, allowing users to perform a wide range of tasks. From simple actions like [changing your desktop wallpaper](https://www.makeuseof.com/windows-11-change-desktop-wallpaper/) to more complex operations like managing user accounts, you can do it all by accessing the Control Panel.

 Follow these steps to disable USB selective suspend via the Control Panel:

1. Press the **Win** key to open the **Start** **Menu**, type **Control** **Panel** in the search bar, and press Enter.
2. Navigate to **System and Security** \> **Power** **Options** \> **Change** **plan** **settings**.
3. Click the **Change** **advanced** **power settings** option.  
![Change advanced power settings option in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-advanced-power-settings-option.jpg)
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Double-click on the **USB settings** option and then expand **USB selective suspend setting**.  
![USB selective suspend setting in Power Option window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-selective-suspend-setting.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
5. Choose **Disabled** for both the **On battery** and **Plugged in** options.  
![Disabled option in Power Option window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disabled-option.jpg)
6. Click **Apply** \> **OK** to save the changes.

 The USB selective suspend feature is now disabled. Let's look at one more way to do so.

## 3\. Using Command Prompt

 Follow these steps to disable USB selective suspend via the Command Prompt:

1. Open the Start Menu, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane.
2. Type the following command in the elevated Command Prompt window and press Enter.  
`powercfg /SETACVALUEINDEX SCHEME_CURRENT 2a737441-1930-4402-8d77-b2bebba308a3 48e6b7a6-50f5-4782-a5d4-53bb8f07e226 0`  
![Disable USB Selective Suspend command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-usb-selective-suspend.jpg)
<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 And you're done! The USB selective suspend feature is now disabled on your Windows computer. If you wish, you can easily turn it back on using the same navigation as shown above.

## USB Selective Suspend Is Good, but Not Perfect

 We've taken a look at how and when to disable USB selective suspend. As mentioned earlier, it can occasionally lead to system instability, introduce latency, or even cause your computer to fail to recognize the USB device. Therefore, disabling it might be preferable when power efficiency isn't a top priority for your system.

 However, if disabling USB selective suspend doesn't resolve the issue, there are various other troubleshooting steps you can take when Windows fails to recognize a USB device.

 If you encounter issues with USB devices on your Windows 11 computer, consider disabling the USB selective suspend feature. Here’s how to do so on Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/024-approved-chasing-likes-and-loads-jake-pauls-youtube-ambition/"><u>[New] 2024 Approved  Chasing Likes and Loads  Jake Paul's YouTube Ambition</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-elevate-video-quality-from-youtube-to-crisp-avis-format/"><u>[New] In 2024, Elevate Video Quality From YouTube to Crisp Avis Format</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-ultimate-guide-to-affordable-online-meetings-plus-desktop-display/"><u>[New] In 2024, Ultimate Guide to Affordable Online Meetings + Desktop Display</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-unlocking-freenocams-webcam-capturing-capabilities/"><u>[New] In 2024, Unlocking FreenoCam's Webcam Capturing Capabilities</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-mastering-the-art-of-online-conference-coordination/"><u>[New] Mastering the Art of Online Conference Coordination</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-streamlined-recording-the-very-best-fullscreen-software-for-2024/"><u>[New] Streamlined Recording  The Very Best Fullscreen Software for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unmatched-tech-elevation-through-srs-enhancement/"><u>[Updated] Unmatched Tech Elevation Through SRS Enhancement</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-4k-lg-display-assessment-the-ultimate-31mu97-b/"><u>2024 Approved  4K LG Display Assessment  The Ultimate 31MU97-B</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-how-to-record-mov-files-on-windows-11/"><u>2024 Approved  How to Record MOV Files on Windows 11</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-unlocking-crypto-potential-the-ultimate-list-of-nft-engines/"><u>2024 Approved  Unlocking Crypto Potential  The Ultimate List of NFT Engines</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-unlock-icloud-account-without-password-from-iphone-14-pro-max-by-drfone-ios/"><u>3 Effective Ways to Unlock iCloud Account Without Password From iPhone 14 Pro Max</u></a></li>
<li><a href="https://unlock-android.techidaily.com/5-solutions-for-honor-magic-5-pro-unlock-without-password-by-drfone-android/"><u>5 Solutions For Honor Magic 5 Pro Unlock Without Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-workflow-paste-and-mouse-jump-techniques/"><u>Accelerate Workflow: Paste & Mouse Jump Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-data-security-activating-controlled-folder-access/"><u>Achieve Data Security: Activating Controlled Folder Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-failure-of-intels-wi-fi-6d-driver-in-os/"><u>Addressing Failure of Intel's Wi-Fi 6D Driver in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-w11-issues-with-csgo/"><u>Addressing W11 Issues with CS:GO</u></a></li>
<li><a href="https://win11-tips.techidaily.com/critical-steps-for-a-complete-operating-system-wipe/"><u>Critical Steps for a Complete Operating System Wipe</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-ways-to-refresh-your-pcs-audio-driver-on-windows-versions-11-10-and-7/"><u>Easy Ways to Refresh Your PC's Audio Driver on Windows Versions 11, 10 & 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-software-disposal-adding-context-menu-shortcuts-to-win-1011/"><u>Efficient Software Disposal: Adding Context Menu Shortcuts to Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-screen-radiance-on-windows-11-practical-fixes/"><u>Elevate Screen Radiance on Windows 11: Practical Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-not-found-error-in-windows-setup/"><u>Eliminating Not Found Error in Windows Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-task-automation-tackling-scheduler-issues/"><u>Enhance Task Automation: Tackling Scheduler Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-interface-quick-menu-install/"><u>Enhancing Windows Interface: Quick Menu Install</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-troubleshooting-steps-for-internal-error-on-windows-1111-pro/"><u>Essential Troubleshooting Steps for Internal Error on Windows 11/11 Pro</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/evaluating-webex-insights-into-its-top-perks-and-pitfalls-for-effective-digital-teamwork/"><u>Evaluating Webex: Insights Into Its Top Perks and Pitfalls for Effective Digital Teamwork</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-editing-text-via-snipping-tool/"><u>Expert Guide: Editing Text via Snipping Tool</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/fb-activity-preview-insight-or-intrusion-whats-safer-for-2024/"><u>FB Activity Preview  Insight or Intrusion – What's Safer for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fine-tuning-virtual-memory-in-windows-11-for-maximum-performance/"><u>Fine-Tuning Virtual Memory in Windows 11 for Maximum Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fractured-fort-knox-continue-current-cybersecurity/"><u>Fractured Fort Knox? Continue Current Cybersecurity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-automating-dns-client-service-configuration/"><u>Guide to Automating DNS Client Service Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-circumvent-ms-defender-block-on-other-av-tools/"><u>How to Circumvent MS Defender Block on Other AV Tools</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-tecno-photos-an-easy-method-explained-by-fonelab-android-recover-photos/"><u>How to Restore Deleted Tecno Photos  An Easy Method Explained.</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-infinix-note-30-vip-drfone-by-drfone-virtual-android/"><u>How to Stop My Spouse from Spying on My Infinix Note 30 VIP | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/icloud-on-windows-common-fixes-for-download-problems/"><u>ICloud on Windows: Common Fixes for Download Problems</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-samsung-galaxy-a25-5g-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Samsung Galaxy A25 5G by Phone Number | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-turn-off-find-my-apple-iphone-12-pro-when-phone-is-broken-by-drfone-ios/"><u>In 2024, How to Turn Off Find My Apple iPhone 12 Pro when Phone is Broken?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-jokegenius-get-the-best-meme-app/"><u>In 2024, JokeGenius - Get the Best Meme App</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-photo-framing-made-easy-leading-apps-and-sites-reviewed/"><u>In 2024, Photo Framing Made Easy  Leading Apps and Sites Reviewed</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-apps-and-online-tools-to-track-xiaomi-redmi-13c-phone-withwithout-imei-number-by-drfone-android/"><u>In 2024, Top Apps and Online Tools To Track Xiaomi Redmi 13C Phone With/Without IMEI Number</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-which-pokemon-can-evolve-with-a-moon-stone-for-honor-x8b-drfone-by-drfone-virtual-android/"><u>In 2024, Which Pokémon can Evolve with a Moon Stone For Honor X8b? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/install-update-and-remove-with-precision-using-windows-package-manager/"><u>Install, Update & Remove with Precision Using Windows Package Manager</u></a></li>
<li><a href="https://program-issues.techidaily.com/latest-guide-to-prevent-obs-from-failing-on-windows-pcs-windows-10-and-11-202-the-provided-information-seems-incomplete-as-the-year-202-is-missing-at-the-en510/"><u>Latest Guide to Prevent OBS From Failing on Windows PCs (Windows 10 & 11, 202 The Provided Information Seems Incomplete as the Year '202' Is Missing at the End of the Title Example [SOLVED] OBS Crashing on Windows 11/10 - 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/laughterbox-easy-entry-endless-entertainment/"><u>LaughterBox  Easy Entry, Endless Entertainment</u></a></li>
<li><a href="https://extra-information.techidaily.com/leading-top-5-agile-action-camera-selections/"><u>Leading Top 5 Agile Action Camera Selections</u></a></li>
<li><a href="https://extra-information.techidaily.com/maximizing-creativity-with-picsart-an-in-depth-2024-guide/"><u>Maximizing Creativity with PicsArt  An In-Depth 2024 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-with-ease-your-guide-to-windows-11-audio-control/"><u>Navigating with Ease: Your Guide to Windows 11 Audio Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-terminal-settings-on-windows-pc/"><u>Optimizing Terminal Settings on Windows PC</u></a></li>
<li><a href="https://extra-resources.techidaily.com/powerdirector-2024-insiders-guide-full-review-and-steps-to-mastery/"><u>PowerDirector 2024 Insider's Guide  Full Review & Steps to Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propel-productivity-the-top-6-win-tracking-software-choices/"><u>Propel Productivity: The Top 6 Win Tracking Software Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-activate-hyper-v-in-windows-11/"><u>Quick Guide to Activate Hyper-V in Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/raising-awareness-with-youtubes-cc-membership-tips-for-view-growth-for-2024/"><u>Raising Awareness with YouTube's CC Membership  Tips for View Growth for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rearrange-screen-alignment-for-windows-users/"><u>Rearrange Screen Alignment for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-stalled-amd-driver-in-windows-environment/"><u>Remedying Stalled AMD Driver in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-this-device-is-being-used-by-someone-else-in-sound/"><u>Resolving 'This Device Is Being Used By Someone Else' In Sound</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-xbox-game-pass-fatal-error-code-0-on-windows-11/"><u>Resolving Xbox Game Pass Fatal Error Code 0 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-printer-connectivity-in-windows-os/"><u>Restoring Printer Connectivity in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-event-viewer-usability/"><u>Restoring Windows Event Viewer Usability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-your-pubg-saved-data-in-windows-1110/"><u>Reviving Your PUBG Saved Data in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpening-up-discord-response-time-on-windows-devices/"><u>Sharpening Up Discord Response Time on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocketing-through-efficiency-top-7-strategies-with-windows-11-39/"><u>Skyrocketing Through Efficiency: Top 7 Strategies with Windows 11 (39)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-file-download-problems-in-windows/"><u>Strategies to Overcome File Download Problems in WIndows</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722973769050-surface-book-driver-update-made-simple-download-now/"><u>Surface Book Driver Update Made Simple – Download Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sync-success-reestablishing-obs-studio-server-connection-in-win/"><u>Sync Success: Reestablishing OBS Studio Server Connection in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-updating-windows-in-isolation/"><u>The Art of Updating Windows in Isolation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-swiftly-show-and-hide-directories-on-windows-11-pcs/"><u>Tips for Swiftly Show & Hide Directories on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-6-windows-to-dos-optimal-apps-compared/"><u>Top 6 Windows To-Dos: Optimal Apps Compared</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trim-down-warmup-latency-top-tips-for-a-quicker-boot-up/"><u>Trim Down Warmup Latency – Top Tips for a Quicker Boot-Up</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/troubleshoot-vanished-facebook-videos-discover-our-top-12-fixes-for-2024/"><u>Troubleshoot Vanished Facebook Videos - Discover Our Top 12 Fixes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-error-code-0x800713f-windows-11s-mail-woes/"><u>Unraveling Error Code 0X800713F: Windows 11'S Mail Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-managing-your-network-proxy/"><u>Windows 11: Managing Your Network Proxy</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>