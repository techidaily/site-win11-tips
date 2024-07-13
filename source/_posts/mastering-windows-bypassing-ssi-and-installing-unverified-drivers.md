---
title: "Mastering Windows: Bypassing SSI & Installing Unverified Drivers"
date: 2024-07-12T16:50:17.065Z
updated: 2024-07-13T16:50:17.065Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Windows: Bypassing SSI & Installing Unverified Drivers"
excerpt: "This Article Describes Mastering Windows: Bypassing SSI & Installing Unverified Drivers"
keywords: Bypass SSID,Unverified Drivers,Windows Modification,Driver Installer,OS Hacking,SSI Bypass Method,Unauthorized Update
thumbnail: https://thmb.techidaily.com/36f59289f42403367e98ee01ecd7f903ee9a9399b65951332a255432e2acfb47.jpg
---

## Mastering Windows: Bypassing SSI & Installing Unverified Drivers

 Sometimes, Windows will block you from installing an unsigned driver, which is a driver you've downloaded elsewhere other than through a Windows Update or the device manufacturer's website. But if you need the driver, and you know it is perfectly safe, you can turn off driver signature enforcement and let it through.

 In this guide, we're going to show you several ways to do it.

## How to Disable Driver Signature Enforcement in the Startup Settings

 A temporary way to disable driver signature enforcement is through Startup Settings, allowing you to install the unsigned drivers. However, the moment you restart your PC, Windows will re-enable driver signature enforcement. The unsigned drivers you've installed will still work, but you may not be able to install new ones.

 To disable driver signature enforcement this way, you'll have to [access the Startup Settings screen](https://www.makeuseof.com/windows-startup-settings/). The **Disable driver signature enforcement** option will be the seventh one, so press **F7** or **7** on your keyboard to select it.

![windows 11 startup settings safe mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-startup-settings-safe-mode.jpg)

 Your computer will then restart, and when it reboots, you'll be able to install those unsigned drivers.

## How to Disable Driver Signature Enforcement in the Local Group Policy Editor

 You can also disable driver signature enforcement by tweaking the **Code signing for driver packages** policy in the Local Group Policy Editor (LGPE). Doing this will allow you to install unsigned drivers even if you restart your computer.

 Unfortunately, you can only natively access the LGPE if you're on Windows Pro or Enterprise Edition. However, there is a way to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

1. Press **Win + S** to bring up Windows Search, enter **group policy** in the Search box, and select **Edit group policy** in the Search results.  
![Open Group Policy Editor Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-group-policy-editor-using-windows-search.jpg)
2. Once the LGPE opens up, head to **User Configuration > Administrative Templates > System > Driver Installation**.
3. Right-click **Code signing for driver packages** and select **Edit**.  
![editing the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-the-code-signing-for-driver-packages-policy.jpg)
4. Click the **Enabled** radio button, and then, in the **Options** section, click on the dropdown and select **Ignore**.  
![enabling the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/enabling-the-code-signing-for-driver-packages-policy.jpg)
5. Click on **OK**.

 If you want to enable driver signature enforcement again, go back to step #4 and set the radio button to **Not configured**.

## How to Disable Driver Signature Enforcement in PowerShell

 Another way to disable driver signature enforcement is by running the command to turn off integrity checks in PowerShell (you'll have to run it as an administrator). And just like with the Local Group Policy Editor, it will remain disabled until you enable it again.

 Follow the steps below to turn off driver signature enforcement in PowerShell:

 You can disable driver signature enforcement by [opening Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) if you prefer it over PowerShell.

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set nointegritychecks on** and paste it into PowerShell.  
![turning off driver signature enforcement in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-off-driver-signature-enforcement-in-terminal.jpg)
4. Hit **Enter** to run the command.

 To turn on driver signature enforcement again, replace the command in step #3 with **bcdedit /set nointegritychecks off**.

 One potential problem you can run into when trying to turn off driver signature enforcement this way is an error stating **The value is protected by Secure Boot policy and cannot be modified or deleted**.

![Secure Boot error in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/secure-boot-error-powershell.jpg)

 If that is the case, you can try [turning off Secure Boot](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) and trying again. But if you don't want to do this, using Startup Settings and the Local Group Policy Editor is perfectly okay.

 You can also put Windows in test mode, which disables driver signature enforcement, allowing you to install those unsigned drivers. To enter test mode, follow the steps below (keep in mind that you may run into the Secure Boot error):

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set testsigning on** and paste it into PowerShell.  
![turning on Test Mode in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-on-test-mode-in-terminal.jpg)
4. Hit **Enter** to run the command.

 Now restart your computer, and when it boots back up, it will be in test mode. After you're done installing those drivers, don't forget to disable test mode. The command to do that is **bcdedit /set testsigning off**.

## Now You Can Install Unsigned Drivers on Windows

 Installing unsigned drivers on Windows is not recommended, since they can lead to unexpected behavior. However, if you trust the driver, there's no reason why the OS should block you from installing it. Just use one of the methods mentioned above, and you should be able to install and use unsigned drivers on your Windows PC.

 In this guide, we're going to show you several ways to do it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/windows-transcends-platforms-iphoneipadmacpc-compatibility-announced/"><u>Windows Transcends Platforms: IPhone/iPad/Mac/PC Compatibility Announced</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-11-writable-memory-protection/"><u>Correcting Windows 11' Writable Memory Protection</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-mastering-the-art-of-iphoneipad-video-logging/"><u>[Updated] Mastering the Art of iPhone/iPad Video Logging</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-how-to-use-luts-in-lumafusion-and-free-resource/"><u>2024 Approved How to Use LUTs in Lumafusion & Free Resource</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-10-step-roadmap-to-winrm/"><u>Unraveling the 10-Step Roadmap to WinRM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-fixing-excel-notation-on-notepad/"><u>Guide: Fixing Excel Notation on Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-yuzu-game-performance-in-windows/"><u>Boosting Yuzu Game Performance in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-reasons-to-choose-win11-over-apples-macos/"><u>Top Reasons to Choose Win11 Over Apple's macOS</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/the-youtube-makeup-craft-color-correction-essentials/"><u>The YouTube Makeup Craft  Color Correction Essentials</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/rt-of-attraction-mastering-youtubes-glamour-trove/"><u>The Art of Attraction  Mastering Youtube's Glamour Trove</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-your-windows-devices-microsoft-store-error-code-x800704cf/"><u>Unlocking Your Windows Devices: Microsoft Store Error Code X800704CF</u></a></li>
<li><a href="https://extra-tips.techidaily.com/holiday-memories-revisited-summertimes-best-vacation-flicks/"><u>Holiday Memories Revisited  Summertime’s Best Vacation Flicks</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-instant-access-windows-photos-view/"><u>[New] Instant Access Windows Photos View</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-fixing-microsoft-store-error-0x80073cf3-in-win11/"><u>Guidelines for Fixing Microsoft Store Error 0X80073CF3 in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-resolving-battlenet-not-available-errors-on-win-1011/"><u>Tips for Resolving Battle.net Not Available Errors on Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cut-the-words-start-talking-windows-11s-method/"><u>Cut the Words, Start Talking: Windows 11'S Method</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-reclaim-the-loss-10-essential-iphone-x-techniques/"><u>[New] Reclaim The Loss  10 Essential iPhone X Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/flattening-the-cornered-look-of-win11/"><u>Flattening the Cornered Look of Win11</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-content-strategy-mastery-selecting-top-rank-trackers-uncovered/"><u>[New] 2024 Approved  Content Strategy Mastery - Selecting Top Rank Trackers Uncovered</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-secure-boot-status-a-windows-bios-solution-manual/"><u>Unlocking Secure Boot Status: A Windows BIOS Solution Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/devhome-explained-mastering-windows-11-upgrades/"><u>DevHome Explained: Mastering Windows 11 Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decrypting-windows-108-error-messages-locations/"><u>Decrypting Windows 10/8 Error Messages Locations</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-create-stunning-videos-add-slow-motion-effects-at-no-cost-with-filmora-for-2024/"><u>New Create Stunning Videos Add Slow Motion Effects at No Cost with Filmora for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-nokia-c22-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Nokia C22 | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-expert-choices-top-browsers-to-capture-your-digital-experience/"><u>[Updated] 2024 Approved  Expert Choices  Top Browsers to Capture Your Digital Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharge-windows-11-boot-speed-heres-how/"><u>Turbocharge Windows 11 Boot Speed – Here’s How</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/ultimate-tutorial-posting-youtube-videos-on-fb/"><u>Ultimate Tutorial  Posting YouTube Videos on FB</u></a></li>
<li><a href="https://techidaily.com/why-can-t-i-play-mp4-files-on-my-motorola-edgeplus-2023-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Why can’t I play MP4 files on my Motorola Edge+ (2023)?</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/excellence-in-video-capture-2024s-top-picks/"><u>Excellence in Video Capture  2024'S Top Picks</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-navigating-regulatory-challenges-in-todays-complex-markets/"><u>[New] Navigating Regulatory Challenges in Today's Complex Markets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-non-loading-messages-in-windows-discord-client/"><u>Correcting Non-Loading Messages in Windows Discord Client</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cut-down-installation-time-with-proper-deps-setup/"><u>Cut Down Installation Time with Proper Deps Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-2023-laptop-reveals-ifa-edition/"><u>Top 2023 Laptop Reveals - IFA Edition</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-unleashing-the-power-of-social-proof-tips-to-amplify-brand-visibility/"><u>In 2024, Unleashing the Power of Social Proof  Tips to Amplify Brand Visibility</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-quick-guide-to-insta-influence-mastery-for-2024/"><u>[Updated] Quick Guide to Insta-Influence Mastery for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-breaking-free-from-windows-movie-maker-top-alternatives-for-2024/"><u>New Breaking Free From Windows Movie Maker Top Alternatives for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-get-instant-twitter-video-dimensions-aspect-ratio-insights-for-2024/"><u>New Get Instant Twitter Video Dimensions Aspect Ratio Insights for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-vivo-v29e-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Vivo V29e? | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-10-free-online-mp3-to-text-converters-wondershare-filmora/"><u>Updated 10 FREE Online MP3 to Text Converters-Wondershare Filmora</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-top-30-boosting-bots-for-enhanced-discord-servers-for-2024/"><u>[New] Top 30 Boosting Bots for Enhanced Discord Servers for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/audio-endings-how-to-decrease-volume-gradually-in-pp-for-2024/"><u>Audio Endings  How to Decrease Volume Gradually in PP for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-network-disruption-unraveling-0x800704b3-code/"><u>Fixing Network Disruption - Unraveling 0X800704B3 Code</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-error-code-0x80070141-making-unreachable-devices-connectable/"><u>Eliminating Error Code 0X80070141: Making Unreachable Devices Connectable</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-expand-your-horizon-best-15-online-science-platforms/"><u>[Updated] Expand Your Horizon  Best 15 Online Science Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-current-frames-crafting-future-windows/"><u>Beyond Current Frames: Crafting Future Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/converting-gmail-to-outlook-on-windows-a-step-by-step-guide/"><u>Converting Gmail To Outlook on Windows – A Step-by-Step Guide</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-vivo-y100-5g-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Vivo Y100 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-disabled-internet-router-configuration/"><u>Fixing Disabled Internet Router Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-default-silence-camera-activation-in-win11/"><u>Breaking the Default Silence: Camera Activation in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-deadly-error-0x8007045d-on-windows-pcs/"><u>Eliminating Deadly Error: 0X8007045D on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/auto-shutdown-mastery-for-idle-pcs-in-w10w11/"><u>Auto Shutdown Mastery for Idle PCs in W10/W11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/the-ultimate-guide-to-excellence-in-english-via-mondly/"><u>The Ultimate Guide to Excellence in English via Mondly</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-oppo-find-n3-flip-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Oppo Find N3 Flip without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-refine-your-beauty-videos-with-youtubes-palette-tweaking/"><u>[Updated] Refine Your Beauty Videos with Youtube's Palette Tweaking</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-ace-your-shots-top-cameras-and-lenses-for-youtubers-for-2024/"><u>[Updated] Ace Your Shots  Top Cameras & Lenses for YouTubers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-fix-for-winerror-0x80072746-in-outlook/"><u>The Ultimate Fix for WinError 0X80072746 in Outlook</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-tecno-pop-7-pro-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Tecno Pop 7 Pro without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-insights-into-windowsstore-accessibility-guide/"><u>Essential Insights Into WindowsStore Accessibility Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-winrars-summation-missteps-with-6-fixes/"><u>Combatting WinRAR's Summation Missteps with 6 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-security-enlarge-pins-best-practices-in-windows-1111/"><u>Boost Security, Enlarge Pins: Best Practices in Windows 11/11</u></a></li>
</ul></div>
