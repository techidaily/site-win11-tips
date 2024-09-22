---
title: How to Create a Safely Remove Hardware Dialog Shortcut in Windows 11
date: 2024-09-21T02:30:26.410Z
updated: 2024-09-22T06:14:00.750Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Create a Safely Remove Hardware Dialog Shortcut in Windows 11
excerpt: This Article Describes How to Create a Safely Remove Hardware Dialog Shortcut in Windows 11
keywords: Hardware Shortcut Creation,Removing HW Dialog Windows,Safe Hardware Uninstall,Windows 11 HW Tools,HW Dialog Window Access,Security in Windows Uninstall,Quick Hardware Remove Guide
thumbnail: https://thmb.techidaily.com/0a8efd832e4ff850ed2946c105917f658a3e5ec7d74782a26831b6d30a49981c.jpg
---

## How to Create a Safely Remove Hardware Dialog Shortcut in Windows 11

 After inserting an external USB flash drive, you can select an option on Windows 11’s system tray to eject it. The eject option is available to enable users to remove external storage devices safely. Data can get corrupted if you remove a USB drive still in use.

 The Safely Remove Hardware dialog is a window that displays all connected USB devices and enables you to stop them for safe ejection. That dialog is accessible with a Run command, but you can set up shortcuts for opening it with the methods below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

## How to Set Up "Safely Remove Hardware" Taskbar and Start Menu Shortcuts

 Setting up a Safely Remove Hardware desktop shortcut will enable you to pin it to the taskbar or Start menu. To do so, right-click the Safely Remove Hardware icon on the desktop and select**Show more options** . The classic context menu in Windows 11 includes**Pin to taskbar** and**Pin to Start** menu options. So, select one of those options to create an alternative Safely Remove Hardware taskbar or Start menu shortcut.

![The Pin to taskbar option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/pin-to-taskbar-option.jpg)

 Adding Safely Remove Hardware to the taskbar or Start menu will make its desktop shortcut redundant. You can remove that desktop shortcut by right-clicking its icon and selecting**Delete** (the trash can icon).

## How to Set Up a "Safely Remove Hardware" Hotkey

 There’s no quicker way to open anything in Windows 11 than pressing a hotkey. A keyboard shortcut enables you to open anything without having to minimize windows to reach the desktop, bring up the Start menu, or move the mouse at all. You can set up a hotkey that opens the Safely Remove Hardware dialog as instructed for method one in our[how to assign keyboard shortcuts to programs on Windows](https://www.makeuseof.com/windows-keyboard-shortcuts-programs/) guide.

![The Shortcut key box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/shortcut-key-box.jpg)

 Creating such a hotkey doesn’t make the Safely Remove Hardware desktop shortcut redundant. The hotkey activates the desktop shortcut you assigned it to. So, erasing the Safely Remove Hardware desktop shortcut will delete the shortcut key.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027195/19272" target="_top" id="2027195">
  <img src="//a.impactradius-go.com/display-ad/19272-2027195" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027195/19272" style="position:absolute;visibility:hidden;" border="0" />
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

 That option can be easily removed from the context menu if you decide not to keep it there. To remove it, return to the registry key specified in step three above; right-click the**Safely Remove Hardware** key you added and select**Delete** . Then select**Yes** to delete the key.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997648/19272" target="_top" id="1997648">
  <img src="//a.impactradius-go.com/display-ad/19272-1997648" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997648/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-animate-and-make-your-own-effects/"><u>[New] In 2024, How to Animate and Make Your Own Effects</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/astering-youtubes-creative-commons-licensing-guide/"><u>[New] Mastering YouTube’s Creative Commons Licensing Guide</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-insight-into-quadcopters-functionality-uncovered/"><u>[Updated] 2024 Approved Insight Into Quadcopters Functionality Uncovered</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-top-tech-gadgets-for-effortless-virtual-meetings-capture/"><u>[Updated] In 2024, Top Tech Gadgets for Effortless Virtual Meetings Capture</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unique-outro-music-files-at-your-fingertips-free/"><u>2024 Approved Unique Outro Music Files at Your Fingertips - Free</u></a></li>
<li><a href="https://youtube-web.techidaily.com/s-galaxy-a-thousand-stars-in-gaming/"><u>Gamers' Galaxy A Thousand Stars in Gaming</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-asus-rog-phone-8-pro-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Asus ROG Phone 8 Pro Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-gaming-potential-tackling-fps-challenges-in-valorant/"><u>Maximize Gaming Potential: Tackling FPS Challenges in Valorant</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/maximizing-your-story-potential-with-instagram-highlights-for-2024/"><u>Maximizing Your Story Potential with Instagram Highlights for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-sleep-how-to-schedule-idle-time-out-on-windows-11/"><u>Secure Sleep: How to Schedule Idle Time-Out on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-resolve-0xc0000005-problem-in-windows/"><u>Strategies to Resolve 0Xc0000005 Problem in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-overcoming-windows-11-error/"><u>Understanding and Overcoming Windows 11 Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-win11s-comic-viewing-protocols/"><u>Unlocking Win11's Comic Viewing Protocols</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-the-yearly-update-plan-means-for-your-windows-11-experience/"><u>What The Yearly Update Plan Means for Your Windows 11 Experience</u></a></li>
</ul></div>

