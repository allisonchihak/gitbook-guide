# Setup

## System Requirements

The minimum system requirements for Mews Operator are: 

* **Payment automation** - To use Operator, all rate groups must have automatic settlement enabled. For more information about how to do this in your settings, see [Rate Groups](https://mews-systems.gitbook.io/guide/commander/settings/sales-settings/services/stay-services/rate-groups). Please note that the settlement action can be set to either "Charge credit card" or "Create preauthorization" for Operator.
* **Door lock integration** - Each individual Operator kiosk must have a key cutter machine connected to it for completing check-ins, which requires a door lock integration be set up for your property. If your property does not already have this integration set up, see our [related article](https://mews-systems.gitbook.io/guide/commander/settings/integrations/create-an-integration/facility-management/key-cutter-integration) to get started.

## Operator Configuration

Before you can begin using Operator at your property, the application must first be configured in your settings. To do so, open Commander and navigate to the Operator Configurations screen using the following path:

* **`Main Menu > Settings > Services > Stay > Operator Configurations`**

Click the `+` button to create a new Operator kiosk. Please note that you must create a new kiosk in Operator Configurations for each device you want to install Operator on. Complete the following fields on the next screen:

* **Language** - Select any languages you would like the key cutting instructions to be in. Selecting a language different from your property’s default language will automatically add a new text box next to the “Take key instructions” and “Cut key instructions” fields for you to complete.    
* **Name** - Enter a descriptive name to identify the kiosk \(for example, “Right Kiosk,” "Left Kiosk," etc.\).
* **Connector integration** - Select the connector integration you would like to use. Please note that you must already have a connector integration set up. If you don't, contact our Integrations team at  [integrations@mewssystems.com](mailto:integrations@mewssystems.com) to get started. 
* **Default language** - Select the default language you would like displayed in the Operator application.
* **Key cutter** - Select the key cutter you would like to connect to this kiosk. Please note that you must already have a door lock integration set up. See [our article](https://mews-systems.gitbook.io/guide/commander/settings/integrations/create-an-integration/facility-management/key-cutter-integration) for more information.
* **Take key instructions** - Enter the instructions you would like displayed on the left side of the screen. This should describe the first step in creating a key \(for example, “Please take a key from the stack.”\).
* **Cut key instructions** - Enter the instructions you would like displayed on the right side of the screen. This should describe the second step in creating a key \(for example, “Place the key on the key cutter.”\).
* **Cut key video URL** - Enter the web address for the instructional key cutting video that you would like displayed onscreen. Please note that it must be a complete address \(for example, http://mewssystems.com\) and must link directly to an mp4 file \(do not link to a video on a video-sharing website, such as YouTube or Vimeo\).

After you have completed all fields, click `Create`. The system will automatically generate a QR code, which you will need when setting up Operator on your device.

## Device Setup

Before you install Operator, please note that your tablet will need to be either new \(and not yet set up\) or factory reset. If you are using a new Android device, it will automatically begin the setup process the first time you turn it on. If it is not new, find instructions on how to factory reset your particular device \(instructions will differ from device to device\), perform the reset, and follow these steps: 

1. Tap the “Welcome” message repeatedly until the QR code setup process begins.
2. Connect to a Wi-Fi network, and the device will automatically begin installing a QR reader.
3. When the QR reader installation is complete, the device will automatically open the camera. In Commander, navigate to the Operator Configurations, click on the kiosk you created previously, and scan the QR code by pointing your device's camera at it.
4. Agree to all terms and conditions to start the installation process.
5. When the installation is complete, your device will automatically open the Operator application.

Your Operator kiosk has now been successfully set up and is ready to be used by guests.

{% hint style="info" %}
### Supported Countries

Operator is currently available for properties in the following countries:

* Australia
* Netherlands
{% endhint %}

