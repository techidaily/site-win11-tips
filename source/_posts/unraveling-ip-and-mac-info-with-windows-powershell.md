---
title: Unraveling IP and MAC Info with Windows Powershell
date: 2024-08-16T01:32:55.236Z
updated: 2024-08-17T01:32:55.236Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unraveling IP and MAC Info with Windows Powershell
excerpt: This Article Describes Unraveling IP and MAC Info with Windows Powershell
keywords: Windows PowerShell Scripts,PSH Network Analysis,IP Address Details,MAC Address Extraction,Powershell Infrastructure Insight,Systems Configuration Tools,Data Interpretation in WinPSH
thumbnail: https://thmb.techidaily.com/f68ad44dfce4596bff961c8c73128e503881dbfbd95e5f1787a78426eec3f375.jpg
---

## Unraveling IP and MAC Info with Windows Powershell

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/024-approved-tricks-for-snagging-youtube-dialogues/"><u>[New] 2024 Approved  Tricks for Snagging YouTube Dialogues</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-animators-artistry-archives/"><u>[New] Animator's Artistry Archives</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-complete-drone-accessory-setlist-for-expert-pilots/"><u>[New] Complete Drone Accessory Setlist for Expert Pilots</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-unlocking-your-videos-top-7-rippers-explored/"><u>[New] Unlocking Your Videos  Top 7 Rippers Explored</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-dissecting-video-self-presentation-uncovering-truthfulness-needs-for-2024/"><u>[Updated] Dissecting Video Self-Presentation  Uncovering Truthfulness Needs for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-effortless-media-transfer-twitter-videos-on-whatsapp/"><u>[Updated] In 2024, Effortless Media Transfer  Twitter Videos on WhatsApp</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-from-script-to-screen-methods-of-inserting-dialogue-into-online-videos/"><u>[Updated] In 2024, From Script to Screen  Methods of Inserting Dialogue Into Online Videos</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-synchronizing-tracks-through-effective-crossfading/"><u>[Updated] Synchronizing Tracks Through Effective Crossfading</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-capture-it-right-essential-camera-lenses-for-video-blogging/"><u>2024 Approved  Capture It Right  Essential Camera Lenses for Video Blogging</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-open-source-video-tools-for-every-desktop-environment/"><u>2024 Approved  Top Open Source Video Tools for Every Desktop Environment</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-understanding-and-utilizing-facebooks-live-feature-a-complete-overview/"><u>2024 Approved  Understanding and Utilizing Facebook's Live Feature  A Complete Overview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-enhancing-performance-in-your-new-windows-11-setup/"><u>A Quick Guide to Enhancing Performance in Your New Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-pc-data-collection-using-everywhereapp/"><u>Accelerated PC Data Collection Using EverywhereApp</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-items-to-windows-11-desktop-menu-hierarchy/"><u>Adding Items to Windows 11 Desktop Menu Hierarchy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-text-hotkeys-setup-for-custom-snip-tapping-in-win11/"><u>Advanced Text Hotkeys Setup for Custom Snip Tapping in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-and-fixing-closed-caption-failures-in-windows-11/"><u>Avoiding and Fixing Closed Caption Failures in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-workflow-essential-wsl-2-strategies-for-dev-enthusiasts/"><u>Boost Your Workflow: Essential WSL 2 Strategies for Dev Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-and-remedying-0x80072af9-issues/"><u>Breaking Down and Remedying 0X80072AF9 Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathe-life-back-into-your-pcs-arrow-keys/"><u>Breathe Life Back Into Your PC's Arrow Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-endless-login-prompts-on-windows-os/"><u>Bypassing Endless Login Prompts on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-storage-disks-in-windows-os/"><u>Deciphering Storage Disks in Windows OS</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-install-insignia-vga-adapter-from-usb-comprehensive-guide/"><u>Download and Install Insignia VGA Adapter From USB: Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-desktop-arrangement-including-this-pc-icons/"><u>Efficient Desktop Arrangement: Including 'This PC' Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-profits-via-windows-11-pro-key-offers/"><u>Elevate Profits via Windows 11 Pro Key Offers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-writing-game-wins-finest-tools/"><u>Elevate Your Writing Game – Win's Finest Tools</u></a></li>
<li><a href="https://extra-information.techidaily.com/enhance-video-content-with-these-expertly-curated-online-subtitles-editors/"><u>Enhance Video Content with These Expertly Curated Online Subtitles Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-real-time-response-on-windows-discord/"><u>Enhancing Real-Time Response on Windows Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-group-policies-in-windows-via-tripartite-lens/"><u>Exploring Group Policies in Windows via Tripartite Lens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-lightweight-browsers-for-chromeoswindowsmacos-ram-and-cpu-wise/"><u>Finding Lightweight Browsers for ChromeOS/Windows/macOS: RAM & CPU-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-awful-chrome-glitches-on-microsoft-os/"><u>Fixing Awful Chrome Glitches on Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-functional-read-aloud-in-office-suite-word/"><u>Fixing Non-Functional Read Aloud in Office Suite (Word)</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/guide-on-how-to-erase-iphone-11-devices-entirely-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>Guide on How To Erase iPhone 11 Devices Entirely | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reinstalling-microsoft-store-apps/"><u>Guide to Reinstalling Microsoft Store Apps</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-lava-storm-5g-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Lava Storm 5G Phones with/without a PC</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-realme-pictures-an-easy-method-explained-by-fonelab-android-recover-pictures/"><u>How to Restore Deleted Realme Pictures  An Easy Method Explained.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-start-wordpad-in-a-windows-desktop/"><u>How to Start WordPad in a Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ignite-old-pcs-with-windows-11-version-22h2/"><u>Ignite Old PCs with Windows 11 Version 22H2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implications-of-removing-windows-11-taskbar-chat-on-your-usage-experience/"><u>Implications of Removing Window's 11 Taskbar Chat on Your Usage Experience</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-quick-guide-to-xiaomi-redmi-13c-5g-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to Xiaomi Redmi 13C 5G FRP Bypass Instantly</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-honor-90-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Honor 90 Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-the-ultimate-guide-to-fb-messenger-call-archiving/"><u>In 2024, The Ultimate Guide to FB Messenger Call Archiving</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/linguistic-ladder-leap-worlds-simplest-languages-ranked/"><u>Linguistic Ladder Leap: World's Simplest Languages Ranked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-recover-faulty-windows-file-organizer/"><u>Methods to Recover Faulty Windows File Organizer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-nullified-network-visibility-in-windows/"><u>Navigating Through Nullified Network Visibility in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/not-responsive-contemporary-timing-not-supported-by-current-monitor-display-technology/"><u>Not Responsive: Contemporary Timing Not Supported by Current Monitor Display Technology</u></a></li>
<li><a href="https://facebook.techidaily.com/outsmart-facebook-scams-find-the-14-predicaments-quickly/"><u>Outsmart Facebook Scams: Find the 14 Predicaments Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-disconnection-dxgi-error-guide/"><u>Overcoming Device Disconnection: DXGI Error Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-vmware-crashes-a-guide-for-win11-users/"><u>Overcoming VMware Crashes: A Guide for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-discord-install-failure/"><u>Overcoming Windows 11 Discord Install Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinventing-win11s-configuration-interface/"><u>Reinventing Win11's Configuration Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revising-the-start-page-to-a-new-preference-in-win11/"><u>Revising the Start Page to a New Preference in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-installation-issues-with-windows-11-troubleshooter/"><u>Solving Installation Issues with Windows 11 Troubleshooter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steering-clear-of-low-performance-pitfalls-intel-gpu-resolution/"><u>Steering Clear of Low-Performance Pitfalls: Intel GPU Resolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-eradicate-0x800713f-error-on-windows-11/"><u>Strategies to Eradicate 0X800713F Error on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-for-operational-windows-desktop-context-menus/"><u>Tactics for Operational Windows Desktop Context Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-app-experience-win11-color-automation/"><u>Tailoring Your App Experience: Win11 Color Automation</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-path-to-stardom-logo-creation-tips-for-podcasters-for-2024/"><u>The Path to Stardom  Logo Creation Tips for Podcasters for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-tips-for-playing-old-championship-manager-on-pc/"><u>Top Tips for Playing Old Championship Manager on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricking-eyes-vanish-taskbar-search-in-windows-11/"><u>Tricking Eyes: Vanish Taskbar Search in Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/ultimate-directory-for-free-visual-treasures-for-2024/"><u>Ultimate Directory for Free Visual Treasures for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-and-resolving-issues-with-registry-editor-missing/"><u>Uncovering and Resolving Issues with 'Registry Editor' Missing</u></a></li>
<li><a href="https://some-guidance.techidaily.com/vantage-point-critique-for-2024/"><u>Vantage Point Critique for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/w11-addressing-undetected-additional-monitor/"><u>W11: Addressing Undetected Additional Monitor</u></a></li>
</ul></div>
