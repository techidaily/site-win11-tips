---
title: Learn to Manage Your Directories in Windows Explorer, Version 11
date: 2024-11-20T17:57:28.446Z
updated: 2024-11-27T17:51:45.321Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Learn to Manage Your Directories in Windows Explorer, Version 11
excerpt: This Article Describes Learn to Manage Your Directories in Windows Explorer, Version 11
keywords: Windows Explorer Directory Management,Learning Directory Navigation,Explore Windows Directories,Navigate Windows 11 Folders,Mastering Windows Explorer,Organize Files in Windows,Directories in Windows OS
thumbnail: https://thmb.techidaily.com/ce1836626dd4307cd42ffb8054ede87619858d1bf1634f1f32732c80e0c8c7aa.jpg
---

## Learn to Manage Your Directories in Windows Explorer, Version 11

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 Before you proceed, we highly recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to familiarize yourself with what we will be doing next. Also important is knowing [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). Considering this is the database that Windows stores the data it needs to operate properly, you will need this backup in case you make an error.

 For showing and hiding folders in This PC to work, make sure you’re running the latest version of Windows 11\. You'll know you have it if File Explorer has tabs.

 With the Registry Editor open, let's get to it.

## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)

 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f3PFn06LijE?si=zHrmlTOzrKxXe-k4&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, refresh File Explorer with **F5** and the **Documents** folder will appear in This PC.

 To hide it, right-click the key on the left panel and select **New > DWORD (32-bit) Value** and name it **HideIfEnabled**. Double-click the newly-created value in the right panel, set **Value data** to **22ab9b9**, and then click **OK**.

![set-hideifenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-hideifenabled.jpg)

 Now when you refresh This PC in File Explorer, you will see that the **Documents** folder is gone.

 The steps to show or hide the other folders from this point on are the same. Just go to the respective key in the Registry Editor and either delete the **HideIfEnabled** value to show the folder in this PC or create the value and set it to **22ab9b9** to hide the folder.

 Here’s the path to the **Music** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{3dfdf296-dbec-4fb4-81d1-6a3438bcf4de}

 Here’s the path to the **Video** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{f86fa3ab-70d2-4fc7-9c99-fcbf05467f3a}

 Here’s the path to the **Pictures** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{24ad3ad4-a569-4530-98e1-ab02f9417aa8}

 Here’s the path to the **Downloads** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{088e3905-0323-4b02-9826-5d99428e115f}

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Choose the Folders You Want to Appear on This PC in Windows 11

 If you want to see folders on This PC, you can do so by making a couple of edits to the Windows Registry. While we do recommend that you know what you’re doing if you proceed, we have made the instructions relatively simple to follow so there's minimal chance of messing up the registry.

 As long as you take the necessary steps not to mess up the Windows Registry, you should be able to hide and show the folders you want easily.

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
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-starry-secrets-a-guide-to-capturing-the-perfect-night-portraits/"><u>[New] In 2024, Starry Secrets A Guide to Capturing the Perfect Night Portraits</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-a-filmmakers-approach-to-youtube-splitscreen-videos/"><u>[Updated] In 2024, A Filmmaker's Approach to YouTube Splitscreen Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cr2-image-to-jpg-a-step-by-step-windows-tutorial/"><u>Cr2 Image to JPG: A Step-by-Step Windows Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-addressing-windows-error-0x80040610-in-outlook/"><u>Expert Tips for Addressing Windows Error 0X80040610 in Outlook</u></a></li>
<li><a href="https://win-solutions.techidaily.com/guide-addressing-and-fixing-the-detected-audio-configuration-problem-in-itunes/"><u>Guide: Addressing and Fixing the Detected Audio Configuration Problem in iTunes</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-cost-effective-recorder-selections-for-youtube-vloggers/"><u>In 2024, Cost-Effective Recorder Selections for YouTube Vloggers</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-pioneering-free-convertors-top-5-online-apps-for-gifs-to-videos/"><u>In 2024, Pioneering Free Convertors Top 5 Online Apps for GIFs to Videos</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/inside-toms-gearbox-unveiling-the-secrets-of-pc-building-and-maintenance/"><u>Inside Tom's Gearbox: Unveiling the Secrets of PC Building and Maintenance</u></a></li>
<li><a href="https://extra-hints.techidaily.com/lightning-flicker-viewer-windows-photos/"><u>Lightning Flicker Viewer - Windows Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-minecraft-wi-fi-gaming-hurdles-on-pc/"><u>Navigating Minecraft Wi-Fi Gaming Hurdles on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-how-to-swiftly-toggle-fn-key-on-windows/"><u>Quick Fix: How to Swiftly Toggle Fn Key on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-outlook-crash-steps-for-windows-users/"><u>Solving Outlook Crash: Steps for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-configuring-windows-hello/"><u>The Essential Guide to Configuring Windows Hello</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-itel-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Itel Phones</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/trasforma-i-tuoi-file-mp4-in-formato-aac-gratuitamente-online-con-moveave-convertitore-audio/"><u>Trasforma I Tuoi File MP4 in Formato AAC Gratuitamente Online Con Moveave | Convertitore Audio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unearthing-windows-11s-inner-workings-its-registry-details/"><u>Unearthing Windows 11’S Inner Workings: Its Registry Details</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-activating-audio-mixing-via-action-center/"><u>Windows 11: Activating Audio Mixing via Action Center</u></a></li>
</ul></div>

