---
title: Sync. Wealth with Elysys analytics
tags: 
 - Elysys Wealth
 - Elysys Analytics
description: How to synchronise a newly created company from Elysys Wealth with the Elysys analytics
---
![/assets/img/ElysysLoansLogo.png](../../assets/img/ElysysWealthLogo.png)
# **User Guide  - How to synchronise a newly created company from Elysys Wealth with the BI analytics**

This document describes how to add a new company in the synchronisation
process for the BI (Business Intelligence).

## 1. Create a new Company

There several options for creating a new company:

-   Copying an existing company,

-   Creating a new company from scratch

![](../../assets/img/SynchNewCompanyBI/image001.jpg)

## 2. Add the new company in the Aggregated View

Access the Aggregate View Companies page and add the newly created
company into the list. The page can be opened directly by searching for
*"Aggregated Companies".*

The page can also be accessed by accessing ***Home page Actions:
Aggregate Aggregate Companies** (while using the Elysys Back-Office
profile).*

![](../../assets/img/SynchNewCompanyBI/image002.jpg)

*Note that the steps from down below can be done in any company (not
mandatory in the Master Company) as the table with the Aggregated
Companies is already shared across all the companies.*

![](../../assets/img/SynchNewCompanyBI/image003.jpg)

Available fields:

-   Co. CCY Code (LCY): this field defaults to the company's LCY (local
    currency)

-   Use for USD Exchange Rate: acts as a Global Currency and it's used
    when translated the BI measure into that specific currency

-   Used for Investment Market Date: Not mandatory

-   Risk Free Rate: Not mandatory

-   Manuel Fees G/L Account: the bank charges that relate to the
    transactions in bank accounts

-   Legal Fees: the facility arrangement charges that apply on loans

-   Consultancy: the portfolio management charges that apply on the
    overall portfolio holding Equity, SN, etc

-   Other Costs: the interest expenses that are applied on loans

That\'s all: the new company will be available in the BI after the next
refresh.

## 3. Adding the company to a specific Group
*Note that the steps from down below can be done in any company (not mandatory in the Master Company) as the table with the Aggregated Companies is already shared across all the companies.*

- User will access the *Consolidation* page and open an existing item in the list. The page can be accessed directly by searching for *“Consolidation”*.

![/assets/img/ComsolidatonList.png](../../assets/img/ComsolidatonList.png)

*Figure 4 Accessing the Consolidation module*

- Select an existing grouping or create a new one if needed.

![/assets/img/SelectConsolList.png](../../assets/img/SelectConsolList.png)

*Figure 5 Selecting an existing group*

- Once the group is opened, insert the new company by creating a new line. Mandatory fields to be filled in:
  - *Ownership:* X%
  - *Entity Type*

![/assets/img/ConsolTest.png](../../assets/img/ConsolTest.png)

*Figure 6 Adding a new company into an existing group*

- As a result, the company will be displayed under the ***CONSOLIDATION TEST 1*** in the BI, having the Entity Type ***“ENTITY TEST”.*** Note that the change will be pickup by the BI at the next refresh (refresh rate is 15 minutes).

![/assets/img/ConsolPage.png](../../assets/img/ConsolPage.png)

*Figure 7 New company added into an existing group*

