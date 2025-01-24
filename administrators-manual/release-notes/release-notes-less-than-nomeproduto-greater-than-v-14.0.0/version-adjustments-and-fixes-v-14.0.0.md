# Version Adjustments and Fixes - V 14.0.0

**Version Adjustments and Fixes - V 14.0.0**

In this version, the following fixes were made:

1. **Application Configuration - "Show in Kiosk" Flag**:\
   The behavior of the "Show in Kiosk" option was adjusted. When a device was registered in a policy with Kiosk Mode active and a manual installation of an app with forced installation type was performed, it was observed that the "Show in Kiosk" option wasn't updating correctly. The app was not displayed when the "Show in Kiosk" flag was enabled, and only appeared when the flag was disabled. This issue was resolved by adjusting the behavior to ensure the app is displayed on the device according to the desired configuration.
2. **Incorrect Behavior When Deleting Company**:\
   When accessing the portal and deleting a company via the **Company → Company Information** menu, the system was correctly sending the WIPE command to registered devices but did not notify the user about the action performed. Additionally, after re-entering the portal, the system was improperly retrieving the company’s information, contradicting the requested deletion. To solve this, an adjustment was implemented to display a confirmation notification to the user, and upon confirmation, the user is redirected out of the portal, preventing the retrieval of the deleted company’s data.
3. **Deletion of Wi-Fi Network Configured in QR Code**:\
   In the portal, when creating a Wi-Fi QR Code policy and associating it with a previously registered Wi-Fi network, deleting that network resulted in the removal of the QR Code from the policy. To resolve this, the configuration was adjusted to ensure that both the QR Code and registration token remain accessible, even if the network previously linked to it was deleted.
4. **Managed App Settings Not Being Saved**:\
   In the **Settings > Manage Policies** menu, when enabling options for specific apps, it was found that the managed settings were not being saved correctly. The system was adjusted to ensure that the activated options remain active after the policy update, ensuring that the desired behavior is reflected on the device.
