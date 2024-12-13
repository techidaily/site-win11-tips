---
title: Unveiling the Power Options Pathway to CPU Extremes
date: 2024-12-05T17:42:28.575Z
updated: 2024-12-12T19:34:43.561Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unveiling the Power Options Pathway to CPU Extremes
excerpt: This Article Describes Unveiling the Power Options Pathway to CPU Extremes
keywords: CPU Extreme Power,CPU Performance Tuning,Advanced Chip Settings,Processor Optimization,Heat Dissipation Techniques,Overclock CPUs Securely,Enhancing CPU Efficiency
thumbnail: https://thmb.techidaily.com/f7eb32e30dabd1ecde240ae4f390a8ba724185aa17a13d5ef1b9d86c145dc8b7.jpg
---

## Unveiling the Power Options Pathway to CPU Extremes

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many[ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

To show the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c -ATTRIB_HIDE`

To hide the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c +ATTRIB_HIDE`

To show the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec -ATTRIB_HIDE`

To hide the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec +ATTRIB_HIDE`

 After you have typed in the command you want in the CMD window, hit the**Enter** key on your keyboard to run it.

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/j5gTm5KxtQ0?si=onF1rBS2nEM5nLGg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sn2STvYRVb8?si=Z-XhJJ1Mc-Em5Kqy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/58KlTPHv8dU?si=7ICagyNgrao7OkVO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-videos.techidaily.com/updated-from-ideas-to-influence-an-insider-look-at-strategic-instagram-videos/"><u>[Updated] From Ideas to Influence An Insider Look at Strategic Instagram Videos</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-integrating-audio-elements-into-facebooks-visual-stories-for-2024/"><u>[Updated] Integrating Audio Elements Into Facebook's Visual Stories for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-pinnacle-speed-windows-10-image-browser/"><u>[Updated] Pinnacle Speed Windows 10 Image Browser</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-conceal-dont-reveal-how-to-blur-faces-online/"><u>2024 Approved Conceal, Don't Reveal How to Blur Faces Online</u></a></li>
<li><a href="https://change-location.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-vivo-s17-pro-drfone-by-drfone-virtual-android/"><u>A Working Guide For Pachirisu Pokemon Go Map On Vivo S17 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-windows-ipmac-using-powershell-techniques/"><u>Easy Windows IP/MAC: Using PowerShell Techniques</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/educational-advancement-powered-by-mondlys-apple-initiative/"><u>Educational Advancement Powered by Mondly’s Apple Initiative</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-disk-space-on-win11-safely-keep-files-intact-max-156-chars/"><u>Enhancing Disk Space on Win11 Safely (Keep Files Intact, Max 156 Chars)</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-breaking-down-the-font-inclusion-process-in-ae/"><u>In 2024, Breaking Down the Font Inclusion Process in AE</u></a></li>
<li><a href="https://some-tips.techidaily.com/jpg-image-te-een-gif-vervangen-gratis-met-de-kloknemers-van-movavi-online/"><u>JPG-Image Te Een Gif Vervangen Gratis Met De Kloknemers Van Movavi Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-firewall-controls-five-techniques/"><u>Mastering Firewall Controls: Five Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-workflow-essential-wins11-god-mode-tips/"><u>Transforming Workflow: Essential Wins11 God Mode Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-nvidia-cp-unresponsiveness-on-win-11/"><u>Troubleshooting Nvidia CP Unresponsiveness on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-password-reset-lockout-period-change/"><u>Windows 10/11 Password Reset Lockout Period Change</u></a></li>
</ul></div>

