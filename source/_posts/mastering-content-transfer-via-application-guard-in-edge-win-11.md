---
title: Mastering Content Transfer via Application Guard in Edge (Win 11)
date: 2024-12-07T23:00:28.434Z
updated: 2024-12-13T01:56:50.944Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Content Transfer via Application Guard in Edge (Win 11)
excerpt: This Article Describes Mastering Content Transfer via Application Guard in Edge (Win 11)
keywords: Edge App Guard,Win 11 Security,Edge Protection,Data Safe Transfer,Secure App Execution,Content Shielding Edge,Gated Application Tech
thumbnail: https://thmb.techidaily.com/047a2ad015e13f7c67c91065d1e02decc0d409c4804539d81be6e1c6e540ee06.png
---

## Mastering Content Transfer via Application Guard in Edge (Win 11)

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Enable Copy and Paste via Windows Settings

 To enable copy and paste in Application Guard for Edge, follow the steps below:

1. Right-click on Start and select**Settings** from the menu list. For more information, check out our guide on[how to open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Privacy & security** from the left pane.
3. Then click the**Windows Security** option on the right-hand side.
4. On the following screen, select**App & browser control** .
5. Go to the Isolated browsing section and click the link "Change Applications Guard settings."  
![Change Application Guard Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-application-guard-settings.jpg)
6. Search for the**Copy and paste** option, then click the toggle to enable it.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/o-sRtqHdEYY?si=NMTMQVxJsUaoguqh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Enable Copy and Paste Using Registry Editor

 The Windows Registry is another method you can use to copy and paste within Application Guard for Edge on your Windows 11 PC. But, please be aware that editing the registry can have severe consequences if done incorrectly. To be safe,[back up the registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you begin making any changes.

 Follow these steps to enable copy and paste using the Windows Registry Editor:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type "regedit" in the text box and press the Enter key.
3. If UAC prompts appear on the screen, click**Yes** to confirm your action.
4. In the Registry Editor window, navigate to the following location:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi`
5. If you don't find the Hvsi key there, you will need to create it. To do this, right-click on Microsoft and select**New > Key** .

1. In the box that appears, give it the name**Hvsi** , and then hit Enter to save the file.
2. Now right-click on**Hvsi** and select**New > DWORD (32-bit) Value** .  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
3. Put**EnableClipboard** as the name for the new DWORD key, then press Enter.
4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

## Copy and Paste Now Works With Edge Application Guard

 With Application Guard for Edge, your device can remain secure while browsing the web. Unfortunately, certain functionalities such as copy and paste are disabled by default - but don't worry! This guide will explain two methods to activate them quickly and easily.

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
<li><a href="https://fox-direct.techidaily.com/new-the-art-of-testimonials-techniques-for-persuasive-video-credibility/"><u>[New] The Art of Testimonials Techniques for Persuasive Video Credibility</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-from-basic-to-brilliant-a-complete-hdr-portrait-guide/"><u>[Updated] 2024 Approved From Basic to Brilliant A Complete HDR Portrait Guide</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-the-gif-grabbers-handbook-a-comprehensible-guide-to-downloading-twitter-gifs/"><u>[Updated] The GIF Grabber's Handbook A Comprehensible Guide to Downloading Twitter GIFs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conversion-gratuite-apng-vers-line-movavi-votre-solution-simplifiee/"><u>Conversion Gratuite Apng Vers Line - Movavi: Votre Solution Simplifiée</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-conversion-of-ogg-to-mp4-streaming-files-with-movavis-online-tool/"><u>Free Conversion of OGG to MP4 Streaming Files with Movavi's Online Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-mov-to-wav-converter-moveavee/"><u>Free Online MOV to WAV Converter - Moveavee</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratis-online-konverter-tod-em-mov-mit-movavi-kostenloses-umwandeln/"><u>Gratis Online Konverter: TOD Em MOV Mit Movavi - Kostenloses Umwandeln</u></a></li>
<li><a href="https://win-howtos.techidaily.com/gratuit-verbetering-mod-naar-mp4-met-movavi-online-konvertor/"><u>Gratuit Verbetering MOD Naar MP4 Met Movavi - Online Konvertor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guia-completa-para-convertir-archivos-snd-sin-coste-con-movavi-metodo-gratuito-y-sencillo/"><u>Guía Completa Para Convertir Archivos SND Sin Coste Con Movavi: Método Gratuito Y Sencillo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guia-facil-y-rapida-para-cambiar-tu-video-desde-m4v-a-wmv-sin-coste-usando-movavi-online-converter/"><u>Guía Fácil Y Rápida Para Cambiar Tu Vídeo Desde M4V a WMV Sin Coste Usando Movavi Online Converter</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-samsung-galaxy-s24plus-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Samsung Galaxy S24+ | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/1715701271427-mastering-vrecorder-download-install/"><u>Mastering VRecorder Download, Install!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mp4-para-mp3-em-segundo-plano-facil-livre-e-direto-com-o-movavi-perfeito-para-todos/"><u>Mp4 Para Mp3 Em Segundo Plano: Fácil, Livre E Direto Com O Movavi - Perfeito Para Todos</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-top-3d-animation-tools-free-and-premium-options-compared-for-2024/"><u>New Top 3D Animation Tools Free and Premium Options Compared for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/no-cost-enjoyable-9-festive-feasts-in-one-wholesome-film-series-for-2024/"><u>No Cost, Enjoyable 9 Festive Feasts in One Wholesome Film Series for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/quick-and-effortless-way-to-download-youtube-as-high-quality-wav-files/"><u>Quick and Effortless Way to Download YouTube as High-Quality WAV Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/toutes-les-etapes-pour-transformer-un-fichier-aac-au-format-ogg-gratuitement-via-le-web-movavi/"><u>Toutes Les Étapes Pour Transformer Un Fichier AAC Au Format Ogg Gratuitement via Le Web - Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-audio-video-interchange-file-format-avi-from-asf-at-no-cost-movavis-expert-guide/"><u>Transform Audio-Video Interchange File Format (AVI) From ASF at No Cost - Movavi's Expert Guide</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-aiff-to-mp3-an-experts-methodology-for-audio-conversion/"><u>Updated 2024 Approved AIFF to MP3 An Experts Methodology for Audio Conversion</u></a></li>
</ul></div>

