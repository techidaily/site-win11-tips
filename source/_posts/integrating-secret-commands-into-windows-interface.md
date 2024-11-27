---
title: Integrating Secret Commands Into Windows Interface
date: 2024-11-26T17:12:05.288Z
updated: 2024-11-27T16:21:34.901Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Integrating Secret Commands Into Windows Interface
excerpt: This Article Describes Integrating Secret Commands Into Windows Interface
keywords: Windows Command Integration,Hidden Commands UI,Secrets in Windows,Enhanced Window Scripts,Windows CLI Tweaks,Stealth System Commands,Windows Interface Updates
thumbnail: https://thmb.techidaily.com/e4a8d7447e854c2de99b048e14a9c3d2b9315b35b4cc07b6ffa3d376da485f27.jpg
---

## Integrating Secret Commands Into Windows Interface

 File Explorer has a Hidden items option you can select to reveal hidden files and folders. Those are mainly important system files and folders hidden for good reason. However, you can also select to hide user files as well.

 Explorer’s **View** menu and tab (in Windows 10) include the **Hidden items** option. However, you can make that option a little more accessible by adding it to the context menu. Then you can toggle hidden files on/off from the right-click menu. This is how you can add a **Hidden items** option to the context menu in Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Add a Hidden Items Option to the Context Menu With a Registry Script

 To add any new option to a Windows context menu, we must modify the registry. Adding a **Hidden items** option to the context menu involves a slightly more complicated registry tweak. So, it’s best to add such an option to the right-click menu with a more automated registry script method like this:

1. Open this [Winaero download page](https://winaero.com/download-toggle-hidden-items-context-menu-in-windows-10-regsitry-tweak/) in web-browsing software.
2. Then select **Click here to download the file** option for the registry script archive.
3. Press both the **Windows** logo and **E** keyboard keys at the same time to [access File Explorer](https://www.makeuseof.com/windows-open-file-explorer/).
4. Navigate to whatever folder the **hidden\_files\_context\_menu** ZIP downloaded in.
5. Unzip (extract) the **hidden\_files\_context\_menu** ZIP file. We have a guide that includes instructions for [unzipping ZIP archives in Windows](https://www.makeuseof.com/unzip-files-windows-10/).  
![The Extract Compressed (Zipped) Folder tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/extraction-utility.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KdpTAZ9zonQ?si=5Nd5SPW1axA7GPuB&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Open the extracted hidden\_files\_context\_menu folder.
2. Double-click the **Add hidden files** **context menu** command registry script file.  
![The registry script's folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/registry-script-folder.jpg)
3. Select **Yes** if a User Account Control prompt pops up.
4. Click **Yes** within the Registry Editor dialog box that asks if you’re sure about continuing.  
![The Registry Editor confirmation prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/registry-script-confirmation-prompt.jpg)
5. Select **OK** on the second dialog box that appears.

 Now bring up the root C: directory in File Explorer to try out the new **Hidden items** context menu option. Right-click anywhere inside that folder to select **Show more options** on Windows 11’s context menu and **Hidden items**. Selecting that option will reveal a few hidden folders in the root directory if that setting isn’t enabled already. Click the same option again to hide the folder and files again.

![The Hidden items option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hidden-items.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The **hidden\_files\_context\_menu** ZIP archive also includes another registry script for removing the context menu. So, you don’t need to manually edit the registry to remove the **Hidden items** context menu. Running the **Undo hidden files in context menu** script will do the job for you.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Add a Hidden Items Option to the Context Menu With Right-Click Extender

 Or you can add options for toggling file visibility to the context menu with Right-Click Extender. Right-Click Extender is a freely available app that includes numerous customization settings for adding new options to the context menus in Windows 11/10\. This is how to add context menu options for showing/hiding hidden files and folders with Right-Click Extender:

1. Go to this [Right-Click Extender](https://www.softpedia.com/get/Tweak/System-Tweak/Right-Click-Extender.shtml) Softpedia download page.
2. Press the **Download** button there to view location options.
3. Click on **Secure Download (US)**, which is the best option for users in North America.
4. Open the folder where your browser downloads the Right-Click Extender ZIP file to within File Explorer.
5. Unzip the Right-Click Extender ZIP archive.
6. Open Right-Click Extender’s extracted directory and double-click on the Right-Click Extender v2 subfolder.
7. Double-click the **Right-Click Extender** file to open that app’s window.
8. Click the **File**/**Folder** tab in Right-Click Extender.  
![toggle-items-checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/toggle-items-checkbox.jpg)
9. Select the **Toggle File**/**Folder Visibility** option along with its Icon checkbox.
10. Click on the **Apply** button.

 Now bring up the classic context menu within a folder in File Explorer by pressing **Shift** \+ **F10**. There you’ll see a new **Toggle File Visibility** submenu. Move your cursor over the **Toggle File Visibility** submenu to select a **Show Hidden Files** option. You can conceal the items again by selecting the opposite **Hide Hidden Files** option.

![The Toggle File Visibility submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/toggle-file-visibility-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Toggle Hidden Items On and Off From File Explorer’s Context Menu

 So, now you can select to show or hide files and folders from your context menu. If you select to show hidden items, you can see and access more folders and files in Windows. A context menu option for enabling/disabling hidden items can be especially useful for users who select to hide things with the attribute settings for files and folders.

 Explorer’s **View** menu and tab (in Windows 10) include the **Hidden items** option. However, you can make that option a little more accessible by adding it to the context menu. Then you can toggle hidden files on/off from the right-click menu. This is how you can add a **Hidden items** option to the context menu in Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-files.techidaily.com/new-comic-crafting-on-apple-devices-for-2024/"><u>[New] Comic Crafting on Apple Devices for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-the-essential-guide-from-twitter-videos-to-high-quality-mp3-soundtracks-for-2024/"><u>[New] The Essential Guide From Twitter Videos to High-Quality MP3 Soundtracks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-cut-cinematic-9-ways-to-ensure-smooth-videos-on-windows-os/"><u>Clear Cut Cinematic: 9 Ways to Ensure Smooth Videos on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-hidden-storage-a-windows-adventure/"><u>Discovering Hidden Storage: A Windows Adventure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fine-tune-your-android-development-top-tips-for-windows-users/"><u>Fine-Tune Your Android Development: Top Tips for Windows Users</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-itel-a70-location-on-skout-drfone-by-drfone-virtual-android/"><u>How to Change Itel A70 Location on Skout | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-unleashing-screen-content-with-zdsofts-magic/"><u>In 2024, Unleashing Screen Content with ZDSoft's Magic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/investigating-the-consequences-of-device-isolation-in-windows/"><u>Investigating the Consequences of Device Isolation in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-map-integration-microsoft-meets-google/"><u>Master the Art of Map Integration: Microsoft Meets Google</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-guide-how-to-check-icloud-activation-lock-status-on-your-iphone-8-by-drfone-ios/"><u>New Guide How To Check iCloud Activation Lock Status On Your iPhone 8</u></a></li>
<li><a href="https://tech-haven.techidaily.com/proactive-design-strategies-using-chatgpt-for-user-personas/"><u>Proactive Design Strategies Using ChatGPT for User Personas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-tackle-malwarebytes-runtime-error-missed-calls/"><u>Strategies to Tackle Malwarebytes Runtime Error: Missed Calls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-blueprint-for-snaps-via-powertoys/"><u>The Ultimate Blueprint for Snaps via PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-applications-for-your-pc-switch-from-mac/"><u>The Ultimate Guide to Applications for Your PC Switch From Mac</u></a></li>
<li><a href="https://extra-information.techidaily.com/unlocking-xboxs-video-call-potential-with-zoom/"><u>Unlocking Xbox's Video Call Potential with Zoom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-1011-zoom-quality-addressing-code-1132-concerns/"><u>Win 10/11 Zoom Quality: Addressing Code 1132 Concerns</u></a></li>
<li><a href="https://video-capture.techidaily.com/windowswebm/"><u>Windows上での拡張性が高く完全に保たれるWebMビデオファイルの編集テクニック</u></a></li>
<li><a href="https://screen-recording.techidaily.com/zoom-webinar-basics-for-beginners-and-those-new-to-virtual-events-for-2024/"><u>Zoom Webinar Basics for Beginners & Those New to Virtual Events for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/1726030558663-vimeo/"><u>ダウンロード不可能なVimeo動画を解決する方法</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    