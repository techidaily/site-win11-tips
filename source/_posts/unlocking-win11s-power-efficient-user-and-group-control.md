---
title: "Unlocking Win11's Power: Efficient User and Group Control"
date: 2024-09-11T20:53:24.014Z
updated: 2024-09-16T22:10:02.195Z
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

 Similarly, you can edit, remove, rename, or add a password to the existing user account. You can also [enable the secret built-in administrator account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/) using the tool.

### Additional Features of the Lusrmgr App

![The search bar in lusrmgr application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-search.jpg)

 Apart from the usual account management features, lusrmgr.exe provides additional functions not available in the native utility. For example, you can use the search function to find a specific account. This is useful for system administrators who manage multiple user accounts in an organization.

 Another handy feature is the ability to define access times for individual accounts. To set an access time, right-click on the username and select **Edit**. Next, open the **Account** tab and click on **Define access time**.

![lusrmgr define account access time screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-define-access-time.jpg)

 By default, the user accounts have no limit on access time. But you can define this by selecting a time block for different days.

 Since lusrmgr is a portable app, you can’t open it with the **lusrmgr.msc** command like the built-in app. To launch the program, double-click the executable file you downloaded and make the necessary changes to the user account or groups.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134494/18498" target="_top" id="2134494">
  <img src="//a.impactradius-go.com/display-ad/18498-2134494" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134494/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Manage Local Users and Groups Using the Command Prompt

 You can use the "net localgroup" or "net user" command-line utility to manage users and groups on Windows 11/10\. It's a handy way to view, add, and delete local groups and users without using a third-party utility.

![How to Run the Command Prompt as an Administrator in Windows Thumbnail](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/how-to-run-the-command-prompt-as-an-administrator-in-windows-thumbnail.jpg)

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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134236/18498" target="_top" id="2134236">
  <img src="//a.impactradius-go.com/display-ad/18498-2134236" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134236/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Local Users and Groups Management console is a handy utility for system administrators to manage local computers and connect remotely to compatible systems. However, if you are running Windows 11 Home and need to use the lusrmgr.msc tool, your only option is to use the third-party application from GitHub.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://desktop-recording.techidaily.com/updated-from-phones-to-cameras-a-guide-to-diy-video-capturing-for-2024/"><u>[Updated] From Phones to Cameras A Guide to DIY Video Capturing for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/-your-story-with-immersive-youtube-video-editing-tips-for-2024/"><u>Craft Your Story with Immersive YouTube Video Editing Tips for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-infinix-note-30-vip-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Infinix Note 30 VIP Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-no-cost-video-editing-solutions-top-imovie-alternatives/"><u>In 2024, No-Cost Video Editing Solutions Top iMovie Alternatives</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-unique-identification-making-your-youtube-url-stand-out/"><u>In 2024, Unique Identification Making Your YouTube URL Stand Out</u></a></li>
<li><a href="https://win11-tips.techidaily.com/introduction-to-chromium-on-the-latest-windows-11-os/"><u>Introduction to Chromium on the Latest Windows 11 OS</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-tecno-phantom-v-fold-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Tecno Phantom V Fold? Look No Further | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-the-world-of-computing-with-toms-hardware-review/"><u>Navigating the World of Computing with Tom's Hardware Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-and-rebooting-reviving-outdated-windows-applications/"><u>Resetting and Rebooting: Reviving Outdated Windows Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-obscure-problem-how-to-resolve-steams-e84-error/"><u>Tackling the Obscure Problem: How to Resolve Steam's E84 Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-guide-to-protecting-your-notebooks/"><u>The Complete Guide to Protecting Your Notebooks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-pc-speakers-after-hardware-changes/"><u>Unblocking PC Speakers After Hardware Changes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/undoing-windows-11s-updated-search-bar-design/"><u>Undoing Windows 11'S Updated Search Bar Design</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    