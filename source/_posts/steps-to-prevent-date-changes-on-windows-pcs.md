---
title: Steps to Prevent Date Changes on Windows PCs
date: 2024-06-25T16:45:00.006Z
updated: 2024-06-26T16:45:00.006Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Prevent Date Changes on Windows PCs
excerpt: This Article Describes Steps to Prevent Date Changes on Windows PCs
keywords: Preventing Windows Date Change,Stop PC Date Alteration,Windows Time Settings Fix,Secure PC Timestamp Control,Avoid PC Date Manipulation,Windows Calendar Safety,Protect PC Date Accuracy
thumbnail: https://thmb.techidaily.com/4ad77a8ea715329fd3e5a5b2d2c2957ac59e62959913be278ad38c42bb2fd196.jpg
---

## Steps to Prevent Date Changes on Windows PCs

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

## 1\. Use the Group Policy Editor

 If your computer is part of an organization and users often change the date and time, use Group Policy Editor to stop it. This will prevent those with limited access to the computer from altering the date and time. However, this method only works for Windows Pro, Enterprise, or Education Editions.

 So, if you have Windows Home Edition, this won’t work. In that case, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems complicated, skip it and try the next solution instead.

 Follow these steps to prevent users from changing the date and time:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **gpedit.msc** in the text box and press Enter. This will open the Group Policy Editor window.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > System > Locale Services
4. In the right-side pane, double-click on **Disallow user override of locale settings**.  
![Disallow user override of locale settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disallow-user-override-of-locale-settings.jpg)
5. In the pop-up window, check the **Enabled** radio button.
6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

## 2\. Tweak the Registry Editor

 If you’re using Windows Home Edition or have disabled the Group Policy Editor, use the Registry Editor to protect date and time settings. This method is more advanced and has a higher risk of system damage.

 In that case, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it. Doing so will restore settings if something goes wrong.

 Follow these steps to stop users from changing the time and date via the registry:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the field and press Enter. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. In the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Software\Policies\Microsoft\Control Panel\International\
4. If the International folder doesn’t exist, create one. To do that, right-click on Control Panel and select **New** \> **Key**. Name it **International**.
5. Then right-click on **International** and select New > DWORD (32-bit) Value.
6. Name the newly created value **PreventUserOverrides**.
7. Double-click on the **PreventUserOverrides** DWORD value.  
![Use Registry Editor to Prevent Users From Chaning date and time settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-registry-editor-to-prevent-users-from-chaning-date-and-time-settings.jpg)
8. In the pop-up window, change the Value data to **1** and click **OK**.

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/unzipping-challenge-managing-multiple-compressed-files-in-a-snap/"><u>Unzipping Challenge: Managing Multiple Compressed Files in a Snap</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-streamlining-display-with-adjusted-desk-icons/"><u>Title: Streamlining Display with Adjusted Desk Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-lowering-windows-acoustic-amplifiers/"><u>Guide to Lowering Windows Acoustic Amplifiers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-virtual-memory-settings-for-peak-windows-performance/"><u>Navigating Through Virtual Memory Settings for Peak Windows Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-file-access-mastering-network-drives-in-win11/"><u>Seamless File Access: Mastering Network Drives in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-capability-of-windows-11-with-multi-display-setup/"><u>Unlock the Full Capability of Windows 11 With Multi-Display Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-line-for-quake-via-windows-terminal/"><u>Command Line for Quake via Windows Terminal</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-google-pixel-fold-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Google Pixel Fold? | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/slapstick-suggestions-a-guide-to-hilarious-short-form-videography/"><u>Slapstick Suggestions  A Guide to Hilarious Short-Form Videography</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-contacts-files-on-infinix-by-fonelab-android-recover-contacts/"><u>Complete guide for recovering contacts files on Infinix .</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-aligning-music-selections-to-video-narratives-for-2024/"><u>Updated Aligning Music Selections to Video Narratives for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-streamline-watching-facebook-videos-on-your-apple-tv-device/"><u>[New] 2024 Approved  Streamline  Watching Facebook Videos on Your Apple TV Device</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-syncing-soundtracks-with-vimeo-video-content/"><u>[New] In 2024, Syncing Soundtracks with Vimeo Video Content</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/snapchat-recovery-quickly-recover-photosvideos-for-2024/"><u>Snapchat Recovery  Quickly Recover Photos/Videos for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-top-narrative-strategies-top-channels-dual-success-formula/"><u>[New] Top Narrative Strategies, Top Channels  Dual Success Formula</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>