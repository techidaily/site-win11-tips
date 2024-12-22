---
title: Steps for Ending Others' Session in Windows 11
date: 2024-12-21T06:52:40.026Z
updated: 2024-12-22T09:57:35.840Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps for Ending Others' Session in Windows 11
excerpt: This Article Describes Steps for Ending Others' Session in Windows 11
keywords: Windows 11 Session Termination,Lock Windows Login,Unauthorized Access Blockage,Secure PC Windows,End User Sessions Win11,Disconnect Others' Window,Prevent Session Hijacking
thumbnail: https://thmb.techidaily.com/7e53aeacfe9180f7bf103bd851c0952fea27590b967ba6821cf8991af471fa5a.jpg
---

## Steps for Ending Others' Session in Windows 11

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Quick Links

* [Sign Out Other Users Using the Task Manager](#sign-out-other-users-using-the-task-manager)
* [Sign Out Other Users Using the Command Prompt](#sign-out-other-users-using-the-command-prompt)
* [Log Off Other Users Using Process Explorer](#log-off-other-users-using-process-explorer)
* [Ask Other Users Before You Sign Them Out](#ask-other-users-before-you-sign-them-out)

### Key Takeaways

* To sign out other users on Windows 11, you can use Task Manager, Command Prompt, or Process Explorer.
* The Task Manager method works on any version of Windows, while the Command Prompt option only works for Pro and above versions of Windows. Process Explorer requires a separate download.
* Be sure to consider any unsaved work before logging off a user.

 Each active user session on your PC means your computer's resources are shared with others, which can impact system performance. If someone is not actively using their session, you can log off the idle user from your account to reclaim those system resources.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Sign Out Other Users Using the Task Manager

 The Task Manager's **Users** tab keeps track of all the user sessions active on your computer. You can use it to manage user accounts on Windows, switch between different user accounts, and sign off other user accounts. If you only need to [sign out of your current session on Windows 11](https://www.makeuseof.com/windows-11-how-to-sign-out/), the process is much simpler, though.

 You must be logged in as an administrator to sign off other user accounts; [check if your user account has administrator rights](https://www.makeuseof.com/check-windows-account-admin-rights/) if you're not sure. Importantly, when you sign out a user, the user's unsaved data might be lost. So tread carefully.

 To sign out other users using Task Manager:

1. Right-click on **Start** and select **Task Manager**. Alternatively, use the keyboard shortcut **Ctrl + Shift + Esc**.
2. In Task Manager, open the **Users** tab in the left pane which displays the number of users currently logged in. If not visible, click the **Open Navigation** button (three horizontal bars) in the top left corner.  
![Winx Menu Task Manager Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/winx-menu-task-manager-windows-11.png)
3. In the **Users** tab, locate the account you want to sign off.
4. Right-click on the user account and select **Sign off**.  
![Users Tab in Task Manager with Logoff Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/users-tab-in-task-manager-with-logoff-option-in-windows-11.jpg)
5. Click **Sign out user**. Windows will close all the open apps and running processes and then log out the user.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RCYs8keh-Vs?si=uDC28-9yh-k6HLj4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Process Explorer App User Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-option-selected-in-windows-11.jpg)
4. In the **Process Explorer** window, click **Users** to view all the active user sessions.  
![Process Explorer App User Account Logoff Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-account-logoff-option-selected-in-windows-11.jpg)
5. Hover your cursor over the user account name and select **Logoff**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Process Explorer will sign out the selected user account from your computer. If you get an [access denied error](https://www.makeuseof.com/windows-11-fix-access-denied-error/), run the procexp64.exe executable with administrator privileges and try again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Ask Other Users Before You Sign Them Out

 When you log off other users, any unsaved work in their accounts is lost. So do consider that before you apply the above methods. Logging off from a Windows account in a multi-user PC is a good habit because it reduces the chance of data loss and frees up the computer's resources for others. Always request others to sign off when their work is finished.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-optimal-transfer-methods-iphone-camera-roll-to-snapchat-journey/"><u>[New] 2024 Approved Optimal Transfer Methods IPhone Camera Roll to Snapchat Journey</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-cutting-edge-editing-advanced-strategies-for-using-the-background-erase-feature/"><u>[New] Cutting Edge Editing Advanced Strategies for Using the Background Erase Feature</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-the-essential-2023-social-media-video-exploration/"><u>[New] In 2024, The Essential 2023 Social Media Video Exploration</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-top-mac-studio-with-state-of-the-art-screen-and-voice-logging-for-2024/"><u>[New] Top Mac Studio with State-of-the-Art Screen and Voice Logging for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-unveiling-the-best-tools-to-download-your-favorite-fb-videos-on-firefox-updated-for-2024/"><u>[New] Unveiling the Best Tools to Download Your Favorite FB Videos on FireFox, Updated for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-ideal-timing-aids-the-best-clock-apps-for-your-big-day-for-2024/"><u>[Updated] Ideal Timing Aids The Best Clock Apps For Your Big Day for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dispatching-opengl-problem-code-3-on-nvidia-windows/"><u>Dispatching OpenGL Problem Code 3 on Nvidia, Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-transition-powertoys-in-your-win11-pc/"><u>Effortless Transition: PowerToys in Your Win11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-share-error-messages-with-nvidias-gui/"><u>Eliminating Share Error Messages with NVIDIA’s GUI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-flaky-snipshot-commands-on-pc/"><u>Enabling Flaky Snipshot Commands on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-ignoring-invalid-security-notices-from-chrome-browser/"><u>Guide: Ignoring Invalid Security Notices From Chrome Browser</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-supercharge-system-controls-running-task-manager-admin-wise-on-win11/"><u>How to Supercharge System Controls: Running Task Manager Admin-Wise on Win11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/prolific-photography-and-video-app-selection-iphone-vs-android-for-2024/"><u>Prolific Photography & Video App Selection IPhone vs Android for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/quick-reference-guide-to-mastering-mobizens-screen-recording-tech-for-2024/"><u>Quick Reference Guide to Mastering Mobizen's Screen Recording Tech for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revisit-the-classics-enhancing-games-with-retroarchs-shaders/"><u>Revisit the Classics: Enhancing Games with RetroArch’s Shaders</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-the-ultimate-compilation-of-costless-peak-quality-audio-apps-for-ios-and-android/"><u>Updated 2024 Approved The Ultimate Compilation of Costless, Peak-Quality Audio Apps for iOS and Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/whats-behind-win32keygen-understanding-its-effect-on-pc-safety/"><u>What's Behind Win32/Keygen? Understanding Its Effect on PC Safety</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    