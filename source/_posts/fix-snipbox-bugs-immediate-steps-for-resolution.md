---
title: "Fix SnipBox Bugs: Immediate Steps for Resolution"
date: 2024-06-25T16:22:14.873Z
updated: 2024-06-26T16:22:14.873Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fix SnipBox Bugs: Immediate Steps for Resolution"
excerpt: "This Article Describes Fix SnipBox Bugs: Immediate Steps for Resolution"
keywords: SnipBox Bug Fix Guide,Quick SnipBox Solutions,SnipBox Troubleshooting,Fixing SnipBox Errors,Immediate SnipBox Repair,Resolve SnipBox Issues,Stop SnipBox Glitches
thumbnail: https://thmb.techidaily.com/865974c7bb05387b6277d30c79ecdc49aad19ee23c97d33e5069a1776373f52c.jpg
---

## Fix SnipBox Bugs: Immediate Steps for Resolution

 The Snipping Tool is an important feature of any Windows operating system; it allows users to capture, edit, and save screenshots directly onto their PC.

 However, since Windows Vista, the program hasn't been the most stable. Even as we moved onto Windows 10 and 11, the Snipping tool tended to run into strange issues. Such issues prompt the “Snipping tool not working” error repeatedly, which might hinder your workflow and slow you down.

 We have tracked down a few reasons why the Snipping Tool can stop working and how to easily resolve them. Let's have a look at how they can be dealt with.

## 1\. Restart the Windows File Explorer

 Let's start by going to the root of the problem. Since the Snipping Tool is a subset of the File Explorer service, it is most probable that the problem likely came from there. If File Explorer goes unresponsive, so too does the Snipping Tool.

 As such, restarting File Explorer may dislodge whatever's keeping the Snipping Tool from working correctly. To do this, press **Ctrl + Alt + Del**, then select **Task Manager**. Alternatively, you can press **CTRL + Shift + ESC** to jump directly into the Task Manager.

![Windows task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/task-manager-1.jpg)

 Scroll down until you find **Windows Explorer** and right-click it. In the drop-down menu that appears, select **Restart.**

 You will notice your desktop will go through some weird changes while File Explorer restarts.

 For example, the taskbar will vanish, and your desktop wallpaper will turn completely black. However, this is totally normal, as all of these elements rely on File Explorer. When you restart the service, it forces all of these elements to restart too.

 Once everything looks okay again, try opening the Snipping Tool and using it.

## 2\. Look for Interfering Third-Party Software

 Sometimes, a program you've recently downloaded can interfere with the smooth running of the Snipping Tool. If you want to reach the bottom of all this mystery, one way to know for sure is by following these steps given below:

1. Type in "system configuration" in the **Start menu** search bar and open the **System Configuration** panel.
2. Switch to the **Services** tab on the top, and then select the option to **hide all the Microsoft services** at the bottom.
3. Disable any service that you think might be interfering with the Snipping Tool.
4. Once you disable it, try running the Snipping Tool once again. If it works properly, it means that the app was in conflict with the Snipping Tool. It should be kept disabled to keep the Snipping Tool on your Windows working properly.

![Services tab in the system configuration section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/system-configuration.jpg)

## 3\. Run the Scannow Tool

 If all else fails and your Snipping Tool still isn't working, you can still use the **scannow** command to repair and restore the damaged files that cause it to malfunction. You can achieve this with the help of the [Command Prompt feature](https://www.makeuseof.com/run-command-prompt-commands-desktop-shortcut/).

 Follow these steps to continue:

1. Type "command prompt" in the **Start menu** search bar and run it as administrator. To do this, either click on **Run as Administrator** on the right panel, or right-click the search result and click **Run as Administrator**.
2. Once inside Command Prompt, type the following command and hit Enter:  
`sfc /scannow`
3. Next, type the following command to launch the Snipping Tool manually:  
`snippingtool.exe`  
 Once done, check to see if the error still persists.

![Windows command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt.jpg)

## 4\. Permit Snipping Tool to Run in the Background

 Snipping Tool also might not work if it lacks the necessary permission to run in the background. This means the app won't work unless you are active in the app's window. To rectify this, authorize the Snipping Tool's application to run in the background by following these steps:

1. Click the **Windows** icon and select **Settings** from the context menu.
2. Hit the **Privacy** button on the Settings page.
3. Scroll down to the panel on the left to locate **Background apps.**
4. Search for **Snip & Sketch** from the app list and ensure it's toggled on.

![List of Background Apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/background-apps-windows.jpg)

## 5\. Update Graphics Drivers

 Sometimes outdated or corrupt graphic drivers are the culprit behind a non-functioning Snipping Tool. Their core responsibility is capturing and processing the screenshot into a format the Windows device understands.

 If it’s outdated, it won’t translate the images appropriately and become incompatible with your computer, resulting in the "Snipping Tool not working" error. Hence, in this scenario, the key is to update these drivers to their latest build.

 Follow these steps to continue:

1. Right-click on the **Windows** icon and select **Device Manager** from the pop-up list.
2. Navigate to **Display adapters,** expand it, and right-click on the available driver.
3. Select **Update driver > Search automatically for drivers.** The system will quickly scan for any available drivers and install them.  
![Update Graphics Driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/update-graphics-driver.jpg)
4. Restart your Windows device.

## 6\. Update Your Windows Computer

 Windows regularly releases updates that fix your PC’s bugs, bring in new features and security-related patches, and generally make your Windows experiences much more accessible and better than before.

 If you haven’t done so in a while, now might be a good time to [update your Windows version](https://www.makeuseof.com/update-windows-manually/). Because this outdated Windows version might very well be the cause of your PC’s bugs or errors.

 So, head to Settings by pressing **Windows Key + I** and select **Windows Update**. The Windows Update app will start scanning your system automatically, and from there, all you have to do is click on **Download & install**and your Windows will be updated.

![windows update menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-update.jpg)

 If this didn't fix the Snipping Tool on your Windows either, jump to the next trick below.

## 7\. Disable Focus

[Focus, earlier known as Focus Assist](http://www.makeuseof.com/microsoft-windows-11-focus-assist-update/), is one of those apps that proves everything has pros and cons. If you’re prone to distraction, you might have used the app already and successfully wiped out many distractions from notifications and random pop-ups.

 However, along with these notifications and other random pings, the feature also blocks out many useful apps—this includes Snipping Tool as well. So, disabling the Focus Assist app can help out here.

 Follow these steps to disable Focus Assist on Windows:

1. Head to the **Start menu** search bar, type in ‘settings,’ and select the best match.
2. From the **Settings** window, choose **System > Focus Assist**.
3. Now toggle off the **Focus assist** features, and you’ll be good to go.

![focus feature on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/focus-feature-on-windows-1.jpg)

 That’s it—when you have the Focus feature disabled, try out the Snipping Tool again. It should be working now in most cases.

## 8\. Reset the Snipping Tool App

 Sometimes things go awry for the weirdest reasons you can’t explain; your apps on Windows are no exception from accidents of such kind.

 When you find any of your Windows apps in a place like this, one of the best tricks is to give the app a quick reset. The reset will bring your app to default settings where everything works smoothly.

 Follow these steps to reset the Snipping Tool app:

1. Launch the Settings app and head to **Apps > Installed apps**.
2. From there scroll down, find the Snipping tool, and then click on **Advanced options**.
3. Find the **Reset** section and then click on the **Reset** button.

![Windows snipping tool reset](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/snipping-tool-reset-1.jpg)

 You’ll get asked for a confirmation for the reset. Click on **Reset** to finally go ahead with the reset, and wait for a check sign to appear before the button. As soon as the button appears, your app will have been reset.

 If the Snipping Tool error was caused because of an abrupt mistake in the app, it should be resolved by the end of the above steps.

## 9\. Enable the Auto Copy Feature

 If someone has disabled the auto-save feature on Snipping Tool, the screenshots won’t be saved in your default location automatically.

 To make sure that’s not the case, launch the Snipping Tool and click on the **Settings** menu (the ellipses icon from the top-right corner).

![Windows snipping tool settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/snipping-tool-settings-1.jpg)

 Once done, toggle on **Automatically save screenshots**. When you have this setup your screenshots will be saved instantly, solving your Snipping Tool errors for good.

## Expanding More on the Snipping Tool

 Because the Snipping Tool is associated with taking screenshots, its importance can’t be understated. Screenshots are an easy way to communicate data and not being able to use this function can leave you in a lurch.

 There’s no doubt about the Snipping Tool being an integral part of the Windows OS; therefore, it is also essential to make full use of this function. Knowing all the useful tips and tricks, shortcuts, and how to make your own hotkeys will make it much easier to capture, edit, and save your screenshots on your Windows PC.

 However, since Windows Vista, the program hasn't been the most stable. Even as we moved onto Windows 10 and 11, the Snipping tool tended to run into strange issues. Such issues prompt the “Snipping tool not working” error repeatedly, which might hinder your workflow and slow you down.

 We have tracked down a few reasons why the Snipping Tool can stop working and how to easily resolve them. Let's have a look at how they can be dealt with.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/maximize-your-desktop-potential-with-new-features-in-win-11-widgets/"><u>Maximize Your Desktop Potential with New Features in Win 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hack-your-hardware-close-multiple-windows-at-once/"><u>Hack Your Hardware: Close Multiple Windows at Once</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-ip-and-mac-info-with-windows-powershell/"><u>Unraveling IP and MAC Info with Windows Powershell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfettered-functions-embrace-tiny11s-power/"><u>Unfettered Functions: Embrace Tiny11's Power</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-directdraw-errors-with-ease-on-new-windows-oses/"><u>Fixing DirectDraw Errors with Ease on New Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-constant-edge-activity-in-windows-11/"><u>Understanding Constant Edge Activity in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-no-server-issues-fixes-and-tips-for-apex-on-windows-(156-chars/"><u>Overcoming 'No Server' Issues: Fixes and Tips for Apex on Windows (<156 Chars)</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-from-business-idea-to-boardroom-on-instagram/"><u>2024 Approved  From Business Idea to Boardroom on Instagram</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-blending-brands-joining-instagram-and-facebook-effortlessly/"><u>[New] In 2024, Blending Brands  Joining Instagram and Facebook Effortlessly</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-joining-friends-showtime-on-tiktok-with-ease/"><u>[New] In 2024, Joining Friends’ Showtime on TikTok with Ease</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-add-edge-to-insta-videos-a-trifecta-guide/"><u>[New] In 2024, Add Edge to Insta Videos - A Trifecta Guide</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-social-spectacle-snatcher/"><u>[New] Social Spectacle Snatcher</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-10-alternative-video-editors-to-replace-windows-movie-maker/"><u>New 2024 Approved 10 Alternative Video Editors to Replace Windows Movie Maker</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-revolutionizing-facebook-advertising-through-creative-insight/"><u>[Updated] Revolutionizing Facebook Advertising Through Creative Insight</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-guide-to-free-music-for-mindfulness-and-serenity/"><u>In 2024, Guide to Free Music for Mindfulness & Serenity</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>