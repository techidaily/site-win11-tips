---
title: How to Fix the “We Couldn't Set Your Default Save Location” Error in Windows 11/10
date: 2025-01-14T17:20:34.496Z
updated: 2025-01-18T18:11:10.722Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the “We Couldn't Set Your Default Save Location” Error in Windows 11/10
excerpt: This Article Describes How to Fix the “We Couldn't Set Your Default Save Location” Error in Windows 11/10
keywords: Solve Save Location Error,Windows Save Issue Fix,Windows 11/10 Default Setting,Correct Windows Saving Error,Set Default Save Path Windows,Overcome File Save Failure,Fix Windows Save Location Message
thumbnail: https://thmb.techidaily.com/d7dc5f497c3ff92b83099053ccb7b434fc4fb16a570e502a336cc42130adb602.jpg
---

## How to Fix the “We Couldn't Set Your Default Save Location” Error in Windows 11/10

 Users have reported error 0x80070005 or 0x80070539 arises when they try to set new apps to save to different external drive locations with Settings. Those error codes have the same message that says, “We couldn’t set your default save location.” This means users can’t change the default save location for apps.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Set Your User Account to Administrator

 If you’re utilizing a standard Windows account, [change your user account type](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) to an administrative one. A standard user account will prevent you from applying any more complicated system changes. Changing the save location for apps is something you might need admin privileges for.

![The Account type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-account-type-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/58KlTPHv8dU?si=7ICagyNgrao7OkVO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Rename the WindowsApps Directory

 This error can arise because the WindowsApps folder where apps save is corrupted. Renaming the WindowsApps folder on the drive or partition you want to save apps can address such an issue. To do so, rename that folder as follows:

1. If you’re trying to set apps to save on an external drive, connect that hard drive to your PC.
2. [Open the File Explorer folder navigator](https://www.makeuseof.com/windows-open-file-explorer/) and click **This PC**.
3. Double-click the drive/partition you want to set as your default save location for apps.
4. Then, right-click on the WindowsApps folder and select its **Rename** context menu option. You should find that directory within the drive’s root directory.  
![The Rename option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-button.jpg)
5. Rename the folder to **WindowsApps.old** and press **Enter**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Thereafter, try changing the default save location for apps again via Settings.

 If that still doesn’t work, then proceed to the next resolution.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Delete or Rename the WpSystem Folder

 Many users confirm that renaming or deleting the WpSystem folder fixes error 0x80070005\. WpSystem is a folder created to store app data. Try renaming that folder to **WpSystem.old** on the drive you can’t set to be a save location for apps, as outlined for the previous method. The WpSystem will be in the same directory as the WindowsApps folder.

 Alternatively, delete the WpSystem folder. You can [erase a file or folder in Explorer](https://www.makeuseof.com/windows-11-delete-select-files/) by right-clicking it and selecting **Delete**. If you can’t find that folder or this potential solution doesn’t work, try the next resolution.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-option.jpg)

## 4\. Set Full System Permission for the System Volume Folder

 Setting full permission for the System Volume folder is another confirmed fix for error 0x80070005\. Follow these steps to set full permission for the System Volume directory:

1. Go into File Explorer and click the three-dot **See more** menu > **Options**. In Windows 10, click **Options** on the **View** tab.
2. Select **View** on the Folder Options window.
3. Deselect the **Hide protected operating system files (Recommended)** option.  
![The Hide protected operating system files checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-protected-operating-system-files.jpg)
4. Select the **Show hidden files, folders and drives** radio button.

5. Click **Apply** to save the new Explorer settings.

1. Select the drive you need to set as the default save location for apps.
2. Right-click the System Volume Information folder and select **Properties**.
3. Click **Security > Advanced** to bring up an Advanced Security Settings window.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-tab.jpg)
4. Press the **Continue** button.

5. Next, click **Add** to view a Permission Entry window.

1. Click the **Select a principal** option.
2. Input **SYSTEM** inside the object name box.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-group.jpg)
3. Click on the **OK** button.

4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oB9V7rZzotw?si=d4xrCbq1jKHXGAWN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Close all remaining open windows. Then, restart your PC and try changing the default save location.

## Set a New Default Save Location in Windows 11/10

 Many users have needed to fix error 0x80070005 and have done so by applying the potential solutions in this guide. The WpSystem folder is often the source of the error, and resolution two is the most widely confirmed method for fixing this issue.

 However, some users have also fixed the issue by applying the less widely cited fourth method.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-hd-mastery-in-action-top-5-screen-recorders-reviewed/"><u>[New] 2024 Approved HD Mastery in Action Top 5 Screen Recorders Reviewed</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-cooking-crusaders-youtube-stars-serving-up-deliciousness/"><u>[New] Cooking Crusaders YouTube Stars Serving Up Deliciousness</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-ultimate-voice-changer-for-valorant-gamers-free-to-use/"><u>[New] Ultimate Voice Changer for Valorant Gamers – Free to Use</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-eternal-void-a-complete-ban-on-youtube-short-video-feature-for-2024/"><u>[Updated] Eternal Void A Complete Ban on YouTube Short Video Feature for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-picture-by-picture-insta-gallery/"><u>[Updated] Picture by Picture Insta Gallery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/202362024/"><u>2023年度人気！動画画像分割手法ベストセレクション6つ（2024年版）</u></a></li>
<li><a href="https://facebook.techidaily.com/balancing-jokes-with-news-on-facebook/"><u>Balancing Jokes with News on Facebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/descargas-gratuitas-para-convertir-archivos-aiff-a-wma-sin-problemas-guia-de-movavi/"><u>Descargas Gratuitas Para Convertir Archivos AIFF a WMA Sin Problemas: Guía De Movavi</u></a></li>
<li><a href="https://extra-resources.techidaily.com/discovering-social-gaming-in-the-metaverse/"><u>Discovering Social Gaming in the Metaverse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-conversion-change-mp4-audio-files-to-flv-format-with-ease/"><u>Free Online Conversion: Change MP4 Audio Files to FLV Format with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-conversion-convert-3gp-files-to-mpeg-with-movavi/"><u>Free Online Conversion: Convert 3GP Files to MPEG with Movavi</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-se-2020-with-a-mask-on-by-drfone-ios/"><u>In 2024, How to Unlock iPhone SE (2020) with a Mask On</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726225145348-movavi-m4a/"><u>Movaviのお使いレコード: 弾かずにオンラインでM4Aファイルを変換してください</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mp4-a-aiff-trasformare-i-formati-di-file-audio-gratuitamente-con-mediahuman-converter/"><u>MP4 a AIFF: Trasformare I Formati Di File Audio Gratuitamente Con MediaHuman Converter</u></a></li>
<li><a href="https://extra-information.techidaily.com/streamlined-video-calls-synchronizing-zoom-and-gmail-for-better-communication/"><u>Streamlined Video Calls Synchronizing Zoom & Gmail for Better Communication</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-15-editors-headlines-of-2024-a-comprehensive-guide/"><u>Top 15 Editor's Headlines of 2024: A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformez-vos-chansons-mp3-en-format-wma-sans-frais-a-laide-du-service-de-convertisseur-en-ligne-de-movavi/"><u>Transformez Vos Chansons MP3 en Format WMA Sans Frais À L'aide Du Service De Convertisseur en Ligne De Movavi</u></a></li>
<li><a href="https://blog-min.techidaily.com/1726030252225-youtube/"><u>オンラインストリーミング動画の効率的なアーカイブ: YouTube ビデオ録画ガイド</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mkvavi/"><u>ダイナミックなオンライン動画フォーマット変更 - 今すぐMKVをAVIに自由に変換！</u></a></li>
</ul></div>

