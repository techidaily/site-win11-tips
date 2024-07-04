---
title: Strategies for Controlling Devices on Dormant Windows Systems
date: 2024-06-25T17:01:12.407Z
updated: 2024-06-26T17:01:12.407Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies for Controlling Devices on Dormant Windows Systems
excerpt: This Article Describes Strategies for Controlling Devices on Dormant Windows Systems
keywords: Device Control Strategy,Window System Security,Dormant PC Management,Safe Windows Shutdown,Antivirus on Idle PCs,Secure System Standby,Halt Devices Protocol
thumbnail: https://thmb.techidaily.com/e9e9b7ca60047014bff6bb18f8c482a86a228fe45f3ba370acbb24c0cc43ac69.jpg
---

## Strategies for Controlling Devices on Dormant Windows Systems

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

## How to Check Which Devices Are Allowed to Wake Your Windows PC From Sleep Mode

 Command Prompt or PowerShell can also tell you which devices are permitted to wake your Windows PC from sleep mode. Here's how to find out.

1. [Open Command Prompt or Windows PowerShell](https://www.makeuseof.com/windows-open-command-prompt-powershell/) on your PC.
2. Type the following command and press**Enter** to view a list of devices that are allowed to wake your computer from sleep mode.  
`powercfg -devicequery wake_armed`  
![Devices Are Allowed to Wake Your Windows PC From Sleep Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Devices-Are-Allowed-to-Wake-Your-Windows-PC-From-Sleep-Mode.jpg)

## How to Find Out What Woke Your Windows PC From Sleep Mode

 Many times, you may find that your Windows computer wakes from sleep mode on its own. Often, it's one of the connected devices or processes that causes your computer to wake up. Windows can tell you exactly what woke your computer from sleep mode.

1. Press**Win + R** to open the Run dialog.
2. Type**cmd** in the box and press**Ctrl + Shift + Enter** to [launch Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
3. Input the following command and press**Enter** .  
`powercfg -lastwake`  
![Check What Woke Windows From Sleep](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-What-Woke-Windows-From-Sleep.jpg)

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

 You can repeat the above steps to configure power management settings for more devices if you want.

 Aside from your devices, your network connections, scheduled tasks, and background wake timers can also wake Windows from sleep mode. If you want to stop that from happening, check our guide on [how to prevent your Windows computer from waking up randomly](https://www.makeuseof.com/tag/stop-windows-computer-randomly-waking/) .

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
<li><a href="https://win11-tips.techidaily.com/navigating-the-labyrinth-a-guide-to-windows-11s-services/"><u>Navigating the Labyrinth: A Guide to Windows 11'S Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/icon-position-correction-made-simple/"><u>Icon Position Correction Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-windows-11-eradicate-delays-and-lags/"><u>Accelerating Windows 11: Eradicate Delays and Lags</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recognizing-unseen-sd-card-fix-for-windows-explorer/"><u>Recognizing Unseen SD Card: Fix for Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-error-code-0x80300024-on-windows-xp/"><u>Eliminating Error Code: 0X80300024 on Windows XP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-hidden-dangers-on-a-computer-screen/"><u>Navigating Hidden Dangers on a Computer Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/battery-friendly-tips-minimize-windows-11-apps-impact/"><u>Battery-Friendly Tips: Minimize Windows 11 Apps' Impact</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-best-vocal-silencing-software-and-platforms-reviewed-for-2024/"><u>Updated Best Vocal Silencing Software and Platforms Reviewed for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-find-your-vfx-match-top-8-sites-for-free-high-quality-green-screen-footage/"><u>[New] 2024 Approved  Find Your VFX Match - Top 8 Sites for FREE High Quality Green Screen Footage</u></a></li>
<li><a href="https://unlock-android.techidaily.com/6-proven-ways-to-unlock-honor-90-phone-when-you-forget-the-password-by-drfone-android/"><u>6 Proven Ways to Unlock Honor 90 Phone When You Forget the Password</u></a></li>
<li><a href="https://techidaily.com/three-methods-to-recover-lost-data-on-motorola-moto-g84-5g-by-fonelab-android-recover-data/"><u>Three methods to recover lost data on Motorola Moto G84 5G</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-videos-back-from-tecno-camon-20-premier-5g-by-fonelab-android-recover-video/"><u>Simple ways to get lost videos back from Tecno Camon 20 Premier 5G</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-top-facebook-audio-downloaders-for-mp3-conversion/"><u>Updated 2024 Approved Top Facebook Audio Downloaders for MP3 Conversion</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/the-definitive-path-from-twitter-video-to-creatively-crafted-gifs/"><u>The Definitive Path From Twitter Video to Creatively Crafted GIFs</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-next-level-video-top-webcam-filters-for-flawless-broadcasts/"><u>[Updated] Next Level Video  Top Webcam Filters for Flawless Broadcasts</u></a></li>
</ul></div>
