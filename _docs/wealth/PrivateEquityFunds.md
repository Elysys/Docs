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

![/assets/img/PrivateEquityFunds/Picture1.png](../../assets/img/PrivateEquityFunds/Picture1.png)


## **How it works – use case**

| | |
| ---        |           --- |
| Start fresh with a new fund with its market value being zero | ![/assets/img/PrivateEquityFunds/Picture2.png](../../assets/img/PrivateEquityFunds/Picture2.png) |
| Process the commitment | ![/assets/img/PrivateEquityFunds/Picture3.png](../../assets/img/PrivateEquityFunds/Picture3.png)|
| Processing the commitment won’t affect the valuation | ![/assets/img/PrivateEquityFunds/Picture4.png](../../assets/img/PrivateEquityFunds/Picture4.png)|
| Process a **capital call** | ![/assets/img/PrivateEquityFunds/Picture5.png](../../assets/img/PrivateEquityFunds/Picture5.png)|
| User is prompted with the following message | ![/assets/img/PrivateEquityFunds/Picture6.png](../../assets/img/PrivateEquityFunds/Picture6.png) |
| By choosing **Yes**, the valuation will be incremented | ![/assets/img/PrivateEquityFunds/Picture7.png](../../assets/img/PrivateEquityFunds/Picture7.png) |
| Process a second **capital call** | ![/assets/img/PrivateEquityFunds/Picture8.png](../../assets/img/PrivateEquityFunds/Picture8.png) |
| The same prompt is shown | ![/assets/img/PrivateEquityFunds/Picture9.png](../../assets/img/PrivateEquityFunds/Picture9.png) |
| By choosing **Yes**, the valuation will be incremented | ![/assets/img/PrivateEquityFunds/Picture10.png](../../assets/img/PrivateEquityFunds/Picture10.png) |
| Process a distribution | ![/assets/img/PrivateEquityFunds/Picture11.png](../../assets/img/PrivateEquityFunds/Picture11.png) |
| The same prompt is shown | ![/assets/img/PrivateEquityFunds/Picture12.png](../../assets/img/PrivateEquityFunds/Picture12.png) |
| *By choosing **Yes**, the valuation will be incremented | ![/assets/img/PrivateEquityFunds/Picture13.png](../../assets/img/PrivateEquityFunds/Picture13.png) |
| Process a PnL transaction **(Dividend)**
**No prompt message is shown, and the valuation is not impacted** | ![/assets/img/PrivateEquityFunds/Picture14.png](../../assets/img/PrivateEquityFunds/Picture14.png) |
| Process a **capital return** | ![/assets/img/PrivateEquityFunds/Picture15.png](../../assets/img/PrivateEquityFunds/Picture15.png) |
| By choosing **Yes**, the valuation will be incremented | ![/assets/img/PrivateEquityFunds/Picture16.png](../../assets/img/PrivateEquityFunds/Picture16.png) |

*After processing a distribution, the reallocation is done via the reallocation journal. Once this is done, the valuation will be changed accordingly i.e capital return ➔ the valuation is decreased.