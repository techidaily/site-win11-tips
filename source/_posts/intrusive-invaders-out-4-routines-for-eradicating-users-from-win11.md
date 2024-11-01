---
title: "Intrusive Invaders Out!: 4 Routines for Eradicating Users From Win11"
date: 2024-10-26T17:48:37.322Z
updated: 2024-11-01T19:44:43.161Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Intrusive Invaders Out!: 4 Routines for Eradicating Users From Win11"
excerpt: "This Article Describes Intrusive Invaders Out!: 4 Routines for Eradicating Users From Win11"
keywords: Win11 User Removal,Secure Win11,Win11 Privacy Protect,Eliminate Win11 Intrusion,Win11 Cleanliness,Remove Win11 Trackers,Win11 Optimize Performance
thumbnail: https://thmb.techidaily.com/1a08c8dedd48664d90b507bda304483e40c9a1d2dac0696255a8394fc453f16e.jpg
---

## Intrusive Invaders Out!: 4 Routines for Eradicating Users From Win11

 You can create multiple users account on Windows 11 for yourself and others. This allows you to create different spaces for your personal and work tasks and enable others to share your computer and have their own spaces.

 But what if you need to stop someone from accessing their account without deleting it? While you can temporarily disable a user account on Windows 11 using the block sign-in option, there are a few other ways to disable specific or all user accounts on Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Disable a User Account in Windows Settings

 Windows allows the system administrator to manage user accounts on Windows 11\. Not only can you[add a local user account](https://www.makeuseof.com/windows-11-create-local-user-account/) there, but you can also block sign-in to disable an account temporarily.

To disable user accounts via Settings:

1. Press**Win + I** to open the**Settings** panel.
2. In the left pane, click on the**Accounts** tab.  
![windows 11 settings account family](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-account-family-1.jpg)
3. Next, in the right pane, scroll down and click on**Family** .
4. Under**Your family** , scroll down and click on the account you want to disable.  
![windows 11 settings account family block sign in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-account-family-block-sign-in-1.jpg)
5. Next, click the**Block sign in** button and click**Block** in the confirmation dialog.  
![windows 11 settings account family allow sign in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-account-family-allow-sign-in-1.jpg)
6. If you need to enable the user account again, click the**Allow sign in** button and click**Allow** to confirm the action.

 Note that you must log in to your administrator account to make changes to user accounts. Also, you can only block sign-in for members of**Your family** in the Family groups from Settings. If you need to disable a local user account, you must use the PowerShell and Command Prompt methods below.

## 2\. How to Disable a User Account Using Windows PowerShell

 If you need to disable and enable user accounts frequently, PowerShell can help you do it efficiently. To do this, you can use the Disable-LocalUser cmdlet and specify the user account name you want to disable.

To disable a user account using PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Terminal (Admin)** . It will open Windows Terminal with PowerShell set as the default profile.
3. If not, click the drop-down icon in the**Terminal** tabs section and select**Windows PowerShell** .  
![powerhsell user account list view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/powerhsell-user-account-list-view.jpg)
4. Next, type the following command to find all the user accounts on your PC:  
`Get-LocalUser`
5. Locate the user account name in the**Name** column.

1. Next, type the following command to disable the specified user account:  
`Disable-LocalUser -Name &ldquo;NewUser&rdquo;`
2. In the above command, replace**NewUser** with the user account name you want to disable.  
![powerhsell user account disable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/powerhsell-user-account-disable.jpg)
3. PowerShell will not return a success message after the user account is disabled.
4. If you need to enable the account again, type the following command and press Enter:  
`Enable-LocalUser -Name &ldquo;NewUser&rdquo;`
5. In the above command replace NewUser with your user account name.

 When disabled, the user account will be hidden from your lock screen. To verify the same, press**Win + L** to[lock your Windows 11 computer](https://www.makeuseof.com/windows-11-ways-to-lock/) . Next, double-click on the lock screen to view the login screen. If disabled, the user account will appear on the lower left side of your screen.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134247/18498" target="_top" id="2134247">
  <img src="//a.impactradius-go.com/display-ad/18498-2134247" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134247/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Disable a User Account Using the Command Prompt

 Another way to disable a local user account is via the Command Prompt. It is a command-line utility that you can use to disable Microsoft or local user accounts.

To disable a user account using Command Prompt:

1. Press**Win + R** to open**Run** .
2. Type**cmd** in the**Run** box. Next, press**OK** while holding the**Ctrl + Shift** key to open the elevated Command Prompt. Click**Yes** if prompted by User Account Control.
3. In the Command Prompt window, type the following command to find all the available user accounts on your PC:  
`net user`
4. Locate the user account name in the return list.  
![command prompt net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/command-prompt-net-user.jpg)
5. Next, type the following command to disable the specified user account:  

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148634/16836" target="_top" id="2148634">
  <img src="//a.impactradius-go.com/display-ad/16836-2148634" border="0" alt="https://techidaily.com" width="80" height="31"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148634/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`net user NewUser /active:no`
6. In the above command, replace**NewUser** with the user account name you want to disable.  
![command prompt net user disable account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/command-prompt-net-user-disable-account.jpg)
7. Next, type**exit** and press Enter to close Command Prompt.
8. If you need to enable the account again, execute the following command:  
`net user NewUser /Active:yes`
9. Make sure to replace NewUser with the account name you want to enable.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052060/7443" target="_top" id="2052060">
  <img src="//a.impactradius-go.com/display-ad/7443-2052060" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052060/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Disable a User Account From the Computer Management Console

 The Computer Management Console gives system administrators access to advanced tools such as Task Scheduler, Event Viewer, Device Manager, etc. Another useful Computer Management feature is Local Users and Groups.

 Local User and Groups lets you manage user accounts and groups on your Windows computer. While the Computer Management console is available on all versions of Windows, Local User and Groups is only available on the Pro, Edu, and Enterprise edition of the OS.

 To disable user accounts using the Local Users and Groups Management console:

1. Click on the**Search icon** in**Taskbar** .
2. Type**computer management** and click on**Computer Management** from the search result.
3. In the**Computer Management** console, expand**System Tools** .  
![computer management local users groups users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/computer-managemnet-local-users-groups-users.jpg)
4. Next, locate and select**Local Users and Groups.**
5. Select the**Users** folder**.**

1. In the right pane, you can view all the user accounts on your PC.
2. To disable a user account, right-click on the**User Account Name** and select**Properties** .  
![computer management local users groups users account is disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/computer-managemnet-local-users-groups-users-account-is-disabled.jpg)
3. In the**Properties** dialog, select the**Account is disabled** option.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134497/18498" target="_top" id="2134497">
  <img src="//a.impactradius-go.com/display-ad/18498-2134497" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134497/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Click**Apply** and**OK** to save the changes.
5. To enable the account gain, uncheck the**Account is disabled** option and click**Apply** and**OK** .

### Disable User Account Using Local Users and Groups on Windows 11 Home

 Windows 11 Home users will have to rely on a third-party tool to disable a user account via the Local User and Groups console. Lusrmgr is a third-party snap-in that offers similar functionalities as the Local Users and Groups Management console.

 To install the tool, follow our guide to[enable Local User and Group Management on Windows 11](https://www.makeuseof.com/windows-home-edition-enable-local-user-group-management/) . Once done, follow the steps below:

1. Double-click on the**lusrmgr.exe** file to launch the application.
2. In the**Local users and groups** dialog, select**Users** .
3. Right-click on the user account you want to disable and select**Edit** .  
![run lusrmgr exe file edit account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/run-lusrmgr-exe-file-edit-account.jpg)
4. Next, open the**Account** tab.
5. Select the**Account is disabled** option.  
![run lusrmgr exe file edit account disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/run-lusrmgr-exe-file-edit-account-disabled.jpg)
6. Click**Apply** and**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399">
  <img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## There Are Many Ways to Disable a User Account on Windows 11

 Disabling a user account lets you restrict access to a specific user account without deleting the account completely. This way, if you need to restore the account at a later stage, you can enable it and continue using it without restoring files and folders.

 That said, removing a user account on Windows 11 is not a complicated process. Just log in to your administrator account and block sign-in or remove user accounts from Settings, and you're pretty much done.

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
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-rectification-of-injustice/"><u>[Updated] In 2024, Rectification of Injustice</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-restore-shadows-in-iphone-hdr-footage-using-premiere-pro-techniques-for-2024/"><u>[Updated] Restore Shadows in iPhone HDR Footage Using Premiere Pro Techniques for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movaviweb-png/"><u>無料で使えるMovaviのWeb-ベースPNG画像編集・変換ツール - 詳しく見てみませんか？</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/beste-kostenlose-umwandlung-von-dvd-in-mp3-fur-windows-und-macos-im-jahr-2023-empfehlungen/"><u>Beste Kostenlose Umwandlung Von DVD in MP3 Für Windows Und macOS Im Jahr 2023 - Empfehlungen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cambia-i-file-wma-in-formato-webm-gratuitamente-su-internet-guida-rapida-di-movavi/"><u>Cambia I File WMA in Formato WebM Gratuitamente Su Internet: Guida Rapida Di Movavi</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/capturing-brilliance-essential-angles-in-iphone-photography-for-2024/"><u>Capturing Brilliance Essential Angles in iPhone Photography for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convert-mov-files-to-ogg-format-for-free-online-expert-results-with-movavi/"><u>Convert MOV Files to OGG Format for Free Online - Expert Results with MOVAVI</u></a></li>
<li><a href="https://techtrends.techidaily.com/convertir-formato-de-archivo-aifc-a-aiff-online-sin-costo-alguno-con-movavi/"><u>Convertir Formato De Archivo AIFC a AIFF Online Sin Costo Alguno Con Movavi</u></a></li>
<li><a href="https://some-approaches.techidaily.com/effortless-conversion-of-youtube-videos-for-iphone-top-tools-for-ios-device-compatibility/"><u>Effortless Conversion of YouTube Videos for iPhone - Top Tools for iOS Device Compatibility</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/elite-faster-imagery-screen-reader-for-2024/"><u>Elite Faster Imagery Screen Reader for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/fixing-cyberpunk-2077-pc-stability-expert-tips-to-prevent-game-crashes/"><u>Fixing Cyberpunk 2077 PC Stability: Expert Tips to Prevent Game Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/geevensamenvoeging-waardevollen-gratuite-programmas-en-apps-voor-beste-resultaten-online-of-desktop-gebruikers/"><u>Geevensamenvoeging Waardevollen Gratuite Programma's en Apps Voor Beste Resultaten, Online of Desktop-Gebruikers</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-is-mega-mewtwo-the-strongest-pokemon-on-apple-iphone-15-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, Is Mega Mewtwo The Strongest Pokémon On Apple iPhone 15 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/moviva-la-solucion-perfecta-para-cambiar-tu-video-swf-al-formato-avi-rapidamente-y-sin-gastar-dinero/"><u>MoviVa: La Solución Perfecta Para Cambiar Tu Vídeo SWF Al Formato AVI Rápidamente Y Sin Gastar Dinero.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforma-tu-fotografia-raw-a-png-de-manera-gratuita-y-facil-con-la-ayuda-de-movavi/"><u>Transforma Tu Fotografía RAW a PNG De Manera Gratuita Y Fácil Con La Ayuda De Movavi</u></a></li>
</ul></div>

