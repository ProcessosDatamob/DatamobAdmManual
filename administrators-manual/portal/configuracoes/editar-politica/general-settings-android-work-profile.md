---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# General Settings - Android - Work Profile

gement mode for personal devices. It allows a user with their personal device to create a secure environment for using work applications, guaranteeing the necessary security for company information and the user's privacy, since the device is personal.&#x20;

To do this, the user needs to download the **Android DPC app** from the app store and scan the **QR CODE** of the policy with the management mode "**Android - Work Profile**". At the end of provisioning, the device will display work apps with the work profile icon (blue case) and private apps without icons.

{% hint style="warning" %}
**IMPORTANT**

* It is not necessary to Factory reset the device to perform provisioning, just download the "Android - DPC" application and follow the provisioning steps.
* When you perform the "**Remove Device**" command in the grouped menu of the "**Device List**" screen, the work profile on the device and the work applications will be removed. The device will not be reset.
* The user has the autonomy to remove the work profile via the device, without requiring authorization from the Administrator
* Android Go supports fully managed and dedicated deployment scenarios. However, the work profile (BYOD) is optional and therefore absent on most Go devices.
{% endhint %}

The general settings are grouped into types:

* Full Lockdown
* Password Restrictions - Device
* Password Restrictions - Work Profile

<figure><img src="../../../../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

This feature allows the administrator to configure a full lockdown of the device outside a specified time period or upon reaching the mobile data limit. This enables locking the device when the user is outside working hours or when the defined mobile data limit for the current cycle is reached.

In the "Settings" tab on the "Edit Policies" screen, click "Full Lockdown" to view configuration options.

<figure><img src="../../../../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

#### **Lock Outside Working Hours**

To lock devices outside of working hours, follow these steps:

1. Activate the "Lock device outside of working hours" option.
2. Fill in the "Working Days" field with the workdays in the week, specifying the start and end days.
3. Fill in the "Working Hours" field with the start and end times for the workday.

<figure><img src="../../../../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**NOTE**\
Leaving the fields blank will cause the system to consider the entire day.
{% endhint %}

When the device is outside the configured working hours, Datamob Enterprise will hide all device apps except "Phone," "Datamob Enterprise," and "Play Store."

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

### **Password Restrictions - Device**

<table data-header-hidden><thead><tr><th width="318.80616740088107"></th><th></th></tr></thead><tbody><tr><td><strong>Configuration</strong></td><td><strong>Description</strong></td></tr><tr><td>Quality of the password</td><td><p>In this configuration, the following options are available:</p><ul><li>Not specified</li><li>Biometric</li><li>Something</li><li>Numeric</li><li>Complex Numeric</li><li>Alphabetic</li><li>Alphanumeric</li><li>Complex</li></ul><p><strong>Note:</strong> The following fields will be displayed according to the selected Password Quality option.</p></td></tr><tr><td>Password History Length</td><td>Sets the number of previously used passwords that cannot be reused</td></tr><tr><td>Maximum Incorrect Passwords Before Wipe</td><td>Sets the maximum number of incorrect attempts before executing a Wipe</td></tr><tr><td>Password Expiration Timeout (days)</td><td>Sets the number of days before the password expires</td></tr><tr><td>Minimum Password Length</td><td><p></p><p>In this configuration, the options are:</p><ul><li><strong>Device Default:</strong> Follows the default setting configured on the device.</li><li><strong>Every Day:</strong> The password will be required daily.</li></ul></td></tr><tr><td>Minimum Number of Letters Required in Password</td><td>This configuration sets the minimum required length for created passwords, enhancing data security.</td></tr><tr><td>Minimum Number of Lowercase Letters Required in Password</td><td>This configuration sets the minimum number of letters required in passwords, specifying a certain number of alphabetic characters within the password combinations.</td></tr><tr><td>Minimum Number of Non-Letter Characters (numeric digits or symbols) Required in Passwords</td><td>Specifies the minimum number of non-alphabetic characters required in passwords</td></tr><tr><td>Minimum Number of Numeric Digits Required in Password</td><td>Sets the minimum number of numeric digits required in passwords.</td></tr><tr><td>Minimum Number of Symbols Required in Password</td><td>This configuration establishes the minimum number of symbols required in passwords, within the password combinations.</td></tr><tr><td>Minimum Number of Uppercase Letters Required in Password</td><td>Sets the minimum number of uppercase letters required in the password.</td></tr></tbody></table>

### Password Restrictions - Work Profile

If the switch is enabled, it allows the user to keep the same password set for the "Device" in the "**Work Profile"**.

When the option is disabled, it forces the user to create a password other than their personal password in order to access their work profile. The same settings described in the table above for setting the password are displayed.

### Work

This functionality allows the admin user to configure a total device lock outside a specific time period, enabling the device to be locked when the user is not within working hours.

In the "Settings" tab on the "Edit Policies" screen, click on "Work" to view the configuration options.

<figure><img src="../../../../.gitbook/assets/image (51).png" alt=""><figcaption></figcaption></figure>

To lock devices outside of working hours, follow these steps:

1. Enable the "Block device outside working hours" option.
2. Fill in the "Working days" field with the days worked in the week, from the start day to the end day.
3. Fill in the "Working hours" field with the start and end times of the working hours.

{% hint style="info" %}
Note

Leaving the fields blank will cause the system to consider the entire day.
{% endhint %}
