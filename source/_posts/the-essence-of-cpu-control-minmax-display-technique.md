---
title: "The Essence of CPU Control: Min/Max Display Technique"
date: 2024-11-24T16:01:10.905Z
updated: 2024-11-27T17:08:07.728Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many[ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/May-pLCUkEA?si=PGlcFZAlsp3S3beI&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/58KlTPHv8dU?si=7ICagyNgrao7OkVO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-iphone-ready-syncing-photos-and-videos-from-pc/"><u>[Updated] 2024 Approved IPhone-Ready Syncing Photos & Videos From PC</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-method-for-pushing-twitter-videos-through-whatsapp-channels/"><u>2024 Approved Method for Pushing Twitter Videos Through WhatsApp Channels</u></a></li>
<li><a href="https://extra-hints.techidaily.com/beyond-3d-a-comparative-guide-to-metaverse-and-omniverse-realities-for-2024/"><u>Beyond 3D A Comparative Guide to Metaverse and Omniverse Realities for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ructing-coherent-youtube-video-sequences-for-2024/"><u>Constructing Coherent YouTube Video Sequences for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-secrets-of-dism-for-system-rebuilds/"><u>Decoding the Secrets of DISM for System Rebuilds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-productivity-get-to-know-these-20-indispensable-cmd-commands/"><u>Enhance Productivity: Get to Know These 20 Indispensable CMD Commands</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-diagnosing-and-resolving-windows-boot-up-failures/"><u>Expert Guide: Diagnosing and Resolving Windows Boot-Up Failures</u></a></li>
<li><a href="https://facebook.techidaily.com/social-network-sets-higher-barrier-against-fake-news-truths/"><u>Social Network Sets Higher Barrier Against Fake News Truths</u></a></li>
<li><a href="https://video-capture.techidaily.com/troubleshooting-steps-resolving-issues-with-non-functional-nvidia-shadowplay/"><u>Troubleshooting Steps: Resolving Issues with Non-Functional NVIDIA ShadowPlay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-customization-in-windows-11-navigating-app-shortcuts/"><u>Unlocking Customization in Windows 11: Navigating App Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-discrepan-marketplace-impact-on-local-and-microsoft-account-accessibility-in-windows/"><u>Unveiling Discrepan Marketplace Impact on Local & Microsoft Account Accessibility in Windows</u></a></li>
<li><a href="https://discover-deluxe.techidaily.com/pcandroidiphone/"><u>クリップした後も続く！ PC/Android/iPhone で動画の最中から切り取る究極ガイド</u></a></li>
</ul></div>

