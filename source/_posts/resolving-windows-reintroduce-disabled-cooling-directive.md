---
title: "Resolving Windows: Reintroduce Disabled Cooling Directive"
date: 2024-10-25T16:05:07.187Z
updated: 2024-11-01T17:28:32.125Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resolving Windows: Reintroduce Disabled Cooling Directive"
excerpt: "This Article Describes Resolving Windows: Reintroduce Disabled Cooling Directive"
keywords: Windows Cooling Fix,Disable Directive Restore,Coolant Windows Update,Hotfix for Windows Cooling,Windows Temp Control Reintroduce,Enhance Windows Cooling,Reactivate Windows Cooler Directive
thumbnail: https://thmb.techidaily.com/d108669ab03559524bb77121c4032c30df350e077c8698244c3203b72aed2547.jpg
---

## Resolving Windows: Reintroduce Disabled Cooling Directive

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
<a href="https://aligracehair.sjv.io/c/5597632/2012429/19272" target="_top" id="2012429">
  <img src="//a.impactradius-go.com/display-ad/19272-2012429" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012429/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399">
  <img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075476/7443" target="_top" id="2075476">
  <img src="//a.impactradius-go.com/display-ad/7443-2075476" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075476/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407">
  <img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-recording.techidaily.com/new-in-2024-premium-macpc-video-recording-software/"><u>[New] In 2024, Premium Mac/PC Video Recording Software</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-prime-software-solutions-for-video-games/"><u>[New] Prime Software Solutions for Video Games</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-construct-playlist-with-film-assortments/"><u>[Updated] Construct Playlist with Film Assortments</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-perfecting-iphone-images-in-dim-light-for-2024/"><u>[Updated] Perfecting iPhone Images in Dim Light for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-your-pc-how-to-turn-on-hyper-v-in-win11/"><u>Boosting Your PC: How To Turn On Hyper-V in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/commentaires-et-recommandations-dexperts-sur-le-logiciel-movavi/"><u>Commentaires Et Recommandations D'experts Sur Le Logiciel Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cortical-remapping-occurs-as-the-brain-adapts-to-changes-in-sensory-input-or-motor-function-following-nerve-damage/"><u>Cortical Remapping Occurs as the Brain Adapts to Changes in Sensory Input or Motor Function Following Nerve Damage.</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-oneplus-ace-2v-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On OnePlus Ace 2V | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratuitamente-converti-dts-online-con-movavi-guida-istantanea/"><u>Gratuitamente Converti DTS Online Con Movavi - Guida Istantanea</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guru-da-conversao-de-audio-transforme-seus-livros-e-podcasts-m4b-em-mp3-com-seguranca-passo-a-passo/"><u>Guru Da Conversão De Audio: Transforme Seus Livros E Podcasts M4B Em MP3 Com Segurança - Passo a Passo</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-nubia-z50s-pro-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Nubia Z50S Pro? | Dr.fone</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-the-ultimate-ranking-of-photo-editors-on-iphones-and-androids/"><u>In 2024, The Ultimate Ranking of Photo Editors on iPhones & Androids</u></a></li>
<li><a href="https://extra-resources.techidaily.com/insider-tips-the-best-5-cameras-for-extended-zoom/"><u>Insider Tips The Best 5 Cameras for Extended Zoom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/istruzioni-semplici-per-ottenere-foto-trasparenti-sfondo-senza-problemi/"><u>Istruzioni Semplici per Ottenere Foto Trasparenti Sfondo Senza Problemi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-download-graca-conversor-de-formatos-em-massa-para-3gp-e-3g2-online-gratuito/"><u>Movavi: Download Graça - Conversor De Formatos Em Massa Para 3GP E 3G2 (Online Gratuito)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/os-8-site-mais-confiaveis-e-populares-para-encanar-filmes-e-series-online-gratuitamente/"><u>Os 8 Site Mais Confiáveis E Populares Para Encanar Filmes E Séries Online Gratuitamente</u></a></li>
<li><a href="https://win11-tips.techidaily.com/qt-mp4-online-movavi/"><u>QT 프로필을 MP4로 바꾸는 방법: Online 무료 송금제 - Movavi</u></a></li>
<li><a href="https://article-files.techidaily.com/sleepy-story-vids-assessment-and-overview/"><u>Sleepy Story Vids Assessment & Overview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/toutes-les-etapes-pour-convertir-un-fichier-vob-en-mp4-gratuitement-guide-detaille-avec-movavi/"><u>Toutes Les Étapes Pour Convertir Un Fichier VOB en MP4 Gratuitement - Guide Détaillé Avec Movavi</u></a></li>
</ul></div>

