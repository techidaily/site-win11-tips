---
title: "Hacked: Is Your Windows Hello Identity Still Secure?"
date: 2024-09-20T00:09:10.369Z
updated: 2024-09-21T23:18:56.858Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Hacked: Is Your Windows Hello Identity Still Secure?"
excerpt: "This Article Describes Hacked: Is Your Windows Hello Identity Still Secure?"
keywords: Windows Hello Security,Hacking Risks,Identity Safety,Windows Hello,Facial Recognition Vulnerability,Secure Login,Personal Data Protection
thumbnail: https://thmb.techidaily.com/134f01974d541e3e4f7e678a539e306f85d908190cede197af26c62a5bdec50a.png
---

## Hacked: Is Your Windows Hello Identity Still Secure?

 Logging into a Windows laptop with a fingerprint scanner is easy; just place your finger on a scanner, and the operating system lets you in. However, researchers have shown that, while this method is convenient, it's not hackproof.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557747/17382" target="_top" id="1557747">
  <img src="//a.impactradius-go.com/display-ad/17382-1557747" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557747/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What Do These Hacks Mean for You?

![Professional Thinking With Laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/professional-thinking-with-laptop.jpg)

 These hacks may sound pretty scary if you use fingerprints to log into your laptop. However, it's essential to remember some crucial things before you forgo fingerprint scans entirely.

### 1\. The Attacks Were Performed by Skilled Hackers

 The reason threats like [ransomware as a service](https://www.makeuseof.com/what-is-ransomware-as-a-service/) are so deadly is that anyone with minimal cybersecurity can use them. However, the above hacks require a high level of expertise, with a deep understanding of how devices authenticate fingerprints and how to avoid them.

### 2\. The Attacks Require the Attacker to Physically Interact With the Device

 The hackers must have physical contact with the device to perform the above hacks. In the report, the hackers stated they might be able to create USB devices that can perform the attack once plugged in, but that means a potential attacker needs to plug something into your PC to hack it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049378/7443" target="_top" id="2049378">
  <img src="//a.impactradius-go.com/display-ad/7443-2049378" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049378/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 3\. The Attacks Only Work on Specific Devices

 You'll notice that each attack had to take a different path to achieve the same goal. Every device is unique, and a hack that works on one device may not work on another. As such, you shouldn't believe that Windows Hello has now been blown wide open on every device; it's just these three that failed.

 While these hacks may sound scary, they'll be challenging to perform against actual targets. The hacker will likely have to steal the device to perform these hacks, which would undoubtedly alert the previous owner.

## How to Stay Safe From Fingerprint Hacking

![The face of a man wearing a hoodie](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hacher-hat.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484939/16446" target="_top" id="1484939">
  <img src="//a.impactradius-go.com/display-ad/16446-1484939" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484939/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 As stated above, the discovered hacks are complicated to perform and may require the hacker to remove the device to hack into it physically. As such, there's an extremely low chance that these attacks will personally target you.

 However, if you're still not satisfied, there are some ways to protect yourself from fingerprint scanner hacks:

### 1\. Do Not Leave Devices Unattended and Unprotected

 Because a hacker will need to interact with your device physically, you should ensure it doesn't fall into the wrong hands. For computers, you can [take steps to stop it from being stolen](https://www.makeuseof.com/tag/stop-entire-desktop-pc-home-office-stolen/). If you're using a laptop, never leave it alone in a public space, and use an [anti-theft laptop bag](https://www.makeuseof.com/tag/anti-theft-laptop-bags/) to stop people from tearing your bag open.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425">
  <img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Use a Different Login Method

 Windows Hello supports many different login methods, some more secure than others. If you've fallen out of love with fingerprint scans, check out if [face, iris, fingerprint, PIN, or password logins are more secure](https://www.makeuseof.com/face-iris-fingerprint-password-pin-most-secure/), and choose one that suits you best.

 If you're worried about these hacks, it's important to remember that there's a very low chance they'll target you specifically. As such, you should be safe using fingerprint scans; just don't allow people to steal your devices.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-high-tech-5-live-screen-recorders/"><u>[New] 2024 Approved High-Tech 5 Live Screen Recorders</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-ultimate-guide-to-chose-the-best-live-platform/"><u>[New] Ultimate Guide to Chose the Best Live Platform</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-expertise-unleashed-best-practices-for-ios-audio-broadcasting-for-2024/"><u>[Updated] Expertise Unleashed Best Practices for iOS Audio Broadcasting for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-how-to-fade-in-and-fade-out-video-clips/"><u>[Updated] How to Fade-In and Fade-Out Video Clips</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-what-exactly-is-disconitro-insider-info-for-freepaid-users-for-2024/"><u>[Updated] What Exactly Is DiscoNitro? Insider Info for Free/Paid Users for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-the-limitless-windows-chatai-with-freedomgpt/"><u>Explore the Limitless Windows ChatAI: With FreedomGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-zero-to-art-starting-up-ms-paint-in-win11/"><u>From Zero to Art: Starting up MS Paint in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-repair-windows-11-assistance-tool/"><u>Guide to Repair Windows 11 Assistance Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-tweaking-your-digital-environment-windows-11-default-actions/"><u>Guide to Tweaking Your Digital Environment: Windows 11 Default Actions</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-samsung-galaxy-m54-5g-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Samsung Galaxy M54 5G Phones? | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-quickcapturepro-the-definitive-guide-to-windows-snaps/"><u>In 2024, QuickCapturePro The Definitive Guide to Windows Snaps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-stuck-windows-updates-with-these-tips/"><u>Navigate Through Stuck Windows Updates with These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-greyed-out-erase-feature-in-windows-11-settings/"><u>Overcoming Greyed Out Erase Feature in Windows 11 Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-login-req-issue-in-windows-11/"><u>Overcoming Windows Login Req Issue in Windows 11</u></a></li>
<li><a href="https://os-tips.techidaily.com/troubleshooting-apple-solutions-when-your-iphone-fails-to-deliver-messages/"><u>Troubleshooting Apple: Solutions When Your iPhone Fails to Deliver Messages</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    