# Rates

## About Rates

Rates are used to define per day pricing for reservations made at your property. As customers create bookings, either via online travel agencies or directly, properties often prefer to offer multiple rate choices. Properties can create up to 100 different rates to offer to customers.

Navigate to the main rates page using the following path:

* **`Main Menu > Services > Stay > Rates`**

This page contains a list of all active rates, organized by their rate groups. Each rate is listed with the following information:

* **Name** - Internal name for this rate
* **Base rate** - Identifies another rate that this rate depends on, if applicable
* **Type** - Public or private
  * **Private** - Rate is visible only to employees
  * **Public** - Rate is visible to anyone
* **External name** - Name displayed to customers
* **Enabled** - Choose to enable or disable your rate
* **Default** - Yes or no; identifies your default rate for booking

From this page, you can create rates, or click on the `Name` of any rate to manage its settings. Below, you'll find a detailed description of how to create and manage your property's rates.

## Create

To create a rate, navigate to the main rates page using the path described above. Look for the `+` button and click on it. Next, you will see the following fields to complete:

* **Service** - Pre-filled with `Stay`
* **Base rate** - This drop-down menu contains all rates available at your property; select a base rate if you'd like to create a dependent rate based off the price of an existing rate; if you're creating an independent rate, leave this field blank
* **Enabled** - To enable this rate, select this box; if the rate is not enabled, guests will not be able to make bookings with this rate
* **Default** - Pre-filled with `No`; to change your default rate, navigate to the main rates page, click on the rate you'd like to make default, and look for the toggle button in the `Detail` tab; the `Rate management` button on the Mews Dashboard will lead you directly to the `Pricing` tab of your selected default rate; Please note that default rate is the base number often used to help calculate other dependent rates, excluding all products or additional fees that you may want to add
* **Type** - Choose who this rate should be visible to
  * **Private** - Rate is visible only to employees
  * **Public** - Rate is visible to anyone
* **Group** - Choose the rate group to which this new rate belongs; for more information, please see our article about `Rate Groups`
* **Accounting category** - Choose the applicable accounting category as per your property's settings
* **Segment** - Apply a standard segment for this rate as per your property's settings; please note that this setting will override any other segment rules in place
* **Name** - Internal name as displayed to your employees
* **Short name** - Abbreviated name used in reports or other places where space is limited
* **Description** - Description will be displayed in Mews Distributor for customers; include any additional details or important information; for example, some properties include cancellation policy information here
* **Ordering** - Choose in which order you'd like your rates to be displayed 
* **External name** - Name of rate displayed to customers while booking via Mews Distributor and in all e-mail confirmations

When these fields are correctly completed, click the `Create` button and you will see these additional fields to complete:

* **Currency** - Choose which currency you'd like this rate to be charged in 
* **Price** - Choose the price per night for this rate
* **Tax rate** - Choose the correct and applicable tax rate; please consult with your accounting team for further assistance 
* **Empty bed adjustment** - If space is not full to capacity, apply a price adjustment for empty space
* **Extra bed adjustment** - If adding an additional bed to accommodate extra guests, apply a price adjustment for exceeding capacity

## Manage

In the Occupancy section of the Dashboard, click **Rates management** to go to the main rates screen, and then click on the `Name` of the rate that you'd like to manage. When you click on the rate, you will be automatically redirected to the first `Detail` tab of the rate. Each rate will have three tabs that you can switch between:

{% tabs %}
{% tab title="Detail" %}
## Detail

The `Detail` tab of a rate is where you can find all original settings and options that were present when the rate was created. In addition to all items that were present at the time of creation, you will see three icons at the top of this window.

* **Make default** - Click on the toggle icon to make this rate your default; the `Rate management` button on the Mews Dashboard will lead you directly to the `Pricing` tab of your selected default rate; please note that you may select only one default rate
* **Action log** - This calendar icon will redirect you to the `Action Log`, where you can view info about changes made in the selected interval
* **Trashcan** - Click on this icon to delete a rate; please note that once a rate is deleted, this action cannot be undone

Within the `Detail` tab are the following fields:

* **Name** - Name this field correctly with its full name, as this is the rate that is visible to the customer directly in the Mews Distributor.
* **Short Name** - Create a short name for all the rates, as this will display better in report columns.
* **Ordering** - This put a numerical order into the list of rates in the earlier "Rates" section.
* **Price** - The base from which all other space types float.
* **Currency** - Ensure that you select the correct currency in the base rate, as this will affect the sales currency of the hotel. Once you have set the base rate, it will update all future dates with this rate. The base rate is the sales rate, inclusive of VAT, but exclusive of products \(such as breakfast\).
* **Tax rate** - Select the appropriate tax rate 
* **Empty Bed Adjustment** - Rooms are sold inclusive of VAT and are assumed to be for the base number of people the room can accommodate in regular beds \(not taking into account extra beds\). If the hotel differentiates its pricing if you, for example, go from double, to single, you can fill in the value with which the rate should drop. Note that in order to lower the rate you have to fill in a negative value \(for example: -10\)
* **Extra Bed Adjustment**: Same as above. The room is assumed to be sold a full capacity of beds, however if you have the possibility to place 1 or more extra beds, in this field you can put the value with how much you would like to charge an extra bed
{% endtab %}

{% tab title="Pricing" %}
## Pricing

The `Pricing` tab is also known as the `Rate Management Screen`.

As you're navigating through this screen, click on any price to manage settings. When you click to edit, the currently selected rate will be highlighted with a black border and you will see setting options appear in a new window.

**Occupancy**: we display the occupancy in this screen, which helps making pricing decisions. Occupancy is always displayed in blue colored boxes, and the darker the box, the busier it gets on that specific date.

**Competition**: we display a number of preset competitors \(data comes from Booking.com, lowest rate available\)

### Base Price {#base-price}

Default rate is the base number often used to help calculate other dependent rates, which excludes all products or additional fees that you may want to add. To set the pricing, there are a number of options

* **Base Price**: click on the value next to the Base Price, this will allow you to set a base price for all eternity. Its really important that you ALWAYS set up a base price, if you do not set this up, you may forget it, and it might send future years to channel managers and booking engines with a 0€ rate.
* **Base adjustments**: next to each room type, you can select the box, which will allow you to set some adjustments based on the base price you set
  * Base adjustment category: would you like to base your pricing on the base price, or maybe another room category? If you make it dependent on another category, then we will hide the rate from the main screen, collapsed into the rate selected.
  * Absolute adjustment: to make a fixed price adjustment from the Base adjustment category
  * Relative adjustment: to make a relative price adjustment from the Base adjustment category
* **Day-by-day pricing**: once you have set the base values, we recommend that you manage your pricing based on the base price, and every time you adjust the base price, all linked room type pricing will follow. However its also possible to manage each room type day-by-day manually by clicking on each individual field and setting the price.
{% endtab %}

{% tab title="Restrictions" %}
## Restrictions

Rate restrictions are used to limit or specify your property's availability. You can create restrictions to require minimum length of stay, set close out dates, or set a minimum number of days for booking in advance.

Navigate to the main rates page using the following path:

* **Main menu &gt; Settings &gt; Services &gt; Stay &gt; Rates**

This page contains a list of all active rates, organized by their rate groups. Each rate has its own separate page for restrictions.

To navigate to the main restrictions page, click on the name of the rate that you'd like to restrict, look for the tab labeled `Restrictions` and click on it. From here, you can create, manage, or delete restrictions.

This page contains a list of all restrictions for the selected rate. Each one is listed with the following information:

* **Restriction type** - Labeled with `Date`, `Earliness`, or `Length` restriction
* **Only for current rate** - Labeled `Yes` or `No`; this indicates whether the restriction applies to only the current base rate, or also to all it's dependent rates
* **Value** - All selected details of the restriction, including minimum or maximum settings, applied intervals, and selected days

Below, you'll find a detailed description of the three different types of restriction in Mews and how to utilize each one.

### Date Restriction

If you would like to create close out dates for a specific rate, you can use a date restriction to specify those terms. For example, you may select dates for a holiday weekend that your property is closed. Please note that date restrictions are used only to prevent bookings in the selected interval.

To create a new date restriction, look for the `+` icon, click on it and select `Date restriction`. You will see the following fields to complete:

* **Start** - Choose a start date for this restriction
* **End** - Choose an end date for this restriction
* **Days** - If applicable, select the days of the week to which this restriction should apply; restriction will be applied if the dates of the reservation is within the start and end dates and if reservation contains any selected days of the week.
* **Only for current rate** - If this is a base rate for any other rates, select this option to apply this restriction only to the mother rate; if you do not select this option, this restriction will apply to all underlying rates

When all information is correctly entered, click the `Create` button and you will be automatically redirected to the main restrictions page.

### Earliness Restriction

Create rates that are only available up to a certain number of nights before arrival. For example, you can set a restriction with a minimum advance of 21 days, which means that the rate will only be bookable starting 21 days before the selected date.

To create a new earliness restriction, look for the `+` icon, click on it and select `Earliness restriction`. You will see the following fields to complete:

* **Start** - Choose a start date for this restriction
* **End** - Choose an end date for this restriction
* **Days** - If applicable, select the days of the week to which this restriction should apply; restriction will be applied if the advance of the reservation is outside of the minimum and maximum number of days and if reservation contains any selected days of the week.
* **Minimum advance** - Select a minimum number of days in advance that this rate should be available
* **Maximum advance** - Select a maximum number of days in advance that this rate should be available; use this field for last minute rates
* **Only for current rate** - If this is a base rate for any other rates, select this option to apply this restriction only to the mother rate; if you do not select this option, this restriction will apply to all underlying rates

When all information is correctly entered, click the `Create` button and you will be automatically redirected to the main restrictions page.

### Length Restriction

Length restrictions allow you to set a minimum or maximum length for bookings. For example, if you set a minimum length of stay as 3 nights, it will only offer this rate to people who select 3 nights or longer.

To create a new length restriction, look for the `+` icon, click on it and select `Length restriction`. You will see the following fields to complete:

* **Start** - Choose a start date for this restriction
* **End** - Choose an end date for this restriction
* **Days** - If applicable, select the days of the week to which this restriction should apply; restriction will be applied if the length of the reservation is outside of the minimum and maximum number of days and if reservation contains any selected days of the week.
* **Minimum length** - Select a minimum number of nights that this rate should apply to
* **Maximum length** - Select a maximum number of nights that this rate should apply to
* **Only for current rate** - If this is a base rate for any other rates, select this option to apply this restriction only to the mother rate; if you do not select this option, this restriction will apply to all underlying rates

When all information is correctly entered, click the `Create` button and you will be automatically redirected to the main restrictions page.

### Delete

To delete a restriction, simply click the `Trashcan` icon next to the unwanted rate and confirm deletion. Look for the green success message and you will automatically be redirected to the main restrictions page for the selected rate.

Please note that once a restriction is deleted, this action cannot be undone. If you decide to reintroduce a restriction, please recreate it using the instructions above.
{% endtab %}
{% endtabs %}

## Best Available \(BAR\)

Your default rate should always be your Best Available Rate \(BAR\). Please note that if you choose this rate to be your default rate, it will act as the base number often used to help calculate other dependent rates, which excludes all products or additional fees that you may want to add:

* **Name**: Name this field correctly with its full name, as this is the rate that is visible to the customer directly in the Mews Distributor.
* **Short Name**: Create a short name for all the rates, as this will display better in report columns.
* **Ordering**: This put a numerical order into the list of rates in the earlier "Rates" section.
* **Price**: which is the base from which all other space types float.
* **Currency**: Ensure that you select the correct currency in the base rate, as this will affect the sales currency of the hotel. Once you have set the base rate, it will update all future dates with this rate. The base rate is the sales rate, inclusive of VAT, but exclusive of products \(such as breakfast\).
* **Tax rate**: select the correct tax rate that applies
* **Empty Bed Adjustment**: Rooms are sold inclusive of VAT and are assumed to be for the base number of people the room can accommodate in regular beds \(not taking into account extra beds\). If the hotel differentiates its pricing if you , for example, go from double, to single, you can fill in the value with which the rate should drop. Note that in order to lower the rate you have to fill in a negative value \(for example: -10\)
* **Extra Bed Adjustment**: Same as above. The room is assumed to be sold a full capacity of beds, however if you have the possibility to place 1 or more extra beds, in this field you can put the value with how much you would like to charge an extra bed

## Dependent \(Floating\)

Once you have set up your "Best Available Rate" in the system, you can create rates that float off this BAR rate at discounted percentages. One such example is a “Non-Refundable Rate,” which, for example, you can set at a 10% discount from the BAR rate. The system will automatically calculate the discount for all room types, saving a lot of work for revenue and reservations managers.

Some examples of rates that can float:

* Non-Refundable Rate
* Advance Purchase Rates: For example, if you wish to give a discount for guests who book 21 days in advance. You must ensure that you set a "New Earliness Restriction" \(see above\).
* Long Stay Rates: For example, if a customer books 7 days or longer, they would receive a 15% discount. You must ensure that you set a "Length Restriction" \(see above\).

## Non-Refundable

1. In the Stay screen, select the "New Rate" button to start creating a new rate.
2. **Base Rate**: Select the rate from which you would like to float a discounted rate. Be very careful with this field. Once you have created a rate floating off another rate, you cannot change it \(and you would have to delete it completely and rebuild it if you did need to change it\). It is recommended to float the rate off the BAR rate.
3. **Type**: If you would like to offer this rate only to specific travel agents or companies or with a special booking code \(for the booking engine\), you need to select "Private" in this box. However if you would like the rate to be publicly available, then select "Public".
4. **Name**: Name this field correctly with its full name, as this is the rate that is visible to the customer directly in the Mews Distributor.
5. **Short Name**: Create a short name for all rates, as this will display better in report columns.
6. Create the rate, and in the next screen, you need to "Enable" it by ticking the box and setting the discount in either a percentage or absolute amount \(in the set currency\)

