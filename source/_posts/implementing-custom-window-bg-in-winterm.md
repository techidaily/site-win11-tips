---
title: Implementing Custom Window Bg in WinTerm
date: 2025-02-27T02:30:55.013Z
updated: 2025-03-04T22:11:06.612Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Implementing Custom Window Bg in WinTerm
excerpt: This Article Describes Implementing Custom Window Bg in WinTerm
keywords: WinTerm Background Tweak,Windows Terminal Color Change,Termite Theme Adjustment,Custom Terminal Skin Creation,Terminal UI Design Update,Window Bg Customization Tool,WinTerm Visual Enhancement
thumbnail: https://thmb.techidaily.com/13322664753ec1bcb9b951122efdf005d8bc61a3a13c44fac0ae0c8584b8720e.jpg
---

## Implementing Custom Window Bg in WinTerm

 Changing the background image of the Windows Terminal is an easy way to customize your command line experience. This adds a personal touch and makes your experience visually appealing.

 This tutorial will explain three methods to change the Terminal background image in Windows 11.

## How to Change Windows Terminal Background Image

 You can change the background image of Windows Terminal in three ways: using the**Default** option within the Terminal app or manually editing the settings.json file using**File Explorer** and**Run** dialog box. All three methods achieve the same result and are easy to use.

 Using the default option is the simplest way to change your background image while editing the settings.json file provides more control and customization options. Below, we will guide you through each option.

## 1\. Change Windows Terminal Background Image via Its Options

 The easiest way to change the background image of Windows Terminal is by using its option. This can be done by opening Windows Terminal and changing settings within the app. Here's how to do it:

 To get started, open the Windows Terminal application first. For this, click on the Windows icon to open the Start menu. Then type**Terminal** into the search box, and select it from the list.

 Once you open the Terminal application, click on the dropdown menu icon in the top left corner, and select the**Settings** option.

 In the settings window's left column, go to**Defaults** . Now move to the right side of the page and tap**Appearance** to expand it.

![Change Windows Terminal Background Image via Default Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-windows-terminal-background-image-via-default-option.jpg)

 Scroll down to the**Background image** section, then click the**Background image path** option. Next, click the**Browse** option and select an image you want to use as a background.

 Click**Open** to confirm your selection. Now you should be able to see the selected image as the background of the terminal.

 You can also copy and paste the file path of an image directly into the Background image path option. Finally, click the**Save** button and the background image will be set.

 To improve the appearance of your image in the Windows Terminal, you can customize it using several options. You can use**Background image stretch mode** to change how the image is resized to fill the window. Further, you can change the**Background image alignment** to adjust the image position, and**Background image opacity** to make it more or less transparent.

 Once you are satisfied with the changes, click the**Save** button in order to apply them. Your custom background image should now be visible in the Windows Terminal.

 If you want to switch to the default image,[reset the Windows Terminal to its default settings](https://www.makeuseof.com/windows-11-reset-terminal-settings/) . This will automatically restore your background to the default image.

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

 Then paste this path into the**backgroundImage** section of settings.json. Remember to include a comma (**,**) after the path, as shown in the image above.

 Once you have pasted the path of your image, save the settings file and close the text editor. To apply this new background image, simply restart your Windows Terminal. The new background image should be displayed on the terminal window.

 You can adjust the image transparency using the same method. Simply input values for the**backgroundImageOpacity** parameters to modify the settings. These additional settings allow you to personalize your Windows Terminal background image even further.

 Restart Windows Terminal for the changes to take effect. In this way, you can easily customize your Windows Terminal background image using the settings.json file.

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
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-streamlining-your-profile-alter-name-in-google-meet/"><u>[Updated] 2024 Approved Streamlining Your Profile Alter Name in Google Meet</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-maximizing-chrome-multitasking-via-picture-in-picture-mode/"><u>[Updated] In 2024, Maximizing Chrome Multitasking via Picture in Picture Mode</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-vimeos-video-mosaics-inserting-chapters-for-clarity/"><u>[Updated] In 2024, Vimeo's Video Mosaics Inserting Chapters for Clarity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creer-des-fichiers-wav-a-partir-de-fichiers-caf-gratuits-online-conversion-avec-movavi/"><u>Créer Des Fichiers WAV À Partir De Fichiers CAF Gratuits - Online Conversion Avec Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effizientes-mp4-komprimieren-mit-movavi-professionelle-tipps-und-tricks/"><u>Effizientes MP4 Komprimieren Mit Movavi: Professionelle Tipps Und Tricks</u></a></li>
<li><a href="https://unlock-android.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-honor-magic-vs-2-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your Honor Magic Vs 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-raw-to-jpeg-converter-easy-and-fast-with-movavi/"><u>Free Online RAW to JPEG Converter - Easy and Fast with Movavi</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/gmail-rescue-mission-steps-to-recover-missing-or-misfiled-email-messages-efficiently/"><u>Gmail Rescue Mission: Steps to Recover Missing or Misfiled Email Messages Efficiently</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-itel-p55t-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Itel P55T to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mp4-file-merging-techniques-with-movavi-a-comprehensive-guide/"><u>MP4 File Merging Techniques with Movavi - A Comprehensive Guide</u></a></li>
<li><a href="https://solve-outstanding.techidaily.com/solving-the-mystery-of-blurry-scans-expert-advice-from-yl-computing/"><u>Solving the Mystery of Blurry Scans: Expert Advice From YL Computing</u></a></li>
<li><a href="https://win-blog.techidaily.com/windows-10-52024/"><u>Windows 10 動画編集ツール強化チャート ベスト5（2024年度更新）</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726222495571-movavi/"><u>모바일 오디오를 조정하는 도구 - Movavi 스크린 리덕터</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aac-ogg-movavi/"><u>무료 솔루션: AAC OGG 데이터를 바꾸기, 인터넷에서 - Movavi</u></a></li>
</ul></div>

