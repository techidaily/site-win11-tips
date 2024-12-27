---
title: Steps for Ending Others' Session in Windows 11
date: 2024-12-26T19:14:34.444Z
updated: 2024-12-27T18:28:58.836Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/g6xXIR_Uh1A?si=TMXzklPEY50MUM05" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Log Off Other Users Using Process Explorer

 Process Explorer is part of [Windows Sysinternal Tools, a suite of system administration utilities](http://www.makeuseof.com/windows-sysinternals-guide/) from Microsoft. Though the freeware is popular among developers and system admins, anyone can use Process Explorer to use some of its advanced features.

 Process Explorer is a powerful tool that maps all currently active processes and DLL files to the accounts running them. Our purpose is to show you how to use its user management feature to kick out other user sessions.

1. Go to Microsoft's official [Process Explorer page](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer) and download Process Exploreras a zip file to a location on your desktop.  
![Download Process Explorer Web Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/download-process-explorer-web-page.jpg)
2. Right-click on the **ProcessExplorer.zip** archive, and select **Extract All**. Select a location and extract the folder.  
![Process Explorer Exe File Run as Administrator Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-exe-file-run-as-administrator-option-in-windows-11.jpg)
3. Open the **ProcessExplorer** folder, right-click on **procexp64.exe**, and select **Run as administrator**.  

![Process Explorer App User Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-option-selected-in-windows-11.jpg)
4. In the **Process Explorer** window, click **Users** to view all the active user sessions.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HaM818fFKXQ?si=ZZLA4lFSHSgCpSE0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Process Explorer App User Account Logoff Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-account-logoff-option-selected-in-windows-11.jpg)
5. Hover your cursor over the user account name and select **Logoff**.

 Process Explorer will sign out the selected user account from your computer. If you get an [access denied error](https://www.makeuseof.com/windows-11-fix-access-denied-error/), run the procexp64.exe executable with administrator privileges and try again.

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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-beef-up-your-cgi-with-these-8-online-repositories-of-free-green-screens-and-clips/"><u>[New] 2024 Approved Beef up Your CGI with These 8 Online Repositories of FREE Green Screens and Clips</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-building-a-brand-on-fb-covers-that-speak-volumes/"><u>[New] In 2024, Building a Brand on FB Covers that Speak Volumes</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-the-nights-reign-black-vs-the-dawns-duty-silver/"><u>[New] The Night's Reign (Black) VS The Dawn’s Duty (Silver)</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-free-video-conferencing-excellence-plus-screen-sharing-guide-for-2024/"><u>[Updated] Free Video Conferencing Excellence + Screen Sharing Guide for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-mastering-iphones-voice-memo-functionality-for-2024/"><u>[Updated] Mastering iPhone's Voice Memo Functionality for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-flex-your-viewing-muscles-handling-multiple-youtube-videos/"><u>2024 Approved Flex Your Viewing Muscles Handling Multiple YouTube Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-your-day-with-these-best-6-windows-11-to-do-applications/"><u>Conquer Your Day with These Best 6 Windows 11 To-Do Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-internal-pc-keys-in-the-microsoft-ecosystem/"><u>Disabling Internal PC Keys in the Microsoft Ecosystem</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-installation-guide-corsair-k70-mouse-drivers-and-software/"><u>Download and Installation Guide: Corsair K70 Mouse Drivers & Software</u></a></li>
<li><a href="https://discover-docs.techidaily.com/easy-file-relocation-techniques-for-windows-users-by-yl-software-move-between-external-and-internal-drives-without-hitches/"><u>Easy File Relocation Techniques for Windows Users by YL Software: Move Between External and Internal Drives Without Hitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-network-analysis-win-ipandmac-via-powershell/"><u>Enhancing Network Analysis: Win IP&MAC via PowerShell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-functionality-repair-intel-unison-in-win11/"><u>Ensuring Functionality: Repair Intel Unison in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leverage-powertoys-for-swift-typing-in-windows/"><u>Leverage PowerToys for Swift Typing in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-policy-bypass-during-windows-installation-issues/"><u>Mastering Policy Bypass During Windows Installation Issues</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/solutions-to-spy-on-apple-iphone-se-2022-with-and-without-jailbreak-drfone-by-drfone-virtual-ios/"><u>Solutions to Spy on Apple iPhone SE (2022) with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-icon-position-restoration/"><u>Techniques for Icon Position Restoration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-best-windows-way-to-enjoy-classic-quests-in-ultra-hd-via-scummvm/"><u>The Best Windows Way to Enjoy Classic Quests in Ultra-HD via ScummVM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trigger-quick-support-functionality-windows-11-guide/"><u>Trigger Quick Support Functionality: Windows 11 Guide</u></a></li>
<li><a href="https://some-skills.techidaily.com/unlocking-nearby-nuggets-your-essential-locale-lens-for-a-smoother-journey-for-2024/"><u>Unlocking Nearby Nuggets Your Essential Locale Lens for a Smoother Journey for 2024</u></a></li>
</ul></div>

