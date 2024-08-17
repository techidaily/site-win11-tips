---
title: The Essential Tips for Sticky Note Backup
date: 2024-08-16T01:40:02.877Z
updated: 2024-08-17T01:40:02.877Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Essential Tips for Sticky Note Backup
excerpt: This Article Describes The Essential Tips for Sticky Note Backup
keywords: Sticky Notes Save,Backup Tips Quick,Data Safeguard Guide,Notebook Info Secure,Storage Solutions Easy,Protect Note Pads,Essential Backup Steps
thumbnail: https://thmb.techidaily.com/24b4a5d68fd5e6bea75410f8f6c4c82cdd5bcbea33115cb8218e3e0a99c10ef2.jpg
---

## The Essential Tips for Sticky Note Backup

 Sticky Notes on Windows turn your computer into a virtual board for posting notes, reminders, lists, and pretty much anything that you need to remember at a glance. So it makes sense that you wouldn't want to lose them, whether you're switching computers or a problem with your PC has caused you to lose your data.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

## How to Back Up and Restore YourSticky Notes Using a Microsoft Account

 The easiest way to back up your sticky notes is to use a Microsoft account, which stores the notes on the cloud. If you don't have one already, then you can [learn how to create a Microsoft account](https://www.makeuseof.com/your-microsoft-account-things-windows-user-should-know/) or skip to the next section to learn how to back up the notes manually.

 If you've been using Windows with your Microsoft account all along, the notes could be synced to the cloud already. If you're not, you can [switch from a local account to a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/) for that to happen.

 To be sure if Sticky Notes is syncing your notes already or, if you're using a local account, give the app the ability to do so, follow the steps below:

1. Connect your Windows PC to the internet and open Sticky Notes.
2. Click on **Settings** (the gear icon) in the top right corner.
3. If you've already signed in, you'll see the details of your Microsoft account at the top with a **Sign out** link. If that's the case, you can skip to step #7 to sync the notes. If you're not signed in, click **Sign in**.
4. In the **Use one of these accounts** section, select the Microsoft account you want to sign in with. If there are no accounts there, select either **Microsoft account** or **Work or school account** in the **Use a different account** section.
5. Click **Continue** and follow the instructions to complete the sign-in process.
6. Once you're signed in, click on **Settings** again in the top right corner.
7. Scroll down and click **Sync now**.  
![the Sync Now button in Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/sync-now-button-in-sticky-notes.jpg)

 To restore the notes on another computer, open the Sticky Notes app (make sure the PC is connected to the internet) and sign in with your Microsoft account. Once signed in, the app will load all the notes you previously synced. Furthermore, every time you finish writing a Sticky Note or edit one, the app will automatically back it up to the cloud.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Manually Back Up and Restore Your Sticky Notes

 If you don't want to use a Microsoft account or want to have an extra backup of your sticky notes, then you can manually back them up yourself. While it's not as easy as just syncing them to the cloud, it can definitely come in handy when you don't have internet access and want to restore the notes.

 To manually back up your sticky notes, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.  
![opening tne Local State folder in Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/opening-local-state-folder-in-windows-run.jpg)
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
3. In the **LocalState** folder, copy the **plum.sqlite** file.  
![the plum database for Sticky Notes on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/the-plum-database-for-sticky-notes-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
4. Paste the **plum.sqlite** file to an external drive, such as a flash drive or external SDD, or upload it to cloud storage, such as OneDrive or Google Drive, for safekeeping.

 To manually restore your sticky notes on another Windows computer, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.
3. Go to where you saved the backup of your sticky notes (the **plum.sqlite** file) and copy it.
4. In the **LocalState** folder, delete the current **plum.sqlite** file.
5. Paste the backup **plum.sqlite** file in the **LocalState** folder.

 Now when you open Sticky Notes, it will load the **plum.sqlite** file, and you should see all your notes appear in the app.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## Never Lose Your Sticky Notes Again

 Losing your sticky notes means you could lose potentially important information. So it makes sense to always have a copy stored somewhere in case you need to restore them. We recommend using your Microsoft account to back up the notes, considering it's convenient to both sync and restore them later on, but it's also a good idea to know that there's a manual option available.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-step-into-the-world-of-high-quality-lenovo-screen-recordings/"><u>[New] Step Into the World of High-Quality Lenovo Screen Recordings</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-the-essential-iphoneside-by-side-guide-for-fb-sharing/"><u>[Updated] In 2024, The Essential iPhoneside by Side Guide for FB Sharing</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-inverted-video-playback-on-android-made-simple/"><u>[Updated] Inverted Video Playback on Android Made Simple</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-overcoming-non-detectable-obs-camera-link-for-2024/"><u>[Updated] Overcoming Non-Detectable OBS Camera Link for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-instagram-highlight-cover-art-inspiration-and-techniques-guide/"><u>2024 Approved  Instagram Highlight Cover Art  Inspiration & Techniques Guide</u></a></li>
<li><a href="https://extra-information.techidaily.com/a-practical-approach-to-hymnal-phone-tones-for-2024/"><u>A Practical Approach to Hymnal Phone Tones for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/broadcasting-zoom-sessions-to-your-hdtv-a-comprehensive-guide/"><u>Broadcasting Zoom Sessions to Your HDTV - A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-sound-glitch-error-0xc00d36b4-on-win11/"><u>Bypassing Sound Glitch: Error 0XC00D36B4 on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/checking-audio-device-integrity-on-windows/"><u>Checking Audio Device Integrity on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-server-slips-for-smooth-ms-store-in-windows-os/"><u>Conquering Server Slips for Smooth MS Store in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-slow-computer-wake-up-the-complete-window-11-startup-guide/"><u>Conquering Slow Computer Wake-Up: The Complete Window 11 Startup Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-winservicesexe-operations/"><u>Demystifying WinServices.exe Operations</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-realme-gt-3-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Realme GT 3 Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-fixes-for-flickering-win1011-screens/"><u>Efficient Fixes for Flickering WIN10/11 Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-printing-at-your-fingertips-slow-printer-remedies-in-windows/"><u>Fast Printing at Your Fingertips: Slow Printer Remedies in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/find-out-if-your-pc-is-a-win11-ready-machine/"><u>Find Out if Your PC Is a Win11-Ready Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/forge-ahead-with-stronger-windows-security-top-four-password-keepers/"><u>Forge Ahead with Stronger Windows Security: Top Four Password Keepers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-clear-visual-elements-from-search-bar/"><u>How to Clear Visual Elements From Search Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-the-home-page-from-the-settings-app-in-windows-11/"><u>How to Remove the Home Page From the Settings App in Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-13-online-here-are-6-easy-ways-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 13 Online? Here are 6 Easy Ways</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-atandt-apple-iphone-xs-max-with-3-methods-by-drfone-ios/"><u>In 2024, How to Unlock AT&T Apple iPhone XS Max with 3 Methods</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-mastering-the-art-of-disconnecting-from-your-old-linkedin-account/"><u>In 2024, Mastering the Art of Disconnecting From Your Old LinkedIn Account</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-transform-your-footage-effective-strategies-for-cropping-and-export-on-instagram/"><u>In 2024, Transform Your Footage  Effective Strategies for Cropping & Export on Instagram</u></a></li>
<li><a href="https://some-techniques.techidaily.com/innovating-communication-microsoft-azure-speech-to-text-explained-for-2024/"><u>Innovating Communication  Microsoft Azure Speech to Text Explained for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-your-pc-experience-mastering-windows-11s-search-tool/"><u>Jumpstart Your PC Experience: Mastering Windows 11’S Search Tool</u></a></li>
<li><a href="https://extra-skills.techidaily.com/laughter-lines-timely-meme-trends-to-share-for-2024/"><u>Laughter Lines  Timely Meme Trends to Share for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-the-microsoft-365-installation-on-laptops-and-desktops-a-comprehensive-walkthrough/"><u>Mastering the Microsoft 365 Installation on Laptops and Desktops – A Comprehensive Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-networking-essential-pre-call-tests-for-webcamsmics/"><u>Navigating Networking: Essential Pre-Call Tests for Webcams/Mics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/operas-plight-unleash-it-from-windows-freeze/"><u>Opera's Plight? Unleash It From Windows Freeze!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-black-screens-in-win11-with-ease/"><u>Overcoming Black Screens in Win11 with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-no-connection-in-windows-ethernet/"><u>Overcoming No Connection in Windows Ethernet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-prime-video-text-barriers-on-windows-11/"><u>Overcoming Prime Video Text Barriers on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-start-guide-initiating-screen-capture-on-win-11/"><u>Quick Start Guide: Initiating Screen Capture on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-utorrent-peer-relationships-on-win/"><u>Reestablishing uTorrent Peer Relationships on Win</u></a></li>
<li><a href="https://data-wizards.techidaily.com/resurgence-dawns-stellars-anywhere-db-revival/"><u>Resurgence Dawns: Stellar's Anywhere DB Revival</u></a></li>
<li><a href="https://win11-tips.techidaily.com/storage-soaring-speeds-stalling-mp60-model/"><u>Storage Soaring, Speeds Stalling - MP60 Model</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-correct-predominant-anydesk-issues-in-os/"><u>Strategies to Correct Predominant AnyDesk Issues in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-data-recovery-on-windows-11-pro/"><u>Streamlining Data Recovery on Windows 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-remedy-steps-for-immediate-failure-in-adding-your-folder-to-onedrive/"><u>Swift Remedy Steps for Immediate Failure in Adding Your Folder to OneDrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-list-top-7-methods-to-grow-storage-without-paying/"><u>The Essential List: Top 7 Methods to Grow Storage Without Paying</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-unauthorized-save-errors-in-microsoft-os/"><u>Troubleshooting Unauthorized Save Errors in Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-potential-four-ways-to-open-disk-management-in-win11/"><u>Unleashing Potential: Four Ways to Open Disk Management in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unseen-sd-card-on-pc-restore-its-visibility-in-explorer/"><u>Unseen SD Card on PC? Restore Its Visibility in Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-6-excellent-tools-for-controlling-windows-screen-luminosity/"><u>Unveiling the 6 Excellent Tools for Controlling Windows Screen Luminosity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-the-antiquity-embellishing-old-games-with-retroarch-awards/"><u>Upgrade the Antiquity - Embellishing Old Games With Retroarch Awards</u></a></li>
</ul></div>
