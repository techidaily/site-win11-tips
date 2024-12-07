---
title: "The Essence of CPU Control: Min/Max Display Technique"
date: 2024-12-04T21:07:36.880Z
updated: 2024-12-06T18:56:10.567Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Essence of CPU Control: Min/Max Display Technique"
excerpt: "This Article Describes The Essence of CPU Control: Min/Max Display Technique"
keywords: CPU Control Basics,Min-Max Display,Max Display Limits,Min Display Range,Display Control Methods,Essential CPU Tech,Compute Performance Range
thumbnail: https://thmb.techidaily.com/b46dbabb50d5277c1ad28a5993cc958234753eefedba62d12174cf3ff84234d4.jpg
---

## The Essence of CPU Control: Min/Max Display Technique

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many[ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

To show the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c -ATTRIB_HIDE`

To hide the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c +ATTRIB_HIDE`

To show the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec -ATTRIB_HIDE`

To hide the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec +ATTRIB_HIDE`

 After you have typed in the command you want in the CMD window, hit the**Enter** key on your keyboard to run it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6nvb0775GOM?si=peBB_Mo_4zcZFuci" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Add or Remove the Minimum and Maximum Processor States From Power Options

 Setting the minimum or maximum processor state on your Windows computer is vital to helping you get the performance you want from it. If you can’t see these options in the Power Options menu, you can easily reveal them with either Command Prompt or the Registry Editor. And after you’re done tweaking the states, you can hide them for their protection.

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-optimizing-ppt-presentations-across-devices-for-google-meet/"><u>[New] 2024 Approved Optimizing PPT Presentations Across Devices for Google Meet</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-iphone-plus-android-tutorial-screen-recording-google-meets-for-2024/"><u>[New] IPhone + Android Tutorial Screen Recording Google Meets for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-premier-ios-gaming-experience-leading-emulators-for-psp-enthusiasts/"><u>[New] Premier iOS Gaming Experience Leading Emulators for PSP Enthusiasts</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-elevate-with-excellence-the-ultimate-guide-to-motivational-films/"><u>[Updated] In 2024, Elevate with Excellence The Ultimate Guide to Motivational Films</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-growth-odyssey-of-ajey-nagar-on-youtube/"><u>[Updated] The Growth Odyssey of Ajey Nagar on YouTube</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/10-superior-text-conversion-tools-for-mac-enthusiasts/"><u>10 Superior Text Conversion Tools for Mac Enthusiasts</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-tips-for-quickerslower-video-in-instagram-stories/"><u>2024 Approved Tips for Quicker/Slower Video in Instagram Stories</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-to-overcome-win11s-error-0x80246007/"><u>Expert Tips to Overcome Win11’s Error 0X80246007</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-signs-that-youve-been-muted-by-someone/"><u>In 2024, Signs That You've Been Muted by Someone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-sense-of-microsofts-bluetooth-linked-app/"><u>Making Sense of Microsoft's Bluetooth-Linked App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-microsoft-shop-hurdles-code-0x80073cf3/"><u>Navigating Through Microsoft Shop Hurdles Code: 0X80073CF3</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-essentials-of-hugging-face-understanding-its-core-features-and-benefits/"><u>The Essentials of Hugging Face - Understanding Its Core Features and Benefits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-script-execution-policy-in-powershell-efficiently/"><u>Utilizing Script Execution Policy in PowerShell Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zero-tolerance-for-windows-1011-recycle-bin-corruption/"><u>Zero Tolerance for Windows 10/11 Recycle Bin Corruption</u></a></li>
</ul></div>

