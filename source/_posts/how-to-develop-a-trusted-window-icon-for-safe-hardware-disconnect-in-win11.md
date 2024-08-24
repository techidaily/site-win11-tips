---
title: How to Develop a Trusted Window Icon for Safe Hardware Disconnect in Win11
date: 2024-08-23T07:08:36.337Z
updated: 2024-08-24T07:08:36.337Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Develop a Trusted Window Icon for Safe Hardware Disconnect in Win11
excerpt: This Article Describes How to Develop a Trusted Window Icon for Safe Hardware Disconnect in Win11
keywords: Windows Secure Icons,Safe Hardware Signal,Hardware Disconnect Safety,Trustworthy Windows Icon,Secure PC Disconnection,Win11 Hardware Lockdown,Trusted Hardware Seal
thumbnail: https://thmb.techidaily.com/5f1dd72a960c69600ce9688063aeb5e7a932b178d483ab7dbc13cbf4ab650189.jpg
---

## How to Develop a Trusted Window Icon for Safe Hardware Disconnect in Win11

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

## How to Set Up "Safely Remove Hardware" Taskbar and Start Menu Shortcuts

 Setting up a Safely Remove Hardware desktop shortcut will enable you to pin it to the taskbar or Start menu. To do so, right-click the Safely Remove Hardware icon on the desktop and select**Show more options** . The classic context menu in Windows 11 includes**Pin to taskbar** and**Pin to Start** menu options. So, select one of those options to create an alternative Safely Remove Hardware taskbar or Start menu shortcut.

![The Pin to taskbar option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/pin-to-taskbar-option.jpg)

 Adding Safely Remove Hardware to the taskbar or Start menu will make its desktop shortcut redundant. You can remove that desktop shortcut by right-clicking its icon and selecting**Delete** (the trash can icon).

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Set Up a "Safely Remove Hardware" Hotkey

 There’s no quicker way to open anything in Windows 11 than pressing a hotkey. A keyboard shortcut enables you to open anything without having to minimize windows to reach the desktop, bring up the Start menu, or move the mouse at all. You can set up a hotkey that opens the Safely Remove Hardware dialog as instructed for method one in our[how to assign keyboard shortcuts to programs on Windows](https://www.makeuseof.com/windows-keyboard-shortcuts-programs/) guide.

![The Shortcut key box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/shortcut-key-box.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
 Creating such a hotkey doesn’t make the Safely Remove Hardware desktop shortcut redundant. The hotkey activates the desktop shortcut you assigned it to. So, erasing the Safely Remove Hardware desktop shortcut will delete the shortcut key.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
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
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
 That option can be easily removed from the context menu if you decide not to keep it there. To remove it, return to the registry key specified in step three above; right-click the**Safely Remove Hardware** key you added and select**Delete** . Then select**Yes** to delete the key.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
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
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-microvid-viewer-analysis-and-comparison-tools/"><u>[New] In 2024, MicroVid Viewer Analysis & Comparison Tools</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-in-depth-look-at-ipad-display-logging/"><u>[Updated] 2024 Approved  In-Depth Look at iPad Display Logging</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-the-essential-iphoneside-by-side-guide-for-fb-sharing/"><u>[Updated] 2024 Approved  The Essential iPhoneside by Side Guide for FB Sharing</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-channel-to-checkbook-conversion-the-path-from-adsense-to-banking/"><u>2024 Approved  Channel to Checkbook Conversion  The Path From AdSense to Banking</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-pushing-the-boundaries-in-depth-review-of-benq-sw320s-4k-display/"><u>2024 Approved  Pushing the Boundaries  In-Depth Review of BenQ SW320's 4K Display</u></a></li>
<li><a href="https://screen-recording.techidaily.com/capture-mac-scenery-screen-and-microphone-feature/"><u>Capture Mac Scenery  Screen and Microphone Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-and-confident-windows-viewing-top-6-fixes-now/"><u>Clear and Confident Windows Viewing: Top 6 Fixes Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configure-spotlight-screenshot-preferences-efficiently-in-windows/"><u>Configure Spotlight Screenshot Preferences Efficiently in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-stealth-network-safeguarding-in-windows-settings/"><u>Crafting Stealth Network Safeguarding in Windows Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cross-era-compatibility-using-windows-7-product-key-in-11/"><u>Cross-Era Compatibility: Using Windows 7 Product Key in 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-memory-usage-by-microsoft-edges-view2/"><u>Decoding Windows Memory Usage by Microsoft Edge's View2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deployment-guide-for-intel-networking-on-ubuntu/"><u>Deployment Guide for Intel Networking on Ubuntu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/devhomes-blueprint-for-cutting-edge-w11-living/"><u>DevHome's Blueprint for Cutting-Edge W11 Living</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/direct3d-initialization-mastered/"><u>Direct3D Initialization Mastered</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-pcs-appeal-animated-backgrounds-in-windows-11/"><u>Elevate Your PC's Appeal: Animated Backgrounds in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-fixing-authentication-in-windows-os/"><u>Essential Guide to Fixing Authentication in Windows OS</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/experience-ultra-hd-quality-with-samsungs-55-ru7300-4k-smart-tv-comprehensive-review/"><u>Experience Ultra HD Quality with Samsung's 55 RU7300 4K Smart TV - Comprehensive Review!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-to-ensure-your-surfaces-software-stays-current/"><u>Expert Tips to Ensure Your Surface's Software Stays Current</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-unsuccessful-execution-of-high-privileges-tasks/"><u>Fixing Unsuccessful Execution of High Privileges Tasks</u></a></li>
<li><a href="https://howto.techidaily.com/gionee-f3-pro-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gionee F3 Pro Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/horizon-to-heavens-photo-taking-on-mobile-for-2024/"><u>Horizon to Heavens  Photo-Taking on Mobile for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-save-location-errors-in-windows-pcs/"><u>How to Correct Save Location Errors in Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-frozen-itunes-on-your-windows-system/"><u>How to Tackle Frozen iTunes on Your Windows System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-uncover-hidden-5ghz-networks-in-windows-11-using-7-tips/"><u>How to Uncover Hidden 5GHz Networks in Windows 11 Using 7 Tips</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-or-downgrade-iphone-6-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade iPhone 6 Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-7-top-ways-to-resolve-apple-id-not-active-issue-for-iphone-8-plus-by-drfone-ios/"><u>In 2024, 7 Top Ways To Resolve Apple ID Not Active Issue For iPhone 8 Plus</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-can-we-unlock-our-samsung-galaxy-xcover-6-pro-tactical-edition-phone-screen-by-drfone-android/"><u>In 2024, How Can We Unlock Our Samsung Galaxy XCover 6 Pro Tactical Edition Phone Screen?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-xiaomi-13-ultra-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track Xiaomi 13 Ultra Location | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/iphone-is-disabled-here-is-the-way-to-unlock-disabled-iphone-12-pro-drfone-by-drfone-ios/"><u>iPhone Is Disabled? Here Is The Way To Unlock Disabled iPhone 12 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-clock-screen-protectors-for-windows-users/"><u>Masterful Clock Screen Protectors for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-quick-fixes-to-common-windows-11-problems/"><u>Mastering Quick FIXES to Common Windows 11 Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-the-empty-directory-claim-in-windows-with-error-0x80070091-resolutions/"><u>Overcome the Empty Directory Claim in Windows with Error 0X80070091 Resolutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-no-projector-found-message-in-windows/"><u>Overcoming No Projector Found Message in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unable-to-link-error-guide-for-nvidia-experience-on-windows-11/"><u>Overcoming Unable to Link Error: Guide for Nvidia Experience on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-windows-update-error-0x80073712/"><u>Quick Fix for Windows Update: Error 0X80073712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-dealing-with-network-failures-on-windows-11-devices/"><u>Quick Fix: Dealing with Network Failures on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/returning-your-windows-system-backup-to-start/"><u>Returning Your Windows System Backup to Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-of-files-in-win-11-os/"><u>Seamless Integration of Files in Win 11 OS</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/seatechs-external-usb-blu-ray-recorder-tested-for-performance-variability-and-review-findings/"><u>SeaTech's External USB Blu-Ray Recorder Tested for Performance Variability and Review Findings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-wi-fi-connectivity-puzzles-clarifying-incomplete-instructions/"><u>Solving Wi-Fi Connectivity Puzzles: Clarifying Incomplete Instructions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-handle-not-handled-interrupt-in-windows-systems/"><u>Steps to Handle Not Handled Interrupt in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-keyboard-gurus-guide-to-windows-photos/"><u>The Keyboard Guru's Guide to Windows Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-non-responsive-key-to-control-display-brightness-on-windows-11/"><u>Unblocking Non-Responsive Key to Control Display Brightness on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninstalling-and-reinstalling-troubled-apps-in-windows/"><u>Uninstalling and Reinstalling Troubled Apps in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-your-ip-terminal-window-steps/"><u>Unveiling Your IP: Terminal Window Steps</u></a></li>
</ul></div>
