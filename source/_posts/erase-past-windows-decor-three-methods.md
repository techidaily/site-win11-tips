---
title: "Erase Past Windows Decor: Three Methods"
date: 2024-06-25T16:16:36.645Z
updated: 2024-06-26T16:16:36.645Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Erase Past Windows Decor: Three Methods"
excerpt: "This Article Describes Erase Past Windows Decor: Three Methods"
keywords: Erase Windows Design,Remove Old Window Style,Cleaning Window Vintage,Modernize Windows Layout,Eliminate Ancient Windows,Update Outdated Windows,Revise Windows Decor
thumbnail: https://thmb.techidaily.com/22c39789b5fe1ed667e7cca081a20115c82b1e4756445b0d8d485b13ec35a1e3.jpg
---

## Erase Past Windows Decor: Three Methods

 When you change the wallpaper on your device, Windows stores a thumbnail of the recently used image in the “wallpaper history” section. Usually, this section contains around five images.

 You might want to clear your wallpaper history for privacy purposes. For example, clearing wallpaper history prevents others from seeing the private images you’ve previously used as wallpapers. In this article, we’ll check out how to clear the Windows wallpaper history.

## How to View Your Wallpaper History on Windows

 To view the five most recent pictures you’ve used as a background, simply follow these steps:

1. Press **Win + I** to open the system settings.
2. Click the **Personalization** option.
3. Click the **Background** drop-down menu and select **Picture**. This should display the five pictures you’ve previously used as wallpapers.

![Viewing wallpaper history on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/viewing-wallpaper-history-on-windows.jpg)

 If there's anything here you don't want people to see, it's time to clean out the wallpaper history.

## 1\. How to Clear the Wallpaper History via the Registry Editor ![A person using a Windows device on a desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-person-using-a-Windows-device-on-a-desk.jpg)

 The Registry Editor is a fantastic tool that allows you to configure some PC settings or troubleshoot system issues. But before you edit the Registry keys, always ensure to [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first. This will ensure that you have something to revert back to if something goes wrong.

 Now, let’s explore how you can clear your wallpaper history using the Registry Editor:

1. Type **Registry Editor** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.
3. Copy and paste the following command into the address bar:

Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Wallpapers

 You should see the following five background history paths on the right-hand side:

* BackgroundHistoryPath0
* BackgroundHistoryPath1
* BackgroundHistoryPath2
* BackgroundHistoryPath3
* BackgroundHistoryPath4 ![Clicking the BackgroundHistoryPath4 value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-backgroundhistorypath4-value-in-the-registry-editor.jpg)

 In this case, **Path0** represents the first image, while **Path4** represents the fifth image in the "wallpaper history" section.

 If you’d like to remove the first image from your wallpaper history, right-click on the **BackgroundHistoryPath0** option and select **Delete**. From there, apply the same steps to delete the other images from the "wallpaper history" section.

 Want to delete all the images simultaneously? Click on the **BackgroundHistoryPath0** option, press **Shift**, and then click on **BackgroundHistoryPath4** (this will highlight all the options). From there, press the **Delete** button.

 Finally, close the Registry Editor and restart your PC to save these changes.

## 2\. Clear Wallpaper History By Using a Registry File ![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 Editing Registry keys can often be a quite tedious task. If you're looking for an easy way out, then [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/).

 Wondering how this works? A Registry file allows you to edit Registry keys with just a few clicks. In fact, you won't even have to open the Registry Editor.

 Now, let’s explore how you can create a Registry file that helps you clear your wallpaper history:

1. Type **Notepad** in the Start menu search bar and select the **Best match**.
2. Next, type the following command:

Windows Registry Editor Version 5.00 [HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Wallpapers]"BackgroundHistoryPath0"=-"BackgroundHistoryPath1"=-"BackgroundHistoryPath2"=-"BackgroundHistoryPath3"=-"BackgroundHistoryPath4"=-

![A Registry file for clearing wallpaper history](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/a-registry-file-for-clearing-wallpaper-history.jpg)

 Now, navigate to the **File** tab and select the **Save As** option. Next, select the folder in which you'd like to save the file. From there, type **ClearMyWallpaperHistory.reg** in the **File name** section

 To use the Registry file, simply double-click on it. This should automatically clear your wallpaper history.

## 3\. Overwrite the Previous Wallpaper History

 Struggling to clear your wallpaper history? Overwriting the Windows wallpaper history could help. To do that, you'd have to use five new different pictures—one at a time—as your background.

 In this case, this will only show your most recently used pictures. That way, you can indirectly "clear" any sensitive images from the wallpaper history and only display what you're comfortable with.

 Here’s how to overwrite your wallpaper history:

1. Press **Win + I** to open the system settings. Alternatively, check out [the different ways to access the Windows system settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Click the **Personalization** option.
3. Click the **Background** drop-down menu and select **Picture**.
4. Scroll down and click the **Browse** button. Finally, select a new image.

![Clicking the Browse button in the Background settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-browse-button-in-the-background-settings.jpg)

 Repeat this process five times. From there, you should start seeing different images in the "wallpaper history" section.

## Your Previous Wallpapers Are Nowhere to Be Found

 Windows allows you to personalize your device to your liking. But then the system often keeps track of the changes you make on your PC. Fortunately, you can easily prevent others from seeing the changes you make on your device. For example, you can remove your wallpaper history using any of the methods we’ve covered.


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
<li><a href="https://win11-tips.techidaily.com/keys-fans-ultimate-guide-to-score-lifetime-windows-11-at-unbeatable-price/"><u>Keys Fans' Ultimate Guide to Score Lifetime Windows 11 at Unbeatable Price</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-finding-files-in-windows-11-with-the-search-bar/"><u>Accelerate Finding Files in Windows 11 with the Search Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brightness-boost-for-windows-11-control-your-pcs-glow/"><u>Brightness Boost for Windows 11: Control Your PC's Glow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-guide-5-steps-to-reset-windows-defender-status/"><u>Troubleshooting Guide: 5 Steps to Reset Windows Defender Status</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-track-of-windows-shots-folders/"><u>Keeping Track of Windows Shots' Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-enhance-powershell-access-control/"><u>Steps to Enhance PowerShell Access Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-code-0x80070091-empty-directories-unveiled/"><u>Tackling Windows Error Code 0X80070091 - Empty Directories Unveiled</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-infinix-note-30-pro-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Infinix Note 30 Pro Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-unveiling-video-sharing-secrets-examining-igtv-and-youtube-in-depth/"><u>[Updated] Unveiling Video Sharing Secrets  Examining IGTV & YouTube in Depth</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-beginners-guide-to-enhancing-imovie-productions-with-audio/"><u>2024 Approved Beginners Guide to Enhancing iMovie Productions with Audio</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-the-ultimate-guide-to-importing-and-exporting-videos-in-adobe-premiere-pro/"><u>2024 Approved The Ultimate Guide to Importing and Exporting Videos in Adobe Premiere Pro</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/unraveling-the-enigma-creating-hidden-snapstories/"><u>Unraveling the Enigma  Creating Hidden Snapstories</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-9-realme-gt-neo-5-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>In 2024, Top 9 Realme GT Neo 5 Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-estimating-time-for-20mb-media-file/"><u>[Updated] 2024 Approved  Estimating Time for 20MB Media File</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-top-video-editing-tools-for-young-creators-free-and-paid-options-for-2024/"><u>Updated Top Video Editing Tools for Young Creators Free and Paid Options for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-advances-in-syma-x8c-flight-autonomy/"><u>[Updated] Advances in Syma X8C Flight Autonomy</u></a></li>
</ul></div>
