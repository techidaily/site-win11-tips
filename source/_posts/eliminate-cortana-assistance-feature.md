---
title: Eliminate Cortana Assistance Feature
date: 2024-08-16T01:45:28.922Z
updated: 2024-08-17T01:45:28.922Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminate Cortana Assistance Feature
excerpt: This Article Describes Eliminate Cortana Assistance Feature
keywords: Cortana Off Switch,Disable Cortana,Remove Cortana Assist,No Cortana Help,Deactivate Cortana,Stop Cortana Support,Turn Off Cortana Aid
thumbnail: https://thmb.techidaily.com/69b1d610dfac71b4ad43b5c58d93dcc4f9582f39ed2f8ffdd69954aaaa5a12ae.jpg
---

## Eliminate Cortana Assistance Feature

 Windows Copilot, Microsoft's new AI assistant, can assist you with a variety of tasks, such as answering questions, changing system settings, and creating AI images. However, if you're not a fan of Copilot or simply don't need it, you can remove its taskbar icon or disable it entirely on your Windows 11 PC. Here, we'll show you how.

## How to Remove the Copilot Icon From the Windows 11 Taskbar

 By default, the Copilot icon appears in the Windows 11 taskbar. However, if you prefer not to have it there but still want to use it occasionally, it's easy to hide the Copilot icon. Simply right-click anywhere on an empty spot on your taskbar and select **Taskbar settings**. In the Settings window that appears, turn off the toggle next to **Copilot**.

![Remove Copilot Icon From Windows 11 Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-copilot-icon-from-windows-11-taskbar.jpg)

 This should remove the Copilot icon from the taskbar. You can still access Copilot by pressing the **Win + C** keyboard shortcut in Windows 11\.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Completely Disable Copilot via Group Policy Settings

 Although hiding the Copilot is quite easy, it does not turn it off completely, and you might inadvertently access it. Fortunately, you can turn off Copilot completely via the Local Group Policy Editor on PCs running the Professional, Education, or Enterprise edition of Windows 11\.

 If you are using Windows 11 Home, skip to the Registry Editor method below or use a [workaround to enable the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **User Configuration > Administrative Templates > Windows Components > Windows Copilot**.
5. Double-click the **Turn off Windows Copilot** policy on your right.
6. Select the **Enabled** option.
7. Hit **Apply** followed by **OK**.  
![Turn Off Windows Copilot Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you complete the above steps, Copilot will be disabled on your Windows 11 PC and you won't be able to access it even with the keyboard shortcut. If you want to re-enable Copilot later, repeat the above steps and set the **Turn off Windows Copilot** policy to **Not configured** or **Disabled**.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Completely Disable Copilot by Modifying Registry Files

 Another way to disable Copilot on Windows 11 involves modifying registry files. However, since editing the registry can be risky, you should follow the steps carefully. Also, be sure to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). This will allow you to restore the registry files in case something goes wrong.

 Once you’ve done that, here’s what you need to do to disable Copilot via the Registry Editor:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter** to open the Registry Editor.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > Software > Policies > Microsoft > Windows**.
5. Right-click the **Windows** key and select **New > Key**. Name it **WindowsCopilot**.
6. Right-click on the **WindowsCopilot** DWORD, go to **New**, and select **DWORD (32-bit) Value** from the submenu. Name the DWORD **TurnOffWindowsCopilot**.
7. Double-click the **TurnOffWindowsCopilot** DWORD, type **1** in the text field, and click **OK**.
8. Restart your PC for the changes to take effect.  
![Turn Off Windows Copilot Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 And that’s about it. Windows Copilot will be disabled on your PC. To re-enable it in the future, repeat the above steps and set the **TurnOffWindowsCopilot** DWORD value to 0\. You can also delete the **TurnOffWindowsCopilot** DWORD instead.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
## Get Rid of Copilot on Windows 11

 While Windows Copilot is a powerful tool, not everyone may want to use it. Fortunately, it’s possible to get rid of it. The above steps will help you achieve your goal, whether you want to keep Copilot out of sight or turn it off entirely.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-simplifying-cross-platform-sharing-instagram-and-facebook-integration/"><u>[New] 2024 Approved  Simplifying Cross-Platform Sharing  Instagram & Facebook Integration</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-explore-our-12-tycoon-classics-for-engrossing-experiences/"><u>[New] Explore Our #12 Tycoon Classics for Engrossing Experiences</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-sharex-review-and-best-alternatives/"><u>[Updated] 2024 Approved  ShareX Review and Best Alternatives</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-the-social-media-savants-guide-to-stellar-instagram-posts/"><u>[Updated] 2024 Approved  The Social Media Savant's Guide to Stellar Instagram Posts</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-best-ios-tools-for-psp-gaming-top-5/"><u>[Updated] Best iOS Tools for PSP Gaming, Top 5</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-compact-powerful-windows-11-camcorders-a-must-try-list-for-2024/"><u>[Updated] Compact, Powerful Windows 11 Camcorders - A Must-Try List for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-freesoundvault-review-unleashing-the-power-of-2024-tech/"><u>[Updated] FreeSoundVault Review  Unleashing the Power of 2024 Tech</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-tweeted-cinematics-from-video-to-wavmp3/"><u>[Updated] In 2024, Tweeted Cinematics  From Video to WAV/MP3</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-smile-station-quick-tips-for-chuckling-creations/"><u>[Updated] Smile Station  Quick Tips for Chuckling Creations</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-the-ultimate-encyclopedia-reacting-effectively-on-youtube-vids-for-2024/"><u>[Updated] The Ultimate Encyclopedia  Reacting Effectively on YouTube Vids for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-vmix-fusion-crossplatform-for-2024/"><u>[Updated] VMix Fusion CrossPlatform for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-efficiently-broadcasting-your-videos-as-shorts-via-computers-and-mobile/"><u>2024 Approved  Efficiently Broadcasting Your Videos as Shorts via Computers & Mobile</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-unlocking-the-secret-to-a-streamlined-tiktok-bio-with-linktree/"><u>2024 Approved  Unlocking the Secret to a Streamlined TikTok Bio with Linktree</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-current-frames-crafting-future-windows/"><u>Beyond Current Frames: Crafting Future Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-yuzu-game-performance-in-windows/"><u>Boosting Yuzu Game Performance in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-winrars-summation-missteps-with-6-fixes/"><u>Combatting WinRAR's Summation Missteps with 6 Fixes</u></a></li>
<li><a href="https://os-tips.techidaily.com/complete-guide-unfreezing-your-ipod-or-ipod-touch-a-step-by-step-visual-tutorial/"><u>Complete Guide: Unfreezing Your iPod or iPod Touch - A Step-by-Step Visual Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cut-down-installation-time-with-proper-deps-setup/"><u>Cut Down Installation Time with Proper Deps Setup</u></a></li>
<li><a href="https://win-dash.techidaily.com/enhance-your-dell-2330ddn-printing-with-updated-mono-laser-printer-drivers/"><u>Enhance Your Dell 2330D/DN Printing with Updated Mono Laser Printer Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-insights-into-windowsstore-accessibility-guide/"><u>Essential Insights Into WindowsStore Accessibility Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-motorola-edge-40-neo-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Motorola Edge 40 Neo Phone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-fixing-microsoft-store-error-0x80073cf3-in-win11/"><u>Guidelines for Fixing Microsoft Store Error 0X80073CF3 in Win11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-google-pixel-7a-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Google Pixel 7a? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-factory-unlock-your-telstra-iphone-7-by-drfone-ios/"><u>How To Factory Unlock Your Telstra iPhone 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-microsoft-store-error-code-0x80073cf3-in-windows-10-and-11/"><u>How to Fix the Microsoft Store Error Code 0X80073CF3 in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stick-notes-to-app-windows-in-windows-1110/"><u>How to Stick Notes to App Windows in Windows 11/10</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-chucklechief-easy-meme-design-tool/"><u>In 2024, ChuckleChief  Easy Meme Design Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-process-of-modifying-user-identities-on-windows-11/"><u>Master the Process of Modifying User Identities on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-desktop-layout-app-sizes-in-windows-11/"><u>Mastering Desktop Layout: App Sizes in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-remedy-for-windows-network-error-0x800704b3/"><u>Mastering Remedy for Windows' Network Error 0X800704B3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-gmaps-integration-process-in-windows/"><u>Navigating the GMaps Integration Process in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-windows-11-calendar-space/"><u>Navigating the Windows 11 Calendar Space</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-top-10plus-best-free-online-video-editors-for-video-editing-online/"><u>New 2024 Approved Top 10+ Best Free Online Video Editors for Video Editing Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-disabled-copy-operation-on-windows-11/"><u>Overcoming Disabled Copy Operation on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-disabled-memory-feature-on-new-windows-11/"><u>Overcoming Disabled Memory Feature on New Windows 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/pattern-locks-are-unsafe-secure-your-oppo-reno-9a-phone-now-with-these-tips-by-drfone-android/"><u>Pattern Locks Are Unsafe Secure Your Oppo Reno 9A Phone Now with These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-windows-icon-arrangement-easily/"><u>Refreshing Windows Icon Arrangement Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-google-chrome-windows-files-not-syncing-problem/"><u>Resolve Google Chrome: Windows Files Not Syncing Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-a-successful-launch-path-for-csgo-on-windows-11/"><u>Securing a Successful Launch Path for CS:GO on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-windows-key-activationdeactivation-process/"><u>Simplifying Windows Key Activation/Deactivation Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-exquisite-photography-building-inspiring-slideshows-and-fixing-spots-in-win11/"><u>Step-by-Step Guide to Exquisite Photography: Building Inspiring Slideshows & Fixing Spots in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-how-to-turn-off-defender-firewall/"><u>Step-by-Step: How to Turn Off Defender Firewall</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-vids-with-these-8-windows-titles/"><u>Streamline Your Vids with These 8 Windows Titles</u></a></li>
<li><a href="https://howto.techidaily.com/stuck-at-android-system-recovery-of-poco-m6-5g-fix-it-easily-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Stuck at Android System Recovery Of Poco M6 5G ? Fix It Easily | Dr.fone</u></a></li>
<li><a href="https://fox-that.techidaily.com/surprisingly-your-vanished-iphone-images-may-still-live-in-the-cloud-discover-how/"><u>Surprisingly, Your Vanished iPhone Images May Still Live in the Cloud! Discover How</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-technical-exploration-of-high-dynamic-range-on-windows-11-platforms/"><u>The Technical Exploration of High Dynamic Range on Windows 11 Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-overcome-ownership-challenges-with-org-managed-configurations-in-windows-11/"><u>Tips to Overcome Ownership Challenges with Org-Managed Configurations in Windows 11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/top-tech-tool-extract-facebook-videos-as-mp4/"><u>Top Tech Tool  Extract Facebook Videos as MP4</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-language-potential-with-windows-1011-hotkey-techniques/"><u>Unleash Language Potential with Windows 10/11 Hotkey Techniques</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlock-hidden-capabilities-the-5-best-kept-secrets-of-chatgpt-revealed/"><u>Unlock Hidden Capabilities: The 5 Best Kept Secrets of ChatGPT Revealed!</u></a></li>
<li><a href="https://ai-topics.techidaily.com/updated-in-2024-top-6-celebrity-text-to-speech-ai-voice-generators-you-may-like/"><u>Updated In 2024, Top 6 Celebrity Text to Speech AI Voice Generators You May Like</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-and-11-pro-mastery-a-guide-to-successfully-uninstall-and-reinstall-extras/"><u>Windows 11 & 11 Pro Mastery: A Guide to Successfully Uninstall and Reinstall Extras</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-screener-a-step-by-step-customization-guide/"><u>Windows 11 Screener: A Step-by-Step Customization Guide</u></a></li>
</ul></div>
