---
title: Expert Tips for Effectively Assigning Shortcuts on Windows 11
date: 2024-09-01T05:14:45.626Z
updated: 2024-09-02T05:14:45.626Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expert Tips for Effectively Assigning Shortcuts on Windows 11
excerpt: This Article Describes Expert Tips for Effectively Assigning Shortcuts on Windows 11
keywords: Win11 Shortcut Tricks,Assign Shortcut W11 Guide,Efficient Shortcuts in Windows,Set W11 Keyboard Shortcuts,Windows 11 Quick Access Tips,Optimize W11 Key Binding,Advanced Win11 Hotkeys
thumbnail: https://thmb.techidaily.com/4a9b602cddaa14e95b4c74e25b7d2e53d393546d813f68c2847153dd0769193c.jpg
---

## Expert Tips for Effectively Assigning Shortcuts on Windows 11

 Context menus are the backbone of Windows—they're the little menus you see when you right-click the mouse on something. And while Windows 11 has brought in a new context menu for your desktop, there still aren’t any native customization options for it. For example, Windows 11 doesn’t include any built-in setting that enables you to add custom software shortcuts to that menu.

 Nevertheless, you can still add program shortcuts to the desktop context menu in Windows 11 by editing the registry. By doing so, you can replace desktop shortcut icons with context menu ones.

## How to Add an Edge Shortcut to the Desktop Context Menu

 As [Microsoft Edge is the default browser](https://www.makeuseof.com/how-windows-11-may-soon-force-you-to-use-microsoft-edge/) included with Windows 11, that's a software package you’ll all have to set up a context menu shortcut for. So, we’ll add an Edge shortcut to the desktop context menu for the sake of an example. This is how you can add a shortcut for that browser to the desktop context menu with a [simple tweak to the Windows registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/):

1. First, right-click the **Start** button on the taskbar and select **Run**.
2. Enter **regedit** in the Open box within Run’s window.
3. Click **OK** to [launch the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
4. Then navigate to the **Computer > HKEY\_CLASSES\_ROOT > Directory > Background > shell** registry key path.  
![The Shell registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-shell-key.png)
5. Right-click the **shell** key to select **New** and **Key** on the context menu.  
![The Key context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-key-option.png)

1. Input **Edge** as the new registry key’s title.
2. Right-click your **Edge** key and select the **New** \> **Key** options again.
3. Enter **command** to be the new subkey’s name.  
![The command registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-command-key.png)
4. Click File Explorer’s taskbar button.
5. Open Edge’s folder, which has this default path: **C:\\Program Files (x86)\\Microsoft\\Edge\\Application**.

1. Right-click msedge.exe there to select the **Copy as** **path** option shown directly below.  
![The Copy as path option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/copy-as-path-option.png)
2. Then return to the Registry Editor, and select the new **command** key you added.
3. Double-click **(Default)** for the **command** key on the right side of the window.
4. Press the **Ctrl** \+ **V** hotkey to paste the copied Edge path within the Value data box.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-edit-string-window.png)
5. Click **OK** to confirm.

 Now you can try out your new Edge context menu shortcut. Right-click the desktop and select **Show more options** to view the classic menu. Then select **Edge** there to open that browser.

![A Microsoft Edge context menu shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/edge-context-menu-shortcut.png)

 If you prefer, you can bring up the classic context menu in Windows 11 with a handy keyboard shortcut. Press the **Shift + F10** hotkey to open the menu instead. Then select your software shortcuts from there.

## How to Add Your Own Shortcuts to the Windows 11 Context Menu

 You can add a shortcut for whatever software you'd like in a similar way to adding Edge. To do this, you need to change the name of the primary registry key to match the name of the software it’s for. Then, open the program’s folder in File Explorer to copy its full path, and paste it in the Value data box for the command subkey’s **(Default)** string.

 To remove one of your software context menu shortcuts, you’ll need to open the key for it in the Registry Editor. Then right-click its primary key to select a **Delete** option. Select **Yes** to confirm and erase.

![The delete context menu option for registry keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-delete-option.png)

 This registry tweak also works much the same in Windows 10 and earlier Microsoft desktop platforms. So, this isn’t just a Windows 11 trick. As Windows 10 has a classic context menu by default, you don’t need to click **Show more options** on that menu to select the shortcut.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Add Program Shortcuts to the Context Menu With Easy Context Menu

 If you prefer not to manually edit the registry, add program shortcuts to the desktop’s context menu with Easy Context Menu. Easy Context Menu is a freeware third-party app for customizing context menus in Windows 11/10\. It enables you to add and remove shortcuts to and from the context menu. This is how you can add shortcuts for opening programs to Windows 11’s context menu with that software:

1. Open this [Easy Context Menu page](https://www.sordum.org/7615/easy-context-menu-v1-6/) in a web browser and download the app.
2. Extract the **ec\_menu** ZIP archive with a method in this article about [unzipping ZIP files in Windows 11](https://www.makeuseof.com/how-to-extract-zip-files-windows-11/).
3. Open the extracted **ec\_menu** folder and double-click the **EcMenu\_x64** file to open Easy Context Menu.
4. Click the **List Editor** button.  
![The List Editor button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/list-editor-button.jpg)
5. Press the **Add new** button.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Select the application (EXE) file for a program to add to the context menu and click **Open**.
2. Next, select **Desktop Context Menu** on the **Target Context Menu** drop-down menu for the shortcut.  
![The Target Context Menu drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/target-context-menu-drop-down-menu.jpg)
3. Click the **Show at bottom of the menu** radio button.
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
4. Press the **Save changes** button.
5. Select the checkbox for the program shortcut in the Easy Context Menu window.
6. Click the **Apply Changes** button on the Easy Context Menu window.  
![The Apply Changes button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/apply-changes-button.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
 Now you’ve added a new program shortcut to the classic context menu in Windows 11\. Bring up the classic context menu by right-clicking anywhere on the desktop and selecting **Show more options**. Then select the new software shortcut, which will be somewhere near the bottom of the classic menu.

 You can remove that shortcut and other options from the right-click menu with Easy Context Menu. To do so, click the **ContextMenu Cleaner** button; deselect the checkbox for the software shortcut to disable it on the context menu (you can still restore it later). Then click **Refresh** to save the context menu changes.

![The ContextMenu Cleaner window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/contextmenu-cleaner-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 There’s also much more you can add to the desktop’s right-click menu with Easy Context Menu than software shortcuts. Easy Context Menu includes many other checkboxes for adding various tools and turn-off options to the right-click menu. Select some of the checkboxes for system tools and turn-off options, and click **Apply Changes** to add handy shortcuts for accessing utilities and shutting down Windows to the context menu.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Make the Most Out of Windows 11’s Context Menu

 Now you can add program shortcuts to the context menu instead of flooding your desktop wallpaper or taskbar with them. That’s a great alternative place to add shortcuts because they don’t clutter your desktop. Keep your Windows 11 desktop clean and tidy by adding more shortcuts to the context menu instead.

 Nevertheless, you can still add program shortcuts to the desktop context menu in Windows 11 by editing the registry. By doing so, you can replace desktop shortcut icons with context menu ones.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-new-to-youtube-how-to-skip-the-top-8-common-errors-on-your-platform-journey/"><u>[New] New to YouTube  How to Skip the Top 8 Common Errors on Your Platform Journey</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-optimal-chuckle-inducing-layout/"><u>[New] Optimal Chuckle-Inducing Layout</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-the-quick-guide-to-capturing-and-storing-twitter-animated-content/"><u>[New] The Quick Guide to Capturing and Storing Twitter Animated Content</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-walk-of-shadows-a-comprehensive-list-of-intense-zombie-games/"><u>[New] Walk of Shadows  A Comprehensive List of Intense Zombie Games</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2023-how-to-find-videos-on-facebook-for-2024/"><u>[Updated] 2023 | How to Find Videos on Facebook for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-capturing-tv-screen-scenes-with-ease-your-ultimate-guide/"><u>[Updated] 2024 Approved  Capturing TV Screen Scenes with Ease - Your Ultimate Guide</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-expeditious-windows-file-audit-tactics/"><u>[Updated] Expeditious Windows File Audit Tactics</u></a></li>
<li><a href="https://extra-information.techidaily.com/accessing-c-span-archives-at-zero-cost-steps-included-for-2024/"><u>Accessing C-Span Archives at Zero Cost - Steps Included for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-screens-enhance-performance-on-windows-11/"><u>Clear Screens, Enhance Performance on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empowering-your-windows-mastery-of-lav-filters-application/"><u>Empowering Your Windows: Mastery of LAV Filters Application</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-why-modern-standby-fails-users/"><u>Exploring Why Modern Standby Fails Users</u></a></li>
<li><a href="https://win-blog.techidaily.com/getting-multiversus-running-on-pc-expert-tips-and-solutions/"><u>Getting MultiVersus Running on PC – Expert Tips and Solutions</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-screen-mastery-essential-free-lessons-from-youtubes-best-4-channels-for-2024/"><u>Green Screen Mastery  Essential Free Lessons From YouTube's Best 4 Channels for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-tecno-spark-10-4g-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the Tecno Spark 10 4G Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-keep-screen-distractions-at-bay-folders/"><u>How to Keep Screen Distractions at Bay: Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reestablish-offline-steam-connection-with-servers-on-pc/"><u>How to Reestablish Offline Steam Connection with Servers on PC</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-audio-enhanced-video-screen-record/"><u>In 2024, Audio-Enhanced Video Screen Record</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-change-your-apple-id-on-iphone-15-pro-max-with-or-without-password-by-drfone-ios/"><u>In 2024, How To Change Your Apple ID on iPhone 15 Pro Max With or Without Password</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-optimal-viewing-times-on-instagram-videos/"><u>In 2024, Optimal Viewing Times on Instagram Videos</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-razer-kiyo-webcam-review/"><u>In 2024, Razer Kiyo Webcam Review</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-honor-magic-6-pro-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Honor Magic 6 Pro? Look No Further | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-hardware-4-techniques-for-opening-the-disk-editor-in-win11/"><u>Master Hardware: 4 Techniques for Opening the Disk Editor in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-chrome-profile-woes-on-windows-pcs/"><u>Overcoming Chrome Profile Woes on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-routing-failed-files-download-on-windows-11-and-11-pcs/"><u>Re-Routing Failed Files Download on Windows 11 & 11 PCs</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722868174752-resolving-noise-issues-in-your-stereo-system-restore-the-sound/"><u>Resolving Noise Issues in Your Stereo System - Restore the Sound</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-stubborn-windows-exe-non-opener/"><u>Resolving Stubborn Windows EXE Non-Opener</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-unresponsive-amd-graphics-driver-in-windows/"><u>Resolving Unresponsive AMD Graphics Driver in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-your-control-over-frozen-windows-exe-files/"><u>Restore Your Control over Frozen Windows EXE Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-your-pc-top-10-techniques-in-windows-repair/"><u>Revive Your PC: Top 10 Techniques in Windows Repair</u></a></li>
<li><a href="https://win11-tips.techidaily.com/scaling-down-applications-effortlessly-with-windows-11s-keys/"><u>Scaling Down Applications Effortlessly with Windows 11'S Keys</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-strategies-for-overcoming-lag-in-windows-11-keyboards/"><u>Solution Strategies for Overcoming Lag in Windows 11 Keyboards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-enable-driver-verifier-in-windows-11/"><u>Steps to Enable Driver Verifier in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-webcam-malfunction-in-windows-11-fixing-error-0xa00f4289/"><u>Streamlining Webcam Malfunction in Windows 11: Fixing Error 0xA00F4289</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-pc-the-process-of-reverting-with-system-restore/"><u>Streamlining Your PC: The Process of Reverting with System Restore</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-resolving-blue-screen-error-interrupt-not-handled/"><u>Techniques for Resolving Blue Screen Error: Interrupt Not Handled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-synchronized-shutdown-of-multiple-windows-apps/"><u>Techniques for Synchronized Shutdown of Multiple Windows Apps</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/the-ultimate-digital-route-for-learn-latin-ease/"><u>The Ultimate Digital Route for Learn Latin Ease</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-nonfunctional-usb-ports-on-windows-11/"><u>Troubleshooting and Fixing Nonfunctional USB Ports on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-fluctuating-print-device-settings/"><u>Troubleshooting Fluctuating Print Device Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-diverse-nvidia-driver-options-gaming-studio/"><u>Understanding Diverse Nvidia Driver Options: Gaming, Studio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-your-sound-potential-in-windows-11/"><u>Unlock Your Sound Potential in Windows 11</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-nikon-video-file-editing-a-comprehensive-guide/"><u>Updated 2024 Approved Nikon Video File Editing A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/usb-wi-fi-woes-heres-a-quick-guide-to-reclaiming-connection-on-windows/"><u>USB Wi-Fi Woes? Here's a Quick Guide to Reclaiming Connection on Windows</u></a></li>
<li><a href="https://facebook.techidaily.com/virtual-conversations-take-flight-with-facebooks-podcast-hub/"><u>Virtual Conversations Take Flight with Facebook’s Podcast Hub</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-samsung-galaxy-xcover-7-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Samsung Galaxy XCover 7 Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-fix-unraveling-error-0x30017/"><u>Win11 Fix: Unraveling Error 0X30017</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-workspace-wizardry-mastering-direct-file-exchange-in-clouds/"><u>Windows Workspace Wizardry: Mastering Direct File Exchange in Clouds</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>