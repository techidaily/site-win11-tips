---
title: Transforming the Default User Home Path on W11 OS
date: 2024-09-05T19:38:46.586Z
updated: 2024-09-06T19:38:46.586Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Transforming the Default User Home Path on W11 OS
excerpt: This Article Describes Transforming the Default User Home Path on W11 OS
keywords: Win11 Home Route Change,Windows W11 Default Path Alteration,Personalized W11 Dashboard Customization,W11 User Interface Redesign,W11 OS Home Navigation Update,Altering W11 Start Menu Layout,Enhance Win11 Homestead Experience
thumbnail: https://thmb.techidaily.com/90c2e01727fc918de7950373ab7790d2b6bd79b92f560dcc1472e9356e8fe972.png
---

## Transforming the Default User Home Path on W11 OS

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135419/19272" target="_top" id="2135419">
  <img src="//a.impactradius-go.com/display-ad/19272-2135419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135419/19272" style="position:absolute;visibility:hidden;" border="0" />
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
![Add other user account in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/add-other-user-account-windows-11.png)
5. Next, click on **I don’t have this person’s sign-in information.**  
![Creating a local user account without a Microsoft account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-local-user-account-without-Microsoft-account.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137201/26400" target="_top" id="2137201">
  <img src="//a.impactradius-go.com/display-ad/26400-2137201" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137201/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://25home.pxf.io/c/5597632/2123475/16836" target="_top" id="2123475">
  <img src="//a.impactradius-go.com/display-ad/16836-2123475" border="0" alt="https://techidaily.com" width="300" height="75"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123475/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Type a name for your user name, click **OK** and **Apply**.  
![user account user name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/user-acount-user-name.jpg)
2. Close the **User Account** dialog and perform a restart.
<!-- affiliate ads begin -->
<span id="1155462">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1155462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1155462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1155462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1155462%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1155462/14559" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115911/19272" target="_top" id="2115911">
  <img src="//a.impactradius-go.com/display-ad/19272-2115911" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115911/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![add new name profile image path registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/add-new-name-profile-image-path-registry-editor.png)
6. Close the Registry Editor and Command Prompt window if open.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118324/7443" target="_top" id="2118324">
  <img src="//a.impactradius-go.com/display-ad/7443-2118324" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118324/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Next, press **Win + E** to open File Explorer and navigate to **C:\\Users\\.**  
![Rename user profile folder name.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/rename-user-profile-folder-name.png)
8. Select your **user profile** and press **F2** to rename it. Enter a new name for your user profile (it must match the user name entered in the Registry Editor).
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115935/19272" target="_top" id="2115935">
  <img src="//a.impactradius-go.com/display-ad/19272-2115935" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115935/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. Click away and then click **Continue** to save the changes.

 You may sometimes encounter the "You can’t perform this action" error when renaming the folder. This error often occurs if you switch to a different administrator account without signing out from the primary user account. Alternatively, restart your PC and repeat the steps to rename the user profile folder without the error.

 Next, log out from your current account and sign in to the user account with the new user folder name. Open File Explorer and navigate to **C:\\Users\\**, and you should be able to use the previous profile with the new pathname.

## Renaming the Default User Profile Folder in Windows 11, Made Easy

 While you can rename the user account in Windows 11 using the Control Panel, doing so will not change the user profile folder name. You need to modify the ProfileImagePath value in the Registry Editor with a different administrator account. Once done, you can remove the new administrator user account to declutter your login screen.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/lite-10-audio-boosters-for-os-x-ios-android/"><u>[New] Elite 10 Audio Boosters for OS X, iOS, Android</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-expert-guide-to-leveraging-obs-in-android/"><u>[New] In 2024, Expert Guide to Leveraging OBS in Android</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-navigating-17-essential-steps-for-capturing-live-online-streams/"><u>[New] Navigating 17 Essential Steps for Capturing Live Online Streams</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-crafting-distinctive-video-stream-names-tips-for-filmora-users/"><u>[Updated] 2024 Approved Crafting Distinctive Video Stream Names Tips for Filmora Users</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-interpreting-the-functionality-behind-facebooks-blue-video-icon/"><u>[Updated] 2024 Approved Interpreting the Functionality Behind Facebook's Blue Video Icon</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-top-5-hidden-gems-to-watch-insta-stories-for-2024/"><u>[Updated] Top 5 Hidden Gems to Watch Insta Stories for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-list-of-8-best-free-and-paid-movie-apps-for-iphone/"><u>2024 Approved List of 8 Best Free and Paid Movie Apps for iPhone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-optimize-periscope-broadcasts-for-maximum-velocity/"><u>2024 Approved Optimize Periscope Broadcasts for Maximum Velocity</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-vivo-y100-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Vivo Y100 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-unsupported-apps-on-windows-vista/"><u>Dealing with Unsupported Apps on Windows Vista</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-file-handling-zipping-with-cli-tools-on-windows-os/"><u>Efficient File Handling: Zipping with CLI Tools on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empower-your-mouse-movements-with-global-friendly-powertoys/"><u>Empower Your Mouse Movements with Global-Friendly PowerToys</u></a></li>
<li><a href="https://techtrends.techidaily.com/essential-tags-for-enhanced-visibility-on-instagram/"><u>Essential #Tags for Enhanced Visibility on Instagram</u></a></li>
<li><a href="https://tech-hub.techidaily.com/from-browser-to-agents-agentgpts-efficiency-tutorial/"><u>From Browser to Agents: AgentGPT’s Efficiency Tutorial</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-samsung-galaxy-f04-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Samsung Galaxy F04 Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-text-messages-from-infinix-hot-30-5g-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Text Messages from Infinix Hot 30 5G to New Phone | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-free-location-spoofers-to-fake-gps-location-on-your-itel-s23plus-drfone-by-drfone-virtual/"><u>In 2024, 10 Free Location Spoofers to Fake GPS Location on your Itel S23+ | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-mastering-the-visuals-a-podcast-logo-blueprint/"><u>In 2024, Mastering the Visuals A Podcast Logo Blueprint</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-techniques-to-overcome-blackout-during-obs-fullscreen/"><u>In 2024, Techniques to Overcome Blackout During OBS Fullscreen</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unleash-creative-potential-a-detailed-breakdown-of-photoshops-background-eraser-feature/"><u>In 2024, Unleash Creative Potential A Detailed Breakdown of Photoshop's Background Eraser Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/new-horizons-essential-alterations-to-windows-11s-explorer/"><u>New Horizons: Essential Alterations to Windows 11'S Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-updater-issue-code-x80246007-on-win1011/"><u>Overcome Updater Issue Code X80246007 on WIn10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/returning-to-standard-windows-folder-layouts/"><u>Returning to Standard Windows Folder Layouts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-guide-modify-your-windows-security-pin/"><u>Simplified Guide: Modify Your Windows Security Pin</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skip-unverified-warning-in-adobe-software/"><u>Skip Unverified Warning in Adobe Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-weather-icon-integration-into-windows-11/"><u>Step-by-Step Guide: Weather Icon Integration Into Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-correcting-bluetooth-connection-failures-in-windows-11/"><u>Steps for Correcting Bluetooth Connection Failures in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-for-rectifying-inaccurate-malware-warning-in-chrome/"><u>Tactics for Rectifying Inaccurate Malware Warning in Chrome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-the-freeze-fix-for-non-opener-exe-files/"><u>Taming the Freeze: Fix for Non-Opener .exe Files</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/the-complete-playbook-for-instagram-revenue-generation-for-2024/"><u>The Complete Playbook for Instagram Revenue Generation for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-motorola-one-hyper-uncovered-a-potent-blend-of-value-and-vibrancy-in-a-mid-range-device/"><u>The Motorola One Hyper Uncovered: A Potent Blend of Value and Vibrancy in a Mid-Range Device</u></a></li>
<li><a href="https://some-techniques.techidaily.com/top-10-essential-cybersecurity-practices-endorsed-by-your-it-team/"><u>Top 10 Essential Cybersecurity Practices Endorsed by Your IT Team</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-unknown-errors-in-windows-1011/"><u>Troubleshooting Unknown Errors in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-off-windows-app-start-monitoring/"><u>Turn Off Windows App Start Monitoring</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-the-full-potential-of-your-windows-11-display/"><u>Unleash the Full Potential of Your Windows 11 Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-screen-sharing-issues-in-teammers/"><u>Unlock Screen Sharing Issues in Teammers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-full-capabilities-of-windows-11-key-adjustments-made-easy/"><u>Unlocking the Full Capabilities of Windows 11: Key Adjustments Made Easy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windowsstore-apps-entry-procedures/"><u>Unlocking WindowsStore Apps: Entry Procedures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-windows-self-scrolling/"><u>Unraveling the Mystery of Windows Self-Scrolling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windocs-remedying-missing-msvcr120dll-file-errors/"><u>WinDOCS: Remedying Missing Msvcr120.dll File Errors</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>