---
title: Restoring Lack of Thermal Management on WinOS
date: 2024-10-27T17:11:34.912Z
updated: 2024-11-01T19:49:42.025Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Lack of Thermal Management on WinOS
excerpt: This Article Describes Restoring Lack of Thermal Management on WinOS
keywords: WinOS Cooling Fix,OS Heat Regulation,WinTemp Control,Thermal OS Repair,Optimize WinTemp,Hotfix WinSystems,TempReg WinOS
thumbnail: https://thmb.techidaily.com/3371d97eae392c322e9b82d456ad7eef262a0a211072cf38379ccece2b069d93.jpg
---

## Restoring Lack of Thermal Management on WinOS

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
<a href="https://appsumo.8odi.net/c/5597632/2100537/7443" target="_top" id="2100537">
  <img src="//a.impactradius-go.com/display-ad/7443-2100537" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100537/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

<!-- affiliate ads begin -->
<span id="2135472">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135472%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135472/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139120/17108" target="_top" id="2139120">
  <img src="//a.impactradius-go.com/display-ad/17108-2139120" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139120/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135352/19272" target="_top" id="2135352">
  <img src="//a.impactradius-go.com/display-ad/19272-2135352" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135352/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-the-ultimate-guide-locating-the-heart-of-youtube-video-management/"><u>[Updated] 2024 Approved The Ultimate Guide Locating the Heart of YouTube Video Management</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-streamlining-team-discussions-combining-slack-and-filmora-for-professionals/"><u>[Updated] In 2024, Streamlining Team Discussions Combining Slack and Filmora for Professionals</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-quick-start-guide-to-setup-and-use-obs-on-apple-systems/"><u>[Updated] Quick Start Guide to Setup and Use OBS on Apple Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/disentangling-compact-icons-on-desktop-shelf/"><u>Disentangling Compact Icons on Desktop Shelf</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-immediate-failure-in-adding-folders-with-windows-onedrive/"><u>Fixing Immediate Failure in Adding Folders with Windows OneDrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-a-three-column-widgets-board-in-windows-11/"><u>How to Enable a Three-Column Widgets Board in Windows 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-banish-silent-tweets-add-volume-to-videos/"><u>In 2024, Banish Silent Tweets Add Volume to Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-how-to-skip-windows-11-lock/"><u>Mastering the Art: How to Skip Windows 11 Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-transition-wsl-and-windows-11-written-by-your-name/"><u>Navigating the Transition: WSL and Windows 11' Written by [Your Name]</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-if-you-are-struggling-to-figure-out-which-online-video-trimmer-is-for-you-then-here-is-a-list-of-the-10-best-free-online-video-trimmers/"><u>New In 2024, If You Are Struggling to Figure Out Which Online Video Trimmer Is for You, Then Here Is a List of the 10 Best Free Online Video Trimmers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/pictorial-pop-culture-their-tales/"><u>Pictorial Pop Culture Their Tales</u></a></li>
<li><a href="https://technical-tips.techidaily.com/understanding-discord-downtime-identifying-if-youre-alone-in-facing-outages-or-if-its-a-widespread-problem/"><u>Understanding Discord Downtime: Identifying If You're Alone in Facing Outages or if It's a Widespread Problem.</u></a></li>
</ul></div>

