# Rate Groups

## Rate Groups

Rate groups are groupings of different rates that use the same cancellation fees. Rate groups help to improve user experience by automatically displaying the lowest available rate, which allows customers to easily select the best price when booking.

To create, manage, and delete rate groups, navigate to the rate groups page using the following path:

* **`Main menu > Setting > Services > Stay > Rate groups`**

### Create

To create a new rate group, look for the `+ icon`, click on it, and complete the following fields:

* **Name** - Enter a name for the rate group \(for example, "Non-Refundable"\).
* **Settlement** - Select your property's preferred method of settlement.
  * **Automatic** - The system automatically settles payments.
  * **Manual** - Employees must manually process and settle payments.
* **Settlement action** - Select the desired action at the time of the settlement trigger. Please note that settlement action only applies to automatic settlements.
  * **Charge credit card** - Card on file will be charged at the time of settlement trigger, including any applicable offset.
  * **Create preauthorization** - Preauthorization will be created for the card on file at the time of settlement trigger, including any applicable offset. However, the card will not be charged until manually processed by an employee.
* **Settlement trigger** - Select the time when the system should automatically charge accommodation cost. Please note that this field only applies to automatic settlements.
  * **Creation** - Time that booking is created.
  * **End** - Date and time of customer's departure.
  * **End date** - Date of departure at 00:00.
  * **Start** - Date and time of customer's arrival.
  * **Start date** - Date of arrival at 00:00.
* **Settlement offset** - Amount of time either subtracted from or added to the settlement trigger time, with negative values subtracting time and positive values adding time. Please note that `Settlement offset` only applies to automatic settlements. 
* **Settlement value** - Percentage of the total booking value that will be charged at the time of `Settlement trigger` \(including `Offset`\). Please note that `Settlement value` only applies to automatic settlements. This value can be greater than 100% in the case that you would like to automatically create preauthorizations including an extra charge in case of damages. The property can then charge a lower amount than is preauthorized at the time of checkout, but cannot charge higher. 
* **Maximum nights for settlement** - Select the maximum number of nights that should be charged automatically as part of automatic settlements. This value will apply only to rate groups with automatic settlements enabled. 
* **Extent** - Choose which items should be included as part of automatic settlements. 
  * **Additional expenses** - Include any additional items applied to cost of stay \(i.e. extra fees, deposits, etc.\)
  * **Nights** - Include cost for all nights; this field is limited by the `Maximum nights for settlement` field
  * **Products** - Include cost of all stay products \(i.e. Breakfast, Parking, etc.\)
* **Options**
  * **Automatic deposit settlement** - Select this option to automatically post deposits to customer bills. Please note that this feature creates deposits based on your legal environment, so it can be activated regardless of whether you are required to pay VAT at the time of payment or the time of consumption..
* **Short name** - An abbreviated label for this rate group, which is used for reference where space may be limited.
* **Description** - A short description of this rate group to display to customers while booking. This space could include cancellation policies or any other further information. 
* **Ordering** - To organize your rate groups in a specific way, use this field to specify the correct order display, with lower numbers appearing first and higher numbers appearing last. 

When all information is correctly entered, click the `Create` button.

This rate group was successfully created. You will see three additional items appear:

* **Created \(UTC\)** - Time that rate group was created
* **Updated \(UTC\)** - Time that rate group was most recently updated
* **Cancellation policies** - This link will appear under your rate group settings. For more information, please see our article about [`Cancellation policies`]().

### Delete

To delete a rate group, navigate to the main rate groups page and click on the name of the unwanted rate group. Look for the trashcan icon, click on it, and confirm your deletion.

{% hint style="info" %}
### Mews Clues

Please note that once a rate group is deleted, this action cannot be undone. If you have mistakenly deleted a rate group, you must completely recreate it.
{% endhint %}

## Cancellation Policies

The system calculates which cancellation conditions should be charged to guests based on the time of the cancellation. Let’s say you have a rate with a cancellation policy of 24 hours prior to arrival. The system knows that your check-in time is 15:00, so if you cancel the reservation at 14:59 the day prior, it knows not to charge any fee. If it were one minute later, however, it would correctly post cancellation fees.

* To set a new cancellation condition, select the + button for "New Cancellation Policy" in the "Options" section of rates. You can select for the specific rate type how many days prior the guest is allowed to cancel free of charge. If the guest cannot cancel, then leave this field black.
* Applicability:
  * Creation: cancellation policy is applied from the moment of creation \(for non refundable rates\)
  * Start: cancellation policy is applied from the start time of the booking
  * Start Date: cancellation policy is applied from the start of the day of arrival \(midnight\)
* Applicability offset: if you would like to set an offset versus the applicability time. For example if you would like the cancellation policy to apply 1 day before the arrival, you would set this field up with "-1 Days".
* Absolute Fee : If you want to charge a fixed cancellation fee, put the amount in this field.
* Currency: in which currency would you wish the absolute fee to be charged?
* Relative fee: If you want to charge a percentage, complete the field here.
* Cancellation Fee Maximum Nights: This is an important field that requires careful attention. If you complete it with the number “1”, it will charge 1 night cancellation fee \(adjusted by the cancellation fee percentage\). If you complete it with “0”, it will not charge any cancellation fee. If you leave the field blank, it will charge the reservation fully, adjusted by the cancellation percentage.
* Fee extent: to which parts of the booking would you like to apply the cancellation fee, to the complete value, or only the nights?

### Examples of Cancellation Policies

*  Fully Flexible / BAR: If you set a rate with a cancellation condition to allow cancellations up to 24 hours prior to arrival \(24 hours prior to the official check-in time set in the system\) and you cancel a booking within the 24 hours, it will automatically post the cancellation charge \(at 0% VAT\) and remove the stay charges.
*  You should only close bills on the day of check-out, because if you close a bill before check-out and try to shorten the reservation or cancel it, the system will attempt to correct the charges on the closed bill \(as they were posted at the wrong VAT level\). This may result in new charges \(cancellation charges\) being posted on the bill.
*  If you try to cancel a bill "Without Fee” but have already closed the bill, then the system will post refunds automatically on the bill.

