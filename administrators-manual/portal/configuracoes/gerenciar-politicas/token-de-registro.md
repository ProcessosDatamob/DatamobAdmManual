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

# Registration Token

As seen in the previous section, it is possible to access the device registration token in the "Settings" menu under the "Manage Policies" option. The registration token screen is shown below.

<figure><img src="../../../../.gitbook/assets/image (48).png" alt=""><figcaption></figcaption></figure>

The items available on this screen are described below:

1. The policy Registration Token can be copied and sent.
2. The policy Zero Touch configuration can be copied to be inserted into the Zero Touch panel.
3. The system will present a field for selecting the 'Wi-Fi Network.' On this screen, it will be possible to choose one of the Wi-Fi networks previously configured in the 'Manage Wi-Fi Networks' section. Upon selection, all possible configurations with the following security types will be included in the QR Code:
   * WPA/WPA 2
   * WEP
   * None&#x20;

When registering using the QR Code, the device will automatically connect to the configured network.

4. The "Enable System Apps" option allows enabling all native system applications on the device. When this option is enabled, the system will update the QR Code image to include the information to enable the system apps.
5. Enabling the "Skip Encryption" field will include the following information in the QR Code: "android.app.extra.PROVISIONING\_SKIP\_ENCRYPTION". The system will also update the QR Code image with the new configuration and update the Zero Touch configuration. After enrolling with the QR Code, the device will skip system encryption.
6. Enabling the "Use Mobile Data" option of the operating system (OS) will include the following information in the QR Code: "android.app.extra.PROVISIONING\_USE\_MOBILE\_DATA". The system will update the QR Code image with the new configuration. After enrolling with the QR Code, the device will use mobile data during the setup process.
7. Upon completing the configurations, the system will allow saving or canceling the configurations, storing them upon finalizing the save process.

The policy QR Code can be read on the screen for the device registration process or can be copied and sent to the device users.
