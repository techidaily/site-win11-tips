---
title: Banish History, Welcome New Hues on Windows
date: 2025-01-31T00:50:59.719Z
updated: 2025-02-01T14:36:16.885Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Banish History, Welcome New Hues on Windows
excerpt: This Article Describes Banish History, Welcome New Hues on Windows
keywords: Banish Old Themes,Modern Windows Colors,Revamp Windows Palette,Update Windows Hues,New Windows Color Scheme,Eliminate History, Enhance Windows,Refresh Windows Theme Colors
thumbnail: https://thmb.techidaily.com/a8a2eae7840110809ce01981ae6ddd7381e7680b0d93e29805eecd4b92108f79.jpg
---

## Banish History, Welcome New Hues on Windows

 When you change the wallpaper on your device, Windows stores a thumbnail of the recently used image in the “wallpaper history” section. Usually, this section contains around five images.

 You might want to clear your wallpaper history for privacy purposes. For example, clearing wallpaper history prevents others from seeing the private images you’ve previously used as wallpapers. In this article, we’ll check out how to clear the Windows wallpaper history.

## How to View Your Wallpaper History on Windows

 To view the five most recent pictures you’ve used as a background, simply follow these steps:

1. Press **Win + I** to open the system settings.
2. Click the **Personalization** option.
3. Click the **Background** drop-down menu and select **Picture**. This should display the five pictures you’ve previously used as wallpapers.

![Viewing wallpaper history on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/viewing-wallpaper-history-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If there's anything here you don't want people to see, it's time to clean out the wallpaper history.

## 1\. How to Clear the Wallpaper History via the Registry Editor

![A person using a Windows device on a desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-person-using-a-Windows-device-on-a-desk.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Clear Wallpaper History By Using a Registry File

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Editing Registry keys can often be a quite tedious task. If you're looking for an easy way out, then [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/).

 Wondering how this works? A Registry file allows you to edit Registry keys with just a few clicks. In fact, you won't even have to open the Registry Editor.

 Now, let’s explore how you can create a Registry file that helps you clear your wallpaper history:

1. Type **Notepad** in the Start menu search bar and select the **Best match**.
2. Next, type the following command:

Windows Registry Editor Version 5.00 [HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Wallpapers]"BackgroundHistoryPath0"=-"BackgroundHistoryPath1"=-"BackgroundHistoryPath2"=-"BackgroundHistoryPath3"=-"BackgroundHistoryPath4"=-

![A Registry file for clearing wallpaper history](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/a-registry-file-for-clearing-wallpaper-history.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://instagram-clips.techidaily.com/new-edge-it-all-out-the-finest-frame-options-for-social-media-photography/"><u>[New] Edge It All Out The Finest Frame Options for Social Media Photography</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-high-definition-videography-unveiled-by-yi/"><u>[Updated] High Definition Videography Unveiled by Yi</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-hide-and-seek-with-fb-episodes/"><u>2024 Approved Hide-and-Seek with FB Episodes</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-under-the-hood-inside-knowledge-for-instagram-story-enthusiasts/"><u>2024 Approved Under the Hood Inside Knowledge for Instagram Story Enthusiasts</u></a></li>
<li><a href="https://win-studio.techidaily.com/3-tipen-om-windows-images-te-verplaatsen-bijeen-akkurate-overlegboek/"><u>3 Tipen Om Windows Images Te Verplaatsen Bijeen - Akkurate Overlegboek</u></a></li>
<li><a href="https://buynow-help.techidaily.com/affordable-tech-marvels-unveiled-the-complete-oneplus-nord-n100-review/"><u>Affordable Tech Marvels Unveiled - The Complete OnePlus Nord N100 Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-and-preventing-video-driving-issues-in-win1110/"><u>Correcting and Preventing Video Driving Issues in Win11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-essential-errors-fixing-issues-in-win10win11/"><u>Eradicating 'Essential' Errors: Fixing Issues in Win10/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-the-full-capabilities-of-windows-snip-and-sketch-tool/"><u>Explore the Full Capabilities of Windows' Snip & Sketch Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-windows-11-definers-guide/"><u>Immediate Windows 11 Definers Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-do-i-stop-someone-from-tracking-my-nokia-c12-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How Do I Stop Someone From Tracking My Nokia C12 Pro? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fake-gps-on-itel-p55-5g-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>In 2024, How To Fake GPS On Itel P55 5G For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-steps-for-print-tool-access-in-windows-11-max-48-chars/"><u>Key Steps for Print Tool Access in Windows 11 (Max 48 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/photo-carousel-in-windows-11-set-it-up-quickly-without-extras/"><u>Photo Carousel in Windows 11 – Set It Up Quickly, Without Extras</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shake-up-your-computing-experience-win-11s-non-native-tools/"><u>Shake Up Your Computing Experience: Win 11'S Non-Native Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-unheard-audio-during-windows-screencasts/"><u>Solutions for Unheard Audio During Windows Screencasts</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/speeding-up-your-periscope-streams-effortlessly-for-2024/"><u>Speeding Up Your Periscope Streams Effortlessly for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/spotlight-on-snapchat-utilization-strategies/"><u>Spotlight on Snapchat Utilization Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-resolving-the-0x8007251d-windows-error/"><u>Understanding and Resolving the 0X8007251d Windows Error</u></a></li>
</ul></div>

