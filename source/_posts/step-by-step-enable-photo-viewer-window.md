---
title: "Step-by-Step: Enable Photo Viewer Window"
date: 2024-08-16T02:27:56.480Z
updated: 2024-08-17T02:27:56.480Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step: Enable Photo Viewer Window"
excerpt: "This Article Describes Step-by-Step: Enable Photo Viewer Window"
keywords: Photo Viewer Setup Guide,Windows Photo Viewing,Enable Image Display,Turn On Photo Window,Activate Picture Viewer,Photos in Windows Screen,Open Image Viewer
thumbnail: https://thmb.techidaily.com/8b7337516e3ab4c7de40944c48ebe243474ab75d4e4c1c2d693991f9d3085553.jpg
---

## Step-by-Step: Enable Photo Viewer Window

 Windows 11’s File Explorer has a tabs feature now. You can open a new location on the disk in a new tab rather than opening a new File Explorer window. Switching between multiple file locations is seamless, all thanks to this feature. But Microsoft isn’t planning to stop here. It wants to completely overhaul the File Explorer.

 File Explorer Gallery is one such new feature that Microsoft is testing in the Canary channel. Having a Gallery section will remove the need to browse separate folders to find or preview an image. Want to enable the feature on your system? Let’s begin.

## What Is the Gallery Feature in Windows File Explorer?

 File Explorer’s Gallery feature works exactly like it sounds. It categorically lists all the images on your system in a separate section, so you can find and view all the images in one tab. Android File Explorers have had this feature for quite a long, but Windows seems to care about it now.

 This new feature is available in the Windows Insider build version 25300 and above. But Microsoft made a big change to the Insider program by adding a Canary channel. So, any new Canary build will also have this experimental feature. Microsoft adds the new File Explorer based on Windows App SDK, which you can verify by hovering over the “pizza” icon in the File Explorer address bar.

 The Gallery section displays images from the Pictures and OneDrive folders and lists them by date. It has nice, rounded corners around each image in the Gallery section, which makes it feel like a part of the overall Windows 11 design. It appears right below the Home option in the left pane.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Enable Gallery in File Explorer in Windows 11

 Repeat the following steps to enable the new Gallery section in File Explorer:

### 1\. Update to the Appropriate Windows Insider Build

 The Gallery section is hidden in Insider builds 25300 and above. If you are a Windows Insider program participant, open and check for the latest Insider builds on your system. Make sure to be in the Dev or Canary channel because this experimental feature is exclusive to these channels only. Or, you can use [UUP Dump to download Windows Insider builds without participating in Microsoft’s Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
### 2\. Download ViVeTool

 You will also need ViVeTool to enable these experimental features on your system. You can [download ViVetool from GitHub](https://github.com/thebookisclosed/ViVe/releases) , but make sure that you pick the most recent release. Extract the tool to the C drive and then proceed to the next section.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
### 2\. Enabling Gallery in Windows File Explorer

 Retrace the following steps to enable the Gallery section on Windows 11:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press**Ctrl + Shift + Enter** keys at once to open a new Command Prompt window with administrator privileges.
2. Now, navigate to the main directory in C drive. Type**cd C:\\ command** and press the enter key.
3. Next, type the**cd Vivetool** command to enter the folder where Vivetool is present in the C drive. It is the main reason why we suggested you extract Vivetool in a convenient location.
4. Type the**Vivetool** command and press enter key to check if the tool is accessible and working. You will see the version of the tool along with the parameters it supports.  
![Enable Gallery in File Explorer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-gallery-in-file-explorer-in-windows-11.jpg)
5. Now, type the following command and press the enter key:  
vivetool /enable /id:41040327
6. If the command executes correctly, you will see a “Successfully set feature configuration(s)” message. But don’t close the Command Prompt window. Type the following commands to enable all the Gallery features one by one and execute them.  
vivetool /enable /id:40729001 vivetool /enable /id:40731912 vivetool /enable /id:41969252 vivetool /enable /id:42922424 vivetool /enable /id:42295138
7. After running all the commands without any error, type**exit** and press the enter key to close the command prompt window.  
![Enable Gallery in File Explorer in Windows 11 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-gallery-in-file-explorer-in-windows-11-2.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
8. Restart your computer for the changes made by Vivetool to take effect.
9. Once your computer boots up, press**Win + E** to open File Explorer. You will see a new**Gallery** option in the left pane below the**Home** option.

## How to View the Gallery in File Explorer

 You can access the Gallery section by launching File Explorer and clicking on the Gallery option in the left navigation pane. You will see all the images from the Pictures folder and OneDrive folder arranged by modification time (new to old). There is also a handy slider to scroll through the vast image tiles without using the mouse scroll wheel.

![Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/gallery-in-windows-file-explorer.jpg)

 The gallery app allows you to adjust the view of the image tiles to accommodate more or less in a single window. You can use the View option in the menu bar of File Explorer to change the image tile size. If you click on any image, it will open in a separate app window (Photos app or any other app that you use).

## How to Add or Remove Locations From Gallery in Windows File Explorer

 By default, the Gallery selection displays all the images located in the Pictures folder and OneDrive. But you can add or remove a folder from the Gallery section as well.

1. To add a folder to the Gallery, go to the menu bar and click on the**Locations** option. A new pop-up window will open and list all the folders that the Gallery section is pulling images from. Click on the**Add** button.  
![Adding a Folder to Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/adding-a-folder-to-gallery-in-windows-file-explorer.jpg)
2. Now select any folder or sub-folder with images and click on the**Include Folder** button.
3. The selected folder will appear in the list of available folders. Click on the**OK** button.
4. File Explorer gallery will now display the images present inside the newly added folder as well.

To remove a folder from Gallery, repeat the following steps:

1. Open the Gallery section and click on the**Locations** option in the menu bar.
2. You will see the list of all the folders currently included in the Gallery.
3. Click on the folder you want to remove to select it. Then click on the**Remove** button.  
![Removing a Folder from Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/removing-a-folder-from-gallery-in-windows-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Lastly, click on the**OK** button to finalize the changes. The Gallery section won’t display any images from the excluded folder from now onwards.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## Problems With the Gallery Section in Windows File Explorer

 The current preview of the Gallery feature is far from perfect. Firstly, the section works well in finding and categorically listing all the images from the included folders. But the images, despite being big, appear hazy. What’s the point of including a section if the images aren’t visible clearly?

 There is also the issue of images opening in a separate tab rather than in the same File Explorer window. If you plan to open the image in another window, you can do it from the image folder as well. So, future builds should include an option to preview the image in the File Explorer window. Otherwise, you are opening two apps to achieve the same thing. The Gallery section cannot list any videos as well and just ignores all the video files.

## Find All Your Images in One Place on Windows With Galleries

 Adding a Gallery section to File Explorer is a fantastic decision by Microsoft. But the current version is full of kinks we hope that Microsoft irons out before the final preview. If done right, this would make the File Explorer app a powerhouse and reduce dependency on other apps.

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
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-drive-engagement-not-farewells-top-strategies-to-keep-your-audience-hooked-on-youtube/"><u>[Updated] 2024 Approved  Drive Engagement, Not Farewells  Top Strategies to Keep Your Audience Hooked on YouTube</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-social-snapshot-post-photosvideos-without-a-twit/"><u>[Updated] 2024 Approved  Social Snapshot  Post Photos/Videos without a Twit</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-from-chaos-to-clarity-mastering-xiaomis-screen-recording/"><u>[Updated] In 2024, From Chaos to Clarity  Mastering Xiaomi's Screen Recording</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-quick-and-reliable-vimeo-file-retrievers/"><u>[Updated] In 2024, Quick and Reliable Vimeo File Retrievers</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-sharp-4k-top-10-mirrorless-cameras/"><u>[Updated] Mastering Sharp 4K  Top 10 Mirrorless Cameras</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-crafting-a-unique-identity-step-by-step-audio-customizations-on-android-phones/"><u>2024 Approved  Crafting a Unique Identity  Step-by-Step Audio Customizations on Android Phones</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-step-by-step-guide-to-creating-a-peak-vr-environment/"><u>2024 Approved  Step-by-Step Guide to Creating a Peak VR Environment</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/chuckle-and-sob-with-these-top-10-instagram-meme-collectives/"><u>Chuckle & Sob with These Top 10 Instagram Meme Collectives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/classic-games-reimagined-utilizing-retroarchs-shaders-effectively/"><u>Classic Games Reimagined: Utilizing RetroArch's Shaders Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-the-windows-11-crash-code-errors/"><u>Clearing Up the Windows 11 Crash Code Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-skies-top-ranked-windows-11-weather-tools/"><u>Decoding the Skies: Top-Ranked Windows 11 Weather Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-pointer-accessibility-simple-steps-for-windows-users/"><u>Elevating Pointer Accessibility: Simple Steps for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-visual-performance-the-ultimate-vram-boosters/"><u>Elevating Visual Performance: The Ultimate VRAM Boosters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-strategies-for-customizing-windows-boot-settings/"><u>Expert Strategies for Customizing Windows Boot Settings</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/exploring-why-apples-vision-pro-model-deserves-you-money/"><u>Exploring Why Apple's Vision Pro Model Deserves You Money</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fine-tuning-system-features-on-windows-11-devices/"><u>Fine-Tuning System Features on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-steps-to-boot-into-pcs-troubleshooting-hub/"><u>Five Steps to Boot Into PC's Troubleshooting Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/highlighting-key-features-windows-11-feb-update/"><u>Highlighting Key Features: Windows 11, FEB Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-address-the-invalid-token-access-error-on-win10/"><u>How To Address the “Invalid Token Access” Error on Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-razer-synapse-not-detecting-razer-devices-in-windows-10-and-11/"><u>How to Fix Razer Synapse Not Detecting Razer Devices in Windows 10 & 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-beyond-basics-professional-tips-from-vidas-features/"><u>In 2024, Beyond Basics  Professional Tips From Vida's Features</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-excavate-extravagance-treasure-hunting-maps-ranked/"><u>In 2024, Excavate Extravagance  Treasure Hunting Maps Ranked</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-how-to-completely-remove-your-instagram-footprint-forever/"><u>In 2024, How to Completely Remove Your Instagram Footprint Forever</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-the-most-of-microsoft-project-keys/"><u>Making the Most of Microsoft Project Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-approaches-to-solve-elevation-prompt-issues-on-winos/"><u>Masterful Approaches to Solve Elevation Prompt Issues on WINOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/migrating-your-torrent-tracking-moving-qbittorrent-efficiently/"><u>Migrating Your Torrent Tracking: Moving qBittorrent Efficiently</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigate-the-future-of-search-easily-why-perplexity-ai-stands-out-as-your-ideal-undiscovered-ai-companion-for-google/"><u>Navigate the Future of Search Easily: Why Perplexity AI Stands Out as Your Ideal, Undiscovered AI Companion for Google</u></a></li>
<li><a href="https://buynow-help.techidaily.com/netatmos-smart-weather-solution-review-a-sleek-and-efficient-system-for-app-dependent-consumers/"><u>Netatmo's Smart Weather Solution Review: A Sleek and Efficient System for App-Dependent Consumers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-os-setup-a-guide-to-installing-win11-in-vmware-17/"><u>Optimizing OS Setup: A Guide to Installing Win11 in VMWare 17</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-sound-output-hurdles-xbox-and-windows-guide/"><u>Overcoming Sound Output Hurdles: Xbox & Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-app-restrictions-for-store/"><u>Overcoming Windows 11 App Restrictions for Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-anydesk-quirks-for-a-smooth-windows-experience/"><u>Resolving AnyDesk Quirks for a Smooth Windows Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-interruptexception-errors-in-windows-os/"><u>Resolving INTERRUPT_EXCEPTION Errors in Windows OS</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/step-by-step-techniques-for-seamless-youtube-subtitling-and-captions-for-2024/"><u>Step-by-Step Techniques for Seamless YouTube Subtitling & Captions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-tricks-for-revoking-read-only-in-win11/"><u>Tips and Tricks for Revoking Read-Only in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-windows-11-photos-the-top-6-rescaling-methods/"><u>Transform Your Windows 11 Photos – The Top 6 Rescaling Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-usb-not-attached-error-in-virtualbox-on-windows-platform/"><u>Troubleshooting 'USB Not Attached' Error in VirtualBox on Windows Platform</u></a></li>
<li><a href="https://buynow-help.techidaily.com/unveiling-the-high-performance-capabilities-of-fujitsus-ix1600-document-scanner-desktop-review/"><u>Unveiling the High-Performance Capabilities of Fujitsu's iX1600 Document Scanner - Desktop Review</u></a></li>
</ul></div>
