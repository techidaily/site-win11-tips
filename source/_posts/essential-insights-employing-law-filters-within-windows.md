---
title: "Essential Insights: Employing LAW Filters Within Windows"
date: 2024-06-25T16:18:28.602Z
updated: 2024-06-26T16:18:28.602Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Essential Insights: Employing LAW Filters Within Windows"
excerpt: "This Article Describes Essential Insights: Employing LAW Filters Within Windows"
keywords: Law Filter Guide,Windows Law Tools,LAW Filter Techniques,Legal Filters Windows,Compliance Windows Filter,Intrusion Prevention LAW,Enhanced Security Filters
thumbnail: https://thmb.techidaily.com/43d04728eb067b27b181109747aeff382529cf3d84fbfcf0819906ab437cf25f.jpg
---

## Essential Insights: Employing LAW Filters Within Windows

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
<li><a href="https://win11-tips.techidaily.com/should-you-block-yourphoneexe-on-home-editions/"><u>Should You Block YourPhone.exe on Home Editions?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-unreachable-mb-status-on-windows-11-systems/"><u>Tackling Unreachable MB Status on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slash-excess-usage-enhancing-efficiency-for-news-in-windows-1011/"><u>Slash Excess Usage: Enhancing Efficiency for News in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-molds-changing-the-winadmin-access-paradigm/"><u>Breaking Molds: Changing the WinAdmin Access Paradigm</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-start-screen-links-in-win11s-options/"><u>Adjusting Start Screen Links in Win11's Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-blue-screen-recovery-steps/"><u>Mastering Windows 11 Blue Screen Recovery Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-digital-desktop-top-5-apps-for-customizable-clock-screen-savers-on-windows/"><u>Upgrade Your Digital Desktop: Top 5 Apps for Customizable Clock Screen Savers on Windows</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-free-and-open-source-audio-conversion-software-top-picks/"><u>Updated In 2024, Free and Open Source Audio Conversion Software Top Picks</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-vlc-recordings-tips-and-tricks/"><u>[Updated] In 2024, VLC Recordings  Tips and Tricks</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-gif-tempo-tweakers-online-ios-and-android-options/"><u>Updated GIF Tempo Tweakers Online, iOS, and Android Options</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-experience-engaged-youtube-exchanges-for-2024/"><u>[Updated] Experience Engaged YouTube Exchanges for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-nokia-c110-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Nokia C110? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-mov-files-of-honor-magic-vs-2-using-video-repair-utility-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and MOV files of Honor Magic Vs 2 using Video Repair Utility on Mac?</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-unlock-the-secret-of-social-media-impact/"><u>[Updated] In 2024, Unlock the Secret of Social Media Impact</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirror-on-apple-iphone-xr-drfone-by-drfone-ios/"><u>How to Screen Mirror on Apple iPhone XR? | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-30-cutting-edge-tiktok-profile-photo-ideas/"><u>[New] 30 Cutting-Edge TikTok Profile Photo Ideas</u></a></li>
</ul></div>
