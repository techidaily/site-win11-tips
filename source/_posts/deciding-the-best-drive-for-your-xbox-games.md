---
title: Deciding the Best Drive for Your Xbox Games
date: 2024-06-25T16:22:05.557Z
updated: 2024-06-26T16:22:05.557Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deciding the Best Drive for Your Xbox Games
excerpt: This Article Describes Deciding the Best Drive for Your Xbox Games
keywords: Xbox Gaming Drives,Optimal Xbox Console,Xbox Game Performance,Xbox Compatible Discs,High-Speed Xbox Drive,Top Xbox Games,Choosing Xbox Storage
thumbnail: https://thmb.techidaily.com/a333bfbef34affdca1048ed2699696db5230242a15d7fcb3455927615d5179aa.JPG
---

## Deciding the Best Drive for Your Xbox Games

 The Xbox app lets you purchase and install games on any of your system drives. Usually, this process works well, but sometimes, the Xbox app won't let you install games in any location other than the default directory. This can be problematic, especially when you want to install a big-size game, but the default directory doesn't have enough space.

 Such situations usually arise due to corruption in the Xbox app or misconfigured registry settings. Fortunately, it's very easy to troubleshoot this problem. Here are some fixes to try when you can't choose a drive to install games on the Xbox app.

## 1\. Restart the Computer ![Restart option in Power menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restart.jpg)

 You might fail to change the installation drive in the Xbox app due to a temporary system glitch or bug. Luckily, you can quickly eliminate such bugs and glitches by restarting your computer.

 To restart, press the**Alt + F4** hotkeys to open the Shut Down Windows prompt, click the drop-down icon, choose**Restart** from the context menu, and then click**OK.** After restart, launch the Xbox app and check if you can choose a different drive to install games. If not, then it's time to dive into the advanced troubleshooting methods.

## 2\. Change the Installation Directory in the Xbox App Settings

 There are two places from where you can change the installation drive on the Xbox app. One is while installing the game, whereas the other is the Xbox settings menu.

 If the first method is not working, you can use the second method to change the installation drive in the Xbox app. So, here's how to edit the Xbox app settings to change its default download location.

1. Launch the Xbox app, click on your profile in the top left corner, and choose**Settings** from the context menu.
2. Choose**General** from the left sidebar.
3. Click the**Change folder** option under**Change where this app installs games by default** .  
![Change Folder in Xbox app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-folder.jpg)
4. Choose the location where you want to install the game and then click the**Select Folder** option.

## 3\. Customize the System Settings

 If editing the Xbox app settings wasn't helpful, you can edit the system settings and check if it makes a difference. Here's what you need to do:

1. Press the**Win + I** hotkeys to open the**Settings app.**
2. Choose**System** from the left sidebar and then click on the**Storage** option in the right pane.
3. Click the drop-down icon next to**Advanced storage settings** and choose**Where new content** **is saved** option from the context menu.  
![Where new content is saved option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/where-new-content-is-saved.png)
4. Click the drop-down icon under the**New** **apps** **will save to** section, choose the drive where you want to install the game, and then click**Apply.**  
![New apps will save to section in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-apps-will-save-to-section.jpg)

 That's it! Restart your computer and check if the problem continues.

## 4\. Restart Important Xbox Services ![Restart Service option in Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restart-service.jpg)

 There are certain Xbox services that must be running for you to use the Xbox app properly. If any of these services fail to start properly, you might face the problem at hand.

 To fix that, restart each service manually. Here's how to do that:

1. Open the Run dialog box by pressing the**Win + R** hotkeys.
2. Type**services.msc** in the search bar and click OK.
3. In the Services window, locate and right-click on the following services and choose**Restart** from the context menu.  
`Xbox Accessory Management  
Xbox Live Game Save  
Xbox Live Auth Manager  
Xbox Live Networking Service`

## 5\. Reinstall the Gaming Services App

 The Gaming Services app allows you to seamlessly download apps and games from the Microsoft Store and the Xbox app. But if the app gets corrupt, you might face various issues, including the one in question.

 The solution, in this case, is to reinstall the Gaming Services app on your computer. You can do that by following the below instructions:

 Editing the registry can be dangerous, as one wrong edit can make your system unstable. To ensure that your data is secure even if something goes wrong,[back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

1. Open the Run dialog box, type**regedit,** and click OK.
2. In the Registry Editor, navigate to the below location:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services`
3. Right-click on the**GamingServices** folder in the left sidebar and choose**Delete** from the context menu.  
![Delete option in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-option.jpg)
4. Click**Yes** to confirm your selection.
5. Next, delete the**GamingServicesNet** folder as well in the left sidebar.

 Now, open the elevated PowerShell window (see how to [open Windows PowerShell as an administrator](https://www.makeuseof.com/windows-powershell-always-open-as-administrator/) ), type the following command, and press**Enter** .

`Get-AppxPackage *gamingservices* -allusers | remove-appxpackage -allusers`

![Remove Gaming Services command in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-gaming-services.jpg)

 After uninstalling the Gaming Services app, restart your computer. Then, open the Microsoft Store, search for and [download the Gaming Services](https://apps.microsoft.com/store/detail/gaming-services/9MWPM2CQNLHN?hl=en-us&gl=us) app again.

## 6\. Repair the Xbox App

 It's very common for the Xbox app to get corrupt and throw various issues. The best way to remove corruption from the UWP apps like the Xbox app is to use the Windows repair feature.

 Check out [how to repair apps and programs on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) for information on how to do this.

## 7\. Update the Xbox App

 If repairing the Xbox app doesn't remove the corruption, consider updating the app. Downloading the latest update of the Xbox app will not only remove the corruption but also introduce new features.

To update the Xbox app, follow the below steps:

1. Open the Microsoft Store and click the**Library** option in the left sidebar.
2. Click the**Get updates** button to allow the Microsoft Store to search for available updates of the installed apps.

 The Microsoft Store will now automatically download updates for installed apps, including the Xbox app.

 While you're at installing updates, we'd also recommend [downloading any available Windows updates](https://www.makeuseof.com/tag/update-windows-software-guide/) . To do so, launch the Settings app, choose**Windows Update** from the left sidebar, and then click the**Check for Updates** button to install any available update on your computer. Following this, you will be able to choose a drive to install games on the Xbox app.

## Change the Download Location of the Xbox App

 The Xbox app is a great place to download your favorite games. However, the app might fail to change the installation location of games. Fortunately, you can quickly eliminate this issue by following the above fixes.

 Meanwhile, you might be interested to know how to increase downloading speed of the Xbox app.


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
<li><a href="https://win11-tips.techidaily.com/how-to-disable-old-user-id-prompt-in-windows-login-screen/"><u>How to Disable 'Old User ID' Prompt in Windows Login Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-swift-steps-for-word-definition-finder/"><u>7 Swift Steps for Word Definition Finder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-silent-auditory-alerts/"><u>Fixing Windows' Silent Auditory Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/onedrives-blob-tag-issue-a-windows-based-solution-guide/"><u>OneDrive's Blob Tag Issue: A Windows-Based Solution Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/routes-to-success-system32-on-windows-11/"><u>Routes to Success: System32 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/raising-the-bar-for-user-interface-in-w11-larger-icons/"><u>Raising the Bar for User Interface in W11: Larger Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directing-local-groups-policy-a-focused-approach-for-users-in-windows-11-and-11/"><u>Directing Local Groups Policy: A Focused Approach for Users in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-unavailability-of-icloud-on-windows/"><u>Fixing the Unavailability of iCloud on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-conquering-win-errors/"><u>The Ultimate Guide to Conquering Win Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-vac-rejection-in-steam-windows-gameplay/"><u>Overcoming VAC Rejection in Steam Windows Gameplay</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-taking-photos-and-posting-youtubes-complete-guidebook/"><u>2024 Approved  Taking Photos and Posting  YouTube's Complete Guidebook</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-enhancing-instagram-visibility-with-powerful-promotions/"><u>[Updated] In 2024, Enhancing Instagram Visibility with Powerful Promotions</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-film-set-harmony-exploring-every-members-critical-function-in-movie-making/"><u>New 2024 Approved Film Set Harmony Exploring Every Members Critical Function in Movie-Making</u></a></li>
<li><a href="https://extra-skills.techidaily.com/precision-in-proiphone-close-up-a-guide-to-professional-results-for-2024/"><u>Precision in Proiphone Close-Up  A Guide to Professional Results for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-beginners-pathway-to-grasping-hd-content-standards/"><u>In 2024, Beginner’s Pathway to Grasping HD Content Standards</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-from-ordinary-to-outstanding-crafting-unique-shorts-thumbnails/"><u>[New] From Ordinary to Outstanding  Crafting Unique Shorts Thumbnails</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-step-up-your-iphone-x7s-selfies-with-these-top-free-tools/"><u>[Updated] Step Up Your iPhone X/7's Selfies with These Top Free Tools</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-expertise-in-hdr-perfecting-dynamic-range-in-photoshop/"><u>[New] Expertise in HDR  Perfecting Dynamic Range in Photoshop</u></a></li>
<li><a href="https://review-topics.techidaily.com/issues-playing-h-265-hevc-video-on-motorola-edgeplus-2023-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Issues playing H.265 HEVC video on Motorola Edge+ (2023)</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-three-no-spend-ways-to-merge-movement-and-melodies-in-your-iphone-video-clips/"><u>In 2024, Three No-Spend Ways to Merge Movement and Melodies in Your iPhone Video Clips</u></a></li>
</ul></div>
