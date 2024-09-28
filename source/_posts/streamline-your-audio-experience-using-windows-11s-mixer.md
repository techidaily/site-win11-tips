---
title: Streamline Your Audio Experience Using Windows 11'S Mixer
date: 2024-09-27T16:51:37.426Z
updated: 2024-09-28T18:05:36.012Z
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
<a href="https://appsumo.8odi.net/c/5597632/2049390/7443" target="_top" id="2049390">
  <img src="//a.impactradius-go.com/display-ad/7443-2049390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049390/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable the Volume Mixer in Windows 11's Action Center

 To enable the volume mixer in Windows 11, you will need to do the following:

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886044/19272" target="_top" id="1886044">
  <img src="//a.impactradius-go.com/display-ad/19272-1886044" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886044/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1484963">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1484963.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1484963">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1484963.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1484963%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1484963/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Log in and press**Win + A** to open Action Center. You will notice a new volume mixer icon next to the volume bar. Click on it to reveal the complete sound settings. Both the Spatial Audio and volume mixer will be present inside.  
![New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-volume-settings-in-action-center.jpg)

<!-- affiliate ads begin -->
<span id="1328683">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328683.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328683">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328683.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328683%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328683/15852" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-friendly.techidaily.com/new-significant-aspects-in-techno-narrative-design-for-2024/"><u>[New] Significant Aspects in Techno Narrative Design for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amending-disabled-windows-shadow-snapshots/"><u>Amending Disabled Windows Shadow Snapshots</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-lock-apps-on-lenovo-thinkphone-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Lenovo ThinkPhone to Protect Your Individual Information</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-guide-for-installing-windows-11-arm-via-iso-download/"><u>How-To Guide for Installing Windows 11 ARM via ISO Download</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-samsung-galaxy-m34-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Samsung Galaxy M34 | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-effortless-capture-and-storage-pro-guide-to-digital-sound-recording/"><u>In 2024, Effortless Capture & Storage Pro Guide to Digital Sound Recording</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/inside-the-tesla-robotaxi-upcoming-prices-release-schedule-and-features-explored/"><u>Inside the Tesla Robotaxi: Upcoming Prices, Release Schedule & Features Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-your-pc-with-hyper-v-on-windows-11/"><u>Jumpstart Your PC with Hyper-V on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-recollection-of-previous-windows-password/"><u>Mending “Recollection of Previous Window's Password”</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-mspm-setup-obstacles-in-windows-vista/"><u>Overcoming MSPM Setup Obstacles in Windows Vista</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/redefining-productivity-on-the-move-in-depth-review-of-the-2021-ipad-pro-m1-and-its-exceptional-performance-for-mobile-users/"><u>Redefining Productivity on the Move: In-Depth Review of the 2021 iPad Pro (M1) and Its Exceptional Performance for Mobile Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-non-definable-error-in-windows-environment/"><u>Tackling 'Non-Definable' Error in Windows Environment</u></a></li>
<li><a href="https://ai-topics.techidaily.com/updated-what-is-talking-avatar-for-2024/"><u>Updated What Is Talking Avatar for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-samsung-galaxy-z-fold-5-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Samsung Galaxy Z Fold 5? | Dr.fone</u></a></li>
</ul></div>

