---
title: "Enrich Your Environment: Adding Tasks to Folder Context Menus"
date: 2024-10-05T18:33:02.890Z
updated: 2024-10-09T00:03:52.804Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enrich Your Environment: Adding Tasks to Folder Context Menus"
excerpt: "This Article Describes Enrich Your Environment: Adding Tasks to Folder Context Menus"
keywords: Add Task Context Menu,Enhance Workflow Efficiency,Improve Folder Organization,Context Menu Customization,Optimize Productivity Tools,Streamline Task Management,Enrich Digital Workspace
thumbnail: https://thmb.techidaily.com/12fbcccb55845f8983544f25e1cc6b0c0aa528d408cbc232f59c597fcdf5f91a.png
---

## Enrich Your Environment: Adding Tasks to Folder Context Menus

 You may frequently need to move or copy files to alternative folders in Windows. To do this, you might move files to different folders by dragging and dropping them. To copy a file to another location, you can either hold the**Ctrl** key while dragging or utilize the copy-paste hotkeys.

 It would be better to have context menu options for moving and copying files to selected locations. Then you could right-click a file and select a**Move to folder** or**Copy to folder** option. This is how you can add context menu options for moving and copying files to folders in Windows 11/10.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Add a Move to Folder Context Menu Option

 To add new context menu options in Windows 11/10, you must tweak the[Windows registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) one way or another. The Registry Editor app enables users to customize Windows’ right-click menus by manually tweaking the registry. You can add a Move to folder option to the context menu with the Registry Editor as follows:

1. Bring up the Registry Editor with a method included in our[how to open regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) guide.
2. Click inside the address bar at the top of Registry Editor, and erase the current key location there.
3. Then enter this**ContextMenuHandlers** key location and press**Return** :  
`HKEY_CLASSES_ROOT\AllFilesystemObjects\shellex\ContextMenuHandlers`
4. Next, right-click**ContextMenuHandlers** and select the**New** submenu.
5. Click**Key** on the submenu.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-key-option.jpg)

1. Enter**Move to folder** for the new key’s name.
2. Select the new**Move to folder** key in the Registry Editor’s sidebar.
3. Double-click the**(Default)** string for the selected key.
4. Input**{C2FBB631-2971-11D1-A18C-00C04FD75D13}** inside the**Value data** box.  
![The value data for the Move to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/an-edit-string-window.jpg)
5. Select**OK** to set the new value for the (Default) string.
6. Exit the Registry Editor.

 You can now try out the new**Move to folder** option on the context menu. Press the**Explorer** taskbar button to view the Windows file manager. Right-click a file and select the new**Move to folder** option. You’ll need to select**Show more options** \>**Move to folder i** n Windows 11.

![The Move to folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/move-to-folder-context-menu-option.jpg)

 A small Move Items window will then appear from which you can select a destination folder. Choose a folder to move the file to in that window. Then click**Move** to place the file in the selected directory.

![The Move Items window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/move-items-window.jpg)

## How to Add a Copy to Folder Context Menu Option

 The Windows context menu includes a**Copy** option, but that doesn’t enable you to select a destination for pasting the file. Thus, users must manually paste copied items into different folders after selecting that option. However, you can add a better**Copy to folder** context menu option that brings up a destination folder selection window like this:

1. Open the**ContextMenuHandlers** registry key as covered in the first three steps for adding a**Move to** folder option.
2. Click the**ContextMenuHandlers** with the right mouse button and select its New option.
3. Select**Key** to add a new one to the registry.
4. Type**Copy to folder** inside the text box for the new key.  
![The Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option-1.jpg)
5. Select**Copy to folder** and double-click its**(Default)** string.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130533/26400" target="_top" id="2130533">
  <img src="//a.impactradius-go.com/display-ad/26400-2130533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130533/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Enter the value**{C2FBB630-2971-11D1-A18C-00C04FD75D13}** inside the**Data** box.  
![The value data for the Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-edit-string-window-for-the-copytokey.jpg)
7. Click the**OK** button to apply the value.
8. Close the Registry Editor app’s window.

 Then you can select the**Copy to folder** context menu option much the same as the move one. Right-click a file in Explorer, select**Show more options** (in Windows 11), and click**Copy to folder** . A Copy Items window will open from which you can choose a folder to include the copied file. Clicking**Copy** will paste the item into the selected folder.

![The Copy to folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option.jpg)

 You can remove the "Copy/Move to folder" options from the right-click menu by deleting their registry keys. Open the**ContextMenuHandlers** key location specified in step three for adding a Move to folder context menu option. Right-click the**Copy to folder** or**Move to folder** registry key and select**Delete** . Select**Yes** when prompted to confirm you’re sure about erasing that key.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098704/14409" target="_top" id="2098704">
  <img src="//a.impactradius-go.com/display-ad/14409-2098704" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098704/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Add Move and Copy to Folder Context Menu Options With WinBubble

 It’s relatively straightforward to add the "Copy/Move to folder" options with the Registry Editor, but there’s still an easier way to do it. You can add the same options to the context menu with the freeware WinBubble. WinBubble is customization software that includes a wide variety of context menu options. This is how to add a "Copy/Move to folder" context menu options with WinBubble:

1. Head over to[the WinBubble](https://www.softpedia.com/get/Tweak/System-Tweak/WinBubble.shtml) page on Softpedia.
2. Press WinBubble’s**Download Now** button.
3. Click the**Softpedia Mirror (US)** option for the download location.
4. Next, bring up a**Downloads** tab or page in whatever web browser you’re utilizing. You can do that in Chrome, Edge, Firefox, or Opera with the**Ctrl** +**J** hotkey.
5. Double-click the WinBubble ZIP to view that archive inside File Explorer.

1. Select**Extract all** on Explorer’s command bar or the**Compressed Folder Tools** tab in Windows 10.  
![The Extract all option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/extract-all-option.jpg)
2. Press the**Browse** button.
3. Choose a suitable directory to extract the archive outside the one it downloaded to, and click the**Select Folder** option.
4. Next, select**Show extracted files when complete** for the WinBubbles folder to automatically open after extraction.
5. Then click**Extract** to bring up the unzipped WinBubbles folder.  
![The Extract Compressed window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-extract-compressed-window.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151860/7443" target="_top" id="2151860">
  <img src="//a.impactradius-go.com/display-ad/7443-2151860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151860/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Now double-click WinBubbles EXE to launch that software.
2. Select the**Move to** option on the**General** tab.
3. Click the**Copy to** checkbox to select that option.  
![The Copy to option in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-checkbox.jpg)
4. Press WinBubble’s**Apply** option when highlighted yellow.  
![The Apply button in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/highlighted-apply-button.jpg)
5. A WinBubble dialog box window will appear confirming the tweaks have been saved. Click**OK** to close that message.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139121/17108" target="_top" id="2139121">
  <img src="//a.impactradius-go.com/display-ad/17108-2139121" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139121/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Minimize or exit the WinBubble window.

 Now look at your new context menu options for copying and moving items to different locations. WinBubble adds them to the classic context menu like the manual registry tweak methods. So, you’ll still need to select**Show more options** or press**Shift** +**F10** to access those options in Windows 11.

 You can also utilize WinBubble to remove the "Copy/Move to Folder" options. Uncheck the selected**Move to** and**Copy to** checkboxes on its**General** tab. Click**Apply** to set the new options.

## Move and Copy Files to Folders With Your New Context Menu Options

 The**"** Copy/Move to folder" context menu options undoubtedly provide more convenient ways to copy and move files into alternative directories. You won’t need to drag files about anymore for moving items in Windows 11 after adding a new**"** Move to Folder option" to the right-click menu. Nor will you need to paste copied files elsewhere in Windows 11 thanks to the "Copy to folder" menu option.

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
<li><a href="https://youtube-docs.techidaily.com/he-art-of-matchmaking-in-the-youtube-collaboration-arena-for-2024/"><u>[New] The Art of Matchmaking in the YouTube Collaboration Arena for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-building-bonds-youtube-and-brands-in-unity-for-2024/"><u>[Updated] Building Bonds YouTube and Brands in Unity for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-dish-to-screen-your-recipe-video-blueprint-for-2024/"><u>[Updated] Dish to Screen Your Recipe Video Blueprint for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-navigating-the-realm-of-sponsorships-on-instagram-influencer-edition/"><u>2024 Approved Navigating the Realm of Sponsorships on Instagram Influencer Edition</u></a></li>
<li><a href="https://some-guidance.techidaily.com/creating-partial-screen-dumps-on-windows-11-a-step-by-step-guide/"><u>Creating Partial Screen Dumps on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-safety-masterful-firewall-configuration/"><u>Enhancing Safety: Masterful Firewall Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-on-managing-users-in-the-cli/"><u>Expert Tips on Managing Users in the CLI</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/how-to-mute-non-stop-fb-video-ad-content-for-2024/"><u>How to Mute Non-Stop FB Video Ad Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-new-horizons-in-windows-11-avoid-these-slips/"><u>Navigating New Horizons in Windows 11: Avoid These Slips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-notes-top-7-windows-tech-choices/"><u>Navigating Notes: Top 7 Windows Tech Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-utorrent-pausefreeze-in-windows-environment/"><u>Overcoming uTorrent Pause/Freeze in Windows Environment</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/pixelated-prowess-celebrating-the-best-shooter-classics/"><u>Pixelated Prowess Celebrating the Best Shooter Classics</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolving-the-critical-stop-error-blue-screen-with-code-0x00000133-in-windows-10/"><u>Resolving the Critical Stop Error: Blue Screen with Code 0X00000133 in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/saving-your-cortana-experiences-step-by-step-guide/"><u>Saving Your Cortana Experiences: Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-solving-windows-errors-top-8-methods/"><u>Swiftly Solving Windows Errors: Top 8 Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-simplified-image-editing-in-windows-photos/"><u>The Art of Simplified Image Editing in Windows Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-customize-windows-1011-icons-with-spacing-tweaks/"><u>Title: Customize Windows 10/11 Icons with Spacing Tweaks</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlocking-made-easy-the-best-10-apps-for-unlocking-your-infinix-smart-7-hd-device-by-drfone-android/"><u>Unlocking Made Easy The Best 10 Apps for Unlocking Your Infinix Smart 7 HD Device</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-top-video-rotation-tools-flip-spin-and-rotate-your-videos-online/"><u>Updated Top Video Rotation Tools Flip, Spin, and Rotate Your Videos Online</u></a></li>
</ul></div>

