---
title: Coordinating Devices in Power-Save Windows States
date: 2024-11-01T18:26:40.124Z
updated: 2024-11-06T18:31:05.743Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Coordinating Devices in Power-Save Windows States
excerpt: This Article Describes Coordinating Devices in Power-Save Windows States
keywords: Power-Save State Control,Device Coordination Windows,Energy Efficient OS,Sleep Mode Synergy,Low Power Device Strategy,Optimized Power States,Wake-On Devices Save
thumbnail: https://thmb.techidaily.com/d20fb0a2bb9049e2210bb23aa9225c390244059cedf35b9a34d45f9a041c8543.jpg
---

## Coordinating Devices in Power-Save Windows States

 When not in use, putting your Windows PC to sleep is an excellent way to preserve its battery life. You can wake your computer at any time by simply wiggling the mouse, pressing the power button, or pressing a key on your keyboard.

 Windows gives you complete control over devices that can wake your computer from a sleep state. In this guide, we will discuss how you can manage those devices.

## How to Check Which Devices Are Capable of Waking Your Windows PC From Sleep Mode

 Not every device connected to your system can wake Windows from sleep mode. You can use Command Prompt or Windows PowerShell to determine which of your devices supports waking the computer.

1. Press**Win + S** to open the search menu.
2. Type in**Windows PowerShell** and select**Run as administrator** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command and press**Enter** to view a list of devices on your system that can wake Windows from any sleep state.  
`powercfg -devicequery wake_from_any`  
![Devices That Can Wake Windows From Sleep Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Devices-That-Can-Wake-Windows-From-Sleep-Mode.jpg)

 On this list, you'll see devices like your keyboard, mouse, network adapter, and more.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/994842/11832" target="_top" id="994842">
  <img src="//a.impactradius-go.com/display-ad/11832-994842" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/994842/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Check Which Devices Are Allowed to Wake Your Windows PC From Sleep Mode

 Command Prompt or PowerShell can also tell you which devices are permitted to wake your Windows PC from sleep mode. Here's how to find out.

1. [Open Command Prompt or Windows PowerShell](https://www.makeuseof.com/windows-open-command-prompt-powershell/) on your PC.
2. Type the following command and press**Enter** to view a list of devices that are allowed to wake your computer from sleep mode.  
`powercfg -devicequery wake_armed`  
![Devices Are Allowed to Wake Your Windows PC From Sleep Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Devices-Are-Allowed-to-Wake-Your-Windows-PC-From-Sleep-Mode.jpg)

## How to Find Out What Woke Your Windows PC From Sleep Mode

 Many times, you may find that your Windows computer wakes from sleep mode on its own. Often, it's one of the connected devices or processes that causes your computer to wake up. Windows can tell you exactly what woke your computer from sleep mode.

1. Press**Win + R** to open the Run dialog.
2. Type**cmd** in the box and press**Ctrl + Shift + Enter** to[launch Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
3. Input the following command and press**Enter** .  
`powercfg -lastwake`  
![Check What Woke Windows From Sleep](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-What-Woke-Windows-From-Sleep.jpg)

<!-- affiliate ads begin -->
<a href="https://oneplusfr.sjv.io/c/5597632/1622438/14044" target="_top" id="1622438">
  <img src="//a.impactradius-go.com/display-ad/14044-1622438" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://oneplusfr.sjv.io/i/5597632/1622438/14044" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you run the above command, Windows will tell you which device or process woke your computer from sleep mode.

 If you see something like**Wake History Count - 0** , it means that Windows doesn't have a record of wake history. This can happen if you've recently rebooted your computer.

## How to Allow or Deny a Device Permission to Wake Your Windows PC From Sleep Mode

 Once you know which devices are waking up your computer without your consent, you can take the necessary steps to prevent them from doing so.

To allow or deny a device permission to wake your computer:

1. Press**Win + X** to open the Power User menu.
2. Select**Device Manager** from the list.
3. Locate the device you want to configure. Right-click on it and select**Properties** .
4. In the Properties window, switch to the**Power Management** tab.
5. Check or uncheck the**Allow this device to wake the computer** checkbox to allow or disallow the permission.
6. Click**OK** to save the changes.  
![Allow or Disallow Device to Wake Computer on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Allow-or-Disallow-Device-to-Wake-Computer-on-Windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047406/19272" target="_top" id="2047406">
  <img src="//a.impactradius-go.com/display-ad/19272-2047406" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047406/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can repeat the above steps to configure power management settings for more devices if you want.

 Aside from your devices, your network connections, scheduled tasks, and background wake timers can also wake Windows from sleep mode. If you want to stop that from happening, check our guide on[how to prevent your Windows computer from waking up randomly](https://www.makeuseof.com/tag/stop-windows-computer-randomly-waking/) .

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014853/22899" target="_top" id="2014853">
  <img src="//a.impactradius-go.com/display-ad/22899-2014853" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014853/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Manage Your Computer’s Sleep

 Now you know what devices can wake your computer from a sleep state and how to prevent them from doing so. That said, putting your computer in sleep mode may not always be the best option for your laptop. Sometimes, it’s better to shut it down completely.

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
<li><a href="https://youtube-sure.techidaily.com/n-2024-halt-autoplay-youtube-recommendations/"><u>[New] In 2024, Halt Autoplay YouTube Recommendations</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/outube-themes-made-easy-by-the-coolest-logo-and-icon-stores-online-for-2024/"><u>[New] YouTube Themes Made Easy by the Coolest Logo & Icon Stores Online for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-top-3-hd-film-scrapers-on-fb-for-2024/"><u>[Updated] Top 3 HD Film Scrapers on Fb for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/1725287795552-winx-hd-video-converter-deluxe/"><u>「WinX HD Video Converter Deluxe」トリミングで困ったときの対策ガイド</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-illustrate-images-select-caption-apps-for-your-photos-iosandroid/"><u>2024 Approved Illustrate Images Select Caption Apps for Your Photos (iOS/Android)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convenient-ways-to-open-up-your-computers-diagnostics/"><u>Convenient Ways to Open Up Your Computer's Diagnostics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-improperly-aligned-thx-surround-on-pcs/"><u>Correcting Improperly Aligned THX Surround on PCs</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/decoding-the-dilemma-local-vs-global-llms/"><u>Decoding the Dilemma: Local vs Global LLMs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disable-windows-automatic-update-warnings/"><u>Disable Windows Automatic Update Warnings</u></a></li>
<li><a href="https://win-net.techidaily.com/download-mirillis-apps-and-programs-for-free-secure-installation-instructions/"><u>Download Mirillis Apps and Programs for Free – Secure Installation Instructions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-crafting-windows-11s-trusted-hardware-dialog-shortcut/"><u>Guide to Crafting Windows 11'S Trusted Hardware Dialog Shortcut</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-xiaomi-13t-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Xiaomi 13T Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-silent-notifications-failure-in-windows-phone-link/"><u>Resolving Silent Notifications Failure in Windows' Phone Link</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-microsofts-latest-upgrade-ai-enhanced-search-capabilities-in-bing/"><u>Unveiling Microsoft's Latest Upgrade: AI Enhanced Search Capabilities in Bing</u></a></li>
</ul></div>

