---
title: "Virtual Vintage: The DOSBox-X Guide to Classic PC Gaming"
date: 2024-10-31T05:41:23.458Z
updated: 2024-11-06T16:25:14.276Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Virtual Vintage: The DOSBox-X Guide to Classic PC Gaming"
excerpt: "This Article Describes Virtual Vintage: The DOSBox-X Guide to Classic PC Gaming"
keywords: Vintage PC Gaming,Classic Games Play,DOSBox X Tutorials,Virtual Console Experience,Retro Gaming Guide,Emulator for Old Games,XPPC Gaming Revival
thumbnail: https://thmb.techidaily.com/bcb4dab5fca23c5552c696b1f9621ccec9d5240a378ece9f04f489b258c09834.jpg
---

## Virtual Vintage: The DOSBox-X Guide to Classic PC Gaming

 If there's one thing abundant today, that's digital entertainment. You can purchase thousands of titles at most popular digital storefronts and find even more completely free. What's the point of being stuck in the past?

 Still, many older games are worth your time, for they're not "relics" but "classics". Titles like Syndicate and the original X-Com look and sound crude compared to today's games. Still, their addictive gameplay can give a lesson even to most modern triple-A titles. And the only way to play them is with software like DOSBox-X.

## What Is DOSBox-X?

 DOSBox-X is a fork of the popular DOSBox app that enables a modern PC to run software made for older PCs. As its name states, it's primarily designed for Microsoft's ancient Disk Operating System, or DOS for short.

 Unlike the "vanilla" DOSBox, DOSBox-X comes with baked-in emulation for hardware like 3dfx's Voodoo 3D accelerators and various popular audio cards. Thanks to this, you can even install older versions of Windows inside its virtual environment.

 For this article, though, we'll stick to classic DOS games.

## How to Download and Install DOSBox-X

 DOSBox-X is free and available on Windows, Macs, and Linux. In this guide, we'll be using its Windows version.

 Although we'll be using DOSBox-X's Windows 7+ version, the other ones work similarly (more or less). So, you can follow along even if you're on a different OS. Still, expect some variations on DOSBox-X's installation and how you'll manage folders, paths, and "ROMs" (AKA: games).

 Start by downloading the app from [DOSBox-X's official site](https://dosbox-x.com/), then install it or extract it to a folder.

![DOSBox-X executable in folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-executable-in-folder.jpg)

 Depending on the version you've downloaded, and if you installed or extracted it, you'll either find a shortcut to the DOSBox-X app in the **Windows Start menu**/your **Desktop**, or you'll have to visit its folder with your favorite file manager and double-click **dosbox-x.exe** to launch it.

 Keep that in mind, but don't launch the app yet - we first have to do some folder juggling.

## Setting Up Your Storage for DOSBox-X

 Unlike other emulators, DOSBox and its fork we're using, DOSBox-X, emulate a "proper" DOS environment, so you can't simply "load ROMs" into it. Thus, you'll have to allocate some storage to it.

 This is easier than it sounds, for it's as simple as creating two folders.

* The first will be DOSBox-X's "working directory" (think of it as the equivalent of "your current Windows installation").
* The second one will be your primary emulated storage, where you'll place all the classic software you want to access from within DOSBox-X.

 For convenience's sake, we suggest you create a folder with a name like "DOS" or "DOSgames" inside the directory where you keep ROMs for other emulators or the disk/partition/folder where you install your modern games.

![DOS ROMs Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dos-roms-folder.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144274/7443" target="_top" id="2144274">
  <img src="//a.impactradius-go.com/display-ad/7443-2144274" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144274/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click in your file manager's "path" field/bar, and **copy the full path** to the folder you created to the Clipboard. Now's the time to **run DOSBox-X**, and the first thing you'll see won't be the app but a requester for the folder it should use. "Tell it" (paste with **CTRL** \+ **V**) to use the folder you created in the previous step.

![DOSBox-X Working Directory](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-working-directory.jpg)

 Return to your file manager and create another folder inside the previous one. We'll configure DOSBox-X to "see" this folder as its primary storage.

 You can give it a name like **C** since, in Microsoft's OSes, that was, is, and probably will remain the letter usually mapped to a PC's "system drive". However, we believe it's better to name it something like **DriveC**, since it will make more sense if you forget about its existence and happen to run into it in the future.

![DOSBox-X Creating DriveC Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-creating-drivec-folder.jpg)

 Don't close your file manager yet; now is a good time to "prepare" your games. If you have them in compressed archives, extract your games into individual folders within the **C**/**DriveC** folder.

![DOSBox-X DriveC Game Folders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-drivec-game-folders.jpg)

 With almost all file-related tasks behind us, it's time to configure DOSBox-X for some retro gaming.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123512/26400" target="_top" id="2123512">
  <img src="//a.impactradius-go.com/display-ad/26400-2123512" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123512/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Configure DOSBox-X for the Best Experience

 DOSBox-X has lots of settings to tweak, so let's get it set up.

### 1\. Setting Up the Directory

 Turn your attention to DOSBox-X's window. Choose its **Configuration tool** from the **Main** menu entry (or press **F11** \+ **C** on your keyboard).

![DOSBox-X Configuration Editor Menu Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-configuration-editor-menu-entry.jpg)

 Instead of manually mounting the folder you created every time you run DOSBox-X, let's have it always available automatically. For that, we'll have to do some classic AutoExec.BAT editing. Thus, choose the last option in the **Configuration Tool**'s panel, **AUTOEXEC.BAT**.

![DOSBox-X Configuration Tool AutoExec BAT](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-configuration-tool-autoexec-bat.jpg)

 You'll see the currently empty DOSBox-X's **AutoExec**.

 Type **mount** in the first line, press **space** once, and then type **c**, which will be the letter of your primary drive inside DOSBox-X's virtual environment. Press **space** again, and **type the full path** to the folder you've created for use as your virtual C drive.

 If you've copied its path to the **Clipboard** from your file manager, you'll find that you can't paste it, as usual, using the **CTRL** \+ **V** keyboard combination. Instead, use the **Paste Clipboard** button.

![DOSBox-X Configuration Tool Editing AutoExec](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-configuration-tool-editing-autoexec.jpg)

 Press **Enter** and type **c:** in the line underneath. That's how you "change the active drive" inside a DOS environment.

 By including this command in DOSBox-X's **AutoExec**, its virtual environment will "change" the active drive to the storage folder you've mounted in the line directly above. If you don't do that, DOSBox-X will show you its internal "Z" drive every time you launch it, and you'll have to switch to your actual storage manually.

![DOSBox-X Configuration Tool Adding Drive Letter to AutoExec](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-configuration-tool-adding-drive-letter-to-autoexec.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144298/7443" target="_top" id="2144298">
  <img src="//a.impactradius-go.com/display-ad/7443-2144298" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144298/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click **OK** to accept the changes and return to DOSBox-X's **Configuration Tool** panel. Choose **Render** to configure the way DOSBox-X shows graphics.

![DOSBox-X Configuration Tool Render Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-configuration-tool-render-entry.jpg)

 To learn more about all available options, click DOSBox's **Help** button.

![DOSBox-X Configuration Tool Calling For Help](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-configuration-tool-calling-for-help.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037475/7443" target="_top" id="2037475">
  <img src="//a.impactradius-go.com/display-ad/7443-2037475" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 DOSBox's **Help** offers information about all its configuration options, but for now, turn your attention to those under **aspect**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094483/7443" target="_top" id="2094483">
  <img src="//a.impactradius-go.com/display-ad/7443-2094483" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094483/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Setting Up the Aspect Ratio

 For this guide, we'll go for **true**, which keeps the original graphics' **4:3** proportions, but scales them to fit the entire display, adding black bars on the sides of the screen. Check the aspect-related information to see if you'd prefer another approach.

 Click **Close** to exit DOSBox-X's Help file.

![DOSBox-X Configuration Tool Help Aspect Info](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-configuration-tool-help-aspect-info.jpg)

 Click on the button with the **three dots** on the right of the **Aspect** line, and enable the graphics aspect you'd like to use. Then, click **OK** to accept and enable the setting.

![DOSBox-X Configuration Tool Configuring Render Aspect](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-configuration-tool-configuring-render-aspect.jpg)

 Click on **Save** to save all changes. On the new panel that shows up, choose **Use primary config file** and then click on **Save & Restart**.

![DOSBox-X Configuration Tool Choosing Config File and Restarting App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-configuration-tool-choosing-config-file-and-restarting-app.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043638/7443" target="_top" id="2043638">
  <img src="//a.impactradius-go.com/display-ad/7443-2043638" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043638/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Launching Your Retro-Favorites With DOSBox-X

 DOSBox-X is easier if you're familiar with DOS since it works precisely like a DOS-era PC. If you aren't, and interacting with your PC using commands is something new for you, it would be best to check our [beginners guide to the Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/).

 If that sounds like too much work for playing a handful of games, here's a quick recap of the most important commands that can get you up and running in mere minutes:

* You can see a listing of all folders on the "current level" of the storage using the command **dir**.
* You can "enter" a folder using the command **cd FolderName** (for example, **cd duke3d**).
* You can "exit" a folder and return "one level up" in your storage using the command **cd ..**.
* To find all executables in a folder, use the commands **dir \*.exe** and **dir \*.bat**.
* To launch one of those executables, **type its full filename** and press **Enter**.
* You can also use the Tab key to **auto-complete** paths and filenames. If the auto-completed one isn't what you're seeking, press **Tab** again to "cycle" through all entries matching what you've typed.

![DOSBox-X Dir Virtual C Drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-dir-virtual-c-drive.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1883998/19272" target="_top" id="1883998">
  <img src="//a.impactradius-go.com/display-ad/19272-1883998" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1883998/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Let's say you want to launch the classic shareware version of id's genre-defining Doom that you already have in your storage in a folder with the game's name.

 Type **cd doom** to "enter" the game's folder.

![DOSBox-X CD Doom](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-cd-doom.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880960/19272" target="_top" id="1880960">
  <img src="//a.impactradius-go.com/display-ad/19272-1880960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880960/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Type **dir \*.bat** to check for any runnable batch files in the folder. You'll see two, **IAFIX.BAT** and **RUN.BAT**.

![DOSBox-X Dir Bat Doom](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-dir-bat-doom.jpg)

 As you can probably guess from its name, the second one is what you need to launch the game. So, type **run.bat** and press **Enter**.

![DOSBox-X Doom Selecting Audio System](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-doom-selecting-audio-system.jpg)

 Like all software from that era, Doom can't auto-detect the audio system used by your (virtual) PC. DOSBox-X is configured by default to emulate a classic **SoundBlaster 16** card by Creative, so choose that entry by pressing **2**.

 Next step, enjoy blasting some demons in Doom!

![DOSBox-X Doom Running in Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-doom-running-in-window.jpg)

 If manually juggling games in DOSBox-X seems like a hassle, maybe it would be worth checking out a front-end like Launchbox. We saw in the past how you can [import MS-DOS games into Launchbox](https://www.makeuseof.com/how-to-import-ms-dos-games-launchbox/), and after the front-end's initial setup, playing a game will be as easy as selecting it from its menu.

## DOS in a Box

 Thanks to DOSBox-X, you can have the best DOS-era computers had to offer on a window on your desktop and a collection of hundreds of the best games in a folder that will take less than 1% of your actual PC's total storage.

 Despite your PC being officially incompatible with such old software, with DOSBox-X, enjoying your retro-favorites in all their pixelated glory will be only one or two commands away!

 Still, many older games are worth your time, for they're not "relics" but "classics". Titles like Syndicate and the original X-Com look and sound crude compared to today's games. Still, their addictive gameplay can give a lesson even to most modern triple-A titles. And the only way to play them is with software like DOSBox-X.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-sure.techidaily.com/nhance-engagement-select-best-fonts-for-your-thumbnails/"><u>[New] Enhance Engagement Select Best Fonts for Your Thumbnails</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-essential-tips-for-harnessing-movie-maker-in-windows-8-systems/"><u>[New] In 2024, Essential Tips for Harnessing Movie Maker in Windows 8 Systems</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unlock-efficiency-the-editors-guide-to-speed-control/"><u>2024 Approved Unlock Efficiency The Editor's Guide to Speed Control</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-t-open-mov-files-on-xiaomi-redmi-13c-5g-by-aiseesoft-video-converter-play-mov-on-android/"><u>Can't open MOV files on Xiaomi Redmi 13C 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conveniently-display-images-within-windows-explorer/"><u>Conveniently Display Images Within Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-the-synergy-6-android-apps-that-thrive-on-windows-11/"><u>Explore the Synergy: 6 Android Apps that Thrive on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-legacy-to-leading-edge-the-art-of-transferring-programs-in-windows-11/"><u>From Legacy to Leading Edge: The Art of Transferring Programs in Windows 11</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ring-360-degree-videos-secure-youtube-uploads/"><u>Mastering 360-Degree Videos Secure YouTube Uploads</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/moveavi-mp3-wav/"><u>Moveavi에서 제공하는 MP3, WAV 비용 없이 구문 변환 도구 - 원격 사용</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-odbc-connector-a-user-guide/"><u>Navigating Windows' ODBC Connector: A User Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/new-era-of-windows-aid-four-upcoming-changes/"><u>New Era of Windows Aid: Four Upcoming Changes</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-zero-budget-big-impact-the-best-free-online-video-editors-for-2024/"><u>New Zero Budget, Big Impact The Best Free Online Video Editors for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-non-selectable-or-hidden-text-on-windows-pdf-readers/"><u>Remedy Non-Selectable or Hidden Text on Windows PDF Readers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/saving-sticky-notes-a-windows-guide/"><u>Saving Sticky Notes: A Windows Guide</u></a></li>
<li><a href="https://extra-hints.techidaily.com/top-live-broadcast-tech-for-industry-experts/"><u>Top Live Broadcast Tech for Industry Experts</u></a></li>
</ul></div>

