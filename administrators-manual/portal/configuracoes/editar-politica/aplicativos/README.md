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

# Applications

The application settings tab allows you to manage settings, permissions, set the installation mode, as well as include and exclude applications.

The "**Edit policy**" screen positioned in the "Applications" tab is shown below.

<figure><img src="../../../../../.gitbook/assets/Captura de tela 2024-05-15 173258.png" alt=""><figcaption></figcaption></figure>

The screen has the following parts, as numbered in the figure:

1. **Application selection mode on Google Play** - allows you to control how applications will be displayed on devices registered under this policy. In "**Restricted**" mode, users can only view and install the apps listed below from the Google Play Store. Other apps will be removed and will not be available on devices.

{% hint style="info" %}
**NOTE**

By selecting the "Open" option, the applications added to the policy will display the installation type: Forced Installation, as it understands that all the applications are already available.
{% endhint %}

2. Use the search box to find applications within the list displayed.
3. List of included applications.
4. Installation type - Choose the type of installation for each device. The installation types are: available, pre-installed, forced installation or locked.

{% hint style="info" %}
**NOTE**

It's important to note that the "Pre-installed" installation type of an application happens only once on the device. In other words: when a pre-installed application is deleted by the user, when changing the policy that has the same application with the "pre-installed" installation type, the application will not be displayed on the device because it has already been removed previously. In order for the application to be displayed on the device with the "pre-installed" installation type, it is necessary to carry out the "Remove Device (WIPE)" command in the portal or factory reset via the device.
{% endhint %}

5. More actions ("...") that can be performed with the application: Managed Settings, Permissions, Advanced Settings and Remove Application.
6. Add Applications - allows you to add applications for management.
7. Restrições de funcionamento -permite criar restrições de acesso aos apps por horário, para que seja possível definir os horários em que os apps não poderão ser acessados. Para mais informações acessar o conteúdo Restrições de Funcionamento nesta página.

### Managed Configurations <a href="#id-3vac5uf" id="id-3vac5uf"></a>

This feature allows administrators to modify the permission requirements needed for application execution. Managed settings provide flexible permission management, adapting them to the specific needs of each application and enhancing the end-user experience and security.

To access the managed settings of an application, navigate to the "Edit Policy" screen with the "Applications" tab selected. Follow these steps:

1. Locate the desired application and click on the three dots "..." at the end of the row.
2. Click on "Managed Settings."

<figure><img src="../../../../../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

On this screen, you can view the identification of the selected application and the chosen configuration screen ("Managed Settings").

{% hint style="info" %}
**NOTE**\
The available settings will be displayed based on what is available for each application, meaning the settings will vary depending on the selected application. For some applications, for example, a message may appear: "No settings are available for this application." These work settings depend on the company that created the application.
{% endhint %}

### Permissions

To access an application's permissions settings, you must be in the "[Edit Policy](../)" screen with the "Applications" tab selected. Follow these steps:

1. Locate the application you want and click on the three dots at the end of the line to display the menu with more options;
2. Click on "Permissions".

After step 2, the following screen will be displayed. The list of permissions that can be configured in the selected application is displayed on this screen.

Permissions can be configured as: Request from user, Enabled or Denied.

{% hint style="info" %}
**Note**

&#x20;If the "Permissions" option appears disabled in the system, it is to prevent the user from accessing settings that are not relevant to their role. This is to ensure that the user does not get confused or attempt to adjust settings that are not within their specific responsibilities or needs within the system.&#x20;
{% endhint %}

### **Advanced Settings**

To access an application's advanced settings, you must be in the "[Edit Policy](../)" screen with the "Applications" tab selected. Follow these steps:

1. Locate the application you want and click on the three dots at the end of the line to display the menu with more options;
2. Click on "Advanced Settings".

After step 2, the following screen will be displayed. On this screen we have the following items:

**Update Priority** - Set the application's update priority to predefined, delayed or priority.

**Minimum version** - allows you to define a minimum version of the application.

### **Remove Application**

To exclude an application from the policy, you must be in the "[Edit Policy](../)" screen with the "Applications" tab selected. Follow these steps:

1. Locate the application you want and click on the three dots at the end of the line to display the menu with more options;
2. Click on "Remove Application".

After step 2, the following screen will appear to confirm the deletion. Click the "Remove" button to remove the application from the list.

{% hint style="info" %}
**NOTE**

The application will be removed from the list of applications in the policy being edited, but it will remain in Managed Applications, can be included in the policy again and can be part of the settings of other policies.
{% endhint %}

### **Add Applications**

The Add apps option will behave differently when Kiosk Mode is enabled or disabled.

*   #### Kiosk Mode Deactivated

    When clicking the "Add Applications" button, if it is a policy with Kiosk Mode deactivated, two options will be displayed: Playstore, which includes the list of applications added using Managed Google Play, and Manual, which allows adding applications manually.

<figure><img src="../../../../../.gitbook/assets/image (205).png" alt=""><figcaption></figcaption></figure>

* Kiosk Mode Enabled: If the policy being edited is a policy with Kiosk Mode Enabled, clicking on the Add applications button will display the 3 options for adding applications.&#x20;

<figure><img src="../../../../../.gitbook/assets/image (52).png" alt=""><figcaption></figcaption></figure>

#### System

1. Click on the "System" option, and the "System Applications" screen will open.
2. Select the Manufacturer and the Device.
3. Select one or more applications by clicking the checkbox.
4. Click the "Add selected" button.

#### Playstore

1. Click on the "Playstore" option, and the "Add Applications" screen will open.
2. Select one or more applications by clicking the checkbox.
3. Click the "Add selected" button.

{% hint style="warning" %}
**IMPORTANT** The applications must first be added using the Managed Google Play.
{% endhint %}

#### Manual

1. Click on the "Manual" option, and the "Add Applications Manually" screen will open.
2. Fill in the fields: App Name (optional), Package Name, and click on "Add".

The installation type will be set to "Available" and will allow changing the app's installation type to the following options: Available, Pre-installed, Forced Installation, or Blocked. The app will be sent to the device with the defined installation type when the policy is saved.&#x20;

{% hint style="info" %}
**NOTE**&#x20;

If the application is not on Google Play, the "Pre-installed" and "Forced Installation" options will have the same effect as the "Available" option. This means that the application will be available for installation, and the user has the option to install it at their convenience. It is not automatically installed on the device.
{% endhint %}

<figure><img src="../../../../../.gitbook/assets/image (206).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**NOTE**&#x20;

When creating a policy with the Android Block SIM management mode, the Block SIM application will automatically be added to the APPLICATIONS tab with Forced installation mode. This means that when the user activates the **\<Nome do Produto>** Device Management using this policy, the Block SIM will already be installed automatically without needing to download it from the Play Store.
{% endhint %}

#### Remote

Applications sent via remote installation, through the "Remote Application Installation" menu, will be displayed in the application list with the ORIGIN = "Remote" and with the installation type set to "Available" with editing locked.

### Operational Restrictions

&#x20;To define operational restrictions for applications by days and times, you need to click on the operational restrictions icon in the row corresponding to the desired application. The following image highlights:&#x20;

1. Icons to access the "Operational Restrictions" option;&#x20;
2. Toggle button to activate restrictions.&#x20;

The "Operational Restrictions" option is available for all applications except: the system application **\<NomeProduto>**, Kiosk Launcher, Block Sim, and Remote View. When an application already has operational restrictions, its operational restrictions icon will change to ![](<../../../../../.gitbook/assets/image (53).png>). &#x20;

To activate the restrictions:&#x20;

1. Select the "Enable restrictions" field.&#x20;
2. Enter the start and end times for the period for each day, or select the "Restrict" field to block operation for the entire day.&#x20;
3. Click "Confirm" to save the changes. The policy will send the application's restriction information to the linked devices.
