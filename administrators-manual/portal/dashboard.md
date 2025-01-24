# DASHBOARD

<mark style="color:red;background-color:orange;">ALTERAR TODAS AS IMAGENS PARA APARECER O ÍCONE DE INFORMAÇÕES</mark>

The purpose of this system screen is to enable the user to view and analyze the various consumption and usage data collected from the devices. All this data will be detailed in this section. To find out how to access and analyze the data displayed on the Dashboard, follow the steps described in this section.

The Dashboard screen can be considered the "Home Screen" of the system, as it is displayed as soon as you access the Portal, but it can also be accessed by clicking on the "Dashboard" menu. On first access, the user, device and consumption indicators will not yet have any information, so they will be set to zero.

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
When hovering the mouse over the information icon next to each graph, you can view a detailed description that explains the data presented, making it easier to understand the displayed content and the context of the graph.
{% endhint %}

When you access the screen, all the information will be displayed separated into sections. Each section corresponds to a different piece of data collected from the device and all the information is displayed according to the options selected in the filter (Company, Group or User). In all the sections, there will be icons indicating whether the graphs include information from Android and iOS or just one of them

By enabling the "**International Roaming**" filter option in the top right-hand corner of the screen, the system will only display information collected when the devices are using a roaming connection.

<figure><img src="../../.gitbook/assets/image (204).png" alt=""><figcaption></figcaption></figure>

The "Company", "Group" and "User" filters allow you to analyze data from devices at a specific level.

Click on the "**Company**" filter, type in and select the company name to display the information collected from all devices.

<figure><img src="../../.gitbook/assets/image (205).png" alt=""><figcaption></figcaption></figure>

Click on the "**Group**" filter, type in and select the name of the group, to display the information collected from all the devices that are part of a Group.

<figure><img src="../../.gitbook/assets/image (206).png" alt=""><figcaption></figcaption></figure>

Click on the "**User**" filter and enter and select the user to display the information collected from the user's device.

<figure><img src="../../.gitbook/assets/image (207).png" alt=""><figcaption></figcaption></figure>

In the top right-hand corner of the screen, there are some icons that have the following functions:

*   Notifications - The icon ![](<../../.gitbook/assets/image (33).png>) allows the administrator to see the portal's notifications, for example, when requesting the generation of a report.


* Admin - The icon ![](<../../.gitbook/assets/image (34).png>) displays the option for the administrator to exit the portal and also displays the current version of the solution and the version number.

<figure><img src="../../.gitbook/assets/Captura de tela 2024-10-30 180706.png" alt=""><figcaption></figcaption></figure>

### Status Bar <a href="#id-44sinio" id="id-44sinio"></a>

The Dashboard status bar shows the current status of all the company's users and licenses

<figure><img src="../../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

### Total Users <a href="#id-2jxsxqh" id="id-2jxsxqh"></a>

This indicator displays the total number of device users using the **\<NomeProduto>** application.

### T**otal of Licenses Contracted** <a href="#id-3awqvm692ar0" id="id-3awqvm692ar0"></a>

This indicator shows the total number of licenses on the portal. In other words, the licenses available and used.

When you click on this indicator, the system will display the "Contracted licenses" screen. To find out how to use this screen, read the "**Contracted licenses**" section.

### Licenses not installed on portal <a href="#z337ya" id="z337ya"></a>

This indicator shows the total number of licenses that do not have a device registered on the portal. In other words, these are the licenses available.

When you click on this indicator, the system will display the "Contracted licenses" screen with the Registered device filter set to No. To find out how to use this screen, read the "**Contracted licenses**" section.

### Devices <a href="#id-2xcytpi" id="id-2xcytpi"></a>

This indicator displays the total number of devices that are active in the system and the devices without communication. It also allows the administrator to see which devices are in Kiosk Mode.

<figure><img src="../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

* **TOTAL -** These devices are considered "Active" when installing and activating the **\<NomeProduto>** application. \
  By clicking on "Total" the indicator will display the "Device List" screen containing the report with the main information on active devices.
* **NO COMMUNICATION** - This indicator displays the total number of devices that have not been sending data to the servers for an extended period. When you click on "No Communication", the system displays the screen of devices without communication.

Communication is the synchronization of information that the device has captured and that is sent to the portal. This lack of communication can occur when the device is in the following situations:

* Turned off;
* No internet connection;
* Uninstalled application.

The time calculation to consider a device as out of communication is the sync time configured for the company + 10 minutes.

If the device stops sending general usage/device information for a time exceeding the defined sync interval + 10 minutes, its status changes to "No Communication." To restore communication, the administrator can send a message with the START\_SERVICES command through the Messages menu in the portal.

Clicking on the No Communication indicator will display a screen with a report of the devices that are out of communication.

### **Mobile Data Usage**

This indicator displays the percentage of the devices' mobile data consumption during the cycle in relation to the total limit configured in the Consumption Profile. If no limit is configured in the Consumption Profile, the graph will not display the percentage, and the system will only display the total amount of data in MB used.

### SMS Consumption <a href="#id-3whwml4" id="id-3whwml4"></a>

This indicator displays the percentage of SMS consumption sent by devices during the cycle in relation to the total limit configured in the Consumption Profile. If no limit is configured in the Consumption Profile, the graph will not display the percentage, but only the total amount of SMS used.

{% hint style="info" %}
**NOTE**

Indicator is only available for Android.
{% endhint %}

### **Total Data Usage**

This chart allows viewing data usage, including mobile data, Wi-Fi, and roaming data, on the portal Dashboard. This feature enables a detailed analysis of data usage on devices.

The chart will display:

* The percentage of local mobile data usage relative to the total data (mobile + Wi-Fi).
* The percentage of Wi-Fi data usage relative to the total data (mobile + Wi-Fi).

**Displayed Legend:**

* **Total:** Sum of mobile and Wi-Fi data.
* **Local Mobile Data:** Usage of mobile data on local networks.
* **Wi-Fi:** Total Wi-Fi data usage.

When the Roaming option is enabled, the displayed chart will update to include roaming data usage.

The chart will display:

* Percentage of local mobile data (mobile + roaming + Wi-Fi).
* Percentage of roaming mobile data (mobile + roaming + Wi-Fi).
* Percentage of Wi-Fi data (mobile + roaming + Wi-Fi).

### Data Consumption per application <a href="#id-2bn6wsx" id="id-2bn6wsx"></a>

This graph displays the name and percentage value of the top 5 apps that consumed the most mobile data and the top 5 apps that consumed the most WiFi data during the cycle. Simply click on the desired view option (Mobile Data or WiFi). The displayed data is sorted according to the percentage.

The percentage value for each of the top 5 apps is calculated based on the total data consumption of all apps during the cycle. The data is updated each time the screen is accessed.

By clicking the “View full list” button, the system will display a screen with the information of all the apps. To learn how to use this screen, refer to the **Apps** section of this manual.

This feature provides users with a more detailed and specific view of data consumption, allowing for more accurate and segmented analysis, both on mobile networks and WiFi.

### Data consumption per user <a href="#qsh70q" id="qsh70q"></a>

This chart displays the top 5 users who consumed the most mobile data and the top 5 users who consumed the most Wi-Fi data during the cycle. Simply click on the desired view option (Mobile Data or Wi-Fi). The displayed data is sorted by percentage.

The percentage value of each of the 5 users is calculated in relation to the total sum of consumption of all users during the cycle.

By clicking on the "View complete list" button, the system will display the screen with the company's consumption information. To find out how to use this screen, read the "[**Company consumption**](empresas/consumos.md)" section of this manual.

### Usage time per Application <a href="#id-3as4poj" id="id-3as4poj"></a>

This graph shows the 5 applications that have been used the most during the cycle. This time is only counted when the app is in use, and does not need to be consuming data. Applications in the background are not counted in this analysis.

The percentage value of each of the 5 applications is calculated in relation to the total sum of the usage time of all the applications during the cycle.

By clicking on the "View complete list" button, the system will display the screen with information on all the applications. To find out how to use this screen, read the "[**Applications**](configuracoes/editar-politica/aplicativos/)" section of this manual.

{% hint style="info" %}
**NOTE**

Indicator only available for Android.
{% endhint %}

### Device Inventory <a href="#id-49x2ik5" id="id-49x2ik5"></a>

This indicator shows the percentage of the 5 manufacturers of active devices. The percentage value of each of the 5 manufacturers is calculated in relation to the total sum of all active devices.

### Most visited sites <a href="#id-2p2csry" id="id-2p2csry"></a>

This indicator shows the percentage of the 5 most accessed sites on devices during the cycle. The percentage value of each of the 5 sites is calculated in relation to the total sum of all accesses to the sites during the cycle.

{% hint style="warning" %}
**IMPORTANT**

The websites visited are retrieved by the **\<NomeProduto>** system's default web browser . This browser is called **Security Browser** and must be installed and configured on the devices. For details on managing and configuring the browser, see the [Security Browser](configuracoes/editar-politica/aplicativos/bloqueio-de-sites-security-browser.md) chapter.
{% endhint %}

### Consumption indicator and history. <a href="#id-147n2zr" id="id-147n2zr"></a>

This indicator displays in percentages the mobile data and SMS consumed in the last 6 cycles.

To carry out an individual analysis of mobile data or SMS consumption, access the "[**Company Consumption**](empresas/consumos.md)" submenu in the "[**COMPANIES**](empresas/)" menu.

### New Device Users and History Indicator <a href="#id-3o7alnk" id="id-3o7alnk"></a>

This indicator shows the number of users of devices activated in the last 6 cycles and the evolution of new users in the current cycle in relation to those in the quarter and semester.

To carry out an individual analysis of device users, click on "[**Device List**](dispositivos/list-of-devices/)" in the "[**Devices**](dashboard.md)" menu.&#x20;

### Device Location <a href="#ihv636" id="ihv636"></a>

The map displays the last location of the devices. For the location to be displayed and updated, the device must be connected to the internet, there must be a GPS signal and the "Location Mode" setting must be "Active" under Location in the policy applied to the device.

<figure><img src="../../.gitbook/assets/image (210).png" alt=""><figcaption></figcaption></figure>

If the system does not load the locations on the map, click the "Show locations" button, and they will be displayed.

<figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

* **Blue**: greater than or equal to 5
* **Yellow**: greater than or equal to 10
* **Red**: greater than or equal to 100
* **Magenta**: greater than or equal to 1.000
* **Violet**: greater than or equal to 10.000

Read the "[**Manage Policies**](configuracoes/gerenciar-politicas/)" section of this manual to find out how to activate "Location Mode" on your devices.

The location of the devices is displayed with a marker on the map, which can be green or red depending on the status of the device (green = sending data and red = not sending data). To view the location information, click on the marker.

Use the map's features to optimize the visualization of locations.

### Downloadable Manuals <a href="#id-32hioqz" id="id-32hioqz"></a>

On this screen we will have access to the manuals for download. Clicking on Know More will take you to the Documents and Support Materials screen.

### Any Questions <a href="#id-1hmsyys" id="id-1hmsyys"></a>

Through the "**Any Questions?**" section, you can access the screen where you can see the frequently asked questions by users:

<figure><img src="../../.gitbook/assets/image (181).png" alt=""><figcaption></figcaption></figure>

By clicking on "Learn More," you will be directed to the following screen, where you can perform a search using the free text field or filter by category.

Scrolling further down, you will find a list of frequently asked questions, and at the bottom of the page, you will also have access to downloadable manuals, as available on the Dashboard.
