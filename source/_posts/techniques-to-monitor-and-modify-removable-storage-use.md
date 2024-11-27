---
title: Techniques to Monitor and Modify Removable Storage Use
date: 2024-11-25T17:34:47.165Z
updated: 2024-11-27T16:19:42.185Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques to Monitor and Modify Removable Storage Use
excerpt: This Article Describes Techniques to Monitor and Modify Removable Storage Use
keywords: Removable Media Tracking,USB Usage Control,Portable Storage Management,Data Loss Prevention,Device Access Limitation,Storage Security Monitoring,File Transfer Safeguarding
thumbnail: https://thmb.techidaily.com/d021ea19d35ef3673abfe0bc9bdff457eb34791e55514d7bc0ce5bafaca00aee.jpg
---

## Techniques to Monitor and Modify Removable Storage Use

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-G7cU8dYvuI?si=JaKqRcW6qq9CDvty&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

### Using the Local Group Policy Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 The Registry Editor is another reliable tool you can use for tweaking system settings and troubleshooting PC issues.

 However, this tool is quite sensitive. So, it’s often worth [backing up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before editing its keys.

 Now, here’s how to use the Registry Editor to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **Enter** to open the Registry Editor.
3. Copy-paste the following command into the address bar and press **Enter**:

HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows

 From there, follow these steps:

1. Right-click on the **Windows** folder and select **New > Key**. From there, name this key as **DeviceInstall** and press **Enter**.
2. Right-click on the **DeviceInstall** key and select **New > Key**. Next, name the key as **Restrictions** and press **Enter**.
3. Click the **Restrictions** folder, right-click on a blank space on the right, and then select **New > DWORD (32-bit) Value**. From there, name the value as **DenyRemovableDevices** and press **Enter**.

![Clicking the DenyRemovableDevices value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-DenyRemovableDevices-value.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gyGoQi7hsZk?si=8OcKcPUj2wSBmVZ1&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Prevent Others From Installing Specific Removable Storage Devices

 In some instances, you might want to prevent others from installing specific removable storage devices. So, let’s show you how you can do that using either the LGPE or the Registry Editor.

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
<li><a href="https://screen-recording.techidaily.com/new-mac-tips-capturing-class-notes-efficiently/"><u>[New] Mac Tips Capturing Class Notes Efficiently</u></a></li>
<li><a href="https://screen-recording.techidaily.com/convenient-interaction-starting-a-skype-group-for-windowsmac-users-for-2024/"><u>Convenient Interaction Starting a Skype Group for Windows/Mac Users for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conversion-wma-en-aac-facile-et-gratuite-sur-internet-audioconverterpro/"><u>Conversion WMA en AAC Facile Et Gratuite Sur Internet - AudioConverterPro</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/creating-perfect-instagram-grids-top-10-vendors-ranked/"><u>Creating Perfect Instagram Grids Top 10 Vendors Ranked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/debuter-avec-le-logiciel-gratuit-de-retouche-photo-movavi-essai-en-ligne/"><u>Débuter Avec Le Logiciel Gratuit De Retouche Photo Movavi : Essai en Ligne</u></a></li>
<li><a href="https://win11-tips.techidaily.com/descargue-su-clave-de-activacion-gratuita-para-el-convertidor-de-videos-de-movavi/"><u>Descargue Su Clave De Activación Gratuita Para El Convertidor De Videos De Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easily-convert-your-asf-media-formats-into-anything-you-need-using-the-movavi-video-converter/"><u>Easily Convert Your ASF Media Formats Into Anything You Need - Using the Movavi Video Converter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/en-lukkelse-til-at-snite-din-forhor-med-fjerntrimmning-af-de-uonskede-avlejningsdeler-i-filmen/"><u>En Lukkelse Til At Snite Din Forhør Med Fjerntrimmning Af De Uønskede Avlejningsdeler I Filmen</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-tecno-spark-20-pro-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Tecno Spark 20 Pro To Phone | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-pokemon-go-no-gps-signal-heres-every-possible-solution-on-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go No GPS Signal? Heres Every Possible Solution On Oppo Reno 9A | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-legendaries-are-in-pokemon-platinum-on-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>In 2024, What Legendaries Are In Pokemon Platinum On Xiaomi Redmi Note 12T Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-image-dimensions-the-ultimate-movavi-resize-tutorial/"><u>Mastering Image Dimensions: The Ultimate Movavi Resize Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-unstoppable-methods-to-turn-off-ms-defender/"><u>Mastering Unstoppable Methods to Turn Off MS Defender</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/96476459-9780880507721-meditation-the-first-and-last-freedom/"><u>Meditation: The First and Last Freedom | Free Book</u></a></li>
<li><a href="https://youtube-web.techidaily.com/g-stars-of-online-videos-top-subscription-hits-for-2024/"><u>Rising Stars of Online Videos Top Subscription Hits for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-simples-pour-envoi-de-films-via-courriel/"><u>Techniques Simples Pour Envoi De Films via Courriel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-images-into-webp-format-instantly-and-free-with-movavis-online-tool/"><u>Transform Images Into WebP Format Instantly and Free with Movavi's Online Tool</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-lava-blaze-pro-5g-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Lava Blaze Pro 5G? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726227055668-wavmkv-movavi/"><u>シェア機能付きWAVからMKVへのオンライン無償変換 - Movavi</u></a></li>
</ul></div>

