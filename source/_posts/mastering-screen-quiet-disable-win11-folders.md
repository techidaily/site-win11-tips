---
title: "Mastering Screen Quiet: Disable Win11 Folders"
date: 2024-08-16T02:09:19.274Z
updated: 2024-08-17T02:09:19.274Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Screen Quiet: Disable Win11 Folders"
excerpt: "This Article Describes Mastering Screen Quiet: Disable Win11 Folders"
keywords: Quiet Windows,Turn Off Noise,Silence PC Sounds,Win11 Volume Control,Reduce System Loudness,Mute Win11 Folders,Disable Audible Alerts
thumbnail: https://thmb.techidaily.com/f5fbbf41453d9824bf6879798120e6de2082db27f668f4cb2a72d45c0fe37f64.jpg
---

## Mastering Screen Quiet: Disable Win11 Folders

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

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
### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  
vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.
5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## Disable Any Windows 11 Feature Using ViVeTool

 File Explorer tabs are more useful than you think. But if you use another File Explorer program or can make do without it, ViVeTool is a great utility to disable/enable it. Moreover, it is completely free, and you can even enable other experimental features of Windows 11.


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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-premier-options-to-play-sonys-ps1-games-on-pc/"><u>[New] 2024 Approved  Premier Options to Play Sony's PS1 Games on PC</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-from-wardrobe-to-webcam-your-macootd-tiktok-adventure/"><u>[New] From Wardrobe to Webcam  Your MacOOTD TikTok Adventure</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-content-makers-compensation-breakdown-for-youtube-shorts/"><u>[New] In 2024, Content Makers' Compensation Breakdown for YouTube Shorts</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-master-the-art-of-mac-screen-record-via-shortcuts/"><u>[New] In 2024, Master the Art of Mac Screen Record via Shortcuts</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-directing-your-podcast-to-itunes-stores/"><u>[Updated] Directing Your Podcast to iTunes Stores</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-countdown-magic-discover-10-must-have-androidios-clocks/"><u>2024 Approved  Countdown Magic  Discover 10 Must-Have Android/iOS Clocks</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-eminent-exchanges-a-curated-list-of-top-reddit-posts/"><u>2024 Approved  Eminent Exchanges  A Curated List of Top Reddit Posts</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-honor-v-purse-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Honor V Purse | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/a-guide-to-securing-top-tier-images-for-free/"><u>A Guide to Securing Top-Tier Images for Free</u></a></li>
<li><a href="https://win11-tips.techidaily.com/become-a-cmd-guru-understand-these-20-crucial-commands/"><u>Become a CMD Guru: Understand These 20 Crucial Commands</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-pictures-from-vivo-g2-by-fonelab-android-recover-pictures/"><u>Best Android Data Recovery - Retrieve Lost Pictures from Vivo G2.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-gaps-improving-windows-11s-trouble-resolution-tools/"><u>Bridging Gaps: Improving Windows 11'S Trouble Resolution Tools</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/crafting-engaging-full-degree-footage-with-adobe-premieres-state-of-the-art-tools-for-2024/"><u>Crafting Engaging Full Degree Footage with Adobe Premiere's State-of-the-Art Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-error-0x80131500-on-microsoft-store/"><u>Disabling Error 0X80131500 on Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-window-management-active-periods-not-permanent-disruptions/"><u>Efficient Window Management: Active Periods, Not Permanent Disruptions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-management-navigating-taskbar-with-windows-hotkeys/"><u>Effortless Management: Navigating Taskbar with Windows Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-pc-performance-insider-tips-on-wintools/"><u>Elevate PC Performance: Insider Tips on WinTools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-share-cant-be-opened-issues-in-geforce/"><u>Eliminating Share Can't Be Opened Issues in GeForce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-windows-storage-the-top-free-volume-boosters-list/"><u>Enhance Your Windows Storage: The Top Free Volume Boosters List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-removal-of-win11s-official-store/"><u>Exclusive Removal of Win11's Official Store</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/harnessing-power-at-no-cost-guide-to-hosting-and-participating-in-gmeet-for-2024/"><u>Harnessing Power at No Cost  Guide to Hosting & Participating in GMeet for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-an-exception-breakpoint-has-been-reached-error-on-windows/"><u>How to Fix the “An Exception Breakpoint Has Been Reached” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-iphone-image-import-something-went-wrong-error-in-windows-10-and-11/"><u>How to Fix the iPhone Image Import “Something Went Wrong” Error in Windows 10 & 11</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-oppo-f23-5g-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Oppo F23 5G</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-best-8-stream-modifiers-for-flawless-webcam-videos/"><u>In 2024, Best 8 Stream Modifiers for Flawless Webcam Videos</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-conquerors-of-the-past-the-prime-7-battle-simulations/"><u>In 2024, Conquerors of the Past  The Prime 7 Battle Simulations</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-get-and-use-pokemon-go-promo-codes-on-realme-narzo-60-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Get and Use Pokemon Go Promo Codes On Realme Narzo 60 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-integrating-multimedia-elements-for-engaging-facebook-slideshows/"><u>In 2024, Integrating Multimedia Elements for Engaging Facebook Slideshows</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-streamline-your-playlist-import-music-into-inshot/"><u>In 2024, Streamline Your Playlist  Import Music Into InShot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-older-systems-healthy-with-win10-improvements/"><u>Keep Older Systems Healthy with Win10 Improvements</u></a></li>
<li><a href="https://extra-support.techidaily.com/keep-your-linkedin-videos-at-the-fingertips-top-6-professional-downloader-apps-for-2024/"><u>Keep Your LinkedIn Videos at the Fingertips  Top 6 Professional Downloader Apps for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/live-stream-reader-for-2024/"><u>Live Stream Reader for 2024</u></a></li>
<li><a href="https://data-wizards.techidaily.com/mastering-the-flow-how-to-stop-buffering/"><u>Mastering the Flow: How to Stop Buffering</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastery-over-multiple-tiktok-video-harvest-for-2024/"><u>Mastery Over Multiple TikTok Video Harvest for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-fixing-media-creators-error-0x8007043c/"><u>Methods for Fixing Media Creator's Error 0X8007043C</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-difficulty-of-error-0x000-in-xbox-game-pass-windows-edition/"><u>Overcoming the Difficulty of Error 0X000_ in Xbox Game Pass Windows Edition</u></a></li>
<li><a href="https://driver-download.techidaily.com/quick-guide-updating-your-msi-gpu-drivers-in-windows-11-and-7/"><u>Quick Guide: Updating Your MSI GPU Drivers in Windows 11 and 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-windows-hosts-overuse-a-guide/"><u>Reducing Windows Host's Overuse: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-microsoft-office-activation-error/"><u>Resolving Microsoft Office Activation Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-your-ps4-remote-link-eliminating-random-drops-in-connection/"><u>Secure Your PS4 Remote Link: Eliminating Random Drops in Connection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-windows-search-with-image-cleanse/"><u>Simplifying Windows Search with Image Cleanse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-your-performance-essential-strategies-with-windows-11/"><u>Skyrocket Your Performance: Essential Strategies with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slash-gpu-load-for-smarter-windows-11-wm-efficiency/"><u>Slash GPU Load for Smarter Windows 11 WM Efficiency</u></a></li>
<li><a href="https://android-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-samsung-galaxy-z-flip-5-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass Samsung Galaxy Z Flip 5 FRP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-activatedeactivate-safeguard-in-windows-10/"><u>Steps to Activate/Deactivate SafeGuard in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-rectify-bluetooth-check-pin-error-in-windows-oses/"><u>Strategies to Rectify Bluetooth Check Pin Error in Windows OSes</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-benefits-of-tubebuddy-manage-your-youtube-channel-for-2024/"><u>The Benefits of TubeBuddy | Manage Your YouTube Channel for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/too-much-glitches-handle-deps-before-virtualbox-on-win/"><u>Too Much Glitches? Handle Deps Before VirtualBox on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-cost-free-windows-audio-cleaners/"><u>Top 5 Cost-Free Windows Audio Cleaners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-full-control-over-your-pc-in-winos/"><u>Unlock Full Control Over Your PC in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/whats-behind-windows-11s-disappearing-thumbnail-issue-fixes-here/"><u>What's Behind Windows 11'S Disappearing Thumbnail Issue? Fixes Here</u></a></li>
</ul></div>
