---
title: Configuring Start/Stop of Windows Installer Service
date: 2024-08-23T07:00:56.280Z
updated: 2024-08-24T07:00:56.280Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Configuring Start/Stop of Windows Installer Service
excerpt: This Article Describes Configuring Start/Stop of Windows Installer Service
keywords: Windows MsiStart/Stop,InstallServiceControl,ManageMsiStartService,MsiServiceConfigure,ControlWindowsInstaller,StopInstallService,StartWindowsInstaller
thumbnail: https://thmb.techidaily.com/65d1648a69e474032218f98a4f9088236faaaabb296646cc458aad0041a1d229.png
---

## Configuring Start/Stop of Windows Installer Service

 Are you looking for a way to disable the Windows Installer Service on your device? This essential component of your operating system performs all necessary installation processes, but can sometimes interfere with other programs.

 Fortunately, there are three ways in which it can be disabled—using the Windows Service tool, Group Policy Editor, or Registry Editor. Check out our guide below to learn how.

## 1\. Use Windows Services

 Windows services are critical programs that typically initiate when you start your computer. It runs silently in the background and provides essential features to run the operating system. If you're looking to enable or disable Windows Installer service using this tool, do the following.

 To begin, press**Win + R** on your keyboard to launch the Run dialog box. In the text box, type**services.msc** , and hit enter. This will open the Services window.

![Disable Windows Installer Service Using Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-services-window.jpg)

 In the window that opens, scroll down until you find**Windows Installer** service then double-click on it for a properties window to open.

 Once you're in the Properties window, click the**Startup type** drop-down menu and select**Automatic** . Now move over towards the**Service status** section and click**Stop** .

![Disable Windows Installer Service Using Windows Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-windows-services.jpg)

 After you've done that, click**Apply** and then**OK** to save the changes. You have now successfully disabled the Windows Installer service on Windows 11.

 If you ever need to re-enable the service, follow the same procedure and click**Start** in the Service status section.

## 2\. Use Local Group Policy Editor

 You can also use the group policy editor to enable or disable the Windows Installer service on your Windows computer system. However, it is important to note that this tool only works on Windows Pro and Enterprise editions. Therefore, if you are using Windows Home Edition, you must first[activate the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 To disable the service using the group policy editor, do the following:

1. Click on Start and type in**gpedit.msc** , then press**Enter** to[launch the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
2. On the left side of the window, navigate to the path:  
`Computer Configuration > Administrative Templates > Windows Components > Windows Installer`
3. Now move to the right and double-click on the policy named**Turn off Windows Installer** .  
![Disable Windows Installer Service Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-group-policy.jpg)
4. In the window that opens, select**Enabled** in the radio box.
5. Under Options, click the drop-down menu and select**Always** .
6. Then click**Apply** and**OK** to save changes.

 That's all there is to it. The Windows Installer service will now be disabled on your system. To re-enable it, simply follow the same steps, but set "Turn off Windows Installer" to**Not Configured** .

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Use the Registry Editor

 Registry Editor is another method you can use to enable or disable the Windows Installer service on any version of Windows, even Home Edition. But make sure to proceed with caution as any incorrect changes can corrupt your system and force you to reinstall Windows. So be mindful and remember to back up your registry before making any modifications.

 To enable or disable this service using Registry Editor, follow these steps:

1. Press**Win + X** , type**regedit** , and press**Enter** to launch the Registry Editor. To learn more, see our guide on how to[open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. If prompted with a UAC warning, click**Yes** to continue.
3. Now once you're in, navigate to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\msiserver`
4. In the right panel, double-click on**Start** and change its value from**2** to**4** .  
![Disable Windows Installer Service Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once you put the Value data, make sure the Base is set to**Hexadecimal** , then click**OK** . Now close the registry editor and restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## Turning Off the Windows Installer Service Made Easy

 If Windows Installer Service is creating issues or hindering another application, you can easily turn it off with one of the three methods outlined in our guide. See which method works best for you and get back to what matters most.


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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-facebooks-best-eight-free-link-collector-tools/"><u>[New] 2024 Approved  Facebook's Best  Eight FREE Link Collector Tools</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-maximize-your-home-studio-webcam-recorder-essentials/"><u>[New] 2024 Approved  Maximize Your Home Studio - WebCam Recorder Essentials</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-jumpstart-your-photo-editing-essential-pixlr-wisdoms/"><u>[New] In 2024, Jumpstart Your Photo Editing  Essential Pixlr Wisdoms</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-instagram-artistry-easy-steps-to-stunning-collage-photos/"><u>[New] Instagram Artistry  Easy Steps to Stunning Collage Photos</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-muting-problem-solutions-for-obs-sound-capture-for-2024/"><u>[New] Muting Problem Solutions for OBS Sound Capture for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-essential-tools-for-free-web-conferencing-a-comprehensible-guide/"><u>[Updated] 2024 Approved  Essential Tools for FREE Web Conferencing  A Comprehensible Guide</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-ps3-gaming-reimagined-best-emulators-of-the-year/"><u>[Updated] 2024 Approved  PS3 Gaming Reimagined  Best Emulators of the Year</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-mastering-igtv-a-comprehensive-guide-for-beginners/"><u>[Updated] In 2024, Mastering IGTV  A Comprehensive Guide for Beginners</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-proactive-preservation-ios-photos-to-your-snap-story/"><u>[Updated] In 2024, Proactive Preservation  IOS Photos to Your Snap Story</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-sonicarchive-pro-downloads-and-analysis/"><u>[Updated] SonicArchive Pro Downloads & Analysis</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-superior-app-dev-editors-top-15-selection/"><u>[Updated] Superior App Dev Editors  Top 15 Selection</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-unveil-the-power-leveraging-windows-11-and-zoom-maximum/"><u>[Updated] Unveil the Power  Leveraging Windows 11 and Zoom Maximum</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-elite-remote-meeting-apps-beyond-zoom/"><u>2024 Approved  Elite Remote Meeting Apps  Beyond Zoom</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-the-definitive-guide-to-live-on-discord/"><u>2024 Approved  The Definitive Guide to Live on Discord</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-tutorial-uploading-youtube-to-instagram-stories-effortlessly/"><u>2024 Approved  Tutorial  Uploading YouTube to Instagram Stories Effortlessly</u></a></li>
<li><a href="https://fox-helps.techidaily.com/action-camera-faceoff-gopro-hero-vs-sony-dslr-for-adventure-seekers-for-2024/"><u>Action Camera Faceoff  GoPro Hero Vs. Sony DSLR for Adventure Seekers for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/blending-primary-and-b-roll-for-smooth-transitions/"><u>Blending Primary and B-Roll for Smooth Transitions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curtail-extra-audio-boost-in-windows/"><u>Curtail Extra Audio Boost in Windows</u></a></li>
<li><a href="https://facebook.techidaily.com/deciphering-the-benefits-of-sleep-mode-in-messenger-kids/"><u>Deciphering the Benefits of Sleep Mode in Messenger Kids</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/efficient-email-organization-techniques-how-to-utilize-labels-for-a-neat-gmail-experience/"><u>Efficient Email Organization Techniques: How to Utilize Labels for a Neat Gmail Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-geforce-nows-xc0f1103f-hitch-in-windows-11/"><u>Eliminate GeForce Now's Xc0f1103f Hitch in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-windows-11-is-operational-3-strategies/"><u>Ensuring Windows 11 Is Operational: 3 Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-windows-11-key-purchases/"><u>Essential Guide to Windows 11 Key Purchases</u></a></li>
<li><a href="https://win11-tips.techidaily.com/express-guide-to-determine-windows-11-gpu-variant/"><u>Express Guide to Determine Windows 11 GPU Variant</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-the-most-out-of-windows-backup-features/"><u>Get the Most Out of Windows Backup Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-screen-flickering-and-flashing-on-windows-10-and-11/"><u>How to Fix Screen Flickering and Flashing on Windows 10 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-lost-windows-patch-service/"><u>How to Reactivate Lost Windows Patch Service</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-5-most-effective-methods-to-unlock-iphone-12-pro-in-lost-mode-drfone-by-drfone-ios/"><u>In 2024, 5 Most Effective Methods to Unlock iPhone 12 Pro in Lost Mode | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-quick-guide-to-oppo-a56s-5g-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to Oppo A56s 5G FRP Bypass Instantly</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlink-apple-id-from-apple-iphone-7-by-drfone-ios/"><u>In 2024, How To Unlink Apple ID From Apple iPhone 7</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-a-samsung-galaxy-xcover-6-pro-tactical-edition-easily-by-drfone-android/"><u>In 2024, How To Unlock a Samsung Galaxy XCover 6 Pro Tactical Edition Easily?</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-xiaomifrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your XiaomiFRP Lock</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-the-art-of-amusement-master-memes-with-kapwing/"><u>In 2024, The Art of Amusement – Master Memes with Kapwing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-machine-11-ways-to-open-control-panel/"><u>Master Your Machine: 11 Ways to Open Control Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-words-best-windows-apps-for-writers/"><u>Mastering Words: Best Windows Apps for Writers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-your-win-11-experience-game-changing-advice-for-the-winning-side/"><u>Optimizing Your Win 11 Experience: Game-Changing Advice for the Winning Side</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-secure-authentication-problems-with-the-epic-launcher/"><u>Overcoming Secure Authentication Problems with the Epic Launcher</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-bing-chat-integration-in-windows-11/"><u>Quick Guide to Bing Chat Integration in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-outlook-responses-a-windows-fix-guide/"><u>Quick Outlook Responses: A Windows Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalizing-windows-11s-ccleaner-functionality/"><u>Revitalizing Windows 11'S CCleaner Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-syncopation-combining-dropbox-and-googledrive-driveletters/"><u>Simplifying Syncopation: Combining Dropbox and GoogleDrive DriveLetters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-language-switching-made-simple-with-windows-keys/"><u>Speedy Language Switching Made Simple with Windows Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stabilize-your-game-solving-apex-legends-on-win11/"><u>Stabilize Your Game: Solving Apex Legends on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealthy-setups-mastering-the-invisible-menu-features/"><u>Stealthy Setups: Mastering the Invisible Menu Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-fingerprint-scanner-unsupported-problems/"><u>Steps to Resolve 'Fingerprint Scanner Unsupported' Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-commence-quickly-open-windows-and-sticky-notes/"><u>Streamlined Commence: Quickly Open Windows and Sticky Notes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-qr-code-processes-with-windows-os/"><u>Streamlining QR Code Processes with Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-efficiency-in-windows-using-smart-launcher-tech/"><u>Supercharge Efficiency in Windows Using Smart Launcher Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-real-deal-on-applecareplus-does-the-extra-security-make-financial-sense/"><u>The Real Deal on AppleCare+ – Does the Extra Security Make Financial Sense?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-automated-file-deletion-on-windows/"><u>The Ultimate Guide to Automated File Deletion on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/timeless-traits-windows-11s-retained-7-classic-characteristics/"><u>Timeless Traits: Windows 11'S Retained 7 Classic Characteristics</u></a></li>
<li><a href="https://unlock-android.techidaily.com/tips-and-tricks-for-setting-up-your-honor-magic-5-lite-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Honor Magic 5 Lite Phone Pattern Lock</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-7-budget-friendly-high-res-4k-cameras-for-2024/"><u>Top 7 Budget-Friendly High-Res 4K Cameras for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-7-windows-pens-tabs-ideal-notetakers/"><u>Top 7 Windows Pens' Tabs: Ideal Notetakers</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/top-techniques-for-streamlining-console-video-saves/"><u>Top Techniques for Streamlining Console Video Saves</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-to-emulate-macos-the-top-5-approaches/"><u>Transforming Windows to Emulate macOS: The Top 5 Approaches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-error-code-0x80070522-in-windows-regain-user-rights/"><u>Unraveling Error Code 0X80070522 in Windows: Regain User Rights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-modern-standby-a-critical-analysis/"><u>Unveiling Modern Standby: A Critical Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgraded-performance-ahead-steps-to-amplify-virtual-memory-in-windows-11/"><u>Upgraded Performance Ahead: Steps to Amplify Virtual Memory in Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-oneplus-12r-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from OnePlus 12R? Here is How | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-should-i-do-if-i-cant-upgrade-my-pc-to-windows-11/"><u>What Should I Do If I Can't Upgrade My PC to Windows 11?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-to-do-if-windows-wont-show-notification-badges-on-taskbar-icons/"><u>What to Do if Windows Won’t Show Notification Badges on Taskbar Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-warning-signs-is-a-restart-needed/"><u>Windows Warning Signs: Is a Restart Needed?</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/your-constant-aerial-companion-choices/"><u>Your Constant Aerial Companion Choices</u></a></li>
</ul></div>
