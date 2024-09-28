---
title: "Windows Scanners Compromised: Biometrics or Busted?"
date: 2024-09-23T18:50:24.811Z
updated: 2024-09-28T18:10:06.899Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Scanners Compromised: Biometrics or Busted?"
excerpt: "This Article Describes Windows Scanners Compromised: Biometrics or Busted?"
keywords: Windows Scanner Risk,Secure Windows Scan,Biometric Security Risks,Safe Biometric Devices,Windows Device Safety,Busted Scanning Tech,Windows Privacy Concerns
thumbnail: https://thmb.techidaily.com/399b71f22f6a0f097f9f941327a817b697b933fa54dbaf37480f689ec0e73886.jpg
---

## Windows Scanners Compromised: Biometrics or Busted?

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

<!-- affiliate ads begin -->
<span id="1531882">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531882.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531882">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531882.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531882%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531882/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886015/19272" target="_top" id="1886015">
  <img src="//a.impactradius-go.com/display-ad/19272-1886015" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886015/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. The Attacks Require the Attacker to Physically Interact With the Device

 The hackers must have physical contact with the device to perform the above hacks. In the report, the hackers stated they might be able to create USB devices that can perform the attack once plugged in, but that means a potential attacker needs to plug something into your PC to hack it.

### 3\. The Attacks Only Work on Specific Devices

 You'll notice that each attack had to take a different path to achieve the same goal. Every device is unique, and a hack that works on one device may not work on another. As such, you shouldn't believe that Windows Hello has now been blown wide open on every device; it's just these three that failed.

 While these hacks may sound scary, they'll be challenging to perform against actual targets. The hacker will likely have to steal the device to perform these hacks, which would undoubtedly alert the previous owner.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144297/7443" target="_top" id="2144297">
  <img src="//a.impactradius-go.com/display-ad/7443-2144297" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144297/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Stay Safe From Fingerprint Hacking

![The face of a man wearing a hoodie](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hacher-hat.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006928/19272" target="_top" id="2006928">
  <img src="//a.impactradius-go.com/display-ad/19272-2006928" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006928/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 As stated above, the discovered hacks are complicated to perform and may require the hacker to remove the device to hack into it physically. As such, there's an extremely low chance that these attacks will personally target you.

 However, if you're still not satisfied, there are some ways to protect yourself from fingerprint scanner hacks:

### 1\. Do Not Leave Devices Unattended and Unprotected

 Because a hacker will need to interact with your device physically, you should ensure it doesn't fall into the wrong hands. For computers, you can [take steps to stop it from being stolen](https://www.makeuseof.com/tag/stop-entire-desktop-pc-home-office-stolen/). If you're using a laptop, never leave it alone in a public space, and use an [anti-theft laptop bag](https://www.makeuseof.com/tag/anti-theft-laptop-bags/) to stop people from tearing your bag open.

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
<li><a href="https://fox-http.techidaily.com/new-tune-the-frame-diy-music-video-production-with-iphone/"><u>[New] Tune the Frame DIY Music Video Production with iPhone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-metaverse-vs-multi-meva-understanding-their-core-differences/"><u>[Updated] Metaverse Vs. Multi-Meva Understanding Their Core Differences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapt-calc-app-for-night-time-viewing-dark-mode-tutorial/"><u>Adapt Calc App for Night-Time Viewing: Dark Mode Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/cambia-tus-archivos-de-imagen-jpg-gratuitamente-a-formato-jpeg-en-linea-usando-movavi/"><u>Cambia Tus Archivos De Imagen JPG Gratuitamente a Formato JPEG en Línea Usando Movavi</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/come-trasformare-i-file-webm-in-mp4-con-alta-definizione-su-windows-1011-ed-mac-os-x-tutorial-dettagliato/"><u>Come Trasformare I File WebM in MP4 Con Alta Definizione Su Windows 10/11 Ed Mac OS X: Tutorial Dettagliato</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-fixes-for-nvidia-gl-driver-issue-3-on-win11/"><u>Expert Fixes for NVIDIA GL Driver Issue #3 on Win11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-lock-apps-on-honor-play-7t-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Honor Play 7T to Protect Your Individual Information</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-chill-and-thrills-highlighting-olympic-snowboard-cross-winners/"><u>In 2024, Chill & Thrills Highlighting Olympic Snowboard Cross Winners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-windows-11-error-code-22-lockout/"><u>Steps to Rectify Windows 11 Error Code 22 Lockout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-path-failure-on-pc-operating-systems/"><u>Tackling PATH Failure on PC Operating Systems</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-dvd-copying-software-winx-dvd-ripper-platinum-for-windows-10-users/"><u>Ultimate DVD Copying Software – WinX DVD Ripper Platinum for Windows 10 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-end-task-control-for-window-management/"><u>Utilizing End Task Control for Window Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-ahead-mastering-upcoming-tools-through-vivetool/"><u>Windows Ahead: Mastering Upcoming Tools Through ViVeTool</u></a></li>
</ul></div>

