---
title: How to Sign Out Other Users on Windows 11
date: 2024-11-04T22:02:42.047Z
updated: 2024-11-07T06:09:31.615Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Sign Out Other Users on Windows 11
excerpt: This Article Describes How to Sign Out Other Users on Windows 11
keywords: Windows Logout Others,Signing Off Users PC,Windows User Exit Guide,Unauthorized Account End,Windows 11 Unsign Out,Remove Other Windows Login,Windows 11 Secure Exit
thumbnail: https://thmb.techidaily.com/b707c0511382e78c7bbc2631c8c2ac749bfdb8b7dcef137c48ff3983d7a66e67.jpg
---

## How to Sign Out Other Users on Windows 11

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115951/19272" target="_top" id="2115951">
  <img src="//a.impactradius-go.com/display-ad/19272-2115951" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115951/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Right-click on the user account and select **Sign off**.  
![Users Tab in Task Manager with Logoff Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/users-tab-in-task-manager-with-logoff-option-in-windows-11.jpg)
5. Click **Sign out user**. Windows will close all the open apps and running processes and then log out the user.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137212/26400" target="_top" id="2137212">
  <img src="//a.impactradius-go.com/display-ad/26400-2137212" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137212/26400" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<span id="1444782">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1444782.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1444782">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1444782.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1444782%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1444782/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Process Explorer Exe File Run as Administrator Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-exe-file-run-as-administrator-option-in-windows-11.jpg)
3. Open the **ProcessExplorer** folder, right-click on **procexp64.exe**, and select **Run as administrator**.  

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005183/22899" target="_top" id="2005183">
  <img src="//a.impactradius-go.com/display-ad/22899-2005183" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005183/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Process Explorer App User Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-option-selected-in-windows-11.jpg)
4. In the **Process Explorer** window, click **Users** to view all the active user sessions.  
![Process Explorer App User Account Logoff Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-account-logoff-option-selected-in-windows-11.jpg)
5. Hover your cursor over the user account name and select **Logoff**.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134497/18498" target="_top" id="2134497">
  <img src="//a.impactradius-go.com/display-ad/18498-2134497" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134497/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://snapchat-videos.techidaily.com/new-dive-into-the-past-with-your-camera-roll-and-snapchat/"><u>[New] Dive Into the Past with Your Camera Roll and Snapchat</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-how-to-buy-1-million-youtube-views-safely-from-trusted-providers/"><u>[Updated] How to Buy 1 Million YouTube Views Safely From Trusted Providers</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-top-8-facebook-movie-downloaders/"><u>[Updated] In 2024, Top 8 Facebook Movie Downloaders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteract-companionless-clicking-audio-restoration-for-pc/"><u>Counteract Companionless Clicking: Audio Restoration for PC</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/diagnosing-and-repairing-windows-10-bad-pool-headers-that-trigger-blue-screen-of-death-errors-expert-tips/"><u>Diagnosing & Repairing Windows 10 'Bad Pool Headers' That Trigger Blue Screen of Death Errors: Expert Tips</u></a></li>
<li><a href="https://vp-tips.techidaily.com/effortless-audio-file-exchange-upload-your-m4a-and-download-as-ogg-without-cost/"><u>Effortless Audio File Exchange - Upload Your M4A and Download as Ogg without Cost</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-browser-efficiency-youtube-stream-optimization/"><u>Enhancing Browser Efficiency: YouTube Stream Optimization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-to-hidden-widgets-on-windows-systems/"><u>Expert Guide to Hidden Widgets on Windows Systems</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-digital-asset-management-implementing-watermarks-on-instagram/"><u>In 2024, Digital Asset Management Implementing Watermarks on Instagram</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-motorola-moto-g34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Motorola Moto G34 5G? | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-tap-into-the-latest-gaming-and-app-splash-of-win11/"><u>In 2024, Tap Into the Latest Gaming and App Splash of Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-restart-rituals-decoding-windows-eight-steps/"><u>Masterful Restart Rituals: Decoding Windows' Eight Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-win11s-package-handling-using-wingetui-tools/"><u>Optimize Win11's Package Handling Using WingetUI Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-resourceerror-display-of-text-in-windows-11/"><u>Overcoming ResourceError: Display of Text in Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-samsung-galaxy-f34-5g-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Samsung Galaxy F34 5G to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-expires-shortly-alert-in-windows-11/"><u>Resolving Windows Expires Shortly Alert in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-resolve-onedrive-glitches-on-win-10-and-11/"><u>Strategies to Resolve OneDrive Glitches on Win 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-0x8007045d-win11-crash-a-practical-approach/"><u>Tackling the 0X8007045D Win11 Crash: A Practical Approach</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-10-oppo-a1x-5g-android-sim-unlock-apk-by-drfone-android/"><u>Top 10 Oppo A1x 5G Android SIM Unlock APK</u></a></li>
</ul></div>

