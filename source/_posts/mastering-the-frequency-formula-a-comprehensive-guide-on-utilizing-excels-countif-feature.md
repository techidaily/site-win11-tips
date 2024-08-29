---
title: "Mastering the Frequency Formula: A Comprehensive Guide on Utilizing Excel's Countif Feature"
date: 2024-08-27 20:38:20
updated: 2024-08-29 12:15:30
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/74ac13432c01dd5c17161c9b4a52f81e0b445cdf2ff78bc2a59c4da0244a5a39.jpg
---

## Mastering the Frequency Formula: A Comprehensive Guide on Utilizing Excel's Countif Feature

### Quick Links

* [What Does the FREQUENCY Function Do?](https://screen-activity-recording.techidaily.com/new-2024-approved-zippyzoom-tortoisepic-timestretch/)
* [Let's Look at an Example](https://some-knowledge.techidaily.com/updated-exploring-innovative-sequencing-with-gopros-burst-feature/)
* [How to Figure Out Frequency Percentages](https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-oppo-reno-10-proplus-5g-devices-drfone-by-drfone-virtual/)
* [Bypassing the Formulas Menu and Using the Function Bar](https://win-able.techidaily.com/troubleshooting-tactics-for-the-application-has-unexpectedly-stopped-on-cod-mw3-mobile-game/)

 Excel's FREQUENCY function lets you count how many times values fall within specific ranges. For example, if you had the ages of a group of people in your spreadsheet, you could figure out how many people fall into different age ranges. Let's take a look at how to calculate frequency distributions and, with a slight modification, frequency percentages.

##  What Does the FREQUENCY Function Do?

 Excel's FREQUENCY array function lets you calculate a dataset's frequency distribution. You provide the numerical dataset (that's the actual cells you use as your source), a list of bin thresholds (that's the categories into which you're sorting data), and then press Ctrl+Shift+Enter.

 So, how might you use it? Well, here's a quick example. Say you're a teacher with a spreadsheet that shows all your student's numerical test scores. You could use the FREQUENCY function to figure out how many students got an A, B, C, D, or F. The numerical test scores are the dataset and the letter grades form your bin thresholds.

 You would apply the FREQUENCY function to a list of student's test scores, and the function would count how many students got which letter grade by comparing each test score to the range of values that define the different letter grades.

 If you round scores to the nearest tenth of a percent, these ranges would apply:

 F <= 59.9 < D <= 69.9 < C <= 79.9 < B <= 89.9 < A

 Excel would assign a score of 79.9 to the C range while a score of 98.2 would fall into the A range. Excel would go through the list of test scores, categorize each score, count the total number of scores that fall into each range, and return an array with five cells showing the total number of scores in each range.

 The FREQUENCY function requires two arrays as inputs: a "Data\_array" and a "Bins\_array." Arrays are simply lists of values. The "Data\_array" needs to contain values---like the numerical grades for students---that Excel can compare to a series of thresholds defined in the "Bins\_array"---like the letter grades in that same example.

##  Let's Look at an Example

 For our example, we will calculate the frequency distribution and frequency percentages of a set of 18 numbers between 0 and 10\. It's just a simple exercise where we're going to determine how many of those numbers fall between one and two, between two and three, and so on.

 In our simple example spreadsheet, we have two columns: Data\_array and Bins\_array.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/excel-frequency-1-example-data.png) 

 The "Data\_array" column contains the numbers, and the "Bins\_array" column contains the thresholds of the bins we will use. Note that we've left a blank cell at the top of the "Bins\_array" column to account for the number of values in the result array, which will always contain one more value than the "Bins\_array."

 We're also going to create a third column where our results can go; we're naming it "Results."

 First, select the cells where you want the results to go. Now switch to the "Formulas" menu and click the "More Functions" button. On the drop-down menu, point to the "Statistical" submenu, scroll down a bit, and then click the "FREQUENCY" function.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/excel-frequency-2-find-function.png) 

 The Function Arguments window pops up. Click in the "Data\_array" box and then highlight the cells in the "Data\_array" column (you can also type the cell numbers if you prefer).

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/excel-frequency-3-select-data-array.png) 

 If you receive an error message saying you cannot edit only part of an array, it means you didn't select all of the cells of the array. Click "OK" and then hit the Esc key.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/excel-frequency-14-array-error-message.png) 

 To edit the formula of an array or delete the array, you must highlight all of the cells of the array first.

 Now, click in the "Bins\_array" box and then select the filled cells in the "Bins\_array" column.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/excel-frequency-4-select-bins-array.png) 

 Click the "OK" button.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/excel-frequency-5-press-ok-button.png) 

 You will see that only the first cell of the "Results" column has a value, the rest are blank.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/excel-frequency-6-initial-result.png) 

 To see the other values, click inside the "Formula" bar and then press Ctrl+Shift+Enter.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/excel-frequency-7-click-inside-function-bar.png) 

 The Results column will now display the missing values.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/excel-frequency-8-results-after-cse.png) 

 You can see that Excel found four values that were less than or equal to one (highlighted in red) and also found the counts of each of our other number ranges. We've added a "Result Description" column to our spreadsheet so that we can explain the logic Excel used to calculate each result.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/excel-frequency-9-results-explanations-1.png) 

##  How to Figure Out Frequency Percentages

 That's all well and a good, but what if instead of raw counts in the results, we wanted to see percentages instead. What percentage of our numbers fell between one and two, for example.

 To calculate the frequency percentages of each bin, we can alter the array formula using Excel's Function Bar. Highlight all of the cells in the "Results" column and then add the following to the end of the formula in the Function Bar:

/COUNT(B3:B20)

 The final formula should look like this:

=FREQUENCY(B3:B20,C3:C20)/COUNT(B3:B20)

 Now, press Ctrl+Shift+Enter again.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/excel-frequency-10-modify-formula-for-percentages.png) 

 The new formula divides each element of the Results array by the total count of values in the "Data\_array" column.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/excel-frequency-11-initial-percentage-results.png) 

 The results are not automatically formatted as percentages, but that's easy enough to change. Switch to the "Home" menu and then press the "%" button.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/excel-frequency-12-format-using-number-menu.png) 

 The values will now appear as percentages. So, for example, you can now see that 17% of the numbers in the "Data\_array" column fell in the 1-2 range.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/excel-frequency-13-formatted-percentage-results.png) 

 Best of all, now that the formula is in place in the "Results" column, you can alter any of the values in the "Data\_array" and "Bins\_array" columns and Excel will automatically refresh the results with updated values.

##  Bypassing the Formulas Menu and Using the Function Bar

 If you prefer typing and know your way around naming columns and cells, you can always bypass digging through the "Formulas" menu by simply typing functions directly into Excel's Function Bar and then pressing Ctrl+Shift+Enter.

 To calculate frequency distribution, use the following syntax:

{=FREQUENCY(Data_array,Bins_array)}

 To calculate frequency percentages, use this syntax instead:

{=FREQUENCY(Data_array,Bins_array)/COUNT(Data_array)}

 Just remember that this is an array formula, so you must press Ctrl+Shift+Enter instead of just Enter. The presence of {curly brackets} around the formula indicates that it has been entered as an array formula.

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
