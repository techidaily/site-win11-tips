---
title: Regain Speed by Tweaking MSRam
date: 2024-06-25T16:28:42.455Z
updated: 2024-06-26T16:28:42.455Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Regain Speed by Tweaking MSRam
excerpt: This Article Describes Regain Speed by Tweaking MSRam
keywords: Speedy RAM Tuning,Optimize Memory Performance,Enhance PC Speed,Boost RAM Efficiency,Increase System Speed,MSRAM Upgrade Tips,RAM Tweaks for Faster Computers
thumbnail: https://thmb.techidaily.com/c38adae2e42bb33172470753ec027ccdb4d1aafb812ed418ac2e91f37424af9f.jpg
---

## Regain Speed by Tweaking MSRam

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
<li><a href="https://win11-tips.techidaily.com/regain-audible-acuity-ending-echo-of-empty-spaces/"><u>Regain Audible Acuity: Ending Echo of Empty Spaces</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapt-calc-app-for-night-time-viewing-dark-mode-tutorial/"><u>Adapt Calc App for Night-Time Viewing: Dark Mode Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-save-settings-restoration-in-windows-1011s-pubg/"><u>Mastering Save Settings Restoration in Windows 10/11'S PUBG</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-windows-11-calculator-activation/"><u>Steps for Windows 11 Calculator Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-typical-directory-display-order-in-win11/"><u>Reviving Typical Directory Display Order in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-audio-test-failure-immediate-action-plan/"><u>Windows Audio Test Failure: Immediate Action Plan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-code-0x887a0006-device-hang-fixes/"><u>Resolving Error Code 0X887A0006: Device Hang Fixes</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-mastering-compressor-a-step-by-step-guide-for-final-cut-pro-x/"><u>Updated 2024 Approved Mastering Compressor A Step-by-Step Guide for Final Cut Pro X</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/10-useful-screen-recorder-for-teachers/"><u>10 Useful Screen Recorder for Teachers</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-most-useful-tips-for-pokemon-go-ultra-league-on-motorola-moto-g84-5g-drfone-by-drfone-virtual-android/"><u>The Most Useful Tips for Pokemon Go Ultra League On Motorola Moto G84 5G | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-comprehensive-vimeo-video-breakdown-including-aspect-ratio/"><u>In 2024, Comprehensive Vimeo Video Breakdown Including Aspect Ratio</u></a></li>
<li><a href="https://extra-information.techidaily.com/unleash-potential-a-step-by-step-solo-podcast-creation/"><u>Unleash Potential  A Step-By-Step Solo Podcast Creation</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-brief-stardom-flash-review-for-2024/"><u>[New] Brief Stardom Flash Review for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-11-without-passcode-drfone-by-drfone-ios/"><u>How to Unlock iPhone 11 Without Passcode? | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-visual-storytelling-at-its-finest-youtube-trailers-through-filmoras-lens/"><u>[New] Visual Storytelling at Its Finest  YouTube Trailers Through Filmora's Lens</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/unbrand-your-videos-removing-filmora-watermark-with-free-and-paid-options-for-2024/"><u>Unbrand Your Videos Removing Filmora Watermark with Free and Paid Options for 2024</u></a></li>
</ul></div>
