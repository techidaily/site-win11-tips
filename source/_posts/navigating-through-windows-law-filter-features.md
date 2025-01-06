---
title: Navigating Through Windows LAW Filter Features
date: 2025-01-03T04:00:47.712Z
updated: 2025-01-05T19:14:16.637Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Through Windows LAW Filter Features
excerpt: This Article Describes Navigating Through Windows LAW Filter Features
keywords: Windows Legal Filters,Law Filter in Windows,LAW Filter Guide,Filtering Laws Windows,Window's Legal Features,LAW Filters Navigation,Understanding LAW Filters
thumbnail: https://thmb.techidaily.com/212e21d96bc4724d21a24c1110e599b63bc2c397e891bb1e1f9fc06be1f08b00.jpg
---

## Navigating Through Windows LAW Filter Features

 Some media players come with them since their creators realize there's no reason to reinvent the wheel. But you can also download them as a standalone solution and install them yourself.

 The result will be broader and better compatibility with most major video and audio formats, increased control over the playback process, and an improved audiovisual experience.

 They're known as "LAV filters" and are a popular and free way to improve your computer's media playback capabilities. Here's a quick guide on how to use them.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3UyJuZYzjt0?si=W87GeyzVKVORAk7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Are LAV Filters?

 LAV Filters are DirectShow filters that act as alternative decoders of audio and video streams for media players like MediaPlayer Classic Home Cinema (MPC-HC).

 Compatible with many formats, from MP4 to MKV and AAC to FLAC, they are highly configurable and come with various options for adjusting output to better match your equipment.

 The best part is that these open-source filters are regularly updated, making them problem-free, ever-evolving, and quick to adopt new features.

## How to Install LAV Filters for Use With Your Media Player

 Most modern media players come with options to replace their default decoding with LAV filters. MPC-HC has the LAV filters built-in. Other players can "collaborate" with LAV filters if you install them manually.

 If you're using a newer version of MPC-HC, you can skip this section and proceed to configure LAV Filters. For other media players, install LAV Filters like this:

1. Download their installer from[LAV Filters' Github page](https://github.com/Nevcairiel/LAVFilters/releases) .  
![LAV Filters Github Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-github-page.jpg)
2. Execute the downloaded installer and leave the default**Destination Location** as is.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![LAV Filters Installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-installer.jpg)
3. Make sure all components are marked for installation on the installer's**Select Components** page. Skip**H.264 MVC 3D Decoder** if you don't have a 3D-capable display.  
![LAV Filters Installation Components Selection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-installation-components-selection.jpg)
4. Leave the rest of the options as they are and hit**Next** until you reach the**Completing the LAV Filters Setup Wizard** page.
5. Place a checkmark on all three**Open LAV X Configuration** , where "X" is Splitter, Audio, and Video.  
![LAV Filters Setup Completion Open Configuration Panels](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-setup-completion-open-configuration-panels.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Although MPC-HC already comes with LAV filters, we're also using it in the following example to keep things simple. However, we made the steps "generic enough" to show you how to add LAV filter functionality to any media player that supports external filters, like PotPlayer.

1. Run your media player of choice and visit its**Options** ,**Settings** , or**Preferences** page. From there, locate its Filters (for example, in PotPlayer, you'll find them under the**Filter Control** sub-page of the app's options).
2. Disable**all** internal filters/methods related to "splitting" or "demuxing" files, audio, and video.  
![MPC HC Internal Filters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mpc-hc-internal-filters.jpg)
3. Move to your media player's option page about "external filters" and select that you want to**Add** (a)**Filter** .  
![MPC HC External Filters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mpc-hc-external-filters.jpg)
4. Choose all four entries related to the LAV Filters:**LAV Splitter** ,**LAV Splitter Source** ,**LAV Audio Decoder** , and**LAV Video Decoder** . You'll probably have to add them one by one.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
4. The next option,**Use Legacy 5.1 Channel Layout** , may be helpful if your speakers go haywire while playing 5.1 audio and you don't hear "properly placed" positional audio. If you don't know what to choose, and only know "you've got a bunch of speakers", check out our guide on[how to understand surround sound systems for beginners](https://www.makeuseof.com/understanding-surround-sound-systems/) .  
![LAV Filters Audio Expand Mono to Stereo](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-audio-expand-mono-to-stereo.jpg)
5. Make sure to also place a checkmark on**Enable System Tray Icon** for LAV Filters' Audio Decoder. Then, move to the**Mixing** tab.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![LAV Filters Audio Enable System Tray Icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-audio-enable-system-tray-icon.jpg)
6. If you play a lot of audio that doesn't match your sound output setup, for example, watching old movies with stereo sound on a 5.1 speaker setup, you can have LAV Filters upmix or downmix the sound to "morph" it for your audio gear. Place a checkmark before**Enable Mixing** and choose your speaker setup from the drop-down menu next to**Output Speaker Configuration** . You can also individually configure the sound levels for the center speaker, behind left and right speakers, and subwoofer (LFE).  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xtylXDY9YfA?si=VonzSiDFGCpJm2uC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![LAV Filters Audio Mixing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-audio-mixing.jpg)
7. If you use the same media player for listening to music, you might want to ensure stereo sources (like most of your beloved music) will remain untouched (and "untainted") from any mixing shenanigans. For that, enable the option**Don't mix Stereo Sources** on the top right of this panel. Click**OK** to accept and save the changes.  
![LAV Filters Audio Dont Mix Stereo Sources](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-audio-dont-mix-stereo-sources.jpg)
8. Finally, for the video settings, choose the best hardware decoder for your GPU under**Hardware Acceleration** . At the time of writing (beginning of 2023),**DXVA2** and**CUVID** are better on Nvidia GPUs, while**D3D11** may work best on AMD's offerings. It's also worth trying those options out on newer Intel Arc GPUs since they use a different decoding engine than the one for which the option**Intel(R) QuickSync (old)** was built.  
![LAV Filters Video Hardware Acceleration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-video-hardware-acceleration.jpg)
9. Remember the option**Enable System Tray Icon** here, too. After enabling it, click**OK** to save the changes and close the last LAV Filters configuration panel.  
![LAV Filters Video Enable System Tray Icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-video-enable-system-tray-icon.jpg)

 Although your videos will play perfectly with LAV filters, if you try to grab some screenshots of your favorite scenes, they might appear blurry. Thankfully, we have a guide on[how to save frame-perfect video screenshots on Windows using a media player](https://www.makeuseof.com/windows-media-player-frame-perfect-screenshot/) that can help you solve this problem, too.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://extra-tips.techidaily.com/new-beat-explorers-guide-online-pulse-sensors/"><u>[New] Beat Explorers’ Guide Online Pulse Sensors</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-exclusive-list-of-windows-10-recording-software/"><u>[Updated] Exclusive List of Windows 10 Recording Software</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-scriptwriting-mastery-elevate-your-youtube-channels-content-quality/"><u>2024 Approved Scriptwriting Mastery Elevate Your YouTube Channel's Content Quality</u></a></li>
<li><a href="https://android-unlock.techidaily.com/5-solutions-for-samsung-galaxy-xcover-6-pro-tactical-edition-unlock-without-password-by-drfone-android/"><u>5 Solutions For Samsung Galaxy XCover 6 Pro Tactical Edition Unlock Without Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/circumvent-windows-updates-error-code-0x80242016/"><u>Circumvent Windows Update's Error: Code 0X80242016</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-your-screen-setup-gmail-pinned-to-the-windows-edge/"><u>Customizing Your Screen Setup: Gmail Pinned to the Window's Edge</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-vivo-y200-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Vivo Y200 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-text-messages-from-samsung-galaxy-f54-5g-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Text Messages from Samsung Galaxy F54 5G to New Phone | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-ultimate-guide-on-oppo-k11x-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide on Oppo K11x FRP Bypass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-pc-management-leveraging-command-prompt-for-effective-identification-and-resolution-of-error-codes/"><u>Proactive PC Management: Leveraging Command Prompt for Effective Identification & Resolution of Error Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-lost-apps-reactivating-the-microsoft-store-windows-11/"><u>Revive Lost Apps: Reactivating the Microsoft Store (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-disk-management-techniques-for-windows-1011/"><u>Simplifying Disk Management: Techniques for Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-the-keys-how-to-fix-quieted-pc-sounds/"><u>Taming the Keys: How to Fix Quieted PC Sounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-windows-11-control-panel-is-missing-key-settings-heres-where-to-find-them/"><u>The Windows 11 Control Panel Is Missing Key Settings, Here's Where to Find Them</u></a></li>
<li><a href="https://change-location.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-vivo-y77t-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Vivo Y77t | Dr.fone</u></a></li>
</ul></div>

