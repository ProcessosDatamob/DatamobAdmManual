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

# Kiosk mode

The purpose of this setting is to enable the creation of an environment in which the user of the device can only access the applications previously authorized by the administrator, i.e. only the icons of the selected applications will be displayed on the device's screen.

To access the "Kiosk Mode" settings, follow these steps:

1. On the "**Edit policy**" screen, select the "**Kiosk mode**" tab.
2. Activate kiosk mode by clicking on the activation button.

<figure><img src="../../../../.gitbook/assets/Captura de tela 2024-02-15 095151.png" alt=""><figcaption></figcaption></figure>

3. A confirmation message will appear on the screen. Confirm by clicking on the "**Activate**" button.

<figure><img src="../../../../.gitbook/assets/image (72).png" alt=""><figcaption></figcaption></figure>

4. When you activate Kiosk Mode in the policy and provision a device with this policy, the Kiosk Launcher Manager application will be automatically installed on the device;

<figure><img src="../../../../.gitbook/assets/image (200).png" alt=""><figcaption></figcaption></figure>

When the device installs the Kiosk application, the application will capture a list of all the applications installed on the device and send this list to the Portal. It will also send the following managed settings to the portal.

### Kiosk Configuration Options

With kiosk mode enabled, the following configuration options will be available:&#x20;

* **Navigation Buttons -** allows you to set the device's navigation buttons to "Active," "Locked," or "Home button only";&#x20;
* **Power Button -** allows you to set the device's power button to "Available" or "Locked";&#x20;
* **Display Error Messages -** allows you to set the display of error messages to "Active" or "Muted";&#x20;
* **Information Displayed on the Status Bar -** allows you to define the information that will be displayed on the device's status bar. It can be set to "Notifications and system information," "System information only," or "None";&#x20;
* **Access to Settings** - allows you to set it to "Allowed" or "Blocked";&#x20;

{% hint style="info" %}
#### NOTE

During the activation of a device under a policy with Kiosk Mode active, the "Access to Settings" configuration needs to be set to "Allowed" so that the user can grant the permissions requested for the activation of the Companion. This is because the user needs to directly access the device's settings interface. Therefore, in kiosk mode, no application will be able to activate permissions that require access to the OS settings interface if the settings are blocked in the policy. After enrollment, the settings can be blocked if necessary. Another option, to avoid leaving settings access allowed, is to set the Companion permissions as optional. This way, the user can activate without needing to grant the permissions. However, in this case, data related to the permissions not granted will not be collected.
{% endhint %}

* **Additional Telephony Services** - allows you to set telephony services to "Active" or "Set by the device." When set to "Active" and the policy is saved, the system will send the telephony service packages to the device within the policy and kiosk mode, allowing the device to make and receive calls. When set to "Set by the device," the device will operate according to its default configuration, with or without the services.
* **Wallpaper** - you can upload a wallpaper image to the policy and set the screen orientation, which will be sent to the application
* **Icon font color** - allows you to set the text color of the icons on the home screen
* **Screen Orientation** - allows you to select the screen orientation for the device, and the default is: "User-defined"
* **Icon size and Fonts** - allows you to select the following display size options: _System default (default), Small (75%) and Large (125%)_
* **Sorting the icons** - allows you to sort the icons
* **Image positioning** - allows you to select the position of the wallpaper image on the device's home screen
* **Block access to Wi-Fi settings -** prevents users from accessing and modifying Wi-Fi settings during the initialization and use of the device in Kiosk Mode.
* **Temporary Device Access** - a configuration that allows the user to access the device for a specified period. To activate the permission, slide the switch to the right while in front of the screen. Additionally, it is possible to define the duration of the user's access to the device, which can be 5, 10, 15, or 30 minutes, or 1 hour. When temporary access is enabled, a password will be generated for the user to access the device. In the "Device Management Options" section, we will provide more details on how it works. After the defined time ends, Kiosk Mode is automatically reactivated.
