---
title: Building a Window for Secure Hardware Removal on Windows 11
date: 2025-01-23T16:34:49.515Z
updated: 2025-01-24T18:41:29.107Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Building a Window for Secure Hardware Removal on Windows 11
excerpt: This Article Describes Building a Window for Secure Hardware Removal on Windows 11
keywords: Windows Hardware Security,Secure Device Uninstall,Hardware Extraction Tool,Safe PC Deletion,11 Windows Removal,Secure Hardware Window,OS Hardware Cleanup
thumbnail: https://thmb.techidaily.com/445d6c97ace4ef05d63cde4f33374d4b0783e76d1e91d61e1ddb527be75674b2.jpg
---

## Building a Window for Secure Hardware Removal on Windows 11

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

 The Safely Remove Hardware desktop shortcut will be blank by default. However, you can add an icon to it by following the instructions in our[guide for customizing Windows 11/10 icons](https://www.makeuseof.com/tag/customize-icon-windows/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Set Up "Safely Remove Hardware" Taskbar and Start Menu Shortcuts

 Setting up a Safely Remove Hardware desktop shortcut will enable you to pin it to the taskbar or Start menu. To do so, right-click the Safely Remove Hardware icon on the desktop and select**Show more options** . The classic context menu in Windows 11 includes**Pin to taskbar** and**Pin to Start** menu options. So, select one of those options to create an alternative Safely Remove Hardware taskbar or Start menu shortcut.

![The Pin to taskbar option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/pin-to-taskbar-option.jpg)

 Adding Safely Remove Hardware to the taskbar or Start menu will make its desktop shortcut redundant. You can remove that desktop shortcut by right-clicking its icon and selecting**Delete** (the trash can icon).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/793ViIxl4tI?si=DDBkjPlPX5bZ-f1Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Set Up a "Safely Remove Hardware" Hotkey

 There’s no quicker way to open anything in Windows 11 than pressing a hotkey. A keyboard shortcut enables you to open anything without having to minimize windows to reach the desktop, bring up the Start menu, or move the mouse at all. You can set up a hotkey that opens the Safely Remove Hardware dialog as instructed for method one in our[how to assign keyboard shortcuts to programs on Windows](https://www.makeuseof.com/windows-keyboard-shortcuts-programs/) guide.

![The Shortcut key box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/shortcut-key-box.jpg)

 Creating such a hotkey doesn’t make the Safely Remove Hardware desktop shortcut redundant. The hotkey activates the desktop shortcut you assigned it to. So, erasing the Safely Remove Hardware desktop shortcut will delete the shortcut key.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 That option can be easily removed from the context menu if you decide not to keep it there. To remove it, return to the registry key specified in step three above; right-click the**Safely Remove Hardware** key you added and select**Delete** . Then select**Yes** to delete the key.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-superior-ai-photo-cutting-master/"><u>[New] 2024 Approved Superior AI Photo Cutting Master</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-crafting-compelling-video-narratives-using-captivate/"><u>[New] In 2024, Crafting Compelling Video Narratives Using Captivate</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-free-youtube-extractors-a-comprehensible-guide-for-beginners-for-2024/"><u>[Updated] Free YouTube Extractors A Comprehensible Guide for Beginners for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-windows-os-eliminating-error-code-0x800704b3/"><u>Conquering Windows OS: Eliminating Error Code 0X800704B3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ease-into-knowing-your-cpus-gen-on-windows-platform/"><u>Ease Into Knowing Your CPU’s Gen on Windows Platform</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/flight-to-perfection-assessing-gopro-karmas-capabilities-for-2024/"><u>Flight to Perfection Assessing GoPro Karma's Capabilities for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-efficiently-export-facebook-features-via-chrome-plug-ins/"><u>In 2024, Efficiently Export Facebook Features via Chrome Plug-Ins</u></a></li>
<li><a href="https://video-capture.techidaily.com/mastering-windows-animation-top-9-apps-for-high-quality-gif-capture/"><u>Mastering Windows Animation Top 9 Apps for High-Quality GIF Capture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-maze-acquire-user-sids-in-windows-11/"><u>Navigating the Maze: Acquire User SIDs in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-unable-to-open-error-in-geforce-experience/"><u>Remedy for Unable to Open Error in GeForce Experience</u></a></li>
<li><a href="https://network-issues.techidaily.com/stepwise-procedure-enable-external-network-device-in-your-pcs/"><u>Stepwise Procedure: Enable External Network Device in Your PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trimming-costs-smart-purchases-of-windows-11-codes/"><u>Trimming Costs: Smart Purchases of Windows 11 Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-4-game-changers-in-microsoft-paint-tools/"><u>Unveiling 4 Game-Changers in Microsoft Paint Tools</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-best-free-video-shrinking-software-for-windows-10-users-for-2024/"><u>Updated Best Free Video Shrinking Software for Windows 10 Users for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-the-record-secure-game-replays-with-intelligence/"><u>Winning the Record: Secure Game Replays with Intelligence</u></a></li>
</ul></div>

