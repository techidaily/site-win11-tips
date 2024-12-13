---
title: Resurrecting Windows Photo Viewer on Windows 11 Systems
date: 2024-12-08T21:41:54.792Z
updated: 2024-12-13T00:28:31.309Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resurrecting Windows Photo Viewer on Windows 11 Systems
excerpt: This Article Describes Resurrecting Windows Photo Viewer on Windows 11 Systems
keywords: Win XP Viewer Update,Revive Photo Viewer,W11 Photo Display,Windows Viewer Fix,Windows 11 Photo Viewer,Restore Image Viewer,Photo Viewer for W11
thumbnail: https://thmb.techidaily.com/5c86eead36fe273b4ffc3fa6b58927f405a2b86a9e9fd87736937318bdb673f7.jpg
---

## Resurrecting Windows Photo Viewer on Windows 11 Systems

### Quick Links

* [How to Restore Windows Photo Viewer in Windows 10/11 Using the Registry](#how-to-restore-windows-photo-viewer-in-windows-10-11-using-the-registry)
* [How to Disable Windows Photo Viewer in Windows 10 and 11](#how-to-disable-windows-photo-viewer-in-windows-10-and-11)
* [Use One Photo Viewer](#use-one-photo-viewer)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* Microsoft replaced the classic Windows Photo Viewer app in Windows 10 and 11 with the new Photos app.
* Fortunately, you can restore Windows Photo Viewer on your Windows computer using a registry hack.
* Additionally, you could try a third-party Windows Photo Viewer alternative like One Photo Viewer, as it offers a clean UI, better performance, and more features.

 Microsoft replaced the classic Photo Viewer app in Windows 10 and 11 with Photos, its modern, feature-rich image viewer. However, if you liked the simplicity of Photo Viewer, here's how you can bring it back in Windows 10 and 11\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Restore Windows Photo Viewer in Windows 10/11 Using the Registry

 You can enable the classic Windows Photo Viewer app using a Windows Registry script. The following Windows Registry script reconfigures and enables the Windows Photo Viewer app.

 Modifying your Windows Registry involves risk as incorrect modifications can cause your system to malfunction. If you intend to proceed with the steps below, first [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [back up your Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This will help you to recover your system if something goes wrong.

1. Press **Win + R** to open the **Run** dialog. Input **notepad** and click **OK**.
2. Copy and paste the following script into the Notepad file. This script activates the Windows Photo Viewer.  
`Windows Registry Editor Version 5.00 [HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll\shell\open] "MuiVerb"="@Windowsphotoviewer.dll,-3043" [HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll\shell\open\command] @="\"%SystemRoot%\\System32\\rundll32.exe\" \"%ProgramFiles%\\Windows Photo Viewer\\PhotoViewer.dll\", ImageView_Fullscreen %1" [HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll\shell\open\DropTarget] "Clsid"="{FFE2A43C-56B9-4bf5-9A79-CC6D4285608A}" [HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll\shell\print\command] @="\"%SystemRoot%\\System32\\rundll32.exe\" \"%ProgramFiles%\\Windows Photo Viewer\\PhotoViewer.dll\", ImageView_PrintTo %1" [HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll\shell\print\DropTarget] "Clsid"="{60fd46de-f830-4894-a628-6fa81bc0190d}"`  
![Notepad App Showing a Written Registry Script in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-written-registry-script-in-windows-11.png)
3. Press **Ctrl + Shift + S** to open the **Save** dialog. Alternatively, go to **File > Save As**.
4. In the **Save as** dialog, enter **ActivateWindowsPhotoViewer.reg** as the file name. Click the **Save as** **type** drop-down and choose **All Files(\*.\*)**. Choose a location and **Save** the file to your drive.  
![Notepad App Showing a Save As Dialog in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-save-as-dialog-in-windows-11.png)
5. Next, open **File Explorer**, browse to the location where you saved the file, double-click **ActivateWindowsPhotoViewer.reg**, and then click **Yes**. When a warning prompt appears, click **Yes**.
6. After the script is executed, you'll see a success message. Click **OK**.
7. To apply the changes, press **Win + X** to open the **Windows Power** **menu** and choose **Task Manager**.
8. In the **Process** tab, find and right-click on **Windows Explorer**, then click **Restart**. Your screen may flash momentarily as Windows Explorer restarts.  
![Windows 11 Task Manager Showing Restart Option for Windows Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-task-manager-showing-restart-option-for-windows-explorer.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Since Windows Photos Viewer doesn't have its own .EXE file, [but only a .DLL](https://www.makeuseof.com/what-are-dll-files-on-windows/), you can't open it from the search bar in Windows. Instead, to open pictures in Photo Viewer, right-click on any image in **File Explorer**, go to **Open With > Choose another app**, and then scroll down and select **Windows Photo Viewer**. Choose **Just once** to open the image. If you select **Always**, Windows will set Photo Viewer as the default app for that image format.

![File Explorer Choose Another App Menu Showing Windows Photo Viewer App Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/file-explorer-choose-another-app-menu-showing-windows-photo-viewer-app-option.png)

## How to Disable Windows Photo Viewer in Windows 10 and 11

 To disable Windows Photo Viewer, you must undo the changes you made earlier to the Windows Registry. It's worth making a backup again before making the changes. Then:

1. Press **Win + R** to open the **Run** dialog. Input **notepad** and click **OK**.
2. Copy and paste the following script into the notepad file:  
`Windows Registry Editor Version 5.00[-HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll]`  
![Notepad App Showing a Registry Script to Disable Windows Photo Viewer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-registry-script-to-disable-windows-photo-viewer-in-windows-11.png)
3. Press **Ctrl + Shift + S** to open the **Save** dialog.
4. Type **DeactivateWindowsPhotoViewer.reg** as the file name. Click the **Save as type** drop-down, choose **All files (\*.\*)**, then click **Save**.  
![Notepad App Showing a Save As Dialog to Disable Windows Photo Viewer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-save-as-dialog-to-disable-windows-photo-viewer-in-windows-11.png)
5. Double-click **DeactivateWindowsPhotoViewer.reg** to execute the script and follow the on-screen instructions.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jjGL9wFdlbo?si=Vb1JgZqRXNc03UGG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once done, [restart Windows Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/), and the Photo Viewer app will be disabled.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Use One Photo Viewer

![One Photo Viewer App Showing Right-Click Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/one-photo-viewer-app-showing-right-click-context-menu.png)

 One Photo Viewer is an excellent Windows Photo Viewer and [Windows Photos alternative](https://www.makeuseof.com/best-windows-10-photos-app-alternatives/). It's fast, free, and offers a clean interface by placing all the controls in the context menu, decluttering the toolbar area. Right-click the app interface to view the menu and access all the tools and settings.

 One Photo Viewer offers all the bells and whistles you expect of an image viewer, plus more. You can scroll through the images using the arrow keys or the dedicated buttons, zoom in and out, rotate, crop, resize, or adjust colors.

 It also supports RAW formats, including HEIC and WEBP animation, a slideshow from a folder or loaded images, custom keyboard shortcuts, and a color correction tool to make quick enhancements. You can also opt for the $3 Pro version to get two additional features: a toolbar for improved functionality and thumbnails for easier navigation.

**Download:** [One Photo Viewer](https://apps.microsoft.com/detail/9PM6W4F0XW3H) (Free, premium version available)

 That said, if you prefer to stick with a native option, give the built-in Windows Photos app another shot. It's not as bad as you may think upon first use.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/new-comparative-analysis-of-best-win-driven-art-tools/"><u>[New] Comparative Analysis of Best Win-Driven Art Tools</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-samsung-image-maker-insights-and-overview-2023/"><u>[New] In 2024, Samsung Image Maker Insights & Overview 2023</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-advanced-filmmaking-techniques-selecting-top-notch-lenses/"><u>[Updated] 2024 Approved Advanced Filmmaking Techniques Selecting Top-Notch Lenses</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-cut-to-the-chase-techniques-for-tightening-youtube-content/"><u>[Updated] Cut to the Chase Techniques for Tightening YouTube Content</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-elevating-business-and-personal-visibility-with-youtube-mobile-edition/"><u>[Updated] In 2024, Elevating Business & Personal Visibility with YouTube, Mobile Edition</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-youtube-seo-guide-how-to-improve-youtube-videos-rankings/"><u>2024 Approved YouTube SEO Guide How to Improve YouTube Videos Rankings</u></a></li>
<li><a href="https://some-guidance.techidaily.com/download-movavi-video-converter-gratis-affidabile-completa-and-senza-costi/"><u>Download Movavi Video Converter Gratis - Affidabile, Completa & Senza Costi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-clear-audio-feedback-in-windows-screen-casts/"><u>Ensuring Clear Audio Feedback in Windows Screen Casts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-stuck-window-settings-saver-recovery-steps/"><u>Fixing Stuck Window Settings: Saver Recovery Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstarting-the-explorer-a-guide-for-windows-11-users/"><u>Jumpstarting the Explorer: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-corrections-for-failing-windows-batch-jobs/"><u>Mastering Corrections for Failing Windows Batch Jobs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-fixes-for-windows-update-error-0x800f0845/"><u>Mastering Fixes for Windows Update Error 0X800f0845</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quell-the-cpu-throttle-a-guide-to-system-health-via-rm/"><u>Quell the CPU Throttle: A Guide to System Health via RM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-windows-scheduler-glitches-now/"><u>Resolve Windows Scheduler Glitches Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-the-start-menu-initiate-file-explorer-via-onedrive-shortcuts/"><u>Tailoring the Start Menu: Initiate File Explorer via OneDrive Shortcuts</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-from-tecno-camon-30-pro-5g-frp-bypass-by-drfone-android/"><u>Ultimate Guide from Tecno Camon 30 Pro 5G FRP Bypass</u></a></li>
<li><a href="https://techtrends.techidaily.com/windowsdvd/"><u>Windows上のDVDインポート: 使いやすさが高められたベストツールリスト</u></a></li>
</ul></div>

