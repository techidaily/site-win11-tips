---
title: "Naming Conventions: Editing Windows 11 User Folders"
date: 2024-08-23T07:02:16.120Z
updated: 2024-08-24T07:02:16.120Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Naming Conventions: Editing Windows 11 User Folders"
excerpt: "This Article Describes Naming Conventions: Editing Windows 11 User Folders"
keywords: Win11 User Naming,Windows Naming Rules,File Folder Conventions,OS User Directory,Windows System Naming,Editing Folders Window,W11 User Folder Guide
thumbnail: https://thmb.techidaily.com/f8310fb64fe59131a1a603b74493ef91ec9be3bf91a44a7ee26654a9f6fff3c0.jpg
---

## Naming Conventions: Editing Windows 11 User Folders

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
1. Click on **Add a user** **without a Microsoft account.**
2. Type a name for the user account. Leave the password field empty and click **Next**.
3. Click on the new user account and click **Change account type.**
4. Click the drop-down for **Account type** and select **Administrator**.
5. Click **OK** to save the changes.

 Now, you can log in with your new administrator account. To do this, click **Start**, then click on the user profile name, and select **Sign out.** Next, sign in with the new administrator account.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
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
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Next, open the Command Prompt. To do this, press **Win + R,** type **cmd,** and click **OK**.  
![SID command prompt user account.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/SID-command-prompt-user-account.png)
4. In the Command Prompt window, type the following command to view **SID (Security Identifier)** for all user accounts:  
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
![add new name profile image path registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/add-new-name-profile-image-path-registry-editor.png)
6. Close the Registry Editor and Command Prompt window if open.
<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://buynow-tips.techidaily.com/plants-vs-zombies-battle-for-neighborville-hilarious-combat-action-reviewed/"><u>'Plants Vs. Zombies: Battle for Neighborville': Hilarious Combat Action Reviewed!</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-rhythmic-reinvention-the-art-of-voice-in-free-fire/"><u>[New] 2024 Approved  Rhythmic Reinvention  The Art of Voice in Free Fire</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-best-in-class-top-drone-gimbals-compared-for-2024/"><u>[New] Best in Class  Top Drone Gimbals Compared for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-deciphering-fb-mystery-vanishing-youtubefacebook-videos-for-2024/"><u>[New] Deciphering FB Mystery  Vanishing YouTube/Facebook Videos for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-fast-tip-mastering-green-screen-techniques/"><u>[New] In 2024, Fast Tip  Mastering Green Screen Techniques</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-ultimate-guide-new-camera-recording-tech-overview-for-2024/"><u>[New] Ultimate Guide  New Camera Recording Tech Overview for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-avoid-unsolicited-podcast-selections-by-spotify/"><u>2024 Approved  Avoid Unsolicited Podcast Selections by Spotify</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/connective-horizons-proven-methods-for-intercultural-conversation/"><u>Connective Horizons: Proven Methods for Intercultural Conversation</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/content-compromise-rapid-deletion-dilemma/"><u>Content Compromise  Rapid Deletion Dilemma</u></a></li>
<li><a href="https://win11-tips.techidaily.com/darkthemetogglefornotepadw10w11/"><u>DarkThemeToggleForNotepadW10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-keystroke-pace-with-typingaid-techniques/"><u>Elevate Keystroke Pace with TypingAid Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhanced-workflow-smartly-add-app-buttons-in-win11-interface/"><u>Enhanced Workflow: Smartly Add App Buttons in Win11 Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-pc-connectivity-using-android-phones-in-windows-11/"><u>Enhancing PC Connectivity: Using Android Phones in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-the-windows-11-entry-point-top-strategies-revealed/"><u>Enhancing the Windows 11 Entry Point: Top Strategies Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/enrich-your-windows-setup-with-personal-menus/"><u>Enrich Your Windows Setup with Personal Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-win-tricks-to-monitor-full-batteries/"><u>Expert Win Tricks to Monitor Full Batteries</u></a></li>
<li><a href="https://win11-tips.techidaily.com/file-time-facelift-top-windows-programs-for-date-tweaking/"><u>File Time Facelift: Top Windows Programs for Date Tweaking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/first-steps-with-windows-canary-channel-for-security/"><u>First Steps with Windows Canary Channel for Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-blank-slate-to-masterpiece-windows-11-desk-drawing-guide/"><u>From Blank Slate to Masterpiece: Windows 11 Desk Drawing Guide</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-google-frp-on-vivo-v29e-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass Google FRP on Vivo V29e</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-change-your-apple-id-on-iphone-12-mini-with-or-without-password-by-drfone-ios/"><u>How To Change Your Apple ID on iPhone 12 mini With or Without Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disable-driver-signature-enforcement-and-install-unsigned-drivers-on-windows/"><u>How to Disable Driver Signature Enforcement and Install Unsigned Drivers on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-optimize-gaming-experience-for-fullscreen/"><u>How to Optimize Gaming Experience for Fullscreen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-the-netstat-command-in-windows-11-to-monitor-network-activity/"><u>How to Use the Netstat Command in Windows 11 to Monitor Network Activity</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-essential-techniques-for-logitech-webcam-videos/"><u>In 2024, Essential Techniques for Logitech Webcam Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/installing-official-windows-os-on-steam-deck/"><u>Installing Official Windows OS on Steam Deck</u></a></li>
<li><a href="https://review-topics.techidaily.com/iphone-6-data-recovery-software-to-recover-lost-ios-data-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>iPhone 6® Data Recovery Software to Recover Lost iOS® Data | Stellar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-heat-efficiency-in-your-windows-11-computer/"><u>Managing Heat Efficiency in Your Windows 11 Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-silence-on-windows-11-shut-down-tabs/"><u>Master Silence on Windows 11: Shut Down Tabs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-efficiency-edgedownloads-and-process-management/"><u>Mastering Efficiency: Edgedownloads & Process Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-multi-device-compatibility-for-win11-notes/"><u>Mastering Multi-Device Compatibility for WIN11 Notes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-image-size-on-windows-11-explore-the-best-techniques/"><u>Optimize Image Size on Windows 11: Explore the Best Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-linux-experience-via-windows-resources/"><u>Optimizing Linux Experience via Windows Resources</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-access-denied-on-nvidia-control-panel-in-win1110/"><u>Overcoming Access Denied on Nvidia Control Panel in Win11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-paths-initiating-windows-self-repair/"><u>Quick Paths: Initiating Windows' Self-Repair</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quickly-enable-hyper-v-in-the-latest-windows-11/"><u>Quickly Enable Hyper-V in the Latest Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-speech-to-text-conversion-in-ms-office-suite-word/"><u>Restoring Speech to Text Conversion in MS Office Suite (Word)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-uninstalling-older-windows-oses-causing-errors/"><u>Solutions for Uninstalling Older Windows OSes Causing Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-regain-control-of-your-windows-enter-input/"><u>Steps to Regain Control of Your Windows 'Enter' Input</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-stabilization-nine-fixes-for-wwe-2k23-on-windows-11/"><u>Swift Stabilization: Nine Fixes for WWE 2K23 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-no-permission-saves-error-windows-wise/"><u>Tackling No Permission Saves Error Windows-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-digital-environment-with-folder-tags-in-explorer/"><u>Tailoring Your Digital Environment with Folder Tags in Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-best-nintendo-switch-emulators-for-windows/"><u>The Best Nintendo Switch Emulators for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-routes-to-mastering-win-policy-rules/"><u>The Ultimate Routes to Mastering Win Policy Rules</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-lava-blaze-2-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Lava Blaze 2? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-missing-text-display-on-pc-discord/"><u>Troubleshooting Missing Text Display on PC Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-info-a-direct-approach/"><u>Unveiling Windows Info: A Direct Approach</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>