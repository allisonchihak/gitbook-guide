# Deposits

In each country, there is a different set of rules when it comes to paying VAT. Whether your legal environment requires that you pay VAT at the time a payment is received or at the time of consumption, deposits allow you to post a payment according to your country's tax requirements.

## Create

To create a new deposit, find the correct booking and navigate to the [`Items` ](https://mews-systems.gitbook.io/guide/commander/reservations/reservation-module#items)tab. Under the `Additional expenses` section, click the `New deposit` button, and then complete the following fields:

* **Currency** - Select the currency of the payment.
* **Price** - Enter the numeric value of the deposit, excluding currency symbols. The system will automatically set this value to 100% of the reservation cost.
* **Tax rate** - Select the desired tax rate. Please note that if your property's legal environment requires VAT be paid at time of consumption, the tax rate should be 0% for deposits posted before a guest's stay. 
* **Issue invoice** - Select this option if you'd like this deposit to be invoiced. It will take you directly to the Review and Invoice screen. Once closed, it will appear under `Unpaid items` in [Billing](https://mews-systems.gitbook.io/guide/commander/profiles/customer-profile#billing) as a "Receivable invoice payment."
* **Notes** - Add any additional notes that you wish to include.

Once you click `Create`, the [Billing](https://mews-systems.gitbook.io/guide/commander/profiles/customer-profile#billing) tab will open, and in the [`Open Bills`](https://mews-systems.gitbook.io/guide/commander/profiles/customer-profile/billing/open-bills) section you will see the deposit item that you have just created. Click on the "Stay" line to expand items and view the deposit in detail.

The deposit will appear as two items–one positive value and one negative value–to create a balance of zero. When you close the bill, the positive value will be reported as revenue and the negative value will remain under the `Unpaid items` section of the Billing screen, to be balanced against the payment, which will appear as a separate item on the bill.

{% hint style="info" %}
### Mews Clues

Please note that if a customer has paid a deposit, and then cancels their reservation at a later date, the consumption time of the negative deposit will be changed to the same time as when the reservation was canceled.
{% endhint %}

## Display

As an optional feature, properties can choose how they'd like their deposits to be displayed on bills. Navigate to your `Accounting configuration` using the following path:

* **`Main Menu > Settings > Property > Finance > Accounting configuration`**

Find the Options field and select "Separate deposits on bill" from the menu to create a separate section of deposits on all of your bills. If selected, a `Deposits` section will appear in between `Items` and `Payments`; if not selected, deposits will appear in the `Items` section. 

Please note that this option is not selected by default, and therefore must be manually turned on by an administrator.

## Automation

If you use Mews Merchant or a direct Adyen integration that is fully set up in the PMS, you can automate deposits and payments.

Navigate to the [Rate Groups](https://mews-systems.gitbook.io/guide/commander/settings/sales-settings/services/stay-services/rate-groups) screen using the following path:

* **`Settings > Services > Stay > Rate groups`**

Select a rate group by clicking on its name, or [create a new one](https://mews-systems.gitbook.io/guide/commander/settings/sales-settings/services/stay-services/rate-groups#create). In the Options field, select "Automatic deposit settlement" and click `Save`.

Select this option if you would like to settle deposits automatically when reservations for that rate group are created; the guest's credit card will be charged and a deposit will be posted on the guest's [Billing ](https://mews-systems.gitbook.io/guide/commander/profiles/customer-profile#billing)screen.

{% hint style="info" %}
### Mews Clues

Please note that you can turn on "Automatic deposit settlement" even if your legal environment requires VAT be paid at the time of consumption. In these cases, the system will automatically create a deposit with a tax rate of 0%, allowing you to pay VAT at a later date. 
{% endhint %}

