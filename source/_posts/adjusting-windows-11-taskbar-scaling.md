---
title: Adjusting Windows 11 Taskbar Scaling
date: 2025-01-25T03:41:30.804Z
updated: 2025-01-31T22:40:21.291Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Windows 11 Taskbar Scaling
excerpt: This Article Describes Adjusting Windows 11 Taskbar Scaling
keywords: Win11TaskbarScale,Windows11BarResize,TaskbarWidthControl,TaskbarScalingWin,WindowBarAdjustment,BarSizeChangeWin,ScalingTaskbarWindows
thumbnail: https://thmb.techidaily.com/6152b7c969d91f2eaae0be3b9bf8b8ec86f6a4683a1dd9c2aefb366c737706ad.jpg
---

## Adjusting Windows 11 Taskbar Scaling

 Ever looked at the Windows 11 Taskbar and thought it looks too small for your liking? Or maybe you feel it could be a little smaller? If that’s the case, you can change its size to suit your needs by making it bigger or smaller.

 Unlike Windows 10, you can’t just unlock the Taskbar and adjust its size freely in Windows 11\. While Microsoft has removed this way of going about it in Windows 11, there is a workaround that you can use, although it’s not as elegant.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Make the Windows 11 Taskbar Bigger or Smaller?

 The only way to change the size of the Taskbar is to use the Registry Editor. However, we advise caution when dealing with the Windows Registry because if something goes wrong, you might experience performance issues on your Windows 11 PC. If you’re unfamiliar with it, we recommend reading our guides on [what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) and [how to not mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) .

 Once you’re all caught up or are already familiar with the Windows Registry, and you know what you’re doing, you can make the Taskbar bigger or smaller. To do that:

1. Start by pressing**Win + R** to open Windows Run.
2. Type**regedit** in the text box and hit the**Enter** key.
3. Then, click**Yes** on the UAC prompt to launch the Registry Editor.
4. Copy and paste the below text in the address bar of the Registry Editor and hit the**Enter** key:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the**Advanced** key, look for a value called**TaskbarSi** . If it’s not there, right-click**Advanced** , select**New > DWORD (32-bit) Value** , and name that value**TaskbarSi.**  
![creating a new dword in the advanced key in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/new-dword-advanced-regedit.jpg)
6. Double-click**TaskbarSi** to edit it, and then enter**2** in the**Value data** text box and click**OK** to make the Taskbar bigger.  
![changing the taskbarsi value to 2 in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/taskbarsi-value-2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fo4lNZ84x9Q?si=WdcYPZp-9VJnZEnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you restart your computer, you will see the result: an enlarged Taskbar.

![an enlarged Taskbar on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-enlarged-taskbar.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To make the Taskbar smaller, enter**0** in the**Value data** text box, click**OK** , and then restart your computer. You will then see that the Taskbar has shrunk.

![a smaller taskbar in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-small-taskbar.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QRaEdFMU-Xc?si=OjaiTvlogJy5wHhN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you decide to go back to the Taskbar’s default size, you can easily set**Value data** to**1** or simply delete the**TaskbarSi** value.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Adjust the Taskbar’s Size to Suit Your Needs on Windows 11

 Even though you can’t make the Taskbar bigger or smaller on Windows 11 as easily as you can on Windows 10, a little know-how can help. And as long as you followed the instructions mentioned above correctly, you shouldn’t worry about messing up the Windows Registry. However, we still recommend that you use this method only if you know what you’re doing.

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
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-caught-the-viral-vibe-here-are-amazons-30-hot-tiktok-deals/"><u>[New] 2024 Approved Caught the Viral Vibe? Here Are Amazon’s 30 Hot TikTok Deals</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-bumper-buddies-bonanza-for-youths/"><u>[Updated] In 2024, Bumper Buddies Bonanza for Youths</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-step-by-step-mastery-in-powerdirector-complete-2024-guide-and-tutorials/"><u>[Updated] Step-by-Step Mastery in PowerDirector Complete 2024 Guide & Tutorials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-esd-files-and-their-conversion-into-iso-on-windows-os/"><u>Decoding ESD Files and Their Conversion Into ISO on Windows OS</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/elevating-your-gaming-the-xbox-recorder-playbook/"><u>Elevating Your Gaming The Xbox Recorder Playbook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-resource-lock-issues-155-chars/"><u>Fixing Windows Resource Lock Issues (155 Chars)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/how-to-create-impressive-slow-motion-content-a-step-by-step-instagram-reel-masterclass-for-2024/"><u>How to Create Impressive Slow Motion Content A Step by Step Instagram Reel Masterclass for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-itel-a60-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Itel A60 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-error-correction-tackling-0x8007045d-in-win11/"><u>Mastering Error Correction: Tackling 0X8007045d in Win11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/maximize-savings-and-performance-the-ultimate-guide-to-the-50-laptop-hack-you-cant-miss/"><u>Maximize Savings and Performance: The Ultimate Guide to the $50 Laptop Hack You Can't Miss!</u></a></li>
<li><a href="https://games-able.techidaily.com/next-level-gameplay-sonys-playstation-5-vs-thrifty-computer/"><u>Next Level Gameplay: Sony's PlayStation 5 VS Thrifty Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalized-keybinding-strategies-for-predefined-text-in-windows-11/"><u>Personalized Keybinding Strategies for Predefined Text in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-immediate-fix-boot-sound-service-reset/"><u>Step-by-Step to Immediate Fix: Boot Sound Service Reset</u></a></li>
<li><a href="https://screen-recording.techidaily.com/streamlining-remote-recordings-a-producers-guide/"><u>Streamlining Remote Recordings A Producer’s Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-system-crashes-unveiling-error-code-secrets/"><u>Tackling System Crashes: Unveiling Error Code Secrets</u></a></li>
</ul></div>

