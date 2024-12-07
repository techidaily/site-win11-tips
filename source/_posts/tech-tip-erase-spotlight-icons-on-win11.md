---
title: "Tech Tip: Erase Spotlight Icons on Win11"
date: 2024-12-05T16:28:03.608Z
updated: 2024-12-06T17:45:33.281Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tech Tip: Erase Spotlight Icons on Win11"
excerpt: "This Article Describes Tech Tip: Erase Spotlight Icons on Win11"
keywords: Win11 Icon Removal,Spotlight Clearance WS,Tech Guide Remove Eye,Delete Spotlight Windows,Erase Search Icons PC,Win11 Spotlight Hide Tip,Cleaning Up Spotlight WS
thumbnail: https://thmb.techidaily.com/9b6869e231e2667ce5b62099e4b236daaa6b93b4b1b8e67663aad45fe3a9f4b0.png
---

## Tech Tip: Erase Spotlight Icons on Win11

 Spotlight is a feature that adds different Bing images to Windows 11’s desktop background when enabled. That feature also adds a "Learn about this picture" icon to the desktop you can double-click to bring up image info. Right-clicking that icon brings up a context menu that includes a **Switch to next picture** option.

 The context menu doesn’t currently have an option for deleting the "Learn about this picture" icon. Maybe Microsoft might add such an option in a future version of Windows 11\. However, you can remove the Spotlight wallpaper icon from the desktop without a delete option with the methods below.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Remove the Spotlight Desktop Icon With a Manual Registry Tweak

 A relatively simple registry tweak is required to remove the "Learn about this picture" icon from the Windows Spotlight wallpaper. These are the steps for removing the Spotlight desktop icon by manually tweaking the registry:

1. Launch Run by right-clicking **Start** (the taskbar icon) and selecting **Run**.
2. Enter **regedit** inside Run’s **Open** command box and select **OK** to [access the Registry Editor app](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Next, go to this **NewStartPanel** key by inputting its path in the registry address bar:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel`
4. Right-click **NewStartPanel** and select **New** to view a submenu with options for adding new registry entries.  
![The New DWORD (32-bit) Value option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-new-dword-option.jpg)
5. Click **DWORD (32-bit) Value** on the submenu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Copy **{2cc5ca98-6485-489a-920e-b3e88a6ccce3}** to your clipboard by selecting the text and pressing **Ctrl** \+ **C**. Then press **Ctrl** \+ **V** to paste that into the DWORD’s name text box.
2. Double-click the **{2cc5ca98-6485-489a-920e-b3e88a6ccce3}** DWORD you just added.
3. Delete **0** in the **Value data** box.
4. Input **1** in the **Value data** box and click **OK**.  
![The NewStartPanel key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-dword-window.jpg)
5. Click Registry Editor’s **X** window button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Right-click any empty part of the desktop and select **Refresh**. The "Learn about this picture icon" will no longer be on the desktop.

 If you ever want to restore that Spotlight icon, you can do so by changing the value of the {**2cc5ca98-6485-489a-920e-b3e88a6ccce3}** DWORD you added to the registry. Double-click **{2cc5ca98-6485-489a-920e-b3e88a6ccce3}** in the **NewStartPanel** key to input **0** in that DWORD’s **Value data** box. Refreshing the desktop will then restore the "Learn about this picture" icon.

![The Learn about this picture desktop icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-learn-about-this-picture-icon.jpg)

## How to Remove the Spotlight Desktop Icon With Winaero Tweaker

 The manual registry tweaking required for removing the "Learn about this picture" icon is relatively straightforward. However, you can remove the Spotlight desktop icon with Winaero Tweaker if you still prefer not to fiddle with the registry.

 At any rate, Winaero Tweaker is a fantastic piece of Windows customization software that’s worth installing. You can remove the Spotlight desktop icon with Winaero Tweaker like this:

1. Go to this [Winaero Tweaker download page](https://winaero.com/download-winaero-tweaker/) and click the download link there.
2. Extract the Winaero Tweaker ZIP and install the software with its setup file. Our guide to [customizing Windows with Winaero Tweaker](https://www.makeuseof.com/windows-11-winaero-tweaker-guide/) includes step-by-step installation instructions for that software.
3. Next, double-click the **Windows 11** category within Winaero Tweaker’s sidebar.  
![The Windows 11 category](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-11-category.jpg)
4. Click **Remove Windows Spotlight** icon from the desktop.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PKZUYice-ws?si=L8iMa9T3h7TMSWdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Select the **Remove Windows Spotlight icon from Desktop** checkbox.  
![The Remove Windows Spotlight Icon from Desktop option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-remove-windows-spotlight-icon.jpg)

 Now the "Learn about this picture" icon will no longer be there. It’s easy to restore that icon with Winaero Tweaker if you ever want to utilize its Spotlight options again. Uncheck the **Remove Windows Spotlight icon from Desktop** checkbox in Winaero Tweaker to bring it back.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get Rid of the "Learn About This Picture" Icon on Windows 11

 The "Learn about this picture" icon only adds extra Windows 11 desktop clutter for users who never utilize its options. If you don’t want that additional Spotlight icon on your Windows 11 desktop, it’s straightforward to remove it with a manual registry tweak or Winaero Tweaker.

 The ExplorerPatcher software also includes an option for disabling that icon, along with other settings for making Windows 11 look like Windows 10\.

 The context menu doesn’t currently have an option for deleting the "Learn about this picture" icon. Maybe Microsoft might add such an option in a future version of Windows 11\. However, you can remove the Spotlight wallpaper icon from the desktop without a delete option with the methods below.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-lessons.techidaily.com/new-crafting-cinematic-experiences-with-magix-video-pro-x/"><u>[New] Crafting Cinematic Experiences with Magix Video Pro X</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-no-cash-to-youtube-wealth-unlocking-earnings-at-the-500-subs-level/"><u>[New] In 2024, From No Cash to YouTube Wealth Unlocking Earnings at the 500 Subs Level</u></a></li>
<li><a href="https://youtube-data.techidaily.com/into-the-art-of-asmr-recording-a-comprehensive-overview-for-2024/"><u>Dive Into the Art of ASMR Recording – A Comprehensive Overview for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-fixes-for-windows-10-and-11s-isdonedll-error/"><u>Effective Fixes for Windows 10 & 11'S ISDone.dll Error</u></a></li>
<li><a href="https://vp-tips.techidaily.com/freihand-kopieren-von-dvd-dateien-auf-einen-usb-stick-schritt-fur-schritt-anleitung/"><u>Freihand Kopieren Von DVD Dateien Auf Einen USB Stick - Schritt-Für-Schritt Anleitung</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-perfecting-motion-capture-a-guide-to-gopro-time-lapse-photos/"><u>In 2024, Perfecting Motion Capture A Guide to GoPro Time Lapse Photos</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-the-art-of-designing-smaller-images-thumbnails-explained/"><u>In 2024, The Art of Designing Smaller Images Thumbnails Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimal-movement-quick-windows-11-cessation/"><u>Minimal Movement: Quick Windows 11 Cessation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-browser-overcoming-high-cpu-use-on-google-chrome/"><u>Optimize Your Browser: Overcoming High CPU Use on Google Chrome</u></a></li>
<li><a href="https://app-tips.techidaily.com/recover-your-missed-texts-and-voicemails-tips-for-retrieving-accidentally-erased-data-on-itunes/"><u>Recover Your Missed Texts and Voicemails: Tips for Retrieving Accidentally Erased Data on iTunes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steering-past-the-storm-resolving-stranded-xbox-on-windows-11/"><u>Steering Past the Storm: Resolving Stranded Xbox on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-resolving-failed-jvm-creation-in-windows/"><u>Techniques for Resolving Failed JVM Creation in WINDOWS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tutorial-setting-windows-calculator-to-dark-mode/"><u>Tutorial: Setting Windows Calculator to Dark Mode</u></a></li>
<li><a href="https://article-helps.techidaily.com/unlock-full-screen-flexibility-with-pip-feature-on-iphones-for-2024/"><u>Unlock Full Screen Flexibility with PIP Feature on iPhones for 2024</u></a></li>
</ul></div>

