---
title: Implementing a Secure Windows 11 Hardware Removal Apt
date: 2024-07-12T17:43:22.573Z
updated: 2024-07-13T17:43:22.573Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Implementing a Secure Windows 11 Hardware Removal Apt
excerpt: This Article Describes Implementing a Secure Windows 11 Hardware Removal Apt
keywords: W11 Security Hw Removal,Safe Windows Hw Removal,Hardware Uninstall Safety,Secure W11 Hardware Exit,Apt Security W11 Extraction,W11 Safe Hardware Disable,Protected Windows Hw Removal
thumbnail: https://thmb.techidaily.com/a34b3784d5ea8d0b2be6eaec5083d1cf0c7c6de5e3aae650ea39b1f4ae6fa12f.jpg
---

## Implementing a Secure Windows 11 Hardware Removal Apt

 After inserting an external USB flash drive, you can select an option on Windows 11’s system tray to eject it. The eject option is available to enable users to remove external storage devices safely. Data can get corrupted if you remove a USB drive still in use.

 The Safely Remove Hardware dialog is a window that displays all connected USB devices and enables you to stop them for safe ejection. That dialog is accessible with a Run command, but you can set up shortcuts for opening it with the methods below.

## How to Set Up a "Safely Remove Hardware" Desktop Shortcut

 The Safely Remove Hardware dialog has a long Run command that’s not easy to remember. To make that feature more directly accessible, you can create a desktop shortcut based on its command. Then you can also turn that shortcut into a taskbar, Start menu, or keyboard one. This is how to set up a Safely Remove Hardware dialog desktop shortcut in Windows 11:

1. Click anywhere on the desktop wallpaper with the mouse’s right button to select**New** and**Shortcut** .  
![The New and Shortcut options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/new-shortcut-options.jpg)
2. Input this command within the location box:  
`rundll32.exe shell32.dll,Control_RunDLL hotplug.dll`
3. Select**Next** to view the shortcut name box.
4. Delete the text in the box, and input**Safely Remove Hardware** to replace it.
5. Click**Finish** to add the Safely Remove Hardware desktop shortcut.

 Now try opening the Safely Remove Hardware window with the shortcut. Double-clicking the**Safely Remove Hardware** shortcut should open the window shown directly below. Select a listed USB device you want to remove there and click**Stop** . Clicking that button opens a**Stop** hardware device window on which you can select to stop a device before removing it.

![The Safely Remove Hardware dialog window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/safely-remove-hardware-devices-window.jpg)

 That**Stop** option is not entirely the same as an ejection one. Selecting**Eject Portable** in the system tray will merely tell you if the device is still in use or safe to remove. Clicking**Stop** will stop what’s using the drive to make the device free for removal.

![The Eject Portable option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/eject-portable-option.jpg)

 The Safely Remove Hardware window also enables you to view properties for listed devices. To do so, select a device and click the**Properties** button. That will bring up a window that includes general, event, and driver details for the device.

 The Safely Remove Hardware desktop shortcut will be blank by default. However, you can add an icon to it by following the instructions in our [guide for customizing Windows 11/10 icons](https://www.makeuseof.com/tag/customize-icon-windows/) .

## How to Set Up "Safely Remove Hardware" Taskbar and Start Menu Shortcuts

 Setting up a Safely Remove Hardware desktop shortcut will enable you to pin it to the taskbar or Start menu. To do so, right-click the Safely Remove Hardware icon on the desktop and select**Show more options** . The classic context menu in Windows 11 includes**Pin to taskbar** and**Pin to Start** menu options. So, select one of those options to create an alternative Safely Remove Hardware taskbar or Start menu shortcut.

![The Pin to taskbar option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/pin-to-taskbar-option.jpg)

 Adding Safely Remove Hardware to the taskbar or Start menu will make its desktop shortcut redundant. You can remove that desktop shortcut by right-clicking its icon and selecting**Delete** (the trash can icon).

## How to Set Up a "Safely Remove Hardware" Hotkey

 There’s no quicker way to open anything in Windows 11 than pressing a hotkey. A keyboard shortcut enables you to open anything without having to minimize windows to reach the desktop, bring up the Start menu, or move the mouse at all. You can set up a hotkey that opens the Safely Remove Hardware dialog as instructed for method one in our [how to assign keyboard shortcuts to programs on Windows](https://www.makeuseof.com/windows-keyboard-shortcuts-programs/) guide.

![The Shortcut key box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/shortcut-key-box.jpg)

 Creating such a hotkey doesn’t make the Safely Remove Hardware desktop shortcut redundant. The hotkey activates the desktop shortcut you assigned it to. So, erasing the Safely Remove Hardware desktop shortcut will delete the shortcut key.

## How to a Set Up a "Safely Remove Hardware" Context Menu Shortcut

 The context menu is an out-of-the-way place to stick shortcuts for opening things. Adding a Safely Remove Hardware option there will enable you to access that dialog by right-clicking the desktop area. Such a shortcut will probably be preferable for users who prefer to minimize desktop and taskbar clutter.

 However, this final method for creating a Safely Remove Hardware shortcut involves editing the registry because Windows 11 doesn’t include any editing feature for customizing the context menu. The registry tweak is a relatively straightforward one to apply that adds a couple of new keys. Follow these steps exactly as specified to add a**Safely Remove Hardware** option to the context menu:

1. Press**Start** (the taskbar menu button) and click inside the search box.
2. Enter**Registry Editor** inside the file search tool and select to open that app from the results.
3. Delete whatever text is in Registry Editor’s address bar, and input this key location there:  
`Computer\HKEY_CLASSES_ROOT\DesktopBackground\Shell\`
4. Then right-click the Shell key and select**New** to bring up a context menu submenu.
5. Select the**Key** option to add a new registry entry.

1. Type**Safely Remove Hardware** inside the key’s text box.
2. Then right-click the newly added**Safely Remove Hardware** registry entry and select the**New** \>**Key** options.
3. Input**command** to be the second key’s title.
4. Select the newly added**command** registry entry and double-click its**(Default)** string value.
5. Then input the following Safely Remove Hardware dialog location inside the**Data value** box:  
`C:\\Windows\\System32\\control.exe hotplug.dll`
6. Click**OK** to confirm the new value.

 Now you can have a look at what you’ve just added to Windows 11’s context menu. Right-click an empty part of your desktop area to select Show more options, which opens the secondary classic menu. Select the**Safely Remove Hardware** option on the classic context menu to bring up that window.

![The Safely Remove Hardware context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/safely-remove-hardware-option.jpg)

 That option can be easily removed from the context menu if you decide not to keep it there. To remove it, return to the registry key specified in step three above; right-click the**Safely Remove Hardware** key you added and select**Delete** . Then select**Yes** to delete the key.

## Utilize the Safely Remove Hardware Dialog Faster on Windows

 Creating a Safely Remove Hardware shortcut with any method above will make that dialog window more accessible whenever you need to remove a device. That dialog provides a handy alternative way for users to safely remove USB drives with additional options for viewing device details. You can use that dialog to view properties for connected drives and select to stop them so they can be removed without corrupting data.

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
<li><a href="https://win11-tips.techidaily.com/accessing-outlook-preview-via-windows-11-os/"><u>Accessing Outlook Preview via Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363006980-discover-solutions-for-programs-that-dont-work-on-vistawindows-7/"><u>Discover Solutions for Programs that Don't Work on Vista/Windows 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719284654722-software-environment-setup/"><u>Software Environment Setup:</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-towards-improved-security-extending-pins-in-oses/"><u>A Step Towards Improved Security: Extending PINs in OSes</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/find-the-perfect-skype-tone-from-these-sites-for-2024/"><u>Find the Perfect Skype Tone From These Sites for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-easy-ways-to-disable-a-user-account-on-windows-11/"><u>4 Easy Ways to Disable a User Account on Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-explore-10-premier-yoga-streams-for-wellness-boost/"><u>[Updated] 2024 Approved  Explore 10 Premier Yoga Streams for Wellness Boost</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-potential-exciting-enhancements-from-w11-22h2-moment/"><u>7 Potential Exciting Enhancements From W11 22H2 Moment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-detailed-walkthrough-of-using-system-restore-in-windows-os/"><u>A Detailed Walkthrough of Using System Restore in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719319213526-essential-tips-for-a-working-winshift/"><u>Essential Tips for a Working WinShift.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-balanced-screen-viewing-a-step-by-step-guide-to-90-degree-rotation/"><u>Achieving Balanced Screen Viewing: A Step-by-Step Guide to 90-Degree Rotation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-command-line-capers-for-the-tech-whimsical/"><u>5 Command Line Capers for the Tech Whimsical</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-empty-display-of-system-startups/"><u>Addressing the Empty Display of System Startups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719306931208-opening-troubled-chrome-remediation-tips-for-win11-users-here/"><u>Opening Troubled Chrome: Remediation Tips for Win11 Users Here.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-sevenfold-approach-to-fix-sync-errors-with-google-drive/"><u>A Sevenfold Approach to Fix Sync Errors with Google Drive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-could-not-initiate-jvm-in-windows-environment/"><u>Addressing Could Not Initiate JVM in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-mastery-accessing-windows-admin-settings/"><u>Achieving Mastery: Accessing Windows Admin Settings</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-top-10-best-action-cameras-for-diving-or-snorkelling-2023-update/"><u>[New] Top 10 Best Action Cameras For Diving Or Snorkelling -2023 Update</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-primeplay-videoapp-inspection/"><u>2024 Approved  PrimePlay VideoApp Inspection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-windows-solid-state-drive-power-of-fresh/"><u>Accelerate Your Windows' Solid State Drive - Power of Fresh</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-ways-to-create-a-windows-11-bootable-usb-drive/"><u>3 Ways to Create a Windows 11 Bootable USB Drive</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-conveying-content-via-discord-optimizing-video-sharing-for-2024/"><u>[Updated] Conveying Content via Discord  Optimizing Video Sharing for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719347202341-unveiling-the-full-potential-of-windows-snip-and-sketch-capabilities/"><u>Unveiling the Full Potential of Windows' Snip and Sketch Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-android-innovations-to-transform-your-windows-11-setup/"><u>6 Android Innovations to Transform Your Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-detailed-walkthrough-of-chromium-installation-in-windows-11/"><u>A Detailed Walkthrough of Chromium Installation in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-total-screen-capture-mastery-using-snip-and-sketch/"><u>Achieving Total Screen Capture Mastery Using Snip & Sketch.</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/things-you-should-know-when-unlocking-total-wireless-of-iphone-13-pro-drfone-by-drfone-ios/"><u>Things You Should Know When Unlocking Total Wireless Of iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719298161302-overcoming-grayed-out-screensaver-in-win-os-top-fixes/"><u>Overcoming Grayed-Out Screensaver in Win OS: Top Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-secure-windows-options-when-bitlocker-isnt-available/"><u>5 Secure Windows Options when Bitlocker Isn't Available</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-11s-fast-assist-procedure/"><u>Activating Windows 11’S Fast Assist Procedure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guidetosettingupdarkinterfaceonwinnotepad/"><u>A GuideToSettingUpDarkInterfaceOnWinNotepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363450902-mastering-the-art-of-total-windows-screen-capturing-with-these-4-tips/"><u>Mastering the Art of Total Windows Screen Capturing with These 4 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-the-most-ignored-yet-crucial-windows-11-features/"><u>A Guide to the Most Ignored Yet Crucial Windows 11 Features</u></a></li>
<li><a href="https://extra-tips.techidaily.com/seizing-stability-eliminating-instability/"><u>Seizing Stability  Eliminating Instability</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/why-is-ipogo-not-working-on-motorola-defy-2-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Motorola Defy 2? Fixed | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719284325307-chrome-opening-woes-resolved-fast-fixed-for-windows-11-users/"><u>Chrome Opening Woes Resolved: Fast Fixed for Windows 11 Users.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-quick-ways-to-disable-usb-selective-suspend-in-windows-11/"><u>3 Quick Ways to Disable USB Selective Suspend in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719285972506-windows-error-trouble-with-compatibility-tool-here-are-quick-solutions/"><u>Windows Error: Trouble with Compatibility Tool? Here Are Quick Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-serenity-windows-sleep-mode-guide/"><u>Achieving Serenity: Windows Sleep Mode Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-deep-dive-into-surface-laptop-studio-2s-creative-edge/"><u>A Deep Dive Into Surface Laptop Studio 2’S Creative Edge</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-vivo-s18-pro-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Vivo S18 Pro | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-discords-broadcasting-features-unveiled-a-step-by-step-guide/"><u>In 2024, Discord's Broadcasting Features Unveiled  A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-optimum-ssd-speed-on-windows-via-ssdfresh/"><u>Achieve Optimum SSD Speed on Windows via SSDFresh</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-errors-caused-by-organization-managed-features-on-windows-11/"><u>Addressing Errors Caused by Organization-Managed Features on Windows 11</u></a></li>
</ul></div>
