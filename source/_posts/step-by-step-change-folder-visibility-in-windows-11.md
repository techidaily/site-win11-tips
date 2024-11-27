---
title: "Step-by-Step: Change Folder Visibility in Windows 11"
date: 2024-11-22T17:19:03.019Z
updated: 2024-11-27T17:08:25.568Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step: Change Folder Visibility in Windows 11"
excerpt: "This Article Describes Step-by-Step: Change Folder Visibility in Windows 11"
keywords: Windows 11 Folder Privacy,Hidden Files View,Windows Settings Guide,File Visibility Control,Enable/Disable Folders,Changing Icon Visibility,Customizing Folder Display
thumbnail: https://thmb.techidaily.com/965654acbd64cd762e18be6423e980e53d1c3fa7dd1512b5cfdc18b0e2b93a57.jpg
---

## Step-by-Step: Change Folder Visibility in Windows 11

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-zero.techidaily.com/iewership-victors-the-worlds-top-10-video-content-makers-for-2024/"><u>[New] Viewership Victors The World's Top 10 Video Content Makers for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-dive-into-design-get-a-complimentary-set-of-50-banner-pieces/"><u>[Updated] 2024 Approved Dive Into Design Get a Complimentary Set of 50 Banner Pieces</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-renowned-crafters-exquisite-instagram-hlv-designers-online/"><u>[Updated] Renowned Crafters Exquisite Instagram HLV Designers Online</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-toggle-between-normal-and-pip-views-for-youtube-app-on-ios/"><u>[Updated] Toggle Between Normal and PIP Views for Youtube App on iOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-a-windows-trash-bin-for-irreversible-file-disposal-11/"><u>Configuring a Windows Trash Bin for Irreversible File Disposal (11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-failing-copy-functionality-in-windows-11/"><u>Correcting Failing Copy Functionality in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-your-ideal-theme-landscape-in-windows-11/"><u>Creating Your Ideal Theme Landscape in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-mp3-conversion-producing-high-quality-audio-cds-via-imgburn-on-pc/"><u>Easy Mp3 Conversion: Producing High-Quality Audio CDs via ImgBurn on PC</u></a></li>
<li><a href="https://hardware-help.techidaily.com/global-tech-showdown-loongsons-newest-16-core-chip-echos-performance-of-intel-ice-lake-and-xeon-silver/"><u>Global Tech Showdown: Loongson's Newest 16-Core Chip Echos Performance of Intel Ice Lake and Xeon Silver</u></a></li>
<li><a href="https://fox-info.techidaily.com/horizon-haven-the-leading-5-cloud-platforms-to-consider/"><u>Horizon Haven The Leading 5 Cloud Platforms to Consider</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-easy-ways-to-copy-contacts-from-honor-magic-6-pro-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Easy Ways to Copy Contacts from Honor Magic 6 Pro to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-exploring-luts-for-sophisticated-photographic-changes/"><u>In 2024, Exploring LUTs for Sophisticated Photographic Changes</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-oppo-reno-10-pro-5g-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Oppo Reno 10 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-get-and-use-pokemon-go-promo-codes-on-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Get and Use Pokemon Go Promo Codes On Xiaomi Redmi Note 12 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/library-installation/"><u>Library Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-specific-app-failures-in-windows-os/"><u>Overcoming Device-Specific App Failures in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/permanent-file-disposal-guide-for-windows-11-desk-bin/"><u>Permanent File Disposal Guide for Windows 11 Desk Bin</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-yuzu-emulation-in-windows-os/"><u>Streamlining Yuzu Emulation in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-top-tier-classic-gaming-in-hd-clarity-windows-plus-scummvm-techniques/"><u>Tips for Top-Tier Classic Gaming in HD Clarity: Windows + ScummVM Techniques</u></a></li>
</ul></div>

