---
title: INM Ledger Entries
description: 
author: 
ms.service : 
---

# INM Ledger Entries

## Summary

///

## Fields
<!-- You need to leave a space betwenn | your text and | -->

| Name | Description |
| ---- | ---- |
| Entry No. | Specifies the number of the involved entry or record, according to the specified number series. This is the unique identifier of loans and deposits. |
| Document No. | Specifies the entries Document No. |
| Trade Date | Specifies the Trade Date of loans and deposits. |
| Posting Date | Specifies the Posting Date of loans and deposits. |
| Investment Code | Specifies the Investment Code of loans and deposits. |
| Document Type | Specifies the Document Type the entry belongs to. |
| Portfolio Code | Specifies the Portfolio of loans and deposits. The Portfolio is a container in which multiple loans and deposits can be grouped for the purpose of reporting. |
| Instrument Type | Specifies the Instrument of loans and deposits. |
| Description | Specifies the description of the Instrument Type of loans and deposits. |
| ICY Code | Specifies the investment |
| Amount (ICY) | Specifies the Amount (ICY) of the entry. |
| Amount (PCY) | Specifies the Amount (PCY) of the entry. |
| Amount (LCY) | Specifies the Amount (LCY) of the entry. |
| Tranche | Specifies the tranche of the current Loan. Used as part of the Facility functionality. |
| Gain / Loss | Specifies the Realized/Unrealized Gain / Losses. |
| Number of Days | Specifies the number of days between the value date and the maturity date. |
| Interest Rate | Specifies the Interest Rate of Loans and Deposits. |
| Interest Base Rate | Specifies the base rate for Loans and Deposits in the case of a floating interest. |
| Counterparty Type | Specifies the system module through which Loans and Deposits will be managed. |
| Counterparty Account | Specifies the sub-ledger account against which the accounting entries will be booked. |
| Sales Invoice No. | Specifies the value of the Sales Invoice No. field. |
| Posted Sales Invoice No. | Specifies the value of the Posted Sales Invoice No. field. |
| Bundled Loan No. | Specifies the value of the Bundled Loan No. field. |
| Fee Code | Specifies the unique code of the Fee. |
| Fee Line No. | Specifies the value of the Fee Line No. field. |
| Fees Paid / Capitalized | Specifies Fees Payment and Capitalization of the Deposit. |
| Reversed | Specifies if the entry has been part of a reverse transaction (correction) made by the Reverse function. |
| Reversed  by Entry No. | Specifies the number of the correcting entry. If the field Specifies a number, the entry cannot be reversed again. |
| Reversed Entry No. | Specifies the number of the original entry that was undone by the reverse transaction. |
| Transaction No. | Specifies the unique number of the Transaction. |
| User Id | Specifies the ID of the user who posted the entry, to be used, for example, in the change log. |
| DateTime Posted | Specifies when the transaction was posted. |
| Last Modified DateTime | Specifies the Date and Time when the transaction was modified. |

## Actions

| Name | Description |
| ---- | ---- |
| Reverse Transaction | Executes the Reverse Transaction action. |
| Navigate | Navigate to entries and documents that exist for the document number and posting date on the selected document. |
| Dimensions | View or edit dimensions, such as area, project, or intercompany, that you can assign to the current loan to further analyse transaction history. |
