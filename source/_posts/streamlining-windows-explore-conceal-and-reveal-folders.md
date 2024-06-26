---
title: "Streamlining Windows Explore: Conceal and Reveal Folders"
date: 2024-06-25T16:40:33.674Z
updated: 2024-06-26T16:40:33.674Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlining Windows Explore: Conceal and Reveal Folders"
excerpt: "This Article Describes Streamlining Windows Explore: Conceal and Reveal Folders"
keywords: Streamline Explorer,Hide Show Folders,Optimize File View,Enhance Explorer UI,Windows Folder Display,Conceal Folder Toggle,Reveal Folder Quickly
thumbnail: https://thmb.techidaily.com/43693d1bcddc3757eef24651324be62efb3dc8d54599f3df8a30593f96e0aa27.jpg
---

## Streamlining Windows Explore: Conceal and Reveal Folders

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

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

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

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
<li><a href="https://win11-tips.techidaily.com/security-scare-can-you-trust-your-biometric-lock-on-windows/"><u>Security Scare: Can You Trust Your Biometric Lock on Windows?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-finding-files-in-windows-11-with-the-search-bar/"><u>Accelerate Finding Files in Windows 11 with the Search Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-bypassing-ssi-and-installing-unverified-drivers/"><u>Mastering Windows: Bypassing SSI & Installing Unverified Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decrypting-windows-108-error-messages-locations/"><u>Decrypting Windows 10/8 Error Messages Locations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-footage-excellence-with-these-best-apps-for-windows-11/"><u>Enhance Footage Excellence with These Best Apps for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hidden-potential-utilize-hotkeys-to-control-windows-taskbar/"><u>Hidden Potential: Utilize Hotkeys to Control Windows Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-disabled-troubleshooters-in-modern-windows/"><u>Resolving Disabled Troubleshooters in Modern Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/reset-itunes-backup-password-of-apple-iphone-se-prevention-and-solution-by-drfone-ios/"><u>Reset iTunes Backup Password Of Apple iPhone SE Prevention & Solution</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/audiovisual-harmony-merging-audio-and-visual-elements-on-youtube/"><u>Audiovisual Harmony  Merging Audio and Visual Elements on YouTube</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-locked-or-disabled-on-apple-iphone-xs-max-7-mehtods-you-cant-miss-by-drfone-ios/"><u>Apple ID Locked or Disabled On Apple iPhone XS Max? 7 Mehtods You Cant-Miss</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-minds-on-trial-select-escapes-that-challenge-you/"><u>2024 Approved  Minds on Trial  Select Escapes That Challenge You</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-a-beginners-guide-to-video-editing-on-mac-create-stunning-movies/"><u>Updated A Beginners Guide to Video Editing on Mac Create Stunning Movies</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-windows-10-sound-engineering-the-ultimate-guide-to-capturing-clear-audio/"><u>New Windows 10 Sound Engineering The Ultimate Guide to Capturing Clear Audio</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-lava-blaze-2-5g-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Lava Blaze 2 5G Is Unlocked</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-your-roadmap-to-acquiring-facebooks-esteemed-verification/"><u>[Updated] Your Roadmap to Acquiring Facebook’s Esteemed Verification</u></a></li>
</ul></div>
