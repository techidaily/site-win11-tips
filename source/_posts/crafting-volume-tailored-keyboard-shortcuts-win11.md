---
title: Crafting Volume Tailored Keyboard Shortcuts (Win11)
date: 2024-09-21T18:35:19.294Z
updated: 2024-09-28T19:03:12.279Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Crafting Volume Tailored Keyboard Shortcuts (Win11)
excerpt: This Article Describes Crafting Volume Tailored Keyboard Shortcuts (Win11)
keywords: Win11 Custom Keys,Tailored PC Shortcuts,Personalized Keyboard Macros,Optimize Windows Control,Enhanced Accessibility Ctrl,Advanced Command Shortcuts,User-Defined Keybindings
thumbnail: https://thmb.techidaily.com/399b71f22f6a0f097f9f941327a817b697b933fa54dbaf37480f689ec0e73886.jpg
---

## Crafting Volume Tailored Keyboard Shortcuts (Win11)

 Not all keyboards include volume control hotkeys for muting, maximizing, and adjusting audio levels. Nor does Windows 11 have any universal sound control keyboard shortcuts. Therefore, some users have to make do with their mouse for volume control.

 However, you can set up custom volume control hotkeys in Windows 11 with some third-party software. Once set up, you’ll be able to change the volume with the press of a few hotkeys instead of fiddling around with sound control bars. Here is how to set up keyboard shortcuts for muting, maximizing, increasing, and decreasing volume with NirCmd and Volume Control.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Download and Extract NirCmd

 NirCmd is a command-line tool that can carry out many useful PC tasks. It has some volume control commands for muting, maximizing, increasing, and reducing sound levels. Although NirCmd doesn’t provide any built-in options for establishing volume control hotkeys, we can set up keyboard shortcuts for its commands.

 First, however, you’ll need to download and extract NirCmd. The app comes packed in a ZIP archive that you’ll need to extract. You can download and extract NirCmd like this.

1. Open the [NirCmd download](https://www.nirsoft.net/utils/nircmd.html) page.
2. Scroll down to the bottom of that page, and click the **Download NirCmd 64-bit** link.
3. Double-click NirCmd’s ZIP to open it.
4. Click **Extract all** on File Explorer’s command bar.  
![The Extract all button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/extract-all-button2.png)
5. Select the **Browse** option to choose an extraction path.
6. Click the **Show extracted files when complete** checkbox to select it.  
![The Extract compressed window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/extract-compressed-window.png)
7. Press the **Extract** button to [extract the ZIP archive in Windows](https://www.makeuseof.com/how-to-extract-zip-files-windows-11/).

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528689/16446" target="_top" id="1528689">
  <img src="//a.impactradius-go.com/display-ad/16446-1528689" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528689/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Set Up a Mute Hotkey

 When you’ve extracted NirCmd’s archive, no program installation is required. Nor do you even need to launch it in any way. You will, however, need to note down, or copy, NirCmd’s extracted path. Then you can set up volume control shortcuts based on that utility’s commands. This is how you can establish a mute hotkey with NirCmd.

1. First, open the extracted NirCmd folder.
2. Right-click the nircmd EXE and select **Copy as path**.
3. Next, right-click an area of your desktop to select the **New** context menu option.
4. Click **Shortcut** on the submenu.  
![The Shortcut context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/shortcut-option.png)
5. Press the **Ctrl + V** keyboard shortcut to paste the copied NirCmd path into the location box.
6. Then press **Space** key once after the NirCmd path, and enter **mutesysvolume 2** in the location box as shown directly below. The location box should then include: **“NirCmd folder path\\nircmd.exe” mutesysvolume 2**.  
![The mutesysvolume command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/mutesysvolume-command.png)
7. Click **Next** to continue.
8. Enter **Mute** in the shortcut name box, and select the **Finish** option.

 Now you’ve got a Mute shortcut on your desktop. Start playing a video in a browser or media player, and click that shortcut to mute it. You can add a hotkey to that desktop Mute button as follows.

1. Right-click your Mute desktop shortcut to select **Properties** on its context menu.
2. Click inside the **Shortcut key** box to place a text cursor there.
3. Press **M** to set up a **Ctrl + Alt + M** hotkey.  
![The Shortcut key box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/shortcut-key-box3.png)
4. Select **Apply** to save.

 Start playing a video, and press the **Ctrl + Alt + M** keyboard shortcut. You can unmute the sound by pressing **Ctrl + Alt + M** again. Pressing that hotkey both mutes and unmutes audio.

 Don’t delete the Mute desktop shortcut. Deleting that shortcut will also erase the hotkey added to it. So, you’ll need to keep all audio control shortcuts on the desktop for their hotkeys to work.

 If you like, you can also change the icon for the desktop shortcut to a more appealing one. To do that, right-click the shortcut and select **Properties**. Click the **Change shortcut** button, and choose an icon on the window. Select the **OK** and **Apply** options to add the icon.

![The Change icon window and Mute desktop shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/change-icon-window.png)

## How to Set Up a Hotkey for Maximizing Volume

 Aside from a mute hotkey, you can [set up a keyboard shortcut](https://www.makeuseof.com/what-is-a-hotkey-how-to-make-custom/) for maximizing volume. If you want a hotkey to max out volume (just don’t disturb the neighbors), you can create one with NirCmd’s **setsysvolume 65535** command. You can establish a max volume desktop shortcut much the same as a mute one with the Create Shortcut tool. The only difference is that you’ll need to input this command in the location box instead: **“NirCmd folder path\\nircmd.exe” setsysvolume 65535**.

![The setsysvolume command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/setsysvolcommand.png)

 The 65,535 in that command is NirCmd’s maximum decibel value. Clicking your new maximum audio desktop shortcut will max out playback volume. Thereafter, you can apply a hotkey to the max volume desktop shortcut just the same as for the mute one.

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1576474/17382" target="_top" id="1576474">
  <img src="//a.impactradius-go.com/display-ad/17382-1576474" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1576474/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Create Volume Up and Down Hotkeys

 NirCmd also has commands that increase or decrease volume by specific values. You can set up hotkeys that activate those commands for raiding or reducing the decibel level. Again, you’ll need to first [set up desktop shortcuts](https://www.makeuseof.com/what-is-desktop-shortcut-how-work/) for those NirCmd commands just the same as for muting or maximizing sound. These are the commands you’ll need to enter into the "Create Shortcut" window’s location box:

 Increase volume by 2,000 units: **“NirCmd folder path\\nircmd.exe” changesysvolume 2000**

 Decrease volume by 5,000 units: **“NirCmd folder path\\nircmd.exe” changesysvolume -5000**

![The changesysvolume command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/changesysvolume-command.png)

 Note that you can change the unit values in those commands. To configure a shortcut to increase volume more, for example, you could input **changesysvolume 5000** in the location box instead. Or enter **changesysvolume -10000** to decrease the decibel level by twice as much. However, all values must be below the maximum of 65,535\.

 When you’ve set up some desktop shortcuts for increasing and reducing volume, right-click them and select **Properties**. You can add new hotkeys to them with their **Shortcut key** boxes as outlined for the mute command. Then press the NirCmd volume up and down hotkeys to your heart’s content to increase and lower the decibel level.

<!-- affiliate ads begin -->
<span id="1492813">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1492813.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1492813">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1492813.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1492813%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1492813/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Set Up Custom Volume Control Hotkeys for a Specific App

 Volume Control is a portable third-party app with which you can set up custom volume control hotkeys and assign them to specific apps. Then the custom keyboard shortcuts set will only change the volume for a program you’ve assigned it to. This is how you can set custom volume control hotkeys for a specific app in Windows 11 with Volume Control:

1. Open the [Volume Control](https://www.softpedia.com/get/Multimedia/Audio/Other-AUDIO-Tools/Volume-Control-radj307.shtml) page on Softpedia.
2. Click **Free Download** to view the location options.
3. Select **Secure Download (US)**, which is best for North America.
4. Right-click Windows 11’s **Start** taskbar button to select **File Explorer**.
5. Open the folder that contains the downloaded Volume Control file.

1. Double-click the **VolumeControl** file to open the software (no installation is needed).
2. Click the **Hotkeys** tab in the Volume Control window.
3. Select the **Volume up** checkbox.
4. Click the **Key** drop-down menu and select a key for your hotkey there. You can also select the **Alt**, **Ctrl**, **Shift**, or **Win** checkboxes to extend your hotkey with one of those modifier keys.  
![The Hotkeys tab in Volume Control](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/hotkeys-tab.jpg)
5. Select the **Volume** **up** checkbox and repeat the previous step to set a hotkey for raising the volume.

1. Then select **Toggle Mute** and repeat step nine to set a keyboard shortcut for muting the volume.
2. Now open a program to assign the hotkeys to. A web browser or media player from which you can play music and videos would be ideal.
3. Click the **Mixer** tab to view a list of open apps.  
![The Mixer tab in Volume Control](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-mixer-tab.jpg)
4. Press the **Select** button beside the software to which you want to assign the custom hotkeys.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1884002/19272" target="_top" id="1884002">
  <img src="//a.impactradius-go.com/display-ad/19272-1884002" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884002/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Click the **Lock** checkbox to ensure the volume control hotkeys always remain assigned to the selected software.

 Try out the custom volume hotkeys you’ve set for the software. Play a video within your software if you can. Press the keyboard shortcuts you’ve assigned to the app to raise, lower, and mute its volume. Those hotkeys will only affect the app’s volume level and won’t change the general system sound beyond it. The Volume bar within the **Mixer** tab shows you the audio level for the software.

![A YouTube video in the Opera browser](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/a-youtube-video.jpg)

 You can also create new volume control hotkeys from scratch with Volume Control. To do so, select the **Advanced Hotkeys** checkbox on the **Settings** tab. Then you’ll see a **Create New Hotkey** button on the **Hotkeys** tab you can press to set up new keyboard shortcuts. You can select options on an **Action** drop-down menu with advanced hotkeys enabled.

![The Action drop-down menu for advanced hotkeys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-create-new-hotkey-button.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148643/16836" target="_top" id="2148643">
  <img src="//a.impactradius-go.com/display-ad/16836-2148643" border="0" alt="https://techidaily.com" width="300" height="75"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148643/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Adjust Playback Volume With Your New Sound Control Hotkeys

 So, you don’t need to get a new keyboard if your current one lacks volume control hotkeys. Simply set up a few custom keyboard shortcuts for muting, maximizing, lowering, and increasing volume with the NirCmd command-line utility or Volume Control. Then you can quickly mute, max out, or raise/lower the decibel level for video and music playback in Windows 11 by pressing those hotkeys.

 However, you can set up custom volume control hotkeys in Windows 11 with some third-party software. Once set up, you’ll be able to change the volume with the press of a few hotkeys instead of fiddling around with sound control bars. Here is how to set up keyboard shortcuts for muting, maximizing, increasing, and decreasing volume with NirCmd and Volume Control.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-access.techidaily.com/new-master-the-art-of-conversation-top-whatsapp-techniques-for-2024/"><u>[New] Master the Art of Conversation Top WhatsApp Techniques for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-unlock-clearer-livestreams-with-these-4-tips/"><u>[New] Unlock Clearer Livestreams with These 4 Tips</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-thriving-livestreams-strategies-for-beginners-with-low-followers/"><u>[Updated] Thriving Livestreams Strategies for Beginners with Low Followers</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-cutting-edge-look-ups-top-15-luts-for-gopro-action-footage/"><u>2024 Approved Cutting-Edge Look-Ups Top 15 LUTs for GoPro Action Footage</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-masterful-techniques-for-swift-blurring-in-picture-editing/"><u>2024 Approved Masterful Techniques for Swift Blurring in Picture Editing</u></a></li>
<li><a href="https://buynow-info.techidaily.com/best-prime-day-ever-score-amazing-deals-on-all-your-favorite-apple-products/"><u>Best Prime Day Ever: Score Amazing Deals on All Your Favorite Apple Products</u></a></li>
<li><a href="https://android-unlock.techidaily.com/best-ways-on-how-to-unlockbypassswiperemove-motorola-moto-g73-5g-fingerprint-lock-by-drfone-android/"><u>Best Ways on How to Unlock/Bypass/Swipe/Remove Motorola Moto G73 5G Fingerprint Lock</u></a></li>
<li><a href="https://tech-hub.techidaily.com/experience-cutting-edge-tech-for-free-mastering-gpt-copilot-integration-seamlessly/"><u>Experience Cutting-Edge Tech for Free – Mastering GPT-Copilot Integration Seamlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-shutting-down-windows-11-privacy-features/"><u>Guide to Shutting Down Windows 11 Privacy Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-notepad-stability/"><u>Mastering Windows Notepad Stability</u></a></li>
<li><a href="https://location-social.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>Proven Ways in How To Hide Location on Life360 For Oppo Reno 9A | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-guide-airpods-and-windows-compatibility/"><u>Simplified Guide: AirPods & Windows Compatibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/veiled-functionality-for-context-tools-on-pcs/"><u>Veiled Functionality for Context Tools on PCs</u></a></li>
</ul></div>

