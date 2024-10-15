---
title: Commanding Your PC's Performance Horizon with CPU
date: 2024-10-10T16:26:08.700Z
updated: 2024-10-15T07:42:02.234Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Commanding Your PC's Performance Horizon with CPU
excerpt: This Article Describes Commanding Your PC's Performance Horizon with CPU
keywords: High-Performance PC Optimization,Boost PC Speed & Efficiency,Enhance Computer Power,Turbocharge Your System,Amplify CPU Performance,Push PC Capabilities,Escalate Processor Strength
thumbnail: https://thmb.techidaily.com/b5d7a060863d8900073e79dab85dc7e851c9bee60e59b4a6159a2401dabd161b.jpg
---

## Commanding Your PC's Performance Horizon with CPU

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094418/7443" target="_top" id="2094418">
  <img src="//a.impactradius-go.com/display-ad/7443-2094418" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094418/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036486/19272" target="_top" id="2036486">
  <img src="//a.impactradius-go.com/display-ad/19272-2036486" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036486/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082520/7443" target="_top" id="2082520">
  <img src="//a.impactradius-go.com/display-ad/7443-2082520" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082520/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918698/19272" target="_top" id="1918698">
  <img src="//a.impactradius-go.com/display-ad/19272-1918698" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918698/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-premium-online-audio-solutions-guide/"><u>[New] Premium Online Audio Solutions Guide</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-revolutionary-videography-toolset-for-vimeo-users-for-2024/"><u>[New] Revolutionary Videography Toolset for Vimeo Users for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-podcast-versus-visual-media-which-suits-your-content-best-for-2024/"><u>[Updated] Podcast versus Visual Media Which Suits Your Content Best for 2024</u></a></li>
<li><a href="https://dvd-bd.techidaily.com/2023mac5/"><u>2023年無料最新Mac用動画変換ツール5選! 使い心地と機能比較、どれがおすすめ？</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ease-teammers-frustrations-quickly/"><u>Ease Teammers' Frustrations, Quickly</u></a></li>
<li><a href="https://vp-tips.techidaily.com/fabricate-funny-face-filters-giphy-style/"><u>Fabricate Funny Face Filters Giphy Style</u></a></li>
<li><a href="https://sound-issues.techidaily.com/headphone-connector-malfunctions-in-laps-causes-and-solutions-unveiled/"><u>Headphone Connector Malfunctions in Laps: Causes & Solutions Unveiled</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/high-definition-face-off-ultimate-legend-sj6-vs-xiaomis-yi-for-2024/"><u>High Definition Face-Off Ultimate Legend SJ6 Vs. Xiaomi's Yi for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-lava-blaze-curve-5g-phone-by-drfone-android/"><u>In 2024, How to Use Google Assistant on Your Lock Screen Of Lava Blaze Curve 5G Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sidestep-vmware-boot-failures-with-8-proven-strategies-win11/"><u>Sidestep VMware Boot Failures with 8 Proven Strategies, Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-economics-of-windows-11-for-microsoft/"><u>The Economics of Windows 11 for Microsoft</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-12-prominent-nokia-xr21-fingerprint-not-working-solutions-by-drfone-android/"><u>Top 12 Prominent Nokia XR21 Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-os-woes-quick-solutions-to-start-photoscape-immediately/"><u>Win OS Woes: Quick Solutions to Start Photoscape Immediately</u></a></li>
</ul></div>

