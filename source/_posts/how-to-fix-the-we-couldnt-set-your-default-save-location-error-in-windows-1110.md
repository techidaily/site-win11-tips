---
title: How to Fix the “We Couldn't Set Your Default Save Location” Error in Windows 11/10
date: 2025-01-18T16:25:53.859Z
updated: 2025-01-24T22:50:50.384Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the “We Couldn't Set Your Default Save Location” Error in Windows 11/10
excerpt: This Article Describes How to Fix the “We Couldn't Set Your Default Save Location” Error in Windows 11/10
keywords: Solve Save Location Error,Windows Save Issue Fix,Windows 11/10 Default Setting,Correct Windows Saving Error,Set Default Save Path Windows,Overcome File Save Failure,Fix Windows Save Location Message
thumbnail: https://thmb.techidaily.com/d7dc5f497c3ff92b83099053ccb7b434fc4fb16a570e502a336cc42130adb602.jpg
---

## How to Fix the “We Couldn't Set Your Default Save Location” Error in Windows 11/10

 Users have reported error 0x80070005 or 0x80070539 arises when they try to set new apps to save to different external drive locations with Settings. Those error codes have the same message that says, “We couldn’t set your default save location.” This means users can’t change the default save location for apps.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Set Your User Account to Administrator

 If you’re utilizing a standard Windows account, [change your user account type](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) to an administrative one. A standard user account will prevent you from applying any more complicated system changes. Changing the save location for apps is something you might need admin privileges for.

![The Account type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-account-type-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Rename the WindowsApps Directory

 This error can arise because the WindowsApps folder where apps save is corrupted. Renaming the WindowsApps folder on the drive or partition you want to save apps can address such an issue. To do so, rename that folder as follows:

1. If you’re trying to set apps to save on an external drive, connect that hard drive to your PC.
2. [Open the File Explorer folder navigator](https://www.makeuseof.com/windows-open-file-explorer/) and click **This PC**.
3. Double-click the drive/partition you want to set as your default save location for apps.
4. Then, right-click on the WindowsApps folder and select its **Rename** context menu option. You should find that directory within the drive’s root directory.  
![The Rename option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-button.jpg)
5. Rename the folder to **WindowsApps.old** and press **Enter**.

6. Thereafter, try changing the default save location for apps again via Settings.

 If that still doesn’t work, then proceed to the next resolution.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/e4Nt2xXXtmE?si=CtKwFry4b0AJXnaN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Delete or Rename the WpSystem Folder

 Many users confirm that renaming or deleting the WpSystem folder fixes error 0x80070005\. WpSystem is a folder created to store app data. Try renaming that folder to **WpSystem.old** on the drive you can’t set to be a save location for apps, as outlined for the previous method. The WpSystem will be in the same directory as the WindowsApps folder.

 Alternatively, delete the WpSystem folder. You can [erase a file or folder in Explorer](https://www.makeuseof.com/windows-11-delete-select-files/) by right-clicking it and selecting **Delete**. If you can’t find that folder or this potential solution doesn’t work, try the next resolution.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-option.jpg)

## 4\. Set Full System Permission for the System Volume Folder

 Setting full permission for the System Volume folder is another confirmed fix for error 0x80070005\. Follow these steps to set full permission for the System Volume directory:

1. Go into File Explorer and click the three-dot **See more** menu > **Options**. In Windows 10, click **Options** on the **View** tab.
2. Select **View** on the Folder Options window.
3. Deselect the **Hide protected operating system files (Recommended)** option.  
![The Hide protected operating system files checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-protected-operating-system-files.jpg)
4. Select the **Show hidden files, folders and drives** radio button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/o-sRtqHdEYY?si=NMTMQVxJsUaoguqh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Click **Apply** to save the new Explorer settings.

1. Select the drive you need to set as the default save location for apps.
2. Right-click the System Volume Information folder and select **Properties**.
3. Click **Security > Advanced** to bring up an Advanced Security Settings window.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-tab.jpg)
4. Press the **Continue** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Next, click **Add** to view a Permission Entry window.

1. Click the **Select a principal** option.
2. Input **SYSTEM** inside the object name box.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-group.jpg)
3. Click on the **OK** button.

4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Close all remaining open windows. Then, restart your PC and try changing the default save location.

## Set a New Default Save Location in Windows 11/10

 Many users have needed to fix error 0x80070005 and have done so by applying the potential solutions in this guide. The WpSystem folder is often the source of the error, and resolution two is the most widely confirmed method for fixing this issue.

 However, some users have also fixed the issue by applying the less widely cited fourth method.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-best-ai-photo-editor/"><u>[New] 2024 Approved Best AI Photo Editor</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-androids-path-to-virtual-reality-tips-and-tricks/"><u>[New] Android's Path to Virtual Reality Tips and Tricks</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-excellent-face-changing-software-iphone-and-android/"><u>[New] Excellent Face-Changing Software, iPhone & Android</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-revolutionizing-audio-documentation-the-art-of-call-recording/"><u>[Updated] Revolutionizing Audio Documentation The Art of Call Recording</u></a></li>
<li><a href="https://android-unlock.techidaily.com/best-oppo-find-x7-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Oppo Find X7 Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-intels-onboard-video-a-walkthrough/"><u>Eliminate Intel's Onboard Video: A Walkthrough</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/hashtag-hype-unveiling-twitters-toptiktok-videos-for-2024/"><u>Hashtag Hype Unveiling Twitter's #TopTikTok Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-python-servers-into-windows-networks/"><u>Integrating Python Servers Into Windows Networks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-rectify-unresponsive-ccleaner-on-windows-os/"><u>Methods to Rectify Unresponsive CCleaner on Windows OS</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/simplify-your-inbox-discover-the-simple-method-that-eliminates-clutter-without-complicated-strategies-or-extra-email-addresses/"><u>Simplify Your Inbox: Discover the Simple Method That Eliminates Clutter Without Complicated Strategies or Extra Email Addresses!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-cure-windows-store-error-0x80072efd/"><u>Steps to Cure Windows Store Error 0X80072EFD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-reconnect-intermittent-ps4-controller-on-windows-system/"><u>Steps to Reconnect Intermittent PS4 Controller on Windows System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-scroll-start-zoom-7-methods-to-tame-wheel-woes/"><u>Stop Scroll, Start Zoom: 7 Methods to Tame Wheel Woes</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/209785244-9781788173940-surrender/"><u>Surrender | Free Book</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-pcs-command-landscape-pick-terminal/"><u>Transform Your PC's Command Landscape: Pick Terminal</u></a></li>
</ul></div>

