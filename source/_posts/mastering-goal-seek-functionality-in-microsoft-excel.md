---
title: Mastering Goal Seek Functionality in Microsoft Excel
date: 2024-12-01T00:13:07.760Z
updated: 2024-12-07T02:12:12.862Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/09/microsoft_excel_hero_1200x675.jpg
---

## Mastering Goal Seek Functionality in Microsoft Excel

### Quick Links

* [What Is Goal Seek in Excel?](https://youtube-stream.techidaily.com/mastering-mobile-media-the-art-of-filming-with-a-smartphone-for-2024/)
* [Goal Seek Examples](https://techtrends.techidaily.com/sequential-screen-time-with-taylor-swift-movie-marathon-essentials/)

 Have you ever had a [financial goal](https://youtube-videos.techidaily.com/2024-approved-comprehensive-guide-your-shorts-hidden-thumbnails/) you sought but weren't exactly sure how to get there? Using Goal Seek in Microsoft Excel, you can determine what you need to accomplish your goal.

 Maybe you want to save a certain amount of money in the next few years but aren't sure how much you need to set aside each month. Or perhaps you want to take out a loan and know [how much you can afford](https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-realme-narzo-60-pro-5g-phone-that-is-locked-by-drfone-android/) every month, but don't know what interest rate to look for.

 Goal Seek can help you with these types of calculations as well as others.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  What Is Goal Seek in Excel?

 Goal Seek is part of the What-If Analysis group built into Excel. It works with values you insert and a [formula you enter](https://youtube-docs.techidaily.com/n-2024-automate-playlist-retrieval-from-youtube-directly/) to calculate those values. This means that a formula is necessary to use Goal Seek.

Related: [5 iPhone Apps to Keep Track of Your Investments](https://android-pokemon-go.techidaily.com/in-2024-here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-samsung-galaxy-a23-5g-drfone-by-drfone-virtual-android/) 

 The tool is especially useful for the situations mentioned above such as savings, [investments](https://android-pokemon-go.techidaily.com/in-2024-here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-samsung-galaxy-a23-5g-drfone-by-drfone-virtual-android/), and loans, but can be used in other scenarios as well. Once you obtain the results from the Goal Seek tool, you can simply view them or pop them into your sheet.

##  Goal Seek Examples

 If you're ready to give this nifty feature a try, let's look at some example uses.

###  Goal Seek for Sales

 For a simple way to get familiar with the tool, we'll start with a basic example. We want to determine how many units of our product we need to sell to reach our goal. So, we have the current Quantity, Unit Price, and Total Sales as shown below.

![Sales figures in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/SalesFigures-ExcelGoalSeek.png) 

 The Total Sales in cell B3 is a formula that multiples the Quantity by the Unit Price: 

        `=B1*B2`
    
 .

 We want to find out how many units we must sell to reach our goal of $20,000 in total sales. For this, Goal Seek is ideal.

 Go to the Data tab, click the What-If Analysis drop-down arrow, and select "Goal Seek."

![Goal Seek in the What-If Analysis menu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/DataGoalSeek-ExcelGoalSeek.png) 

 In the small Goal Seek box, insert the following:

**Set Cell**: Enter the cell reference containing the formula you want to change. Remember, changing the formula shows us the input we need to reach our goal.

**To Value**: Enter the result you want. For us, this is 20,000.

**By Changing Cell**: Enter the reference for cell you want to adjust. For us, this is B1 for the Quantity.

![Goal Seek for sales figures](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/SalesSeek-ExcelGoalSeek.png) 

 When you finish, click "OK." The Goal Seek Status box shows a solution was found and you'll see a preview in your spreadsheet.

![Goal Seek results for sales figures](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/SalesSeekResults-ExcelGoalSeek.png) 

 As you can see, we now know that we must sell 800 units of our product to reach our $20,000 goal. Click "OK" to apply the change to your sheet or "Cancel" to simply close the Goal Seek Status window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZLb1ViO4WR8?si=g_aiHGNCd7eAvmDM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

###  Goal Seek for Loans

 Another good way to use Goal Seek in Excel is for help with loans. You may have the loan amount, term in months, and payment you can afford, but want to know what interest rate you should seek. Because the Goal Seek tool works off of formulas, you can leave the interest rate cell blank and allow Goal Seek to fill it.

Related: [How to Calculate a Loan Payment, Interest, or Term in Excel](https://article-tips.techidaily.com/2024-approved-deciphering-the-world-of-augmented-reality-stickers-googles-role/) 

 Here we have the Loan Amount, Term, and Payment fields filled in. (You can ignore the payment amount displayed for now since the formula still needs the interest rate.) We have the formula for the [PMT (Payment) function](https://article-tips.techidaily.com/2024-approved-deciphering-the-world-of-augmented-reality-stickers-googles-role/) in cell B4: 

        `=PMT(B3/12,B2,B1)`
    
 .

![Loan figures in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/LoanFigures-ExcelGoalSeek.png) 

 Select Data > What-If Analysis > Goal Seek and insert the following:

**Set Cell**: Enter the cell reference containing the formula you want to change. For us, this is B4.

**To Value**: Enter the result you want. For us, this is -800 because we can afford $800 monthly.

**By Changing Cell**: Enter the reference for cell you want to adjust. For us, this is B3 for the Interest Rate.

 Excel uses a negative number for the payment when using the PMT function.

![Goal Seek for loan figures](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/LoanSeek-ExcelGoalSeek.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click "OK" to see the results. It looks like we'll try for a 4.77% annual interest rate for our loan.

![Goal Seek results for loan figures](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/LoanResults-ExcelGoalSeek.png) 

 Select "OK" to apply the change to your sheet or "Cancel" to close the box.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

###  Goal Seek for Savings

 For one more example, you might have a savings goal you want to reach in a certain amount of time. We want to save $5,000 in 12 months, our [bank](https://www.reviewgeek.com/67538/here-are-the-best-alternatives-to-simples-online-banking-service/) offers 1.5% interest, and we need to know how much to deposit each month.

 Here we have the Interest Rate and Number of Payments filled in. The Payment is blank because Goal Seek will enter it and the Goal is at $0 because the formula still needs the payment amount. We have the formula for the [FV (Future Value) function](https://support.microsoft.com/en-us/office/fv-function-2eef9f44-a084-4c61-bdd8-4fe4bb1b71b3) in cell B4: 

        `=FV(B1/12,B2,B3)`
    
 .

![Savings figures in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/SavingsFigures-ExcelGoalSeek.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Head back to Data > What-If Analysis > Goal Seek and insert the following:

**Set Cell**: Enter the cell reference containing the formula which is B4 in our example.

**To Value**: Enter the result you want. For our goal, this is 5000.

**By Changing Cell**: Enter the reference for cell you want to adjust which is B3 for the Payment.

![Goal Seek for savings figures](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/SavingsSeek-ExcelGoalSeek.png) 

 Click "OK" to view your results. We see that we need to save just over $413 per month for the next year to reach our $5,000 goal.

![Goal Seek results for savings figures](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/SavingsResults-ExcelGoalSeek.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/omWG4u39lmE?si=yk1AEo_gzDpGjYbl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Excel uses a negative number for the payment when using the FV function.

 Again, click "OK" to apply the change or "Cancel" to close the window.

 When you need help figuring out how to reach your financial goal, pop open the Goal Seek tool in Excel. For more, take a look at [how to use Excel's built-in stocks feature](https://screen-recording.techidaily.com/2024-approved-ultimate-guide-cost-effective-pc-screen-recording-apps/).

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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-comparing-streamlabs-with-obs-for-professional-broadcasts/"><u>[New] 2024 Approved Comparing Streamlabs with OBS for Professional Broadcasts</u></a></li>
<li><a href="https://vp-tips.techidaily.com/ai-powered-digital-creation-simplified-unstablefusion-across-windows-macos-and-linux/"><u>AI-Powered Digital Creation Simplified: UnstableFusion Across Windows, macOS & Linux</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/from-processors-to-peripherals-your-trusted-source-for-computer-hardware-toms-hardware/"><u>From Processors to Peripherals: Your Trusted Source for Computer Hardware - Tom's Hardware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-this-app-is-preventing-windows-from-shutting-down-restarting-or-signing-out-error-on-windows/"><u>How to Fix “This App Is Preventing Windows From Shutting Down, Restarting, or Signing Out” Error on Windows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-essential-guide-to-choosing-video-aspect-ratios/"><u>In 2024, The Essential Guide to Choosing Video Aspect Ratios</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-4-ways-to-trace-oppo-reno-10-pro-5g-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 4 Ways to Trace Oppo Reno 10 Pro 5G Location | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-unlocking-video-potential-the-creme-de-la-creme-browser-recorders/"><u>In 2024, Unlocking Video Potential The Crème De La Crème Browser Recorders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pause-in-play-reactivating-computers-sound-system/"><u>Pause in Play? Reactivating Computer's Sound System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-old-computers-switching-away-from-windows/"><u>Refreshing Old Computers: Switching Away From Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-microsoft-words-audio-readback-function/"><u>Reinstating Microsoft Word's Audio Readback Function</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-6-best-multi-monitor-brightness-control-software-for-windows/"><u>The 6 Best Multi-Monitor Brightness Control Software for Windows</u></a></li>
<li><a href="https://driver-download.techidaily.com/the-definitive-walkthrough-on-obtaining-the-newest-zebra-zp450-printer-drivers-and-updates/"><u>The Definitive Walkthrough on Obtaining the Newest Zebra ZP450 Printer Drivers & Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-potential-how-ai-transforms-windows-innovations/"><u>Unlocking Potential: How AI Transforms Windows Innovations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-methods-enhancing-windows-disk-capacity-without-spending/"><u>Winning Methods: Enhancing Windows Disk Capacity without Spending</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winvpn-error-connection-lost-explained-and-fixed/"><u>WinVPN Error: Connection Lost Explained and Fixed</u></a></li>
</ul></div>

