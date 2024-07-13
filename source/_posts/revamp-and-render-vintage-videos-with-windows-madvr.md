---
title: Revamp and Render Vintage Videos with Windows MadVR
date: 2024-07-12T16:49:30.483Z
updated: 2024-07-13T16:49:30.483Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Revamp and Render Vintage Videos with Windows MadVR
excerpt: This Article Describes Revamp and Render Vintage Videos with Windows MadVR
keywords: Vintage Video Enhancer,MadVR Windows Update,Visualize Retro Media,Modernize Old Videos,MadVR Rendering Tool,Vintage Video Transformation,Windows-Based Vid Upgrade
thumbnail: https://thmb.techidaily.com/088a2140549716da6b5748cac96819433a88c8dbf67bc5c9abb78e2279e38684.jpg
---

## Revamp and Render Vintage Videos with Windows MadVR

 You've just purchased a new monitor, perfect for gaming and using apps. But, when you tried to watch your offline media, the quality was a blocky and blurry mess. Shouldn't everything look better on your brand-new monitor?

 Welcome to the world of modern high-res displays, where most of our older video files can only cover one-fourth of the screen... at best. To improve the quality of these older videos, you need to use smart filters and upscalers, and madVR is one of the best for Windows.

## What Is MadVR?

 MadVR is a powerful post-processing filter "enhancer" for many popular media players. It offers a range of sophisticated algorithms to upscale and improves video quality. Unlike apps like the [top video editors for YouTube](https://www.makeuseof.com/free-video-editors-youtube-2022/) that we've already covered, it works in real-time, "improving" your videos as they play.

 With some tweaking, madVR can make lower-resolution videos look better on high-resolution displays, and reduce the effects of compression on highly-compressed files. The more compressed the file, the more striking the improvement.

 MadVR is heavily optimized yet relatively lightweight, so you can use it on older PCs without worrying about resources.

Best of all, it is open-source and free to use.

## How to Add MadVR to MPC-HC

 You can use madVR with many media players. Still, for this tutorial, we'll use the popular Media Player Classic - HomeCinema, better known as "MPC-HC". It's old and has ceased development, but it remains one of the best solutions for playing media when paired with madVR.

1. Start by downloading its latest version from [madVR's official site](https://madvr.com/) . We assume you've downloaded and installed the media player part of the equation from [MPC-HC's official site](https://mpc-hc.org/) .  
![madVR Official Site](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-official-site.jpg)
2. Extract madVR's downloaded archive into any folder of your choice. You can extract it directly in MPC-HC's installation folder, but if you want to use it in more than one player, it's best to extract it in a folder of its own.
3. Launch MPC-HC and choose**View** \>**Options** .  
![MPC HC Options Menu Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mpc-hc-options-menu-entry.jpg)
4. Look for the**External Filters** options page on the list on the left and click on it — it's the fourth entry if viewing the list in fully collapsed view.
5. Click on**Add Filter** at the top right.  
![MPC HC Add Filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mpc-hc-add-filter.jpg)

1. Click on**Browse** at the bottom left of the new**Select Filter** window. Point the requester to the folder where you extracted madVR and select the**madVR.ax** file. Click**OK** to return to the**Select Filter** window. Locate**madVR** among the entries, select it, and click**OK** .  
![MPC HC Select Filter MadVR](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mpc-hc-select-filter-madvr.jpg)
2. Click on the newly-added**madVR** entry on the**External Filters** list. Choose**Prefer** from the options on the right.  
![MPC HC MadVR Prefer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mpc-hc-madvr-prefer.jpg)
3. Expand the**Playback** entry from the list on the left and choose**Output** .
4. Click on the drop-down menu under**DirectShow Video** and select**madVR** .
5. Press**OK** to save the changes. Close and relaunch MPC-HC to ensure it will be using the madVR renderer.

## Tweaking the MadVR Settings

 After adding and enabling madVR in MPC-HC, if you start playing a video file with it, you'll see a new icon for madVR appear in the Windows tray. Right-click on it and choose**Edit madVR Settings** to configure the renderer according to your gear and preferences.

### 1\. Setting Up the Basics With MadVR

 Expand the**devices** group from the list on the left, and choose your display device. Change its**device type** to reflect its type. For most, it will probably be**Digital Monitor / TV** . Do the same for your other display devices if you use more than one.

![MadVR Devices](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-devices.jpg)

 Expand the**processing** group, and choose**deinterlacing** . If you're a fan of anime, disable**only look at pixels in the frame center** .

![MadVR Deinterlacing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-deinterlacing.jpg)

 Move to**artifact removal** , and pause for a second. Now's the time to drag and drop a video, preferably a highly-compressed one, onto MPC-HC's window, and let it play in the background. This way, you'll be able to check how your madVR settings affect how videos look.

 Try enabling the options in this section one by one and, if available, progressively increasing their strength. You can click on**Apply** at any time to check their effect on your video.

![MadVR Artifact Removal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-artifact-removal.jpg)

 When your video starts looking "off", with annoyingly pronounced "edges" around elements, dial your last settings down a notch. If playing a lot of MPEG4/HEVC content (encoded with DivX/XviD/H.264/H.265/NVENC), make sure to try out**reduce compression artifacts** . Setting its quality to**very high** and enabling**process chroma channels, too** come with higher requirements but can also further reduce the annoying "(macro)blocks" on highly-compressed files.

![MadVR Reduce Compression Artifacts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-reduce-compression-artifacts.jpg)

 Do the same for the options in the**image enhancements** section. Since their result depends on both the active video and your perception of what looks best, we'll leave the choice of which you should enable and their values up to you. Remember that you can see their effect in any active video immediately after hitting the**Apply** button on the window.

![MadVR Image Enhancements](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-image-enhancements.jpg)

### 2\. Performing Upscaling With MadVR

 Move to the**scaling algorithms** and start from**chroma upscaling** . All options here take advantage of modern GPUs, so you can choose any you want without wasting resources. For each option, madVR will show you how it affects the video on the top right of its window.

**Positive** results are marked with**green bars** and**negative** ones with**red bars** . The longer the bar, the more noticeable the effect. Also, enable the**SuperRes** filter and increase its strength to 2 or 3 to take advantage of madVR's scaling chops.

![MadVR Chroma Upscaling](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-chroma-upscaling.jpg)

 Modern GPUs are pretty good at downscaling. Thus, you can choose**DXVA2** from the**image downscaling** page to have the task entirely performed by your GPU. However, the other options also "run" on the GPU, either on its texture units or as pixel shaders, and may offer even crisper visuals. It's worth trying them all out to see which you prefer.

![MadVR Image Downscaling](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-image-downscaling.jpg)

 Move to**image upscaling** , and notice how the options here are split into two lists:**Upscaling** and**Doubling** .**Upscaling** lists advanced algorithms that analyze each frame and try to create more visual detail from what already exists.

**Doubling** lists various methods that also "make a video look larger than it is" but with simpler "show-each-pixel-more-than-once" methods (hence "pixel doubling"). This writer's personal preference is**Jinc** , but fans of Anime will also want to try**super-XBR** .

![MadVR Image Upscaling](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-image-upscaling.jpg)

 As before, we won't suggest specific settings for the options on**upscaling refinement** . Enable them one by one, play with their values, and click**Apply** to find what you like. If you see strange artifacts, lines, or elements of your video look "glitchy", change the last option on this page to**Refine the image only once after upscaling is complete** .

![MadVR Upscaling Refinement](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-upscaling-refinement.jpg)

### 3\. Adjusting the Quality With MadVR

 If your videos look jerky in motion, expand the**Rendering** section, and on the**Smooth Motion** page, place a checkmark on**enable smooth motion frame rate conversion** . This may lead to the "soap opera effect," which refers to how TV shows look compared to movies (because of their higher framerate).

![MadVR Smooth Motion](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-smooth-motion.jpg)

 For the highest quality, you can visit the**Trade Quality for Performance** page and disable some or all of the default settings. However, these will make less of a difference compared to the other options.

![MadVR Quality Or Performance](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-quality-or-performance.jpg)

## A Final Note About MadVR

 Keep in mind that not all videos are equal. Your madVR settings will need tweaking depending on the video you're watching. You can use "mild" defaults for general improvement of all videos on your monitor, but madVR is best when you invest a minute in fine-tuning it for each video.

 Still, madVR has its limitations. It can improve how videos look and perform smart upscaling, but it's still a filter, tailored for real-time media reproduction, not a full-blown upscaling app. If you want the best upscaling quality for your videos, you'll have to use a dedicated app and invest some time to do it manually, as we saw on our guide on [how to upscale a video to 4K](https://www.makeuseof.com/how-to-upscale-video-to-4k/) .

 However, if you configure madVR with relatively mild settings, it will essentially be a "set it and forget it" affair. After its initial configuration, it will start enhancing every video you play with MPC-HC. Plus, if you enable it in any other media player, you won't have to reconfigure its settings; it will make your videos look just as good there.

 Still, you may need to make occasional tweaks here and there to make a video look its best. One video might need less sharpening, while another might look better with a higher "reduce compression artifacts" value.

## Getting Optimal Playback With MadVR

 And that's how madVR can go beyond being just a video renderer and become a full-blown hobby. Don't be alarmed if you find yourself trying to upgrade every video and constantly adjusting madVR's settings. You'll be joining a club of many.


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
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-the-ultimate-screen-recorder-test-active-vs-top-contenders/"><u>[New] In 2024, The Ultimate Screen Recorder Test  Active vs Top Contenders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-powershell-errors-with-script-enablement-fixes/"><u>Troubleshooting PowerShell Errors with Script Enablement Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-routines-to-pause-windows-and-office-software-updates/"><u>4 Routines to Pause Windows & Office Software Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-access-to-top-7-highly-rated-cost-free-pc-passwords/"><u>Exclusive Access to Top 7 Highly Rated, Cost-Free PC Passwords</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-best-apps-to-go-live-on-youtube-from-iphone-or-android/"><u>[New] 7 Best Apps to Go Live on YouTube From iPhone or Android</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-still-using-pattern-locks-with-realme-narzo-60x-5g-tips-tricks-and-helpful-advice-by-drfone-android/"><u>In 2024, Still Using Pattern Locks with Realme Narzo 60x 5G? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-caption-kings-and-queens-top-10-mobile-writing-aids-iosandroid/"><u>2024 Approved  Caption Kings and Queens  Top 10 Mobile Writing Aids (iOS/Android)</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-gain-extensive-engagement-master-the-view-multiplier/"><u>2024 Approved  Gain Extensive Engagement  Master the View Multiplier</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-how-to-choose-the-background-music-for-the-trailer/"><u>[New] How to Choose the Background Music for the Trailer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/too-much-glitches-handle-deps-before-virtualbox-on-win/"><u>Too Much Glitches? Handle Deps Before VirtualBox on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-the-gap-quick-fixes-for-slow-windows-app-connections/"><u>Bridge the Gap: Quick Fixes for Slow Windows App Connections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-how-to-disguise-taskbar-on-win-11/"><u>Expert Guide: How to Disguise Taskbar on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-enabledisable-bing-ai-on-windows-11-search-bar/"><u>Turbo Enable/Disable: Bing AI on Windows 11 Search Bar</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-secrets-to-capturing-your-iphone-7-screen/"><u>[New] 2024 Approved  Secrets to Capturing Your iPhone 7 Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/use-external-tools-explore-third-party-software-like-flux-redshift-or-display-temp-to-customize-display-behavior-according-to-time-of-day-and-ambient-light-26/"><u>Use External Tools: Explore Third-Party Software Like f.lux, Redshift, or Display Temp to Customize Display Behavior According to Time of Day and Ambient Light Conditions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-remedy-disconnected-windows-11-printers/"><u>Guide to Remedy Disconnected Windows 11 Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-10s-guide-to-effortlessly-merge-data/"><u>Win 10'S Guide to Effortlessly Merge Data</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-beyond-basic-filters-elevating-your-snapchat-game-for-2024/"><u>[New] Beyond Basic Filters  Elevating Your Snapchat Game for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-the-art-and-science-of-striking-youtube-live-images/"><u>[New] In 2024, The Art and Science of Striking YouTube Live Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncharted-errors-the-8-most-crucial-mistakes-for-new-windows-11-users/"><u>Uncharted Errors: The 8 Most Crucial Mistakes for New Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dims-masterclass-restoring-and-repairing-win11-images/"><u>DIMS Masterclass: Restoring and Repairing Win11 Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-strategies-to-cut-down-system-energy-usage-games/"><u>Efficient Strategies to Cut Down System Energy Usage Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-strategies-to-control-external-hard-drive-usage/"><u>Effective Strategies to Control External Hard Drive Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-window-lock-out-duration-in-windows/"><u>Customize Window Lock-Out Duration in Windows</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-how-to-edit-youtube-videos-in-easy-steps/"><u>New How To Edit Youtube Videos In Easy Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assisting-users-with-erratic-gesture-inputs-in-windows/"><u>Assisting Users with Erratic Gesture Inputs in Windows</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-a-step-by-step-guide-to-embedding-timestamp-metadata/"><u>In 2024, A Step-by-Step Guide to Embedding Timestamp Metadata</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-avoiding-common-pitfalls-in-uploading-hd-videos-to-youtube/"><u>[New] Avoiding Common Pitfalls in Uploading HD Videos to YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-right-video-coding-technique-for-win-os-users/"><u>Deciphering the Right Video Coding Technique for Win OS Users</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-apps-and-online-tools-to-track-vivo-y17s-phone-withwithout-imei-number-by-drfone-android/"><u>Top Apps and Online Tools To Track Vivo Y17s Phone With/Without IMEI Number</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-excellent-10-drone-set-professional-filming-and-photography/"><u>[Updated] Excellent 10-Drone Set  Professional Filming & Photography</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-troubleshooting-winning-against-camera-app-failures/"><u>Effortless Troubleshooting: Winning Against Camera App Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-download-and-install-msixbundle-and-appxappxbundle-files-from-the-microsoft-store/"><u>How to Download and Install Msixbundle and Appx/Appxbundle Files From the Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-windows-11-login-issues-without-screen-display/"><u>Clear Windows 11 Login Issues Without Screen Display</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-step-by-step-the-top-10-video-players-for-frame-by-frame-analysis/"><u>New 2024 Approved Step-by-Step The Top 10 Video Players for Frame-by-Frame Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-steps-to-disable-automatic-updates-in-windows/"><u>5 Steps To Disable Automatic Updates in Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/perfect-panning-crossfading-in-logic-pro-x/"><u>Perfect Panning  Crossfading in Logic Pro X</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-realme-gt-neo-5-se-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-premier-list-of-smartphone-compatible-vr-headset/"><u>[New] The Premier List of Smartphone-Compatible VR Headset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-the-windows-print-management-tool-and-how-do-you-access-it/"><u>What Is the Windows Print Management Tool, and How Do You Access It?</u></a></li>
<li><a href="https://extra-tips.techidaily.com/forge-funnies-giphys-playground/"><u>Forge Funnies  Giphy's Playground</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719307808288-tackling-windows-glitches-find-solutions-now/"><u>Tackling Windows Glitches: Find Solutions Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win10-isolating-and-fixing-unilateral-audio-malfunction/"><u>Win10: Isolating and Fixing Unilateral Audio Malfunction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-the-no-image-preview-error-in-your-windows-11-environment/"><u>Fix the No Image Preview Error in Your Windows 11 Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-users-through-terminal-restart-on-win11/"><u>Guiding Users Through Terminal Restart on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-christmas-ify-your-windows-11/"><u>7 Ways to Christmas-Ify Your Windows 11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-how-to-block-facebook-video-ads/"><u>[New] How to Block Facebook Video Ads?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/whats-behind-windows-11s-disappearing-thumbnail-issue-fixes-here/"><u>What's Behind Windows 11'S Disappearing Thumbnail Issue? Fixes Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/iosandroid-sync-with-windows-server-files/"><u>IOS/Android: Sync with Windows Server Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-update-error-code-0x8024800c/"><u>Fixing Windows Update Error Code 0X8024800C</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-combo-guide-zooming-into-facebook-streaming-for-2024/"><u>The Ultimate Combo Guide  Zooming Into Facebook Streaming for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/smooth-snapshot-mastery-eliminate-shakes/"><u>Smooth Snapshot Mastery - Eliminate Shakes</u></a></li>
</ul></div>
