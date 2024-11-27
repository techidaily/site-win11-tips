---
title: Guide to Remove OneDrive From Windows Explorer App
date: 2024-11-20T16:45:03.794Z
updated: 2024-11-27T16:41:08.645Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Remove OneDrive From Windows Explorer App
excerpt: This Article Describes Guide to Remove OneDrive From Windows Explorer App
keywords: Removing OneDrive Explorer,Unlink OneDrive Explorer,DropOneDrive Windows,Exclude OneDrive Folder,Disable OneDrive Explorer,Turn Off OneDrive Sync,Hide OneDrive Icon Windows
thumbnail: https://thmb.techidaily.com/6889b29c9a1ca37c06d96850359e16ed975462ec122694d578843a25c7f44c71.jpg
---

## Guide to Remove OneDrive From Windows Explorer App

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on[removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you[create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. When you open File Explorer, the OneDrive icon will not be visible anymore.

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

## Remove OneDrive Icon Without Uninstalling OneDrive

 This registry hack is a handy way to make the OneDrive icon disappear without deleting the app entirely from your PC. Alternatively, if you don’t use the service, you can completely remove OneDrive on Windows 11 or disable the service using Group Policy Editor.

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-soundsnatcher-free-guide-and-assessment/"><u>[New] In 2024, SoundSnatcher Free Guide & Assessment</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-top-8-youtube-imagery-techniques-for-higher-engagement/"><u>[New] In 2024, Top 8 YouTube Imagery Techniques for Higher Engagement</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-identifying-your-individual-song-collection-on-youtube/"><u>2024 Approved Identifying Your Individual Song Collection on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/como-montar-seu-primeiro-video-usando-o-criador-do-mac-tutoriais-movavi-simplificados/"><u>Como Montar Seu Primeiro Vídeo Usando O Criador Do Mac - Tutoriais Movavi Simplificados</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/convertir-archivos-jpeg-a-formato-png-online-sin-coste-alguno/"><u>Convertir Archivos JPEG a Formato PNG Online Sin Coste Alguno</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decouvrez-la-fabrique-dimages-de-storyboard-methode-et-procedes-pour-creer-un-effet-visuel-persuasif/"><u>Découvrez La Fabrique D'Images De Storyboard: Méthode Et Procédés Pour Créer Un Effet Visuel Persuasif!</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-full-guide-to-unlock-iphone-6s-with-itunes-by-drfone-ios/"><u>In 2024, Full Guide to Unlock iPhone 6s with iTunes</u></a></li>
<li><a href="https://common-error.techidaily.com/master-the-fix-dealing-with-persistent-pc-freezing-issues-successfully/"><u>Master the Fix: Dealing with Persistent PC Freezing Issues Successfully</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/revolutionizing-remote-communications-how-zooms-new-vision-pro-compatibility-could-affect-your-meetings-discover-more-on-zdnet/"><u>Revolutionizing Remote Communications: How Zoom's New Vision Pro Compatibility Could Affect Your Meetings - Discover More on ZDNET</u></a></li>
<li><a href="https://fox-useful.techidaily.com/solving-the-issue-of-missing-itunes-songs-in-your-ios-library-iphone-2024/"><u>Solving the Issue of Missing iTunes Songs in Your iOS Library (iPhone - 2024)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trasformare-i-file-mp3-in-formato-webm-senza-costi-con-il-servizio-di-movavi/"><u>Trasformare I File MP3 in Formato WEBM Senza Costi Con Il Servizio Di Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-202/"><u>동영상 줄이기 기술에서 시대를 전환하는 데 도움이 되는 10가지 권장 프로그: 202</u></a></li>
<li><a href="https://win11-tips.techidaily.com/m2p-mpeg-movavi/"><u>오피스용 무세금 M2P MPEG 데이터를 자동으로 변환하는 Movavi - 단순한 방법</u></a></li>
</ul></div>

