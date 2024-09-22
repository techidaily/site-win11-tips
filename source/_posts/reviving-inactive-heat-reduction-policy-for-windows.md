---
title: Reviving Inactive Heat Reduction Policy for Windows
date: 2024-09-15T01:38:38.383Z
updated: 2024-09-22T00:16:25.084Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reviving Inactive Heat Reduction Policy for Windows
excerpt: This Article Describes Reviving Inactive Heat Reduction Policy for Windows
keywords: HeatPolicyUpdate,WindowsCoolingAct,TempReductionWin,WindowsHeatSave,ReviveTempPolicy,WinCoolActNow,PolicyReviveWins
thumbnail: https://thmb.techidaily.com/8f88442ac6dedc419a65e9e8bd02cadcc874f8f080f0e1330c1b328f3cf15bd0.jpg
---

## Reviving Inactive Heat Reduction Policy for Windows

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

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

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
<li><a href="https://youtube-zero.techidaily.com/024-approved-the-art-of-youtube-thumbnails-for-mac-professionals/"><u>[New] 2024 Approved The Art of YouTube Thumbnails for Mac Professionals</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-mastering-the-basics-of-asmr-video-content/"><u>[New] In 2024, Mastering the Basics of ASMR Video Content</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-expert-choices-for-tiktok-video-to-gif-transformations-for-2024/"><u>[Updated] Expert Choices for TikTok Video to GIF Transformations for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-ages-in-a-windows-configuration/"><u>Decoding Ages in a Windows Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-process-how-to-use-system-restore-correctly/"><u>Decoding the Process: How to Use System Restore Correctly</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-chatgpt-differs-from-siri-and-google-assistant-as-unique-voice-activated-helpers/"><u>How ChatGPT Differs From Siri and Google Assistant as Unique Voice-Activated Helpers.</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-enhanced-eyes-complimentary-mobile-picture-upgrade/"><u>In 2024, Enhanced Eyes Complimentary Mobile Picture Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-column-addition-solutions-for-excel-windows-problems/"><u>Mastering Column Addition: Solutions for Excel Windows Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-error-0x80d03801-on-microsoft-pcs/"><u>Overcoming Error 0X80D03801 on Microsoft PCs</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1834906">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834906.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834906">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834906.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834906%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834906/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

