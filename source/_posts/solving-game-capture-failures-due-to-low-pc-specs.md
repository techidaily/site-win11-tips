---
title: Solving Game Capture Failures Due to Low PC Specs
date: 2024-12-21T02:02:38.795Z
updated: 2024-12-22T04:47:07.833Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solving Game Capture Failures Due to Low PC Specs
excerpt: This Article Describes Solving Game Capture Failures Due to Low PC Specs
keywords: Fix PC Graphics Lag,Enhance Gaming Performance,Optimize Low-End PCs,Resolve Inadequate Capture,Boost Game Play Specs,Upgrade PC for Games,Improve PC Capability
thumbnail: https://thmb.techidaily.com/c774dca3ab72d0dd337e416f6694c83a3258e570406ced6f2d33110479fdae4a.jpg
---

## Solving Game Capture Failures Due to Low PC Specs

 Many users utilize the Xbox Game Bar app pre-installed with Windows for recording game clips. However, some users can’t record anything with the Game Bar because of an error that says, “sorry, your PC doesn't meet the hardware requirements for captures.” That error message can appear within Settings or when users select to record.

 The error message highlights a PC doesn’t meet system requirements for Game Bar recording. Yet, this error often arises for users who’ve utilized Game Bar’s recording on their PCs before. This is how you can fix the “PC doesn't meet the hardware requirements for captures” error in Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Enable Game DVR With Game DVR Config

 Game DVR Config is third-party software with which some users have resolved the “PC doesn't meet the hardware requirements for captures” error. That software includes settings users can select to enable Game DVR along with audio and microphone capture.

 Here is how you can enable Game DVR with that software:

1. Open the [Game DVR Config](https://github.com/FunkyFr3sh/GameDVR%5FConfig/releases) page.
2. Click the **GameDVR\_Config.exe** download link.
3. Bring up Windows Explorer and the Downloads folder or other directory containing the Game DVR file.
4. Double-click the **GameDVR\_Config** file.
5. Select the **Enable Game DVR (Win+G)** checkbox.  
![The Game DVR Config software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/game-dvr-config.jpg)
6. Click the **Force software MFT** checkbox to select that setting.

7. Exit Game DVR Config and [open Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/).
8. Look for the Broadcast DVR server on the **Processes** tab. Right-click Broadcast DVR Server and select **End task** if you can find that process.

## Edit the Control Registry Key

 Editing the Control registry key is a fix that’s worked for some users. Try editing that key like this:

1. To activate Run, simultaneously press **Win** \+ **R**.
2. Type **regedit** within the Run command box and press the **Enter** key.
3. Clear the text in the address bar and input this registry key location there:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control`
4. If there isn’t a **PortableOperatingSystem** DWORD already, right-click on the **Control** key and select **New** and **DWORD**. Input **PortableOperatingSystem** within the new key’s text box.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/new-key-options.jpg)
5. Double-click on the **PortableOperatingSystem** DWORD in the Control key.

6. Delete the **0** number and input **1** within the **Value data** box.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window.jpg)
7. Set the value by clicking **OK** inside the Edit DWORD window.
8. Then close out of the Registry Editor app and restart Windows.

## Update Your Graphics Adapter’s Driver

 An outdated or faulty graphics driver might be causing this recording issue on your PC. Try installing the latest graphics driver for your GPU if you haven’t updated it in a while (or ever). This guide tells you [how to update a PC’s graphics driver in Windows](http://www.makeuseof.com/update-graphics-drivers-in-windows-10/).

![The NVIDIA graphics driver download page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/nvidia-driver-download.jpg)

## Enable the Windows Game Recording and Broadcasting Policy

 Group Policy Editor includes a Game Recording and Broadcasting policy that prevents recording when disabled. So, Windows Pro and Enterprise users must make sure that the Game Recording and Broadcasting policy is set to enabled. Do note that Windows Home doesn’t include the Group Policy Editor.

 Here is how you can enable that policy:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/) and double-click **Computer Configuration** when it appears.
2. Double-click **Administrative Templates** \> **Windows Components**.
3. Select **Windows Game Recording and Broadcasting** in Group Policy’s sidebar.
4. Then double-click on the **Enables or disables Windows Game Recording and Broadcasting** policy.  
![The Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/group-policy-editor.jpg)
5. Click **Enabled** if that policy is disabled.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Select **Apply** to enable the recording policy and **OK** to close the window.  
![The Enables or disables Windows Game Recording and Broadcasting policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-game-and-recording-policy-window.jpg)
7. Close Group Policy Editor, bring up your Start menu and select **Power** \> **Restart**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Erase Data in the GameDVR Registry Key

 Corrupted GameDVR entries within the registry can cause the “PC doesn't meet the hardware requirements for captures” error. You can fix that by deleting DWORDs and strings in the GameDVR registry key, which will automatically regenerate. However, we still recommend users back up the registry before applying this potential solution.

 You can erase data from the GameDVR registry key as follows:

1. Open Registry Editor with Run, as covered in the first couple of steps of resolution two.
2. Go to this GameDVR registry key location:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\GameDVR`
3. Select all DWORDs and strings within the GameDVR key by holding the **Ctrl** key and clicking on them.
4. Then right-click and select **Delete** \> **Yes**.  
![the-delete-option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-delete-option.jpg)
5. Click the Start menu’s Power button and select **Restart**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qNrOsjUdRz0?si=xGzhmNmtgxNTsRxN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get Recording Again With the Xbox Game Bar

 The potential solutions covered here are widely confirmed to resolve the “PC doesn't meet the hardware requirements for captures” by users who’ve needed to fix that issue. So, it’s most likely applying the potential fixes above will resolve that Game Bar recording issue on your Windows laptop or desktop. Then you can record video while gaming with the Game Bar’s recording feature again.

 The error message highlights a PC doesn’t meet system requirements for Game Bar recording. Yet, this error often arises for users who’ve utilized Game Bar’s recording on their PCs before. This is how you can fix the “PC doesn't meet the hardware requirements for captures” error in Windows 10 and 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-video-recordings.techidaily.com/elevating-video-discoverability-with-strategic-tagging-on-youtube-for-2024/"><u>Elevating Video Discoverability with Strategic Tagging on Youtube for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/facebook-video-downloader-winmacosmobile-power-up-for-2024/"><u>Facebook Video Downloader Win/macOS/Mobile Power-Up for 2024</u></a></li>
<li><a href="https://win-rankings.techidaily.com/guia-passo-a-passo-clonagem-de-hd-noble-em-sistemas-windows-1011-com-inicializacao-simplificada/"><u>Guia Passo a Passo: Clonagem De HD Noble Em Sistemas Windows 10/11 Com Inicialização Simplificada</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-users-through-domain-based-biometric-settings-in-w11/"><u>Guiding Users Through Domain-Based Biometric Settings in W11</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/harnessing-the-power-of-cookiebot-technology-for-marketing-insights/"><u>Harnessing the Power of Cookiebot Technology for Marketing Insights</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-dji-mini-and-air-2-mixing-made-easy-with-20-free-luts/"><u>In 2024, DJI Mini & Air 2 Mixing Made Easy with 20 Free LUTS</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-premium-aerial-imagery-crews-the-10-drones/"><u>In 2024, Premium Aerial Imagery Crews The #10 Drones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-touch-typing-features-in-windows/"><u>Navigating Through Touch Typing Features in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-the-unknown-component-alert-from-windows/"><u>Removing the Unknown Component Alert From Windows</u></a></li>
<li><a href="https://win-info.techidaily.com/step-by-step-guide-successfully-adding-and-configuring-new-pc-hardware-in-windows-tips-from-yl-computing/"><u>Step-by-Step Guide: Successfully Adding and Configuring New PC Hardware in Windows - Tips From YL Computing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-quintessence-of-modern-design-tools-microsoft-paints-upgrades/"><u>The Quintessence of Modern Design Tools - Microsoft Paint's Upgrades</u></a></li>
<li><a href="https://win-docs.techidaily.com/top-8-secure-password-tools-compatible-with-windows-11/"><u>Top 8 Secure Password Tools Compatible with Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/venture-into-virtual-worlds-a-close-look-at-lgs-360-tech-for-2024/"><u>Venture Into Virtual Worlds A Close Look at LG's 360 Tech for 2024</u></a></li>
</ul></div>

