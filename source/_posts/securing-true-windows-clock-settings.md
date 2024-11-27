---
title: Securing True Windows Clock Settings
date: 2024-11-24T16:24:20.786Z
updated: 2024-11-27T16:29:11.867Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Securing True Windows Clock Settings
excerpt: This Article Describes Securing True Windows Clock Settings
keywords: Windows Time Lock,Secure Windows Clock,Windows Clock Security,Set Safe Windows Time,Protect Windows Alarm,Guarantee True Windows Hour,Safeguard Windows Clock Settings
thumbnail: https://thmb.techidaily.com/a5f798f7cf1ad15667826396aa244ceb4353a103f9fb628a857687ce3978b94e.png
---

## Securing True Windows Clock Settings

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-turning-heads-with-efficient-video-rotation-in-vlc/"><u>[New] In 2024, Turning Heads with Efficient Video Rotation in VLC</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-thriving-in-the-world-of-youtube-broadcasting-master-class/"><u>[New] Thriving in the World of YouTube Broadcasting Master Class</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-25plus-futuristic-insights-on-ar-enhanced-worlds/"><u>[Updated] 25+ Futuristic Insights on AR-Enhanced Worlds</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-behind-the-scenes-how-ajey-monetizes-content/"><u>2024 Approved Behind the Scenes How Ajey Monetizes Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-null-associated-app-errors-windows/"><u>Dealing with Null Associated App Errors (Windows)</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-the-latest-corsair-k55-controller-drivers-free-updates-available/"><u>Download the Latest Corsair K55 Controller Drivers - Free Updates Available</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-null-audio-device-issue-in-win-10/"><u>How To Fix Null Audio Device Issue in Win 10</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-the-art-of-monitors-reimagined-an-insight-into-the-z32x/"><u>In 2024, The Art of Monitors Reimagined An Insight Into the Z32X</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/aging-your-google-id-for-private-yt-video-distribution/"><u>Leveraging Your Google ID for Private YT Video Distribution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-fatal-error-unraveling-0x800f0831/"><u>Navigating Through Fatal Error: Unraveling 0X800f0831</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-operation-automatic-updates-plus-swap-graphics-card-in-win10/"><u>Smooth Operation: Automatic Updates + Swap Graphics Card in Win10</u></a></li>
<li><a href="https://discover-exclusive.techidaily.com/step-by-step-instructions-erasing-data-and-reinstalling-windows-for-your-gateway-desktop-computer-in-windows-11/"><u>Step-by-Step Instructions: Erasing Data and Reinstalling Windows for Your Gateway Desktop Computer in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taking-control-your-w11-microphone-mastery-plan/"><u>Taking Control: Your W11 Microphone Mastery Plan</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/1715701153697-the-ultimate-guide-to-setting-up-a-group-conversation-that-caters-to-all-systems-in-skype/"><u>The Ultimate Guide to Setting up a Group Conversation that Caters to All Systems in Skype.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-eradicating-windows-search-icons/"><u>Tips for Eradicating Windows Search Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-control-over-mouse-dynamics-in-windows/"><u>Unleashing Control Over Mouse Dynamics in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-luminosity-taming-windows-colour-chaos/"><u>Unlocking Luminosity: Taming Windows' Colour Chaos</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    