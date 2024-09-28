---
title: The Essentials of Win11 Personalized Volume Shortcuts
date: 2024-08-16T01:50:21.888Z
updated: 2024-08-17T01:50:21.888Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Essentials of Win11 Personalized Volume Shortcuts
excerpt: This Article Describes The Essentials of Win11 Personalized Volume Shortcuts
keywords: Win11 Custom Shortcuts,Personalize Win11 Keys,Windows Volume Hotkeys,Optimize Win11 Hotkey,Quick Access Win11 Tools,Enhanced Win11 Keyboard,Streamline Win11 Shortcuts
thumbnail: https://thmb.techidaily.com/053654aac9195ea45d1f77852c408a3b2770cc6c802ff6728e9e3d8c452deddb.jpg
---

## The Essentials of Win11 Personalized Volume Shortcuts

 Not all keyboards include volume control hotkeys for muting, maximizing, and adjusting audio levels. Nor does Windows 11 have any universal sound control keyboard shortcuts. Therefore, some users have to make do with their mouse for volume control.

 However, you can set up custom volume control hotkeys in Windows 11 with some third-party software. Once set up, you’ll be able to change the volume with the press of a few hotkeys instead of fiddling around with sound control bars. Here is how to set up keyboard shortcuts for muting, maximizing, increasing, and decreasing volume with NirCmd and Volume Control.

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
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
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Select **Apply** to save.

 Start playing a video, and press the **Ctrl + Alt + M** keyboard shortcut. You can unmute the sound by pressing **Ctrl + Alt + M** again. Pressing that hotkey both mutes and unmutes audio.

 Don’t delete the Mute desktop shortcut. Deleting that shortcut will also erase the hotkey added to it. So, you’ll need to keep all audio control shortcuts on the desktop for their hotkeys to work.

 If you like, you can also change the icon for the desktop shortcut to a more appealing one. To do that, right-click the shortcut and select **Properties**. Click the **Change shortcut** button, and choose an icon on the window. Select the **OK** and **Apply** options to add the icon.

![The Change icon window and Mute desktop shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/change-icon-window.png)
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->

## How to Set Up a Hotkey for Maximizing Volume

 Aside from a mute hotkey, you can [set up a keyboard shortcut](https://www.makeuseof.com/what-is-a-hotkey-how-to-make-custom/) for maximizing volume. If you want a hotkey to max out volume (just don’t disturb the neighbors), you can create one with NirCmd’s **setsysvolume 65535** command. You can establish a max volume desktop shortcut much the same as a mute one with the Create Shortcut tool. The only difference is that you’ll need to input this command in the location box instead: **“NirCmd folder path\\nircmd.exe” setsysvolume 65535**.

![The setsysvolume command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/setsysvolcommand.png)

 The 65,535 in that command is NirCmd’s maximum decibel value. Clicking your new maximum audio desktop shortcut will max out playback volume. Thereafter, you can apply a hotkey to the max volume desktop shortcut just the same as for the mute one.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
## How to Create Volume Up and Down Hotkeys

 NirCmd also has commands that increase or decrease volume by specific values. You can set up hotkeys that activate those commands for raiding or reducing the decibel level. Again, you’ll need to first [set up desktop shortcuts](https://www.makeuseof.com/what-is-desktop-shortcut-how-work/) for those NirCmd commands just the same as for muting or maximizing sound. These are the commands you’ll need to enter into the "Create Shortcut" window’s location box:

 Increase volume by 2,000 units: **“NirCmd folder path\\nircmd.exe” changesysvolume 2000**

 Decrease volume by 5,000 units: **“NirCmd folder path\\nircmd.exe” changesysvolume -5000**

![The changesysvolume command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/changesysvolume-command.png)

 Note that you can change the unit values in those commands. To configure a shortcut to increase volume more, for example, you could input **changesysvolume 5000** in the location box instead. Or enter **changesysvolume -10000** to decrease the decibel level by twice as much. However, all values must be below the maximum of 65,535\.

 When you’ve set up some desktop shortcuts for increasing and reducing volume, right-click them and select **Properties**. You can add new hotkeys to them with their **Shortcut key** boxes as outlined for the mute command. Then press the NirCmd volume up and down hotkeys to your heart’s content to increase and lower the decibel level.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
5. Select the **Volume** **up** checkbox and repeat the previous step to set a hotkey for raising the volume.

1. Then select **Toggle Mute** and repeat step nine to set a keyboard shortcut for muting the volume.
2. Now open a program to assign the hotkeys to. A web browser or media player from which you can play music and videos would be ideal.
3. Click the **Mixer** tab to view a list of open apps.  
![The Mixer tab in Volume Control](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-mixer-tab.jpg)
4. Press the **Select** button beside the software to which you want to assign the custom hotkeys.
5. Click the **Lock** checkbox to ensure the volume control hotkeys always remain assigned to the selected software.

 Try out the custom volume hotkeys you’ve set for the software. Play a video within your software if you can. Press the keyboard shortcuts you’ve assigned to the app to raise, lower, and mute its volume. Those hotkeys will only affect the app’s volume level and won’t change the general system sound beyond it. The Volume bar within the **Mixer** tab shows you the audio level for the software.

![A YouTube video in the Opera browser](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/a-youtube-video.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->

 You can also create new volume control hotkeys from scratch with Volume Control. To do so, select the **Advanced Hotkeys** checkbox on the **Settings** tab. Then you’ll see a **Create New Hotkey** button on the **Hotkeys** tab you can press to set up new keyboard shortcuts. You can select options on an **Action** drop-down menu with advanced hotkeys enabled.

![The Action drop-down menu for advanced hotkeys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-create-new-hotkey-button.jpg)

## Adjust Playback Volume With Your New Sound Control Hotkeys

 So, you don’t need to get a new keyboard if your current one lacks volume control hotkeys. Simply set up a few custom keyboard shortcuts for muting, maximizing, lowering, and increasing volume with the NirCmd command-line utility or Volume Control. Then you can quickly mute, max out, or raise/lower the decibel level for video and music playback in Windows 11 by pressing those hotkeys.

 However, you can set up custom volume control hotkeys in Windows 11 with some third-party software. Once set up, you’ll be able to change the volume with the press of a few hotkeys instead of fiddling around with sound control bars. Here is how to set up keyboard shortcuts for muting, maximizing, increasing, and decreasing volume with NirCmd and Volume Control.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>



