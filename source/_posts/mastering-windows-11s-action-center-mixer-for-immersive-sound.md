---
title: Mastering Windows 11'S Action Center Mixer for Immersive Sound
date: 2024-12-20T08:25:01.624Z
updated: 2024-12-21T21:29:47.238Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Windows 11'S Action Center Mixer for Immersive Sound
excerpt: This Article Describes Mastering Windows 11'S Action Center Mixer for Immersive Sound
keywords: Win11SoundMixer,ActionCenterAudio,ImmersionSoundWin,AudioMixMasterWin,MixerWinAudioControl,Windows11ImmersiveSon,SonicWinActionCenter
thumbnail: https://thmb.techidaily.com/058506d9dfd3499ce050a0189a74f361c7f5cd9f1ab1cb47d3f2f93a3bce610c.jpg
---

## Mastering Windows 11'S Action Center Mixer for Immersive Sound

 Remember the old volume mixer which you could access from the system tray notifications? Windows 11 seems to be missing that ever since its release. When you click on the Volume icon in the Action Center, you only see an option to change the sound output device. There are no means to directly access the volume mixer from there. But Microsoft isn’t done with the volume settings on Windows 11.

 In a new experimental feature, Microsoft is revamping the sound settings in the Action Center. You will be able to switch output devices and adjust the volume of each of the apps listed in the Volume Mixer. Wondering how to get the feature on your system? Here's how.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Do You Need a Volume Mixer in Action Center?

 The present state of volume settings in Windows 11 is quite lackluster. You can only adjust the volume of the system and cycle between multiple audio devices. For opening any other settings, even something as trivial as a volume mixer: you need to dive deep into system sound settings.

 It is baffling how Microsoft missed something so crucial in Windows 11\. These missing volume settings gave rise to apps like[EarTrumpet](https://apps.microsoft.com/store/detail/9NBLGGH516XP?hl=en-us&gl=US&ranMID=24542&ranEAID=nOD%2FrLJHOac&ranSiteID=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&epi=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&activetab=pivot%3Aoverviewtab&ranMID=43674&ranEAID=RIg0ReKk7DI&ranSiteID=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&epi=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&irgwc=1&OCID=AID2200057%5Faff%5F7795%5F1243925&tduid=%28ir%5F%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00%29%287795%29%281243925%29%28RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ%29%28%29&irclickid=%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00) which offered rich sound customization settings. Along with that, you can even access the old volume mixers, adjust the sound levels of each app, and map shortcuts.

![Old Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/old-volume-settings-in-action-center.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 However, Microsoft is slowly identifying such missing features in Windows 11 and is adding an inbuilt solution for it. Recently,[Microsoft began testing an RGB lighting feature](https://www.makeuseof.com/enable-rgb-lighting-controls-windows-11/) that will eliminate the need for third-party customization apps. So, it is pretty clear that Microsoft wants to reduce the reliance on third-party apps for vital system features and tweaks.

## How to Enable the Volume Mixer in Windows 11's Action Center

 To enable the volume mixer in Windows 11, you will need to do the following:

### 1\. Download the Latest Windows Insider Build and ViVeTool

 Currently, the volume mixer feature is an experimental feature hidden in Windows Insider build 25295\. So, you must install this Windows Insider build or a higher version to enable this feature. We recommend[using UUP Dump to download Windows Insider builds without subscribing to Windows Insider](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

 Microsoft recently expanded the Insider program with a new Canary channel, and it makes it difficult to downgrade to another channel. So, you can use UPP Dump to avoid this program and get builds directly.

 You will also need to download[ViVeTool from GitHub](https://github.com/thebookisclosed/ViVe/releases) to enable the experimental volume mixer feature. It is a command-line tool that can both activate and deactivate experimental Windows features. However, extract the tool to an easily accessible location in the C drive.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Enable Volume Mixer in Windows Using ViVeTool

After you have the ViVeTool ready, repeat the following steps:

1. Press the**Win** key to open the Start menu. Type**cmd** and press the**Ctrl + Shift + Enter** key.
2. UAC will pop up. Click on the**Yes** button to[open the Command Prompt with administrator privileges](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
3. Now, you need to navigate to the location where the ViVeTool folder exists. We extracted the tool to a folder named ViVeTool in**C** drive for easy access, and suggest you do the same. Otherwise, you have to change the directory multiple time to get to the tool’s folder.
4. Type the**cd C:\\** command and press the enter key to go to the main C drive directory.
5. After that, type**cd ViVeTool** command and press the enter key. Now, you are in the directory where ViVeTool executable file is present.
6. Type the following command and press the enter key to enable the hidden volume mixer:  
vivetool /enable /id:42106010
7. You will see a “**Successfully set feature configuration(s)** ” message. Type the**exit** command and press the enter key to close the command prompt window.  
![Enabling New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enabling-new-volume-settings-in-action-center.jpg)
8. Restart your system to allow the changes to take effect.
9. Log in and press**Win + A** to open Action Center. You will notice a new volume mixer icon next to the volume bar. Click on it to reveal the complete sound settings. Both the Spatial Audio and volume mixer will be present inside.  
![New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-volume-settings-in-action-center.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/97ydpSmzTJw?si=tFcelmtQX4u-b3u5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Adjust Your Volume Like A Pro on Windows 11

 Windows 11 uprooted a lot of useful settings and features. Users resorted to registry hacks and third-party programs to fix this issue. However, the new volume mixer attempts to fix that to some extent. Microsoft might improve the volume mixer further to overshadow apps like EarTrumpet, but that’s a very slim possibility.

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
<li><a href="https://eaxpv-info.techidaily.com/authentic-platinum-edition-dvd-ripping-tool-effortlessly-transform-your-dvd-media-into-mp4-h264hevc-format-in-half-an-hour-or-less/"><u>[Authentic] Platinum Edition DVD Ripping Tool – Effortlessly Transform Your DVD Media Into MP4 (H.264/HEVC) Format in Half an Hour Or Less</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/nnovate-your-channels-closing-scenes-free-end-screens-for-2024/"><u>[New] Innovate Your Channels' Closing Scenes Free End Screens for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/dts-aac-movavi-audio-converter/"><u>網路上免費 DTS 到 AAC 音頻格式轉換 - 使用 Movavi Audio Converter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/critiquing-the-functionality-of-windows-modern-standby/"><u>Critiquing the Functionality of Windows' Modern Standby</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-pc-best-ms-store-picks/"><u>Enhance Your PC: Best MS Store Picks</u></a></li>
<li><a href="https://win-bytes.techidaily.com/how-to-fix-an-improper-scanner-setup-on-your-device-expert-advice-by-yl-software-solutions/"><u>How to Fix an Improper Scanner Setup on Your Device - Expert Advice by YL Software Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-non-playable-media-error-0xc10100bf/"><u>How to Resolve Non-Playable Media Error 0XC10100BF</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-face-fluidity-techniques-implementing-motion-blur-effects/"><u>In 2024, Face Fluidity Techniques Implementing Motion Blur Effects</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-vivo-v30-lite-5g-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Vivo V30 Lite 5G by Phone Number | Dr.fone</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-visualize-and-create-with-top-7-innovative-animation-suites/"><u>In 2024, Visualize & Create with Top 7 Innovative Animation Suites</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-remote-storage-access-dropbox-and-google-drive-by-drives/"><u>Integrating Remote Storage: Access Dropbox & Google Drive by Drives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-windows-high-resource-drain-from-unrealcefsubprocess/"><u>Mitigating Windows' High Resource Drain From UnrealCEFSubprocess</u></a></li>
<li><a href="https://howto.techidaily.com/play-store-stuck-on-downloading-of-vivo-s17t-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Vivo S17t? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/quest-for-freedom-guide-to-affordable-mmo-games/"><u>Quest for Freedom Guide to Affordable MMO Games</u></a></li>
</ul></div>

