---
title: Editing Directory Names for Users in Windows 11 Edition
date: 2024-07-12T17:23:18.505Z
updated: 2024-07-13T17:23:18.505Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Editing Directory Names for Users in Windows 11 Edition
excerpt: This Article Describes Editing Directory Names for Users in Windows 11 Edition
keywords: Win11 Dir Edit Guide,Editing Window Editions,Win11 Name Changes,Windows 11 Naming,Directories in Win11,User Edits in Windows,Update Directory Names (Win11)
thumbnail: https://thmb.techidaily.com/81e161f907419dfdc391568e85d3e05da23f1ff740a914248fee4864660d3de9.jpg
---

## Editing Directory Names for Users in Windows 11 Edition

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
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-efficient-game-recordings-in-the-era-of-win10/"><u>2024 Approved  Efficient Game Recordings in the Era of Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crucial-cross-platform-tools-windows-meets-android/"><u>Crucial Cross-Platform Tools: Windows Meets Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-non-definable-error-in-windows-environment/"><u>Tackling 'Non-Definable' Error in Windows Environment</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-top-16-best-free-easy-movie-makers-for-2024/"><u>New Top 16 Best Free Easy Movie Makers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-windows-exploration-without-the-use-of-ls/"><u>Streamlined Windows Exploration Without the Use of LS</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/from-footage-to-frame-crafting-youtube-thumbnails-on-mobile-devices-for-2024/"><u>From Footage to Frame  Crafting YouTube Thumbnails on Mobile Devices for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-microsoft-store-fault-code-0x80072efd/"><u>Eradicating Microsoft Store Fault Code 0X80072EFD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-strategy-for-sound-graph-segregation/"><u>Understanding Windows' Strategy for Sound Graph Segregation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/successfully-overcome-windows-error-0x80070003-a-step-by-step-guide/"><u>Successfully Overcome Windows Error 0X80070003 - A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-insiders-guide-to-customizing-the-desktop-menu/"><u>The Insider's Guide to Customizing the Desktop Menu</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/exquisite-couple-clips-the-best-weddings-online-8-picks-for-2024/"><u>Exquisite Couple Clips  The Best Weddings Online (8 Picks) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-evolves-spotlight-on-new-updates-capabilities/"><u>Windows 11 Evolves: Spotlight on New Updates' Capabilities</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-inside-splice-video-editor-a-close-up-look-at-its-features-and-functionality/"><u>Updated Inside Splice Video Editor A Close-Up Look at Its Features and Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/where-windows-hides-shot-files/"><u>Where Windows Hides Shot Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winrars-hash-harmony-six-ways-to-ensure-correct-sums/"><u>WinRAR's Hash Harmony: Six Ways to Ensure Correct Sums</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-prevent-date-changes-on-windows-pcs/"><u>Steps to Prevent Date Changes on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-write-file-access-issue-on-windows-1011/"><u>Troubleshooting Write File Access Issue on Windows 10/11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-screen-recorder-freedom-top-10-no-cost-choices-for-cameras/"><u>2024 Approved  Screen Recorder Freedom  Top 10 No-Cost Choices for Cameras</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-windows-crash-focus-on-0x800f0831/"><u>Eliminate Windows Crash: Focus on 0X800f0831</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-restoring-accessibility-of-displays-in-nvidia-software/"><u>Tips for Restoring Accessibility of Displays in Nvidia Software</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-unveiling-techniques-from-recording-room-to-facebook-lives/"><u>2024 Approved  Unveiling Techniques  From Recording Room to Facebook Lives</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-the-artisans-approach-to-archiving-facebook-discussions-for-2024/"><u>[New] The Artisan's Approach to Archiving Facebook Discussions for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-free-filmora-without-the-risk-safe-and-legal-alternatives/"><u>New In 2024, Free Filmora Without the Risk Safe and Legal Alternatives</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/the-ultimate-selection-of-youtube-content-cutters-online/"><u>The Ultimate Selection of YouTube Content Cutters Online</u></a></li>
<li><a href="https://article-files.techidaily.com/new-ultimate-online-broadcast-platforms/"><u>[New] Ultimate Online Broadcast Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-failure-code-0x0001-on-nvidia-software/"><u>Addressing Failure Code 0X0001 on Nvidia Software</u></a></li>
<li><a href="https://extra-information.techidaily.com/cross-platform-mixmaster-2023/"><u>Cross-Platform MixMaster 2023</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-ascending-altitudes-in-depth-analysis-of-the-gopro-karma-drone/"><u>[Updated] Ascending Altitudes  In-Depth Analysis of the GoPro Karma Drone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719334227097-windows-transcends-platforms-iphoneipadmacpc-compatibility-announced/"><u>Windows Transcends Platforms: IPhone/iPad/Mac/PC Compatibility Announced!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disabled-lock-screen-timeout-windows/"><u>Addressing Disabled Lock Screen Timeout Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11-potential-steps-for-successful-optional-components-integration/"><u>Unlocking Windows 11 Potential: Steps for Successful Optional Components Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-setting-up-window-sandbox/"><u>The Ultimate Guide to Setting up Window Sandbox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-code-0x0000004e-on-windows-os/"><u>Eliminating Code 0X0000004E on Windows OS</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-download-vllo-for-mac-os-and-uncover-alternative-options/"><u>2024 Approved Download VLLO for Mac OS and Uncover Alternative Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-windows-11s-notepad-with-copilot/"><u>Supercharge Windows 11’S Notepad With Copilot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-and-o365-sync-issues-a-quick-guide-to-fixing-errors/"><u>Win 11 and O365 Sync Issues: A Quick Guide to Fixing Errors</u></a></li>
</ul></div>
