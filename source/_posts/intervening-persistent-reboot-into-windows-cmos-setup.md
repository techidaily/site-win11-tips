---
title: Intervening Persistent Reboot Into Windows CMOS Setup
date: 2024-12-20T20:09:30.415Z
updated: 2024-12-22T09:08:26.327Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Intervening Persistent Reboot Into Windows CMOS Setup
excerpt: This Article Describes Intervening Persistent Reboot Into Windows CMOS Setup
keywords: Windows CMOS Boot,Persistent Reboot Fix,CMOS Configuration,System Reboot Solutions,Windows CMOS Recovery,BIOS Reset Guide,PC Restart Troubleshoot
thumbnail: https://thmb.techidaily.com/f080364c9fd10c7a5fc9c9d8f37fc816490a2b5446a3998c55dc9f0ed4866d4c.jpg
---

## Intervening Persistent Reboot Into Windows CMOS Setup

 Does your Windows device keep booting to BIOS every time you restart it? Numerous factors could be responsible for this, such as having the boot key pressed on the keyboard, running outdated BIOS, improperly plugged-in operating system drive, misconfigured boot sequence, or a CMOS battery issue.

 If you have trouble booting the operating system repeatedly and want your device to boot to Windows rather than BIOS, here are a few checks and fixes you can apply.

## 1\. Disconnect Peripherals and Discharge Static Charge

 Disconnecting the peripherals and discharging the static charge has fixed the issue under discussion for some users. Therefore, before you proceed with any other fixes, unplug all peripherals from your device, and press the power button for half a minute to discharge static electricity. After that, reboot your device. If it boots back into BIOS, begin applying the remaining fixes.

## 2\. Perform a Quick Restart From the BIOS

 Although it sounds pretty simple, restarting the computer after saving BIOS settings usually boots a device into Windows, which may help bypass the issue. Therefore, once your device boots into BIOS, do not make any changes; save the changes and exit BIOS. Afterward, your device may restart once and boot directly into Windows this time.

 Even if this workaround works, it isn't a permanent fix, as you will need to restart Windows through BIOS every time you turn it on, which can be annoying. Continue applying the remaining fixes for a permanent solution.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Check Your Boot Sequence

 Boot sequence refers to the order in which your device searches for bootable data. It's recommended to keep the device containing your OS at the top of the sequence, especially if you have multiple storage devices connected. With this, your device can quickly find the bootable data and boot your operating system.

 If the drive containing your OS appears connected in the previous step, ensure it comes first in the boot sequence. To check that on a Dell device, select **Boot Sequence** from the left sidebar. After that, choose **Legacy** under **Boot List Option** and make sure your desired drive appears first in the **Boot Sequence**.

![Changing the Boot Mode in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/changing-the-boot-mode-in-bios.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If it isn't selected, click on the **arrow button** and move the drive containing your operating system to the top.

![Putting the Drive Containing the OS at Top in Boot Sequence in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/putting-the-drive-containing-the-os-at-top-in-boot-sequence-in-bios.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Disable Fast Startup

 The Fast Startup feature in Windows hibernates the system and loads the files quicker. In a nutshell, it helps Windows boot faster. Even though it saves users a lot of time and helps them get back to work quickly, it is known to cause annoying issues during bootup. Often, disabling this feature fixes most of these problems.

 If you can boot into Windows from BIOS, our guide on [turning Fast Startup on and off](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) can help you disable this feature. However, if you are stuck at the BIOS screen and cannot boot into Windows, you can also disable Fast Startup from there. For that, go to your laptop manufacturer's website for instructions on turning off Fast Startup from BIOS.

## 7\. Update the BIOS

 An outdated BIOS can also prevent Windows from booting correctly. It's the most neglected cause of most booting problems. Therefore, to ensure that the issue under discussion is not caused due to an outdated BIOS, you should upgrade it to the latest version.

 So, if you are able to boot to Windows from BIOS but again encounter the issue when restarting, refer to our guide on [how to update your UEFI BIOS in Windows](https://www.makeuseof.com/tag/update-uefi-bios-windows/). If you cannot boot to Windows, you will have to resort to other methods of updating BIOS.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 8\. Replace or Reinsert the CMOS Battery

![Person tampering with a motherboard.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/cmos-battery-explained-featured.jpg)

 The CMOS battery powers the BIOS firmware on the laptop. If you are unable to boot to Windows, a dead CMOS battery could also be to blame. Often, just removing and reinserting the battery fixes the issue; however, it resets a few settings, including the date and time. In case of a dead battery, you may need to replace it.

 If you want to know more about the CMOS battery and how to remove it, refer to our guide on [what a CMOS battery is](https://www.makeuseof.com/what-is-a-cmos-battery-and-how-do-you-remove-one/).

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
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-altvmix-cross-platform-virtual-mixer/"><u>[New] 2024 Approved AltVMix Cross-Platform Virtual Mixer</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-the-ultimate-blueprint-for-successful-freefire-videos-on-youtube/"><u>[Updated] In 2024, The Ultimate Blueprint for Successful FreeFire Videos on YouTube</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-timeless-titans-a-list-of-the-top-10-classic-adventure-games/"><u>[Updated] In 2024, Timeless Titans A List of the Top 10 Classic Adventure Games</u></a></li>
<li><a href="https://extra-tips.techidaily.com/audible-annotations-choosing-the-top-speech-to-text-apps-for-2024/"><u>Audible Annotations Choosing the Top Speech-to-Text Apps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-media-creation-tool-issue-x8007043c/"><u>Decoding Windows' Media Creation Tool Issue X.8007043C</u></a></li>
<li><a href="https://sound-issues.techidaily.com/diagnosing-and-repairing-issues-in-your-logitech-g230-mic-for-crystal-clear-audio/"><u>Diagnosing and Repairing Issues in Your Logitech G230 Mic for Crystal Clear Audio</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-6s-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 6s without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-service-did-not-respond-error-1053-on-windows/"><u>How to Fix “The Service Did Not Respond” Error 1053 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-win11-taskbar-sizes-and-placement/"><u>Mastering Win11 Taskbar Sizes and Placement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-full-screen-capture-annoyances-with-these-4-strategies/"><u>Overcoming Full-Screen Capture Annoyances with These 4 Strategies.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-start-mastering-pc-directx-setup-and-maintenance/"><u>Quick Start: Mastering PC DirectX Setup & Maintenance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-the-saved-image-effect-uninstalling-webp-in-chrome-win-wise/"><u>Reversing the Saved Image Effect: Uninstalling WebP in Chrome, Win-Wise</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-your-computers-double-clicking-technique/"><u>Revolutionize Your Computer's Double-Clicking Technique</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpening-performance-reducing-ums-load-from-vanguard-on-windows-pcs/"><u>Sharpening Performance: Reducing UMS Load From Vanguard on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-wake-up-cycle-customizing-boot-menu-duration-in-win11/"><u>Speedy Wake-Up Cycle: Customizing Boot Menu Duration in Win11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/steps-to-prevent-thumbnail-absence-on-shorts-videos/"><u>Steps to Prevent Thumbnail Absence on Shorts Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-store-glitches-on-win-11/"><u>Tackling Store Glitches on Win 11</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/g-down-the-veil-youtubes-most-elusive-videos-for-2024/"><u>Taking Down the Veil YouTube's Most Elusive Videos for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-rated-ipad-gadgets-and-peripherals-featuring-insights-from-zdnet/"><u>Top-Rated iPad Gadgets and Peripherals - Featuring Insights From ZDNet</u></a></li>
</ul></div>

