---
title: Quick Guide to Control Folder Display on Windows 11
date: 2024-11-04T01:04:52.093Z
updated: 2024-11-07T01:37:37.603Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Guide to Control Folder Display on Windows 11
excerpt: This Article Describes Quick Guide to Control Folder Display on Windows 11
keywords: Windows 11 Folder Visibility,Control Folder Show Windows,Set Folders Windows 11,Manage Folder Display Win11,Windows 11 Display Settings,Turn Off Folder Windows 11,Adjust Folder View Windows
thumbnail: https://thmb.techidaily.com/6f8414097089a9fbc68b8b5aaac7c01bdc6e5c33b0986ef04ba67ea8a7553849.jpg
---

## Quick Guide to Control Folder Display on Windows 11

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/977686/11832" target="_top" id="977686">
  <img src="//a.impactradius-go.com/display-ad/11832-977686" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/977686/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934142/19272" target="_top" id="1934142">
  <img src="//a.impactradius-go.com/display-ad/19272-1934142" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934142/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049382/7443" target="_top" id="2049382">
  <img src="//a.impactradius-go.com/display-ad/7443-2049382" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049382/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://homestyler.sjv.io/c/5597632/1943647/22993" target="_top" id="1943647">
  <img src="//a.impactradius-go.com/display-ad/22993-1943647" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943647/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-resources.techidaily.com/new-beyond-ustream-live-streaming-choices/"><u>[New] Beyond Ustream Live Streaming Choices</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-elevating-your-instagram-highlights-with-exquisite-photography-for-2024/"><u>[Updated] Elevating Your Instagram Highlights with Exquisite Photography for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-innovative-use-of-plugins-for-skype-call-capture-in-obs-for-2024/"><u>[Updated] Innovative Use of Plugins for Skype Call Capture in OBS for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-unveiling-elite-selection-9-best-mic-recorders-online-for-2024/"><u>[Updated] Unveiling Elite Selection 9 Best Mic Recorders Online for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-samsung-galaxy-f14-5g-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Samsung Galaxy F14 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-to-setting-up-powertoys-on-win11/"><u>Expert Guide to Setting Up PowerToys on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-internal-audio-errors-in-audacity-for-windows-1111/"><u>Fixing Internal Audio Errors in Audacity for Windows 11/11</u></a></li>
<li><a href="https://win-blog.techidaily.com/gratuit-mp3-converter-en-ligne-convertissez-facilement-vos-chansons-gsm-a-laide-du-convertisseur-de-movavi/"><u>Gratuit MP3 Converter en Ligne: Convertissez Facilement Vos Chansons GSM À L'aide Du Convertisseur De Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-circumvent-direct-folder-name-challenges-on-windows-11/"><u>How to Circumvent Direct Folder Name Challenges on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-resolving-error-0x800700e1-on-windows-11-systems/"><u>Solutions for Resolving Error 0X800700E1 on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-installer-problems-on-microsoft-store/"><u>Solving Installer Problems on Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-jumbled-symbols-in-os-taskbar-display/"><u>Solving Jumbled Symbols in OS Taskbar Display</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/top-strategies-to-maximize-win11-usage/"><u>Top Strategies to Maximize Win11 Usage</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-samsung-galaxy-s21-fe-5g-2023-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Samsung Galaxy S21 FE 5G (2023) | Dr.fone</u></a></li>
</ul></div>

