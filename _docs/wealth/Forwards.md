---
title: Forwards
tags: 
 - Elysys Wealth
 - Forwards
description: How to setup and use the Forwards module.
---
![/assets/img/ElysysLoansLogo.png](../../assets/img/ElysysWealthLogo.png)

# ***Elysys Wealth -- Forwards***

This document describes the standard functionalities of the Forwards
module within Elysys Wealth, as well as the required setup.

![](../../assets/img/Forwards/image001.png)

![Graphical user interface, application Descriptionautomatically generated](../../assets/img/Forwards/image022.png)
![Graphical user interface, application Description automatically generated](../../assets/img/Forwards/image002.png)

## Investment General Setup

The user must make sure the following settings had been set up:

*Home Page ➔ Application Setup ➔ Investment General Setup ➔ Button: New
or Edit*

![A screenshot of a computer Description automatically
generated](../../assets/img/Forwards/image003.png)

This page contains the investment module setup. This setup needs to be
done at the early stage and before any entries can be made by the
module.

-   *Portfolio Dimension code:* Specifies the code to identify the
    Portfolio throughout the system.

-   *Investment Dimension code:* Specifies the code used to identify the
    Investment throughout the system.

-   *Investment Contracts Header Nos:* Specifies the number series to
    number Investment contract headers.

-   *Swift Management Header:* Specifies the number series used by the
    Switch Contract function.

-   *Transfer Management Header:* Specifies the number series used by
    the Transfer Contract function.

-   *Clearing No.:* Specifies the clearing account is used by the Switch
    function. The balance of the investment closed by the function is
    booked to this account and the value of the investment being opened
    is also booked from this account.

-   *Trade Date Accounting:* Specifies if the user needs to run the
    settlement process to transfer the cash from the settlement account
    to the bank.

-   *Forwards No.*: Specifies the number series used in the Forward
    Contract.

-   *User Forward Rate:* specifies if the user allows the revaluation of
    Forward's unrealized market gain/loss;

-   *Use Spot Rate:* specifies if the user allows the revaluation of
    Forward's unrealized Forex Bought and Sold gain/loss.

## Investment Type

Now, we need to define all Investment types that will be used throughout
the investment module with their accounting rules. Investment types need
to be defined according to how investments need to be grouped and
accounted together, it is the equivalent of the product posting group of
Business Central. Investment types are required for every Investment
product ranging from Equities to Options and Forex products plus Private
Equity.

-   *Code:* Specifies the code to identify the Investment Type.

-   *Name:* Specifies the name for the Investment type.

-   *Asset Class:* Specifies the asset class relating to the investment
    type being created. The Asset Class defines how the investments are
    managed / handled by Elysys Wealth as each asset class uses its own
    logic.

![A blue and white line Description automatically
generated](../../assets/img/Forwards/image004.png)

## Forex Posting Group

Once all investment types are created, the accounting rules must be
specified using Investment posting group.

![A screenshot of a computer Description automatically
generated](../../assets/img/Forwards/image005.png)

Accounting rules allows Elysys Wealth to know which account to use in
the process of creating all accounting entries when booking investment
trades. The Investment posting group page is one of the setup page used
by the module along with the coupons posting group, the forex posting
group, the options posting group, the dividends posting groups and so
on.

For each of the Investment type belonging to those assets class a
nominal account is required for the following account:

-   *BS at Cost Account:* Specifies the General Account used to book
    cost related entries such as purchase and sales type entries

-   *BS UR Forex Gain/Loss Reval:* Specifies the Balance Sheet General
    account used to book unrealised forex gain and loss calculated by
    the revaluation.

-   *BS UR Market Gain/Loss Reval:* Specifies the balance Sheet General
    account used to book unrealised Market gain and loss calculated by
    the revaluation.

-   *PnL UR Market Reval:* Specifies the Profit and Loss General account
    used to book unrealised Market gain and loss calculated by the
    revaluation.

-   *PnL UR Forex G/L Reval:* Specifies the Profit and Loss General
    account used to book unrealised forex gain and loss calculated by
    the revaluation.

## Investment Card 

No investment card is needed.

# Journals & Posting procedures 

### 1. Subscription 

Create a new Forward Subscription Contract.

 ![A screenshot of a computer Description automatically
 generated](../../assets/img/Forwards/image006.png)

 \- After selecting a Portfolio and the Posting Date, choose
 "Subscription" as the Document Type then fill in all the remaining
 information on the contract line.

 \- Before definitely posting the contract in the system, make sure you
 preview the to-be-posted entries by using the "Test Report" function
 from the ribbon. The use the "Post" function to validate it.

 \- Subscription contracts will not have any impact on the bank
 balances.

 ![A screenshot of a computer Description automatically
 generated](../../assets/img/Forwards/image007.png)

 Test Preview to check the accounting impact that will be generated
 after posting. The contract will be posted in the Forex Ledger.

 ![A diagram of a solar system Description automatically generated with
 medium confidence](../../assets/img/Forwards/image008.png)

### 2. Portfolio Revaluation 

 **Go to: Home Periodic Activities Button: Forwards Revaluation**

 First, fill in the forward rate with the rate + maturity date +
 relation/ couple.

 ![](../../assets/img/Forwards/image009.png)

 The **Forwards revaluation job** will generate 3 lines, for the
 revaluation of the forward contract rate (Market), the currency sold
 (Forex Sold) and the currency bought (Forex Bought).

 ![A close-up of a white page Description automatically
 generated](../../assets/img/Forwards/image010.png)

 ![A screenshot of a computer Description automatically
 generated](../../assets/img/Forwards/image011.png)

 Test Report to see the accounting impact before posting.

 ![A close-up of a computer screen Description automatically
 generated](../../assets/img/Forwards/image012.png)

### 3. Maturity 

 **Go to: Home ➔ Actions: Periodic Activities ➔ Button: Coupon Journal
 or Structured Notes Coupon Journal**

 To create a Forward Maturity contract, select a Portfolio and the
 Posting Date. The Posting Date must match the Maturity Date of the
 Forward you want to mature.

 Fill in the contract line by selecting "Maturity" as a Document Type,
 the corresponding Investment Type, then double-click the "No." field
 and select the Forward No. you want to mature (or use the function
 \"Close Forward\").

 ![A screenshot of a computer Description automatically
 generated](../../assets/img/Forwards/image013.png)

 Contract generated by Close Forward function (to change the status to
 Completed).

 ![A screenshot of a computer Description automatically
 generated](../../assets/img/Forwards/image014.png)

 Created contract.

 ![A screenshot of a computer Description automatically
 generated](../../assets/img/Forwards/image015.png)

#### Preview of the maturity with NDF unticked

 ![A group of black text Description automatically
 generated](../../assets/img/Forwards/image016.png)

#### Preview of the maturity with NDF ticked

 ![A group of black text Description automatically
 generated](../../assets/img/Forwards/image017.png)

# Navigate functions 

### Detailed View (Open Position)

 ![A screenshot of a computer Description automatically
 generated](../../assets/img/Forwards/image018.png)

 ![A close-up of a computer screen Description automatically
 generated](../../assets/img/Forwards/image019.png)

### Forex Ledger Entries

 Shows all the ledger entries for the relevant "Investment Code".

 Down below is the Subscription contract posted in the ledger and the
 maturity contract.

 ![A close-up of a computer screen Description automatically
 generated](../../assets/img/Forwards/image020.png)

### Dimensions

Link Dimensions to the investment card. These Dimensions will be linked
to all ledger entries.
