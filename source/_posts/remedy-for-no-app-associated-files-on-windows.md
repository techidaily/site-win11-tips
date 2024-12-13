---
title: Remedy for No App Associated Files on Windows
date: 2024-12-10T02:12:03.041Z
updated: 2024-12-12T19:29:59.750Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedy for No App Associated Files on Windows
excerpt: This Article Describes Remedy for No App Associated Files on Windows
keywords: Windows File Issue Remedy,Solve Windows No Apps Error,Fixing Windows Missing File Problem,Resolve Windows Application Loss,Mend Windows App Not Found,Windows Files Association Help,Cure Unlinked Windows Extensions
thumbnail: https://thmb.techidaily.com/310ebf5ae5294b3c09bff886e3c558b63079bc0b815690abddeb6c6ade1d7933.JPG
---

## Remedy for No App Associated Files on Windows

 The error "this file does not have an app associated with it" mainly occurs when Windows can't find a compatible app for opening a specific file type. If you have the relevant app installed, it might not be set as default to open files of that format, or the app or file itself could be corrupted or damaged.

 The error can also occur when opening folders, mainly from Windows Search, and even when running apps and games. Here are some solutions you can apply to resolve this error regardless of where you get it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Ensure You Have an App Installed That Can Open Such Files

 Windows presents this error primarily when it fails to find the appropriate app to open files. Therefore, first, you should check whether you have the right app installed to open files in this particular format. There are several ways to check this, but here is one of the easiest:

1. Navigate to the file that is displaying this error when you open it.
2. Right-click the file and select**Properties** .
3. Navigate to the**General** tab and look for the file format next to**Type of file** .  
![Check the File Format in Properties Window of File in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/1-1.jpg)

 If it's a commonly used file format, such as PDF, JPEG, PNG, Docx, etc., for which you have the appropriate app installed, move on directly to heading #2\. However, if you see an unusual file format here—something you haven't seen before, make sure you have the appropriate app installed.

 To confirm this, right-click the file and navigate to**Open with > Choose another app** .

![Click on Choose Another App by Right-clicking on the File in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/2-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you have a relevant app installed, Windows will suggest you select it to open the file. If you don't see any app suggestions here, you probably don't have any apps installed capable of opening this file type.

![Windows Suggesting Some Apps to Open the Image File in PNG Format](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-suggesting-some-apps-to-open-the-image-file-in-png-format.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If that's the case, simply go to any of your browsers, search for Windows apps that can run files in that format, and download them. After downloading the appropriate app, make it the default for opening this file type.

## 2\. Set the Default Application for the File Type

 The error message states that if the app is already installed, you need to create an association in the Default Programs. If you already had the compatible app installed or have just downloaded it, your next step should be to set it as default for files having that file type or format. Setting the compatible application as default may solve this problem right away.

 If you haven't changed a default app before, check out our article on[Windows 11 default apps](https://www.makeuseof.com/change-windows-11-default-apps/) . The article discusses various ways to change the default app, but we recommend using the second method, which is using the Settings app. That's because this method lets you search for specific file formats and choose a default app for them.

## 3\. Is the Default App Already Selected? Repair or Change It

 If the app you intend to set as default for a particular file format is already selected as a default application, but Windows still displays this error, the app has likely become corrupt, thus causing the error.

 To rule out this possibility, you should run the App troubleshooter, update the problematic app, reset its cache, or repair and reset it. You can find instructions for performing these steps in our[g](https://www.makeuseof.com/apps-arent-working-properly-windows/) uide for[fixing apps that don't work on Windows](https://www.makeuseof.com/apps-arent-working-properly-windows/) .

 Try these steps to see if they fix the problem. If the issue persists after that, we recommend you reinstall the app or select a different one as the default. If you don't have a different app installed on your device that supports these files, install one that does.

## 4\. Check for Specific File Issues

 If you're opening the file in a compatible app, it's working normally, and you've already set it as default, but you're still encountering the error, verify the file itself isn't corrupt. To confirm that, open any other file having the same file format and see if it returns the same error.

 If other files open without error, but the issue persists with one file, it's likely that the file is corrupt. If that's the case, follow our[guide on using Windows built-in tools to fix corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) . If that doesn't fix the problem, try using one of the[dedicated tools for repairing corrupted files](https://www.makeuseof.com/tag/best-tools-repair-corrupted-damaged-files-windows/) .

 Misconfiguring the Registry settings can result in undesirable outcomes and even render your device unbootable. Before you try the next fix, create a[backup of the Windows Registry so you can restore it](https://www.makeuseof.com/tag/backup-restore-windows-registry/) if something goes wrong.

## 5\. Use the Registry

 If none of the above fixes have been successful, try this registry tweak as a last resort:

1. Type**"regedit"** in Windows Search and open the**Registry Editor** .  
![Open Registry Editor App From Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/4-1.jpg)
2. Paste the path below into the address bar of Registry Editor.  
Computer\HKEY_CLASSES_ROOT\lnkfile
3. Select the**Inkfile** key. Then, look in the right pane and see if there is a string value called**"IsShortcut** .**"**  
![Locate the IsShortcut String Value in the Inkfile Key of Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/5-1.jpg)
4. If it's not there, right-click in the blank area and go to**New > String Value** . Then rename it to**"IsShortcut** .**"**  
![Create and Rename the New String Value in Windows Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/6.jpg)
5. If the string value is already there, right-click on it and select**Delete** .  
![Select Delete by Right-clicking on the String Value in Windows Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/7.jpg)
6. After that, follow step four to recreate it. Don't forget to rename it appropriately so you don't encounter any issues.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Restart your device once after that.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Do You Encounter the Error When Opening Folders? Follow These Tips

 If you get the "This file does not have an app associated with it" error when opening folders, try these checks:

* Restart File Explorer (see[how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) for tips).
* If you're opening a folder by searching it in Windows Search or Quick Access, consider opening it directly from File Explorer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Do You Encounter the Error When Opening Apps or Games? Try These Tips

 If you get the "This file does not have an app associated with it" error when opening an app or game, perform the following checks:

* If you're using a shortcut to open games, especially the ones installed in a gaming client, open them from the gaming client or the installation directory.
* In case the game launcher requires you to log in before playing any of the installed games, ensure you do so.
* If you're experiencing this error in a specific game or app, ensure its files haven't been corrupted.

## Easily Open Your Apps, Files, and Folders Again on Windows

 Seeing the error "this file does not have an app associated with it" when opening a file, folder, or app can be frustrating. If the file or folder isn't corrupt, the above fixes will help you identify and resolve the issue's root cause. If nothing works, you can reinstall the app or restore the older version of the file or folder from your backup.

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-effective-screenrecording-practices-for-professionals-for-2024/"><u>[New] Effective ScreenRecording Practices for Professionals for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analisi-completa-di-apowersoft-screen-recorder-dettagli-sul-funzionamento-costi-e-piu-informazioni/"><u>Analisi Completa Di Apowersoft Screen Recorder - Dettagli Sul Funzionamento, Costi E Più Informazioni</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cele-mai-populari-convertitorii-de-video-gratuti-mkv-in-mp4-format-compatibile-cu-windows-si-mac-treiste-o-vizibilitate-mai-mare/"><u>Cele Mai Populari Convertitorii De Video Gratuți, MKV in MP4 Format, Compatibile Cu Windows Și Mac - Treiște O Vizibilitate Mai Mare!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-transition-from-mpg-to-m4v-get-started-here-for-free/"><u>Effortlessly Transition From MPG to M4V - Get Started Here for Free!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-converter-transform-flac-files-into-m4a-format-with-ease-movavi/"><u>Free Online Converter: Transform FLAC Files Into M4A Format with Ease - Movavi</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-fix-baldurs-gate-3-pc-instability-issues-successfully/"><u>How to Fix Baldur's Gate 3 PC Instability Issues Successfully</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-identify-and-open-an-avi-file-a-comprehensive-guide/"><u>How To Identify and Open an AVI File: A Comprehensive Guide</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-asus-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass Asus FRP</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-elevating-windows-10-photos-visuals-through-personalized-filtersmusic/"><u>In 2024, Elevating Windows 10 Photos Visuals Through Personalized Filters/Music</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/introduction-to-mandarin-scripting/"><u>Introduction to Mandarin Scripting</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/kindleoasis-2019-comprehensive-review-for-a-paper-quality-reading-experience/"><u>KindleOasis (2019) Comprehensive Review for a Paper-Quality Reading Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/kostenloze-omzetting-van-rmvb-naar-wmv-online-efficient-met-movavi/"><u>Kostenloze Omzetting Van RMVB Naar WMV Online - Efficiënt Met Movavi</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-in-2024-are-there-better-alternatives-to-magix-samplitude-for-professional-sound-design/"><u>New In 2024, Are There Better Alternatives to MAGIX Samplitude for Professional Sound Design?</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/top-three-asian-languages-quick-sort-and-keep-track/"><u>Top Three Asian Languages: Quick Sort & Keep Track</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforma-tu-archivo-aif-a-formato-de-audio-m4a-sin-coste-alguno-con-el-servicio-online-de-convertidor-de-archivos/"><u>Transforma Tu Archivo AIF a Formato De Audio M4A Sin Coste Alguno Con El Servicio Online De Convertidor De Archivos</u></a></li>
</ul></div>

