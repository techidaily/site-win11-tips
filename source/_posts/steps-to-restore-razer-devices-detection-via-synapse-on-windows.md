---
title: Steps to Restore Razer Devices Detection via Synapse on Windows
date: 2024-07-12T17:01:56.913Z
updated: 2024-07-13T17:01:56.913Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Restore Razer Devices Detection via Synapse on Windows
excerpt: This Article Describes Steps to Restore Razer Devices Detection via Synapse on Windows
keywords: Razer Device Recovery Guide,WinRazer Detection Trick,Synapse Settings Fix,Restore Razer Synapse,Windows Razer Device Pairing,Revive Razer on PC,Razer Device Link Fix
thumbnail: https://thmb.techidaily.com/ed43cb68b7509790195a4106080566d9794dc5d45025fc9ee05e6abe84591529.jpg
---

## Steps to Restore Razer Devices Detection via Synapse on Windows

 Razer Synapse is the official software for configuring Razer devices, such as keyboards and mice. However, Synapse sometimes doesn’t detect connected Razer devices. Consequently, users can’t configure their devices because they don’t show up in the Synapse software.

 The issue of Synapse not detecting devices is mostly reported for Razer mice and keyboards. However, that issue can also occur for Razer headphones, broadcast microphones, and other accessories that software will usually detect. This is how you can fix the Synapse software not detecting Razer devices within Windows 10 and 11.

## But First, Double-Check Device Compatibility With Razer Synapse

 First, before you hop into the troubleshooting steps, note that Synapse will not detect non-Razer devices. There are even some Razer products Synapse 3.0 and 2.0 don’t support. It might be the case Synapse isn’t detecting your hardware because it doesn’t support it. So, double-check your Razer Synapse software supports the device it’s not detecting.

 You can check supported hardware at the [Razer Synapse 3 supported device page](https://mysupport.razer.com/app/answers/detail/a%5Fid/4130/~/razer-synapse-3-supported-devices) . Click a category on that page to see if your device is listed there. You can also check compatibility for version 2.0 at the [Razer Synapse 2.0](https://mysupport.razer.com/app/answers/detail/a%5Fid/4131/~/razer-synapse-2.0-supported-devices) supported device page. If your device is listed among the supported hardware on one of those pages, your Synapse software should detect it.

## 1\. Run the Hardware and Devices Troubleshooter

 Windows has a Hardware and Devices troubleshooter that could identify and even resolve issues with the Razer device Synapse isn’t detecting. However, that troubleshooter isn’t visible within Settings. Nevertheless, you can run the Hardware and Devices troubleshooter from Command Prompt like this:

1. Make sure your Razer device is connected to your PC.
2. Click a**Type here to search** (magnifying glass) button or box on your Windows 11/10 taskbar.
3. To find Command Prompt, input the phrase**cmd** in the**Type here to search** box.
4. Select the Command Prompt app in the Windows search tool.
5. Execute this Hardware and Devices troubleshooter command:  
`msdt.exe -id DeviceDiagnostic`  
![The Hardware and Devices troubleshooter command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hardware-troubleshooter-command.jpg)
6. Click**Next** in the Hardware and Devices troubleshooter.  
![The Hardware and Devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-hardware-and-devices-troubleshooter.jpg)
7. Select**Apply this fix** for resolutions the troubleshooter suggests.

## 2\. Plug the Razer Device into an Alternative USB Port

 This issue can occur because of USB port connection issues. Some users have revealed that plugging Razer devices into different USB ports on their PCs resolved the issue of synapse not detecting them. So, try unplugging your Razer device and plugging it into an alternative USB port. Also, plug the device directly into your PC without using any intermediary USB hubs.

 It’s also recommended to select a**Remove device** option in Settings before plugging your device into another port. To do that, press the**Windows** logo +**I** key, select**Bluetooth and devices** , and click**View more** **devices** . Then click the three-dot button for your Razer hardware and select**Remove device** . In Windows 10’s Settings app, you can select a Razer peripheral on the**Bluetooth & other devices** tab and press**Remove device** .

![The Remove device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-device-option.jpg)

## 3\. Select Synapse’s Repair Option

 A lot of users have also said they’ve been able to fix Synapse not detecting devices by selecting a**Repair** option for that software. Synapse has a**Repair** option you can select on a Razer Gaming Software window. This is how you can select that option in Windows 11/10:

1. Bring up the Windows uninstaller utility in the Control Panel with a method in our guide for [opening Programs and Features on Windows](https://www.makeuseof.com/windows-open-programs-and-features-tool/) .
2. Then select Razer Synapse in Programs and Features.
3. Click the**Change** button for Razer Synapse.  
![The Change button for Synapse](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-button.jpg)
4. Select the**Repair** option in the window that opens.  
![The Repair button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-button.jpg)
5. Sign back into Razer Synapse after selecting**Repair** .
6. Then select**Restart** in Windows 11/10 before launching Synapse.

## 4\. Reinstall Razer Synapse

 Corrupted or missing Synapse modules can cause the issue of Synapse not detecting Razer devices. So, thoroughly uninstalling Synapse by erasing leftover data and reinstalling the software will often resolve that issue. Reinstall Razer Synapse as follows:

1. Open the Programs and Features applet.
2. Click Razer Synapse to select that software.
3. Select**Uninstall** in Programs and Features to open a Razer Gaming Software window.
4. Then click the**Uninstall** option in the window to remove Synapse.
5. Uninstall Cortex and any other associated Razer sub-programs.
6. Press the**Windows** logo key +**R** to access a Run command box.
7. Input this folder directory in Run and click**OK** :  
`C:\Program Files (x86)\Razer`  
![The Program Files > Razer folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/razer-directory.jpg)
8. Press**Ctrl** +**A** to select any remaining files in the Razer folder.
9. Press the**Del** key to erase the selected files.

 Next, input this Razer directories path in Explorer’s address bar and hit**Enter** :

`C:\ProgramData\Razer`

![The ProgramData > Razer folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/razer-subfolder.jpg)

 Repeat steps eight and nine to delete all files in the Razer directories folder. Once done, restart your PC.

1. Click**Download Now** on the [Razer Synapse](https://razer.a9yw.net/c/119570/642901/10229?subId1=UUmuoUeUpU2022703&subId2=emuo&u=https%3A%2F%2Fwww.razer.com%2Fgb-en%2Fsynapse-3) page.
2. Double-click the downloaded**RazerSynapseInstaller\_V1.12.0.385.exe** file to open the setup wizard.  
![The Razer software installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/razer-installer.jpg)
3. Select the**Synapse** checkbox along with other Razer software to reinstall, and click the**Install** option.

## 5\. Reinstall Mouse and Keyboard Device Drivers

 Another fix confirmed to work for this Synapse issue is to reinstall all Razer and HID-compliant mouse and keyboard devices. Applying that potential resolution can resolve device driver conflicts. You can reinstall HID mouse and keyboard drivers as follows:

1. Press the**Win +** **X** keyboard shortcut that brings up a Power User menu.
2. Click**Device Manager** to view that tool’s window.
3. Double-click**Mice and other pointing devices** to view peripherals for that category.
4. Right-click a Razer mouse and select**Uninstall device** \>**Uninstall** .  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-device-option.jpg)
5. Repeat the previous step for all HID mice devices listed.
6. Then double-click the**Keyboards** category.  
![The Keyboards device category](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/keyboards-category.jpg)
7. Uninstall all Razer and HID keyboard devices listed there as outlined in step four.
8. Reboot the Windows PC for the automatic reinstallation of device drivers. You can also select**Action** and**Scan for hardware changes** in Device Manager to reinstall uninstalled peripherals.

## 6\. Disable Antivirus Utilities

 Temporarily antivirus apps on your PC to ensure they aren’t blocking Synapse in any way. You can disable Windows Security’s real-time protection as outlined in our guide for [disabling Microsoft Defender](https://www.makeuseof.com/how-to-turn-off-microsoft-defender-windows-11/) . If there’s a third-party antivirus tool on your PC, turn off its shield via its system tray icon’s context menu.

![Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/real-time-protection-option2.jpg)

 Launch Razer Synapse to see if it detects your devices after disabling antivirus software on your PC. If this potential resolution works, consider adding Razer Synapse to the [exclusion list in Windows Security](https://www.makeuseof.com/windows-11-security-exclusions/) or alternative security software. Then turn your antivirus protection back on.

## Configure Your Razer Devices in Synapse Again on Windows

 Those potential solutions will most likely resolve Synapse not detecting connected devices. Then you can reconfigure your Razer mouse, keyboard, or any other supported hardware with that software. However, any users who still need more troubleshooting guidance for this issue can submit a ticket to Razer’s support service by clicking the**Contact Support** button on this [Synapse 3 page](https://mysupport.razer.com/app/answers/detail/a%5Fid/3783/~/razer-synapse-3-support) .

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
<li><a href="https://win11-tips.techidaily.com/strategies-for-correcting-severe-browser-js-problem-in-discord/"><u>Strategies for Correcting Severe Browser JS Problem in Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-revive-network-router-page-on-windows/"><u>Methods to Revive Network Router Page on Windows</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-gourmet-guides-leading-food-vloggers-online/"><u>[Updated] Gourmet Guides  Leading Food Vloggers Online</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-streamlined-processes-for-effective-apple-display-recording/"><u>[New] 2024 Approved  Streamlined Processes for Effective Apple Display Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-buyers-guide-affordable-access-to-windows-11-vcs/"><u>A Buyer’s Guide: Affordable Access to Windows 11 VCs</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-seamless-sharing-twitch-links-on-your-fb-page-for-2024/"><u>[Updated] Seamless Sharing  Twitch Links on Your FB Page for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-geforce-experience-setup-failure-windows-11-edition/"><u>Resolving GeForce Experience Setup Failure, Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-rectifications-quick-tricks-to-prevent-windows-crashes-in-games/"><u>Rapid Rectifications: Quick Tricks to Prevent Windows Crashes in Games</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-ideal-mp4-slicer-for-mac-boost-your-vlog-game/"><u>2024 Approved  Ideal MP4 Slicer for Mac  Boost Your Vlog Game</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-monitoring-integrating-system-resource-data-in-systray/"><u>Streamline Monitoring: Integrating System Resource Data in SysTray</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-elevated-visuals-selecting-the-right-card/"><u>2024 Approved  Elevated Visuals  Selecting the Right Card</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-steps-to-correct-cannot-find-gpeditmsc-issue/"><u>Unveiling Steps to Correct Cannot Find Gpedit.msc Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-grades-with-these-top-8-windows-study-hacks/"><u>Skyrocket Grades with These Top 8 Windows Study Hacks</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-quicksnap-win10-recording-master/"><u>[New] In 2024, QuickSnap Win10 Recording Master</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-music-from-honor-x7b-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Music from Honor X7b to iPod | Dr.fone</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ocial-media-broadcast-battle-facebook-vs-youtube-and-twitvision/"><u>[New] Social Media Broadcast Battle  FACEbook Vs. YOUTube & TWITVision</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-sound-streaming-showdown-which-is-the-better-choice-podcast-or-youtube/"><u>2024 Approved  Sound Streaming Showdown  Which Is the Better Choice, Podcast or YouTube?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalize-your-windows-11-interface-with-these-tips/"><u>Revitalize Your Windows 11 Interface with These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/start-your-chatgpt-experience-windows-guide/"><u>Start Your ChatGPT Experience: Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11s-secure-testing-solution-enabling-and-configuring-sandbox/"><u>Win 11'S Secure Testing Solution: Enabling and Configuring Sandbox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-manual-for-mending-screen-size-issues-on-windows/"><u>A Step-by-Step Manual for Mending Screen Size Issues on Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/boosting-video-conference-quality-a-guide-to-using-zoom-and-skype-for-2024/"><u>Boosting Video Conference Quality  A Guide to Using ZOOM & SKYPE for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-minecraft-glitches-with-these-fixes/"><u>Stop Minecraft Glitches with These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-conquering-win-errors/"><u>The Ultimate Guide to Conquering Win Errors</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-purr-fect-tone-simulation-for-2024/"><u>New Purr-Fect Tone Simulation for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-pictures-from-honor-v-purse-by-fonelab-android-recover-pictures/"><u>Possible solutions to restore deleted pictures from Honor V Purse.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricks-for-rapid-download-experience-at-ms-store/"><u>Tricks for Rapid Download Experience at MS Store</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-apple-iphone-15-pro-max-to-other-iphone-without-icloud-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer Photos from Apple iPhone 15 Pro Max to other iPhone without iCloud | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-hidden-pin-removal-switch-in-windows-11/"><u>Unlocking Hidden Pin Removal Switch in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-0x8024800c-in-windows-update/"><u>Steps to Resolve 0X8024800C in Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/telnet-integration-in-modern-windows-11/"><u>Telnet Integration in Modern Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-methodology-for-windows-update-reset/"><u>Stepwise Methodology for Windows Update Reset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-valorant-microphone-failures-on-windows-10/"><u>Overcoming Valorant Microphone Failures on Windows 10</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-boost-interaction-on-your-tiktok-with-these-5-innovative-caption-methods/"><u>[Updated] In 2024, Boost Interaction on Your TikTok with These 5 Innovative Caption Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-new-waves-in-windows-unlocking-vivetools-secrets/"><u>Navigating New Waves in Windows: Unlocking ViVeTool's Secrets</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-essential-guide-to-documenting-macs-roblox-playthroughs-for-2024/"><u>[Updated] Essential Guide to Documenting Mac's Roblox Playthroughs for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-banish-buffering-repair-facebook-videos-on-phonestablets/"><u>2024 Approved  Banish Buffering – Repair Facebook Videos on Phones/Tablets</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-practical-technique-swap-film-direction-in-vlc-player/"><u>[New] Practical Technique  Swap Film Direction in VLC Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-microsoft-store-blockage-issue-on-win11/"><u>Resolving Microsoft Store Blockage Issue on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-unidentified-window-second-screen/"><u>Resolving Unidentified Window Second Screen</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-step-by-step-screen-recording-snapshots-on-mobile-for-2024/"><u>[Updated] Step-by-Step Screen Recording Snapshots on Mobile for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-10-visionary-beauty-experts-leading-online-trends/"><u>[New] In 2024, 10 Visionary Beauty Experts Leading Online Trends</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/efficient-methods-to-use-the-recording-app-on-samsung-s10s9-phones-for-2024/"><u>Efficient Methods to Use the Recording App on Samsung S10/S9 Phones for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essentials-of-epic-data-preservation-techniques/"><u>The Essentials of Epic Data Preservation Techniques</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-art-of-sound-transition-in-logic-pro-x/"><u>[New] The Art of Sound Transition in Logic Pro X</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-your-step-by-step-guide-to-successful-lol-streaming/"><u>2024 Approved  Your Step-by-Step Guide to Successful LOL Streaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-unseen-resurrect-off-screen-windows-in-win1011/"><u>Unlock the Unseen: Resurrect Off-Screen Windows in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-secrets-efficient-qr-codes-on-windows-systems/"><u>Unlocking Secrets: Efficient QR Codes on Windows Systems</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-samsung-galaxy-m34-drfone-by-drfone-virtual-android/"><u>How to Change Netflix Location to Get More Country Version On Samsung Galaxy M34 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/bypassreset-samsung-galaxy-a05s-phone-screen-passcodepatternpin-by-drfone-android-unlock-android-unlock/"><u>Bypass/Reset Samsung Galaxy A05s Phone Screen Passcode/Pattern/Pin</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reboot-the-process-solving-hidden-logins-on-windows-11/"><u>Reboot the Process: Solving Hidden Logins on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-selectivity-enable-checkbox-file-option-in-win11/"><u>Perfecting Selectivity: Enable Checkbox File Option in Win11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-free-versatile-tools-for-amateurs-and-professionals-in-ar/"><u>2024 Approved  Free, Versatile Tools for Amateurs & Professionals in AR</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/up-your-viewership-with-these-proven-methods-for-2024/"><u>Pump Up Your Viewership with These Proven Methods for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-the-insiders-guide-to-tiktok-on-apple-and-windows-systems/"><u>[New] In 2024, The Insider's Guide to TikTok on Apple and Windows Systems</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-mastery-in-video-handling-with-microsoft-hubs-for-2024/"><u>[Updated] Mastery in Video Handling with Microsoft Hubs for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-from-click-to-view-the-art-of-creating-effective-youtube-thumbnails-size-design-and-more/"><u>New In 2024, From Click to View The Art of Creating Effective YouTube Thumbnails (Size, Design, and More)</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-harmonizing-hits-the-best-melodies-to-complement-cinematic-short-films-and-videos/"><u>Updated 2024 Approved Harmonizing Hits The Best Melodies to Complement Cinematic Short Films and Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-comics-an-intuitive-approach-for-win11-users/"><u>Navigating Comics: An Intuitive Approach for Win11 Users</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-superior-budget-friendly-cam-viewer/"><u>[New] In 2024, Superior Budget-Friendly Cam Viewer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-windows-11-keyboard-shortcuts-next-to-power-icon/"><u>Tailoring Windows 11: Keyboard Shortcuts Next to Power Icon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-win11-space-to-perfection/"><u>Tailoring Your Win11 Space to Perfection</u></a></li>
</ul></div>
