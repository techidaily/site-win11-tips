---
title: Modernizing the User Experience with Windows 10/11 Shortcuts
date: 2024-09-11T01:20:50.093Z
updated: 2024-09-12T01:20:50.093Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Modernizing the User Experience with Windows 10/11 Shortcuts
excerpt: This Article Describes Modernizing the User Experience with Windows 10/11 Shortcuts
keywords: Win10 UX Improvements,Windows 10 Efficiency Boost,Shortcuts in Windows 10,Modern UI Enhancements,UX Optimization with Win11,Quick Access Windows Features,User-Friendly Window Settings
thumbnail: https://thmb.techidaily.com/909f3c7957e52f6fe9de5cd9ae15915a5af92e86352ca57ab485a51d50b112ab.png
---

## Modernizing the User Experience with Windows 10/11 Shortcuts

 You may frequently need to move or copy files to alternative folders in Windows. To do this, you might move files to different folders by dragging and dropping them. To copy a file to another location, you can either hold the**Ctrl** key while dragging or utilize the copy-paste hotkeys.

 It would be better to have context menu options for moving and copying files to selected locations. Then you could right-click a file and select a**Move to folder** or**Copy to folder** option. This is how you can add context menu options for moving and copying files to folders in Windows 11/10.





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129738/7443" target="_top" id="2129738">
  <img src="//a.impactradius-go.com/display-ad/7443-2129738" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129738/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Add a Move to Folder Context Menu Option

 To add new context menu options in Windows 11/10, you must tweak the[Windows registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) one way or another. The Registry Editor app enables users to customize Windows’ right-click menus by manually tweaking the registry. You can add a Move to folder option to the context menu with the Registry Editor as follows:

1. Bring up the Registry Editor with a method included in our[how to open regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) guide.
2. Click inside the address bar at the top of Registry Editor, and erase the current key location there.
3. Then enter this**ContextMenuHandlers** key location and press**Return** :  
`HKEY_CLASSES_ROOT\AllFilesystemObjects\shellex\ContextMenuHandlers`
4. Next, right-click**ContextMenuHandlers** and select the**New** submenu.
5. Click**Key** on the submenu.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-key-option.jpg)





<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129043/19576" target="_top" id="2129043">
  <img src="//a.impactradius-go.com/display-ad/19576-2129043" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129043/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




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





<!-- affiliate ads begin -->
<span id="1912746">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1912746.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20231-1912746">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1912746.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmindmanager.sjv.io%2Fc%2F5597632%2F1912746%2F20231'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1912746/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Add a Copy to Folder Context Menu Option

 The Windows context menu includes a**Copy** option, but that doesn’t enable you to select a destination for pasting the file. Thus, users must manually paste copied items into different folders after selecting that option. However, you can add a better**Copy to folder** context menu option that brings up a destination folder selection window like this:

1. Open the**ContextMenuHandlers** registry key as covered in the first three steps for adding a**Move to** folder option.
2. Click the**ContextMenuHandlers** with the right mouse button and select its New option.
3. Select**Key** to add a new one to the registry.
4. Type**Copy to folder** inside the text box for the new key.  
![The Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option-1.jpg)
5. Select**Copy to folder** and double-click its**(Default)** string.
6. Enter the value**{C2FBB630-2971-11D1-A18C-00C04FD75D13}** inside the**Data** box.  
![The value data for the Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-edit-string-window-for-the-copytokey.jpg)
7. Click the**OK** button to apply the value.
8. Close the Registry Editor app’s window.

 Then you can select the**Copy to folder** context menu option much the same as the move one. Right-click a file in Explorer, select**Show more options** (in Windows 11), and click**Copy to folder** . A Copy Items window will open from which you can choose a folder to include the copied file. Clicking**Copy** will paste the item into the selected folder.

![The Copy to folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option.jpg)





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135370/19272" target="_top" id="2135370">
  <img src="//a.impactradius-go.com/display-ad/19272-2135370" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135370/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 You can remove the "Copy/Move to folder" options from the right-click menu by deleting their registry keys. Open the**ContextMenuHandlers** key location specified in step three for adding a Move to folder context menu option. Right-click the**Copy to folder** or**Move to folder** registry key and select**Delete** . Select**Yes** when prompted to confirm you’re sure about erasing that key.

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
<a href="https://unicoeye.pxf.io/c/5597632/2134493/18498" target="_top" id="2134493">
  <img src="//a.impactradius-go.com/display-ad/18498-2134493" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134493/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




1. Now double-click WinBubbles EXE to launch that software.
2. Select the**Move to** option on the**General** tab.
3. Click the**Copy to** checkbox to select that option.  
![The Copy to option in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-checkbox.jpg)
4. Press WinBubble’s**Apply** option when highlighted yellow.  
![The Apply button in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/highlighted-apply-button.jpg)
5. A WinBubble dialog box window will appear confirming the tweaks have been saved. Click**OK** to close that message.




<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137204/26400" target="_top" id="2137204">
  <img src="//a.impactradius-go.com/display-ad/26400-2137204" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137204/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




6. Minimize or exit the WinBubble window.

 Now look at your new context menu options for copying and moving items to different locations. WinBubble adds them to the classic context menu like the manual registry tweak methods. So, you’ll still need to select**Show more options** or press**Shift** +**F10** to access those options in Windows 11.

 You can also utilize WinBubble to remove the "Copy/Move to Folder" options. Uncheck the selected**Move to** and**Copy to** checkboxes on its**General** tab. Click**Apply** to set the new options.





<!-- affiliate ads begin -->
<span id="1993645">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993645.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993645">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993645.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993645%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993645/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




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
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-unlock-youtubes-best-viewing-experience-with-ratios/"><u>[Updated] 2024 Approved Unlock YouTube's Best Viewing Experience with Ratios</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-best-practices-in-converting-videos-for-twitter/"><u>[Updated] Best Practices in Converting Videos for Twitter</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-how-to-amass-a-picture-collection-for-free-the-ultimate-12-website-guide/"><u>[Updated] In 2024, How to Amass a Picture Collection for Free – The Ultimate 12 Website Guide</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-laughlens-pictorial-humor-studio/"><u>2024 Approved LaughLens Pictorial Humor Studio</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-strategies-for-selecting-and-syncing-music-with-visuals/"><u>2024 Approved Strategies for Selecting and Syncing Music with Visuals</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-transform-your-photos-removing-backdrops-with-ease/"><u>2024 Approved Transform Your Photos Removing Backdrops with Ease</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-ultimate-action-camera-selection-under-100/"><u>2024 Approved Ultimate Action Camera Selection Under $100</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/accessing-vintage-facebook-content-tips-for-all-devices/"><u>Accessing Vintage Facebook Content Tips for All Devices</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/comparing-cable-tv-with-streaming-platforms-a-comprehensive-guide/"><u>Comparing Cable TV with Streaming Platforms – A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-enigma-unraveling-wacatacbmls-mechanism-on-windows/"><u>Deciphering the Enigma: Unraveling Wacatac.B!ml's Mechanism on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-windows-update-numbering-systems/"><u>Demystifying Windows Update Numbering Systems</u></a></li>
<li><a href="https://win-amazing.techidaily.com/effortless-installation-of-microsoft-sculpt-keyboards-latest-drivers/"><u>Effortless Installation of Microsoft Sculpt Keyboard's Latest Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-performance-of-faulty-windows-cleaners/"><u>Enhancing Performance of Faulty Windows Cleaners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-user-experience-3-ways-to-boost-mouse-speed/"><u>Enhancing User Experience: 3 Ways to Boost Mouse Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-picks-best-torrent-software-for-windows-devices/"><u>Expert Picks: Best Torrent Software for Windows Devices</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-google-frp-lock-from-oppo-a58-4g-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Oppo A58 4G Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correctly-fix-the-bluetooth-disappeared-error-on-windows-11-a-simple-guide/"><u>How to Correctly Fix the 'Bluetooth Disappeared' Error on Windows 11 – A Simple Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-vivo-y27s-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Vivo Y27s? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disable-or-remove-hyper-v-in-windows-11/"><u>How to Disable or Remove Hyper-V in Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-lock-apps-on-huawei-p60-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Huawei P60 to Protect Your Individual Information</u></a></li>
<li><a href="https://driver-download.techidaily.com/improve-graphic-experience-free-and-easy-intel-graphics-driver-downloads-for-windows-1011-devices/"><u>Improve Graphic Experience: Free & Easy Intel Graphics Driver Downloads for Windows 10/11 Devices</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-3-ways-to-fake-gps-without-root-on-nubia-z50-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Fake GPS Without Root On Nubia Z50 Ultra | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-oneplus-ace-2-pro-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock OnePlus Ace 2 Pro Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-resolve-your-iphone-11-pro-keeps-asking-for-outlook-password-drfone-by-drfone-ios/"><u>In 2024, Resolve Your iPhone 11 Pro Keeps Asking for Outlook Password | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovating-windows-subsystem-for-android-resource-utilization/"><u>Innovating Windows Subsystem for Android Resource Utilization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-fast-forward-youtube-on-windows-chrome/"><u>Mastering Fast-Forward YouTube on Windows Chrome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-of-windows-faults-0x0000004e-demystified/"><u>Mastery of Windows Faults: 0X0000004E Demystified</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/nifty-editing-edits-discover-the-top-5-online-strategies-for-cutting-and-condensing-videos-for-2024/"><u>Nifty Editing Edits Discover the Top 5 Online Strategies for Cutting & Condensing Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-wins-alert-settings-on-windows-11/"><u>Perfecting Wins Alert Settings on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalized-group-policy-application-on-windows-users-versions-1111/"><u>Personalized Group Policy Application on Windows Users, Versions 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-guide-stop-vmware-virtual-machine-error-in-win11/"><u>Quick Fix Guide: Stop VMware Virtual Machine Error in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-common-windows-onedrive-problems/"><u>Quick Fixes for Common Windows OneDrive Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rebooting-astra-pilot-link-on-latest-os-ws11/"><u>Rebooting Astra Pilot Link on Latest OS, WS11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefining-digital-canvas-4-key-upgrades-to-microsoft-paint/"><u>Redefining Digital Canvas: 4 Key Upgrades to Microsoft Paint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reworking-the-windows-experience-a-triad-of-tips/"><u>Reworking the Windows Experience: A Triad of Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-error-30005-creating-files-unsuccessful-in-windows/"><u>Solving Error 30005: Creating Files Unsuccessful in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-turn-offon-smartfiltration-on-windows-11/"><u>Steps to Turn Off/On SmartFiltration on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-handling-windows-11s-read-only-files/"><u>Strategies for Handling Windows 11'S Read-Only Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-windows-top-video-converters-reviewed/"><u>Streamline Your Windows: Top Video Converters Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-approach-from-mkv-to-mp4-on-windows-pcs/"><u>Streamlined Approach: From MKV to MP4 on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-outlook-performance-on-your-windows-machine/"><u>Supercharge Outlook Performance on Your Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swivel-pictures-perfectly-in-windows-11/"><u>Swivel Pictures Perfectly in Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-art-and-science-of-capturing-stunning-gopro-time-lapse-for-2024/"><u>The Art & Science of Capturing Stunning GoPro Time Lapse for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-ultimate-troubleshooting-tips-for-default-settings-crash-in-amd-radeon-wattman/"><u>The Ultimate Troubleshooting Tips for Default Settings Crash in AMD Radeon WattMan</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-updated-method-to-bypass-infinix-smart-7-frp-by-drfone-android/"><u>The Updated Method to Bypass Infinix Smart 7 FRP</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mysteries-of-sam-errors-windows-edition/"><u>Unraveling the Mysteries of SAM Errors, Windows Edition</u></a></li>
<li><a href="https://win-answers.techidaily.com/update-online-authentication-for-origin-players-fully-operational-now/"><u>Update: Online Authentication for Origin Players Fully Operational Now</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-final-cut-pro-x-title-templates-how-to-use-and-customize-them/"><u>Updated In 2024, Final Cut Pro X Title Templates How to Use and Customize Them</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-windows-app-interactivity-via-streamlined-connection-solutions/"><u>Upgrade Window's App Interactivity via Streamlined Connection Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-developing-a-security-focused-removal-applet/"><u>Windows 11: Developing a Security-Focused Removal Applet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/xbox-wont-start-try-these-fixes-for-windows-users/"><u>Xbox Won't Start? Try These Fixes for Windows Users</u></a></li>
</ul></div>
