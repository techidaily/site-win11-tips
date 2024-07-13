---
title: Too Much Glitches? Handle Deps Before VirtualBox on Win
date: 2024-07-12T17:19:52.024Z
updated: 2024-07-13T17:19:52.024Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Too Much Glitches? Handle Deps Before VirtualBox on Win
excerpt: This Article Describes Too Much Glitches? Handle Deps Before VirtualBox on Win
keywords: Win VirtualBox Dependency,Glitch Handling in VMs,Preventing VBox Errors,Virtualization Stability,Managing System Deps,Optimizing Windows VMs,Fixing Glitches on OS X
thumbnail: https://thmb.techidaily.com/8165b01ed064346696cef87d703a956f25f7e75ad27ec5fc1142917a3643401d.jpg
---

## Too Much Glitches? Handle Deps Before VirtualBox on Win

 VirtualBox is a virtualization platform that allows you to run multiple operating systems on a single computer. It's installation on Windows requires a couple of packages available upfront. Without meeting these dependencies, VirtualBox installation will end up with an error.

 Visual C++ Redistributable is a straightforward installation, it is not the same case with Python as it requires configuring as well. The good thing is it is easy to do.

## Dependencies for Installation of VirtualBox on Windows

 VirtualBox is a cross-platform software. Apart from Windows, you can [install VirtualBox on Linux](https://www.makeuseof.com/install-ubuntu-virtualbox/) and Mac as well. The installation package is available for download from the official [VirtualBox site](https://www.virtualbox.org/wiki/Downloads).

![VirtualBox download page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/01-virtualbox-download-page.jpg)

 Before you install VirtualBox, you must install these packages:

* Microsoft Visual C++ 2019 Redistributable Package
* Python core / win32ap

 If they are not installed already, VirtualBox will ask you during installation to set them up first. See the following images for reference:

![Popup window in VirtualBox asks for Visual C++ Redistributable Package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/02-popup-window-in-virtualbox-asks-for-visual-c-redistributable-package-2.jpg)

![VirtualBox window displays the need for Missing Dependencies Python Core win32api](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/03-virtualbox-window-displays-the-need-for-missing-dependencies-python-core-win32api.jpg)

Close

 If you try to continue the installation of VirtualBox without meeting the dependencies, the installation will end up in an error and show the following error message:

![VirtualBox Installation failed! Fatal error during installation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/04-virtualbox-installation-failed-fatal-error-during-installation.jpg)

## How to Install Visual C++ Redistributable on Windows

 You can download Microsoft Visual C++ Redistributable from the [Microsoft Learn webpage](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170). You need to download the version that suits your operating system (x86/32-bit or x64/64-bit). Once downloaded, proceed with the installation, the process is straightforward.

![Microsoft Visual C++ Redistributable download page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/05-microsoft-visual-c-redistributable-download-page.jpg)

![Microsoft Visual C++ Redistributable download choose architechture](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/06-microsoft-visual-c-redistributable-download-choose-architechture.jpg)

![Microsoft Visual C++ Redistributable installation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/07-microsoft-visual-c-redistributable-installation.jpg)

Close

## How to Install and Configure Python / win32api on Windows

 Python is another dependency for VirtualBox. You can download it from the official [Python website](https://www.python.org/downloads/).

![Download Python win32api for Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/08-download-python-win32api-for-windows.jpg)

 Once downloaded, start the installation. You need to check **Add python.exe to PATH**, and complete the installation. When added to PATH, Python packages and scripts can be accessed from any directory. Complete the installation.

![Install Python win32api for Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/09-install-python-win32api-for-windows.jpg)

 Now, configure Python for Win32 extensions. It provides access to Windows APIs from Python. To do this, open the Command Prompt or PowerShell as administrator and run the command:

`pip install pywin32`

![Command to install pywin32 in WIndows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/10-command-to-install-pywin32-in-windows.jpg)

 Your computer has now met all the dependencies to install VirtualBox.

## Error Free Installation of VirtualBox on Windows

 Start the installation of VirtualBox, and it will complete without any errors. Browse the following images for reference:

![Install VirtualBox in WIndows using the wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/11-install-virtualbox-in-windows-using-the-wizard.jpg)

![Install VirtualBox in WIndows custom setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/12-install-virtualbox-in-windows-custom-setup.jpg)

![Install VirtualBox in WIndows network interfaces warning](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/13-install-virtualbox-in-windows-network-interfaces-warning.jpg)

![Install VirtualBox in WIndows ready to install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/14-install-virtualbox-in-windows-ready-to-install.jpg)

![VirtualBox in WIndows installation complete](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/15-virtualbox-in-windows-installation-complete.jpg)

![VirtualBox manager in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/16-virtualbox-manager-in-windows.jpg)

Close

## Run a Guest Operating System of Your Choice via VirtualBox

 With its simple interface and impressive features, VirtualBox is a strong contender among virtualization applications.

 With its ability to create snapshots, VirtualBox can even help safeguard the data of the guest operating systems against virus or ransomware attacks.

 Visual C++ Redistributable is a straightforward installation, it is not the same case with Python as it requires configuring as well. The good thing is it is easy to do.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-gamers-pathway-to-impeccable-recordings/"><u>[Updated] Gamers' Pathway to Impeccable Recordings</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-oppo-a58-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Oppo A58 4G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accurate-timekeeping-at-your-fingertips-winning-windows-timers/"><u>Accurate Timekeeping at Your Fingertips: Winning Windows Timers</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-step-by-step-approach-to-mastering-the-art-of-morphvox-sound-alteration/"><u>In 2024, Step-by-Step Approach to Mastering the Art of MorphVOX Sound Alteration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricks-to-speed-up-system-restart-with-windows-11/"><u>Tricks to Speed Up System Restart with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-made-dns-strategies-for-windows-11-enthusiasts/"><u>Tailor-Made DNS Strategies for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/nraveling-youtubes-highest-peaks-post-vidcon-for-2024/"><u>[New] Unraveling Youtube's Highest Peaks (Post-VidCon) for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-experts-pathway-navigating-fullscreen-realms-in-premiere-pro/"><u>2024 Approved  Expert's Pathway  Navigating Fullscreen Realms in Premiere Pro</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-harmonious-majesties-a-treasury-of-royalty-free-cinematic-piano-music-for-film-and-video-production/"><u>Updated Harmonious Majesties A Treasury of Royalty-Free Cinematic Piano Music for Film & Video Production</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-0x800700e1-on-w10w11/"><u>Steps to Fix 0X800700E1 on W10/W11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-streamlining-your-gaming-diary-overwatch-video-documentation/"><u>[Updated] Streamlining Your Gaming Diary  Overwatch Video Documentation</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-top-7-gratis-youtube-tags-extractor-tools/"><u>2024 Approved  Top 7 Gratis Youtube Tags Extractor Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-windows-11-blackout-with-easy-tips-and-tricks/"><u>Bypass Windows 11 Blackout with Easy Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-11s-resolution-settings/"><u>Adjusting Windows 11'S Resolution Settings</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-asus-rog-phone-8-pro-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Asus ROG Phone 8 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/yourphoneexe-explained-is-it-safe-on-windows-7xp/"><u>YourPhone.exe Explained - Is It Safe on Windows 7/XP?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-ceasing-random-windows-key-activation/"><u>Strategies for Ceasing Random Windows Key Activation</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-free-and-frugal-mac-mp3-optimizer-app/"><u>In 2024, Free & Frugal Mac MP3 Optimizer App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-overcoming-uninstall-restrictions-on-win-11/"><u>Troubleshooting: Overcoming Uninstall Restrictions on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-fix-the-steam-must-be-running-to-play-this-game-error-in-windows-11/"><u>7 Ways to Fix the Steam Must Be Running to Play This Game Error in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-devices-on-the-frontline-top-5-ways-to-confirm-availability/"><u>Windows 11 Devices on the Frontline: Top 5 Ways to Confirm Availability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-free-note-taking-tricks-in-windows-11/"><u>Top Free Note-Taking Tricks in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-pagefilesys-understanding-its-windows-purpose/"><u>What Is Pagefile.sys? Understanding Its Windows Purpose</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-manipulating-the-windows-11-registry-to-unlock-themes/"><u>The Art of Manipulating the Windows 11 Registry to Unlock Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-pc-sound-with-new-windows-audio-drivers/"><u>Streamline Your PC Sound with New Windows Audio Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-upcoming-license-expiration-error-in-w10w11/"><u>Addressing Upcoming License Expiration Error in W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-overcome-sudden-screen-loss-during-win-games/"><u>Techniques to Overcome Sudden Screen Loss During WIN Games</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-paving-the-way-to-success-with-professional-insights-into-youtube-banners/"><u>In 2024, Paving the Way to Success with Professional Insights Into YouTube Banners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boot-into-peace-five-tactics-to-overcome-windows-security-failures/"><u>Boot Into Peace: Five Tactics to Overcome Windows Security Failures</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-ultimate-selection-identifying-best-12-vloggers-camera-choices/"><u>In 2024, The Ultimate Selection  Identifying Best 12 Vloggers' Camera Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-entry-point-issues-on-windows-systems/"><u>Bypassing Entry Point Issues on Windows Systems</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-crafting-visual-magic-the-essentials-of-snapchat-photo-editing/"><u>[Updated] Crafting Visual Magic  The Essentials of Snapchat Photo Editing</u></a></li>
<li><a href="https://extra-tips.techidaily.com/5-upgrades-to-shine-your-digital-clips-for-2024/"><u>5 Upgrades to Shine Your Digital Clips for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/5-quick-methods-to-bypass-vivo-v27e-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Vivo V27e FRP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719365974672-ten-terminal-tricks-you-can-try-today/"><u>Ten Terminal Tricks You Can Try Today!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-fixing-non-displaying-searches-in-win-1011-os/"><u>Strategies for Fixing Non-Displaying Searches in Win 10/11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-and-streamlining-the-microsoft-store-in-win11/"><u>Unblocking and Streamlining the Microsoft Store in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convenient-cleanup-integrating-uninstall-shortcuts-into-wins-interface/"><u>Convenient Cleanup: Integrating Uninstall Shortcuts Into Win's Interface</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-food-fans-unite-these-15-top-rated-tiktok-culinary-adventures-worth-trying-out/"><u>[Updated] In 2024, Food Fans Unite! These 15 Top-Rated TikTok Culinary Adventures Worth Trying Out</u></a></li>
</ul></div>
