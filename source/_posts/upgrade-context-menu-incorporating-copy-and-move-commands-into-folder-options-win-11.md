---
title: "Upgrade Context Menu: Incorporating Copy & Move Commands Into Folder Options (Win 11)"
date: 2024-08-28T01:09:32.302Z
updated: 2024-08-29T01:09:32.302Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Upgrade Context Menu: Incorporating Copy & Move Commands Into Folder Options (Win 11)"
excerpt: "This Article Describes Upgrade Context Menu: Incorporating Copy & Move Commands Into Folder Options (Win 11)"
keywords: Win 11 Upgrade,Copy Move Commands,Folder Options Update,Context Menu Enhancement,Windows Settings Improvement,File Management Tools,Optimize Windows Experience
thumbnail: https://thmb.techidaily.com/e82cf746d7129d54494e27c7a2ced91643ff65f2f3b23f8677650a8fb00dc7f5.png
---

## Upgrade Context Menu: Incorporating Copy & Move Commands Into Folder Options (Win 11)

 You may frequently need to move or copy files to alternative folders in Windows. To do this, you might move files to different folders by dragging and dropping them. To copy a file to another location, you can either hold the**Ctrl** key while dragging or utilize the copy-paste hotkeys.

 It would be better to have context menu options for moving and copying files to selected locations. Then you could right-click a file and select a**Move to folder** or**Copy to folder** option. This is how you can add context menu options for moving and copying files to folders in Windows 11/10.

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
6. Enter the value**{C2FBB630-2971-11D1-A18C-00C04FD75D13}** inside the**Data** box.  
![The value data for the Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-edit-string-window-for-the-copytokey.jpg)
7. Click the**OK** button to apply the value.
8. Close the Registry Editor app’s window.

 Then you can select the**Copy to folder** context menu option much the same as the move one. Right-click a file in Explorer, select**Show more options** (in Windows 11), and click**Copy to folder** . A Copy Items window will open from which you can choose a folder to include the copied file. Clicking**Copy** will paste the item into the selected folder.

![The Copy to folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option.jpg)

 You can remove the "Copy/Move to folder" options from the right-click menu by deleting their registry keys. Open the**ContextMenuHandlers** key location specified in step three for adding a Move to folder context menu option. Right-click the**Copy to folder** or**Move to folder** registry key and select**Delete** . Select**Yes** when prompted to confirm you’re sure about erasing that key.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
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
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
3. Choose a suitable directory to extract the archive outside the one it downloaded to, and click the**Select Folder** option.
4. Next, select**Show extracted files when complete** for the WinBubbles folder to automatically open after extraction.
5. Then click**Extract** to bring up the unzipped WinBubbles folder.  
![The Extract Compressed window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-extract-compressed-window.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
1. Now double-click WinBubbles EXE to launch that software.
2. Select the**Move to** option on the**General** tab.
3. Click the**Copy to** checkbox to select that option.  
![The Copy to option in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-checkbox.jpg)
4. Press WinBubble’s**Apply** option when highlighted yellow.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
![The Apply button in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/highlighted-apply-button.jpg)
5. A WinBubble dialog box window will appear confirming the tweaks have been saved. Click**OK** to close that message.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
6. Minimize or exit the WinBubble window.

 Now look at your new context menu options for copying and moving items to different locations. WinBubble adds them to the classic context menu like the manual registry tweak methods. So, you’ll still need to select**Show more options** or press**Shift** +**F10** to access those options in Windows 11.

 You can also utilize WinBubble to remove the "Copy/Move to Folder" options. Uncheck the selected**Move to** and**Copy to** checkboxes on its**General** tab. Click**Apply** to set the new options.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-the-secret-to-stylish-borders-in-instagram-visuals/"><u>[New] 2024 Approved  The Secret to Stylish Borders in Instagram Visuals</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-comparing-sharex-with-industry-leaders/"><u>[New] Comparing ShareX with Industry Leaders</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-battlefield-brethren-compiling-the-ultimate-7-fps-collection-for-2024/"><u>[Updated] Battlefield Brethren  Compiling the Ultimate 7 FPS Collection for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-locking-out-youtube-channels-on-computers-and-phones/"><u>[Updated] In 2024, Locking Out Youtube Channels on Computers and Phones</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-toy-wheels-tournament-tunes/"><u>[Updated] Toy Wheels Tournament Tunes</u></a></li>
<li><a href="https://extra-resources.techidaily.com/blueprint-for-effective-metaverse-engagement/"><u>Blueprint for Effective Metaverse Engagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-line-concoctions-5-hilarious-tricks-at-work/"><u>Command Line Concoctions: 5 Hilarious Tricks at Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correction-of-windows-1011-zoom-failure-code-1132/"><u>Correction of Windows 10/11 Zoom Failure - Code 1132</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/disabling-apple-iphone-xr-parental-restrictions-withwithout-password-by-drfone-ios/"><u>Disabling Apple iPhone XR Parental Restrictions With/Without Password</u></a></li>
<li><a href="https://extra-tips.techidaily.com/dive-into-display-dimensions-for-video-newbies/"><u>Dive Into Display Dimensions  For Video Newbies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-steam-error-on-windows-no-more-blank-screens/"><u>Fixing Steam Error on Windows: No More Blank Screens</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-find-and-install-the-right-hp-network-drivers-on-your-windows-machine-win-10-win-7-or-win-8/"><u>How to Find and Install the Right HP Network Drivers on Your Windows Machine (Win 10, Win 7 or Win 8)</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-the-soft-bricked-infinix-note-30-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked Infinix Note 30? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-can-i-remove-the-apple-watch-activation-lock-by-apple-iphone-12-without-the-previous-owner-by-drfone-ios/"><u>In 2024, Can I Remove the Apple Watch Activation Lock By Apple iPhone 12 without the Previous Owner?</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-xiaomi-redmi-note-12-4gwithwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Xiaomi Redmi Note 12 4Gwith/without a PC</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-jumpstart-to-understanding-av1-codecs/"><u>In 2024, Jumpstart to Understanding AV1 Codecs</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlocking-iphone-14-passcode-without-a-computer-by-drfone-ios/"><u>In 2024, Unlocking iPhone 14 Passcode without a Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instantly-install-hyper-v-on-your-windows-11-homesystem/"><u>Instantly Install Hyper-V on Your Windows 11 Homesystem</u></a></li>
<li><a href="https://review-topics.techidaily.com/iphone-8-plus-data-recovery-software-to-recover-lost-ios-data-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>iPhone 8 Plus® Data Recovery Software to Recover Lost iOS® Data | Stellar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-fingertip-input-windows-tutorial/"><u>Mastering Fingertip Input: Windows Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mobility-control-deactivation-in-w11/"><u>Mastering Mobility Control Deactivation in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-guide-to-bypass-ms-teams-error-80080300-on-windows-11/"><u>Mastery Guide to Bypass MS Teams Error 80080300 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-charmap-problems-with-ease/"><u>Mending Windows CharMap Problems with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-graphics-shortage-on-enchanted-magic-school-platform/"><u>Overcoming Graphics Shortage on Enchanted Magic School Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-steams-non-syncing-library-files/"><u>Quick Fix for Steam's Non-Syncing Library Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-eradicating-xbox-service-interruption/"><u>Quick Fixes: Eradicating Xbox Service Interruption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-powerful-cpu-usage-a-compre-cookie/"><u>Reducing Powerful CPU Usage: A Compre Cookie</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-the-disk-read-failure-issue-in-windows/"><u>Remedying the Disk Read Failure Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-unresponsive-windows-webcam/"><u>Remedying Unresponsive Windows Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-disconnected-win-ethernet/"><u>Resurrecting Disconnected Win Ethernet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-rectifying-white-login-screens-on-win1011-oses/"><u>Steps for Rectifying White Login Screens on Win10/11 OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-locate-and-open-windowsstore-folder/"><u>Steps to Locate and Open WindowsStore Folder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-to-22h2-windows-setbacks/"><u>Swift Solutions to 22H2 Windows Setbacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-error-0x0000007b-quick-fixes-for-windows/"><u>Taming Error 0X0000007B - Quick Fixes for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-halt-windows-shutdown-clock/"><u>Techniques to Halt Windows Shutdown Clock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-gpu-potential-win-friendly-tools-ranked-1-6/"><u>Unleash GPU Potential: Win-Friendly Tools Ranked #1-#6</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-optimized-web-linkage-in-your-windows-applications-today/"><u>Unlock Optimized Web Linkage in Your Windows Applications Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-windows-11s-auto-hdr-effectively/"><u>Utilizing Windows 11'S Auto HDR Effectively</u></a></li>
<li><a href="https://sound-issues.techidaily.com/warzone-voice-and-microphone-malfunctions-quick-solutions-for-console-and-pc-gamers/"><u>Warzone Voice & Microphone Malfunctions: Quick Solutions for Console & PC Gamers</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-wisdom-secrets-to-instant-dossiers-creation/"><u>Win11 Wisdom: Secrets to Instant Dossiers Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-edge-less-design-tips/"><u>Windows 11 Edge-Less Design Tips</u></a></li>
</ul></div>
