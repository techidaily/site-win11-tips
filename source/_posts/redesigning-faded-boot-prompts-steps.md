---
title: "Redesigning Faded Boot Prompts: Steps"
date: 2024-12-29T17:59:53.109Z
updated: 2025-01-06T01:56:38.068Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Redesigning Faded Boot Prompts: Steps"
excerpt: "This Article Describes Redesigning Faded Boot Prompts: Steps"
keywords: Redesign Fades Boots,Revitalize Old Boots,Boot Renewal Guide,Restore Boot Appearance,Faded Boot Fix,Boot Prompt Update,Step-by-Step Boot Care
thumbnail: https://thmb.techidaily.com/6b564cfcc68d7fa9fa2ebcc8ac34b00c6e2d610d2ee82b6185002beb469144e3.jpg
---

## Redesigning Faded Boot Prompts: Steps

 Newer computers come with Unified Extensible Firmware Interface (UEFI) as the new standard. However, Legacy BIOS is still largely part of most active systems due to legacy software and hardware support. Switching from UEFI to Legacy BIOS is easy using the firmware utility. But what if the legacy boot option is grayed out in BIOS?

 This can happen for a few reasons. A common reason for the grayed-out BIOS is if you have Secure Boot or Platform Trusted Technology (TPM) enabled. Issues with Modern Standby supported system is another reason that prevents you from switching from UEFI to Legacy BIOS.

 Here is how to fix the Legacy Boot grayed-out in BIOS issue on your Windows system.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Causes the Legacy Boot Grayed Out Problem?

 You may find the Legacy Boot option grayed out if the UEFI settings, such as Secure Boot and TPM are enabled in the BIOS utility. In some instances, the BIOS utility can tell you why you can't switch to the Legacy boot option.

 Boot into your BIOS utility and open**Advanced Boot** **Options** . Next, check the**Enable Legacy Option ROMs** option. You may see an error prompt explaining why the Legacy option cannot be enabled. It usually hints that PPT/TPM or Secure Boot is enabled.

 If you don't have any such option, try the troubleshooting steps below to restore the Legacy boot option in BIOS.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/grbt-5VvbuI?si=qnoirlmljslpqcQj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Disable Secure Boot to Enable Boot

 Secure Boot is a UEFI feature that protects your computer against malware by allowing only trusted system software to run on your computer. When enabled, it will perform a cryptographic check during the boot process to verify the integrity of the system image.

 However, if you have Secure Boot enabled, it will likely disable Legacy Boot as well. You'll need to[disable Secure Boot in your BIOS utility](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) to fix the issue.

 The below steps to disable Secure Boot are for an HP Pavilion computer. For other systems, refer to your system manual.

To disable secure boot:

1. Click on**Start** and then click on**Power** .
2. Press and hold the**Shift key** and click on**Restart** . Confirm the action if necessary.
3. Release the**Shift** key as the PC shuts down and boot into the**Recovery Menu.**
4. Go to**Troubleshoot** and click on**Advanced options** .
5. Next, click on**UEFI Firmware Settings.**  
![Advanced OptionspUEFI Firmware Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/advanced-optionspuefi-firmware-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Click**Restart** to boot into the**Startup Menu.**  
![startup menu HP](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/startup-menu-hp-1.jpg)
2. In the Startup Menu, press**F10** to access the**BIOS Settings** . You may see other options depending on your computer manufacturer.
3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
5. Select**Disabled** and make sure the changes are shown in the Boot Options tab.
6. Press**F10** to save the changes and disable Secure Boot.

## 2\. Disable Trusted Platform Technology (TPM)

![disable TPM state BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-tpm-state-bios-1.jpg)

 In addition to Secure Boot, you may also have enabled Trusted Platform Module (TPM), disabling Legacy BIOS. To fix the issue, check if TPM is enabled on your PC, which is likely a case on a Windows 11 running system, and disable the option if necessary.

 You can disable TPM from the BIOS setup utility. Here's how to do it.

1. Boot into your BIOS utility using the**Windows Recovery Menu.**
2. Next, open the**Security** tab using the right and left arrow keys.
3. Highlight the**TPM State** option and press**Enter** . If no TPM option is available, look for the**PTT** option.
4. Select**Disabled** to disable TPM on your device.
5. Press**F10** to save the change and exit.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Disable Modern Standby

 Modern Standby (S0) is a newer power mode available on select modern computers. It is enabled by default on compatible systems but can cause issues with Legacy Boot.

 To fix the issue, try to[disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Restore a Grayed Out Legacy Boot Option in Your BIOS

 You can fix the grayed-out Legacy boot option in BIOS by disabling Secure Boot and Trusted Platform Technology. In addition, disable Standard Standby (S0) to fix the problem.

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
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-essential-guide-to-hashtagging-for-game-focused-yt-channels/"><u>[Updated] In 2024, Essential Guide to Hashtagging for Game-Focused YT Channels</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-film-school-at-home-mastering-video-editing-via-youtube-and-alternatives/"><u>[Updated] In 2024, Film School at Home Mastering Video Editing via YouTube & Alternatives</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-mastering-the-art-of-search-engine-optimization-for-podcasts-for-2024/"><u>[Updated] Mastering the Art of Search Engine Optimization for Podcasts for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-youtube-money-mastery-from-clicks-to-checkbook-balance/"><u>2024 Approved YouTube Money Mastery From Clicks to Checkbook Balance</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-sign-out-of-apple-id-from-apple-iphone-se-without-password-by-drfone-ios/"><u>In 2024, How to Sign Out of Apple ID From Apple iPhone SE without Password?</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-pioneering-cinematic-language/"><u>In 2024, Pioneering Cinematic Language</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-the-key-ingredients-of-a-powerful-podcast-launch-video/"><u>In 2024, The Key Ingredients of a Powerful Podcast Launch Video</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-the-loss-of-razer-device-support-in-win1011/"><u>Mending the Loss of Razer Device Support in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11s-mail-app-html-glitches-in-email-previews/"><u>Overcoming Windows 11'S Mail App HTML Glitches in Email Previews</u></a></li>
<li><a href="https://solve-lab.techidaily.com/real-time-streaming-mastery-discover-manycam-features-virtual-webcams-and-professional-live-video-editing/"><u>Real-Time Streaming Mastery: Discover ManyCam Features, Virtual Webcams, and Professional Live Video Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-insufficient-usb-functionality/"><u>Remedying Insufficient USB Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguard-internet-experience-include-trusted-sites-on-windows-11/"><u>Safeguard Internet Experience: Include Trusted Sites on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-window-management-taskmanager-priority/"><u>Unveiling Window Management: TaskManager Priority</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/your-entry-level-equipment-checklist-for-youtube-success-for-2024/"><u>Your Entry-Level Equipment Checklist for YouTube Success for 2024</u></a></li>
</ul></div>

