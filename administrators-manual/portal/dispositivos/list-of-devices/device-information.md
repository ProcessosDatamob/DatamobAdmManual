# Device Information

On the "Devices" screen within "Device List" you can access the device's information by clicking on the information button:

<figure><img src="../../../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

After clicking the icon above, the following screen will be displayed, which gives you access to the device information:

<figure><img src="../../../../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
The date shown in **Last Update** in the upper-right corner of the Device Information screen is the date of the device's update with Google, meaning it refers to communication between AMAPI and the portal. The data that is updated includes:

* **Details**
* **Installation**
* **Non-Compliance Report**
{% endhint %}



Below, we will detail the information contained in each of the fields in the images above:

### Details

* User - name of the user registered on the portal;&#x20;
* ID - ID registered for the device; Phone - phone number;&#x20;
* Group - group registered for the device;
* Department - This is a free text field, meaning the administrators can type anything they wish. It indicates the unit or department of the organization to which the device is assigned.
* User Phone - This is a free text field, meaning the administrators can type anything they wish. It indicates the phone number associated with the user of the device.
* IMEI - internal and unique number for each device. In Android 10 it is no longer possible to capture this information from the device because we use another method to receive this information with URL Enrichment; UDID - the device's unique identifier number;&#x20;
* ICCID - SIM chip number; Model - device model;
* Serial Number - device serial number;&#x20;
* License - License number;
* Model - device model;&#x20;
* Manufacturer - name of the device manufacturer;&#x20;
* Operating System - device operating system;&#x20;
* Android Version - device Android version;
*   Temporary Access Password - this temporary password is generated when the "Temporary Device Access" configuration is activated in Kiosk Mode. The password should be provided to the device user and will be updated on the portal every 5 minutes, with the option to copy it and display the remaining time until the password expires.

    Therefore, if a 10-minute access time has been defined for the user to access the device, they will not be able to use the same password after those 10 minutes as it will have already been updated. On the device, with the password in hand, the user should access the Initial Settings, click on the Temporary Access option, and enter the password in the "Code" field.

### Installation

* Applied Status: device registration status; if the device is fully registered, the status will be "Active".
* Registration Date: device registration date.
* Management Mode: displays the management mode used.
* App Version: version of the companion app installed on the device.
* Policy Name on Portal: name of the policy assigned to the device.
* Policy Name on Device: name of the policy assigned on the device.
* Applied Policy Version: version of the policy.
* Policy Synchronization Date: displays the date of the policy synchronization.
* Compliance: indicates whether the device adheres to all assigned policy settings. If any setting has not been applied, the value for this option will be "No".
*   Last Communication Date: displays the date when the device last communicated with the portal.\


    The data updated in the portal when the **Last Communication Date** is refreshed includes:

    * **Device Information Screen:** The data updated in the portal will match exactly what is on the device at the time of the last communication.
    * **Hardware:** Battery and storage
    * **Permissions:** All permissions
    * **Connectivity:** All data listed under Connectivity

### Hardware

* Total Memory: Total amount of RAM available on the device
* Available Memory: Amount of RAM currently free and available for use on the device
* Total Internal Storage: Total amount of internal storage the device has
* Available Internal Storage: Amount of internal storage currently free and available for use on the device
* Total SD Card Storage: Total amount of storage available on the SD card inserted in the device
* Available SD Card Storage: Amount of storage currently free and available on the SD card inserted in the device
* Processor: Information about the device’s processor, including the model and speed
* Battery Health: General state of the device’s battery, indicating its capacity and condition
* Battery Charge Cycle: Number of full charge and discharge cycles the device’s battery has undergone

### Permissions

* Access to Usage Data: status yes or no. If the user does not enable this permission, the application will not capture data usage and app usage time.
* Ignore Battery Optimization: status yes or no. If the user does not enable this permission, the application may be affected by battery optimization settings, stop capturing device locations, and stop sending information to the Portal.
* Write System Settings: status yes or no. If the user does not enable this permission, the Kiosk Launcher Manager application will not allow the user to change some system settings when in Kiosk mode.
* Read SMS: status yes or no. If the user does not enable this permission, the application will not capture the information of sent SMS messages.
* Schedule Alarms - Status options are "Yes" or "No." If the user does not enable this permission, the app will not perform the following functions: notification of received messages and documents, remote app installation, device geolocation logging, and SIM lock removal.
* Install Apps from Unknown Sources - This permission is optional and can be enabled during initial setup. If the user chooses not to enable it, the app will not be able to install apps remotely.
* Screen Overlay - This permission is also optional during activation. If not enabled, the app will not display confirmation messages when installing apps remotely.

### Conectividade

* Connected Network Type (Wi-Fi/Mobile) - Indicates whether the device is connected via Wi-Fi or a mobile network.
* Bandwidth (Mobile) - Available bandwidth for the mobile network.
* Bandwidth (Wi-Fi) - Available bandwidth for the Wi-Fi network.
* Latency - Time taken for a data packet to travel from its source to its destination and return. Measured by sending packets to google.com, a reliable server, to assess network performance.
* Band Configuration - Specific configuration of the frequency band used.
* Connected Wi-Fi Network - Name of the Wi-Fi network to which the device is connected.
* Signal Strength - Signal intensity of the connected network.
* Wi-Fi Roaming - Device's ability to automatically connect to different Wi-Fi access points within the same network without losing connection.
* Wi-Fi Band Frequency - Frequency used by the Wi-Fi network (e.g., 2.4 GHz or 5 GHz).
* Wi-Fi Link Speed - Connection speed to the Wi-Fi network.
* Wi-Fi MAC Address - MAC address of the device's Wi-Fi adapter.
* IP (Wi-Fi Network) - IP address assigned to the device on the Wi-Fi network.
* IPv6 (Wi-Fi Network) - IPv6 address assigned to the device on the Wi-Fi network.
* Network BSSID - Unique identifier of the Wi-Fi network.
* Connected Network Operator - Name of the connected mobile network operator.
* Mobile Data Roaming - Indicates if the device is in mobile data roaming.
* IP (Mobile Network) - IP address assigned to the device on the mobile network.
* IPv6 (Mobile Network) - IPv6 address assigned to the device on the mobile network.
* DBM (RSRP - Antenna Power) - Measure of the antenna signal strength.
* Cell ID - Identification of the cell to which the device is connected.
* LAC - Local Area Code.
* Antenna Technology - Type of antenna technology used.

### SIM

* Connected SIM - Indicates which SIM is currently connected to the mobile network.
* SIM 1 Operator - Name of the operator for the first SIM.
* SIM 1 Phone Number - Phone number associated with the first SIM.
* SIM 1 ICCID - Unique identifier of SIM card 1.
* SIM 1 IMEI - International Mobile Equipment Identity number for SIM 1.
* SIM 1 Subscriber Number - Subscriber number associated with SIM 1.
* SIM 1 MCC - Mobile country code for SIM 1.
* SIM 1 MNC - Mobile network code for SIM 1.
* SIM 2 Operator - Name of the operator for the second SIM.
* SIM 2 Phone Number - Phone number associated with the second SIM.
* SIM 2 ICCID - Unique identifier of SIM card 2.
* SIM 2 IMEI - International Mobile Equipment Identity number for SIM 2.
* SIM 2 Subscriber Number - Subscriber number associated with SIM 2.
* SIM 2 MCC - Mobile country code for SIM 2.
* SIM 2 MNC - Mobile network code for SIM 2.
* eSIM Operator - Name of the operator associated with the eSIM.
* eSIM Phone Number - Phone number associated with the eSIM.
* eSIM ICCID - Unique identifier of the eSIM.
* eSIM Subscription ID - Subscription identifier associated with the eSIM.
