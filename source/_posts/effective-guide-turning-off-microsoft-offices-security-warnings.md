---
title: "Effective Guide: Turning Off Microsoft Office's Security Warnings"
date: 2024-08-28T01:07:23.958Z
updated: 2024-08-29T01:07:23.958Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/10021b17375d6e35424f943b31fb1f59b98c4b332e933017960911271c0d2245.jpg
---

## Effective Guide: Turning Off Microsoft Office's Security Warnings

Macros in Microsoft Office programs allow you to automate repetitive tasks, but some macros can be dangerous. Macros are bits of computer code and they’re [infamous for containing malware](https://extra-information.techidaily.com/where-to-download-your-own-personalized-tyrion-lannister-ringtone/) that will infect your computer if you run them. Microsoft Office protects you from files containing macros by default.

 When you open a Word, Excel, or PowerPoint file containing macros (.docm, .xlsm, or .pptm, respectively), a Security Warning message displays below the ribbon in the program telling you that macros have been disabled. If, and only if, you know the document came from a trusted source, you can click the “Enable Content” button on the Security Warning message to enable the macros in that document.

Related: [How to Show the Developer Tab on the Ribbon in Office Programs](https://extra-approaches.techidaily.com/2024-approved-reinstate-your-airdrop-linkages-simple-fixes-for-iosmacos-issues/) 

 If you know what you're doing, and you don’t want to see that message every time you open an Office document, you can disable it. We’ll show you how to disable the message without compromising the security of your Office programs. However, this doesn’t mean you can’t ever use macros in your Office documents again. If you deal with some Office files that have macros from trusted sources, you can set up a trusted location in which you can place those trusted files for each Microsoft Office program. Office files placed in a trusted location are ignored when you open them from that location, and macros are not disabled. We’ll also show you how to set up a trusted location for important files received from trusted sources.

 First, we’ll disable the Security Warning message bar. To do that, you’ll need to [enable the Developer tab](https://some-guidance.techidaily.com/the-ultimate-beginners-guide-to-mastering-final-cut-pro-for-2024/), then click on it.

![01_clicking_developer_tab](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/01_clicking_developer_tab.png) 

 In the “Code” section, click “Macro Security”.

![02_clicking_macro_security](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/02_clicking_macro_security.png) 

 The Trust Center dialog box displays with the Macro Settings screen active. The “Disable all macros with notification” option is selected by default. You can disable the Security Warning by selecting “Disable all macros without notification”.

 If you want to allow digitally signed macros to run, select the “Disable all macros except digitally signed macros” option. This only allows macros digitally signed by a publisher you’ve trusted to run. If you have not trusted the publisher, you are notified. All unsigned macros are automatically disabled without notification.

![03_changing_macro_settings](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/03_changing_macro_settings.png) 

 Microsoft explains what "digitally signed" means [here](https://support.microsoft.com/en-us/kb/820738):

> Excel uses digital signatures on the workbook contents to help ensure that the workbook has not been modified and saved since it was signed. Digital signatures can also help you distinguish workbooks and macros created by a reliable source from undesirable and potentially damaging workbooks or macro code (viruses).
> 
> A digital signature is a public certificate plus the value of the signed data as encrypted by a private key. The value is a number that a cryptographic algorithm generates for any data that you want to sign. This algorithm makes it nearly impossible to change the data without changing the resulting value. So, by encrypting the value instead of the data, a digital signature helps a user to verify the data was not changed.

 We do NOT recommend selecting the last option, "Enable all macros", as that will leave your computer unprotected from potential malware in macros from unknown sources.

 Changing these macro settings in the Trust Center only affects the Office program you are currently using. To change these settings in Excel or PowerPoint, you must open those programs and change the settings there as well. The macro settings are accessed the same way in Excel and PowerPoint as they are in Word.

 There is also another way to disable the Security Warning message that will disable the message in all Office programs and overrides the macro settings regarding notifications. Click “Message Bar” in the list of items on the left side of the Trust Center dialog box.

![04_clicking_message_bar](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/04_clicking_message_bar.png) 

 In the “Message Bar Settings for all Office Applications” section, select the “Never show information about blocked content” option. The Security Warning will not display in any of the Office programs now, even if the “Disable all macros with notification” option is selected on the Macro Settings screen.

![05_selecting_never_show_info_about_blocked_content](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/05_selecting_never_show_info_about_blocked_content.png) 

 You might work with documents containing macros that you receive from trusted sources, such as documents in which your co-workers or boss created some macros to make it easier to create and maintain the documents. For those types of documents, you can choose a folder on your computer to be a trusted location where you can store and access these documents. Any Office documents opened from within that folder are ignored when the Office program checks for macros. To set up a trusted location to store and access documents from trusted sources, click “Trusted Locations” in the list on the left.

![06_clicking_trusted_locations](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/06_clicking_trusted_locations.png) 

 Microsoft automatically adds some folders as trusted locations that the current program uses when running. You can add your own folders to that list.

![07_default_trusted_locations](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/07_default_trusted_locations.png) 

 Click “Add new location” towards the bottom of the Trust Center dialog box.

![08_clicking_add_new_location](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/08_clicking_add_new_location.png) 

 The Microsoft Office Trusted Location dialog box displays. The default location currently selected in the User Locations list is automatically entered into the Path edit box. To change this location, either type a new full path in the edit box or click “Browse”. Browsing for the location is easier, so we’ll do that.

![09_clicking_browse](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/09_clicking_browse.png) 

 Navigate to the folder in which you want to store your trusted documents for access and click “OK”.

![10_selecting_trusted_folder](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/10_selecting_trusted_folder.png) 

 The selected full path is added to the Path edit box. If you want to include any subfolders within the selected folder as trusted locations, select the “Subfolders of this location are also trusted” check box so there is a check mark in the box.

Related: [Your Passwords Are Terrible, and It's Time to Do Something About It](https://fox-http.techidaily.com/step-by-step-guide-to-mastering-slug-line-crafting-for-2024/) 

 NOTE: We do NOT recommend using a network drive as a trusted location because other people who have access to the same network could have tampered with the file. You should only make folders on your local hard drive trusted locations, and you should protect your Windows account with a [strong password](https://fox-http.techidaily.com/step-by-step-guide-to-mastering-slug-line-crafting-for-2024/).

 Enter a description for this folder in the "Description" box, so you know the purpose of this folder when you see it in the list on the Trusted Locations screen. Then, click “OK”.

![11_clicking_ok_on_trusted_location_dialog](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/11_clicking_ok_on_trusted_location_dialog.png) 

 The path, description, and data modified for the new trusted location is added to the list.

![12_new_location_added_to_user_locations_list](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/12_new_location_added_to_user_locations_list.png) 

 Details about the selected trusted location are also listed at the bottom of the Trusted Locations screen, including whether or not Sub Folders are allowed.

 If you selected a folder on a network as your trusted location (again, we do NOT recommend this), select the “Allow Trusted Locations on my network (not recommended)” check box.

 You can Modify trusted locations in the list or Remove them by selecting the location in the list and clicking the appropriate button to the right of the Add new location button. Once you’ve finished setting up your trusted location, click “OK” on the Trust Center dialog box to accept your changes and close it.

![13_clicking_ok](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/13_clicking_ok.png) 

 Now your Microsoft Office programs will remain protected from malware in the form of macros, but you can still run macros in trusted documents. And you don’t have to see the Security Warning message every time.

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
<li><a href="https://youtube-zero.techidaily.com/024-approved-crafting-perfect-thumbnails-for-higher-clickthrough-rates/"><u>[New] 2024 Approved  Crafting Perfect Thumbnails for Higher Clickthrough Rates</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-2024-approved-setting-the-scene-a-complete-guide-to-adding-custom-sounds-and-ringtones-on-android/"><u>[New] 2024 Approved  Setting the Scene  A Complete Guide to Adding Custom Sounds and Ringtones on Android</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-fast-forward-altering-instagram-stories-tempo/"><u>[New] Fast-Forward  Altering Instagram Stories' Tempo</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-from-feedback-to-fanbase-the-video-journey/"><u>[New] From Feedback to Fanbase  The Video Journey</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-acquiring-free-music-youtube-video-edition/"><u>[New] In 2024, Acquiring Free Music  YouTube Video Edition</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-how-to-clone-yourself-on-tiktok/"><u>[New] In 2024, How to Clone Yourself on TikTok</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-x-mix-master-pro-for-computer-users/"><u>[New] In 2024, X-Mix Master Pro for Computer Users</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-twitter-livestreaming-a-comprehensive-guide-for-2024/"><u>[New] Twitter Livestreaming  A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-immediate-capture-in-zoom-conferences-via-snap/"><u>[Updated] 2024 Approved  Immediate Capture in Zoom Conferences via Snap</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-navigating-the-world-of-zooms-camera-snapping-easily/"><u>[Updated] 2024 Approved  Navigating the World of Zoom's Camera Snapping Easily</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-best-auto-tracking-camera-mount/"><u>[Updated] Best Auto Tracking Camera Mount</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-boost-your-tiktok-presence-advanced-mac-video-techniques-for-2024/"><u>[Updated] Boost Your TikTok Presence  Advanced Mac Video Techniques for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-easy-access-best-free-youtube-subtitle-extractors/"><u>[Updated] In 2024, Easy Access  Best Free YouTube Subtitle Extractors</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-mastering-twitter-videos-adhere-to-aspect-ratio-rules-for-2024/"><u>[Updated] Mastering Twitter Videos  Adhere to Aspect Ratio Rules for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-solving-grey-voids-in-gaming-capture-software/"><u>[Updated] Solving Grey Voids in Gaming Capture Software</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-spoofing-success-the-path-to-parody-proficiency-for-2024/"><u>[Updated] Spoofing Success  The Path to Parody Proficiency for 2024</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/2024s-most-advanced-and-immersive-htpc-setups-reviewed/"><u>2024'S Most Advanced and Immersive HTPC Setups Reviewed!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723204746170-bluetooth-troubles-in-windows-11-quick-tips-to-get-it-working-again/"><u>Bluetooth Troubles in Windows 11? Quick Tips to Get It Working Again!</u></a></li>
<li><a href="https://extra-tips.techidaily.com/brief-blotter-for-film-blueprint-for-2024/"><u>Brief Blotter for Film Blueprint for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/commanding-your-computer-to-rest-when-not-in-use/"><u>Commanding Your Computer to Rest When Not In Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/connectivity-through-time-leveraging-windows-7-for-windows-11-activation/"><u>Connectivity Through Time: Leveraging Windows 7 for Windows 11 Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-false-listings-of-devices-in-windows-error-logs/"><u>Correcting False Listings of Devices in Windows Error Logs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-and-control-your-windows-11-program-preferences/"><u>Customize and Control Your Windows 11 Program Preferences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-error-messages-with-windows-11-and-ms/"><u>Deciphering Error Messages with Windows 11 and MS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-risks-of-keygen-virus-and-windows-security-measures/"><u>Decoding the Risks of Keygen Virus & Windows Security Measures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-to-the-heart-of-recent-windows-use/"><u>Direct to the Heart of Recent Windows Use</u></a></li>
<li><a href="https://tech-revival.techidaily.com/dissecting-ai-opportunities-vs-threats-to-humanity/"><u>Dissecting AI: Opportunities vs Threats to Humanity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diving-into-windows-sound-system-architecture/"><u>Diving Into Windows' Sound System Architecture</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-update-drivers-for-netgear-a6100-on-windows-computers/"><u>Download & Update Drivers for Netgear A6100 on Windows Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-privilege-based-errors-in-system-installation/"><u>Easing Privilege-Based Errors in System Installation</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/effortless-blocking-of-pop-ups-on-chrome-firefox-and-edge-a-step-by-step-guide/"><u>Effortless Blocking of Pop-Ups on Chrome, Firefox & Edge: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-reading-experience-in-windows-11-notepad/"><u>Elevate Reading Experience in Windows 11 Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-creativity-with-these-8-premium-video-cutters-for-windows/"><u>Enhance Creativity with These 8 Premium Video Cutters for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-operational-usb-on-your-windows-machine/"><u>Fixing Non-Operational USB on Your Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-precursor-pcs-to-progressive-windows-11-platforms/"><u>From Precursor PCs to Progressive Windows 11 Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-windows-capabilities-for-bulk-archive-decompression/"><u>Harnessing Windows Capabilities for Bulk Archive Decompression</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-poco-m6-pro-4g-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Poco M6 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-vivo-v30-drfone-by-drfone-virtual-android/"><u>How to Turn Off Google Location to Stop Tracking You on Vivo V30 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-oppo-a78-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Oppo A78 to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-realme-11-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Realme 11 Pro | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-twitter-jokes-made-accessible-with-3-simple-steps-pc/"><u>In 2024, Twitter Jokes Made Accessible with 3 Simple Steps (PC)</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-wondering-the-best-alternative-to-hola-on-realme-note-50-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>In 2024, Wondering the Best Alternative to Hola On Realme Note 50? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-win-plus-p-not-working-on-windows-heres-how-to-fix-it/"><u>Is Win + P Not Working on Windows? Here's How to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-windows-update-self-replacing-amd-graphics-drivers/"><u>Master Windows Update: Self-Replacing AMD Graphics Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-compression-techniques-for-disk-optimization/"><u>Mastering File Compression Techniques for Disk Optimization</u></a></li>
<li><a href="https://win-forum.techidaily.com/maximize-windows-11-performance-by-deleting-unneeded-files/"><u>Maximize Windows 11 Performance by Deleting Unneeded Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/naming-conventions-editing-windows-11-user-folders/"><u>Naming Conventions: Editing Windows 11 User Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/on-premise-self-hosted-gpt-the-windows-path-via-gpt4all/"><u>On-Premise, Self-Hosted GPT: The Windows Path via GPT4All.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-windows-installer-efficiency/"><u>Optimizing Windows Installer Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-hurdles-in-accessing-network-router/"><u>Overcoming Hurdles in Accessing Network Router</u></a></li>
<li><a href="https://win11-tips.techidaily.com/professional-procrastination-buster-top-windows-productivity-hacks/"><u>Professional Procrastination Buster: Top Windows Productivity Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establishing-a-seamless-search-experience-in-windows-11-tm/"><u>Re-Establishing a Seamless Search Experience in Windows 11 TM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-edge-browser-setting-up-microsofts-defender-application-guard-in-win-11/"><u>Secure Edge Browser: Setting up Microsoft's Defender Application Guard in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-stop-non-data-transfer-from-usb-ports-on-pc/"><u>Solutions to Stop Non-Data Transfer From USB Ports on PC</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/step-by-step-tutorial-downloading-and-installing-dell-g15-drivers-on-pcs-with-windows-os/"><u>Step-by-Step Tutorial: Downloading and Installing Dell G15 Drivers on PCs with Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-entry-into-windows-startup-hub/"><u>Stepwise Entry Into Windows Startup Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-11-home-into-a-virtual-environment-with-hyper-v/"><u>Transforming Windows 11 Home Into a Virtual Environment with Hyper-V</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-the-self-opens-issue-with-msdnstore/"><u>Troubleshooting the Self-Opens Issue with MSDN/Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-files-in-windows-no-more-read-only-limit/"><u>Unlocking Files in Windows: No More Read-Only Limit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-issues-from-a-recent-windows-system-upgrade/"><u>Unraveling Issues From a Recent Windows System Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-window-icon-location-techniques/"><u>Unveiling Window Icon Location Techniques</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-everything-you-need-to-know-about-xmlfiles-in-fcpx/"><u>Updated In 2024, Everything You Need to Know About XMLFiles in FCPX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-your-game-restoring-ps4-input-link-to-stability-on-computer/"><u>Winning Back Your Game: Restoring PS4 Input Link to Stability on Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zeroing-in-on-browsers-post-windows-setup/"><u>Zeroing in on Browsers Post-Windows Setup</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->