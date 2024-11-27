---
title: Comprehensive Guide for SFC Scan on Windows PCs
date: 2024-11-20T16:38:15.841Z
updated: 2024-11-27T16:13:22.229Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Comprehensive Guide for SFC Scan on Windows PCs
excerpt: This Article Describes Comprehensive Guide for SFC Scan on Windows PCs
keywords: SFC Scan Guide,Windows SFC Troubleshoot,SFC Scan Steps,Fixing SFC Issues,SFC Diagnostics for PC,Guide to SFC Scan,Perform SFC on Windows
thumbnail: https://thmb.techidaily.com/00e1438c22966a36d893eecd9042143ec66d342044498e4db45f5bcf754631a6.jpg
---

## Comprehensive Guide for SFC Scan on Windows PCs

 Your Windows computer depends on operating system files to get the information it needs to run smoothly. But sometimes, these files can become corrupted or go missing from your PC, affecting your system negatively in various ways. For example, when something’s wrong with a critical system file, your computer might become slow or crash frequently.

 An easy way to fix problematic system files is to use the System File Checker (SFC). This tool will scan your computer, check the integrity of each system file, and repair those that are damaged or missing.

 Here’s what you need to know about running the SFC tool on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Run a System File Checker Scan on Windows

 To use the SFC, you need to run a single command in Command Prompt. Here’s how:

1. Press**Win + S** to open Windows Search and type**command prompt** in the search box.
2. This will bring up**Command Prompt** in the search result. Click on the**Run as administrator** option.  
![Run Command Prompt Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-Command-Prompt-Using-Windows-Search.jpg)
3. Click**Yes** in the UAC prompt to allow Command Prompt to make changes to your computer.
4. In Command Prompt, enter the below command, and then hit the**Enter** key:  
`SFC /scannow`

 If you’re unfamiliar with operating system files, please read our guide on[what system files are on Windows](https://www.makeuseof.com/windows-system-files-guide/) . And to learn everything you need to know about Command Prompt, you can check out our[beginner's guide to Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) .

## What Happens After I Run the System File Checker?

 After the System File Checker completes its scan, it will display a message in the Command Prompt window with the results.

 If your system files are okay, you’ll see a message that says "Windows Resource Protection did not find any integrity violations." If SFC found and fixed all problematic files, the message will read "Windows Resource Protection found corrupt files and successfully repaired them."

![the results of an sfc scan in Command Prompt on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-scan-results.jpg)

 On the other hand, if it found corrupted files but couldn’t repair any or all of them, the message will read "Windows Resource Protection found corrupt files but was unable to fix some of them." And if SFC encounters a problem, the message will say "Windows Resource Protection could not perform the requested operation."

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Other SFC Commands You Can Run on Windows

 The**SFC /scannow** isn’t the only System File Checker Command you can run. Here are a couple more and what they do:

| SFC Command | Description                                                                                                                                                                                                                                                                       |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| /verifyonly | Run this command if you want SFC to check for problematic operating system files without fixing them.                                                                                                                                                                             |
| /scanfile   | Run this command if you want SFC to check a specific file for problems and fix it if it does have them. For example, Here’s the full command for checking and fixing the**user32.dll** file:**SFC /scanfile=c:\\windows\\system32\\user32.dll**                                   |
| /verifyfile | Run this command if you only want to check a particular system file for problems. Even if SFC finds an issue with the file, it will not repair it. For example, Here’s the full command for checking the**user32.dll** file:**SFC /verifyfile=c:\\windows\\system32\\user32.dll** |
| /offbootdir | Run this command to tell the SFC which directory contains a bootable version of Windows. You need to do this every time you use the tool outside of Windows. For example, to select the**E:** drive on your PC, enter**/offbootdir=e:\\**                                         |
| /offwindir  | Run this command to tell the SFC which folder in the directory — the one you specified with the**SFC /offbootdir** command — contains Windows. For example, enter**/offwindir=e:\\windows** to tell the System File Checker that Windows is on the**E:** drive.                   |

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Run an Offline SFC Scan on Windows

 There are a few scenarios that warrant the use of the SFC without logging into Windows. One such scenario is if the operating system files are so corrupted that Windows cannot start.

 In that case, you can run SFC by[creating a bootable Windows disc or drive](https://www.makeuseof.com/tag/make-bootable-usb-cd-dvd-install-windows-using-iso-file/) and using it to fix damaged system files. This is called an offline scan.

 The important thing to remember about an offline scan is that you need to tell the SFC where to find Windows on the bootable drive. Here’s what a**/scannow** command would look like if you ran it offline:

`SFC /scannow /offbootdir=d:\ /offwindir=d:\windows`

 That above command will tell SFC to look for Windows in the**Windows** folder on the**D:** drive. But keep in mind that the Windows version on the bootable media needs to be the same as the one installed on your PC for the scan and repair to be successful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Find the SFC Log File On Windows

 After the SFC does its thing, it will log the results of the scan and any repairs it made into a text file called**CBS.log** . To open it, press**Win + R** to open Windows Run, enter the below text, and click**OK** :

`%windir%\logs\cbs\cbs.log`

 The CBS.log file contains other logs besides those from the System File Checker. When looking through the entries, look for those that have an**\[SR\]** tag on them. Each entry will contain the date and time of the scan, along with the details of what happened.

![cbs log file on Windows that has been opened in Notepad with the SR tag part showing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/cbs-log-sfc-windows.jpg)

 If you don’t want to bother with searching through the**CBS.log** file for the entries with the**\[SR\]** tag, you can extract them to a file called**sfcdetails.txt** . To do that, open Command Prompt as an administrator, and run the below command:

`findstr /c:"[SR]" %windir%\logs\cbs\cbs.log >sfcdetails.txt`

 You can find**sfcdetails.txt** by heading to**This PC > Local Disk (C:) > Windows > System32** .

![the sfc details text file in File Explorer on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-details-file.jpg)

 You’ll see that the log file contains entries from the System File Checker only.

![the sfc details text file on Windows opened in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-detail-txt.jpg)

 If you’re doing an offline scan, you can enable logging by simply specifying the file path with the following command structure:

`/offlogfile=[offline log file path]`

 Just replace**offline log file path** in the square brackets with the actual path you want to store the offline log file in the offline directory. Then, insert this entire command after the**/windir** command when running an offline SFC scan.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Running the System File Checker, Demystified

 We have only just begun to scratch the surface of what you can do with the System File Checker on Windows 10 and 11\. However, now that you know**how to run SFC** (both in and out of Windows), you can use the tool effectively to troubleshoot problems with operating system files.

 Using the SFC effectively is a necessary skill for every Windows user, and it’s just one of the many tools you can use to fix problems on your Windows computer.

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
<li><a href="https://youtube-sure.techidaily.com/urturing-partnerships-with-top-brands-the-famebit-blueprint-for-2024/"><u>[New] Nurturing Partnerships with Top Brands The FameBit Blueprint for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-creating-a-clickable-thumbnail-enhancing-video-visibility-without-costs/"><u>[Updated] 2024 Approved Creating a Clickable Thumbnail Enhancing Video Visibility without Costs</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-make-my-video-perfectly-fit-instagram/"><u>[Updated] In 2024, Make My Video Perfectly Fit Instagram?</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-zoom-essentials-for-webinar-novices-an-introductory-walkthrough/"><u>2024 Approved Zoom Essentials for Webinar Novices An Introductory Walkthrough</u></a></li>
<li><a href="https://win-premium.techidaily.com/acronis-clone/"><u>最佳無料 Acronis Clone 複製軟體替代品：選擇分析</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-xiaomi-redmi-k70-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Xiaomi Redmi K70? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cambio-sin-costo-de-archivos-wav-a-flac-en-linea-con-movavi-convertidor-libre/"><u>Cambio Sin Costo De Archivos Wav a Flac en Línea Con Movavi - Convertidor Libre</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comprehensive-tutorial-erasing-personal-information-from-your-dell-machine/"><u>Comprehensive Tutorial: Erasing Personal Information From Your Dell Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conversor-libre-en-linea-webm-a-wav-con-movavi-herramienta-sin-coste/"><u>Conversor Libre en Línea: WEBM a WAV Con Movavi - Herramienta Sin Coste</u></a></li>
<li><a href="https://win11-tips.techidaily.com/filtragem-de-imagens-online-livre-com-o-conversor-rw2-do-movavi-sem-custo/"><u>Filtragem De Imagens Online Livre Com O Conversor RW2 Do Movavi - Sem Custo!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-converter-change-wav-files-to-mp4-movavi-video-editor/"><u>Free Online Converter: Change WAV Files to MP4 - Movavi Video Editor</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/overcoming-green-tint-in-youtubes-on-mac-a-guide-for-2024/"><u>Overcoming Green Tint in YouTubes on Mac A Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformer-un-fichier-flac-au-format-mp4-gratuitement-sur-internet-convertisseur-rapide-et-efficace/"><u>Transformer Un Fichier FLAC Au Format MP4 Gratuitement Sur Internet - Convertisseur Rapide Et Efficace</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-capabilities-of-lexar-ssds-a-comprehensive-review-of-the-sl500-and-professional-sl600-series-for-ultra-fast-data-transfer/"><u>Unveiling the Capabilities of Lexar SSDs: A Comprehensive Review of the SL500 & Professional SL600 Series for Ultra-Fast Data Transfer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wmv-vers-wma-conversion-virtuelle-and-gratuite-par-movavi/"><u>WMV Vers WMA Conversion Virtuelle & Gratuite Par Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gifpng-movavi-web/"><u>무료 구성 GIF/PNG 변환기를 찾는다! Movavi와 함께 Web용 이미지 마이크업</u></a></li>
<li><a href="https://win11-tips.techidaily.com/flv-wav-movavi/"><u>오픈소스 FLV-WAV 이동은? 최고의 무료 바이트 조작 도구 - Movavi</u></a></li>
</ul></div>

