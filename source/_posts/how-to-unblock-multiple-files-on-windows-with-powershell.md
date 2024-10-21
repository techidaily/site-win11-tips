---
title: How to Unblock Multiple Files on Windows With PowerShell
date: 2024-10-18T17:31:09.513Z
updated: 2024-10-20T16:20:20.171Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Unblock Multiple Files on Windows With PowerShell
excerpt: This Article Describes How to Unblock Multiple Files on Windows With PowerShell
keywords: Unblock Windows Files,PowerShell File Tools,Windows Unblock Command,Multiple Files Unlock,PowerShell Scripts File,Unblock Files Windows PS,Remove Blocked Windows Files
thumbnail: https://thmb.techidaily.com/ecd5393b4b11cd27ce9b151fec19432ec4c563d2b818d2405502179fc7ce1c3d.jpg
---

## How to Unblock Multiple Files on Windows With PowerShell

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  
![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885932/19272" target="_top" id="1885932">
  <img src="//a.impactradius-go.com/display-ad/19272-1885932" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Now You Know How to Unblock Files You Know Are Safe

 With the instruction above unlocking a bunch of downloaded files in a directory should be easier. Keep in mind that you shouldn’t do this on files you don’t trust. The last thing you want to do is put your Windows PC at risk unnecessarily

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
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-hidden-gems-to-hit-videos-strategies-for-success/"><u>[Updated] 2024 Approved From Hidden Gems to Hit Videos Strategies for Success</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-webcam-use-in-professional-settings-for-slide-shows/"><u>[Updated] 2024 Approved Webcam Use in Professional Settings for Slide Shows</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-block-automated-youtube-content-triggers/"><u>[Updated] Block Automated YouTube Content Triggers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1-free-online-conversion-changing-pef-format-to-png-with-ease-moveavi/"><u>1. Free Online Conversion: Changing PEF Format to PNG with Ease - Moveavi</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-the-art-of-capturing-attention-top-6-videos-to-watch/"><u>2024 Approved The Art of Capturing Attention Top 6 Videos to Watch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modwma-movavi/"><u>無需付費的MOD到WMA格式線上轉化 - 利用Movavi優化</u></a></li>
<li><a href="https://driver-download.techidaily.com/1722971800916-enhance-your-pcs-audio-experience-get-official-microsoft-sound-drivers-now/"><u>Enhance Your PC's Audio Experience - Get Official Microsoft Sound Drivers Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guia-paso-a-paso-para-cambiar-formatos-dpx-a-png-sin-coste-mediante-movavi/"><u>Guía Paso a Paso Para Cambiar Formatos DPX a PNG Sin Coste Mediante Movavi</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-oppo-a1-5g-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Oppo A1 5G? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/join-the-meme-revolution-expert-tips-for-the-metaverse-for-2024/"><u>Join the Meme Revolution Expert Tips for the Metaverse for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trasforma-i-tuoi-file-mp4-in-formato-aac-gratuitamente-con-il-servizio-di-conversione-online-di-moveavi/"><u>Trasforma I Tuoi File MP4 in Formato AAC Gratuitamente Con Il Servizio Di Conversione Online Di Moveavi</u></a></li>
</ul></div>

