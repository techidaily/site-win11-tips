---
title: Remedy Missing Thermal Constraint Policy on PCs
date: 2024-10-12T17:42:12.293Z
updated: 2024-10-15T05:03:55.309Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedy Missing Thermal Constraint Policy on PCs
excerpt: This Article Describes Remedy Missing Thermal Constraint Policy on PCs
keywords: PC Thermal Limit,Heat Constraint PC,Thermal Policy PC,Manage PC Temp,Optimize PC Heating,Thermal Control PC,PC Overheat Prevention
thumbnail: https://thmb.techidaily.com/4494210181b361ed33c42bb9503adb4d12c1be013a2d22176a91ef5b8d6bd2e7.jpg
---

## Remedy Missing Thermal Constraint Policy on PCs

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on[what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137378/7443" target="_top" id="2137378">
  <img src="//a.impactradius-go.com/display-ad/7443-2137378" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137378/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/947750/11832" target="_top" id="947750">
  <img src="//a.impactradius-go.com/display-ad/11832-947750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/947750/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136613/26400" target="_top" id="2136613">
  <img src="//a.impactradius-go.com/display-ad/26400-2136613" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136613/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137976/21526" target="_top" id="2137976">
  <img src="//a.impactradius-go.com/display-ad/21526-2137976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137976/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Bringing Back the System Cooling Policy on Windows

 Now that the system cooling policy has returned you can tweak it to your liking. We have even shown you how to hide it again in case you don’t want others messing with it. If these methods don’t work, you might have another problem with your computer.

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
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-creating-a-viral-traction-with-6-strategic-steps-in-youtube-marketing/"><u>[Updated] 2024 Approved Creating a Viral Traction with 6 Strategic Steps in YouTube Marketing</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-elevate-your-igtv-presence-secrets-to-skyrocketing-subscribers-for-2024/"><u>[Updated] Elevate Your IGTV Presence Secrets to Skyrocketing Subscribers for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-honor-90-lite-drfone-by-drfone-virtual-android/"><u>5 Easy Ways to Change Location on YouTube TV On Honor 90 Lite | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/devhome-explained-the-gateway-to-cutting-edge-w11/"><u>DevHome Explained: The Gateway to Cutting-Edge W11</u></a></li>
<li><a href="https://win-answers.techidaily.com/fix-how-to-resolve-msi-afterburners-inability-to-recognize-gpu-in-windows-11/"><u>Fix: How to Resolve MSI Afterburner's Inability to Recognize GPU in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mend-steam-network-error-on-latest-windows-pcs/"><u>How to Mend Steam Network Error on Latest Windows PCs</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-your-easycap-software-instantly-fast-and-straightforward-downloads-available/"><u>Install Your EasyCap Software Instantly - Fast and Straightforward Downloads Available!</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-convert-videos-to-dvd-format-on-pc-and-mac-a-3-step-guide/"><u>New 2024 Approved Convert Videos to DVD Format on PC and Mac A 3-Step Guide</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/sectionalviewpoint-investigation-for-2024/"><u>SectionalViewpoint Investigation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-microsoft-office-activation-failure/"><u>Strategies to Overcome Microsoft Office Activation Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-text-editor-to-a-dark-screenplay/"><u>Transform Your Text Editor to a Dark Screenplay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-uac-dynamics-from-an-admins-perspective/"><u>Transforming Windows UAC Dynamics From an Admin's Perspective</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-error-xc0f1103f-in-geforce-experience-win-1011/"><u>Unraveling Error XC0F1103F in GeForce Experience Win 10/11</u></a></li>
</ul></div>

