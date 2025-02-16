---
title: Steps for Ending Others' Session in Windows 11
date: 2025-02-13T16:56:03.720Z
updated: 2025-02-15T21:51:58.120Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hXIq2G0nShk?si=5Z4Fwv7ZB6oKWsdd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
3. In the **Users** tab, locate the account you want to sign off.

4. Right-click on the user account and select **Sign off**.  
![Users Tab in Task Manager with Logoff Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/users-tab-in-task-manager-with-logoff-option-in-windows-11.jpg)
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/o-sRtqHdEYY?si=NMTMQVxJsUaoguqh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`Logoff 3`
6. Upon successful execution, Windows will sign out the specified user account.  
![Command Prompt With Logoff Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-logoff-command-running-on-windows-11.jpg)
7. Once done, type **exit** and press Enter to close the Command Prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Process Explorer App User Account Logoff Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-account-logoff-option-selected-in-windows-11.jpg)
5. Hover your cursor over the user account name and select **Logoff**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-lab.techidaily.com/esigning-dynamic-denouements/"><u>[New] Designing Dynamic Denouements</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-6-free-youtube-outros-for-aspiring-filmmakers/"><u>[New] In 2024, 6 FREE YouTube Outros for Aspiring Filmmakers</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-heartfelt-cheers-access-to-free-and-paid-otu-ideas/"><u>[Updated] 2024 Approved Heartfelt Cheers Access to Free & Paid OTU Ideas</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-post-a-highlight-from-the-latest-audio-show/"><u>[Updated] Post a Highlight From the Latest Audio Show</u></a></li>
<li><a href="https://win-marvelous.techidaily.com/vmwarewindows-os/"><u>物理マシンから仮想マシンへ: VMwareでWindows OSを移行するガイド</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-tecno-spark-10-4g-drfone-by-drfone-virtual-android/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Tecno Spark 10 4G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-coding-repair-x-script-in-ragnarok/"><u>Conquer Coding: Repair X-Script in Ragnarok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-key-differences-between-exe-software-packages-and-msi/"><u>Deciphering Key Differences Between Exe Software Packages & Msi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-ssd-optimize-with-ssd-fresh-for-windows-users/"><u>Enhance Your SSD: Optimize with SSD Fresh for Windows Users</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-activation-lock-and-icloud-account-on-iphone-15-by-drfone-ios/"><u>How to Unlock iCloud Activation Lock and iCloud Account On iPhone 15?</u></a></li>
<li><a href="https://extra-tips.techidaily.com/infinity-series-ultra-hd-single-touch-display/"><u>Infinity Series – Ultra HD, Single Touch Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-focus-with-our-select-8-windows-pomodoro-tools/"><u>Maximize Focus with Our Select 8 Windows Pomodoro Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-window-whisperer-decoding-and-fixing-windows-11-screen-issues/"><u>The Window Whisperer: Decoding and Fixing Windows 11 Screen Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-removing-windows-bt-directories-effectively/"><u>Understanding and Removing Windows ~BT Directories Effectively</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unlock-humor-pay-nothing-easymeme-tools-guide/"><u>Unlock Humor, Pay Nothing EasyMeme Tools Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-hidden-steps-to-fullscreen-integrity/"><u>Unveiling Hidden Steps to Fullscreen Integrity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-reset-reclaim-default-user-access-rights/"><u>Windows 11 Reset: Reclaim Default User Access Rights</u></a></li>
</ul></div>

