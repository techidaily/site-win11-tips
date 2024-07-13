---
title: Advanced Insights Into Integrating Disjoint Windows Partitions
date: 2024-07-12T18:03:18.961Z
updated: 2024-07-13T18:03:18.961Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Advanced Insights Into Integrating Disjoint Windows Partitions
excerpt: This Article Describes Advanced Insights Into Integrating Disjoint Windows Partitions
keywords: Window Partitioning Basics,Advanced Data Segregation,Uniting Windows Partitions,Cross-DB Integration Tech,Disjointed DB Optimization,Seamless Data Migrations,Hybrid Partition Management
thumbnail: https://thmb.techidaily.com/26c79816e74e12a8f414621a79d8575a6f7513edd59ad13bbdba2af26e7005b7.jpg
---

## Advanced Insights Into Integrating Disjoint Windows Partitions

 Have you run out of space on one of your drives and want to expand it by merging in it another drive with free space? If so, you can easily do this if the partitions you want to merge are adjacent; if they are not adjacent, the process would be more complicated. This begs the question: how do adjacent and nonadjacent partitions differ?

 Below, we'll show you how to merge adjacent and non-adjacent partitions using Device Management and NIUBI Partition Editor, a third-party app.

## How Do Adjacent and Non-Adjacent Partitions Differ?

 As the name implies, adjacent partitions are located next to each other. If you have two drives right next to each other, C and D, they are considered adjacent partitions. In contrast, if you have three partitions, C, D, and E, then C and E are nonadjacent partitions because drive D separates them.

 It's straightforward to merge adjacent partitions using the Windows built-in tool and any third-party app. However, merging two non-adjacent partitions could be complicated.

## How to Merge Adjacent Partitions Using Windows Disk Management

 Disk Management is a Windows built-in utility that allows us to manage the hard drives installed on our device. The tool enables us to create, format, and delete partitions, shrink the drive volume by creating a new partition, expand the drive volume by merging space from another drive, and much more.

 When merging a partition with the Disk Management tool, it is necessary to delete an existing volume (adjacent to the drive you wish to extend) and release some space first. Later, you can merge this unallocated space into a partition of your choice.

 Therefore, you'll lose all your data on the drive you want to merge (or delete), which is a major disadvantage. Because of that, you'll need to [relocate your essential Windows apps](https://www.makeuseof.com/tag/move-installed-apps-programs-windows-10/) and files from that drive, and then delete the volume.

 Let's say you want to merge drive D with drive C. This will require you to delete drive D first and merge it into drive C after that. You can delete the volume by following these steps:

1. Type **"Create and format"** in the Windows Search box and click **Create and format hard disk partitions**.  
![Type Create and Format in Windows Search to Open the Disk Management Utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/1-type-create-and-format-in-windows-search-to-open-the-disk-management-utility.jpg)
2. Right-click the volume (the drive you want to merge into another) and select **Delete Volume**.  
![Delete Volume D From Windows Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-delete-volume-d-from-windows-disk-management-tool.jpg)

 Once you've got enough unallocated space available, follow these steps to merge it into your preferred drive:

1. Right-click the drive you want to extend and select **Extend Volume**.  
![Right-Click the Drive You Want to Extend and select Extend Volume in the Windows Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-right-click-the-drive-you-want-to-extend-and-select-extend-volume-in-the-windows-disk-management-tool.jpg)
2. Click **Next**, then select the amount of space you want to merge in the box next to **Select the amount of space in MB**. Following that, click **Next** a second time.  
![Click Next After Selecting the Amount of Space in MB You Want to Extend the Volume By in Windows Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-click-next-after-selecting-the-amount-of-space-in-mb-you-want-to-extend-the-volume-by-in-windows-disk-management-tool.jpg)
3. Then, click **Finish** to merge the unallocated space into your destination drive.

## How to Merge Non-Adjacent Partitions With Disk Management

 If you have unallocated space non-adjacent to the destination drive, the Extend Volume option will appear grayed out in Disk Management, meaning you can't merge the non-adjacent space into the destination drive. You need to first delete the volumes between your destination drive and unallocated space.

 Deleting the in-between volumes will increase the unallocated space and it'll become adjacent to your destination drive. Later, you can merge some portion of the unallocated space into the destination drive and use the rest to recreate the in-between volumes you deleted earlier.

![Delete the Volumes Between Your Destination Drive and Unallocated Space in Windows Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/6-delete-the-volumes-between-your-destination-drive-and-unallocated-space-in-windows-disk-management-tool.jpg)

 Because deleting a volume also deletes its data, you have to [create a backup of all drives](https://www.makeuseof.com/windows-11-create-complete-backup/) en route to your destination and unallocated space before deleting them. Because of this, merging nonadjacent partitions using Device Management is considered ineffective and time-consuming. An easy way to avoid this hassle is to use third-party tools.

## How to Merge Two Non-Adjacent Partitions Using NIUBI Partition Editor

 NIUBI Partition Editor makes merging nonadjacent partitions easy and doesn't require you to delete partitions between the unallocated space and destination partition. Here's how you can merge two non-adjacent partitions, say C and E, using NIUBI:

1. Download the NIUBI Partition Editor software from the [HDD-Tool official website](https://www.hdd-tool.com/download.html). There are two ways to use the software: download and install the setup file or download the portable version and use it without installing it.
2. Search for **NIUBI** in Windows Search to open the software.
3. Right-click the **E** drive you want to merge into **C** and click **Delete volume**. Click **Yes** to confirm; this will release the space.  
![Delete Volume E in NIUBI Partition Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/8-delete-volume-e-in-niubi-partition-editor.jpg)
4. Now, right-click on partition **D,** which is between partition **C** and unallocated space, and click **Resize/Move volume**.  
![Click on ResizeMode to Relocate the Partition D in NIUBI Partition Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/9-click-on-resizemode-to-relocate-the-partition-d-in-niubi-partition-editor.jpg)
5. Then, move the whole volume (don't extend the volume) to the unallocated space right next to it, which will move drive **D** to where the unallocated space was, making the unallocated space adjacent to drive **C**.  
![Drag the Drive D towards the Unallocated Space to Make the Free Space Adjacent to the Drive C](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/10-drag-the-drive-d-towards-the-unallocated-space-to-make-the-free-space-adjacent-to-the-drive-c.jpg)
6. Once adjacent, right-click the **C** drive, click **Resize/Move Volume**, then expand the **C** drive's space to cover the unallocated space. It will merge the unallocated space into the **C** drive.  
![Extend the C Drive to Merge the Unallocated Space into It in the NUIBI Partition Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/11-extend-the-c-drive-to-merge-the-unallocated-space-into-it-in-the-nuibi-partition-editor.jpg)

 That's how you can merge two non-adjacent drives without deleting the drives between the source and destination.

## How Can You Resize and Move Partitions if NIUBI Partition Editor Doesn't Let You?

 The third-party disk management software, such as NIUBI Partition Editor, sometimes doesn't allow users to move or resize their drives. They either find these options grayed out or missing altogether. It usually happens when you try to move or resize an encrypted drive.

 If you see either of these options missing or grayed out for a specific drive, you should first remove the drive encryption, which is Bitlocker by default in Windows. While you can turn off encryption from individual partitions in different ways, we recommend turning off encryption at the device level for a short period of time. Here's how:

1. Search for **"Device Encryption"** in the Windows Search and click on **Device encryption settings**.
2. Turn the toggle next to **Device encryption** off.  
![Turn the Device Encryption Off in Windows Device Encryption Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/12-turn-the-device-encryption-off-in-windows-device-encryption-settings-in-windows-settings-app.jpg)

 Turning off encryption can take a long time, so be patient while the process finishes, and you see the toggle next to **Device encryption** turned off. Once that's done, you can resize and move all the drives without restrictions. Once you're done merging the partitions, re-enable the device encryption.

## Merge Partitions With Ease on Windows

 You can merge partitions to use free space better or expand the volume of a drive running low on storage. Hopefully, you'll now be able to merge adjacent and non-adjacent partitions more easily. Don't forget to turn off device encryption if you cannot resize the drive.

 Also, it is not necessary to use NIUBI Partition Editor; you can use any disk management software of your choice.

 Below, we'll show you how to merge adjacent and non-adjacent partitions using Device Management and NIUBI Partition Editor, a third-party app.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/boost-pc-safety-change-your-windows-11-password/"><u>Boost PC Safety: Change Your Windows 11 Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-the-100-quagmire-with-these-simple-solutions/"><u>Beat the 100%% Quagmire with These Simple Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-spacious-and-slow-a-bittersweet-blend/"><u>Blackview: Spacious and Slow - A Bittersweet Blend</u></a></li>
<li><a href="https://win11-tips.techidaily.com/become-a-speech-converter-transcribe-talk-with-whisper-in-windows/"><u>Become a Speech Converter: Transcribe Talk with Whisper in Windows</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-the-key-elements-in-achieving-proficient-interview-performance/"><u>[Updated] In 2024, The Key Elements in Achieving Proficient Interview Performance</u></a></li>
<li><a href="https://youtube-data.techidaily.com/outube-update-easy-access-to-your-shorts-for-2024/"><u>[New] YouTube Update  Easy Access to Your Shorts for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-resource-allocation-for-ntoskrnlexe/"><u>Balancing Resource Allocation for Ntoskrnl.exe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-system-a-strategy-for-fixing-0x800700e9-in-xbox-game-passwindows-11/"><u>Beating the System: A Strategy for Fixing 0X800700E9 in Xbox Game Pass/Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-the-blue-screen-bane-11-tricks-for-windows-11/"><u>Beat the Blue Screen Bane: 11 Tricks for Windows 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-social-media-sweepstakes-twitters-favorite-videos-ranked/"><u>[Updated] 2024 Approved  Social Media Sweepstakes  Twitter's Favorite Videos Ranked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-the-worst-javascript-failures-while-using-discord-in-win-oses/"><u>Avoiding the Worst JavaScript Failures While Using Discord in Win OSes</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-realme-gt-5-pro-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Realme GT 5 Pro If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bargain-hunters-rejoice-key-lovers-snag-best-prices-for-lifetime-windows-11/"><u>Bargain Hunters Rejoice: Key Lovers Snag Best Prices for Lifetime Windows 11!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-common-pitfalls-of-roblox-error-262/"><u>Avoiding Common Pitfalls of Roblox Error 262</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-tutorial-how-to-make-a-smooth-speed-ramping-in-premiere-pro/"><u>New Tutorial | How to Make a Smooth Speed Ramping in Premiere Pro?</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-vivo-y27-5g-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Vivo Y27 5G | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/zoom-windows-speed-up-overcoming-slow-net-issues/"><u>Zoom Windows Speed Up: Overcoming Slow Net Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-windows-efficiency-embrace-adaptive-tiling/"><u>Amplify Windows Efficiency: Embrace Adaptive Tiling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blueprint-to-rule-winos-apps-browsers/"><u>Blueprint to Rule WinOS Apps, Browsers</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/essential-tips-for-smooth-screen-sharing-on-skype-while-working-from-home/"><u>Essential Tips for Smooth Screen Sharing on Skype While Working From Home</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-deadlock-in-windows-desktop-menu-navigation/"><u>Avoiding Deadlock in Windows Desktop Menu Navigation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-fps-measurement-software-for-windows-11-users/"><u>Best FPS Measurement Software for Windows 11 Users</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-flip-the-script-on-instagram-vids-complete-guide/"><u>[New] In 2024, Flip the Script on Instagram Vids [Complete Guide]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-with-automatic-file-disposal-in-windows-11/"><u>Boost Efficiency with Automatic File Disposal in Windows 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/dual-display-documentation-technique-for-2024/"><u>Dual Display Documentation Technique for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-winning-factors-9-pc-features-that-trump-macs/"><u>Analyzing the Winning Factors: 9 PC Features That Trump Macs</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-streamlining-your-social-media-presence-with-zoom-and-fb-live/"><u>2024 Approved  Streamlining Your Social Media Presence with ZOOM & FB Live</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-the-ultimate-macos-experience-with-screenflow-reviewed/"><u>[New] The Ultimate MacOS Experience with ScreenFlow Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advance-your-wallet-harness-w11-pro-offers-wisely/"><u>Advance Your Wallet: Harness W11 Pro Offers Wisely</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-asus-rog-phone-8-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Asus ROG Phone 8 Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alt-tab-techniques-efficiently-arrange-your-open-windows-win1110/"><u>Alt-Tab Techniques: Efficiently Arrange Your Open Windows (Win11/10)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-copilot-arrives-on-windows-11-transforming-user-interaction/"><u>AI Copilot Arrives on Windows 11, Transforming User Interaction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/awaken-your-pc-to-god-like-powers-with-windows-11/"><u>Awaken Your PC to God-Like Powers with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-revenue-flow-in-microsofts-windows-11-landscape/"><u>Analyzing Revenue Flow in Microsoft's Windows 11 Landscape</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-abletons-soften-sound-strategies/"><u>In 2024, Ableton's Soften Sound Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boltgun-playtime-maximized-overcoming-computer-delays-in-warhammer-40k/"><u>Boltgun Playtime Maximized: Overcoming Computer Delays in Warhammer 40K</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-dji-inspire-2-full-review/"><u>[New] 2024 Approved  DJI Inspire 2 Full Review</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/speedy-screen-grab-creation-techniques-for-2024/"><u>Speedy Screen Grab Creation Techniques for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-webcam-integration-on-windows-11-pcs/"><u>Android Webcam Integration on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-steam-downloads-combatting-speedy-slowdowns/"><u>Boosting Steam Downloads: Combatting Speedy Slowdowns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-the-pitfalls-of-mysterious-obs-studio-recordings/"><u>Avoiding the Pitfalls of Mysterious OBS Studio Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-storage-efficiency-in-windows-11/"><u>Boosting Storage Efficiency in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-words-settings-for-consistent-openness-of-email-attachments-as-text/"><u>Adjust Word's Settings for Consistent Openness of Email Attachments as Text</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advance-your-dev-workflow-with-wsl-2-best-practices-for-windows/"><u>Advance Your Dev Workflow with WSL 2 Best Practices for Windows</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-the-experts-guide-to-effortless-video-submissions-on-igtv/"><u>[New] 2024 Approved  The Expert's Guide to Effortless Video Submissions on IGTV</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-quick-steps-to-convert-macs-image-file-types-for-2024/"><u>[New] Quick Steps to Convert Mac's Image File Types for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/reel-mastery-viewing-twitters-video-in-high-res/"><u>Reel Mastery  Viewing Twitter's Video in High Res</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blank-screenshare-reconnecting-windows-microphone-to-google-meet/"><u>Blank Screenshare: Reconnecting Windows Microphone to Google Meet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-disruptions-securing-winnet-for-peace-of-mind/"><u>Avoid Disruptions: Securing WinNet for Peace of Mind</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-transforming-single-frames-into-motion-narratives/"><u>In 2024, Transforming Single Frames Into Motion Narratives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-generated-windows-keys-unveiling-potential-perils/"><u>AI-Generated Windows Keys: Unveiling Potential Perils</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-journey-from-monochrome-masterpieces-to-vivid-hdri-imagery/"><u>In 2024, Journey From Monochrome Masterpieces to Vivid HDRI Imagery</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-transforming-windows-photos-viewer-with-creative-filter-settings-and-soundscape/"><u>[Updated] Transforming Windows Photos Viewer with Creative Filter Settings & Soundscape</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-best-no-pressure-pc-games-guide/"><u>[New] 2024 Approved  Best No-Pressure PC Games Guide</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-tech-epochs-windows-7-key-to-boot-windows-11/"><u>Bridging the Tech Epochs: Windows 7 Key to Boot Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-gaming-prowess-mastering-adventure-games-in-high-definition-hd/"><u>Boost Your Gaming Prowess: Mastering Adventure Games in High-Definition HD</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/-journey-top-tags-to-accelerate-views-in-short-form-videos-for-2024/"><u>Viral Journey  Top Tags to Accelerate Views in Short Form Videos for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-all-you-need-to-know-about-podcast-funding/"><u>[New] All You Need To Know About Podcast Funding</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-system-safety-wins-7-top-rated-zero-cost-pass-gen-software/"><u>Boost System Safety: Win's 7 Top Rated Zero-Cost Pass Gen Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/batch-processing-closure-for-busy-windows-users/"><u>Batch-Processing Closure for Busy Windows Users</u></a></li>
<li><a href="https://some-techniques.techidaily.com/expertise-in-action-mastering-iphone-silhouette-art-for-2024/"><u>Expertise in Action  Mastering iPhone Silhouette Art for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-aesir-clash-in-the-shadow-of-ragnarok/"><u>[New] Aesir Clash  In the Shadow of Ragnarok</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-create-unforgettable-moments-best-online-collage-makers/"><u>New 2024 Approved Create Unforgettable Moments Best Online Collage Makers</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-decoding-windows-10s-secret-for-file-imports/"><u>2024 Approved  Decoding Windows 10'S Secret for File Imports</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-getting-started-with-snapchat-a-mac-users-guide/"><u>2024 Approved  Getting Started with Snapchat  A Mac User's Guide</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-elevate-your-feed-10-must-have-instagram-tools/"><u>2024 Approved  Elevate Your Feed  10 Must-Have Instagram Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-efficiency-integrating-new-folders-into-windows-11-menu/"><u>Boosting Efficiency: Integrating New Folders Into Windows 11 Menu</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-streamlining-mov-files-on-windows-11-os/"><u>[Updated] 2024 Approved  Streamlining MOV Files on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automated-password-inclusion-in-windows-file-management/"><u>Automated Password Inclusion in Windows File Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-techniques-to-master-voice-activated-accessibility-on-windows/"><u>Advanced Techniques to Master Voice-Activated Accessibility on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augment-windows-security-incorporating-advanced-firewalls-in-the-context-menu/"><u>Augment Windows Security: Incorporating Advanced Firewalls in the Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-net-speed-win-pc-download-acceleration-tips/"><u>Boosting Net Speed: Win-PC Download Acceleration Tips</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>