# Full Lockdown

This feature allows the administrator to configure a full lockdown of the device outside a specified time period or upon reaching the mobile data limit. This enables locking the device when the user is outside working hours or when the defined mobile data limit for the current cycle is reached.

In the "Settings" tab on the "Edit Policies" screen, click "Full Lockdown" to view configuration options.

<figure><img src="../../../../../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

#### **Lock Outside Working Hours**

To lock devices outside of working hours, follow these steps:

1. Activate the "Lock device outside of working hours" option.
2. Fill in the "Working Days" field with the workdays in the week, specifying the start and end days.
3. Fill in the "Working Hours" field with the start and end times for the workday.

<figure><img src="../../../../../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**NOTE**\
Leaving the fields blank will cause the system to consider the entire day.
{% endhint %}

When the device is outside the configured working hours, \<NomeProduto> will hide all device apps except "Phone," "\<NomeProduto>," and "Play Store."

The installed apps on the device will only be hidden, and a fixed notification will appear on the device with the following message: "App access blocked by administrator."

Thus, when the device is outside the configured working hours, accessing the hidden apps will not be permitted, although accessing device settings and powering off or restarting the device will be allowed.

When the device is within the configured working hours, all apps will be displayed again without needing reinstallation.

#### **Data Limit Lock**

To enable device lock based on mobile data usage limits, activate the "Lock device by mobile data usage limit" option.

When the device reaches the configured mobile data usage limit for the current cycle, will hide all device apps except "Phone," "Management App," and "Play Store."

The device will display a fixed notification with the message: "App access blocked by administrator." This notification informs the user of the lock.

Thus, when the device is locked due to data usage limits, hidden apps cannot be accessed but will remain installed. The user can still access device settings, and the device can be powered off or restarted.

Additionally, any app installed via Play Store or remotely will be hidden.

If mobile data usage falls below the limit or if the administrator disables the "Lock device by mobile data usage limit" setting in the policy, will display all device apps according to the provisioned policy.

If the device meets any conditions that require activating a Full Lockdown (either outside working hours or reaching the mobile data limit), enabling one Full Lockdown does not interfere with or override the other. Both locks can coexist and will be applied according to their respective conditions.
