---
title: Stop Windows From Repeatedly Accessing CMOS Settings
date: 2024-08-16T01:48:09.969Z
updated: 2024-08-17T01:48:09.969Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stop Windows From Repeatedly Accessing CMOS Settings
excerpt: This Article Describes Stop Windows From Repeatedly Accessing CMOS Settings
keywords: Stop CMOS Resets,Avoid CMOS Errors,Prevent BIOS Changes,Guard Against System Resets,Protect PC Boot Process,Secure BIOS Settings,Shield From Repeated CMOS Access
thumbnail: https://thmb.techidaily.com/6d644818f4603c573461e1572ce0a1a0270aa91bb3cb0a406132a63c5b84e5a5.jpg
---

## Stop Windows From Repeatedly Accessing CMOS Settings

 Does your Windows device keep booting to BIOS every time you restart it? Numerous factors could be responsible for this, such as having the boot key pressed on the keyboard, running outdated BIOS, improperly plugged-in operating system drive, misconfigured boot sequence, or a CMOS battery issue.

 If you have trouble booting the operating system repeatedly and want your device to boot to Windows rather than BIOS, here are a few checks and fixes you can apply.

## 1\. Disconnect Peripherals and Discharge Static Charge

 Disconnecting the peripherals and discharging the static charge has fixed the issue under discussion for some users. Therefore, before you proceed with any other fixes, unplug all peripherals from your device, and press the power button for half a minute to discharge static electricity. After that, reboot your device. If it boots back into BIOS, begin applying the remaining fixes.

## 2\. Perform a Quick Restart From the BIOS

 Although it sounds pretty simple, restarting the computer after saving BIOS settings usually boots a device into Windows, which may help bypass the issue. Therefore, once your device boots into BIOS, do not make any changes; save the changes and exit BIOS. Afterward, your device may restart once and boot directly into Windows this time.

 Even if this workaround works, it isn't a permanent fix, as you will need to restart Windows through BIOS every time you turn it on, which can be annoying. Continue applying the remaining fixes for a permanent solution.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
## 3\. Ensure That the Boot Key Isn't Pressed Down

 Booting into BIOS requires users to press a specific key on the keyboard, which is different for nearly every Windows laptop manufacturer. If you're unfamiliar with it, our guide on [how to enter the BIOS](https://www.makeuseof.com/tag/enter-bios-computer/) covers the correct key to enter BIOS on laptops from different manufacturers.

![HyperX Alloy Origins Core Function Keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/02/Alloy-Origins-Core-HyperX-Function-Keys.jpg)

 When this button is pressed, Windows will boot into BIOS instead of the operating system following a turn-on. So, if your device is automatically booting into BIOS, it is possible that this key got stuck while pressed down on the keyboard, telling your PC to boot into BIOS.

 Therefore, make sure the boot key on your keyboard isn't pressed. If there are any dust particles on it, wipe them off and press the key several times to ensure nothing is stuck.

## 4\. Ensure the Drive Containing the Operating System Is Plugged In

 Your device can also boot into BIOS if it does not find a bootable drive containing your operating system. Typically, it happens when your PC's hard drive disconnects or is no longer detected by your device due to a hardware issue.

 Thus, you must ensure that your drive is connected and detectable by your system and that it isn't causing your device to boot into BIOS. Since the BIOS interfaces of most laptops differ between manufacturers, the process to check that varies.

 Users facing this issue on a Dell device should navigate to the **System Information** tab in BIOS and look under **Device Information**.

![Checking the Device Information in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/checking-the-device-information-in-bios-1.jpg)

 If you don't see the drive with your OS installed, ensure it's connected properly. If your drive is connected but not detectable by your device, you should have it inspected to see if there is a hardware problem. However, if the drive containing your operating system is listed there, move on to the next step.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 5\. Check Your Boot Sequence

 Boot sequence refers to the order in which your device searches for bootable data. It's recommended to keep the device containing your OS at the top of the sequence, especially if you have multiple storage devices connected. With this, your device can quickly find the bootable data and boot your operating system.

 If the drive containing your OS appears connected in the previous step, ensure it comes first in the boot sequence. To check that on a Dell device, select **Boot Sequence** from the left sidebar. After that, choose **Legacy** under **Boot List Option** and make sure your desired drive appears first in the **Boot Sequence**.

![Changing the Boot Mode in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/changing-the-boot-mode-in-bios.jpg)

 If it isn't selected, click on the **arrow button** and move the drive containing your operating system to the top.

![Putting the Drive Containing the OS at Top in Boot Sequence in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/putting-the-drive-containing-the-os-at-top-in-boot-sequence-in-bios.jpg)

## 6\. Disable Fast Startup

 The Fast Startup feature in Windows hibernates the system and loads the files quicker. In a nutshell, it helps Windows boot faster. Even though it saves users a lot of time and helps them get back to work quickly, it is known to cause annoying issues during bootup. Often, disabling this feature fixes most of these problems.

 If you can boot into Windows from BIOS, our guide on [turning Fast Startup on and off](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) can help you disable this feature. However, if you are stuck at the BIOS screen and cannot boot into Windows, you can also disable Fast Startup from there. For that, go to your laptop manufacturer's website for instructions on turning off Fast Startup from BIOS.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
## 7\. Update the BIOS

 An outdated BIOS can also prevent Windows from booting correctly. It's the most neglected cause of most booting problems. Therefore, to ensure that the issue under discussion is not caused due to an outdated BIOS, you should upgrade it to the latest version.

 So, if you are able to boot to Windows from BIOS but again encounter the issue when restarting, refer to our guide on [how to update your UEFI BIOS in Windows](https://www.makeuseof.com/tag/update-uefi-bios-windows/). If you cannot boot to Windows, you will have to resort to other methods of updating BIOS.

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Replace or Reinsert the CMOS Battery
![Person tampering with a motherboard.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/cmos-battery-explained-featured.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->

 The CMOS battery powers the BIOS firmware on the laptop. If you are unable to boot to Windows, a dead CMOS battery could also be to blame. Often, just removing and reinserting the battery fixes the issue; however, it resets a few settings, including the date and time. In case of a dead battery, you may need to replace it.

 If you want to know more about the CMOS battery and how to remove it, refer to our guide on [what a CMOS battery is](https://www.makeuseof.com/what-is-a-cmos-battery-and-how-do-you-remove-one/).

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Don’t Let Your Windows PC Boot to BIOS

 Seeing your device boot directly into BIOS rather than Windows can be extremely frustrating. We hope the above fixes will help you successfully resolve the issue and boot to Windows. If the above fixes don't work, repair or reinstall Windows. If that doesn't work either, the laptop could have a hardware problem, so take it to a technician for inspection.

 If you have trouble booting the operating system repeatedly and want your device to boot to Windows rather than BIOS, here are a few checks and fixes you can apply.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/n-2024-crafting-engaging-video-content-for-live-streams/"><u>[New] In 2024, Crafting Engaging Video Content for Live Streams</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-music-infused-content-sharing-strategies-for-facebook/"><u>[New] In 2024, Music-Infused Content Sharing Strategies for Facebook</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-climbing-the-youtube-search-rankings-key-seo-strategies-unveiled/"><u>[Updated] 2024 Approved  Climbing the YouTube Search Rankings  Key SEO Strategies Unveiled</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-break-free-from-linearity-mastering-jump-cut-transitions-for-2024/"><u>[Updated] Break Free From Linearity  Mastering Jump Cut Transitions for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-premier-online-repositories-for-typography/"><u>[Updated] Premier Online Repositories for Typography</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-snickerstreamer-share-your-wit-with-a-click/"><u>[Updated] SnickerStreamer  Share Your Wit with a Click</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-tiktok-and-triller-showdown-similarities-and-differences-explored-max-156-chars-for-2024/"><u>[Updated] TikTok and Triller Showdown  Similarities & Differences Explored (Max 156 Chars) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-quick-ways-to-check-your-graphics-card-model-on-windows-11/"><u>3 Quick Ways to Check Your Graphics Card Model on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-laptop-onoff-trick-for-energy-conservation/"><u>Boost Your Laptop: On/Off Trick for Energy Conservation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-barrier-win-solution-for-epic-games-access/"><u>Bypassing the Barrier: Win Solution for Epic Games Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/click-without-the-rush-learn-to-deactivate-mouse-acceleration-windows-style/"><u>Click Without the Rush: Learn to Deactivate Mouse Acceleration Windows Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-steam-cloud-connection-problems/"><u>Correcting Steam Cloud Connection Problems</u></a></li>
<li><a href="https://screen-recording.techidaily.com/from-reality-to-virtuality-best-practices-for-recording-gameplay-worlds/"><u>From Reality to Virtuality  Best Practices for Recording Gameplay Worlds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719295110946-get-a-free-self-hosted-gptclone-with-gpt4all/"><u>Get a Free, Self-Hosted GPTClone with GPT4All</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-correct-xbox-mic-issues-in-os/"><u>Guidelines to Correct Xbox Mic Issues in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-adjust-windows-activity-lock/"><u>How to Adjust Windows Activity Lock</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-change-your-infinix-smart-7-hd-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Infinix Smart 7 HD Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-command-prompt-not-running-as-administrator-on-windows/"><u>How to Fix Command Prompt Not Running as Administrator on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-error-code-0xc0000001-on-windows-11-or-11/"><u>How to Fix Error Code 0Xc0000001 on Windows 11 or 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-go-joystick-on-lava-yuva-2-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Lava Yuva 2? | Dr.fone</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-autoplay-youtube-on-mobile-no-distractions/"><u>In 2024, AutoPlay YouTube on Mobile, No Distractions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-rectifying-device-is-unreachable-error-in-windows/"><u>Mastering the Art of Rectifying Device Is Unreachable Error in Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ode-to-open-minds-transitioning-playlists-freely/"><u>Ode to Open Minds  Transitioning Playlists Freely</u></a></li>
<li><a href="https://win-solutions.techidaily.com/overcoming-the-missing-msvcr110dll-problem-in-helldivers-2-with-easy-fixes/"><u>Overcoming the Missing MSVCR110.dll Problem in Helldivers 2 with Easy Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-non-display-at-operating-system-kickoff/"><u>Resolving Non-Display at Operating System Kickoff</u></a></li>
<li><a href="https://win11-tips.techidaily.com/severing-the-ties-unlink-onedrive-from-your-msid-on-windows/"><u>Severing the Ties: Unlink OneDrive From Your MSID on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-desktop-icon-update-process-on-windows/"><u>Simplifying Desktop Icon Update Process on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-addressing-damaged-windows-store-data-reserves/"><u>Solution Guide: Addressing Damaged Windows Store Data Reserves</u></a></li>
<li><a href="https://program-issues.techidaily.com/solution-overcoming-download-and-installation-problems-for-age-of-empires-iv-in-the-microsoft-marketplace/"><u>Solution: Overcoming Download and Installation Problems for Age of Empires IV in the Microsoft Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-approach-to-editing-windows-registry-with-command-prompt/"><u>Stepwise Approach to Editing Windows Registry with Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-instructions-for-installing-chrome-on-windows-11/"><u>Stepwise Instructions for Installing Chrome on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-extend-wait-time-before-shutting-down-in-windows-10/"><u>Tactics to Extend Wait Time Before Shutting Down in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/timely-tactics-effective-execution-of-ping-commands/"><u>Timely Tactics: Effective Execution of Ping Commands</u></a></li>
<li><a href="https://location-social.techidaily.com/top-7-skype-hacker-to-hack-any-skype-account-on-your-realme-12plus-5g-drfone-by-drfone-virtual-android/"><u>Top 7 Skype Hacker to Hack Any Skype Account On your Realme 12+ 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-upgrading-isnt-feeling-right-for-many-to-windows-11/"><u>Why Upgrading Isn't Feeling Right for Many to Windows 11</u></a></li>
</ul></div>
