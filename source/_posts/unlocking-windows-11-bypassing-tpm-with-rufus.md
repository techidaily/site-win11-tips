---
title: "Unlocking Windows 11: Bypassing TPM with Rufus"
date: 2024-07-12T17:20:58.658Z
updated: 2024-07-13T17:20:58.658Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking Windows 11: Bypassing TPM with Rufus"
excerpt: "This Article Describes Unlocking Windows 11: Bypassing TPM with Rufus"
keywords: Windows 11 Unlock Guide,Bypassing TPM,TPM Bypass Methods,Rufus for TPM Workaround,Enabling Windows WOE,Boot Win11 without TPM,Secure Boot Alternatives
thumbnail: https://thmb.techidaily.com/521ad24db07aed403ac9c63a8882a3a87b12e15e0d1178b868dfaacb16286760.jpg
---

## Unlocking Windows 11: Bypassing TPM with Rufus

 Windows 11 still has the minimum requirement of TPM 2.0 and Secure Boot to run on any operating system. After it launched, enthusiasts quickly discovered a registry hack to bypass both of these requirements and install the operating system without any difficulty.

 There are even tweaked ISO files of Windows 11 available which bypasses both requirements before installation. However, Rufus has a better solution. It can help you prepare a Windows installation media while bypassing these requirements and adding more tweaks. Want to know more? Let’s begin.

## Why Is Rufus the Tool for the Job?

 In Rufus version 3.2 and above, you can create a tweaked Windows 11 bootable media. The main attraction is that it can remove the 4GB RAM, TPM 2.0, and Secure Boot requirements while creating the bootable USB drive.

 Apart from that, it can also remove the infuriating requirement of signing in using a Microsoft Account before setting up your Windows 11 PC. These two requirements deter a lot of users from trying out Windows 11, but Rufus can now bypass both of these. All you need to do is configure Rufus to create a bootable USB drive.

 Apart from these two tweaks, Rufus can also speed up the installation process by avoiding the setup pages for tracking, [disabling BitLocker encryption](https://www.makeuseof.com/windows-10-disable-or-suspend-bitlocker/), and settings the same language and region options as the computer you are using to create a bootable USB drive. So, you can prepare a Windows 11 bootable drive that takes less time to install and set up on a new system.

## How to Create a Bootable USB Drive Which Bypasses Windows 11 Requirements Using Rufus

 Firstly, you need to [download the latest version of Rufus](https://rufus.ie/). It is available on Microsoft Store, GitHub and even has an official website where they post the details about new and upcoming releases. We suggest you download the portable version of Rufus to avoid the installation process altogether. You will also need the latest version of the Windows 11 ISO image file. Visit the official Microsoft webpage and [download the ISO file](https://www.microsoft.com/en-in/software-download/windows11) from there.

 After downloading the portable version of Rufus, repeat the following steps:

1. Go to the downloads folder and double-click on Rufus to run the tool.
2. **UAC** will pop up. Click on the **Yes** button to continue.
3. Insert a USB drive into your Windows 11 system. Ensure that the USB drive has a capacity of 8 GB or more. Rufus will automatically recognize the USB drive.
4. Click on the **Select** button in the **Boot selection** section. **Browse** your computer for the ISO file and select it.
5. Next, click on the **Partition scheme** option. Select **MBR** if you want to use this USB drive on a system with BIOS or UEFI. Leave the Target system and Partition scheme untouched if you plan to use this bootable USB drive on a UEFI system.  
![Create a Bootable USB Drive Using Rufus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/create-a-bootable-usb-drive-using-rufus.jpg)

1. Navigate to the bottom of Rufus' window and click on the **Start** button.
2. A Windows User Experience box will open. Here, you can apply all the customizations you want to the Windows 11 bootable USB drive. Click on the checkbox in front of the **Remove requirement for 4GB+ RAM, Secure Boot, and TPM 2.0** option.
3. Similarly, select the **Remove requirement for an online Microsoft account** checkbox and **Disable data collection (Skip privacy questions)** checkbox.  
![Create a Bootable USB Drive Using Rufus 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/create-a-bootable-usb-drive-using-rufus-2.jpg)
4. Click on the **OK** button. Rufus will generate a warning about deleting all data on the USB drive.  
![Create a Bootable USB Drive Using Rufus 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/create-a-bootable-usb-drive-using-rufus-3.jpg)
5. Lastly, click on the **OK** button and wait for Rufus to create the bootable Windows 11 USB drive. Eject the drive after you see a “**Ready**” message.

## How to Install the Modified Windows 11 on Your System

 Repeat the following steps to install Windows 11 while bypassing its system requirements:

1. Plug the bootable USB drive you created with Rufus into the target system. Press the designated F-key repeatedly (F10, F12, F2, or Esc) to enter the boot devices menu.
2. Select the USB drive from the list using the arrow keys and press the **Enter** key to boot.
3. Select the language and region and click on the **Next** button. Then, click on the **Install now** button.  
![Install the Modified Windows 11 on Your System](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-the-modified-windows-11-on-your-system.jpg)
4. Click on the **I don’t have the product key** option.  
![Install the Modified Windows 11 on Your System 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-the-modified-windows-11-on-your-system-2.jpg)
5. Select the version of Windows 11 you want to install (Home, Pro, Enterprise, or Education) and click on **Next**.  
![Install the Modified Windows 11 on Your System 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-the-modified-windows-11-on-your-system-3.jpg)

1. Accept the EULA and click on the **Next** button. Then, click on the **Custom** option.
2. Pick the drive where you want to install Windows 11\. Click on the **Format** button to format the drive and click on **Next**.
3. The setup will begin installing Windows 11 automatically. However, if TPM and Secure Boot bypass weren’t in place, you would never make it past the Enter product key page.  
![Install the Modified Windows 11 on Your System 4](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-the-modified-windows-11-on-your-system-4.jpg)
4. Your system will restart a few times and then boot to the Windows 11 setup page. Disconnect your system from the internet otherwise, it will attempt to check and download updates which can take a long time.
5. Enter your **Name** and select **three security questions** and their answers as well. Click on **Next**.  
![Install the Modified Windows 11 on Your System 5](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-the-modified-windows-11-on-your-system-5.jpg)
6. Windows will prepare your system for the first boot. After a short while you will boot to the desktop.  
![Windows 11 up and running on an unsupported system](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-11-up-and-running-on-an-unsupported-system.jpg)

## Benefits of Using Rufus to Create a Custom Windows 11 Installation Media

 Rufus isn’t just a means to bypass the Windows 11 stern requirements on an unsupported system. It can also help you avoid the excessively long route Windows 11 setup forces you to take while installing the operating system. Forcing users to sign up or sign in using a Microsoft Account, downloading and installing updates, and not allowing them to [proceed with a Windows installation without an internet connection](https://www.makeuseof.com/windows-11-set-up-without-internet-connection/) end up ruining the user experience.

 Moreover, confusing privacy and tracking settings take up a whole page. You need to disable the six-eight toggles to opt out of it and have to deal with pop-ups like Microsoft 365 and Xbox GamePass.

 But you can avoid all these things by selecting the **Disable data collection (Skip privacy questions)** checkbox in Rufus. If you want to keep the PC name and region settings on the target system the same as your primary system, you can select the **Set regional options to the same values as this user’s** and **Create a local account with username** checkboxes.

 However, you will need to set up a new PIN if you plan to inherit the same username and region options as your main Windows computer. Otherwise, you won’t be able to log in.

## A Frictionless Windows 11 Installation With Rufus

 Rufus can help you create a custom Windows 11 bootable drive that bypasses all the unnecessary requirements and setup pages. It is much better than using a tweaked ISO file with questionable security. Plus you don’t have to pay a dime because Rufus is completely open-source.

 There are even tweaked ISO files of Windows 11 available which bypasses both requirements before installation. However, Rufus has a better solution. It can help you prepare a Windows installation media while bypassing these requirements and adding more tweaks. Want to know more? Let’s begin.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/navigating-through-non-functioning-intel-unison-issues-in-windows-11/"><u>Navigating Through Non-Functioning Intel Unison Issues in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-captcha-troubles-in-steam/"><u>Overcoming Windows CAPTCHA Troubles in Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-adding-wordpad-shortcut-accessibility/"><u>Mastering Windows 11: Adding WordPad Shortcut Accessibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-users-guide-to-managing-monitor-luminosity/"><u>Win Users Guide to Managing Monitor Luminosity</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-youtubes-twist-rearranging-queue-from-end-to-beginning/"><u>[Updated] YouTube's Twist  Rearranging Queue From End to Beginning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-taskmanagers-dominance/"><u>Mastery Over TaskManager's Dominance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-prevent-unintentional-erasure-of-panel-settings-by-cp/"><u>Techniques to Prevent Unintentional Erasure of Panel Settings by CP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hide-windows-11-language-line-from-status-bar/"><u>Hide Windows 11 Language Line From Status Bar</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-videography-titans-battle/"><u>[New] In 2024, Videography Titans Battle</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-best-5-gif-to-video-converter-online-no-need-to-download/"><u>[Updated] Best 5 GIF to Video Converter Online [No Need to Download]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-google-chrome-from-creating-new-tabs-ownself/"><u>Preventing Google Chrome From Creating New Tabs Ownself</u></a></li>
<li><a href="https://win11-tips.techidaily.com/productive-power-up-with-top-6-windows-apps-for-organizers/"><u>Productive Power-Up with Top 6 Windows Apps for Organizers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-original-terminals-in-win11/"><u>Regaining Original Terminals in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-walkthrough-for-finding-windows-keys-losses/"><u>The Complete Walkthrough for Finding Windows Keys Losses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-resolving-file-corrupted-error-x70-on-windows-1011/"><u>Swiftly Resolving 'File Corrupted' Error X70 on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insightful-strategies-for-hardware-serial-numbers-on-windows/"><u>Insightful Strategies for Hardware Serial Numbers on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-barriers-how-to-successfully-install-java/"><u>Overcoming Barriers: How to Successfully Install Java</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-securing-sound-speed-increase-in-the-digital-world-of-spotify/"><u>In 2024, Securing Sound Speed Increase in the Digital World of Spotify</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-0x0000011b-failures-in-windows-os/"><u>How to Stop 0X0000011B Failures in Windows OS</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-dish-on-titles-creative-concepts-for-cookery-vids/"><u>[Updated] Dish on Titles  Creative Concepts for Cookery Vids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-java-vm-creation-failed-in-windows/"><u>Troubleshooting Java VM Creation Failed in Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-boost-your-files-future-with-these-20-best-in-class-no-cost-services/"><u>[New] Boost Your Files' Future with These 20 Best-in-Class No-Cost Services</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-oppo-a78-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Oppo A78 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-window-placement-with-powertoys/"><u>Personalizing Window Placement with PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-random-restarts-on-windows-11-systems/"><u>Troubleshoot Random Restarts on Windows 11 Systems</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-a-practical-guide-to-using-vsco-for-professionals/"><u>[New] A Practical Guide to Using VSCO for Professionals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-addressing-roblox-shutdown-issues-on-your-windows-machine/"><u>Swiftly Addressing Roblox Shutdown Issues on Your Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-with-ease-the-windows-11-touchpad-guide/"><u>Navigating with Ease: The Windows 11 Touchpad Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-windows-note-placement-guide/"><u>Tailored Windows Note Placement Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-mastery-building-hotkeys-for-repetitive-text-snapping-tasks/"><u>Windows 11 Mastery: Building Hotkeys for Repetitive Text Snapping Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-eliminating-webcam-dark-screen/"><u>Techniques for Eliminating Webcam Dark Screen</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-clearing-up-cacophony-3-easy-steps-to-mute-audio-echoes/"><u>2024 Approved Clearing Up Cacophony 3 Easy Steps to Mute Audio Echoes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-lost-steam-games-iconage/"><u>Solutions for Lost Steam Games Iconage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-play-your-favorite-oldschool-pc-games-with-dosbox-x/"><u>How to Play Your Favorite Oldschool PC Games With DOSBox-X</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-the-essentials-of-using-tiktok-on-both-macs-and-pcs-for-2024/"><u>[Updated] The Essentials of Using TikTok on Both Macs & PCs for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-credible-power-consumption-forecasts-in-win-11-setup/"><u>Reestablishing Credible Power Consumption Forecasts in Win 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719242997504-navigate-past-chrome-hiccups-fixes-for-w11-users/"><u>Navigate Past Chrome Hiccups: Fixes for W11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hacking-the-login-loop-in-windows-1011/"><u>Hacking the Login Loop in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-file-extraction-failures-in-windows-1110/"><u>Navigating Through File Extraction Failures in Windows 11/10</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-best-practices-for-youtube-video-brightness-and-contrast-for-2024/"><u>[New] Best Practices for YouTube Video Brightness and Contrast for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocketing-printer-speed-in-windows-realm/"><u>Skyrocketing Printer Speed in Windows Realm</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-untouched-live-visual-recorders/"><u>2024 Approved  Untouched Live Visual Recorders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalize-auto-lock-and-screensaver-interval/"><u>Personalize Auto-Lock & Screensaver Interval</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manage-widget-notifications-on-windows-11/"><u>How to Manage Widget Notifications on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-your-desktop-layout-with-one-click/"><u>Restoring Your Desktop Layout with One Click</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-more-value-black-friday-offers-at-612-win10/"><u>Get More Value: Black Friday Offers at $6.12 Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-offline-lsa-message-in-windows-os/"><u>Fixing the Offline LSA Message in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-code-0x0001-problem-in-ge-for-windows/"><u>Steps to Resolve Code 0X0001 Problem in GE for Windows</u></a></li>
</ul></div>
