---
title: Modify User Folder Name Settings in Windows 11 OS
date: 2025-02-11T22:42:35.999Z
updated: 2025-02-15T16:07:12.767Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Modify User Folder Name Settings in Windows 11 OS
excerpt: This Article Describes Modify User Folder Name Settings in Windows 11 OS
keywords: Windows 11 Folder Edit,Change User Path Win11,Adjust User Profile Window11,Username Update Windows11,Personalize User Name WinOS,Rename Folders Windows11User,Set User Name Win11 Settings
thumbnail: https://thmb.techidaily.com/3c1c5ccae26de82b5c27b74337e4224665d5a7b903378f876b3f4cc7ee4fa520.png
---

## Modify User Folder Name Settings in Windows 11 OS

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Key Takeaways

* Windows 11 creates a default user profile folder based on the first five characters of your account name, but you can change it using a registry hack.
* Changing the user profile folder name can cause issues with some Microsoft Store apps, but signing out and signing back in may fix the problem.
* To change the user profile folder name, create a new administrator account, modify the registry entries associated with your user account, and then rename the user profile folder in File Explorer.

 When you create a new user account in Windows 11, the operating system automatically creates a new user profile folder in C:\\Users\\Username. However, this default user profile folder name is not always what you want.

 Windows, by default, will use the first five characters of your user account name as the profile folder name. If you don’t like the user profile folder name, you can change it using a registry hack. Here, we show you how to change the name of the user profile folder in Windows 11\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## But First, Some Potential Issues That May Arise From These Steps

 While the registry hack should help you successfully change your user account folder name, it can lead to some complications. For example, some of your Microsoft Store apps, including OneDrive and Outlook, can stop working.

 Try to sign out and sign in to your app as a quick fix. If that does not work, you’ll need to move the existing path and define the new correct path after changing the user folder name.

 Also, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and exercise extreme caution while changing your user name folder. Incorrect modification to the Windows Registry can cause serious issues and may require reinstallation of the operating system.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QRaEdFMU-Xc?si=OjaiTvlogJy5wHhN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Create a New Administrator User Account in Windows 11

 To change your current user profile name, log into a different administrator account. You cannot modify an existing user account profile path from the same account.

 To do this, you can [enable and use the built-in administrator account in Windows 11](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/). If not, follow these steps to create a new administrator account in Windows 11\.

 To create a new administrator account:

1. Press **Win + I** to open **Settings**.
2. Open the **Accounts** tab in the left pane.
3. Click on **Family & other users** in the right pane.  
![Windows 11 add user account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/Windows-11-add-user-account.png)
4. Click **Other users.** This option is useful to create a local user account without a Microsoft Account.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Add other user account in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/add-other-user-account-windows-11.png)
5. Next, click on **I don’t have this person’s sign-in information.**  

![Creating a local user account without a Microsoft account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-local-user-account-without-Microsoft-account.png)

1. Click on **Add a user** **without a Microsoft account.**
2. Type a name for the user account. Leave the password field empty and click **Next**.
3. Click on the new user account and click **Change account type.**
4. Click the drop-down for **Account type** and select **Administrator**.
5. Click **OK** to save the changes.

 Now, you can log in with your new administrator account. To do this, click **Start**, then click on the user profile name, and select **Sign out.** Next, sign in with the new administrator account.

## How to Change the User Profile Folder Name Using the Registry Editor

 You can modify the registry entries associated with your user account to change the user profile folder name in Windows 11\.

 This process involves modifying your registry entries, so we recommend you create a restore point. You can [use the restore point to restore your PC](https://www.makeuseof.com/use-system-restore-windows/) if something goes wrong during the process.

 To change the user profile folder name:

1. Sign out from your current user account and log in with a built-in or newly created administrator account
2. Next, press **Win + R** to open the **Run** dialog.
3. Type **netplwiz** and click **OK** to open the **User Accounts** dialog.
4. Here, select your **user account** and click on **Properties**.  
![User accounts properties.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/user-accounts-properties.jpg)
5. In the **User Properties** dialog, you’ll see your **User name** and **Full name.**

1. Type a name for your user name, click **OK** and **Apply**.  
![user account user name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/user-acount-user-name.jpg)
2. Close the **User Account** dialog and perform a restart.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Next, open the Command Prompt. To do this, press **Win + R,** type **cmd,** and click **OK**.  
![SID command prompt user account.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/SID-command-prompt-user-account.png)
4. In the Command Prompt window, type the following command to view **SID (Security Identifier)** for all user accounts:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`wmic useraccount get name,SID`
5. Here, note the **SID** for the user account you want to change the user profile folder name. In this case, the **SID** for the username **tashr** is **S-1-5-21-200486166-247335145-1769094253-1001.**

 Now that we have the SID, we must enter it into the Registry Editor. To do that, follow these steps:

1. Press **Win + R**, type **regedit,** and click **OK** to open **Registry Editor.**
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\ProfileList`
3. Inside the **ProfileList** key, locate and click on the key name identical to the **SID** you noted earlier.
4. In the right pane, right-click on **ProfileImagePath** value and select **Modify**.  
![Modify profile image path in the registry editor.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/modify-profile-image-path-registry-editor.png)
5. Enter a name you want for the profile folder and click **OK**.  

![add new name profile image path registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/add-new-name-profile-image-path-registry-editor.png)
6. Close the Registry Editor and Command Prompt window if open.

7. Next, press **Win + E** to open File Explorer and navigate to **C:\\Users\\.**  
![Rename user profile folder name.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/rename-user-profile-folder-name.png)
8. Select your **user profile** and press **F2** to rename it. Enter a new name for your user profile (it must match the user name entered in the Registry Editor).

9. Click away and then click **Continue** to save the changes.

 You may sometimes encounter the "You can’t perform this action" error when renaming the folder. This error often occurs if you switch to a different administrator account without signing out from the primary user account. Alternatively, restart your PC and repeat the steps to rename the user profile folder without the error.

 Next, log out from your current account and sign in to the user account with the new user folder name. Open File Explorer and navigate to **C:\\Users\\**, and you should be able to use the previous profile with the new pathname.

## Renaming the Default User Profile Folder in Windows 11, Made Easy

 While you can rename the user account in Windows 11 using the Control Panel, doing so will not change the user profile folder name. You need to modify the ProfileImagePath value in the Registry Editor with a different administrator account. Once done, you can remove the new administrator user account to declutter your login screen.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-posts.techidaily.com/new-amplify-engagement-essential-tips-for-tiktok-unbox-videos-for-2024/"><u>[New] Amplify Engagement Essential Tips for TikTok Unbox Videos for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-boosting-youtube-productions-best-mac-mp4-editors-guide/"><u>[Updated] In 2024, Boosting YouTube Productions Best Mac MP4 Editors Guide</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-why-are-my-videos-flipped-in-instagram-written-by-michael-aaron-millman-and-richard-g-cox-jr/"><u>[Updated] In 2024, Why Are My Videos Flipped in Instagram' Written by Michael Aaron Millman and Richard G. Cox, Jr</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-latest-tp-link-wifi-adapter-software-optimized-for-windows-10-8-and-7-devices/"><u>Download Latest TP-Link WiFi Adapter Software: Optimized for Windows 10, 8 and 7 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-conversion-techniques-from-docx-to-pdf-on-windows-11/"><u>Efficient Conversion Techniques From Docx to PDF on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-missing-items-in-windows-explorer-navigation/"><u>Fixing Missing Items in Windows Explorer Navigation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-turn-your-mp3s-into-audio-cds-with-imgburn-on-windows/"><u>How to Turn Your Mp3s Into Audio CDs With ImgBurn on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterbatch-execution-automation-via-task-scheduler/"><u>Masterbatch Execution: Automation via Task Scheduler</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/perfect-whatsapp-ringtones-for-iphone-and-android-users/"><u>Perfect WhatsApp Ringtones for iPhone & Android Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-and-effective-fixes-to-windows-onedrive-problems/"><u>Quick and Effective Fixes to Windows OneDrive Problems</u></a></li>
<li><a href="https://fox-info.techidaily.com/razer-gaming-hub-analysis-wireless-networking-options/"><u>Razer Gaming Hub Analysis: Wireless Networking Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-techniques-to-alter-files-on-your-win-os/"><u>Tailored Techniques to Alter Files on Your Win OS</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-science-behind-how-nightshades-enamel-coatings-and-synthetic-ai-poisons-operate/"><u>The Science Behind How Nightshades, Enamel Coatings, and Synthetic AI Poisons Operate</u></a></li>
<li><a href="https://discover-able.techidaily.com/the-ultimate-walkthrough-for-enabling-and-using-synology-duplicate-file-elimination/"><u>The Ultimate Walkthrough for Enabling and Using Synology Duplicate File Elimination</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/top-5-snug-scenarios-for-your-snowy-youtube-sessions/"><u>Top 5 Snug Scenarios for Your Snowy Youtube Sessions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/yule-time-share-windows-games-through-ms-store/"><u>Yule Time: Share Windows Games Through MS Store</u></a></li>
</ul></div>

