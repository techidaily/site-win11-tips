---
title: Setting WinTerminal's Bg Pic
date: 2024-08-16T01:51:10.591Z
updated: 2024-08-17T01:51:10.591Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Setting WinTerminal's Bg Pic
excerpt: This Article Describes Setting WinTerminal's Bg Pic
keywords: Terminal Color Background,Windows Terminal Image,Set Win Terminal Picture,Win Terminal Desktop Palette,Customize Win Terminal Backdrop,Change WinTerminal BG Pic,WinTerminal Theme Adjustment
thumbnail: https://thmb.techidaily.com/1fc6ba74c900007ae783d7c5d15561029afe7a276cbf090aca63438453de7715.jpg
---

## Setting WinTerminal's Bg Pic

 Changing the background image of the Windows Terminal is an easy way to customize your command line experience. This adds a personal touch and makes your experience visually appealing.

 This tutorial will explain three methods to change the Terminal background image in Windows 11.

## How to Change Windows Terminal Background Image

 You can change the background image of Windows Terminal in three ways: using the**Default** option within the Terminal app or manually editing the settings.json file using**File Explorer** and**Run** dialog box. All three methods achieve the same result and are easy to use.

 Using the default option is the simplest way to change your background image while editing the settings.json file provides more control and customization options. Below, we will guide you through each option.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
## 1\. Change Windows Terminal Background Image via Its Options

 The easiest way to change the background image of Windows Terminal is by using its option. This can be done by opening Windows Terminal and changing settings within the app. Here's how to do it:

 To get started, open the Windows Terminal application first. For this, click on the Windows icon to open the Start menu. Then type**Terminal** into the search box, and select it from the list.

 Once you open the Terminal application, click on the dropdown menu icon in the top left corner, and select the**Settings** option.

 In the settings window's left column, go to**Defaults** . Now move to the right side of the page and tap**Appearance** to expand it.

![Change Windows Terminal Background Image via Default Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-windows-terminal-background-image-via-default-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->

 Scroll down to the**Background image** section, then click the**Background image path** option. Next, click the**Browse** option and select an image you want to use as a background.

 Click**Open** to confirm your selection. Now you should be able to see the selected image as the background of the terminal.

 You can also copy and paste the file path of an image directly into the Background image path option. Finally, click the**Save** button and the background image will be set.

 To improve the appearance of your image in the Windows Terminal, you can customize it using several options. You can use**Background image stretch mode** to change how the image is resized to fill the window. Further, you can change the**Background image alignment** to adjust the image position, and**Background image opacity** to make it more or less transparent.

 Once you are satisfied with the changes, click the**Save** button in order to apply them. Your custom background image should now be visible in the Windows Terminal.

 If you want to switch to the default image,[reset the Windows Terminal to its default settings](https://www.makeuseof.com/windows-11-reset-terminal-settings/) . This will automatically restore your background to the default image.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
## 2\. Change the Windows Terminal Background Image via Windows File Explorer

 Manually editing settings.json is another great way to customize your Windows Terminal background image. For this, you need to open the settings.json file in any text editor, such as Notepad. Here's how to do it:

1. Open Windows File Explorer (see our guide on [how to open File Explorer on a Windows PC](https://www.makeuseof.com/windows-open-file-explorer/) ).
2. Once you're in File Explorer, navigate to your**C:** drive and select the**Users** folder.
3. Locate your**username** in this folder, then open the**AppData** folder and the**Local** folder.
4. In the Local folder, find and open the**Packages** folder.
5. Look for the**Microsoft.WindowsTerminal\_8wekyb3d8bbwe** folder and open it.
6. Finally, in this folder, double-click on**Settings** to open settings.json in any text editor.

 In the settings.json file, you will find a section called**backgroundImage** . You can use**Ctrl + F** to find it quickly.

 This is where you can enter the path of your own image to set as the Windows Terminal background. To do this, first copy the full file path for the image you want to use, including the file name.

![How to Change Windows Terminal Background Image From Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-change-windows-terminal-background-image-from-windows-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->

 Then paste this path into the**backgroundImage** section of settings.json. Remember to include a comma (**,**) after the path, as shown in the image above.

 Once you have pasted the path of your image, save the settings file and close the text editor. To apply this new background image, simply restart your Windows Terminal. The new background image should be displayed on the terminal window.

 You can adjust the image transparency using the same method. Simply input values for the**backgroundImageOpacity** parameters to modify the settings. These additional settings allow you to personalize your Windows Terminal background image even further.

 Restart Windows Terminal for the changes to take effect. In this way, you can easily customize your Windows Terminal background image using the settings.json file.

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
## 3\. Change the Windows Terminal Background Image Using the Run Command

 The Run Command can also help you change your Windows Terminal background image. Instead of searching for the settings.json file in Windows File Explorer, you can directly access and modify it using this tool.

 Follow these instructions to customize your Windows Terminal background image using the Run Command tool:

1. Right-click on Start and select**Run** from the menu list. If you prefer using shortcut keys, press**Win + R** on your keyboard to open the tool directly.
2. In the text box, type the following command and press Enter:  
`%localappdata%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState`
3. This will open the Local State folder containing the settings.json file. Right-click on**Settings** and select**Open with** \>**Notepad** .  
![Change Windows Terminal Background Image From Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-windows-terminal-background-image-from-windows-file-explorer.jpg)
4. Scroll down to the**backgroundImage** section and replace the image path with your own.
5. Then press**Ctrl + S** on your keyboard to save the changes.
6. Close Notepad, then open Windows Terminal to see your new background image.

 You’re done! Now you know how to customize your Windows Terminal background image using the Run Command tool. You can further explore the settings.json file or use other tools to [customize and personalize your Windows Terminal](https://www.makeuseof.com/windows-terminal-customization/) .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Set a New Background Image for Windows Terminal

 It's easy to customize your Windows Terminal by adding or changing the background image. All you need to do is access the settings.json file, where you can also adjust your image's transparency. Just remember to restart Windows Terminal after making changes. Read this guide to learn how to customize your Windows Terminal background image easily.

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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-flip-the-script-learning-to-negative-play-in-instagram/"><u>[New] 2024 Approved  Flip the Script  Learning to Negative Play in Instagram</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-the-process-to-enable-incessant-auto-video-on-facebook/"><u>[New] In 2024, The Process to Enable Incessant Auto-Video on Facebook</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-a-comprehensive-list-of-the-best-6-microphones-for-video-hosts/"><u>[Updated] A Comprehensive List of the Best 6 Microphones for Video Hosts</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-tailored-minecraft-filming-techniques-for-gamers/"><u>[Updated] In 2024, Tailored Minecraft Filming Techniques for Gamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disrupted-microphone-input-in-valorant-windows/"><u>Addressing Disrupted Microphone Input in Valorant (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-admin-username-on-windows-11-step-by-step-guide/"><u>Altering Admin Username on Windows 11: Step-by-Step Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/are-experiencing-issues-with-nintendo-switch-online-service-disruption-or-connectivity-problems/"><u>Are Experiencing Issues with Nintendo Switch Online - Service Disruption or Connectivity Problems?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-language-skills-using-windows-1011-hotkeys/"><u>Boost Your Language Skills Using Windows 10/11 Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breakdown-of-microsofts-earnings-through-windows-11/"><u>Breakdown of Microsoft's Earnings Through Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-no-wi-fi-in-windows-network/"><u>Breaking Down No Wi-Fi in Windows Network</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-windows-11-theme-barriers-using-registry/"><u>Breaking Through Windows 11 Theme Barriers Using Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-a-secure-quick-launch-button-for-hardware-removal/"><u>Creating a Secure, Quick-Launch Button for Hardware Removal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diminish-noise-restoring-your-keys-sound-functionality/"><u>Diminish Noise: Restoring Your Key's Sound Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-reasons-to-never-turn-off-your-windows-11-push-notifications/"><u>Discover Reasons to Never Turn Off Your Windows 11 Push Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-device-safety-increase-win11-pin-length/"><u>Elevate Your Device Safety: Increase Win11 PIN Length</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11-taskbar-responsiveness/"><u>Enhancing Windows 11 Taskbar Responsiveness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-updating-username-on-windows-11/"><u>Essential Guide to Updating Username on Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/expert-tips-for-effortless-google-podcast-upload/"><u>Expert Tips for Effortless Google Podcast Upload</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-nokia-c210-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Nokia C210 Phones with/without a PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-cut-down-on-menus-in-windows-11/"><u>How to Cut Down on Menus in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-a-nonfunctional-nvidia-cp-on-windows-11/"><u>How to Reactivate a Nonfunctional Nvidia CP on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-spot-and-dismantle-unused-windows-folders-easily/"><u>How to Spot & Dismantle Unused Windows Folders Easily</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-ispoofer-on-vivo-y02t-drfone-by-drfone-virtual-android/"><u>How to use iSpoofer on Vivo Y02T? | Dr.fone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-bring-your-spotify-mixes-online-5-top-playlist-conversion-apps-for-youtube/"><u>In 2024, Bring Your Spotify Mixes Online  5 Top Playlist Conversion Apps for YouTube</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-instagram-influence-made-possible-today/"><u>In 2024, Instagram Influence Made Possible Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/incorporating-external-disk-into-explorer-nav-pane/"><u>Incorporating External Disk Into Explorer Nav Pane</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-the-dxgidll-file-missing-in-windows-11-heres-how-to-fix-it/"><u>Is the Dxgi.dll File Missing in Windows 11? Here's How to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-disabling-xbox-game-pass-error/"><u>Mastering the Art of Disabling Xbox Game Pass Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-terminal-configuration-basics/"><u>Mastering Windows Terminal Configuration Basics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-mouse-controls-in-win11-effortlessly/"><u>Navigating Mouse Controls in Win11 Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-depths-of-diablos-first-adventure/"><u>Navigating the Depths of Diablo's First Adventure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/power-up-your-device-instantly-mastering-win-11s-double-clicked-apk-method/"><u>Power Up Your Device Instantly: Mastering Win 11'S Double-Clicked APK Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-your-lost-dxgidll-with-these-win11-hacks/"><u>Restore Your Lost Dxgi.dll with These Win11 Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-initiate-sfc-process-in-windows-1087/"><u>Steps to Initiate SFC Process in Windows 10/8/7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-tackling-windows-1011-interrupt-crashes/"><u>Strategies for Tackling Windows 10/11 INTERRUPT Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-file-denial-in-steam-for-windows-11-users/"><u>Tackling File Denial in Steam for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-pathways-open-directory-games-in-windows/"><u>The Hidden Pathways: Open Directory Games in Windows</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/unveiling-the-hidden-treasure-of-royalty-free-graphics/"><u>Unveiling the Hidden Treasure of Royalty-Free Graphics</u></a></li>
</ul></div>
