---
title: "Precision in CPU Control: Min/Max Processor Insights"
date: 2024-11-25T18:00:57.529Z
updated: 2024-11-27T16:28:07.479Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Precision in CPU Control: Min/Max Processor Insights"
excerpt: "This Article Describes Precision in CPU Control: Min/Max Processor Insights"
keywords: CPU Precision Guide,Min Max Tech,Processor Range,CPU Performance Tips,MIN MAX Analysis,Core Control Secrets,Processor Insights Deep
thumbnail: https://thmb.techidaily.com/1a9ff9a0df36e63422a5b90ac24e55bb1f02f4633cff516b42a4d7954e71a5e9.jpg
---

## Precision in CPU Control: Min/Max Processor Insights

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many[ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jjGL9wFdlbo?si=Vb1JgZqRXNc03UGG&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

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
<li><a href="https://youtube-lab.techidaily.com/eyword-mastery-the-10-best-online-resources-to-increase-views/"><u>[New] Keyword Mastery The 10 Best Online Resources to Increase Views</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-the-cutting-edge-8-innovative-open-source-video-meeting-systems-for-2024/"><u>[New] The Cutting Edge 8 Innovative Open Source Video Meeting Systems for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-elevating-your-vlog-with-proper-tripod-angles-for-2024/"><u>[Updated] Elevating Your Vlog with Proper Tripod Angles for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-blur-out-not-your-photos-top-10-edits-to-fix-fuzziness/"><u>2024 Approved Blur Out, Not Your Photos! Top 10 Edits to Fix Fuzziness</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-xiaomi-civi-3-disney-100th-anniversary-edition-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your Xiaomi Civi 3 Disney 100th Anniversary Edition Location Settings | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-clarity-top-windows-11-display-tweaks/"><u>Enhancing Clarity: Top Windows 11 Display Tweaks</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-the-future-with-a-touchscreen-macbook-benefits-and-drawbacks-analyzed-by-experts/"><u>Exploring the Future with a Touchscreen MacBook: Benefits and Drawbacks Analyzed by Experts</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/how-everyday-life-benefits-from-ais-progression/"><u>How Everyday Life Benefits From AI's Progression</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-configure-microsoft-word-to-always-open-email-attachments-in-reading-view-on-windows/"><u>How to Configure Microsoft Word to Always Open Email Attachments in Reading View on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-your-email-address-from-the-login-screen-in-windows/"><u>How to Remove Your Email Address From the Login Screen in Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-turn-your-youtube-videos-into-lively-gifs-without-saving-files/"><u>In 2024, Turn Your YouTube Videos Into Lively GIFs Without Saving Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lost-astra-pilot-in-windows-11-solutions-now/"><u>Lost Astra Pilot In Windows 11: Solutions Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-word-docx-to-pdf-conversion-on-windows-11/"><u>Mastering Word Docx to PDF Conversion on Windows 11</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastery-through-art-the-ultimate-list-of-free-mac-drawing-apps-for-2024/"><u>Mastery Through Art The Ultimate List of FREE Mac Drawing Apps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-could-not-start-speech-recognition-windows-error/"><u>Steps to Rectify 'Could Not Start' Speech Recognition Windows Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-unlocking-hidden-powers-in-commands/"><u>Windows 11: Unlocking Hidden Powers in Commands</u></a></li>
</ul></div>

