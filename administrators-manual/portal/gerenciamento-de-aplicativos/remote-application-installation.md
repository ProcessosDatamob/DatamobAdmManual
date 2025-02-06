# Remote Application Installation

This system screen aims to allow the user to remotely install applications without the application being on the Play Store.&#x20;

To manage and send remote application installations to the devices, click on the "Application Management" menu and select "Remote Application Installation."

<figure><img src="../../../.gitbook/assets/Captura de tela 2024-05-15 180510 (2).png" alt=""><figcaption></figcaption></figure>

The system will display a list of the applications installed on the company's devices.

<figure><img src="../../../.gitbook/assets/Captura de tela 2024-05-15 181019.png" alt=""><figcaption></figcaption></figure>

1. The system will display a date range filter.
2. In the search field, you can search for specific information.
3. To export the device report, click the “Excel” button.
4. To copy the device information, click the “Copy” button.
5. In the "New Installation" field, you can send a remote application installation to the devices. For more details, access "Install Application" on this same page.
6. The application information list displays the following details: Submission Date, App Name, Package Name, and Download URL.
7. Sort the device list by the columns using the "↑↓" arrows.
8. By clicking on the ellipsis "...", and selecting “View Installation”, you can access the “Application Submission Details” screen.

<figure><img src="../../../.gitbook/assets/image (204).png" alt=""><figcaption></figcaption></figure>

**Install Application**

To remotely install an application, follow these steps:

1. Select the policy and device users linked to policies in the following management modes: Android, Android - Block SIM, and Android - Work Profile.&#x20;
2. Fill in the required fields: Name, Package Name, and Download URL.&#x20;
3. Click "Submit."

{% hint style="info" %}
**NOTE**

Upon confirming the submission, the system will display a success message, send an app installation push notification to all devices of the selected policy and users, and add the app package to the policy of all selected devices as "Available."
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
#### NOTE

The application sent through remote installation is sent with the installation type "Available." Therefore, if the user uninstalls the application, to reinstall it, the administrator will need to send the install application command again via the portal to the device. Currently, this functionality is not available in policies with Kiosk Mode activated. If the package inserted by the user is different from the package of the app available at the download link:

* The notification will remain fixed on the device until it is restarted.
* The app will be automatically removed from the device by Google.
{% endhint %}
