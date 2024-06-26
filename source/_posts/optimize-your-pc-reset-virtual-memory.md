---
title: "Optimize Your PC: Reset Virtual Memory"
date: 2024-06-25T16:27:43.792Z
updated: 2024-06-26T16:27:43.792Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimize Your PC: Reset Virtual Memory"
excerpt: "This Article Describes Optimize Your PC: Reset Virtual Memory"
keywords: PC Memory Optimization,Virtual Mem Reset Guide,Enhance System Speed,RAM Efficiency Tips,Increase PC Performance,Adjust Virtual RAM,Boost Computer Speed
thumbnail: https://thmb.techidaily.com/e8d9fb9f5398f4a792320d2b13c1a57276ee28fb817fc4d294eae20885dd4758.jpg
---

## Optimize Your PC: Reset Virtual Memory

 Are you having trouble with virtual memory on Windows 11? Resetting virtual memory on Windows can improve system performance or free up extra hard drive space. So, we'll show you exactly how to reset the virtual memory on your Windows 11 computer.

## What Is Virtual Memory and How Does It Work?

 Virtual memory, also known as a paging file, is a technology used in computers to allow programs to use more memory than what's physically available on it. When you run out of RAM, your operating system relies on virtual memory to continue running programs.

 The computer creates a special file called a page or swap file on the hard drive. It stores some data temporarily removed from RAM and written to the hard drive. This way, the computer can access more memory than what's installed.

 Although virtual memory allows programs to operate smoothly, it can also hurt overall performance. For example, if your computer runs out of RAM, it will use more of the hard drive to store data. This also significantly slows overall performance as HDDs and SSDs are much slower than RAM.

 Let's now see how to reset Virtual Memory on Windows.

## 1\. Use the System Properties window

 If you want to reset virtual memory settings on your Windows device, you can use the System Properties window. To do this, press **Win + R** on your keyboard to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).

 In the text box, type **sysdm.cpl**, and hit Enter. A system properties window will open up. Then, go to the **Advanced** tab and click the **Settings** button in the Performance section.

![How to Reset Virtual Memory on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-reset-virtual-memory-on-windows-11.jpg)

 This will open up the Performance Options window, where you can manage virtual memory settings. For this, switch to the **Advanced** tab and click on **Change** in the Virtual Memory section.

![Reset Page Size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-page-size.jpg)

 On the next screen, uncheck the **Automatically manage paging file size for all drives** checkbox and select the drive you want to configure virtual memory. Normally, this will be the drive on which Windows is installed.

 Set the custom size for virtual memory. Then, check the **No paging file** radio button and click **Set**. If you see a warning message, click **Yes** to confirm.

 After following the above steps, click **OK** to save your changes. Now close the System Properties and Settings windows and restart your computer. The new virtual memory settings should now be in effect.

## 2\. Use Group Policy Editor

 You can also use the Local Group Policy Editor to reset virtual memory settings on your Windows device. But remember that this method is only available on Pro and Enterprise editions.

 If you're using a Home edition, you should first [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To get started, open the Run dialog box and type **gpedit.msc** into the text box. Then click **OK** or press Enter to open the Local Group Policy Editor window.

![Clear virtual memory pagefile Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clear-virtual-memory-pagefile-using-group-policy.jpg)

 Then navigate to the following location:

Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Option

 Scroll down and double-click **Shutdown: Clear virtual memory pagefile** policy. In the Properties window, select Enabled and then click **Apply**. Next, click **OK** to save it.

## 3\. Use Registry Editor

 If you don't have access to the Local Group Policy Editor, you can also use the Registry Editor to reset virtual memory settings on Windows. Before proceeding, you should [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) in case something gets wrong.

![Reset Virtual Memory Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-virtual-memory-using-registry.jpg)

 To get started, search for **Registry Editor** in the Start menu and click on it. Once you open the Registry Editor, navigate to the following path:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management

 Next, double-click on the **ClearPageFileAtShutdown** key and set its value to **1**. Click on the **OK** button to save your changes.

## Reset Virtual Memory To Get Better Performance

 Resetting virtual memory settings improves Windows computer performance. This guide introduces three methods to learn how to reset virtual memory on Windows. Give it a try and see which methods work best for you. If you face any issues while doing this, you can always use system restore to revert to the previous settings.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-utorrent-not-installing-on-windows/"><u>How to Fix uTorrent Not Installing on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-setting-powershell-policies/"><u>A Practical Approach to Setting PowerShell Policies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-users-through-admin-level-execution-woes/"><u>Guiding Users Through Admin-Level Execution Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-the-functionality-of-fn-keys-on-modern-pcs-windows-11/"><u>Configuring the Functionality of FN Keys on Modern PCs (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-system-tray-and-secret-icons-in-win11/"><u>Decoding System Tray & Secret Icons in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-the-onedrive-symbol-from-windows-11-filesystem/"><u>Eradicating the OneDrive Symbol From Windows 11 Filesystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-desktop-icon-update-process-on-windows/"><u>Simplifying Desktop Icon Update Process on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-disk-designations-c-and-d-varieties/"><u>Navigating Disk Designations: C and D Varieties</u></a></li>
<li><a href="https://win11-tips.techidaily.com/learn-cmd-lingo-top-5-playful-procedures-unveiled/"><u>Learn Cmd Lingo: Top 5 Playful Procedures Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-there-are-no-more-files-error-on-windows-10-and-11/"><u>How to Fix the “There Are No More Files” Error on Windows 10 & 11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-special-features-virtual-location-on-xiaomi-13t-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Xiaomi 13T? | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/1714937847087-new-2024-approved-how-to-add-audio-fade-in-effect/"><u>New 2024 Approved How to Add Audio Fade In Effect?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-flavorful-filmmaking-top-7-strategies-for-culinary-videos/"><u>2024 Approved  Flavorful Filmmaking  Top 7 Strategies for Culinary Videos</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-unleash-your-creativity-the-top-10-free-green-screen-apps-for-mobile-video-editing/"><u>New 2024 Approved Unleash Your Creativity The Top 10 Free Green Screen Apps for Mobile Video Editing</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/hunters-picks-best-video-recorders-reviewed-for-2024/"><u>Hunters' Picks  Best Video Recorders Reviewed for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/effortlessly-create-and-manage-cross-platform-communication-channels-with-skype-groups/"><u>Effortlessly Create and Manage Cross-Platform Communication Channels with Skype Groups</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-why-and-how-to-choose-a-lone-players-path-in-apex-legends/"><u>[Updated] Why and How to Choose a Lone Player's Path in Apex Legends</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/transform-your-music-library-best-free-software-choices-for-youtube-to-mp3-for-2024/"><u>Transform Your Music Library  Best Free Software Choices for YouTube-to-MP3 for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-vivo-v29-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Vivo V29 Location | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-how-to-detach-audio-from-video-in-premiere-pro/"><u>Updated How to Detach Audio From Video in Premiere Pro?</u></a></li>
</ul></div>
