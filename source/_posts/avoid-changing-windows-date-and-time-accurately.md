---
title: Avoid Changing Windows Date & Time Accurately
date: 2025-01-30T00:30:31.171Z
updated: 2025-02-01T07:14:37.789Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Avoid Changing Windows Date & Time Accurately
excerpt: This Article Describes Avoid Changing Windows Date & Time Accurately
keywords: TimeSync Avoidance,WindowDateAccuracy,SystemTimeStable,WindowsDateTimeSafety,DateChangePrevention,TimestampSecurity,OSDateTimeIntegrity
thumbnail: https://thmb.techidaily.com/7f4ae1b9b31cac38f7f5bddb79d648495e38c22783ddea3f0c620d5fbd42617b.jpg
---

## Avoid Changing Windows Date & Time Accurately

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/h5uImbOWmTg?si=z4kP-R0QbXbBAJTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-clips.techidaily.com/new-2024-approved-how-can-i-post-twitter-video-on-instagram/"><u>[New] 2024 Approved How Can I Post Twitter Video on Instagram?</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-introduce-circular-smoothing-transition-via-adobe-photoshop-for-2024/"><u>[New] Introduce Circular Smoothing Transition via Adobe Photoshop for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-tweeting-visual-content-from-video-to-gif-transformation/"><u>[Updated] In 2024, Tweeting Visual Content From Video to GIF Transformation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-how-to-bypass-windows-11-lock-screen/"><u>Deciphering How to Bypass Windows 11 Lock Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deep-dive-into-windows-component-services-command-line-utility/"><u>Deep Dive Into Windows Component Services Command-Line Utility</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-the-finest-prime-day-savings-get-your-hands-on-hp-apple-razer-and-other-great-laptop-bargains/"><u>Discover the Finest Prime Day Savings: Get Your Hands On HP, Apple, Razer & Other Great Laptop Bargains!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-bloatware-banishment-in-modern-windows-11/"><u>Effortless Bloatware Banishment in Modern Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/heaviest-airborran-aerial-haulers-ultimate-choices-for-2024/"><u>Heaviest Airborran Aerial Haulers - Ultimate Choices for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-control-for-voice-only-windows-bluetooth/"><u>How to Enable Control for Voice-Only Windows Bluetooth</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionary-possibilities-with-windows-11s-newest-moment/"><u>Revolutionary Possibilities with Windows 11'S Newest Moment</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/secure-your-video-conferences-recording-made-easy-for-2024/"><u>Secure Your Video Conferences Recording Made Easy for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-with-ease-windows-users-meet-kali/"><u>Transitioning with Ease: Windows Users, Meet Kali</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-perfecting-audio-levels-in-film-and-streaming-content/"><u>Updated Perfecting Audio Levels in Film and Streaming Content</u></a></li>
</ul></div>

