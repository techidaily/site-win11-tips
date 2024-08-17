---
title: The Insider's Guide to Customizing the Desktop Menu
date: 2024-08-16T01:53:22.138Z
updated: 2024-08-17T01:53:22.138Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Insider's Guide to Customizing the Desktop Menu
excerpt: This Article Describes The Insider's Guide to Customizing the Desktop Menu
keywords: Desktop Menu Tips,Personalize Menu Bar,UI Customization Steps,Menu Layout Design,Quick Menu Setup,Interface Tweaks Guide,User Preferences Change
thumbnail: https://thmb.techidaily.com/26300a30b40be91fd1403de278cb19bb64bc0cc7c24d1ddb32b678a579f7aa1d.jpg
---

## The Insider's Guide to Customizing the Desktop Menu

 Windows 11’s desktop context menu is a place where you can add many software shortcuts even though the platform doesn’t include built-in customization settings for that menu. Many users add shortcuts to that menu with third-party software, but you can manually customize it with Registry Editor.

 If you add many shortcuts to that menu, organizing them into submenus is a good idea. Doing so will enable you to add more shortcuts without greatly extending the length of the classic context menu. This is how you can add new submenus to the Windows 11’s desktop context menu.

## How to Add a Submenu to the Context Menu by Manually Editing the Registry

 You can manually create a context menu submenu that includes any number of software shortcuts with the Registry Editor. For the sake of example, here we’ll create a submenu that includes shortcuts for opening the Notepad and Remote Desktop Connection apps. Then you can add more shortcuts for software on your PC. First, you’ll need to lay the foundation for the submenu as follows:

1. To access the registry app, check out this guide about [how to open Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
2. Go to a **shell** key by inputting the following location into the Registry Editor’s address bar:  
`Computer\HKEY_CLASSES_ROOT\Directory\Background\shell`
3. Right-click the **shell** key in the left sidebar and select the **New** \> **Key** options for adding a new registry entry.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/new-key-options.jpg)
4. Enter **Menu1** to be the new key’s name.
5. Right-click **Menu1** to select the **New** \> **String Value** options.

1. Input **MUIVerb** for the new string’s name.
2. Repeat step five to add another new string to the **Menu1** key. However, enter **SubCommands** to be this new string’s name.  
![The Menu1 registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/the-menu1-key.jpg)
3. Double-click the **MUIVerb** string added to the **Menu1** key.
4. Enter **Apps** in the **Value** box for the **MUIVerb** string, which will be the heading for your new context menu submenu. Or you can input a different submenu heading in the **Value data** box if preferred.  
![The MUIVerb string value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/muiverb-string.jpg)
5. Click **OK** to exit the Edit String window for **MUIVerb**.
6. Next, double-click on the **SubCommand** string inside the **Menu1** key.
7. Input **Notepad; Remote Desktop Connection** inside the **Value** box for the **SubCommands** string and click **OK**.  
![subcommands-string-value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/subcommands-string-value.jpg)

 Now a new **App** submenu will be visible on Windows 11’s classic context menu. However, it won’t include any shortcuts. So, you will need to do some further editing of a different **shell** key to add functionality to the submenu. Edit the registry like this to complete the submenu:

1. Return to the Registry Editor and input this location into its address bar:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CommandStore\Shell`
2. Right-click **shell** to select **Key** on the **New** submenu.
3. Input **Notepad** to be the title for this new registry key.
4. Right-click on **Notepad** in Registry Editor’s left sidebar to select **New** \> **Key**.
5. Enter **command** to be the name of the subkey.
6. Double-click **(Default)** in the **Notepad** key.
7. Input **Notepad** into the **Value** box and click **OK**.
8. Double-click the **(Default)** string in the **command** subkey.
9. Enter this Notepad location into the **Value** box and select **OK**:  
`C:\Windows\System32\notepad.exe`  
![The Notepad path value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/the-notepad-path-value.jpg)
10. Repeat steps two to five to create a **Remote Desktop Connection** key with a **command** subkey, as shown in the snapshot directly below. Instead of naming the key Notepad, input **Remote Desktop Connection** for the new key’s title.  
![The Remote Desktop Connection and Notepad keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/notepad-and-remote-desktop-connection-keys.jpg)
11. Double-click the **(Default)** string for the **Remote Desktop Connection** key you created.
12. Input **Remote Desktop Connection** into the **Value** box and select **OK**.
13. Select the **command** subkey for the **Remote Desktop Connection** key and double-click its **(Default)** string.
14. Enter the following Remote Desktop Connection app path in the **Value** box and click **OK**:  
`"C:\Windows\System32\mstsc"`

 Now the new context menu submenu is complete. Right-click within an area of the Windows 11 desktop and select **Show more options** to view the secondary classic context menu. Move the cursor over the new **Apps** submenu from which you can select to open Notepad and Remote Desktop Connection.

![The Apps submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/the-apps-submenu.jpg)

 You can add more software shortcuts to that submenu. Note that the values you input for the **SubCommands** string must match the names of the registry keys created for the software shortcuts. In the example above, the **Notepad** and **Remote Desktop Connection** registry keys matched values input for the **SubCommands** string.

 You must also input the exact and full paths for whatever software you want the shortcuts to open within the **(Default)** strings of the command subkeys. In the example above, the **(Default)** strings of the **command** subkeys within the **Remote Desktop Connection** and **Notepad** keys include the paths for opening those apps.

 If you ever want to remove the submenu from the context menu, delete the key that created it. To do so, return to the registry location that includes the **Menu1** key. Right-click the **Menu1** key to select **Delete** and **Yes** for confirmation.

![The Delete option for the Menu1 key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/delete-option.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
## How to Add a Submenu to the Context Menu With Easy Context Menu

 Easy Context Menu is a freely available context menu customization desktop app. That software enables you to add custom software shortcut submenus to the right-click menu without [manually editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/).

 You can create a custom software shortcuts submenu with Easy Context Menu like this:

1. Navigate to the [Easy Context Menu](https://www.sordum.org/downloads/?easy-context-menu) download page.
2. Click **Direct Download** on that page to save the ZIP archive for Easy Context Menu.
3. Extract the **ec\_menu** ZIP with a method in this [guide for unzipping ZIP archives](https://www.makeuseof.com/how-to-extract-zip-files-windows-11/) within Windows.  
![The Extract All option for ZIP archives](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/extract-all-option.jpg)
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Open the extracted folder for Easy Context Menu and double-click the EXE file that runs the software from there.
5. Click the **List Editor** button in Easy Context Menu.

1. Select **Desktop Context Menu** and press the **Add Sub Menu** button.
2. Input **Software Shortcuts** in the **Title** box for the new submenu.  
![The List Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/software-shortcuts-submenu.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
3. Click the **Add New** button with the **Software Shortcuts** submenu selected.
4. Select a program you want to include in the submenu and click **Open**.
5. Repeat the previous two steps to add more programs to the submenu.  
![A program shortcut added to the Software Shortcuts submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/program-shortcuts.jpg)
6. Select the checkboxes for the new **Software Shortcuts** submenu and the programs added to it in the List Editor window.
7. Press the **Save Changes** button and close the List Editor window.
8. Select the checkboxes for the **Software Shortcuts** submenu and the program options it includes within the Easy Context Menu window.  
![The Easy Context Menu window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/easy-context-menu-window.jpg)
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. Click **Apply Changes** to add the new submenu.

 Now check out the new **Software Shortcuts** submenu on Windows 11’s classic desktop context menu. That cascading menu will include all the programs you selected to add to it. It will also include program icons, so long as you leave the **Show icon in the Context Menu** checkboxes selected.

![software-shortcuts-submenu2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/software-shortcuts-submenu2.jpg)
<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Another advantage of utilizing Easy Context Menu is that it includes options for positing the submenu. You can configure the approximate position of that submenu by selecting one of the three **Show at** options for it within the List Editor window. You can also reposition the submenu or items in it by selecting them and clicking the **Move Up** or **Move Down** buttons.

 Easy Context Menu also includes **Tools**, **System Tools**, and **Turn Off Options** submenus for you to add to the right-click menu. To add those submenus, select the **System Tools**, **Turn Off Options**, and **Tools** checkboxes for the desktop context menu and click **Apply Changes**. You can also deselect some of the checkboxes for those submenus to remove certain shortcuts from them.

![A Tools submenu added with Easy Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/the-tools-submenu.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
## Organize Your Windows Desktop Context Menu Shortcuts With Submenus

 Adding one or more submenus to Windows 11’s desktop context menu will enable you to organize the software shortcuts added to it.

 You could create multiple submenus on the context menu that include shortcuts for opening different software categories, such as web browsers, media players, productivity apps, etc. Or you can add a new desktop context menu submenu for accessing Windows tools and turn off options with Easy Context Menu.

 If you add many shortcuts to that menu, organizing them into submenus is a good idea. Doing so will enable you to add more shortcuts without greatly extending the length of the classic context menu. This is how you can add new submenus to the Windows 11’s desktop context menu.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-capture.techidaily.com/new-a-comprehensive-list-of-top-virtual-classrooms-not-inspired-by-udemy-for-2024/"><u>[New] A Comprehensive List of Top Virtual Classrooms Not Inspired by Udemy for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-androvid-video-editor-complete-review-for-2024/"><u>[Updated] AndroVid Video Editor – Complete Review for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-enhance-your-browsing-fixing-fuzzy-videos-in-chrome-and-phone-apps/"><u>[Updated] Enhance Your Browsing  Fixing Fuzzy Videos in Chrome and Phone Apps</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-the-real-strategy-behind-instagram-reels/"><u>[Updated] The Real Strategy Behind Instagram Reels</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-5-mac-videography-tools-unleashed-in-sierra-os/"><u>2024 Approved  Top 5 Mac Videography Tools Unleashed in Sierra OS</u></a></li>
<li><a href="https://fox-glue.techidaily.com/auroras-role-in-enhancing-image-contrast-for-2024/"><u>Aurora's Role in Enhancing Image Contrast for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosted-methods-for-graphic-detail-recognition-windows-11/"><u>Boosted Methods for Graphic Detail Recognition, Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/circumventing-verify-errors-for-third-party-windows-apps/"><u>Circumventing Verify Errors for Third-Party Windows Apps</u></a></li>
<li><a href="https://fox-access.techidaily.com/enhance-with-ease-introduction-to-video-enhancer-v22/"><u>Enhance with Ease  Introduction to Video Enhancer V2.2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-new-depths-noteworthy-alterations-in-windows-11s-interface/"><u>Exploring New Depths: Noteworthy Alterations in Windows 11'S Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-apply-local-group-policies-to-a-specific-user-account-in-windows-10-and-11/"><u>How to Apply Local Group Policies to a Specific User Account in Windows 10 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-spotify-application-is-not-responding-error-in-windows-11-and-11/"><u>How to Fix the “Spotify Application Is Not Responding” Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-open-and-use-the-windows-terminal-in-quake-mode/"><u>How to Open and Use the Windows Terminal in Quake Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-discord-from-launching-at-startup-and-searching-for-updates-on-windows/"><u>How to Stop Discord From Launching at Startup and Searching for Updates on Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-oppo-reno-11-pro-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Oppo Reno 11 Pro 5G Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-learn-how-everything-works-on-oneplus-12r-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Learn How Everything Works On OnePlus 12R | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-pro-tips-iphone-in-the-dark-spotlight/"><u>In 2024, Pro Tips  IPhone in the Dark Spotlight</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-setup-for-bings-ai-assistance-in-windows-11-search-shortcuts/"><u>Instant Setup for Bing's AI Assistance in Windows 11 Search Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-starting-csgo-in-w11/"><u>Mastering the Art of Starting CS:GO in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-unique-devices-names-erase-in-use-issues-on-pcs/"><u>Mastering Unique Devices Names: Erase 'In Use' Issues on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-efficiency-in-windows-photos-via-shortcuts/"><u>Maximize Efficiency in Windows Photos via Shortcuts</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/melody-meets-science-the-ultimate-guide-to-learning-multiple-languages/"><u>Melody Meets Science: The Ultimate Guide to Learning Multiple Languages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-disconnection-issues-with-ea-services-in-win/"><u>Overcoming Disconnection Issues with EA Services in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-jot-down-techniques-in-windows-11-no-apps/"><u>Quick Jot-Down Techniques in Windows 11, No Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restarting-affected-windows-netflix-functions/"><u>Restarting Affected Windows Netflix Functions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slaying-windows-beast-error-code-0xc00ce556/"><u>Slaying Window's Beast Error: Code 0xC00CE556</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snowflake-surprises-gifting-windows-games-via-mstore/"><u>Snowflake Surprises: Gifting Windows Games via MSTORE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/surface-laptop-studio-2-explored-creators-dream-device/"><u>Surface Laptop Studio 2 Explored: Creator's Dream Device?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-resolve-win11s-blue-screen-through-these-tips/"><u>Swiftly Resolve Win11's Blue Screen Through These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-installer-lacks-permissions-in-windows-1110/"><u>Troubleshooting Installer Lacks Permissions in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-wins-update-failure-on-win11-v22h2/"><u>Troubleshooting Wins Update Failure on Win11 V22H2</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/ultimate-raspberry-pi-400-assessment-portable-mini-computer-meets-ergonomic-keyboard/"><u>Ultimate Raspberry Pi 400 Assessment: Portable Mini-Computer Meets Ergonomic Keyboard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-solving-token-access-failure-errors/"><u>Understanding and Solving Token Access Failure Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-watchlist-spot-the-red-flags-in-these-7-tasks/"><u>Windows Watchlist: Spot the Red Flags in These 7 Tasks</u></a></li>
</ul></div>
