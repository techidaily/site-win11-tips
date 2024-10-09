---
title: Hidden Pc Folders Exposed in Windows 11
date: 2024-10-01T16:28:53.715Z
updated: 2024-10-08T19:36:54.492Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Hidden Pc Folders Exposed in Windows 11
excerpt: This Article Describes Hidden Pc Folders Exposed in Windows 11
keywords: Hidden PC Files Uncovered W11,Windows 11 Access Hidden Folders,Revealing Windows 11 Secrets,Exposed Pc Files in W11 OS,Windows 11 Hidden File Discovery,Disclosing Hidden PC Windows 11,Unlock Hidden Pc Directories W11
thumbnail: https://thmb.techidaily.com/2ef3dcd0a65154e26137d2fe405a5df0d2493a5332797322ea1d725cb91b8167.jpg
---

## Hidden Pc Folders Exposed in Windows 11

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

<!-- affiliate ads begin -->
<a href="https://bluettifr.pxf.io/c/5597632/2145082/17095" target="_top" id="2145082">
  <img src="//a.impactradius-go.com/display-ad/17095-2145082" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettifr.pxf.io/i/5597632/2145082/17095" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135415/19272" target="_top" id="2135415">
  <img src="//a.impactradius-go.com/display-ad/19272-2135415" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135412/19272" target="_top" id="2135412">
  <img src="//a.impactradius-go.com/display-ad/19272-2135412" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135412/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1896541/19272" target="_top" id="1896541">
  <img src="//a.impactradius-go.com/display-ad/19272-1896541" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896541/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-approaches.techidaily.com/new-the-essential-wmp-routine-for-cds-ripping-and-batch-processing/"><u>[New] The Essential WMP Routine for CDs Ripping & Batch Processing</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-zoom-strategy-for-videoleap-videos/"><u>[New] The Ultimate Zoom Strategy for Videoleap Videos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-instagram-illuminati-the-top-25-visionaries-you-need-to-see/"><u>[Updated] 2024 Approved Instagram Illuminati The Top 25 Visionaries You Need to See</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-cutting-edge-tools-for-unique-youtube-channel-names/"><u>[Updated] Cutting-Edge Tools for Unique YouTube Channel Names</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-directors-academy-youtube-channels-for-cinematic-innovation/"><u>[Updated] Directors Academy YouTube Channels for Cinematic Innovation</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-decoding-mycam-cams-video-quality-and-recording-speed/"><u>2024 Approved Decoding MyCam Cam’s Video Quality and Recording Speed</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-premier-baking-studio-best-cookies-to-try-and-buy/"><u>In 2024, Premier Baking Studio Best Cookies to Try and Buy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leading-non-windows-programs-as-substitutes-for-the-windows-snip-tool/"><u>Leading Non-Windows Programs as Substitutes for the Window’s Snip Tool</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-samsung-galaxy-m54-5g-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Samsung Galaxy M54 5G? Look No Further | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-best-weather-apps-for-windows-11-and-11/"><u>The Best Weather Apps for Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-launching-windows-ea-quickly/"><u>The Ultimate Guide to Launching Windows EA Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-profile-management-new-folder-titles/"><u>Win 11 Profile Management: New Folder Titles</u></a></li>
</ul></div>

