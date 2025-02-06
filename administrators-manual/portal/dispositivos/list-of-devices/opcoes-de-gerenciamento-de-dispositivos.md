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

# Device management options

### **Device Commands and Actions**

And by clicking on the ellipsis "..." on the right in the list of devices, the options for consulting and configuring the device appear

<figure><img src="../../../../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

The available options vary according to the Management Mode of the policy to which the device is linked and are highlighted in the following image:

<table><thead><tr><th width="242">Management mode</th><th>Available options</th></tr></thead><tbody><tr><td>Android</td><td>Change Policy<br>Activate/Deactivate Device<br>Turn Off Screen<br>Restart Device<br>Generate New Device Password<br>Remove Device (WIPE)<br>Manage Information</td></tr><tr><td>Android Block SIM</td><td>Change Policy<br>Activate/Deactivate Device<br>Turn Off Screen<br>Restart Device<br>Generate New Screen Lock Password<br>Remove Screen Lock<br>Remove SIM Lock<br>Remove Device (WIPE)<br>Manage</td></tr><tr><td>Android Work Profile</td><td>Change Policy<br>Remove Device (WIPE)<br>Manage</td></tr></tbody></table>

The options highlighted in the figures are detailed in the following subsections.

### Change Policy

When you choose the Change Policy option, a dialog box will appear in the center of the screen for you to choose the policy to be assigned to the device. Choose the policy from those listed and click update to change the device's policy.

The policy defines settings, including criteria for hardware, software, operating system, security, etc. To find out more about Policies, read the settings section of this manual.

<figure><img src="../../../../.gitbook/assets/image (228).png" alt=""><figcaption></figcaption></figure>

### Disable Device

When you send the Deactivate Devices command, all non-Google applications will be deactivated, phone calls will be allowed and the device status will change to deactivated. To deactivate a device, use the "Deactivate Device" option in the device options menu. This option only appears for devices that are in "Active" status. A confirmation screen will appear.

<figure><img src="../../../../.gitbook/assets/image (229).png" alt=""><figcaption></figcaption></figure>

Click on the "Deactivate" button to confirm the operation.

### **Enable Device**

This option only appears for devices that are in "Disabled" status. To activate a disabled device, click on "Activate Device" in the device management options.

Confirm the update by clicking "Activate" in the dialog box, as shown below.

### Turn off device screen

The "Turn Screen Off" option sends a command to turn off the device's screen. When you click on the "Turn off screen" option, the command is executed directly and a message appears on the screen to inform you that the command has been sent to the device.

### Restart device

This operation sends a command to restart the device. Choose the "Restart Device" option. A message is displayed on the portal screen to confirm that the command has been sent.

### **Generate New Screen Lock Password**

This option allows the administrator to set the screen lock password for Block SIM, enabling remote password change. In the Device List, click on "Generate New Screen Lock Password," enter and confirm the new Screen Lock Password using letters, numbers, and symbols. Confirm the password change, and upon confirmation, the command will be sent via push to the Management App for application on the device.

1. In the Device List, click the three dots "...".
2. Click the option "Generate New Lock Screen Password."
3. Enter and confirm the new Lock Screen password, using letters, numbers, and symbols.
4. Confirm the password change, and upon confirmation, the command will be sent via push to for application on the device.
5. The device will receive the command via push.

Once the password is changed, Block SIM will receive the new password and activate the lock screen with the newly defined password.

{% hint style="info" %}
**Limitations with Block SIM**\
When the device is configured in a policy with Block SIM active, incoming calls cannot be answered without unlocking the screen first.

**Guidance**\
If answering calls is necessary even with the screen locked:

* Evaluate if the Block SIM policy is suitable for these specific cases.
* Communicate this limitation to the end users.
{% endhint %}

### Remove Screen Lock

This operation sends a command to remove the screen lock from the device. Choose the "Remove Screen Lock" option. A message is displayed on the portal screen to confirm that the command has been sent.

{% hint style="info" %}
**Note**

This option will only be available for devices activated with Android Block SIM management mode policy.
{% endhint %}

### Generate new device password

The system allows you to generate a new password for the device. To do this, choose the "Generate New Device Password" option as shown in the image below.

Fill in the "New password" and "Confirm new password" fields with the same values so that the "Confirm" button is enabled. Optionally, the following options can be checked as required:

* Do not allow other administrators to change the password again until the user enters it on the device;
* &#x20;Do not ask for user credentials at device startup;&#x20;

Lock the device after the password has been reset.

<figure><img src="../../../../.gitbook/assets/image (230).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
#### NOTE

When selecting the option "Do not request user credentials at device startup," the password will not be requested during the startup process. The password will only be necessary to unlock the device's screen. Secure Boot: The password requested at startup is a security measure implemented by Secure Boot. This functionality protects the startup process from security attacks originating from malicious code, such as malware and ransomware.
{% endhint %}

### **Remove SIM Lock**

This option allows the administrator to send a command to remove the SIM lock from a device, granting user access to the device.

In the "Device List" screen, select the "Android - Block SIM" policy and choose the "Remove SIM Lock" option. The system will display a confirmation message for sending the SIM lock removal command, allowing you to confirm or cancel. After sending the removal command, the device will receive a push notification with the command, and will capture and send the command to Block SIM. The device user needs to click on the push notification or open the Block SIM app to complete the lock removal.

### **Restart SIM Lock**

The "Restart SIM Lock" feature allows the administrator to reapply the SIM lock on a device after it has been removed.

This enables the administrator, following the lock removal, to change the device's SIM and apply a new lock, ensuring flexibility in management and security for managed devices.

{% hint style="info" %}
**NOTE**\
After removing the lock, it is possible to reapply a lock without resetting or formatting the device.
{% endhint %}

### Remove Device (WIPE)

This operation allows you to delete a device. It clears the device's data and settings. Deleted devices do not appear in the company's device list. The "Remove Device" option appears in the list of device options on the device list screen ("Devices" menu, "List Devices" option).

{% hint style="info" %}
**NOTE**

A message is displayed on the screen for information and warning. The operation cannot be undone, so only confirm when you are sure you want to delete the device.
{% endhint %}

### **Remove Device with Locked CHIP**

When sending the removal command for a device that is activated with the "Android - Block SIM" policy and has the CHIP locked, the administrator will be alerted to send a command to remove the CHIP lock before removing the device from the portal.

After choosing to send the unlock command for the CHIP, and once the portal receives the confirmation of the CHIP lock removal on the device, the system will display the following message:

"Do you really want to remove this device? This action cannot be undone."

The options "Remove" and "Cancel" will be displayed. This functionality helps prevent issues with CHIP locking when removing devices from management.

The system will show this message: "This device may have the SIM CHIP locked. Do you want to send a command to remove the 'CHIP Lock'?"

When clicking "Yes", the CHIP lock removal command will be sent, and the system will show: "Command sent successfully! Please wait before attempting to remove the device again."

The system will then wait for confirmation before allowing the removal of the device.

The user of the device needs to click on the push notification or open the Block SIM app to perform the CHIP lock removal.

If the administrator chooses not to send the command, the following message will be displayed:

"By removing this device, the mobile data usage of the user's SIM CHIP may be blocked! Do you really want to remove this device? This action cannot be undone."

### **Remove Device with SIM Locked**

When sending the removal command for a device that is activated under an Android Block SIM policy and has a locked SIM, the administrator will be alerted to send a command to remove the SIM lock before removing the device from the portal.

A message will be displayed: **This device may have the SIM lock enabled. Do you want to send a command to remove the "SIM Lock"?**\
By clicking "Yes," the command to remove the SIM lock is sent, and a message will appear: Command sent successfully! Please wait to try removing the device again.

The system will then wait for confirmation before allowing the device removal. The device user needs to click on the push notification or open the Block SIM app to complete the lock removal.

{% hint style="info" %}
The device user needs to click on the push notification or open the Block SIM app to complete the lock removal.
{% endhint %}

If the administrator chooses not to send the command, the following message will be displayed: By removing this device, the mobile data usage of the user's SIM card may be blocked! Do you really want to remove this device? This action cannot be undone.

After opting to send the SIM unlock command and the portal has received confirmation of the SIM lock removal on the device, the system will display the following message: Do you really want to remove this device? This action cannot be undone.

The options "Remove" and "Cancel" will be presented.

This functionality helps prevent potential SIM lock issues that may arise when removing devices from management.

### Managing

Clicking on the "Manage" option will display the Device Management screen.

<figure><img src="../../../../.gitbook/assets/image (223).png" alt=""><figcaption></figcaption></figure>

This screen groups the Device Commands and Actions that we detailed earlier, based on the Management Mode or Operating System. The behavior of each functionality will be the same as in the "Device List" screen.

The options to "Back" and "Refresh" will be displayed. Clicking "Refresh" will update the information, and hovering over the refresh button will show the last updated date.

The tabs with options for editing and information about the device are as follows:

* Information
* Applications
* Battery
* Free Storage
* Geolocation
* Non-Conformities

Below is the explanation of each tab:

#### **Information**

When you open the Device Management screen, the first tab, "Information," is pre-selected. In this tab, you can edit the following device data: User, Identification, Group, Department, and User Phone Number.

<figure><img src="../../../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

In addition to being able to edit the data, lower down the screen, there are lists displaying Details, Installation, Hardware, Permissions, Connectivity, and SIM, all related to the managed device.

<figure><img src="../../../../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

The sections are detailed on the Device Information page: "Details," "Installation," "Hardware," "Permissions," "Connectivity," and "SIM."

{% hint style="info" %}
**NOTE**\
You can quickly access the policy editing screen for a device by clicking on the policy name, which functions as a link.
{% endhint %}

#### **Applications**

In the "Applications" tab, you can access the list of all applications installed on the device, which includes the following information: icon, name, mobile data usage, Wi-Fi data usage, and usage time. The data on consumption and usage time is recorded within the cycle. You can search for a specific application using the search field, export complete reports or the current page, and copy the information from the list. By clicking on the three dots, you can view the "Consumption History" graph for the application during the cycle.

#### **Battery**

In the "Battery" tab, you can select a date to view the desired information. Upon choosing the date, the system will retrieve and display the battery data in a graphical format.

#### **Free Storage**

In the "Free Storage" tab, you can view the available memory in the device's internal storage by selecting a date to see the desired information. Once you choose the date, the system will retrieve and display the storage data in a graphical format.

#### **Geolocation**

When accessing the "Geolocation" tab, you can filter locations using the following filters: Locate, Date, Time Zone, and Accuracy. By clicking on "Search," a map will be displayed, showing the registered geolocations, if available.

To view the geographic locations of a device, follow these steps:&#x20;

1. Select the Locate option: By Date or Now. \
   If you select the "Locate By Date" option, follow these steps:
2. Choose the date on which the locations were recorded.
3. Specify the time zone in which you want to view the locations.
4. Select the accuracy limit for the locations.
5. Click the "Search" button to display the locations on the map according to the specified filters.
6. The system will display the locations with markers that outline the path taken by the device user. The markers will have different colors indicating the type of location. Use the legend to identify the type:

* Initial GPS Reading Position – The first location of the device recorded on the day.
* Current Position or Last Collected Position of the Day – The last location of the device recorded on the day.
* Places Where the User Passed – Locations recorded on the day, between the first and last.

Click on the marker to view the location information. Use the map features to optimize the visualization.

#### **Non-Conformities**

In this tab, all non-conformities of the device will be listed with detailed information regarding Configuration, Reason for Non-Conformity, and Non-Conformity Details.

{% hint style="info" %}
**NOTE**\
The "Non-Conformities" tab will be disabled if the device does not have any non-conformities.
{% endhint %}

For each listed non-conformity item, the following information will be displayed: Package Name, Field Path, Current Value, Installation Failure Reason, Wi-Fi Context, and Policy Password Context.

You can "Export" and "Copy," allowing you to export the report information to an Excel file or copy the information to the clipboard.
