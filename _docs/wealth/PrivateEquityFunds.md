---
title: Private Equity Funds
tags: 
 - Elysys Wealth
 - Private Equity Funds
description: The Auto-Adjust PE Market Value functionality allows users to automatically update the market price of the private equity funds at the same time when posting transactions.
---
![/assets/img/ElysysLoansLogo.png](../../assets/img/ElysysWealthLogo.png) ![/assets/img/ElysysLoansLogo.png](../../assets/img/ElysysLoansLogo.png)

# ***Elysys Wealth – Private Equity Funds***

The **Auto-Adjust PE Market Value** functionality allows users to automatically update the market price of the private equity funds at the same time when posting transactions.

## **Summary**
-	When processing a **capital call** or **distribution** ➔ the market value increases at the date of the transaction by the amount added in the contract,
-	When processing a **capital return** ➔ the market value decreases at the date of the transaction by the amount added in the contract,
-	When processing a reallocation ➔ the market value is updated accordingly,
-	When processing an **impairment** ➔ the market value increases at the date of the transaction by the amount added in the contract.
-	When a **PnL** transaction or a **commitment** is recorded ➔ the market value doesn't change.

## **How to enable it**
Access the Investment General Setup and toggle on the **Auto-Adjust PE Market Value** field

![/assets/img/PrivateEquityFunds/image001.png](../../assets/img/PrivateEquityFunds/image001.png)


## **How it works – use case**

| | |
| ---        |           --- |
| Start fresh with a new fund with its market value being zero | ![/assets/img/PrivateEquityFunds/image003.png](../../assets/img/PrivateEquityFunds/image003.png) |
| Process the commitment | ![/assets/img/PrivateEquityFunds/image005.png](../../assets/img/PrivateEquityFunds/image005.png)|
| Processing the commitment won’t affect the valuation | ![/assets/img/PrivateEquityFunds/image007.png](../../assets/img/PrivateEquityFunds/image007.png)|
| Process a **capital call** | ![/assets/img/PrivateEquityFunds/image009.png](../../assets/img/PrivateEquityFunds/image009.png)|
| User is prompted with the following message | ![/assets/img/PrivateEquityFunds/image011.png](../../assets/img/PrivateEquityFunds/image011.png) |
| By choosing **Yes**, the valuation will be incremented | ![/assets/img/PrivateEquityFunds/image013.png](../../assets/img/PrivateEquityFunds/image013.png) |
| Process a second **capital call** | ![/assets/img/PrivateEquityFunds/image015.png](../../assets/img/PrivateEquityFunds/image015.png) |
| The same prompt is shown | ![/assets/img/PrivateEquityFunds/image017.png](../../assets/img/PrivateEquityFunds/image017.png) |
| By choosing **Yes**, the valuation will be incremented | ![/assets/img/PrivateEquityFunds/image019.png](../../assets/img/PrivateEquityFunds/image019.png) |
| Process a distribution | ![/assets/img/PrivateEquityFunds/image021.png](../../assets/img/PrivateEquityFunds/image021.png) |
| The same prompt is shown | ![/assets/img/PrivateEquityFunds/image023.png](../../assets/img/PrivateEquityFunds/image023.png) |
| *By choosing **Yes**, the valuation will be incremented | ![/assets/img/PrivateEquityFunds/image025.png](../../assets/img/PrivateEquityFunds/image025.png) |
| Process a PnL transaction **(Dividend)**
**No prompt message is shown, and the valuation is not impacted** | ![/assets/img/PrivateEquityFunds/image027.png](../../assets/img/PrivateEquityFunds/image027.png) |
| Process a **capital return** | ![/assets/img/PrivateEquityFunds/image029.png](../../assets/img/PrivateEquityFunds/image029.png) |
| By choosing **Yes**, the valuation will be incremented | ![/assets/img/PrivateEquityFunds/image031.png](../../assets/img/PrivateEquityFunds/image031.png) |

*After processing a distribution, the reallocation is done via the reallocation journal. Once this is done, the valuation will be changed accordingly i.e capital return ➔ the valuation is decreased.