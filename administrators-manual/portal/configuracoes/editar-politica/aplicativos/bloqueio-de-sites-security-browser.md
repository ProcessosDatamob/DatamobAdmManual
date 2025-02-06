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

# Security Browser Website Blocking

Security Browser is a secure and easy-to-use browser. Designed for Android, Security Browser allows device administrators to control and monitor the websites accessed by users, to ensure safer use and controlled data consumption.&#x20;

Website blocking is carried out by the Security Browser application. It is part of the system **\<NomeProduto>** and its purpose is to configure website blocking by URL, keyword and category. It is also responsible for recording and transmitting the user's browsing history to the administration portal, allowing reports and rankings of sites visited to be drawn up.&#x20;

It is therefore important to note that installing and configuring the Security Browser application is essential for the correct performance of the functionalities related to blocking and monitoring visited websites.

### Security Browser Installation Process

The browser installation process is simple and transparent for the end user. However, it is important to advise the user to use this web browser by default. In this way, it will be possible to correctly block and monitor the websites visited.

To install the application, access the "[Application Management"](../../../gerenciamento-de-aplicativos/) menu and the "[Managed Google Play](../../../gerenciamento-de-aplicativos/google-play-gerenciada.md)" option. On the Managed Google Play screen, perform the following steps:

1. Use the search field to search for "Security Browser".
2. Selecione o aplicativo "**Security Browser**".
3. The screen with more information about the application will open. Click on the "Select" button.
4. Click on the confirm button to add it.
5. The Security Browser application will appear in the "[Managed Applications](../../../gerenciamento-de-aplicativos/aplicativos-gerenciados.md)" list.
6. Go to the "[Manage Policies](../../gerenciar-politicas/)" screen in the "[Settings](../../)" menu.
7. Click on the "New Policy" button to create a policy to include the Security Browser.
8. Or edit an existing policy if you have already created one. To do this, go to the "..." at the end of the policy line and choose "Edit Policy".
9. On the "Edit Policy" screen, select the "Applications" tab.
10. Click on the "Add Applications" button.
11. Check the checkbox at the end of the line where the Security Browser application is located
12. Click on the "Add selected" button.

Once the application has been included in the policy, the blocking settings can be defined. The next subsection shows how to block websites.

### **Managed Settings for Security Browser**

1. On the Edit Policies screen, click on the "Applications" tab.
2. Select the "Installation Type" for the Security Browser as either "Forced Installation" or "Pre-installed."&#x20;
3. Click on "Managed Settings" to open the managed settings screen for the Security Browser.

<figure><img src="../../../../../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

Clicking on Managed Settings will display the following screen:

<figure><img src="../../../../../.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

The Managed Settings for the Security Browser are:

* **Block All Sites** - As an administrator, you can activate the complete blocking of access to all sites. When total blocking is enabled, no site can be accessed by the device. This means any browsing attempt will be blocked, ensuring that users cannot visit any web pages.
* **Favorite Sites** - As an administrator, you can configure favorite sites in the Security Browser to make them available to users. Add favorite sites with Name and URL, and upon saving the policy, the settings will be sent to the devices. When opening the Favorites menu in the Security Browser app on the device, the URLs registered in the managed configuration's list of favorite sites will be displayed.
* **Blocking Page** - It is possible to customize the site blocking by redirecting to a predefined default page. This means that if a user attempts to access a site that is blocked by URL, keyword, or category, when the app blocks the site, it will redirect to the blocking URL provided in the managed configuration and will not register the URL as accessed.
* **Blocked and Unblocked URLs and Keywords** - The administrator can specify URLs and keywords to block or allow access in the app, enabling granular control over the content accessed by users, ensuring that unwanted sites are blocked while approved sites remain accessible.
* **Site Blocking by Category** - Access to sites can be blocked based on specific categories. The administrator can select different categories of sites to block. When category blocking is enabled, any site belonging to one of the selected categories will be automatically blocked.

Click "Save" to store the information.
