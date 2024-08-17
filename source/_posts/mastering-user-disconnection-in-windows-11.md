---
title: Mastering User Disconnection in Windows 11
date: 2024-08-16T02:20:35.227Z
updated: 2024-08-17T02:20:35.227Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering User Disconnection in Windows 11
excerpt: This Article Describes Mastering User Disconnection in Windows 11
keywords: Win11 Disconnect Mastery,Windows Severe Logout,UX Dropouts Control,Network Severance Guide,Sign-Out Efficiency Tips,Login Failure Solutions,User Detachment Techniques
thumbnail: https://thmb.techidaily.com/485101ae8f555e145174a15eda6071c25617b2b00c96089d339b8e4537366b75.jpg
---

## Mastering User Disconnection in Windows 11

### Quick Links

* [Sign Out Other Users Using the Task Manager](#sign-out-other-users-using-the-task-manager)
* [Sign Out Other Users Using the Command Prompt](#sign-out-other-users-using-the-command-prompt)
* [Log Off Other Users Using Process Explorer](#log-off-other-users-using-process-explorer)
* [Ask Other Users Before You Sign Them Out](#ask-other-users-before-you-sign-them-out)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
### Key Takeaways

* To sign out other users on Windows 11, you can use Task Manager, Command Prompt, or Process Explorer.
* The Task Manager method works on any version of Windows, while the Command Prompt option only works for Pro and above versions of Windows. Process Explorer requires a separate download.
* Be sure to consider any unsaved work before logging off a user.

 Each active user session on your PC means your computer's resources are shared with others, which can impact system performance. If someone is not actively using their session, you can log off the idle user from your account to reclaim those system resources.

## 1\. Sign Out Other Users Using the Task Manager

 The Task Manager's **Users** tab keeps track of all the user sessions active on your computer. You can use it to manage user accounts on Windows, switch between different user accounts, and sign off other user accounts. If you only need to [sign out of your current session on Windows 11](https://www.makeuseof.com/windows-11-how-to-sign-out/), the process is much simpler, though.

 You must be logged in as an administrator to sign off other user accounts; [check if your user account has administrator rights](https://www.makeuseof.com/check-windows-account-admin-rights/) if you're not sure. Importantly, when you sign out a user, the user's unsaved data might be lost. So tread carefully.

 To sign out other users using Task Manager:

1. Right-click on **Start** and select **Task Manager**. Alternatively, use the keyboard shortcut **Ctrl + Shift + Esc**.
2. In Task Manager, open the **Users** tab in the left pane which displays the number of users currently logged in. If not visible, click the **Open Navigation** button (three horizontal bars) in the top left corner.  
![Winx Menu Task Manager Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/winx-menu-task-manager-windows-11.png)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. In the **Users** tab, locate the account you want to sign off.
4. Right-click on the user account and select **Sign off**.  
![Users Tab in Task Manager with Logoff Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/users-tab-in-task-manager-with-logoff-option-in-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
5. Click **Sign out user**. Windows will close all the open apps and running processes and then log out the user.

## 2\. Sign Out Other Users Using the Command Prompt

 On Windows 11 Pro, Edu, and Enterprise editions, you can use Command Prompt's "query sessions" command to check and log off active user accounts. This command is unlikely to work on a Windows 11 Home, limiting your options.

 To sign out other users using Command Prompt:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**.
3. In the Command Prompt window, type the following command to view all the active user sessions with a query:  
`query session`
4. The output will show all the active user sessions on your computer. Make a note of the user account **ID** you want to sign out. In this instance, we have **Tashreef** as **1** and **Guest21** as **3** under the **ID** column.  
![Command Prompt With Query Session Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-query-session-command-running-on-windows-11.jpeg)
5. Type the following command to sign out the specified user. Replace **2** below with the user account ID you want to sign out:  
`Logoff 3`
6. Upon successful execution, Windows will sign out the specified user account.  
![Command Prompt With Logoff Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-logoff-command-running-on-windows-11.jpg)
7. Once done, type **exit** and press Enter to close the Command Prompt.

## 3\. Log Off Other Users Using Process Explorer

 Process Explorer is part of [Windows Sysinternal Tools, a suite of system administration utilities](http://www.makeuseof.com/windows-sysinternals-guide/) from Microsoft. Though the freeware is popular among developers and system admins, anyone can use Process Explorer to use some of its advanced features.

 Process Explorer is a powerful tool that maps all currently active processes and DLL files to the accounts running them. Our purpose is to show you how to use its user management feature to kick out other user sessions.

1. Go to Microsoft's official [Process Explorer page](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer) and download Process Exploreras a zip file to a location on your desktop.  
![Download Process Explorer Web Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/download-process-explorer-web-page.jpg)
2. Right-click on the **ProcessExplorer.zip** archive, and select **Extract All**. Select a location and extract the folder.  
![Process Explorer Exe File Run as Administrator Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-exe-file-run-as-administrator-option-in-windows-11.jpg)
3. Open the **ProcessExplorer** folder, right-click on **procexp64.exe**, and select **Run as administrator**.  
![Process Explorer App User Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-option-selected-in-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. In the **Process Explorer** window, click **Users** to view all the active user sessions.  
![Process Explorer App User Account Logoff Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-account-logoff-option-selected-in-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Hover your cursor over the user account name and select **Logoff**.

 Process Explorer will sign out the selected user account from your computer. If you get an [access denied error](https://www.makeuseof.com/windows-11-fix-access-denied-error/), run the procexp64.exe executable with administrator privileges and try again.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Ask Other Users Before You Sign Them Out

 When you log off other users, any unsaved work in their accounts is lost. So do consider that before you apply the above methods. Logging off from a Windows account in a multi-user PC is a good habit because it reduces the chance of data loss and frees up the computer's resources for others. Always request others to sign off when their work is finished.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-exploring-8-premium-open-source-videoconferencing-platforms-for-2024/"><u>[New] Exploring 8 Premium Open-Source Videoconferencing Platforms for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-unveiling-the-secrets-to-audio-visual-cohesion-on-facebook/"><u>[New] Unveiling the Secrets to Audio-Visual Cohesion on Facebook</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-blur-no-more-top-10-web-photo-sharpening-apps/"><u>[Updated] Blur No More! Top 10 Web Photo Sharpening Apps</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-crafting-content-masterpieces-select-the-ultimate-androidpc-apps/"><u>[Updated] In 2024, Crafting Content Masterpieces  Select the Ultimate Android/PC Apps</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-upgrade-your-content-creation-process-via-youtube-studio/"><u>[Updated] Upgrade Your Content Creation Process via YouTube Studio</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-copyright-aware-techniques-for-reposting-imagery/"><u>2024 Approved  Copyright-Aware Techniques for Reposting Imagery</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-realme-gt-5-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Realme GT 5 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augmenting-file-explorer-menus-with-auto-update-features/"><u>Augmenting File Explorer Menus with Auto-Update Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/break-free-from-operators-downloading-deadlock-in-windows/"><u>Break Free From Operator's Downloading Deadlock in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-xc0f1103f-issues-with-geforce-now-on-win11/"><u>Correcting Xc0f1103f Issues with GeForce Now on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/desktops-uncluttered-remove-win11s-spotlight-symbol/"><u>Desktops Uncluttered: Remove Win11's Spotlight Symbol</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/elevate-your-digital-marketing-strategy-with-nextgencookie-solutions-for-smarter-ppc-campaigns/"><u>Elevate Your Digital Marketing Strategy with NextGenCookie Solutions for Smarter PPC Campaigns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-the-gaming-experience-winning-strategies-for-ps1-and-windows-duckstations-guide/"><u>Elevating the Gaming Experience: Winning Strategies for PS1 and Windows - Duckstation's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-error-code-0x80300024-on-windows-xp/"><u>Eliminating Error Code: 0X80300024 on Windows XP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-secure-text-transfer-operation-steps-in-edges-shielded-environment-win11-version/"><u>Enabling Secure Text Transfer: Operation Steps in Edge's Shielded Environment, Win11 Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-wi-fi-management-with-win-11-tips/"><u>Enhance Your Wi-Fi Management with Win 11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-user-experience-by-fixing-menu-glitches/"><u>Enhancing User Experience by Fixing Menu Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-resolve-steam-video-hiccups/"><u>Essential Steps to Resolve Steam Video Hiccups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/executing-an-uncluttered-system-restart-in-windows-11-guide/"><u>Executing an Uncluttered System Restart in Windows 11: Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-installed-optional-windows-functions-a-7-step-guide/"><u>Fixing Non-Installed Optional Windows Functions: A 7-Step Guide</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-choosing-streaming-giants-vimeo-youtube-or-dailymotion/"><u>In 2024, Choosing Streaming Giants  Vimeo, YouTube, or DailyMotion?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-perfect-blend-of-efficiency-and-artistry-in-apple-photography-apps/"><u>In 2024, The Perfect Blend of Efficiency and Artistry in Apple Photography Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-windows-local-space-management-tips-no-file-removal-max-156-chars/"><u>Innovative Windows Local Space Management Tips (No File Removal) (Max 156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/joining-forces-onedrive-and-windows-live-account-sync/"><u>Joining Forces: OneDrive & Windows Live Account Sync</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launch-in-pc-no-fee-clone-of-chatgpt-on-windows/"><u>Launch In-PC, No-Fee Clone of ChatGPT on Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-game-pass-access-restoration-in-win-oses/"><u>Mastering Game Pass Access Restoration in Win OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-updater-failures-0xca00a009/"><u>Mastering the Art of Fixing Updater Failures #0xCA00A009</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-shortcuts-for-microsoft-store-uwp/"><u>Mastering Windows Shortcuts for Microsoft Store UWP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multiplying-malware-defenses-think-again-windows/"><u>Multiplying Malware Defenses? Think Again, Windows!</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-giants-of-social-platforms-twitter-facebook-insta-and-yt/"><u>Navigating the Giants of Social Platforms: Twitter, Facebook, Insta & YT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/onedrive-repositioning-in-the-windows-11-environment/"><u>OneDrive Repositioning in the Windows 11 Environment</u></a></li>
<li><a href="https://extra-tips.techidaily.com/pushing-the-boundaries-of-fb-video-speed/"><u>Pushing the Boundaries of FB Video Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-correcting-ipad-picture-importer-mishaps-in-windows/"><u>Quick Guide: Correcting iPad Picture Importer Mishaps in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-remedies-for-non-functional-windows-alt-codes-49-characters/"><u>Quick Remedies for Non-Functional Windows Alt Codes (49 Characters)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-camera-not-detected-error-on-win11/"><u>Remedy for “Camera Not Detected” Error on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-to-amd-gpu-software-on-pcs/"><u>Restoring Functionality to AMD GPU Software on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-icon-alignment-in-windows-10/"><u>Simplify Icon Alignment in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-isdonedll-complications-quickly/"><u>Solving Windows ISDone.dll Complications Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-non-responsive-services-on-windows-pcs/"><u>Steps to Rectify Non-Responsive Services on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-address-microsoft-store-error-0x80073cf3/"><u>Strategies to Address Microsoft Store Error 0X80073cf3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-copy-pasting-predefined-text-with-windows-11-hotkeys/"><u>Streamline Copy-Pasting Predefined Text with Windows 11 Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-non-start-troubles-in-csgo-and-w11/"><u>Tackling Non-Start Troubles in CS:GO & W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-resolving-microsoft-store-error-on-windows-devices/"><u>Tips for Resolving Microsoft Store Error on Windows Devices</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/transform-your-instagram-reels-into-high-quality-mp4-files-anywhere/"><u>Transform Your Instagram Reels Into High-Quality MP4 Files Anywhere</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-shortcut-tactics-for-optimal-voice-input-on-win-11/"><u>Ultimate Shortcut Tactics for Optimal Voice Input on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-upgrade-error-xc004f050-code/"><u>Unblocking Windows Upgrade Error Xc004f050 Code</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-mystery-of-windows-1011-failed-app-start/"><u>Unveiling the Mystery of Windows 10/11 Failed App Start</u></a></li>
</ul></div>
