---
title: How to Correct Windows VLC Unreadable Input Error
date: 2024-12-20T02:18:40.398Z
updated: 2024-12-22T05:08:49.689Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Correct Windows VLC Unreadable Input Error
excerpt: This Article Describes How to Correct Windows VLC Unreadable Input Error
keywords: Fixing VLC Playback Errors,Resolving VLC File Format Issues,Overcoming VLC Unreadable Content,Removing VLC Video Input Problems,Tackling VLC Editing Errors,Addressing Windows VLC Malfunctions,Correcting VLC Playback Notifications
thumbnail: https://thmb.techidaily.com/b5066dad0b601fca3256158753d40238cd5a1c7754394d186d31755e512b1e70.jpg
---

## How to Correct Windows VLC Unreadable Input Error

 It is not often that VLC Media Player fails to play a file. But sometimes, when you try to open a media file, you may encounter the "your input can’t be opened" error on VLC. This error can occur with both local media files and when you try to stream a YouTube video, albeit for different reasons.

 Invalid file or folder name, issues with the VLC media player, and issues with YouTube.luac file are the common causes of this error. If you experience this error, here are a few quick fixes to resolve the "your input can’t be opened" VLC error on Windows.

 If the error occurs when streaming a YouTube video, skip to the fourth solution in this guide.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Change the File/Folder Path

![copy folder file move windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/copy-folder-file-move-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/omWG4u39lmE?si=yk1AEo_gzDpGjYbl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The "your input can’t be opened" error can occur if the folder path for the saved media is too long. For example, if your file is saved in D:\\Users\\Downloads\\Media\\New\\Files, moving it to a main folder such as**D:\\Users** can fix the issue.

To move the media file to a different folder:

1. Press**Win + E** to open**File Explorer** .
2. Next, navigate to the folder where your media files are saved.
3. Right-click on the media file and select**Copy** .
4. Next, create a new folder in**D:\\Users** and paste the file. Now open the file to see if it plays without the error.

## 2\. Change Folder or File Name

![rename file folder windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/rename-file-folder-windows-11.jpg)

 If you have a large folder with hundreds of media files,[renaming the folder or file on Windows](https://www.makeuseof.com/windows-11-rename-files/) can help you fix this error. Try to rename the folder with a short name to fix the error.

 That said, if the issue is with individual files, try to rename the video file to something simple without using any special characters. Even if the original file name has no visible special characters, rename it with a random name and then try to play the media.

To rename the folder:

1. Press**Win + E** to open**File Explorer** .
2. Next, navigate to the folder which has your media files with errors.
3. Select and right-click on the folder.
4. Select the**Rename** option from the context menu. Alternatively, press**F2** on your keyboard to access the rename option.
5. Rename the folder or file to a small name than the current folder name. Avoid using any special characters.
6. Once renamed, open the folder and play any media file with the error to see if the problem is resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l4R7_qNIQvY?si=2zJOPfEcm6_3udzn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Reset VLC Media Player Preference

 VLC offers tons of customization options. If the error is triggered after making a change to the VLC media player, you can reset the preferences to fix the issue.

 Note that when you reset preferences, you will lose all the changes made to your VLC media player. To reset VLC's preferences:

1. Launch the**VLC Media Player** and click on**Tools** .
2. Select**Preferences** from the context menu. Alternatively, press**Ctrl + P** to open the Simple Preferences dialog.  
![vlc media player preferences](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/vlc-media-player-preferences.jpg)
3. In the**Interface** tab, scroll down and click on**Reset Preferences.**  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![reset preferences vlc media player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-preferences-vlc-media-player.jpg)
4. Click**OK** when the **Are you sure you want to reset your VLC media player preferences** dialog appears.
5. Relaunch the VLC media player and try to play the media file to see if the error is resolved.

## 4\. Modify the Youtube.luac VLC File to Fix Issues With YouTube Video Steaming

 When trying to stream a YouTube video, you may encounter the VLC is unable to open the MRL error. To fix the YouTube streaming error on VLC, you’ll need to modify an associated YouTube.luac file and replace it with a new script available on GitHub. Here’s how to do it.

1. Open the[GitHub page for the YouTube.luac file](http://github.com/videolan/vlc/blob/master/share/lua/playlist/youtube.lua) .
2. Next, select all the content of the script on the YouTube.luac page. Alternatively, click the**Copy raw content** button in the top right corner to copy the code to your clipboard.  
![youtube luac code script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/youtube-luac-code-script.jpg)
3. Next, press the**Win key** and type**VLC** .
4. Right-click on the VLC Media Player icon and select**Open File Location.**  
![open vlc media player file location](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-vlc-medai-player-file-location.jpg)
5. Next, right-click again on the**VLC media player** icon in the new**File Explore** tab and select**Open file location.**

1. Here, locate and open the**lua** folder.
2. Next, open the**playlist** folder.
3. Locate and right-click on the**youtube.luac** file.  
![edit youtube luac file vlc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/edit-youtube-luac-file-vlc.jpg)
4. Select**Open with** and select**Notepad++** or another text file editor to open the file.  

![youtube luac script save](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/youtube-luac-script-save.jpg)
5. When the file opens, press**Ctrl + A** to select all the contents of the file. Then, press**Ctrl + V** to paste the script copied from the GitHub page for VLC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Press**Ctrl + S** and click**Yes** to confirm the action.

 Once the file is saved, launch VLC and check if the error is resolved. If not, try to create a new text file with the above script and save it as**youtube.lua** . Next, delete the**youtube.luac** file in**VLC\\lua\\playlist** and then move the**youtube.lua** file to the same folder. Try to stream any YouTube video via VLC to check if the error is resolved.

## 5\. Take Ownership of the Media File

 You can[take ownership of a file in Windows](https://www.makeuseof.com/take-ownership-of-windows-files-and-folders-with-these-tools/) to fix the "your input can’t be opened" error in VLC. Taking ownership should work if the error is triggered due to insufficient permission to access the file.

To take ownership of a media file:

1. Open**File Explorer** and navigate to the location where the file is stored.
2. Right-click on the media file and select**Properties** .  
![properties media](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/properties-media.jpg)
3. In the**Properties** dialog, open the**Security** tab.
4. Next, click the**Advanced** button.  
![file properties advanced security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-properties-advanced-security.jpg)
5. Click the**Change** button for**Owner** .  

![file properties advanced security change owner](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-properties-advanced-security-change-owner.jpg)
6. Next, type your user account name in the**Enter** t**he object name to select the** field and click**Check Names.**  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![file properties advanced security change owner select user group](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-properties-advanced-security-change-owner-select-user-group.jpg)
7. If the user is found, click**OK** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8. Click**Apply** and**OK** on all the open dialogs to save the changes.

## 6\. Reinstall VLC Media Player

 In rare instances, the error can be due to an issue with the VLC app. If none of the solutions above work, try to uninstall and reinstall VLC to see if that helps fix the error.

To uninstall the VLC media player:

1. Press**Win + I** to open**Settings** .
2. Next, open the**Apps** tab in the left pane.  
![windows 11 view installed apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-view-installed-apps.jpg)
3. Click on**Installed apps** and then search for VLC.  
![uninstall vlc media player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-vlc-media-player.jpg)
4. Click the**three-dots menu** for the VLC media player and select**Uninstall** . Click**Uninstall** once again to confirm the action.

5. Once uninstalled, open the[VLC media player page](https://www.videolan.org/vlc/) and download the installer. Install the app and check for any improvements.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Invalid File Name and Long File Path Triggers This Error

 If the error occurs when playing a local media file, you can fix it by renaming it or moving it to a different folder. Often an invalid file name issue seem to trigger this error on VLC. However, to fix the issue while streaming a YouTube video, you’ll need to modify the youtube.luac file and add the new code to make it work again.

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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-decoding-vimeo-where-creative-videos-meet/"><u>[New] 2024 Approved Decoding Vimeo Where Creative Videos Meet</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-surging-social-media-accelerating-instagram-interactions/"><u>[New] Surging Social Media Accelerating Instagram Interactions</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-a-stepwise-journey-through-the-world-of-professional-srt-creation/"><u>[Updated] A Stepwise Journey Through the World of Professional SRT Creation</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-the-ultimate-action-plan-from-ttml-and-xml-to-srt-translation-for-2024/"><u>[Updated] The Ultimate Action Plan From TTML & XML to SRT Translation for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/apple-targets-dominant-web-browser-with-alarming-new-ad-campaign-revealed-on-zdnet/"><u>Apple Targets Dominant Web Browser with Alarming New Ad Campaign Revealed on ZDNet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/corrective-measures-for-faulty-brightness-fn-key-in-windows-11/"><u>Corrective Measures for Faulty Brightness Fn Key in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discreet-data-transfer-embedding-zip-in-windows-image-files/"><u>Discreet Data Transfer: Embedding ZIP in Windows Image Files</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-what-legendaries-are-in-pokemon-platinum-on-poco-c51-drfone-by-drfone-virtual-android/"><u>In 2024, What Legendaries Are In Pokemon Platinum On Poco C51? | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/ingenious-webcam-use-cases-at-home/"><u>Ingenious Webcam Use Cases at Home</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/inside-the-pros-and-cons-of-onyx-boox-tab-ultra-a-comprehensive-guide-to-the-premier-e-paper-tablet/"><u>Inside the Pros and Cons of Onyx Boox Tab Ultra: A Comprehensive Guide to the Premier E-Paper Tablet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-turn-off-defender-firewall/"><u>Mastering Windows 11: Turn Off Defender Firewall</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-invalid-captcha-response/"><u>Navigating the 'Invalid' CAPTCHA Response</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-inefficient-workflow-rulesets-in-outlook/"><u>Overcoming Inefficient Workflow Rulesets in Outlook</u></a></li>
<li><a href="https://extra-skills.techidaily.com/panorama-pixels-cutting-edge-photo-assembler-for-2024/"><u>Panorama Pixels Cutting-Edge Photo Assembler for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-balanced-windows-audio-output-for-two-sides/"><u>Restoring Balanced Windows Audio Output for Two Sides</u></a></li>
<li><a href="https://tech-hub.techidaily.com/revolutionizing-support-leading-5-cognitive-bot-apps/"><u>Revolutionizing Support: Leading 5 Cognitive Bot Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-typing-tips-eliminate-latency-in-win-11-pcs/"><u>Speedy Typing Tips: Eliminate Latency in Win 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-6-best-computer-usage-tracking-apps-for-windows/"><u>The 6 Best Computer Usage Tracking Apps for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricks-to-modify-static-power-controls-in-windows-11/"><u>Tricks to Modify Static Power Controls in Windows 11</u></a></li>
</ul></div>

