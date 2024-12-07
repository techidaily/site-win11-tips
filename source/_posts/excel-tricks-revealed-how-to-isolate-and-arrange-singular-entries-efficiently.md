---
title: "Excel Tricks Revealed: How to Isolate & Arrange Singular Entries Efficiently"
date: 2024-12-04T21:35:30.991Z
updated: 2024-12-06T23:43:53.830Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/24b4a5d68fd5e6bea75410f8f6c4c82cdd5bcbea33115cb8218e3e0a99c10ef2.jpg
---

## Excel Tricks Revealed: How to Isolate & Arrange Singular Entries Efficiently

### Quick Links

* [Use the UNIQUE Function in Excel](https://facebook-video-content.techidaily.com/new-in-2024-unlocking-your-fb-watchlist-access-liked-movies-and-shows/)
* [Sort the List Automatically](https://fox-that.techidaily.com/the-journey-of-facetime-snapshots-how-to-retrieve-and-store-them-safely/)
* [Combine Unique Values](https://youtube-clips.techidaily.com/from-passion-to-paychecks-your-vlog-venture-guide/)

 When you want a list of customers, email addresses, product IDs, or something similar where each one is distinct, [Excel has a function](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/) to help. We'll show you how to use this function to list unique values and text.

 You can already use functions in Excel to total [the number of distinct values](https://youtube-help.techidaily.com/in-2024-unleash-potential-with-optimal-hashtags-for-gaming-vids/). But here we'll show you how to list those values instead using the UNIQUE function. Plus, we'll throw in easy ways to sort the list and combine values.

As of March 2022, the UNIQUE function is available in Excel for Microsoft 365, Excel for the web, Excel 2021 or later, or Excel for iPhone, iPad, or Android phones or tablets.

Related: [How to Count Unique Values in Microsoft Excel](https://youtube-help.techidaily.com/in-2024-unleash-potential-with-optimal-hashtags-for-gaming-vids/) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Use the UNIQUE Function in Excel

 You can use the UNIQUE [function for text](https://video-screen-grab.techidaily.com/updated-the-art-of-smooth-video-transitioning-for-2024/) or numbers, decide how to compare the cell range, and opt to show results that only appear once.

 The syntax for the function is 

        `UNIQUE(array, column, only_once)`
    
 where only the first argument is required. Include the 

        `column`
    
 argument to compare columns instead of rows and the `only_once` argument to return values that occur only one time in the array.

 Should you choose to include the optional arguments, you'll use the TRUE indicator in the formula for each. If no indicator is included, the function assumes FALSE.

 As an example, we'll create a list of customers for an email blast. Rather than use the existing list in cells A2 through A10 because some customers ordered more than once, we'll make a new list where each customer appears one time.

=UNIQUE(A2:A10)

![UNIQUE function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/UNIQUE-ExcelUNIQUEFunction.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 For another example, we'll add the third argument, `only_once`, to find those customers who've only ordered once.

=UNIQUE(A2:A10,,TRUE)

![UNIQUE function for data appearing once](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/OnlyOnce-ExcelUNIQUEFunction.png) 

 Because the second argument assumes FALSE if nothing is included, we simply add a comma after the first argument and then another comma before the last argument. Alternatively, you can use this formula to obtain the same result:

=UNIQUE(A2:A10,FALSE,TRUE)

 You can use the UNIQUE function to list distinct values as well as text. In this formula, we can list unique [dates](https://screen-sharing-recording.techidaily.com/updated-2024-approved-economical-pc-playback-devices/):

=UNIQUE(F2:F10)

![UNIQUE function for dates](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/UNIQUEDates-ExcelUNIQUEFunction.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Related: [How to Sort by Date in Microsoft Excel](https://screen-sharing-recording.techidaily.com/updated-2024-approved-economical-pc-playback-devices/) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Sort the List Automatically

 As mentioned, you can [sort the list](https://facebook-video-share.techidaily.com/free-audio-treasures-to-amplify-youtube-in-2024/) automatically at the same time you use the UNIQUE function to create it. To do this, you simply add the SORT function to the beginning of the formula.

 The SORT function is currently only available in the Excel versions listed [earlier](https://fox-http.techidaily.com/in-2024-experience-like-never-before-leading-10-vr-devices/).

 The syntax for this function is `SORT(array, index, order, column)` where only the first argument is required.

 Using the first list of unique customers we created above and sort it immediately, you would use this formula:

=SORT(UNIQUE(A2:A10))

 As you can see, the UNIQUE formula is the required `array` argument for the SORT function.

![Sort values in ascending order](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/SortAscending-ExcelUNIQUEFunction.png) 

 By default, the SORT function lists items in ascending order. To sort the same list in descending order, you would use the following formula which adds the `order` argument.

=SORT(UNIQUE(A2:A10),,-1)

 Notice here we have a double comma again. This is because we don't want the `index` argument, only the `order` argument. Use 1 for ascending order and -1 for descending order. If no value is used, the function assumes 1 by default.

![Sort values in descending order](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/SortDescending-ExcelUNIQUEFunction.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Combine Unique Values

 One more handy addition to the UNIQUE function allows you to combine values. For instance, maybe your list has values in two columns instead of just one as in the screenshot below.

![First and last names to combine](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/NamesToConcatenate-ExcelUNIQUEFunction.png) 

 By adding the ampersand (&) operator and a space, we can create a list of first and last names of unique customers with this formula:

=UNIQUE(A2:A10&" "&B2:B10)

 To break down the formula, the first array, A2 through A10, contains the first names, the ampersands [concatenate the first names to the last names](https://article-helps.techidaily.com/updated-2024-approved-elevate-your-drone-game-with-top-tier-lipo-tech/) in B2 through B10 with a space between them in quotes.

![Combine unique first and last names](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/Concatenate-ExcelUNIQUEFunction.png) 

 You can also include the SORT function here to put your list in ascending order with this formula:

=SORT(UNIQUE(A2:A10&" "&B2:B10))

![Combine and sort unique first and last names](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/ConcatenateSort-ExcelUNIQUEFunction.png) 

 Just like you might want to [highlight duplicate values in Excel](https://instagram-clips.techidaily.com/how-to-share-igtv-videos-to-facebook-3-ways-for-2024/), you may want to find unique ones. Keep the UNIQUE function and these additional ways to use it in the mind the next time you need to create a list of distinct values or text in Excel.

Related: [How to Use Conditional Formatting to Find Duplicate Data in Excel](https://instagram-clips.techidaily.com/how-to-share-igtv-videos-to-facebook-3-ways-for-2024/)

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
<li><a href="https://video-capture.techidaily.com/new-advanced-strategies-for-logging-lol-contests/"><u>[New] Advanced Strategies for Logging LOL Contests</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-breaking-down-live-mastering-four-fundamental-recording-techniques/"><u>[Updated] Breaking Down Live Mastering Four Fundamental Recording Techniques</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-is-it-lawful-to-screen-capture-youtube-content/"><u>2024 Approved Is It Lawful to Screen-Capture YouTube Content?</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-the-unlisted-conundrum-dissecting-non-indexed-youtube-videos/"><u>2024 Approved The Unlisted Conundrum Dissecting Non-Indexed YouTube Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/contrast-in-connectivity-boosting-pcs-sluggish-internet/"><u>Contrast in Connectivity: Boosting PC's Sluggish Internet</u></a></li>
<li><a href="https://buynow-info.techidaily.com/decoding-macbook-variants-a-comprehebsive-guide-to-air-and-pro/"><u>Decoding MacBook Variants - A Comprehebsive Guide to Air and Pro</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-installation-of-arduino-mega-2560-driver-software/"><u>Easy Installation of Arduino Mega 2560 Driver Software</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-itel-a05s-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Itel A05s | Dr.fone</u></a></li>
<li><a href="https://fox-access.techidaily.com/get-your-data-on-site-quickly-5-best-techniques-for-computer-transfer/"><u>Get Your Data On-Site Quickly 5 Best Techniques for Computer Transfer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-configure-clipboard-functionality-within-microsoft-written-assurance-mode-windows-11/"><u>How to Configure Clipboard Functionality Within Microsoft' Written Assurance Mode, Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-no-available-display-options-on-pc/"><u>How to Correct No Available Display Options on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-the-inconvenience-of-an-endless-updating/"><u>How to Resolve the Inconvenience of an Endless Updating</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-family-safety-a-guide-for-modern-families/"><u>Microsoft Family Safety: A Guide for Modern Families</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconnect-your-printer-to-regain-printing-power/"><u>Reconnect Your Printer to Regain Printing Power</u></a></li>
<li><a href="https://tech-hub.techidaily.com/revolutionize-your-publishing-with-ipublish-streamlined-online-publication-solutions/"><u>Revolutionize Your Publishing with IPublish: Streamlined Online Publication Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-tricks-for-maximizing-microsofts-family-safety/"><u>Tips & Tricks for Maximizing Microsoft's Family Safety</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-win-1111-server-error-in-microsoft-store/"><u>Troubleshooting Win 11/11 Server Error in Microsoft Store</u></a></li>
<li><a href="https://extra-information.techidaily.com/video-show-reviewed-detailed-analysis-of-the-2024-edition/"><u>Video Show Reviewed Detailed Analysis of the 2024 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-status-audit-top-3-strategies/"><u>Windows 11 Status Audit: Top 3 Strategies</u></a></li>
</ul></div>

