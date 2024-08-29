---
title: Mastering Goal Seek Functionality in Microsoft Excel
date: 2024-08-28 14:11:45
updated: 2024-08-29 11:42:58
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

 Click "OK" to see the results. It looks like we'll try for a 4.77% annual interest rate for our loan.

![Goal Seek results for loan figures](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/LoanResults-ExcelGoalSeek.png) 

 Select "OK" to apply the change to your sheet or "Cancel" to close the box.

###  Goal Seek for Savings

 For one more example, you might have a savings goal you want to reach in a certain amount of time. We want to save $5,000 in 12 months, our [bank](https://www.reviewgeek.com/67538/here-are-the-best-alternatives-to-simples-online-banking-service/) offers 1.5% interest, and we need to know how much to deposit each month.

 Here we have the Interest Rate and Number of Payments filled in. The Payment is blank because Goal Seek will enter it and the Goal is at $0 because the formula still needs the payment amount. We have the formula for the [FV (Future Value) function](https://support.microsoft.com/en-us/office/fv-function-2eef9f44-a084-4c61-bdd8-4fe4bb1b71b3) in cell B4: 

        `=FV(B1/12,B2,B3)`
    
 .

![Savings figures in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/SavingsFigures-ExcelGoalSeek.png) 

 Head back to Data > What-If Analysis > Goal Seek and insert the following:

**Set Cell**: Enter the cell reference containing the formula which is B4 in our example.

**To Value**: Enter the result you want. For our goal, this is 5000.

**By Changing Cell**: Enter the reference for cell you want to adjust which is B3 for the Payment.

![Goal Seek for savings figures](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/SavingsSeek-ExcelGoalSeek.png) 

 Click "OK" to view your results. We see that we need to save just over $413 per month for the next year to reach our $5,000 goal.

![Goal Seek results for savings figures](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/SavingsResults-ExcelGoalSeek.png) 

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
