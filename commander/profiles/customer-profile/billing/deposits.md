# Deposits

In a number of European countries, there are different rules on when you have to pay VAT. For example, in the Czech Republic, Denmark, and Austria, VAT should be paid at the time that the payment is taken \(not when the service is consumed\). For that reason, we have created a feature where you can make a payment with a today’s date to pay VAT correctly, and then make future corrections.

## Create

To create a new deposit, find the correct booking and navigate to the [`Items` ](https://mews-systems.gitbook.io/guide/commander/reservations/reservation-module#items)tab. Under the `Additional expenses` section, find the `New deposit` button and click on it.

Complete the following fields:

* **Currency** - Choose the correct currency of the payment
* **Price** - Select the value of the deposit, excluding currency symbols. The system will automatically set this value to 100% of the reservation cost.
* **Tax rate** - Select the correct tax rate 
* **Issue invoice** - Select this option if you'd like this deposit to be invoiced. It will take you directly to be [reviewed and closed](https://mews-systems.gitbook.io/guide/commander/profiles/customer-profile/billing/review-and-close). Once closed, it will appear under Unpaid items as a 'Receivable invoice payment'.
* **Notes** - Add any additional notes that you wish to include

Once you click `Create`, the [`Billing` ](https://mews-systems.gitbook.io/guide/commander/profiles/customer-profile#billing)tab will open, and in the [`Open Bills`](https://mews-systems.gitbook.io/guide/commander/profiles/customer-profile/billing/open-bills) section you will see the deposit item that you have just created. Click on the stay line to expand items and view the deposit.

The deposit will appear as two items, one positive value and one negative value to create a balance of zero. When you close the bill, the deposit \(positive value\) will be reported as revenue and the negative value will remain under the unpaid items so that it will be balanced again to zero against the payment form, which will appear as a separate item on the bill.

{% hint style="info" %}
### Mews Clues

Please note that if a customer has paid a deposit and later cancelled their reservation, the negative deposit consumption time will be changed to the same time as their cancellation.
{% endhint %}

## Display

As an optional feature, properties can choose how they'd like their deposits to be displayed on bills. Navigate to your `Accounting configuration` using the following path:

* **`Main Menu > Settings > Property > Finance > Accounting configuration`**

Look for `Options` and look for the following item in the drop-down menu:

* **Separate deposits on bill** - Select this option to create a separate section of `Deposits` on all your bills; if selected, `Deposits` will appear between the `Items` and `Payments` sections; if not selected, deposits will appear in the `Items` section.

Please note that this option is not selected by default, and therefore must be manually enabled by an admin.

## Automation

If you use Mews Merchant or direct Adyen integration that is fully set up in the PMS, you can automate deposits and payments.

Navigate to [Rate Groups](https://mews-systems.gitbook.io/guide/commander/settings/sales-settings/services/stay-services/rate-groups) screen using the following path:

* **`Settings > Services > Stay > Rate groups`**

Select a rate group by clicking on its name, or [create a new one](https://mews-systems.gitbook.io/guide/commander/settings/sales-settings/services/stay-services/rate-groups#create).

Under the `Options` drop-down, select the box next to `Automatic deposit settlement` and `Save`.

Select this option if you would like to settle deposits automatically when reservations for that rate group come in. In this case, the guest’s credit card will be charged and a deposit will be posted on the guest’s [Billing ](https://mews-systems.gitbook.io/guide/commander/profiles/customer-profile#billing)screen.

