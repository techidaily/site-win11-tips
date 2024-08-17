---
title: Stepwise Method to Disable Wired Keys for PCs Running Windows
date: 2024-08-16T02:33:31.184Z
updated: 2024-08-17T02:33:31.184Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stepwise Method to Disable Wired Keys for PCs Running Windows
excerpt: This Article Describes Stepwise Method to Disable Wired Keys for PCs Running Windows
keywords: Disabling Wired Keyboard Windows,PC Windows Keyboard Deactivation,Stepwise Wired Key Disabler,Windows Mouse+Keyboard Control,Turn Off Keys in Win OS,Windows Key Binding Removal,Systematic Key Deactivation Windows
thumbnail: https://thmb.techidaily.com/3b5dbab902dc8db71b72fe778c491655a451dd9fd6fc0286da7f19ebe4c291dd.jpg
---

## Stepwise Method to Disable Wired Keys for PCs Running Windows

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

## How to Find Your Laptop Keyboard in Device Manager

 Whether you want to disable your laptop keyboard temporarily or permanently, you will need to uninstall the input device from Device Manager.

 For this, you’ll need to identify the integrated keyboard in Device Manager. Since Device Manager will list all the recognized keyboards, including external keyboards, here’s how you can identify your laptop keyboard from the list.

 To identify the built-in keyboard in Device Manager:

1. Press **Win + R** to open **Run**.
2. Type **devmgmt.msc** and click **OK** to open Device Manager.
3. In Device Manager, expand the **Keyboards** section.  
![device manager keyboards 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/device-manager-keyboards-1.jpg)
4. Right-click on the first keyboard entry **(HID/Standard)** and select **Properties**.
5. In the **General** tab, check the **Location** section. If it says **Location 1** or **Plugged into keyboard port**, it is likely your laptop’s internal keyboard.
6. Bluetooth and USB keyboards will show **On Bluetooth Low Energy** and **On US Input Device**, respectively as its location.

 If you don't find your keyboard listed, make sure you have [set Device Manager to show hidden devices.](https://www.makeuseof.com/view-hidden-devices-in-windows/)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Disable the Laptop Keyboard Temporarily

 To disable your laptop’s keyboard temporarily:

1. Right-click on all the **HID** and **PS/2 Keyboard** entries with the **Properties Location** set to **Location 1** or **Plugged into keyboard.**  
![uninstall keyboard device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/uninstall-keyboard-device-device-manager.jpg)
2. Next, select **Uninstall Device** from the context menu.
3. Click **Yes** to confirm the action.
4. That’s it. You have disabled your laptop’s internal keyboard successfully.

 That said, this is a temporary solution. As soon as you restart your system, Windows will look for the connected but unrecognized devices and install the necessary drivers to make them functional.

## How to Disable Your Laptop Keyboard Permanently

![disable ps 2 port 18042prt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/disable-ps-2-port-18042prt-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to disable your laptop keyboard permanently, you can disable your laptop’s built-in keyboard driver PS/2 i8042prt service using the Command Prompt. We'll use the sc command-line utility to configure the service and set its start parameter to disabled.

 To disable the laptop keyboard permanently:

1. Press the **Win key** and type **cmd** in the Windows search bar.
2. Right-click on **Command Prompt** and select **Run as Administrator**. Click **Yes** when the UAC prompt appears.
3. In the Command Prompt window, type the following command and press Enter:  
`sc config i8042prt start= disabled`
4. When the success message appears, close the Command Prompt, and restart your PC. After the restart, your laptop keyboard will stop registering any inputs.

 Note that, for this to work, you will need to uninstall your keyboard from Device Manager as shown above and restart your PC.

 If you change your mind and want to re-enable the keyboard, you can use the following command in an [elevated Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/).

`sc config i8042prt start= auto`

 Once you see the success message, restart your PC to apply the changes.

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Disable the Built-in Keyboard Using an Incompatible Driver

 Another quirky solution to disable a built-in keyboard is to install an incompatible driver for the input device. Here's how to do it.

1. Open Device Manager and expand the **Keyboard** section.
2. Right-click on your laptop keyboard device and select **Update driver**.  
![Update the Relevant Keyboard Driver in Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-update-the-relevant-keyboard-driver-in-windows-device-manager.jpg)
3. Select **Browse my computer for drivers**.  
![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)
4. Next, select **Let me pick from a list of available drivers on my computer**.  
![update driver keyboard pick from list of available drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-keyboard-pick-from-list-of-available-drivers-device-manager.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Uncheck the **Show compatible hardware** option.
6. Select a random manufacturer under the **Manufacturer** column.  
![install incompatible keyboard driver windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-incompatible-keyboard-driver0windows.jpg)
7. Click **Next**. Click **Yes** if an **Update Driver Warning** dialog appears.
8. Once installed, close Device Manager and reboot your computer.

 After the restart, your laptop keyboard will stop working. If you need to install the correct driver again to enable the keyboard, right-click on the keyboard device and select **Update driver**. Next, select **Search automatically for drivers**. Windows will look for a compatible driver and install it.

![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->

 Alternatively, select **Browse my computer for drivers** in the Update Drivers dialogue. Next, select **Let me pick from a list of available drivers on my computer**. Make sure the **Show compatible hardware** option is enabled. Select an **HID Keyboard Device** driver from the list and click **Next**.

![install compatible hardware driver keyboard device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-compatible-hardware-driver-keyboard-device-manager.jpg)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->

 Wait for the driver to install. Once done, reboot your computer, and the keyboard will start working again.

## Disable Your Laptop Keyboard Permanently on Windows

 The built-in chiclet keyboard on your laptop is the primary input method available, so there is no way to disable it with a single click. Also, you wouldn’t want to disable your keyboard accidentally. If you determine your keyboard to have gone rogue and typing on its own, you can permanently disable it using the Command Prompt and Device Manager.

 That said, apart from the hardware issues, your laptop keyboard can act up for many other reasons. To fix your keyboard, check for pending driver updates, use the built-in troubleshooter, or simply disable the individual keys.

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://graphic-issues.techidaily.com/solved-how-to-fix-no-signal-on-monitor-quickly-and-easily/"><u>[SOLVED] How to Fix No Signal on Monitor Quickly & Easily</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-obs-vs-shadowplay-the-ultimate-showdown-for-gamers/"><u>[Updated] OBS vs ShadowPlay  The Ultimate Showdown for Gamers</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-ultimate-5-slow-motion-capturers/"><u>2024 Approved  Ultimate 5 Slow Motion Capturers</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/5-solutions-for-motorola-g24-power-unlock-without-password-by-drfone-android/"><u>5 Solutions For Motorola G24 Power Unlock Without Password</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-lava-blaze-2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Lava Blaze 2 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-full-screen-windows-alignment-in-windows/"><u>Achieving Full-Screen Windows Alignment in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-barriers-editing-your-win11-fax-pages-with-ease/"><u>Breaking Down Barriers: Editing Your Win11 Fax Pages with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-restrictions-for-microsoft-store-on-win11/"><u>Clearing Restrictions for Microsoft Store on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/craft-your-win11-boot-experience-steps-to-optimize-service-setups/"><u>Craft Your Win11 Boot Experience: Steps to Optimize Service Setups</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/own-clutter-how-to-efficiently-handle-unwanted-youtube-content-pcmobile/"><u>Cut Down Clutter  How to Efficiently Handle Unwanted YouTube Content (PC/Mobile)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-process-for-moving-qbittorrent-software-across-pcs/"><u>Detailed Process for Moving qBittorrent Software Across PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-not-found-efficient-windows-repairs/"><u>Eliminate 'Not Found': Efficient Windows Repairs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-shortcuts-for-power-users-on-windows/"><u>Essential Shortcuts for Power Users on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-windows-11-calendar-usage/"><u>Essential Tips for Windows 11 Calendar Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/foster-robust-windows-application-connections-with-simple-fixes/"><u>Foster Robust Windows Application Connections with Simple Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-classic-to-continuous-understanding-windows-10-and-11s-evolution/"><u>From Classic to Continuous: Understanding Windows 10 & 11'S Evolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-graphic-design-to-daily-use-ai-in-windows/"><u>From Graphic Design to Daily Use: AI in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reopen-battlenet-desktop-client-on-windows-os/"><u>Guide to Reopen Battle.net Desktop Client on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-securely-manage-editing-accessibility/"><u>Guide to Securely Manage Editing Accessibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-and-disable-the-windows-key/"><u>How to Enable and Disable the Windows Key</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-find-ispoofer-pro-activation-key-on-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>How to Find iSpoofer Pro Activation Key On Realme Narzo 60x 5G? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-failed-windows-update-issues-effectively/"><u>How to Fix Failed Windows Update Issues Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-ways-to-augment-folder-context-menus/"><u>Innovative Ways to Augment Folder Context Menus</u></a></li>
<li><a href="https://driver-install.techidaily.com/lightning-fast-updates-to-windows-10s-acer-drivers-guide/"><u>Lightning-Fast Updates to Windows 10'S Acer Drivers Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-desktop-potential-with-new-features-in-win-11-widgets/"><u>Maximize Your Desktop Potential with New Features in Win 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-open-secrets-of-windows-11-sticky-notes/"><u>Navigating the Open Secrets of Windows 11 Sticky Notes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-w11-way-to-alter-your-fax-cover-page/"><u>Navigating the W11 Way to Alter Your Fax Cover Page</u></a></li>
<li><a href="https://tech-revival.techidaily.com/next-up-how-chatgpt-helps-you-pick-the-best-movies-and-shows-to-watch/"><u>Next Up? How ChatGPT Helps You Pick The Best Movies & Shows to Watch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-update-obstacles-with-these-fixes/"><u>Overcome Update Obstacles with These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-camera-issue-fixing-error-f429f/"><u>Overcoming Windows 11 Camera Issue: Fixing Error F429F</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redirecting-home-page-in-win11-settings/"><u>Redirecting Home Page in Win11 Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-intel-unison-app-issues-on-win11-pcs/"><u>Resolving Intel Unison App Issues on Win11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-downloads-for-windows-top-10-choices-revealed/"><u>Secure Downloads for Windows: Top 10 Choices Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-failed-windows-speech-recognition-initialization/"><u>Solving Failed Windows Speech Recognition Initialization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-reigniting-wifi-detection-in-windows-11-systems/"><u>Steps for Reigniting Wifi Detection in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-the-dizzy-spins-fixing-your-wheeling-mouse/"><u>Stop the Dizzy Spins: Fixing Your Wheeling Mouse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-maintain-saving-windows-audio-configuration/"><u>Strategies to Maintain Saving Windows Audio Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-roblox-unrecoverable-errors/"><u>Strategies to Overcome Roblox Unrecoverable Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-tasks-with-these-windows-11-hacks/"><u>Streamline Tasks with These Windows 11 Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tap-into-divine-interface-capabilities-in-windows-11/"><u>Tap Into Divine Interface Capabilities in Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-abcs-of-ar-vr-mr-and-xr-how-do-they-contrast/"><u>The ABCs of AR, VR, MR & XR – How Do They Contrast?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-end-of-windows-xp-7-and-81-era-from-microsoft/"><u>The End of Windows XP, 7 & 8.1 Era From Microsoft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-disabled-roblox-game-due-to-user-settings-in-windows/"><u>Troubleshooting Disabled Roblox Game Due to User Settings in WINDOWS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-to-professional-recording-on-windows-11/"><u>Unveiling the Secrets to Professional Recording on Windows 11</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-in-2024-making-triggered-memes-with-filmora-video-editor/"><u>Updated In 2024, Making Triggered Memes with Filmora Video Editor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-display-experience-shift-to-adaptive-layouts/"><u>Upgrade Display Experience: Shift to Adaptive Layouts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-settings-returning-to-initial-touch-keyboard-configuration/"><u>Win 11 Settings: Returning to Initial Touch Keyboard Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-guide-to-opening-quick-capture-utility/"><u>Windows 11 Guide to Opening Quick Capture Utility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zeroing-out-0x800f0831-windows-troubleshoot-guide/"><u>Zeroing Out 0X800F0831: Windows Troubleshoot Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>