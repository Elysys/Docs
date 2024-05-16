---
title: Multi-Company General Journal
description: How to use the Multi-Company General Journal
---

# Multi-Company General Journal

## Scope 

Multi Company General Journal allows posting financial transactions
across all entities within one screen.

Path: Elysys Wealth -\> Toolkit -\> Multicompany General Journal

## Notes

-   **Transactions** can be posted from any company, regardless of the
    companies involved.

-   **Posted Lines** screen takes us to historical aggregated view for
    all journals posted across all entities.

-   **Cashflow Classification** specifies the cashflow category the
    transaction belongs to.

-   **Shortcut Dimensions** are used for analytical purposes and allow
    tracking the source of transactions in the ledger entries. **T**he
    system populates dimension fields in the journal based on the
    shortcut dimensions defined on the General Ledger Setup page.

## Setup & Workflow

1. Two journals for two different companies are inserted via the
Multicompany General Journal.

![](../../assets/img/MulticompanyGeneralJournal/image001.png)

![](../../assets/img/MulticompanyGeneralJournal/image002.png)

Dimensions -- IC A

![](../../assets/img/MulticompanyGeneralJournal/image003.png)

Dimensions -- IC B

![](../../assets/img/MulticompanyGeneralJournal/image004.png)

**Cashflow Classification -** specifies the cashflow category the
transaction belongs to. The categories are user definable and are
predefined in the Cashflow Classification Setup screen. 

![](../../assets/img/MulticompanyGeneralJournal/image00e5.png)

![](../../assets/img/MulticompanyGeneralJournal/image006.png)

**Posting**

To post Multi Company General Journal the following conditions must be
met:

-   Total Balance for all lines must be equal to zero.

-   The general journal lines are balanced by date, based on the Posting
    Date.

The user has an option to either post all or selected lines only.

![](../../assets/img/MulticompanyGeneralJournal/image007.png)

**Posted Lines** take us to the aggregated/historical view for all
transactions posted across all entities.

![](../../assets/img/MulticompanyGeneralJournal/image008.png)

2.  **Document Number Management and Default Currency**

To populate Document No. in the Multi-Company General Journal and
synchronize the same Number Series code across all entities, it is
necessary to create a unique Number Series line that will be linked to a
specific batch in the journal.

It is created within one company, which will serve as the reference
point for calculating Document No. in the Multi-Company General Journal.

To activate it, the No. Series line should be linked to the batch with
which it will be used.

The unique No. Series is created in a dedicated company that will be
linked to the batch in the Multi-Company General Journal. It is
recommended to create the No. Series in the Master Company.

i.  No. Series Set-up

interinter

![](../../assets/img/MulticompanyGeneralJournal/image009.png)

The No. Series Company and No. Series are linked to the batch. The
set-up serves as the reference point for Document No. calculation in the
journal.

ii. Batch Set-up

![](../../assets/img/MulticompanyGeneralJournal/image010.png)

-   No. Series should be used by one batch and one journal only.

-   Default Currency Code: the user can specify the Default Currency to
    be populated in the journal.

-   Currency Mandatory: if flagged, the entry will be blocked if the
    Currency field in the journal is blank.

-   No. Series Company: the company from which the No. Series is used to
    calculate Document Nos.

iii. Multi Company Journal Mapping

![](../../assets/img/MulticompanyGeneralJournal/image011.png)

iv. General Journal Template

The batch used in the Multi-Company General Journal must have the **No.
Series** defined under the General Journal Batches page.

If No. Series should be used, then the **Posting No. Series** must be
left blank.

If the **Posted No. Series** is defined, the No. Series will be
overwritten by the Posted No. Series.

![](../../assets/img/MulticompanyGeneralJournal/image012.png)

v.  Multi-Company General Journal

Based on the above set-up, the Multi-Company General Journal populated
the following Document Numbers and Currencies.

![](../../assets/img/MulticompanyGeneralJournal/image013.png)

The user can manually edit the Document No. if the Manual No. is flagged
in the No. Series set-up page.

vi. Renumber Documents

![](../../assets/img/MulticompanyGeneralJournal/image014.png)

Renumber Document Number is used to manage document numbers in the
system across all companies. assign document numbers and prevent posting
errors in the journal.

The system automatically assigns document numbers based on the No.
Series Company, the reference company, and the No. Series defined within
the batch used.