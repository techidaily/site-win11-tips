---
title: Direct User Name Changes for W11 Enthusiasts
date: 2024-06-25T16:17:30.261Z
updated: 2024-06-26T16:17:30.261Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Direct User Name Changes for W11 Enthusiasts
excerpt: This Article Describes Direct User Name Changes for W11 Enthusiasts
keywords: W11 Username Update,W11 Account Change,New W11 Nicknames,W11 Identity Revision,W11 User Editing,Alter W11 Username,Personalize W11 ID
thumbnail: https://thmb.techidaily.com/ea52c7c75e7b3032041ebf8f7a073a81be868964630fead8d644714b724c8d98.jpg
---

## Direct User Name Changes for W11 Enthusiasts

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/enhance-control-over-group-policy-in-windows-11/"><u>Enhance Control over Group Policy in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-printmanagementmsc-not-found-error-on-windows/"><u>How to Fix the Printmanagement.msc Not Found Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-build-custom-text-transcription-software-on-windows-with-whisper/"><u>How to Build Custom Text Transcription Software on Windows with Whisper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-high-cpu-usage-in-dropbox-on-windows-pcs/"><u>Tackling High CPU Usage in Dropbox on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-workflow-paste-and-mouse-jump-techniques/"><u>Accelerate Workflow: Paste & Mouse Jump Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stopping-spontaneous-activation-of-file-explorer/"><u>Stopping Spontaneous Activation of File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-windows-11-calculator-activation/"><u>Steps for Windows 11 Calculator Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-switching-back-the-windows-11-search-icons/"><u>Steps for Switching Back the Windows 11 Search Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-security-running-as-administrator/"><u>Navigating Windows Security: Running As Administrator</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-10-catchy-pixel-art-wallpapers-and-how-to-custom-your-own-with-ease-for-2024/"><u>Updated 10 Catchy Pixel Art Wallpapers and How to Custom Your Own with Ease for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-tecno-pova-5-pro-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Tecno Pova 5 Pro Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/rclass-banishing-green-on-your-mac-for-youtube-success/"><u>Masterclass  Banishing Green on Your Mac for YouTube Success</u></a></li>
<li><a href="https://ai-voice.techidaily.com/updated-2024-approved-top-5-ai-voice-generators-online-supports-all-browsers/"><u>Updated 2024 Approved Top 5 AI Voice Generators Online (Supports All Browsers)</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-essential-steps-to-implement-video-card-anchors-on-youtube-for-2024/"><u>[Updated] Essential Steps to Implement Video Card Anchors on YouTube for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-efficient-use-of-obs-with-zoom-video-platform-for-2024/"><u>[Updated] Efficient Use of OBS with Zoom Video Platform for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-oneplus-11r-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My OnePlus 11R? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-gathered-greetings-grabber/"><u>2024 Approved  Gathered Greetings Grabber</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-ipad-speech-recording-uncovered-top-methods/"><u>In 2024, IPad Speech Recording Uncovered  Top Methods</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-hdr-mastery-for-home-and-professional-pcs/"><u>2024 Approved  HDR Mastery for Home and Professional PCs</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>