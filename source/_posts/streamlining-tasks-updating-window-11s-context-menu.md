---
title: "Streamlining Tasks: Updating Window 11'S Context Menu"
date: 2024-07-12T16:36:59.547Z
updated: 2024-07-13T16:36:59.547Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlining Tasks: Updating Window 11'S Context Menu"
excerpt: "This Article Describes Streamlining Tasks: Updating Window 11'S Context Menu"
keywords: Windows 11 Update,Menu Context Streamline,UI Enhancement W11,Context Menu Modernize,Task Optimization Win11,User Interface Simplify,Efficiency in WinMenu
thumbnail: https://thmb.techidaily.com/bc869d9d43a6e8eaba8010b4b670a5dfb48692bbace90e7ba999d6674c090e3f.jpg
---

## Streamlining Tasks: Updating Window 11'S Context Menu

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-turning-onoff-secure-boot-in-virtualbox/"><u>Step-by-Step Guide: Turning On/Off Secure Boot in VirtualBox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-remove-black-display-on-pc-webcam/"><u>Tips to Remove Black Display on PC Webcam</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/six-easy-steps-to-acquire-fb-links-for-free/"><u>Six Easy Steps to Acquire FB Links for FREE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-changing-windows-11-default-applications/"><u>Step-by-Step: Changing Windows 11 Default Applications</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/epic-plots-scripts-that-elevated-cinema/"><u>Epic Plots  Scripts that Elevated Cinema</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-the-ultimate-guide-to-popular-tiktok-reactions/"><u>[New] The Ultimate Guide to Popular TikTok Reactions</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-leading-firefox-recording-software-for-2024/"><u>[New] Leading Firefox Recording Software for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use GPS Joystick to Fake GPS Location On Xiaomi Redmi Note 12T Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-video-drivers-errors/"><u>Mastering the Art of Fixing Video Drivers Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-tips-for-leveraging-the-power-of-windows-11-calendar/"><u>Pro Tips for Leveraging the Power of Windows 11 Calendar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-visibility-unveiling-windows-11s-system-tray-and-hidden-items/"><u>Maximizing Visibility: Unveiling Windows 11'S System Tray & Hidden Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-badge-indicators-on-taskbars/"><u>Restoring Badge Indicators on Taskbars</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-fixed-bluetooth-pairing-error-in-win-os/"><u>Quick Guide to Fixed: Bluetooth Pairing Error in Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinvigorating-computers-top-8-windows-tricks/"><u>Reinvigorating Computers: Top 8 Windows Tricks</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/the-best-ispoofer-alternative-to-try-on-apple-iphone-se-2022-drfone-by-drfone-virtual-ios/"><u>The Best iSpoofer Alternative to Try On Apple iPhone SE (2022) | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-must-haves-alerts-windows-10-and-11-troubleshooting/"><u>Avoiding 'Must-Haves' Alerts: Windows 10 & 11 Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unreachable-issues-fixing-mb-service-disconnect-in-windows-11/"><u>Overcoming Unreachable Issues: Fixing MB Service Disconnect in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-mobile-app-positions-in-windows-ui/"><u>Mastery Over Mobile App Positions in Windows UI</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-pivot-to-popularity-mastering-video-flip-on-social/"><u>[New] In 2024, Pivot to Popularity  Mastering Video Flip on Social</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-the-best-of-the-best-28-video-to-gif-converter-reviews/"><u>New In 2024, The Best of the Best 28 Video to GIF Converter Reviews</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-win11s-reversion-of-files-to-read-only/"><u>Tackling Win11's Reversion of Files to Read-Only</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-cursor-visibility-on-win-11-a-guide/"><u>Maximizing Cursor Visibility on Win 11: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purging-steams-domain-name-system-on-windows-systems/"><u>Purging Steam's Domain Name System on Windows Systems</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713963442695-updated-hey-are-you-looking-for-video-reverse-effects-in-your-videos-then-you-are-at-the-right-place-this-article-will-guide-you-in-creating-a-video-reverse/"><u>Updated Hey! Are You Looking for Video Reverse Effects in Your Videos? Then, You Are at the Right Place. This Article Will Guide You in Creating a Video Reverse Effect for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-asus-rog-phone-7-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Asus ROG Phone 7 | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-launch-success-a-guide-to-10-motivating-movies/"><u>[New] Launch Success  A Guide to 10 Motivating Movies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenges-of-windows-11-licensing-expiration/"><u>Overcoming the Challenges of Windows 11 Licensing Expiration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-windows-11-faces-a-slow-uptake-from-users/"><u>Why Windows 11 Faces a Slow Uptake From Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-disconnected-pc-from-wireless-lan/"><u>Steps to Fix Disconnected PC From Wireless LAN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automating-power-indicators-full-charges-notify-you-in-win11/"><u>Automating Power Indicators: Full Charges Notify You in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-web-pace-unify-phone-and-laptop-connectivity/"><u>Balancing Web Pace: Unify Phone & Laptop Connectivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-your-workflow-why-the-latest-windows-outlook-matters/"><u>Revolutionize Your Workflow: Why the Latest Windows' Outlook Matters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-context-menu-quick-uninstall-in-win-1110/"><u>Mastering Context Menu: Quick Uninstall in Win 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unnoticed-slowdown-agents-innocent-looking-apps-for-windows-11/"><u>Unnoticed Slowdown Agents: Innocent-Looking Apps for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shifting-win11-to-new-subnets-easily/"><u>Shifting Win11 to New Subnets Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-from-starting-spotify-by-default/"><u>Stop Windows From Starting Spotify by Default</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-win-workflow-selecting-the-best-productivity-tools-for-windows-11/"><u>Pro-Win Workflow: Selecting the Best Productivity Tools for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rejuvenate-your-machine-windows-11s-bloatware-hack/"><u>Rejuvenate Your Machine: Windows 11'S Bloatware Hack</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfolding-windows-11s-enigma-insights-into-the-registry/"><u>Unfolding Windows 11'S Enigma: Insights Into the Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-resume-windows-netflix-playback/"><u>Strategies to Resume Windows Netflix Playback</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-performance-replacing-aged-technology/"><u>Streamlining Windows Performance: Replacing Aged Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-checklist-for-dolby-atmos-installation-in-windows/"><u>The Essential Checklist for Dolby Atmos Installation in Windows</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-10-essential-aspect-ratio-converter-solutions/"><u>Updated 2024 Approved 10 Essential Aspect Ratio Converter Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-ignoring-license-expires-messages-in-win11/"><u>Quick Tips: Ignoring ‘License Expires’ Messages in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-the-benefits-in-not-muting-wins-11-pushes/"><u>Uncovering the Benefits in Not Muting Wins 11 Pushes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restarting-the-windows-indexer-a-quick-guide/"><u>Restarting the Windows Indexer: A Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterpiece-ahead-initiating-mspaint-windows-11-style/"><u>Masterpiece Ahead: Initiating MSPaint, Windows 11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essentials-of-win11-personalized-volume-shortcuts/"><u>The Essentials of Win11 Personalized Volume Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-shift-whats-updated-in-windows-11/"><u>Navigating the Shift: What's Updated in Windows 11?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-non-scrolling-issue-in-microsoft-excel-pc/"><u>Resolve Non-Scrolling Issue in Microsoft Excel PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-workday-woes-into-productivity-peaks-using-windows-11s-tools/"><u>Transform Workday Woes Into Productivity Peaks Using Windows 11'S Tools</u></a></li>
</ul></div>
