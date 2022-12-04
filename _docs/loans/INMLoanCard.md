---
title: INM Loan Card
description: 
author: 
ms.service : 
---

# INM Loan Card

## Summary

 ## Fields

## Fields
<!-- You need to leave a space betwenn | your text and | -->

| Name | Description |
| ---- | ---- |
| No. | Specifies the number of the involved entry or record, according to the specified number series. This is the unique identifier of the Loan. |
| Instrument Type | Specifies the accounting rules of the loan, to link business transactions made for the loan with the appropriate account in the general ledger. |
| Description | Specifies the description of the loan. |
| Portfolio Code | Specifies the Portfolio of the loan. The Portfolio is a container in which multiple loans and deposits, can be grouped for the purpose of reporting. |
| Portfolio Currency Code | Specifies the currency of the selected Portfolio, also called Portfolio Currency (PCY). |
| Lending | Specifies if the loan is a Lending or a Borrowing. If this field is enabled, the Loan will be posted as a lending, otherwise it will be a borrowing. |
| Counterparty Type | Specifies the system module through which the Loan will be managed. |
| Counterparty Account | Specifies the sub-ledger account against which the accounting entries will be booked. |
| Loan Currency Code | Specifies the currency of the Loan. It is defaulted to the Counterparty Account Currency. |
| Cash Loan | Specifies if the loan amount should be disbursed to the Customer in cash. |
| Cash Bank Account | Specifies from which current Bank Account the cash should be disbursed to the Customer. |
| Collateral Investment | Specifies an investment which is used as collateral against the loan. |
| Closed | Specifies if the Loan is closed. |
| Renewed | Specifies if the loan has been involved in a loan renewal. |
| Cancelled | Specifies if the loan has been cancelled. A loan can be cancelled only once all transactions have been reversed. |
| Renewed by Loan No. | Specifies the Loan number with which the current loan has been renewed. |
| Renewed Loan No. | Specifies the loan number which the current loan has renewed. |
| Bundled Loan No. | Specifies the Bundled Loan number the current loan is part of. |
| Manually Imported Payment Schedule | Specifies if the loan uses a manual payment schedule. Once the manual payment schedule has been triggered, all loan movements must be managed through the “Import Manual Payment Schedule” page. |
| Issuer | Specifies the loan Issuer. Analytical field. |
| Third-Party Manager | Specifies the loan Third-Party Manager. Analytical field. |
| Particular Manager | Specifies the loan Particular Manager. Analytical field. |
| Restricted Cash | Specifies the loan balance should be considered as Restricted Cash. Analytical field. |
| Enable ST/LT Reallocation | Specifies if the loan is subject to the reallocation of balance between short-term and long-term. To be used with the Loan Reallocation Journal |
| Loan Type | Specifies the type of the loan. The Loan Type defines the payment schedule calculation. |
| Loan Amount (ICY) | Specifies the initial loan disbursement amount, in Loan Currency. |
| Loan Currency Code (ICY) | Specifies the currency of the Loan. It is defaulted to the Counterparty Account Currency. |
| Loan Limit Amount (ICY) | Specifies a limit for the loan which should not be exceeded. |
| Initial Fees (ICY) | System field. |
| Trade Date | Specifies the trade date of the loan. |
| Value Date | Specifies the value date of the loan at which the initial disbursement will be made, as well as the starting date of the payment schedule calculation. |
| Duration (Days) | Specifies the number of days between the value date and the maturity date. |
| Maturity Date | Specifies the maturity date of the loan. |
| Market Calendar Code | Specifies a calendar which can be configured to prevent posting a transaction on a non-working day. |
| Rate Type | Specifies if the loan interest is calculated using a fixed rate or a variable rate. |
| Rate (%) | specifies the fixed component of the loan interest rate. |
| Period | Specifies the payment frequency of the loan. |
| + Base | Specifies the base name in the case of a floating interest rate loan. |
| Payment Amount | Specifies the Total Due Amount in the case of a “Fixed Capital And Interest Repayment” type of loan. |
| Start Date for Payment Amount | Specifies the date starting which the payment amount has been used. |
| Day Count | Specifies the calculation method of the interest amount. |
| Include Inception Day | Specifies if the Value Date of the loan is included when calculating the interest. |
| Or % | System field. |
| Replace Date | Specifies the value of the Replace Date field. |
| New First Payment Date | System field. |
| Rate Calculation Method | System field. |
| Starting Date of Repayment | Specifies the first repayment date of the loan, when the Postpone option is used. |
| Postponement Type | Specifies in which way the loan should be postponed. |
| Balloon Payment Date | Specifies the balloon payment date. |
| Facility Loan | Specifies the principal loan of which the current loan is part of. Used as part of the Facility functionality. |
| Tranche | Specifies the tranche of the current loan. Used as part of the Facility functionality. |
| Lender | Specifies the lender of the Facility. Used as part of the Facility functionality. |
| Merged into Loan No. | Specifies the Facility into which the current loan has been merged. Used as part of the Facility functionality. |
| Premium Day Count | Specifies the calculation method of the premium amount. Used as part of the Facility functionality. |
| Custom Asset Class | Specifies the Custom Asset Class. |
| Custom Sub Class | Specifies the Custom Sub Class. |
| Risk Class | Specifies the Risk Class. |
| Current Team | Specifies the Current Team. |
| Liquidity | Specifies the Liquidity. |
| Bank Exposure | Specifies the Bank Exposure. |
| Industry Sector | Specifies the Industry Sector. |
| Industry Sub-Sector Code | Specifies the Industry Sub-Sector. |
| Market place | Specifies the Market place. |
| Country/Region Code | Specifies the Country/Region. |
| Analytic 1 | Specifies the Analytic 1 field. This is a customizable analytical field. |
| Analytic 2 | Specifies the Analytic 2 field. This is a customizable analytical field. |
| Analytic 3 | Specifies the Analytic 3 field. This is a customizable analytical field. |
| Analytic 4 | Specifies the Analytic 4 field. This is a customizable analytical field. |
| Analytic 5 | Specifies the Analytic 5 field. This is a customizable analytical field. |
| Analytic 6 | Specifies the Analytic 6 field. This is a customizable analytical field. |
| Loan Sub-Type | Specifies the Loan Sub-Type. |
| Underlying Investment | Specified the underlying investment. |
| Investment Description | specified the description of the underlying investment. |
| Quantity | Specifies the Quantity of the underlying investment. |

## Actions

| Name | Description |
| ---- | ---- |
| Disbursements | Insert increases or decreases of capital for the loan. |
| Post Initial Disbursement | Automatically post the initial capital disbursement of the loan. |
| Payments Schedule | View and modify the payment schedule of the loan. |
| Import Manual Payment Schedule | View and modify the manual payment schedule of the loan. |
| Fees | Insert fee transactions for the loan. |
| Calendar | Executes the Calendar action. |
| Interest Rates | Executes the Interest Rates action. |
| Simulation | Executes the Simulation action. |
| Loan Statement | Executes the Loan Statement action. |
| Redemption | Executes the Redemption action. |
| Renew with Capitalisation of Interest | Executes the Renew with Capitalisation of Interest action. |
| Renew without Capitalisation of Interest | Executes the Renew without Capitalisation of Interest action. |
| Close and Extend Loan | Executes the Close and Extend Loan action. |
| Early Repayment | Executes the Early Repayment action. |
| Capitalise Interest | Executes the Capitalise Interest action. |
| Pay Ad hoc Interest | Executes the Pay Ad hoc Interest action. |
| Change Payment Amount | Executes the Change Payment Amount action. |
| Change Maturity Date | Executes the Change Maturity Date action. |
| Cancel Loan | Executes the Cancel Loan action. |
| View Pledge | Executes the View Pledge action. |
| Dimensions | View or edit dimensions, such as area, project, or intercompany, that you can assign to the current loan to further analyse transaction history. |
| Loan & Deposit Journal | Post any capital, interest or fee transaction for the loan. |
| Accrued Interest Journal | Post the accrued interest entries for the loan. |
| Loan & Deposit Revaluation | Post any forex revaluation transactions for the loan. |
| Loan & Deposit IFRS Year End Closing | Post the year-end IFRS entries for the loan. |
| Loan Reallocation Journal | Post the long-term/short-term reallocation entries for the loan. |
| Loan Capitalize Interests Batch | Executes the Loan Capitalize Interests Batch action. |
| Merge Loan | Executes the Merge Loan action. |
| Daily Accrued | Executes the Daily Accrued action. |
| Facility Related Company | Executes the Facility Related Company action. |
| Facility Setup | Executes the Facility Setup action. |
| Collateral | Executes the Collateral action. |
| LP Investment | Executes the LP Investment action. |
| Loan & Deposit Ledger Entries | View the history of disbursements and fees transactions that have been posted for the current loan. |
| Interest Ledger Entries | View the history of interest transactions that have been posted for the current loan. |
| Accrued Interest Ledger Entries | View the history of accrued interest transactions that have been posted for the current loan. |
| Income Ledger Entries | View the history of realized forex transactions that have been posted for the current loan. |
| Renewed Ledger Entries | View the history of the renewed loans which the current loan is part of. |
| Bank Account | Executes the Bank Account action. |
| Bank Account Ledger Entries | View the history of transactions cash that have been posted for the current loan. |
| Customer | Open the Customer Card linked to the current loan. |
| Customer Ledger Entries | Executes the Customer Ledger Entries action. |
| Sale Invoices | Executes the Sale Invoices action. |
| Posted Sales Invoices | Executes the Posted Sales Invoices action. |
| Vendor | Open the Vendor Card linked to the current loan. |
| Vendor Ledger Entries | Executes the Vendor Ledger Entries action. |
| Purchase Invoice | Executes the Purchase Invoice action. |
| Purchase Invoice Posted | Executes the Purchase Invoice Posted action. |
