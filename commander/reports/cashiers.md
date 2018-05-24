# Cashiers

## About Cashiers

Cashiers record all cash transactions made in Mews Commander. These include both internal transactions and cash payments on guests' bills. Commander also maintains a full overview of cash income \(money coming in\) and outcome \(money paid out\). Cashiers must be set up in your [`Finance Settings`](https://mews-systems.gitbook.io/guide/commander/settings/finance-settings/cashiers) before your property can handle transactions.

At any point, users can view a current shift overview, including the current balance, which should correspond to the actual real-life balance of the cashier.

All cash transactions are recorded in chronological order. Once completed, transactions are organized into shift overviews. Past transactions can be found at any time by searching for the past shift during which it was completed. Each transaction is also accompanied by a unique receipt.

## Managing Existing Cashiers

To manage your existing cashiers, you can access the Cashier page directly via the Finance section of the Dashboard or using the following path:

* **`Main Menu > Finance > Cashier`**

Here you will find a list of all cashiers set up in your property settings. To manage a cashier, click on the title. Within each cashier page, you can take internal cash transactions, manage shifts, and view previously completed transactions.

## Shift Overview

When you click on the title of a Cashier, you will see an overview of the current shift, with the following details:

* **Currency** - All currencies enabled for this cashier in your Finance Settings
* **Starting balance** - Amount of money in the cashier at the time the shift was opened
* **Income** - Amount of money that was received during the shift
* **Outcome** - Starting balance, plus income, and minus remaining balance. This is the amount of money that should be taken from the cashier and given to the accountants at the end of the shift.
* **Balance** - Amount of money left in the cashier for the start of the next shift

## Transactions

Under the current shift overview, you will also see a list of transactions for that shift. This list will include payments made by customers and petty cash transactions for internal use, e.g. "flowers for reception." You will also find two buttons, labeled `+ Transaction received` and `+ Transaction paid`, for managing your internal, petty cash transactions.

### Transactions Received

To post small incoming cash payments for internal use, click on the `+ Transaction received` button and complete the following fields:

* **Currency** - Select the correct currency of the cash you're receiving from the drop-down list of your property's enabled currencies
* **Value received** - The amount of money that you are receiving
* **Notes** - Enter the reason for the transaction, e.g. "flowers for reception"

When you have completed all fields, click `Save` to post the transaction. It will automatically be added to the current list of transactions for that particular cashier. 

{% hint style="info" %}
### Mews Clues

In order for a transaction to be linked to revenue reports, it must be posted as a cash payment on the Billing Screen of the guests' profile. This ensures that the system will recognize the payment as revenue.

Revenue is evident in the system when you can see two corresponding bill items. The first is the total value of goods, often itemized, and the second is a negative value representing what was paid. These two can be found alongside one another on an open bill and the balance of both items adds up to a value of $0 when a bill is ready to be closed.

If cash is posted directly to the cashier as a transaction received, revenue is not automatically posted against it, so it is therefore considered a simple cash exchange, which do not impact accounting reports.

* **Example 1:** If an employee is sent to a shop to buy flowers using money directly from the cashier, it can be entered as a transaction paid and the receipt would be included in the shift overview. In this case only an outgoing payment is posted in the cashier, which will not impact accounting reports.
* **Example 2:** If a customer pays for a minibar item in cash, you must to go to their Guest Profile, post the minibar item on an open bill, and then post the cash as a payment, which will appear as a separate transaction on the open bill. In this scenario, both revenue and the payment are posted and will be included in accounting reports.
{% endhint %}

### Transactions Paid

To post small outgoing cash payments for internal use, click on the `+ Transactions paid` button and complete the following fields:

* **Currency** - Select the correct currency of the cash you're receiving from the drop-down list of your property's enabled currencies
* **Value paid out** - The amount of money that you are paying out; please note that it is not necessary to add a minus sign in front of the value because the system will automatically recognize it as a negative value
* **Notes** - Enter the reason for the transaction, e.g. "flowers for reception"

When you have completed all fields, click `Save` to post the transaction. It will automatically be added to the current list of transactions for that particular cashier.

### Receipts

After creating an incoming or outgoing cash transaction, a receipt with all relevant data will become available for each transaction. If the receipt was created during the current shift, you can access it within that cashier's page by clicking on the transaction number. If the receipt was created during a past shift, you can use the `Past shifts` button to search by date, locate the correct shift, view a list of transactions from that day, and then click on the transaction number to view the receipt.

Each receipt will include the following information:

* **Number** -  An automatically-generated number used for identifying transactions
* **Created** -  Date and time that transaction was created
* **Issuer** -  Employee who created the transaction
* **Value** - Amount of money posted in the transaction
* **Customer** -  Name of the customer who paid or received the transaction value. If it was an internal transaction made by an employee, this column will remain blank.
* **Notes** - If the transaction was associated with a customer, this column will state whether the transaction is a payment or refund. Currency is displayed here as well. Additional notes can be manually added by an employee at the time that the transaction is created.

Click on the `Print` icon to print the receipt if necessary. 

## Opening a Shift

The first time you open a cashier that has recently been set up, it will open with a balance of zero. Typically, you begin a shift with a minimum opening balance to ensure that you have some change in your drawer for customers who don't pay their bill with an exact amount. To set the opening balance at the beginning of a shift, click the `+ Transactions received` button and fill in the following details about the transaction:

* **Currency** - Select the currency you would like to post the transaction in
* **Value received** - Post the amount of money received for the starting balance
* **Notes** - Include a note describing the initial balance setup

After you have clicked `Save`, the transaction will be added to the list of transactions below the shift overview. Once you have set up your starting balance correctly, you can begin using the cashier. 

## Closing a Shift

To close a shift, click on the title of that cashier. At this time, employees should count the money that is physically present in the cashier. This number should match the balance stated in the shift overview. If the balances match, you can click on the `Close shift` button to open a new page. Here, you will find the following details regarding the shift:

* **Base value correction** 
  * **Currency** - A list of currencies the selected cashier is able to accept
  * **Base value \(optional\)** - The amount of money that you would like to leave in the cashier for the beginning of the next shift. You may enter a base value for each currency that your property has chosen to support; however, none are required.
* **Shift overview** 

When you have completed all relevant fields, you can click `Close shift` to be taken to a second screen featuring the following details about the shift:

* **Start** - Date and time that the shift was opened
* **Closed** - Date and time that the shift was closed
* **Closer** - Employee that closed the shift
* **Notes** - Any additional notes or information
* **Shift overview** - This overview will include your updated balance
  * **Currency** - List of each enabled currency for this cashier
  * **Starting balance** - Amount of money in the cashier at the time the shift was opened
  * **Income** - Amount of money that was received during the shift
  * **Outcome** - Starting balance, plus income, and minus remaining balance. This is the amount of money that should be taken from the cashier and given to the accountants at the end of the shift.
  * **Balance** - Amount of money left in the cashier for the start of the next shift
* **Transactions** - A list of each transaction that occurred throughout the shift, including base value corrections. For more information, see transactions.

## Reviewing Past Shifts

You can review a past shift by navigating to Cashier page, selecting the cashier you wish to review, and selecting the `Pasts shift` button. Here you will see an overview of every past shift over the last week. To review a shift from further in the past, use the filter options to select the date range you would like to search within and click `OK`.

Each shift listed features the following details:

* **Start** - Date and time that the shift started
* **Closed** - Date and time that the shift was closed
* **Closer** - Employee that closed the shift
* **Notes** - Any additional notes or information
* **Balance per currency** - Starting balance minus the remaining balance of that shift for each supported currency

Click on a shift to view more details or reprint a shift report.

