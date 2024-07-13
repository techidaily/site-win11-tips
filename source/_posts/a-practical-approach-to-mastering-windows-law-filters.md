---
title: A Practical Approach to Mastering Windows LAW Filters
date: 2024-07-12T17:50:11.538Z
updated: 2024-07-13T17:50:11.538Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Practical Approach to Mastering Windows LAW Filters
excerpt: This Article Describes A Practical Approach to Mastering Windows LAW Filters
keywords: Laws Filter Guide,Windows Law Tools,LAW Filter Tutorial,Mastering Window Filters,Legal Aid Filters,LAW Software Tricks,Filter Techniques Win
thumbnail: https://thmb.techidaily.com/48eb4fc0f083727828418817e7d3c53949a229ffb44504b07d25f967a878becd.png
---

## A Practical Approach to Mastering Windows LAW Filters

 Some media players come with them since their creators realize there's no reason to reinvent the wheel. But you can also download them as a standalone solution and install them yourself.

 The result will be broader and better compatibility with most major video and audio formats, increased control over the playback process, and an improved audiovisual experience.

 They're known as "LAV filters" and are a popular and free way to improve your computer's media playback capabilities. Here's a quick guide on how to use them.

## What Are LAV Filters?

 LAV Filters are DirectShow filters that act as alternative decoders of audio and video streams for media players like MediaPlayer Classic Home Cinema (MPC-HC).

 Compatible with many formats, from MP4 to MKV and AAC to FLAC, they are highly configurable and come with various options for adjusting output to better match your equipment.

 The best part is that these open-source filters are regularly updated, making them problem-free, ever-evolving, and quick to adopt new features.

## How to Install LAV Filters for Use With Your Media Player

 Most modern media players come with options to replace their default decoding with LAV filters. MPC-HC has the LAV filters built-in. Other players can "collaborate" with LAV filters if you install them manually.

 If you're using a newer version of MPC-HC, you can skip this section and proceed to configure LAV Filters. For other media players, install LAV Filters like this:

1. Download their installer from [LAV Filters' Github page](https://github.com/Nevcairiel/LAVFilters/releases) .  
![LAV Filters Github Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-github-page.jpg)
2. Execute the downloaded installer and leave the default**Destination Location** as is.  
![LAV Filters Installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-installer.jpg)
3. Make sure all components are marked for installation on the installer's**Select Components** page. Skip**H.264 MVC 3D Decoder** if you don't have a 3D-capable display.  
![LAV Filters Installation Components Selection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-installation-components-selection.jpg)
4. Leave the rest of the options as they are and hit**Next** until you reach the**Completing the LAV Filters Setup Wizard** page.
5. Place a checkmark on all three**Open LAV X Configuration** , where "X" is Splitter, Audio, and Video.  
![LAV Filters Setup Completion Open Configuration Panels](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-setup-completion-open-configuration-panels.jpg)

 Although MPC-HC already comes with LAV filters, we're also using it in the following example to keep things simple. However, we made the steps "generic enough" to show you how to add LAV filter functionality to any media player that supports external filters, like PotPlayer.

1. Run your media player of choice and visit its**Options** ,**Settings** , or**Preferences** page. From there, locate its Filters (for example, in PotPlayer, you'll find them under the**Filter Control** sub-page of the app's options).
2. Disable**all** internal filters/methods related to "splitting" or "demuxing" files, audio, and video.  
![MPC HC Internal Filters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mpc-hc-internal-filters.jpg)
3. Move to your media player's option page about "external filters" and select that you want to**Add** (a)**Filter** .  
![MPC HC External Filters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mpc-hc-external-filters.jpg)
4. Choose all four entries related to the LAV Filters:**LAV Splitter** ,**LAV Splitter Source** ,**LAV Audio Decoder** , and**LAV Video Decoder** . You'll probably have to add them one by one.  
![MPC HC Adding External Filters LAV Filters Selection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mpc-hc-adding-external-filters-lav-filters-selection.jpg)
5. Depending on your media player, ensure they also appear in that order (for example, PotPlayer offers extra up/down buttons for re-arranging them) and are enabled/have a checkmark next to them (PotPlayer) or are set to**Prefer** (old versions of MPC-HC).  
![MPC HC External Filters Prefer Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mpc-hc-external-filters-prefer-option.jpg)
6. On PotPlayer, you'll also have to enable all formats for them when adding them from the**Source/Splitter** \>**Filter Management** panel. Click on each of the LAV filters and then enable the appropriate formats for it - file formats for the two**Splitters** , audio formats for the**Audio Decoder** , and video formats for the**Video Decoder** . Then, move to each**Filter Control** sub-section, like**Video Decoder** and**Audio Decoder** , and ensure the LAV filters are set as the default for all formats.
7. After a click on**OK** to close your media player's settings window, LAV Filters should have replaced its internal media-splitting and decoding functions. Close and re-run the app to ensure all changes have been applied.

## How to Configure LAV Filters for Your Media & Hardware

 You can configure the LAV filters from their entries in the Start menu. Click on the**Start** button or press the**Windows Key** on your keyboard. Then, type "LAV Filters" to locate them, and "run" each filter's configuration panel.

 In the last versions of MPC-HC, where the LAV filters are "baked-in", you can move to the app's**Options** and, from there, to the**Internal Filters** section. At the bottom of the page, you'll see three entries under**Internal LAV Filters settings** .

![MPC HC Internal LAV Filters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mpc-hc-internal-lav-filters.jpg)

 Click on each to access the settings panel for the**Splitter** ,**Video decoder** , and**Audio decoder** LAV filters, respectively.

1. For the LAV Splitter, you can leave most options as they are. To have it auto-select your preferred language for audio and subtitles, enter its shortcode (like "en" for English) in the fields under**Audio** and**Subtitles** . Place a checkmark on**Enable System Tray Icon** on the bottom left of the window to have the LAV Splitter filter's options easily accessible from the Windows tray.  
![LAV Filters Splitter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-splitter.jpg)
2. For the**Audio Decoder** settings, if the "audio gear" where your PC "sends" its audio (headphones, speakers, monitor) can decode digital streams, enable the appropriate formats under**Bitstreaming** . We can't offer suggestions on how to do that since different audio equipment requires different settings. Leave**Fallback to PCM if Bitstreaming is not supported** so that if your audio gear can't play the above formats, you'll still hear audio.  
![LAV Filters Audio Bitstreaming](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-audio-bitstreaming.jpg)
3. If you're using a multi-speaker setup, monophonic streams will only play from a single speaker by default. If you'd prefer the classic approach of "expanding" the mono stream to two stereo speakers, enable**Expand Mono to Stereo** . We'd suggest you also enable**Expand 6.1 to 7.1** if you use a 7.1 speaker setup with your PC.
4. The next option,**Use Legacy 5.1 Channel Layout** , may be helpful if your speakers go haywire while playing 5.1 audio and you don't hear "properly placed" positional audio. If you don't know what to choose, and only know "you've got a bunch of speakers", check out our guide on [how to understand surround sound systems for beginners](https://www.makeuseof.com/understanding-surround-sound-systems/) .  
![LAV Filters Audio Expand Mono to Stereo](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-audio-expand-mono-to-stereo.jpg)
5. Make sure to also place a checkmark on**Enable System Tray Icon** for LAV Filters' Audio Decoder. Then, move to the**Mixing** tab.  
![LAV Filters Audio Enable System Tray Icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-audio-enable-system-tray-icon.jpg)
6. If you play a lot of audio that doesn't match your sound output setup, for example, watching old movies with stereo sound on a 5.1 speaker setup, you can have LAV Filters upmix or downmix the sound to "morph" it for your audio gear. Place a checkmark before**Enable Mixing** and choose your speaker setup from the drop-down menu next to**Output Speaker Configuration** . You can also individually configure the sound levels for the center speaker, behind left and right speakers, and subwoofer (LFE).  
![LAV Filters Audio Mixing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-audio-mixing.jpg)
7. If you use the same media player for listening to music, you might want to ensure stereo sources (like most of your beloved music) will remain untouched (and "untainted") from any mixing shenanigans. For that, enable the option**Don't mix Stereo Sources** on the top right of this panel. Click**OK** to accept and save the changes.  
![LAV Filters Audio Dont Mix Stereo Sources](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-audio-dont-mix-stereo-sources.jpg)
8. Finally, for the video settings, choose the best hardware decoder for your GPU under**Hardware Acceleration** . At the time of writing (beginning of 2023),**DXVA2** and**CUVID** are better on Nvidia GPUs, while**D3D11** may work best on AMD's offerings. It's also worth trying those options out on newer Intel Arc GPUs since they use a different decoding engine than the one for which the option**Intel(R) QuickSync (old)** was built.  
![LAV Filters Video Hardware Acceleration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-video-hardware-acceleration.jpg)
9. Remember the option**Enable System Tray Icon** here, too. After enabling it, click**OK** to save the changes and close the last LAV Filters configuration panel.  
![LAV Filters Video Enable System Tray Icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-video-enable-system-tray-icon.jpg)

 Although your videos will play perfectly with LAV filters, if you try to grab some screenshots of your favorite scenes, they might appear blurry. Thankfully, we have a guide on [how to save frame-perfect video screenshots on Windows using a media player](https://www.makeuseof.com/windows-media-player-frame-perfect-screenshot/) that can help you solve this problem, too.

## Achieve Optimal Playback With LAV Filters

 After making sure to close and re-run your media player, LAV Filters should be installed, configured, and ready to go. Try playing some media as usual, and you should see the LAV Filters' icons pop up on the Windows tray.

 More importantly, you should see an improvement compared to your media player's native decoding, smoother playback, and possibly lower CPU utilization!


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
<li><a href="https://win11-tips.techidaily.com/swift-solutions-to-fixed-windows-itunes-applications/"><u>Swift Solutions to Fixed Windows iTunes Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-non-working-activation-codes-in-win11/"><u>Solutions for Non-Working Activation Codes in Win11</u></a></li>
<li><a href="https://android-frp.techidaily.com/the-complete-guide-to-htc-u23-pro-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to HTC U23 Pro FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-controlling-sounds-on-windows-11/"><u>The Ultimate Guide to Controlling Sounds on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-enable-photo-viewer-window/"><u>Step-by-Step: Enable Photo Viewer Window</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-80plus-catchy-cooking-channel-names-to-attract-more-audience-for-2024/"><u>[Updated] 80+ Catchy Cooking Channel Names to Attract More Audience for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-avoid-dark-screen-while-playing-winos-titles/"><u>Tips to Avoid Dark Screen While Playing WINOS Titles</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-mastering-snapchat-three-simple-steps-for-calls-and-chats/"><u>[New] 2024 Approved  Mastering Snapchat  Three Simple Steps for Calls and Chats</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-top-3-techniques-for-capturing-sports-spectacles/"><u>2024 Approved  Top 3 Techniques for Capturing Sports Spectacles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-flawless-gameplay-combat-apex-legends-freezes/"><u>Unleash Flawless Gameplay: Combat Apex Legends Freezes</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-get-started-with-video-editing-top-free-options-for-desktop-online-and-mobile/"><u>Updated In 2024, Get Started with Video Editing Top Free Options for Desktop, Online, and Mobile</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-implementation-of-updater-in-win11-version-22h2/"><u>Seamless Implementation of Updater in WIN11 Version 22H2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-to-address-retrieve-settings-error-on-winx/"><u>Quick Steps to Address Retrieve Settings Error on WinX</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-ultimate-list-the-top-10-thrilling-action-packed-games/"><u>[Updated] Ultimate List  The Top 10 Thrilling Action-Packed Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solution-regain-shared-resources-access/"><u>Swift Solution: Regain Shared Resources Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-mechanism-behind-windows-sound-graph-isolation/"><u>The Mechanism Behind Windows Sound Graph Isolation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-remedying-full-screen-troubles-in-sonic-games/"><u>Understanding and Remedying Full-Screen Troubles in Sonic Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-enabling-task-managers-quick-find-feature-on-win11/"><u>Step-by-Step Guide: Enabling Task Manager's Quick Find Feature on Win11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-elevate-your-video-game-on-instagram-with-right-dimensions/"><u>In 2024, Elevate Your Video Game on Instagram with Right Dimensions</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastering-googles-text-conversion-service-a-detailed-walkthrough-for-2024/"><u>Mastering Google's Text Conversion Service  A Detailed Walkthrough for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-win-11-taskbar-power/"><u>The Ultimate Guide to Win 11 Taskbar Power</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-unlocking-windows-11/"><u>Quick Guide: Unlocking Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/finding-and-exploring-your-own-music-selection-zone-on-youtube/"><u>Finding and Exploring Your Own Music Selection Zone on Youtube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/santas-digital-deliveries-via-microsoft-marketplace/"><u>Santa's Digital Deliveries via Microsoft Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-a-non-responsive-mouse-on-windows-computers/"><u>Resurrecting a Non-Responsive Mouse on Windows Computers</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-in-2024-best-10-tikfilters-for-viral-video-success/"><u>[Updated] In 2024, Best 10 TikFilters for Viral Video Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-mouse-gurus-autoclick-wonders-on-windows-pcs/"><u>Top 5 Mouse Gurus: Autoclick Wonders on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11s-gpo-settings-quickly/"><u>Unlocking Windows 11'S GPO Settings Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninstalling-microsoft-edge-from-windows-11/"><u>Uninstalling Microsoft Edge From Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-0x80072af9-failure/"><u>Unraveling the Mystery of 0X80072AF9 Failure</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-xiaomi-redmi-note-12-pro-5g-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Xiaomi Redmi Note 12 Pro 5G without App | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/screen-sharing-not-working-in-microsoft-teams-for-windows-try-these-fixes/"><u>Screen Sharing Not Working in Microsoft Teams for Windows? Try These Fixes</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-the-3-elemental-strategies-for-writing-effective-social-media-promotions-for-2024/"><u>[Updated] The 3 Elemental Strategies for Writing Effective Social Media Promotions for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-leading-edge-techniques-for-video-based-seminars/"><u>In 2024, Leading Edge Techniques for Video-Based Seminars</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-odins-progeny-clash-of-titans/"><u>[New] Odin’s Progeny  Clash of Titans</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-templates-increase-the-editing-possibilities-for-beginners-and-professionals-read-this-article-to-learn-about-some-customizable-slow-motio/"><u>New 2024 Approved Templates Increase the Editing Possibilities for Beginners and Professionals. Read This Article to Learn About some Customizable Slow-Motion CapCut Templates</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-visualize-your-movies-with-best-grabbers/"><u>[Updated] 2024 Approved  Visualize Your Movies with Best Grabbers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/new-windows-11-users-beware-of-these-top-8-errors/"><u>New Windows 11 Users, Beware of These Top 8 Errors!</u></a></li>
</ul></div>
