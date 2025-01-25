---
title: Brightening Dull Screen on PC's BOOT Menu
date: 2025-01-23T23:18:20.128Z
updated: 2025-01-24T20:47:59.436Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Brightening Dull Screen on PC's BOOT Menu
excerpt: This Article Describes Brightening Dull Screen on PC's BOOT Menu
keywords: Boost Boot Screens,Enhance PC Display,Clear Boot Lighting,Brighten Boot Panel,Luminous Screen Start,Improve Boot Menu,Glow Up Boot Interface
thumbnail: https://thmb.techidaily.com/046b51c249713a58e7f91807e73ec08e3a40b03e4add7fe4a3b9657a9796ae66.jpg
---

## Brightening Dull Screen on PC's BOOT Menu

 Newer computers come with Unified Extensible Firmware Interface (UEFI) as the new standard. However, Legacy BIOS is still largely part of most active systems due to legacy software and hardware support. Switching from UEFI to Legacy BIOS is easy using the firmware utility. But what if the legacy boot option is grayed out in BIOS?

 This can happen for a few reasons. A common reason for the grayed-out BIOS is if you have Secure Boot or Platform Trusted Technology (TPM) enabled. Issues with Modern Standby supported system is another reason that prevents you from switching from UEFI to Legacy BIOS.

 Here is how to fix the Legacy Boot grayed-out in BIOS issue on your Windows system.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3UyJuZYzjt0?si=W87GeyzVKVORAk7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Causes the Legacy Boot Grayed Out Problem?

 You may find the Legacy Boot option grayed out if the UEFI settings, such as Secure Boot and TPM are enabled in the BIOS utility. In some instances, the BIOS utility can tell you why you can't switch to the Legacy boot option.

 Boot into your BIOS utility and open**Advanced Boot** **Options** . Next, check the**Enable Legacy Option ROMs** option. You may see an error prompt explaining why the Legacy option cannot be enabled. It usually hints that PPT/TPM or Secure Boot is enabled.

 If you don't have any such option, try the troubleshooting steps below to restore the Legacy boot option in BIOS.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Click**Restart** to boot into the**Startup Menu.**  
![startup menu HP](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/startup-menu-hp-1.jpg)
2. In the Startup Menu, press**F10** to access the**BIOS Settings** . You may see other options depending on your computer manufacturer.
3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
5. Select**Disabled** and make sure the changes are shown in the Boot Options tab.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mMYEK2gtY5c?si=ytxNz_JHZkTrwb4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Disable Modern Standby

 Modern Standby (S0) is a newer power mode available on select modern computers. It is enabled by default on compatible systems but can cause issues with Legacy Boot.

 To fix the issue, try to[disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qbuund2HKOQ?si=NaGHqIrx8hSL7gWV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://hardware-tips.techidaily.com/avoiding-imperfections-tips-for-smooth-finishes-in-additive-manufacturing/"><u>Avoiding Imperfections: Tips for Smooth Finishes in Additive Manufacturing</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/crafting-memorable-tweets-using-ai-assistance/"><u>Crafting Memorable Tweets Using AI Assistance</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/explore-traditional-and-modern-japanese-design-with-our-diverse-gallery-of-wallpaper-images-and-photo-collections-handcrafted-by-yl-software/"><u>Explore Traditional & Modern Japanese Design with Our Diverse Gallery of Wallpaper Images & Photo Collections – Handcrafted by YL Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-deactivate-windows-shutdown-timer/"><u>How to Deactivate Window's Shutdown Timer</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-gionee-f3-pro-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Gionee F3 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-activity-log-inspection-in-windows-10/"><u>Mastering Activity Log Inspection in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-ms-store-failures-error-0x80072f17-resolution/"><u>Navigating MS Store Failures: Error 0X80072f17 Resolution</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/one-click-humor-your-guide-to-the-ifunny-meme-app-for-2024/"><u>One Click Humor Your Guide to the iFunny Meme App for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/overcome-asus-ac56-driver-challenges-a-step-by-step-guide-for-multiple-windows-operating-systems/"><u>Overcome ASUS AC56 Driver Challenges: A Step-by-Step Guide for Multiple Windows Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-post-update-issues-a-guide-for-windows-discord-users/"><u>Overcoming Post-Update Issues: A Guide for Windows Discord Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quality-audio-boosters-the-ultimate-free-windows-list/"><u>Quality Audio Boosters: The Ultimate Free Windows List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-unwinding-catastrophic-javascript-hiccup-in-discord-w10w11/"><u>Quick Guide: Unwinding Catastrophic Javascript Hiccup in Discord W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rustic-tech-resurgence-atlasos-update/"><u>Rustic Tech Resurgence: AtlasOS Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-network-adapter-error-31-on-windows/"><u>Steps to Rectify Network Adapter Error 31 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-adjusting-icons-distance-on-windows-1110/"><u>Title: Adjusting Icons' Distance on Windows 11/10</u></a></li>
<li><a href="https://win-tricks.techidaily.com/top-alternativen-zu-corsairs-cloning-kit-professionelles-und-einfaches-kopieren-von-ssds-and-hdds/"><u>Top-Alternativen Zu Corsair's Cloning Kit: Professionelles Und Einfaches Kopieren Von SSDs & HDDs</u></a></li>
<li><a href="https://technical-tips.techidaily.com/trouble-connecting-to-twitch-diagnosing-network-vs-platform-issues/"><u>Trouble Connecting to Twitch? Diagnosing Network Vs. Platform Issues</u></a></li>
<li><a href="https://program-issues.techidaily.com/world-of-warcraft-halted-by-error-132-heres-how-to-get-you-back-in-game/"><u>World of Warcraft Halted by Error 132? Here's How to Get You Back In-Game</u></a></li>
<li><a href="https://extra-tips.techidaily.com/youtube-tricks-for-enhancing-screen-real-estate/"><u>YouTube Tricks for Enhancing Screen Real Estate</u></a></li>
</ul></div>

