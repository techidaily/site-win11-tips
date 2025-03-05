---
title: "Mastering Sound Levels: Windows 11'S Volume Mixer Guide"
date: 2025-02-27T04:02:53.882Z
updated: 2025-03-04T16:49:08.581Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Sound Levels: Windows 11'S Volume Mixer Guide"
excerpt: "This Article Describes Mastering Sound Levels: Windows 11'S Volume Mixer Guide"
keywords: WinVolumeMixGuide,VolControlW11,WIndowsSoundLevel,MixerProW11,SoundManagerWin,VolumeAdjustmentW,WindowsAudioControl
thumbnail: https://thmb.techidaily.com/74045d9d6303c7a70563d004d7c7b11c2909530a50d24fd1a27318344d95b256.jpg
---

## Mastering Sound Levels: Windows 11'S Volume Mixer Guide

 Remember the old volume mixer which you could access from the system tray notifications? Windows 11 seems to be missing that ever since its release. When you click on the Volume icon in the Action Center, you only see an option to change the sound output device. There are no means to directly access the volume mixer from there. But Microsoft isn’t done with the volume settings on Windows 11.

 In a new experimental feature, Microsoft is revamping the sound settings in the Action Center. You will be able to switch output devices and adjust the volume of each of the apps listed in the Volume Mixer. Wondering how to get the feature on your system? Here's how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Do You Need a Volume Mixer in Action Center?

 The present state of volume settings in Windows 11 is quite lackluster. You can only adjust the volume of the system and cycle between multiple audio devices. For opening any other settings, even something as trivial as a volume mixer: you need to dive deep into system sound settings.

 It is baffling how Microsoft missed something so crucial in Windows 11\. These missing volume settings gave rise to apps like[EarTrumpet](https://apps.microsoft.com/store/detail/9NBLGGH516XP?hl=en-us&gl=US&ranMID=24542&ranEAID=nOD%2FrLJHOac&ranSiteID=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&epi=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&activetab=pivot%3Aoverviewtab&ranMID=43674&ranEAID=RIg0ReKk7DI&ranSiteID=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&epi=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&irgwc=1&OCID=AID2200057%5Faff%5F7795%5F1243925&tduid=%28ir%5F%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00%29%287795%29%281243925%29%28RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ%29%28%29&irclickid=%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00) which offered rich sound customization settings. Along with that, you can even access the old volume mixers, adjust the sound levels of each app, and map shortcuts.

![Old Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/old-volume-settings-in-action-center.jpg)

 However, Microsoft is slowly identifying such missing features in Windows 11 and is adding an inbuilt solution for it. Recently,[Microsoft began testing an RGB lighting feature](https://www.makeuseof.com/enable-rgb-lighting-controls-windows-11/) that will eliminate the need for third-party customization apps. So, it is pretty clear that Microsoft wants to reduce the reliance on third-party apps for vital system features and tweaks.

## How to Enable the Volume Mixer in Windows 11's Action Center

 To enable the volume mixer in Windows 11, you will need to do the following:

### 1\. Download the Latest Windows Insider Build and ViVeTool

 Currently, the volume mixer feature is an experimental feature hidden in Windows Insider build 25295\. So, you must install this Windows Insider build or a higher version to enable this feature. We recommend[using UUP Dump to download Windows Insider builds without subscribing to Windows Insider](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

 Microsoft recently expanded the Insider program with a new Canary channel, and it makes it difficult to downgrade to another channel. So, you can use UPP Dump to avoid this program and get builds directly.

 You will also need to download[ViVeTool from GitHub](https://github.com/thebookisclosed/ViVe/releases) to enable the experimental volume mixer feature. It is a command-line tool that can both activate and deactivate experimental Windows features. However, extract the tool to an easily accessible location in the C drive.

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
<li><a href="https://extra-skills.techidaily.com/new-m1-pro-and-m1-max-a-comparative-insight-into-apples-latest-chips/"><u>[New] M1 Pro and M1 Max - A Comparative Insight Into Apple's Latest Chips</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-master-quick-youtube-video-uploads-and-rendering-secrets/"><u>[New] Master Quick YouTube Video Uploads and Rendering Secrets</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-seamless-multiplayer-sessions-with-xbox-zoom-support/"><u>[New] Seamless Multiplayer Sessions with Xbox Zoom Support</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-tailoring-textual-terminals/"><u>[New] Tailoring Textual Terminals</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-compose-better-yi-4k-footage-must-have-accessories-for-2024/"><u>[Updated] Compose Better YI 4K Footage Must-Have Accessories for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/beginners-booklet-on-backdrops-and-blending/"><u>Beginner's Booklet on Backdrops & Blending</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conceal-ctrl-invisible-control-panel-in-1011-edition/"><u>Conceal CTRL: Invisible Control Panel in 10/11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-steps-to-rectify-management-tool-inaccessibility-in-windows-11/"><u>Decoding Steps to Rectify Management Tool Inaccessibility in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-defender-a-guide-to-third-party-virus-protection/"><u>Disabling Defender: A Guide to Third-Party Virus Protection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-task-management-positioning-this-pc-on-screen/"><u>Elevate Task Management: Positioning 'This PC' On Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-cannot-find-gpeditmsc-in-windows-with-ease/"><u>Fixing Cannot Find Gpedit.msc in Windows with Ease</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-show-wi-fi-password-on-oneplus-nord-ce-3-5g-by-drfone-android/"><u>How to Show Wi-Fi Password on OnePlus Nord CE 3 5G</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-create-an-apple-developer-account-on-iphone-12-pro-by-drfone-ios/"><u>In 2024, How To Create an Apple Developer Account On iPhone 12 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-your-gear-use-through-windows-widgets/"><u>Navigating Your Gear Use Through Windows Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-dotnet-a-complete-windows-guide-max-156/"><u>Reviving DotNet: A Complete Windows Guide (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-no-media-found-error-on-hard-drive-windows/"><u>Stop 'No Media Found' Error on Hard Drive Windows</u></a></li>
</ul></div>

