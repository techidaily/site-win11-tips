---
title: "Shorten System Awakening: Edit Boot Sequence Timing Windows 11"
date: 2024-09-11T01:20:44.238Z
updated: 2024-09-12T01:20:44.238Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Shorten System Awakening: Edit Boot Sequence Timing Windows 11"
excerpt: "This Article Describes Shorten System Awakening: Edit Boot Sequence Timing Windows 11"
keywords: Win11 BOOT SEQUENCE,WIN11 EDIT TIME,Boot Time Shorten,System Awakening Adjust,Timing Windows Update,Windows Sequence Shorten,Edit Boot Window 11
thumbnail: https://thmb.techidaily.com/61e1fbca092ac5d2ffa00e76582e3823f6ee9bd8608e03fb6613489ba0869657.jpg
---

## Shorten System Awakening: Edit Boot Sequence Timing Windows 11

 When you turn on your dual-boot system, Windows waits for a while, allowing you to choose the operating system you want to load. However, the default wait time may be too short, giving you little time to decide.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137210/26400" target="_top" id="2137210">
  <img src="//a.impactradius-go.com/display-ad/26400-2137210" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137210/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 1\. Change Boot Menu Timeout Using the Settings App

 The quickest way to configure the boot menu timeout is via the Settings app. Here's a step-by-step instructions to do that:

1. Press the **Win + I** hotkey to open the **Settings app**.
2. Choose **System** from the left sidebar and **About** from the right pane.
3. Choose **System protection**.  
![System protection option in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-protection.jpg)
4. Switch to the **Advanced** tab and click the **Settings** button under the **Startup and Recovery** section.




<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139117/17108" target="_top" id="2139117">
  <img src="//a.impactradius-go.com/display-ad/17108-2139117" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139117/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




5. Click the drop-down icon under the **Default operating system** option and choose your default OS.
6. Check the **Time to display list of operating systems** option and select the timeout value. The value can range from **0** to **999**.  
![Time to display list of operating systems option in System Protection window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/time-to-display-list-of-operating-systems-option.jpg)
7. Click **OK** to save the changes.

## 2\. Change Boot Menu Timeout Using System Configuration

 The System Configuration app, aka msconfig, is a built-in Windows utility that lets you [control your system's startup programs](https://www.makeuseof.com/optimize-startup-programs-windows-11/) and services. You can also use it to adjust various system settings, including the boot menu timeout. To change the boot menu timeout using the System Configuration app, follow the below instructions:

1. Press the **Win** key to open the **Start Menu,** type **System Configuration** in the search bar, and select the same from the result.
2. Switch to the **Boot** tab.
3. Enter the value (seconds) in the **Timeout** section and check the **Make all boot settings permanent** option.  
![Timeout option in msconfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timeout-option.jpg)
4. Click **Apply.**
5. Click **Yes** to confirm your changes.  
![Yes option in msconfig window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/yes-option-1.jpg)
6. Choose the **Restart** button.

## 3\. Change Boot Menu Timeout Using the Command Prompt

 If you're an advanced Windows user, you can use Command Prompt to configure the boot menu timeout on your Windows PC. Here's how:

1. Open the Start Menu, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane. If this method doesn't work, check out other ways to [launch Command Prompt in Windows](https://www.makeuseof.com/windows-11-open-command-prompt/).
2. In the elevated Command Prompt window, type the following command and press Enter. This will display the current time for which the boot menu appears.  
`bcdedit`
3. Type the following command and press Enter to change the timeout. Make sure to replace **`SECONDS`**with the new timeout.  
`bcdedit /timeout SECONDS`  
![Timeout change command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timout-change-command.jpg)

 That's it! From the next boot, the boot manager will appear for the specified duration of time.





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123512/26400" target="_top" id="2123512">
  <img src="//a.impactradius-go.com/display-ad/26400-2123512" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123512/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 4\. Change Boot Menu Timeout Using the Boot Options

 Another efficient way to configure the boot menu timeout is through the Boot Manager. The Boot Manager, also known as the Boot Loader, is responsible for launching your operating system when you turn on your computer. Not only that, it enables you to select a specific operating system if you are using multiple operating systems on your device.

 To modify the boot menu timeout through the Boot Manager, follow these instructions:

1. Open the Start Menu, click the **Power icon** and choose **Restart** from the context menu. If this method doesn't work, try any other [ways to restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/).
2. In the Boot Manager, click on **Change defaults or choose other options**.  
![Change defaults or choose other options in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-defaults-or-choose-other-options.jpg)
3. Select the **Change the timer** option.  




<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123477/16836" target="_top" id="2123477">
  <img src="//a.impactradius-go.com/display-ad/16836-2123477" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123477/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




![Change the timer option in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-timer.jpg)
4. Choose a time between the given options.  
![Choose time in the Boot Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/choose-time.jpg)





<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014853/22899" target="_top" id="2014853">
  <img src="//a.impactradius-go.com/display-ad/22899-2014853" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014853/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->








<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139121/17108" target="_top" id="2139121">
  <img src="//a.impactradius-go.com/display-ad/17108-2139121" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139121/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Control Your System Boot Menu on Windows

 Optimizing the boot menu timeout in Windows is a simple yet effective way to manage your system's startup time. By adjusting the duration for which the boot menu appears, you can ensure that you have adequate time to select your preferred operating system.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-access.techidaily.com/new-2024-approved-harmonizing-iphone-with-the-world-of-podcasts/"><u>[New] 2024 Approved Harmonizing iPhone with the World of Podcasts</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-authoritative-guide-to-premium-auto-camera-tech/"><u>[New] Authoritative Guide to Premium Auto Camera Tech</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-screen-capture-showdown-obs-vs-shadow-for-2024/"><u>[New] Screen Capture Showdown OBS vs Shadow for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-optimal-instagram-posting-times-a-comprehensive-overview/"><u>[Updated] 2024 Approved Optimal Instagram Posting Times A Comprehensive Overview</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-communicating-confidently-on-google-meet/"><u>[Updated] Communicating Confidently on Google Meet</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-elevating-your-listening-palette-with-youtube-music/"><u>[Updated] In 2024, Elevating Your Listening Palette with YouTube Music</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-dominating-viewership-tips-for-your-video-to-be-a-staff-choice/"><u>2024 Approved Dominating Viewership Tips for Your Video to Be a Staff Choice</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/4-ways-to-unlock-iphone-15-to-use-usb-accessories-without-passcode-by-drfone-ios/"><u>4 Ways to Unlock iPhone 15 to Use USB Accessories Without Passcode</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/7-ways-to-unlock-a-locked-poco-x6-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Poco X6 Phone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Motorola Defy 2 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-cursor-visibility-win10-and-11-techniques/"><u>Clearing Up Cursor Visibility: Win10 & 11 Techniques</u></a></li>
<li><a href="https://tools.techidaily.com/macxdvd/products/"><u>Digiarty Software(MacXDVD)</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/discover-the-upsides-of-speaking-german-top-10/"><u>Discover the Upsides of Speaking German (Top 10)</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/diy-photography-hack-the-complete-strategy-for-effective-selfie-light-usage/"><u>DIY Photography Hack: The Complete Strategy for Effective Selfie Light Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/double-the-ease-of-double-clicking-windows-mouse/"><u>Double the Ease of Double-Clicking Windows Mouse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-access-to-bing-ai-via-windows-11-keyboard-shortcuts/"><u>Efficient Access to Bing AI via Windows 11 Keyboard Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-organization-essential-productivity-software-for-windows/"><u>Effortless Organization: Essential Productivity Software for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-skyrim-x-script-woes-on-windows/"><u>Enhance Skyrim: X-Script Woes on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-ideal-nvidia-drivers-for-gamers-or-studios/"><u>Finding Ideal Nvidia Drivers for Gamers or Studios</u></a></li>
<li><a href="https://win-able.techidaily.com/fixing-persistent-errors-resolving-warno-issues-on-your-windows-pc/"><u>Fixing Persistent Errors: Resolving WARNO Issues on Your Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hotkey-hack-innovative-text-pasting-shortcuts/"><u>Hotkey Hack: Innovative Text Pasting Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-eradicate-elusive-recordings-errors-on-windows-11-os/"><u>How to Eradicate Elusive Recordings Errors on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-open-the-system32-folder-in-windows-11/"><u>How to Open the System32 Folder in Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-oppo-f25-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Oppo F25 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-fixes-for-cannot-open-file-error-in-windows/"><u>Immediate Fixes for Cannot Open File Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-your-startup-clearing-and-regenerating-windows-icons/"><u>Improve Your Startup: Clearing and Regenerating Windows Icons</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-3-ways-to-export-contacts-from-apple-iphone-8-plus-to-excel-csv-and-vcard-easily-drfone-by-drfone-transfer-from-ios/"><u>In 2024, 3 Ways to Export Contacts from Apple iPhone 8 Plus to Excel CSV & vCard Easily | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-phone-number-from-your-apple-id-from-your-iphone-15-plus-by-drfone-ios/"><u>In 2024, How To Remove Phone Number From Your Apple ID from Your iPhone 15 Plus?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-vivo-t2x-5g-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Vivo T2x 5G to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-from-apple-iphone-11-to-iphone-81111-pro-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer from Apple iPhone 11 to iPhone 8/11/11 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-leading-tech-for-remote-team-engagement/"><u>In 2024, Leading Tech for Remote Team Engagement</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-mastering-switch-saving-gameplay-footage/"><u>In 2024, Mastering Switch Saving Gameplay Footage</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-uncovering-10-discreet-instagram-story-aficionados/"><u>In 2024, Uncovering 10 Discreet Instagram Story Aficionados</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-poco-x6-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Poco X6? Fixed | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-pin-display-in-the-windows-11-menu/"><u>Maximizing Pin Display in the Windows 11 Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-to-the-shadowed-elements-of-windows-11/"><u>Navigating to the Shadowed Elements of Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-win1011s-network-maze-exiting-error-code-0x800704b3/"><u>Navigating Win10/11's Network Maze: Exiting Error Code: 0X800704B3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/network-knights-guide-to-overcoming-obs-studios-windows-hiccup-7-ways/"><u>Network Knights' Guide to Overcoming OBS Studio's Windows Hiccup (7 Ways)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-silenced-volume-backup-procedure/"><u>Reactivating Silenced Volume Backup Procedure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-fill-void-of-msvcr120dll-in-windows-os/"><u>Solutions to Fill Void of MSVCR120.DLL in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-interpreting-error-messages-in-w11-using-ms-tools/"><u>Step-by-Step Guide to Interpreting Error Messages in W11 Using MS Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-fixing-unsuccessful-connection-with-nvidia-experience/"><u>Step-by-Step Guide: Fixing Unsuccessful Connection with Nvidia Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-correcting-projector-connection-issues-in-windows/"><u>Steps for Correcting Projector Connection Issues in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategic-flush-methods-for-your-windows-domain-nameservers/"><u>Strategic Flush Methods for Your Windows Domain Nameservers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-selection-activating-selective-filters-in-win11/"><u>Streamline Selection: Activating Selective Filters in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-keyboard-use-eliminate-delay-in-windows-11s-typing-process/"><u>Swift Keyboard Use: Eliminate Delay in Windows 11'S Typing Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-off-windows-11s-hyper-v-service/"><u>Switching Off Windows 11'S Hyper-V Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-11-installation-errors-head-on/"><u>Tackling Windows 11 Installation Errors Head-On</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-enabling-missing-device-drivers-in-windows-11/"><u>Techniques for Enabling Missing Device Drivers in Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-definitive-list-of-video-stabilizer-brands-for-content-makers/"><u>The Definitive List of Video Stabilizer Brands for Content Makers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-install-pre-windows-xp-application-packages/"><u>Tips to Install Pre-Windows XP Application Packages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-windows-drawers-eclipsing-procreate/"><u>Top 5 Windows Drawers Eclipsing Procreate</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-system-speed-with-enhanced-window-run-utility/"><u>Transforming System Speed with Enhanced Window Run Utility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-guide-stop-vmfreeze-and-freezes-in-windows-11/"><u>Troubleshooting Guide: Stop VMfreeze & Freezes in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-international-communication-using-shortcuts-in-windows-os/"><u>Unlocking International Communication: Using Shortcuts in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-experience-in-ultraportables/"><u>Windows Experience in Ultraportables</u></a></li>
<li><a href="https://win-able.techidaily.com/winning-over-witcher-woes-strategies-to-stop-the-witcher-3-from-crashing-on-your-pc/"><u>Winning Over Witcher Woes: Strategies to Stop The Witcher 3 From Crashing on Your PC</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>