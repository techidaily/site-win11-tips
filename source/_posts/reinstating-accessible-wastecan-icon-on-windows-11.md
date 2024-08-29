---
title: Reinstating Accessible Wastecan Icon on Windows 11
date: 2024-08-28T01:18:16.076Z
updated: 2024-08-29T01:18:16.076Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Accessible Wastecan Icon on Windows 11
excerpt: This Article Describes Reinstating Accessible Wastecan Icon on Windows 11
keywords: Wastecan Accessibility,Win11 Waste Icon,Wastebins in Win11,Accessible Bin Icon,Waste Management Icon,Windows 11 Bin Icon,Restore Waste Can Symbol
thumbnail: https://thmb.techidaily.com/e35da50e74d4ad42a2d4ca6cbb01ed721572402298c4b208ceac1efbbaaf58d4.png
---

## Reinstating Accessible Wastecan Icon on Windows 11

 The Recycle Bin has been a staple on Windows for a long time, but not everyone wants it on the desktop. You can disable it via the Desktop Icon Settings, but there is a bug where if you try to re-enable it, the "Recycle Bin" option is grayed out and cannot be toggled.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

## 1\. How to Bring Back the Recycle Bin Using the Group Policy Editor

 The Group Policy Editor lets you show or hide the Recycle Bin icon from the desktop. Check if you have modified and accidentally disabled the Recycle Bin group policy recently. If so you can set the Remove Recycle Bin icon from the desktop policy to "Not Configured" which will restore it.

 You may not find the Local Group Policy Editor in Windows Home Edition. However, you can run a batch script to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) or skip to the Registry Editor-based fix in the next step.

 To restore the Recycle Bin icon using the Group Policy Editor:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor**.  
![gpedit msc windows 11 run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/gpedit-msc-windows-11-run.jpg)
3. Next, navigate to the following location:  
`User Configuration > Administrative Templates > Desktop`
4. In the right pane, locate and double-click on the **Remove Recycle Bin icon from the desktop** option to open its properties.  
![edit remove recycle bin icon from settings gpedit policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy.jpg)
5. In the **Properties** dialog, select **Not Configured**.  
![edit remove recycle bin icon from settings gpedit policy not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy-not-configured.jpg)
6. Click **Apply** and **OK** to save the changes.

 Close the Group Policy Editor and check your desktop to see if you can access the Recycle Bin. If not, make sure the Recycle Bin is set to show in Desktop Icon Settings.

 To enable Recycle Bin in Desktop Icon Settings:

1. Press **Win + I** to open **Settings**.
2. Next, open the **Personalization** tab in the left panel.
3. Click on **Themes**.  
![desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/desktop-icon-settings-windows-11.jpg)
4. Click on **Desktop icon settings** under the **Related settings** section.
5. In the **Desktop Icon Settings** dialog, select **Recycle Bin**.  
![enable recycle bin desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/enable-recycle-bin-desktop-icon-settings-windows-11.jpg)
6. Click **Apply** and **OK** to save the changes.

 If you can’t access Group Policy Editor or if the issue persists, you can use the Registry Editor to fix this problem.

## 2\. Modify the Recycle Bin Registry Settings

 Another way to resolve and restore the grayed-out Recycle Bin icon in the Desktop settings is via the Windows Registry. You can modify the registry entry value responsible for the settings and configurations of Recycle Bin working to restore the functionality.

 Making modifications to the Windows registry involves tweaking settings that may harm your device if performed incorrectly. We recommend you [create a Windows restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [take a Windows registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before attempting to modify the Windows registry.

 To modify the Recycle Bin registry value:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**. Click **Yes** if prompted by **User Account Control**.
3. In the Registry Editor, navigate to the following location. You can copy and paste the path in the editor for quicker navigation:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\NonEnum`
4. In the right pane, locate the **{645FF040-5081-101B-9F08-00AA002F954E}** DWORD (32-bit) value.  
![registry editor nonnum new dword value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value.jpg)
5. If it does not exist, you’ll need to create a new value. To do this, right-click on the **NonEnum** subkey folder in the left pane and select **New > DWORD (32-bit) Value**.
6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
8. Type **0** in the Value data field and click **OK** to save the changes.
9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
## Get Access to the Recycle Bin Desktop Icon Setting Again

 An incorrectly modified group policy can gray out the Recycle Bin icon in the Desktop Icon Settings dialog. Fortunately, it's an easy fix, and you should now have your Recycle Bin back to how you like it.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-power-up-your-discord-experience-with-the-art-of-adding-gifs/"><u>[New] 2024 Approved  Power up Your Discord Experience with the Art of Adding GIFs</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-exploring-originality-how-to-uncover-roots-of-instagram-visuals/"><u>[New] Exploring Originality  How to Uncover Roots of Instagram Visuals</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-six-winning-strategies-to-recording-and-saving-mov-on-windows-11/"><u>[New] Six Winning Strategies to Recording and Saving .mov on Windows 11</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-craft-powerful-tags-for-maximum-youtube-engagement/"><u>[Updated] In 2024, How to Craft Powerful Tags for Maximum Youtube Engagement</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-the-beginners-handbook-to-instagrams-most-popular-feature-reels/"><u>[Updated] In 2024, The Beginner’s Handbook to Instagram’s Most Popular Feature – Reels</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-whats-catching-eyes-the-leading-8-video-sensations-for-2024/"><u>[Updated] What's Catching Eyes? The Leading 8 Video Sensations for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-unlock-android-games-funimate-pro-apk-deep-dive/"><u>2024 Approved  Unlock Android Games - Funimate Pro APK Deep Dive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-the-slate-executing-a-clean-boot-in-windows-11/"><u>Clearing the Slate: Executing a Clean Boot in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-the-most-effective-tool-for-win-soft-dependency/"><u>Discovering the Most Effective Tool for Win Soft Dependency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empowering-policy-management-using-gpresult/"><u>Empowering Policy Management Using GPResult</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-file-writing-capability-in-windows-1011/"><u>Enhancing File Writing Capability in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-system-safety-with-new-passwords-in-win-11/"><u>Enhancing System Safety with New Passwords in Win 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-resolved-fix-for-semaphore-error-code-0x80070079-now-available/"><u>Error Resolved: Fix for Semaphore Error Code 0X80070079 Now Available</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-procedure-to-clear-steams-domain-name-service-caches/"><u>Essential Procedure to Clear Steam's Domain Name Service Caches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-bypass-the-admin-restriction-error-message-on-pcs/"><u>How to Bypass the Admin Restriction Error Message on PCs</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-nokia-c110-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Nokia C110 to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-apple-iphone-11-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Apple iPhone 11 Pro | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-12-mini-with-a-mask-on-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 12 mini with a Mask On</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-pioneering-visual-stories-with-windows-10-photos-and-story-remix/"><u>In 2024, Pioneering Visual Stories with Window's 10 Photos & Story Remix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/make-full-privilege-access-to-terminal-a-snap-shot/"><u>Make Full-Privilege Access to Terminal A Snap Shot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-concurrent-archive-decompression-in-a-digital-age/"><u>Mastering Concurrent Archive Decompression in a Digital Age</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-gpos-on-user-profiles-in-windows-11-and-11/"><u>Mastering GPOs on User Profiles in Windows 11 & 11</u></a></li>
<li><a href="https://facebook.techidaily.com/mastery-over-mobile-facebook-exploration/"><u>Mastery Over Mobile Facebook Exploration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-extender-writes-to-reduce-power-draw/"><u>Optimizing Extender' Writes to Reduce Power Draw</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-error-0x80041015-on-windows-a-step-by-step-guide/"><u>Overcoming Error 0X80041015 on Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-errors-when-attempting-to-login-to-battlenet/"><u>Overcoming Errors When Attempting to Login to Battle.net</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-input-sluggishness-in-win-os-via-7-fixes/"><u>Overcoming Input Sluggishness in WIN OS via 7 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-text-display-error-w11s-msresource-challenge/"><u>Overcoming Text Display Error: W11's MsResource Challenge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-your-desktop-image-in-windows-easily/"><u>Personalizing Your Desktop Image in Windows Easily</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ng-perfection-30-unique-and-appealing-recipe-channels-for-2024/"><u>Plating Perfection  30 Unique and Appealing Recipe Channels for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-lost-luster-how-to-repeat-steam-accomplishments/"><u>Restore Lost Luster: How to Repeat Steam Accomplishments</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/saving-the-world-one-movie-at-a-time-watch-supermans-epic-adventures-in-order/"><u>Saving the World, One Movie at a Time: Watch Superman's Epic Adventures in Order</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-navigation-window-11-power-user-guide/"><u>Simplify Navigation: Window 11 Power User Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-system-crash-code-0xc0000001/"><u>Steps to Resolve System Crash: Code 0xC0000001</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-consequences-of-muting-windows-11-notification-tones/"><u>The Consequences of Muting Windows 11 Notification Tones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triumphant-tech-revival-quick-windows-resets-in-3-steps/"><u>Triumphant Tech Revival: Quick Windows Resets in 3 Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharge-ssds-syncing-ssd-fresh-and-windows/"><u>Turbocharge SSDs: Syncing SSD Fresh & Windows</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/unlocking-secrets-your-complete-overview-of-stardew-and-ginger-isle-for-2024/"><u>Unlocking Secrets  Your Complete Overview of Stardew and Ginger Isle for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-the-ultimate-mac-video-editor-adobe-premiere-pro-for-pros-for-2024/"><u>Updated The Ultimate Mac Video Editor Adobe Premiere Pro for Pros for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>