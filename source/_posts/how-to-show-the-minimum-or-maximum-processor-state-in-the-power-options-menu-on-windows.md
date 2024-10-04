---
title: How to Show the Minimum or Maximum Processor State in the Power Options Menu on Windows
date: 2024-09-27T20:21:58.299Z
updated: 2024-10-04T00:25:23.651Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Show the Minimum or Maximum Processor State in the Power Options Menu on Windows
excerpt: This Article Describes How to Show the Minimum or Maximum Processor State in the Power Options Menu on Windows
keywords: Win CPU Status Setting,Min/Max CPU Display,Windows Performance Controls,Manage CPU Limits,Adjust System Power,Optimize Processor Usage,CPU State Management Windows
thumbnail: https://thmb.techidaily.com/6e2f3010b64553c858c441b2aa0463f3e8a124b61c9d02d5a4f78ba177103c47.png
---

## How to Show the Minimum or Maximum Processor State in the Power Options Menu on Windows

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

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137225/26400" target="_top" id="2137225">
  <img src="//a.impactradius-go.com/display-ad/26400-2137225" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137225/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135399/19272" target="_top" id="2135399">
  <img src="//a.impactradius-go.com/display-ad/19272-2135399" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135399/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043597/7443" target="_top" id="2043597">
  <img src="//a.impactradius-go.com/display-ad/7443-2043597" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043597/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006941/19272" target="_top" id="2006941">
  <img src="//a.impactradius-go.com/display-ad/19272-2006941" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006941/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-hide-and-view-fb-snapshot-tool/"><u>[New] 2024 Approved Hide-and-View FB Snapshot Tool</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-flipping-the-script-turning-online-games-into-channel-gold/"><u>[Updated] 2024 Approved Flipping the Script Turning Online Games Into Channel Gold</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-tips-and-tricks-for-iphone-low-light-photography/"><u>2024 Approved Tips and Tricks for iPhone Low Light Photography</u></a></li>
<li><a href="https://blog-min.techidaily.com/6-ways-to-transfer-contacts-from-oppo-find-x7-ultra-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>6 Ways To Transfer Contacts From Oppo Find X7 Ultra to iPhone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-windows-vmfreeze-ups-vmware-guide/"><u>Clearing Up Windows VMfreeze-Ups: VMware Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/declutter-drives-identifying-massive-storage-consumers-in-windows/"><u>Declutter Drives: Identifying Massive Storage Consumers in Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-setup-with-official-insignia-drivers-for-windows-pcs-free-downloads-available/"><u>Easy Setup with Official Insignia Drivers for Windows PCs - Free Downloads Available</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-pcs-gaming-potential-with-advanced-amd-radeon/"><u>Elevate Your PC's Gaming Potential With Advanced AMD Radeon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enablingdisabling-content-filter-on-modern-windows/"><u>Enabling/Disabling Content Filter on Modern Windows</u></a></li>
<li><a href="https://data-wizards.techidaily.com/guidelines-on-fixing-broken-nikon-video-data/"><u>Guidelines on Fixing Broken Nikon Video Data</u></a></li>
<li><a href="https://fox-search.techidaily.com/how-to-modify-startup-settings-in-the-configuration-window/"><u>How to Modify Startup Settings in the Configuration Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-recover-lost-pin-on-windows-11-amidst-errors/"><u>How To Recover Lost PIN on Windows 11 Amidst Errors</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-changefake-your-vivo-y100i-power-5g-location-on-viber-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Fake Your Vivo Y100i Power 5G Location on Viber | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-flawed-windows-scripts-to-function-again/"><u>Overhauling Flawed Windows Scripts to Function Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-ensure-win-calculator-supremacy/"><u>Steps to Ensure Win Calculator Supremacy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-playtime-fixing-minecraft-exit-failures/"><u>Streamline Playtime: Fixing Minecraft Exit Failures</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/superior-performance-on-the-rise-upgraded-drivers-for-amd-hd-6950/"><u>Superior Performance on the Rise: Upgraded Drivers for AMD HD 6950</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/swift-snapfile-reinstatement-guide/"><u>Swift Snapfile Reinstatement Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unshackle-onedrive-and-microsoft-id-integration-on-windows-systems/"><u>Unshackle OneDrive and Microsoft ID Integration on Windows Systems</u></a></li>
</ul></div>

