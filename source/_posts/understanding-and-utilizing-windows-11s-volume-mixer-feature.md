---
title: Understanding and Utilizing Windows 11'S Volume Mixer Feature
date: 2024-10-03T06:41:41.044Z
updated: 2024-10-08T23:02:20.784Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding and Utilizing Windows 11'S Volume Mixer Feature
excerpt: This Article Describes Understanding and Utilizing Windows 11'S Volume Mixer Feature
keywords: WinVolumeMixControl,Windows11AudioMix,VolumeMixerWindows,AudioAdjustmentWin11,MixerSetupWindows11,ManageSoundWins11,SoundBalanceWin11
thumbnail: https://thmb.techidaily.com/3fd32f657ca906fd6ed8ec321bcb0a471e050e9fdbe1e0332d4aba568afc6cd5.jpg
---

## Understanding and Utilizing Windows 11'S Volume Mixer Feature

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135415/19272" target="_top" id="2135415">
  <img src="//a.impactradius-go.com/display-ad/19272-2135415" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable the Volume Mixer in Windows 11's Action Center

 To enable the volume mixer in Windows 11, you will need to do the following:

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105873/7443" target="_top" id="2105873">
  <img src="//a.impactradius-go.com/display-ad/7443-2105873" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105873/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137976/21526" target="_top" id="2137976">
  <img src="//a.impactradius-go.com/display-ad/21526-2137976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137976/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Log in and press**Win + A** to open Action Center. You will notice a new volume mixer icon next to the volume bar. Click on it to reveal the complete sound settings. Both the Spatial Audio and volume mixer will be present inside.  
![New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-volume-settings-in-action-center.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130874/7443" target="_top" id="2130874">
  <img src="//a.impactradius-go.com/display-ad/7443-2130874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130874/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-files.techidaily.com/new-flair-filled-images-top-10-screenshot-sticker-addons-on-iphonesandroids-for-2024/"><u>[New] Flair-Filled Images – Top 10 Screenshot Sticker Addons on iPhones/Androids for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-unlocking-the-full-potential-of-iphone-7-screen-save-for-2024/"><u>[New] Unlocking the Full Potential of iPhone 7 Screen Save for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-your-ultimate-guide-to-top-streamers-platforms/"><u>[Updated] 2024 Approved Your Ultimate Guide to Top Streamers Platforms</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-essential-insights-on-asmr-videos-unveiled-for-2024/"><u>[Updated] Essential Insights on ASMR Videos Unveiled for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-tips-for-achieving-crystal-clear-1080p-on-fb/"><u>[Updated] In 2024, Tips for Achieving Crystal Clear 1080P on FB</u></a></li>
<li><a href="https://win11-tips.techidaily.com/13-methods-to-resuscitate-windows-system-backup/"><u>13 Methods to Resuscitate Windows System Backup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-open-the-print-management-tool-in-windows-11/"><u>9 Ways to Open the Print Management Tool in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-beginners-path-to-implementing-hyper-v-on-win-11-homes/"><u>A Beginner's Path to Implementing Hyper-V on Win 11 Homes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-missing-d3dx9-point-on-windows-11/"><u>Addressing Missing D3DX9 Point on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-mouse-accessibility-in-windows-11-with-ease/"><u>Adjusting Mouse Accessibility in Windows 11 with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-overview-of-user-dissatisfaction-with-windows-11-upgrade/"><u>An Overview of User Dissatisfaction with Windows 11 Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-common-mistakes-fixing-office-error-0x80041015/"><u>Avoiding Common Mistakes Fixing Office Error 0X80041015</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-spacious-and-slow-a-bittersweet-blend/"><u>Blackview: Spacious and Slow - A Bittersweet Blend</u></a></li>
<li><a href="https://fix-guide.techidaily.com/does-find-my-friends-work-on-honor-magic-5-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Honor Magic 5 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/download-arc-browser-the-newest-web-browsing-option-compatible-with-windows-10/"><u>Download Arc Browser: The Newest Web Browsing Option Compatible with Windows 10</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/eluding-prying-eyes-privacy-preserving-video-editing/"><u>Eluding Prying Eyes Privacy-Preserving Video Editing</u></a></li>
<li><a href="https://extra-resources.techidaily.com/flamenco-finch-frolic/"><u>Flamenco Finch Frolic</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-oppo-find-n3-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Oppo Find N3 to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719266840560-prevent-unwanted-updates-on-your-pc-today/"><u>Prevent Unwanted Updates on Your PC Today!</u></a></li>
</ul></div>

