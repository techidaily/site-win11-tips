---
title: Securing True Windows Clock Settings
date: 2024-12-01T17:02:48.504Z
updated: 2024-12-06T21:06:02.129Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/UUPt2zKtJ5k?si=LLHdsFDLzVByJsKj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/6xGqSETroqA?si=4C1GPgXi-AksR_oO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-a-step-by-step-guide-to-gopro-time-lapse-mastery/"><u>[New] In 2024, A Step-by-Step Guide to GoPro Time-Lapse Mastery</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-synthesizing-success-the-power-of-magix-samplitude/"><u>[New] Synthesizing Success The Power of Magix Samplitude</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-effortless-video-recordings-of-google-meets-on-phones-for-2024/"><u>[Updated] Effortless Video Recordings of Google Meets on Phones for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-expert-timekeeping-tools-without-a-price/"><u>2024 Approved Expert Timekeeping Tools Without a Price</u></a></li>
<li><a href="https://location-social.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-apple-iphone-12-pro-max-by-name-drfone-by-drfone-virtual-ios/"><u>4 Most-Known Ways to Find Someone on Tinder For Apple iPhone 12 Pro Max by Name | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/a-newbies-introduction-to-langchain-llm-comprehensive-guide-and-tips/"><u>A Newbie’s Introduction to LangChain LLM: Comprehensive Guide and Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/countering-lsa-protection-off-alert-in-windows-os/"><u>Countering LSA Protection OFF Alert in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-error-e8024002e-for-update-issues/"><u>Fixing Error E:8024002E for Update Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-silent-sound-capture-a-step-by-step-guide-for-w11-users/"><u>Fixing Silent Sound Capture: A Step-by-Step Guide for W11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-unopened-sharing-error-in-windows-1011s-experience/"><u>Fixing Unopened Sharing Error in Windows 10/11'S Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inside-ftdibussys-how-it-challenges-windows-memory-security/"><u>Inside ftdibus.sys: How It Challenges Windows Memory Security</u></a></li>
<li><a href="https://technical-tips.techidaily.com/loreal-triumphs-with-dual-accolades-for-revolutionary-inclusivity-in-beauty-technology-at-the-2023-consumer-electronics-show-insights-from-zdnet/"><u>L'Oréal Triumphs with Dual Accolades for Revolutionary Inclusivity in Beauty Technology at the 2023 Consumer Electronics Show - Insights From ZDNet</u></a></li>
<li><a href="https://extra-resources.techidaily.com/premier-quality-4k-panels-for-expert-colour-correction/"><u>Premier Quality 4K Panels for Expert Colour Correction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-faulty-usb-stick-behavior-on-windows-systems/"><u>Rectifying Faulty USB Stick Behavior on Windows Systems</u></a></li>
<li><a href="https://sound-issues.techidaily.com/skype-volume-troubles-heres-how-to-restore-your-sound/"><u>Skype Volume Troubles? Here's How to Restore Your Sound</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-windows-aesthetics-in-8-easy-steps/"><u>Streamline Your Windows Aesthetics in 8 Easy Steps</u></a></li>
</ul></div>

