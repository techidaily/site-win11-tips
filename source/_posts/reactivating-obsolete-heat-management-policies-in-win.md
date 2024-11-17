---
title: Reactivating Obsolete Heat Management Policies in Win
date: 2024-11-15T16:05:18.089Z
updated: 2024-11-17T16:42:46.867Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reactivating Obsolete Heat Management Policies in Win
excerpt: This Article Describes Reactivating Obsolete Heat Management Policies in Win
keywords: Heat Policy Reactivation,Obsolete Heat Strategies,Reviving WIN Heat Systems,Old Heat Control Methods,Modernizing Outdated WIN Heating,Enhancing WIN Temperature Policies,Updating WIN Thermal Protocols
thumbnail: https://thmb.techidaily.com/35db44591f3dcbc09fec63cf1897abe760727c167b28e2d4a0f6ad0bbea5b61b.jpg
---

## Reactivating Obsolete Heat Management Policies in Win

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

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
<a href="https://appsumo.8odi.net/c/5597632/2100529/7443" target="_top" id="2100529">
  <img src="//a.impactradius-go.com/display-ad/7443-2100529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2148619/17108" target="_top" id="2148619">
  <img src="//a.impactradius-go.com/display-ad/17108-2148619" border="0" alt="https://techidaily.com" width="100" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2148619/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094418/7443" target="_top" id="2094418">
  <img src="//a.impactradius-go.com/display-ad/7443-2094418" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094418/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<span id="1424531">
					<video width="864" height="NaN" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424531.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424531">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424531.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424531%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424531/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-cutting-edge-editors-scouting-the-ultimate-tools-for-youtube-shorts/"><u>[New] 2024 Approved Cutting Edge Editors Scouting the Ultimate Tools for YouTube Shorts</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-the-art-of-designing-smaller-images-thumbnails-explained/"><u>[New] 2024 Approved The Art of Designing Smaller Images Thumbnails Explained</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-essential-webcams-for-peak-twitch-performance/"><u>[Updated] Essential Webcams for Peak Twitch Performance</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-mastering-the-art-of-using-ez-grabber-with-this-tutorial-for-2024/"><u>[Updated] Mastering the Art of Using EZ Grabber with This Tutorial for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-expert-pick-websites-showcasing-hd-sky-shots/"><u>2024 Approved Expert Pick Websites Showcasing HD Sky Shots</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-fine-tune-youtube-video-pacing-desktopmobile/"><u>2024 Approved Fine-Tune YouTube Video Pacing - Desktop/Mobile</u></a></li>
<li><a href="https://fox-glue.techidaily.com/best-15-online-photo-editors-2023free/"><u>Best 15 Online Photo Editors 2023[Free]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-step-by-step-process-for-converting-your-mp3-collection-into-widespread-high-quality-audio-cds-via-imgburn-windows/"><u>Easy Step-by-Step Process for Converting Your Mp3 Collection Into Widespread, High-Quality Audio Cds via ImgBurn (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-older-software-works-on-contemporary-windows-10/"><u>Ensuring Older Software Works on Contemporary Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-previous-windows-sleepshutdown-configs/"><u>Regaining Previous Windows Sleep/Shutdown Configs</u></a></li>
<li><a href="https://win-extraordinary.techidaily.com/solving-the-mystery-of-googles-sudden-diverts-to-bing-causes-and-solutions-explained/"><u>Solving the Mystery of Google's Sudden Diverts to Bing: Causes & Solutions Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-install-icloud-successfully-on-your-windows-pc/"><u>Steps to Install iCloud Successfully on Your Window's PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taking-charge-of-pcs-core-management-interface/"><u>Taking Charge of PC's Core Management Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-convert-esd-to-iso-in-windows-environment/"><u>The Ultimate Guide to Convert ESD to ISO in Windows Environment</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-ultimate-guide-to-determining-real-time-ram-speeds-on-latest-windows-platforms/"><u>The Ultimate Guide to Determining Real-Time RAM Speeds on Latest Windows Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-gaming-potential-combatting-directdraw-faults-on-windows-11/"><u>Unlocking Gaming Potential: Combatting DirectDraw Faults on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-blue-screen-addressing-interruptexception/"><u>Win11 Blue Screen: Addressing INTERRUPT_EXCEPTION</u></a></li>
</ul></div>

