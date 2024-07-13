---
title: Master the Art of Hyper-V Installation on W11 Home Systems
date: 2024-07-12T17:30:49.650Z
updated: 2024-07-13T17:30:49.650Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Master the Art of Hyper-V Installation on W11 Home Systems
excerpt: This Article Describes Master the Art of Hyper-V Installation on W11 Home Systems
keywords: Hyper-V Setup Guide,Virtualization Basics,W11 VM Deployment,VPS Installation Tips,Home Systems VM,Hyper-V Techniques,Windows 11 Virtualization
thumbnail: https://thmb.techidaily.com/5f5f5b93e7d5296621d28cc46446de06ad76f2671bd83441f8c16419df01fcdb.jpg
---

## Master the Art of Hyper-V Installation on W11 Home Systems

 You can enable Hyper-V in Windows 11 as an optional feature included by default with the operating system. It lets you create virtual machines to install and run the guest OS on virtual hardware. However, Hyper-V is only available for the Pro, Education, and Enterprise edition of the OS. If you are using the Home edition, you have to rely on a third-party virtual machine manager.

 If you don’t want to use a third-party virtual machine manager, here is how to install Hyper-V on Windows 11 Home using a batch script hack.

## How to Enable Hardware Virtualization in Windows 11
![enable hardware virtualization bios hp laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hardware-virtualization-bios-hp-laptoop-1.jpg)

 Hyper-V is a bare-metal hypervisor and requires [Hardware Virtualization enabled in BIOS to work](https://www.makeuseof.com/what-is-virtualization-and-what-is-it-for/). Most modern systems support Hardware Virtualization, and you can enable it in BIOS.

 The below steps are for an HP laptop. Refer to the user manual or Knowledge Base resources on the computer manufacturer's website for other systems.

 To enable Hardware Virtualization in BIOS:

1. Shut down your PC if it is powered on.
2. Press the **Power** button to turn on the computer and then start pressing the **F10 key** to enter BIOS. The BIOS setup key varies depending on the manufacturer. So, use **F10, F2, F12, F1,** or **DEL** and see which one works for you.
3. Once in the BIOS Setup utility, open the **Configuration** tab.
4. Use the down arrow key and highlight **Virtualization Technology.**
5. Hit **Enter** and then select **Enabled**. Press **Enter** again to make the selection.
6. Next, press **F10** to save the changes and exit **BIOS**.
7. Your PC will restart with the Hardware Virtualization enabled. Now you can continue to install Hyper-V on your system.

## How to Install Hyper-V on Windows 11 Home

 The next step is to create and run a batch script to install the required files to enable Hyper-V in Windows 11 Home.

 Before you proceed with the next set of steps, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). This will help you restore your computer to its current state if something goes wrong during the process.

 To enable Hyper-V in Windows 11 Home:

 1\. Open a new Notepad file. To do this, press **Win + R**, type notepad, and click **OK.**

![hyper v install windows 11 home script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/hyper-v-install-windows-11-home-script.png)

 2\. In the Notepad file, copy and paste the following script:

`pushd "%~dp0"  
dir /b %SystemRoot%\servicing\Packages\*Hyper-V*.mum >hyper-v.txt  
for /f %%i in ('findstr /i . hyper-v.txt 2^>nul') do dism /online /norestart /add-package:"%SystemRoot%\servicing\Packages\%%i"  
del hyper-v.txt  
Dism /online /enable-feature /featurename:Microsoft-Hyper-V -All /LimitAccess /ALL  
pause`

 3\. Press **Ctrl + S** to open the save dialog.

 4\. In the file name field, type **hyperv.bat.** The **.bat** extension at the end of the file name is important to execute the script.

![save hyperv install script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/save-hyperv-install-script.png)

 5\. Next, click the drop-down for **Save as type** and select **All Files.**

 6\. Click the **Save** button to save the file.

![run hyperv bat script administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/run-hyperv-bat-script-administrator.png)

 7\. Next, right-click on the **hyperv.bat** file and select **Run as administrator**. Click **Yes** if prompted by User Account Control.

 8\. The scrip will start executing in the Command Prompt to install Hyper-V. It may take a while, so wait till the process is complete.

 9.Once completed, you will see the Operation completed successfully message.

![install hyper v install windows 11 home](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/install-hyper-v-install-windows-11-home.png)

 10\. Type **Y** to confirm and restart your PC. If not, enter N to exit the Command Prompt.

 Note that you will need to restart your PC to apply the changes. After the restart, you should have Hyper-V installed in Windows 11 Home. Type Hyper-V in Windows search and click on Hyper-V Manager to create new a virtual machine.

 If it is still not available, you can [enable Hyper-V using the Windows Features dialog](https://www.makeuseof.com/windows-11-enable-hyper-v/), Command Prompt, and Windows PowerShell.

 Here's how you can quickly add Hyper-V to Windows 11 using Command Prompt:

1. Press the **Win** key and type **cmd**. Then right-click on **Command Prompt** and select **Run as administrator.**  
![enable hyper v command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-command-prompt.png)
2. In the Command Prompt window, type the following command and press **Enter**:  
`<code>DISM /Online /Enable-Feature /All /FeatureName:Microsoft-Hyper-V`
3. The above command uses the Deployment Imaging Service and Management (DISM) tool to enable Microsoft Hyper-V and the necessary dependencies on your Windows computer. The operation completed successfully message means you have successfully enabled Hyper-V.

## How to Disable Hyper-V on Windows 11 Home
![disable hyper v windows 11 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/disable-hyper-v-windows-11-windows-features.jpg)

 You can disable Hyper-V in Windows 11 Home using the Windows Features dialog.

 To disable Hyper-V:

1. Press **Win + R** to open the **Run** dialog box.
2. Type **optionalfeatures.exe** and click **OK**.
3. In the **Windows Features** dialog, locate the Hyper-V option.
4. Uncheck the **Hyper-V** option and click **OK**. Wait for the uninstallation process to complete.
5. Next, click on **Restart Now** to restart your PC and apply the changes.

 Apart from Hyper-V, the Windows OS features another nifty virtualization solution, Windows Sandbox—a lightweight desktop environment to run applications in isolation. You can [enable Windows Sandbox from Windows Features](https://www.makeuseof.com/enable-set-up-windows-sandbox-windows-11/), but only on the Pro and Enterprise edition of the OS.

 Unlike Hyper-V, there is no batch script hack to install the sandbox app on the Home edition of Windows 11\. Instead, you can use one of the [Windows Sandbox Alternatives for Windows](https://www.makeuseof.com/windows-11-sandbox-alternatives/) to run and test applications in isolation.

## Run Hyper-V on Windows 11 Home

 Microsoft has officially restricted the use of Hyper-V to the Pro, Education, and Enterprise edition of the OS. However, a little tweak in the BIOS and a handy batch script can help you install Hyper-V on Windows 11 Home.

 Once you have Hyper-V up and running, you can install Windows, Ubuntu, and other supported operating systems in a virtual machine.

 If you don’t want to use a third-party virtual machine manager, here is how to install Hyper-V on Windows 11 Home using a batch script hack.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook.techidaily.com/masked-manipulations-how-design-misguides-us/"><u>Masked Manipulations: How Design Misguides Us</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-keyboard-shortcuts-to-access-windows-ease-of-access/"><u>5 Keyboard Shortcuts to Access Windows Ease of Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-steps-to-tame-the-gpu-hungry-desktop-window-manager/"><u>7 Steps to Tame the GPU-Hungry Desktop Window Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-command-line-capers-for-the-tech-whimsical/"><u>5 Command Line Capers for the Tech Whimsical</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-executing-the-last-goodbye-to-your-instagram-account/"><u>[New] Executing the Last Goodbye to Your Instagram Account</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/instas-best-practices-choosing-videography-sizes-and-formats-for-2024/"><u>Insta's Best Practices - Choosing Videography Sizes & Formats for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719274715388-how-to-organize-your-notes-visually-with-obsidian-canvas/"><u>How to Organize Your Notes Visually with Obsidian Canvas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-secure-windows-options-when-bitlocker-isnt-available/"><u>5 Secure Windows Options when Bitlocker Isn't Available</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-crystal-clear-captures-selecting-webcams-for-impeccable-podcasts/"><u>2024 Approved  Crystal Clear Captures  Selecting Webcams for Impeccable Podcasts</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-14-pro-phone-password-without-factory-reset-by-drfone-android/"><u>How to Unlock Xiaomi 14 Pro Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-beam-it-up-15-must-haves-for-your-youtube-live-stream/"><u>[New] Beam It Up! 15 Must-Haves for Your YouTube Live Stream</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-nokia-105-classic-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Nokia 105 Classic Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-windows-solid-state-drive-power-of-fresh/"><u>Accelerate Your Windows' Solid State Drive - Power of Fresh</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-routes-to-activate-telnet-in-windows-11-os/"><u>3 Routes to Activate Telnet in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-easy-ways-to-disable-a-user-account-on-windows-11/"><u>4 Easy Ways to Disable a User Account on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-guide-to-enhance-and-immerse-in-atmos-on-windows/"><u>A Complete Guide to Enhance and Immerse in Atmos on Windows</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/invisible-impact-the-underestimated-toll-of-trick-likes-for-2024/"><u>Invisible Impact  The Underestimated Toll of Trick Likes for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-top-pick-screen-capture-tools-for-apple-devices/"><u>[Updated] Top Pick  Screen Capture Tools for Apple Devices</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/restore-pristine-photos-easily-discover-top-10-online-enhancers/"><u>Restore Pristine Photos Easily  Discover Top 10 Online Enhancers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-android-innovations-to-transform-your-windows-11-setup/"><u>6 Android Innovations to Transform Your Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-towards-improved-security-extending-pins-in-oses/"><u>A Step Towards Improved Security: Extending PINs in OSes</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-mastering-the-art-of-old-facebook-features-step-by-step/"><u>[Updated] Mastering the Art of Old Facebook Features  Step-by-Step</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-infinix-hot-40-pro-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My Infinix Hot 40 Pro Wont Charge | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-potential-exciting-enhancements-from-w11-22h2-moment/"><u>7 Potential Exciting Enhancements From W11 22H2 Moment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-lossed-graphics-support-in-overwatch-2/"><u>Addressing Lossed Graphics Support in Overwatch 2</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-transforming-voices-with-technology-the-best-software-to-watch-out-for/"><u>New Transforming Voices with Technology The Best Software to Watch Out For</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-the-most-extensive-selection-of-free-illustrator-portals/"><u>2024 Approved  The Most Extensive Selection of Free Illustrator Portals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719356387702-stuck-google-chrome-on-win11-try-these-immediate-actions/"><u>Stuck Google Chrome on Win11? Try These Immediate Actions</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-examining-updates-the-2023-samsung-bd-j5900/"><u>2024 Approved  Examining Updates  The 2023 Samsung BD-J5900</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-balanced-screen-viewing-a-step-by-step-guide-to-90-degree-rotation/"><u>Achieving Balanced Screen Viewing: A Step-by-Step Guide to 90-Degree Rotation</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-enhance-zoom-videos-efficiently-with-top-three-methods/"><u>[New] 2024 Approved  Enhance Zoom Videos Efficiently with Top Three Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-eliminate-hardware-detection-faults/"><u>A Quick Guide to Eliminate Hardware Detection Faults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-deep-dive-into-surface-laptop-studio-2s-creative-edge/"><u>A Deep Dive Into Surface Laptop Studio 2’S Creative Edge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-serenity-windows-sleep-mode-guide/"><u>Achieving Serenity: Windows Sleep Mode Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719319213526-essential-tips-for-a-working-winshift/"><u>Essential Tips for a Working WinShift.</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/unlocking-youtube-studios-power-for-professional-edits/"><u>Unlocking YouTube Studio's Power for Professional Edits</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-start-crafting-movies-xp-edition-install-guide/"><u>[Updated] Start Crafting Movies  Xp Edition Install Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-total-screen-capture-mastery-using-snip-and-sketch/"><u>Achieving Total Screen Capture Mastery Using Snip & Sketch.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363450902-mastering-the-art-of-total-windows-screen-capturing-with-these-4-tips/"><u>Mastering the Art of Total Windows Screen Capturing with These 4 Tips</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-oneplus-12r-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your OnePlus 12R | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-could-not-initiate-jvm-in-windows-environment/"><u>Addressing Could Not Initiate JVM in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363006980-discover-solutions-for-programs-that-dont-work-on-vistawindows-7/"><u>Discover Solutions for Programs that Don't Work on Vista/Windows 7</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-free-location-spoofers-to-fake-gps-location-on-your-samsung-galaxy-s23plus-drfone-by-drfone-virtual/"><u>In 2024, 10 Free Location Spoofers to Fake GPS Location on your Samsung Galaxy S23+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-mastery-accessing-windows-admin-settings/"><u>Achieving Mastery: Accessing Windows Admin Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-optimal-dns-performance-via-reset/"><u>Achieving Optimal DNS Performance via Reset</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-create-glitch-text-effect/"><u>Updated Create Glitch Text Effect</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/spotlight-on-success-top-tiktok-tweets/"><u>Spotlight on Success  Top TikTok Tweets</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-8-best-screen-capture-tools-for-linux/"><u>[New] In 2024, 8 Best Screen Capture Tools for Linux</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/understanding-user-psychology-in-youtube-shorts-template-design-for-2024/"><u>Understanding User Psychology in YouTube Shorts Template Design for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/mastering-digital-compositing-a-complete-kinemaster-green-screen-tutorial-for-2024/"><u>Mastering Digital Compositing  A Complete Kinemaster Green Screen Tutorial for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compre-written-guide-to-creating-a-trident-widget-grid-on-win11/"><u>A Compre Written Guide to Creating a Trident Widget Grid on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719285972506-windows-error-trouble-with-compatibility-tool-here-are-quick-solutions/"><u>Windows Error: Trouble with Compatibility Tool? Here Are Quick Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-outlook-preview-via-windows-11-os/"><u>Accessing Outlook Preview via Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-empty-directory-alert-in-windows-11/"><u>Addressing Empty Directory Alert in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-contacts-from-poco-x6-pro-by-fonelab-android-recover-contacts/"><u>How to Rescue Lost Contacts from Poco X6 Pro?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-precise-walkthrough-for-windows-update-resetting/"><u>A Precise Walkthrough for Windows Update Resetting</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-free-limit-breakers-for-every-story-lover/"><u>[Updated] In 2024, Free Limit Breakers for Every Story Lover</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719284325307-chrome-opening-woes-resolved-fast-fixed-for-windows-11-users/"><u>Chrome Opening Woes Resolved: Fast Fixed for Windows 11 Users.</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/unlock-the-potential-of-your-mind-learn-languages-with-mondlys-ar/"><u>Unlock the Potential of Your Mind: Learn Languages with Mondly’s AR</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-oneplus-11r-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location On Facebook Dating for your OnePlus 11R | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719347202341-unveiling-the-full-potential-of-windows-snip-and-sketch-capabilities/"><u>Unveiling the Full Potential of Windows' Snip and Sketch Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-file-transfer-times-in-battlenet-gaming/"><u>Accelerating File Transfer Times in Battle.net Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-detailed-walkthrough-of-chromium-installation-in-windows-11/"><u>A Detailed Walkthrough of Chromium Installation in Windows 11</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/ultimate-tiktok-to-mp4-recorder/"><u>Ultimate TikTok to MP4 Recorder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-guide-to-resolving-steam-setup-problems-win11-edition/"><u>A Practical Guide to Resolving Steam Setup Problems, Win11 Edition</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-master-your-automotive-tunes-top-5-mac-friendly-music-mixing-software-selections/"><u>In 2024, Master Your Automotive Tunes Top 5 Mac-Friendly Music Mixing Software Selections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-running-imessage-on-windows/"><u>A Comprehensive Guide to Running iMessage on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-newcomers-path-in-the-world-of-original-diablo/"><u>A Newcomer's Path in the World of Original Diablo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-sudden-screen-blackouts-in-winsteam/"><u>Addressing Sudden Screen Blackouts in WinSteam</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-metaverse-joke-ology-building-your-own-hilarious-memes/"><u>[Updated] Metaverse Joke-Ology  Building Your Own Hilarious Memes</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-things-you-must-know-for-screen-mirroring-apple-iphone-se-drfone-by-drfone-ios/"><u>In 2024, Things You Must Know for Screen Mirroring Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-empty-display-of-system-startups/"><u>Addressing the Empty Display of System Startups</u></a></li>
</ul></div>
