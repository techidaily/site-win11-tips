---
title: User Directory Customization in Windows 11
date: 2024-11-21T17:55:57.828Z
updated: 2024-11-27T17:40:43.005Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes User Directory Customization in Windows 11
excerpt: This Article Describes User Directory Customization in Windows 11
keywords: Win11 User Dir Config,Personalized Window Settings,Customize User Interface Win11,Enhance User Experience Win11,Windows 11 User Profile Customization,Individualized UI in Win11,Tailor-Fit Windows 11 Interface
thumbnail: https://thmb.techidaily.com/cc90cfb91ad0a20c12f9d720fc85b3d9e0382268e1d979284c574fcec450998c.jpg
---

## User Directory Customization in Windows 11

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* Windows 11 creates a default user profile folder based on the first five characters of your account name, but you can change it using a registry hack.
* Changing the user profile folder name can cause issues with some Microsoft Store apps, but signing out and signing back in may fix the problem.
* To change the user profile folder name, create a new administrator account, modify the registry entries associated with your user account, and then rename the user profile folder in File Explorer.

 When you create a new user account in Windows 11, the operating system automatically creates a new user profile folder in C:\\Users\\Username. However, this default user profile folder name is not always what you want.

 Windows, by default, will use the first five characters of your user account name as the profile folder name. If you don’t like the user profile folder name, you can change it using a registry hack. Here, we show you how to change the name of the user profile folder in Windows 11\.

## But First, Some Potential Issues That May Arise From These Steps

 While the registry hack should help you successfully change your user account folder name, it can lead to some complications. For example, some of your Microsoft Store apps, including OneDrive and Outlook, can stop working.

 Try to sign out and sign in to your app as a quick fix. If that does not work, you’ll need to move the existing path and define the new correct path after changing the user folder name.

 Also, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and exercise extreme caution while changing your user name folder. Incorrect modification to the Windows Registry can cause serious issues and may require reinstallation of the operating system.

## How to Create a New Administrator User Account in Windows 11

 To change your current user profile name, log into a different administrator account. You cannot modify an existing user account profile path from the same account.

 To do this, you can [enable and use the built-in administrator account in Windows 11](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/). If not, follow these steps to create a new administrator account in Windows 11\.

 To create a new administrator account:

1. Press **Win + I** to open **Settings**.
2. Open the **Accounts** tab in the left pane.
3. Click on **Family & other users** in the right pane.  
![Windows 11 add user account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/Windows-11-add-user-account.png)
4. Click **Other users.** This option is useful to create a local user account without a Microsoft Account.  
![Add other user account in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/add-other-user-account-windows-11.png)
5. Next, click on **I don’t have this person’s sign-in information.**  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Type a name for your user name, click **OK** and **Apply**.  
![user account user name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/user-acount-user-name.jpg)
2. Close the **User Account** dialog and perform a restart.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Next, open the Command Prompt. To do this, press **Win + R,** type **cmd,** and click **OK**.  
![SID command prompt user account.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/SID-command-prompt-user-account.png)
4. In the Command Prompt window, type the following command to view **SID (Security Identifier)** for all user accounts:  
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. Click away and then click **Continue** to save the changes.

 You may sometimes encounter the "You can’t perform this action" error when renaming the folder. This error often occurs if you switch to a different administrator account without signing out from the primary user account. Alternatively, restart your PC and repeat the steps to rename the user profile folder without the error.

 Next, log out from your current account and sign in to the user account with the new user folder name. Open File Explorer and navigate to **C:\\Users\\**, and you should be able to use the previous profile with the new pathname.

## Renaming the Default User Profile Folder in Windows 11, Made Easy

 While you can rename the user account in Windows 11 using the Control Panel, doing so will not change the user profile folder name. You need to modify the ProfileImagePath value in the Registry Editor with a different administrator account. Once done, you can remove the new administrator user account to declutter your login screen.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-navigating-the-world-of-gopro-streaming-and-social-media-networks/"><u>[New] Navigating the World of Gopro Streaming and Social Media Networks</u></a></li>
<li><a href="https://common-error.techidaily.com/0x80070490-error-code-in-windows-update-fixed/"><u>0X80070490 Error Code in Windows Update [FIXED]</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-ultimate-selection-economical-hd-action-recordings/"><u>2024 Approved Ultimate Selection Economical HD Action Recordings</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/2024-approved-youtube-integration-a-beginners-guide-to-google-meet/"><u>2024 Approved YouTube Integration A Beginner's Guide to Google Meet</u></a></li>
<li><a href="https://location-social.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-poco-x5-pro-by-name-drfone-by-drfone-virtual-android/"><u>4 Most-Known Ways to Find Someone on Tinder For Poco X5 Pro by Name | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-guide-to-chrome-setup-in-windows-11/"><u>Comprehensive Guide to Chrome Setup in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-productivity-with-our-experts-choice-of-8-windows-timer-tools/"><u>Enhance Productivity with Our Expert's Choice of 8 Windows Timer Tools</u></a></li>
<li><a href="https://hardware-help.techidaily.com/ensure-optimal-performance-downloading-and-updating-razer-graphics-drivers-for-all-windows-versions/"><u>Ensure Optimal Performance: Downloading and Updating Razer Graphics Drivers for All Windows Versions</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/expertly-curated-green-screen-gear-list-for-2024/"><u>Expertly Curated Green Screen Gear List for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-crafting-gentle-sound-declines-with-logic-pro/"><u>In 2024, Crafting Gentle Sound Declines with Logic Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-launching-techniques-for-modern-applications-in-windows/"><u>Innovative Launching Techniques for Modern Applications in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-ps-to-find-ip-and-mac-on-windows-devices/"><u>Leveraging PS to Find IP and MAC on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-zip-in-windows-11-with-these-tips/"><u>Master ZIP in Windows 11 With These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-token-reference-error-in-modern-oses/"><u>Overcoming the Token Reference Error in Modern OSes</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/razer-blackwidow-find-install-and-update-drivers-with-expert-advice/"><u>Razer BlackWidow: Find, Install & Update Drivers with Expert Advice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stick-to-your-pc-screen-8-innovative-non-writing-tools/"><u>Stick to Your PC Screen: 8 Innovative, Non-Writing Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-tricks-for-net-revival-on-your-os-max-156/"><u>Top Tricks for .NET Revival on Your OS (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-graphics-issues-a-windows-10-and-11-fix-it/"><u>Troubleshooting Graphics Issues: A Windows 10 & 11 Fix-It</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/s-edge-over-youtube-what-the-data-says-for-2024/"><u>Vimeo’s Edge Over YouTube? What the Data Says for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    