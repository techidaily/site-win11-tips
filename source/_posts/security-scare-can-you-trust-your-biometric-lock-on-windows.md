---
title: "Security Scare: Can You Trust Your Biometric Lock on Windows?"
date: 2024-07-03T12:38:48.522Z
updated: 2024-07-04T12:38:48.522Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Security Scare: Can You Trust Your Biometric Lock on Windows?"
excerpt: "This Article Describes Security Scare: Can You Trust Your Biometric Lock on Windows?"
keywords: Windows Security,Biometrics Safety,Lock Integrity,Facial Recognition,Fingerprint Scanning,Authentication Trust,Safe Access Control
thumbnail: https://thmb.techidaily.com/aef9f8cb7b85429cf28cb38f2d49cc0528e1c43a7556fd8a130e20454901702b.jpg
---

## Security Scare: Can You Trust Your Biometric Lock on Windows?

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

## How to Stay Safe From Fingerprint Hacking
![The face of a man wearing a hoodie](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hacher-hat.jpg)

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
<li><a href="https://win11-tips.techidaily.com/prioritize-protection-activating-tpm-and-secure-boot-before-w11-update/"><u>Prioritize Protection: Activating TPM and Secure Boot Before W11 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-put-a-windows-computer-to-sleep/"><u>9 Ways to Put a Windows Computer to Sleep</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-ragnarok-overcoming-x-script-woes/"><u>Restoring Ragnarok: Overcoming X-Script Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-task-automation-tackling-scheduler-issues/"><u>Enhance Task Automation: Tackling Scheduler Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quelling-irregular-beats-soundcard-irq-solutions/"><u>Quelling Irregular Beats: Soundcard IRQ Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-normalcy-windows-11s-basic-user-reset-guide/"><u>Unleashing Normalcy: Windows 11'S Basic User Reset Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensure-non-crashy-windows-user-experience/"><u>Ensure Non-Crashy Windows User Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-your-shopping-microsoft-store-error-0x80072f30-cure/"><u>Simplify Your Shopping: Microsoft Store Error 0X80072F30 Cure</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-macs-leading-10-screen-capture-and-recorder-software-for-2024/"><u>[Updated] Mac's Leading 10 Screen Capture & Recorder Software for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/iphone-14-asking-for-passcode-after-ios-1714-update-what-to-do-drfone-by-drfone-ios/"><u>iPhone 14 Asking for Passcode after iOS 17/14 Update, What to Do? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-effortless-transformation-of-your-youtube-content-into-webm/"><u>[Updated] 2024 Approved  Effortless Transformation of Your YouTube Content Into WebM</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-mac-techniques-to-shorten-instagram-vids/"><u>2024 Approved  Mac Techniques to Shorten Instagram Vids</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/best-animated-video-makers-for-teachers-and-students/"><u>Best Animated Video Makers for Teachers and Students</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/premier-destinations-amplifying-youtube-videos-for-2024/"><u>Premier Destinations Amplifying YouTube Videos for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-best-apps-and-programs-for-image-video-integration/"><u>In 2024, Best Apps and Programs for Image Video Integration</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-guard-your-camera-top-10-shields-reviewed/"><u>[Updated] 2024 Approved  Guard Your Camera - Top 10 Shields Reviewed</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/b-roll-builder-kit-for-2024/"><u>B-Roll Builder Kit for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>