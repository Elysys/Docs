---
title: INM Loan List Select
description: 
author: 
ms.service : 
---

# INM Loan List Select

## Summary

///

## Fields
<!-- You need to leave a space betwenn | your text and | -->

| Name | Description |
| ---- | ---- |
| No. | Specifies the number of the involved entry or record, according to the specified number series. This is the unique identifier of the Loan. |
| Loan Type | Specifies the type of the loan. The Loan Type defines the payment schedule calculation. |
| Portfolio Code | Specifies the Portfolio of the loan. The Portfolio is a container in which multiple loans and deposits, can be grouped for the purpose of reporting. |
| Portfolio Currency Code | Specifies the currency of the selected Portfolio, also called Portfolio Currency (PCY). |
| Description | Specifies the description of the loan. |
| Counterparty Type | Specifies the system module through which the Loan will be managed. |
| Counterparty Account | Specifies the sub-ledger account against which the accounting entries will be booked. |
| Value Date | Specifies the value date of the loan at which the initial disbursement will be made, as well as the starting date of the payment schedule calculation. |
| Maturity Date | Specifies the maturity date of the loan. |
| Duration | Specifies the number of days between the value date and the maturity date. |
| Loan Currency Code (ICY) | Specifies the currency of the Loan. It is defaulted to the Counterparty Account Currency. |
| Loan Amount (ICY) | Specifies the initial loan disbursement amount, in Loan Currency. |
| Rate Type | Specifies if the loan interest is calculated using a fixed rate or a variable rate. |
| Rate | specifies the fixed component of the loan interest rate. |
| Rate Base | Specifies the base name in the case of a floating interest rate loan. |
| Starting Date Repayment | Specifies the first repayment date of the loan, when the Postpone option is used. |
| Period | Specifies the payment frequency of the loan. |
| Postponement Type | Specifies in which way the loan should be postponed. |
| Instrument Type | Specifies the accounting rules of the loan, to link business transactions made for the loan with the appropriate account in the general ledger. |
| Lending | Specifies if the loan is a Lending or a Borrowing. If this field is enabled, the Loan will be posted as a lending, otherwise it will be a borrowing. |
| Renewed | Specifies if the loan has been involved in a loan renewal. |
| Renew With Interest | Specifies the value of the Renew With Interest field. |
| Closed | Specifies if the Loan is closed. |
| Renewed by Loan No. | Specifies the Loan number with which the current loan has been renewed. |
| Market Calendar Code | Specifies a calendar which can be configured to prevent posting a transaction on a non-working day. |
| Bundled Loan No. | Specifies the Bundled Loan number the current loan is part of. |
| Balloon Payment Date | Specifies the balloon payment date. |
| Cancelled | Specifies if the loan has been cancelled. A loan can be cancelled only once all transactions have been reversed. |
| Include Inception Day | Specifies if the Value Date of the loan is included when calculating the interest. |
| Company Name | Specifies the value of the Company Name field. |

## Actions

| Name | Description |
| ---- | ---- |
| Loan & Deposit Ledger Entries | Executes the Loan & Deposit Ledger Entries action. |
| Interest Ledger Entries | Executes the Interest Ledger Entries action. |
| Bank Account Ledger Entries | Executes the Bank Account Ledger Entries action. |
| Renewed Ledger Entries | Executes the Renewed Ledger Entries action. |
| Accrued Interest Ledger Entries | Executes the Accrued Interest Ledger Entries action. |
| Income Ledger Entries | Executes the Income Ledger Entries action. |
| Disbursements | Executes the Disbursements action. |
| Fees | Executes the Fees action. |
| Payments Schedule | Executes the Payments Schedule action. |
| Dimensions | Executes the Dimensions action. |
| Customer | Executes the Customer action. |
| Sales Invoice | Executes the Sales Invoice action. |
| Bank Account | Executes the Bank Account action. |
| Renew with Capitalisation of Interest | Executes the Renew with Capitalisation of Interest action. |
| Renew without Capitalisation of Interest | Executes the Renew without Capitalisation of Interest action. |
| Early Repayment | Executes the Early Repayment action. |
| Change Payment Amount | Executes the Change Payment Amount action. |
| Change Maturity Date | Executes the Change Maturity Date action. |
| Capitalise Interest | Executes the Capitalise Interest action. |
| Cancel Loan | Executes the Cancel Loan action. |
| Loan & Deposit Journal | Executes the Loan & Deposit Journal action. |
| Accrued Interest Journal | Executes the Accrued Interest Journal action. |
| Loan & Deposit Revaluation | Executes the Loan & Deposit Revaluation action. |
| Loan & Deposit IFRS Year End Closing | Executes the Loan & Deposit IFRS Year End Closing action. |
| Loan Statement | Executes the Loan Statement action. |
| Simulation | Executes the Simulation action. |
| Interest Rates | Executes the Interest Rates action. |
| Calendar | Executes the Calendar action. |
| View Pledge | Executes the View Pledge action. |
