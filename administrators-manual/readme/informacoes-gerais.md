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

# General Information

### Solution Overview <a href="#tyjcwt" id="tyjcwt"></a>

&#x20;**\<NomeProduto>** is a Corporate Mobility Management solution composed of:

* **Administration Portal** **\<NomeProduto> -** web system that manages all  the company's mobile devices.
* **\<NomeProduto> app -** Android app that collects usage and cosumption information from mobile devices. This app is installed by default in all devices enrolled in the system.
* **Security Browser App -** Android Web browser app responsible for blocking web sites and monitoring user's navigation.
* **Block SIM app -** Is responsible for blocking the SIM Card,  preventing from being used in another device.
* **Mob Settings App** - This app is designed to streamline the management of essential mobile device settings, such as Bluetooth, Display, and Wi-Fi, without the need to directly access the device's settings menu.

{% hint style="info" %}
**IMPORTANT**

* The Security Browser and Mob Settings apps are available on the Play Store and should be included in the device enrollment policy. The step-by-step guide for adding the apps to the Managed Apps List can be found in the respective Security Browser and Mob Settings sections.
* To use SIM card blocking, when creating a new policy you must choose the "Android - Block SIM" management type, so that the system automatically adds the Block SIM application, restricts device password changes and ensures that the SIM card is linked to the device. When registering the device, the user must follow the installation steps and grant the requested permissions. More details on the SIM blocking process can be found in the "Block SIM Installation Manual".&#x20;
{% endhint %}

From **\<NomeProduto>** you can access information on the consumption and use of the devices allocated to a company's employees. It is also possible to define blocking policies to restrict improper use of the devices, enabling the administrator to evaluate and increase employee productivity by analyzing and managing the company's telecommunications resources.&#x20;

### Data Flow <a href="#id-3dy6vkm" id="id-3dy6vkm"></a>

All the information collected by the application is periodically sent to the system's servers. The information is compiled and consolidated for viewing on the administration portal. The consumption data collected by the application is sent according to the time configured in the portal, in the "Synchronize each" option available in the [COMPANIES menu --> General Settings](../portal/empresas/configuracoes-gerais.md)

The usage data collected by the app is sent according to the interval configured in the portal under the "Sync every" option, which ranges from 1 to 24 hours.

### Data Storage <a href="#id-1t3h5sf" id="id-1t3h5sf"></a>

All Portal data remains stored for 6 months, after which time the information will be deleted from the servers.&#x20;

If the servers become unavailable, the application will keep the information until communication with the servers is re-established.&#x20;

All data sent by the portal and received by the device remains stored, ensuring that policies remain active even when there is no Internet access and regardless of the availability of the servers. The connection will only be needed to receive new policies or messages and to send the data to the Portal.

### Portal Access Level <a href="#id-4d34og8" id="id-4d34og8"></a>

The Administration Portal has two access levels:

* **Portal administrator:** this level gives full access to information and allows you to set blocking policies for devices;
* **Group administrator:** this level gives you access to your group's data and allows you to send messages to the group;

To find out how to create a portal or group administrator, read the section on ["Registering a New Administrator User".](../portal/usuarios/cadastrar-novo-usuario-administrador.md)

### Device Compatibility

The product was created in partnership with Google in the Android Enterprise program. Google maintains a list of approved and recommended devices for use with Android Enterprise in its Enterprise Solutions Directory. To access the devices recommended under the Android Enterprise program, contact the Google Solutions Directory via the link https://androidenterprisepartners.withgoogle.com/devices/.&#x20;

The Android Enterprise Recommended label identifies Android devices that meet certain security, performance and management standards suitable for use in enterprise environments. When a device receives the "Android Enterprise Recommended" certification, it means that it has passed rigorous tests and meets specific requirements set by Google.&#x20;

Just because a device isn't on Google's list of recommended devices doesn't mean it won't work. Android Enterprise is currently compatible with all versions of Android 6.0. However, some features may not be available on earlier versions of the operating system. It is recommended that you use the latest versions of Android to take advantage of all the features and benefits that the platform offers.&#x20;

It is important to note that the **\<NomeProduto>** has been developed with Google Android Enterprise and other additional technologies, which means that some functions, such as location, battery consumption and storage, may behave differently than expected, depending on the device's operating system settings.

{% hint style="info" %}
**Important**\
The solution was developed with Google Android Enterprise and additional technologies, which means some functions, such as location, battery consumption, and storage, may behave differently than expected, depending on the device's operating system settings.
{% endhint %}
