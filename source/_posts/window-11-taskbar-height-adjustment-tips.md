---
title: Window 11 Taskbar Height Adjustment Tips
date: 2024-10-11T07:39:50.603Z
updated: 2024-10-15T07:22:55.874Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Window 11 Taskbar Height Adjustment Tips
excerpt: This Article Describes Window 11 Taskbar Height Adjustment Tips
keywords: Window 11 Setup,New Taskbar Height,Adjust Taskbar Size,Windows 11 Customize,Taskbar Sizing Guide,Optimize Taskbar Display,Taskbar Config Tips
thumbnail: https://thmb.techidaily.com/38a7a5c0a5123e7708eb11aa967d228491b39460885352e6b8c3f7846969574b.jpg
---

## Window 11 Taskbar Height Adjustment Tips

 Ever looked at the Windows 11 Taskbar and thought it looks too small for your liking? Or maybe you feel it could be a little smaller? If that’s the case, you can change its size to suit your needs by making it bigger or smaller.

 Unlike Windows 10, you can’t just unlock the Taskbar and adjust its size freely in Windows 11\. While Microsoft has removed this way of going about it in Windows 11, there is a workaround that you can use, although it’s not as elegant.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How Do I Make the Windows 11 Taskbar Bigger or Smaller?

 The only way to change the size of the Taskbar is to use the Registry Editor. However, we advise caution when dealing with the Windows Registry because if something goes wrong, you might experience performance issues on your Windows 11 PC. If you’re unfamiliar with it, we recommend reading our guides on[what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) and[how to not mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) .

 Once you’re all caught up or are already familiar with the Windows Registry, and you know what you’re doing, you can make the Taskbar bigger or smaller. To do that:

1. Start by pressing**Win + R** to open Windows Run.
2. Type**regedit** in the text box and hit the**Enter** key.
3. Then, click**Yes** on the UAC prompt to launch the Registry Editor.
4. Copy and paste the below text in the address bar of the Registry Editor and hit the**Enter** key:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the**Advanced** key, look for a value called**TaskbarSi** . If it’s not there, right-click**Advanced** , select**New > DWORD (32-bit) Value** , and name that value**TaskbarSi.**  
![creating a new dword in the advanced key in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/new-dword-advanced-regedit.jpg)
6. Double-click**TaskbarSi** to edit it, and then enter**2** in the**Value data** text box and click**OK** to make the Taskbar bigger.  
![changing the taskbarsi value to 2 in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/taskbarsi-value-2.jpg)

 Once you restart your computer, you will see the result: an enlarged Taskbar.

![an enlarged Taskbar on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-enlarged-taskbar.jpg)

 To make the Taskbar smaller, enter**0** in the**Value data** text box, click**OK** , and then restart your computer. You will then see that the Taskbar has shrunk.

![a smaller taskbar in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-small-taskbar.jpg)

 If you decide to go back to the Taskbar’s default size, you can easily set**Value data** to**1** or simply delete the**TaskbarSi** value.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139114/17108" target="_top" id="2139114">
  <img src="//a.impactradius-go.com/display-ad/17108-2139114" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139114/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Adjust the Taskbar’s Size to Suit Your Needs on Windows 11

 Even though you can’t make the Taskbar bigger or smaller on Windows 11 as easily as you can on Windows 10, a little know-how can help. And as long as you followed the instructions mentioned above correctly, you shouldn’t worry about messing up the Windows Registry. However, we still recommend that you use this method only if you know what you’re doing.

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
<li><a href="https://fox-cloud.techidaily.com/new-seamless-shifts-creating-timelapse-videos-on-samsung-devices/"><u>[New] Seamless Shifts Creating Timelapse Videos on Samsung Devices</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-instant-archive-access-revived-deleted-reddit-entries/"><u>[Updated] Instant Archive Access Revived Deleted Reddit Entries</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-the-ultimate-guide-to-gourmet-cookies-for-every-palate-for-2024/"><u>[Updated] The Ultimate Guide to Gourmet Cookies for Every Palate for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-open-the-display-settings-in-windows-11/"><u>10 Ways to Open the Display Settings in Windows 11</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-the-essentials-of-image-augmentation-inserting-text-into-images-for-pc-and-mac-users/"><u>2024 Approved The Essentials of Image Augmentation Inserting Text Into Images for PC & Mac Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-tricks-to-correct-your-pcs-pink-screen-misstep/"><u>5 Tricks to Correct Your PC's Pink Screen Misstep</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-mastery-accessing-windows-admin-settings/"><u>Achieving Mastery: Accessing Windows Admin Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-discord-updates-and-autostart-on-windows-10/"><u>Avoid Discord Updates & Autostart on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-using-powertoys-copy-pasting-features/"><u>Boost Efficiency: Using PowerToys' Copy-Pasting Features</u></a></li>
<li><a href="https://android-unlock.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-asus-rog-phone-8-pro-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Asus ROG Phone 8 Pro</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/complete-guide-steps-to-revoke-itunes-and-apple-store-subscriptions-using-your-iphone-on-latest-ios-version/"><u>Complete Guide: Steps to Revoke iTunes & Apple Store Subscriptions Using Your iPhone on Latest iOS Version</u></a></li>
<li><a href="https://win-solutions.techidaily.com/comprehensive-fixes-for-unresponsive-moments-during-a-session-of-fall-guys-on-desktop/"><u>Comprehensive Fixes for Unresponsive Moments During a Session of Fall Guys on Desktop</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-instagram-video-editor-how-to-edit-instagram-videos/"><u>In 2024, Instagram Video Editor How to Edit Instagram Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719341599288-windows-chatbot-simulation-localize-for-free-with-gpt4all/"><u>Windows ChatBot Simulation: Localize for Free with GPT4All</u></a></li>
</ul></div>

