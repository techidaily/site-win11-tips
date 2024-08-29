---
title: Mastering Microsoft Excel's MATCH Formula for Efficiently Finding Cell Values and Their Rows
date: 2024-08-26 11:41:31
updated: 2024-08-29 10:39:57
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/09/microsoft_excel_hero_1200x675.jpg
---

## Mastering Microsoft Excel's MATCH Formula for Efficiently Finding Cell Values and Their Rows

### Quick Links

* [What Is the MATCH Function in Excel?](https://android-location-track.techidaily.com/in-2024-how-to-track-a-lost-realme-narzo-60x-5g-for-free-drfone-by-drfone-virtual-android/)
* [Use MATCH in Excel](https://easy-unlock-android.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-nokia-c210-device-by-drfone-android/)

 When you need to find a value's exact position in your spreadsheet, you can use the MATCH function in Excel. This saves you from manually searching for the location that you may need [for reference](https://extra-information.techidaily.com/in-2024-chic-coverage-for-your-portable-screen/) or another formula.

 The MATCH function is often used with [the INDEX function](https://youtube-help.techidaily.com/in-2024-the-full-course-on-becoming-a-yt-creator-expert/) as an advanced lookup. But here, we'll walk through how to use MATCH on its own to find a value's spot.

##  What Is the MATCH Function in Excel?

 The MATCH function in Excel [searches](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/) for a value in the array, or range of cells, that you specify.

 For instance, you might look up the value 10 in the cell range B2 through B5\. Using MATCH in a formula, the result would be 3 because the value 10 is in the third position of that array.

![Position of a value in a cell range](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/Position-ExcelMATCHFunction.png) 

 The syntax for the function is 

        `MATCH(value, array, match_type)`
    
 where the first two arguments are required and 

        `match_type`
    
 is optional.

 The match type can be one of the following three options. If the argument is omitted from the formula, 1 is used by default.

* **1**: Finds the largest value less than or equal to the searched  
        `value`  
      
 . The range must be in ascending order.
* **0**: Finds the value exactly equal to the searched  
        `value`  
      
 and the range can be in any order.
* **\-1**: Finds the smallest value greater than or equal to the searched  
        `value`  
      
 . The range must be in descending order.

 You may also see these match types as a tooltip when you build your formula in Excel.

![Match type tool tip in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MatchTypes-ExcelMATCHFunction.png) 

 The MATCH function is not case sensitive, allows the wildcards asterisk (\*) and question mark (?), and returns #N/A as the [error](https://instagram-videos.techidaily.com/updated-cut-and-paste-success-enhancing-videos-for-instagram-shares/) if no match is found.

##  Use MATCH in Excel

 When you're ready to put the MATCH function to work, take a look at these examples to help you walk through [building the formula](https://extra-resources.techidaily.com/2024-approved-crafting-visuals-in-ae-selecting-excellent-plugin-choices/).

 Using our example above, you would use this formula to find the value 10 in the range B2 through B5\. Again, our result is 3 representing the third position in the cell range.

=MATCH(10,B2:B5)

![MATCH used to look up a value's position](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/Match10-ExcelMATCHFunction.png) 

 For another example, we'll include the match type 1 at the end of our formula. Remember, match type 1 requires the array be in ascending order.

=MATCH(10,B2:B5,1)

 The result is 4 which is the position of the number 9 in our range. That's the highest value less than or equal to 10.

![MATCH with match type 1](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MatchType1-ExcelMATCHFunction.png) 

 Here's an example using match type 0 for an exact match. As you can see, we receive the #N/A error because there is no exact match to our value.

=MATCH(10,B2:B5,0)

![MATCH with match type 0](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MatchType0-ExcelMATCHFunction.png) 

 Let's use the final match type -1 in this formula.

=MATCH(10,B2:B5,-1)

 The result is 2 which is the position of the number 11 in our range. That's the lowest value greater than or equal to 10\. Again, match type -1 requires the array be in descending order.

![MATCH with match type -1](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MatchType-1-ExcelMATCHFunction.png) 

 For an example using text, here we can find Caps in the cell range A2 through A5\. The result is 1 which is the first position in our array.

=MATCH("Caps",A2:A5)

![MATCH for finding text in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MatchText-ExcelMATCHFunction.png) 

 Now that you know the basics of using the MATCH function in Excel, you might also be interested in learning about using [XLOOKUP in Excel](https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-asus-rog-phone-7-ultimate-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/) or using [VLOOKUP for a range of values](https://win-able.techidaily.com/1723001670706-troubleshooting-genshin-impact-fix-stability-issues-and-stop-pc-crashes/).

| |  Mastering Excel Functions |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |  |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |  |
| Functions                    | [AVERAGE](https://win-able.techidaily.com/fixing-overwatch-startup-issues-how-to-get-rid-of-the-persistent-black-screen/) **·** [CONCATENATE](https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/) **·** [COUNT](https://android-location-track.techidaily.com/how-to-track-a-lost-xiaomi-redmi-note-12t-pro-for-free-drfone-by-drfone-virtual-android/) **·** [COUNTIF](https://win-forum.techidaily.com/complete-tutorial-clearing-out-windows-10-memory-dump-data/) **·** [DATEDIF](https://youtube-data.techidaily.com/n-2024-explore-the-best-historian-content-top-10-youtube-recommendations/) **·** [FILTER](https://youtube-sure.techidaily.com/024-approved-the-ultimate-guide-to-youtube-live-streaming/) **·** [FREQUENCY](https://digital-screen-recording.techidaily.com/new-ideal-low-impact-recording-devices-for-eco-conscious-filmmakers/) **·** [FV](https://on-screen-recording.techidaily.com/updated-2024-approved-enhancing-gaming-experience-with-steam-switch-control/) **·** [HYPERLINK](https://some-guidance.techidaily.com/updated-the-minimalists-guide-to-aerial-imagery-with-dji-spark/) **·** [IF](https://android-unlock.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-huawei-phone-by-drfone-android/) **·** [IFS](https://screen-recording.techidaily.com/updated-ultimate-techniques-for-precise-iptv-screen-imaging/) **·** [IMAGE](https://screen-mirror.techidaily.com/top-10-airplay-apps-in-xiaomi-redmi-note-12-5g-for-streaming-drfone-by-drfone-android/) **·** [INDEX](https://youtube-help.techidaily.com/in-2024-the-full-course-on-becoming-a-yt-creator-expert/) **·** [IS](https://win-amazing.techidaily.com/new-release-gtx-1650-super-driver-updates-compatible-with-windows-11/) **·** [LEN](https://extra-hints.techidaily.com/scalable-and-stylish-type-in-ae-with-top-choices/) **·** [MATCH](https://extra-guidance.techidaily.com/mirthful-missions-delving-into-the-goofy-movie-vhs-for-2024/) **·**[MEDIAN](https://some-techniques.techidaily.com/in-2024-from-novice-to-expert-the-complete-powerdirector-journey/) **·** [RAND](https://instagram-video-recordings.techidaily.com/updated-master-igtv-edits-top-10-tools-ranked/) **·** [ROUND](https://youtube-zero.techidaily.com/ed-2024-approved-the-quick-pathway-to-establishing-a-video-channel-on-your-phone/) **·** [RRI](https://vp-tips.techidaily.com/2024-approved-quick-cash-on-reddit-here-are-13-ways-for-new-users/) **·** [SORT](https://some-techniques.techidaily.com/2024-approved-gopro-versus-polaroid-editing-faces-vs-cameras-that-shoot-them/) **·** [SQRT](https://screen-video-capture.techidaily.com/in-2024-master-guide-ultimate-tips-for-maximizing-mobizens-screen-capture/) **·** [SUBSTITUTE](https://screen-sharing-recording.techidaily.com/updated-maiden-shoot-revelations-and-critique-for-2024/) **·** [SUBTOTAL](https://phone-solutions.techidaily.com/in-2024-prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-oppo-a78-5g-drfone-by-drfone-virtual-android/) **·** [SUM](https://instagram-videos.techidaily.com/updated-steps-to-instagram-verification-and-fan-growth-in-under-150-characters/) **·** [SUMIF](https://on-screen-recording.techidaily.com/pinnacle-platforms-transforming-online-interaction/) **·** [TODAY](https://some-guidance.techidaily.com/2024-approved-unlock-spark-ars-full-potential-with-personalized-lut-implementations/) **·** [TRIM](https://graphic-issues.techidaily.com/regaining-access-to-nvidia-writable-displays/) **·** [TRUNC](https://windows11.techidaily.com/balancing-cpu-and-memory-use-after-news-downloads/) **·** [VLOOKUP](https://extra-tips.techidaily.com/integrate-sound-and-sight-web-studio/) **·** [WEEKDAY](https://youtube-tips.techidaily.com/n-2024-virtual-voyage-youtubes-premier-10-vr-video-experience/) **·** [XLOOKUP](https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-asus-rog-phone-7-ultimate-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/) **·** [YEAR](https://facebook-record-videos.techidaily.com/updated-in-2024-captivating-content-the-basics-of-removing-background-from-videos/) |  |
| Types                        | [Basic](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) **·** [Budgeting](https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-realme-narzo-60-pro-5g-phone-that-is-locked-by-drfone-android/) **·** [Data Entry](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) **·** [Logical](https://extra-skills.techidaily.com/in-2024-spark-engagement-the-ultimate-list-of-video-text-effects/) **·** [Text](https://video-screen-grab.techidaily.com/updated-the-art-of-smooth-video-transitioning-for-2024/) **·** [Time and Date](https://extra-lessons.techidaily.com/kickstart-your-telegram-promotion-journey-tips-for-newbies/)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |  |
| Explained                    | [Copying Formulas](https://extra-tips.techidaily.com/in-2024-converting-personal-memories-from-stillness-to-motion/) **·** [Evaluating Formulas](https://youtube-blog.techidaily.com/ed-the-role-of-youtube-images-in-video-promotion-and-discovery-for-2024/) **·** [Finding Functions](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/) **·** [Fixing Formula Errors](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/) **·** [Functions vs Formulas](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/) **·** [Comparing Lookup Functions](https://tech-revival.techidaily.com/examining-codegpts-capabilities-in-tech-innovation/) **·** [Locking Formulas](https://some-guidance.techidaily.com/in-2024-unveiling-effective-sales-methods/) **·** [Structuring Formulas](https://youtube-docs.techidaily.com/n-2024-automate-playlist-retrieval-from-youtube-directly/) **·** [Translating Formulas](https://extra-tips.techidaily.com/techniques-to-reduce-nausea-while-in-vr/)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |  |

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
