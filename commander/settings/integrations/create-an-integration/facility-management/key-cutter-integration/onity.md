# Onity

Connecting key encoders to Mews is a great way to cut down on check-in time and simplify processes, allowing properties to send commands directly from Mews Commander to your key encoding devices without having to operate a separate Onity application.

 Should you be interested in integrating Onity key encoders with your Mews PMS, please contact [integrations@mewssystems.com](mailto:integrations@mewssystems.com).

## Mews Connector

If you have not yet done so, please see our article about [Mews Connector](https://mews-systems.gitbooks.io/commander-guide/content/settings/integrations/create-an-integration/facility-management/mews-connector.html) and follow those instructions before returning to this article.

If you have already installed Mews Connector, please proceed with the instructions below.

## Integration

To create a new key cutter integration, navigate to the Integrations screen using the following path:

* **`Main Menu > Settings > Integrations`**

Look for the `+` icon and click it. Next, in the **Facility management** section, click **key cutter integration**, and complete the following fields:

* **Name** - Onity
* **API URL** - This field consists of three parts. You can use the image just below for reference:
  * Add `http://`
  * Following this, enter the local IP address of the computer where the Onity Interface System \(Client & Server\) application is running. For more information about finding your local IP address, [click here](https://support.microsoft.com/en-us/help/15291/windows-find-pc-ip-address). 
  * Lastly, enter the interface port. In the Onity application, choose **Configuration** &gt; **Station configuration** &gt; **Ethernet** &gt; **Service number**. Be sure to include a `:` between your IP address and interface port. See [here](https://raw.githubusercontent.com/MewsSystems/gitbook-guide/master/assets/Onity1.png) for an example.
  * In your settings, please make sure that `TCP/IP` is enabled.
  * Please note that you should not add any spaces between these three pieces of data. When completed, your API URL will look something like this: `http://127.0.0.1:10003`
* **Username** - Leave this field blank; used only for VisiOnline integration
* **Password** - Leave this field blank; used only for VisiOnline integration
* **Notes** - Add any additional notes or information that you'd like to include

When all information is correctly entered, click `Create` and you will see the following additional fields:

* **Enabled** - Select this box to enable this integration
* **Created \(UTC\)** - Date and time that this integration was created
* **Updated \(UTC\)** - Date and time that integration settings were most recently updated

After selecting the `Enabled` option, don't forget to click `Save`.

## Key Cutters

Look for the **Key cutters** link and click on it. You will automatically be redirected to a second page, where you will finish the setup process.

Click the `+` button, and complete the following fields:

* **Name** - Name each key cutter based on where the device is located or what will be easily understandable for your staff.
* **Identifier** - Navigate to your `Onity Interface System (Server)` application. Click the `Client` tab and copy the number found under the `Address` column, next to the name of your device. See [here](https://raw.githubusercontent.com/MewsSystems/gitbook-guide/master/assets/Onity2.png) for an example.
* **Data JSON** - Complete this field with `{ "Type": "OnityKeyCutter" }`.

When all details are correctly entered, click `Create` and look for the green success message.

Navigate back to the main Key Cutters screen, where you will see a list of active key cutters in your property’s system. Add all key cutters that you would like to implement, using the same steps as described above for each one.

## Key Cutter Mapping

If your room numbers in Mews do not match the room numbers listed in Onity, you will need to set up a key cutter mapping for each space to communicate the name difference between the two systems. If these two sets of data are already matching, you may not need to set up mappings.

To add a key cutter mapping, navigate back to the main Key Cutter Integration screen and look for the **Key cutter mapping** link. Click it to be redirected to a second page, and then click the `+` button. You will see the following fields to complete:

* **Room** - Select from a drop-down menu of all room numbers created in Mews
* **Lock identifier** - Enter the corresponding room number as it is identified in Onity

When both fields are correctly entered, click `Create`. When you navigate back to the main Key Cutter Mapping screen, where you will see a list of all mappings created for your property. Add all mappings that you would like to implement, using the same steps as described above for each one.

Once you have completed all of the steps above, please contact [integrations@mewssystems.com](mailto:integrations@mewssystems.com) and we will activate the key cutters for your integration.

## Cut Keys

If all steps above were correctly completed, you should see two new buttons in the Reservation module, under the **State** tab, after check-in is complete:

* **Cut all keys** - Cut keys for all companions included in the selected bookings.
* **Cut key** - Cut a select number of keys.

If the reservation has not yet been checked in, these buttons will be gray. Once check-in is complete, the button will change to blue, indicating that it is active and you can select the encoder that you’d like to send the key cutting commands to.

After clicking the `Cut keys` button, the selected key cutter should “ping” and the display will indicate which room the key\(s\) is have been cut for.

Keys are valid from the moment of cutting until the checkout time of the reservation. If the guest prolongs their reservation, you will need to update their departure time first, and then cut a new key for those guests.

## Troubleshooting

If you receive an error that Mews cannot communicate to the Onity application, please restart the application and log your issue with Onity.

Should you encounter any issues with the integration, please contact [integrations@mewssystems.com](mailto:integrations@mewssystems.com) for further assistance.

