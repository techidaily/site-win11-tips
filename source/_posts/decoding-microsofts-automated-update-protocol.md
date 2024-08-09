---
title: Decoding Microsoft's Automated Update Protocol
date: 2024-08-08T11:09:29.052Z
updated: 2024-08-09T11:09:29.052Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Decoding Microsoft's Automated Update Protocol
excerpt: This Article Describes Decoding Microsoft's Automated Update Protocol
keywords: UpdProtoMS,MSUpdateAuto,MicrosoftUpdates,AutoUpdateWin,TechUpdateMic,DecodeMicrosoftUpdate,ProtocolDecodingMS
thumbnail: https://thmb.techidaily.com/3854233be38a7a3b692f6b1c87d1917c44d3f0b5ad0376d97a1f07070c0cf22e.jpg
---

## Decoding Microsoft's Automated Update Protocol

 We all love staying up-to-date with the latest Windows versions. But have you ever wondered what happens in the backend? How does Microsoft send Windows updates to our devices?

 This is where the Windows Update and Update Orchestrator services come into play. You may be wondering: what these services do and how they work together.

 Do not worry; we will explain everything about both services and how you can fix almost all Windows update errors with them.

## What Is the Windows Update Service?

 The Windows Update service is a process (task) that handles everything related to updates on Windows. If this sounds confusing, then understand it as a small-sized application that runs in the background. It ensures that you receive all the updates on time.

 This service takes care of [downloading and installing Windows updates](<http://downloading> and installing Windows updates), including security patches, and bug fixes, to name a few. So now you can imagine how helpful this service is on Windows.

 If it fails to work for any reason, you may witness a series of Windows update errors. This is why most internet guides suggest you restart the Windows Update service when an update fails to install.

 To better understand what could go wrong, explore our article on the [common reasons why Windows updates fail](https://www.makeuseof.com/reasons-why-windows-updates-fail/).

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## What's the Purpose of the Update Orchestrator Service?

 The Update Orchestrator service helps your Windows device fetch updates from Microsoft's server.

 This service starts in the background when you open your computer and connect directly to Microsoft's update server. After finding an update on their server, it checks for device compatibility and fetches the required details.

 This way, when you click the "**Check for updates**" button, you sometimes see the latest updates available for downloading.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Windows Update Settings Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-update-settings-preview.jpg)

 Think of this service as a scheduler that helps manage the timing and installation of updates. So, if the [latest Windows update is unavailable](https://www.makeuseof.com/why-is-the-latest-windows-update-not-showing-on-my-pc-/) on your computer, restarting the Update Orchestrator service may help.

 Now that you know about both services, let's look at how to fix almost all the Windows update issues with them.

## How to Troubleshoot Common Windows Update Issues

 Windows updates may occasionally hit a snag at times. But don't worry; you can quickly fix most of them.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
### 1\. Restart Windows Update and Update Orchestrator Services

 If one of the core Windows services crashes or stops for no reason, update error codes are not far behind. In such a case, your priority should be to restart them first.

 Here's how to restart the Windows update and Update orchestrator services:

1. Press **Win + R** to bring up the Run app. It allows you to launch any Windows program using its executable name or file path.
2. In the Run dialog box, enter **services.msc**. Click **OK** to run the command and open the Services app.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
![Services Command On Run App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/services-command-on-run.jpg)
3. Scroll down the list until you locate the **Update Orchestrator** service. Right-click on it and choose **Restart** from the context menu that appears.
4. Repeat these steps for the **Windows Update** service: right-click and select **Restart**.  
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
![Windows Update Service Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-update-service-preview.jpg)

 If there is no option to restart the service, select **Start** instead. This will fix nearly all the issues related to Windows updates.

### 2\. Try Some Common Update Fixes on Windows

 If restarting the services doesn't do the trick, don't worry! There are other ways to fix the Windows updating failing problem.

 Let's explore some general suggestions for you to try on your computer. The first go-to tool is the Windows Update troubleshooter. If you're using Windows 11, access the troubleshooter by going to **Settings > System > Troubleshoot > Other Troubleshooters**. This handy built-in tool can help you find the root cause of update issues and fix them on the go.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
![Windows Other Troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-other-troubleshooters.jpg)

 However, if the troubleshooter isn't cutting it, there is more to try. Our in-depth guide on [resolving stuck Windows Updates](https://www.makeuseof.com/tag/windows-update-stuck/) can help in this scenario.

 If you're on the latest Windows version, sometimes standard fixes don't work. In such cases, consider exploring our article on [how to fix Windows Update errors](https://www.makeuseof.com/windows-11-update-error-fixes/) as a last resort.

## Windows Update Services, Simplified

 If you don't enjoy tinkering with Windows, you may not be familiar with both services. But, now that you've learned about them be sure to check them out when dealing with Windows update issues.

 Remember that keeping Windows up-to-date is important in the long run. So, being familiar with such Windows services will help ensure a better computing experience.

 This is where the Windows Update and Update Orchestrator services come into play. You may be wondering: what these services do and how they work together.

 Do not worry; we will explain everything about both services and how you can fix almost all Windows update errors with them.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-hints.techidaily.com/new-2024-video-show-revamp-complete-analysis-and-guide/"><u>[New] 2024 Video Show Revamp - Complete Analysis & Guide</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-5-top-android-ps2-game-simulators-for-2024/"><u>[New] 5 Top Android PS2 Game Simulators for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-exploring-the-updated-windows-11-interface/"><u>[New] Exploring the Updated Windows 11 Interface</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-how-to-make-a-video-meme-for-facebook-and-instagram/"><u>[New] In 2024, How to Make a Video Meme for Facebook and Instagram</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-proven-ways-to-enhance-your-fb-presence-and-boost-engagement/"><u>[New] In 2024, Proven Ways to Enhance Your FB Presence and Boost Engagement</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-ultimate-screen-companionship-the-right-cms-guidebook/"><u>[New] Ultimate Screen Companionship  The Right CMS Guidebook</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-understanding-and-leveraging-snapchat-spotlight/"><u>[New] Understanding and Leveraging Snapchat Spotlight</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-enhance-visibility-with-any-channel-title-through-free-makers/"><u>[Updated] 2024 Approved  Enhance Visibility With Any Channel Title Through Free Makers</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-master-guide-implementing-chapters-in-vimeo/"><u>[Updated] In 2024, Master Guide  Implementing Chapters in Vimeo</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-leveraging-obs-for-smooth-streaming-mac-and-pc-users-guide-for-2024/"><u>[Updated] Leveraging OBS for Smooth Streaming  Mac & PC Users' Guide for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-samsung-ue590-ultra-hd-4k-gaming-and-freesync-screen/"><u>[Updated] Samsung UE590 - Ultra HD 4K, Gaming & FreeSync Screen</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-streamline-your-media-convert-fb-videos-to-mp4-hd1080p-for-free-for-2024/"><u>[Updated] Streamline Your Media - Convert FB Videos to MP4 HD/1080P for Free for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-the-ultimate-guide-to-screen-capture-tools-for-2024/"><u>[Updated] The Ultimate Guide to Screen Capture Tools for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-vimeos-revenue-revolution-strategies-for-sustainable-earnings-for-2024/"><u>[Updated] Vimeo's Revenue Revolution  Strategies for Sustainable Earnings for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-21-innovative-solutions-for-free-recording-of-online-meetings/"><u>2024 Approved  21 Innovative Solutions for Free Recording of Online Meetings</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-forge-funny-online-content-on-the-fly/"><u>2024 Approved  Forge Funny Online Content on the Fly</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-maximizing-vimeo-video-watch-time/"><u>2024 Approved  Maximizing Vimeo Video Watch Time</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-unveiling-the-most-shared-stock-photos-and-backstories/"><u>2024 Approved  Unveiling the Most Shared Stock Photos & Backstories</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-easy-steps-to-wipe-your-drives-partitions-in-windows/"><u>4 Easy Steps to Wipe Your Drive's Partitions in Windows</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-apple-iphone-15-pro-max-drfone-by-drfone-virtual-ios/"><u>5 Easy Ways to Change Location on YouTube TV On Apple iPhone 15 Pro Max | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-strategies-to-tackle-delay-in-typing-windows-11s-keyboard/"><u>8 Strategies to Tackle Delay in Typing Windows 11'S Keyboard</u></a></li>
<li><a href="https://extra-hints.techidaily.com/a-comprehensive-guide-to-focusing-on-your-iphone-camera-for-2024/"><u>A Comprehensive Guide to Focusing on Your iPhone Camera for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-lifeline-for-gaming-ensuring-persistent-connection-of-your-ps4-controller-in-windows/"><u>A Lifeline for Gaming: Ensuring Persistent Connection of Your PS4 Controller in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-optimal-performance-kali-on-windows/"><u>Achieve Optimal Performance: Kali on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-barriers-of-error-80080300-a-guide-to-enhanced-teamwork-on-windows/"><u>Breaking Barriers of Error 80080300: A Guide to Enhanced Teamwork on Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-oppo-a78-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Oppo A78</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-repeated-team-sign-ins-on-windows-systems/"><u>Bypassing Repeated Team Sign-Ins on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combat-dxgierror-with-device-reattachment/"><u>Combat DXGI_ERROR with Device Reattachment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-prompt-pranks-engage-in-5-digital-delights/"><u>Command Prompt Pranks: Engage in 5 Digital Delights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-strategies-for-overcoming-file-access-barriers-in-windows/"><u>Comprehensive Strategies for Overcoming File Access Barriers in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-and-configuring-your-win11-screensavers/"><u>Crafting and Configuring Your Win11 Screensavers</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/curtail-unexpected-youtube-recommendations/"><u>Curtail Unexpected YouTube Recommendations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-windows-navigator-placement-of-this-pc-icons/"><u>Customizing Windows Navigator: Placement of 'This PC' Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-windows-11-experience-implementing-superior-run-capabilities/"><u>Elevate Your Windows 11 Experience: Implementing Superior Run Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-user-experience-in-windows-11-notepad/"><u>Enhancing User Experience in Windows 11 Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/examining-the-prospects-why-choose-win11-over-macos/"><u>Examining the Prospects: Why Choose Win11 Over MacOS</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/explore-ioss-premier-choice-in-ps2-gaming-tools/"><u>Explore iOS’s Premier Choice in PS2 Gaming Tools</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/exploring-instagrams-video-sharing-cap/"><u>Exploring Instagram's Video Sharing Cap</u></a></li>
<li><a href="https://some-techniques.techidaily.com/harmonizing-highlights-how-to-add-soundtracks-to-powerpoint-for-2024/"><u>Harmonizing Highlights  How to Add Soundtracks to PowerPoint for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-ios-images-not-working-with-windows-1011/"><u>How to Fix iOS Images Not Working with Windows 10/11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-vivo-v29-pro-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Vivo V29 Pro in Minutes | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-realme-12plus-5g-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Realme 12+ 5G to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-change-your-apple-id-on-apple-iphone-13-mini-with-or-without-password-drfone-by-drfone-ios/"><u>In 2024, How To Change Your Apple ID on Apple iPhone 13 mini With or Without Password | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-an-airtag-from-your-apple-id-account-from-apple-iphone-13-pro-by-drfone-ios/"><u>In 2024, How to Remove an AirTag from Your Apple ID Account From Apple iPhone 13 Pro?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-of-user-profile-control-with-cmd/"><u>In-Depth Analysis of User Profile Control with CMD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovate-your-experience-avoiding-common-pitfalls-in-windows-11/"><u>Innovate Your Experience: Avoiding Common Pitfalls in Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/inside-look-whatsapps-voice-message-technology-for-2024/"><u>Inside Look  WhatsApp's Voice Message Technology for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instantly-power-off-windows-11-when-not-in-use/"><u>Instantly Power Off Windows 11 When Not in Use</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/master-online-engagement-with-proficient-use-of-snap-in-teams-for-2024/"><u>Master Online Engagement with Proficient Use of Snap in Teams for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-aligning-sticky-notes-in-w11/"><u>Mastering the Art of Aligning Sticky Notes in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-modifying-windows-files/"><u>Mastering the Art of Modifying Windows Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-task-runner-error-code-0x8007000f-in-winos/"><u>Mastery over Task Runner Error Code 0X8007000f in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multi-monitor-mastery-personalized-pixelation-per-system-screen/"><u>Multi-Monitor Mastery: Personalized Pixelation per System Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimal-pc-protection-limiting-multiple-antiviruses/"><u>Optimal PC Protection: Limiting Multiple Antiviruses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-page-lockout-in-windows-systems/"><u>Overcoming Page Lockout in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-login-error-compatibility-issue-with-scanner/"><u>Overcoming Windows Login Error: Compatibility Issue with Scanner</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/perfect-video-demos-in-adobe-captivate/"><u>Perfect Video Demos in Adobe Captivate</u></a></li>
<li><a href="https://screen-capture.techidaily.com/professional-setup-for-screen-capture-during-games-for-2024/"><u>Professional Setup for Screen Capture During Games for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-sudden-device-disconnection-dxgi/"><u>Remedy for Sudden Device Disconnection (DXGI)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-your-quest-preventing-crashes-on-your-pcs-platform/"><u>Securing Your Quest: Preventing Crashes on Your PC's Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpen-windows-safety-edge-context-menu-firewall-customization-guide/"><u>Sharpen Windows Safety Edge: Context Menu Firewall Customization Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-spectrum-mastering-windows-network-adapter-assessment-methods/"><u>Speed Spectrum: Mastering Windows' Network Adapter Assessment Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/surreptitious-shutdown-strategy-for-windows-11/"><u>Surreptitious Shutdown Strategy for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-for-windows-11s-0x8004def5-glitches/"><u>Swift Solutions for Windows 11'S 0X8004DEF5 Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-mute-microphone-issue-during-video-recordings/"><u>Tackling Mute Microphone Issue During Video Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-window-11-screens-a-comprehensive-wallpaper-plan/"><u>Tailoring Window 11 Screens: A Comprehensive Wallpaper Plan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/take-notes-no-downloads-windows-11-secrets/"><u>Take Notes, No Downloads: Windows 11 Secrets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taking-web-pages-to-desktop-level-with-windows-guide/"><u>Taking Web Pages to Desktop Level with Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-keep-microsoft-teams-from-crashing-win11-win10/"><u>Tips to Keep Microsoft Teams From Crashing Win11, Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/underrated-yet-stunning-best-windows-11-themes/"><u>Underrated, Yet Stunning: Best Windows 11 Themes</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unlock-clearer-visuals-with-iphone-video-focus/"><u>Unlock Clearer Visuals with iPhone Video Focus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unpacking-the-delay-in-windows-11-adoption/"><u>Unpacking the Delay in Windows 11 Adoption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-routes-to-windows-control-panel-entry/"><u>Unveiling the Routes to Windows Control Panel Entry</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>