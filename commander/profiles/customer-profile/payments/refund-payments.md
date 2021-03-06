# Refund Payments

## About

A refund is money returned to the customer for a payment transaction \(e.g. return of a deposit\), whereas a rebate is money returned to the customer for any non-payment item for any reason \(e.g. correction of minibar bill item\). For more information, see [Rebate Bills](https://mews-systems.gitbook.io/guide/commander/profiles/customer-profile/billing/rebate-bills).

## Refund

To refund a payment, navigate to `Payments` page within the customer's profile, and look for the `Payments` section. Locate the payment that should be refunded, and click on the `More Options` icon to the right of it to open the Actions menu. Click on `Refund` to open a new window with the following information:

* **Currency** - Pre-filled with charged currency
* **Charged** - Pre-filled with charged amount
* **Refundable amount** - Pre-filled with the amount eligible for refund
* **Refund partially** - Select this option if you'd like to refund an amount that is different from the charged amount. 
  * **Amount** - If refunding a different amount, enter that value here without any currency symbols. Please note that this field will only appear when the `Refund partially` option is selected. 
* **Reason** - Enter a reason for refund or any additional notes. Please note that this field is required and cannot be left blank.

When all information is correctly entered, click the `Refund` button and you will automatically be redirected back to the customer profile `Payments` page.

In the payments section, you will see a second item appear just under the first payment. The `State` badge of both the refunded transaction and the second new refund transaction will both be marked as charged. This is because the first transaction was indeed charged, and the second transaction was also charged for a negative value, hence the amount is returned to the customer. Look under the `Type` column for the second transaction, which will be marked as a refund.

{% hint style="info" %}
### Mews Clues

Please note that if a card is within 7 days of the expiration date, it is not possible to refund any payments to that card as it often takes more than that amount of time to fully process refunds through banks.
{% endhint %}

## Partial Refund

Please note that if you refund only part of a transaction, the `Refundable amount` will update so that you are still capable of refunding the rest of the transaction value. In this case, you will see multiple refund transactions appear in the `Payments` section, just underneath the original transaction.

