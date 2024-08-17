---
title: "Identity Infiltration: Windows Fingerprints in the Crosshairs"
date: 2024-08-16T01:55:54.292Z
updated: 2024-08-17T01:55:54.292Z
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

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
### How the Hackers Breached Windows Hello on the Microsoft Surface Pro Type Cover

 The hackers believed the Surface Pro would be the hardest device to crack, but they were surprised to find the Surface Pro lacked a lot of security measures for checking valid fingerprints. In fact, they discovered that they only had to dodge past one defense, then tell the Surface Pro that the fingerprint scan was successful, and the device let them in.

## What Do These Hacks Mean for You?

![Professional Thinking With Laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/professional-thinking-with-laptop.jpg)
<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 These hacks may sound pretty scary if you use fingerprints to log into your laptop. However, it's essential to remember some crucial things before you forgo fingerprint scans entirely.

### 1\. The Attacks Were Performed by Skilled Hackers

 The reason threats like [ransomware as a service](https://www.makeuseof.com/what-is-ransomware-as-a-service/) are so deadly is that anyone with minimal cybersecurity can use them. However, the above hacks require a high level of expertise, with a deep understanding of how devices authenticate fingerprints and how to avoid them.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
### 2\. The Attacks Require the Attacker to Physically Interact With the Device

 The hackers must have physical contact with the device to perform the above hacks. In the report, the hackers stated they might be able to create USB devices that can perform the attack once plugged in, but that means a potential attacker needs to plug something into your PC to hack it.

### 3\. The Attacks Only Work on Specific Devices

 You'll notice that each attack had to take a different path to achieve the same goal. Every device is unique, and a hack that works on one device may not work on another. As such, you shouldn't believe that Windows Hello has now been blown wide open on every device; it's just these three that failed.

 While these hacks may sound scary, they'll be challenging to perform against actual targets. The hacker will likely have to steal the device to perform these hacks, which would undoubtedly alert the previous owner.

## How to Stay Safe From Fingerprint Hacking
![The face of a man wearing a hoodie](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hacher-hat.jpg)
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 As stated above, the discovered hacks are complicated to perform and may require the hacker to remove the device to hack into it physically. As such, there's an extremely low chance that these attacks will personally target you.

 However, if you're still not satisfied, there are some ways to protect yourself from fingerprint scanner hacks:

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Do Not Leave Devices Unattended and Unprotected

 Because a hacker will need to interact with your device physically, you should ensure it doesn't fall into the wrong hands. For computers, you can [take steps to stop it from being stolen](https://www.makeuseof.com/tag/stop-entire-desktop-pc-home-office-stolen/). If you're using a laptop, never leave it alone in a public space, and use an [anti-theft laptop bag](https://www.makeuseof.com/tag/anti-theft-laptop-bags/) to stop people from tearing your bag open.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
### 2\. Use a Different Login Method

 Windows Hello supports many different login methods, some more secure than others. If you've fallen out of love with fingerprint scans, check out if [face, iris, fingerprint, PIN, or password logins are more secure](https://www.makeuseof.com/face-iris-fingerprint-password-pin-most-secure/), and choose one that suits you best.

 If you're worried about these hacks, it's important to remember that there's a very low chance they'll target you specifically. As such, you should be safe using fingerprint scans; just don't allow people to steal your devices.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-digital-deftness-transforming-photo-colors-professionally/"><u>[New] 2024 Approved  Digital Deftness  Transforming Photo Colors Professionally</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-elevating-social-influence-top-techniques-for-facebook-seo-excellence/"><u>[New] 2024 Approved  Elevating Social Influence  Top Techniques for Facebook SEO Excellence</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-hilarityhub-design-memes-with-ease-and-speed/"><u>[New] In 2024, HilarityHub  Design Memes with Ease and Speed</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-visualizer-vs-studio-monitors-for-2024/"><u>[New] Visualizer Vs Studio Monitors for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-harnessing-high-dynamic-range-the-future-of-photo-techniques/"><u>[Updated] 2024 Approved  Harnessing High Dynamic Range  The Future of Photo Techniques</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-best-screen-recorder-no-ads-for-android/"><u>[Updated] In 2024, Best Screen Recorder No Ads for Android</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-emulate-action-with-kinetic-blur-effects/"><u>2024 Approved  Emulate Action with Kinetic Blur Effects</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-essential-guide-software-free-techniques-for-vimeo-downloads/"><u>2024 Approved  Essential Guide  Software-Free Techniques for Vimeo Downloads</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-smartphone-streaming-success-without-a-massive-subscriber-base/"><u>2024 Approved  Smartphone Streaming Success Without a Massive Subscriber Base</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-fresh-perspective-key-modifications-in-windows-11-marketplace/"><u>A Fresh Perspective: Key Modifications in Windows 11' Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-focus-and-time-management-best-rated-windows-pomodoro-apps/"><u>Boost Your Focus and Time Management: Best-Rated Windows Pomodoro Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-mold-reinventing-yourself-with-a-new-username-in-windows-11/"><u>Breaking the Mold: Reinventing Yourself with a New UserName in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clarifying-auditory-data-handling-wasd-in-windows-os/"><u>Clarifying Auditory Data Handling: WASD in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-vmware-freeze-ups-on-windows-11/"><u>Clearing Up VMware Freeze-Ups on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-linking-drives-on-new-windows-version/"><u>Efficiently Linking Drives on New Windows Version</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/elite-environmentally-friendly-cinematography-tech/"><u>Elite Environmentally Friendly Cinematography Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expedite-your-pcs-performance-windows-11-cleansing-tips/"><u>Expedite Your PC's Performance: Windows 11 Cleansing Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-keys-to-unlocking-email-access-issues-in-windows-11-mail-service/"><u>Five Keys to Unlocking Email Access Issues in Windows 11 Mail Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-nonstop-techsign-in-issues-in-ms-teams-windows/"><u>Fixing Nonstop TechSign In Issues in MS Teams Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-hide-the-power-button-from-the-start-menu-on-windows-11-and-11/"><u>How to Hide the Power Button From the Start Menu on Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-the-forgotten-windows-start-menu/"><u>How to Reactivate the Forgotten Windows Start Menu</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-crafting-a-compelling-video-story-with-b-roll-variety/"><u>In 2024, Crafting a Compelling Video Story with B-Roll Variety</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-apple-iphone-11-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Apple iPhone 11 Pro | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Motorola Defy 2? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-find-ispoofer-pro-activation-key-on-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>In 2024, How to Find iSpoofer Pro Activation Key On Motorola Defy 2? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-the-pulse-of-internet-stability-at-work/"><u>Keeping the Pulse of Internet Stability at Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leading-the-way-in-qr-decoding-with-your-windows-machine/"><u>Leading the Way in QR Decoding with Your Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-the-power-of-combined-android-and-windows-11-displays/"><u>Leveraging the Power of Combined Android & Windows 11 Displays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-transparent-taskbars-on-win11/"><u>Mastering the Art of Transparent Taskbars on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-tackle-non-responsive-function-keys-for-brighness-on-windows-11/"><u>Methods to Tackle Non-Responsive Function Keys for Brighness on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-your-systems-core-settings/"><u>Navigating Through Your System's Core Settings</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/nostalgic-snapshots-from-your-camera-roll-on-snapchat-for-2024/"><u>Nostalgic Snapshots From Your Camera Roll on Snapchat for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinvigorate-dull-volume-options-in-disk-management-tool/"><u>Reinvigorate Dull Volume Options in Disk Management Tool</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolving-connectivity-problems-with-voice-chat-in-call-of-duty-black-ops-cold-war/"><u>Resolving Connectivity Problems with Voice Chat in Call of Duty: Black Ops Cold War</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-reinstate-working-state-of-amd-graphics-suite/"><u>Steps to Reinstate Working State of AMD Graphics Suite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-fixes-for-microsoft-store-crash-code-error-0x80072efd/"><u>Swift Fixes for Microsoft Store Crash Code Error 0X80072EFD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-steam-disk-write-failures-effectively/"><u>Tackling Windows Steam Disk Write Failures Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-correcting-code-0x0000004e-in-os/"><u>Techniques for Correcting Code 0X0000004E in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-uninstall-guide-enhancing-your-workflow-in-windows/"><u>The Ultimate Uninstall Guide: Enhancing Your Workflow in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-xbox-game-pass-error-code-0x00000001-on-windows-os/"><u>Troubleshooting Xbox Game Pass Error Code 0X00000001 on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/update-with-ease-a-guide-for-surface-computer-owners/"><u>Update with Ease: A Guide for Surface Computer Owners</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-oppo-find-x7-ultra-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Oppo Find X7 Ultra | Dr.fone</u></a></li>
</ul></div>
