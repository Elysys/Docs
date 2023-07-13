---
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

  <b>Ex-Dividend Date:</b> Date at which the dividend is received in the account    <br>
  <b>Type:</b> Cash means it is received as cash    <br>
  <b>Dividend Amount (ICY):</b> amount of dividend received per share   <br>
  <b>Announcement date:</b> for information only (not mandatory)    <br>
  <b>Payment Date:</b> the date at which the payment is received (mandatory)    <br>


  </div>
      <div class="image" style= "flex: 2">
        <img src="../../assets/img/DividendsCoupons/image001.jpg"/>
    </div>
 </div>
 <br>

  **Second setup** is to setup the account rules for the dividend
postings.   
For each Investment Type, you may setup one GL account for:

<div style= "display:flex; align-items:stretch; align-content:space-between">
    <div class="text" style="flex: 1">


-   <b>PNL Dividend:</b> dividend realised account <br>
-   <b>Tax, Fees, Expense Account:</b> dividend tax, fee, expense account <br>
-   <b>Settlement Account:</b> dividend accrual/ transit account before the amount is received to the bank <br>

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

-  <b>PNL accrued interest:</b> accrued interest <br>
-  <b>BS Accrued Interest:</b> BS accrued interest <br>
-  <b>PNL Interest:</b> PNL interest <br>
-  <b>Tax, Expense Account:</b> coupon tax, expense account <br>
-  <b>Settlement Account:</b> transit account before the amount is received to the bank (used only if Trade Date accounting is required) <br>

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

