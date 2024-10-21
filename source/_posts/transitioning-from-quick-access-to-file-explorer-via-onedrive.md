---
title: Transitioning From Quick Access to File Explorer via OneDrive
date: 2024-10-18T03:27:49.531Z
updated: 2024-10-20T17:00:34.866Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Transitioning From Quick Access to File Explorer via OneDrive
excerpt: This Article Describes Transitioning From Quick Access to File Explorer via OneDrive
keywords: Quick Access Shift,OneDrive Navigation,File Explorer Transition,Access to OneDrive,File Explorer Switching,Direct File Browsing,OneDrive Explore Change
thumbnail: https://thmb.techidaily.com/45bc41dfd22bb4252a227dcc20488f6faf42f4a30eaffbfeaeadce5abdbcdc1d.png
---

## Transitioning From Quick Access to File Explorer via OneDrive

 When you launch Windows File Explorer, it automatically takes you to the "Quick Access" view. This page displays shortcuts to recently accessed folders and files and lists your favorite folders. It might be convenient for some users but not for others who prefer easy access to their cloud storage.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Use the Folder Options

 If you want to make OneDrive the starting point of your File Explorer, you can do so using folder options. Here's how to do it:

1. Open the Start menu and type **File Explorer** in the search box. When the File Explorer icon appears, click it to launch the app. You can also use **Win + E** to open the program quickly.
2. In the File Explorer window, look for **See more** (three dots) at the top. Clicking on it opens the Folder Options dialog box.  
![Open Folder Options in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-folder-options-in-file-explorer.jpg)
3. On the General tab, click the **Open File Explorer to** drop-down menu and select "Username Personal". Here, "Username" refers to your Windows account name.  
![Open File Explorer to OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive.jpg)
4. Click **Apply** \> **OK** to close the dialog box.

 From now on, opening File Explorer will automatically launch OneDrive rather than Quick Access.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136619/26400" target="_top" id="2136619">
  <img src="//a.impactradius-go.com/display-ad/26400-2136619" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136619/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Using the Registry Editor

 You can also use the Registry Editor to set OneDrive as your default File Explorer view. But be warned: if you make an incorrect change to the system registry, you could damage your computer. We recommend [backing up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 Once backed up, follow these steps to make OneDrive the default view:

1. [Open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the text box and hit **Enter**.
3. If you're prompted for permission, select **Yes** to continue. The Registry Editor window will open.
4. In the Registry Editor window, navigate to this path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the right pane, locate and double-click the **LaunchTo** entry. If the entry isn't present, you'll need to create it. For that, right-click on the **Advanced** folder and select **New > DWORD (32-bit) Value**. Name the value "LaunchTo" and press Enter. Doing so will create a new DWORD in the registry.  
![Set File Explorer to Open OneDrive Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/set-file-explorer-to-open-onedrive-using-registry.jpg)
6. Double-click on this newly created value and set its value to **4**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896546/19272" target="_top" id="1896546">
  <img src="//a.impactradius-go.com/display-ad/19272-1896546" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896546/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

## 3\. Using a Reg File

 The third and final method to set OneDrive as the default view involves using a reg file. It contains the necessary instructions that modify the registry on your behalf. So, if you're not comfortable using the registry editor, this is the right way to go.

 To create the reg file, follow these steps:

1. Right-click on your desktop and select **New > Text Document**.
2. Name the file **OneDrive.reg** and hit **Enter**.
3. Now open the file in a text editor such as Notepad.
4. Copy and paste the following code into the text document:  
`<code>Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced]  
"LaunchTo"=dword:00000004`
5. After pasting the given code, click **File** \> **Save as**.
6. In the Save as dialog box, select **All files** from the Save as type drop-down menu and hit Enter. Make sure the file is saved as a **.reg** file and not as a .txt file.  
![Open File Explorer to OneDrive Using REG File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive-using-reg-file.jpg)
7. Double-click the REG file you just created. If you're prompted for permission to change your computer, click **Yes**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886044/19272" target="_top" id="1886044">
  <img src="//a.impactradius-go.com/display-ad/19272-1886044" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886044/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123730/7443" target="_top" id="2123730">
  <img src="//a.impactradius-go.com/display-ad/7443-2123730" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123730/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Set File Explorer to Open OneDrive Instead of Quick Access

 There you have it; three different methods to make OneDrive your default File Explorer view. If you like, you can also change other folder views, such as Downloads or This PC, using the same techniques we discussed above. I hope this guide helped you get things done quickly and easily.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/updated-tackling-facebook-message-video-not-sending-issue-androidiphone/"><u>[Updated] Tackling Facebook Message Video Not Sending Issue (Android/iPhone)</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/a-comprehensive-review-of-watch-dogs-legions-unique-environment-and-storyline/"><u>A Comprehensive Review of Watch Dogs: Legion's Unique Environment and Storyline</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/crafting-a-continuous-youtube-video-stream-from-separate-files-for-2024/"><u>Crafting a Continuous Youtube Video Stream From Separate Files for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/descargue-e-importe-archivos-gratis-desde-jpg-a-png-con-convertidor-de-imagenes-online-movavi/"><u>Descargue E Importe Archivos Gratis Desde JPG a PNG Con Convertidor De Imágenes Online - Movavi</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-icloud-lock-from-your-iphone-13-pro-and-ipad-by-drfone-ios/"><u>In 2024, How to Unlock iCloud lock from your iPhone 13 Pro and iPad?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-will-ispoofer-update-on-nokia-c02-drfone-by-drfone-virtual-android/"><u>In 2024, Will iSpoofer update On Nokia C02 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-m4b-m/"><u>Movavi를 사용한 무료 온라인 M4B, M</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/perfecting-zoom-screen-sharpness-users-handbook/"><u>Perfecting Zoom Screen Sharpness User's Handbook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-12-playermp3-di-file-audio-liberi-e-ottimizzati-per-windows-and-mac/"><u>Top 12 PlayerMP3 Di File Audio Liberi E Ottimizzati Per Windows & Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trasforma-i-file-flac-in-m4a-online-gratuitamente-con-convertitore-di-movavi/"><u>Trasforma I File Flac in M4A Online Gratuitamente Con Convertitore Di Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cr2-tiff-movavi/"><u>컴퓨터에서 무료 CR2 포트라이트를 TIFF로 전환하는 방법 - Movavi</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    