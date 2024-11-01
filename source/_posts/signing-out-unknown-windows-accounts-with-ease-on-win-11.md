---
title: Signing Out Unknown Windows Accounts with Ease on Win 11
date: 2024-10-29T16:51:51.214Z
updated: 2024-11-01T18:14:56.189Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Signing Out Unknown Windows Accounts with Ease on Win 11
excerpt: This Article Describes Signing Out Unknown Windows Accounts with Ease on Win 11
keywords: Easy Unknown Account Exit,Win 11 Sign-Out Process,Remove Wins Unauthorized Access,Secure Windows Account Deactivation,Prevent Unseen Login Sessions,Win 11 Effortless User Logout,Manage Privileged Users Safely
thumbnail: https://thmb.techidaily.com/ceeb71131f67470128687850a84b0078790624844b7b52caccd45c8365ecdd85.jpg
---

## Signing Out Unknown Windows Accounts with Ease on Win 11

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
<a href="https://25home.pxf.io/c/5597632/2148633/16836" target="_top" id="2148633">
  <img src="//a.impactradius-go.com/display-ad/16836-2148633" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148633/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

* To sign out other users on Windows 11, you can use Task Manager, Command Prompt, or Process Explorer.
* The Task Manager method works on any version of Windows, while the Command Prompt option only works for Pro and above versions of Windows. Process Explorer requires a separate download.
* Be sure to consider any unsaved work before logging off a user.

 Each active user session on your PC means your computer's resources are shared with others, which can impact system performance. If someone is not actively using their session, you can log off the idle user from your account to reclaim those system resources.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135405/19272" target="_top" id="2135405">
  <img src="//a.impactradius-go.com/display-ad/19272-2135405" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135405/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126492/26400" target="_top" id="2126492">
  <img src="//a.impactradius-go.com/display-ad/26400-2126492" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126492/26400" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880956/19272" target="_top" id="1880956">
  <img src="//a.impactradius-go.com/display-ad/19272-1880956" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880956/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398455/3022" target="_top" id="398455">
  <img src="//a.impactradius-go.com/display-ad/3022-398455" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398455/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Process Explorer Exe File Run as Administrator Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-exe-file-run-as-administrator-option-in-windows-11.jpg)
3. Open the **ProcessExplorer** folder, right-click on **procexp64.exe**, and select **Run as administrator**.  
![Process Explorer App User Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-option-selected-in-windows-11.jpg)
4. In the **Process Explorer** window, click **Users** to view all the active user sessions.  
![Process Explorer App User Account Logoff Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-account-logoff-option-selected-in-windows-11.jpg)
5. Hover your cursor over the user account name and select **Logoff**.

 Process Explorer will sign out the selected user account from your computer. If you get an [access denied error](https://www.makeuseof.com/windows-11-fix-access-denied-error/), run the procexp64.exe executable with administrator privileges and try again.

## Ask Other Users Before You Sign Them Out

 When you log off other users, any unsaved work in their accounts is lost. So do consider that before you apply the above methods. Logging off from a Windows account in a multi-user PC is a good habit because it reduces the chance of data loss and frees up the computer's resources for others. Always request others to sign off when their work is finished.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-files.techidaily.com/new-non-standard-windows-media-development-tools-for-2024/"><u>[New] Non-Standard Windows Media Development Tools for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-quench-your-relaxation-aspertronics-guide/"><u>[Updated] 2024 Approved Quench Your Relaxation Aspertronics Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1-mastering-icon-hiding-on-video-three-effective-methods-to-keep-your-brand-intact/"><u>1. Mastering Icon Hiding on Video: Three Effective Methods to Keep Your Brand Intact</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726225811433-mp2-mp4-movavi/"><u>線上自由MP2 MP4轉換服務 - 利用Movavi便捷格式修改</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-pictures-from-oppo-k11-5g-by-fonelab-android-recover-pictures/"><u>Best Android Data Recovery - Retrieve Lost Pictures from Oppo K11 5G.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/copiar-e-colar-em-videos-no-formato-f4v-ferramenta-on-line-gratuitaria-do-movavi/"><u>Cópiar E Colar Em Vídeos No Formato F4V - Ferramenta On-Line Gratuitária Do Movavi</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ffpm-demystified-your-guide-to-multi-tasking/"><u>FFPM Demystified Your Guide to Multi-Tasking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavimp3-swfmp3/"><u>MovaviのフリーオンラインMP3変換ツール - SWFから直接MP3に!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/png-or-jpg-a-detailed-comparison-for-optimal-image-resolution-and-quality/"><u>PNG or JPG: A Detailed Comparison for Optimal Image Resolution and Quality.</u></a></li>
<li><a href="https://extra-information.techidaily.com/premier-top-eight-for-unparalleled-4k-viewing/"><u>Premier Top Eight for Unparalleled 4K Viewing</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-installation-problems-in-windows-store/"><u>Remedying Installation Problems in Windows Store</u></a></li>
<li><a href="https://facebook.techidaily.com/safeguard-against-unknown-users-in-your-tech-world/"><u>Safeguard Against Unknown Users in Your Tech World</u></a></li>
<li><a href="https://fox-direct.techidaily.com/top-drone-picks-available-now/"><u>Top Drone Picks Available Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trasforma-i-tuoi-video-in-gif-animate-con-facilita-scopri-le-top-10-tecniche-di-movavi/"><u>Trasforma I Tuoi Video in Gif Animate Con Facilità: Scopri Le Top 10 Tecniche Di Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-fixing-non-hdcp-compliant-monitor-displays/"><u>Troubleshooting: Fixing Non-HDCP Compliant Monitor Displays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726227481489-wavmp3-movavi/"><u>WAVファイルから効率的なMP3への変換テクニック - Movaviオンラインツールをご利用ください🔊</u></a></li>
<li><a href="https://win11-tips.techidaily.com/webppngmovavimobile/"><u>WebP画像からPNGへの高効率変換手順【Movavi・Mobile】</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    