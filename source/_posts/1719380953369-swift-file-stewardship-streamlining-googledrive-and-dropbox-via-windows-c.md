---
title: "Swift File Stewardship: Streamlining GoogleDrive & Dropbox via Windows C:"
date: 2024-07-12T17:57:15.682Z
updated: 2024-07-13T17:57:15.682Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Swift File Stewardship: Streamlining GoogleDrive & Dropbox via Windows C:"
excerpt: "This Article Describes Swift File Stewardship: Streamlining GoogleDrive & Dropbox via Windows C:"
keywords: "Swift Cloud Management,Google Drive Optimization,Dropbox Workflow Efficiency,Windows File Sharing,Streamline Cloud Storage,Data Governance C:,Secure Dropbox Syncing"
thumbnail: https://thmb.techidaily.com/157145562d322ac42b18debf7cc17b6e328143a79a361dfc0ab65e3b0afbaf26.jpg
---

## Swift File Stewardship: Streamlining GoogleDrive & Dropbox via Windows C

 Today, cloud storage solutions are an essential part of our daily life, to the point that all major OSes come with support for such cloud services "baked in".

 Cloud storage services are easier than ever to access, they offer free storage, and as a bonus, they can make your life miserable if you want to access anything stored there using a quirky app instead of your web browser.

 That's why you can find extra third-party tools that assist in using cloud storage "as a normal drive". For this article, though, we'll do the same by exploiting Windows' built-in shared folders functionality!

## Common Cloud Storage Issues You May Encounter on Windows

 Dropbox, Google Drive, and similar cloud storage/sync services are easy to access from a web browser or the OS's default file manager. When you demand more than merely accessing your files, though, you may run into issues.

* Dropbox is accessible from a link in the file manager that brings you to its actual local folder, inside which your files are synced. Alternatively, you can visit that folder yourself. Dropbox cannot be "accessible through a letter" by default.
* Google Drive offers the option to map every account to a drive letter. However, try to access the contents of the virtual drive "behind" its "official" drive letter. Instead of your Google Drive files, you'll find a link to its local folder.
* Other alternatives may be even worse, with some only accessible locally through their custom clients.

 So, is it impossible to have your cloud storage account's "root folder" accessible directly from a drive letter?

 Thankfully, you can use a third-party solution for that. They're usually straightforward and can make your cloud storage "behave" like a normal drive on your computer. Still, you might want to avoid such apps for various reasons.

* Most cost money or are ad-supported.
* You'll be giving access to your data to another third party (on top of the cloud storage provider).
* The more apps and services that have access to your files, the higher the chances they'll fall into the wrong hands after a security breach.
* Extra software and services translate to increased complexity and potential for failure: some files may not sync when you expect them, metadata might get lost, etc.

 The major case against them is that there's no reason to use more software than you need.

## Why Not Just Use Google Drive's Folders?

 Let's see how Google Drive fails to offer proper access to its local folder through a letter.

1. Right-click on **Google Drive's icon** on the tray, click on the **cog icon** on the top right to access its menu and choose **Preferences**. Click on the **cog icon** in Google Drive Preferences window to access your account's settings. Ensure there's a drive letter assigned to your Google Drive.  
![Google Drive Settings Drive Letter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/google-drive-settings-drive-letter.jpg)
2. Visit the actual **drive letter** through any file manager and wonder how there's a "My Drive" folder instead of your files.  
![Google Drive Actual Drive Letter Contents](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/google-drive-actual-drive-letter-contents.jpg)
3. Try "entering" that folder and marvel at how the **path** changes to the true one where Google Drive's folder is stored, potentially breaking some apps.  
![Google Drive True Folder Path](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/google-drive-true-folder-path.jpg)

 Now, let's fix, or rather "sidestep" this little issue by exploiting how network folders work on Windows.

## How to Set Up Windows Shared Folders

 The first part of the process will be "sharing" the actual folder used by the cloud storage service that we want to access directly from a drive. Don't worry; you won't be sharing anything with anyone (apart from the cloud service provider where you already keep your files).

 For this example, we'll swap cloud services and "do Dropbox", but you can use the same process with any cloud storage service's local folder.

1. Run your favorite file manager and visit the path "directly above" your cloud storage folder (so that you can see it in your file manager).  
![Dropbox Folder In Windows Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-in-windows-explorer.jpg)
2. Right-click on the folder and choose **Properties**.  
![Dropbox Folder Windows Explorer Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-windows-explorer-properties.jpg)
3. Move to the **Sharing** tab and enable sharing for your folder. If you need help, check our guide on [how to access shared folders on Windows](https://www.makeuseof.com/unable-to-access-shared-folder-windows/).  
![Dropbox Folder Windows Explorer Properties Sharing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-windows-explorer-properties-sharing.jpg)

## How to Assign Letters to “Networked” Cloud Storage Folders

 Your folder should be accessible "as a share" by now, but it still isn't mapped to a letter. For that, we'll use Windows' ability to assign letters to "network drives" for easy access.

 Thankfully, Windows also recognizes the shared folder as "a network drive", even if it's stored locally.

1. Type "**\\\\localhost**" in your file manager's location bar to see all the shared folders on your local PC. Among them should be your newly shared cloud storage folder.  
![Windows Explorer Localhost Shared Folders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-localhost-shared-folders.jpg)
2. Right-click on it and choose **Map network drive**.  
![Windows Explorer Localhost Shared Folders Menu Map Network Drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-localhost-shared-folders-menu-map-network-drive.jpg)
3. Choose the **letter** you want to assign to your cloud storage folder from the drop-down menu next to **Drive**. Click **Finish** to apply the change.  
![Windows Explorer Map Network Drive Letter Selection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-map-network-drive-letter-selection.jpg)
4. Visit your "new drive" using the letter you assigned, and you should have direct access to your cloud storage's contents.  
![Windows Explorer Direct Access To Dropbox Folder From Letter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-direct-access-to-dropbox-folder-from-letter.jpg)

 The above implies that you'll set up your cloud storage client to fully sync all files and folders/keep them stored locally.

## What About Using Subst?

 You may wonder why we didn't go with subst for this guide. Indeed, subst is so useful that we've made sure to include it on our list of [the essential Windows CMD commands you should know](https://www.makeuseof.com/tag/essential-windows-cmd-commands/). But what is it, how can it help, and how do you use it?

 Open Windows Search with **Win + S**, search for "**Terminal**" or "**PowerShell**", and choose **Run as Administrator**. There, use subst like:

subst DRIVE_LETTER: FULL:\PATH\TO\FOLDER

 For example, to map the folder "c:\\Cloud Drives\\Dropbox" to the letter "Z", the command would be:

subst Z: "C:\Cloud Drives\Dropbox"

 After that, your folder should be accessible from the drive you assigned to it. If the change isn't apparent immediately, log off and back on or restart your PC.

## A Local Folder for Your Cloud Storage on Windows

 Thanks to Microsoft's somewhat square logic of "if it's a shared folder, you can map it, no matter where it is", it's easy to access your cloud storage folders directly from a drive letter. All it takes is to share them with yourself!

 Of course, power users would probably prefer to "subst them" to submission. Strangely, many forget that "subst" can also be used with cloud storage folders. Despite your chosen path, we can probably mark this little annoyance when using cloud storage folders with a "problem solved."

 Cloud storage services are easier than ever to access, they offer free storage, and as a bonus, they can make your life miserable if you want to access anything stored there using a quirky app instead of your web browser.

 That's why you can find extra third-party tools that assist in using cloud storage "as a normal drive". For this article, though, we'll do the same by exploiting Windows' built-in shared folders functionality!



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-clips.techidaily.com/digital-deck-of-cards-youtubes-milestone-challenges/"><u>Digital Deck of Cards  YouTube's Milestone Challenges</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/mastering-the-art-of-cinematic-content-on-instagram-for-2024/"><u>Mastering the Art of Cinematic Content on Instagram for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713963822627-new-in-this-article-we-talk-about-how-to-add-old-film-overlays-and-other-effects-to-turn-the-videos-or-photos-more-vintage-and-with-an-older-aspect-we-take-/"><u>New In This Article, We Talk About How to Add Old Film Overlays and Other Effects to Turn the Videos or Photos More Vintage and with an Older Aspect. We Take a Look at Filmora in This Guide and Give Tips on How to Create Great Retro Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/storage-soaring-speeds-stalling-mp60-model/"><u>Storage Soaring, Speeds Stalling - MP60 Model</u></a></li>
<li><a href="https://win11-tips.techidaily.com/operas-plight-unleash-it-from-windows-freeze/"><u>Opera's Plight? Unleash It From Windows Freeze!</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/precision-and-flexibility-exploring-the-best-10-mac-recording-tools-for-2024/"><u>Precision and Flexibility  Exploring the Best 10 Mac Recording Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-black-screens-in-win11-with-ease/"><u>Overcoming Black Screens in Win11 with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-utorrent-peer-relationships-on-win/"><u>Reestablishing uTorrent Peer Relationships on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-windows-schedule-breakdown-quickly/"><u>Troubleshoot Windows Schedule Breakdown Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/premier-window-warriors-championing-stronger-passwords-today/"><u>Premier Window Warriors: Championing Stronger Passwords Today</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-10-must-have-sound-recording-devices-for-broadcast-enthusiasts/"><u>2024 Approved 10 Must-Have Sound Recording Devices for Broadcast Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-data-recovery-on-windows-11-pro/"><u>Streamlining Data Recovery on Windows 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unseen-sd-card-on-pc-restore-its-visibility-in-explorer/"><u>Unseen SD Card on PC? Restore Its Visibility in Explorer</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-monetize-smart-a-creative-approach-to-earning-with-vimeo/"><u>In 2024, Monetize Smart  A Creative Approach to Earning with Vimeo</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/merging-technology-and-commerce-through-vr-innovation/"><u>Merging Technology & Commerce Through VR Innovation</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-find-the-best-value-top-6-budget-friendly-camera-options/"><u>[New] In 2024, Find the Best Value  Top 6 Budget-Friendly Camera Options</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-step-by-step-guide-to-edges-pip-functionality/"><u>[New] Step-by-Step Guide to Edge’s PIP Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/paperless-pages-winning-window-based-notepad-substitutes/"><u>Paperless Pages: Winning Window-Based Notepad Substitutes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-correct-predominant-anydesk-issues-in-os/"><u>Strategies to Correct Predominant AnyDesk Issues in OS</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-tips-and-tricks-adjusting-the-tempo-of-your-snapchat-videos/"><u>[Updated] Tips and Tricks  Adjusting the Tempo of Your Snapchat Videos</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-facebook-videos-made-simple-unified-techniques-for-desktop-and-mobile-for-2024/"><u>[New] Facebook Videos Made Simple  Unified Techniques for Desktop & Mobile for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instantaneous-transcription-experience-with-whisper-desktop/"><u>Instantaneous Transcription Experience with Whisper Desktop</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-resolving-an-alone-earpiece-dilemma/"><u>2024 Approved  Resolving an Alone Earpiece Dilemma</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-potential-four-ways-to-open-disk-management-in-win11/"><u>Unleashing Potential: Four Ways to Open Disk Management in Win11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-reviving-past-joy-on-fb-the-look-back-video-editing-path-for-2024/"><u>[New] Reviving Past Joy on FB  The Look Back Video Editing Path for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-no-connection-in-windows-ethernet/"><u>Overcoming No Connection in Windows Ethernet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-cut-out-onedrive-from-your-pcs-file-explorer-screenshot/"><u>How to Cut Out OneDrive From Your PC's File Explorer Screenshot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-disabled-windows-application/"><u>How to Enable Disabled Windows Application</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-11s-snip-and-sketch-shortcut/"><u>Launching Windows 11'S Snip & Sketch Shortcut</u></a></li>
<li><a href="https://android-unlock.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-motorola-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Motorola</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-precision-cuts-at-a-touch-select-the-best-short-form-editors/"><u>[Updated] Precision Cuts at a Touch  Select the Best Short Form Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-value-with-smart-acquisition-of-windows-10-product-keys/"><u>Maximizing Value with Smart Acquisition of Windows 10 Product Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-your-windows-hurdles-and-complications/"><u>Quick Fixes for Your Windows Hurdles & Complications!</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-social-media-snippet-seizers-2023/"><u>In 2024, Social Media Snippet Seizers, 2023</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-easy-ways-to-copy-contacts-from-poco-x6-pro-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Easy Ways to Copy Contacts from Poco X6 Pro to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-6-excellent-tools-for-controlling-windows-screen-luminosity/"><u>Unveiling the 6 Excellent Tools for Controlling Windows Screen Luminosity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-share-issue-on-geforce-experience-windows-1011/"><u>Solving Share Issue on GeForce Experience (Windows 10/11)</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-the-2023-assessment-of-apeaksofts-pioneering-screens-recording/"><u>[New] In 2024, The 2023 Assessment of Apeaksoft's Pioneering Screens Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-error-0x80070522-unlocking-client-privileges-in-windows-1110/"><u>Troubleshooting Error 0X80070522: Unlocking Client Privileges in Windows 11/10</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-discovering-premier-software-for-silencing-ambient-sounds/"><u>New 2024 Approved Discovering Premier Software for Silencing Ambient Sounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-gits-full-potential-with-github-desktop-on-windows/"><u>Unlocking Git's Full Potential with GitHub Desktop on Windows</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-effortless-fb-stream-setup-using-obs-on-laptops-mac-and-pc-for-2024/"><u>[New] Effortless FB Stream Setup  Using OBS on Laptops, Mac & PC for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-how-to-leave-a-life360-group-on-xiaomi-13-ultra-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How To Leave a Life360 Group On Xiaomi 13 Ultra Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-start-guide-initiating-screen-capture-on-win-11/"><u>Quick Start Guide: Initiating Screen Capture on Win 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-action-spectacular-the-full-t5-camera-review/"><u>In 2024, Action Spectacular  The Full T5 Camera Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-prime-video-text-barriers-on-windows-11/"><u>Overcoming Prime Video Text Barriers on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-unauthorized-save-errors-in-microsoft-os/"><u>Troubleshooting Unauthorized Save Errors in Microsoft OS</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unlock-the-power-of-pixels-master-color-correction-techniques-11-steps/"><u>In 2024, Unlock the Power of Pixels - Master Color Correction Techniques (11 Steps)</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-insta-influence-playbook-the-9-actions-that-build-a-brand/"><u>[Updated] Insta Influence Playbook  The 9 Actions that Build a Brand</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-remedy-steps-for-immediate-failure-in-adding-your-folder-to-onedrive/"><u>Swift Remedy Steps for Immediate Failure in Adding Your Folder to OneDrive</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-perfect-guide-uploading-subtitles-via-social-networks/"><u>2024 Approved  Perfect Guide  Uploading Subtitles via Social Networks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-system-secrets-generating-and-evaluating-reports/"><u>Unlock Windows System Secrets: Generating & Evaluating Reports</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-nubia-z50s-pro-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from Nubia Z50S Pro Phones with/without a PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-cannot-add-columns-error-in-ms-excel-for-windows-users/"><u>Tackling the 'Cannot Add Columns' Error in MS Excel for Windows Users</u></a></li>
<li><a href="https://audio-editing.techidaily.com/zero-distraction-viewing-stripping-down-your-videos-acoustic-layers-for-2024/"><u>Zero Distraction Viewing Stripping Down Your Videos Acoustic Layers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-windows-environment-top-6-innovative-android-apps/"><u>Transform Your Windows Environment: Top 6 Innovative Android Apps</u></a></li>
<li><a href="https://some-approaches.techidaily.com/transform-your-screen-pip-tutorials-for-macos-enthusiasts-for-2024/"><u>Transform Your Screen  PIP Tutorials for macOS Enthusiasts for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-an-airtag-from-your-apple-id-account-on-iphone-13-pro-by-drfone-ios/"><u>In 2024, How to Remove an AirTag from Your Apple ID Account On iPhone 13 Pro?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-are-windows-cab-files-and-how-do-you-install-them/"><u>What Are Windows CAB Files and How Do You Install Them?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-networking-essential-pre-call-tests-for-webcamsmics/"><u>Navigating Networking: Essential Pre-Call Tests for Webcams/Mics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-your-pc-experience-mastering-windows-11s-search-tool/"><u>Jumpstart Your PC Experience: Mastering Windows 11’S Search Tool</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-assessing-the-capabilities-of-yuneecs-typhoon-h-drone/"><u>2024 Approved  Assessing the Capabilities of Yuneec's Typhoon H Drone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-stepwise-guide-to-conducting-video-chats-on-laptop-via-whatsapp/"><u>[New] 2024 Approved  Stepwise Guide to Conducting Video Chats on Laptop via WhatsApp</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-navigating-vimeo-tiers-free-plus-and-pro-options/"><u>[Updated] Navigating Vimeo Tiers  Free, Plus, and Pro Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-commands-to-access-pc-health-stats/"><u>Step-by-Step Commands to Access PC Health Stats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-the-antiquity-embellishing-old-games-with-retroarch-awards/"><u>Upgrade the Antiquity - Embellishing Old Games With Retroarch Awards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-list-top-7-methods-to-grow-storage-without-paying/"><u>The Essential List: Top 7 Methods to Grow Storage Without Paying</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-vanishing-folder-icons-in-explore/"><u>Overcoming Vanishing Folder Icons in Explore</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-the-home-page-from-the-settings-app-in-windows-11/"><u>How to Remove the Home Page From the Settings App in Windows 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-zooming-in-and-out-like-a-storytelling-pro-insta-tips/"><u>[New] 2024 Approved  Zooming in and Out Like a Storytelling Pro  Insta Tips</u></a></li>
</ul></div>
