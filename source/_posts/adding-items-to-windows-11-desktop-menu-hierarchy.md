---
title: Adding Items to Windows 11 Desktop Menu Hierarchy
date: 2024-06-25T17:02:26.435Z
updated: 2024-06-26T17:02:26.435Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adding Items to Windows 11 Desktop Menu Hierarchy
excerpt: This Article Describes Adding Items to Windows 11 Desktop Menu Hierarchy
keywords: Windows 11 Menu Add-Ons,11X Desktop Item Hierarchy,Win11 Menu Organization,Enhance Desktop Menu Items,Windows 11 UI Customization,Desktop Menu Arrangement,Update Windows 11 Menu
thumbnail: https://thmb.techidaily.com/b1b6775bf38540cce32c7cf3ae0c3f9781deea4b62c3dc654004acc69b97d819.jpg
---

## Adding Items to Windows 11 Desktop Menu Hierarchy

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

## How to Add a Submenu to the Context Menu With Easy Context Menu

 Easy Context Menu is a freely available context menu customization desktop app. That software enables you to add custom software shortcut submenus to the right-click menu without [manually editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/).

 You can create a custom software shortcuts submenu with Easy Context Menu like this:

1. Navigate to the [Easy Context Menu](https://www.sordum.org/downloads/?easy-context-menu) download page.
2. Click **Direct Download** on that page to save the ZIP archive for Easy Context Menu.
3. Extract the **ec\_menu** ZIP with a method in this [guide for unzipping ZIP archives](https://www.makeuseof.com/how-to-extract-zip-files-windows-11/) within Windows.  
![The Extract All option for ZIP archives](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/extract-all-option.jpg)
4. Open the extracted folder for Easy Context Menu and double-click the EXE file that runs the software from there.
5. Click the **List Editor** button in Easy Context Menu.

1. Select **Desktop Context Menu** and press the **Add Sub Menu** button.
2. Input **Software Shortcuts** in the **Title** box for the new submenu.  
![The List Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/software-shortcuts-submenu.jpg)
3. Click the **Add New** button with the **Software Shortcuts** submenu selected.
4. Select a program you want to include in the submenu and click **Open**.
5. Repeat the previous two steps to add more programs to the submenu.  
![A program shortcut added to the Software Shortcuts submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/program-shortcuts.jpg)
6. Select the checkboxes for the new **Software Shortcuts** submenu and the programs added to it in the List Editor window.
7. Press the **Save Changes** button and close the List Editor window.
8. Select the checkboxes for the **Software Shortcuts** submenu and the program options it includes within the Easy Context Menu window.  
![The Easy Context Menu window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/easy-context-menu-window.jpg)
9. Click **Apply Changes** to add the new submenu.

 Now check out the new **Software Shortcuts** submenu on Windows 11’s classic desktop context menu. That cascading menu will include all the programs you selected to add to it. It will also include program icons, so long as you leave the **Show icon in the Context Menu** checkboxes selected.

![software-shortcuts-submenu2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/software-shortcuts-submenu2.jpg)

 Another advantage of utilizing Easy Context Menu is that it includes options for positing the submenu. You can configure the approximate position of that submenu by selecting one of the three **Show at** options for it within the List Editor window. You can also reposition the submenu or items in it by selecting them and clicking the **Move Up** or **Move Down** buttons.

 Easy Context Menu also includes **Tools**, **System Tools**, and **Turn Off Options** submenus for you to add to the right-click menu. To add those submenus, select the **System Tools**, **Turn Off Options**, and **Tools** checkboxes for the desktop context menu and click **Apply Changes**. You can also deselect some of the checkboxes for those submenus to remove certain shortcuts from them.

![A Tools submenu added with Easy Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/the-tools-submenu.jpg)

## Organize Your Windows Desktop Context Menu Shortcuts With Submenus

 Adding one or more submenus to Windows 11’s desktop context menu will enable you to organize the software shortcuts added to it.

 You could create multiple submenus on the context menu that include shortcuts for opening different software categories, such as web browsers, media players, productivity apps, etc. Or you can add a new desktop context menu submenu for accessing Windows tools and turn off options with Easy Context Menu.

 If you add many shortcuts to that menu, organizing them into submenus is a good idea. Doing so will enable you to add more shortcuts without greatly extending the length of the classic context menu. This is how you can add new submenus to the Windows 11’s desktop context menu.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/1719268439990-chrome-freeze-no-more-top-solutions-for-windows-11-users/"><u>Chrome Freeze No More: Top Solutions for Windows 11 Users!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/declutter-drive-space-recognizing-the-leviathans-in-windows-pcs/"><u>Declutter Drive Space: Recognizing the Leviathans in Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-instant-addition-problems-with-windows-onedrive-a-compreenhensive-guide/"><u>Resolving Instant Addition Problems with Windows OneDrive - A Compreenhensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ways-to-streamline-win11s-print-management-max-52-chars/"><u>Ways to Streamline Win11’s Print Management (Max 52 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-managed-users-and-groups-in-win1110-homes/"><u>Enabling Managed Users and Groups in Win11/10 Homes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-files-and-folders-win-1011-edition/"><u>Conquering Files and Folders, Win 10/11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamping-gpos-a-step-by-step-guide-for-windows-users/"><u>Revamping GPOs: A Step-by-Step Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-self-closure-in-windows-os/"><u>Eliminating Self-Closure in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensible-guide-quick-fix-for-active-directory-domain-services-printer-errors/"><u>Comprehensible Guide: Quick Fix for Active Directory Domain Services Printer Errors</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-vivo-t2-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/3-ways-for-android-pokemon-go-spoofing-on-xiaomi-redmi-note-13-pro-5g-drfone-by-drfone-virtual-android/"><u>3 Ways for Android Pokemon Go Spoofing On Xiaomi Redmi Note 13 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-techniques-to-reclaim-your-exclusive-snaps-for-2024/"><u>[New] Techniques to Reclaim Your Exclusive Snaps for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-fading-audio-tips-for-better-mixes-in-ableton/"><u>[New] Fading Audio Tips for Better Mixes in Ableton</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-edit-like-a-pro-video-file-editing-on-mac-os-x-yosemite-made-easy-for-2024/"><u>Updated Edit Like a Pro Video File Editing on Mac OS X Yosemite Made Easy for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-best-of-breed-snapchat-augmentations-await/"><u>[New] In 2024, Best of Breed Snapchat Augmentations Await</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-get-the-apple-id-verification-code-on-apple-iphone-15-in-the-best-ways-by-drfone-ios/"><u>In 2024, How To Get the Apple ID Verification Code On Apple iPhone 15 in the Best Ways</u></a></li>
<li><a href="https://fix-guide.techidaily.com/realme-gt-5-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Realme GT 5 Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-discover-the-10-best-yoga-platforms-for-enhanced-fitness/"><u>2024 Approved  Discover The 10 Best Yoga Platforms For Enhanced Fitness</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-prime-8-virtual-vision-composition-program/"><u>[New] Prime 8 Virtual Vision Composition Program</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>