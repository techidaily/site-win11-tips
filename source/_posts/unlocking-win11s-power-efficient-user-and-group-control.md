---
title: "Unlocking Win11's Power: Efficient User and Group Control"
date: 2024-10-01T20:56:15.904Z
updated: 2024-10-04T01:06:54.222Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking Win11's Power: Efficient User and Group Control"
excerpt: "This Article Describes Unlocking Win11's Power: Efficient User and Group Control"
keywords: Win11 Power Unlock,Efficiency in Windows 11,User Groups Optimization,Control Win11 Performance,Enhance User Access,Group Management Tips,Boost System Stability
thumbnail: https://thmb.techidaily.com/4546ddfed47c887fd8822a083e53e55a360fbac19fd97cadc5d42f68a2d04c9c.png
---

## Unlocking Win11's Power: Efficient User and Group Control

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Quick Links

* [Enable the Local Users and Groups Management Console in Windows 11/10 Home](#enable-the-local-users-and-groups-management-console-in-windows-11-10-home)
* [Manage Local Users and Groups Using the Command Prompt](#manage-local-users-and-groups-using-the-command-prompt)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036486/19272" target="_top" id="2036486">
  <img src="//a.impactradius-go.com/display-ad/19272-2036486" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036486/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

* Local Users and Groups Management is not available in Windows 11/10 Home editions. You need a third-party program to access it.
* You can use Lusrmgr.exe, a portable third-party alternative, to enable the Microsoft Management Console snap-in in Windows 11 Home. The Lusrmgr application provides additional features like account search and defining access times.
* The Command Prompt can also be used to manage users and groups without a third-party utility.

 Local Users and Groups Management is a shell application to manage local and remote computers and access system administrator tools. However, Local Users and Groups Management is unavailable in the Windows 11/10 Home editions, so you must rely on a third-party program to use it there.

## Enable the Local Users and Groups Management Console in Windows 11/10 Home

 Like the Local Group Policy Editor, Local Users and Groups Management (lusrmgr.msc) is an advanced feature available only on Windows Pro, Education, and Enterprise.

 However, while you can use workarounds to [enable Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), it is not possible to enable the Local Users and Groups Management snap-in console.

 Instead, you can use Lusrmgr.exe, a third-party alternative, to enable the Microsoft Management Console snap-in in Windows 11 Home. Lusrmgr.exe is similar to the built-in Local Users and Groups Management console. It is a portable application, and you can download it from GitHub for free.

 Here's how to download and use the Local User and Group Management tool on Windows 11 Home. Follow the same steps on a Windows 10 PC:

1. Open the [lusrmgr GitHub page](https://github.com/proviq/lusrmgr).
2. On the default **Code** tab, scroll down to the **Download** link to get the latest version of the file.
3. Once downloaded, double-click the **lusrmgr.exe**file to run the program.

![lusrmgr program home screen running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-program.jpg)

 You will notice the lusrmgr application looks similar to [opening the native Local Users and Groups Management console](http://www.makeuseof.com/windows-open-local-users-and-groups/). However, the difference lies in the usability of the tool. Below are side-by-side images for the built-in lusrmgr console (left) and the third-party application (right) for reference.

![Lucal User and Groups app and lusrmgr app side by side comparison](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/lucal-user-and-gropups-app-and-lusrmgr.jpg)

 To create a new user account with this Local User and Group Management tool:

1. Right-click on **User** and select **Create**. Then fill in the details for the new user account.
2. Click the **Advanced** button to configure the advanced account option, local path, and profile path.  
![lusrmgr create new user account screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-create-new-user.jpg)
3. Click on **Create** to add the new user account.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087262/19272" target="_top" id="2087262">
  <img src="//a.impactradius-go.com/display-ad/19272-2087262" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087262/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Similarly, you can edit, remove, rename, or add a password to the existing user account. You can also [enable the secret built-in administrator account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/) using the tool.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1815678/21290" target="_top" id="1815678">
  <img src="//a.impactradius-go.com/display-ad/21290-1815678" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1815678/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Additional Features of the Lusrmgr App

![The search bar in lusrmgr application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-search.jpg)

 Apart from the usual account management features, lusrmgr.exe provides additional functions not available in the native utility. For example, you can use the search function to find a specific account. This is useful for system administrators who manage multiple user accounts in an organization.

 Another handy feature is the ability to define access times for individual accounts. To set an access time, right-click on the username and select **Edit**. Next, open the **Account** tab and click on **Define access time**.

![lusrmgr define account access time screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-define-access-time.jpg)

 By default, the user accounts have no limit on access time. But you can define this by selecting a time block for different days.

 Since lusrmgr is a portable app, you can’t open it with the **lusrmgr.msc** command like the built-in app. To launch the program, double-click the executable file you downloaded and make the necessary changes to the user account or groups.

## 2\. Manage Local Users and Groups Using the Command Prompt

 You can use the "net localgroup" or "net user" command-line utility to manage users and groups on Windows 11/10\. It's a handy way to view, add, and delete local groups and users without using a third-party utility.

![How to Run the Command Prompt as an Administrator in Windows Thumbnail](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/how-to-run-the-command-prompt-as-an-administrator-in-windows-thumbnail.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135397/19272" target="_top" id="2135397">
  <img src="//a.impactradius-go.com/display-ad/19272-2135397" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135397/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

  First, open a Command Prompt window with administrative privilege. To do this, press the **Windows** key, type **cmd**, right-click on **Command Prompt**, and select **Run as administrator**.

 Below is a list of commands to view and manage local users and groups using the Command Prompt:

1. To view the name of the server and local groups on the computer, type:  
`net localgroup`
2. To view all users in a group, enter:  
`net localgroup [groupname]`
3. To create a new group, use the following command. Replace **xyz** with the group name you want to create:  
`net localgroup xyz /add`
4. To view all user accounts:  
`net user`
5. To create a new user account (replace **abc** with the username you want to add):  
`net user abc /add`

1. To view all the accounts with administrator privileges:  
`net localgroup administrator`
2. To add a user account to the administrator group (be sure to change **abc**, and **Administrator** to the group name if needed):  
`net localgroup Administrator abc /add`
3. To delete a local group:  
`net localgroup xyz /delete`
4. To delete a local user:  
`net user abc /delete`
5. If you need help with syntax for a specific command, use this:  
`net help <command>`

![Command Prompt screen with the net localgroup command displayed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/command-prompt-screen-with-the-net-localgroup-command-displayed.jpg)

 The Local Users and Groups Management console is a handy utility for system administrators to manage local computers and connect remotely to compatible systems. However, if you are running Windows 11 Home and need to use the lusrmgr.msc tool, your only option is to use the third-party application from GitHub.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-elevate-conference-quality-the-list-of-top-10-free-audio-capture-for-2024/"><u>[New] Elevate Conference Quality The List of Top 10 Free Audio Capture for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-mapping-instagrams-unfollowers-landscape/"><u>[Updated] Mapping Instagram's Unfollowers Landscape</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/amd-rx-6800-drivers-step-by-step-download-instructions-tailored-for-windows-11-10-8-and-windows-7-users/"><u>Amd Rx 6800 Drivers - Step-by-Step Download Instructions Tailored for Windows 11, 10, 8 and Windows 7 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-9-tricks-for-enhancing-windows-11s-sound-experience/"><u>Discover 9 Tricks for Enhancing Windows 11'S Sound Experience</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-resolve-samsung-galaxy-s23-screen-not-working-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Resolve Samsung Galaxy S23 Screen Not Working | Dr.fone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-secure-extraction-of-audio-from-youtube-at-zero-cost/"><u>In 2024, Secure Extraction of Audio From YouTube at Zero Cost</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-12-prominent-nubia-red-magic-9-pro-fingerprint-not-working-solutions-by-drfone-android/"><u>In 2024, Top 12 Prominent Nubia Red Magic 9 Pro Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/learn-to-manipulate-software-sizes-using-windows-11s-shortcut-keys/"><u>Learn to Manipulate Software Sizes Using Windows 11'S Shortcut Keys</u></a></li>
<li><a href="https://review-topics.techidaily.com/realme-12-proplus-5g-support-forgotten-screen-lock-by-drfone-android-unlock-android-unlock/"><u>Realme 12 Pro+ 5G support - Forgotten screen lock.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-error-code-0x80041015-on-windows/"><u>Steps to Rectify Error Code 0X80041015 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-disabling-method-for-windows-11-alerts/"><u>Swift Disabling Method for Windows 11 Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-unseen-paths-of-mouse-control-on-win11/"><u>The Unseen Paths of Mouse Control on Win11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-reasons-behind-malfunctioning-vehicle-speakers-explained/"><u>Top Reasons Behind Malfunctioning Vehicle Speakers Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-extra-potential-with-your-devices-via-a-90-degree-window-flip/"><u>Unlock Extra Potential with Your Devices via a 90-Degree Window Flip</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-fixes-define-role-of-chkdsk-sfc-dism/"><u>Unraveling Windows Fixes: DEFINE Role of CHKDSK, SFC, DISM</u></a></li>
</ul></div>

