---
title: Unlocking Photo Gallery Functions on Windows PC
date: 2024-06-25T17:11:16.644Z
updated: 2024-06-26T17:11:16.644Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking Photo Gallery Functions on Windows PC
excerpt: This Article Describes Unlocking Photo Gallery Functions on Windows PC
keywords: Windows Photo Access,WinPhotoGallery,Unlock Photo View,Windows Photo Enhance,PC Photo Explore,Gallery Photo Unlocker,Windows Photo Functions
thumbnail: https://thmb.techidaily.com/51abaf027a31735325c9f76686dddc367d5ab57a5b37d142ebd628755c0e5ec6.jpg
---

## Unlocking Photo Gallery Functions on Windows PC

 Windows 11’s File Explorer has a tabs feature now. You can open a new location on the disk in a new tab rather than opening a new File Explorer window. Switching between multiple file locations is seamless, all thanks to this feature. But Microsoft isn’t planning to stop here. It wants to completely overhaul the File Explorer.

 File Explorer Gallery is one such new feature that Microsoft is testing in the Canary channel. Having a Gallery section will remove the need to browse separate folders to find or preview an image. Want to enable the feature on your system? Let’s begin.

## What Is the Gallery Feature in Windows File Explorer?

 File Explorer’s Gallery feature works exactly like it sounds. It categorically lists all the images on your system in a separate section, so you can find and view all the images in one tab. Android File Explorers have had this feature for quite a long, but Windows seems to care about it now.

 This new feature is available in the Windows Insider build version 25300 and above. But Microsoft made a big change to the Insider program by adding a Canary channel. So, any new Canary build will also have this experimental feature. Microsoft adds the new File Explorer based on Windows App SDK, which you can verify by hovering over the “pizza” icon in the File Explorer address bar.

 The Gallery section displays images from the Pictures and OneDrive folders and lists them by date. It has nice, rounded corners around each image in the Gallery section, which makes it feel like a part of the overall Windows 11 design. It appears right below the Home option in the left pane.

## How to Enable Gallery in File Explorer in Windows 11

 Repeat the following steps to enable the new Gallery section in File Explorer:

### 1\. Update to the Appropriate Windows Insider Build

 The Gallery section is hidden in Insider builds 25300 and above. If you are a Windows Insider program participant, open and check for the latest Insider builds on your system. Make sure to be in the Dev or Canary channel because this experimental feature is exclusive to these channels only. Or, you can use [UUP Dump to download Windows Insider builds without participating in Microsoft’s Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

### 2\. Download ViVeTool

 You will also need ViVeTool to enable these experimental features on your system. You can [download ViVetool from GitHub](https://github.com/thebookisclosed/ViVe/releases) , but make sure that you pick the most recent release. Extract the tool to the C drive and then proceed to the next section.

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
4. Lastly, click on the**OK** button to finalize the changes. The Gallery section won’t display any images from the excluded folder from now onwards.

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
<li><a href="https://win11-tips.techidaily.com/decoding-user-dissatisfaction-with-microsofts-latest-update/"><u>Decoding User Dissatisfaction with Microsoft's Latest Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-end-of-windows-xp-7-and-81-era-from-microsoft/"><u>The End of Windows XP, 7 & 8.1 Era From Microsoft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/charting-your-course-through-cortana-history-windows/"><u>Charting Your Course Through Cortana History (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-dims-handbook-for-windows-11-repair/"><u>The Complete DIMS Handbook for Windows 11 Repair</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-no-wi-fi-in-windows-network/"><u>Breaking Down No Wi-Fi in Windows Network</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-visual-display-top-5-ideal-windows-pc-clock-themed-screensavers/"><u>Enhance Visual Display: Top 5 Ideal Windows PC Clock-Themed Screensavers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-endless-login-prompts-on-windows-os/"><u>Bypassing Endless Login Prompts on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-the-functionality-of-fn-keys-on-modern-pcs-windows-11/"><u>Configuring the Functionality of FN Keys on Modern PCs (Windows 11)</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-instagram-reels-sonic-boom-integrating-music-voiceovers/"><u>2024 Approved  Instagram Reels Sonic Boom  Integrating Music, Voiceovers</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-top-10-best-video-speed-changing-apps-for-free-ios-and-android-2022/"><u>New 2024 Approved Top 10 Best Video Speed Changing Apps for FREE iOS and Android, 2022</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-unseen-features-in-depth-look-at-instagrams-ask-emoji/"><u>[New] In 2024, Unseen Features  In-Depth Look at Instagram’s Ask Emoji</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/harmonizing-silence-a-comprehensive-guide-to-muting-superfluous-sounds-and-background-distractions-in-visionpro-studio-for-2024/"><u>Harmonizing Silence A Comprehensive Guide to Muting Superfluous Sounds and Background Distractions in VisionPro Studio for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-navigating-melodic-waters-a-legal-guide-on-instagram-for-2024/"><u>[Updated] Navigating Melodic Waters  A Legal Guide on Instagram for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-real-vs-fake-quick-ways-to-audit-your-insta-circle/"><u>2024 Approved  Real Vs. Fake  Quick Ways to Audit Your Insta Circle</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-the-aiff-converter-checklist-essential-features-to-look-for/"><u>Updated The AIFF Converter Checklist Essential Features to Look For</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/free-speech-to-text-conversion-software-for-2024/"><u>Free Speech-to-Text Conversion Software for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-guide-to-recovering-stopped-fb-livestreams/"><u>[New] 2024 Approved  Guide to Recovering Stopped FB Livestreams</u></a></li>
</ul></div>
