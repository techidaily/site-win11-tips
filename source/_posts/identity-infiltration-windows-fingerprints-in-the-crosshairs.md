---
title: "Identity Infiltration: Windows Fingerprints in the Crosshairs"
date: 2024-06-25T16:41:57.545Z
updated: 2024-06-26T16:41:57.545Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Identity Infiltration: Windows Fingerprints in the Crosshairs"
excerpt: "This Article Describes Identity Infiltration: Windows Fingerprints in the Crosshairs"
keywords: Identity Theft Attacks,Fingerprint Security Risks,Windows Vulnerability,Digital Hacking Danger,Cyber Intrusion Threat,Privacy Breach Prevention,Secure Windows Systems
thumbnail: https://thmb.techidaily.com/7771a2b06b1c9409671f87688822caf9758687ec74141e34200890076f60dc1f.jpg
---

## Identity Infiltration: Windows Fingerprints in the Crosshairs

 Logging into a Windows laptop with a fingerprint scanner is easy; just place your finger on a scanner, and the operating system lets you in. However, researchers have shown that, while this method is convenient, it's not hackproof.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?

## Can People Hack Windows Hello Fingerprint Scanners?

![Lock Having Fingerprint in the Middle on Blue Background](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/passwords-are-a-thing-of-the-past-passwordless-logins-benefits.jpg)

 If a hacker wants to bypass a fingerprint scanner on a Windows machine, they're aiming to get past a service called Windows Hello. This service handles how you log into Windows, such as PINs, facial scans, and fingerprint scans.

 As part of research into Windows Hello's strength, two [white-hat hackers](https://www.makeuseof.com/white-hat-hacker/), Jesse D'Aguanno and Timo Teräs, posted a report on their website, [Blackwing HQ](https://blackwinghq.com/blog/posts/a-touch-of-pwn-part-i/). The report details how they breached three popular devices: the Dell Inspiron 15, Lenovo ThinkPad T14, and the Microsoft Surface Pro Type Cover.

### How the Hackers Breached Windows Hello on the Dell Inspiron 15

 For the Dell Inspiron 15, the hackers noticed they could boot into Linux on the laptop. Once logged into Linux, they can register their fingerprints in the system and give it the same ID as the Windows user they want to log into.

 Then, they perform a man-in-the-middle attack on the connection between the PC and the sensor. They set it up so that when Windows goes to double-check that a scanned fingerprint is legitimate, it ends up checking the Linux database of fingerprints instead of its own.

 To dodge Windows Hello, the hackers uploaded their fingerprints to the Linux database, assigned it the same ID as the user on Windows, and then tried to log into Windows with their fingerprints. During the authentication process, they redirected the packet to the Linux database, which told Windows that the user at the specified ID was ready to log in.

### How the Hackers Breached Windows Hello on the Lenovo ThinkPad T14

 For the Lenovo ThinkPad, the hackers discovered that the laptop used a custom encryption method to verify fingerprints. With some work, the hackers managed to decrypt it, giving them a way into the fingerprint verification process.

 Once done, the hackers could force the fingerprint database to accept their fingerprint as the user's. Then, all they had to do was scan their fingerprint to access the Lenovo ThinkPad.

### How the Hackers Breached Windows Hello on the Microsoft Surface Pro Type Cover

 The hackers believed the Surface Pro would be the hardest device to crack, but they were surprised to find the Surface Pro lacked a lot of security measures for checking valid fingerprints. In fact, they discovered that they only had to dodge past one defense, then tell the Surface Pro that the fingerprint scan was successful, and the device let them in.

## What Do These Hacks Mean for You?

![Professional Thinking With Laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/professional-thinking-with-laptop.jpg)

 These hacks may sound pretty scary if you use fingerprints to log into your laptop. However, it's essential to remember some crucial things before you forgo fingerprint scans entirely.

### 1\. The Attacks Were Performed by Skilled Hackers

 The reason threats like [ransomware as a service](https://www.makeuseof.com/what-is-ransomware-as-a-service/) are so deadly is that anyone with minimal cybersecurity can use them. However, the above hacks require a high level of expertise, with a deep understanding of how devices authenticate fingerprints and how to avoid them.

### 2\. The Attacks Require the Attacker to Physically Interact With the Device

 The hackers must have physical contact with the device to perform the above hacks. In the report, the hackers stated they might be able to create USB devices that can perform the attack once plugged in, but that means a potential attacker needs to plug something into your PC to hack it.

### 3\. The Attacks Only Work on Specific Devices

 You'll notice that each attack had to take a different path to achieve the same goal. Every device is unique, and a hack that works on one device may not work on another. As such, you shouldn't believe that Windows Hello has now been blown wide open on every device; it's just these three that failed.

 While these hacks may sound scary, they'll be challenging to perform against actual targets. The hacker will likely have to steal the device to perform these hacks, which would undoubtedly alert the previous owner.

## How to Stay Safe From Fingerprint Hacking ![The face of a man wearing a hoodie](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hacher-hat.jpg)

 As stated above, the discovered hacks are complicated to perform and may require the hacker to remove the device to hack into it physically. As such, there's an extremely low chance that these attacks will personally target you.

 However, if you're still not satisfied, there are some ways to protect yourself from fingerprint scanner hacks:

### 1\. Do Not Leave Devices Unattended and Unprotected

 Because a hacker will need to interact with your device physically, you should ensure it doesn't fall into the wrong hands. For computers, you can [take steps to stop it from being stolen](https://www.makeuseof.com/tag/stop-entire-desktop-pc-home-office-stolen/). If you're using a laptop, never leave it alone in a public space, and use an [anti-theft laptop bag](https://www.makeuseof.com/tag/anti-theft-laptop-bags/) to stop people from tearing your bag open.

### 2\. Use a Different Login Method

 Windows Hello supports many different login methods, some more secure than others. If you've fallen out of love with fingerprint scans, check out if [face, iris, fingerprint, PIN, or password logins are more secure](https://www.makeuseof.com/face-iris-fingerprint-password-pin-most-secure/), and choose one that suits you best.

 If you're worried about these hacks, it's important to remember that there's a very low chance they'll target you specifically. As such, you should be safe using fingerprint scans; just don't allow people to steal your devices.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/how-to-disable-background-apps-in-windows-11/"><u>How to Disable Background Apps in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-art-microsoft-paints-latest-enhancements/"><u>Mastering Art: Microsoft Paint's Latest Enhancements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-windows-11-integrating-cutting-edge-run-commands/"><u>Upgrade Your Windows 11: Integrating Cutting-Edge Run Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-disconnected-pc-from-wireless-lan/"><u>Steps to Fix Disconnected PC From Wireless LAN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-confusion-a-guide-to-reinstalling-store-software/"><u>Clearing Up Confusion: A Guide to Reinstalling Store Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-code-30015-26-in-m365-for-windows-computers/"><u>Resolving Error Code 30015-26 in M365 for Windows Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-reigniting-wifi-detection-in-windows-11-systems/"><u>Steps for Reigniting Wifi Detection in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-using-dism-with-win11-system-recovery/"><u>The Ultimate Guide to Using Dism with Win11 System Recovery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hotkey-hacks-masterful-window-management-made-simple/"><u>Hotkey Hacks: Masterful Window Management Made Simple</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-ahead-of-time-tomorrows-melancholic-masterpieces-and-their-origins/"><u>In 2024, Ahead of Time Tomorrows Melancholic Masterpieces and Their Origins</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-5-essential-browser-recording-apps-unveiled-for-2024/"><u>[New] 5 Essential Browser Recording Apps Unveiled for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Samsung Galaxy A05? | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/audio-editing-techniques-for-mp4-files-for-2024/"><u>Audio Editing Techniques for MP4 Files for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-poco-f5-5g-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Poco F5 5G Location on Skout | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/step-by-step-guide-to-elevating-video-presence-through-thumbnails-for-2024/"><u>Step-by-Step Guide to Elevating Video Presence Through Thumbnails for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-video-editor-selection-guide-understanding-filmora-and-democracy-creator-for-2024/"><u>[New] Video Editor Selection Guide  Understanding Filmora and Democracy Creator for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-filmora-discount-code-finder-explore-the-best-deals/"><u>Updated In 2024, Filmora Discount Code Finder Explore the Best Deals</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-proven-steps-for-choosing-an-effective-4k-camera-lens/"><u>[Updated] Proven Steps for Choosing an Effective 4K Camera Lens</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/bring-your-videos-to-life-top-conversion-apps-and-tutorials-for-2024/"><u>Bring Your Videos to Life Top Conversion Apps and Tutorials for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>