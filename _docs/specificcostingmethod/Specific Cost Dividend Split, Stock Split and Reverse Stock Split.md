---
title: Specific Cost Divident Split, Stocks Split and Reverse Stock Split
tags: 
 - Specific Cost
 - Split
description:
---

![/assets/img/ElysysLoansLogo.png](../../assets/img/ElysysLoansLogo.png)

This document is accompanying the **Elysys Wealth** module, and it has
been created for the purpose of providing users with brief guidance on
how to process contracts for the dividend split, stock split and reverse
stock split.

The system is enhanced by adding Dividend Split, Stock Split and Reverse
Stock Split shares calculation.

 

The feature works with Equities, Funds, Alternative Investments and
Cryptocurrency and it allows stock increase and decrease to the
outstanding number of shares.

 

A new field **Qty Change Type** was added to the contract level. In
combination with **Type** = **Qty Change**, the user can select from the
three options below.

 

![A screenshot of a computer Description automatically
generated](media/image1.png){width="2.3367891513560806in"
height="1.2159995625546807in"}

>  

-   **Dividend Stock** - distribution of additional shares.

-   **Stock Split** - increases the number of outstanding shares. Stock
    Split allows only positive adjustment and is calculated by dividing
    existing shares into multiple shares.

-   **Reverse Stock Split** - decreases the number of outstanding shares
    and only negative adjustment is allowed.

 

![A screenshot of a computer Description automatically
generated](media/image2.png){width="6.268055555555556in"
height="1.7583333333333333in"}

 

**(1) Dividend Stock Qty Change**

 

Equities - Back Office

![A screenshot of a computer Description automatically
generated](media/image3.png){width="6.268055555555556in"
height="2.2222222222222223in"}

 

**Report**

 

![A close-up of a white background Description automatically
generated](media/image4.png){width="6.268055555555556in"
height="0.84375in"}

 

 

Investment Ledger Entries

 

![A screenshot of a computer Description automatically
generated](media/image5.png){width="6.268055555555556in"
height="1.0430555555555556in"}

 

Investment Cost Entry

 

![A screenshot of a computer Description automatically
generated](media/image6.png){width="6.268055555555556in"
height="1.1993055555555556in"}

 

 

 

**(2) Stock Split Qty Change**

 

-   Automatic allocation to outstanding lot at trade date based on the
    following formula:

 

-   Quantity Lot 1/ ((Sum of all Purchases)/(Sum of all Purchases+ Qty
    Stock Split Change))

 

-   Stock Split allows positive adjustments only.

 

Equities - Back Office

 

![A screenshot of a computer Description automatically
generated](media/image7.png){width="6.268055555555556in"
height="2.5319444444444446in"}

 

**Report**

 

Initial lots are written off and Purchase lines are reopened with new
Quantity.

 

![A close-up of a computer screen Description automatically
generated](media/image8.png){width="6.268055555555556in"
height="1.9020833333333333in"}

 

Purchase = 298.01 USD is calculated as follows:

100/ ((1010)/(1010+2000)) = 298.01, where

100 = Qty (lot 1)

1000 = SUM (Qty (lot1): Qty (lot 6))

 

![A screenshot of a computer Description automatically
generated](media/image9.png){width="6.268055555555556in"
height="1.0083333333333333in"}

 

 

![A screenshot of a computer Description automatically
generated](media/image10.png){width="6.268055555555556in"
height="2.765277777777778in"}

 

 

**(3) Reverse Stock Split**

 

Decreases the number of initial shares hence it needs to be booked in
negative quantity.

 

![A screenshot of a computer Description automatically
generated](media/image11.png){width="6.268055555555556in"
height="2.967361111111111in"}

 

**Report**

 

Initial lots are written off and Purchase lines are reopened with new
Quantity.

 

![A close-up of a computer screen Description automatically
generated](media/image12.png){width="6.268055555555556in"
height="1.926388888888889in"}

 

![A screenshot of a computer Description automatically
generated](media/image13.png){width="6.268055555555556in"
height="1.0645833333333334in"}

 

 

![A screenshot of a computer Description automatically
generated](media/image14.png){width="6.268055555555556in"
height="3.134027777777778in"}
