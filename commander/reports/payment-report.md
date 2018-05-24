# Payment Report

The Payment Report gives an overview of all the payments and rebates made in the selected time period.

## Filters

* **States** - this is important for hotels with the Merchant, where we capture the different stages that payments go through during their cycle.
  * **Cancelled** - to see payments that were cancelled
  * **Charged** - to see payments that were charged, but not yet settled \(Merchant\)
  * **Failed** - to see payments that failed to charge \(Merchant\)
  * **Pending** - to see payments where a charge attempt was made, but its still pending approval from the bank
  * **Settled** - the payment was settled by the Merchant to the bank account of the hotel/hostel.
* **Type**
  * **Payments** - 
  * **Refunds** - 
* **Filter** - you can filter out the types of payments that you would like to display in the report
  * **Cash payments** - All cash payments taken in the selected time period. Please note that payments listed are not necessarily on closed bills, as some payments may have been taken as deposits prior to bill closure.
  * **Terminal CC payments** - Payments made and posted manually via external payment terminal. Once such a manual transaction is made, the employee will need to manually post this transaction in the system as a "Terminal Payment"
  * **Gateway CC payments** - Payments made via the Mews Merchant or through an Adyen account, if you have integrated a payment solution. 
  * **External Payments** - Payments made using any of the external sources that your property has enabled
  * **Invoice payments** - Invoices issued and payments received for a previously issued invoice
  * **Cancelled payments** - Payments that were cancelled before they were settled
  * **Cashier transactions** - Internal transactions made in through your property's cashiers
* **Credit Cards** - 
* **Currency** - 
* **Employee** - 
* **Integration** - here you can select the gateway via which payments were made
* **Charge Currency** - 
* **Mode** - 
  * Cancelled - 
  * Created - 
  * Settled - 
* **Start date & time** - Date and time that report data begins. 
* **End date & time** - Date and time that report data ends.

## Data Features: {#merchantadyenonly}

Features are split into two sections: Payments and Transactions

### Payments

As per the selections that you made under the **'Filter'** option above, payments will be displayed as expandable and collapsable lines, grouped by payment type. Cash payments will be listed with a separate line for each currency. To view the payments made for each type, click the **'+'** button, and you will see each payment item listed with the following details:

* **Customer** - Click on the customer name to be taken directly to [customer profile](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/profiles/customer-profile/customer-profile-sections/profile.md).
* **Created** - Date and time that payment was made, plus employee who created the transaction
* **Bill** - Click on this bill number to be taken directly to the [closed document](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/profiles/customer-profile/customer-profile-sections/billing/close-a-bill.md).
* **Credit Card** - For card payments, card type and last 4 digits will be listed here
* **Identifier** - Unique identifier provided by the payment integration
* **State** - States as described above will be visible here. You can hover over the state badge for more information. This field is only applicable to Gateway card payments 
* **Payment** - Sum received will be displayed here.
* **Refund** - Sum paid out will be displayed here
* **Value** - Total amount either given or received
* **Totals** - Sums of each column converted into default currency

Please note that payment and refund fields should not be used together, so either one or the other should be filled in, with the other left blank.

### Transactions

This sections includes details regarding all cash payments made within the specified time frame, including all currencies. Each cash transaction is listed with the following details:

* **Cashier** - Name of cashier used for transaction
* **Number** - Transaction number, generated by Mews
* **Customer** - Name of customer who made the payment
* **Created** - Date and time that payment was made
* **Bill** - Click on this bill number to be taken directly to the [closed document](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/profiles/customer-profile/customer-profile-sections/billing/close-a-bill.md).
* **Notes** - This will list the type of payment, including currency and any additionally added notes
* **Value** - Total amount received or paid, including currency symbols

### Mews Clues:

* Mews would recommend that each employee posting payments should print the report at the end of their shift by choosing their name from the **'Employee'** filter. Employees should ensure they have the proper backup, receipts, and bill copies for each single payment taken. These should be double-checked and countersigned by another team member. Once complete, we recommend these be handed over to the accounting department.
* As part of the report, you see a column, which is highlighting the "rebates", which is important to keep record of, since your accounting team may need to approve all refunds given. At the top of the report, you can select to see only refunds using the **'Type'** filter.
