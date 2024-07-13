---
title: "Restoring USB Health in Windows: A Troubleshooting Checklist"
date: 2024-07-12T16:29:53.909Z
updated: 2024-07-13T16:29:53.909Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Restoring USB Health in Windows: A Troubleshooting Checklist"
excerpt: "This Article Describes Restoring USB Health in Windows: A Troubleshooting Checklist"
keywords: USB Recovery Guide,Fixing USB Issues,Healthy USB Windows,USB Troubleshoot Steps,Revive USB Connectivity,Restoring USB Functions,Windows USB Diagnostics
thumbnail: https://thmb.techidaily.com/61e1fbca092ac5d2ffa00e76582e3823f6ee9bd8608e03fb6613489ba0869657.jpg
---

## Restoring USB Health in Windows: A Troubleshooting Checklist

 Have your PC or laptop USB ports stopped working? To fix this, you need to diagnose the root of the problem. Here's everything you need to know to quickly get your USB ports working again on any PC or laptop.

## Think Your USB Port Is Not Working? Test It

 Before proceeding, be sure that it is the port that is faulty, rather than the device you're connecting.

 To establish which is the problem, you'll need to know how to troubleshoot the USB port. This means knowing how to test the USB port.

 Start by connecting the device to another USB port. If it works, then the problem is the first port; if the device remains undetected, you have a faulty device. (Note that if you can't [reformat the USB drive](https://www.makeuseof.com/tag/format-usb-drive/), it will need replacing.)

![Have your USB ports stopped working?](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/03/muo-diy-fix-USB-ports.jpg)

 If there's a problem with your USB port, you'll notice it thanks to either of these things:

* The connected device fails to be detected
* Your operating system displays an error message relating to the device (removing and replacing the device might solve this)

 Either way, you should investigate the state of the USB port. Has it been damaged in any way? The safest way to find out is to shut down your PC or laptop.

 Next, look at the USB port. Is it clean and dust free? There's a chance that dirt, dust, and general detritus might have become embedded in the port. This can happen with laptop and desktop computers alike.

 Dust will reduce airflow, causing your system to overheat. It is particularly damaging to laptops, where [overheating can reduce performance in seconds](https://www.makeuseof.com/tag/fix-overheating-laptop/). To fix this, clean out the USB port with a can of compressed air. A vacuum cleaner might also prove handy here.

 Finally, grab a USB cable (or flash drive) and gently wiggle it around. If the drive is moving and feels loose---typically this will be up and down---then you have a problem.

## How to Fix a Broken USB Port on PC and Laptop

 We'll look at some software fixes in a moment, but first, what if the USB port is loose?

 USB ports are soldered to a board within your computer. This may be the motherboard but is typically a secondary printed circuit board (PCB). With regular use, ports can become movable, at times completely unattached.

 Often, this is down to the shape of the connected USB devices. While small Wi-Fi, Bluetooth, and even new USB flash memory are unlikely to put any significant strain on the port's physical connection, older "stick" memory drives are a different story. So are USB cables; their size and associated weight act as a sort of lever, contributing to USB ports working loose.

 If you suspect that your motherboard USB ports are not working, replacing them isn't easy. On a desktop computer, you may be able to find a replacement board that can be slotted in without too much effort. Want to know how to fix a USB port on a laptop? It's going to take a soldering iron.

 Of course, you could take this to an expert for repair, but there will be associated costs with this. If you want to do it yourself, make sure you [learn how to solder](http://www.makeuseof.com/tag/learn-solder-simple-tips-projects/). If you're not sure, check out the software fixes first.

## Can Restarting a Computer Fix Broken USB Ports?

 "Have you tried turning it off and back on again?"

 This old tech support standby is well-known for a reason: it works!

 With your unrecognized USB device correctly inserted into the suspect USB port, restart your computer. Once the operating system has rebooted, it should detect the USB device. If not, it's worth looking at the device in the Windows device manager.

## How to Check USB Ports on Windows 10 With Device Manager

 Device Manager is a system tool in Windows that lists devices attached to your computer. They’re grouped into categories, listed alphabetically, which enables you to quickly find the device you’re looking for.

 To check the status of your USB ports in Windows 10 and 11:

1. Right-click **Start** and select **Device Manager**  
![Open Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/03/muo-diy-fix-USB-ports-device-mgr.png)
2. **Browse the list for** **Universal Serial Bus controllers**
3. Expand this and look for the **USB Host Controller**(your device may have a longer title, but it will feature those three words)  
![Find the USB Host Controller](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/03/muo-diy-fix-USB-ports-device-mgr-host-controller.png)
4. Right-click USB Host Controller (and any duplicates) and select **Uninstall**  
![Uninstall USB Host Controller](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/03/muo-diy-fix-USB-ports-device-mgr-host-controller-uninstall.png)
5. Restart your computer
6. If no USB Host Controller is listed, click **Scan for hardware changes** on the toolbar

 If you're using a USB mouse and keyboard, it will be disabled while the USB Host Controllers are uninstalled.

## Have Power Settings Stopped Your USB Ports Working?

 If power management settings are overriding your USB controller, this will impact the detection of USB devices. It will appear that USB is not working, but in fact the operating system has put the device to sleep.

 This is particularly relevant if you think your laptop USB port is not working. However, if you're keen to reduce power usage, you might have set your Windows 10 desktop to low power.

**USB Selective Suspend** is a power saving setting that cuts power to the USB device, thereby reducing battery use.

 The feature usually works well, but at times makes it look as if there is a problem with your USB ports.

 Fix this by opening the Windows Control Panel and adjusting the settings.

1. Click **Start** and enter **control panel**
2. Select the corresponding result
3. Go to **Hardware and Sound > Power Options**
4. Here, find the selected plan and click **Change plan settings > Change advanced power settings**
5. Find **USB Settings** and expand to find **USB selecting suspend setting**
6. Change the drop-down menu to **Disabled**  
![Alter USB power settings in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/muo-windows-dead-usb-suspend-bg-2022.jpg)
7. Click **Apply** and **OK** to confirm
8. Finally, reboot your PC to ensure this change is applied

 You should find that any USB ports that were not working have now been fixed.

## USB Port Still Not Working? Reset the BIOS/UEFI Settings

 Your BIOS/UEFI exists to help provide a low-level interface between the hardware, software, and firmware on your computer. In other words, it helps all the major components of your PC combine and work together. In terms of specific functions, it helps you carry out the boot-up process, hardware initialization, system configuration, firmware updates, and so on.

 It's no wonder, then, that any tampered settings in your BIOS or UEFI will leave a variety of problems in its wake, including a malfunctioning USB port. So if you've reason to believe something has gone wrong with the BIOS/UEFI settings, we suggest resetting its settings.

 Check out [how to enter the BIOS settings on Windows](https://www.makeuseof.com/tag/enter-bios-computer/) for instructions. If it was indeed a faulty BIOS/ UEFI stopping your USB port from working properly, then everything will be back to normal after a reset.

## You've Fixed Your Broken USB Port

 As you can see, you have several options for repairing an unresponsive USB port. In most cases, it won't be dead, and you'll be able to fix it.

 USB ports aren't the only potential weak spots on your computer. Looking after your hardware will reduce potential failures, and you can save a lot of money if you know how to test your PC for failing hardware.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-based-audacity-crash-code-9999/"><u>Fixing Windows-Based Audacity Crash Code 9999</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-apple-iphone-14-pro-max-drfone-by-drfone-virtual-ios/"><u>What is the best Pokemon for pokemon pvp ranking On Apple iPhone 14 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-screen-lock-pin-on-vivo-s17-like-a-pro-5-easy-ways-by-drfone-android/"><u>How To Remove Screen Lock PIN On Vivo S17 Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-straightforward-steps-simplified-laptop-screening-on-dell/"><u>In 2024, Straightforward Steps  Simplified Laptop Screening on Dell</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-hidden-techniques-for-private-anonymous-instagram-live-participation/"><u>[New] The Hidden Techniques for Private, Anonymous Instagram Live Participation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-identity-under-threat-are-biometrics-safe/"><u>Windows Identity Under Threat: Are Biometrics Safe?</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/button-pressing-on-keyboards-the-uk-us-disparity/"><u>Button Pressing on Keyboards: The UK-US Disparity</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-exploring-the-hottest-stock-photos-and-their-journeys/"><u>In 2024, Exploring the Hottest Stock Photos & Their Journeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-steam-cloud-syncs-in-win-10/"><u>Fixing Steam Cloud Syncs in Win 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-the-reset-failure-count-for-incorrect-login-attempts-on-windows-11/"><u>Configuring the Reset Failure Count for Incorrect Login Attempts on Windows 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/unveiling-the-best-video-grabber-listings-for-2024/"><u>Unveiling the Best Video Grabber Listings for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-using-the-netstat-command-in-win11/"><u>A Step-by-Step Approach: Using the Netstat Command in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-overcapacity-alerts-for-gpt-service/"><u>Counteracting Overcapacity Alerts for GPT Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-pc-reawakening-top-3-windows-reset-methods/"><u>Efficient PC Reawakening: Top 3 Windows Reset Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ephemeral-approach-to-suspending-windows-11-protection-systems/"><u>Ephemeral Approach to Suspending Windows 11 Protection Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workflow-enhancer-integrating-sticky-notes-into-your-windows-morning-ritual/"><u>Workflow Enhancer: Integrating Sticky Notes Into Your Windows Morning Ritual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wrinkle-free-up-operator-installation/"><u>Windows Wrinkle? Free Up Operator Installation</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-examining-the-income-mechanics-of-tseries-on-youtube/"><u>[New] In 2024, Examining the Income Mechanics of TSeries on YouTube</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/mastering-live-streams-from-your-gopro-camera-to-social-networks/"><u>Mastering Live Streams From Your GoPro Camera to Social Networks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-the-battle-against-freezes-in-apex-legends/"><u>Winning the Battle Against Freezes in Apex Legends</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-streamlining-picture-shading-with-adobe-tools/"><u>In 2024, Streamlining Picture Shading with Adobe Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparative-analysis-understanding-the-variance-between-non-microsoft-and-microsoft-account-in-os/"><u>Comparative Analysis: Understanding the Variance Between Non-Microsoft and Microsoft Account in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-win-pcs-voice-input-problems/"><u>Diagnosing Win PCs' Voice Input Problems</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/-tips-to-get-more-views-with-youtube-optimization-free-checklist-for-2024/"><u>[New] 5 Tips to Get More Views with YouTube Optimization [Free Checklist] for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-mastering-elegant-mosaic-imagery-fusions/"><u>In 2024, Mastering Elegant Mosaic Imagery Fusions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/defend-with-confidence-top-4-password-protectors-for-win-11-users/"><u>Defend With Confidence: Top 4 Password Protectors for Win 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-things-to-try-when-prime-videos-subtitles-arent-working-on-windows-11/"><u>4 Things to Try When Prime Video's Subtitles Aren't Working on Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/boosting-streams-switching-to-av1-in-youtubes-settings-for-2024/"><u>Boosting Streams  Switching to AV1 in YouTube's Settings for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-nokia-c12-pro-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Nokia C12 Pro without App | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-closer-look-at-ais-individuality-and-innovation/"><u>A Closer Look at AI's Individuality and Innovation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ancient-pc-modern-atlasos/"><u>Ancient PC, Modern AtlasOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-fix-the-sorry-there-is-a-problem-with-the-onedrive-servers-error-on-windows/"><u>6 Ways to Fix the “Sorry, There Is a Problem With the OneDrive Servers” Error on Windows</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-holographic-horizons-trendsetting-wallpapers/"><u>[Updated] Holographic Horizons  Trendsetting Wallpapers</u></a></li>
<li><a href="https://extra-resources.techidaily.com/10-advanced-techniques-to-master-with-canva-designer/"><u>10 Advanced Techniques to Master with Canva Designer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-directdraw-errors-with-ease-on-new-windows-oses/"><u>Fixing DirectDraw Errors with Ease on New Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disentangle-onedrive-and-microsoft-account-on-windows-machine/"><u>Disentangle OneDrive & Microsoft Account on Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-try-now-bluetooth-hurdle-on-pcs-and-tablets/"><u>Bypass 'Try Now' Bluetooth Hurdle on PCs & Tablets</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-8-best-video-conferencing-software-for-small-business-safe-and-stable/"><u>In 2024, 8 Best Video Conferencing Software for Small Business (Safe and Stable)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-storage-activating-windows-11s-compression/"><u>Efficient Storage: Activating Windows 11’S Compression</u></a></li>
</ul></div>
