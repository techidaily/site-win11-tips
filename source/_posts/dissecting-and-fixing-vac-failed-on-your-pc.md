---
title: Dissecting and Fixing VAC Failed on Your PC
date: 2024-08-23T07:09:09.054Z
updated: 2024-08-24T07:09:09.054Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Dissecting and Fixing VAC Failed on Your PC
excerpt: This Article Describes Dissecting and Fixing VAC Failed on Your PC
keywords: VAC Failure,PC Repair Guide,System Boot Troubleshooting,Diagnosing VAC Errors,Hardware Fix Strategies,Technical Tips for PC Fans,Restarting Computer Issues
thumbnail: https://thmb.techidaily.com/662c307b916403e88dc997e74395824da6bd2c6533fd74096afaf9205f685325.jpg
---

## Dissecting and Fixing VAC Failed on Your PC

 When you attempt to matchmake in a Steam game, do you receive the error message "VAC was unable to verify your game session"? In most cases, it occurs when you try to enter the game with a cheat or hack enabled. However, Steam sometimes raises a false flag when you're simply trying to play fair, resulting in this error message.

 But what exactly is this VAC that couldn't verify your game session? In this article, we'll discuss this error in detail and offer solutions you can use to fix it.

## What Does the "VAC Was Unable to Verify Your Game Session" Error Mean?

 To understand what this error message represents, you must understand how VAC works. VAC, known as Valve's Anti-Cheat, is a software program developed by the same company, Valve, that owns many popular Steam games, including Counter-Strike, Day of Defeat, etc.

 This software works with Steam and hunts down players who attempt to enter the game session with a hack or cheat software enabled. Not only does it detect an unallowed program or script running with the game, but it also detects any changes to the game files. Once the software detects unfair play, it immediately bans the user.

 In light of this, the error message "VAC was unable to verify your game session" means that VAC, an anti-cheat program, was unable to verify your game session because it detected some tempering in your game files or detected a third-party program or script that attempted to alter the game processing.

 When you encountered this error, did you run such a program or make unapproved changes to the game files? If so, make sure VAC hasn't banned you.

## First, Ensure You Aren't VAC-Banned

 The most common reason for this error message is that you might have received a VAC ban. Therefore, it's a good idea to rule this out first. Follow these steps to confirm:

1. Log in to your Steam account.
2. In the top-left corner, click **Steam** and select **Settings**.
3. In the left sidebar, click the **Account** tab.
4. In the right pane, check the **VAC Status**.  
![Steam Account Settigns Showing No Vac Bans on the Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/steam-account-settigns-showing-no-vac-bans-on-the-account.jpg)

 If it says **"No VAC Bans on Account,"** there are no VAC bans on your account. If it says you're banned, go to the [VACBanned website](http://www.vacbanned.com/engine/check), enter your SteamID in the top-right search bar, and hit **Enter**. The VACBanned engine checker will show you when you received the VAC ban.

![Checking the VAC Status of an Account on VACBanned Website by Entering the Steam ID in the Search Bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Image-2-Checking-the-VAC-Status-of-an-Account-on-VACBanned-Website-by-Entering-the-Steam-ID-in-the-Search-Bar.jpg)

 If it was placed recently and you are confident that you did not do anything wrong, it might automatically be removed once the investigation by the Steam support team completes. Regarding Steam support's investigation timeframe, no information has been provided on how long it takes. So, let's wait a couple of days and see what happens.

 Nevertheless, if it's been there for a long time, the investigation might already be complete. There is no option to appeal VAC bans, so you may only have the option of creating a new account.

## Now, Perform Some Preliminary Checks…

 If you're not banned, perform the following preliminary checks to rule out minor glitches:

* Leave your game session, restart the game, and try to matchmake again.
* Restart the Steam client.
* Re-login to your Steam account after logging out.
* Restart your Windows device.
* [Disable Windows Defender](https://www.makeuseof.com/how-to-turn-off-windows-defender/) or any other antivirus you use, or whitelist the Steam client and directory folders.
* If you have been using a VPN, now is the time to turn it off.
* Ensure your Steam client and game are up-to-date.
* Ensure your operating system is up-to-date.

 If none of these checks help, it's time to dig deeper.

## 1\. Run Steam as an Administrator

 VAC may not verify your game session because Steam cannot access specific game files. To rule this out, give Steam exclusive access to all system files by running it as an administrator. To do that, right-click the Steam shortcut and click **Run as administrator**.

![Running Steam Client as Administrator by Right-clicking on Steam Shortcut on Windows Desktop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Image-3-Running-Steam-Client-as-Administrator-by-Right-clicking-on-Steam-Shortcut-on-Windows-Desktop.jpg)

 Apply the following fix if you continue to receive the error.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Run the Game as an Administrator

 For the same reason we gave Steam client administrator rights, you should run the CS: Go or any other game as an administrator to ensure that limited access isn't resulting in the error under discussion. Here are the steps you need to follow:

1. Paste the following path in Windows File Explorer:  
`C:\Program Files (x86)\Steam\steamapps\common`
2. Open the folder of the game you're having trouble with.
3. Find the game's executable file.
4. Right-click on it and select **Properties**.  
![Opening Properties Option by Right-clicking on the Counter Strike’s Executable File after Locating It in the File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Image-4-Opening-Properties-Option-by-Right-clicking-on-the-Counter-Strike’s-Executable-File-after-Locating-It-in-the-File-Explorer.jpg)
5. Navigate to the **Compatibility** tab in the **Properties** window.
6. Check the box for **Run this program as an administrator**.  
![Checking the Box for Run this Program as an Administrator by Navigating to Compatibility Tab in the Properties Window of Counter Strike’s Executable File in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Image-5-Checking-the-Box-for-Run-this-Program-as-an-Administrator-by-Navigating-to-Compatibility-Tab-in-the-Properties-Window-of-Counter-Strike’s-Executable-File-in-Windows.jpg)

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Rule Out Interference From Other Programs

 Although you can only be banned or get the error under discussion when you try to enter a game session hosted on a VAC-secured server with a cheat program, it is possible to encounter this error even when playing other single-player or offline games where cheating is allowed.

 So, ensure you aren't running a cheat program for any Steam game other than CS: GO. If you're, you should temporarily close it. Likewise, you should ensure that no such background apps or tasks are running, which you may not see, but could be causing the error. For reference, see our guide on [how to disable background apps in Windows 11](https://www.makeuseof.com/windows-11-disable-background-apps/).

 If the error persists after closing such programs, apply the next fix.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Verify the Integrity of Game Files

 The "VAC was unable to verify your game session" error may occur due to improper installation of the game files. It means you may not be running any cheat programs or making unauthorized changes to the game files, but Steam may consider the improper installation of files a violation of VAC guidelines. As a result, you receive an error message.

 To rule out this possibility, you should verify the integrity of game files, which can be done through Steam. Here are the steps you need to follow:

1. Log in to your Steam account.
2. Right-click the game you're encountering the error with and select **Properties**.
3. In the left sidebar, click the **Local Files** tab.
4. In the right-pane, click **Verify integrity of game files**.  
![Clicking on Verify Integrity of Games Files under Local Files Tab in Game’s Properties Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Image-6-Clicking-on-Verify-Integrity-of-Games-Files-under-Local-Files-Tab-in-Game’s-Properties-Window.jpg)

## 5\. Switch to Offline Mode and Back to Online Mode

 If verifying the integrity of game files does not work, attempt a rather unusual but handy fix by switching between Steam's offline and online modes once. Performing this step will ensure that any temporary issues with the game's connectivity aren't the cause of the problem. Here are the steps you need to follow:

1. Start Steam and log in.
2. In the top-left corner, click the **Steam** tab.
3. Click on **Go Offline**.  
![Click on the Go Offline Button under the Steam Tab in Steam App to Turn on Offline Mode in Steam Client](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/click-on-the-go-offline-button-under-the-steam-tab-in-steam-app-to-turn-on-offline-mode-in-steam-client.jpg)
4. Click **Enter Offline Mode**.
<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Take a few minutes to wait.
6. Go back to the **Steam** tab, and click **Go Online**.
7. Click **Leave Offline Mode**.  
![Click on Leave Offline Mode after Clicking on Go Online Button under the Steam Tab in Steam App to Leave Offline Mode in Steam Client-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/click-on-leave-offline-mode-after-clicking-on-go-online-button-under-the-steam-tab-in-steam-app-to-leave-offline-mode-in-steam-client-1.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Repair the Steam Library Folder

 Repairing the Steam Library folder also has a good chance of resolving the issue. Follow these steps to run the repair as a last resort:

1. Log in to your Steam account.
2. In the top-left corner, click **Steam** and select **Settings**.
3. In the left sidebar, click the **Downloads** tab.
4. In the right pane, click **Steam Library Folders**.  
![Opening the Steam Library Folder by Clicking on the Downloads Tab in Steam Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Image-9-Opening-the-Steam-Library-Folder-by-Clicking-on-the-Downloads-Tab-in-Steam-Settings.jpg)
5. Next to a storage location, click on the **three horizontal dots**.
6. Hit **Repair Folder**.  
![Repairing the Steam Folder by Clicking on Three Horizontal Dots Next to Storage Location in Steam Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Image-10-Repairing-the-Steam-Folder-by-Clicking-on-Three-Horizontal-Dots-Next-to-Storage-Location-in-Steam-Settings.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
 Run Steam again once the folder has been repaired to see if the issue has been resolved.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Reinstall Any Error-Prone Games and Steam

 If the issue persists, it may be necessary to reinstall the games you are experiencing the error with. If you're not sure how to do that, check our guide on [how to uninstall and reinstall Steam games](https://www.makeuseof.com/how-to-uninstall-steam-games-reinstall/) for more information.

 If that doesn't work, you'll have to reinstall Steam itself. Uninstalling Steam will erase all your games, including their saves. As such, be sure to back up your saves or ensure they're uploaded to Steam Cloud before continuing.

## Getting Back Into Your Steam Games

 We hope our fixes will help you fix the "VAC was unable to verify your game session" error.

 When you attempt to matchmake in a Steam game, do you receive the error message "VAC was unable to verify your game session"? In most cases, it occurs when you try to enter the game with a cheat or hack enabled. However, Steam sometimes raises a false flag when you're simply trying to play fair, resulting in this error message.

 But what exactly is this VAC that couldn't verify your game session? In this article, we'll discuss this error in detail and offer solutions you can use to fix it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>