# Channel Manager Queue

The Channel Manager Queue shows the status of all system updates sent to your channel manager via Mews Commander. To view, navigate to:

* **`Main menu > Queues > Channel manager`**

## Filters

You can filter all channel manager items by:

* **Client** - Select the channel manager that you want to view queue items for.
* **Origin** 
  * **Manual** - Select to view items that were produced manually. 
  * **System** - Select to view items that were produced automatically by the system. 
* **Type** 
  * **Change notification** - Changes made in the system, such as changes to rates or space descriptions.
  * **Inventory push** - Updated rates and availability.
  * **Reservation** - Reservation created in Commander. 
* **State** - Select the state or states of queue items you would like to view.
* **Filter** - To view items that were created or processed within a specific set of dates, select one of the two options below, and then select the start and end dates.
  * **Created**
  * **Processed**
* **Start** - Select a start date to view items created or processed within a specific set of dates.
* **End** - Select an end date to view items created or processed within a specific set of dates.

Select the desired filter options, and click `OK` to view your changes. 

## Data

In the Channel Manager Queue, items are listed with the following details:

* **Type**  
* **Integration** - The connected channel manager integration
* **Enterprise** - The name of the property
* **Origin** 
* **Created \(UTC\)** - The date and time that the item was created
* **Processed \(UTC\)** - The date and time that the item was processed
* **Difference** - The time difference between when the item was created and when it was processed
* **State** 

Click the `More Options` button next to a queue item to open the Actions menu. You can choose from the following actions:

* **Delete** - Select this option to delete the queue item. 
* **Execute** - Select this option to process a failed item again. Selecting this option will change the item's `Failed` badge to a `Pending` badge. 
* **Failed** - This option will appear after you select the "Execute" option. Select to relabel the item as `Failed`.



#### 



