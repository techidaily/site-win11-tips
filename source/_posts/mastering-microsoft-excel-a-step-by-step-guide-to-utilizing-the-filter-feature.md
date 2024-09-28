---
title: "Mastering Microsoft Excel: A Step-by-Step Guide to Utilizing the Filter Feature"
date: 2024-08-28T01:08:43.930Z
updated: 2024-08-29T01:08:43.930Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/0ee1c1c5a9be407cbf065c21cefa3d097b024c8bd5c0bbace26a3b7cf94a12be.jpg
---

## Mastering Microsoft Excel: A Step-by-Step Guide to Utilizing the Filter Feature

### Quick Links

* [What Is the FILTER Function in Excel?](https://fox-access.techidaily.com/boosting-productivity-with-zoom-and-a-chromebook-for-2024/)
* [How to Create a Basic Filter Formula](https://extra-skills.techidaily.com/in-2024-precision-zoom-mastery-in-microsoft-teams-sessions/)
* [Filter Using Multiple Criteria in the FILTER Function](https://android-pokemon-go.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-oneplus-ace-2-drfone-by-drfone-virtual-android/)
* [How to Sort Your Filtered Data in Excel](https://instagram-video-files.techidaily.com/updated-in-2024-transformations-unlocked-the-2-most-effective-ways-to-convert-video/)

### Key Takeaways

To use the FILTER function, enter simply enter the array and range for your criteria. To avoid an Excel error for empty filter results, use the third optional argument to display a custom indicator.

 Microsoft Excel offers a [built-in filter feature](https://facebook-video-share.techidaily.com/free-audio-treasures-to-amplify-youtube-in-2024/) along with the option to use an advanced filter. But if you want to filter by multiple criteria and even [sort the results](https://win11-tips.techidaily.com/steps-to-resolve-iphone-image-failure-in-windows-os/), check out the FILTER function in Excel.

 Using the FILTER function, you can use operators for "and" and "or" to combine criteria. As a bonus, we'll show you how to apply the SORT function to the formula to display your results in ascending or descending order by a particular column.

##  What Is the FILTER Function in Excel?

 The syntax for the formula is 

        `FILTER(array, range=criteria, if_empty)`
    
 where only the first two arguments are required. You can use a cell reference, number, or text in quotes for the criteria, depending on your data.

 Use the third optional argument if your data set may return an empty result since it'll display the [#CALC! error](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/) by default. To replace the error message, you can include text, a letter, or number in quotes or simply leave the quotes empty for a blank cell.

##  How to Create a Basic Filter Formula

 To get started, we'll start with a basic filter so that you can [see how the function works](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/). In each screenshot, you'll see our filter results on the right.

Related: [How to Find the Function You Need in Microsoft Excel](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/) 

 For filtering the data in cells A2 through D13 using the content of cell B2 (Electronics) as criteria, here's the formula:

=FILTER(A2:D13,B2:B13=B2)

 To break down the formula, you see the `array` argument is A2:D13 and the `range=criteria` argument is B2:B13=B2\. This returns all results containing Electronics.

![FILTER function basic formula in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/BasicCellReference-ExcelFILTERFunction.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
 Another way to write the formula is by entering the contents of cell B2 in quotation marks as follows:

=FILTER(A2:D13,B2:B13="Electronics")

![FILTER function formula using text criteria](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/BasicText-ExcelFILTERFunction.png) 

 You can also use criteria from another cell to filter the data in the `range=criteria` area. Here, we'll use the data in cell B15.

=FILTER(A2:D13,B2:B13=B15)

![FILTER function using a separate cell as criteria](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/BasicOtherCellReference-ExcelFILTERFunction.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
 If your data contains a number, you can use this as the criteria without quotation marks. In this example, we'll use the same cell range, but filter by cells D2 through D13 looking for 10.

=FILTER(A2:D13,D2:D13=10)

![FILTER function formula using number criteria](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/BasicNumber-ExcelFILTERFunction.png) 

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
 If you aren't receiving any results for your formula or are seeing the #CALC! error, you can use the third argument `if_empty`. For instance, we'll display None if the result is blank.

=FILTER(A2:D13,D2:D13=75,"None")

 As you can see, the `range=criteria` data doesn't include 75, therefore, our result is None.

![FILTER function formula with no results](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/BasicNoResults-ExcelFILTERFunction.png) 

##  Filter Using Multiple Criteria in the FILTER Function

 An advantage of the FILTER function in Excel is that you can filter by multiple criteria. You'll include an operator for [AND (\*) or OR (+)](https://extra-skills.techidaily.com/in-2024-spark-engagement-the-ultimate-list-of-video-text-effects/).

 For example, we'll filter our data set by both A3 (West) and B2 (Electronics) using an asterisk (\*) with this formula:

=FILTER(A2:D13,(A2:A13=A3)*(B2:B13=B2))

 As you can see, we have one result that includes both West and Electronics.

![FILTER function formula for multiple criteria using AND](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/MultipleCriteriaAND-ExcelFILTERFunction.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
 To use the other operator, we'll filter for either A3 or B2 using a plus sign (+) as follows:

=FILTER(A2:D13,(A2:A13=A3)+(B2:B13=B2))

 Now, you can see that our results contain five records with West or Electronics.

![FILTER function formula for multiple criteria using OR](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/MultipleCriteriaOR-ExcelFILTERFunction.png) 

##  How to Sort Your Filtered Data in Excel

 If you want to [sort the results](https://some-knowledge.techidaily.com/new-frame-flair-choosing-the-best-video-cameras-for-deliberate-moves/) you receive from the FILTER function, you can add the SORT function to the formula. This is simply an alternative to using the Sort feature on the Data tab, but doesn't require you to reposition your data.

 For more information on the [SORT function](https://some-techniques.techidaily.com/2024-approved-gopro-versus-polaroid-editing-faces-vs-cameras-that-shoot-them/) before you try it out, take a look at our how-to for full details.

Related: [How to Use the Microsoft Excel SORT Function](https://some-techniques.techidaily.com/2024-approved-gopro-versus-polaroid-editing-faces-vs-cameras-that-shoot-them/) 

 Here, we'll use our basic filter from the beginning of this tutorial: `FILTER(A2:D13,B2:B13=B2)`. Then, we'll add SORT with its arguments to sort by the fourth column (Loss) in descending order (-1):

=SORT(FILTER(A2:D13,B2:B13=B2),4,-1)

 To break down this formula, we have our FILTER formula as the `array` argument for the SORT function. After that, we have `4` to sort by the fourth column in the data set and `-1` to display the results in descending order.

![FILTER function with SORT function in descending order](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/SortDescending-ExcelFILTERFunction.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
 To display the results in ascending order instead, replace the `-1` with `1`:

=SORT(FILTER(A2:D13,B2:B13=B2),4,1)

![FILTER function with SORT function in ascending order](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/SortAscending-ExcelFILTERFunction.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 Excel's built-in filter is great for quickly seeing specific records in a data set. And the [advanced filter](https://driver-error.techidaily.com/error-22-addressed-device-now-online/) works well for filtering by a criteria range in place or another location. But for using multiple criteria and sorting at the same time, take the FILTER function for a spin.

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


