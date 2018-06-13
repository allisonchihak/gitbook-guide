# Reservation Module

The Reservation Module is a split screen, utilizing the left and right sides for different reasons. Above this split screen, there is a header including eight different tabs.

At any given time, only one highlighted tab is visible in the left side of the split screen. The left side is used to edit or update booking details.

On the right side, you can see reservation details and select bookings that you'd like to edit. Select multiple bookings at a time to manage them simultaneously or click on each line hide or expand individual details.

## Selection

Before you begin to edit reservations, it is important to take note of which bookings you may be editing. Since Mews is customer-centric, multiple bookings may be connected to the same customer and therefore visible from the Reservation Module.

Booking information will only be displayed for the reservations that are selected on the right-hand side of the `Reservation Module`, and you must select at least one reservation to make changes.

For example, if you've selected only canceled reservations on the right-hand side of the Booking Module, you will not see any information under the 'Rooms' section.

## Header

Within the Reservation Module, you will see the following features on the top bar throughout each individual tab.

* **Lock All** - Lock all bookings so that no one can edit or move them. Lock individual bookings by clicking on the toggle button next to customer name. 
* **Unlock All** - Unlock all bookings to edit details or move. Unlock individual bookings by clicking on the toggle button next to the name on the right-hand side. 
* **Select All** - In case of multiple bookings, use this button to select them all and edit them at once. Select bookings individually using the checkboxes just before customer name. 
* **Deselect All** - In case of multiple bookings, use this button to deselect all the bookings at once. Deselect bookings individually using the checkboxes just before customer name. 
* **Open All** - Expand the booking details of each individual reservation in this group.
* **Close All** - Collapse all details of each individuals booking so reservations appear in one line each
* **+ Reservation** - To [create a new booking](create-a-reservation-nnrs.md) for an already existing group, you can click on this button, which will open the new reservation screen, with a group code pre-filled, once you complete the new booking, it will automatically be added as a part of the same booking.

## Manage

The Reservation Module is split up into the following 8 sub-sections:

{% tabs %}
{% tab title="State" %}
## State

Within the `State` tab, there are many parts of a reservation that you can manage. Below, you will find a detailed description of all functions that are available using the `State`tab of the Reservation Module.

### Customers

At the top of the State screen, under the 'Customers' title, you will see the following items:

* **Passport Scanner Integration** - If you have a passport scanner integration, you will find a "Scan" button next to each guest. Click this button to scan that guest's document and auto-complete the details in their profile.
* **Print Registration Cards** - Click this button to automatically print registration cards for all customers connected with this booking.
* **Customer** - A list of all customers connected with this booking. Click on the customer's name to be taken directly to their customer profile.
* **Balance** - Amount due for each customers assigned to the group; for group bookings you will see the balance of all participants individually and also the balance of the whole group.
* **Total** - Amount due for all items connected with this booking
* **Billing** - Direct link to customer's billing screen to take payments or settle bills; please note that a blue `Billing` button means that there is action required, as there are open bills to be closed. If a balance is set to 0 and the button is blue, that means that the bill is not yet closed.
* **Payments** - Direct link to customer's payments screen to add a payment or preauthorization to the booking. To add a deposit, navigate to the `Items` tab.

### Rooms

The 'Rooms' section contains the following items:

* **Holding** - This section will contain any optional bookings associated with this reservation.
* **Confirmed** - Any confirmed bookings associated with this reservation
* **Canceled** - Any canceled bookings that are associated with this reservation. Please note that once a reservation has been canceled, this action cannot be undone.

Beneath each of these headings, each individual reservation will all appear with the following details:

* **Dates of stay** - Date of arrival - date of departure
* **Customer name** - Name associated with customer's profile
* **Room number button** - Click on this room number to change the assigned room number. You will see a drop-down list of all other rooms at your property organized by room category along with their occupation status, housekeeping status, and room features in parentheses; ; if you have a group with multiple bookings, select them all to assign multiple rooms at once; from the room assignment drop-down, select `None` to move this booking to an overbooking slot, which will cause the button to turn blue and be labeled `Assign`, so that you can assign a room for the reservation later
  * **Housekeeping status badge** - Badge will display the current room status in its appropriate action color
  * **Make inspected** - Click this button to change housekeeping status from any other status to `Inspected`. Rooms must be inspected before any reservation can be checked-in.
  * **Cut key** - If you have a door lock integration set up, this button will appear under the Rooms section. Once you have checked in a booking, you can select `Cut key` to create a key for that room. From the drop-down menu, select the number of keys you would like to create \(for example: if there are two people booked to a single space, you will be presented with the option to create either one or two keys\), as well as the key cutter machine you wish to use. Please note that this button is only clickable after the booking is checked-in.

### Confirmation

Under the Rooms section of the State screen, you will find the 'Confirmation' section. This section will contain

Please note that this section will only be present when only optional reservations are selected for editing. If you have selected any non-optional reservation as well, this section will not be visible.

* **Send confirmation e-mail** - Select this box if you'd like the customer to receive a confirmation e-mail. This e-mail will automatically be sent the moment that you click the `Confirm` button.
* **Confirm** - Please note that this button will not appear if you have selected any non-optional reservations; confirm multiple bookings simultaneously by selecting them all before clicking `Confirm` .

### Cancellation

Cancel reservations in the last section of the 'State' screen, labeled `Cancellation`. If there are multiple connected reservations, you can cancel one reservation individually or select multiple to delete them all at once.

First, you must check that you've selected only the reservations that you'd like to cancel on the right-hand side of the Booking Module. Please note that once a reservation has been canceled, this action cannot be undone.

You will see the following items in this section:

* **Reason** - Please note that this is a required field
  * **Other** - None of these options accurately describe the reason; please note that it is then required to specify the reason in the open-text-field below
  * **Confirmation missed** - Customer has an optional booking, but did not confirm by the release date
  * **Booked elsewhere** - Guest has booked another hotel or destination
  * **Force majeure** - Guest must cancel their stay due to a force majeure event, such as earthquakes, floods, etc.
  * **Guest complaint** - Guest complains and then wants to cancel their order
  * **No show** - Guest did not show up for reservation
  * **Price is too high** - Guest canceled stay due to the high price
  * **Service not available** - Property is fully booked or you cannot accommodate guest for any reason property-related
  * **Input error** - Booking was input by error
  * **Invalid payment** - Payment details provided by the guest were not valid
  * **Travel agency** - Agency cancels and does not provide a further reason
  * **Requested by guest** - Cancellation directly by guest with no further reason provided
* **Details** - Please note that this is a required field
* **Apply Cancellation Fee** - The system will automatically recognize the cancellation policies for each rate type, and will add it as an item on the customer's billing page. For more information, please see the `Cancellation Policies` page.
* **Send e-mail** - Send a cancellation confirmation e-mail to the guest at the moment that you click the `Cancel` button

Finally, when all fields are correct, click the `Cancel` button and look for the green success message.

{% hint style="info" %}
### Mews Clues

* It's very important to select the correct reason for cancellation, as this information is often used for statistics and analysis. You can also describe it in the open-text-field.
* Reservations that are currently in house cannot be canceled. If a guest needs to leave early, you must shorten the reservation and proceed with the checkout process.
* If a reservation must be canceled, you must do this within the [editable history window](https://mews-systems.gitbook.io/guide/mews-commander/settings/finance-settings/accounting-configuration), as you cannot edit reservations outside of this time frame.
{% endhint %}

### Status

In the State screen you are able to manage the current status of the reservation. The system knows the following statuses:

* **Optional** - Booking is not yet confirmed but is blocking availability and space on the timeline. If a booking is still optional, revenue is not yet recorded in any reports. If optional bookings are canceled, no cancellation fees will be charged to the customer. All optional bookings have a release date assigned, indicating the customer's deadline to confirm the booking. On the date of release, the booking will be highlighted in the reservation overview report and the space block will change from grey to orange on the timeline, indicating that urgent action is required. At this time, the property may cancel the booking manually, contact the customer to extend the release date, or leave the booking as it is. Within your [stay settings](https://mews-systems.gitbook.io/guide/mews-commander/settings/sales-settings/services/stay-services), if you have selected to `Enable automatic option cancellation`, the system will automatically release unconfirmed bookings 24 hours past that chosen release date to free up inventory at your property. For optional bookings that have not yet been confirmed, properties can also navigate to their [stay settings](https://mews-systems.gitbook.io/guide/mews-commander/settings/sales-settings/services/stay-services) and select `Enable automatic release reminder e-mail`, which will send a reminder to the customer 24 hours before the release date.
* **Confirmed** - Confirmed reservations are often paid in full at the time of booking. Bookings that are confirmed will display on the timeline and have revenue assigned. If canceled, customers are usually subject to cancellation fees, according to the selected rate type.
* **Canceled** - Canceled bookings will be removed from the timeline, and depending on the rate, they are often subject to cancellation fees according to the selected rate. Waive cancellation fees by unselecting the `Apply cancellation fee` option before clicking `Cancel`
* **Checked-out**: All bookings that have completed their stay will have the status "Checked-Out". Once a booking is checked-out, you can no longer check it back in.
* **Checked-in**: A booking that is currently in-house will be considered "Checked-In"

Please note that the default release date is calculated using the midpoint between reservation creation time and the arrival time. In case of group bookings with multiple arrival times, the system will use the closest start time for calculation. If there is an odd number of days or hours, time will be rounded down.

**Confirmed**

* If a booking is on OPTIONAL state, you can confirm bookings directly from this screen. It will change the status to "Confirmed" and post the revenue on the customer bill. Next to the confirmation box you are also able to send a confirmation to another person who is not assigned to the booking. Type the e-mail in the box and he/she will receive the confirmation e-mail with a summary of all the bookings that are selected.

**Checked In**

* Once you have assigned an inspected room, you can select the button “Check-In.” Note that the check-in button will only appear if you have selected a booking\(s\) that is on arrival today. It will check in all bookings that were selected, allowing you to check-in multiple bookings at the same time. If a booking is due to arrive today, there is also a "print" button next to it, allowing you to instantly print the registration card of the guest, if your country still requires physical signatures on the registration cards.

**Checked Out**

* On the day of departure for the booking\(s\) selected, a new button will appear called "Check-Out.” The system will only allow you to check-out a guest for whom all open bills and unsettled items have been paid with a balance on zero. Should you wish to check-out a customer with an open balance \(as he may pay it later\), select the "Check-Out with Open Bill" and fill in the reason. This room will then be transferred to the Guest Ledger report in red, where the payment will need to be resolved as soon as possible.

### Check-In

Once you have identified the booking, select the “Check In” button on the booking screen. This button only appears on the day of arrival. It will open the "Booking Management" screen in the tab "State" where you can perform the following steps.

1. Verify all booking details with the customer, which includes the arrival and departure date, room-type, rate and number of people. Also inform the guest whether the booking was prepaid or not. Once verified, check with the guest how he/she would like to guarantee payment for the booking and any possible incidental charges.
2. Take preauthorization or deposit from the guest for the amount agreed. Once the money has been accepted, process this in the system by selecting either the “Preauthorization” or “Deposit” button, which will allow you to post the amount directly in the system.
3. Check that the pre-assigned room is inspected. If it is not, check if there is another room of the same type that is available and inspected. This can be spotted quickly from the dropdown menu. If no room is available ensure you assign an available \(dirty or clean\) room and contact housekeeping to get the room cleaned.
4. Once an inspected room is assigned, you can press “Check-in,” and the room is checked in. It will be locked, so that it cannot be moved in the system.

### Group Check-In

If you have multiple bookings that are part of the same group, you can navigate to the `State` tab and select all eligible bookings on the right side and then click on the `Check in` button to check them in simultaneously.

> #### Mews Clues {#mews-clues-1}
>
> Please note that it is not possible to undo check-in outside of the editable history window
>
> Please note that if you send your confirmation to custom e-mail, the link to check-in online will not allow the possibly different person to get into profile of the reservation owner. The e-mail will contain a link to sign-in screen of navigator. As a solution, please be sure that guests use their primary e-mail address on their customer profile and not sending it to custom e-mail addresses.

### Continuing

Checking in a continuing reservation can be quite challenging.

* First, you will want to ensure that the same room number has been allocated for the continuing booking, so that the guest will not be required to move. Ensure that this is done at the booking stage, as it may be harder to move bookings around on the day of arrival. Always lock your booking, so that no one can move the room.
* Check-out the current booking. The booking that is currently checked-in will have to be checked out. You can check it out by ticking the box "Check Out with Open Balance,” and it will leave the charges unpaid on the guest profile.
* Lastly, you can check in the new reservation, and once this is done, you will see that all the charges from the first booking are automatically transferred to this bill.

### Check-Out

Once you have identified the booking, select the “Check Out” button on the booking screen. This button only appears on the booking on the day of departure or for bookings with a missed departure.

In case of error, users can undo checkout within your property's editable history window. Navigate to the `State` tab of the Reservation Module, look for the `Undo checkout` section, enter a reason and click the `Undo` button to complete checkout later.

### Balances

If the balance is zero, you can immediately check-out the reservation by clicking the “Check Out” button, and the customer is ready to leave. If the balance is not zero, click on the billing button, and you will be taken to the payment screen. To understand how to settle the balance, please refer to the section “Payment Screen” in this manual. Once the balance is settled, you can return to the check-out screen and check the room out.

Note if you need to check out a guest even though they have not yet settled the bill \(for example for a continue-ing booking\) this is possible, Next to the "Check-out" button, simply click "Check-out with Open Bill", provide a reason, and the reservation will be checked out. The bill will appear in the Guest Ledger, so that you can follow up on the payment.

Once the room is checked-out in the system, it will automatically turn "dirty" in the system so that housekeeping is informed that it requires cleaning.
{% endtab %}

{% tab title="Properties" %}
## Properties

### Arrival & Departure

Before you start editing booking details, please be sure to select only the reservations you wish to amend. Note that if you select multiple bookings with the same arrival and departure dates, the system will pre-fill the date fields with the correct dates. If you select bookings with different dates, it will not be able to pre-fill these fields.

If you are extending a booking with additional nights, there is no need to tick the box "Cancel without Fee" as this button is not applicable for extensions.

This section contains the following items:

* **Arrival** - Date and time selection for time of arrival
* **Departure** - Date and time selection for time of departure

To change either of these details, navigate to this `Properties` tab of the Reservation module and select the correct date or time from these date and timepicker fields. When you have correctly selected the amended date or time, click `OK` and you should see a green success message that the interval of the booking was successfully changed.

If you do change any reservation details, you may want to re-send a confirmation e-mail to the customer to be sure that everyone is properly informed of the booking change.

### Segment

You can select whether the Business Segment of the booking. The hotel can set up different business segments themselves in the configuration \(under the rates section in "services"\).

### Origin

Select the source of business for further statistics and analysis.

* **Walk-in** - Customer physically walked into the property to make booking
* **Channel** - Manually created reservations received via a third party channel \(e.g. OTA, Travel Agencies, etc.\)
* **Telephone** - Booked manually over the telephone
* **E-mail** - Booked manually via e-mail to the property
* **Website** - Booked manually via the property's website
* **Message** - Booked manually by sending a message to the property

### Room Category

If you would like to change the booked room category to a higher or lower category in the system, you can select the new room category here. When you make this change, you need to decide whether you would like to keep the old price or whether you would like the system to re-price it against the pricing set in the system \(for those specific dates and the new room type\).

### Adults & Children

If the occupancy of the room has changed, you can select here the new number of people occupying the room. If you tick the box "Keep Old Price," it will keep the base price the same. Please note that the only thing the system will add or subtract is the cost of the per-person-per-night items within the booking \(such as breakfast cost\).

### Company

If you wish to add an existing company to a booking, this will allow you to track the company production in reports. It also opens up the possibility in billing to open a bill to the company name/address.

### Travel Agency

If you wish to add an existing travel agent to the booking, this will allow you to track the travel agent production in reports. It also opens up the possibility in the billing to open a bill to the travel agent/address.

{% hint style="info" %}
### Mews Clues

If you'd like to remove a Company or Travel Agency from a reservation, simply leave the field blank and click the `OK` button next to the Company or Travel Agency. After clicking `OK`, you should see that information leave the simple detail summary on the right-hand side of the properties screen.
{% endhint %}

### Notes

Here you can add or update notes on a booking. To add a new note, write your message in the box and click `OK`. Your note will be saved and labeled with the time of its creation, and a new box will appear to add another note, if necessary. Every time you create a note, a new empty box will appear, meaning you can have multiple notes attached to one booking. 

Please note that if you select multiple bookings and the existing notes are different, it will not be able to display any notes \(the `Notes` box will be empty\).[  
](https://mews-systems.gitbook.io/guide/mews-commander/reservations/reservation-module/rm-state)
{% endtab %}

{% tab title="Group" %}
## Group

### Group Name

Assign a group name to the booking, enabling you to quickly \(through the search box\) find all bookings related to the group name. Each booking is automatically assigned a group name which is constructed from the arrival date and the guest name. Note that group names should not contain spaces, allowing you to search for groups via the search box.

### Merge Group

If you wish to add reservations to an existing group, you can use this option.

* Step 1: Make the additional bookings manually.
* Step 2: Assign the new booking\(s\) the same group name.
* Step 3: Merge the groups.

### Add an Existing Customer

If you would like to manage the customers staying in the physical room, you can assign a customer with an existing customer profile. Type his name to find the profile and add it to the booking.

### Add a New Customer

If the customer you are trying to add to the booking does not have an existing profile in the system, you can quickly generate a new profile. The only required detail is the last name of the customer. Once you have added a customer to the booking, in the booking details you will see a list of all customers assigned to the booking. You have to always ensure that 1 customer is made the owner of the booking because this will ensure that there is 1 main person displayed on the timeline and in the arrivals report. For example, if a room is booked for 2 persons, and you are trying to assign a 3rd person to this room, the system will not allow it. You have to press the "&lt;" arrow to move 1 person out of the booking into the list of "Unassigned Companions.”

Note: all companions assigned to the group \(even if they are in the "unassigned companions" section\) will be connected, and if you enter the bill of one of the group members, you will be able to see all items on the group bill for all companions of the group. To remove a member from a group, press the "X" next to their name, and they will be removed from the group and group-billing details.
{% endtab %}

{% tab title="Pricing" %}
## Pricing

### Rate

When you select this box, it will offer you all available rate types in the system, and you can change the rate type \(which will impact the cancellation conditions on the booking\). It will also automatically recalculate the value of the booking based on the new rate type assigned. If you wish to keep the same rate value, tick the box "Keep Old Rate"

### Set Average Night Cost

If you wish to amend the average night rate, type the new value and select the currency.

All rate changes require a reason to be completed in order to notify management of the change.

### Relative Adjustment

To give a relative discount, type the discount percentage and complete the reason for the discount. Note that as this is a relative adjustment field, in order to give a discount, you have to make the amount negative, for example a 10% discount should be input as -10%.

### Per Night Pricing

First select the currency of the rate. Secondly for each night of the accommodation you can set a custom price that you have negotiated. In the last box, provide a reason for the reprice. Note that you cannot set a price that is negative. If you set the price to a value below the value of the products, it will set the value of the products \(such as breakfast, etc\) to 0.[  
](https://mews-systems.gitbook.io/guide/mews-commander/reservations/reservation-module/rm-group)
{% endtab %}

{% tab title="Items" %}
## Items

In this tab you will see a list of all the items that have been ordered by or for the guest related to the booking. First you will see the accommodation nights. Secondly you will see a list of product orders \(such as breakfast, parking, etc.\). You can select each posted product to see more details about the creator, time of creation, etc. If the product has not yet been consumed, you will still be able to cancel the item from the bill.

### Nights

You can quickly see each accommodation night and its value. But more importantly you can see on whose bill the accommodation was posted, so when you move the accommodation to someone elses bill, this is a quick way to find out where it was moved to.

### Additional Expenses

When the booking is cancelled and you post cancellation fees, you can quickly see that in this overview

### New Deposit

This is a feature that is specifically for hotels that operate in a country where tax is paid when money is received, not when revenue is consumed \(for example Czech Republic, Germany, Denmark\). This feature allows for a correct taxation of the revenue. For example:

1. A non-refundable booking is made for next month
2. You take payment today \(as its non-refundable\), which means you should pay VAT also today. However as teh revenue is only posted next month, we have built a 3rd step.
3. You select the deposit option, which allows you to post a deposit \(revenue correction\). You can select the amount you would like to post, and the currency and VAT. Once posted, the system posts 1 revevenue item called "deposit" which should be closed against the payment you received today, allowing you to close the bill of these 2 items. The system will also post a second "deposit" item \(with a consumption date, one month from today\) which will balance out the future accommodation revenue and set the bill balance to 0, this bill should be closed on the day of departure.

### Product Orders

An overview of all the products that are linked to the accommodation part of the booking \(such as city tax, breakfast, etc\). If you are handling a future stay, you are able to quickly cancel products from the booking, by pressing "cancel".

### Add Product

If you made a booking and you forgot to include a product \(such as city tax/breakast\) you can quickly select the product and add it. Note that when you add a product, it will increase the total price of the accommodation.[  
](https://mews-systems.gitbook.io/guide/mews-commander/reservations/reservation-module/rm-pricing)
{% endtab %}

{% tab title="Mailing" %}
## Mailing

You can access the Reservation Module by clicking `Manage` button within the `Simple detail` for any reservation.

From the `Mailing` tab of the Reservation Module, you are able to manually re-send e-mails to your customers. All e-mails will be sent to the customer's registered e-mail address by default, or you can choose to send them to a custom e-mail address instead.

### Resend E-Mail

Depending on the current state of the reservation, you can resend the following types of e-mail:

* **Cancellation** - If the booking is cancelled, you can send the customer a confirmation of his/her cancellation
* **Confirmation** - Resend a confirmation e-mail including all booking details
* **Quotation** - Available only for optional bookings, this e-mail includes a price quotation, booking details, and release date.
* **Invitation to online check-in** - If you would like the customer to fill in their credit card details, this e-mail will confirm booking details and will include a link where they can check in online.
* **Release date reminder** - If an optional booking is close to its release date, you can manually trigger an e-mail that will prompt them to confirm their booking before that date.
* **After start e-mail** - Resend a welcome message to your guests after they have arrived and completed check-in

Below, you will see two additional fields that are optional to complete:

* **Language** - It is possible to send an e-mail in multiple languages, but it's important that you have created templates for each language that you would like to have available. If this field is not specified, the system will send the e-mail in the Default property language. If your default property language is not determined and there are no e-mail templates available, the e-mail will be sent in English by default.
* **Custom e-mail** - Use this field to specify an e-mail address that is different from the address listed in the customer's profile. This field is optional, and by default, all e-mails will be sent to the primary e-mail address of the customer.

{% hint style="info" %}
### Mews Clues

Please note that all e-mails will only be resent to the owner of the reservation. If you would like to resend e-mails to any companions on the booking, you must manually enter their e-mail addresses in the `Custom e-mail` field.
{% endhint %}
{% endtab %}

{% tab title="Action Log" %}
## Action Log

The Action Log is an overview of all changes made to a booking since its creation. It provides details about the person, time, date, and specific change.
{% endtab %}

{% tab title="Summary" %}
## Summary

### Overview

This first section includes a table with a per night view of the amount and types of spaces booked by the customer. Each line displays the following items:

* Date
* Guest count per room category
* Total spaces
* Total persons

### Room List

To see a complete list of customers and the room which they are assigned to, this is a great report to print. Each line displays the following items:

* Room number
* Customer
  * Profile icon
  * Billing icon
{% endtab %}
{% endtabs %}

## Summaries

The right-hand side contains the expandable and collapsible [reservation simple detail](simple-detail.md).

If you have a group booking you will see multiple customer names on the right, listed under the dates of their stay. Click on reservation lines by name to open up the details of each booking.

If selected bookings contain the same details, those fields will be pre-filled on the left-hand side. If information is different, fields will appear to be blank until one is deselected.

Each collapsible reservation title includes the following information:

* **Checkbox** - Select this box to edit a booking; if no booking is selected, the tabs will not appear on the left-hand side
* **Guest count** - Number of guests will be displayed in `number` x `profile icon` format
* **Customer profile icon** - Link directly to the guest profile
* **Billing icon** - Link directly to the [customer profile billing screen](../profiles/customer-profile/billing/)
* **Timeline icon** - Link to view this booking on the timeline
* **Credit card icon** - Link directly to the [customer profile payments screen](../profiles/customer-profile/payments/)
* **Customer name** - Name of guest who made the original booking
* **Assigned room** - Room number assigned to reservation
* **Requested category** - Space category of the original booking
* **Status of booking** - Labeled in brackets with the current status

