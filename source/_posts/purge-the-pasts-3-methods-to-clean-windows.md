---
title: "Purge the Pasts: 3 Methods to Clean Windows"
date: 2024-09-14T22:21:40.180Z
updated: 2024-09-22T01:19:39.582Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Purge the Pasts: 3 Methods to Clean Windows"
excerpt: "This Article Describes Purge the Pasts: 3 Methods to Clean Windows"
keywords: Window Cleaning Tips,Effective Window Washing,Professional Window Deep Clean,Sparkling Windows Guide,Streak-Free Window Techniques,Eco-Friendly Window Care,Home Window Hygiene Methods
thumbnail: https://thmb.techidaily.com/8404aae8332517e90ea13209ccbcb49d56b9cbe41228f9bbeee698b42d6caf34.jpg
---

## Purge the Pasts: 3 Methods to Clean Windows

 When you change the wallpaper on your device, Windows stores a thumbnail of the recently used image in the “wallpaper history” section. Usually, this section contains around five images.

 You might want to clear your wallpaper history for privacy purposes. For example, clearing wallpaper history prevents others from seeing the private images you’ve previously used as wallpapers. In this article, we’ll check out how to clear the Windows wallpaper history.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to View Your Wallpaper History on Windows

 To view the five most recent pictures you’ve used as a background, simply follow these steps:

1. Press **Win + I** to open the system settings.
2. Click the **Personalization** option.
3. Click the **Background** drop-down menu and select **Picture**. This should display the five pictures you’ve previously used as wallpapers.

![Viewing wallpaper history on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/viewing-wallpaper-history-on-windows.jpg)

 If there's anything here you don't want people to see, it's time to clean out the wallpaper history.

## 1\. How to Clear the Wallpaper History via the Registry Editor

![A person using a Windows device on a desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-person-using-a-Windows-device-on-a-desk.jpg)

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
* BackgroundHistoryPath4

![Clicking the BackgroundHistoryPath4 value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-backgroundhistorypath4-value-in-the-registry-editor.jpg)

 In this case, **Path0** represents the first image, while **Path4** represents the fifth image in the "wallpaper history" section.

 If you’d like to remove the first image from your wallpaper history, right-click on the **BackgroundHistoryPath0** option and select **Delete**. From there, apply the same steps to delete the other images from the "wallpaper history" section.

 Want to delete all the images simultaneously? Click on the **BackgroundHistoryPath0** option, press **Shift**, and then click on **BackgroundHistoryPath4** (this will highlight all the options). From there, press the **Delete** button.

 Finally, close the Registry Editor and restart your PC to save these changes.

## 2\. Clear Wallpaper History By Using a Registry File

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 Editing Registry keys can often be a quite tedious task. If you're looking for an easy way out, then [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/).

 Wondering how this works? A Registry file allows you to edit Registry keys with just a few clicks. In fact, you won't even have to open the Registry Editor.

 Now, let’s explore how you can create a Registry file that helps you clear your wallpaper history:

1. Type **Notepad** in the Start menu search bar and select the **Best match**.
2. Next, type the following command:

Windows Registry Editor Version 5.00[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Wallpapers]"BackgroundHistoryPath0"=-"BackgroundHistoryPath1"=-"BackgroundHistoryPath2"=-"BackgroundHistoryPath3"=-"BackgroundHistoryPath4"=-

![A Registry file for clearing wallpaper history](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/a-registry-file-for-clearing-wallpaper-history.jpg)

 Now, navigate to the **File** tab and select the **Save As** option. Next, select the folder in which you'd like to save the file. From there, type **ClearMyWallpaperHistory.reg** in the **File name** section

 To use the Registry file, simply double-click on it. This should automatically clear your wallpaper history.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902278/19272" target="_top" id="1902278">
  <img src="//a.impactradius-go.com/display-ad/19272-1902278" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902278/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Overwrite the Previous Wallpaper History

 Struggling to clear your wallpaper history? Overwriting the Windows wallpaper history could help. To do that, you'd have to use five new different pictures—one at a time—as your background.

 In this case, this will only show your most recently used pictures. That way, you can indirectly "clear" any sensitive images from the wallpaper history and only display what you're comfortable with.

 Here’s how to overwrite your wallpaper history:

1. Press **Win + I** to open the system settings. Alternatively, check out [the different ways to access the Windows system settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Click the **Personalization** option.
3. Click the **Background** drop-down menu and select **Picture**.
4. Scroll down and click the **Browse** button. Finally, select a new image.

![Clicking the Browse button in the Background settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-browse-button-in-the-background-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080317/19272" target="_top" id="2080317">
  <img src="//a.impactradius-go.com/display-ad/19272-2080317" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080317/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://extra-approaches.techidaily.com/new-leading-the-color-grading-revolution-with-lightrooms-best-10-luts/"><u>[New] Leading the Color Grading Revolution with LightRoom’s Best 10 LUTs</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-streamline-the-conversion-vimeo-videos-to-mp3-files-for-2024/"><u>[Updated] Streamline the Conversion Vimeo Videos to MP3 Files for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-top-4-remedies-enhancing-iphone-hdr-images-in-premiere-pro/"><u>[Updated] Top 4 Remedies Enhancing iPhone HDR Images in Premiere Pro</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-futures-virtual-frontier-predicted-top-5-new-ps-vr-titles/"><u>2024 Approved Future's Virtual Frontier Predicted Top 5 New PS VR Titles</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-in-depth-look-at-obs-studios-full-screen-recorder-tools/"><u>2024 Approved In-Depth Look at OBS Studio's Full Screen Recorder Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/2024teki-zengin-uygulamalar-farkli-cesitli-video-vize-yayincilik-prodikti/"><u>2024'Teki Zengin Uygulamalar: Farklı Çeşitli Video Vize Yayıncılık Prodikti</u></a></li>
<li><a href="https://win11-tips.techidaily.com/converting-tiff-images-to-jpeg-format-free-easy-guide-with-movavi/"><u>Converting TIFF Images to JPEG Format Free - Easy Guide with Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-offline-vob-to-m4a-transformation-try-the-no-cost-movavi-solution/"><u>Easy Offline VOB to M4A Transformation - Try the No Cost Movavi Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guia-de-descarga-gratuita-para-convertir-archivos-avi-a-formato-m4a-con-convertidor-on-line-de-movavi/"><u>Guía De Descarga Gratuita Para Convertir Archivos AVI a Formato M4A Con Convertidor On-Line De Movavi</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-xiaomi-redmi-12-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Xiaomi Redmi 12 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/i-migliori-strumenti-per-la-fusione-musicale-del-2024-scelta-definitiva-secondo-movavi/"><u>I Migliori Strumenti per La Fusione Musicale Del 2024: Scelta Definitiva Secondo Movavi</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-exploring-unconventional-perspectives-in-photos/"><u>In 2024, Exploring Unconventional Perspectives in Photos</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tips-and-tricks-to-tell-if-your-apple-iphone-15-pro-max-is-unlocked-by-drfone-ios/"><u>In 2024, Tips And Tricks To Tell if Your Apple iPhone 15 Pro Max Is Unlocked</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-legendaries-are-in-pokemon-platinum-on-motorola-razr-40-drfone-by-drfone-virtual-android/"><u>In 2024, What Legendaries Are In Pokemon Platinum On Motorola Razr 40? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/m4a-aac-movavi/"><u>M4A를 AAC로 자유성 변환하는 웹 기회 - Movavi에서 시작!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-ranked-photography-slide-show-apps-windows-mac-and-web-options/"><u>Top-Ranked Photography Slide Show Apps : Windows, Mac & Web Options</u></a></li>
</ul></div>

