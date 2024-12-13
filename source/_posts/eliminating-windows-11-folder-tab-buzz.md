---
title: Eliminating Windows 11 Folder Tab Buzz
date: 2024-12-12T01:26:00.968Z
updated: 2024-12-13T00:58:37.005Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating Windows 11 Folder Tab Buzz
excerpt: This Article Describes Eliminating Windows 11 Folder Tab Buzz
keywords: Win11 NoisyTab Fix,Quieting W11 Folders,Stop W11 TabBuzz,SilentW11 FolderTabs,End Windows 11 Buzzes,Toggle W11 FolderNoise,Mute Win11 FolderTab
thumbnail: https://thmb.techidaily.com/8ec7f9d19b5395810145f1bf31b1db142a6ba9be6ed8b5f1e4a621d2eef1f390.jpg
---

## Eliminating Windows 11 Folder Tab Buzz

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9wiIVztRIqQ?si=GBgdwQ78k5hbeFDv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6xGqSETroqA?si=4C1GPgXi-AksR_oO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0Ww1YIIUe4?si=cQ-Gkh9UCJABuPZU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.
5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NTQGoOOiJzs?si=zbZwflEfXgBY3qbs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Disable Any Windows 11 Feature Using ViVeTool

 File Explorer tabs are more useful than you think. But if you use another File Explorer program or can make do without it, ViVeTool is a great utility to disable/enable it. Moreover, it is completely free, and you can even enable other experimental features of Windows 11.

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
<li><a href="https://screen-recording.techidaily.com/updated-enhancing-call-clarity-silencing-distractions-for-2024/"><u>[Updated] Enhancing Call Clarity Silencing Distractions for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-expert-tips-for-crafting-immersive-soundscapes-in-youtube-for-2024/"><u>[Updated] Expert Tips for Crafting Immersive Soundscapes in YouTube for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-capture-games-effortlessly-with-nvidia/"><u>2024 Approved Capture Games Effortlessly with NVIDIA</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-instagram-exit-wave-analysis/"><u>2024 Approved Instagram Exit Wave Analysis</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/beat-the-hype-with-budget-friendly-apple-vision-xr-companions-zdnet-review/"><u>Beat the Hype with Budget-Friendly Apple Vision XR Companions - ZDNet Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-conversion-of-mov-files-to-vob-format-move-itcom/"><u>Free Online Conversion of MOV Files to VOB Format - Move-it.com</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-honor-x50-gt-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Honor X50 GT Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/les-12-maitres-du-montage-video-en-haute-volee-en-2024-decouvrez-avec-movavi/"><u>Les 12 Maîtres Du Montage Vidéo en Haute Volée en 2024 - Découvrez Avec Movavi</u></a></li>
<li><a href="https://win-able.techidaily.com/overcoming-black-ops-cold-war-error-code-0xc0000005-a-step-by-step-solution/"><u>Overcoming Black Ops Cold War Error Code 0Xc0000005 - A Step-by-Step Solution</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/95642493-9781786780706-the-healing-power-of-life-alignment/"><u>The Healing Power of Life Alignment | Free Book</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforma-su-contenido-flash-al-formato-mp4-por-internet-sin-gastos-guia-paso-a-paso-solucion-gratuita-de-movavi/"><u>Transforma Su Contenido Flash Al Formato MP4 Por Internet Sin Gastos, Guía Paso a Paso - Solución Gratuita De Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726221843560-3g2-mp4-movavi/"><u>구독 없이 3G2 파일을 무료 MP4 형식으로 전환하는 - Movavi 소프트웨어</u></a></li>
</ul></div>

