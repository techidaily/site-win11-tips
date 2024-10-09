---
title: Remedy Missing Thermal Constraint Policy on PCs
date: 2024-10-02T04:32:28.679Z
updated: 2024-10-09T03:12:48.228Z
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
<a href="https://appsumo.8odi.net/c/5597632/2151866/7443" target="_top" id="2151866">
  <img src="//a.impactradius-go.com/display-ad/7443-2151866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151866/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049364/7443" target="_top" id="2049364">
  <img src="//a.impactradius-go.com/display-ad/7443-2049364" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049364/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130874/7443" target="_top" id="2130874">
  <img src="//a.impactradius-go.com/display-ad/7443-2130874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130874/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1061528/11832" target="_top" id="1061528">
  <img src="//a.impactradius-go.com/display-ad/11832-1061528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1061528/11832" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-streamlined-video-production-youtube-studio-edition/"><u>[Updated] 2024 Approved Streamlined Video Production YouTube Studio Edition</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-capture-in-clarity-best-tools-for-quality-4k-conversion/"><u>[Updated] Capture in Clarity Best Tools for Quality 4K Conversion</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/conversione-free-online-dei-file-mod-a-wma-con-movavi-ottenere-la-qualita-senza-costo/"><u>Conversione Free Online Dei File MOD a WMA Con Movavi - Ottenere La Qualità Senza Costo</u></a></li>
<li><a href="https://win-able.techidaily.com/dayz-low-fps-woes-learn-swift-techniques-for-smooth-gaming-now/"><u>DayZ Low FPS Woes? Learn Swift Techniques for Smooth Gaming Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-maze-of-win1011s-error-0x800704b3/"><u>Navigating the Maze of Win10/11's Error 0X800704B3</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/resolving-the-high-cpu-usage-by-dwmexe-in-windows-11-a-complete-guide/"><u>Resolving the High CPU Usage by dwm.exe in Windows 11: A Complete Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-monitor-configuration-on-desktops/"><u>Reversing Monitor Configuration on Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-recover-failed-steamuidll-load/"><u>Techniques to Recover Failed Steamui.dll Load</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-resolving-a-warframe-game-patch-installation-error/"><u>Troubleshooting Tips: Resolving a Warframe Game Patch Installation Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-pathway-to-a-functional-windows-sandbox/"><u>Your Pathway to a Functional Windows Sandbox</u></a></li>
</ul></div>

