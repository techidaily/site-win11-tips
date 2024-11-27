---
title: Simplified Methodology for Placing App Shortcuts in Windows 11
date: 2024-11-21T17:10:36.946Z
updated: 2024-11-27T17:32:20.564Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Simplified Methodology for Placing App Shortcuts in Windows 11
excerpt: This Article Describes Simplified Methodology for Placing App Shortcuts in Windows 11
keywords: Shortcut Placement Guide,Win11 App Shortcuts,Easy Shortcut Installation,Windows Shortcut Methodology,Optimize Win11 Hotkeys,Placing Shortcuts in Windows 11,Simplified Shortcut Configuration
thumbnail: https://thmb.techidaily.com/130efd155dd3113027502bebb58cb6e6e0e86e94cc569dcea85fd93839ec481a.jpg
---

## Simplified Methodology for Placing App Shortcuts in Windows 11

 Context menus are the backbone of Windows—they're the little menus you see when you right-click the mouse on something. And while Windows 11 has brought in a new context menu for your desktop, there still aren’t any native customization options for it. For example, Windows 11 doesn’t include any built-in setting that enables you to add custom software shortcuts to that menu.

 Nevertheless, you can still add program shortcuts to the desktop context menu in Windows 11 by editing the registry. By doing so, you can replace desktop shortcut icons with context menu ones.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Add an Edge Shortcut to the Desktop Context Menu

 As [Microsoft Edge is the default browser](https://www.makeuseof.com/how-windows-11-may-soon-force-you-to-use-microsoft-edge/) included with Windows 11, that's a software package you’ll all have to set up a context menu shortcut for. So, we’ll add an Edge shortcut to the desktop context menu for the sake of an example. This is how you can add a shortcut for that browser to the desktop context menu with a [simple tweak to the Windows registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/):

1. First, right-click the **Start** button on the taskbar and select **Run**.
2. Enter **regedit** in the Open box within Run’s window.
3. Click **OK** to [launch the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
4. Then navigate to the **Computer > HKEY\_CLASSES\_ROOT > Directory > Background > shell** registry key path.  
![The Shell registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-shell-key.png)
5. Right-click the **shell** key to select **New** and **Key** on the context menu.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Key context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-key-option.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Input **Edge** as the new registry key’s title.
2. Right-click your **Edge** key and select the **New** \> **Key** options again.
3. Enter **command** to be the new subkey’s name.  
![The command registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-command-key.png)
4. Click File Explorer’s taskbar button.
5. Open Edge’s folder, which has this default path: **C:\\Program Files (x86)\\Microsoft\\Edge\\Application**.

1. Right-click msedge.exe there to select the **Copy as** **path** option shown directly below.  
![The Copy as path option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/copy-as-path-option.png)
2. Then return to the Registry Editor, and select the new **command** key you added.
3. Double-click **(Default)** for the **command** key on the right side of the window.
4. Press the **Ctrl** \+ **V** hotkey to paste the copied Edge path within the Value data box.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-edit-string-window.png)
5. Click **OK** to confirm.

 Now you can try out your new Edge context menu shortcut. Right-click the desktop and select **Show more options** to view the classic menu. Then select **Edge** there to open that browser.

![A Microsoft Edge context menu shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/edge-context-menu-shortcut.png)

 If you prefer, you can bring up the classic context menu in Windows 11 with a handy keyboard shortcut. Press the **Shift + F10** hotkey to open the menu instead. Then select your software shortcuts from there.

## How to Add Your Own Shortcuts to the Windows 11 Context Menu

 You can add a shortcut for whatever software you'd like in a similar way to adding Edge. To do this, you need to change the name of the primary registry key to match the name of the software it’s for. Then, open the program’s folder in File Explorer to copy its full path, and paste it in the Value data box for the command subkey’s **(Default)** string.

 To remove one of your software context menu shortcuts, you’ll need to open the key for it in the Registry Editor. Then right-click its primary key to select a **Delete** option. Select **Yes** to confirm and erase.

![The delete context menu option for registry keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-delete-option.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This registry tweak also works much the same in Windows 10 and earlier Microsoft desktop platforms. So, this isn’t just a Windows 11 trick. As Windows 10 has a classic context menu by default, you don’t need to click **Show more options** on that menu to select the shortcut.

## How to Add Program Shortcuts to the Context Menu With Easy Context Menu

 If you prefer not to manually edit the registry, add program shortcuts to the desktop’s context menu with Easy Context Menu. Easy Context Menu is a freeware third-party app for customizing context menus in Windows 11/10\. It enables you to add and remove shortcuts to and from the context menu. This is how you can add shortcuts for opening programs to Windows 11’s context menu with that software:

1. Open this [Easy Context Menu page](https://www.sordum.org/7615/easy-context-menu-v1-6/) in a web browser and download the app.
2. Extract the **ec\_menu** ZIP archive with a method in this article about [unzipping ZIP files in Windows 11](https://www.makeuseof.com/how-to-extract-zip-files-windows-11/).
3. Open the extracted **ec\_menu** folder and double-click the **EcMenu\_x64** file to open Easy Context Menu.
4. Click the **List Editor** button.  
![The List Editor button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/list-editor-button.jpg)
5. Press the **Add new** button.

1. Select the application (EXE) file for a program to add to the context menu and click **Open**.
2. Next, select **Desktop Context Menu** on the **Target Context Menu** drop-down menu for the shortcut.  
![The Target Context Menu drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/target-context-menu-drop-down-menu.jpg)
3. Click the **Show at bottom of the menu** radio button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jjGL9wFdlbo?si=Vb1JgZqRXNc03UGG&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Press the **Save changes** button.
5. Select the checkbox for the program shortcut in the Easy Context Menu window.
6. Click the **Apply Changes** button on the Easy Context Menu window.  
![The Apply Changes button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/apply-changes-button.jpg)

 Now you’ve added a new program shortcut to the classic context menu in Windows 11\. Bring up the classic context menu by right-clicking anywhere on the desktop and selecting **Show more options**. Then select the new software shortcut, which will be somewhere near the bottom of the classic menu.

 You can remove that shortcut and other options from the right-click menu with Easy Context Menu. To do so, click the **ContextMenu Cleaner** button; deselect the checkbox for the software shortcut to disable it on the context menu (you can still restore it later). Then click **Refresh** to save the context menu changes.

![The ContextMenu Cleaner window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/contextmenu-cleaner-tool.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 There’s also much more you can add to the desktop’s right-click menu with Easy Context Menu than software shortcuts. Easy Context Menu includes many other checkboxes for adding various tools and turn-off options to the right-click menu. Select some of the checkboxes for system tools and turn-off options, and click **Apply Changes** to add handy shortcuts for accessing utilities and shutting down Windows to the context menu.

## Make the Most Out of Windows 11’s Context Menu

 Now you can add program shortcuts to the context menu instead of flooding your desktop wallpaper or taskbar with them. That’s a great alternative place to add shortcuts because they don’t clutter your desktop. Keep your Windows 11 desktop clean and tidy by adding more shortcuts to the context menu instead.

 Nevertheless, you can still add program shortcuts to the desktop context menu in Windows 11 by editing the registry. By doing so, you can replace desktop shortcut icons with context menu ones.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-blog.techidaily.com/n-2024-channel-title-genius-ideas-for-your-video-hub/"><u>[New] In 2024, Channel Title Genius Ideas for Your Video Hub</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-how-to-record-gameplay-on-windows-10/"><u>[Updated] 2024 Approved How to Record Gameplay on Windows 10</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-no-cost-memes-made-simple-our-meme-kit/"><u>[Updated] No-Cost Memes Made Simple Our Meme Kit</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-pretending-playfulness-making-mocks-and-laughs-for-2024/"><u>[Updated] Pretending Playfulness Making Mocks and Laughs for 2024</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/95955303-9780008302016-aquarius-2019-your-personal-horoscope/"><u>Aquarius 2019: Your Personal Horoscope | Free Book</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-email-readability-pinning-gmail-bar-on-pc/"><u>Boosting Email Readability: Pinning Gmail Bar on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/como-utilizar-capcut-no-pc-guia-passo-a-passo-para-download-e-uso/"><u>Como Utilizar CapCut No Pc - Guia Passo a Passo Para Download E Uso</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conversion-facile-de-fichiers-mxf-en-avi-en-ligne-gratuit-utilisez-la-solution-de-movavi-pour-obtenir-les-meilleurs-resultats/"><u>Conversion Facile De Fichiers MXF en AVI en Ligne Gratuit : Utilisez La Solution De Movavi Pour Obtenir Les Meilleurs Résultats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-converter-from-wma-to-swf-movavi-media-editor/"><u>Free Online Converter From WMA to SWF - Movavi Media Editor</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-ensure-your-acer-aspire-works-perfectly-windows-driver-downloads-explained/"><u>How to Ensure Your Acer Aspire Works Perfectly: Windows Driver Downloads Explained</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-fix-apple-iphone-6s-plus-unavailable-issue-with-ease-by-drfone-ios/"><u>In 2024, How To Fix Apple iPhone 6s Plus Unavailable Issue With Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inventer-des-techniques-pour-retourner-une-sequence-video/"><u>Inventer Des Techniques Pour Retourner Une Sequence Video</u></a></li>
<li><a href="https://howto.techidaily.com/spotify-keeps-crashing-a-complete-list-of-fixes-you-can-use-on-oppo-find-x7-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Spotify Keeps Crashing A Complete List of Fixes You Can Use on Oppo Find X7 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformar-videos-de-wtv-a-formato-avi-online-sin-coste-haga-lo-suyo-con-convertidor-de-movavi/"><u>Transformar Vídeos De WTV a Formato AVI Online Sin Coste - Haga Lo Suyo Con Convertidor De Movavi</u></a></li>
</ul></div>

