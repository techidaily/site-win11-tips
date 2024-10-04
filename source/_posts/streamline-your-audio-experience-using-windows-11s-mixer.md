---
title: Streamline Your Audio Experience Using Windows 11'S Mixer
date: 2024-09-30T17:32:33.362Z
updated: 2024-10-04T01:19:34.145Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamline Your Audio Experience Using Windows 11'S Mixer
excerpt: This Article Describes Streamline Your Audio Experience Using Windows 11'S Mixer
keywords: Windows 11 Audio Mixing,Enhance Audio W11,Streamlined Audio PC,Elevate Windows Sound,Optimize W11 Music,Windows Audio Boost,Improve W11 Mixer
thumbnail: https://thmb.techidaily.com/6471b67acfe8051c9c2c5b701d3d154a93913c9b510e1febb60299ae780985b8.jpg
---

## Streamline Your Audio Experience Using Windows 11'S Mixer

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
<a href="https://aligracehair.sjv.io/c/5597632/2135358/19272" target="_top" id="2135358">
  <img src="//a.impactradius-go.com/display-ad/19272-2135358" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135358/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable the Volume Mixer in Windows 11's Action Center

 To enable the volume mixer in Windows 11, you will need to do the following:

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094428/7443" target="_top" id="2094428">
  <img src="//a.impactradius-go.com/display-ad/7443-2094428" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094428/7443" style="position:absolute;visibility:hidden;" border="0" />
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

9. Log in and press**Win + A** to open Action Center. You will notice a new volume mixer icon next to the volume bar. Click on it to reveal the complete sound settings. Both the Spatial Audio and volume mixer will be present inside.  
![New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-volume-settings-in-action-center.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151865/7443" target="_top" id="2151865">
  <img src="//a.impactradius-go.com/display-ad/7443-2151865" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151865/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886015/19272" target="_top" id="1886015">
  <img src="//a.impactradius-go.com/display-ad/19272-1886015" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886015/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-activity-recording.techidaily.com/new-frame-grabbers-companion/"><u>[New] Frame Grabber's Companion</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-mastering-skype-meetings-windowsos-x-record/"><u>[Updated] Mastering Skype Meetings Windows/OS X Record</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-audiophile-tools-best-audio-interfaces-for-podcasters/"><u>2024 Approved Audiophile Tools Best Audio Interfaces for Podcasters</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-focused-freedom-advanced-mounting-solutions-for-phonescams/"><u>2024 Approved Focused Freedom Advanced Mounting Solutions for Phones/Cams</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/4-ways-to-record-facebook-live-stream/"><u>4 Ways to Record Facebook Live Stream</u></a></li>
<li><a href="https://fox-http.techidaily.com/compact-your-content-explore-the-most-admirable-33-video-reducers/"><u>Compact Your Content Explore the Most Admirable 33 Video Reducers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-winerror-misconfigured-file-history-settings/"><u>Correcting WinError: Misconfigured File History Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disarming-error-0x80040610-a-practical-guide-to-outlook-recovery/"><u>Disarming Error 0X80040610: A Practical Guide to Outlook Recovery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-apex-legends-crashes-with-w11-fixes/"><u>Eliminating Apex Legends Crashes with W11 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-performance-four-routes-to-windows-disk-explorer/"><u>Enhancing Performance: Four Routes to Windows Disk Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-altering-keyboard-layout-on-windows-11/"><u>Expert Tips for Altering Keyboard Layout on Windows 11</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-the-latest-hp-laserjet-1018-printing-drivers-for-free/"><u>Get the Latest HP LaserJet 1018 Printing Drivers for Free</u></a></li>
<li><a href="https://win11-tips.techidaily.com/handling-the-unexpected-windows-device-dropout/"><u>Handling the Unexpected Windows Device Dropout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-window-placement-on-windows-os-defeat-overscan/"><u>Improve Window Placement on Windows OS: Defeat Overscan</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mastering-macs-preview-app-an-in-depth-tutorial-for-users/"><u>In 2024, Mastering Mac's Preview App An In-Depth Tutorial for Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-intel-unison-not-working-woes-on-win11/"><u>Overcoming Intel Unison Not Working Woes on Win11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/premium-devices-to-elevate-your-mobile-video-skills/"><u>Premium Devices to Elevate Your Mobile Video Skills</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-7-best-free-volume-boosters-for-windows/"><u>The 7 Best Free Volume Boosters for Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/top-5-from-samsung-galaxy-xcover-6-pro-tactical-edition-to-iphone-contacts-transfer-apps-and-software-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Top 5 from Samsung Galaxy XCover 6 Pro Tactical Edition to iPhone Contacts Transfer Apps and Software | Dr.fone</u></a></li>
</ul></div>

