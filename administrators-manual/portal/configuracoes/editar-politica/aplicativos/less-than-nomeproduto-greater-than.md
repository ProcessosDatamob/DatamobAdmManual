# Datamob Enterprise

**Optional Permissions for**\
Within Managed Settings, Optional Permissions have been created for to enable activation on devices that do not have the requested permissions at activation.

To access "Optional Permissions," click on the three dots "..." at the end of the row, then select "Managed Settings" for .

<figure><img src="../../../../../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>

When expanding "Optional Permissions," various options will be displayed, allowing you to enable or disable each setting individually.

<figure><img src="../../../../../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

**Optional Permissions** include the following settings:

* **Set "Usage Data Access" Permission as Optional:** Allows the user to opt out of enabling this <mark style="color:red;">p</mark>ermission during setup. Without it, the application will not capture usage and app usage time data, and this information will not be displayed on the Portal.
* **Set "Ignore Battery Optimization" Permission as Optional:** Allows the user to opt out of enabling this permission during setup. Without it, the application may be affected by battery optimization, potentially missing location captures and data transfers to the Portal.
* **Set "Write System Settings" Permission as Optional:** Allows the user to opt out of enabling this permission during setup. Without it, the Kiosk Launcher Manager app will not be able to modify certain system settings in kiosk mode.
* **Set "Read SMS" Permission as Optional:** Allows the user to opt out of enabling this permission during setup. Without it, the application will not capture SMS information, and this data will not be displayed on the Portal.
* **Set "Install Apps from Unknown Sources" Permission as Optional:** Allows the user to opt out of enabling this permission during setup. Without it, the application will not be able to install apps remotely.
* **Set "Screen Overlay" Permission as Optional:** Allows the user to opt out of enabling this permission during setup. Without it, the application will not display a confirmation message for remote app installations.
* **Set "Schedule Alarms" Permission as Optional:** Allows the user to opt out of enabling this permission during setup. Without it, the application will not perform the following functions: remote app installation, device geolocation logging, SIM card unblocking, and total app lockdown. This setting will not appear on devices running Android versions below 13, and if "Ignore Battery Optimization" is enabled, as this setting automatically activates the "Schedule Alarms" permission.

Clicking "Save" will send the selected configurations to the devices.
