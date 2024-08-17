---
title: Tackling Windows Sound System Malfunctions
date: 2024-08-16T02:23:59.963Z
updated: 2024-08-17T02:23:59.963Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Windows Sound System Malfunctions
excerpt: This Article Describes Tackling Windows Sound System Malfunctions
keywords: Fixing Windows Audio Errors,Troubleshoot Windows Sounds,Solve Windows Sound Issues,Windows Audio Problems Help,Windows Sound Glitches Cure,Address Windows Audio Failures,Overcome Windows Sound Breakdown
thumbnail: https://thmb.techidaily.com/51b5c705b272c6a35f26cbee92033b8d25124b814164fccb1a1f598c30e520f7.jpg
---

## Tackling Windows Sound System Malfunctions

 Although Windows includes a dedicated audio troubleshooter that can help resolve most audio-related issues, it may not always be effective. At times, the Windows audio troubleshooter may fail to resolve the underlying issue and display the “Audio services not responding” error.

 If the audio services on your Windows computer have become unresponsive, don’t fret. This guide packs some useful troubleshooting tips that should help you resolve the issue in no time.

## 1\. Restart the Windows Audio Service

 Typically, the Windows Audio service starts automatically when your computer boots. However, if the service encounters any problems during startup, it may malfunction. If it's just a one-off glitch, restarting the Windows Audio service should fix the issue. Hence, you should start with that.

To restart the Windows Audio service:

1. Press**Win + S** to open the search menu.
2. Type**services** in the text box and press**Enter** .
3. In the Services window, scroll down to locate the**Windows Audio** service on the list. Then, right-click on it and select**Restart** .  
![Restart Windows Audio Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-windows-audio-service.jpg)

## 2\. Make Sure the Supporting Audio Components Are Running

 Windows Audio service relies on several system components to function properly on your PC. If one of these components is not running, audio services may stop responding.

Here’s how to check if the required services are running.

1. Press**Win + R** to open the Run dialog box.
2. Type**services.msc** in the Open field and press**Enter** .
3. Locate the**RPC Endpoint Mapper** service on the list and double-click on it to open its properties.
4. Click the drop-down menu next to**Startup type** to select**Automatic** .
5. Click**Apply** followed by**OK** .
6. Similarly, change the startup type for**Remote Procedure Call (RPC)** and**DCOM Server Process Launcher** services as well.  
![Remote Procedure Call Service in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/remote-procedure-call-service-in-windows.jpg)

Restart your PC after this and check if the issue is still there.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Add Local and Network Services Using Command Prompt

 Another thing you can do to resolve this issue is to register local and network services on Windows using Command Prompt. Here are the steps for the same.

1. Right-click on the**Start icon** or press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command in the console and press**Enter** to register network services on your system.  
`net localgroup Administrators /add networkservice`
5. Now run the following command to register local services:  
`net localgroup Administrators /add localservice`
6. Exit the Command Prompt window and then restart your PC.  
![Add Local and Network Services Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-local-and-network-services-using-command-prompt.jpg)

 Like using Command Prompt? Check our guide to learn [how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Update Audio Drivers

 Outdated or incompatible audio drivers on your PC can also cause the audio services to malfunction. If that's the case, updating the audio drivers on your PC should do the trick. If you need help with that, check our guide on [how to update audio drivers on Windows](https://www.makeuseof.com/update-audio-drivers-windows/) and follow the steps outlined there.

 If updating audio drivers manually sounds like a tedious task, you can get one of the [best driver updater for Windows](https://www.makeuseof.com/windows-best-free-driver-updaters/) to ease the process.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## 5\. Switch to the Default Sound Drivers

 Your Windows computer comes with its own set of sound drivers. If updating your current audio drivers does not help, you can switch to Windows' default sound drivers and see if that works. To do so, use the following steps:

1. Click the**magnifying icon** on the taskbar or press**Win + S** to open the search menu.
2. Type**control panel** in the text box and select the first result that appears.
3. Navigate to**System > Advanced System Settings** .
4. In the System Properties window, switch to the**Hardware** tab and click the**Device Installation Settings** button.
5. Select the**No (your device might not work as expected)** option and click**Save Changes** .

1. Select**Yes** when the User Account Control (UAC) prompt appears.  
![Device Installation Settings on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/device-installation-settings-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
2. Now use one of the [many ways to open Device Manager](https://www.makeuseof.com/windows-open-device-manager/) .
3. Expand the**Sound, video, and game controllers** .
4. Right-click on your sound driver and select**Uninstall device** .
5. Select**Uninstall** to confirm the action.
6. In the Device Manager window, click the**Action** menu at the top and select**Scan for hardware changes** from the list.  
![Uninstall Sound Driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/uninstall-sound-driver.jpg)

## 6\. Run the SFC and DISM Scans

 Corrupt or damaged system files on Windows can also cause audio services to stop responding. System File Checker (SFC) and Deployment Image Servicing and Management (DISM) are two Windows tools that can help you identify and repair such system files.

 The SFC scan will check your computer for missing or corrupt system files, whereas DISM will repair the Windows system image. You can run these tools using Command Prompt. To know more, check our guide on [how to repair corrupt Windows files with Windows built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/) and follow the steps outlined there.

## 7\. Perform a System Restore

 System Restore is a useful feature on Windows that creates a backup of your entire system at predefined intervals. It can help you restore your system to the point before the problem occurred.

 System Restore will undo any recent changes made to your computer and resolve the issue for good. Don’t worry, this process won’t affect any of your personal data.

To perform a system restore on Windows, use these steps:

1. Right-click on the**Start** icon and select**Run** from the list.
2. Type**sysdm.cpl** in the box and press**Enter** .
3. In the System Properties window, switch to the**System Protection** tab.
4. Click on**System Restore** .
5. Click**Next** .
6. Select a restore point before the issue first appeared and hit**Next** .
7. Review all the details and click**Finish** .  
![System Restore Dialog on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/system-restore-dialog-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->

 Wait for Windows to restart and revert to the specified restore point. After that, the audio services should work fine.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
## Fixing Audio Services on Windows Is Easy

 It can be confusing if the audio services on Windows suddenly become unresponsive. In most cases, manually restarting the audio services should resolve the issue. If not, you may have to go through the trouble of scanning the system files or performing a system restore.

 That said, if none of the above solutions work, you can consider resetting your Windows computer or performing an in-place upgrade as a last resort.


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
<li><a href="https://youtube-sure.techidaily.com/024-approved-earning-strategies-for-successful-youtube-shorts-must-haves-earnings-prospects/"><u>[New] 2024 Approved  Earning Strategies for Successful Youtube Shorts  Must-Haves, Earnings Prospects</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-leading-audio-visual-artists-collaborating-photos/"><u>[New] 2024 Approved  Leading Audio-Visual Artists Collaborating Photos</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-capitalizing-on-hairstyle-demonstrations/"><u>[New] In 2024, Capitalizing on Hairstyle Demonstrations</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-elevate-your-visuals-music-integration-for-vimeo-films/"><u>[New] In 2024, Elevate Your Visuals  Music Integration for Vimeo Films</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-skype-talk-improvement-silence-the-surroundings/"><u>[New] Skype Talk Improvement  Silence the Surroundings</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-2024-approved-foremost-10-video-subtitling-services-online/"><u>[Updated] 2024 Approved  Foremost 10 Video Subtitling Services Online</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-visual-voice-choir-discovering-video-driven-music/"><u>[Updated] 2024 Approved  Visual Voice Choir  Discovering Video-Driven Music</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-exploring-video-realm-mirrorless-challenges-to-dslrs/"><u>[Updated] Exploring Video Realm  Mirrorless Challenges to DSLRs</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-expert-audacity-tricks-for-premium-audio/"><u>2024 Approved  Expert Audacity Tricks for Premium Audio</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-gain-listener-traffic-advanced-techniques-in-podcast-seo/"><u>2024 Approved  Gain Listener Traffic  Advanced Techniques in Podcast SEO</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-navigating-the-world-of-ifunny-memes/"><u>2024 Approved  Navigating the World of iFunny Memes</u></a></li>
<li><a href="https://article-tips.techidaily.com/best-6-social-media-platforms-for-business-for-2024/"><u>Best 6 Social Media Platforms for Business for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-value-4k-photography-equipment-for-2024/"><u>Best Value 4K Photography Equipment for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-your-windows-pdf-viewers/"><u>Customizing Your Window's PDF Viewers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dodging-dangers-the-downside-to-discounted-windows-activation-codes/"><u>Dodging Dangers: The Downside to Discounted Windows Activation Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicate-the-zero-error-on-new-win11-systems/"><u>Eradicate the Zero Error on New Win11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-on-installing-win11s-version-22h2-upgrade-successfully/"><u>Expert Advice on Installing Win11's Version 22H2 Upgrade Successfully</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/flip-the-script-mastering-instagram-video-replay/"><u>Flip the Script  Mastering Instagram Video Replay</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-new-nvidia-rtx-2080-supers-drivers-compatible-with-windows-1011-download-now/"><u>Get the New Nvidia RTX 2080 Supers Drivers – Compatible with Windows 10/11, Download Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-microsoft-365-error-code-30015-26-on-windows/"><u>How to Fix the Microsoft 365 Error Code 30015-26 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-windows-update-automatically-replacing-your-amd-graphics-driver/"><u>How to Fix Windows Update Automatically Replacing Your AMD Graphics Driver</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-open-sticky-notes-in-windows-11/"><u>How to Open Sticky Notes in Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-oppo-find-x6-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Oppo Find X6 by Phone Number | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-of-the-best-pokemon-discord-servers-to-join-on-nokia-xr21-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some of the Best Pokemon Discord Servers to Join On Nokia XR21 | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-instant-impact-the-ultimate-10-principles-of-iphone-photography-design/"><u>In 2024, Instant Impact  The Ultimate 10 Principles of iPhone Photography Design</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-apple-iphone-14-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Apple iPhone 14 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-the-power-of-words-in-podcast-summaries/"><u>In 2024, The Power of Words in Podcast Summaries</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Location is Not Updating and How to Fix On Oppo Find N3 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mapping-out-your-connections-a-netstat-guide-for-windows-11-users/"><u>Mapping Out Your Connections: A Netstat Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-privacy-remove-login-email-in-windows/"><u>Mastering Privacy: Remove Login Email in Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/mastering-the-art-of-automated-audio-transcription-with-azure-for-2024/"><u>Mastering the Art of Automated Audio Transcription with Azure for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterpieces-at-your-fingertips-4-notable-new-paint-features/"><u>Masterpieces at Your Fingertips: 4 Notable New Paint Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-difficulties-handling-winscomrsvdll-problems/"><u>Navigate Through Difficulties: Handling WinscomrsvDll Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-key-discrepancies-an-essential-guide-to-troubleshooting-on-windows-11/"><u>Navigating Key Discrepancies: An Essential Guide to Troubleshooting on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-robloxs-code-403-issue-on-pc/"><u>Overcoming Roblox's Code 403 Issue on PC</u></a></li>
<li><a href="https://fake-location.techidaily.com/prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-infinix-note-30-vip-racing-edition-drfone-by-drfone-virtual-android/"><u>Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Infinix Note 30 VIP Racing Edition | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/premier-pick-top-10-apps-to-catch-football-and-tennis-in-the-moment-for-2024/"><u>Premier Pick  Top 10 Apps to Catch Football and Tennis in the Moment for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prioritizing-deps-ensuring-vbox-works-smoothly-on-win/"><u>Prioritizing Deps, Ensuring VBox Works Smoothly on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-disconnected-spotify-pc-app/"><u>Quick Fix for Disconnected Spotify PC App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-rockalldlldll-disappearance-on-pcs/"><u>Repairing Rockalldll.dll Disappearance on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-windows-sharing-dilemmas-immediately/"><u>Resolve Windows Sharing Dilemmas Immediately</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-procedures-for-resetting-windows-updates/"><u>Simplified Procedures for Resetting Windows Updates</u></a></li>
<li><a href="https://extra-resources.techidaily.com/soft-onset-visual-effects/"><u>Soft Onset Visual Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-directx-update-issues-in-windows/"><u>Solutions for DirectX Update Issues in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solve-your-winerror-effective-fixes-for-script-issues/"><u>Solve Your WinError: Effective Fixes for Script Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-prevent-full-capacity-on-windows-gpt/"><u>Strategies to Prevent Full Capacity on Windows GPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-steps-for-updating-administrator-in-win11-environment/"><u>Streamlined Steps for Updating Administrator in Win11 Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-file-management-windows-11s-auto-transfer-trick/"><u>Streamlining File Management: Windows 11'S Auto-Transfer Trick</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-execution-optimizing-android-studio-on-windows/"><u>Swift Execution: Optimizing Android Studio on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-your-tech-timetable-optimizing-windows-11s-update-processes/"><u>Tailor Your Tech Timetable: Optimizing Windows 11'S Update Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-temperature-spikes-during-high-performance-gaming/"><u>Taming Temperature Spikes During High-Performance Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-integrating-secondary-antivirus-without-defenders-limits/"><u>Techniques for Integrating Secondary Antivirus without Defender’s Limits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-prevent-activation-of-windows-mobility-center-win-11/"><u>Tips: Prevent Activation of Windows Mobility Center (Win 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/toggle-system-editor-enabledisable-in-win11/"><u>Toggle System Editor: Enable/Disable in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-no-hypervisor-in-windows-sandbox/"><u>Troubleshooting No Hypervisor in Windows Sandbox</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unboxing-and-evaluating-the-best-big-screen-phone-the-definitive-samsung-galaxy-note-9-review/"><u>Unboxing and Evaluating the Best Big Screen Phone: The Definitive Samsung Galaxy Note 9 Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-potential-of-warhammer-40k-eliminate-pc-lag/"><u>Unlock the Full Potential of Warhammer 40K: Eliminate PC Lag</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unraveling-the-ai-talk-twist-gpt-vs-bingbot-breakdown/"><u>Unraveling the AI Talk Twist: GPT Vs. BingBot Breakdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wake-the-world-4-key-steps-to-restore-windows-server-time/"><u>Wake the World: 4 Key Steps to Restore Windows Server Time</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ways-to-halt-the-start-of-edge-tabs-in-windows-11/"><u>Ways to Halt the Start of Edge Tabs in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-users-ready-for-sudo/"><u>Windows Users, Ready for Sudo?</u></a></li>
</ul></div>
