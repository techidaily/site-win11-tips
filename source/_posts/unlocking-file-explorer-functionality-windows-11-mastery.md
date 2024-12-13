---
title: "Unlocking File Explorer Functionality: Windows 11 Mastery"
date: 2024-12-05T16:30:42.735Z
updated: 2024-12-12T16:25:56.291Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking File Explorer Functionality: Windows 11 Mastery"
excerpt: "This Article Describes Unlocking File Explorer Functionality: Windows 11 Mastery"
keywords: Win11 Folder Tools,Explore Files Ease,Power Windows File,XP Toolkit Window,Navigate Explorer Tips,Master File Access,Exploit OS Explorer
thumbnail: https://thmb.techidaily.com/259bceb776cdbf3be867bf48c477b3f9885a0b2e906117f4f6cafe9378e4fe6f.jpg
---

## Unlocking File Explorer Functionality: Windows 11 Mastery

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iPCr_bxZjMQ?si=ubOsoq5umPEXL9xL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 Before you proceed, we highly recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to familiarize yourself with what we will be doing next. Also important is knowing [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). Considering this is the database that Windows stores the data it needs to operate properly, you will need this backup in case you make an error.

 For showing and hiding folders in This PC to work, make sure you’re running the latest version of Windows 11\. You'll know you have it if File Explorer has tabs.

 With the Registry Editor open, let's get to it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)

 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0nGlyEL5K6Y?si=3KZhTTBvKcPmyS68" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UcplMvRBulA?si=iBonbwDS1v7RAlHK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, refresh File Explorer with **F5** and the **Documents** folder will appear in This PC.

 To hide it, right-click the key on the left panel and select **New > DWORD (32-bit) Value** and name it **HideIfEnabled**. Double-click the newly-created value in the right panel, set **Value data** to **22ab9b9**, and then click **OK**.

![set-hideifenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-hideifenabled.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-mobile-mastery-the-leading-app-list-for-popularity-growth/"><u>[New] 2024 Approved Mobile Mastery The Leading App List for Popularity Growth</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-straightforward-strategies-for-iphones-screen-recording/"><u>[New] In 2024, Straightforward Strategies for iPhone's Screen Recording</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-maximize-space-free-20plus-storage-options-with-limits-up-to-1tb/"><u>[Updated] 2024 Approved Maximize Space Free 20+ Storage Options With Limits (Up To 1TB)</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-crafting-your-unique-look-in-windows-photos-app-with-music-and-filter-choices/"><u>[Updated] Crafting Your Unique Look in Windows Photos App with Music and Filter Choices</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-virality-vault-uncovering-keywords-that-drive-video-shares/"><u>[Updated] In 2024, Virality Vault Uncovering Keywords That Drive Video Shares</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-capacity-barrier-in-gpt-windows-service/"><u>Clearing Capacity Barrier in GPT-Windows Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-center-mastery-administering-windows-panel/"><u>Command Center Mastery: Administering Windows Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-methods-incorporate-isp-data-on-desktop/"><u>Easy Methods: Incorporate ISP Data on Desktop</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-from-apple-iphone-11-pro-max-to-iphone-8x11-drfone-by-drfone-transfer-from-ios/"><u>How to Transfer from Apple iPhone 11 Pro Max to iPhone 8/X/11 | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/irobot-roomba-combo-j9-plus-evaluation-an-innovative-robotic-cleaner-with-smart-features-and-user-friendly-interface/"><u>IRobot Roomba Combo J9 Plus Evaluation: An Innovative Robotic Cleaner with Smart Features & User-Friendly Interface</u></a></li>
<li><a href="https://media-tips.techidaily.com/seamless-streaming-with-airplay-across-ios-13-ipads-iphones-and-new-models/"><u>Seamless Streaming with AirPlay Across iOS 13 iPads, iPhones & New Models</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tame-frozen-windows-handbraked-beast/"><u>Tame Frozen Windows-Handbraked Beast</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-dominating-your-gameplay-in-ps1-and-win/"><u>The Ultimate Guide to Dominating Your Gameplay in PS1 and WIN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreezing-sleep-with-inputs-on-win11/"><u>Unfreezing Sleep with Inputs on Win11</u></a></li>
</ul></div>

