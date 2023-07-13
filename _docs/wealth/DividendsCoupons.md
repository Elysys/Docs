title: Dividends and Coupons
tags: 
 - Elysys Wealth
 - Elysys Loans
 - Dividends
  - coupons
description: How to setup and use the dividends and coupons journals
---
![/assets/img/ElysysLoansLogo.png](../../assets/img/ElysysWealthLogo.png) ![/assets/img/ElysysLoansLogo.png](../../assets/img/ElysysLoansLogo.png)

# Dividends and Coupons
## **Dividends Journal**

The Dividend Journal will be used to migrate/ process dividend
information.

**First step** is to enter the details in the **Dividend Information**
page. This is available on each investment card such as Equity Card,
Fund, Private Equity Fund.

*Go to: Investment card (i.e Equity) ➔ Dividend ➔ Button: Dividends
Information*

<div style= "display:flex; align-items:stretch; align-content:space-between">
    <div class="text" style="flex: 1">

  **Ex-Dividend Date:** Date at which the dividend is received in the account   
  **Type:** Cash means it is received as cash   
  **Dividend Amount (ICY):** amount of dividend received per share  
  **Announcement date:** for information only (not mandatory)   
  **Payment Date:** the date at which the payment is received (mandatory)   


  </div>
      <div class="image" style= "flex: 2">
        <img src="../../assets/img/DividendsCoupons/image001.jpg"/>
    </div>
 </div>

  **Second setup** is to setup the account rules for the dividend
postings.   
For each Investment Type, you may setup one GL account for:

<div style= "display:flex; align-items:stretch; align-content:space-between">
    <div class="text" style="flex: 1">


-   **PNL Dividend**: dividend realised account
-   **Tax, Fees, Expense Account**: dividend tax, fee, expense account
-   **Settlement Account**: dividend accrual/ transit account before the amount is received to the bank

  </div>
      <div class="image" style= "flex: 2">
        <img src="../../assets/img/DividendsCoupons/image002.jpg"/>
    </div>
 </div>



Next step is to **book the dividend amount in the income statement.**

*Go to: Home ➔ Actions: Periodic Activities ➔ Button: Dividend Journal.*

From this page, run the \"Suggest Dividend\" function and enter the date
at which you need to process all your dividends in the \"Last payment
Date\" field.

The suggest function will provide the list of all the outstanding
dividends at the date. You may now post those dividends using the "Post"
function in the ribbon. The dividend entries have now been posted to an
income statement dividend account and a receivables account.

Last step is to **settle the cash** received in the bank.

Once the cash from dividends has been received in the bank, the entries
need to be settled.

*Go to: Home ➔ Actions: Periodic Activities ➔ Button: Settlement
Journal.*

Then run the \"Suggest Settlement\" function and enter the date at which
you need to process all your settlement entries in the \"Settlement
Date\" field.

## **Coupons Journal**

The Coupon Journal will be used to process coupon/ interest information.

   **First** is to setup the account rules for the coupon postings.
For each Investment Type, you may setup one GL account for:
<div style= "display:flex; align-items:stretch; align-content:space-between">
    <div class="text" style="flex: 1">

-   **PNL accrued interest:** accrued interest
-   **BS Accrued Interest:** BS accrued interest
-   **PNL Interest:** PNL interest
-   **Tax, Expense Account:** coupon tax, expense account
-   **Settlement Account:** transit account before the amount is received to the bank (used only if Trade Date accounting is required)

  </div>
      <div class="image" style= "flex: 2">
        <img src="../../assets/img/DividendsCoupons/image003.jpg"/>
    </div>
 </div>






Next step is to book the coupon amount.

*Go to: Home ➔ Actions: Periodic Activities ➔ Button: Coupon Journal.*

Then run the \"Suggest Coupons\" function and enter the date at which
you need to process all your settlement entries in the \"Last Payment
Date\" field.

## **Investments Revaluation**

### **Import the Market Price for each investment to be revalued**

*Go to: Home ➔ Periodic Activities ➔ Button: Portfolio Revaluation*

The Portfolio Revaluation journal will be used to revalue the
investments and this process will impact the General Ledger.

As a prerequisite, you must insert the Market Price (in the investment
currency) and the last trading date in the Market Value table before
running the revaluation.

![](../../assets/img/DividendsCoupons/image004.jpg)
