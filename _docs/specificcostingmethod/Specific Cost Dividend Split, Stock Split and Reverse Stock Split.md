---
title: Specific Cost Divident Split, Stocks Split and Reverse Stock Split
tags: 
 - Specific Cost
 - Split
description:
---

![/assets/img/ElysysWealthLogo.png](../../assets/img/ElysysWealthLogo.png) 

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

 
![/assets/img/DividentSplit/image001.png](../../assets/img/DividentSplit/image001.png)
  

-   **Dividend Stock** - distribution of additional shares.

-   **Stock Split** - increases the number of outstanding shares. Stock
    Split allows only positive adjustment and is calculated by dividing
    existing shares into multiple shares.

-   **Reverse Stock Split** - decreases the number of outstanding shares
    and only negative adjustment is allowed.


![/assets/img/DividentSplit/image003.png](../../assets/img/DividentSplit/image003.png)


**(1) Dividend Stock Qty Change**


Equities - Back Office

![/assets/img/DividentSplit/image004.png](../../assets/img/DividentSplit/image004.png)


**Report**


![/assets/img/DividentSplit/image006.png](../../assets/img/DividentSplit/image006.png)

Investment Ledger Entries


![/assets/img/DividentSplit/image008.png](../../assets/img/DividentSplit/image008.png)


Investment Cost Entry


![/assets/img/DividentSplit/image010.png](../../assets/img/DividentSplit/image010.png)



**(2) Stock Split Qty Change**


-   Automatic allocation to outstanding lot at trade date based on the
    following formula:


-   Quantity Lot 1/ ((Sum of all Purchases)/(Sum of all Purchases+ Qty
    Stock Split Change))


-   Stock Split allows positive adjustments only.


Equities - Back Office


![/assets/img/DividentSplit/image012.png](../../assets/img/DividentSplit/image012.png)
 

**Report**


Initial lots are written off and Purchase lines are reopened with new
Quantity.


![/assets/img/DividentSplit/image014.png](../../assets/img/DividentSplit/image014.png)


Purchase = 298.01 USD is calculated as follows:

100/ ((1010)/(1010+2000)) = 298.01, where

100 = Qty (lot 1)

1000 = SUM (Qty (lot1): Qty (lot 6))


![/assets/img/DividentSplit/image016.png](../../assets/img/DividentSplit/image016.png)


 

![/assets/img/DividentSplit/image018.png](../../assets/img/DividentSplit/image018.png)


 

**(3) Reverse Stock Split**


Decreases the number of initial shares hence it needs to be booked in
negative quantity.


![/assets/img/DividentSplit/image020.png](../../assets/img/DividentSplit/image020.png)


**Report**


Initial lots are written off and Purchase lines are reopened with new
Quantity.


![/assets/img/DividentSplit/image022.png](../../assets/img/DividentSplit/image022.png)


![/assets/img/DividentSplit/image024.png](../../assets/img/DividentSplit/image024.png)


 

![/assets/img/DividentSplit/image025.png](../../assets/img/DividentSplit/image025.png)
