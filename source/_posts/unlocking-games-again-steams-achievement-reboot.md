---
title: "Unlocking Games Again: Steam's Achievement Reboot"
date: 2024-08-16T01:40:08.905Z
updated: 2024-08-17T01:40:08.905Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking Games Again: Steam's Achievement Reboot"
excerpt: "This Article Describes Unlocking Games Again: Steam's Achievement Reboot"
keywords: Game Unlock Guide,Steam Achievements Revamp,Rebooted Gaming Titles,Steam Backlog Access,Streaming Game Success,Achievement Reset Benefits,Games Re-Release Strategy
thumbnail: https://thmb.techidaily.com/f7e33e46d8576e8a405f890f9187eb22b423a0b9361503ab0ea4cb809046ec66.jpg
---

## Unlocking Games Again: Steam's Achievement Reboot

 Unlocking achievements is fun. Locking them again isn't so fun, especially if the developer hasn't offered the player an option to do so in the first place.

 Thankfully, Steam has a catch-all solution to resetting achievements for individual games.

## Resetting Steam Achievements
![screenshot of a steam achievement list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_steam_achievements_list.jpg)

 There's no simple switch for resetting Steam achievements. Some games offer the option to reset player progress, and this may include Steam achievements as well.

 You'll want to make sure this simpler, in-game method isn't available first.

 To reset your progress for Steam achievements, we'll need to use something called the Steam Client Console.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
## Enable Steam Client Console

 The easiest way to open the Steam Client Console is by hitting **Win + R** to open the Windows Run Command Dialog.

 If you can't use this method to open the Run window, have a look at our guide on [ways to open the Run Command Dialog](https://www.makeuseof.com/windows-open-run-command-dialog-box/).

 With the Run window open, input the following command.

`steam://open/console`

 This will open Steam with a new tab available from the main window. The **Console** tab.

![screenshot of the steam client console](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_steam_client_console_overview-1.jpg)
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This is where we'll input our commands to reset achievements.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
## Achievements and Stat Commands
![screenshot of achievement clear in steam client console](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_achievement_clear_in_steam_client_console.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->

 The command we'll need to use is **achievement\_clear**. On its own, it doesn't do anything. We need a couple of things first.

 Head over to [**SteamDB**, or the Steam Database](https://steamdb.info/apps/), and search for the game associated with the achievement you're resetting.

![screenshot of half life 2 in steam database](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_hl2_in_steam_db.jpg)
<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Copy the **AppID** listed against your game. Note this down or paste it somewhere you'll remember. Scroll down the page and click on the **Achievements** tab.

![screenshot of half life 2 achievements in steam database](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_hl2_achievements_in_steam_db.jpg)
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This will list all the achievements and their **API Names**. Pick out the achievement you want to reset and note that name.

 Now you have your command. Input the information you've gathered like so.

`achievement_clear <AppID> <Achievement API Name>`

 Using the example in our screenshots, the code should look something like this. Remember to use the achievement name from SteamDB, and not simply the in-game name of the achievement.

![screenshot of the steam client console with an input command filled out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_resetting_achievement_steam_client_console_filled_out.jpg)

 You'll know it worked if you see the message **achievement\_clear success**.

 There is a second command that accompanies the above. Inputting **reset\_all\_stats** followed by an AppID will reset any stats Steam tracks for that game. For example, kills or time played. Be careful with this command, as it can behave differently depending on how any given game tracks those stats. For example, it might not function at all, or it may mess up crucial game statistics.

## Reset Steam Achievements With Steam Achievement Manager
![screenshot of the steam achievement manager main page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/screenshot_of_steam_achievement_manager_main_page.jpg)

 The above method is as close to an 'official' method as you can get. If you're after something a little easier, but also a little less 'legitimate,' consider the Steam Achievement Manager.

[Learning how to use the Steam Achievement Manager](https://www.makeuseof.com/how-to-use-steam-achievement-manager/) makes this process much easier, with a GUI to ensure you're resetting the right achievements. However, this method falls into a gray area of Steam's terms of service. It's easier, but it's not guaranteed to be a completely safe method.

## A Complicated Process

 Ideally, there would be an easier way to reset achievements for any Steam game, as you never know when you'll want to replay a game from the ground up.

 At least we have the option with the Steam Client Console.

 Thankfully, Steam has a catch-all solution to resetting achievements for individual games.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-advanced-techniques-for-effective-mobile-screen-capturing-with-mobizen/"><u>[New] 2024 Approved  Advanced Techniques for Effective Mobile Screen Capturing with Mobizen</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-overcoming-full-screen-issues-in-obs/"><u>[New] 2024 Approved  Overcoming Full Screen Issues in Obs</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/onverting-live-streamed-youtubes-into-animated-gif-formats-for-2024/"><u>[New] Converting Live Streamed YouTubes Into Animated GIF Formats for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-bring-your-creative-windows-video-projects-online-via-vimeo/"><u>[New] In 2024, Bring Your Creative Windows Video Projects Online via Vimeo</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-2024-approved-the-most-trending-twitch-originals-from-amazon-prime/"><u>[Updated] 2024 Approved  The Most Trending Twitch Originals From Amazon Prime</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-visual-impact-blueprint-for-success-in-instagram-video-campaigns/"><u>[Updated] 2024 Approved  Visual Impact  Blueprint for Success in Instagram Video Campaigns</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-best-unplugged-android-gaming-apps-no-internet-required/"><u>[Updated] In 2024, Best Unplugged Android Gaming Apps (No Internet Required)</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-unlock-crystal-clear-facebook-video-on-android/"><u>[Updated] Unlock Crystal-Clear Facebook Video on Android</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-abbreviated-film-dialogue-scheme/"><u>2024 Approved  Abbreviated Film Dialogue Scheme</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-unwind-with-these-top-15-anime-web-vids/"><u>2024 Approved  Unwind with These Top 15 Anime Web Vids</u></a></li>
<li><a href="https://screen-recording.techidaily.com/advanced-tips-for-integrating-markers-in-videography-for-2024/"><u>Advanced Tips for Integrating Markers in Videography for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/basic-procedure-swapping-video-playback-in-vlc-media-player/"><u>Basic Procedure  Swapping Video Playback in VLC Media Player</u></a></li>
<li><a href="https://extra-tips.techidaily.com/blend-soundscape-into-ppt-narratives/"><u>Blend Soundscape Into PPT Narratives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-virtual-machine-security-with-vboxs-secure-boot-toggle/"><u>Boost Virtual Machine Security with VBox's Secure Boot Toggle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boot-into-peace-five-tactics-to-overcome-windows-security-failures/"><u>Boot Into Peace: Five Tactics to Overcome Windows Security Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-windows-11-blackout-with-easy-tips-and-tricks/"><u>Bypass Windows 11 Blackout with Easy Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-privilege-needed-blue-screen-windows-fix-guide/"><u>Bypassing 'Privilege Needed' Blue Screen: Windows Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719381834367-cep-library-integration/"><u>CEP Library Integration:</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-your-windows-11-experience-with-nircmd-tips/"><u>Command Your Windows 11 Experience with NirCmd Tips</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/cutting-edge-tips-for-outshining-others-in-facebooks-social-space-for-2024/"><u>Cutting-Edge Tips for Outshining Others in Facebook's Social Space for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-not-empty-assertion-a-practical-guide-to-x80070091-fixes/"><u>Disabling 'Not Empty' Assertion: A Practical Guide to X80070091 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-rectify-cant-add-your-folder-now-in-onedrive/"><u>Essential Steps to Rectify 'Can't Add Your Folder Now' In OneDrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719218779653-expert-tips-reinstating-functionality-of-wwinplusp-in-os/"><u>Expert Tips: Reinstating Functionality of WWin+P in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-disparities-in-cloud-and-offline-windows-updates/"><u>Exploring Disparities in Cloud and Offline Windows Updates</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-tecno-camon-20-pro-5g-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/from-beginner-to-expert-video-editing-with-windows-movie-maker-for-2024/"><u>From Beginner to Expert Video Editing with Windows Movie Maker for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-can-we-bypass-google-pixel-8-frp-by-drfone-android/"><u>How Can We Bypass Google Pixel 8 FRP?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-keygen-malware-on-windows-recognition-and-eradication-steps/"><u>Identifying Keygen Malware on Windows: Recognition and Eradication Steps</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-direct-upload-from-twitter-to-tumblr/"><u>In 2024, Direct Upload From Twitter to Tumblr</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-find-my-friends-work-on-apple-iphone-15-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, Does find my friends work on Apple iPhone 15 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-asus-rog-phone-8mirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Asus ROG Phone 8Mirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-without-jailbreak-on-poco-c55-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location without Jailbreak On Poco C55 | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-fix-auto-lock-greyed-out-on-iphone-7-plus-drfone-by-drfone-ios/"><u>In 2024, How To Fix Auto Lock Greyed Out on iPhone 7 Plus | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-honor-x50-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Honor X50 to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-poco-f5-pro-5g-phone-by-drfone-android/"><u>In 2024, How to Use Google Assistant on Your Lock Screen Of Poco F5 Pro 5G Phone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-innovative-vertical-video-editing-for-instagrams-igtv/"><u>In 2024, Innovative Vertical Video Editing for Instagram's IGTV</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-no-frills-screensaver-windows-compatible/"><u>In 2024, No Frills Screensaver - Windows Compatible</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-nostalgia-frame-portraits-on-the-x-phone/"><u>In 2024, Nostalgia Frame  Portraits on the X Phone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Oppo Reno 9A | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-ultimate-scriptsmiths-network/"><u>In 2024, Ultimate Scriptsmiths Network</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unlocking-potential-with-polarrs-advanced-editing-features/"><u>In 2024, Unlocking Potential with Polarr's Advanced Editing Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrate-compatibility-troubleshoot-in-windows-clippy/"><u>Integrate Compatibility Troubleshoot in Windows Clippy</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-zte-blade-a73-5gfrp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your ZTE Blade A73 5GFRP Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-pc-storage-identifying-excess-disk-usage-in-windows/"><u>Maximizing PC Storage: Identifying Excess Disk Usage in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-prevent-windowed-app-relocations/"><u>Methods to Prevent Windowed App Relocations</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigating-the-process-a-detailed-walkthrough-of-sharing-your-steam-redeemable-codes/"><u>Navigating the Process: A Detailed Walkthrough of Sharing Your Steam Redeemable Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/organize-windows-icons-harmoniously/"><u>Organize Windows Icons Harmoniously</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-nvidia-connect-error-in-windows-oses/"><u>Overcoming NVIDIA Connect Error in Windows OSes</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/overcoming-phone-connection-challenges-on-the-samsung-galaxy-watch-effective-fixes-and-tips/"><u>Overcoming Phone Connection Challenges on the Samsung Galaxy Watch – Effective Fixes and Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-win11s-security-measures-through-rufus-mastery/"><u>Overcoming Win11's Security Measures Through Rufus Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-unreachable-network-paths/"><u>Overcoming Windows' Unreachable Network Paths</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/pro-streaming-setup-leading-livestream-hardware-and-software/"><u>Pro Streaming Setup  Leading Livestream Hardware and Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-absent-system-cooling-policy-in-pcs/"><u>Reinstating Absent System Cooling Policy in PCs</u></a></li>
<li><a href="https://win-blog.techidaily.com/say-goodbye-to-lag-in-fortnite-effective-strategies-for-optimal-performance/"><u>Say Goodbye to Lag in Fortnite: Effective Strategies for Optimal Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/say-goodbye-to-old-files-enabling-the-autodelete-option-on-windows-11/"><u>Say Goodbye to Old Files: Enabling the Autodelete Option on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-wirelessly-link-dualshock-3-and-win/"><u>Seamless Integration: Wirelessly Link DualShock 3 & Win</u></a></li>
<li><a href="https://driver-install.techidaily.com/set-up-printer-driver-canon-inkjet-series-for-windows/"><u>Set up Printer Driver: Canon Inkjet Series for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stay-connected-disable-usb-sleep-on-windows-11-pc/"><u>Stay Connected: Disable USB Sleep on Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-error-0x00000709/"><u>Steps to Rectify Error 0X00000709</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-revitalize-stuck-and-slow-downloads-in-windows-directory/"><u>Steps to Revitalize Stuck and Slow Downloads in Windows Directory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-unlocking-screen-pin-free-windows-projection/"><u>Stop Unlocking Screen: PIN-Free Windows Projection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-address-unsuccessful-onedrive-procedures/"><u>Strategies to Address Unsuccessful OneDrive Procedures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-lcd-panels-simplified-guide/"><u>Switching LCD Panels Simplified Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-free-gaming-setup-dualshock-for-windows-users/"><u>Tech-Free Gaming Setup: DualShock for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-5-best-torrent-clients-for-windows/"><u>The 5 Best Torrent Clients for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/thriving-without-11-upgrade-boost-your-pc-health/"><u>Thriving Without 11 Upgrade: Boost Your PC Health</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-dark-displays-during-win-games/"><u>Troubleshooting Dark Displays During Win Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turning-spoken-words-into-written-phrases-a-guide-for-windows-users/"><u>Turning Spoken Words Into Written Phrases: A Guide for Windows Users</u></a></li>
<li><a href="https://extra-information.techidaily.com/unleash-your-potential-with-filmoras-loved-9-traits/"><u>Unleash Your Potential with Filmora's Loved 9 Traits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-full-potential-of-the-windows-key/"><u>Unlocking Full Potential of the Windows Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-content-restricted-in-windows-steam/"><u>Unraveling Content Restricted in Windows Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-activate-educational-themes/"><u>Win 11: Activate Educational Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-troubleshooting-for-elusive-temp-files/"><u>Windows Troubleshooting for Elusive Temp Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-customization-increasing-icon-dimensions-in-w11/"><u>Winning at Customization: Increasing Icon Dimensions in W11</u></a></li>
</ul></div>
